---
title: ParagraphCollection
second_title: Aspose.Slides pro Android prostřednictvím reference Java API
description: Representuje kolekci odstavců.
type: docs
url: /cs/com.aspose.slides/paragraphcollection/
---
**Dědičnost:**
java.lang.Object, com.aspose.slides.DomObject

**Všechny implementované rozhraní:**
[com.aspose.slides.IParagraphCollection](../../com.aspose.slides/iparagraphcollection)
```
public final class ParagraphCollection extends DomObject<TextFrame> implements IParagraphCollection
```

Represents a collection of a paragraphs.
## Metody

| Metoda | Popis |
| --- | --- |
| [getCount()](#getCount--) | Získává počet prvků skutečně obsažených v kolekci. |
| [isReadOnly()](#isReadOnly--) | Získává hodnotu indikující, zda je [IGenericCollection](../../com.aspose.slides/igenericcollection) pouze pro čtení. |
| [get_Item(int index)](#get-Item-int-) | Získává prvek na zadaném indexu. |
| [add(IParagraph value)](#add-com.aspose.slides.IParagraph-) | Přidá Paragraph na konec kolekce. |
| [add(IParagraphCollection value)](#add-com.aspose.slides.IParagraphCollection-) | Přidá obsah ParagraphCollection na konec kolekce. |
| [indexOf(IParagraph item)](#indexOf-com.aspose.slides.IParagraph-) | Určuje index konkrétní položky v List. |
| [insert(int index, IParagraph value)](#insert-int-com.aspose.slides.IParagraph-) | Vloží Paragraph do kolekce na zadaném indexu. |
| [insert(int index, IParagraphCollection value)](#insert-int-com.aspose.slides.IParagraphCollection-) | Vloží obsah ParagraphCollection do kolekce na zadaném indexu. |
| [clear()](#clear--) | Odstraní všechny prvky z kolekce. |
| [contains(IParagraph item)](#contains-com.aspose.slides.IParagraph-) | Určuje, zda [IGenericCollection](../../com.aspose.slides/igenericcollection) obsahuje konkrétní hodnotu. |
| [copyTo(IParagraph[] array, int arrayIndex)](#copyTo-com.aspose.slides.IParagraph---int-) | Kopíruje prvky [IGenericCollection](../../com.aspose.slides/igenericcollection) do pole, počínaje určitým indexem pole. |
| [removeAt(int index)](#removeAt-int-) | Odstraňuje prvek na zadaném indexu kolekce. |
| [remove(IParagraph item)](#remove-com.aspose.slides.IParagraph-) | Odstraňuje první výskyt konkrétního objektu z [IGenericCollection](../../com.aspose.slides/igenericcollection). |
| [iterator()](#iterator--) | Vrací enumerátor, který prochází kolekcí. |
| [iteratorJava()](#iteratorJava--) | Vrací java iterátor pro celou kolekci. |
| [getSlide()](#getSlide--) | Vrací rodičovský slide kolekce odstavců. |
| [getPresentation()](#getPresentation--) | Vrací rodičovskou prezentaci kolekce odstavců. |
| [addFromHtml(String text)](#addFromHtml-java.lang.String-) | Přidá text ze zadaného html řetězce do kolekce. |
| [addFromHtml(String text, IExternalResourceResolver resolver, String uri)](#addFromHtml-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-) | Přidá text ze zadaného html řetězce do kolekce. |
| [exportToHtml(int firstParagraphIndex, int paragraphsCount, ITextToHtmlConversionOptions options)](#exportToHtml-int-int-com.aspose.slides.ITextToHtmlConversionOptions-) | Převádí určené odstavce do HTML a vrací jej jako objekt typu String. |

### getCount() {#getCount--}
```
public final int getCount()
```

Získává počet prvků skutečně obsažených v kolekci. Pouze pro čtení int.

**Vrací:**
int

### isReadOnly() {#isReadOnly--}
```
public final boolean isReadOnly()
```

Získává hodnotu indikující, zda je [IGenericCollection](../../com.aspose.slides/igenericcollection) pouze pro čtení. Pouze pro čtení boolean.

**Vrací:**
boolean – true, pokud je [IGenericCollection](../../com.aspose.slides/igenericcollection) pouze pro čtení; jinak false.

### get_Item(int index) {#get-Item-int-}
```
public final IParagraph get_Item(int index)
```

Získává prvek na zadaném indexu.

**Parametry:**
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

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | [IParagraph](../../com.aspose.slides/iparagraph) | Paragraph, který má být přidán na konec kolekce. |

### add(IParagraphCollection value) {#add-com.aspose.slides.IParagraphCollection-}
```
public final int add(IParagraphCollection value)
```

Přidá obsah ParagraphCollection na konec kolekce.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | [IParagraphCollection](../../com.aspose.slides/iparagraphcollection) | ParagraphCollection, který má být přidán na konec kolekce. |

**Vrací:**
int – Index, na který byl Paragraph přidán, nebo -1, pokud není nic k přidání.

### indexOf(IParagraph item) {#indexOf-com.aspose.slides.IParagraph-}
```
public final int indexOf(IParagraph item)
```

Určuje index konkrétní položky v List.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| item | [IParagraph](../../com.aspose.slides/iparagraph) | Objekt, který se má najít v List. |

**Vrací:**
int – Index položky, pokud je v listu nalezena; jinak -1.

### insert(int index, IParagraph value) {#insert-int-com.aspose.slides.IParagraph-}
```
public final void insert(int index, IParagraph value)
```

Vloží Paragraph do kolekce na zadaném indexu.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| index | int | Nulově založený index, na který má být Paragraph vložen. |
| value | [IParagraph](../../com.aspose.slides/iparagraph) | Paragraph, který má být vložen. |

### insert(int index, IParagraphCollection value) {#insert-int-com.aspose.slides.IParagraphCollection-}
```
public final void insert(int index, IParagraphCollection value)
```

Vloží obsah ParagraphCollection do kolekce na zadaném indexu.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| index | int | Nulově založený index, na který mají být odstavce vloženy. |
| value | [IParagraphCollection](../../com.aspose.slides/iparagraphcollection) | Odstavce, které mají být vloženy. |

### clear() {#clear--}
```
public final void clear()
```

Odstraní všechny prvky z kolekce.

### contains(IParagraph item) {#contains-com.aspose.slides.IParagraph-}
```
public final boolean contains(IParagraph item)
```

Určuje, zda [IGenericCollection](../../com.aspose.slides/igenericcollection) obsahuje konkrétní hodnotu.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| item | [IParagraph](../../com.aspose.slides/iparagraph) | Objekt, který se má najít v [IGenericCollection](../../com.aspose.slides/igenericcollection). |

**Vrací:**
boolean – true, pokud je položka nalezena v [IGenericCollection](../../com.aspose.slides/igenericcollection); jinak false.

### copyTo(IParagraph[] array, int arrayIndex) {#copyTo-com.aspose.slides.IParagraph---int-}
```
public final void copyTo(IParagraph[] array, int arrayIndex)
```

Kopíruje prvky [IGenericCollection](../../com.aspose.slides/igenericcollection) do pole, počínaje určitým indexem pole.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| array | [IParagraph\[\]](../../com.aspose.slides/iparagraph) | Jednorozměrné pole, kam jsou kopírovány prvky z [IGenericCollection](../../com.aspose.slides/igenericcollection). Pole musí mít nulové indexování. |
| arrayIndex | int | Nulově založený index v poli, kde začíná kopírování. |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

Odstraňuje prvek na zadaném indexu kolekce.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| index | int | Nulově založený index prvku, který má být odstraněn. |

### remove(IParagraph item) {#remove-com.aspose.slides.IParagraph-}
```
public final boolean remove(IParagraph item)
```

Odstraňuje první výskyt konkrétního objektu z [IGenericCollection](../../com.aspose.slides/igenericcollection).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| item | [IParagraph](../../com.aspose.slides/iparagraph) | Objekt, který má být odstraněn z [IGenericCollection](../../com.aspose.slides/igenericcollection). |

**Vrací:**
boolean – true, pokud byla položka úspěšně odstraněna z [IGenericCollection](../../com.aspose.slides/igenericcollection); jinak false. Tato metoda také vrací false, pokud položka není v původním [IGenericCollection](../../com.aspose.slides/igenericcollection) nalezena.

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IParagraph> iterator()
```

Vrací enumerátor, který prochází kolekcí.

**Vrací:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IParagraph> - A IGenericEnumerator that can be used to iterate through the collection.

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IParagraph> iteratorJava()
```

Vrací java iterátor pro celou kolekci.

**Vrací:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IParagraph> - An java.util.Iterator for the entire collection.

### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

Vrací rodičovský slide kolekce odstavců. Pouze pro čtení [BaseSlide](../../com.aspose.slides/baseslide).

**Vrací:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)

### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

Vrací rodičovskou prezentaci kolekce odstavců. Pouze pro čtení [IPresentation](../../com.aspose.slides/ipresentation).

**Vrací:**
[IPresentation](../../com.aspose.slides/ipresentation)

### addFromHtml(String text) {#addFromHtml-java.lang.String-}
```
public final void addFromHtml(String text)
```

Přidá text ze zadaného html řetězce do kolekce.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| text | java.lang.String | HTML text. |

### addFromHtml(String text, IExternalResourceResolver resolver, String uri) {#addFromHtml-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-}
```
public final void addFromHtml(String text, IExternalResourceResolver resolver, String uri)
```

Přidá text ze zadaného html řetězce do kolekce.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| text | java.lang.String | HTML text. |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | Callback objekt resolveru, který řeší URI a načítá odkazované objekty. |
| uri | java.lang.String | URI pro přidání HTML dokumentu. Používá se k řešení relativních odkazů. |

Specifikace resolveru může potenciálně představovat zranitelnost. Používejte s opatrností. |
--------------------

### exportToHtml(int firstParagraphIndex, int paragraphsCount, ITextToHtmlConversionOptions options) {#exportToHtml-int-int-com.aspose.slides.ITextToHtmlConversionOptions-}
```
public final String exportToHtml(int firstParagraphIndex, int paragraphsCount, ITextToHtmlConversionOptions options)
```

Převádí určené odstavce do HTML a vrací jej jako objekt typu String.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| firstParagraphIndex | int | Index prvního odstavce int |
| paragraphsCount | int | Počet odstavců int |
| options | [ITextToHtmlConversionOptions](../../com.aspose.slides/itexttohtmlconversionoptions) | Možnosti převodu [ITextToHtmlConversionOptions](../../com.aspose.slides/itexttohtmlconversionoptions) |

**Vrací:**
java.lang.String – Vygenerované HTML.