---
title: ParagraphCollection
second_title: Aspose.Slides Android számára Java API hivatkozás
description: Egy bekezdésgyűjteményt képvisel.
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

Egy bekezdés gyűjteményét képviseli.
## Metódusok

| Metódus | Leírás |
| --- | --- |
| [getCount()](#getCount--) | Visszaadja a gyűjteményben ténylegesen szereplő elemek számát. |
| [isReadOnly()](#isReadOnly--) | Visszaadja azt az értéket, amely jelzi, hogy a [IGenericCollection](../../com.aspose.slides/igenericcollection) csak olvasható-e. |
| [get_Item(int index)](#get-Item-int-) | Visszaadja a megadott indexű elemet. |
| [add(IParagraph value)](#add-com.aspose.slides.IParagraph-) | Egy Paragraph elemet ad a gyűjtemény végéhez. |
| [add(IParagraphCollection value)](#add-com.aspose.slides.IParagraphCollection-) | A ParagraphCollection tartalmát adja a gyűjtemény végéhez. |
| [indexOf(IParagraph item)](#indexOf-com.aspose.slides.IParagraph-) | Meghatározza egy adott elem indexét a Listában. |
| [insert(int index, IParagraph value)](#insert-int-com.aspose.slides.IParagraph-) | Beszúr egy Paragraph elemet a gyűjteménybe a megadott indexen. |
| [insert(int index, IParagraphCollection value)](#insert-int-com.aspose.slides.IParagraphCollection-) | A ParagraphCollection tartalmát szúrja be a gyűjteménybe a megadott indexen. |
| [clear()](#clear--) | Eltávolítja a gyűjtemény összes elemét. |
| [contains(IParagraph item)](#contains-com.aspose.slides.IParagraph-) | Megállapítja, hogy a [IGenericCollection](../../com.aspose.slides/igenericcollection) tartalmaz-e egy adott értéket. |
| [copyTo(IParagraph[] array, int arrayIndex)](#copyTo-com.aspose.slides.IParagraph---int-) | Átmásolja a [IGenericCollection](../../com.aspose.slides/igenericcollection) elemeit egy tömbbe, egy adott tömbindexnél kezdve. |
| [removeAt(int index)](#removeAt-int-) | Eltávolítja a megadott indexű elemet a gyűjteményből. |
| [remove(IParagraph item)](#remove-com.aspose.slides.IParagraph-) | Eltávolítja egy adott objektum első előfordulását a [IGenericCollection](../../com.aspose.slides/igenericcollection)-ból. |
| [iterator()](#iterator--) | Visszaad egy enumerátort, amely végigiterál a gyűjteményen. |
| [iteratorJava()](#iteratorJava--) | Visszaad egy java iterátort a teljes gyűjteményhez. |
| [getSlide()](#getSlide--) | Visszaadja a bekezdésgyűjtemény szülődiapozitívját. |
| [getPresentation()](#getPresentation--) | Visszaadja a bekezdésgyűjtemény szülő prezentációját. |
| [addFromHtml(String text)](#addFromHtml-java.lang.String-) | Szöveget ad a megadott html karakterláncból a gyűjteményhez. |
| [addFromHtml(String text, IExternalResourceResolver resolver, String uri)](#addFromHtml-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-) | Szöveget ad a megadott html karakterláncból a gyűjteményhez. |
| [exportToHtml(int firstParagraphIndex, int paragraphsCount, ITextToHtmlConversionOptions options)](#exportToHtml-int-int-com.aspose.slides.ITextToHtmlConversionOptions-) | Átkonvertálja a megadott bekezdéseket HTML-re, és String objektumként adja vissza. |

### getCount() {#getCount--}
```
public final int getCount()
```

Visszaadja a gyűjteményben ténylegesen szereplő elemek számát. **Csak olvasható** int.

**Visszatér:**
int

### isReadOnly() {#isReadOnly--}
```
public final boolean isReadOnly()
```

Visszaadja azt az értéket, amely jelzi, hogy a [IGenericCollection](../../com.aspose.slides/igenericcollection) csak olvasható-e. **Csak olvasható** boolean.

**Visszatér:**
boolean - igaz, ha a [IGenericCollection](../../com.aspose.slides/igenericcollection) csak olvasható; egyébként hamis.

### get_Item(int index) {#get-Item-int-}
```
public final IParagraph get_Item(int index)
```

Visszaadja a megadott indexű elemet.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int |  |

**Visszatér:**
[IParagraph](../../com.aspose.slides/iparagraph)

### add(IParagraph value) {#add-com.aspose.slides.IParagraph-}
```
public final void add(IParagraph value)
```

Egy Paragraph elemet ad a gyűjtemény végéhez.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | [IParagraph](../../com.aspose.slides/iparagraph) | A Paragraph, amelyet a gyűjtemény végéhez kell hozzáadni. |

### add(IParagraphCollection value) {#add-com.aspose.slides.IParagraphCollection-}
```
public final int add(IParagraphCollection value)
```

A ParagraphCollection tartalmát adja a gyűjtemény végéhez.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | [IParagraphCollection](../../com.aspose.slides/iparagraphcollection) | A ParagraphCollection, amelyet a gyűjtemény végéhez kell hozzáadni. |

**Visszatér:**
int - Az az index, amelyen a Paragraph hozzá lett adva, vagy -1, ha nincs mit hozzáadni.

### indexOf(IParagraph item) {#indexOf-com.aspose.slides.IParagraph-}
```
public final int indexOf(IParagraph item)
```

Meghatározza egy adott elem indexét a Listában.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| item | [IParagraph](../../com.aspose.slides/iparagraph) | A objektum, amelyet a Listában kell megtalálni. |

**Visszatér:**
int - Az elem indexe, ha megtalálják a listában; egyébként -1.

### insert(int index, IParagraph value) {#insert-int-com.aspose.slides.IParagraph-}
```
public final void insert(int index, IParagraph value)
```

Beszúr egy Paragraph elemet a gyűjteménybe a megadott indexen.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int | A nulláról induló index, amelyen a Paragraph-ot be kell szúrni. |
| value | [IParagraph](../../com.aspose.slides/iparagraph) | A beszúrandó Paragraph. |

### insert(int index, IParagraphCollection value) {#insert-int-com.aspose.slides.IParagraphCollection-}
```
public final void insert(int index, IParagraphCollection value)
```

A ParagraphCollection tartalmát szúrja be a gyűjteménybe a megadott indexen.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int | A nulláról induló index, amelyen a bekezdéseket be kell szúrni. |
| value | [IParagraphCollection](../../com.aspose.slides/iparagraphcollection) | A beszúrandó bekezdések. |

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
| item | [IParagraph](../../com.aspose.slides/iparagraph) | A objektum, amelyet a [IGenericCollection](../../com.aspose.slides/igenericcollection)-ban kell megtalálni. |

**Visszatér:**
boolean - igaz, ha az elem megtalálható a [IGenericCollection](../../com.aspose.slides/igenericcollection)-ban; egyébként hamis.

### copyTo(IParagraph[] array, int arrayIndex) {#copyTo-com.aspose.slides.IParagraph---int-}
```
public final void copyTo(IParagraph[] array, int arrayIndex)
```

Átmásolja a [IGenericCollection](../../com.aspose.slides/igenericcollection) elemeit egy tömbbe, egy adott tömbindexnél kezdve.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| array | [IParagraph\[\]](../../com.aspose.slides/iparagraph) | Az egydimenziós tömb, amely a [IGenericCollection](../../com.aspose.slides/igenericcollection)-ból másolt elemek célhelye. A tömbnek nulláról induló indexelése van. |
| arrayIndex | int | A nulláról induló index a tömbben, ahol a másolás kezdődik. |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

Eltávolítja a megadott indexű elemet a gyűjteményből.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int | A nulláról induló index az eltávolítandó elemhez. |

### remove(IParagraph item) {#remove-com.aspose.slides.IParagraph-}
```
public final boolean remove(IParagraph item)
```

Eltávolítja egy adott objektum első előfordulását a [IGenericCollection](../../com.aspose.slides/igenericcollection)-ból.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| item | [IParagraph](../../com.aspose.slides/iparagraph) | A objektum, amelyet a [IGenericCollection](../../com.aspose.slides/igenericcollection)-ból kell eltávolítani. |

**Visszatér:**
boolean - igaz, ha az elemet sikeresen eltávolították a [IGenericCollection](../../com.aspose.slides/igenericcollection)-ból; egyébként hamis. Ez a metódus hamisat is visszaad, ha az elem nem található az eredeti [IGenericCollection](../../com.aspose.slides/igenericcollection)-ban.

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IParagraph> iterator()
```

Visszaad egy enumerátort, amely végigiterál a gyűjteményen.

**Visszatér:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IParagraph> - Egy IGenericEnumerator, amely a gyűjteményen való iteráláshoz használható.

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IParagraph> iteratorJava()
```

Visszaad egy java iterátort a teljes gyűjteményhez.

**Visszatér:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IParagraph> - Egy java.util.Iterator a teljes gyűjteményhez.

### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

Visszaadja a bekezdésgyűjtemény szülődiapozitívját. **Csak olvasható** [BaseSlide](../../com.aspose.slides/baseslide).

**Visszatér:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)

### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

Visszaadja a bekezdésgyűjtemény szülő prezentációját. **Csak olvasható** [IPresentation](../../com.aspose.slides/ipresentation).

**Visszatér:**
[IPresentation](../../com.aspose.slides/ipresentation)

### addFromHtml(String text) {#addFromHtml-java.lang.String-}
```
public final void addFromHtml(String text)
```

Szöveget ad a megadott HTML karakterláncból a gyűjteményhez.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| text | java.lang.String | HTML szöveg. |

### addFromHtml(String text, IExternalResourceResolver resolver, String uri) {#addFromHtml-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-}
```
public final void addFromHtml(String text, IExternalResourceResolver resolver, String uri)
```

Szöveget ad a megadott HTML karakterláncból a gyűjteményhez.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| text | java.lang.String | HTML szöveg. |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | A resolver visszahívási objektum, amely feloldja az URI-kat és letölti a hivatkozott objektumokat. |
| uri | java.lang.String | Az HTML dokumentum hozzáadásához használt URI. Relatív linkek feloldásához használják.

--------------------

A resolver megadása potenciálisan sebezhetőséget vezethet be. Csak óvatosan használja. |

### exportToHtml(int firstParagraphIndex, int paragraphsCount, ITextToHtmlConversionOptions options) {#exportToHtml-int-int-com.aspose.slides.ITextToHtmlConversionOptions-}
```
public final String exportToHtml(int firstParagraphIndex, int paragraphsCount, ITextToHtmlConversionOptions options)
```

Átkonvertálja a megadott bekezdéseket HTML-re, és String objektumként adja vissza.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| firstParagraphIndex | int | Az első bekezdés indexe (int) |
| paragraphsCount | int | A bekezdések száma (int) |
| options | [ITextToHtmlConversionOptions](../../com.aspose.slides/itexttohtmlconversionoptions) | Átalakítási beállítások [ITextToHtmlConversionOptions](../../com.aspose.slides/itexttohtmlconversionoptions) |

**Visszatér:**
java.lang.String - Generált HTML.