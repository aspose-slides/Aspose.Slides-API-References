---
title: InsertFromHtml
second_title: Aspose.Sildes dla .NET – dokumentacja API
description: Tworzy slajdy z tekstu HTML i wstawia je do kolekcji w określonej pozycji.
type: docs
weight: 90
url: /pl/aspose.slides/islidecollection/insertfromhtml/
---
## InsertFromHtml(int, string, IExternalResourceResolver, string) {#insertfromhtml_7}

Tworzy slajdy z tekstu HTML i wstawia je do kolekcji w określonej pozycji.

```csharp
public ISlide[] InsertFromHtml(int index, string htmlText, IExternalResourceResolver resolver, 
    string uri)
```

| Parametr | Typ | Opis |
| --- | --- | --- |
| index | Int32 | Pozycja wstawienia. |
| htmlText | String | HTML do dodania. |
| resolver | IExternalResourceResolver | Obiekt wywołania zwrotnego używany do pobierania obiektów zewnętrznych. Jeśli ten parametr jest null, wszystkie obiekty zewnętrzne zostaną zignorowane. |
| uri | String | Adres URI określonego HTML. Używany do rozwiązywania względnych odnośników. |

### Wartość zwracana

Dodane slajdy.

### Zobacz także

* interfejs [ISlide](../../islide)
* interfejs [IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver)
* interfejs [ISlideCollection](../../islidecollection)
* przestrzeń nazw [Aspose.Slides](../../islidecollection)
* zestaw [Aspose.Slides](../../../)

---

## InsertFromHtml(int, string) {#insertfromhtml_6}

Tworzy slajdy z tekstu HTML i wstawia je do kolekcji w określonej pozycji.

```csharp
public ISlide[] InsertFromHtml(int index, string htmlText)
```

| Parametr | Typ | Opis |
| --- | --- | --- |
| index | Int32 | Pozycja wstawienia. |
| htmlText | String | HTML do dodania. |

### Wartość zwracana

Dodane slajdy

### Zobacz także

* interfejs [ISlide](../../islide)
* interfejs [ISlideCollection](../../islidecollection)
* przestrzeń nazw [Aspose.Slides](../../islidecollection)
* zestaw [Aspose.Slides](../../../)

---

## InsertFromHtml(int, TextReader, IExternalResourceResolver, string) {#insertfromhtml_5}

Tworzy slajdy z tekstu HTML i wstawia je do kolekcji w określonej pozycji.

```csharp
public ISlide[] InsertFromHtml(int index, TextReader htmlReader, 
    IExternalResourceResolver resolver, string uri)
```

| Parametr | Typ | Opis |
| --- | --- | --- |
| index | Int32 | Pozycja wstawienia. |
| htmlReader | TextReader | Obiekt TextReader, który będzie używany jako źródło pliku HTML. |
| resolver | IExternalResourceResolver | Obiekt wywołania zwrotnego używany do pobierania obiektów zewnętrznych. Jeśli ten parametr jest null, wszystkie obiekty zewnętrzne zostaną zignorowane. |
| uri | String | Adres URI określonego HTML. Używany do rozwiązywania względnych odnośników. |

### Wartość zwracana

Dodane slajdy.

### Zobacz także

* interfejs [ISlide](../../islide)
* interfejs [IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver)
* interfejs [ISlideCollection](../../islidecollection)
* przestrzeń nazw [Aspose.Slides](../../islidecollection)
* zestaw [Aspose.Slides](../../../)

---

## InsertFromHtml(int, TextReader) {#insertfromhtml_4}

Tworzy slajdy z tekstu HTML i wstawia je do kolekcji w określonej pozycji.

```csharp
public ISlide[] InsertFromHtml(int index, TextReader htmlReader)
```

| Parametr | Typ | Opis |
| --- | --- | --- |
| index | Int32 | Pozycja wstawienia. |
| htmlReader | TextReader | Obiekt TextReader, który będzie używany jako źródło pliku HTML. |

