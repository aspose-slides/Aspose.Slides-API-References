---
title: ParagraphCollection
second_title: Aspose.Slides pro Java – reference API
description: Představuje kolekci odstavců.
type: docs
url: /cs/com.aspose.slides/paragraphcollection/
---
**Inheritance:**
java.lang.Object, com.aspose.slides.DomObject

**All Implemented Interfaces:**
[com.aspose.slides.IParagraphCollection](../../com.aspose.slides/iparagraphcollection)
```
public final class ParagraphCollection extends DomObject<TextFrame> implements IParagraphCollection
```

Representuje kolekci odstavců.
## Methods

| Method | Description |
| --- | --- |
| [getCount()](#getCount--) | Získá počet skutečně obsažených prvků v kolekci. |
| [isReadOnly()](#isReadOnly--) | Získá hodnotu určující, zda je [IGenericCollection](../../com.aspose.slides/igenericcollection) jen pro čtení. |
| [get_Item(int index)](#get-Item-int-) | Získá prvek na zadaném indexu. |
| [add(IParagraph value)](#add-com.aspose.slides.IParagraph-) | Přidá Paragraph na konec kolekce. |
| [add(IParagraphCollection value)](#add-com.aspose.slides.IParagraphCollection-) | Přidá obsah ParagraphCollection na konec kolekce. |
| [indexOf(IParagraph item)](#indexOf-com.aspose.slides.IParagraph-) | Určí index konkrétní položky v Listu. |
| [insert(int index, IParagraph value)](#insert-int-com.aspose.slides.IParagraph-) | Vloží Paragraph do kolekce na zadaném indexu. |
| [insert(int index, IParagraphCollection value)](#insert-int-com.aspose.slides.IParagraphCollection-) | Vloží obsah ParagraphCollection do kolekce na zadaném indexu. |
| [clear()](#clear--) | Odstraní všechny prvky z kolekce. |
| [contains(IParagraph item)](#contains-com.aspose.slides.IParagraph-) | Určí, zda [IGenericCollection](../../com.aspose.slides/igenericcollection) obsahuje konkrétní hodnotu. |
| [copyTo(IParagraph[] array, int arrayIndex)](#copyTo-com.aspose.slides.IParagraph---int-) | Zkopíruje prvky [IGenericCollection](../../com.aspose.slides/igenericcollection) do pole, počínaje určitým indexem pole. |
| [removeAt(int index)](#removeAt-int-) | Odstraní prvek na zadaném indexu v kolekci. |
| [remove(IParagraph item)](#remove-com.aspose.slides.IParagraph-) | Odstraní první výskyt konkrétního objektu z [IGenericCollection](../../com.aspose.slides/igenericcollection). |
| [iterator()](#iterator--) | Vrátí enumerátor, který prochází kolekcí. |
| [iteratorJava()](#iteratorJava--) | Vrátí java iterátor pro celou kolekci. |
| [getSlide()](#getSlide--) | Vrátí nadřazený slide kolekce odstavců. |
| [getPresentation()](#getPresentation--) | Vrátí nadřazenou prezentaci kolekce odstavců. |
| [addFromHtml(String text)](#addFromHtml-java.lang.String-) | Přidá text z určeného řetězce HTML do kolekce. |
| [addFromHtml(String text, IExternalResourceResolver resolver, String uri)](#addFromHtml-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-) | Přidá text z určeného řetězce HTML do kolekce. |
| [exportToHtml(int firstParagraphIndex, int paragraphsCount, ITextToHtmlConversionOptions options)](#exportToHtml-int-int-com.aspose.slides.ITextToHtmlConversionOptions-) | Převede určené odstavce do HTML a vrátí jej jako objekt String. |
### getCount() {#getCount--}
```
public final int getCount()
```

Získá počet skutečně obsažených prvků v kolekci. Read-only int.

**Vrací:**
int
### isReadOnly() {#isReadOnly--}
```
public final boolean isReadOnly()
```

Získá hodnotu určující, zda je [IGenericCollection](../../com.aspose.slides/igenericcollection) jen pro čtení. Read-only boolean.

**Vrací:**
boolean - true pokud je [IGenericCollection](../../com.aspose.slides/igenericcollection) jen pro čtení; jinak false.
### get_Item(int index) {#get-Item-int-}
```
public final IParagraph get_Item(int index)
```

Získá prvek na zadaném indexu.

**Parameters:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| index | int |  |

**Vrací:**
[IParagraph](../../com.aspose.slides/iparagraph)
### add(IParagraph value) {#add-com.aspose.slides.IParagraph-}
```
public final void add(IParagraph value)
```

Přidá Paragraph na konec kolekce.

**Parameters:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | [IParagraph](../../com.aspose.slides/iparagraph) | Paragraph, který bude přidán na konec kolekce. |
### add(IParagraphCollection value) {#add-com.aspose.slides.IParagraphCollection-}
```
public final int add(IParagraphCollection value)
```

Přidá obsah ParagraphCollection na konec kolekce.

**Parameters:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | [IParagraphCollection](../../com.aspose.slides/iparagraphcollection) | ParagraphCollection, který bude přidán na konec kolekce. |

**Vrací:**
int - Index, na který byl Paragraph přidán, nebo -1 pokud není co přidat.
### indexOf(IParagraph item) {#indexOf-com.aspose.slides.IParagraph-}
```
public final int indexOf(IParagraph item)
```

Určí index konkrétní položky v Listu.

**Parameters:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| item | [IParagraph](../../com.aspose.slides/iparagraph) | Objekt, který má být nalezen v Listu. |

**Vrací:**
int - Index položky, pokud je nalezena v seznamu; jinak -1.
### insert(int index, IParagraph value) {#insert-int-com.aspose.slides.IParagraph-}
```
public final void insert(int index, IParagraph value)
```

Vloží Paragraph do kolekce na zadaném indexu.

**Parameters:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| index | int | Index založený na nule, na který má být Paragraph vložen. |
| value | [IParagraph](../../com.aspose.slides/iparagraph) | Paragraph, který se vloží. |
### insert(int index, IParagraphCollection value) {#insert-int-com.aspose.slides.IParagraphCollection-}
```
public final void insert(int index, IParagraphCollection value)
```

Vloží obsah ParagraphCollection do kolekce na zadaném indexu.

**Parameters:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| index | int | Nulový index, na který mají být odstavce vloženy. |
| value | [IParagraphCollection](../../com.aspose.slides/iparagraphcollection) | Odstavce, které se vloží. |
### clear() {#clear--}
```
public final void clear()
```

Odstraní všechny prvky z kolekce.
### contains(IParagraph item) {#contains-com.aspose.slides.IParagraph-}
```
public final boolean contains(IParagraph item)
```

Určí, zda [IGenericCollection](../../com.aspose.slides/igenericcollection) obsahuje konkrétní hodnotu.

**Parameters:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| item | [IParagraph](../../com.aspose.slides/iparagraph) | Objekt, který má být nalezen v [IGenericCollection](../../com.aspose.slides/igenericcollection). |

**Vrací:**
boolean - true pokud je položka nalezena v [IGenericCollection](../../com.aspose.slides/igenericcollection); jinak false.
### copyTo(IParagraph[] array, int arrayIndex) {#copyTo-com.aspose.slides.IParagraph---int-}
```
public final void copyTo(IParagraph[] array, int arrayIndex)
```

Zkopíruje prvky [IGenericCollection](../../com.aspose.slides/igenericcollection) do pole, počínaje určitým indexem pole.

**Parameters:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| array | [IParagraph\[\]](../../com.aspose.slides/iparagraph) | Jednorozměrné pole, které je cílem pro zkopírované prvky z [IGenericCollection](../../com.aspose.slides/igenericcollection). Pole musí mít indexování od nuly. |
| arrayIndex | int | Nulový index v poli, od kterého začíná kopírování. |
### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

Odstraní prvek na zadaném indexu v kolekci.

**Parameters:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| index | int | Nulový index prvku, který má být odstraněn. |
### remove(IParagraph item) {#remove-com.aspose.slides.IParagraph-}
```
public final boolean remove(IParagraph item)
```

Odstraní první výskyt konkrétního objektu z [IGenericCollection](../../com.aspose.slides/igenericcollection).

**Parameters:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| item | [IParagraph](../../com.aspose.slides/iparagraph) | Objekt, který má být odstraněn z [IGenericCollection](../../com.aspose.slides/igenericcollection). |

**Vrací:**
boolean - true pokud byl objekt úspěšně odstraněn z [IGenericCollection](../../com.aspose.slides/igenericcollection); jinak false. Tato metoda také vrací false, pokud objekt není nalezen v původním [IGenericCollection](../../com.aspose.slides/igenericcollection).
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IParagraph> iterator()
```

Vrátí enumerátor, který prochází kolekcí.

**Vrací:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IParagraph> - IGenericEnumerator, který lze použít k iteraci přes kolekci.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IParagraph> iteratorJava()
```

Vrátí java iterátor pro celou kolekci.

**Vrací:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IParagraph> - java.util.Iterator pro celou kolekci.
### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

Vrátí nadřazený slide kolekce odstavců. Read-only [BaseSlide](../../com.aspose.slides/baseslide).

**Vrací:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)
### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

Vrátí nadřazenou prezentaci kolekce odstavců. Read-only [IPresentation](../../com.aspose.slides/ipresentation).

**Vrací:**
[IPresentation](../../com.aspose.slides/ipresentation)
### addFromHtml(String text) {#addFromHtml-java.lang.String-}
```
public final void addFromHtml(String text)
```

Přidá text z určeného řetězce HTML do kolekce.

**Parameters:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| text | java.lang.String | HTML text. |
### addFromHtml(String text, IExternalResourceResolver resolver, String uri) {#addFromHtml-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-}
```
public final void addFromHtml(String text, IExternalResourceResolver resolver, String uri)
```

Přidá text z určeného řetězce HTML do kolekce.

**Parameters:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| text | java.lang.String | HTML text. |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | Callback objekt resolveru, který řeší URI a načítá odkazované objekty. |
| uri | java.lang.String | URI pro přidání HTML dokumentu. Používá se k řešení relativních odkazů.

--------------------

Specifikace resolveru může potenciálně představovat zranitelnost. Používejte opatrně. |
### exportToHtml(int firstParagraphIndex, int paragraphsCount, ITextToHtmlConversionOptions options) {#exportToHtml-int-int-com.aspose.slides.ITextToHtmlConversionOptions-}
```
public final String exportToHtml(int firstParagraphIndex, int paragraphsCount, ITextToHtmlConversionOptions options)
```

Převede určené odstavce do HTML a vrátí jej jako objekt String.

**Parameters:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| firstParagraphIndex | int | Index prvního odstavce (int) |
| paragraphsCount | int | Počet odstavců (int) |
| options | [ITextToHtmlConversionOptions](../../com.aspose.slides/itexttohtmlconversionoptions) | Možnosti převodu [ITextToHtmlConversionOptions](../../com.aspose.slides/itexttohtmlconversionoptions) |

**Vrací:**
java.lang.String - Vygenerované HTML.