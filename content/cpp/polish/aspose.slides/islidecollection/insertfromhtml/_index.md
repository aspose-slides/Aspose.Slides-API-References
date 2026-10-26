---
title: InsertFromHtml()
second_title: Aspose.Slides dla C++ – referencja API
description: Tworzy slajdy z tekstu HTML i wstawia je do kolekcji w określonej pozycji.
type: docs
weight: 157
url: /pl/aspose.slides/islidecollection/insertfromhtml/
---
## ISlideCollection::InsertFromHtml(int32_t, System::String, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String) method

Tworzy slajdy z tekstu HTML i wstawia je do kolekcji w podanej pozycji.

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::InsertFromHtml(int32_t index, System::String htmlText, System::SharedPtr<Import::IExternalResourceResolver> resolver, System::String uri)=0
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| index | **int32_t** | Pozycja wstawiania. |
| htmlText | [System::String](../../../system/string/) | HTML do dodania. |
| resolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | Obiekt zwrotny używany do pobierania zewnętrznych obiektów. Jeśli ten parametr jest null, wszystkie zewnętrzne obiekty zostaną zignorowane. |
| uri | [System::String](../../../system/string/) | Adres URI określonego HTML. Używany do rozwiązywania względnych odnośników. |

### Wartość zwracana

Dodane slajdy.

## ISlideCollection::InsertFromHtml(int32_t, System::String) method

Tworzy slajdy z tekstu HTML i wstawia je do kolekcji w podanej pozycji.

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::InsertFromHtml(int32_t index, System::String htmlText)=0
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| index | **int32_t** | Pozycja wstawiania. |
| htmlText | [System::String](../../../system/string/) | HTML do dodania. |

### Wartość zwracana

Dodane slajdy

## ISlideCollection::InsertFromHtml(int32_t, System::SharedPtr\<System::IO::TextReader\>, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String) method

Tworzy slajdy z tekstu HTML i wstawia je do kolekcji w podanej pozycji.

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::InsertFromHtml(int32_t index, System::SharedPtr<System::IO::TextReader> htmlReader, System::SharedPtr<Import::IExternalResourceResolver> resolver, System::String uri)=0
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| index | **int32_t** | Pozycja wstawiania. |
| htmlReader | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::TextReader](../../../system.io/textreader/)\> | Obiekt TextReader, który zostanie użyty jako źródło pliku HTML. |
| resolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | Obiekt zwrotny używany do pobierania zewnętrznych obiektów. Jeśli ten parametr jest null, wszystkie zewnętrzne obiekty zostaną zignorowane. |
| uri | [System::String](../../../system/string/) | Adres URI określonego HTML. Używany do rozwiązywania względnych odnośników. |

### Wartość zwracana

Dodane slajdy.

## ISlideCollection::InsertFromHtml(int32_t, System::SharedPtr\<System::IO::TextReader\>) method

Tworzy slajdy z tekstu HTML i wstawia je do kolekcji w podanej pozycji.

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::InsertFromHtml(int32_t index, System::SharedPtr<System::IO::TextReader> htmlReader)=0
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| index | **int32_t** | Pozycja wstawiania. |
| htmlReader | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::TextReader](../../../system.io/textreader/)\> | Obiekt TextReader, który zostanie użyty jako źródło pliku HTML. |

### Wartość zwracana

Dodane slajdy

## ISlideCollection::InsertFromHtml(int32_t, System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String) method

Tworzy slajdy z tekstu HTML i wstawia je do kolekcji w podanej pozycji.

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::InsertFromHtml(int32_t index, System::SharedPtr<System::IO::Stream> htmlStream, System::SharedPtr<Import::IExternalResourceResolver> resolver, System::String uri)=0
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| index | **int32_t** | Pozycja wstawiania. |
| htmlStream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Obiekt Stream, który zostanie użyty jako źródło pliku HTML. |
| resolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | Obiekt zwrotny używany do pobierania zewnętrznych obiektów. Jeśli ten parametr jest null, wszystkie zewnętrzne obiekty zostaną zignorowane. |
| uri | [System::String](../../../system/string/) | Adres URI określonego HTML. Używany do rozwiązywania względnych odnośników. |

### Wartość zwracana

Dodane slajdy.

## ISlideCollection::InsertFromHtml(int32_t, System::SharedPtr\<System::IO::Stream\>) method

Tworzy slajdy z tekstu HTML i wstawia je do kolekcji w podanej pozycji.

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::InsertFromHtml(int32_t index, System::SharedPtr<System::IO::Stream> htmlStream)=0
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| index | **int32_t** | Pozycja wstawiania. |
| htmlStream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Obiekt Stream, który zostanie użyty jako źródło pliku HTML. |

### Wartość zwracana

Dodane slajdy

## ISlideCollection::InsertFromHtml(int32_t, System::String, bool) method

