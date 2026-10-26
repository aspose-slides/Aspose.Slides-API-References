---
title: ITiming
second_title: Aspose.Slides for Java API Reference
description: Αντιπροσωπεύει το χρονοδιάγραμμα της κίνησης.
type: docs
url: /el/com.aspose.slides/itiming/
---```
public interface ITiming
```

Αντιπροσωπεύει το χρονοδιάγραμμα της κίνησης.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getAccelerate()](#getAccelerate--) | Περιγράφει το ποσοστό της διάρκειας της επιτάχυνσης της συμπεριφοράς του εφέ. |
| [setAccelerate(float value)](#setAccelerate-float-) | Περιγράφει το ποσοστό της διάρκειας της επιτάχυνσης της συμπεριφοράς του εφέ. |
| [getDecelerate()](#getDecelerate--) | Περιγράφει το ποσοστό της διάρκειας της επιβράδυνσης της συμπεριφοράς του εφέ. |
| [setDecelerate(float value)](#setDecelerate-float-) | Περιγράφει το ποσοστό της διάρκειας της επιβράδυνσης της συμπεριφοράς του εφέ. |
| [getAutoReverse()](#getAutoReverse--) | Περιγράφει εάν θα αναπαράγεται αυτόματα το εφέ ανάποδα μετά την αναπαραγωγή του προς τα εμπρός. |
| [setAutoReverse(boolean value)](#setAutoReverse-boolean-) | Περιγράφει εάν θα αναπαράγεται αυτόματα το εφέ ανάποδα μετά την αναπαραγωγή του προς τα εμπρός. |
| [getDuration()](#getDuration--) | Περιγράφει τη διάρκεια του εφέ κίνησης. |
| [setDuration(float value)](#setDuration-float-) | Περιγράφει τη διάρκεια του εφέ κίνησης. |
| [getRepeatCount()](#getRepeatCount--) | Περιγράφει τον αριθμό των επαναλήψεων του εφέ. |
| [setRepeatCount(float value)](#setRepeatCount-float-) | Περιγράφει τον αριθμό των επαναλήψεων του εφέ. |
| [getRepeatUntilEndSlide()](#getRepeatUntilEndSlide--) | Αυτό το χαρακτηριστικό καθορίζει εάν το εφέ θα επαναληφθεί μέχρι το τέλος της διαφάνειας. |
| [setRepeatUntilEndSlide(boolean value)](#setRepeatUntilEndSlide-boolean-) | Αυτό το χαρακτηριστικό καθορίζει εάν το εφέ θα επαναληφθεί μέχρι το τέλος της διαφάνειας. |
| [getRepeatUntilNextClick()](#getRepeatUntilNextClick--) | Αυτό το χαρακτηριστικό καθορίζει εάν το εφέ θα επαναληφθεί μέχρι το επόμενο κλικ. |
| [setRepeatUntilNextClick(boolean value)](#setRepeatUntilNextClick-boolean-) | Αυτό το χαρακτηριστικό καθορίζει εάν το εφέ θα επαναληφθεί μέχρι το επόμενο κλικ. |
| [getRepeatDuration()](#getRepeatDuration--) | Περιγράφει τον αριθμό των επαναλήψεων του εφέ. |
| [setRepeatDuration(float value)](#setRepeatDuration-float-) | Περιγράφει τον αριθμό των επαναλήψεων του εφέ. |
| [getRestart()](#getRestart--) | Καθορίζει εάν ένα εφέ πρέπει να επανεκκινήσει μετά την ολοκλήρωση. |
| [setRestart(int value)](#setRestart-int-) | Καθορίζει εάν ένα εφέ πρέπει να επανεκκινήσει μετά την ολοκλήρωση. |
| [getSpeed()](#getSpeed--) | Καθορίζει το ποσοστό κατά το οποίο θα επιταχυνθεί (ή θα επιβραδυνθεί) η χρονική διάρκεια. |
| [setSpeed(float value)](#setSpeed-float-) | Καθορίζει το ποσοστό κατά το οποίο θα επιταχυνθεί (ή θα επιβραδυνθεί) η χρονική διάρκεια. |
| [getTriggerDelayTime()](#getTriggerDelayTime--) | Περιγράφει τον χρόνο καθυστέρησης μετά τη ενεργοποίηση. |
| [setTriggerDelayTime(float value)](#setTriggerDelayTime-float-) | Περιγράφει τον χρόνο καθυστέρησης μετά τη ενεργοποίηση. |
| [getTriggerType()](#getTriggerType--) | Περιγράφει τον τύπο ενεργοποίησης. |
| [setTriggerType(int value)](#setTriggerType-int-) | Περιγράφει τον τύπο ενεργοποίησης. |
| [getRewind()](#getRewind--) | Αυτό το χαρακτηριστικό καθορίζει εάν το εφέ θα επανέλθει στην αρχή όταν ολοκληρωθεί η αναπαραγωγή. |
| [setRewind(boolean value)](#setRewind-boolean-) | Αυτό το χαρακτηριστικό καθορίζει εάν το εφέ θα επανέλθει στην αρχή όταν ολοκληρωθεί η αναπαραγωγή. |
### getAccelerate() {#getAccelerate--}
```
public abstract float getAccelerate()
```


Περιγράφει το ποσοστό της διάρκειας της επιτάχυνσης της συμπεριφοράς του εφέ. Ανάγνωση/εγγραφή float.

**Επιστρέφει:**
float
### setAccelerate(float value) {#setAccelerate-float-}
```
public abstract void setAccelerate(float value)
```


Περιγράφει το ποσοστό της διάρκειας της επιτάχυνσης της συμπεριφοράς του εφέ. Ανάγνωση/εγγραφή float.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | float |  |

### getDecelerate() {#getDecelerate--}
```
public abstract float getDecelerate()
```


Περιγράφει το ποσοστό της διάρκειας της επιβράδυνσης της συμπεριφοράς του εφέ. Ανάγνωση/εγγραφή float.

**Επιστρέφει:**
float
### setDecelerate(float value) {#setDecelerate-float-}
```
public abstract void setDecelerate(float value)
```


Περιγράφει το ποσοστό της διάρκειας της επιβράδυνσης της συμπεριφοράς του εφέ. Ανάγνωση/εγγραφή float.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | float |  |

### getAutoReverse() {#getAutoReverse--}
```
public abstract boolean getAutoReverse()
```


Περιγράφει εάν θα αναπαράγεται αυτόματα το εφέ ανάποδα μετά την αναπαραγωγή του προς τα εμπρός. Ανάγνωση/εγγραφή boolean.

**Επιστρέφει:**
boolean
### setAutoReverse(boolean value) {#setAutoReverse-boolean-}
```
public abstract void setAutoReverse(boolean value)
```


Περιγράφει εάν θα αναπαράγεται αυτόματα το εφέ ανάποδα μετά την αναπαραγωγή του προς τα εμπρός. Ανάγνωση/εγγραφή boolean.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |

### getDuration() {#getDuration--}
```
public abstract float getDuration()
```


Περιγράφει τη διάρκεια του εφέ κίνησης. Ανάγνωση/εγγραφή float.

**Επιστρέφει:**
float
### setDuration(float value) {#setDuration-float-}
```
public abstract void setDuration(float value)
```


Περιγράφει τη διάρκεια του εφέ κίνησης. Ανάγνωση/εγγραφή float.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | float |  |

### getRepeatCount() {#getRepeatCount--}
```
public abstract float getRepeatCount()
```


Περιγράφει τον αριθμό των επαναλήψεων του εφέ. Ανάγνωση/εγγραφή float.

**Επιστρέφει:**
float
### setRepeatCount(float value) {#setRepeatCount-float-}
```
public abstract void setRepeatCount(float value)
```


Περιγράφει τον αριθμό των επαναλήψεων του εφέ. Ανάγνωση/εγγραφή float.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | float |  |

### getRepeatUntilEndSlide() {#getRepeatUntilEndSlide--}
```
public abstract boolean getRepeatUntilEndSlide()
```


Αυτό το χαρακτηριστικό καθορίζει εάν το εφέ θα επαναληφθεί μέχρι το τέλος της διαφάνειας. Ανάγνωση/εγγραφή boolean.

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // Λάβετε τη σειρά εφέ για την πρώτη διαφάνεια
>      ISequence effectsSequence = presentation.getSlides().get_Item(0).getTimeline().getMainSequence();
>      // Λάβετε το πρώτο εφέ της κύριας σειράς.
>      IEffect effect = effectsSequence.get_Item(0);
>      // Αλλάξτε το Χρονισμό/Επανάληψη του εφέ σε "Until End of Slide"
>      effect.getTiming().setRepeatUntilEndSlide(true);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Επιστρέφει:**
boolean
### setRepeatUntilEndSlide(boolean value) {#setRepeatUntilEndSlide-boolean-}
```
public abstract void setRepeatUntilEndSlide(boolean value)
```


Αυτό το χαρακτηριστικό καθορίζει εάν το εφέ θα επαναληφθεί μέχρι το τέλος της διαφάνειας. Ανάγνωση/εγγραφή boolean.

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // Λάβετε τη σειρά εφέ για την πρώτη διαφάνεια
>      ISequence effectsSequence = presentation.getSlides().get_Item(0).getTimeline().getMainSequence();
>      // Λάβετε το πρώτο εφέ της κύριας σειράς.
>      IEffect effect = effectsSequence.get_Item(0);
>      // Αλλάξτε το Χρονισμό/Επανάληψη του εφέ σε "Until End of Slide"
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
public abstract boolean getRepeatUntilNextClick()
```


Αυτό το χαρακτηριστικό καθορίζει εάν το εφέ θα επαναληφθεί μέχρι το επόμενο κλικ. Ανάγνωση/εγγραφή boolean.

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // Λάβετε τη σειρά εφέ για την πρώτη διαφάνεια
>      ISequence effectsSequence = presentation.getSlides().get_Item(0).getTimeline().getMainSequence();
>      // Λάβετε το πρώτο εφέ της κύριας σειράς.
>      IEffect effect = effectsSequence.get_Item(0);
>      // Αλλάξτε το Χρονισμό/Επανάληψη του εφέ σε "Until Next Click"
>      effect.getTiming().setRepeatUntilNextClick(true);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Επιστρέφει:**
boolean
### setRepeatUntilNextClick(boolean value) {#setRepeatUntilNextClick-boolean-}
```
public abstract void setRepeatUntilNextClick(boolean value)
```


Αυτό το χαρακτηριστικό καθορίζει εάν το εφέ θα επαναληφθεί μέχρι το επόμενο κλικ. Ανάγνωση/εγγραφή boolean.

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // Λάβετε τη σειρά εφέ για την πρώτη διαφάνεια
>      ISequence effectsSequence = presentation.getSlides().get_Item(0).getTimeline().getMainSequence();
>      // Λάβετε το πρώτο εφέ της κύριας σειράς.
>      IEffect effect = effectsSequence.get_Item(0);
>      // Αλλάξτε το Χρονισμό/Επανάληψη του εφέ σε "Until Next Click"
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
public abstract float getRepeatDuration()
```


Περιγράφει τον αριθμό των επαναλήψεων του εφέ. Ανάγνωση/εγγραφή float.

**Επιστρέφει:**
float
### setRepeatDuration(float value) {#setRepeatDuration-float-}
```
public abstract void setRepeatDuration(float value)
```


Περιγράφει τον αριθμό των επαναλήψεων του εφέ. Ανάγνωση/εγγραφή float.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | float |  |

### getRestart() {#getRestart--}
```
public abstract int getRestart()
```


Καθορίζει εάν ένα εφέ πρέπει να επανεκκινήσει μετά την ολοκλήρωση. Ανάγνωση/εγγραφή [EffectRestartType](../../com.aspose.slides/effectrestarttype).

**Επιστρέφει:**
int
### setRestart(int value) {#setRestart-int-}
```
public abstract void setRestart(int value)
```


Καθορίζει εάν ένα εφέ πρέπει να επανεκκινήσει μετά την ολοκλήρωση. Ανάγνωση/εγγραφή [EffectRestartType](../../com.aspose.slides/effectrestarttype).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | int |  |

### getSpeed() {#getSpeed--}
```
public abstract float getSpeed()
```


Καθορίζει το ποσοστό κατά το οποίο θα επιταχυνθεί (ή θα επιβραδυνθεί) η χρονική διάρκεια. Ανάγνωση/εγγραφή float.

**Επιστρέφει:**
float
### setSpeed(float value) {#setSpeed-float-}
```
public abstract void setSpeed(float value)
```


Καθορίζει το ποσοστό κατά το οποίο θα επιταχυνθεί (ή θα επιβραδυνθεί) η χρονική διάρκεια. Ανάγνωση/εγγραφή float.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | float |  |

### getTriggerDelayTime() {#getTriggerDelayTime--}
```
public abstract float getTriggerDelayTime()
```


Περιγράφει τον χρόνο καθυστέρησης μετά τη ενεργοποίηση. Ανάγνωση/εγγραφή float.

**Επιστρέφει:**
float
### setTriggerDelayTime(float value) {#setTriggerDelayTime-float-}
```
public abstract void setTriggerDelayTime(float value)
```


Περιγράφει τον χρόνο καθυστέρησης μετά τη ενεργοποίηση. Ανάγνωση/εγγραφή float.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | float |  |

### getTriggerType() {#getTriggerType--}
```
public abstract int getTriggerType()
```


Περιγράφει τον τύπο ενεργοποίησης. Ανάγνωση/εγγραφή [EffectTriggerType](../../com.aspose.slides/effecttriggertype).

**Επιστρέφει:**
int
### setTriggerType(int value) {#setTriggerType-int-}
```
public abstract void setTriggerType(int value)
```


Περιγράφει τον τύπο ενεργοποίησης. Ανάγνωση/εγγραφή [EffectTriggerType](../../com.aspose.slides/effecttriggertype).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | int |  |

### getRewind() {#getRewind--}
```
public abstract boolean getRewind()
```


Αυτό το χαρακτηριστικό καθορίζει εάν το εφέ θα επανέλθει στην αρχή όταν ολοκληρωθεί η αναπαραγωγή. Ανάγνωση/εγγραφή boolean.

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // Λάβετε τη σειρά εφέ για την πρώτη διαφάνεια
>      ISequence effectsSequence = presentation.getSlides().get_Item(0).getTimeline().getMainSequence();
>      // Λάβετε το πρώτο εφέ της κύριας σειράς.
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
public abstract void setRewind(boolean value)
```


Αυτό το χαρακτηριστικό καθορίζει εάν το εφέ θα επανέλθει στην αρχή όταν ολοκληρωθεί η αναπαραγωγή. Ανάγνωση/εγγραφή boolean.

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // Λάβετε τη σειρά εφέ για την πρώτη διαφάνεια
>      ISequence effectsSequence = presentation.getSlides().get_Item(0).getTimeline().getMainSequence();
>      // Λάβετε το πρώτο εφέ της κύριας σειράς.
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