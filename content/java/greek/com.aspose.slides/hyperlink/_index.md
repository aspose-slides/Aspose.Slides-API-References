---
title: Hyperlink
second_title: Aspose.Slides για την αναφορά API της Java
description: Αναπαριστά έναν υπερσύνδεσμο.
type: docs
url: /el/com.aspose.slides/hyperlink/
---
**Κληρονομικότητα:**  
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**Όλες οι Υλοποιημένες Διεπαφές:**  
[com.aspose.slides.IHyperlink](../../com.aspose.slides/ihyperlink), com.aspose.slides.IDOMObject  
```
public final class Hyperlink extends PVIObject implements IHyperlink, IDOMObject
```

Αναπαριστά έναν υπερσύνδεσμο.

## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [Hyperlink(String url)](#Hyperlink-java.lang.String-) | Δημιουργεί μια παρουσία ενός υπερσυνδέσμου. |
| [Hyperlink(ISlide slide)](#Hyperlink-com.aspose.slides.ISlide-) | Δημιουργεί μια παρουσία ενός υπερσυνδέσμου που δείχνει σε συγκεκριμένη διαφάνεια. |
| [Hyperlink(Hyperlink source, String targetFrame, String tooltip, boolean history, boolean stopSoundsOnClick, boolean highlightClick)](#Hyperlink-com.aspose.slides.Hyperlink-java.lang.String-java.lang.String-boolean-boolean-boolean-) | Δημιουργεί μια παρουσία ενός υπερσυνδέσμου χρησιμοποιώντας έναν άλλο υπερσύνδεσμο ως πηγή, αντικαθιστώντας δευτερεύουσες ιδιότητες. |

## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getNoAction()](#getNoAction--) | Επιστρέφει έναν ειδικό υπερσύνδεσμο «μην κάνεις τίποτα». |
| [getMedia()](#getMedia--) | Επιστρέφει έναν ειδικό υπερσύνδεσμο «αναπαραγωγή αρχείου πολυμέσων». |
| [getNextSlide()](#getNextSlide--) | Επιστρέφει έναν υπερσύνδεσμο στην επόμενη διαφάνεια. |
| [getPreviousSlide()](#getPreviousSlide--) | Επιστρέφει έναν υπερσύνδεσμο στην προηγούμενη διαφάνεια. |
| [getFirstSlide()](#getFirstSlide--) | Επιστρέφει ένας υπερσύνδεσμος στην πρώτη διαφάνεια της παρουσίασης. |
| [getLastSlide()](#getLastSlide--) | Επιστρέφει ένας υπερσύνδεσμος στην τελευταία διαφάνεια της παρουσίασης. |
| [getLastVievedSlide()](#getLastVievedSlide--) | Επιστρέφει ένας υπερσύνδεσμος στην τελευταία προβλεπόμενη διαφάνεια. |
| [getEndShow()](#getEndShow--) | Επιστρέφει ένας υπερσύνδεσμος που λήγει την παρουσίαση. |
| [getActionType()](#getActionType--) | Επιστρέφει τον τύπο της ενέργειας του Hyperlink. |
| [getExternalUrl()](#getExternalUrl--) | Καθορίζει το εξωτερικό URL. |
| [getTargetSlide()](#getTargetSlide--) | Αν ο Hyperlink στοχεύει σε συγκεκριμένη διαφάνεια, επιστρέφει αυτή τη διαφάνεια. |
| [getExternalUrlOriginal()](#getExternalUrlOriginal--) | Αναπαριστά έναν υπερσύνδεσμο που ορίζεται για αυτό το τμήμα χωρίς να λαμβάνει υπόψη το πραγματικό περιεχόμενο του τμήματος. |
| [getTargetFrame()](#getTargetFrame--) | Επιστρέφει το πλαίσιο μέσα στο γονικό HTML frameset για τον στόχο του γονικού υπερσυνδέσμου όταν υπάρχει. |
| [setTargetFrame(String value)](#setTargetFrame-java.lang.String-) | Επιστρέφει το πλαίσιο μέσα στο γονικό HTML frameset για τον στόχο του γονικού υπερσυνδέσμου όταν υπάρχει. |
| [getTooltip()](#getTooltip--) | Επιστρέφει τη συμβολοσειρά που μπορεί να εμφανιστεί σε διεπαφή χρήστη ως συσχετισμένη με τον γονικό υπερσύνδεσμο. |
| [setTooltip(String value)](#setTooltip-java.lang.String-) | Επιστρέφει τη συμβολοσειρά που μπορεί να εμφανιστεί σε διεπαφή χρήστη ως συσχετισμένη με τον γονικό υπερσύνδεσμο. |
| [getHistory()](#getHistory--) | Καθορίζει εάν ο στόχος του γονικού υπερσυνδέσμου θα προστεθεί σε λίστα προσεγμένων υπερσυνδέσμων όταν ενεργοποιηθεί. |
| [setHistory(boolean value)](#setHistory-boolean-) | Καθορίζει εάν ο στόχος του γονικού υπερσυνδέσμου θα προστεθεί σε λίστα προσεγμένων υπερσυνδέσμων όταν ενεργοποιηθεί. |
| [getHighlightClick()](#getHighlightClick--) | Καθορίζει εάν ο υπερσύνδεσμος πρέπει να επισημαίνεται κατά το κλικ. |
| [setHighlightClick(boolean value)](#setHighlightClick-boolean-) | Καθορίζει εάν ο υπερσύνδεσμος πρέπει να επισημαίνεται κατά το κλικ. |
| [getStopSoundOnClick()](#getStopSoundOnClick--) | Καθορίζει εάν ο ήχος πρέπει να σταματήσει στο κλικ του υπερσυνδέσμου. |
| [setStopSoundOnClick(boolean value)](#setStopSoundOnClick-boolean-) | Καθορίζει εάν ο ήχος πρέπει να σταματήσει στο κλικ του υπερσυνδέσμου. |
| [getSound()](#getSound--) | Αναπαριστά τον ήχο αναπαραγωγής του υπερσυνδέσμου. |
| [setSound(IAudio value)](#setSound-com.aspose.slides.IAudio-) | Αναπαριστά τον ήχο αναπαραγωγής του υπερσυνδέσμου. |
| [getColorSource()](#getColorSource--) | Αναπαριστά την πηγή του χρώματος του υπερσυνδέσμου – είτε στυλ είτε μορφοποίηση τμήματος. |
| [setColorSource(int value)](#setColorSource-int-) | Αναπαριστά την πηγή του χρώματος του υπερσυνδέσμου – είτε στυλ είτε μορφοποίηση τμήματος. |
| [equals(Object obj)](#equals-java.lang.Object-) | Καθορίζει εάν οι δύο στιγμές του Hyperlink είναι ίσες. |
| [equals(IHyperlink hlink)](#equals-com.aspose.slides.IHyperlink-) | Καθορίζει εάν οι δύο στιγμές του Hyperlink είναι ίσες. |
| [op_Equality(Hyperlink hlink1, Hyperlink hlink2)](#op-Equality-com.aspose.slides.Hyperlink-com.aspose.slides.Hyperlink-) | Δοκιμάζει δύο υπερσυνδέσμους για ισότητα. |
| [op_Inequality(Hyperlink hlink1, Hyperlink hlink2)](#op-Inequality-com.aspose.slides.Hyperlink-com.aspose.slides.Hyperlink-) | Δοκιμάζει δύο υπερσυνδέσμους για ανισότητα. |
| [hashCode()](#hashCode--) | Λειτουργεί ως συνάρτηση κατακερματισμού για έναν συγκεκριμένο τύπο, κατάλληλη για χρήση σε αλγόριθμους κατακερματισμού και δομές δεδομένων όπως ένας πίνακας κατακερματισμού. |
| [getParent_Immediate()](#getParent-Immediate--) |  |

### Hyperlink(String url) {#Hyperlink-java.lang.String-}
```
public Hyperlink(String url)
```

Δημιουργεί μια παρουσία ενός υπερσυνδέσμου.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| url | java.lang.String | URL του υπερσυνδέσμου. |

### Hyperlink(ISlide slide) {#Hyperlink-com.aspose.slides.ISlide-}
```
public Hyperlink(ISlide slide)
```

Δημιουργεί μια παρουσία ενός υπερσυνδέσμου που δείχνει σε συγκεκριμένη διαφάνεια. Σημείωση: ο δημιουργημένος υπερσύνδεσμος πρέπει να ανατεθεί σε κάποιο αντικείμενο από την ίδια παρουσίαση, διαφορετικά ο σύνδεσμος θα αποθηκευτεί ως NoAction.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| slide | [ISlide](../../com.aspose.slides/islide) | Διαφάνεια-στόχος. |

### Hyperlink(Hyperlink source, String targetFrame, String tooltip, boolean history, boolean stopSoundsOnClick, boolean highlightClick) {#Hyperlink-com.aspose.slides.Hyperlink-java.lang.String-java.lang.String-boolean-boolean-boolean-}
```
public Hyperlink(Hyperlink source, String targetFrame, String tooltip, boolean history, boolean stopSoundsOnClick, boolean highlightClick)
```

Δημιουργεί μια παρουσία ενός υπερσυνδέσμου χρησιμοποιώντας έναν άλλο υπερσύνδεσμο ως πηγή, αντικαθιστώντας δευτερεύουσες ιδιότητες.

**Παράμεtroι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| source | [Hyperlink](../../com.aspose.slides/hyperlink) | Πηγή υπερσυνδέσμου |
| targetFrame | java.lang.String | Πλαίσιο προορισμού |
| tooltip | java.lang.String | Κείμενο συμβουλής εργαλείου |
| history | boolean | Καθορίζει εάν ο στόχος του γονικού υπερσυνδέσμου θα προστεθεί σε λίστα προσεγμένων υπερσυνδέσμων όταν ενεργοποιηθεί. |
| stopSoundsOnClick | boolean | Καθορίζει εάν ο ήχος πρέπει να σταματήσει στο κλικ του υπερσυνδέσμου. |
| highlightClick | boolean | Καθορίζει εάν ο υπερσύνδεσμος πρέπει να επισημανθεί κατά το κλικ. |

### getVersion() {#getVersion--}
```
public long getVersion()
```

Έκδοση. Μόνο για ανάγνωση long.

**Επιστρέφει:**
long

### getNoAction() {#getNoAction--}
```
public static Hyperlink getNoAction()
```

Επιστρέφει έναν ειδικό υπερσύνδεσμο «μην κάνεις τίποτα». Μόνο για ανάγνωση [Hyperlink](../../com.aspose.slides/hyperlink).

**Επιστρέφει:**
[Hyperlink](../../com.aspose.slides/hyperlink)

### getMedia() {#getMedia--}
```
public static Hyperlink getMedia()
```

Επιστρέφει έναν ειδικό υπερσύνδεσμο «αναπαραγωγή αρχείου πολυμέσων». Χρησιμοποιείται σε AudioFrame και VideoFrame. Μόνο για ανάγνωση [Hyperlink](../../com.aspose.slides/hyperlink).

**Επιστρέφει:**
[Hyperlink](../../com.aspose.slides/hyperlink)

### getNextSlide() {#getNextSlide--}
```
public static Hyperlink getNextSlide()
```

Επιστρέφει έναν υπερσύνδεσμο στην επόμενη διαφάνεια. Μόνο για ανάγνωση [Hyperlink](../../com.aspose.slides/hyperlink).

**Επιστρέφει:**
[Hyperlink](../../com.aspose.slides/hyperlink)

### getPreviousSlide() {#getPreviousSlide--}
```
public static Hyperlink getPreviousSlide()
```

Επιστρέφει έναν υπερσύνδεσμο στην προηγούμενη διαφάνεια. Μόνο για ανάγνωση [Hyperlink](../../com.aspose.slides/hyperlink).

**Επιστρέφει:**
[Hyperlink](../../com.aspose.slides/hyperlink)

### getFirstSlide() {#getFirstSlide--}
```
public static Hyperlink getFirstSlide()
```

Επιστρέφει έναν υπερσύνδεσμο στην πρώτη διαφάνεια της παρουσίασης. Μόνο για ανάγνωση [Hyperlink](../../com.aspose.slides/hyperlink).

**Επιστρέφει:**
[Hyperlink](../../com.aspose.slides/hyperlink)

### getLastSlide() {#getLastSlide--}
```
public static Hyperlink getLastSlide()
```

Επιστρέφει έναν υπερσύνδεσμο στην τελευταία διαφάνεια της παρουσίασης. Μόνο για ανάγνωση [Hyperlink](../../com.aspose.slides/hyperlink).

**Επιστρέφει:**
[Hyperlink](../../com.aspose.slides/hyperlink)

### getLastVievedSlide() {#getLastVievedSlide--}
```
public static Hyperlink getLastVievedSlide()
```

Επιστρέφει έναν υπερσύνδεσμο στην τελευταία προβλεπόμενη διαφάνεια. Μόνο για ανάγνωση [Hyperlink](../../com.aspose.slides/hyperlink).

**Επιστρέφει:**
[Hyperlink](../../com.aspose.slides/hyperlink)

### getEndShow() {#getEndShow--}
```
public static Hyperlink getEndShow()
```

Επιστρέφει έναν υπερσύνδεσμο που λήγει την παρουσίαση. Μόνο για ανάγνωση [Hyperlink](../../com.aspose.slides/hyperlink).

**Επιστρέφει:**
[Hyperlink](../../com.aspose.slides/hyperlink)

### getActionType() {#getActionType--}
```
public final int getActionType()
```

Επιστρέφει τον τύπο της ενέργειας του Hyperlink. Μόνο για ανάγνωση [HyperlinkActionType](../../com.aspose.slides/hyperlinkactiontype).

**Επιστρέφει:**
int

### getExternalUrl() {#getExternalUrl--}
```
public final String getExternalUrl()
```

Καθορίζει το εξωτερικό URL. Μόνο για ανάγνωση String.

**Επιστρέφει:**
java.lang.String

### getTargetSlide() {#getTargetSlide--}
```
public final ISlide getTargetSlide()
```

Αν ο Hyperlink στοχεύει σε συγκεκριμένη διαφάνεια, επιστρέφει αυτή τη διαφάνεια. Μόνο για ανάγνωση [ISlide](../../com.aspose.slides/islide).

**Επιστρέφει:**
[ISlide](../../com.aspose.slides/islide)

### getExternalUrlOriginal() {#getExternalUrlOriginal--}
```
public final String getExternalUrlOriginal()
```

Αναπαριστά έναν υπερσύνδεσμο που ορίζεται για αυτό το τμήμα χωρίς να λαμβάνει υπόψη το πραγματικό περιεχόμενο του τμήματος.

PowerPoint συμπεριφέρεται ειδικά για συνδέσμους και το αντίστοιχο κείμενό τους σε ένα τμήμα. Επιτρέπει τη δημιουργία κειμένου για τον υπερσύνδεσμο με τη μορφή ενός έγκυρου URL, διαφορετικό από τη πραγματική διεύθυνση του συνδέσμου. Σε αυτήν την περίπτωση, όταν προβάλετε τον σύνδεσμο στο παράθυρο επεξεργασίας, θα αλλάξει ώστε να ταιριάζει με το τμήμα κειμένου. Αυτή η ιδιότητα αντιπροσωπεύει την αρχική τιμή του υπερσυνδέσμου.

**Επιστρέφει:**
java.lang.String

### getTargetFrame() {#getTargetFrame--}
```
public final String getTargetFrame()
```

Επιστρέφει το πλαίσιο μέσα στο γονικό HTML frameset για τον στόχο του γονικού υπερσυνδέσμου όταν υπάρχει. Ανάγνωση/εγγραφή String.

**Επιστρέφει:**
java.lang.String

### setTargetFrame(String value) {#setTargetFrame-java.lang.String-}
```
public final void setTargetFrame(String value)
```

Ορίζει το πλαίσιο μέσα στο γονικό HTML frameset για τον στόχο του γονικού υπερσυνδέσμου όταν υπάρχει. Ανάγνωση/εγγραφή String.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | java.lang.String |  |

### getTooltip() {#getTooltip--}
```
public final String getTooltip()
```

Επιστρέφει τη συμβολοσειρά που μπορεί να εμφανιστεί σε διεπαφή χρήστη ως συσχετισμένη με τον γονικό υπερσύνδεσμο. Ανάγνωση/εγγραφή String.

**Επιστρέφει:**
java.lang.String

### setTooltip(String value) {#setTooltip-java.lang.String-}
```
public final void setTooltip(String value)
```

Ορίζει τη συμβολοσειρά που μπορεί να εμφανιστεί σε διεπαφή χρήστη ως συσχετισμένη με τον γονικό υπερσύνδεσμο. Ανάγνωση/εγγραφή String.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | java.lang.String |  |

### getHistory() {#getHistory--}
```
public final boolean getHistory()
```

Καθορίζει εάν ο στόχος του γονικού υπερσυνδέσμου θα προστεθεί σε λίστα προσεγμένων υπερσυνδέσμων όταν ενεργοποιηθεί. Ανάγνωση/εγγραφή boolean.

**Επιστρέφει:**
boolean

### setHistory(boolean value) {#setHistory-boolean-}
```
public final void setHistory(boolean value)
```

Καθορίζει εάν ο στόχος του γονικού υπερσυνδέσμου θα προστεθεί σε λίστα προσεγμένων υπερσυνδέσμων όταν ενεργοποιηθεί. Ανάγνωση/εγγραφή boolean.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |

### getHighlightClick() {#getHighlightClick--}
```
public final boolean getHighlightClick()
```

Καθορίζει εάν ο υπερσύνδεσμος πρέπει να επισημανθεί κατά το κλικ. Ανάγνωση/εγγραφή boolean.

**Επιστρέφει:**
boolean

### setHighlightClick(boolean value) {#setHighlightClick-boolean-}
```
public final void setHighlightClick(boolean value)
```

Καθορίζει εάν ο υπερσύνδεσμος πρέπει να επισημανθεί κατά το κλικ. Ανάγνωση/εγγραφή boolean.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |

### getStopSoundOnClick() {#getStopSoundOnClick--}
```
public final boolean getStopSoundOnClick()
```

Καθορίζει εάν ο ήχος πρέπει να σταματήσει στο κλικ του υπερσυνδέσμου. Ανάγνωση/εγγραφή boolean.

**Επιστρέφει:**
boolean

### setStopSoundOnClick(boolean value) {#setStopSoundOnClick-boolean-}
```
public final void setStopSoundOnClick(boolean value)
```

Καθορίζει εάν ο ήχος πρέπει να σταματήσει στο κλικ του υπερσυνδέσμου. Ανάγνωση/εγγραφή boolean.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |

### getSound() {#getSound--}
```
public final IAudio getSound()
```

Αναπαριστά τον ήχο αναπαραγωγής του υπερσυνδέσμου. Ανάγνωση/εγγραφή [IAudio](../../com.aspose.slides/iaudio).

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
> 
>      // Λαμβάνει τον πρώτο σύνδεσμο σχήματος
>      IHyperlink link = presentation.getSlides().get_Item(0).getShapes().get_Item(0).getHyperlinkClick();
> 
>      if (link.getSound() != null)
>      {
>          // Εξάγει τον ήχο του υπερσυνδέσμου σε byte array
>          byte[] audioData = link.getSound().getBinaryData();
>      }
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Επιστρέφει:**
[IAudio](../../com.aspose.slides/iaudio)

### setSound(IAudio value) {#setSound-com.aspose.slides.IAudio-}
```
public final void setSound(IAudio value)
```

Αναπαριστά τον ήχο αναπαραγωγής του υπερσυνδέσμου. Ανάγνωση/εγγραφή [IAudio](../../com.aspose.slides/iaudio).

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
> 
>      // Λάβετε τον πρώτο υπερσύνδεσμο του σχήματος
>      IHyperlink link = presentation.getSlides().get_Item(0).getShapes().get_Item(0).getHyperlinkClick();
> 
>      if (link.getSound() != null)
>      {
>          // Εξάγετε τον ήχο του υπερσυνδέσμου σε πίνακα byte
>          byte[] audioData = link.getSound().getBinaryData();
>      }
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [IAudio](../../com.aspose.slides/iaudio) |  |

### getColorSource() {#getColorSource--}
```
public final int getColorSource()
```

Αναπαριστά την πηγή του χρώματος του υπερσυνδέσμου – είτε στυλ είτε μορφοποίηση τμήματος. Ανάγνωση/εγγραφή [HyperlinkColorSource](../../com.aspose.slides/hyperlinkcolorsource).

**Επιστρέφει:**
int

### setColorSource(int value) {#setColorSource-int-}
```
public final void setColorSource(int value)
```

Αναπαριστά την πηγή του χρώματος του υπερσυνδέσμου – είτε στυλ είτε μορφοποίηση τμήματος. Ανάγνωση/εγγραφή [HyperlinkColorSource](../../com.aspose.slides/hyperlinkcolorsource).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | int |  |

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

Καθορίζει εάν οι δύο στιγμές του Hyperlink είναι ίσες.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| obj | java.lang.Object | Ο Hyperlink προς σύγκριση με τον τρέχοντα Hyperlink. |

**Επιστρέφει:**
boolean - **true** εάν ο καθορισμένος Hyperlink είναι ίσος με τον τρέχοντα Hyperlink· διαφορετικά, **false**.

### equals(IHyperlink hlink) {#equals-com.aspose.slides.IHyperlink-}
```
public final boolean equals(IHyperlink hlink)
```

Καθορίζει εάν οι δύο στιγμές του Hyperlink είναι ίσες.

**Παράμεtroι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| hlink | [IHyperlink](../../com.aspose.slides/ihyperlink) | Ο Hyperlink προς σύγκριση με τον τρέχοντα Hyperlink. |

**Επιστρέφει:**
boolean - **true** εάν ο καθορισμένος Hyperlink είναι ίσος με τον τρέχοντα Hyperlink· διαφορετικά, **false**.

### op_Equality(Hyperlink hlink1, Hyperlink hlink2) {#op-Equality-com.aspose.slides.Hyperlink-com.aspose.slides.Hyperlink-}
```
public static boolean op_Equality(Hyperlink hlink1, Hyperlink hlink2)
```

Δοκιμάζει δύο υπερσυνδέσμους για ισότητα.

**Παράμεtroι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| hlink1 | [Hyperlink](../../com.aspose.slides/hyperlink) | Πρώτος υπερσύνδεσμος προς δοκιμή. |
| hlink2 | [Hyperlink](../../com.aspose.slides/hyperlink) | Δεύτερος υπερσύνδεσμος προς δοκιμή. |

**Επιστρέφει:**
boolean - **true** εάν οι υπερσύνδεσμοι είναι ίσοι.

### op_Inequality(Hyperlink hlink1, Hyperlink hlink2) {#op-Inequality-com.aspose.slides.Hyperlink-com.aspose.slides.Hyperlink-}
```
public static boolean op_Inequality(Hyperlink hlink1, Hyperlink hlink2)
```

Δοκιμάζει δύο υπερσυνδέσμους για ανισότητα.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| hlink1 | [Hyperlink](../../com.aspose.slides/hyperlink) | Πρώτος υπερσύνδεσμος προς δοκιμή. |
| hlink2 | [Hyperlink](../../com.aspose.slides/hyperlink) | Δεύτερος υπερσύνδεσμος προς δοκιμή. |

**Επιστρέφει:**
boolean - **false** εάν οι υπερσύνδεσμοι είναι ίσοι.

### hashCode() {#hashCode--}
```
public int hashCode()
```

Λειτουργεί ως συνάρτηση κατακερματισμού για έναν συγκεκριμένο τύπο, κατάλληλη για χρήση σε αλγόριθμους κατακερματισμού και δομές δεδομένων όπως ένας πίνακας κατακερματισμού.

**Επιστρέφει:**
int - Κώδικας κατακερματισμού για ένα URL.

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Επιστρέφει το αντικείμενο Parent_Immediate. Μόνο για ανάγνωση IDOMObject.

**Επιστρέφει:**
com.aspose.slides.IDOMObject