### Wartość zwracana

Dodane slajdy

### Zobacz także

* interfejs [ISlide](../../islide)
* interfejs [ISlideCollection](../../islidecollection)
* przestrzeń nazw [Aspose.Slides](../../islidecollection)
* zestaw [Aspose.Slides](../../../)

---

## InsertFromHtml(int, Stream, IExternalResourceResolver, string) {#insertfromhtml_1}

Tworzy slajdy z tekstu HTML i wstawia je do kolekcji w określonej pozycji.

```csharp
public ISlide[] InsertFromHtml(int index, Stream htmlStream, IExternalResourceResolver resolver, 
    string uri)
```

| Parametr | Typ | Opis |
| --- | --- | --- |
| index | Int32 | Pozycja wstawienia. |
| htmlStream | Stream | Obiekt Stream, który będzie używany jako źródło pliku HTML. |
| resolver | IExternalResourceResolver | Obiekt wywołania zwrotnego używany do pobierania obiektów zewnętrznych. Jeśli ten parametr jest null, wszystkie obiekty zewnętrzne zostaną zignorowane. |
| uri | String | Adres URI określonego HTML. Używany do rozwiązywania względnych odnośników. |

### Wartość zwracana

Dodane slajdy.

### Zobacz także

* interfejs [ISlide](../../islide)
* interfejs [IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver)
* interfejs [ISlideCollection](../../islidecollection)
* przestrzeń nazw [Aspose.Slides](../../islidecollection)
* zestaw [Aspose.Slides](../../../)

---

## InsertFromHtml(int, Stream) {#insertfromhtml}

Tworzy slajdy z tekstu HTML i wstawia je do kolekcji w określonej pozycji.

```csharp
public ISlide[] InsertFromHtml(int index, Stream htmlStream)
```

| Parametr | Typ | Opis |
| --- | --- | --- |
| index | Int32 | Pozycja wstawienia. |
| htmlStream | Stream | Obiekt Stream, który będzie używany jako źródło pliku HTML. |

### Wartość zwracana

Dodane slajdy

### Zobacz także

* interfejs [ISlide](../../islide)
* interfejs [ISlideCollection](../../islidecollection)
* przestrzeń nazw [Aspose.Slides](../../islidecollection)
* zestaw [Aspose.Slides](../../../)

---

## InsertFromHtml(int, string, bool) {#insertfromhtml_9}

Tworzy slajdy z tekstu HTML i wstawia je do kolekcji w określonej pozycji.

```csharp
public ISlide[] InsertFromHtml(int index, string htmlText, bool useSlideWithIndexAsStart)
```

| Parametr | Typ | Opis |
| --- | --- | --- |
| index | Int32 | Pozycja wstawienia. |
| htmlText | String | HTML do dodania. |
| useSlideWithIndexAsStart | Boolean | Ta flaga określa, jak rozpocząć wstawianie: od nowego slajdu lub od slajdu o określonym indeksie. Jeśli **true**, wstawianie danych rozpocznie się od pustego miejsca na slajdzie o podanym indeksie. Jeśli **false**, dane zostaną dodane do utworzonych slajdów. |

### Wartość zwracana

Dodane slajdy

### Zobacz także

* interfejs [ISlide](../../islide)
* interfejs [ISlideCollection](../../islidecollection)
* przestrzeń nazw [Aspose.Slides](../../islidecollection)
* zestaw [Aspose.Slides](../../../)

---

## InsertFromHtml(int, string, IExternalResourceResolver, string, bool) {#insertfromhtml_8}

Tworzy slajdy z tekstu HTML i wstawia je do kolekcji w określonej pozycji.

```csharp
public ISlide[] InsertFromHtml(int index, string htmlText, IExternalResourceResolver resolver, 
    string uri, bool useSlideWithIndexAsStart)
```

