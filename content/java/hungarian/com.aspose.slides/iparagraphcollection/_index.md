---
title: IParagraphCollection
second_title: Aspose.Slides Java API referencia
description: A bekezdések gyűjteményét reprezentálja.
type: docs
url: /hu/com.aspose.slides/iparagraphcollection/
---
**Minden megvalósított interfész:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable, [com.aspose.slides.ISlideComponent](../../com.aspose.slides/islidecomponent)
```
public interface IParagraphCollection extends System.Collections.Generic.IGenericEnumerable<IParagraph>, ISlideComponent
```

Egy Paragraph gyűjteményét reprezentálja.

## Módszerek

| Módszer | Leírás |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Visszaadja a megadott indexű elemet. |
| [getCount()](#getCount--) | Visszaadja a gyűjteményben ténylegesen tárolt elemek számát. |
| [add(IParagraph value)](#add-com.aspose.slides.IParagraph-) | Hozzáad egy Paragraph-ot a gyűjtemény végéhez. |
| [add(IParagraphCollection value)](#add-com.aspose.slides.IParagraphCollection-) | Hozzáad egy ParagraphCollection tartalmát a gyűjtemény végéhez. |
| [insert(int index, IParagraph value)](#insert-int-com.aspose.slides.IParagraph-) | Beszúr egy Paragraph-ot a gyűjteménybe a megadott indexnél. |
| [insert(int index, IParagraphCollection value)](#insert-int-com.aspose.slides.IParagraphCollection-) | Beszúr egy ParagraphCollection tartalmát a gyűjteménybe a megadott indexnél. |
| [clear()](#clear--) | Eltávolítja a gyűjtemény összes elemét. |
| [removeAt(int index)](#removeAt-int-) | Eltávolítja a gyűjteményben a megadott indexű elemet. |
| [remove(IParagraph item)](#remove-com.aspose.slides.IParagraph-) | Eltávolítja egy adott Paragraph első előfordulását. |
| [addFromHtml(String text)](#addFromHtml-java.lang.String-) | Szöveget ad hozzá a gyűjteményhez a megadott HTML-karakterláncból. |
| [addFromHtml(String text, IExternalResourceResolver resolver, String uri)](#addFromHtml-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-) | Szöveget ad hozzá a gyűjteményhez a megadott HTML-karakterláncból. |
| [exportToHtml(int firstParagraphIndex, int paragraphsCount, ITextToHtmlConversionOptions options)](#exportToHtml-int-int-com.aspose.slides.ITextToHtmlConversionOptions-) | Átalakítja a megadott Paragraph-okat HTML-re, és visszaadja String objektumként. |

### get_Item(int index) {#get-Item-int-}
```
public abstract IParagraph get_Item(int index)
```

Visszaadja a megadott indexű elemet.

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

Visszaadja a gyűjteményben ténylegesen tárolt elemek számát. Csak olvasható int.

**Visszatérési érték:**
int

### add(IParagraph value) {#add-com.aspose.slides.IParagraph-}
```
public abstract void add(IParagraph value)
```

Hozzáad egy Paragraph-ot a gyűjtemény végéhez.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | [IParagraph](../../com.aspose.slides/iparagraph) | A Paragraph, amelyet a gyűjtemény végéhez kell hozzáadni. |

### add(IParagraphCollection value) {#add-com.aspose.slides.IParagraphCollection-}
```
public abstract int add(IParagraphCollection value)
```

Hozzáad egy ParagraphCollection tartalmát a gyűjtemény végéhez.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | [IParagraphCollection](../../com.aspose.slides/iparagraphcollection) | A ParagraphCollection, amelyet a gyűjtemény végéhez kell hozzáadni. |

**Visszatérési érték:**
int – Az index, ahol a Paragraph hozzá lett adva, vagy -1, ha nincs mit hozzáadni.

### insert(int index, IParagraph value) {#insert-int-com.aspose.slides.IParagraph-}
```
public abstract void insert(int index, IParagraph value)
```

Beszúr egy Paragraph-ot a gyűjteménybe a megadott indexnél.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int | A nulláralapú index, ahol a Paragraph-ot be kell szúrni. |
| value | [IParagraph](../../com.aspose.slides/iparagraph) | A beszúrandó Paragraph. |

### insert(int index, IParagraphCollection value) {#insert-int-com.aspose.slides.IParagraphCollection-}
```
public abstract void insert(int index, IParagraphCollection value)
```

Beszúr egy ParagraphCollection tartalmát a gyűjteménybe a megadott indexnél.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int | A nulláralapú index, ahol a ParagraphCollection elemeket be kell szúrni. |
| value | [IParagraphCollection](../../com.aspose.slides/iparagraphcollection) | A beszúrandó ParagraphCollection. |

### clear() {#clear--}
```
public abstract void clear()
```

Eltávolítja a gyűjtemény összes elemét.

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

Eltávolítja a gyűjteményben a megadott indexű elemet.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int | A nulláralapú index, amelynek az elemét el kell távolítani. |

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
boolean – true, ha az elem sikeresen eltávolításra került; egyébként false.

### addFromHtml(String text) {#addFromHtml-java.lang.String-}
```
public abstract void addFromHtml(String text)
```

Szöveget ad a gyűjteményhez a megadott HTML-karakterláncból.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| text | java.lang.String | HTML szöveg. |

### addFromHtml(String text, IExternalResourceResolver resolver, String uri) {#addFromHtml-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-}
```
public abstract void addFromHtml(String text, IExternalResourceResolver resolver, String uri)
```

Szöveget ad a gyűjteményhez a megadott HTML-karakterláncból.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| text | java.lang.String | HTML szöveg. |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | Resolver visszahívási objektum, amely feloldja az URI-kat és letölti a hivatkozott objektumokat. |
| uri | java.lang.String | Az URI, amelyet a HTML-dokumentum hozzáadásához használunk. Relatív hivatkozások feloldásához. |

---

A resolver megadása potenciálisan sebezhetőséget okozhat. Óvatosan használja.

### exportToHtml(int firstParagraphIndex, int paragraphsCount, ITextToHtmlConversionOptions options) {#exportToHtml-int-int-com.aspose.slides.ITextToHtmlConversionOptions-}
```
public abstract String exportToHtml(int firstParagraphIndex, int paragraphsCount, ITextToHtmlConversionOptions options)
```

Átalakítja a megadott Paragraph-okat HTML-re, és visszaadja String objektumként.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| firstParagraphIndex | int | Az első Paragraph indexe (int) |
| paragraphsCount | int | Paragraphok száma (int) |
| options | [ITextToHtmlConversionOptions](../../com.aspose.slides/itexttohtmlconversionoptions) | Átalakítási beállítások [ITextToHtmlConversionOptions](../../com.aspose.slides/itexttohtmlconversionoptions) |

**Visszatérési érték:**
java.lang.String – Generált HTML.