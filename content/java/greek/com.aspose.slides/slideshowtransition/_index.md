---
title: SlideShowTransition
second_title: Aspose.Slides για την Αναφορά API Java
description: Αναπαριστά τη μετάβαση παρουσίασης διαφανειών.
type: docs
url: /el/com.aspose.slides/slideshowtransition/
---
**Κληρονομεί:**
java.lang.Object, com.aspose.slides.DomObject

**Όλες Οι Υλοποιημένες Διεπαφές:**
[com.aspose.slides.ISlideShowTransition](../../com.aspose.slides/islideshowtransition)
```
public class SlideShowTransition extends DomObject<BaseSlide> implements ISlideShowTransition
```

Αναπαριστά τη μετάβαση παρουσίασης διαφανειών.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getSound()](#getSound--) | Επιστρέφει ή ορίζει τα ενσωματωμένα δεδομένα ήχου. |
| [setSound(IAudio value)](#setSound-com.aspose.slides.IAudio-) | Επιστρέφει ή ορίζει τα ενσωματωμένα δεδομένα ήχου. |
| [getSoundMode()](#getSoundMode--) | Ορίζει ή επιστρέφει τη λειτουργία ήχου για τη μετάβαση διαφάνειας. |
| [setSoundMode(int value)](#setSoundMode-int-) | Ορίζει ή επιστρέφει τη λειτουργία ήχου για τη μετάβαση διαφάνειας. |
| [getSoundLoop()](#getSoundLoop--) | Αυτό το χαρακτηριστικό καθορίζει αν ο ήχος θα επαναλαμβάνεται έως ότου συμβεί το επόμενο ηχητικό γεγονός στην παρουσίαση. |
| [setSoundLoop(boolean value)](#setSoundLoop-boolean-) | Αυτό το χαρακτηριστικό καθορίζει αν ο ήχος θα επαναλαμβάνεται έως ότου συμβεί το επόμενο ηχητικό γεγονός στην παρουσίαση. |
| [getAdvanceOnClick()](#getAdvanceOnClick--) | Καθορίζει εάν ένα κλικ του ποντικιού θα προχωρήσει στη διαφάνεια ή όχι. |
| [setAdvanceOnClick(boolean value)](#setAdvanceOnClick-boolean-) | Καθορίζει εάν ένα κλικ του ποντικιού θα προχωρήσει στη διαφάνεια ή όχι. |
| [getAdvanceAfter()](#getAdvanceAfter--) | Αυτό το χαρακτηριστικό καθορίζει εάν η παρουσίαση θα μεταβεί στην επόμενη διαφάνεια μετά από ορισμένο χρόνο. |
| [setAdvanceAfter(boolean value)](#setAdvanceAfter-boolean-) | Αυτό το χαρακτηριστικό καθορίζει εάν η παρουσίαση θα μεταβεί στην επόμενη διαφάνεια μετά από ορισμένο χρόνο. |
| [getAdvanceAfterTime()](#getAdvanceAfterTime--) | Καθορίζει τον χρόνο, σε χιλιοστά του δευτερολέπτου, μετά τον οποίο η μετάβαση πρέπει να ξεκινήσει. |
| [setAdvanceAfterTime(long value)](#setAdvanceAfterTime-long-) | Καθορίζει τον χρόνο, σε χιλιοστά του δευτερολέπτου, μετά τον οποίο η μετάβαση πρέπει να ξεκινήσει. |
| [getSpeed()](#getSpeed--) | Καθορίζει την ταχύτητα μετάβασης που θα χρησιμοποιηθεί κατά τη μετάβαση από την τρέχουσα διαφάνεια στην επόμενη. |
| [setSpeed(int value)](#setSpeed-int-) | Καθορίζει την ταχύτητα μετάβασης που θα χρησιμοποιηθεί κατά τη μετάβαση από την τρέχουσα διαφάνεια στην επόμενη. |
| [getValue()](#getValue--) | Τιμή μετάβασης παρουσίασης διαφανειών. |
| [getType()](#getType--) | Τύπος μετάβασης. |
| [setType(int value)](#setType-int-) | Τύπος μετάβασης. |
| [getSoundIsBuiltIn()](#getSoundIsBuiltIn--) | Καθορίζει εάν αυτός ο ήχος είναι ενσωματωμένος ή όχι. |
| [setSoundIsBuiltIn(boolean value)](#setSoundIsBuiltIn-boolean-) | Καθορίζει εάν αυτός ο ήχος είναι ενσωματωμένος ή όχι. |
| [getSoundName()](#getSoundName--) | Καθορίζει ένα αναγνώσιμο από άνθρωπο όνομα για τον ήχο της μετάβασης. |
| [setSoundName(String value)](#setSoundName-java.lang.String-) | Καθορίζει ένα αναγνώσιμο από άνθρωπο όνομα για τον ήχο της μετάβασης. |
| [getDuration()](#getDuration--) | Αποκτά ή ορίζει τη διάρκεια του εφέ μετάβασης διαφάνειας σε χιλιοστά του δευτερολέπτου. |
| [setDuration(int value)](#setDuration-int-) | Αποκτά ή ορίζει τη διάρκεια του εφέ μετάβασης διαφάνειας σε χιλιοστά του δευτερολέπτου. |
| [equals(Object obj)](#equals-java.lang.Object-) | Καθορίζει εάν οι δύο παρουσίες SlideShowTransition είναι ίσες. |
| [hashCode()](#hashCode--) | Λειτουργεί ως συνάρτηση κατακερματισμού για συγκεκριμένο τύπο, κατάλληλη για χρήση σε αλγόριθμους κατακερματισμού και δομές δεδομένων όπως πίνακας κατακερματισμού. |

### getSound() {#getSound--}
```
public final IAudio getSound()
```

Επιστρέφει ή ορίζει τα ενσωματωμένα δεδομένα ήχου. Ανάγνωση/εγγραφή [IAudio](../../com.aspose.slides/iaudio).

**Επιστρέφει:**
[IAudio](../../com.aspose.slides/iaudio)

### setSound(IAudio value) {#setSound-com.aspose.slides.IAudio-}
```
public final void setSound(IAudio value)
```

Επιστρέφει ή ορίζει τα ενσωματωμένα δεδομένα ήχου. Ανάγνωση/εγγραφή [IAudio](../../com.aspose.slides/iaudio).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [IAudio](../../com.aspose.slides/iaudio) |  |

### getSoundMode() {#getSoundMode--}
```
public final int getSoundMode()
```

Ορίζει ή επιστρέφει τη λειτουργία ήχου για τη μετάβαση διαφάνειας. Ανάγνωση/εγγραφή [TransitionSoundMode](../../com.aspose.slides/transitionsoundmode).

**Επιστρέφει:**
int

### setSoundMode(int value) {#setSoundMode-int-}
```
public final void setSoundMode(int value)
```

Ορίζει ή επιστρέφει τη λειτουργία ήχου για τη μετάβαση διαφάνειας. Ανάγνωση/εγγραφή [TransitionSoundMode](../../com.aspose.slides/transitionsoundmode).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | int |  |

### getSoundLoop() {#getSoundLoop--}
```
public final boolean getSoundLoop()
```

Αυτό το χαρακτηριστικό καθορίζει αν ο ήχος θα επαναλαμβάνεται έως ότου συμβεί το επόμενο ηχητικό γεγονός στην παρουσίαση. Ανάγνωση/εγγραφή boolean.

**Επιστρέφει:**
boolean

### setSoundLoop(boolean value) {#setSoundLoop-boolean-}
```
public final void setSoundLoop(boolean value)
```

Αυτό το χαρακτηριστικό καθορίζει αν ο ήχος θα επαναλαμβάνεται έως ότου συμβεί το επόμενο ηχητικό γεγονός στην παρουσίαση. Ανάγνωση/εγγραφή boolean.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |

### getAdvanceOnClick() {#getAdvanceOnClick--}
```
public final boolean getAdvanceOnClick()
```

Καθορίζει εάν ένα κλικ του ποντικιού θα προχωρήσει στη διαφάνεια ή όχι. Εάν αυτό το χαρακτηριστικό δεν έχει οριστεί, υποτίθεται τιμή true. Ανάγνωση/εγγραφή boolean.

**Επιστρέφει:**
boolean

### setAdvanceOnClick(boolean value) {#setAdvanceOnClick-boolean-}
```
public final void setAdvanceOnClick(boolean value)
```

Καθορίζει εάν ένα κλικ του ποντικιού θα προχωρήσει στη διαφάνεια ή όχι. Εάν αυτό το χαρακτηριστικό δεν έχει οριστεί, υποτίθεται τιμή true. Ανάγνωση/εγγραφή boolean.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |

### getAdvanceAfter() {#getAdvanceAfter--}
```
public final boolean getAdvanceAfter()
```

Αυτό το χαρακτηριστικό καθορίζει εάν η παρουσίαση θα μεταβεί στην επόμενη διαφάνεια μετά από ορισμένο χρόνο. Ανάγνωση/εγγραφή boolean.

--------------------

> ```
> Presentation pres = new Presentation("demo.pptx");
>  try {
>      // Get the first slide Transition
>      ISlideShowTransition slideTransition = pres.getSlides().get_Item(0).getSlideShowTransition();
> 
>      // Check if the Advance Slide After flag is checked
>      if (slideTransition.getAdvanceAfter())
>      {
>          // Get the Advance Slide After Time value
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

Αυτό το χαρακτηριστικό καθορίζει εάν η παρουσίαση θα μεταβεί στην επόμενη διαφάνεια μετά από ορισμένο χρόνο. Ανάγνωση/εγγραφή boolean.

--------------------

> ```
> Presentation pres = new Presentation("demo.pptx");
>  try {
>      // Get the first slide Transition
>      ISlideShowTransition slideTransition = pres.getSlides().get_Item(0).getSlideShowTransition();
> 
>      // Check if the Advance Slide After flag is checked
>      if (slideTransition.getAdvanceAfter())
>      {
>          // Get the Advance Slide After Time value
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

Καθορίζει τον χρόνο, σε χιλιοστά του δευτερολέπτου, μετά τον οποίο η μετάβαση πρέπει να ξεκινήσει. Αυτή η ρύθμιση μπορεί να χρησιμοποιηθεί μαζί με το χαρακτηριστικό advClick. Εάν αυτό το χαρακτηριστικό δεν έχει οριστεί, θεωρείται ότι δεν θα γίνει αυτόματη προώθηση. Ανάγνωση/εγγραφή long.

**Επιστρέφει:**
long

### setAdvanceAfterTime(long value) {#setAdvanceAfterTime-long-}
```
public final void setAdvanceAfterTime(long value)
```

Καθορίζει τον χρόνο, σε χιλιοστά του δευτερολέπτου, μετά τον οποίο η μετάβαση πρέπει να ξεκινήσει. Αυτή η ρύθμιση μπορεί να χρησιμοποιηθεί μαζί με το χαρακτηριστικό advClick. Εάν αυτό το χαρακτηριστικό δεν έχει οριστεί, θεωρείται ότι δεν θα γίνει αυτόματη προώθηση. Ανάγνωση/εγγραφή long.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | long |  |

### getSpeed() {#getSpeed--}
```
public final int getSpeed()
```

Καθορίζει την ταχύτητα μετάβασης που θα χρησιμοποιηθεί κατά τη μετάβαση από την τρέχουσα διαφάνεια στην επόμενη. Ανάγνωση/εγγραφή [TransitionSpeed](../../com.aspose.slides/transitionspeed).

**Επιστρέφει:**
int

### setSpeed(int value) {#setSpeed-int-}
```
public final void setSpeed(int value)
```

Καθορίζει την ταχύτητα μετάβασης που θα χρησιμοποιηθεί κατά τη μετάβαση από την τρέχουσα διαφάνεια στην επόμενη. Ανάγνωση/εγγραφή [TransitionSpeed](../../com.aspose.slides/transitionspeed).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | int |  |

### getValue() {#getValue--}
```
public final ITransitionBase getValue()
```

Τιμή μετάβασης παρουσίασης διαφανειών. Μόνο για ανάγνωση [ITransitionValueBase](../../com.aspose.slides/itransitionvaluebase).

**Επιστρέφει:**
[ITransitionValueBase](../../com.aspose.slides/itransitionvaluebase)

### getType() {#getType--}
```
public final int getType()
```

Τύπος μετάβασης. Ανάγνωση/εγγραφή [TransitionType](../../com.aspose.slides/transitiontype).

**Επιστρέφει:**
int

### setType(int value) {#setType-int-}
```
public final void setType(int value)
```

Τύπος μετάβασης. Ανάγνωση/εγγραφή [TransitionType](../../com.aspose.slides/transitiontype).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | int |  |

### getSoundIsBuiltIn() {#getSoundIsBuiltIn--}
```
public final boolean getSoundIsBuiltIn()
```

Καθορίζει εάν αυτός ο ήχος είναι ενσωματωμένος ή όχι. Εάν αυτό το χαρακτηριστικό οριστεί σε true, τότε η δημιουργική εφαρμογή ειδοποιείται να ελέγξει το χαρακτηριστικό name που έχει οριστεί για αυτόν τον ήχο στη λίστα των ενσωματωμένων ήχων και μπορεί να εμφανίσει προσαρμοσμένο όνομα ή UI ανάλογα. Ανάγνωση/εγγραφή boolean.

**Επιστρέφει:**
boolean

### setSoundIsBuiltIn(boolean value) {#setSoundIsBuiltIn-boolean-}
```
public final void setSoundIsBuiltIn(boolean value)
```

Καθορίζει εάν αυτός ο ήχος είναι ενσωματωμένος ή όχι. Εάν αυτό το χαρακτηριστικό οριστεί σε true, τότε η δημιουργική εφαρμογή ειδοποιείται να ελέγξει το χαρακτηριστικό name που έχει οριστεί για αυτόν τον ήχο στη λίστα των ενσωματωμένων ήχων και μπορεί να εμφανίσει προσαρμοσμένο όνομα ή UI ανάλογα. Ανάγνωση/εγγραφή boolean.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |

### getSoundName() {#getSoundName--}
```
public final String getSoundName()
```

Καθορίζει ένα αναγνώσιμο από άνθρωπο όνομα για τον ήχο της μετάβασης. Η ιδιότητα Sound (\#getSound.getSound/\#setSound(IAudio).setSound(IAudio)) πρέπει να έχει ανατεθεί για την λήψη ή τον ορισμό του ονόματος ήχου. Ανάγνωση/εγγραφή String.

**Επιστρέφει:**
java.lang.String

### setSoundName(String value) {#setSoundName-java.lang.String-}
```
public final void setSoundName(String value)
```

Καθορίζει ένα αναγνώσιμο από άνθρωπο όνομα για τον ήχο της μετάβασης. Η ιδιότητα Sound (\#getSound.getSound/\#setSound(IAudio).setSound(IAudio)) πρέπει να έχει ανατεθεί για την λήψη ή τον ορισμό του ονόματος ήχου. Ανάγνωση/εγγραφή String.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | java.lang.String |  |

### getDuration() {#getDuration--}
```
public final int getDuration()
```

Αποκτά ή ορίζει τη διάρκεια του εφέ μετάβασης διαφάνειας σε χιλιοστά του δευτερολέπτου. Ανάγνωση/εγγραφή int.

--------------------

Αντιστοιχεί στο χαρακτηριστικό p14:dur του στοιχείου p:transition στο σχήμα PresentationML. Εάν δεν έχει οριστεί, η διάρκεια καθορίζεται αυτόματα βάσει της ιδιότητας \#getSpeed.getSpeed/\#setSpeed(int).setSpeed(int) και του τύπου μετάβασης.

**Επιστρέφει:**
int

### setDuration(int value) {#setDuration-int-}
```
public final void setDuration(int value)
```

Αποκτά ή ορίζει τη διάρκεια του εφέ μετάβασης διαφάνειας σε χιλιοστά του δευτερολέπτου. Ανάγνωση/εγγραφή int.

--------------------

Αντιστοιχεί στο χαρακτηριστικό p14:dur του στοιχείου p:transition στο σχήμα PresentationML. Εάν δεν έχει οριστεί, η διάρκεια καθορίζεται αυτόματα βάσει της ιδιότητας \#getSpeed.getSpeed/\#setSpeed(int).setSpeed(int) και του τύπου μετάβασης.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | int |  |

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

Καθορίζει εάν οι δύο παρουσίες SlideShowTransition είναι ίσες. Ανάγνωση/εγγραφή boolean.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| obj | java.lang.Object | Η SlideShowTransition για σύγκριση με την τρέχουσα SlideShowTransition. |

**Επιστρέφει:**
boolean -  **true**  εάν η συγκεκριμένη SlideShowTransition είναι ίση με την τρέχουσα SlideShowTransition· διαφορετικά,  **false** .

### hashCode() {#hashCode--}
```
public int hashCode()
```

Λειτουργεί ως συνάρτηση κατακερματισμού για συγκεκριμένο τύπο, κατάλληλη για χρήση σε αλγόριθμους κατακερματισμού και δομές δεδομένων όπως πίνακας κατακερματισμού.

**Επιστρέφει:**
int - 23454

--------------------

Αναθεωρήθηκε ώστε να ικανοποιεί τον μεταγλωττιστή. Πάντα επιστρέφει σταθερά επειδή το αντικείμενο είναι μεταβλητό.