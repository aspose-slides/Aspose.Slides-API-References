---
title: InsertFromHtml()
second_title: Aspose.Slides voor C++ API-referentie
description: Maakt dia's van HTML-tekst en voegt ze toe aan de collectie op de opgegeven positie.
type: docs
weight: 209
url: /nl/aspose.slides/slidecollection/insertfromhtml/
---
## SlideCollection::InsertFromHtml(int32_t, System::String, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String) method


Maakt dia's van HTML-tekst en voegt ze toe aan de collectie op de opgegeven positie.

```cpp
System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::SlideCollection::InsertFromHtml(int32_t index, System::String htmlText, System::SharedPtr<Import::IExternalResourceResolver> resolver, System::String uri) override
```


### Argumenten

| Parameter | Type | Description |
| --- | --- | --- |
| index | **int32_t** | Positie om in te voegen. |
| htmlText | [System::String](../../../system/string/) | Html om toe te voegen. |
| resolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | Een callback-object dat wordt gebruikt om externe objecten op te halen. Als deze parameter null is, worden alle externe objecten genegeerd. |
| uri | [System::String](../../../system/string/) | Een URI van de opgegeven HTML. Wordt gebruikt om relatieve koppelingen op te lossen. |

### Retourwaarde

Toegevoegde dia's.

## SlideCollection::InsertFromHtml(int32_t, System::String, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String, bool) method


Maakt dia's van HTML-tekst en voegt ze toe aan de collectie op de opgegeven positie.

```cpp
System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::SlideCollection::InsertFromHtml(int32_t index, System::String htmlText, System::SharedPtr<Import::IExternalResourceResolver> resolver, System::String uri, bool useSlideWithIndexAsStart) override
```


### Argumenten

| Parameter | Type | Description |
| --- | --- | --- |
| index | **int32_t** | Positie om in te voegen. |
| htmlText | [System::String](../../../system/string/) | Html om toe te voegen. |
| resolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | Een callback-object dat wordt gebruikt om externe objecten op te halen. Als deze parameter null is, worden alle externe objecten genegeerd. |
| uri | [System::String](../../../system/string/) | Een URI van de opgegeven HTML. Wordt gebruikt om relatieve koppelingen op te lossen. |
| useSlideWithIndexAsStart | **bool** | Deze vlag bepaalt hoe de invoeging wordt gestart: vanaf een nieuwe dia of vanaf de dia met de opgegeven index. Als **true**, dan start de gegevensinvoer vanaf een lege ruimte op de dia met de opgegeven index. Als **false**, dan worden gegevens toegevoegd aan de aangemaakte dia's. |

### Retourwaarde

Toegevoegde dia's.

## SlideCollection::InsertFromHtml(int32_t, System::String) method


Maakt dia's van HTML-tekst en voegt ze toe aan de collectie op de opgegeven positie.

```cpp
System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::SlideCollection::InsertFromHtml(int32_t index, System::String htmlText) override
```


### Argumenten

| Parameter | Type | Description |
| --- | --- | --- |
| index | **int32_t** | Positie om in te voegen. |
| htmlText | [System::String](../../../system/string/) | Html om toe te voegen. |

### Retourwaarde

Toegevoegde dia's

## SlideCollection::InsertFromHtml(int32_t, System::String, bool) method


Maakt dia's van HTML-tekst en voegt ze toe aan de collectie op de opgegeven positie.

```cpp
System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::SlideCollection::InsertFromHtml(int32_t index, System::String htmlText, bool useSlideWithIndexAsStart) override
```


### Argumenten

| Parameter | Type | Description |
| --- | --- | --- |
| index | **int32_t** | Positie om in te voegen. |
| htmlText | [System::String](../../../system/string/) | Html om toe te voegen. |
| useSlideWithIndexAsStart | **bool** | Deze vlag bepaalt hoe de invoeging wordt gestart: vanaf een nieuwe dia of vanaf de dia met de opgegeven index. Als **true**, dan start de gegevensinvoer vanaf een lege ruimte op de dia met de opgegeven index. Als **false**, dan worden gegevens toegevoegd aan de aangemaakte dia's. |

### Retourwaarde

Toegevoegde dia's

## SlideCollection::InsertFromHtml(int32_t, System::SharedPtr\<System::IO::TextReader\>, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String) method


Maakt dia's van HTML-tekst en voegt ze toe aan de collectie op de opgegeven positie.

```cpp
System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::SlideCollection::InsertFromHtml(int32_t index, System::SharedPtr<System::IO::TextReader> htmlReader, System::SharedPtr<Import::IExternalResourceResolver> resolver, System::String uri) override
```


### Argumenten

| Parameter | Type | Description |
| --- | --- | --- |
| index | **int32_t** | Positie om in te voegen. |
| htmlReader | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::TextReader](../../../system.io/textreader/)\> | TextReader-object dat als bron van een HTML-bestand wordt gebruikt. |
| resolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | Een callback-object dat wordt gebruikt om externe objecten op te halen. Als deze parameter null is, worden alle externe objecten genegeerd. |
| uri | [System::String](../../../system/string/) | Een URI van de opgegeven HTML. Wordt gebruikt om relatieve koppelingen op te lossen. |

