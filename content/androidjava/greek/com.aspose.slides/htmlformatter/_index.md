---
title: HtmlFormatter
second_title: Aspose.Slides για Android μέσω Αναφοράς API Java
description: Αντιπροσωπεύει το πρότυπο αρχείου HTML.
type: docs
url: /el/com.aspose.slides/htmlformatter/
---
**Κληρονομικότητα:**
java.lang.Object

**Όλες οι υλοποιημένες διεπαφές:**
[com.aspose.slides.IHtmlFormatter](../../com.aspose.slides/ihtmlformatter)
```
public final class HtmlFormatter implements IHtmlFormatter
```

Αντιπροσωπεύει το πρότυπο αρχείου HTML.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [createDocumentFormatter(String css, boolean showSlideTitle)](#createDocumentFormatter-java.lang.String-boolean-) | Δημιουργεί και επιστρέφει διαμορφωτή HTML για μια απλή προβολή εγγράφου που αποτελείται από ακολουθίες διαφανειών η μία κάτω από την άλλη. |
| [createSlideShowFormatter(String css, boolean showSlideTitle)](#createSlideShowFormatter-java.lang.String-boolean-) | Δημιουργεί και επιστρέφει διαμορφωτή HTML για μια απλή παρουσίαση διαφανειών που εμφανίζει τις διαφάνειες η μία μετά την άλλη. |
| [createCustomFormatter(IHtmlFormattingController formattingController)](#createCustomFormatter-com.aspose.slides.IHtmlFormattingController-) | Δημιουργεί και επιστρέφει διαμορφωτή HTML για προσαρμοσμένη δημιουργία HTML που βασίζεται σε κλήσεις ανάκλησης. |
### createDocumentFormatter(String css, boolean showSlideTitle) {#createDocumentFormatter-java.lang.String-boolean-}
```
public static HtmlFormatter createDocumentFormatter(String css, boolean showSlideTitle)
```


Δημιουργεί και επιστρέφει διαμορφωτή HTML για μια απλή προβολή εγγράφου που αποτελείται από ακολουθίες διαφανειών η μία κάτω από την άλλη.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| css | java.lang.String | Καθορίζει CSS για αυτό το αρχείο. |
| showSlideTitle | boolean | Προσθέτει τίτλο διαφάνειας εάν υπάρχει πάνω από την εικόνα της διαφάνειας. |

**Επιστρέφει:**
[HtmlFormatter](../../com.aspose.slides/htmlformatter) - Το [HtmlFormatter](../../com.aspose.slides/htmlformatter) αντικείμενο.
### createSlideShowFormatter(String css, boolean showSlideTitle) {#createSlideShowFormatter-java.lang.String-boolean-}
```
public static HtmlFormatter createSlideShowFormatter(String css, boolean showSlideTitle)
```


Δημιουργεί και επιστρέφει διαμορφωτή HTML για μια απλή παρουσίαση διαφανειών που εμφανίζει τις διαφάνειες η μία μετά την άλλη.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| css | java.lang.String | Καθορίζει URL του αρχείου CSS που χρησιμοποιείται. |
| showSlideTitle | boolean | Προσθέτει τίτλο διαφάνειας εάν υπάρχει πάνω από την εικόνα της διαφάνειας. |

**Επιστρέφει:**
[HtmlFormatter](../../com.aspose.slides/htmlformatter) - Το [HtmlFormatter](../../com.aspose.slides/htmlformatter) αντικείμενο.
### createCustomFormatter(IHtmlFormattingController formattingController) {#createCustomFormatter-com.aspose.slides.IHtmlFormattingController-}
```
public static HtmlFormatter createCustomFormatter(IHtmlFormattingController formattingController)
```


Δημιουργεί και επιστρέφει διαμορφωτή HTML για προσαρμοσμένη δημιουργία HTML που βασίζεται σε κλήσεις ανάκλησης.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| formattingController | [IHtmlFormattingController](../../com.aspose.slides/ihtmlformattingcontroller) | Διεπαφή κλήσης ανάκλησης η οποία ελέγχει τη δημιουργία του αρχείου HTML. |

**Επιστρέφει:**
[HtmlFormatter](../../com.aspose.slides/htmlformatter) - Το [HtmlFormatter](../../com.aspose.slides/htmlformatter) αντικείμενο.