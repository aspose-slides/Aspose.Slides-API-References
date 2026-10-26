---
title: InsertFromHtml()
second_title: Aspose.Slides voor C++ API-referentie
description: Maakt dia's aan vanuit HTML-tekst en voegt ze toe aan de collectie op de opgegeven positie.
type: docs
weight: 157
url: /nl/aspose.slides/islidecollection/insertfromhtml/
---
## ISlideCollection::InsertFromHtml(int32_t, System::String, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String) methode


Maakt dia's aan vanuit HTML-tekst en voegt ze toe aan de collectie op de opgegeven positie.

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::InsertFromHtml(int32_t index, System::String htmlText, System::SharedPtr<Import::IExternalResourceResolver> resolver, System::String uri)=0
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | **int32_t** | Positie om in te voegen. |
| htmlText | [System::String](../../../system/string/) | HTML om toe te voegen. |
| resolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | Een callback-object dat wordt gebruikt om externe objecten op te halen. Als deze parameter null is, worden alle externe objecten genegeerd. |
| uri | [System::String](../../../system/string/) | Een URI van de opgegeven HTML. Wordt gebruikt om relatieve links te resolven. |

### Retourwaarde

Toegevoegde dia's.

## ISlideCollection::InsertFromHtml(int32_t, System::String) methode


Maakt dia's aan vanuit HTML-tekst en voegt ze toe aan de collectie op de opgegeven positie.

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::InsertFromHtml(int32_t index, System::String htmlText)=0
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | **int32_t** | Positie om in te voegen. |
| htmlText | [System::String](../../../system/string/) | HTML om toe te voegen. |

### Retourwaarde

Toegevoegde dia's

## ISlideCollection::InsertFromHtml(int32_t, System::SharedPtr\<System::IO::TextReader\>, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String) methode


Maakt dia's aan vanuit HTML-tekst en voegt ze toe aan de collectie op de opgegeven positie.

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::InsertFromHtml(int32_t index, System::SharedPtr<System::IO::TextReader> htmlReader, System::SharedPtr<Import::IExternalResourceResolver> resolver, System::String uri)=0
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | **int32_t** | Positie om in te voegen. |
| htmlReader | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::TextReader](../../../system.io/textreader/)\> | TextReader-object dat wordt gebruikt als bron van een HTML-bestand. |
| resolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | Een callback-object dat wordt gebruikt om externe objecten op te halen. Als deze parameter null is, worden alle externe objecten genegeerd. |
| uri | [System::String](../../../system/string/) | Een URI van de opgegeven HTML. Wordt gebruikt om relatieve links te resolven. |

### Retourwaarde

Toegevoegde dia's.

## ISlideCollection::InsertFromHtml(int32_t, System::SharedPtr\<System::IO::TextReader\>) methode


Maakt dia's aan vanuit HTML-tekst en voegt ze toe aan de collectie op de opgegeven positie.

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::InsertFromHtml(int32_t index, System::SharedPtr<System::IO::TextReader> htmlReader)=0
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | **int32_t** | Positie om in te voegen. |
| htmlReader | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::TextReader](../../../system.io/textreader/)\> | TextReader-object dat wordt gebruikt als bron van een HTML-bestand. |

### Retourwaarde

Toegevoegde dia's

## ISlideCollection::InsertFromHtml(int32_t, System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String) methode


Maakt dia's aan vanuit HTML-tekst en voegt ze toe aan de collectie op de opgegeven positie.

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::InsertFromHtml(int32_t index, System::SharedPtr<System::IO::Stream> htmlStream, System::SharedPtr<Import::IExternalResourceResolver> resolver, System::String uri)=0
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | **int32_t** | Positie om in te voegen. |
| htmlStream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Een Stream-object dat wordt gebruikt als bron van een HTML-bestand. |
| resolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | Een callback-object dat wordt gebruikt om externe objecten op te halen. Als deze parameter null is, worden alle externe objecten genegeerd. |
| uri | [System::String](../../../system/string/) | Een URI van de opgegeven HTML. Wordt gebruikt om relatieve links te resolven. |

### Retourwaarde

Toegevoegde dia's.

## ISlideCollection::InsertFromHtml(int32_t, System::SharedPtr\<System::IO::Stream\>) methode


Maakt dia's aan vanuit HTML-tekst en voegt ze toe aan de collectie op de opgegeven positie.

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::InsertFromHtml(int32_t index, System::SharedPtr<System::IO::Stream> htmlStream)=0
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | **int32_t** | Positie om in te voegen. |
| htmlStream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Een Stream-object dat wordt gebruikt als bron van een HTML-bestand. |

### Retourwaarde

Toegevoegde dia's

