---
title: NormalViewProperties
second_title: Aspose.Slides για Android μέσω Αναφοράς Java API
description: Αντιπροσωπεύει τις ιδιότητες της κανονικής προβολής.
type: docs
url: /el/com.aspose.slides/normalviewproperties/
---
**Κληρονομικότητα:**
java.lang.Object

**Όλες οι υλοποιημένες διεπαφές:**
[com.aspose.slides.INormalViewProperties](../../com.aspose.slides/inormalviewproperties)
```
public class NormalViewProperties implements INormalViewProperties
```

Αντιπροσωπεύει τις ιδιότητες της κανονικής προβολής. Η κανονική προβολή αποτελείται από τρεις περιοχές περιεχομένου: τη διαφάνεια ίδια, μια πλευρική περιοχή περιεχομένου και μια κάτω περιοχή περιεχομένου.

--------------------

> ```
> The following example shows how to configure ViewProperties.NormalViewProperties properties of a PowerPoint Presentation.
>  
>  //Δημιουργήστε ένα αντικείμενο παρουσίασης που αντιπροσωπεύει ένα αρχείο παρουσίασης
>  Presentation pres = new Presentation("demo.pptx");
>  try {
>      pres.getViewProperties().getNormalViewProperties().setHorizontalBarState(SplitterBarStateType.Restored);
>      pres.getViewProperties().getNormalViewProperties().setVerticalBarState(SplitterBarStateType.Maximized);
>      pres.getViewProperties().getNormalViewProperties().getRestoredTop().setAutoAdjust(true);
>      pres.getViewProperties().getNormalViewProperties().getRestoredTop().setDimensionSize(80);
>      pres.getViewProperties().getNormalViewProperties().setShowOutlineIcons(true);
>      pres.save("presentation_normal_view_state.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getShowOutlineIcons()](#getShowOutlineIcons--) | Καθορίζει εάν η εφαρμογή πρέπει να εμφανίζει εικονίδια όταν εμφανίζει περιεχόμενο περιγράμματος σε οποιαδήποτε από τις περιοχές περιεχομένου της λειτουργίας κανονικής προβολής. |
| [setShowOutlineIcons(boolean value)](#setShowOutlineIcons-boolean-) | Καθορίζει εάν η εφαρμογή πρέπει να εμφανίζει εικονίδια όταν εμφανίζει περιεχόμενο περιγράμματος σε οποιαδήποτε από τις περιοχές περιεχομένου της λειτουργίας κανονικής προβολής. |
| [getSnapVerticalSplitter()](#getSnapVerticalSplitter--) | Καθορίζει εάν ο κάθετος διαχωριστής πρέπει να «κλειδώνει» σε κατάσταση ελαχιστοποίησης όταν η πλευρική περιοχή είναι επαρκώς μικρή. |
| [setSnapVerticalSplitter(boolean value)](#setSnapVerticalSplitter-boolean-) | Καθορίζει εάν ο κάθετος διαχωριστής πρέπει να «κλειδώνει» σε κατάσταση ελαχιστοποίησης όταν η πλευρική περιοχή είναι επαρκώς μικρή. |
| [getVerticalBarState()](#getVerticalBarState--) | Καθορίζει την κατάσταση στην οποία πρέπει να εμφανίζεται η κάθετη μπάρα διαχωριστή. |
| [setVerticalBarState(int value)](#setVerticalBarState-int-) | Καθορίζει την κατάσταση στην οποία πρέπει να εμφανίζεται η κάθετη μπάρα διαχωριστή. |
| [getHorizontalBarState()](#getHorizontalBarState--) | Καθορίζει την κατάσταση στην οποία πρέπει να εμφανίζεται η οριζόντια μπάρα διαχωριστή. |
| [setHorizontalBarState(int value)](#setHorizontalBarState-int-) | Καθορίζει την κατάσταση στην οποία πρέπει να εμφανίζεται η οριζόντια μπάρα διαχωριστή. |
| [getPreferSingleView()](#getPreferSingleView--) | Καθορίζει εάν ο χρήστης προτιμά να δει μια ενιαία περιοχή περιεχομένου πλήρους παραθύρου αντί για την τυπική κανονική προβολή με τρεις περιοχές περιεχομένου. |
| [setPreferSingleView(boolean value)](#setPreferSingleView-boolean-) | Καθορίζει εάν ο χρήστης προτιμά να δει μια ενιαία περιοχή περιεχομένου πλήρους παραθύρου αντί για την τυπική κανονική προβολή με τρεις περιοχές περιεχομένου. |
| [getRestoredLeft()](#getRestoredLeft--) | Αυτό το στοιχείο καθορίζει το μέγεθος της πλευρικής περιοχής περιεχομένου της κανονικής προβολής, όταν η περιοχή βρίσκεται σε μεταβλητό αποκατεστημένο μέγεθος (ούτε ελαχιστοποιημένη ούτε μεγιστοποιημένη). |
| [getRestoredTop()](#getRestoredTop--) | Αυτό το στοιχείο καθορίζει το μέγεθος της επάνω περιοχής διαφάνειας της κανονικής προβολής, όταν η περιοχή βρίσκεται σε μεταβλητό αποκατεστημένο μέγεθος (ούτε ελαχιστοποιημένη ούτε μεγιστοποιημένη). |
### getShowOutlineIcons() {#getShowOutlineIcons--}
```
public final boolean getShowOutlineIcons()
```


Καθορίζει εάν η εφαρμογή πρέπει να εμφανίζει εικονίδια όταν εμφανίζει περιεχόμενο περιγράμματος σε οποιαδήποτε από τις περιοχές περιεχομένου της λειτουργίας κανονικής προβολής. Ανάγνωση/εγγραφή boolean.

**Επιστρέφει:**
boolean
### setShowOutlineIcons(boolean value) {#setShowOutlineIcons-boolean-}
```
public final void setShowOutlineIcons(boolean value)
```


Καθορίζει εάν η εφαρμογή πρέπει να εμφανίζει εικονίδια όταν εμφανίζει περιεχόμενο περιγράμματος σε οποιαδήποτε από τις περιοχές περιεχομένου της λειτουργίας κανονικής προβολής. Ανάγνωση/εγγραφή boolean.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |

### getSnapVerticalSplitter() {#getSnapVerticalSplitter--}
```
public final boolean getSnapVerticalSplitter()
```


Καθορίζει εάν ο κάθετος διαχωριστής πρέπει να «κλειδώνει» σε κατάσταση ελαχιστοποίησης όταν η πλευρική περιοχή είναι επαρκώς μικρή. Ανάγνωση/εγγραφή boolean.

**Επιστρέφει:**
boolean
### setSnapVerticalSplitter(boolean value) {#setSnapVerticalSplitter-boolean-}
```
public final void setSnapVerticalSplitter(boolean value)
```


Καθορίζει εάν ο κάθετος διαχωριστής πρέπει να «κλειδώνει» σε κατάσταση ελαχιστοποίησης όταν η πλευρική περιοχή είναι επαρκώς μικρή. Ανάγνωση/εγγραφή boolean.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |

### getVerticalBarState() {#getVerticalBarState--}
```
public final int getVerticalBarState()
```


Καθορίζει την κατάσταση στην οποία πρέπει να εμφανίζεται η κάθετη μπάρα διαχωριστή. Μια κάθετη μπάρα διαχωριστή χωρίζει τη διαφάνεια από την πλευρική περιοχή περιεχομένου.

**Επιστρέφει:**
int
### setVerticalBarState(int value) {#setVerticalBarState-int-}
```
public final void setVerticalBarState(int value)
```


Καθορίζει την κατάσταση στην οποία πρέπει να εμφανίζεται η κάθετη μπάρα διαχωριστή. Μια κάθετη μπάρα διαχωριστή χωρίζει τη διαφάνεια από την πλευρική περιοχή περιεχομένου.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | int |  |

### getHorizontalBarState() {#getHorizontalBarState--}
```
public final int getHorizontalBarState()
```


Καθορίζει την κατάσταση στην οποία πρέπει να εμφανίζεται η οριζόντια μπάρα διαχωριστή. Μια οριζόντια μπάρα διαχωριστή χωρίζει τη διαφάνεια από την περιοχή περιεχομένου κάτω από τη διαφάνεια.

**Επιστρέφει:**
int
### setHorizontalBarState(int value) {#setHorizontalBarState-int-}
```
public final void setHorizontalBarState(int value)
```


Καθορίζει την κατάσταση στην οποία πρέπει να εμφανίζεται η οριζόντια μπάρα διαχωριστή. Μια οριζόντια μπάρα διαχωριστή χωρίζει τη διαφάνεια από την περιοχή περιεχομένου κάτω από τη διαφάνεια.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | int |  |

### getPreferSingleView() {#getPreferSingleView--}
```
public final boolean getPreferSingleView()
```


Καθορίζει εάν ο χρήστης προτιμά να δει μια ενιαία περιοχή περιεχομένου πλήρους παραθύρου αντί για την τυπική κανονική προβολή με τρεις περιοχές περιεχομένου. Εάν ενεργοποιηθεί, η εφαρμογή ενδέχεται να επιλέξει να εμφανίσει μια από τις περιοχές περιεχομένου σε ολόκληρο το παράθυρο. Ανάγνωση/εγγραφή boolean.

**Επιστρέφει:**
boolean
### setPreferSingleView(boolean value) {#setPreferSingleView-boolean-}
```
public final void setPreferSingleView(boolean value)
```


Καθορίζει εάν ο χρήστης προτιμά να δει μια ενιαία περιοχή περιεχομένου πλήρους παραθύρου αντί για την τυπική κανονική προβολή με τρεις περιοχές περιεχομένου. Εάν ενεργοποιηθεί, η εφαρμογή ενδέχεται να επιλέξει να εμφανίσει μια από τις περιοχές περιεχομένου σε ολόκληρο το παράθυρο. Ανάγνωση/εγγραφή boolean.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |

### getRestoredLeft() {#getRestoredLeft--}
```
public final INormalViewRestoredProperties getRestoredLeft()
```


Αυτό το στοιχείο καθορίζει το μέγεθος της πλευρικής περιοχής περιεχομένου της κανονικής προβολής, όταν η περιοχή βρίσκεται σε μεταβλητό αποκατεστημένο μέγεθος (ούτε ελαχιστοποιημένη ούτε μεγιστοποιημένη). Μόνο για ανάγνωση [INormalViewRestoredProperties](../../com.aspose.slides/inormalviewrestoredproperties).

**Επιστρέφει:**
[INormalViewRestoredProperties](../../com.aspose.slides/inormalviewrestoredproperties)
### getRestoredTop() {#getRestoredTop--}
```
public final INormalViewRestoredProperties getRestoredTop()
```


Αυτό το στοιχείο καθορίζει το μέγεθος της επάνω περιοχής διαφάνειας της κανονικής προβολής, όταν η περιοχή βρίσκεται σε μεταβλητό αποκατεστημένο μέγεθος (ούτε ελαχιστοποιημένη ούτε μεγιστοποιημένη). Μόνο για ανάγνωση [INormalViewRestoredProperties](../../com.aspose.slides/inormalviewrestoredproperties).

**Επιστρέφει:**
[INormalViewRestoredProperties](../../com.aspose.slides/inormalviewrestoredproperties)