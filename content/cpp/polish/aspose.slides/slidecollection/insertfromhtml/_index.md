---
title: InsertFromHtml()
second_title: Aspose.Slides dla C++ - odniesienie API
description: Tworzy slajdy z tekstu HTML i wstawia je do kolekcji w określonej pozycji.
type: docs
weight: 209
url: /pl/aspose.slides/slidecollection/insertfromhtml/
---
## SlideCollection::InsertFromHtml(int32_t, System::String, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String) metoda


Tworzy slajdy z tekstu HTML i wstawia je do kolekcji na określonej pozycji.

```cpp
System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::SlideCollection::InsertFromHtml(int32_t index, System::String htmlText, System::SharedPtr<Import::IExternalResourceResolver> resolver, System::String uri) override
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| index | **int32_t** | Pozycja wstawienia. |
| htmlText | [System::String](../../../system/string/) | HTML do dodania. |
| resolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | Obiekt wywołania zwrotnego używany do pobierania zewnętrznych obiektów. Jeśli ten parametr jest równy null, wszystkie zewnętrzne obiekty będą pomijane. |
| uri | [System::String](../../../system/string/) | Adres URI określonego HTML. Używany do rozwiązywania względnych odnośników. |

### Wartość zwracana

Dodane slajdy.

## SlideCollection::InsertFromHtml(int32_t, System::String, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String, bool) metoda


Tworzy slajdy z tekstu HTML i wstawia je do kolekcji na określonej pozycji.

```cpp
System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::SlideCollection::InsertFromHtml(int32_t index, System::String htmlText, System::SharedPtr<Import::IExternalResourceResolver> resolver, System::String uri, bool useSlideWithIndexAsStart) override
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| index | **int32_t** | Pozycja wstawienia. |
| htmlText | [System::String](../../../system/string/) | HTML do dodania. |
| resolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | Obiekt wywołania zwrotnego używany do pobierania zewnętrznych obiektów. Jeśli ten parametr jest równy null, wszystkie zewnętrzne obiekty będą pomijane. |
| uri | [System::String](../../../system/string/) | Adres URI określonego HTML. Używany do rozwiązywania względnych odnośników. |
| useSlideWithIndexAsStart | **bool** | Ta flaga określa, jak rozpocząć wstawianie: od nowego slajdu lub od slajdu o określonym indeksie. Jeśli **true**, wstawianie danych rozpocznie się od pustego miejsca na slajdzie o określonym indeksie. Jeśli **false**, dane zostaną dodane do utworzonych slajdów. |

### Wartość zwracana

Dodane slajdy.

## SlideCollection::InsertFromHtml(int32_t, System::String) metoda


Tworzy slajdy z tekstu HTML i wstawia je do kolekcji na określonej pozycji.

```cpp
System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::SlideCollection::InsertFromHtml(int32_t index, System::String htmlText) override
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| index | **int32_t** | Pozycja wstawienia. |
| htmlText | [System::String](../../../system/string/) | HTML do dodania. |

### Wartość zwracana

Dodane slajdy

## SlideCollection::InsertFromHtml(int32_t, System::String, bool) metoda


Tworzy slajdy z tekstu HTML i wstawia je do kolekcji na określonej pozycji.

```cpp
System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::SlideCollection::InsertFromHtml(int32_t index, System::String htmlText, bool useSlideWithIndexAsStart) override
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| index | **int32_t** | Pozycja wstawienia. |
| htmlText | [System::String](../../../system/string/) | HTML do dodania. |
| useSlideWithIndexAsStart | **bool** | Ta flaga określa, jak rozpocząć wstawianie: od nowego slajdu lub od slajdu o określonym indeksie. Jeśli **true**, wstawianie danych rozpocznie się od pustego miejsca na slajdzie o określonym indeksie. Jeśli **false**, dane zostaną dodane do utworzonych slajdów. |

### Wartość zwracana

Dodane slajdy

## SlideCollection::InsertFromHtml(int32_t, System::SharedPtr\<System::IO::TextReader\>, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String) metoda


Tworzy slajdy z tekstu HTML i wstawia je do kolekcji na określonej pozycji.

```cpp
System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::SlideCollection::InsertFromHtml(int32_t index, System::SharedPtr<System::IO::TextReader> htmlReader, System::SharedPtr<Import::IExternalResourceResolver> resolver, System::String uri) override
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| index | **int32_t** | Pozycja wstawienia. |
| htmlReader | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::TextReader](../../../system.io/textreader/)\> | Obiekt TextReader, który zostanie użyty jako źródło pliku HTML. |
| resolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | Obiekt wywołania zwrotnego używany do pobierania zewnętrznych obiektów. Jeśli ten parametr jest równy null, wszystkie zewnętrzne obiekty będą pomijane. |
| uri | [System::String](../../../system/string/) | Adres URI określonego HTML. Używany do rozwiązywania względnych odnośników. |

### Wartość zwracana

Dodane slajdy.

## SlideCollection::InsertFromHtml(int32_t, System::SharedPtr\<System::IO::TextReader\>) metoda


Tworzy slajdy z tekstu HTML i wstawia je do kolekcji na określonej pozycji.

```cpp
System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::SlideCollection::InsertFromHtml(int32_t index, System::SharedPtr<System::IO::TextReader> htmlReader) override
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| index | **int32_t** | Pozycja wstawienia. |
| htmlReader | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::TextReader](../../../system.io/textreader/)\> | Obiekt TextReader, który zostanie użyty jako źródło pliku HTML. |

