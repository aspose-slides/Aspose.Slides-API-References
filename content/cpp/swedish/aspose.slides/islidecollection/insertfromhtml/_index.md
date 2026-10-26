---
title: InsertFromHtml()
second_title: Aspose.Slides för C++ API-referens
description: Skapar bilder från HTML-text och infogar dem i samlingen på den angivna positionen.
type: docs
weight: 157
url: /sv/aspose.slides/islidecollection/insertfromhtml/
---
## ISlideCollection::InsertFromHtml(int32_t, System::String, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String) metod


Skapar bilder från HTML-text och infogar dem i samlingen på den angivna positionen.

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::InsertFromHtml(int32_t index, System::String htmlText, System::SharedPtr<Import::IExternalResourceResolver> resolver, System::String uri)=0
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | **int32_t** | Position att infoga. |
| htmlText | [System::String](../../../system/string/) | HTML att lägga till. |
| resolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | Ett återuppringningsobjekt som används för att hämta externa objekt. Om denna parameter är null ignoreras alla externa objekt. |
| uri | [System::String](../../../system/string/) | En URI för den angivna HTML-koden. Används för att lösa relativa länkar. |

### Returvärde

Tillagda bilder.

## ISlideCollection::InsertFromHtml(int32_t, System::String) metod


Skapar bilder från HTML-text och infogar dem i samlingen på den angivna positionen.

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::InsertFromHtml(int32_t index, System::String htmlText)=0
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | **int32_t** | Position att infoga. |
| htmlText | [System::String](../../../system/string/) | HTML att lägga till. |

### Returvärde

Tillagda bilder

## ISlideCollection::InsertFromHtml(int32_t, System::SharedPtr\<System::IO::TextReader\>, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String) metod


Skapar bilder från HTML-text och infogar dem i samlingen på den angivna positionen.

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::InsertFromHtml(int32_t index, System::SharedPtr<System::IO::TextReader> htmlReader, System::SharedPtr<Import::IExternalResourceResolver> resolver, System::String uri)=0
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | **int32_t** | Position att infoga. |
| htmlReader | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::TextReader](../../../system.io/textreader/)\> | Ett TextReader-objekt som kommer att användas som källa för en HTML-fil. |
| resolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | Ett återuppringningsobjekt som används för att hämta externa objekt. Om denna parameter är null ignoreras alla externa objekt. |
| uri | [System::String](../../../system/string/) | En URI för den angivna HTML-koden. Används för att lösa relativa länkar. |

### Returvärde

Tillagda bilder.

## ISlideCollection::InsertFromHtml(int32_t, System::SharedPtr\<System::IO::TextReader\>) metod


Skapar bilder från HTML-text och infogar dem i samlingen på den angivna positionen.

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::InsertFromHtml(int32_t index, System::SharedPtr<System::IO::TextReader> htmlReader)=0
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | **int32_t** | Position att infoga. |
| htmlReader | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::TextReader](../../../system.io/textreader/)\> | Ett TextReader-objekt som kommer att användas som källa för en HTML-fil. |

### Returvärde

Tillagda bilder

## ISlideCollection::InsertFromHtml(int32_t, System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String) metod


Skapar bilder från HTML-text och infogar dem i samlingen på den angivna positionen.

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::InsertFromHtml(int32_t index, System::SharedPtr<System::IO::Stream> htmlStream, System::SharedPtr<Import::IExternalResourceResolver> resolver, System::String uri)=0
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | **int32_t** | Position att infoga. |
| htmlStream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Ett Stream-objekt som kommer att användas som källa för en HTML-fil. |
| resolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | Ett återuppringningsobjekt som används för att hämta externa objekt. Om denna parameter är null ignoreras alla externa objekt. |
| uri | [System::String](../../../system/string/) | En URI för den angivna HTML-koden. Används för att lösa relativa länkar. |

### Returvärde

Tillagda bilder.

## ISlideCollection::InsertFromHtml(int32_t, System::SharedPtr\<System::IO::Stream\>) metod