### Retourwaarde

Toegevoegde dia's.

## SlideCollection::InsertFromHtml(int32_t, System::SharedPtr\<System::IO::TextReader\>) method


Maakt dia's van HTML-tekst en voegt ze toe aan de collectie op de opgegeven positie.

```cpp
System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::SlideCollection::InsertFromHtml(int32_t index, System::SharedPtr<System::IO::TextReader> htmlReader) override
```


### Argumenten

| Parameter | Type | Description |
| --- | --- | --- |
| index | **int32_t** | Positie om in te voegen. |
| htmlReader | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::TextReader](../../../system.io/textreader/)\> | TextReader-object dat als bron van een HTML-bestand wordt gebruikt. |

### Retourwaarde

Toegevoegde dia's

## SlideCollection::InsertFromHtml(int32_t, System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String) method


Maakt dia's van HTML-tekst en voegt ze toe aan de collectie op de opgegeven positie.

```cpp
System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::SlideCollection::InsertFromHtml(int32_t index, System::SharedPtr<System::IO::Stream> htmlStream, System::SharedPtr<Import::IExternalResourceResolver> resolver, System::String uri) override
```


### Argumenten

| Parameter | Type | Description |
| --- | --- | --- |
| index | **int32_t** | Positie om in te voegen. |
| htmlStream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Een Stream-object dat als bron van een HTML-bestand wordt gebruikt. |
| resolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | Een callback-object dat wordt gebruikt om externe objecten op te halen. Als deze parameter null is, worden alle externe objecten genegeerd. |
| uri | [System::String](../../../system/string/) | Een URI van de opgegeven HTML. Wordt gebruikt om relatieve koppelingen op te lossen. |

### Retourwaarde

Toegevoegde dia's.

## SlideCollection::InsertFromHtml(int32_t, System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String, bool) method


Maakt dia's van HTML-tekst en voegt ze toe aan de collectie op de opgegeven positie.

```cpp
System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::SlideCollection::InsertFromHtml(int32_t index, System::SharedPtr<System::IO::Stream> htmlStream, System::SharedPtr<Import::IExternalResourceResolver> resolver, System::String uri, bool useSlideWithIndexAsStart) override
```


### Argumenten

| Parameter | Type | Description |
| --- | --- | --- |
| index | **int32_t** | Positie om in te voegen. |
| htmlStream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Een Stream-object dat als bron van een HTML-bestand wordt gebruikt. |
| resolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | Een callback-object dat wordt gebruikt om externe objecten op te halen. Als deze parameter null is, worden alle externe objecten genegeerd. |
| uri | [System::String](../../../system/string/) | Een URI van de opgegeven HTML. Wordt gebruikt om relatieve koppelingen op te lossen. |
| useSlideWithIndexAsStart | **bool** | Deze vlag bepaalt hoe de invoeging wordt gestart: vanaf een nieuwe dia of vanaf de dia met de opgegeven index. Als **true**, dan start de gegevensinvoer vanaf een lege ruimte op de dia met de opgegeven index. Als **false**, dan worden gegevens toegevoegd aan de aangemaakte dia's. |

### Retourwaarde

Toegevoegde dia's.

## SlideCollection::InsertFromHtml(int32_t, System::SharedPtr\<System::IO::Stream\>) method


Maakt dia's van HTML-tekst en voegt ze toe aan de collectie op de opgegeven positie.

```cpp
System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::SlideCollection::InsertFromHtml(int32_t index, System::SharedPtr<System::IO::Stream> htmlStream) override
```


### Argumenten

| Parameter | Type | Description |
| --- | --- | --- |
| index | **int32_t** | Positie om in te voegen. |
| htmlStream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Een Stream-object dat als bron van een HTML-bestand wordt gebruikt. |

### Retourwaarde

Toegevoegde dia's

## SlideCollection::InsertFromHtml(int32_t, System::SharedPtr\<System::IO::Stream\>, bool) method


Maakt dia's van HTML-tekst en voegt ze toe aan de collectie op de opgegeven positie.

```cpp
System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::SlideCollection::InsertFromHtml(int32_t index, System::SharedPtr<System::IO::Stream> htmlStream, bool useSlideWithIndexAsStart) override
```


### Argumenten

| Parameter | Type | Description |
| --- | --- | --- |
| index | **int32_t** | Positie om in te voegen. |
| htmlStream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Een Stream-object dat als bron van een HTML-bestand wordt gebruikt. |
| useSlideWithIndexAsStart | **bool** | Deze vlag bepaalt hoe de invoeging wordt gestart: vanaf een nieuwe dia of vanaf de dia met de opgegeven index. Als **true**, dan start de gegevensinvoer vanaf een lege ruimte op de dia met de opgegeven index. Als **false**, dan worden gegevens toegevoegd aan de aangemaakte dia's. |

### Retourwaarde

Toegevoegde dia's

## Zie ook

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