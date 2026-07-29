---
title: AddFromHtml()
second_title: Aspose.Slides för C++ API-referens
description: Skapar bilder från HTML-text och lägger till dem i slutet av samlingen.
type: docs
weight: 196
url: /sv/aspose.slides/slidecollection/addfromhtml/
---
## SlideCollection::AddFromHtml(System::String, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String) metod

Skapar bilder från HTML-text och lägger till dem i slutet av samlingen.

```cpp
System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::SlideCollection::AddFromHtml(System::String htmlText, System::SharedPtr<Import::IExternalResourceResolver> resolver, System::String uri) override
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| htmlText | [System::String](../../../system/string/) | Html att lägga till. |
| resolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | Ett återuppringningsobjekt som används för att hämta externa objekt. Om den här parametern är null kommer alla externa objekt att ignoreras. |
| uri | [System::String](../../../system/string/) | En URI för den specificerade HTML:n. Används för att lösa relativa länkar. |

### Returvärde

Tillagda bilder.

## SlideCollection::AddFromHtml(System::String) metod

Skapar bilder från HTML-text och lägger till dem i slutet av samlingen.

```cpp
System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::SlideCollection::AddFromHtml(System::String htmlText) override
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| htmlText | [System::String](../../../system/string/) | Html att lägga till. |

### Returvärde

Tillagda bilder

## SlideCollection::AddFromHtml(System::SharedPtr\<System::IO::TextReader\>, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String) metod

Skapar bilder från HTML-text och lägger till dem i slutet av samlingen.

```cpp
System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::SlideCollection::AddFromHtml(System::SharedPtr<System::IO::TextReader> htmlReader, System::SharedPtr<Import::IExternalResourceResolver> resolver, System::String uri) override
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| htmlReader | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::TextReader](../../../system.io/textreader/)\> | TextReader-objekt som kommer att användas som källa för en HTML-fil. |
| resolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | Ett återuppringningsobjekt som används för att hämta externa objekt. Om den här parametern är null kommer alla externa objekt att ignoreras. |
| uri | [System::String](../../../system/string/) | En URI för den specificerade HTML:n. Används för att lösa relativa länkar. |

### Returvärde

Tillagda bilder.

## SlideCollection::AddFromHtml(System::SharedPtr\<System::IO::TextReader\>) metod

Skapar bilder från HTML-text och lägger till dem i slutet av samlingen.

```cpp
System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::SlideCollection::AddFromHtml(System::SharedPtr<System::IO::TextReader> htmlReader) override
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| htmlReader | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::TextReader](../../../system.io/textreader/)\> | TextReader-objekt som kommer att användas som källa för en HTML-fil. |

### Returvärde

Tillagda bilder

## SlideCollection::AddFromHtml(System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String) metod

Skapar bilder från HTML-text och lägger till dem i slutet av samlingen.

```cpp
System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::SlideCollection::AddFromHtml(System::SharedPtr<System::IO::Stream> htmlStream, System::SharedPtr<Import::IExternalResourceResolver> resolver, System::String uri) override
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| htmlStream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Stream-objekt som kommer att användas som källa för en HTML-fil. |
| resolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | Ett återuppringningsobjekt som används för att hämta externa objekt. Om den här parametern är null kommer alla externa objekt att ignoreras. |
| uri | [System::String](../../../system/string/) | En URI för den specificerade HTML:n. Används för att lösa relativa länkar. |

### Returvärde

Tillagda bilder.

## SlideCollection::AddFromHtml(System::SharedPtr\<System::IO::Stream\>) metod

Skapar bilder från HTML-text och lägger till dem i slutet av samlingen.

```cpp
System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::SlideCollection::AddFromHtml(System::SharedPtr<System::IO::Stream> htmlStream) override
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| htmlStream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Stream-objekt som kommer att användas som källa för en HTML-fil. |

### Returvärde

Tillagda bilder

## Anmärkningar

```cpp
// Skapa en instans av Presentation-klassen.
auto presentation = System::MakeObject<Presentation>();

{
    auto htmlStream = System::IO::File::OpenRead(u"page.html");

    // Anropa AddFromHtml-metoden och skicka med HTML-filen.
    presentation->get_Slides()->AddFromHtml(htmlStream);
}

// Använd Save-metoden för att spara filen som ett PowerPoint-dokument.
presentation->Save(u"MyPresentation.pptx", SaveFormat::Pptx);
```

## Se också

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [ISlide](../../islide/)
* Klass [String](../../../system/string/)
* Klass [IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)
* Klass [SlideCollection](../)
* Klass [TextReader](../../../system.io/textreader/)
* Klass [Stream](../../../system.io/stream/)
* Namnrymd [Aspose::Slides](../../)
* Bibliotek [Aspose.Slides](../../../)