# Digital Musicology Project

🎵💃🎵💃🎵💃🎵💃🎵💃🎵💃

## Update 2021/5/24

1. We drop the years that have less than 1000 slices. So 1783, 1789, and1811 are omitted. But we think the division is very rough, so we still use consecutive plots. 
2. Add introduction for music21 and the `isConsonant()` method.
3. A4 now is 440Hz.
6. Delete Vieira et al. 2012
7. As for other instruments, we find that they all have much less pieces than piano. So we do not include them. 
8. We compare different composers' curves for new chords and find that Beethoven is not unique. So we reject the previous finding. Thank you for your advice.  

## Introduction

Beethoven, one of the most admired and talented composers in the history of Western music, wrote countless masterpieces even he was affected by ear disease, which started from about 1801 and led to his deafness in 1818. Although musicians and historians usually divided Beethoven's composition styles into three periods and have characterized them with prolific theories and research, it is still controversial about the relation between style changes and Beethoven's ear disease. The composition habits and styles can be affected by many factors and it is almost impossible to inspect them directly. 

From medical perspectives, some researchers believe that the composer tended to use higher tones to seek feedback more easily because it was recorded that Beethoven utilized some mechanical tools to assist his hearing (Saccenti, Smilde and Saris, 2011). On the contrary, some pointed out they did not find evidence that demonstrated the progressive increase or decrease of the use of high tones.

To examine the hypothesis that whether deafness had an impact on Beethoven's styles, we start from a perspective of composition raw materials, namely the basic properties and distributions of pitches and chords, trying to find cogent evidence for or against it. 

## Concepts and Data 

Beethoven (1770-1827) first mentioned hearing loss in a letter to Dr. Franz Wegler dated June 29, 1801: "*In the past three years, my hearing has been gradually weaker. I can give you some idea of this peculiar deafness when I must tell you that in the theatre I have to get very close to the orchestra to understand the performers and that from a distance I do not hear the high notes of the instruments and the singers’ voices. . .Sometimes too I hardly hear people who speak softly. The sound I can hear is true, but not the words. And yet if anyone shouts I can’t bear it.*” (Saccenti, 2011). The following is more detailed information about his deafness: the left ear was affected first, and he was reported (bilateral) tinnitus, and poor speech discrimination is associated with high-pitched hearing loss and loud recruitment. Stevens KM reports that people had to shout to make themselves understood (1970). In 1818, Beethoven began to communicate using notebooks. There was no report that he could still understand oral conversations after 1825, so we assume his deafness was almost complete by then (Ealy GT, 1994). As his hearing got worse, Saccenti points out that he favoured lower and middle-range notes in his music in the British Medical Journal (2011). So we want to study if there is any difference in distribution of lower and middle-range notes, between his pre-deafness period (1770-1801) and post-deafness period (1801-1827); and how does the note distribution of Beethoven's music change during the process of his gradual deafness (1801-1827).

We plan to focus on the major differences between the music Beethoven made before and after his deafness in the view of various music materials: 

1) We’ll start from notes and analyze some other statistics criterions for music. In these three periods, we’ll compare the frequencies of different notes to find out the notes that were used most and used least, analyzing if the distribution of notes over periods changed a lot. Besides, we assume that pitches should be the most different material after Bethoveen’s deafness because of human perception. Quantitative analysis for pitch classes should also be a significant indicator for the Bethoveen’s style among these periods.

2) Chord distribution. We plan to regard notes in different octaves as the same note to reduce the scale of chord amount. In this way, some chords can be used very rarely, while some can be far more frequently used than others. We are going to figure out whether there are high density regions in the chords distribution. If there are, we will dive into different periods and look into the dissonance and consonance of high-frequent chords. We also think Beethoven might borrow some chords from his previous works to replicate the expected effects. That is to say, did he still continuously use new materials or tend to borrow them from previous work? 


## Methods

We will divide Beethoven’s creative career into three different periods according to the development of his deafness, and try to characterize the transformations of his composition style by some basic music materials. By analyzing the changes in the distribution of Beethoven’s works in different periods, we can see whether Beethoven’s work style has changed and whether it will confirm the assumptions as mentioned in previous sections. 

Because the causations of such transformations could be tangled, we only use his deafness as milestones to mark the boundaries of his creative career. As for the correlation between his deafness and style changes, it can require further experiments and analysis. 

## References

 - Cuthbert, M. S. and Ariza, C. (2010) ‘music21: A Toolkit for Computer-Aided Musicology and Symbolic Music Data’, p. 7.
 - Holmes, J. A. (2017) ‘Expert Listening beyond the Limits of Hearing: Music and Deafness’, *Journal of the American Musicological Society*, 70(1), pp. 171–220. doi: 10.1525/jams.2017.70.1.171.
 - Liu, L. *et al.* (2013) ‘A Statistical Physics View of Pitch Fluctuations in the Classical Music from Bach to Chopin: Evidence for Scaling’, *PLoS ONE*. Edited by D. Abbott, 8(3), p. e58710. doi: 10.1371/journal.pone.0058710.
 - Saccenti, E., Smilde, A. K. and Saris, W. H. M. (2011) ‘Beethoven’s deafness and his three styles’, *BMJ*, 343(dec20 3), pp. d7589–d7589. doi: 10.1136/bmj.d7589.
 - White, C. W. and Quinn, I. (2016) ‘The Yale-Classical Archives Corpus’, *Empirical Musicology Review*, 11(1), p. 50. doi: 10.18061/emr.v11i1.4958.
