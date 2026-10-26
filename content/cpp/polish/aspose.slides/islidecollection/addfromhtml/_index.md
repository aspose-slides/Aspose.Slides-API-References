---
title: AddFromHtml()
second_title: Aspose.Slides dla C++ – Dokumentacja API
description: Tworzy slajdy z tekstu HTML i dodaje je na koniec kolekcji.
type: docs
weight: 144
url: /pl/aspose.slides/islidecollection/addfromhtml/
---
## ISlideCollection::AddFromHtml(System::String, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String) metoda

Tworzy slajdy z tekstu HTML i dodaje je na koniec kolekcji.

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::AddFromHtml(System::String htmlText, System::SharedPtr<Import::IExternalResourceResolver> resolver, System::String uri)=0
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| htmlText | [System::String](../../../system/string/) | HTML do dodania. |
| resolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | Obiekt wywołania zwrotnego używany do pobierania zewnętrznych obiektów. Jeśli ten parametr jest równy null, wszystkie zewnętrzne obiekty zostaną zignorowane. |
| uri | [System::String](../../../system/string/) | Adres URI określonego HTML. Używany do rozwiązywania względnych odnośników. |

### Wartość zwracana

Dodane slajdy.

## ISlideCollection::AddFromHtml(System::String) metoda

Tworzy slajdy z tekstu HTML i dodaje je na koniec kolekcji.

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::AddFromHtml(System::String htmlText)=0
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| htmlText | [System::String](../../../system/string/) | HTML do dodania. |

### Wartość zwracana

Dodane slajdy

## ISlideCollection::AddFromHtml(System::SharedPtr\<System::IO::TextReader\>, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String) metoda

Tworzy slajdy z tekstu HTML i dodaje je na koniec kolekcji.

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::AddFromHtml(System::SharedPtr<System::IO::TextReader> htmlReader, System::SharedPtr<Import::IExternalResourceResolver> resolver, System::String uri)=0
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| htmlReader | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::TextReader](../../../system.io/textreader/)\> | Obiekt TextReader, który będzie używany jako źródło pliku HTML. |
| resolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | Obiekt wywołania zwrotnego używany do pobierania zewnętrznych obiektów. Jeśli ten parametr jest równy null, wszystkie zewnętrzne obiekty zostaną zignorowane. |
| uri | [System::String](../../../system/string/) | Adres URI określonego HTML. Używany do rozwiązywania względnych odnośników. |

### Wartość zwracana

Dodane slajdy.

## ISlideCollection::AddFromHtml(System::SharedPtr\<System::IO::TextReader\>) metoda

Tworzy slajdy z tekstu HTML i dodaje je na koniec kolekcji.

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::AddFromHtml(System::SharedPtr<System::IO::TextReader> htmlReader)=0
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| htmlReader | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::TextReader](../../../system.io/textreader/)\> | Obiekt TextReader, który będzie używany jako źródło pliku HTML. |

### Wartość zwracana

Dodane slajdy

## ISlideCollection::AddFromHtml(System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String) metoda

Tworzy slajdy z tekstu HTML i dodaje je na koniec kolekcji.

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::AddFromHtml(System::SharedPtr<System::IO::Stream> htmlStream, System::SharedPtr<Import::IExternalResourceResolver> resolver, System::String uri)=0
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| htmlStream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Obiekt Stream, który będzie używany jako źródło pliku HTML. |
| resolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | Obiekt wywołania zwrotnego używany do pobierania zewnętrznych obiektów. Jeśli ten parametr jest równy null, wszystkie zewnętrzne obiekty zostaną zignorowane. |
| uri | [System::String](../../../system/string/) | Adres URI określonego HTML. Używany do rozwiązywania względnych odnośników. |

### Wartość zwracana

Dodane slajdy.

## ISlideCollection::AddFromHtml(System::SharedPtr\<System::IO::Stream\>) metoda

Tworzy slajdy z tekstu HTML i dodaje je na koniec kolekcji.

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::AddFromHtml(System::SharedPtr<System::IO::Stream> htmlStream)=0
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| htmlStream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Obiekt Stream, który będzie używany jako źródło pliku HTML. |

### Wartość zwracana

Dodane slajdy

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