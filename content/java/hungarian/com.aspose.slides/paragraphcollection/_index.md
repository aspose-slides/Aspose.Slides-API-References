---
title: ParagraphCollection
second_title: Aspose.Slides a Java API hivatkozása
description: Bekezdések gyűjményt képviseli.
type: docs
url: /hu/com.aspose.slides/paragraphcollection/
---
**Öröklés:**
java.lang.Object, com.aspose.slides.DomObject

**Minden megvalósított interfész:**
[com.aspose.slides.IParagraphCollection](../../com.aspose.slides/iparagraphcollection)
```
public final class ParagraphCollection extends DomObject<TextFrame> implements IParagraphCollection
```

Egy bekezdésgyűjteményt képvisel.
## Módszerek

| Módszer | Leírás |
| --- | --- |
| [getCount()](#getCount--) | A gyűjteményben ténylegesen lévő elemek számát adja vissza. |
| [isReadOnly()](#isReadOnly--) | Egy értéket ad, amely jelzi, hogy a [IGenericCollection](../../com.aspose.slides/igenericcollection) csak olvasható-e. |
| [get_Item(int index)](#get-Item-int-) | A megadott indexű elemet adja vissza. |
| [add(IParagraph value)](#add-com.aspose.slides.IParagraph-) | Egy Paragraph-ot hozzáad a gyűjtemény végéhez. |
| [add(IParagraphCollection value)](#add-com.aspose.slides.IParagraphCollection-) | A ParagraphCollection tartalmát hozzáadja a gyűjtemény végéhez. |
| [indexOf(IParagraph item)](#indexOf-com.aspose.slides.IParagraph-) | Meghatározza egy adott elem indexét a Listában. |
| [insert(int index, IParagraph value)](#insert-int-com.aspose.slides.IParagraph-) | Beszúr egy Paragraph-ot a gyűjteménybe a megadott indexnél. |
| [insert(int index, IParagraphCollection value)](#insert-int-com.aspose.slides.IParagraphCollection-) | Beszúr egy ParagraphCollection tartalmát a gyűjteménybe a megadott indexnél. |
| [clear()](#clear--) | Eltávolítja a gyűjtemény összes elemét. |
| [contains(IParagraph item)](#contains-com.aspose.slides.IParagraph-) | Megállapítja, hogy a [IGenericCollection](../../com.aspose.slides/igenericcollection) tartalmaz-e egy adott értéket. |
| [copyTo(IParagraph[] array, int arrayIndex)](#copyTo-com.aspose.slides.IParagraph---int-) | A [IGenericCollection](../../com.aspose.slides/igenericcollection) elemeit egy tömbbe másolja, egy adott tömbindexnél kezdve. |
| [removeAt(int index)](#removeAt-int-) | Eltávolítja a gyűjteményben a megadott indexű elemet. |
| [remove(IParagraph item)](#remove-com.aspose.slides.IParagraph-) | Eltávolítja egy adott objektum első előfordulását a [IGenericCollection](../../com.aspose.slides/igenericcollection)-ből. |
| [iterator()](#iterator--) | Visszaad egy enumerátort, amely a gyűjteményen iterál. |
| [iteratorJava()](#iteratorJava--) | Visszaad egy java iterátort az egész gyűjteményhez. |
| [getSlide()](#getSlide--) | Visszaadja a bekezdésgyűjtemény szülő slide-ot. |
| [getPresentation()](#getPresentation--) | Visszaadja a bekezdésgyűjtemény szülő prezentációját. |
| [addFromHtml(String text)](#addFromHtml-java.lang.String-) | Szöveget ad hozzá a megadott HTML karakterláncból a gyűjteményhez. |
| [addFromHtml(String text, IExternalResourceResolver resolver, String uri)](#addFromHtml-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-) | Szöveget ad hozzá a megadott HTML karakterláncból a gyűjteményhez. |
| [exportToHtml(int firstParagraphIndex, int paragraphsCount, ITextToHtmlConversionOptions options)](#exportToHtml-int-int-com.aspose.slides.ITextToHtmlConversionOptions-) | A megadott bekezdéseket HTML-re konvertálja, és String objektumként adja vissza. |
### getCount() {#getCount--}
```
public final int getCount()
```


A gyűjteményben ténylegesen lévő elemek számát adja vissza. Csak olvasható int.

**Visszatérési érték:**
int
### isReadOnly() {#isReadOnly--}
```
public final boolean isReadOnly()
```


Egy értéket ad, amely jelzi, hogy a [IGenericCollection](../../com.aspose.slides/igenericcollection) csak olvasható-e. Csak olvasható boolean.

**Visszatérési érték:**
boolean - true if the [IGenericCollection](../../com.aspose.slides/igenericcollection) is read-only; otherwise, false.
### get_Item(int index) {#get-Item-int-}
```
public final IParagraph get_Item(int index)
```


A megadott indexű elemet adja vissza.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int |  |

**Visszatérési érték:**
[IParagraph](../../com.aspose.slides/iparagraph)
### add(IParagraph value) {#add-com.aspose.slides.IParagraph-}
```
public final void add(IParagraph value)
```


Egy Paragraph-ot hozzáad a gyűjtemény végéhez.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | [IParagraph](../../com.aspose.slides/iparagraph) | The Paragraph to be added to the end of the collection. |

### add(IParagraphCollection value) {#add-com.aspose.slides.IParagraphCollection-}
```
public final int add(IParagraphCollection value)
```


A ParagraphCollection tartalmát hozzáadja a gyűjtemény végéhez.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | [IParagraphCollection](../../com.aspose.slides/iparagraphcollection) | The ParagraphCollection to be added to the end of the collection. |

**Visszatérési érték:**
int - The index at which the Paragraph has been added or -1 if there are nothing to add.
### indexOf(IParagraph item) {#indexOf-com.aspose.slides.IParagraph-}
```
public final int indexOf(IParagraph item)
```


Meghatározza egy adott elem indexét a Listában.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| item | [IParagraph](../../com.aspose.slides/iparagraph) | The object to locate in the List. |

**Visszatérési érték:**
int - The index of item if found in the list; otherwise, -1.
### insert(int index, IParagraph value) {#insert-int-com.aspose.slides.IParagraph-}
```
public final void insert(int index, IParagraph value)
```


Beszúr egy Paragraph-ot a gyűjteménybe a megadott indexnél.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int | The zero-based index at which Paragraph should be inserted. |
| value | [IParagraph](../../com.aspose.slides/iparagraph) | The Paragraph to insert. |

### insert(int index, IParagraphCollection value) {#insert-int-com.aspose.slides.IParagraphCollection-}
```
public final void insert(int index, IParagraphCollection value)
```


Beszúr egy ParagraphCollection tartalmát a gyűjteménybe a megadott indexnél.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int | The zero-based index at which paragraphs should be inserted. |
| value | [IParagraphCollection](../../com.aspose.slides/iparagraphcollection) | The paragraphs to insert. |

### clear() {#clear--}
```
public final void clear()
```


Eltávolítja a gyűjtemény összes elemét.

### contains(IParagraph item) {#contains-com.aspose.slides.IParagraph-}
```
public final boolean contains(IParagraph item)
```


Megállapítja, hogy a [IGenericCollection](../../com.aspose.slides/igenericcollection) tartalmaz-e egy adott értéket.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| item | [IParagraph](../../com.aspose.slides/iparagraph) | The object to locate in the [IGenericCollection](../../com.aspose.slides/igenericcollection). |

**Visszatérési érték:**
boolean - true if item is found in the [IGenericCollection](../../com.aspose.slides/igenericcollection); otherwise, false.
### copyTo(IParagraph[] array, int arrayIndex) {#copyTo-com.aspose.slides.IParagraph---int-}
```
public final void copyTo(IParagraph[] array, int arrayIndex)
```


A [IGenericCollection](../../com.aspose.slides/igenericcollection) elemeit egy tömbbe másolja, egy adott tömbindexnél kezdve.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| array | [IParagraph\[\]](../../com.aspose.slides/iparagraph) | The one-dimensional Array that is the destination of the elements copied from [IGenericCollection](../../com.aspose.slides/igenericcollection). The Array must have zero-based indexing. |
| arrayIndex | int | The zero-based index in array at which copying begins. |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```


Eltávolítja a gyűjteményben a megadott indexű elemet.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int | The zero-based index of the element to remove. |

### remove(IParagraph item) {#remove-com.aspose.slides.IParagraph-}
```
public final boolean remove(IParagraph item)
```


Eltávolítja egy adott objektum első előfordulását a [IGenericCollection](../../com.aspose.slides/igenericcollection)-ből.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| item | [IParagraph](../../com.aspose.slides/iparagraph) | The object to remove from the [IGenericCollection](../../com.aspose.slides/igenericcollection). |

**Visszatérési érték:**
boolean - true if item was successfully removed from the [IGenericCollection](../../com.aspose.slides/igenericcollection); otherwise, false. This method also returns false if item is not found in the original [IGenericCollection](../../com.aspose.slides/igenericcollection).
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IParagraph> iterator()
```


Visszaad egy enumerátort, amely a gyűjteményen iterál.

**Visszatérési érték:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IParagraph> - A IGenericEnumerator that can be used to iterate through the collection.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IParagraph> iteratorJava()
```


Visszaad egy java iterátort az egész gyűjteményhez.

**Visszatérési érték:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IParagraph> - An java.util.Iterator for the entire collection.
### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```


Visszaadja a bekezdésgyűjtemény szülő slide-ot. Csak olvasható [BaseSlide](../../com.aspose.slides/baseslide).

**Visszatérési érték:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)
### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```


Visszaadja a bekezdésgyűjtemény szülő prezentációját. Csak olvasható [IPresentation](../../com.aspose.slides/ipresentation).

**Visszatérési érték:**
[IPresentation](../../com.aspose.slides/ipresentation)
### addFromHtml(String text) {#addFromHtml-java.lang.String-}
```
public final void addFromHtml(String text)
```


Szöveget ad hozzá a megadott HTML karakterláncból a gyűjteményhez.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| text | java.lang.String | HTML text. |

### addFromHtml(String text, IExternalResourceResolver resolver, String uri) {#addFromHtml-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-}
```
public final void addFromHtml(String text, IExternalResourceResolver resolver, String uri)
```


Szöveget ad hozzá a megadott HTML karakterláncból a gyűjteményhez.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| text | java.lang.String | HTML text. |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | Resolver callback object which resolves URIs and fetches referrenced objects. |
| uri | java.lang.String | URI for adding HTML document. Used for resolving relative links.

--------------------

A resolver megadása potenciálisan sebezhetőséget vezethet be. Óvatosan használja. |
### exportToHtml(int firstParagraphIndex, int paragraphsCount, ITextToHtmlConversionOptions options) {#exportToHtml-int-int-com.aspose.slides.ITextToHtmlConversionOptions-}
```
public final String exportToHtml(int firstParagraphIndex, int paragraphsCount, ITextToHtmlConversionOptions options)
```


A megadott bekezdéseket HTML-re konvertálja, és String objektumként adja vissza.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| firstParagraphIndex | int | First paragraph index int |
| paragraphsCount | int | Paragraph count int |
| options | [ITextToHtmlConversionOptions](../../com.aspose.slides/itexttohtmlconversionoptions) | Convert options [ITextToHtmlConversionOptions](../../com.aspose.slides/itexttohtmlconversionoptions) |

**Visszatérési érték:**
java.lang.String - Generated HTML.