## ISlideCollection::InsertFromHtml(int32_t, System::String, bool) methode


Maakt dia's aan vanuit HTML-tekst en voegt ze toe aan de collectie op de opgegeven positie.

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::InsertFromHtml(int32_t index, System::String htmlText, bool useSlideWithIndexAsStart)=0
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | **int32_t** | Positie om in te voegen. |
| htmlText | [System::String](../../../system/string/) | HTML om toe te voegen. |
| useSlideWithIndexAsStart | **bool** | Deze vlag bepaalt hoe de invoeging start: vanaf een nieuwe dia of vanaf de dia met de opgegeven index. Als **true**, begint de gegevensinvoer op een lege ruimte op de dia met de opgegeven index. Als **false**, worden gegevens toegevoegd aan de gemaakte dia's. |

### Retourwaarde

Toegevoegde dia's

## ISlideCollection::InsertFromHtml(int32_t, System::String, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String, bool) methode


Maakt dia's aan vanuit HTML-tekst en voegt ze toe aan de collectie op de opgegeven positie.

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::InsertFromHtml(int32_t index, System::String htmlText, System::SharedPtr<Import::IExternalResourceResolver> resolver, System::String uri, bool useSlideWithIndexAsStart)=0
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | **int32_t** | Positie om in te voegen. |
| htmlText | [System::String](../../../system/string/) | HTML om toe te voegen. |
| resolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | Een callback-object dat wordt gebruikt om externe objecten op te halen. Als deze parameter null is, worden alle externe objecten genegeerd. |
| uri | [System::String](../../../system/string/) | Een URI van de opgegeven HTML. Wordt gebruikt om relatieve links te resolven. |
| useSlideWithIndexAsStart | **bool** | Deze vlag bepaalt hoe de invoeging start: vanaf een nieuwe dia of vanaf de dia met de opgegeven index. Als **true**, begint de gegevensinvoer op een lege ruimte op de dia met de opgegeven index. Als **false**, worden gegevens toegevoegd aan de gemaakte dia's. |

### Retourwaarde

Toegevoegde dia's.

## ISlideCollection::InsertFromHtml(int32_t, System::SharedPtr\<System::IO::Stream\>, bool) methode


Maakt dia's aan vanuit HTML-tekst en voegt ze toe aan de collectie op de opgegeven positie.

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::InsertFromHtml(int32_t index, System::SharedPtr<System::IO::Stream> htmlStream, bool useSlideWithIndexAsStart)=0
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | **int32_t** | Positie om in te voegen. |
| htmlStream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Een Stream-object dat wordt gebruikt als bron van een HTML-bestand. |
| useSlideWithIndexAsStart | **bool** | Deze vlag bepaalt hoe de invoeging start: vanaf een nieuwe dia of vanaf de dia met de opgegeven index. Als **true**, begint de gegevensinvoer op een lege ruimte op de dia met de opgegeven index. Als **false**, worden gegevens toegevoegd aan de gemaakte dia's. |

### Retourwaarde

Toegevoegde dia's

## ISlideCollection::InsertFromHtml(int32_t, System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String, bool) methode


Maakt dia's aan vanuit HTML-tekst en voegt ze toe aan de collectie op de opgegeven positie.

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::InsertFromHtml(int32_t index, System::SharedPtr<System::IO::Stream> htmlStream, System::SharedPtr<Import::IExternalResourceResolver> resolver, System::String uri, bool useSlideWithIndexAsStart)=0
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | **int32_t** | Positie om in te voegen. |
| htmlStream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Een Stream-object dat wordt gebruikt als bron van een HTML-bestand. |
| resolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | Een callback-object dat wordt gebruikt om externe objecten op te halen. Als deze parameter null is, worden alle externe objecten genegeerd. |
| uri | [System::String](../../../system/string/) | Een URI van de opgegeven HTML. Wordt gebruikt om relatieve links te resolven. |
| useSlideWithIndexAsStart | **bool** | Deze vlag bepaalt hoe de invoeging start: vanaf een nieuwe dia of vanaf de dia met de opgegeven index. Als **true**, begint de gegevensinvoer op een lege ruimte op de dia met de opgegeven index. Als **false**, worden gegevens toegevoegd aan de gemaakte dia's. |

### Retourwaarde

Toegevoegde dia's.

## Zie ook

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [ISlide](../../islide/)
* Klasse [String](../../../system/string/)
* Klasse [IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)
* Klasse [ISlideCollection](../)
* Klasse [TextReader](../../../system.io/textreader/)
* Klasse [Stream](../../../system.io/stream/)
* Naamruimte [Aspose::Slides](../../)
* Bibliotheek [Aspose.Slides](../../../)