---
title: IOverridableText
second_title: Aspose.Slides για Android μέσω αναφοράς Java API
description: Αναπαριστά κείμενο που μπορεί να παρακαμφθεί για ένα γράφημα.
type: docs
url: /el/com.aspose.slides/ioverridabletext/
---
**Όλες οι Υλοποιημένες Διεπαφές:**
[com.aspose.slides.IFormattedTextContainer](../../com.aspose.slides/iformattedtextcontainer)
```
public interface IOverridableText extends IFormattedTextContainer
```

Αναπαριστά κείμενο που μπορεί να παρακαμφθεί για ένα γράφημα.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getTextFrameForOverriding()](#getTextFrameForOverriding--) | Μπορεί να περιέχει πλούσιο μορφοποιημένο κείμενο. |
| [addTextFrameForOverriding(String text)](#addTextFrameForOverriding-java.lang.String-) | Αρχικοποιεί το TextFrameForOverriding με το κείμενο στην παράμετρο "text". |
### getTextFrameForOverriding() {#getTextFrameForOverriding--}
```
public abstract ITextFrame getTextFrameForOverriding()
```

Μπορεί να περιέχει πλούσιο μορφοποιημένο κείμενο. Εάν αυτή η ιδιότητα δεν είναι null, τότε αυτή η μορφοποιημένη τιμή κειμένου παρακάμπτει το αυτόματα δημιουργημένο κείμενο. Το αυτόματα δημιουργημένο κείμενο είναι μια έμμεση ιδιότητα της ετικέτας δεδομένων, της ετικέτας μονάδας εμφάνισης του άξονα τιμών, του τίτλου άξονα, του τίτλου γραφήματος, της ετικέτας της γραμμής τάσης. Το αυτόματα δημιουργημένο κείμενο μορφοποιείται με την ιδιότητα IFormattedTextContainer.TextFormat. Μόνο για ανάγνωση [ITextFrame](../../com.aspose.slides/itextframe).

**Επιστρέφει:**
[ITextFrame](../../com.aspose.slides/itextframe)
### addTextFrameForOverriding(String text) {#addTextFrameForOverriding-java.lang.String-}
```
public abstract ITextFrame addTextFrameForOverriding(String text)
```

Αρχικοποιεί το TextFrameForOverriding με το κείμενο στην παράμετρο "text". Εάν το TextFrameForOverriding είναι ήδη αρχικοποιημένο, τότε απλώς αλλάζει το κείμενό του.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| text | java.lang.String | Κείμενο για ένα νέο TextFrameForOverriding. |

**Επιστρέφει:**
[ITextFrame](../../com.aspose.slides/itextframe) - Πλαίσιο κειμένου [ITextFrame](../../com.aspose.slides/itextframe)