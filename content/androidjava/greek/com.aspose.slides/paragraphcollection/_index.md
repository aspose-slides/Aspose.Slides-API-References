---
title: ParagraphCollection
second_title: Aspose.Slides για Android μέσω αναφοράς API Java
description: Αντιπροσωπεύει μια συλλογή παραγράφων.
type: docs
url: /el/com.aspose.slides/paragraphcollection/
---
**Κληρονομικότητα:**
java.lang.Object, com.aspose.slides.DomObject

**Όλες οι Υλοποιημένες Διεπαφές:**
[com.aspose.slides.IParagraphCollection](../../com.aspose.slides/iparagraphcollection)
```
public final class ParagraphCollection extends DomObject<TextFrame> implements IParagraphCollection
```

Represents a collection of a paragraphs.
## Methods

| Method | Description |
| --- | --- |
| [getCount()](#getCount--) | Λαμβάνει τον αριθμό των στοιχείων που περιέχονται πραγματικά στη συλλογή. |
| [isReadOnly()](#isReadOnly--) | Λαμβάνει μια τιμή που υποδεικνύει αν το [IGenericCollection](../../com.aspose.slides/igenericcollection) είναι μόνο για ανάγνωση. |
| [get_Item(int index)](#get-Item-int-) | Λαμβάνει το στοιχείο στον καθορισμένο δείκτη. |
| [add(IParagraph value)](#add-com.aspose.slides.IParagraph-) | Προσθέτει ένα Paragraph στο τέλος της συλλογής. |
| [add(IParagraphCollection value)](#add-com.aspose.slides.IParagraphCollection-) | Προσθέτει ένα περιεχόμενο του ParagraphCollection στο τέλος της συλλογής. |
| [indexOf(IParagraph item)](#indexOf-com.aspose.slides.IParagraph-) | Καθορίζει τον δείκτη ενός συγκεκριμένου στοιχείου στη List. |
| [insert(int index, IParagraph value)](#insert-int-com.aspose.slides.IParagraph-) | Εισάγει ένα Paragraph στη συλλογή στον καθορισμένο δείκτη. |
| [insert(int index, IParagraphCollection value)](#insert-int-com.aspose.slides.IParagraphCollection-) | Εισάγει ένα περιεχόμενο του ParagraphCollection στη συλλογή στον καθορισμένο δείκτη. |
| [clear()](#clear--) | Αφαιρεί όλα τα στοιχεία από τη συλλογή. |
| [contains(IParagraph item)](#contains-com.aspose.slides.IParagraph-) | Καθορίζει εάν το [IGenericCollection](../../com.aspose.slides/igenericcollection) περιέχει μια συγκεκριμένη τιμή. |
| [copyTo(IParagraph[] array, int arrayIndex)](#copyTo-com.aspose.slides.IParagraph---int-) | Αντιγράφει τα στοιχεία του [IGenericCollection](../../com.aspose.slides/igenericcollection) σε έναν Array, ξεκινώντας από έναν συγκεκριμένο δείκτη Array. |
| [removeAt(int index)](#removeAt-int-) | Αφαιρεί το στοιχείο στον καθορισμένο δείκτη της συλλογής. |
| [remove(IParagraph item)](#remove-com.aspose.slides.IParagraph-) | Αφαιρεί την πρώτη εμφάνιση ενός συγκεκριμένου αντικειμένου από το [IGenericCollection](../../com.aspose.slides/igenericcollection). |
| [iterator()](#iterator--) | Επιστρέφει έναν enumerator που διατρέχει τη συλλογή. |
| [iteratorJava()](#iteratorJava--) | Επιστρέφει έναν java iterator για ολόκληρη τη συλλογή. |
| [getSlide()](#getSlide--) | Επιστρέφει τη γονική διαφάνεια μιας συλλογής παραγράφων. |
| [getPresentation()](#getPresentation--) | Επιστρέφει την γονική παρουσίαση μιας συλλογής παραγράφων. |
| [addFromHtml(String text)](#addFromHtml-java.lang.String-) | Προσθέτει κείμενο από το καθορισμένο html string στη συλλογή. |
| [addFromHtml(String text, IExternalResourceResolver resolver, String uri)](#addFromHtml-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-) | Προσθέτει κείμενο από το καθορισμένο html string στη συλλογή. |
| [exportToHtml(int firstParagraphIndex, int paragraphsCount, ITextToHtmlConversionOptions options)](#exportToHtml-int-int-com.aspose.slides.ITextToHtmlConversionOptions-) | Μετατρέπει τις καθορισμένες παραγράφους σε HTML και το επιστρέφει ως αντικείμενο String. |

### getCount() {#getCount--}
```
public final int getCount()
```

Λαμβάνει τον αριθμό των στοιχείων που περιέχονται πραγματικά στη συλλογή. Μόνο για ανάγνωση int.

**Επιστρέφει:**
int

### isReadOnly() {#isReadOnly--}
```
public final boolean isReadOnly()
```

Λαμβάνει μια τιμή που υποδεικνύει αν το [IGenericCollection](../../com.aspose.slides/igenericcollection) είναι μόνο για ανάγνωση. Μόνο για ανάγνωση boolean.

**Επιστρέφει:**
boolean - true εάν το [IGenericCollection](../../com.aspose.slides/igenericcollection) είναι μόνο για ανάγνωση· διαφορετικά, false.

### get_Item(int index) {#get-Item-int-}
```
public final IParagraph get_Item(int index)
```

Λαμβάνει το στοιχείο στον καθορισμένο δείκτη.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int |  |

**Επιστρέφει:**
[IParagraph](../../com.aspose.slides/iparagraph)

### add(IParagraph value) {#add-com.aspose.slides.IParagraph-}
```
public final void add(IParagraph value)
```

Προσθέτει ένα Paragraph στο τέλος της συλλογής.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [IParagraph](../../com.aspose.slides/iparagraph) | Το Paragraph που θα προστεθεί στο τέλος της συλλογής. |

### add(IParagraphCollection value) {#add-com.aspose.slides.IParagraphCollection-}
```
public final int add(IParagraphCollection value)
```

Προσθέτει ένα περιεχόμενο του ParagraphCollection στο τέλος της συλλογής.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [IParagraphCollection](../../com.aspose.slides/iparagraphcollection) | Το ParagraphCollection που θα προστεθεί στο τέλος της συλλογής. |

**Επιστρέφει:**
int - Ο δείκτης στον οποίο προστέθηκε το Paragraph ή -1 αν δεν υπάρχει τίποτα προς προσθήκη.

### indexOf(IParagraph item) {#indexOf-com.aspose.slides.IParagraph-}
```
public final int indexOf(IParagraph item)
```

Καθορίζει τον δείκτη ενός συγκεκριμένου στοιχείου στη List.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| item | [IParagraph](../../com.aspose.slides/iparagraph) | Το αντικείμενο που πρέπει να εντοπιστεί στη List. |

**Επιστρέφει:**
int - Ο δείκτης του στοιχείου αν βρεθεί στη λίστα· διαφορετικά, -1.

### insert(int index, IParagraph value) {#insert-int-com.aspose.slides.IParagraph-}
```
public final void insert(int index, IParagraph value)
```

Εισάγει ένα Paragraph στη συλλογή στον καθορισμένο δείκτη.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int | Ο δείκτης που αρχίζει από το 0, στον οποίο θα εισαχθεί το Paragraph. |
| value | [IParagraph](../../com.aspose.slides/iparagraph) | Το Paragraph προς εισαγωγή. |

### insert(int index, IParagraphCollection value) {#insert-int-com.aspose.slides.IParagraphCollection-}
```
public final void insert(int index, IParagraphCollection value)
```

Εισάγει ένα περιεχόμενο του ParagraphCollection στη συλλογή στον καθορισμένο δείκτη.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int | Ο δείκτης που αρχίζει από το 0, στον οποίο θα εισαχθούν οι παράγραφοι. |
| value | [IParagraphCollection](../../com.aspose.slides/iparagraphcollection) | Οι παράγραφοι προς εισαγωγή. |

### clear() {#clear--}
```
public final void clear()
```

Αφαιρεί όλα τα στοιχεία από τη συλλογή.

### contains(IParagraph item) {#contains-com.aspose.slides.IParagraph-}
```
public final boolean contains(IParagraph item)
```

Καθορίζει εάν το [IGenericCollection](../../com.aspose.slides/igenericcollection) περιέχει μια συγκεκριμένη τιμή.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| item | [IParagraph](../../com.aspose.slides/iparagraph) | Το αντικείμενο που πρέπει να εντοπιστεί στο [IGenericCollection](../../com.aspose.slides/igenericcollection). |

**Επιστρέφει:**
boolean - true εάν το στοιχείο βρεθεί στο [IGenericCollection](../../com.aspose.slides/igenericcollection)· διαφορετικά, false.

### copyTo(IParagraph[] array, int arrayIndex) {#copyTo-com.aspose.slides.IParagraph---int-}
```
public final void copyTo(IParagraph[] array, int arrayIndex)
```

Αντιγράφει τα στοιχεία του [IGenericCollection](../../com.aspose.slides/igenericcollection) σε έναν Array, ξεκινώντας από έναν συγκεκριμένο δείκτη Array.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| array | [IParagraph\[\]](../../com.aspose.slides/iparagraph) | Ο μονοδιάστατος Array που είναι ο προορισμός των στοιχείων που αντιγράφονται από [IGenericCollection](../../com.aspose.slides/igenericcollection). Ο Array πρέπει να έχει δείκτη που αρχίζει από το 0. |
| arrayIndex | int | Ο μηδενικός δείκτης στον array από όπου αρχίζει η αντιγραφή. |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

Αφαιρεί το στοιχείο στον καθορισμένο δείκτη της συλλογής.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int | Ο μηδενικός δείκτης του στοιχείου που πρέπει να αφαιρεθεί. |

### remove(IParagraph item) {#remove-com.aspose.slides.IParagraph-}
```
public final boolean remove(IParagraph item)
```

Αφαιρεί την πρώτη εμφάνιση ενός συγκεκριμένου αντικειμένου από το [IGenericCollection](../../com.aspose.slides/igenericcollection).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| item | [IParagraph](../../com.aspose.slides/iparagraph) | Το αντικείμενο που πρέπει να αφαιρεθεί από το [IGenericCollection](../../com.aspose.slides/igenericcollection). |

**Επιστρέφει:**
boolean - true εάν το στοιχείο αφαιρεθεί με επιτυχία από το [IGenericCollection](../../com.aspose.slides/igenericcollection)· διαφορετικά, false. Αυτή η μέθοδος επίσης επιστρέφει false εάν το στοιχείο δεν βρεθεί στο αρχικό [IGenericCollection](../../com.aspose.slides/igenericcollection).

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IParagraph> iterator()
```

Επιστρέφει έναν enumerator που διατρέχει τη συλλογή.

**Επιστρέφει:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IParagraph> - Ένας IGenericEnumerator που μπορεί να χρησιμοποιηθεί για την διαδρομή μέσω της συλλογής.

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IParagraph> iteratorJava()
```

Επιστρέφει έναν java iterator για ολόκληρη τη συλλογή.

**Επιστρέφει:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IParagraph> - Ένα java.util.Iterator για ολόκληρη τη συλλογή.

### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

Επιστρέφει τη γονική διαφάνεια μιας συλλογής παραγράφων. Μόνο για ανάγνωση [BaseSlide](../../com.aspose.slides/baseslide).

**Επιστρέφει:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)

### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

Επιστρέφει την γονική παρουσίαση μιας συλλογής παραγράφων. Μόνο για ανάγνωση [IPresentation](../../com.aspose.slides/ipresentation).

**Επιστρέφει:**
[IPresentation](../../com.aspose.slides/ipresentation)

### addFromHtml(String text) {#addFromHtml-java.lang.String-}
```
public final void addFromHtml(String text)
```

Προσθέτει κείμενο από το καθορισμένο html string στη συλλογή.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| text | java.lang.String | Κείμενο HTML. |

### addFromHtml(String text, IExternalResourceResolver resolver, String uri) {#addFromHtml-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-}
```
public final void addFromHtml(String text, IExternalResourceResolver resolver, String uri)
```

Προσθέτει κείμενο από το καθορισμένο html string στη συλλογή.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| text | java.lang.String | Κείμενο HTML. |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | Αντικείμενο κλήσης επιστροφής resolver που επιλύει URIs και ανακτά τα αναφερόμενα αντικείμενα. |
| uri | java.lang.String | URI για την προσθήκη εγγράφου HTML. Χρησιμοποιείται για την επίλυση σχετικών συνδέσμων. |

--------------------
Ο καθορισμός resolver μπορεί ενδεχομένως να εισάγει μια ευπάθεια. Χρησιμοποιήστε με προσοχή. |

### exportToHtml(int firstParagraphIndex, int paragraphsCount, ITextToHtmlConversionOptions options) {#exportToHtml-int-int-com.aspose.slides.ITextToHtmlConversionOptions-}
```
public final String exportToHtml(int firstParagraphIndex, int paragraphsCount, ITextToHtmlConversionOptions options)
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