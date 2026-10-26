---
title: SlideShowTransition
second_title: Aspose.Slides για Android μέσω αναφοράς Java API
description: Αναπαριστά τη μετάβαση παρουσίασης διαφάνειας.
type: docs
url: /el/com.aspose.slides/slideshowtransition/
---
**Κληρονομικότητα:**
java.lang.Object, com.aspose.slides.DomObject

**Όλες οι Υλοποιημένες Διεπαφές:**
[com.aspose.slides.ISlideShowTransition](../../com.aspose.slides/islideshowtransition)
```
public class SlideShowTransition extends DomObject<BaseSlide> implements ISlideShowTransition
```

Αναπαριστά τη μετάβαση παρουσίασης διαφάνειας.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getSound()](#getSound--) | Επιστρέφει ή ορίζει τα ενσωματωμένα δεδομένα ήχου. |
| [setSound(IAudio value)](#setSound-com.aspose.slides.IAudio-) | Επιστρέφει ή ορίζει τα ενσωματωμένα δεδομένα ήχου. |
| [getSoundMode()](#getSoundMode--) | Ορίζει ή επιστρέφει τη λειτουργία ήχου για τη μετάβαση διαφάνειας. |
| [setSoundMode(int value)](#setSoundMode-int-) | Ορίζει ή επιστρέφει τη λειτουργία ήχου για τη μετάβαση διαφάνειας. |
| [getSoundLoop()](#getSoundLoop--) | Αυτό το χαρακτηριστικό καθορίζει αν ο ήχος θα επαναλαμβάνεται μέχρι να συμβεί το επόμενο ηχητικό γεγονός στη παρουσίαση. |
| [setSoundLoop(boolean value)](#setSoundLoop-boolean-) | Αυτό το χαρακτηριστικό καθορίζει αν ο ήχος θα επαναλαμβάνεται μέχρι να συμβεί το επόμενο ηχητικό γεγονός στη παρουσίαση. |
| [getAdvanceOnClick()](#getAdvanceOnClick--) | Καθορίζει αν ένα κλικ του ποντικιού θα προχωρήσει τη διαφάνεια ή όχι. |
| [setAdvanceOnClick(boolean value)](#setAdvanceOnClick-boolean-) | Καθορίζει αν ένα κλικ του ποντικιού θα προχωρήσει τη διαφάνεια ή όχι. |
| [getAdvanceAfter()](#getAdvanceAfter--) | Αυτό το χαρακτηριστικό καθορίζει αν η παρουσίαση θα μεταβεί στην επόμενη διαφάνεια μετά από κάποιο χρονικό διάστημα. |
| [setAdvanceAfter(boolean value)](#setAdvanceAfter-boolean-) | Αυτό το χαρακτηριστικό καθορίζει αν η παρουσίαση θα μεταβεί στην επόμενη διαφάνεια μετά από κάποιο χρονικό διάστημα. |
| [getAdvanceAfterTime()](#getAdvanceAfterTime--) | Καθορίζει το χρόνο, σε χιλιοστά του δευτερολέπτου, μετά τον οποίο πρέπει να ξεκινήσει η μετάβαση. |
| [setAdvanceAfterTime(long value)](#setAdvanceAfterTime-long-) | Καθορίζει το χρόνο, σε χιλιοστά του δευτερολέπτου, μετά τον οποίο πρέπει να ξεκινήσει η μετάβαση. |
| [getSpeed()](#getSpeed--) | Καθορίζει την ταχύτητα μετάβασης που θα χρησιμοποιηθεί κατά τη μετάβαση από την τρέχουσα διαφάνεια στην επόμενη. |
| [setSpeed(int value)](#setSpeed-int-) | Καθορίζει την ταχύτητα μετάβασης που θα χρησιμοποιηθεί κατά τη μετάβαση από την τρέχουσα διαφάνεια στην επόμενη. |
| [getValue()](#getValue--) | Τιμή μετάβασης παρουσίασης διαφάνειας. |
| [getType()](#getType--) | Τύπος μετάβασης. |
| [setType(int value)](#setType-int-) | Τύπος μετάβασης. |
| [getSoundIsBuiltIn()](#getSoundIsBuiltIn--) | Καθορίζει αν αυτός ο ήχος είναι ενσωματωμένος ή όχι. |
| [setSoundIsBuiltIn(boolean value)](#setSoundIsBuiltIn-boolean-) | Καθορίζει αν αυτός ο ήχος είναι ενσωματωμένος ή όχι. |
| [getSoundName()](#getSoundName--) | Καθορίζει ένα ανθρώπινα αναγνώσιμο όνομα για τον ήχο της μετάβασης. |
| [setSoundName(String value)](#setSoundName-java.lang.String-) | Καθορίζει ένα ανθρώπινα αναγνώσιμο όνομα για τον ήχο της μετάβασης. |
| [getDuration()](#getDuration--) | Λαμβάνει ή ορίζει τη διάρκεια του εφέ μετάβασης διαφάνειας σε χιλιοστά του δευτερολέπτου. |
| [setDuration(int value)](#setDuration-int-) | Λαμβάνει ή ορίζει τη διάρκεια του εφέ μετάβασης διαφάνειας σε χιλιοστά του δευτερολέπτου. |
| [equals(Object obj)](#equals-java.lang.Object-) | Καθορίζει αν οι δύο παρουσίες SlideShowTransition είναι ίσες. |
| [hashCode()](#hashCode--) | Λειτουργεί ως συνάρτηση κατακερματισμού για ένα συγκεκριμένο τύπο, κατάλληλη για χρήση σε αλγόριθμους κατακερματισμού και δομές δεδομένων όπως πίνακας κατακερματισμού. |

### getSound() {#getSound--}
```
public final IAudio getSound()
```

Επιστρέφει ή ορίζει τα ενσωματωμένα δεδομένα ήχου. Ανάγνωση/Εγγραφή [IAudio](../../com.aspose.slides/iaudio).

**Επιστρέφει:**
[IAudio](../../com.aspose.slides/iaudio)
### setSound(IAudio value) {#setSound-com.aspose.slides.IAudio-}
```
public final void setSound(IAudio value)
```

Επιστρέφει ή ορίζει τα ενσωματωμένα δεδομένα ήχου. Ανάγνωση/Εγγραφή [IAudio](../../com.aspose.slides/iaudio).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [IAudio](../../com.aspose.slides/iaudio) |  |

### getSoundMode() {#getSoundMode--}
```
public final int getSoundMode()
```

Ορίζει ή επιστρέφει τη λειτουργία ήχου για τη μετάβαση διαφάνειας. Ανάγνωση/Εγγραφή [TransitionSoundMode](../../com.aspose.slides/transitionsoundmode).

**Επιστρέφει:**
int
### setSoundMode(int value) {#setSoundMode-int-}
```
public final void setSoundMode(int value)
```

Ορίζει ή επιστρέφει τη λειτουργία ήχου για τη μετάβαση διαφάνειας. Ανάγνωση/Εγγραφή [TransitionSoundMode](../../com.aspose.slides/transitionsoundmode).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | int |  |

### getSoundLoop() {#getSoundLoop--}
```
public final boolean getSoundLoop()
```

Αυτό το χαρακτηριστικό καθορίζει αν ο ήχος θα επαναλαμβάνεται μέχρι να συμβεί το επόμενο ηχητικό γεγονός στη παρουσίαση. Ανάγνωση/Εγγραφή boolean.

**Επιστρέφει:**
boolean
### setSoundLoop(boolean value) {#setSoundLoop-boolean-}
```
public final void setSoundLoop(boolean value)
```

Αυτό το χαρακτηριστικό καθορίζει αν ο ήχος θα επαναλαμβάνεται μέχρι να συμβεί το επόμενο ηχητικό γεγονός στη παρουσίαση. Ανάγνωση/Εγγραφή boolean.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |

### getAdvanceOnClick() {#getAdvanceOnClick--}
```
public final boolean getAdvanceOnClick()
```

Καθορίζει αν ένα κλικ του ποντικιού θα προχωρήσει τη διαφάνεια ή όχι. Αν αυτό το χαρακτηριστικό δεν καθοριστεί, θεωρείται τιμή true. Ανάγνωση/Εγγραφή boolean.

**Επιστρέφει:**
boolean
### setAdvanceOnClick(boolean value) {#setAdvanceOnClick-boolean-}
```
public final void setAdvanceOnClick(boolean value)
```

Καθορίζει αν ένα κλικ του ποντικιού θα προχωρήσει τη διαφάνεια ή όχι. Αν αυτό το χαρακτηριστικό δεν καθοριστεί, θεωρείται τιμή true. Ανάγνωση/Εγγραφή boolean.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |

### getAdvanceAfter() {#getAdvanceAfter--}
```
public final boolean getAdvanceAfter()
```

Αυτό το χαρακτηριστικό καθορίζει αν η παρουσίαση θα μεταβεί στην επόμενη διαφάνεια μετά από κάποιο χρονικό διάστημα. Ανάγνωση/Εγγραφή boolean.

--------------------

> ```
> Presentation pres = new Presentation("demo.pptx");
>  try {
>      // Λάβετε την πρώτη μετάβαση διαφάνειας
>      ISlideShowTransition slideTransition = pres.getSlides().get_Item(0).getSlideShowTransition();
> 
>      // Ελέγξτε αν η σημαία Advance Slide After είναι ελεγμένη
>      if (slideTransition.getAdvanceAfter())
>      {
>          // Λάβετε την τιμή χρόνου Advance Slide After
>          long advanceAfterTime = slideTransition.getAdvanceAfterTime();
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Επιστρέφει:**
boolean
### setAdvanceAfter(boolean value) {#setAdvanceAfter-boolean-}
```
public final void setAdvanceAfter(boolean value)
```

Αυτό το χαρακτηριστικό καθορίζει αν η παρουσίαση θα μεταβεί στην επόμενη διαφάνεια μετά από κάποιο χρονικό διάστημα. Ανάγνωση/Εγγραφή boolean.

--------------------

> ```
> Presentation pres = new Presentation("demo.pptx");
>  try {
>      // Λάβετε την πρώτη μετάβαση διαφάνειας
>      ISlideShowTransition slideTransition = pres.getSlides().get_Item(0).getSlideShowTransition();
> 
>      // Ελέγξτε αν η σημαία Advance Slide After είναι ελεγμένη
>      if (slideTransition.getAdvanceAfter())
>      {
>          // Λάβετε την τιμή χρόνου Advance Slide After
>          long advanceAfterTime = slideTransition.getAdvanceAfterTime();
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |

### getAdvanceAfterTime() {#getAdvanceAfterTime--}
```
public final long getAdvanceAfterTime()
```

Καθορίζει το χρόνο, σε χιλιοστά του δευτερολέπτου, μετά τον οποίο πρέπει να ξεκινήσει η μετάβαση. Η ρύθμιση αυτή μπορεί να χρησιμοποιηθεί μαζί με το χαρακτηριστικό advClick. Αν αυτό το χαρακτηριστικό δεν καθοριστεί, θεωρείται ότι δεν θα υπάρξει αυτόματη προώθηση. Ανάγνωση/Εγγραφή long.

**Επιστρέφει:**
long
### setAdvanceAfterTime(long value) {#setAdvanceAfterTime-long-}
```
public final void setAdvanceAfterTime(long value)
```

Καθορίζει το χρόνο, σε χιλιοστά του δευτερολέπτου, μετά τον οποίο πρέπει να ξεκινήσει η μετάβαση. Η ρύθμιση αυτή μπορεί να χρησιμοποιηθεί μαζί με το χαρακτηριστικό advClick. Αν αυτό το χαρακτηριστικό δεν καθοριστεί, θεωρείται ότι δεν θα υπάρξει αυτόματη προώθηση. Ανάγνωση/Εγγραφή long.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | long |  |

### getSpeed() {#getSpeed--}
```
public final int getSpeed()
```

Καθορίζει την ταχύτητα μετάβασης που θα χρησιμοποιηθεί κατά τη μετάβαση από την τρέχουσα διαφάνεια στην επόμενη. Ανάγνωση/Εγγραφή [TransitionSpeed](../../com.aspose.slides/transitionspeed).

**Επιστρέφει:**
int
### setSpeed(int value) {#setSpeed-int-}
```
public final void setSpeed(int value)
```

Καθορίζει την ταχύτητα μετάβασης που θα χρησιμοποιηθεί κατά τη μετάβαση από την τρέχουσα διαφάνεια στην επόμενη. Ανάγνωση/Εγγραφή [TransitionSpeed](../../com.aspose.slides/transitionspeed).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | int |  |

### getValue() {#getValue--}
```
public final ITransitionValueBase getValue()
```

Τιμή μετάβασης παρουσίασης διαφάνειας. Μόνο για ανάγνωση [ITransitionValueBase](../../com.aspose.slides/itransitionvaluebase).

**Επιστρέφει:**
[ITransitionValueBase](../../com.aspose.slides/itransitionvaluebase)
### getType() {#getType--}
```
public final int getType()
```

Τύπος μετάβασης. Ανάγνωση/Εγγραφή [TransitionType](../../com.aspose.slides/transitiontype).

**Επιστρέφει:**
int
### setType(int value) {#setType-int-}
```
public final void setType(int value)
```

Τύπος μετάβασης. Ανάγνωση/Εγγραφή [TransitionType](../../com.aspose.slides/transitiontype).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | int |  |

### getSoundIsBuiltIn() {#getSoundIsBuiltIn--}
```
public final boolean getSoundIsBuiltIn()
```

Καθορίζει αν αυτός ο ήχος είναι ενσωματωμένος ή όχι. Αν αυτό το χαρακτηριστικό οριστεί σε true, η εφαρμογή που το δημιουργεί ενημερώνεται για να ελέγξει το χαρακτηριστικό name που έχει οριστεί για αυτόν τον ήχο στη λίστα ενσωματωμένων ήχων και μπορεί, εφόσον χρειαστεί, να εμφανίσει προσαρμοσμένο όνομα ή UI. Ανάγνωση-Εγγραφή boolean.

**Επιστρέφει:**
boolean
### setSoundIsBuiltIn(boolean value) {#setSoundIsBuiltIn-boolean-}
```
public final void setSoundIsBuiltIn(boolean value)
```

Καθορίζει αν αυτός ο ήχος είναι ενσωματωμένος ή όχι. Αν αυτό το χαρακτηριστικό οριστεί σε true, η εφαρμογή που το δημιουργεί ενημερώνεται για να ελέγξει το χαρακτηριστικό name που έχει οριστεί για αυτόν τον ήχο στη λίστα ενσωματωμένων ήχων και μπορεί, εφόσον χρειαστεί, να εμφανίσει προσαρμοσμένο όνομα ή UI. Ανάγνωση-Εγγραφή boolean.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |

### getSoundName() {#getSoundName--}
```
public final String getSoundName()
```

Καθορίζει ένα ανθρώπινα αναγνώσιμο όνομα για τον ήχο της μετάβασης. Η ιδιότητα Sound (\#getSound.getSound/\#setSound(IAudio).setSound(IAudio)) πρέπει να οριστεί για να ληφθεί ή να οριστεί το όνομα ήχου. Ανάγνωση-Εγγραφή String.

**Επιστρέφει:**
java.lang.String
### setSoundName(String value) {#setSoundName-java.lang.String-}
```
public final void setSoundName(String value)
```

Καθορίζει ένα ανθρώπινα αναγνώσιμο όνομα για τον ήχο της μετάβασης. Η ιδιότητα Sound (\#getSound.getSound/\#setSound(IAudio).setSound(IAudio)) πρέπει να οριστεί για να ληφθεί ή να οριστεί το όνομα ήχου. Ανάγνωση-Εγγραφή String.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | java.lang.String |  |

### getDuration() {#getDuration--}
```
public final int getDuration()
```

Λαμβάνει ή ορίζει τη διάρκεια του εφέ μετάβασης διαφάνειας σε χιλιοστά του δευτερολέπτου. Ανάγνωση/Εγγραφή int.

--------------------

Αντιστοιχεί στο χαρακτηριστικό p14:dur του στοιχείου p:transition στο σχήμα PresentationML. Αν δεν οριστεί, η διάρκεια υπολογίζεται αυτόματα βάσει της ιδιότητας \#getSpeed.getSpeed/\#setSpeed(int).setSpeed(int) και του τύπου μετάβασης.

**Επιστρέφει:**
int
### setDuration(int value) {#setDuration-int-}
```
public final void setDuration(int value)
```

Λαμβάνει ή ορίζει τη διάρκεια του εφέ μετάβασης διαφάνειας σε χιλιοστά του δευτερολέπτου. Ανάγνωση/Εγγραφή int.

--------------------

Αντιστοιχεί στο χαρακτηριστικό p14:dur του στοιχείου p:transition στο σχήμα PresentationML. Αν δεν οριστεί, η διάρκεια υπολογίζεται αυτόματα βάσει της ιδιότητας \#getSpeed.getSpeed/\#setSpeed(int).setSpeed(int) και του τύπου μετάβασης.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | int |  |

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

Καθορίζει αν οι δύο παρουσίες SlideShowTransition είναι ίσες. Ανάγνωση/Εγγραφή boolean.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| obj | java.lang.Object | Η SlideShowTransition για σύγκριση με την τρέχουσα SlideShowTransition. |

**Επιστρέφει:**
boolean -  **true**  αν η συγκεκριμένη SlideShowTransition είναι ίση με την τρέχουσα SlideShowTransition· διαφορετικά,  **false** .
### hashCode() {#hashCode--}
```
public int hashCode()
```

Λειτουργεί ως συνάρτηση κατακερματισμού για ένα συγκεκριμένο τύπο, κατάλληλη για χρήση σε αλγόριθμους κατακερματισμού και δομές δεδομένων όπως πίνακας κατακερματισμού.

**Επιστρέφει:**
int - 23454

--------------------

Ανανεωμένο για να ικανοποιεί τον μεταγλωττιστή. Πάντα επιστρέφει σταθερή τιμή επειδή το αντικείμενο είναι μεταβλητό.