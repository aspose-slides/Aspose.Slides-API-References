---
title: AddFromHtml()
second_title: Aspose.Slides dla C++ – referencja API
description: Tworzy slajdy z tekstu HTML i dodaje je na koniec kolekcji.
type: docs
weight: 196
url: /pl/aspose.slides/slidecollection/addfromhtml/
---
## SlideCollection::AddFromHtml(System::String, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String) metoda

Tworzy slajdy z tekstu HTML i dodaje je na koniec kolekcji.

```cpp
System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::SlideCollection::AddFromHtml(System::String htmlText, System::SharedPtr<Import::IExternalResourceResolver> resolver, System::String uri) override
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| htmlText | [System::String](../../../system/string/) | HTML do dodania. |
| resolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | Obiekt wywołania zwrotnego używany do pobierania obiektów zewnętrznych. Jeśli ten parametr jest null, wszystkie obiekty zewnętrzne zostaną zignorowane. |
| uri | [System::String](../../../system/string/) | Adres URI określonego HTML. Używany do rozwiązywania względnych odnośników. |

### Wartość zwracana

Dodane slajdy.

## SlideCollection::AddFromHtml(System::String) metoda

Tworzy slajdy z tekstu HTML i dodaje je na koniec kolekcji.

```cpp
System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::SlideCollection::AddFromHtml(System::String htmlText) override
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| htmlText | [System::String](../../../system/string/) | HTML do dodania. |

### Wartość zwracana

Dodane slajdy

## SlideCollection::AddFromHtml(System::SharedPtr\<System::IO::TextReader\>, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String) metoda

Tworzy slajdy z tekstu HTML i dodaje je na koniec kolekcji.

```cpp
System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::SlideCollection::AddFromHtml(System::SharedPtr<System::IO::TextReader> htmlReader, System::SharedPtr<Import::IExternalResourceResolver> resolver, System::String uri) override
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| htmlReader | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::TextReader](../../../system.io/textreader/)\> | Obiekt TextReader, który będzie używany jako źródło pliku HTML. |
| resolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | Obiekt wywołania zwrotnego używany do pobierania obiektów zewnętrznych. Jeśli ten parametr jest null, wszystkie obiekty zewnętrzne zostaną zignorowane. |
| uri | [System::String](../../../system/string/) | Adres URI określonego HTML. Używany do rozwiązywania względnych odnośników. |

### Wartość zwracana

Dodane slajdy.

## SlideCollection::AddFromHtml(System::SharedPtr\<System::IO::TextReader\>) metoda

Tworzy slajdy z tekstu HTML i dodaje je na koniec kolekcji.

```cpp
System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::SlideCollection::AddFromHtml(System::SharedPtr<System::IO::TextReader> htmlReader) override
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| htmlReader | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::TextReader](../../../system.io/textreader/)\> | Obiekt TextReader, który będzie używany jako źródło pliku HTML. |

### Wartość zwracana

Dodane slajdy

## SlideCollection::AddFromHtml(System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String) metoda

Tworzy slajdy z tekstu HTML i dodaje je na koniec kolekcji.

```cpp
System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::SlideCollection::AddFromHtml(System::SharedPtr<System::IO::Stream> htmlStream, System::SharedPtr<Import::IExternalResourceResolver> resolver, System::String uri) override
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| htmlStream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Obiekt Stream, który będzie używany jako źródło pliku HTML. |
| resolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | Obiekt wywołania zwrotnego używany do pobierania obiektów zewnętrznych. Jeśli ten parametr jest null, wszystkie obiekty zewnętrzne zostaną zignorowane. |
| uri | [System::String](../../../system/string/) | Adres URI określonego HTML. Używany do rozwiązywania względnych odnośników. |

### Wartość zwracana

Dodane slajdy.

## SlideCollection::AddFromHtml(System::SharedPtr\<System::IO::Stream\>) metoda

Tworzy slajdy z tekstu HTML i dodaje je na koniec kolekcji.

```cpp
System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::SlideCollection::AddFromHtml(System::SharedPtr<System::IO::Stream> htmlStream) override
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| htmlStream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Obiekt Stream, który będzie używany jako źródło pliku HTML. |

### Wartość zwracana

Dodane slajdy

## Uwagi

```cpp
// Utwórz instancję klasy Presentation.
auto presentation = System::MakeObject<Presentation>();

{
    auto htmlStream = System::IO::File::OpenRead(u"page.html");

    // Wywołaj metodę AddFromHtml i przekaż plik HTML.
    presentation->get_Slides()->AddFromHtml(htmlStream);
}

// Użyj metody Save, aby zapisać plik jako dokument PowerPoint.
presentation->Save(u"MyPresentation.pptx", SaveFormat::Pptx);
```

## Zobacz także

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ISlide](../../islide/)
* Class [String](../../../system/string/)
* Class [IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)
* Class [SlideCollection](../)
* Class [TextReader](../../../system.io/textreader/)
* Class [Stream](../../../system.io/stream/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)