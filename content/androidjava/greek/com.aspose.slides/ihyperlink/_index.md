---
title: IHyperlink
second_title: Aspose.Slides for Android via Java API Reference
description: Represents a hyperlink.
type: docs
url: /el/com.aspose.slides/ihyperlink/
---```
public interface IHyperlink
```

Αναπαριστά έναν υπερσύνδεσμο.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getActionType()](#getActionType--) | Επιστρέφει τον τύπο της ενέργειας του HyperLinkEx. |
| [getExternalUrl()](#getExternalUrl--) | Καθορίζει το εξωτερικό URL. Εάν αυτή η ιδιότητα γίνει μη μηδενική, τότε η ιδιότητα TargetSlide γίνεται μηδενική. |
| [getExternalUrlOriginal()](#getExternalUrlOriginal--) | Αναπαριστά έναν υπερσύνδεσμο που έχει οριστεί για αυτό το τμήμα χωρίς να λαμβάνεται υπόψη το πραγματικό περιεχόμενο του τμήματος. |
| [getTargetSlide()](#getTargetSlide--) | Εάν το HyperlinkEx στοχεύει σε συγκεκριμένη διαφάνεια, επιστρέφει αυτή τη διαφάνεια. |
| [getTargetFrame()](#getTargetFrame--) | Επιστρέφει το πλαίσιο μέσα στο γονικό σύνολο πλαισίων HTML για τον προορισμό του γονικού υπερσυνδέσμου, όταν υπάρχει. |
| [setTargetFrame(String value)](#setTargetFrame-java.lang.String-) | Επιστρέφει το πλαίσιο μέσα στο γονικό σύνολο πλαισίων HTML για τον προορισμό του γονικού υπερσυνδέσμου, όταν υπάρχει. |
| [getTooltip()](#getTooltip--) | Επιστρέφει τη συμβολοσειρά που μπορεί να εμφανιστεί σε διεπαφή χρήστη ως συσχετισμένη με το γονικό υπερσύνδεσμο. |
| [setTooltip(String value)](#setTooltip-java.lang.String-) | Επιστρέφει τη συμβολοσειρά που μπορεί να εμφανιστεί σε διεπαφή χρήστη ως συσχετισμένη με το γονικό υπερσύνδεσμο. |
| [getHistory()](#getHistory--) | Καθορίζει εάν ο προορισμός του γονικού υπερσυνδέσμου θα προστεθεί σε λίστα προβεβλημένων υπερσυνδέσμων όταν ενεργοποιηθεί. |
| [setHistory(boolean value)](#setHistory-boolean-) | Καθορίζει εάν ο προορισμός του γονικού υπερσυνδέσμου θα προστεθεί σε λίστα προβεβλημένων υπερσυνδέσμων όταν ενεργοποιηθεί. |
| [getHighlightClick()](#getHighlightClick--) | Καθορίζει εάν ο υπερσύνδεσμος πρέπει να επισημαίνεται κατά το κλικ. |
| [setHighlightClick(boolean value)](#setHighlightClick-boolean-) | Καθορίζει εάν ο υπερσύνδεσμος πρέπει να επισημαίνεται κατά το κλικ. |
| [getStopSoundOnClick()](#getStopSoundOnClick--) | Καθορίζει εάν ο ήχος πρέπει να σταματήσει κατά το κλικ στον υπερσύνδεσμο. |
| [setStopSoundOnClick(boolean value)](#setStopSoundOnClick-boolean-) | Καθορίζει εάν ο ήχος πρέπει να σταματήσει κατά το κλικ στον υπερσύνδεσμο. |
| [getSound()](#getSound--) | Αναπαριστά τον αναπαραγόμενο ήχο του υπερσυνδέσμου. |
| [setSound(IAudio value)](#setSound-com.aspose.slides.IAudio-) | Αναπαριστά τον αναπαραγόμενο ήχο του υπερσυνδέσμου. |
| [getColorSource()](#getColorSource--) | Αναπαριστά την πηγή του χρώματος του υπερσυνδέσμου — είτε στυλ είτε μορφοποίηση τμήματος. |
| [setColorSource(int value)](#setColorSource-int-) | Αναπαριστά την πηγή του χρώματος του υπερσυνδέσμου — είτε στυλ είτε μορφοποίηση τμήματος. |
| [equals(IHyperlink hlink)](#equals-com.aspose.slides.IHyperlink-) | Καθορίζει εάν οι δύο αντικείμενα Hyperlink είναι ισοδύναμα. |

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

Αναπαριστά έναν υπερσύνδεσμο που έχει οριστεί για αυτό το τμήμα χωρίς να λαμβάνεται υπόψη το πραγματικό περιεχόμενο του τμήματος.

--------------------

PowerPoint συμπεριφέρεται ειδικά για συνδέσμους και το αντίστοιχο κείμενό τους σε ένα τμήμα. Επιτρέπει τη δημιουργία κειμένου για τον υπερσύνδεσμο με τη μορφή έγκυρου URL, διαφορετικού από τη πραγματική διεύθυνση του συνδέσμου. Σε αυτή την περίπτωση, όταν προβάλετε το σύνδεσμο στο παράθυρο επεξεργασίας, θα αλλάξει ώστε να ταιριάζει με το κείμενο του τμήματος. Αυτή η ιδιότητα αντιπροσωπεύει την αρχική τιμή του υπερσυνδέσμου.

**Επιστρέφει:**
java.lang.String

### getTargetSlide() {#getTargetSlide--}
```
public abstract ISlide getTargetSlide()
```

Εάν το HyperlinkEx στοχεύει σε συγκεκριμένη διαφάνεια, επιστρέφει αυτή τη διαφάνεια. Εάν η ιδιότητα γίνει μη μηδενική, τότε η ιδιότητα ExternalUrl γίνεται μηδενική. Μόνο για ανάγνωση [ISlide](../../com.aspose.slides/islide).

**Επιστρέφει:**
[ISlide](../../com.aspose.slides/islide)

### getTargetFrame() {#getTargetFrame--}
```
public abstract String getTargetFrame()
```

Επιστρέφει το πλαίσιο μέσα στο γονικό σύνολο πλαισίων HTML για τον προορισμό του γονικού υπερσυνδέσμου, όταν υπάρχει. Ανάγνωση/εγγραφή String.

**Επιστρέφει:**
java.lang.String

### setTargetFrame(String value) {#setTargetFrame-java.lang.String-}
```
public abstract void setTargetFrame(String value)
```

Επιστρέφει το πλαίσιο μέσα στο γονικό σύνολο πλαισίων HTML για τον προορισμό του γονικού υπερσυνδέσμου, όταν υπάρχει. Ανάγνωση/εγγραφή String.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | java.lang.String |  |

### getTooltip() {#getTooltip--}
```
public abstract String getTooltip()
```

Επιστρέφει τη συμβολοσειρά που μπορεί να εμφανιστεί σε διεπαφή χρήστη ως συσχετισμένη με το γονικό υπερσύνδεσμο. Ανάγνωση/εγγραφή String.

**Επιστρέφει:**
java.lang.String

### setTooltip(String value) {#setTooltip-java.lang.String-}
```
public abstract void setTooltip(String value)
```

Επιστρέφει τη συμβολοσειρά που μπορεί να εμφανιστεί σε διεπαφή χρήστη ως συσχετισμένη με το γονικό υπερσύνδεσμο. Ανάγνωση/εγγραφή String.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | java.lang.String |  |

### getHistory() {#getHistory--}
```
public abstract boolean getHistory()
```

Καθορίζει εάν ο προορισμός του γονικού υπερσυνδέσμου θα προστεθεί σε λίστα προβεβλημένων υπερσυνδέσμων όταν ενεργοποιηθεί. Ανάγνωση/εγγραφή boolean.

**Επιστρέφει:**
boolean

### setHistory(boolean value) {#setHistory-boolean-}
```
public abstract void setHistory(boolean value)
```

Καθορίζει εάν ο προορισμός του γονικού υπερσυνδέσμου θα προστεθεί σε λίστα προβεβλημένων υπερσυνδέσμων όταν ενεργοποιηθεί. Ανάγνωση/εγγραφή boolean.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |

### getHighlightClick() {#getHighlightClick--}
```
public abstract boolean getHighlightClick()
```

Καθορίζει εάν ο υπερσύνδεσμος πρέπει να επισημαίνεται κατά το κλικ. Ανάγνωση/εγγραφή boolean.

**Επιστρέφει:**
boolean

### setHighlightClick(boolean value) {#setHighlightClick-boolean-}
```
public abstract void setHighlightClick(boolean value)
```

Καθορίζει εάν ο υπερσύνδεσμος πρέπει να επισημαίνεται κατά το κλικ. Ανάγνωση/εγγραφή boolean.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |

### getStopSoundOnClick() {#getStopSoundOnClick--}
```
public abstract boolean getStopSoundOnClick()
```

Καθορίζει εάν ο ήχος πρέπει να σταματήσει κατά το κλικ στον υπερσύνδεσμο. Ανάγνωση/εγγραφή boolean.

**Επιστρέφει:**
boolean

### setStopSoundOnClick(boolean value) {#setStopSoundOnClick-boolean-}
```
public abstract void setStopSoundOnClick(boolean value)
```

Καθορίζει εάν ο ήχος πρέπει να σταματήσει κατά το κλικ στον υπερσύνδεσμο. Ανάγνωση/εγγραφή boolean.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |

### getSound() {#getSound--}
```
public abstract IAudio getSound()
```

Αναπαριστά τον αναπαραγόμενο ήχο του υπερσυνδέσμου. Ανάγνωση/εγγραφή [IAudio](../../com.aspose.slides/iaudio).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
> 
>      // Λάβετε το πρώτο υπερσύνδεσμο σχήματος
>      IHyperlink link = presentation.getSlides().get_Item(0).getShapes().get_Item(0).getHyperlinkClick();
> 
>      if (link.getSound() != null)
>      {
>          // Εξαγωγή του ήχου του υπερσυνδέσμου σε πίνακα byte
>          byte[] audioData = link.getSound().getBinaryData();
>      }
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
```

**Επιστρέφει:**
[IAudio](../../com.aspose.slides/iaudio)

### setSound(IAudio value) {#setSound-com.aspose.slides.IAudio-}
```
public abstract void setSound(IAudio value)
```

Αναπαριστά τον αναπαραγόμενο ήχο του υπερσυνδέσμου. Ανάγνωση/εγγραφή [IAudio](../../com.aspose.slides/iaudio).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
> 
>      // Λάβετε το πρώτο υπερσύνδεσμο σχήματος
>      IHyperlink link = presentation.getSlides().get_Item(0).getShapes().get_Item(0).getHyperlinkClick();
> 
>      if (link.getSound() != null)
>      {
>          // Εξαγωγή του ήχου του υπερσυνδέσμου σε πίνακα byte
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

Αναπαριστά την πηγή του χρώματος του υπερσυνδέσμου — είτε στυλ είτε μορφοποίηση τμήματος. Ανάγνωση/εγγραφή [HyperlinkColorSource](../../com.aspose.slides/hyperlinkcolorsource).

**Επιστρέφει:**
int

### setColorSource(int value) {#setColorSource-int-}
```
public abstract void setColorSource(int value)
```

Αναπαριστά την πηγή του χρώματος του υπερσυνδέσμου — είτε στυλ είτε μορφοποίηση τμήματος. Ανάγνωση/εγγραφή [HyperlinkColorSource](../../com.aspose.slides/hyperlinkcolorsource).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | int |  |

### equals(IHyperlink hlink) {#equals-com.aspose.slides.IHyperlink-}
```
public abstract boolean equals(IHyperlink hlink)
```

Καθορίζει εάν οι δύο αντικείμενα Hyperlink είναι ισοδύναμα.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| hlink | [IHyperlink](../../com.aspose.slides/ihyperlink) | Ο Hyperlink προς σύγκριση με τον τρέχον Hyperlink. |

**Επιστρέφει:**
boolean - **true** εάν ο συγκεκριμένος Hyperlink είναι ίσος με τον τρέχον Hyperlink· διαφορετικά, **false**.