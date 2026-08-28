---
title: SlideShowTransition
second_title: Aspose.Sildes για PHP μέσω αναφοράς API Java
description: 
type: docs

url: /el/aspose.slides/slideshowtransition/
---
## SlideShowTransition κλάση

Αναπαριστά τη μετάβαση παρουσίασης διαφανειών.

### equals {#equals}

| Όνομα | Περιγραφή |
| --- | --- |
| equals (Object) | Καθορίζει εάν τα δύο στιγμιότυπα SlideShowTransition είναι ίσα. Ανάγνωση/εγγραφή boolean. |

**Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| obj | Object | Το SlideShowTransition προς σύγκριση με το τρέχον SlideShowTransition. |

**Επιστρέφει:**
boolean


---


### getAdvanceAfter {#getAdvanceAfter}

| Όνομα | Περιγραφή |
| --- | --- |
| getAdvanceAfter () | Αυτό το χαρακτηριστικό καθορίζει εάν η παρουσίαση θα περάσει στην επόμενη διαφάνεια μετά από κάποιο χρονικό διάστημα. Ανάγνωση/εγγραφή boolean. |

**Επιστρέφει:**
boolean


---


### getAdvanceAfterTime {#getAdvanceAfterTime}

| Όνομα | Περιγραφή |
| --- | --- |
| getAdvanceAfterTime () | Καθορίζει το χρόνο, σε χιλιοστά του δευτερολέπτου, μετά τον οποίο πρέπει να ξεκινήσει η μετάβαση. Αυτή η ρύθμιση μπορεί να χρησιμοποιηθεί μαζί με το χαρακτηριστικό advClick. Εάν αυτό το χαρακτηριστικό δεν καθοριστεί, τότε θεωρείται ότι δεν θα υπάρξει αυτόματη προώθηση. Ανάγνωση/εγγραφή long. |

**Επιστρέφει:**
long


---


### getAdvanceOnClick {#getAdvanceOnClick}

| Όνομα | Περιγραφή |
| --- | --- |
| getAdvanceOnClick () | Καθορίζει εάν ένα κλικ του ποντικού θα προωθήσει τη διαφάνεια ή όχι. Εάν αυτό το χαρακτηριστικό δεν καθοριστεί, τότε υποτίθεται τιμή true. Ανάγνωση/εγγραφή boolean. |

**Επιστρέφει:**
boolean


---


### getDuration {#getDuration}

| Όνομα | Περιγραφή |
| --- | --- |
| getDuration () | Λαμβάνει ή ορίζει τη διάρκεια του εφέ μετάβασης διαφάνειας σε χιλιοστά του δευτερολέπτου. Ανάγνωση/εγγραφή int. Συμπίπτει με το χαρακτηριστικό p14:dur του στοιχείου p:transition στο σχήμα PresentationML. Εάν δεν οριστεί, η διάρκεια υπολογίζεται αυτόματα βάσει της ιδιότητας #getSpeed/ #setSpeed(int) και του τύπου μετάβασης. |

**Επιστρέφει:**
int


---


### getSound {#getSound}

| Όνομα | Περιγραφή |
| --- | --- |
| getSound () | Επιστρέφει ή ορίζει τα ενσωματωμένα δεδομένα ήχου. Ανάγνωση/εγγραφή IAudio. |

**Επιστρέφει:**
[Audio](../audio)


---


### getSoundIsBuiltIn {#getSoundIsBuiltIn}

| Όνομα | Περιγραφή |
| --- | --- |
| getSoundIsBuiltIn () | Καθορίζει εάν αυτός ο ήχος είναι ενσωματωμένος ή όχι. Εάν αυτό το χαρακτηριστικό οριστεί σε true, τότε η δημιουργική εφαρμογή ειδοποιείται να ελέγξει το χαρακτηριστικό name που έχει καθοριστεί για αυτόν τον ήχο στη λίστα ενσωματωμένων ήχων της και μπορεί να εμφανίσει προσαρμοσμένο όνομα ή διεπαφή χρήστη όπως απαιτείται. Ανάγνωση-εγγραφή boolean. |

**Επιστρέφει:**
boolean


---


### getSoundLoop {#getSoundLoop}

| Όνομα | Περιγραφή |
| --- | --- |
| getSoundLoop () | Αυτό το χαρακτηριστικό καθορίζει εάν ο ήχος θα επαναληφθεί μέχρι να συμβεί το επόμενο ηχητικό γεγονός στην παρουσίαση. Ανάγνωση/εγγραφή boolean. |

**Επιστρέφει:**
boolean