| Parametr | Typ | Opis |
| --- | --- | --- |
| index | Int32 | Pozycja wstawienia. |
| htmlText | String | HTML do dodania. |
| resolver | IExternalResourceResolver | Obiekt wywołania zwrotnego używany do pobierania obiektów zewnętrznych. Jeśli ten parametr jest null, wszystkie obiekty zewnętrzne zostaną zignorowane. |
| uri | String | Adres URI określonego HTML. Używany do rozwiązywania względnych odnośników. |
| useSlideWithIndexAsStart | Boolean | Ta flaga określa, jak rozpocząć wstawianie: od nowego slajdu lub od slajdu o określonym indeksie. Jeśli **true**, wstawianie danych rozpocznie się od pustego miejsca na slajdzie o podanym indeksie. Jeśli **false**, dane zostaną dodane do utworzonych slajdów. |

### Wartość zwracana

Dodane slajdy.

### Zobacz także

* interfejs [ISlide](../../islide)
* interfejs [IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver)
* interfejs [ISlideCollection](../../islidecollection)
* przestrzeń nazw [Aspose.Slides](../../islidecollection)
* zestaw [Aspose.Slides](../../../)

---

## InsertFromHtml(int, Stream, bool) {#insertfromhtml_3}

Tworzy slajdy z tekstu HTML i wstawia je do kolekcji w określonej pozycji.

```csharp
public ISlide[] InsertFromHtml(int index, Stream htmlStream, bool useSlideWithIndexAsStart)
```

| Parametr | Typ | Opis |
| --- | --- | --- |
| index | Int32 | Pozycja wstawienia. |
| htmlStream | Stream | Obiekt Stream, który będzie używany jako źródło pliku HTML. |
| useSlideWithIndexAsStart | Boolean | Ta flaga określa, jak rozpocząć wstawianie: od nowego slajdu lub od slajdu o określonym indeksie. Jeśli **true**, wstawianie danych rozpocznie się od pustego miejsca na slajdzie o podanym indeksie. Jeśli **false**, dane zostaną dodane do utworzonych slajdów. |

### Wartość zwracana

Dodane slajdy

### Zobacz także

* interfejs [ISlide](../../islide)
* interfejs [ISlideCollection](../../islidecollection)
* przestrzeń nazw [Aspose.Slides](../../islidecollection)
* zestaw [Aspose.Slides](../../../)

---

## InsertFromHtml(int, Stream, IExternalResourceResolver, string, bool) {#insertfromhtml_2}

Tworzy slajdy z tekstu HTML i wstawia je do kolekcji w określonej pozycji.

```csharp
public ISlide[] InsertFromHtml(int index, Stream htmlStream, IExternalResourceResolver resolver, 
    string uri, bool useSlideWithIndexAsStart)
```

| Parametr | Typ | Opis |
| --- | --- | --- |
| index | Int32 | Pozycja wstawienia. |
| htmlStream | Stream | Obiekt Stream, który będzie używany jako źródło pliku HTML. |
| resolver | IExternalResourceResolver | Obiekt wywołania zwrotnego używany do pobierania obiektów zewnętrznych. Jeśli ten parametr jest null, wszystkie obiekty zewnętrzne zostaną zignorowane. |
| uri | String | Adres URI określonego HTML. Używany do rozwiązywania względnych odnośników. |
| useSlideWithIndexAsStart | Boolean | Ta flaga określa, jak rozpocząć wstawianie: od nowego slajdu lub od slajdu o określonym indeksie. Jeśli **true**, wstawianie danych rozpocznie się od pustego miejsca na slajdzie o podanym indeksie. Jeśli **false**, dane zostaną dodane do utworzonych slajdów. |

### Wartość zwracana

Dodane slajdy.

### Zobacz także

* interfejs [ISlide](../../islide)
* interfejs [IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver)
* interfejs [ISlideCollection](../../islidecollection)
* przestrzeń nazw [Aspose.Slides](../../islidecollection)
* zestaw [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->