Skapar bilder från HTML-text och infogar dem i samlingen på den angivna positionen.

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::InsertFromHtml(int32_t index, System::SharedPtr<System::IO::Stream> htmlStream)=0
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | **int32_t** | Position att infoga. |
| htmlStream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Ett Stream-objekt som kommer att användas som källa för en HTML-fil. |

### Returvärde

Tillagda bilder

## ISlideCollection::InsertFromHtml(int32_t, System::String, bool) metod


Skapar bilder från HTML-text och infogar dem i samlingen på den angivna positionen.

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::InsertFromHtml(int32_t index, System::String htmlText, bool useSlideWithIndexAsStart)=0
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | **int32_t** | Position att infoga. |
| htmlText | [System::String](../../../system/string/) | HTML att lägga till. |
| useSlideWithIndexAsStart | **bool** | Denna flagga bestämmer hur infogningen ska startas: från en ny bild eller från bilden med det angivna indexet. Om **true** startar data-infogning från ett tomt utrymme på bilden med det angivna indexet. Om **false** läggs data till de skapade bilderna. |

### Returvärde

Tillagda bilder

## ISlideCollection::InsertFromHtml(int32_t, System::String, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String, bool) metod


Skapar bilder från HTML-text och infogar dem i samlingen på den angivna positionen.

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::InsertFromHtml(int32_t index, System::String htmlText, System::SharedPtr<Import::IExternalResourceResolver> resolver, System::String uri, bool useSlideWithIndexAsStart)=0
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | **int32_t** | Position att infoga. |
| htmlText | [System::String](../../../system/string/) | HTML att lägga till. |
| resolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | Ett återuppringningsobjekt som används för att hämta externa objekt. Om denna parameter är null ignoreras alla externa objekt. |
| uri | [System::String](../../../system/string/) | En URI för den angivna HTML-koden. Används för att lösa relativa länkar. |
| useSlideWithIndexAsStart | **bool** | Denna flagga bestämmer hur infogningen ska startas: från en ny bild eller från bilden med det angivna indexet. Om **true** startar data-infogning från ett tomt utrymme på bilden med det angivna indexet. Om **false** läggs data till de skapade bilderna. |

### Returvärde

Tillagda bilder.

## ISlideCollection::InsertFromHtml(int32_t, System::SharedPtr\<System::IO::Stream\>, bool) metod


Skapar bilder från HTML-text och infogar dem i samlingen på den angivna positionen.

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::InsertFromHtml(int32_t index, System::SharedPtr<System::IO::Stream> htmlStream, bool useSlideWithIndexAsStart)=0
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | **int32_t** | Position att infoga. |
| htmlStream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Ett Stream-objekt som kommer att användas som källa för en HTML-fil. |
| useSlideWithIndexAsStart | **bool** | Denna flagga bestämmer hur infogningen ska startas: från en ny bild eller från bilden med det angivna indexet. Om **true** startar data-infogning från ett tomt utrymme på bilden med det angivna indexet. Om **false** läggs data till de skapade bilderna. |

### Returvärde

Tillagda bilder

## ISlideCollection::InsertFromHtml(int32_t, System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String, bool) metod


Skapar bilder från HTML-text och infogar dem i samlingen på den angivna positionen.

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::InsertFromHtml(int32_t index, System::SharedPtr<System::IO::Stream> htmlStream, System::SharedPtr<Import::IExternalResourceResolver> resolver, System::String uri, bool useSlideWithIndexAsStart)=0
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | **int32_t** | Position att infoga. |
| htmlStream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Ett Stream-objekt som kommer att användas som källa för en HTML-fil. |
| resolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | Ett återuppringningsobjekt som används för att hämta externa objekt. Om denna parameter är null ignoreras alla externa objekt. |
| uri | [System::String](../../../system/string/) | En URI för den angivna HTML-koden. Används för att lösa relativa länkar. |
| useSlideWithIndexAsStart | **bool** | Denna flagga bestämmer hur infogningen ska startas: från en ny bild eller från bilden med det angivna indexet. Om **true** startar data-infogning från ett tomt utrymme på bilden med det angivna indexet. Om **false** läggs data till de skapade bilderna. |

### Returvärde

Tillagda bilder.

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