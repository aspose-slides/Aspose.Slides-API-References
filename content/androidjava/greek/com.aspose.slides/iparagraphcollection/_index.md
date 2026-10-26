---
title: IParagraphCollection
second_title: Aspose.Slides για Android μέσω Αναφοράς API Java
description: Αντιπροσωπεύει μια συλλογή παραγράφων.
type: docs
url: /el/com.aspose.slides/iparagraphcollection/
---
**All Implemented Interfaces:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable, [com.aspose.slides.ISlideComponent](../../com.aspose.slides/islidecomponent)
```
public interface IParagraphCollection extends System.Collections.Generic.IGenericEnumerable<IParagraph>, ISlideComponent
```

Αντιπροσωπεύει μια συλλογή παραγράφων.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Λαμβάνει το στοιχείο στο καθορισμένο δείκτη. |
| [getCount()](#getCount--) | Λαμβάνει τον αριθμό των στοιχείων που πραγματικά περιέχονται στη συλλογή. |
| [add(IParagraph value)](#add-com.aspose.slides.IParagraph-) | Προσθέτει ένα Paragraph στο τέλος της συλλογής. |
| [add(IParagraphCollection value)](#add-com.aspose.slides.IParagraphCollection-) | Προσθέτει το περιεχόμενο του ParagraphCollection στο τέλος της συλλογής. |
| [insert(int index, IParagraph value)](#insert-int-com.aspose.slides.IParagraph-) | Εισάγει ένα Paragraph στη συλλογή στο καθορισμένο δείκτη. |
| [insert(int index, IParagraphCollection value)](#insert-int-com.aspose.slides.IParagraphCollection-) | Εισάγει το περιεχόμενο του ParagraphCollection στη συλλογή στο καθορισμένο δείκτη. |
| [clear()](#clear--) | Αφαιρεί όλα τα στοιχεία από τη συλλογή. |
| [removeAt(int index)](#removeAt-int-) | Αφαιρεί το στοιχείο στο καθορισμένο δείκτη της συλλογής. |
| [remove(IParagraph item)](#remove-com.aspose.slides.IParagraph-) | Αφαιρεί την πρώτη εμφάνιση μιας συγκεκριμένης παραγράφου. |
| [addFromHtml(String text)](#addFromHtml-java.lang.String-) | Προσθέτει κείμενο από το καθορισμένο html string στη συλλογή. |
| [addFromHtml(String text, IExternalResourceResolver resolver, String uri)](#addFromHtml-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-) | Προσθέτει κείμενο από το καθορισμένο html string στη συλλογή. |
| [exportToHtml(int firstParagraphIndex, int paragraphsCount, ITextToHtmlConversionOptions options)](#exportToHtml-int-int-com.aspose.slides.ITextToHtmlConversionOptions-) | Μετατρέπει τις καθορισμένες παραγράφους σε HTML και το επιστρέφει ως αντικείμενο String. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IParagraph get_Item(int index)
```


Λαμβάνει το στοιχείο στο καθορισμένο δείκτη.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int |  |

**Επιστρέφει:**
[IParagraph](../../com.aspose.slides/iparagraph)
### getCount() {#getCount--}
```
public abstract int getCount()
```


Λαμβάνει τον αριθμό των στοιχείων που πραγματικά περιέχονται στη συλλογή. Μόνο για ανάγνωση int.

**Επιστρέφει:**
int
### add(IParagraph value) {#add-com.aspose.slides.IParagraph-}
```
public abstract void add(IParagraph value)
```


Προσθέτει ένα Paragraph στο τέλος της συλλογής.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [IParagraph](../../com.aspose.slides/iparagraph) | Το Paragraph που θα προστεθεί στο τέλος της συλλογής. |

### add(IParagraphCollection value) {#add-com.aspose.slides.IParagraphCollection-}
```
public abstract int add(IParagraphCollection value)
```


Προσθέτει το περιεχόμενο του ParagraphCollection στο τέλος της συλλογής.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [IParagraphCollection](../../com.aspose.slides/iparagraphcollection) | Το ParagraphCollection που θα προστεθεί στο τέλος της συλλογής. |

**Επιστρέφει:**
int - Ο δείκτης στον οποίο προστέθηκε το Paragraph ή -1 αν δεν υπάρχει τίποτα προς προσθήκη.
### insert(int index, IParagraph value) {#insert-int-com.aspose.slides.IParagraph-}
```
public abstract void insert(int index, IParagraph value)
```


Εισάγει ένα Paragraph στη συλλογή στο καθορισμένο δείκτη.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int | Ο μηδενικός δείκτης στον οποίο θα εισαχθεί το Paragraph. |
| value | [IParagraph](../../com.aspose.slides/iparagraph) | Το Paragraph προς εισαγωγή. |

### insert(int index, IParagraphCollection value) {#insert-int-com.aspose.slides.IParagraphCollection-}
```
public abstract void insert(int index, IParagraphCollection value)
```


Εισάγει το περιεχόμενο του ParagraphCollection στη συλλογή στο καθορισμένο δείκτη.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int | Ο μηδενικός δείκτης στον οποίο θα εισαχθούν οι παράγραφοι. |
| value | [IParagraphCollection](../../com.aspose.slides/iparagraphcollection) | Οι παράγραφοι προς εισαγωγή. |

### clear() {#clear--}
```
public abstract void clear()
```


Αφαιρεί όλα τα στοιχεία από τη συλλογή.

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```


Αφαιρεί το στοιχείο στο καθορισμένο δείκτη της συλλογής.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int | Ο μηδενικός δείκτης του στοιχείου που θα αφαιρεθεί. |

### remove(IParagraph item) {#remove-com.aspose.slides.IParagraph-}
```
public abstract boolean remove(IParagraph item)
```


Αφαιρεί την πρώτη εμφάνιση μιας συγκεκριμένης παραγράφου.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| item | [IParagraph](../../com.aspose.slides/iparagraph) | Η παράγραφος που θα αφαιρεθεί από τη συλλογή. |

**Επιστρέφει:**
boolean - true αν το αντικείμενο αφαιρέθηκε επιτυχώς· διαφορετικά, false.
### addFromHtml(String text) {#addFromHtml-java.lang.String-}
```
public abstract void addFromHtml(String text)
```


Προσθέτει κείμενο από το καθορισμένο html string στη συλλογή.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| text | java.lang.String | Κείμενο HTML. |

### addFromHtml(String text, IExternalResourceResolver resolver, String uri) {#addFromHtml-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-}
```
public abstract void addFromHtml(String text, IExternalResourceResolver resolver, String uri)
```


Προσθέτει κείμενο από το καθορισμένο html string στη συλλογή.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| text | java.lang.String | Κείμενο HTML. |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | Αντικείμενο callback Resolver που επιλύει URI και ανακτά τα αναφερθέντα αντικείμενα. |
| uri | java.lang.String | URI για την προσθήκη του εγγράφου HTML. Χρησιμοποιείται για την επίλυση σχετικών συνδέσμων.

--------------------

Η χρήση resolver μπορεί δυνητικά να εισαγάγει ευπάθεια. Χρησιμοποιήστε με προσοχή. |
### exportToHtml(int firstParagraphIndex, int paragraphsCount, ITextToHtmlConversionOptions options) {#exportToHtml-int-int-com.aspose.slides.ITextToHtmlConversionOptions-}
```
public abstract String exportToHtml(int firstParagraphIndex, int paragraphsCount, ITextToHtmlConversionOptions options)
```


Μετατρέπει τις καθορισμένες παραγράφους σε HTML και το επιστρέφει ως αντικείμενο String.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| firstParagraphIndex | int | Δείκτης πρώτης παραγράφου int |
| paragraphsCount | int | Αριθμός παραγράφων int |
| options | [ITextToHtmlConversionOptions](../../com.aspose.slides/itexttohtmlconversionoptions) | Επιλογές μετατροπής [ITextToHtmlConversionOptions](../../com.aspose.slides/itexttohtmlconversionoptions) |

**Επιστρέφει:**
java.lang.String - Δημιουργημένο HTML.