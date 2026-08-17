---
title: IHyperlink
second_title: Aspose.Slides για Java API Αναφορά
description: Αναπαριστά έναν σύνδεσμο.
type: docs
url: /el/com.aspose.slides/ihyperlink/
---```
public interface IHyperlink
```

Αναπαριστά έναν σύνδεσμο.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getActionType()](#getActionType--) | Επιστρέφει τον τύπο της ενέργειας του HyperLinkEx. |
| [getExternalUrl()](#getExternalUrl--) | Καθορίζει το εξωτερικό URL. Εάν αυτή η ιδιότητα γίνει μη μηδενική, τότε η ιδιότητα TargetSlide γίνεται μηδενική. |
| [getExternalUrlOriginal()](#getExternalUrlOriginal--) | Αναπαριστά έναν σύνδεσμο που ορίζεται για αυτό το τμήμα χωρίς να λαμβάνεται υπόψη το πραγματικό περιεχόμενο του τμήματος. |
| [getTargetSlide()](#getTargetSlide--) | Αν το HyperlinkEx στοχεύει σε συγκεκριμένη διαφάνεια, επιστρέφει αυτή τη διαφάνεια. |
| [getTargetFrame()](#getTargetFrame--) | Επιστρέφει το πλαίσιο εντός του γονικού HTML frameset για τον στόχο του γονικού συνδέσμου όταν υπάρχει. |
| [setTargetFrame(String value)](#setTargetFrame-java.lang.String-) | Επιστρέφει το πλαίσιο εντός του γονικού HTML frameset για τον στόχο του γονικού συνδέσμου όταν υπάρχει. |
| [getTooltip()](#getTooltip--) | Επιστρέφει τη συμβολοσειρά που μπορεί να εμφανιστεί σε διεπαφή χρήστη ως συσχετισμένη με το γονικό σύνδεσμο. |
| [setTooltip(String value)](#setTooltip-java.lang.String-) | Επιστρέφει τη συμβολοσειρά που μπορεί να εμφανιστεί σε διεπαφή χρήστη ως συσχετισμένη με το γονικό σύνδεσμο. |
| [getHistory()](#getHistory--) | Καθορίζει εάν ο στόχος του γονικού συνδέσμου θα προστεθεί σε λίστα προβλεπόμενων συνδέσμων όταν ενεργοποιηθεί. |
| [setHistory(boolean value)](#setHistory-boolean-) | Καθορίζει εάν ο στόχος του γονικού συνδέσμου θα προστεθεί σε λίστα προβλεπόμενων συνδέσμων όταν ενεργοποιηθεί. |
| [getHighlightClick()](#getHighlightClick--) | Καθορίζει εάν ο σύνδεσμος θα επισημαίνεται κατά το κλικ. |
| [setHighlightClick(boolean value)](#setHighlightClick-boolean-) | Καθορίζει εάν ο σύνδεσμος θα επισημαίνεται κατά το κλικ. |
| [getStopSoundOnClick()](#getStopSoundOnClick--) | Καθορίζει εάν ο ήχος θα διακοπεί κατά το κλικ στον σύνδεσμο. |
| [setStopSoundOnClick(boolean value)](#setStopSoundOnClick-boolean-) | Καθορίζει εάν ο ήχος θα διακοπεί κατά το κλικ στον σύνδεσμο. |
| [getSound()](#getSound--) | Αναπαριστά τον ήχο που αναπαράγεται από το σύνδεσμο. |
| [setSound(IAudio value)](#setSound-com.aspose.slides.IAudio-) | Αναπαριστά τον ήχο που αναπαράγεται από το σύνδεσμο. |
| [getColorSource()](#getColorSource--) | Αναπαριστά την πηγή του χρώματος του συνδέσμου – είτε στυλ είτε μορφή τμήματος. |
| [setColorSource(int value)](#setColorSource-int-) | Αναπαριστά την πηγή του χρώματος του συνδέσμου – είτε στυλ είτε μορφή τμήματος. |
| [equals(IHyperlink hlink)](#equals-com.aspose.slides.IHyperlink-) | Καθορίζει αν τα δύο αντικείμενα Hyperlink είναι ίσα. |

### getActionType() {#getActionType--}
```
public abstract int getActionType()
```


Επιστρέφει τον τύπο της ενέργειας του HyperLinkEx. Μόνο για ανάγνωση [HyperlinkActionType](../../com.aspose.slides/hyperlinkactiontype).

**Επιστρέφει:**
int
### getExternalUrl() {#getExternalUrl--}
```
public abstract String getExternalUrl()
```


Καθορίζει το εξωτερικό URL. Εάν αυτή η ιδιότητα γίνει μη μηδενική, τότε η ιδιότητα TargetSlide γίνεται μηδενική. Μόνο για ανάγνωση String.

**Επιστρέφει:**
java.lang.String
### getExternalUrlOriginal() {#getExternalUrlOriginal--}
```
public abstract String getExternalUrlOriginal()
```


Αναπαριστά έναν σύνδεσμο που ορίζεται για αυτό το τμήμα χωρίς να λαμβάνεται υπόψη το πραγματικό περιεχόμενο του τμήματος.

--------------------

Το PowerPoint συμπεριφέρεται ειδικά για συνδέσμους και το αντίστοιχο κείμενό τους σε ένα τμήμα. Επιτρέπει τη δημιουργία κειμένου για τον σύνδεσμο με τη μορφή έγκυρου URL, διαφορετικού από τη πραγματική διεύθυνση του συνδέσμου. Σε αυτή την περίπτωση, όταν βλέπετε τον σύνδεσμο στο παράθυρο επεξεργασίας, θα αλλάξει για να ταιριάζει με το τμήμα κειμένου. Αυτή η ιδιότητα αναπαριστά την αρχική τιμή του συνδέσμου.

**Επιστρέφει:**
java.lang.String
### getTargetSlide() {#getTargetSlide--}
```
public abstract ISlide getTargetSlide()
```


Αν το HyperlinkEx στοχεύει σε συγκεκριμένη διαφάνεια, επιστρέφει αυτή τη διαφάνεια. Εάν η ιδιότητα γίνει μη μηδενική, τότε η ιδιότητα ExternalUrl γίνεται μηδενική. Μόνο για ανάγνωση [ISlide](../../com.aspose.slides/islide).

**Επιστρέφει:**
[ISlide](../../com.aspose.slides/islide)
### getTargetFrame() {#getTargetFrame--}
```
public abstract String getTargetFrame()
```


Επιστρέφει το πλαίσιο εντός του γονικού HTML frameset για τον στόχο του γονικού συνδέσμου όταν υπάρχει. Ανάγνωση/γραφή String.

**Επιστρέφει:**
java.lang.String
### setTargetFrame(String value) {#setTargetFrame-java.lang.String-}
```
public abstract void setTargetFrame(String value)
```


Επιστρέφει το πλαίσιο εντός του γονικού HTML frameset για τον στόχο του γονικού συνδέσμου όταν υπάρχει. Ανάγνωση/γραφή String.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | java.lang.String |  |

### getTooltip() {#getTooltip--}
```
public abstract String getTooltip()
```


Επιστρέφει τη συμβολοσειρά που μπορεί να εμφανιστεί σε διεπαφή χρήστη ως συσχετισμένη με το γονικό σύνδεσμο. Ανάγνωση/γραφή String.

**Επιστρέφει:**
java.lang.String
### setTooltip(String value) {#setTooltip-java.lang.String-}
```
public abstract void setTooltip(String value)
```


Επιστρέφει τη συμβολοσειρά που μπορεί να εμφανιστεί σε διεπαφή χρήστη ως συσχετισμένη με το γονικό σύνδεσμο. Ανάγνωση/γραφή String.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | java.lang.String |  |

### getHistory() {#getHistory--}
```
public abstract boolean getHistory()
```


Καθορίζει εάν ο στόχος του γονικού συνδέσμου θα προστεθεί σε λίστα προβλεπόμενων συνδέσμων όταν ενεργοποιηθεί. Ανάγνωση/γραφή boolean.

**Επιστρέφει:**
boolean
### setHistory(boolean value) {#setHistory-boolean-}
```
public abstract void setHistory(boolean value)
```


Καθορίζει εάν ο στόχος του γονικού συνδέσμου θα προστεθεί σε λίστα προβλεπόμενων συνδέσμων όταν ενεργοποιηθεί. Ανάγνωση/γραφή boolean.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |

### getHighlightClick() {#getHighlightClick--}
```
public abstract boolean getHighlightClick()
```


Καθορίζει εάν ο σύνδεσμος θα επισημαίνεται κατά το κλικ. Ανάγνωση/γραφή boolean.

**Επιστρέφει:**
boolean
### setHighlightClick(boolean value) {#setHighlightClick-boolean-}
```
public abstract void setHighlightClick(boolean value)
```


Καθορίζει εάν ο σύνδεσμος θα επισημαίνεται κατά το κλικ. Ανάγνωση/γραφή boolean.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |

### getStopSoundOnClick() {#getStopSoundOnClick--}
```
public abstract boolean getStopSoundOnClick()
```


Καθορίζει εάν ο ήχος θα διακοπεί κατά το κλικ στον σύνδεσμο. Ανάγνωση/γραφή boolean.

**Επιστρέφει:**
boolean
### setStopSoundOnClick(boolean value) {#setStopSoundOnClick-boolean-}
```
public abstract void setStopSoundOnClick(boolean value)
```


Καθορίζει εάν ο ήχος θα διακοπεί κατά το κλικ στον σύνδεσμο. Ανάγνωση/γραφή boolean.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |

### getSound() {#getSound--}
```
public abstract IAudio getSound()
```


Αναπαριστά τον ήχο που αναπαράγεται από το σύνδεσμο. Ανάγνωση/γραφή [IAudio](../../com.aspose.slides/iaudio).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
> 
>      // Λάβετε τον πρώτο σύνδεσμο σχήματος
>      IHyperlink link = presentation.getSlides().get_Item(0).getShapes().get_Item(0).getHyperlinkClick();
> 
>      if (link.getSound() != null)
>      {
>          // Εξάγετε τον ήχο του συνδέσμου σε πίνακα byte
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
public abstract void setSound(IAudio value)
```


Αναπαριστά τον ήχο που αναπαράγεται από το σύνδεσμο. Ανάγνωση/γραφή [IAudio](../../com.aspose.slides/iaudio).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
> 
>      // Λάβετε τον πρώτο σύνδεσμο σχήματος
>      IHyperlink link = presentation.getSlides().get_Item(0).getShapes().get_Item(0).getHyperlinkClick();
> 
>      if (link.getSound() != null)
>      {
>          // Εξάγετε τον ήχο του συνδέσμου σε πίνακα byte
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
public abstract int getColorSource()
```


Αναπαριστά την πηγή του χρώματος του συνδέσμου – είτε στυλ είτε μορφή τμήματος. Ανάγνωση/γραφή [HyperlinkColorSource](../../com.aspose.slides/hyperlinkcolorsource).

**Επιστρέφει:**
int
### setColorSource(int value) {#setColorSource-int-}
```
public abstract void setColorSource(int value)
```


Αναπαριστά την πηγή του χρώματος του συνδέσμου – είτε στυλ είτε μορφή τμήματος. Ανάγνωση/γραφή [HyperlinkColorSource](../../com.aspose.slides/hyperlinkcolorsource).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | int |  |

### equals(IHyperlink hlink) {#equals-com.aspose.slides.IHyperlink-}
```
public abstract boolean equals(IHyperlink hlink)
```


Καθορίζει αν τα δύο αντικείμενα Hyperlink είναι ίσα.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| hlink | [IHyperlink](../../com.aspose.slides/ihyperlink) | Ο Hyperlink για σύγκριση με τον τρέχον Hyperlink. |

**Επιστρέφει:**
boolean - **true** εάν ο συγκεκριμένος Hyperlink είναι ίσος με τον τρέχον Hyperlink· διαφορετικά, **false**.