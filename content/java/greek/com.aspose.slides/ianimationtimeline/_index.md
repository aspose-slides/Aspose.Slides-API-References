---
title: IAnimationTimeLine
second_title: Aspose.Slides for Java API Reference
description: Represents timeline of animation.
type: docs
url: /el/com.aspose.slides/ianimationtimeline/
---```
public interface IAnimationTimeLine
```

Αναπαριστά τη χρονογραμμή του animation.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getInteractiveSequences()](#getInteractiveSequences--) | Επιστρέφει τη συλλογή των διαδραστικών ακολουθιών. |
| [getMainSequence()](#getMainSequence--) | Επιστρέφει την κύρια ακολουθία που μπορεί να περιέχει μόνο τη συλλογή κύριων εφέ. |
| [getTextAnimationCollection()](#getTextAnimationCollection--) | Επιστρέφει τη συλλογή κειμενικών κινήσεων. |
### getInteractiveSequences() {#getInteractiveSequences--}
```
public abstract ISequenceCollection getInteractiveSequences()
```

Επιστρέφει τη συλλογή των διαδραστικών ακολουθιών. Αυτές οι ακολουθίες μπορεί να περιέχουν μόνο εφέ με «κλικ στο σχήμα» που καθορίζει το στόχο σχήματος. Μόνο για ανάγνωση [ISequenceCollection](../../com.aspose.slides/isequencecollection).

**Επιστρέφει:**
[ISequenceCollection](../../com.aspose.slides/isequencecollection)
### getMainSequence() {#getMainSequence--}
```
public abstract ISequence getMainSequence()
```

Επιστρέφει την κύρια ακολουθία που μπορεί να περιέχει μόνο τη συλλογή κύριων εφέ. Μόνο για ανάγνωση [ISequence](../../com.aspose.slides/isequence).

**Επιστρέφει:**
[ISequence](../../com.aspose.slides/isequence)
### getTextAnimationCollection() {#getTextAnimationCollection--}
```
public abstract ITextAnimationCollection getTextAnimationCollection()
```

Επιστρέφει τη συλλογή κειμενικών κινήσεων. Μόνο για ανάγνωση [ITextAnimationCollection](../../com.aspose.slides/itextanimationcollection).

**Επιστρέφει:**
[ITextAnimationCollection](../../com.aspose.slides/itextanimationcollection)