---
title: ParagraphCollection
second_title: Aspose.Slides για την Αναφορά API της Java
description: Αναπαριστά μια συλλογή παραγράφων.
type: docs
url: /el/com.aspose.slides/paragraphcollection/
---
**Κληρονομικότητα:**
java.lang.Object, com.aspose.slides.DomObject

**Όλες οι υλοποιημένες διεπαφές:**
[com.aspose.slides.IParagraphCollection](../../com.aspose.slides/iparagraphcollection)
```
public final class ParagraphCollection extends DomObject<TextFrame> implements IParagraphCollection
```

Αναπαριστά μια συλλογή παραγράφων.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getCount()](#getCount--) | Επιστρέφει τον αριθμό των στοιχείων που περιέχονται στην συλλογή. |
| [isReadOnly()](#isReadOnly--) | Λαμβάνει μια τιμή που υποδεικνύει εάν το [IGenericCollection](../../com.aspose.slides/igenericcollection) είναι μόνο για ανάγνωση. |
| [get_Item(int index)](#get-Item-int-) | Επιστρέφει το στοιχείο στον καθορισμένο δείκτη. |
| [add(IParagraph value)](#add-com.aspose.slides.IParagraph-) | Προσθέτει ένα Paragraph στο τέλος της συλλογής. |
| [add(IParagraphCollection value)](#add-com.aspose.slides.IParagraphCollection-) | Προσθέτει το περιεχόμενο του ParagraphCollection στο τέλος της συλλογής. |
| [indexOf(IParagraph item)](#indexOf-com.aspose.slides.IParagraph-) | Καθορίζει το δείκτη ενός συγκεκριμένου στοιχείου στη λίστα. |
| [insert(int index, IParagraph value)](#insert-int-com.aspose.slides.IParagraph-) | Εισάγει ένα Paragraph στη συλλογή στον καθορισμένο δείκτη. |
| [insert(int index, IParagraphCollection value)](#insert-int-com.aspose.slides.IParagraphCollection-) | Εισάγει το περιεχόμενο του ParagraphCollection στη συλλογή στον καθορισμένο δείκτη. |
| [clear()](#clear--) | Αφαιρεί όλα τα στοιχεία από τη συλλογή. |
| [contains(IParagraph item)](#contains-com.aspose.slides.IParagraph-) | Καθορίζει εάν το [IGenericCollection](../../com.aspose.slides/igenericcollection) περιέχει μια συγκεκριμένη τιμή. |
| [copyTo(IParagraph[] array, int arrayIndex)](#copyTo-com.aspose.slides.IParagraph---int-) | Αντιγράφει τα στοιχεία του [IGenericCollection](../../com.aspose.slides/igenericcollection) σε έναν πίνακα, ξεκινώντας από έναν συγκεκριμένο δείκτη πίνακα. |
| [removeAt(int index)](#removeAt-int-) | Αφαιρεί το στοιχείο στον καθορισμένο δείκτη της συλλογής. |
| [remove(IParagraph item)](#remove-com.aspose.slides.IParagraph-) | Αφαιρεί την πρώτη εμφάνιση ενός συγκεκριμένου αντικειμένου από το [IGenericCollection](../../com.aspose.slides/igenericcollection). |
| [iterator()](#iterator--) | Επιστρέφει έναν enumerator που διασχίζει τη συλλογή. |
| [iteratorJava()](#iteratorJava--) | Επιστρέφει έναν java iterator για ολόκληρη τη συλλογή. |
| [getSlide()](#getSlide--) | Επιστρέφει τη γονική διαφάνεια μιας συλλογής παραγράφων. |
| [getPresentation()](#getPresentation--) | Επιστρέφει την γονική παρουσίαση μιας συλλογής παραγράφων. |
| [addFromHtml(String text)](#addFromHtml-java.lang.String-) | Προσθέτει κείμενο από την καθορισμένη αλυσίδα html στη συλλογή. |
| [addFromHtml(String text, IExternalResourceResolver resolver, String uri)](#addFromHtml-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-) | Προσθέτει κείμενο από την καθορισμένη αλυσίδα html στη συλλογή. |
| [exportToHtml(int firstParagraphIndex, int paragraphsCount, ITextToHtmlConversionOptions options)](#exportToHtml-int-int-com.aspose.slides.ITextToHtmlConversionOptions-) | Μετατρέπει τις καθορισμένες παραγράφους σε HTML και τις επιστρέφει ως αντικείμενο String. |

### getCount() {#getCount--}
```
public final int getCount()
```

Επιστέφει τον αριθμό των στοιχείων που περιέχονται στην συλλογή. Μόνο για ανάγνωση int.

**Επιστρέφει:**  
int

### isReadOnly() {#isReadOnly--}
```
public final boolean isReadOnly()
```

Λαμβάνει μια τιμή που υποδεικνύει εάν το [IGenericCollection](../../com.aspose.slides/igenericcollection) είναι μόνο για ανάγνωση. Μόνο για ανάγνωση boolean.

**Επιστρέφει:**  
boolean - true εάν το [IGenericCollection](../../com.aspose.slides/igenericcollection) είναι μόνο για ανάγνωση· διαφορετικά, false.

### get_Item(int index) {#get-Item-int-}
```
public final IParagraph get_Item(int index)
```

Επιστέφει το στοιχείο στον καθορισμένο δείκτη.

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

Προσθέτει το περιεχόμενο του ParagraphCollection στο τέλος της συλλογής.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [IParagraphCollection](../../com.aspose.slides/iparagraphcollection) | Το ParagraphCollection που θα προστεθεί στο τέλος της συλλογής. |

**Επιστρέφει:**  
int - Το δείκτη στο οποίο προστέθηκε το Paragraph ή -1 εάν δεν υπάρχει κάτι προς προσθήκη.

### indexOf(IParagraph item) {#indexOf-com.aspose.slides.IParagraph-}
```
public final int indexOf(IParagraph item)
```

Καθορίζει το δείκτη ενός συγκεκριμένου στοιχείου στη λίστα.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| item | [IParagraph](../../com.aspose.slides/iparagraph) | Το αντικείμενο προς εντοπισμό στη Λίστα. |

**Επιστρέφει:**  
int - Το δείκτη του αντικειμένου αν βρεθεί στη λίστα· διαφορετικά, -1.

### insert(int index, IParagraph value) {#insert-int-com.aspose.slides.IParagraph-}
```
public final void insert(int index, IParagraph value)
```

Εισάγει ένα Paragraph στη συλλογή στον καθορισμένο δείκτη.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int | Ο μηδενικός δείκτης στον οποίο θα εισαχθεί το Paragraph. |
| value | [IParagraph](../../com.aspose.slides/iparagraph) | Το Paragraph προς εισαγωγή. |

### insert(int index, IParagraphCollection value) {#insert-int-com.aspose.slides.IParagraphCollection-}
```
public final void insert(int index, IParagraphCollection value)
```

Εισάγει το περιεχόμενο του ParagraphCollection στη συλλογή στον καθορισμένο δείκτη.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int | Ο μηδενικός δείκτης στον οποίο θα εισαχθούν οι παράγραφοι. |
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
| item | [IParagraph](../../com.aspose.slides/iparagraph) | Το αντικείμενο προς εντοπισμό στο [IGenericCollection](../../com.aspose.slides/igenericcollection). |

**Επιστρέφει:**  
boolean - true εάν το αντικείμενο βρεθεί στο [IGenericCollection](../../com.aspose.slides/igenericcollection)· διαφορετικά, false.

### copyTo(IParagraph[] array, int arrayIndex) {#copyTo-com.aspose.slides.IParagraph---int-}
```
public final void copyTo(IParagraph[] array, int arrayIndex)
```

Αντιγράφει τα στοιχεία του [IGenericCollection](../../com.aspose.slides/igenericcollection) σε έναν πίνακα, ξεκινώντας από έναν συγκεκριμένο δείκτη πίνακα.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| array | [IParagraph\[\]](../../com.aspose.slides/iparagraph) | Ο μονοδιάστατος πίνακας που είναι προορισμός των στοιχείων που αντιγράφονται από το [IGenericCollection](../../com.aspose.slides/igenericcollection). Ο πίνακας πρέπει να έχει μηδενική βάση. |
| arrayIndex | int | Ο μηδενικός δείκτης στον πίνακα όπου ξεκινά η αντιγραφή. |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

Αφαιρεί το στοιχείο στον καθορισμένο δείκτη της συλλογής.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int | Ο μηδενικός δείκτης του στοιχείου που θα αφαιρεθεί. |

### remove(IParagraph item) {#remove-com.aspose.slides.IParagraph-}
```
public final boolean remove(IParagraph item)
```

Αφαιρεί την πρώτη εμφάνιση ενός συγκεκριμένου αντικειμένου από το [IGenericCollection](../../com.aspose.slides/igenericcollection).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| item | [IParagraph](../../com.aspose.slides/iparagraph) | Το αντικείμενο προς αφαίρεση από το [IGenericCollection](../../com.aspose.slides/igenericcollection). |

**Επιστρέφει:**  
boolean - true εάν το αντικείμενο αφαιρεθεί επιτυχώς από το [IGenericCollection](../../com.aspose.slides/igenericcollection)· διαφορετικά, false. Αυτή η μέθοδος επιστρέφει επίσης false εάν το αντικείμενο δεν βρεθεί στο αρχικό [IGenericCollection](../../com.aspose.slides/igenericcollection).

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IParagraph> iterator()
```

Επιστέφει έναν enumerator που διασχίζει τη συλλογή.

**Επιστρέφει:**  
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IParagraph> - Ένας IGenericEnumerator που μπορεί να χρησιμοποιηθεί για την επανάληψη στη συλλογή.

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IParagraph> iteratorJava()
```

Επιστέφει έναν java iterator για ολόκληρη τη συλλογή.

**Επιστρέφει:**  
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IParagraph> - Ένας java.util.Iterator για ολόκληρη τη συλλογή.

### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

Επιστέφει τη γονική διαφάνεια μιας συλλογής παραγράφων. Μόνο για ανάγνωση [BaseSlide](../../com.aspose.slides/baseslide).

**Επιστρέφει:**  
[IBaseSlide](../../com.aspose.slides/ibaseslide)

### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

Επιστέφει την γονική παρουσίαση μιας συλλογής παραγράφων. Μόνο για ανάγνωση [IPresentation](../../com.aspose.slides/ipresentation).

**Επιστρέφει:**  
[IPresentation](../../com.aspose.slides/ipresentation)

### addFromHtml(String text) {#addFromHtml-java.lang.String-}
```
public final void addFromHtml(String text)
```

Προσθέτει κείμενο από την καθορισμένη αλυσίδα html στη συλλογή.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| text | java.lang.String | Κείμενο HTML. |

### addFromHtml(String text, IExternalResourceResolver resolver, String uri) {#addFromHtml-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-}
```
public final void addFromHtml(String text, IExternalResourceResolver resolver, String uri)
```

Προσθέτει κείμενο από την καθορισμένη αλυσίδα html στη συλλογή.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| text | java.lang.String | Κείμενο HTML. |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | Αντικείμενο callback resolver που επιλύει URIs και φέρνει τα αναφερόμενα αντικείμενα. |
| uri | java.lang.String | URI για την προσθήκη του εγγράφου HTML. Χρησιμοποιείται για την επίλυση σχετικών συνδέσμων.

--------------------

Ο καθορισμός resolver μπορεί ενδεχομένως να εισαγάγει ευπάθεια. Χρησιμοποιήστε με προσοχή. |

### exportToHtml(int firstParagraphIndex, int paragraphsCount, ITextToHtmlConversionOptions options) {#exportToHtml-int-int-com.aspose.slides.ITextToHtmlConversionOptions-}
```
public final String exportToHtml(int firstParagraphIndex, int paragraphsCount, ITextToHtmlConversionOptions options)
```

Μετατρέπει τις καθορισμένες παραγράφους σε HTML και τις επιστρέφει ως αντικείμενο String.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| firstParagraphIndex | int | Δείκτης πρώτης παραγράφου int |
| paragraphsCount | int | Αριθμός παραγράφων int |
| options | [ITextToHtmlConversionOptions](../../com.aspose.slides/itexttohtmlconversionoptions) | Επιλογές μετατροπής [ITextToHtmlConversionOptions](../../com.aspose.slides/itexttohtmlconversionoptions) |

**Επιστρέφει:**  
java.lang.String - Generated HTML.