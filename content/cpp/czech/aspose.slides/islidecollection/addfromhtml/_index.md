---
title: AddFromHtml()
second_title: Aspose.Slides pro C++ API Reference
description: Vytvoří snímky z textu HTML a přidá je na konec kolekce.
type: docs
weight: 144
url: /cs/aspose.slides/islidecollection/addfromhtml/
---
## ISlideCollection::AddFromHtml(System::String, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String) metoda


Vytvoří snímky z textu HTML a přidá je na konec kolekce.

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::AddFromHtml(System::String htmlText, System::SharedPtr<Import::IExternalResourceResolver> resolver, System::String uri)=0
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| htmlText | [System::String](../../../system/string/) | Html to add. |
| resolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | A callback object used to fetch external objects. If this parameter is null all external objects will be ignored. |
| uri | [System::String](../../../system/string/) | An URI of the specified HTML. Used to resolve relative links. |

### Návratová hodnota

Added slides.

## ISlideCollection::AddFromHtml(System::String) metoda


Vytvoří snímky z textu HTML a přidá je na konec kolekce.

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::AddFromHtml(System::String htmlText)=0
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| htmlText | [System::String](../../../system/string/) | Html to add. |

### Návratová hodnota

Added slides

## ISlideCollection::AddFromHtml(System::SharedPtr\<System::IO::TextReader\>, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String) metoda


Vytvoří snímky z textu HTML a přidá je na konec kolekce.

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::AddFromHtml(System::SharedPtr<System::IO::TextReader> htmlReader, System::SharedPtr<Import::IExternalResourceResolver> resolver, System::String uri)=0
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| htmlReader | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::TextReader](../../../system.io/textreader/)\> | TextReader object which will be used as a source of a HTML file. |
| resolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | A callback object used to fetch external objects. If this parameter is null all external objects will be ignored. |
| uri | [System::String](../../../system/string/) | An URI of the specified HTML. Used to resolve relative links. |

### Návratová hodnota

Added slides.

## ISlideCollection::AddFromHtml(System::SharedPtr\<System::IO::TextReader\>) metoda


Vytvoří snímky z textu HTML a přidá je na konec kolekce.

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::AddFromHtml(System::SharedPtr<System::IO::TextReader> htmlReader)=0
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| htmlReader | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::TextReader](../../../system.io/textreader/)\> | TextReader object which will be used as a source of a HTML file. |

### Návratová hodnota

Added slides

## ISlideCollection::AddFromHtml(System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String) metoda


Vytvoří snímky z textu HTML a přidá je na konec kolekce.

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::AddFromHtml(System::SharedPtr<System::IO::Stream> htmlStream, System::SharedPtr<Import::IExternalResourceResolver> resolver, System::String uri)=0
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| htmlStream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | A Stream object which will be used as a source of a HTML file. |
| resolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | A callback object used to fetch external objects. If this parameter is null all external objects will be ignored. |
| uri | [System::String](../../../system/string/) | An URI of the specified HTML. Used to resolve relative links. |

### Návratová hodnota

Added slides.

## ISlideCollection::AddFromHtml(System::SharedPtr\<System::IO::Stream\>) metoda


Vytvoří snímky z textu HTML a přidá je na konec kolekce.

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::AddFromHtml(System::SharedPtr<System::IO::Stream> htmlStream)=0
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| htmlStream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | A Stream object which will be used as a source of a HTML file. |

### Návratová hodnota

Added slides

## Viz také

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [ISlide](../../islide/)
* Třída [String](../../../system/string/)
* Třída [IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)
* Třída [ISlideCollection](../)
* Třída [TextReader](../../../system.io/textreader/)
* Třída [Stream](../../../system.io/stream/)
* Jmenný prostor [Aspose::Slides](../../)
* Knihovna [Aspose.Slides](../../../)