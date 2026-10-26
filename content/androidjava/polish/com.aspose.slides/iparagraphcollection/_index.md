---
title: IParagraphCollection
second_title: Aspose.Slides dla Androida - odniesienie API Java
description: Reprezentuje kolekcję akapitów.
type: docs
url: /pl/com.aspose.slides/iparagraphcollection/
---
**Wszystkie zaimplementowane interfejsy:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable, [com.aspose.slides.ISlideComponent](../../com.aspose.slides/islidecomponent)
```
public interface IParagraphCollection extends System.Collections.Generic.IGenericEnumerable<IParagraph>, ISlideComponent
```

Reprezentuje kolekcję akapitów.
## Metody

| Metoda | Opis |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Pobiera element pod określonym indeksem. |
| [getCount()](#getCount--) | Pobiera liczbę elementów faktycznie zawartych w kolekcji. |
| [add(IParagraph value)](#add-com.aspose.slides.IParagraph-) | Dodaje obiekt Paragraph na koniec kolekcji. |
| [add(IParagraphCollection value)](#add-com.aspose.slides.IParagraphCollection-) | Dodaje zawartość ParagraphCollection na koniec kolekcji. |
| [insert(int index, IParagraph value)](#insert-int-com.aspose.slides.IParagraph-) | Wstawia obiekt Paragraph do kolekcji pod określonym indeksem. |
| [insert(int index, IParagraphCollection value)](#insert-int-com.aspose.slides.IParagraphCollection-) | Wstawia zawartość ParagraphCollection do kolekcji pod określonym indeksem. |
| [clear()](#clear--) | Usuwa wszystkie elementy z kolekcji. |
| [removeAt(int index)](#removeAt-int-) | Usuwa element pod określonym indeksem w kolekcji. |
| [remove(IParagraph item)](#remove-com.aspose.slides.IParagraph-) | Usuwa pierwsze wystąpienie określonego akapitu. |
| [addFromHtml(String text)](#addFromHtml-java.lang.String-) | Dodaje tekst z określonego ciągu HTML do kolekcji. |
| [addFromHtml(String text, IExternalResourceResolver resolver, String uri)](#addFromHtml-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-) | Dodaje tekst z określonego ciągu HTML do kolekcji. |
| [exportToHtml(int firstParagraphIndex, int paragraphsCount, ITextToHtmlConversionOptions options)](#exportToHtml-int-int-com.aspose.slides.ITextToHtmlConversionOptions-) | Konwertuje określone akapity do HTML i zwraca je jako obiekt String. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IParagraph get_Item(int index)
```

Pobiera element pod określonym indeksem.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| index | int |  |

**Zwraca:**
[IParagraph](../../com.aspose.slides/iparagraph)
### getCount() {#getCount--}
```
public abstract int getCount()
```

Pobiera liczbę elementów faktycznie zawartych w kolekcji. int tylko do odczytu.

**Zwraca:**
int
### add(IParagraph value) {#add-com.aspose.slides.IParagraph-}
```
public abstract void add(IParagraph value)
```

Dodaje obiekt Paragraph na koniec kolekcji.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | [IParagraph](../../com.aspose.slides/iparagraph) | Obiekt Paragraph, który ma zostać dodany na koniec kolekcji. |

### add(IParagraphCollection value) {#add-com.aspose.slides.IParagraphCollection-}
```
public abstract int add(IParagraphCollection value)
```

Dodaje zawartość ParagraphCollection na koniec kolekcji.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | [IParagraphCollection](../../com.aspose.slides/iparagraphcollection) | Obiekt ParagraphCollection, który ma zostać dodany na koniec kolekcji. |

**Zwraca:**
int – indeks, pod którym został dodany obiekt Paragraph, lub -1, jeśli nie ma nic do dodania.
### insert(int index, IParagraph value) {#insert-int-com.aspose.slides.IParagraph-}
```
public abstract void insert(int index, IParagraph value)
```

Wstawia obiekt Paragraph do kolekcji pod określonym indeksem.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| index | int | Indeks oparty na zerze, pod którym ma zostać wstawiony obiekt Paragraph. |
| value | [IParagraph](../../com.aspose.slides/iparagraph) | Obiekt Paragraph do wstawienia. |

### insert(int index, IParagraphCollection value) {#insert-int-com.aspose.slides.IParagraphCollection-}
```
public abstract void insert(int index, IParagraphCollection value)
```

Wstawia zawartość ParagraphCollection do kolekcji pod określonym indeksem.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| index | int | Indeks oparty na zerze, pod którym mają zostać wstawione akapity. |
| value | [IParagraphCollection](../../com.aspose.slides/iparagraphcollection) | Akapity do wstawienia. |

### clear() {#clear--}
```
public abstract void clear()
```

Usuwa wszystkie elementy z kolekcji.

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

Usuwa element pod określonym indeksem w kolekcji.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| index | int | Indeks oparty na zerze elementu do usunięcia. |

### remove(IParagraph item) {#remove-com.aspose.slides.IParagraph-}
```
public abstract boolean remove(IParagraph item)
```

Usuwa pierwsze wystąpienie określonego akapitu.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| item | [IParagraph](../../com.aspose.slides/iparagraph) | Akapit do usunięcia z kolekcji. |

**Zwraca:**
boolean – true, jeśli element został pomyślnie usunięty; w przeciwnym razie false.
### addFromHtml(String text) {#addFromHtml-java.lang.String-}
```
public abstract void addFromHtml(String text)
```

Dodaje tekst z określonego ciągu HTML do kolekcji.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| text | java.lang.String | Tekst HTML. |

### addFromHtml(String text, IExternalResourceResolver resolver, String uri) {#addFromHtml-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-}
```
public abstract void addFromHtml(String text, IExternalResourceResolver resolver, String uri)
```

Dodaje tekst z określonego ciągu HTML do kolekcji.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| text | java.lang.String | Tekst HTML. |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | Obiekt zwrotnego wywołania resolvera, który rozwiązuje URI i pobiera odwoływane obiekty. |
| uri | java.lang.String | URI używany do dodawania dokumentu HTML. Używany do rozwiązywania linków względnych.

--------------------

Określenie resolvera może potencjalnie wprowadzić lukę bezpieczeństwa. Używać ostrożnie. |
### exportToHtml(int firstParagraphIndex, int paragraphsCount, ITextToHtmlConversionOptions options) {#exportToHtml-int-int-com.aspose.slides.ITextToHtmlConversionOptions-}
```
public abstract String exportToHtml(int firstParagraphIndex, int paragraphsCount, ITextToHtmlConversionOptions options)
```

Konwertuje określone akapity do HTML i zwraca je jako obiekt String.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| firstParagraphIndex | int | Indeks pierwszego akapitu int |
| paragraphsCount | int | Liczba akapitów int |
| options | [ITextToHtmlConversionOptions](../../com.aspose.slides/itexttohtmlconversionoptions) | Opcje konwersji [ITextToHtmlConversionOptions](../../com.aspose.slides/itexttohtmlconversionoptions) |

**Zwraca:**
java.lang.String – wygenerowany HTML.