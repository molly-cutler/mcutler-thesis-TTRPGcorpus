# mcutler-thesis-TTRPGcorpus
 
This is a corpus ("The TTRPG Corpus") intended for facilitating linguistic analysis of the structure and use of language (here, English) in tabletop role-playing games, or TTRPGs. It contains 4 plaintext files: one each with selected transcripts of TTRPG gameplay sourced from a particular actual-play show. The shows included in the corpus are The Adventure Zone (21 episodes included), Dimension 20 (18 episodes included), Friends at the Table (18 episodes included), and NeoScum (18 episodes included). The corpus totals 1,119,403 words. 

The transcripts have been lightly cleaned and reformatted for accuracy and consistency. Obvious misspellings and errors were corrected. Some “Previously on…” or “Next time on…” openers and closers, which contain audio already included in another episode, were removed. All non-speech text was removed, including notations of sounds, actions, or manner of delivery (e.g. “[laughs],” “[rolls dice],” “[quietly]”). This decision was made because the object of study is a structural, grammatical form in linguistic context, so words besides the actual speech do not need to be counted when collecting analytics (e.g. it would not be desirable to pay attention to “[laughs]” as an example of a present verb, because it was not actually spoken with that morphology by any individual in the recording). Occasionally, removing bracketed text of this sort yielded two lines in a row tagged with the same speaker; in these cases, the second speaker tag was removed and the two lines were combined into one passage. Other similarly minor formatting adjustments were made as needed. 

Speaker tags (e.g. “Griffin: ”) do remain in the corpus. They were left in to guide reading comprehension and to distinguish between paragraph breaks and new speakers, all of which may be useful especially when considering whether the phenomenon at hand is correlated with who is speaking and their role in the game, with short or long narrations, etc. When speaker tags contained a note marking the character (e.g. “Ali as Hella: ” or “MM (as DR): ”) the name of the player was replaced with the name of the character (thus “Hella: ” and “DR: ”), for consistency with other shows’ transcripts where in-character speech is tagged as being spoken by the character (e.g. “Merle: ”), and to allow for an analysis that considers differences between out-of-character and in-character speech. Also remaining in the transcripts as non-speech text are brief markers of breaks between episodes (e.g. “[EPISODE1]”), which permitted easier organization and compilation of the data.

I emphasize here that the text in this transcripts is not my original work (all credit goes to the shows' respective creators for the words themselves and to the original transcribers), and is drawn from the following publicly available sources:

Dimension 20 Wiki Contributors. Episode Transcripts. Retrieved November 10, 2022, from https://dimension20.fandom.com/wiki/Episode_Transcripts#Fantasy_High

Friends at the Table transcription team. Transcripts at the Table. Retrieved November 10, 2022, from https://friendsatthetable.fandom.com/wiki/Transcripts_at_the_Table

Maximum Fun. The Adventure Zone transcripts. Retrieved November 10, 2022, from https://maximumfun.org/transcripts/adventure-zone/

NeoScum. The NeoScum Transcription Project. Retrieved November 10, 2022, from https://neoscum.com/transcriptions

What I have done here is to organize and group together transcripts into a corpus, to ease the difficulties of studying each one individually, given the sheer number of words involved; such analysis can be done with, for instance, Python's Natural Language Toolkit (Bird et al. 2009, [nltk.org](https://www.nltk.org/)). 

This corpus can be used, with appropriate credit, to pursue future (ethical) linguistic work in the area of game studies.