Tworzy slajdy z tekstu HTML i wstawia je do kolekcji w podanej pozycji.

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::InsertFromHtml(int32_t index, System::String htmlText, bool useSlideWithIndexAsStart)=0
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| index | **int32_t** | Pozycja wstawiania. |
| htmlText | [System::String](../../../system/string/) | HTML do dodania. |
| useSlideWithIndexAsStart | **bool** | Ten parametr określa, jak rozpocząć wstawianie: od nowego slajdu lub od slajdu o podanym indeksie. Jeśli **true**, wstawianie danych rozpocznie się od pustej przestrzeni na slajdzie o podanym indeksie. Jeśli **false**, dane zostaną dodane do utworzonych slajdów. |

### Wartość zwracana

Dodane slajdy

## ISlideCollection::InsertFromHtml(int32_t, System::String, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String, bool) method

Tworzy slajdy z tekstu HTML i wstawia je do kolekcji w podanej pozycji.

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::InsertFromHtml(int32_t index, System::String htmlText, System::SharedPtr<Import::IExternalResourceResolver> resolver, System::String uri, bool useSlideWithIndexAsStart)=0
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| index | **int32_t** | Pozycja wstawiania. |
| htmlText | [System::String](../../../system/string/) | HTML do dodania. |
| resolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | Obiekt zwrotny używany do pobierania zewnętrznych obiektów. Jeśli ten parametr jest null, wszystkie zewnętrzne obiekty zostaną zignorowane. |
| uri | [System::String](../../../system/string/) | Adres URI określonego HTML. Używany do rozwiązywania względnych odnośników. |
| useSlideWithIndexAsStart | **bool** | Ten parametr określa, jak rozpocząć wstawianie: od nowego slajdu lub od slajdu o podanym indeksie. Jeśli **true**, wstawianie danych rozpocznie się od pustej przestrzeni na slajdzie o podanym indeksie. Jeśli **false**, dane zostaną dodane do utworzonych slajdów. |

### Wartość zwracana

Dodane slajdy.

## ISlideCollection::InsertFromHtml(int32_t, System::SharedPtr\<System::IO::Stream\>, bool) method

Tworzy slajdy z tekstu HTML i wstawia je do kolekcji w podanej pozycji.

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::InsertFromHtml(int32_t index, System::SharedPtr<System::IO::Stream> htmlStream, bool useSlideWithIndexAsStart)=0
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| index | **int32_t** | Pozycja wstawiania. |
| htmlStream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Obiekt Stream, który zostanie użyty jako źródło pliku HTML. |
| useSlideWithIndexAsStart | **bool** | Ten parametr określa, jak rozpocząć wstawianie: od nowego slajdu lub od slajdu o podanym indeksie. Jeśli **true**, wstawianie danych rozpocznie się od pustej przestrzeni na slajdzie o podanym indeksie. Jeśli **false**, dane zostaną dodane do utworzonych slajdów. |

### Wartość zwracana

Dodane slajdy

## ISlideCollection::InsertFromHtml(int32_t, System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String, bool) method

Tworzy slajdy z tekstu HTML i wstawia je do kolekcji w podanej pozycji.

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::InsertFromHtml(int32_t index, System::SharedPtr<System::IO::Stream> htmlStream, System::SharedPtr<Import::IExternalResourceResolver> resolver, System::String uri, bool useSlideWithIndexAsStart)=0
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| index | **int32_t** | Pozycja wstawiania. |
| htmlStream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Obiekt Stream, który zostanie użyty jako źródło pliku HTML. |
| resolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | Obiekt zwrotny używany do pobierania zewnętrznych obiektów. Jeśli ten parametr jest null, wszystkie zewnętrzne obiekty zostaną zignorowane. |
| uri | [System::String](../../../system/string/) | Adres URI określonego HTML. Używany do rozwiązywania względnych odnośników. |
| useSlideWithIndexAsStart | **bool** | Ten parametr określa, jak rozpocząć wstawianie: od nowego slajdu lub od slajdu o podanym indeksie. Jeśli **true**, wstawianie danych rozpocznie się od pustej przestrzeni na slajdzie o podanym indeksie. Jeśli **false**, dane zostaną dodane do utworzonych slajdów. |

### Wartość zwracana

Dodane slajdy.

## Zobacz także

* Definicja typu [ArrayPtr](../../../system/arrayptr/)
* Definicja typu [SharedPtr](../../../system/sharedptr/)
* Klasa [ISlide](../../islide/)
* Klasa [String](../../../system/string/)
* Klasa [IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)
* Klasa [ISlideCollection](../)
* Klasa [TextReader](../../../system.io/textreader/)
* Klasa [Stream](../../../system.io/stream/)
* Przestrzeń nazw [Aspose::Slides](../../)
* Biblioteka [Aspose.Slides](../../../)