---


### getSoundMode {#getSoundMode}

| Όνομα | Περιγραφή |
| --- | --- |
| getSoundMode () | Ορίζει ή επιστρέφει τη λειτουργία ήχου για τη μετάβαση διαφάνειας. Ανάγνωση/εγγραφή TransitionSoundMode. |

**Επιστρέφει:**
int


---


### getSoundName {#getSoundName}

| Όνομα | Περιγραφή |
| --- | --- |
| getSoundName () | Καθορίζει ένα ανθρώπινα αναγνώσιμο όνομα για τον ήχο της μετάβασης. Η ιδιότητα Sound( #getSound/ #setSound(IAudio)) πρέπει να έχει οριστεί για να ληφθεί ή οριστεί το όνομα του ήχου. Ανάγνωση-εγγραφή String. |

**Επιστρέφει:**
String

**Εξαίρεση**

| Σφάλμα | Κατάσταση |
| --- | --- |
| PptxException | Όταν η ιδιότητα {@code Sound}( #getSound/ #setSound(IAudio)) δεν έχει οριστεί. Αυτό το όνομα εμφανίζεται στη διεπαφή χρήστη του PowerPoint όταν ρυθμίζεται χειροκίνητα ο ήχος μετάβασης. |


---


### getSpeed {#getSpeed}

| Όνομα | Περιγραφή |
| --- | --- |
| getSpeed () | Καθορίζει την ταχύτητα μετάβασης που θα χρησιμοποιηθεί κατά τη μετάβαση από την τρέχουσα διαφάνεια στην επόμενη. Ανάγνωση/εγγραφή TransitionSpeed. |

**Επιστρέφει:**
int


---


### getType {#getType}

| Όνομα | Περιγραφή |
| --- | --- |
| getType () | Τύπος μετάβασης. Ανάγνωση/εγγραφή TransitionType. |

**Επιστρέφει:**
int


---


### getValue {#getValue}

| Όνομα | Περιγραφή |
| --- | --- |
| getValue () | Τιμή μετάβασης παρουσίασης διαφανειών. Μόνο ανάγνωση ITransitionValueBase. |

**Επιστρέφει:**
[OrientationTransition](../orientationtransition), [OptionalBlackTransition](../optionalblacktransition), [FlyThroughTransition](../flythroughtransition), [LeftRightDirectionTransition](../leftrightdirectiontransition), [TransitionValueBase](../transitionvaluebase), [EightDirectionTransition](../eightdirectiontransition), [EmptyTransition](../emptytransition), [RippleTransition](../rippletransition), [WheelTransition](../wheeltransition), [RevealTransition](../revealtransition), [MorphTransition](../morphtransition), [SplitTransition](../splittransition), [InOutTransition](../inouttransition), [GlitterTransition](../glittertransition), [SideDirectionTransition](../sidedirectiontransition), [ShredTransition](../shredtransition), [CornerDirectionTransition](../cornerdirectiontransition)


---


### hashCode {#hashCode}

| Όνομα | Περιγραφή |
| --- | --- |
| hashCode () | Λειτουργεί ως συνάρτηση κατακερματισμού για έναν συγκεκριμένο τύπο, κατάλληλη για χρήση σε αλγορίθμους κατακερματισμού και δομές δεδομένων όπως ένα πίνακα κατακερματισμού. |

**Επιστρέφει:**
int


---


### setAdvanceAfter {#setAdvanceAfter}

| Όνομα | Περιγραφή |
| --- | --- |
| setAdvanceAfter (boolean) | Αυτό το χαρακτηριστικό καθορίζει εάν η παρουσίαση θα περάσει στην επόμενη διαφάνεια μετά από κάποιο χρονικό διάστημα. Ανάγνωση/εγγραφή boolean. |

**Επιστρέφει:**
void


---


### setAdvanceAfterTime {#setAdvanceAfterTime}

| Όνομα | Περιγραφή |
| --- | --- |
| setAdvanceAfterTime (long) | Καθορίζει το χρόνο, σε χιλιοστά του δευτερολέπτου, μετά τον οποίο πρέπει να ξεκινήσει η μετάβαση. Αυτή η ρύθμιση μπορεί να χρησιμοποιηθεί μαζί με το χαρακτηριστικό advClick. Εάν αυτό το χαρακτηριστικό δεν καθοριστεί, τότε θεωρείται ότι δεν θα υπάρξει αυτόματη προώθηση. Ανάγνωση/εγγραφή long. |

**Επιστρέφει:**
void


---


### setAdvanceOnClick {#setAdvanceOnClick}

| Όνομα | Περιγραφή |
| --- | --- |
| setAdvanceOnClick (boolean) | Καθορίζει εάν ένα κλικ του ποντικού θα προωθήσει τη διαφάνεια ή όχι. Εάν αυτό το χαρακτηριστικό δεν καθοριστεί, τότε υποτίθεται τιμή true. Ανάγνωση/εγγραφή boolean. |

**Επιστρέφει:**
void


---


### setDuration {#setDuration}

| Όνομα | Περιγραφή |
| --- | --- |
| setDuration (int) | Λαμβάνει ή ορίζει τη διάρκεια του εφέ μετάβασης διαφάνειας σε χιλιοστά του δευτερολέπτου. Ανάγνωση/εγγραφή int. Συμπίπτει με το χαρακτηριστικό p14:dur του στοιχείου p:transition στο σχήμα PresentationML. Εάν δεν οριστεί, η διάρκεια υπολογίζεται αυτόματα βάσει της ιδιότητας #getSpeed/ #setSpeed(int) και του τύπου μετάβασης. |

**Επιστρέφει:**
void


---


### setSound {#setSound}

| Όνομα | Περιγραφή |
| --- | --- |
| setSound ([Audio](../audio)) | Επιστρέφει ή ορίζει τα ενσωματωμένα δεδομένα ήχου. Ανάγνωση/εγγραφή IAudio. |

**Επιστρέφει:**
void


---


### setSoundIsBuiltIn {#setSoundIsBuiltIn}

| Όνομα | Περιγραφή |
| --- | --- |
| setSoundIsBuiltIn (boolean) | Καθορίζει εάν αυτός ο ήχος είναι ενσωματωμένος ή όχι. Εάν αυτό το χαρακτηριστικό οριστεί σε true, τότε η δημιουργική εφαρμογή ειδοποιείται να ελέγξει το χαρακτηριστικό name που έχει καθοριστεί για αυτόν τον ήχο στη λίστα ενσωματωμένων ήχων της και μπορεί να εμφανίσει προσαρμοσμένο όνομα ή διεπαφή χρήστη όπως απαιτείται. Ανάγνωση-εγγραφή boolean. |

**Επιστρέφει:**
void


---


### setSoundLoop {#setSoundLoop}

| Όνομα | Περιγραφή |
| --- | --- |
| setSoundLoop (boolean) | Αυτό το χαρακτηριστικό καθορίζει εάν ο ήχος θα επαναληφθεί μέχρι να συμβεί το επόμενο ηχητικό γεγονός στην παρουσίαση. Ανάγνωση/εγγραφή boolean. |

**Επιστρέφει:**
void


---


### setSoundMode {#setSoundMode}

| Όνομα | Περιγραφή |
| --- | --- |
| setSoundMode (int) | Ορίζει ή επιστρέφει τη λειτουργία ήχου για τη μετάβαση διαφάνειας. Ανάγνωση/εγγραφή TransitionSoundMode. |

**Επιστρέφει:**
void


---


### setSoundName {#setSoundName}

| Όνομα | Περιγραφή |
| --- | --- |
| setSoundName (String) | Καθορίζει ένα ανθρώπινα αναγνώσιμο όνομα για τον ήχο της μετάβασης. Η ιδιότητα Sound( #getSound/ #setSound(IAudio)) πρέπει να έχει οριστεί για να ληφθεί ή οριστεί το όνομα του ήχου. Ανάγνωση-εγγραφή String. |

**Επιστρέφει:**
void

**Εξαίρεση**

| Σφάλμα | Κατάσταση |
| --- | --- |
| PptxException | Όταν η ιδιότητα {@code Sound}( #getSound/ #setSound(IAudio)) δεν έχει οριστεί. Αυτό το όνομα εμφανίζεται στη διεπαφή χρήστη του PowerPoint όταν ρυθμίζεται χειροκίνητα ο ήχος μετάβασης. |


---


### setSpeed {#setSpeed}

| Όνομα | Περιγραφή |
| --- | --- |
| setSpeed (int) | Καθορίζει την ταχύτητα μετάβασης που θα χρησιμοποιηθεί κατά τη μετάβαση από την τρέχουσα διαφάνεια στην επόμενη. Ανάγνωση/εγγραφή TransitionSpeed. |

**Επιστρέφει:**
void


---


### setType {#setType}

| Όνομα | Περιγραφή |
| --- | --- |
| setType (int) | Τύπος μετάβασης. Ανάγνωση/εγγραφή TransitionType. |

**Επιστρέφει:**
void


---