---
title: AnimationTimeLine
second_title: Aspose.Slides για Java API Αναφορά
description: Αντιπροσωπεύει τη χρονογραμμή του animation.
type: docs
url: /el/com.aspose.slides/animationtimeline/
---
**Κληρονομιά:**  
java.lang.Object, com.aspose.slides.DomObject

**Όλες οι υλοποιημένες διεπαφές:**  
[com.aspose.slides.IAnimationTimeLine](../../com.aspose.slides/ianimationtimeline)  
```
public class AnimationTimeLine extends DomObject<BaseSlide> implements IAnimationTimeLine
```

Αναπαριστά τη χρονογραμμή του animation.

## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getInteractiveSequences()](#getInteractiveSequences--) | Επιστρέφει μια συλλογή διαδραστικών ακολουθιών. |
| [getMainSequence()](#getMainSequence--) | Επιστρέφει την κύρια ακολουθία που μπορεί να περιέχει μόνο τη συλλογή κύριων εφέ. |
| [getTextAnimationCollection()](#getTextAnimationCollection--) | Επιστρέφει μια συλλογή κειμενικών animation. |

### getInteractiveSequences() {#getInteractiveSequences--}
```
public final ISequenceCollection getInteractiveSequences()
```

Επιστρέφει μια συλλογή διαδραστικών ακολουθιών. Αυτές οι ακολουθίες μπορεί να περιέχουν μόνο εφέ με «click on shape» που προδιαγράφουν το σχήμα-στόχο. Μόνο για ανάγνωση [ISequenceCollection](../../com.aspose.slides/isequencecollection).

**Επιστρέφει:**  
[ISequenceCollection](../../com.aspose.slides/isequencecollection)

### getMainSequence() {#getMainSequence--}
```
public final ISequence getMainSequence()
```

Επιστρέφει την κύρια ακολουθία που μπορεί να περιέχει μόνο τη συλλογή κύριων εφέ. Μόνο για ανάγνωση [ISequence](../../com.aspose.slides/isequence).

**Επιστρέφει:**  
[ISequence](../../com.aspose.slides/isequence)

### getTextAnimationCollection() {#getTextAnimationCollection--}
```
public final ITextAnimationCollection getTextAnimationCollection()
```

Επιστρέφει μια συλλογή κειμενικών animation. Μόνο για ανάγνωση [ITextAnimationCollection](../../com.aspose.slides/itextanimationcollection).

**Επιστρέφει:**  
[ITextAnimationCollection](../../com.aspose.slides/itextanimationcollection)