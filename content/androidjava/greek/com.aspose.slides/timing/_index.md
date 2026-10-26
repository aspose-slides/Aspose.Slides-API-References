---
title: Timing
second_title: Aspose.Slides για Android μέσω Java API Reference
description: Αναπαριστά τον χρονισμό της κίνησης.
type: docs
url: /el/com.aspose.slides/timing/
---
**Κληρονομικότητα:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.slides.ITiming](../../com.aspose.slides/itiming), com.aspose.slides.IDOMObject
```
public class Timing implements ITiming, IDOMObject
```

Αντιπροσωπεύει τον χρονισμό της κίνησης.
## Μεθόδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getAccelerate()](#getAccelerate--) | Περιγράφει το ποσοστό της διάρκειας του εφέ επιτάχυνσης. |
| [setAccelerate(float value)](#setAccelerate-float-) | Περιγράφει το ποσοστό της διάρκειας του εφέ επιτάχυνσης. |
| [getDecelerate()](#getDecelerate--) | Περιγράφει το ποσοστό της διάρκειας του εφέ επιβράδυνσης. |
| [setDecelerate(float value)](#setDecelerate-float-) | Περιγράφει το ποσοστό της διάρκειας του εφέ επιβράδυνσης. |
| [getAutoReverse()](#getAutoReverse--) | Περιγράφει εάν η κίνηση θα αναπαραχθεί αυτόματα ανάποδα μετά την αναπαραγωγή της προς τα εμπρός. |
| [setAutoReverse(boolean value)](#setAutoReverse-boolean-) | Περιγράφει εάν η κίνηση θα αναπαραχθεί αυτόματα ανάποδα μετά την αναπαραγωγή της προς τα εμπρός. |
| [getDuration()](#getDuration--) | Περιγράφει τη διάρκεια του εφέ κίνησης. |
| [setDuration(float value)](#setDuration-float-) | Περιγράφει τη διάρκεια του εφέ κίνησης. |
| [getRepeatCount()](#getRepeatCount--) | Περιγράφει τον αριθμό των επαναλήψεων του εφέ. |
| [setRepeatCount(float value)](#setRepeatCount-float-) | Περιγράφει τον αριθμό των επαναλήψεων του εφέ. |
| [getRepeatUntilEndSlide()](#getRepeatUntilEndSlide--) | Αυτό το χαρακτηριστικό καθορίζει εάν το εφέ θα επαναλαμβάνεται μέχρι το τέλος της διαφάνειας. |
| [setRepeatUntilEndSlide(boolean value)](#setRepeatUntilEndSlide-boolean-) | Αυτό το χαρακτηριστικό καθορίζει εάν το εφέ θα επαναλαμβάνεται μέχρι το τέλος της διαφάνειας. |
| [getRepeatUntilNextClick()](#getRepeatUntilNextClick--) | Αυτό το χαρακτηριστικό καθορίζει εάν το εφέ θα επαναλαμβάνεται μέχρι το επόμενο κλικ. |
| [setRepeatUntilNextClick(boolean value)](#setRepeatUntilNextClick-boolean-) | Αυτό το χαρακτηριστικό καθορίζει εάν το εφέ θα επαναλαμβάνεται μέχρι το επόμενο κλικ. |
| [getRepeatDuration()](#getRepeatDuration--) | Περιγράφει τον αριθμό των επαναλήψεων του εφέ. |
| [setRepeatDuration(float value)](#setRepeatDuration-float-) | Περιγράφει τον αριθμό των επαναλήψεων του εφέ. |
| [getRestart()](#getRestart--) | Καθορίζει εάν ένα εφέ θα επανεκκινηθεί μετά την ολοκλήρωση. |
| [setRestart(int value)](#setRestart-int-) | Καθορίζει εάν ένα εφέ θα επανεκκινηθεί μετά την ολοκλήρωση. |
| [getRewind()](#getRewind--) | Αυτό το χαρακτηριστικό καθορίζει εάν το εφέ θα επανέλθει στην αρχή όταν ολοκληρωθεί η αναπαραγωγή. |
| [setRewind(boolean value)](#setRewind-boolean-) | Αυτό το χαρακτηριστικό καθορίζει εάν το εφέ θα επανέλθει στην αρχή όταν ολοκληρωθεί η αναπαραγωγή. |
| [getSpeed()](#getSpeed--) | Καθορίζει το ποσοστό με το οποίο θα επιταχυνθεί (ή θα επιβραδυνθεί) ο χρονισμός. |
| [setSpeed(float value)](#setSpeed-float-) | Καθορίζει το ποσοστό με το οποίο θα επιταχυνθεί (ή θα επιβραδυνθεί) ο χρονισμός. |
| [getTriggerDelayTime()](#getTriggerDelayTime--) | Περιγράφει τον χρόνο καθυστέρησης μετά το ερέθισμα. |
| [setTriggerDelayTime(float value)](#setTriggerDelayTime-float-) | Περιγράφει τον χρόνο καθυστέρησης μετά το ερέθισμα. |
| [getTriggerType()](#getTriggerType--) | Περιγράφει τον τύπο ερεθίσματος. |
| [setTriggerType(int value)](#setTriggerType-int-) | Περιγράφει τον τύπο ερεθίσματος. |
| [getParent_Immediate()](#getParent-Immediate--) |  |

### getAccelerate() {#getAccelerate--}
```
public final float getAccelerate()
```

Περιγράφει το ποσοστό της διάρκειας του εφέ επιτάχυνσης. Ανάγνωση/εγγραφή float.

**Επιστρέφει:**
float
### setAccelerate(float value) {#setAccelerate-float-}
```
public final void setAccelerate(float value)
```

Περιγράφει το ποσοστό της διάρκειας του εφέ επιτάχυνσης. Ανάγνωση/εγγραφή float.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | float |  |

### getDecelerate() {#getDecelerate--}
```
public final float getDecelerate()
```

Περιγράφει το ποσοστό της διάρκειας του εφέ επιβράδυνσης. Ανάγνωση/εγγραφή float.

**Επιστρέφει:**
float
### setDecelerate(float value) {#setDecelerate-float-}
```
public final void setDecelerate(float value)
```

Περιγράφει το ποσοστό της διάρκειας του εφέ επιβράδυνσης. Ανάγνωση/εγγραφή float.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | float |  |

### getAutoReverse() {#getAutoReverse--}
```
public final boolean getAutoReverse()
```

Περιγράφει εάν η κίνηση θα αναπαραχθεί αυτόματα ανάποδα μετά την αναπαραγωγή της προς τα εμπρός. Ανάγνωση/εγγραφή boolean.

**Επιστρέφει:**
boolean
### setAutoReverse(boolean value) {#setAutoReverse-boolean-}
```
public final void setAutoReverse(boolean value)
```

Περιγράφει εάν η κίνηση θα αναπαραχθεί αυτόματα ανάποδα μετά την αναπαραγωγή της προς τα εμπρός. Ανάγνωση/εγγραφή boolean.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |

### getDuration() {#getDuration--}
```
public final float getDuration()
```

Περιγράφει τη διάρκεια του εφέ κίνησης. Ανάγνωση/εγγραφή float.

**Επιστρέφει:**
float
### setDuration(float value) {#setDuration-float-}
```
public final void setDuration(float value)
```

Περιγράφει τη διάρκεια του εφέ κίνησης. Ανάγνωση/εγγραφή float.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | float |  |

### getRepeatCount() {#getRepeatCount--}
```
public final float getRepeatCount()
```

Περιγράφει τον αριθμό των επαναλήψεων του εφέ. Ανάγνωση/εγγραφή float.

**Επιστρέφει:**
float
### setRepeatCount(float value) {#setRepeatCount-float-}
```
public final void setRepeatCount(float value)
```

Περιγράφει τον αριθμό των επαναλήψεων του εφέ. Ανάγνωση/εγγραφή float.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | float |  |

### getRepeatUntilEndSlide() {#getRepeatUntilEndSlide--}
```
public final boolean getRepeatUntilEndSlide()
```

Αυτό το χαρακτηριστικό καθορίζει εάν το εφέ θα επαναλαμβάνεται μέχρι το τέλος της διαφάνειας. Ανάγνωση/εγγραφή boolean.

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // Get the effects sequence for the first slide
>      ISequence effectsSequence = presentation.getSlides().get_Item(0).getTimeline().getMainSequence();
>      // Get the first effect of main sequence.
>      IEffect effect = effectsSequence.get_Item(0);
>      // Change the effect Timing/Repeat to "Until End of Slide"
>      effect.getTiming().setRepeatUntilEndSlide(true);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Επιστρέφει:**
boolean
### setRepeatUntilEndSlide(boolean value) {#setRepeatUntilEndSlide-boolean-}
```
public final void setRepeatUntilEndSlide(boolean value)
```

Αυτό το χαρακτηριστικό καθορίζει εάν το εφέ θα επαναλαμβάνεται μέχρι το τέλος της διαφάνειας. Ανάγνωση/εγγραφή boolean.

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // Get the effects sequence for the first slide
>      ISequence effectsSequence = presentation.getSlides().get_Item(0).getTimeline().getMainSequence();
>      // Get the first effect of main sequence.
>      IEffect effect = effectsSequence.get_Item(0);
>      // Change the effect Timing/Repeat to "Until End of Slide"
>      effect.getTiming().setRepeatUntilEndSlide(true);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |

### getRepeatUntilNextClick() {#getRepeatUntilNextClick--}
```
public final boolean getRepeatUntilNextClick()
```

Αυτό το χαρακτηριστικό καθορίζει εάν το εφέ θα επαναλαμβάνεται μέχρι το επόμενο κλικ. Ανάγνωση/εγγραφή boolean.

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // Αποκτήστε τη σειρά εφέ για την πρώτη διαφάνεια
>      ISequence effectsSequence = presentation.getSlides().get_Item(0).getTimeline().getMainSequence();
>      // Αποκτήστε το πρώτο εφέ της κύριας ακολουθίας.
>      IEffect effect = effectsSequence.get_Item(0);
>      // Αλλάξτε το Timing/Repeat του εφέ σε "Until Next Click"
>      effect.getTiming().setRepeatUntilNextClick(true);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Επιστρέφει:**
boolean
### setRepeatUntilNextClick(boolean value) {#setRepeatUntilNextClick-boolean-}
```
public final void setRepeatUntilNextClick(boolean value)
```

Αυτό το χαρακτηριστικό καθορίζει εάν το εφέ θα επαναλαμβά

ταν μέχρι το επόμενο κλικ. Ανάγνωση/εγγραφή boolean.

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // Get the effects sequence for the first slide
>      ISequence effectsSequence = presentation.getSlides().get_Item(0).getTimeline().getMainSequence();
>      // Get the first effect of main sequence.
>      IEffect effect = effectsSequence.get_Item(0);
>      // Change the effect Timing/Repeat to "Until Next Click"
>      effect.getTiming().setRepeatUntilNextClick(true);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |

### getRepeatDuration() {#getRepeatDuration--}
```
public final float getRepeatDuration()
```

Περιγράφει τον αριθμό των επαναλήψεων του εφέ. Ανάγνωση/εγγραφή float.

**Επιστρέφει:**
float
### setRepeatDuration(float value) {#setRepeatDuration-float-}
```
public final void setRepeatDuration(float value)
```

Περιγράφει τον αριθμό των επαναλήψεων του εφέ. Ανάγνωση/εγγραφή float.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | float |  |

### getRestart() {#getRestart--}
```
public final int getRestart()
```

Καθορίζει εάν ένα εφέ θα επανεκκινηθεί μετά την ολοκλήρωση. Ανάγνωση/εγγραφή [EffectRestartType](../../com.aspose.slides/effectrestarttype).

**Επιστρέφει:**
int
### setRestart(int value) {#setRestart-int-}
```
public final void setRestart(int value)
```

Καθορίζει εάν ένα εφέ θα επανεκκινηθεί μετά την ολοκλήρωση. Ανάγνωση/εγγραφή [EffectRestartType](../../com.aspose.slides/effectrestarttype).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | int |  |

### getRewind() {#getRewind--}
```
public final boolean getRewind()
```

Αυτό το χαρακτηριστικό καθορίζει εάν το εφέ θα επανέλθει στην αρχή όταν ολοκληρωθεί η αναπαραγωγή. Ανάγνωση/εγγραφή boolean.

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // Αποκτήστε τη σειρά εφέ για την πρώτη διαφάνεια
>      ISequence effectsSequence = presentation.getSlides().get_Item(0).getTimeline().getMainSequence();
>      // Αποκτήστε το πρώτο εφέ της κύριας ακολουθίας.
>      IEffect effect = effectsSequence.get_Item(0);
>      // Ενεργοποιήστε το Timing/Rewind του εφέ.
>      effect.getTiming().setRewind(true);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Επιστρέφει:**
boolean
### setRewind(boolean value) {#setRewind-boolean-}
```
public final void setRewind(boolean value)
```

Αυτό το χαρακτηριστικό καθορίζει εάν το εφέ θα επανέλθει στην αρχή όταν ολοκληρωθεί η αναπαραγωγή. Ανάγνωση/εγγραφή boolean.

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // Αποκτήστε τη σειρά εφέ για την πρώτη διαφάνεια
>      ISequence effectsSequence = presentation.getSlides().get_Item(0).getTimeline().getMainSequence();
>      // Αποκτήστε το πρώτο εφέ της κύριας ακολουθίας.
>      IEffect effect = effectsSequence.get_Item(0);
>      // Ενεργοποιήστε το Timing/Rewind του εφέ.
>      effect.getTiming().setRewind(true);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |

### getSpeed() {#getSpeed--}
```
public final float getSpeed()
```

Καθορίζει το ποσοστό με το οποίο θα επιταχυνθεί (ή θα επιβραδυνθεί) ο χρονισμός. Ανάγνωση/εγγραφή float.

**Επιστρέφει:**
float
### setSpeed(float value) {#setSpeed-float-}
```
public final void setSpeed(float value)
```

Καθορίζει το ποσοστό με το οποίο θα επιταχυνθεί (ή θα επιβραδυνθεί) ο χρονισμός. Ανάγνωση/εγγραφή float.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | float |  |

### getTriggerDelayTime() {#getTriggerDelayTime--}
```
public final float getTriggerDelayTime()
```

Περιγράφει τον χρόνο καθυστέρησης μετά το ερέθισμα. Ανάγνωση/εγγραφή float.

**Επιστρέφει:**
float
### setTriggerDelayTime(float value) {#setTriggerDelayTime-float-}
```
public final void setTriggerDelayTime(float value)
```

Περιγράφει τον χρόνο καθυστέρησης μετά το ερέθισμα. Ανάγνωση/εγγραφή float.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | float |  |

### getTriggerType() {#getTriggerType--}
```
public final int getTriggerType()
```

Περιγράφει τον τύπο ερεθίσματος. Ανάγνωση/εγγραφή [EffectTriggerType](../../com.aspose.slides/effecttriggertype).

**Επιστρέφει:**
int
### setTriggerType(int value) {#setTriggerType-int-}
```
public final void setTriggerType(int value)
```

Περιγράφει τον τύπο ερεθίσματος. Ανάγνωση/εγγραφή [EffectTriggerType](../../com.aspose.slides/effecttriggertype).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | int |  |

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Επιστρέφει το αντικείμενο Parent_Immediate. Μόνο ανάγνωση IDOMObject.

**Επιστρέφει:**
com.aspose.slides.IDOMObject