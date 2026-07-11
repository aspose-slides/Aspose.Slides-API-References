---
title: AnimationTimeLine
second_title: Aspose.Slides για Android μέσω αναφοράς Java API
description: Αναπαριστά το χρονοδιάγραμμα της κινούμενης εικόνας.
type: docs
url: /el/com.aspose.slides/animationtimeline/
---
**Κληρονομικότητα:**
java.lang.Object, com.aspose.slides.DomObject

**Όλες οι Υλοποιημένες Διεπαφές:**
[com.aspose.slides.IAnimationTimeLine](../../com.aspose.slides/ianimationtimeline)
```
public class AnimationTimeLine extends DomObject<BaseSlide> implements IAnimationTimeLine
```

Αναπαριστά το χρονοδιάγραμμα της κινούμενης εικόνας.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getInteractiveSequences()](#getInteractiveSequences--) | Επιστρέφει τη συλλογή των διαδραστικών ακολουθιών. |
| [getMainSequence()](#getMainSequence--) | Επιστρέφει την κύρια ακολουθία που ενδέχεται να περιέχει μόνο τη συλλογή κύρων εφέ. |
| [getTextAnimationCollection()](#getTextAnimationCollection--) | Επιστρέφει τη συλλογή των κινούμενων κειμένων. |
### getInteractiveSequences() {#getInteractiveSequences--}
```
public final ISequenceCollection getInteractiveSequences()
```


Επιστρέφει τη συλλογή των διαδραστικών ακολουθιών. Αυτές οι ακολουθίες ενδέχεται να περιέχουν μόνο εφέ με «κλικ στο σχήμα» που καθορίζουν το σχήμα-στόχο. Μόνο για ανάγνωση [ISequenceCollection](../../com.aspose.slides/isequencecollection).

**Επιστρέφει:**
[ISequenceCollection](../../com.aspose.slides/isequencecollection)
### getMainSequence() {#getMainSequence--}
```
public final ISequence getMainSequence()
```


Επιστρέφει την κύρια ακολουθία που ενδέχεται να περιέχει μόνο τη συλλογή κύρων εφέ. Μόνο για ανάγνωση [ISequence](../../com.aspose.slides/isequence).

**Επιστρέφει:**
[ISequence](../../com.aspose.slides/isequence)
### getTextAnimationCollection() {#getTextAnimationCollection--}
```
public final ITextAnimationCollection getTextAnimationCollection()
```


Επιστρέφει τη συλλογή των κινούμενων κειμένων. Μόνο για ανάγνωση [ITextAnimationCollection](../../com.aspose.slides/itextanimationcollection).

**Επιστρέφει:**
[ITextAnimationCollection](../../com.aspose.slides/itextanimationcollection)