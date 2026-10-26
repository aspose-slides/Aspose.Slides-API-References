---
title: Hyperlink
second_title: Aspose.Slides για Android μέσω Java API Αναφορά
description: Αντιπροσωπεύει έναν υπερσύνδεσμο.
type: docs
url: /el/com.aspose.slides/hyperlink/
---
**Κληρονομικότητα:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**Όλες οι υλοποιημένες διεπαφές:**
[com.aspose.slides.IHyperlink](../../com.aspose.slides/ihyperlink), com.aspose.slides.IDOMObject
```
public final class Hyperlink extends PVIObject implements IHyperlink, IDOMObject
```

Αναπαριστά έναν υπερσύνδεσμο.
## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [Hyperlink(String url)](#Hyperlink-java.lang.String-) | Creates an instance of a hyperlink. |
| [Hyperlink(ISlide slide)](#Hyperlink-com.aspose.slides.ISlide-) | Creates an instance of a hyperlink which points to specific slide. |
| [Hyperlink(Hyperlink source, String targetFrame, String tooltip, boolean history, boolean stopSoundsOnClick, boolean highlightClick)](#Hyperlink-com.aspose.slides.Hyperlink-java.lang.String-java.lang.String-boolean-boolean-boolean-) | Creates an instance of a hyperlink using another hyperlink as source, overriding secondary properties. |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getNoAction()](#getNoAction--) | Επιστρέφει έναν ειδικό υπερσύνδεσμο «do nothing». |
| [getMedia()](#getMedia--) | Επιστρέφει έναν ειδικό υπερσύνδεσμο «play mediafile». |
| [getNextSlide()](#getNextSlide--) | Επιστρέφει έναν υπερσύνδεσμο στην επόμενη διαφάνεια. |
| [getPreviousSlide()](#getPreviousSlide--) | Επιστρέφει έναν υπερσύνδεσμο στην προηγούμενη διαφάνεια. |
| [getFirstSlide()](#getFirstSlide--) | Επιστρέφει έναν υπερσύνδεσμο στην πρώτη διαφάνεια της παρουσίασης. |
| [getLastSlide()](#getLastSlide--) | Επιστρέφει έναν υπερσύνδεσμο στην τελευταία διαφάνεια της παρουσίασης. |
| [getLastVievedSlide()](#getLastVievedSlide--) | Επιστρέφει έναν υπερσύνδεσμο στην τελευταία προβλεπόμενη διαφάνεια. |
| [getEndShow()](#getEndShow--) | Επιστρέφει έναν υπερσύνδεσμο που τερματίζει την παρουσίαση. |
| [getActionType()](#getActionType--) | Επιστρέφει τον τύπο ενέργειας του Hyperlink. |
| [getExternalUrl()](#getExternalUrl--) | Καθορίζει το εξωτερικό URL. |
| [getTargetSlide()](#getTargetSlide--) | Εάν ο Hyperlink στοχεύει σε συγκεκριμένη διαφάνεια, επιστρέφει αυτή τη διαφάνεια. |
| [getExternalUrlOriginal()](#getExternalUrlOriginal--) | Αναπαριστά έναν υπερσύνδεσμο που ορίζεται για αυτό το τμήμα χωρίς να λαμβάνει υπόψη το πραγματικό περιεχόμενο του τμήματος. |
| [getTargetFrame()](#getTargetFrame--) | Επιστρέφει το frame εντός του γονικού HTML frameset για τον στόχο του γονικού υπερσυνδέσμου όταν υπάρχει. |
| [setTargetFrame(String value)](#setTargetFrame-java.lang.String-) | Επιστρέφει το frame εντός του γονικού HTML frameset για τον στόχο του γονικού υπερσυνδέσμου όταν υπάρχει. |
| [getTooltip()](#getTooltip--) | Επιστρέφει τη συμβολοσειρά που μπορεί να εμφανιστεί σε διεπαφή χρήστη ως σχετική με τον γονικό υπερσύνδεσμο. |
| [setTooltip(String value)](#setTooltip-java.lang.String-) | Επιστρέφει τη συμβολοσειρά που μπορεί να εμφανιστεί σε διεπαφή χρήστη ως σχετική με τον γονικό υπερσύνδεσμο. |
| [getHistory()](#getHistory--) | Καθορίζει εάν ο στόχος του γονικού υπερσυνδέσμου θα προστεθεί σε λίστα προβλεπόμενων υπερσυνδέσμων όταν κληθεί. |
| [setHistory(boolean value)](#setHistory-boolean-) | Καθορίζει εάν ο στόχος του γονικού υπερσυνδέσμου θα προστεθεί σε λίστα προβλεπόμενων υπερσυνδέσμων όταν κληθεί. |
| [getHighlightClick()](#getHighlightClick--) | Καθορίζει εάν ο υπερσύνδεσμος πρέπει να επισημαίνεται με κλικ. |
| [setHighlightClick(boolean value)](#setHighlightClick-boolean-) | Καθορίζει εάν ο υπερσύνδεσμος πρέπει να επισημαίνεται με κλικ. |
| [getStopSoundOnClick()](#getStopSoundOnClick--) | Καθορίζει εάν ο ήχος πρέπει να σταματήσει κατά το κλικ του υπερσυνδέσμου. |
| [setStopSoundOnClick(boolean value)](#setStopSoundOnClick-boolean-) | Καθορίζει εάν ο ήχος πρέπει να σταματήσει κατά το κλικ του υπερσυνδέσμου. |
| [getSound()](#getSound--) | Αναπαριστά τον ήχο αναπαραγωγής του υπερσυνδέσμου. |
| [setSound(IAudio value)](#setSound-com.aspose.slides.IAudio-) | Αναπαριστά τον ήχο αναπαραγωγής του υπερσυνδέσμου. |
| [getColorSource()](#getColorSource--) | Αναπαριστά την πηγή χρώματος του υπερσυνδέσμου – είτε στυλ είτε μορφή τμήματος. |
| [setColorSource(int value)](#setColorSource-int-) | Αναπαριστά την πηγή χρώματος του υπερσυνδέσμου – είτε στυλ είτε μορφή τμήματος. |
| [equals(Object obj)](#equals-java.lang.Object-) | Καθορίζει εάν οι δύο περιπτώσεις Hyperlink είναι ίσες. |
| [equals(IHyperlink hlink)](#equals-com.aspose.slides.IHyperlink-) | Καθορίζει εάν οι δύο περιπτώσεις Hyperlink είναι ίσες. |
| [op_Equality(Hyperlink hlink1, Hyperlink hlink2)](#op-Equality-com.aspose.slides.Hyperlink-com.aspose.slides.Hyperlink-) | Δοκιμάζει δύο υπερσυνδέσμους για ισότητα. |
| [op_Inequality(Hyperlink hlink1, Hyperlink hlink2)](#op-Inequality-com.aspose.slides.Hyperlink-com.aspose.slides.Hyperlink-) | Δοκιμάζει δύο υπερσυνδέσμους για ανισότητα. |
| [hashCode()](#hashCode--) | Λειτουργεί ως συνάρτηση κατακερματισμού για έναν συγκεκριμένο τύπο, κατάλληλη για αλγόριθμους κατακερματισμού και δομές δεδομένων όπως πίνακας κατακερματισμού. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
### Hyperlink(String url) {#Hyperlink-java.lang.String-}
```
public Hyperlink(String url)
```

Δημιουργεί μια παρουσία υπερσυνδέσμου.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| url | java.lang.String | Hyperlink URL. |

### Hyperlink(ISlide slide) {#Hyperlink-com.aspose.slides.ISlide-}
```
public Hyperlink(ISlide slide)
```

Δημιουργεί μια παρουσία υπερσυνδέσμου που στοχεύει σε συγκεκριμένη διαφάνεια. Σημείωση: ο δημιουργημένος υπερσύνδεσμος πρέπει να εκχωρηθεί σε κάποιο αντικείμενο από την ίδια παρουσίαση· διαφορετικά ο σύνδεσμος θα αποθηκευτεί ως NoAction.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| slide | [ISlide](../../com.aspose.slides/islide) | Target slide. |

### Hyperlink(Hyperlink source, String targetFrame, String tooltip, boolean history, boolean stopSoundsOnClick, boolean highlightClick) {#Hyperlink-com.aspose.slides.Hyperlink-java.lang.String-java.lang.String-boolean-boolean-boolean-}
```
public Hyperlink(Hyperlink source, String targetFrame, String tooltip, boolean history, boolean stopSoundsOnClick, boolean highlightClick)
```

Δημιουργεί μια παρουσία υπερσυνδέσμου χρησιμοποιώντας έναν άλλο υπερσύνδεσμο ως πηγή, παρακάμπτοντας τις δευτερεύουσες ιδιότητες.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| source | [Hyperlink](../../com.aspose.slides/hyperlink) | Source hyperlink |
| targetFrame | java.lang.String | Target frame |
| tooltip | java.lang.String | Tooltip text |
| history | boolean | Καθορίζει εάν ο στόχος του γονικού υπερσυνδέσμου θα προστεθεί σε λίστα προβλεπόμενων υπερσυνδέσμων όταν κληθεί. |
| stopSoundsOnClick | boolean | Καθορίζει εάν ο ήχος πρέπει να σταματήσει κατά το κλικ του υπερσυνδέσμου. |
| highlightClick | boolean | Καθορίζει εάν ο υπερσύνδεσμος πρέπει να επισημαίνεται με κλικ. |

### getVersion() {#getVersion--}
```
public long getVersion()
```

Έκδοση. **Μόνο για ανάγνωση** long.

**Επιστρέφει:**
long
### getNoAction() {#getNoAction--}
```
public static Hyperlink getNoAction()
```

Επιστρέφει έναν ειδικό υπερσύνδεσμο «do nothing». **Μόνο για ανάγνωση** [Hyperlink](../../com.aspose.slides/hyperlink).

**Επιστρέφει:**
[Hyperlink](../../com.aspose.slides/hyperlink)
### getMedia() {#getMedia--}
```
public static Hyperlink getMedia()
```

Επιστρέφει έναν ειδικό υπερσύνδεσμο «play mediafile». Χρησιμοποιείται σε AudioFrame και VideoFrame. **Μόνο για ανάγνωση** [Hyperlink](../../com.aspose.slides/hyperlink).

**Επιστρέφει:**
[Hyperlink](../../com.aspose.slides/hyperlink)
### getNextSlide() {#getNextSlide--}
```
public static Hyperlink getNextSlide()
```

Επιστρέφει έναν υπερσύνδεσμο στην επόμενη διαφάνεια. **Μόνο για ανάγνωση** [Hyperlink](../../com.aspose.slides/hyperlink).

**Επιστρέφει:**
[Hyperlink](../../com.aspose.slides/hyperlink)
### getPreviousSlide() {#getPreviousSlide--}
```
public static Hyperlink getPreviousSlide()
```

Επιστρέφει έναν υπερσύνδεσμο στην προηγούμενη διαφάνεια. **Μόνο για ανάγνωση** [Hyperlink](../../com.aspose.slides/hyperlink).

**Επιστρέφει:**
[Hyperlink](../../com.aspose.slides/hyperlink)
### getFirstSlide() {#getFirstSlide--}
```
public static Hyperlink getFirstSlide()
```

Επιστρέφει έναν υπερσύνδεσμο στην πρώτη διαφάνεια της παρουσίασης. **Μόνο για ανάγνωση** [Hyperlink](../../com.aspose.slides/hyperlink).

**Επιστρέφει:**
[Hyperlink](../../com.aspose.slides/hyperlink)
### getLastSlide() {#getLastSlide--}
```
public static Hyperlink getLastSlide()
```

Επιστρέφει έναν υπερσύνδεσμο στην τελευταία διαφάνεια της παρουσίασης. **Μόνο για ανάγνωση** [Hyperlink](../../com.aspose.slides/hyperlink).

**Επιστρέφει:**
[Hyperlink](../../com.aspose.slides/hyperlink)
### getLastVievedSlide() {#getLastVievedSlide--}
```
public static Hyperlink getLastVievedSlide()
```

Επιστρέφει έναν υπερσύνδεσμο στην τελευταία προβλεπόμενη διαφάνεια. **Μόνο για ανάγνωση** [Hyperlink](../../com.aspose.slides/hyperlink).

**Επιστρέφει:**
[Hyperlink](../../com.aspose.slides/hyperlink)
### getEndShow() {#getEndShow--}
```
public static Hyperlink getEndShow()
```

Επιστρέφει έναν υπερσύνδεσμο που τερματίζει την παρουσίαση. **Μόνο για ανάγνωση** [Hyperlink](../../com.aspose.slides/hyperlink).

**Επιστρέφει:**
[Hyperlink](../../com.aspose.slides/hyperlink)
### getActionType() {#getActionType--}
```
public final int getActionType()
```

Επιστρέφει τον τύπο ενέργειας του Hyperlink. **Μόνο για ανάγνωση** [HyperlinkActionType](../../com.aspose.slides/hyperlinkactiontype).

**Επιστρέφει:**
int
### getExternalUrl() {#getExternalUrl--}
```
public final String getExternalUrl()
```

Καθορίζει το εξωτερικό URL. **Μόνο για ανάγνωση** String.

**Επιστρέφει:**
java.lang.String
### getTargetSlide() {#getTargetSlide--}
```
public final ISlide getTargetSlide()
```

Εάν ο Hyperlink στοχεύει σε συγκεκριμένη διαφάνεια, επιστρέφει αυτή τη διαφάνεια. **Μόνο για ανάγνωση** [ISlide](../../com.aspose.slides/islide).

**Επιστρέφει:**
[ISlide](../../com.aspose.slides/islide)
### getExternalUrlOriginal() {#getExternalUrlOriginal--}
```
public final String getExternalUrlOriginal()
```

Αναπαριστά έναν υπερσύνδεσμο που ορίζεται για αυτό το τμήμα χωρίς να λαμβάνει υπόψη το πραγματικό περιεχόμενο του τμήματος.

PowerPoint συμπεριφέρεται ειδικά για συνδέσμους και το αντίστοιχο κείμενο σε ένα τμήμα. Σας επιτρέπει να δημιουργήσετε κείμενο για τον υπερσύνδεσμο με τη μορφή έγκυρου URL, διαφορετικό από τη πραγματική διεύθυνση του συνδέσμου. Σε αυτή την περίπτωση, όταν προβάλετε το σύνδεσμο στο παράθυρο επεξεργασίας, θα αλλάξει ώστε να ταιριάζει με το κείμενο του τμήματος. Αυτή η ιδιότητα αντιπροσωπεύει την αρχική τιμή του υπερσυνδέσμου.

**Επιστρέφει:**
java.lang.String
### getTargetFrame() {#getTargetFrame--}
```
public final String getTargetFrame()
```

Επιστρέφει το frame εντός του γονικού HTML frameset για τον στόχο του γονικού υπερσυνδέσμου όταν υπάρχει. **Ανάγνωση/εγγραφή** String.

**Επιστρέφει:**
java.lang.String
### setTargetFrame(String value) {#setTargetFrame-java.lang.String-}
```
public final void setTargetFrame(String value)
```

Επιστρέφει το frame εντός του γονικού HTML frameset για τον στόχο του γονικού υπερσυνδέσμου όταν υπάρχει. **Ανάγνωση/εγγραφή** String.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | java.lang.String |  |

### getTooltip() {#getTooltip--}
```
public final String getTooltip()
```

Επιστρέφει τη συμβολοσειρά που μπορεί να εμφανιστεί σε διεπαφή χρήστη ως σχετική με τον γονικό υπερσύνδεσμο. **Ανάγνωση/εγγραφή** String.

**Επιστρέφει:**
java.lang.String
### setTooltip(String value) {#setTooltip-java.lang.String-}
```
public final void setTooltip(String value)
```

Επιστρέφει τη συμβολοσειρά που μπορεί να εμφανιστεί σε διεπαφή χρήστη ως σχετική με τον γονικό υπερσύνδεσμο. **Ανάγνωση/εγγραφή** String.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | java.lang.String |  |

### getHistory() {#getHistory--}
```
public final boolean getHistory()
```

Καθορίζει εάν ο στόχος του γονικού υπερσυνδέσμου θα προστεθεί σε λίστα προβλεπόμενων υπερσυνδέσμων όταν κληθεί. **Ανάγνωση/εγγραφή** boolean.

**Επιστρέφει:**
boolean
### setHistory(boolean value) {#setHistory-boolean-}
```
public final void setHistory(boolean value)
```

Καθορίζει εάν ο στόχος του γονικού υπερσυνδέσμου θα προστεθεί σε λίστα προβλεπόμενων υπερσυνδέσμων όταν κληθεί. **Ανάγνωση/εγγραφή** boolean.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |

### getHighlightClick() {#getHighlightClick--}
```
public final boolean getHighlightClick()
```

Καθορίζει εάν ο υπερσύνδεσμος πρέπει να επισημαίνεται με κλικ. **Ανάγνωση/εγγραφή** boolean.

**Επιστρέφει:**
boolean
### setHighlightClick(boolean value) {#setHighlightClick-boolean-}
```
public final void setHighlightClick(boolean value)
```

Καθορίζει εάν ο υπερσύνδεσμος πρέπει να επισημαίνεται με κλικ. **Ανάγνωση/εγγραφή** boolean.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |

### getStopSoundOnClick() {#getStopSoundOnClick--}
```
public final boolean getStopSoundOnClick()
```

Καθορίζει εάν ο ήχος πρέπει να σταματήσει κατά το κλικ του υπερσυνδέσμου. **Ανάγνωση/εγγραφή** boolean.

**Επιστρέφει:**
boolean
### setStopSoundOnClick(boolean value) {#setStopSoundOnClick-boolean-}
```
public final void setStopSoundOnClick(boolean value)
```

Καθορίζει εάν ο ήχος πρέπει να σταματήσει κατά το κλικ του υπερσυνδέσμου. **Ανάγνωση/εγγραφή** boolean.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |

### getSound() {#getSound--}
```
public final IAudio getSound()
```

Αναπαριστά τον ήχο αναπαραγωγής του υπερσυνδέσμου. **Ανάγνωση/εγγραφή** [IAudio](../../com.aspose.slides/iaudio).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
> 
>      // Λάβετε τον υπερσύνδεσμο του πρώτου σχήματος
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

**Επιστρέφει:**
[IAudio](../../com.aspose.slides/iaudio)
### setSound(IAudio value) {#setSound-com.aspose.slides.IAudio-}
```
public final void setSound(IAudio value)
```

Αναπαριστά τον ήχο αναπαραγωγής του υπερσυνδέσμου. **Ανάγνωση/εγγραφή** [IAudio](../../com.aspose.slides/iaudio).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
> 
>      // Λάβετε τον υπερσύνδεσμο του πρώτου σχήματος
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

Αναπαριστά την πηγή χρώματος του υπερσυνδέσμου – είτε στυλ είτε μορφή τμήματος. **Ανάγνωση/εγγραφή** [HyperlinkColorSource](../../com.aspose.slides/hyperlinkcolorsource).

**Επιστρέφει:**
int
### setColorSource(int value) {#setColorSource-int-}
```
public final void setColorSource(int value)
```

Αναπαριστά την πηγή χρώματος του υπερσυνδέσμου – είτε στυλ είτε μορφή τμήματος. **Ανάγνωση/εγγραφή** [HyperlinkColorSource](../../com.aspose.slides/hyperlinkcolorsource).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | int |  |

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

Καθορίζει εάν οι δύο περιπτώσεις Hyperlink είναι ίσες.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| obj | java.lang.Object | The Hyperlink to compare with the current Hyperlink. |

**Επιστρέφει:**
boolean - **true** εάν ο καθορισμένος Hyperlink είναι ίσος με τον τρέχοντα Hyperlink· διαφορετικά, **false**.
### equals(IHyperlink hlink) {#equals-com.aspose.slides.IHyperlink-}
```
public final boolean equals(IHyperlink hlink)
```

Καθορίζει εάν οι δύο περιπτώσεις Hyperlink είναι ίσες.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| hlink | [IHyperlink](../../com.aspose.slides/ihyperlink) | The Hyperlink to compare with the current Hyperlink. |

**Επιστρέφει:**
boolean - **true** εάν ο καθορισμένος Hyperlink είναι ίσος με τον τρέχοντα Hyperlink· διαφορετικά, **false**.
### op_Equality(Hyperlink hlink1, Hyperlink hlink2) {#op-Equality-com.aspose.slides.Hyperlink-com.aspose.slides.Hyperlink-}
```
public static boolean op_Equality(Hyperlink hlink1, Hyperlink hlink2)
```

Δοκιμάζει δύο υπερσυνδέσμους για ισότητα.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| hlink1 | [Hyperlink](../../com.aspose.slides/hyperlink) | First hyperlink to be tested. |
| hlink2 | [Hyperlink](../../com.aspose.slides/hyperlink) | Second hyperlink to be tested. |

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
| hlink1 | [Hyperlink](../../com.aspose.slides/hyperlink) | First hyperlink to be tested. |
| hlink2 | [Hyperlink](../../com.aspose.slides/hyperlink) | Second hyperlink to be tested. |

**Επιστρέφει:**
boolean - **false** εάν οι υπερσύνδεσμοι είναι ίσοι.
### hashCode() {#hashCode--}
```
public int hashCode()
```

Λειτουργεί ως συνάρτηση κατακερματισμού για έναν συγκεκριμένο τύπο, κατάλληλη για χρήση σε αλγόριθμους κατακερματισμού και δομές δεδομένων όπως πίνακας κατακερματισμού.

**Επιστρέφει:**
int - Hash code for an URL.
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Επιστρέφει το αντικείμενο Parent_Immediate. **Μόνο για ανάγνωση** IDOMObject.

**Επιστρέφει:**
com.aspose.slides.IDOMObject