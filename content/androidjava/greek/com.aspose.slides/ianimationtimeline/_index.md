---
title: IAnimationTimeLine
second_title: Aspose.Slides for Android μέσω Java API Reference
description: Αντιπροσωπεύει τη χρονογραμμή του animation.
type: docs
url: /el/com.aspose.slides/ianimationtimeline/
---```
public interface IAnimationTimeLine
```

Αντιπροσωπεύει τη χρονογραμμή του animation.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getInteractiveSequences()](#getInteractiveSequences--) | Returns collection of interactive sequences. |
| [getMainSequence()](#getMainSequence--) | Returns main sequence which may contain only main effects collection. |
| [getTextAnimationCollection()](#getTextAnimationCollection--) | Returns collection of text animations. |
### getInteractiveSequences() {#getInteractiveSequences--}
```
public abstract ISequenceCollection getInteractiveSequences()
```

Επιστρέφει τη συλλογή των διαδραστικών ακολουθιών. Αυτές οι ακολουθίες μπορεί να περιέχουν μόνο εφέ με «click on shape» με καθορισμένο σχήμα-στόχο. Μόνο για ανάγνωση [ISequenceCollection](../../com.aspose.slides/isequencecollection).

**Επιστρέφει:**
[ISequenceCollection](../../com.aspose.slides/isequencecollection)
### getMainSequence() {#getMainSequence--}
```
public abstract ISequence getMainSequence()
```

Επιστρέφει την κύρια ακολουθία η οποία μπορεί να περιέχει μόνο τη συλλογή κύριων εφέ. Μόνο για ανάγνωση [ISequence](../../com.aspose.slides/isequence).

**Επιστρέφει:**
[ISequence](../../com.aspose.slides/isequence)
### getTextAnimationCollection() {#getTextAnimationCollection--}
```
public abstract ITextAnimationCollection getTextAnimationCollection()
```

Επιστρέφει τη συλλογή των κινήσεων κειμένου. Μόνο για ανάγνωση [ITextAnimationCollection](../../com.aspose.slides/itextanimationcollection).

**Επιστρέφει:**
[ITextAnimationCollection](../../com.aspose.slides/itextanimationcollection)