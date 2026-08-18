---
title: IParagraphCollection
second_title: Referencja API Aspose.Slides dla Java
description: Reprezentuje kolekcję akapitów.
type: docs
url: /pl/com.aspose.slides/iparagraphcollection/
---
**All Implemented Interfaces:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable, [com.aspose.slides.ISlideComponent](../../com.aspose.slides/islidecomponent)
```
public interface IParagraphCollection extends System.Collections.Generic.IGenericEnumerable<IParagraph>, ISlideComponent
```

Reprezentuje kolekcję akapitów.
## Metody

| Metoda | Opis |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Pobiera element pod wskazanym indeksem. |
| [getCount()](#getCount--) | Pobiera liczbę elementów rzeczywiście znajdujących się w kolekcji. |
| [add(IParagraph value)](#add-com.aspose.slides.IParagraph-) | Adds a Paragraph to the end of collection. |
| [add(IParagraphCollection value)](#add-com.aspose.slides.IParagraphCollection-) | Adds a content of ParagraphCollection to the end of collection. |
| [insert(int index, IParagraph value)](#insert-int-com.aspose.slides.IParagraph-) | Inserts a Paragraph into the collection at the specified index. |
| [insert(int index, IParagraphCollection value)](#insert-int-com.aspose.slides.IParagraphCollection-) | Inserts a content of ParagraphCollection into the collection at the specified index. |
| [clear()](#clear--) | Usuwa wszystkie elementy z kolekcji. |
| [removeAt(int index)](#removeAt-int-) | Usuwa element pod wskazanym indeksem w kolekcji. |
| [remove(IParagraph item)](#remove-com.aspose.slides.IParagraph-) | Usuwa pierwsze wystąpienie określonego akapitu. |
| [addFromHtml(String text)](#addFromHtml-java.lang.String-) | Dodaje tekst z określonego łańcucha HTML do kolekcji. |
| [addFromHtml(String text, IExternalResourceResolver resolver, String uri)](#addFromHtml-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-) | Dodaje tekst z określonego łańcucha HTML do kolekcji. |
| [exportToHtml(int firstParagraphIndex, int paragraphsCount, ITextToHtmlConversionOptions options)](#exportToHtml-int-int-com.aspose.slides.ITextToHtmlConversionOptions-) | Konwertuje określone akapity do HTML i zwraca je jako obiekt typu String. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IParagraph get_Item(int index)
```

Pobiera element pod wskazanym indeksem.

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

Pobiera liczbę elementów rzeczywiście znajdujących się w kolekcji. tylko do odczytu int.

**Zwraca:**
int
### add(IParagraph value) {#add-com.aspose.slides.IParagraph-}
```
public abstract void add(IParagraph value)
```

Adds a Paragraph to the end of collection.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | [IParagraph](../../com.aspose.slides/iparagraph) | The Paragraph to be added to the end of the collection. |

### add(IParagraphCollection value) {#add-com.aspose.slides.IParagraphCollection-}
```
public abstract int add(IParagraphCollection value)
```

Adds a content of ParagraphCollection to the end of collection.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | [IParagraphCollection](../../com.aspose.slides/iparagraphcollection) | The ParagraphCollection to be added to the end of the collection. |

**Zwraca:**
int - Indeks, pod którym został dodany Paragraph lub -1, jeśli nie ma nic do dodania.
### insert(int index, IParagraph value) {#insert-int-com.aspose.slides.IParagraph-}
```
public abstract void insert(int index, IParagraph value)
```

Inserts a Paragraph into the collection at the specified index.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| index | int | The zero-based index at which Paragraph should be inserted. |
| value | [IParagraph](../../com.aspose.slides/iparagraph) | The Paragraph to insert. |

### insert(int index, IParagraphCollection value) {#insert-int-com.aspose.slides.IParagraphCollection-}
```
public abstract void insert(int index, IParagraphCollection value)
```

Inserts a content of ParagraphCollection into the collection at the specified index.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| index | int | Zero-bazowy indeks, pod którym należy wstawić akapity. |
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

Usuwa element pod wskazanym indeksem w kolekcji.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| index | int | The zero-based index of the element to remove. |

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
boolean - true, jeśli item został pomyślnie usunięty; w przeciwnym razie false.
### addFromHtml(String text) {#addFromHtml-java.lang.String-}
```
public abstract void addFromHtml(String text)
```

Adds text from specified html string to the collection.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| text | java.lang.String | tekst HTML. |

### addFromHtml(String text, IExternalResourceResolver resolver, String uri) {#addFromHtml-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-}
```
public abstract void addFromHtml(String text, IExternalResourceResolver resolver, String uri)
```

Adds text from specified html string to the collection.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| text | java.lang.String | tekst HTML. |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | Resolver callback object which resolves URIs and fetches referrenced objects. |
| uri | java.lang.String | URI for adding HTML document. Used for resolving relative links. |

Określenie resolvera może potencjalnie wprowadzić lukę bezpieczeństwa. Use with caution. |
### exportToHtml(int firstParagraphIndex, int paragraphsCount, ITextToHtmlConversionOptions options) {#exportToHtml-int-int-com.aspose.slides.ITextToHtmlConversionOptions-}
```
public abstract String exportToHtml(int firstParagraphIndex, int paragraphsCount, ITextToHtmlConversionOptions options)
```

Converts specifying paragraphs to the HTML and returns it as String object.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| firstParagraphIndex | int | Indeks pierwszego akapitu int |
| paragraphsCount | int | Liczba akapitów int |
| options | [ITextToHtmlConversionOptions](../../com.aspose.slides/itexttohtmlconversionoptions) | Convert options [ITextToHtmlConversionOptions](../../com.aspose.slides/itexttohtmlconversionoptions) |

**Zwraca:**
java.lang.String - Wygenerowany HTML.