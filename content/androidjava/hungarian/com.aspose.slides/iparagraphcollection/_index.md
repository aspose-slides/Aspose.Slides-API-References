---
title: IParagraphCollection
second_title: Aspose.Slides Androidhoz a Java API hivatkozás
description: A bekezdések gyűjteményét reprezentálja.
type: docs
url: /hu/com.aspose.slides/iparagraphcollection/
---
**Minden megvalósított interfész:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable, [com.aspose.slides.ISlideComponent](../../com.aspose.slides/islidecomponent)
```
public interface IParagraphCollection extends System.Collections.Generic.IGenericEnumerable<IParagraph>, ISlideComponent
```

Egy Paragraph gyűjteményt reprezentál.
## Metódusok

| Metódus | Leírás |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | A megadott indexű elemet adja vissza. |
| [getCount()](#getCount--) | A gyűjteményben valóban tárolt elemek számát adja vissza. |
| [add(IParagraph value)](#add-com.aspose.slides.IParagraph-) | Egy Paragraph-ot ad a gyűjtemény végéhez. |
| [add(IParagraphCollection value)](#add-com.aspose.slides.IParagraphCollection-) | A ParagraphCollection tartalmát adja a gyűjtemény végéhez. |
| [insert(int index, IParagraph value)](#insert-int-com.aspose.slides.IParagraph-) | Beszúr egy Paragraph-ot a gyűjteménybe a megadott indexnél. |
| [insert(int index, IParagraphCollection value)](#insert-int-com.aspose.slides.IParagraphCollection-) | A ParagraphCollection tartalmát szúrja be a gyűjteménybe a megadott indexnél. |
| [clear()](#clear--) | Eltávolítja az összes elemet a gyűjteményből. |
| [removeAt(int index)](#removeAt-int-) | Eltávolítja a gyűjtemény megadott indexű elemét. |
| [remove(IParagraph item)](#remove-com.aspose.slides.IParagraph-) | Eltávolítja egy adott Paragraph első előfordulását. |
| [addFromHtml(String text)](#addFromHtml-java.lang.String-) | Szöveget ad a megadott HTML-karakterláncból a gyűjteményhez. |
| [addFromHtml(String text, IExternalResourceResolver resolver, String uri)](#addFromHtml-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-) | Szöveget ad a megadott HTML-karakterláncból a gyűjteményhez. |
| [exportToHtml(int firstParagraphIndex, int paragraphsCount, ITextToHtmlConversionOptions options)](#exportToHtml-int-int-com.aspose.slides.ITextToHtmlConversionOptions-) | A megadott bekezdéseket HTML-re konvertálja, és String objektumként adja vissza. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IParagraph get_Item(int index)
```

A megadott indexű elemet adja vissza.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int |  |

**Visszatérési érték:**
[IParagraph](../../com.aspose.slides/iparagraph)
### getCount() {#getCount--}
```
public abstract int getCount()
```

A gyűjteményben valóban tárolt elemek számát adja vissza. Csak olvasható int.

**Visszatérési érték:**
int
### add(IParagraph value) {#add-com.aspose.slides.IParagraph-}
```
public abstract void add(IParagraph value)
```

Egy Paragraph-ot ad a gyűjtemény végéhez.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | [IParagraph](../../com.aspose.slides/iparagraph) | A Paragraph, amelyet a gyűjtemény végéhez kell hozzáadni. |

### add(IParagraphCollection value) {#add-com.aspose.slides.IParagraphCollection-}
```
public abstract int add(IParagraphCollection value)
```

A ParagraphCollection tartalmát adja a gyűjtemény végéhez.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | [IParagraphCollection](../../com.aspose.slides/iparagraphcollection) | A ParagraphCollection, amelyet a gyűjtemény végéhez kell hozzáadni. |

**Visszatérési érték:**
int – Az az index, ahová a Paragraph hozzá lett adva, vagy -1, ha nincs mit hozzáadni.
### insert(int index, IParagraph value) {#insert-int-com.aspose.slides.IParagraph-}
```
public abstract void insert(int index, IParagraph value)
```

Beszúr egy Paragraph-ot a gyűjteménybe a megadott indexnél.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int | A nulla alapú index, ahol a Paragraph-ot be kell illeszteni. |
| value | [IParagraph](../../com.aspose.slides/iparagraph) | Az illeszteni kívánt Paragraph. |

### insert(int index, IParagraphCollection value) {#insert-int-com.aspose.slides.IParagraphCollection-}
```
public abstract void insert(int index, IParagraphCollection value)
```

A ParagraphCollection tartalmát szúrja be a gyűjteménybe a megadott indexnél.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int | A nulla alapú index, ahol a bekezdéseket be kell illeszteni. |
| value | [IParagraphCollection](../../com.aspose.slides/iparagraphcollection) | A beillesztendő bekezdések. |

### clear() {#clear--}
```
public abstract void clear()
```

Eltávolítja az összes elemet a gyűjteményből.

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

Eltávolítja a gyűjtemény megadott indexű elemét.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int | A eltávolítandó elem nulla alapú indexe. |

### remove(IParagraph item) {#remove-com.aspose.slides.IParagraph-}
```
public abstract boolean remove(IParagraph item)
```

Eltávolítja egy adott Paragraph első előfordulását.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| item | [IParagraph](../../com.aspose.slides/iparagraph) | A gyűjteményből eltávolítandó Paragraph. |

**Visszatérési érték:**
boolean – true, ha az elem sikeresen eltávolítva lett; egyébként false.
### addFromHtml(String text) {#addFromHtml-java.lang.String-}
```
public abstract void addFromHtml(String text)
```

Szöveget ad a megadott HTML-karakterláncból a gyűjteményhez.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| text | java.lang.String | HTML szöveg. |

### addFromHtml(String text, IExternalResourceResolver resolver, String uri) {#addFromHtml-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-}
```
public abstract void addFromHtml(String text, IExternalResourceResolver resolver, String uri)
```

Szöveget ad a megadott HTML-karakterláncból a gyűjteményhez.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| text | java.lang.String | HTML szöveg. |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | Resolver visszahívási objektum, amely feloldja az URI-kat és lekéri a hivatkozott objektumokat. |
| uri | java.lang.String | Az HTML-dokumentum hozzáadásához használt URI. Relatív hivatkozások feloldására szolgál.

--------------------

A resolver megadása potenciálisan sebezhetőséget okozhat. Óvatosan használja. |
### exportToHtml(int firstParagraphIndex, int paragraphsCount, ITextToHtmlConversionOptions options) {#exportToHtml-int-int-com.aspose.slides.ITextToHtmlConversionOptions-}
```
public abstract String exportToHtml(int firstParagraphIndex, int paragraphsCount, ITextToHtmlConversionOptions options)
```

A megadott bekezdéseket HTML-re konvertálja, és String objektumként adja vissza.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| firstParagraphIndex | int | Első bekezdés index (int) |
| paragraphsCount | int | A bekezdések száma (int) |
| options | [ITextToHtmlConversionOptions](../../com.aspose.slides/itexttohtmlconversionoptions) | Konvertálási beállítások [ITextToHtmlConversionOptions](../../com.aspose.slides/itexttohtmlconversionoptions) |

**Visszatérési érték:**
java.lang.String – Generált HTML.