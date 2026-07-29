---
title: AddFromHtml()
second_title: Aspose.Slides för C++ API-referens
description: Skapar bilder från HTML-text och lägger till dem i slutet av samlingen.
type: docs
weight: 144
url: /sv/aspose.slides/islidecollection/addfromhtml/
---
## ISlideCollection::AddFromHtml(System::String, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String) metod

Skapar bilder från HTML-text och lägger till dem i slutet av samlingen.

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::AddFromHtml(System::String htmlText, System::SharedPtr<Import::IExternalResourceResolver> resolver, System::String uri)=0
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| htmlText | [System::String](../../../system/string/) | Html att lägga till. |
| resolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | Ett återuppringningsobjekt som används för att hämta externa objekt. Om den här parametern är null ignoreras alla externa objekt. |
| uri | [System::String](../../../system/string/) | En URI för den angivna HTML. Används för att lösa relativa länkar. |

### Returvärde

Tillagda bilder.

## ISlideCollection::AddFromHtml(System::String) metod

Skapar bilder från HTML-text och lägger till dem i slutet av samlingen.

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::AddFromHtml(System::String htmlText)=0
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| htmlText | [System::String](../../../system/string/) | Html att lägga till. |

### Returvärde

Tillagda bilder

## ISlideCollection::AddFromHtml(System::SharedPtr\<System::IO::TextReader\>, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String) metod

Skapar bilder från HTML-text och lägger till dem i slutet av samlingen.

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::AddFromHtml(System::SharedPtr<System::IO::TextReader> htmlReader, System::SharedPtr<Import::IExternalResourceResolver> resolver, System::String uri)=0
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| htmlReader | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::TextReader](../../../system.io/textreader/)\> | TextReader-objekt som kommer att användas som källa för en HTML-fil. |
| resolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | Ett återuppringningsobjekt som används för att hämta externa objekt. Om den här parametern är null ignoreras alla externa objekt. |
| uri | [System::String](../../../system/string/) | En URI för den angivna HTML. Används för att lösa relativa länkar. |

### Returvärde

Tillagda bilder.

## ISlideCollection::AddFromHtml(System::SharedPtr\<System::IO::TextReader\>) metod

Skapar bilder från HTML-text och lägger till dem i slutet av samlingen.

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::AddFromHtml(System::SharedPtr<System::IO::TextReader> htmlReader)=0
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| htmlReader | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::TextReader](../../../system.io/textreader/)\> | TextReader-objekt som kommer att användas som källa för en HTML-fil. |

### Returvärde

Tillagda bilder

## ISlideCollection::AddFromHtml(System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String) metod

Skapar bilder från HTML-text och lägger till dem i slutet av samlingen.

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::AddFromHtml(System::SharedPtr<System::IO::Stream> htmlStream, System::SharedPtr<Import::IExternalResourceResolver> resolver, System::String uri)=0
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| htmlStream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Ett Stream-objekt som kommer att användas som källa för en HTML-fil. |
| resolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | Ett återuppringningsobjekt som används för att hämta externa objekt. Om den här parametern är null ignoreras alla externa objekt. |
| uri | [System::String](../../../system/string/) | En URI för den angivna HTML. Används för att lösa relativa länkar. |

### Returvärde

Tillagda bilder.

## ISlideCollection::AddFromHtml(System::SharedPtr\<System::IO::Stream\>) metod

Skapar bilder från HTML-text och lägger till dem i slutet av samlingen.

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::AddFromHtml(System::SharedPtr<System::IO::Stream> htmlStream)=0
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| htmlStream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Ett Stream-objekt som kommer att användas som källa för en HTML-fil. |

### Returvärde

Tillagda bilder

## Se också

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [ISlide](../../islide/)
* Klass [String](../../../system/string/)
* Klass [IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)
* Klass [ISlideCollection](../)
* Klass [TextReader](../../../system.io/textreader/)
* Klass [Stream](../../../system.io/stream/)
* Namnrymd [Aspose::Slides](../../)
* Bibliotek [Aspose.Slides](../../../)