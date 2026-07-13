---
title: ParagraphCollection
second_title: Aspose.Slides dla Androida - odniesienie API Java
description: Reprezentuje kolekcję akapitów.
type: docs
url: /pl/com.aspose.slides/paragraphcollection/
---
**Dziedziczenie:**  
java.lang.Object, com.aspose.slides.DomObject

**Wszystkie zaimplementowane interfejsy:**  
[com.aspose.slides.IParagraphCollection](../../com.aspose.slides/iparagraphcollection)  
```
public final class ParagraphCollection extends DomObject<TextFrame> implements IParagraphCollection
```

Reprezentuje kolekcję akapitów.

## Metody

| Metoda | Opis |
| --- | --- |
| [getCount()](#getCount--) | Zwraca liczbę elementów faktycznie zawartych w kolekcji. |
| [isReadOnly()](#isReadOnly--) | Zwraca wartość wskazującą, czy [IGenericCollection](../../com.aspose.slides/igenericcollection) jest tylko do odczytu. |
| [get_Item(int index)](#get-Item-int-) | Zwraca element o podanym indeksie. |
| [add(IParagraph value)](#add-com.aspose.slides.IParagraph-) | Dodaje Paragraph na koniec kolekcji. |
| [add(IParagraphCollection value)](#add-com.aspose.slides.IParagraphCollection-) | Dodaje zawartość ParagraphCollection na koniec kolekcji. |
| [indexOf(IParagraph item)](#indexOf-com.aspose.slides.IParagraph-) | Określa indeks konkretnego elementu w liście. |
| [insert(int index, IParagraph value)](#insert-int-com.aspose.slides.IParagraph-) | Wstawia Paragraph do kolekcji pod podanym indeksem. |
| [insert(int index, IParagraphCollection value)](#insert-int-com.aspose.slides.IParagraphCollection-) | Wstawia zawartość ParagraphCollection do kolekcji pod podanym indeksem. |
| [clear()](#clear--) | Usuwa wszystkie elementy z kolekcji. |
| [contains(IParagraph item)](#contains-com.aspose.slides.IParagraph-) | Określa, czy [IGenericCollection](../../com.aspose.slides/igenericcollection) zawiera określoną wartość. |
| [copyTo(IParagraph[] array, int arrayIndex)](#copyTo-com.aspose.slides.IParagraph---int-) | Kopiuje elementy [IGenericCollection](../../com.aspose.slides/igenericcollection) do tablicy, zaczynając od określonego indeksu tablicy. |
| [removeAt(int index)](#removeAt-int-) | Usuwa element o podanym indeksie z kolekcji. |
| [remove(IParagraph item)](#remove-com.aspose.slides.IParagraph-) | Usuwa pierwsze wystąpienie określonego obiektu z [IGenericCollection](../../com.aspose.slides/igenericcollection). |
| [iterator()](#iterator--) | Zwraca enumerator, który iteruje po kolekcji. |
| [iteratorJava()](#iteratorJava--) | Zwraca iterator języka Java dla całej kolekcji. |
| [getSlide()](#getSlide--) | Zwraca slajd-nadrzędny kolekcji akapitów. |
| [getPresentation()](#getPresentation--) | Zwraca prezentację-nadrzędną kolekcji akapitów. |
| [addFromHtml(String text)](#addFromHtml-java.lang.String-) | Dodaje tekst z podanego łańcucha HTML do kolekcji. |
| [addFromHtml(String text, IExternalResourceResolver resolver, String uri)](#addFromHtml-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-) | Dodaje tekst z podanego łańcucha HTML do kolekcji. |
| [exportToHtml(int firstParagraphIndex, int paragraphsCount, ITextToHtmlConversionOptions options)](#exportToHtml-int-int-com.aspose.slides.ITextToHtmlConversionOptions-) | Konwertuje określone akapity na HTML i zwraca go jako obiekt String. |

### getCount() {#getCount--}
```
public final int getCount()
```

Zwraca liczbę elementów faktycznie zawartych w kolekcji. Tylko do odczytu int.

**Zwraca:**  
int

### isReadOnly() {#isReadOnly--}
```
public final boolean isReadOnly()
```

Zwraca wartość wskazującą, czy [IGenericCollection](../../com.aspose.slides/igenericcollection) jest tylko do odczytu. Tylko do odczytu boolean.

**Zwraca:**  
boolean - true jeśli [IGenericCollection](../../com.aspose.slides/igenericcollection) jest tylko do odczytu; w przeciwnym razie false.

### get_Item(int index) {#get-Item-int-}
```
public final IParagraph get_Item(int index)
```

Zwraca element o podanym indeksie.

**Parametry:**  
| Parametr | Typ | Opis |
| --- | --- | --- |
| index | int |  |

**Zwraca:**  
[IParagraph](../../com.aspose.slides/iparagraph)

### add(IParagraph value) {#add-com.aspose.slides.IParagraph-}
```
public final void add(IParagraph value)
```

Dodaje Paragraph na koniec kolekcji.

**Parametry:**  
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | [IParagraph](../../com.aspose.slides/iparagraph) | Paragraph, który ma zostać dodany na koniec kolekcji. |

### add(IParagraphCollection value) {#add-com.aspose.slides.IParagraphCollection-}
```
public final int add(IParagraphCollection value)
```

Dodaje zawartość ParagraphCollection na koniec kolekcji.

**Parametry:**  
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | [IParagraphCollection](../../com.aspose.slides/iparagraphcollection) | ParagraphCollection, który ma zostać dodany na koniec kolekcji. |

**Zwraca:**  
int - Indeks, pod którym Paragraph został dodany lub -1, jeśli nie ma nic do dodania.

### indexOf(IParagraph item) {#indexOf-com.aspose.slides.IParagraph-}
```
public final int indexOf(IParagraph item)
```

Określa indeks określonego elementu w liście.

**Parametry:**  
| Parametr | Typ | Opis |
| --- | --- | --- |
| item | [IParagraph](../../com.aspose.slides/iparagraph) | Obiekt do zlokalizowania w liście. |

**Zwraca:**  
int - Indeks elementu, jeśli został znaleziony na liście; w przeciwnym razie -1.

### insert(int index, IParagraph value) {#insert-int-com.aspose.slides.IParagraph-}
```
public final void insert(int index, IParagraph value)
```

Wstawia Paragraph do kolekcji pod podanym indeksem.

**Parametry:**  
| Parametr | Typ | Opis |
| --- | --- | --- |
| index | int | Indeks zerowy, pod którym Paragraph ma być wstawiony. |
| value | [IParagraph](../../com.aspose.slides/iparagraph) | Paragraph do wstawienia. |

### insert(int index, IParagraphCollection value) {#insert-int-com.aspose.slides.IParagraphCollection-}
```
public final void insert(int index, IParagraphCollection value)
```

Wstawia zawartość ParagraphCollection do kolekcji pod podanym indeksem.

**Parametry:**  
| Parametr | Typ | Opis |
| --- | --- | --- |
| index | int | Indeks zerowy, pod którym akapity mają być wstawione. |
| value | [IParagraphCollection](../../com.aspose.slides/iparagraphcollection) | Akapity do wstawienia. |

### clear() {#clear--}
```
public final void clear()
```

Usuwa wszystkie elementy z kolekcji.

### contains(IParagraph item) {#contains-com.aspose.slides.IParagraph-}
```
public final boolean contains(IParagraph item)
```

Określa, czy [IGenericCollection](../../com.aspose.slides/igenericcollection) zawiera określoną wartość.

**Parametry:**  
| Parametr | Typ | Opis |
| --- | --- | --- |
| item | [IParagraph](../../com.aspose.slides/iparagraph) | Obiekt do zlokalizowania w [IGenericCollection](../../com.aspose.slides/igenericcollection). |

**Zwraca:**  
boolean - true jeśli element zostanie znaleziony w [IGenericCollection](../../com.aspose.slides/igenericcollection); w przeciwnym razie false.

### copyTo(IParagraph[] array, int arrayIndex) {#copyTo-com.aspose.slides.IParagraph---int-}
```
public final void copyTo(IParagraph[] array, int arrayIndex)
```

Kopiuje elementy [IGenericCollection](../../com.aspose.slides/igenericcollection) do tablicy, zaczynając od określonego indeksu tablicy.

**Parametry:**  
| Parametr | Typ | Opis |
| --- | --- | --- |
| array | [IParagraph\[\]](../../com.aspose.slides/iparagraph) | Jednowymiarowa tablica będąca celem elementów kopiowanych z [IGenericCollection](../../com.aspose.slides/igenericcollection). Tablica musi mieć indeksowanie zerowe. |
| arrayIndex | int | Indeks zerowy w tablicy, od którego rozpoczyna się kopiowanie. |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

Usuwa element o podanym indeksie z kolekcji.

**Parametry:**  
| Parametr | Typ | Opis |
| --- | --- | --- |
| index | int | Indeks zerowy elementu do usunięcia. |

### remove(IParagraph item) {#remove-com.aspose.slides.IParagraph-}
```
public final boolean remove(IParagraph item)
```

Usuwa pierwsze wystąpienie określonego obiektu z [IGenericCollection](../../com.aspose.slides/igenericcollection).

**Parametry:**  
| Parametr | Typ | Opis |
| --- | --- | --- |
| item | [IParagraph](../../com.aspose.slides/iparagraph) | Obiekt do usunięcia z [IGenericCollection](../../com.aspose.slides/igenericcollection). |

**Zwraca:**  
boolean - true jeśli element został pomyślnie usunięty z [IGenericCollection](../../com.aspose.slides/igenericcollection); w przeciwnym razie false. Metoda również zwraca false, jeśli element nie został znaleziony w oryginalnym [IGenericCollection](../../com.aspose.slides/igenericcollection).

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IParagraph> iterator()
```

Zwraca enumerator, który iteruje po kolekcji.

**Zwraca:**  
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IParagraph> - IGenericEnumerator, który można używać do iteracji po kolekcji.

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IParagraph> iteratorJava()
```

Zwraca iterator języka Java dla całej kolekcji.

**Zwraca:**  
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IParagraph> - java.util.Iterator dla całej kolekcji.

### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

Zwraca slajd-nadrzędny kolekcji akapitów. Tylko do odczytu [BaseSlide](../../com.aspose.slides/baseslide).

**Zwraca:**  
[IBaseSlide](../../com.aspose.slides/ibaseslide)

### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

Zwraca prezentację-nadrzędną kolekcji akapitów. Tylko do odczytu [IPresentation](../../com.aspose.slides/ipresentation).

**Zwraca:**  
[IPresentation](../../com.aspose.slides/ipresentation)

### addFromHtml(String text) {#addFromHtml-java.lang.String-}
```
public final void addFromHtml(String text)
```

Dodaje tekst z podanego łańcucha HTML do kolekcji.

**Parametry:**  
| Parametr | Typ | Opis |
| --- | --- | --- |
| text | java.lang.String | Tekst HTML. |

### addFromHtml(String text, IExternalResourceResolver resolver, String uri) {#addFromHtml-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-}
```
public final void addFromHtml(String text, IExternalResourceResolver resolver, String uri)
```

Dodaje tekst z podanego łańcucha HTML do kolekcji.

**Parametry:**  
| Parametr | Typ | Opis |
| --- | --- | --- |
| text | java.lang.String | Tekst HTML. |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | Obiekt zwrotnego wywołania resolvera, który rozwiązuje URI i pobiera odwoływane obiekty. |
| uri | java.lang.String | URI do dodania dokumentu HTML. Używane do rozwiązywania względnych linków. |

--------------------
Określenie resolvera może potencjalnie wprowadzić podatność. Używać ostrożnie. |

### exportToHtml(int firstParagraphIndex, int paragraphsCount, ITextToHtmlConversionOptions options) {#exportToHtml-int-int-com.aspose.slides.ITextToHtmlConversionOptions-}
```
public final String exportToHtml(int firstParagraphIndex, int paragraphsCount, ITextToHtmlConversionOptions options)
```

Konwertuje określone akapity na HTML i zwraca je jako obiekt String.

**Parametry:**  
| Parametr | Typ | Opis |
| --- | --- | --- |
| firstParagraphIndex | int | Indeks pierwszego akapitu int |
| paragraphsCount | int | Liczba akapitów int |
| options | [ITextToHtmlConversionOptions](../../com.aspose.slides/itexttohtmlconversionoptions) | Opcje konwersji [ITextToHtmlConversionOptions](../../com.aspose.slides/itexttohtmlconversionoptions) |

**Zwraca:**  
java.lang.String - Wygenerowany HTML.