---
title: HtmlFormatter
second_title: Aspose.Slides για την Αναφορά API της Java
description: Αναπαριστά πρότυπο αρχείου HTML.
type: docs
url: /el/com.aspose.slides/htmlformatter/
---
**Κληρονομικότητα:**
java.lang.Object

**Όλες οι Υλοποιημένες Διεπαφές:**
[com.aspose.slides.IHtmlFormatter](../../com.aspose.slides/ihtmlformatter)
```
public final class HtmlFormatter implements IHtmlFormatter
```

Αναπαριστά το πρότυπο αρχείου HTML.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [createDocumentFormatter(String css, boolean showSlideTitle)](#createDocumentFormatter-java.lang.String-boolean-) | Creates and returns HTML formatter for a simple document view which consists of sequences of slides one below another. |
| [createSlideShowFormatter(String css, boolean showSlideTitle)](#createSlideShowFormatter-java.lang.String-boolean-) | Creates and returns HTML formatter for a simple slide show html which shows slides one after another. |
| [createCustomFormatter(IHtmlFormattingController formattingController)](#createCustomFormatter-com.aspose.slides.IHtmlFormattingController-) | Creates and returns HTML formatter for custom callback-driven html generation. |
### createDocumentFormatter(String css, boolean showSlideTitle) {#createDocumentFormatter-java.lang.String-boolean-}
```
public static HtmlFormatter createDocumentFormatter(String css, boolean showSlideTitle)
```


Δημιουργεί και επιστρέφει έναν HTML formatter για μια απλή προβολή εγγράφου που αποτελείται από ακολουθίες διαφανειών η μία κάτω από την άλλη.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| css | java.lang.String | Καθορίζει το CSS για αυτό το αρχείο. |
| showSlideTitle | boolean | Προσθέτει τον τίτλο της διαφάνειας εάν υπάρχει πάνω από την εικόνα της διαφάνειας. |

**Επιστρέφει:**
[HtmlFormatter](../../com.aspose.slides/htmlformatter) - Το αντικείμενο [HtmlFormatter](../../com.aspose.slides/htmlformatter).

### createSlideShowFormatter(String css, boolean showSlideTitle) {#createSlideShowFormatter-java.lang.String-boolean-}
```
public static HtmlFormatter createSlideShowFormatter(String css, boolean showSlideTitle)
```


Δημιουργεί και επιστρέφει έναν HTML formatter για ένα απλό slide show html που εμφανίζει τις διαφάνειες η μία μετά την άλλη.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| css | java.lang.String | Καθορίζει το URL του αρχείου CCS που χρησιμοποιείται. |
| showSlideTitle | boolean | Προσθέτει τον τίτλο της διαφάνειας εάν υπάρχει πάνω από την εικόνα της διαφάνειας. |

**Επιστρέφει:**
[HtmlFormatter](../../com.aspose.slides/htmlformatter) - Το αντικείμενο [HtmlFormatter](../../com.aspose.slides/htmlformatter).

### createCustomFormatter(IHtmlFormattingController formattingController) {#createCustomFormatter-com.aspose.slides.IHtmlFormattingController-}
```
public static HtmlFormatter createCustomFormatter(IHtmlFormattingController formattingController)
```


Δημιουργεί και επιστρέφει έναν HTML formatter για προσαρμοσμένη δημιουργία html βάσει κλήσεων επανάκλησης.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| formattingController | [IHtmlFormattingController](../../com.aspose.slides/ihtmlformattingcontroller) | Διεπαφή κλήσης επανάκλησης που ελέγχει τη δημιουργία του αρχείου html. |

**Επιστρέφει:**
[HtmlFormatter](../../com.aspose.slides/htmlformatter) - Το αντικείμενο [HtmlFormatter](../../com.aspose.slides/htmlformatter).