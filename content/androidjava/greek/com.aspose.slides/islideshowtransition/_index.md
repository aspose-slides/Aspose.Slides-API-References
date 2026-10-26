---
title: ISlideShowTransition
second_title: Aspose.Slides for Android via Java API Reference
description: Αντιπροσωπεύει τη μετάβαση παρουσίασης διαφανειών.
type: docs
url: /el/com.aspose.slides/islideshowtransition/
---```
public interface ISlideShowTransition
```

Αντιπροσωπεύει τη μετάβαση παρουσίασης διαφανειών.
## Μεθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getSound()](#getSound--) | Επιστρέφει ή ορίζει τα ενσωματωμένα δεδομένα ήχου. |
| [setSound(IAudio value)](#setSound-com.aspose.slides.IAudio-) | Επιστρέφει ή ορίζει τα ενσωματωμένα δεδομένα ήχου. |
| [getSoundMode()](#getSoundMode--) | Ορίζει ή επιστρέφει τη λειτουργία ήχου για τη μετάβαση διαφάνειας. |
| [setSoundMode(int value)](#setSoundMode-int-) | Ορίζει ή επιστρέφει τη λειτουργία ήχου για τη μετάβαση διαφάνειας. |
| [getSoundLoop()](#getSoundLoop--) | Αυτό το χαρακτηριστικό καθορίζει εάν ο ήχος θα επαναλαμβάνεται έως ότου συμβεί το επόμενο ηχητικό γεγονός στην παρουσίαση. |
| [setSoundLoop(boolean value)](#setSoundLoop-boolean-) | Αυτό το χαρακτηριστικό καθορίζει εάν ο ήχος θα επαναλαμβάνεται έως ότου συμβεί το επόμενο ηχητικό γεγονός στην παρουσίαση. |
| [getAdvanceOnClick()](#getAdvanceOnClick--) | Καθορίζει εάν ένα κλικ του ποντικιού θα προχωρήσει τη διαφάνεια ή όχι. |
| [setAdvanceOnClick(boolean value)](#setAdvanceOnClick-boolean-) | Καθορίζει εάν ένα κλικ του ποντικιού θα προχωρήσει τη διαφάνεια ή όχι. |
| [getAdvanceAfter()](#getAdvanceAfter--) | Αυτό το χαρακτηριστικό καθορίζει εάν η παρουσίαση θα μεταβεί στην επόμενη διαφάνεια μετά από κάποιο χρόνο. |
| [setAdvanceAfter(boolean value)](#setAdvanceAfter-boolean-) | Αυτό το χαρακτηριστικό καθορίζει εάν η παρουσίαση θα μεταβεί στην επόμενη διαφάνεια μετά από κάποιο χρόνο. |
| [getAdvanceAfterTime()](#getAdvanceAfterTime--) | Καθορίζει το χρονικό διάστημα, σε χιλιοστά του δευτερολέπτου, μετά το οποίο πρέπει να ξεκινήσει η μετάβαση. |
| [setAdvanceAfterTime(long value)](#setAdvanceAfterTime-long-) | Καθορίζει το χρονικό διάστημα, σε χιλιοστά του δευτερολέπτου, μετά το οποίο πρέπει να ξεκινήσει η μετάβαση. |
| [getSpeed()](#getSpeed--) | Καθορίζει την ταχύτητα μετάβασης που θα χρησιμοποιηθεί κατά τη μετάβαση από την τρέχουσα διαφάνεια στην επόμενη. |
| [setSpeed(int value)](#setSpeed-int-) | Καθορίζει την ταχύτητα μετάβασης που θα χρησιμοποιηθεί κατά τη μετάβαση από την τρέχουσα διαφάνεια στην επόμενη. |
| [getValue()](#getValue--) | Τιμή μετάβασης παρουσίασης διαφανειών. |
| [getType()](#getType--) | Τύπος μετάβασης. |
| [setType(int value)](#setType-int-) | Τύπος μετάβασης. |
| [getSoundIsBuiltIn()](#getSoundIsBuiltIn--) | Καθορίζει εάν αυτός ο ήχος είναι ενσωματωμένος ή όχι. |
| [setSoundIsBuiltIn(boolean value)](#setSoundIsBuiltIn-boolean-) | Καθορίζει εάν αυτός ο ήχος είναι ενσωματωμένος ή όχι. |
| [getSoundName()](#getSoundName--) | Καθορίζει ένα ανθρώπινα αναγνώσιμο όνομα για τον ήχο της μετάβασης. |
| [setSoundName(String value)](#setSoundName-java.lang.String-) | Καθορίζει ένα ανθρώπινα αναγνώσιμο όνομα για τον ήχο της μετάβασης. |
| [getDuration()](#getDuration--) | Ανακτά ή ορίζει τη διάρκεια του εφέ μετάβασης διαφάνειας σε χιλιοστά του δευτερολέπτου. |
| [setDuration(int value)](#setDuration-int-) | Ανακτά ή ορίζει τη διάρκεια του εφέ μετάβασης διαφάνειας σε χιλιοστά του δευτερολέπτου. |
### getSound() {#getSound--}
```
public abstract IAudio getSound()
```

Επιστρέφει ή ορίζει τα ενσωματωμένα δεδομένα ήχου. Ανάγνωση-εγγραφή [IAudio](../../com.aspose.slides/iaudio).

**Επιστρέφει:**
[IAudio](../../com.aspose.slides/iaudio)
### setSound(IAudio value) {#setSound-com.aspose.slides.IAudio-}
```
public abstract void setSound(IAudio value)
```

Επιστρέφει ή ορίζει τα ενσωματωμένα δεδομένα ήχου. Ανάγνωση-εγγραφή [IAudio](../../com.aspose.slides/iaudio).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [IAudio](../../com.aspose.slides/iaudio) |  |
### getSoundMode() {#getSoundMode--}
```
public abstract int getSoundMode()
```

Ορίζει ή επιστρέφει τη λειτουργία ήχου για τη μετάβαση διαφάνειας. Ανάγνωση-εγγραφή [TransitionSoundMode](../../com.aspose.slides/transitionsoundmode).

**Επιστρέφει:**
int
### setSoundMode(int value) {#setSoundMode-int-}
```
public abstract void setSoundMode(int value)
```

Ορίζει ή επιστρέφει τη λειτουργία ήχου για τη μετάβαση διαφάνειας. Ανάγνωση-εγγραφή [TransitionSoundMode](../../com.aspose.slides/transitionsoundmode).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | int |  |
### getSoundLoop() {#getSoundLoop--}
```
public abstract boolean getSoundLoop()
```

Αυτό το χαρακτηριστικό καθορίζει εάν ο ήχος θα επαναλαμβάνεται έως ότου συμβεί το επόμενο ηχητικό γεγονός στην παρουσίαση. Ανάγνωση-εγγραφή boolean.

**Επιστρέφει:**
boolean
### setSoundLoop(boolean value) {#setSoundLoop-boolean-}
```
public abstract void setSoundLoop(boolean value)
```

Αυτό το χαρακτηριστικό καθορίζει εάν ο ήχος θα επαναλαμβάνεται έως ότου συμβεί το επόμενο ηχητικό γεγονός στην παρουσίαση. Ανάγνωση-εγγραφή boolean.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |
### getAdvanceOnClick() {#getAdvanceOnClick--}
```
public abstract boolean getAdvanceOnClick()
```

Καθορίζει εάν ένα κλικ του ποντικιού θα προχωρήσει τη διαφάνεια ή όχι. Εάν αυτό το χαρακτηριστικό δεν καθοριστεί, υποτίθεται τιμή true. Ανάγνωση-εγγραφή boolean.

**Επιστρέφει:**
boolean
### setAdvanceOnClick(boolean value) {#setAdvanceOnClick-boolean-}
```
public abstract void setAdvanceOnClick(boolean value)
```

Καθορίζει εάν ένα κλικ του ποντικιού θα προχωρήσει τη διαφάνεια ή όχι. Εάν αυτό το χαρακτηριστικό δεν καθοριστεί, υποτίθεται τιμή true. Ανάγνωση-εγγραφή boolean.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |
### getAdvanceAfter() {#getAdvanceAfter--}
```
public abstract boolean getAdvanceAfter()
```

Αυτό το χαρακτηριστικό καθορίζει εάν η παρουσίαση θα μεταβεί στην επόμενη διαφάνεια μετά από κάποιο χρόνο. Ανάγνωση/εγγραφή  boolean .

--------------------

> ```
> Presentation pres = new Presentation("demo.pptx");
>  try {
>      // Λάβετε την πρώτη μετάβαση διαφάνειας
>      ISlideShowTransition slideTransition = pres.getSlides().get_Item(0).getSlideShowTransition();
> 
>      // Ελέγξτε αν η σημαία Προώθησης Διαφάνειας Μετά είναι ενεργοποιημένη
>      if (slideTransition.getAdvanceAfter())
>      {
>          // Λάβετε την τιμή του χρόνου Προώθησης Διαφάνειας Μετά
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
public abstract void setAdvanceAfter(boolean value)
```

Αυτό το χαρακτηριστικό καθορίζει εάν η παρουσίαση θα μεταβεί στην επόμενη διαφάνεια μετά από κάποιο χρόνο. Ανάγνωση/εγγραφή  boolean .

--------------------

> ```
> Presentation pres = new Presentation("demo.pptx");
>  try {
>      // Λάβετε την πρώτη μετάβαση διαφάνειας
>      ISlideShowTransition slideTransition = pres.getSlides().get_Item(0).getSlideShowTransition();
> 
>      // Ελέγξτε αν η σημαία Προώθησης Διαφάνειας Μετά είναι ενεργοποιημένη
>      if (slideTransition.getAdvanceAfter())
>      {
>          // Λάβετε την τιμή του χρόνου Προώθησης Διαφάνειας Μετά
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
public abstract long getAdvanceAfterTime()
```

Καθορίζει το χρονικό διάστημα, σε χιλιοστά του δευτερολέπτου, μετά το οποίο πρέπει να ξεκινήσει η μετάβαση. Αυτή η ρύθμιση μπορεί να χρησιμοποιηθεί μαζί με το χαρακτηριστικό advClick. Εάν το χαρακτηριστικό δεν καθοριστεί, υποτίθεται ότι δεν θα γίνει αυτόματη προώθηση. Ανάγνωση-εγγραφή long.

**Επιστρέφει:**
long
### setAdvanceAfterTime(long value) {#setAdvanceAfterTime-long-}
```
public abstract void setAdvanceAfterTime(long value)
```

Καθορίζει το χρονικό διάστημα, σε χιλιοστά του δευτερολέπτου, μετά το οποίο πρέπει να ξεκινήσει η μετάβαση. Αυτή η ρύθμιση μπορεί να χρησιμοποιηθεί μαζί με το χαρακτηριστικό advClick. Εάν το χαρακτηριστικό δεν καθοριστεί, υποτίθεται ότι δεν θα γίνει αυτόματη προώθηση. Ανάγνωση-εγγραφή long.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | long |  |
### getSpeed() {#getSpeed--}
```
public abstract int getSpeed()
```

Καθορίζει την ταχύτητα μετάβασης που θα χρησιμοποιηθεί κατά τη μετάβαση από την τρέχουσα διαφάνεια στην επόμενη. Ανάγνωση-εγγραφή [TransitionSpeed](../../com.aspose.slides/transitionspeed).

**Επιστρέφει:**
int
### setSpeed(int value) {#setSpeed-int-}
```
public abstract void setSpeed(int value)
```

Καθορίζει την ταχύτητα μετάβασης που θα χρησιμοποιηθεί κατά τη μετάβαση από την τρέχουσα διαφάνεια στην επόμενη. Ανάγνωση-εγγραφή [TransitionSpeed](../../com.aspose.slides/transitionspeed).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | int |  |
### getValue() {#getValue--}
```
public abstract ITransitionValueBase getValue()
```

Τιμή μετάβασης παρουσίασης διαφανειών. Μόνο-ανάγνωση [ITransitionValueBase](../../com.aspose.slides/itransitionvaluebase).

**Επιστρέφει:**
[ITransitionValueBase](../../com.aspose.slides/itransitionvaluebase)
### getType() {#getType--}
```
public abstract int getType()
```

Τύπος μετάβασης. Ανάγνωση-εγγραφή [TransitionType](../../com.aspose.slides/transitiontype).

**Επιστρέφει:**
int
### setType(int value) {#setType-int-}
```
public abstract void setType(int value)
```

Τύπος μετάβασης. Ανάγνωση-εγγραφή [TransitionType](../../com.aspose.slides/transitiontype).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | int |  |
### getSoundIsBuiltIn() {#getSoundIsBuiltIn--}
```
public abstract boolean getSoundIsBuiltIn()
```

Καθορίζει εάν αυτός ο ήχος είναι ενσωματωμένος ή όχι. Εάν αυτό το χαρακτηριστικό οριστεί σε true, η εφαρμογή δημιουργίας ενημερώνεται ώστε να ελέγξει το χαρακτηριστικό name που καθορίζεται για αυτόν τον ήχο στη λίστα ενσωματωμένων ήχων και μπορεί, έτσι, να εμφανίσει προσαρμοσμένο όνομα ή διεπαφή χρήστη όπως απαιτείται. Ανάγνωση-εγγραφή boolean.

**Επιστρέφει:**
boolean
### setSoundIsBuiltIn(boolean value) {#setSoundIsBuiltIn-boolean-}
```
public abstract void setSoundIsBuiltIn(boolean value)
```

Καθορίζει εάν αυτός ο ήχος είναι ενσωματωμένος ή όχι. Εάν αυτό το χαρακτηριστικό οριστεί σε true, η εφαρμογή δημιουργίας ενημερώνεται ώστε να ελέγξει το χαρακτηριστικό name που καθορίζεται για αυτόν τον ήχο στη λίστα ενσωματωμένων ήχων και μπορεί, έτσι, να εμφανίσει προσαρμοσμένο όνομα ή διεπαφή χρήστη όπως απαιτείται. Ανάγνωση-εγγραφή boolean.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |
### getSoundName() {#getSoundName--}
```
public abstract String getSoundName()
```

Καθορίζει ένα ανθρώπινα αναγνώσιμο όνομα για τον ήχο της μετάβασης. Η ιδιότητα (\#getSound.getSound/\#setSound(IAudio).setSound(IAudio)) πρέπει να οριστεί για να ληφθεί ή να οριστεί το όνομα ήχου. Ανάγνωση-εγγραφή String.

**Επιστρέφει:**
java.lang.String
### setSoundName(String value) {#setSoundName-java.lang.String-}
```
public abstract void setSoundName(String value)
```

Καθορίζει ένα ανθρώπινα αναγνώσιμο όνομα για τον ήχο της μετάβασης. Η ιδιότητα \#getSound.getSound/\#setSound(IAudio).setSound(IAudio) πρέπει να οριστεί για να ληφθεί ή να οριστεί το όνομα ήχου. Ανάγνωση-εγγραφή String.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | java.lang.String |  |
### getDuration() {#getDuration--}
```
public abstract int getDuration()
```

Ανακτά ή ορίζει τη διάρκεια του εφέ μετάβασης διαφάνειας σε χιλιοστά του δευτερολέπτου. Ανάγνωση/εγγραφή int.

--------------------

Αντίστοιχο με το χαρακτηριστικό p14:dur του στοιχείου p:transition στο σχήμα PresentationML. Εάν δεν οριστεί, η διάρκεια καθορίζεται αυτόματα βάσει της ιδιότητας \#getSpeed.getSpeed/\#setSpeed(int).setSpeed(int) και του τύπου μετάβασης.

**Επιστρέφει:**
int
### setDuration(int value) {#setDuration-int-}
```
public abstract void setDuration(int value)
```

Ανακτά ή ορίζει τη διάρκεια του εφέ μετάβασης διαφάνειας σε χιλιοστά του δευτερολέπτου. Ανάγνωση/εγγραφή int.

--------------------

Αντίστοιχο με το χαρακτηριστικό p14:dur του στοιχείου p:transition στο σχήμα PresentationML. Εάν δεν οριστεί, η διάρκεια καθορίζεται αυτόματα βάσει της ιδιότητας \#getSpeed.getSpeed/\#setSpeed(int).setSpeed(int) και του τύπου μετάβασης.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | int |  |