### Wartość zwracana

Dodane slajdy

## SlideCollection::InsertFromHtml(int32_t, System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String) metoda


Tworzy slajdy z tekstu HTML i wstawia je do kolekcji na określonej pozycji.

```cpp
System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::SlideCollection::InsertFromHtml(int32_t index, System::SharedPtr<System::IO::Stream> htmlStream, System::SharedPtr<Import::IExternalResourceResolver> resolver, System::String uri) override
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| index | **int32_t** | Pozycja wstawienia. |
| htmlStream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Obiekt Stream, który zostanie użyty jako źródło pliku HTML. |
| resolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | Obiekt wywołania zwrotnego używany do pobierania zewnętrznych obiektów. Jeśli ten parametr jest równy null, wszystkie zewnętrzne obiekty będą pomijane. |
| uri | [System::String](../../../system/string/) | Adres URI określonego HTML. Używany do rozwiązywania względnych odnośników. |

### Wartość zwracana

Dodane slajdy.

## SlideCollection::InsertFromHtml(int32_t, System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String, bool) metoda


Tworzy slajdy z tekstu HTML i wstawia je do kolekcji na określonej pozycji.

```cpp
System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::SlideCollection::InsertFromHtml(int32_t index, System::SharedPtr<System::IO::Stream> htmlStream, System::SharedPtr<Import::IExternalResourceResolver> resolver, System::String uri, bool useSlideWithIndexAsStart) override
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| index | **int32_t** | Pozycja wstawienia. |
| htmlStream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Obiekt Stream, który zostanie użyty jako źródło pliku HTML. |
| resolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | Obiekt wywołania zwrotnego używany do pobierania zewnętrznych obiektów. Jeśli ten parametr jest równy null, wszystkie zewnętrzne obiekty będą pomijane. |
| uri | [System::String](../../../system/string/) | Adres URI określonego HTML. Używany do rozwiązywania względnych odnośników. |
| useSlideWithIndexAsStart | **bool** | Ta flaga określa, jak rozpocząć wstawianie: od nowego slajdu lub od slajdu o określonym indeksie. Jeśli **true**, wstawianie danych rozpocznie się od pustego miejsca na slajdzie o określonym indeksie. Jeśli **false**, dane zostaną dodane do utworzonych slajdów. |

### Wartość zwracana

Dodane slajdy.

## SlideCollection::InsertFromHtml(int32_t, System::SharedPtr\<System::IO::Stream\>) metoda


Tworzy slajdy z tekstu HTML i wstawia je do kolekcji na określonej pozycji.

```cpp
System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::SlideCollection::InsertFromHtml(int32_t index, System::SharedPtr<System::IO::Stream> htmlStream) override
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| index | **int32_t** | Pozycja wstawienia. |
| htmlStream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Obiekt Stream, który zostanie użyty jako źródło pliku HTML. |

### Wartość zwracana

Dodane slajdy

## SlideCollection::InsertFromHtml(int32_t, System::SharedPtr\<System::IO::Stream\>, bool) metoda


Tworzy slajdy z tekstu HTML i wstawia je do kolekcji na określonej pozycji.

```cpp
System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::SlideCollection::InsertFromHtml(int32_t index, System::SharedPtr<System::IO::Stream> htmlStream, bool useSlideWithIndexAsStart) override
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| index | **int32_t** | Pozycja wstawienia. |
| htmlStream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Obiekt Stream, który zostanie użyty jako źródło pliku HTML. |
| useSlideWithIndexAsStart | **bool** | Ta flaga określa, jak rozpocząć wstawianie: od nowego slajdu lub od slajdu o określonym indeksie. Jeśli **true**, wstawianie danych rozpocznie się od pustego miejsca na slajdzie o określonym indeksie. Jeśli **false**, dane zostaną dodane do utworzonych slajdów. |

### Wartość zwracana

Dodane slajdy

## Zobacz także

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasa [ISlide](../../islide/)
* Klasa [String](../../../system/string/)
* Klasa [IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)
* Klasa [SlideCollection](../)
* Klasa [TextReader](../../../system.io/textreader/)
* Klasa [Stream](../../../system.io/stream/)
* Przestrzeń nazw [Aspose::Slides](../../)
* Biblioteka [Aspose.Slides](../../../)