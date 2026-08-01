---
title: AddFromHtml()
second_title: Aspose.Slides voor C++ API Referentie
description: Maakt dia's van HTML-tekst en voegt ze toe aan het einde van de collectie.
type: docs
weight: 144
url: /nl/aspose.slides/islidecollection/addfromhtml/
---
## ISlideCollection::AddFromHtml(System::String, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String) method

Maakt dia's van HTML-tekst en voegt ze toe aan het einde van de collectie.

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::AddFromHtml(System::String htmlText, System::SharedPtr<Import::IExternalResourceResolver> resolver, System::String uri)=0
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| htmlText | [System::String](../../../system/string/) | HTML om toe te voegen. |
| resolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | Een callback-object dat wordt gebruikt om externe objecten op te halen. Als deze parameter null is, worden alle externe objecten genegeerd. |
| uri | [System::String](../../../system/string/) | Een URI van de opgegeven HTML. Wordt gebruikt om relatieve koppelingen op te lossen. |

### Retourwaarde

Toegevoegde dia's.

## ISlideCollection::AddFromHtml(System::String) method

Maakt dia's van HTML-tekst en voegt ze toe aan het einde van de collectie.

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::AddFromHtml(System::String htmlText)=0
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| htmlText | [System::String](../../../system/string/) | HTML om toe te voegen. |

### Retourwaarde

Toegevoegde dia's

## ISlideCollection::AddFromHtml(System::SharedPtr\<System::IO::TextReader\>, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String) method

Maakt dia's van HTML-tekst en voegt ze toe aan het einde van de collectie.

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::AddFromHtml(System::SharedPtr<System::IO::TextReader> htmlReader, System::SharedPtr<Import::IExternalResourceResolver> resolver, System::String uri)=0
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| htmlReader | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::TextReader](../../../system.io/textreader/)\> | TextReader-object dat zal worden gebruikt als bron van een HTML-bestand. |
| resolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | Een callback-object dat wordt gebruikt om externe objecten op te halen. Als deze parameter null is, worden alle externe objecten genegeerd. |
| uri | [System::String](../../../system/string/) | Een URI van de opgegeven HTML. Wordt gebruikt om relatieve koppelingen op te lossen. |

### Retourwaarde

Toegevoegde dia's.

## ISlideCollection::AddFromHtml(System::SharedPtr\<System::IO::TextReader\>) method

Maakt dia's van HTML-tekst en voegt ze toe aan het einde van de collectie.

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::AddFromHtml(System::SharedPtr<System::IO::TextReader> htmlReader)=0
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| htmlReader | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::TextReader](../../../system.io/textreader/)\> | TextReader-object dat zal worden gebruikt als bron van een HTML-bestand. |

### Retourwaarde

Toegevoegde dia's

## ISlideCollection::AddFromHtml(System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String) method

Maakt dia's van HTML-tekst en voegt ze toe aan het einde van de collectie.

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::AddFromHtml(System::SharedPtr<System::IO::Stream> htmlStream, System::SharedPtr<Import::IExternalResourceResolver> resolver, System::String uri)=0
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| htmlStream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Een Stream-object dat zal worden gebruikt als bron van een HTML-bestand. |
| resolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | Een callback-object dat wordt gebruikt om externe objecten op te halen. Als deze parameter null is, worden alle externe objecten genegeerd. |
| uri | [System::String](../../../system/string/) | Een URI van de opgegeven HTML. Wordt gebruikt om relatieve koppelingen op te lossen. |

### Retourwaarde

Toegevoegde dia's.

## ISlideCollection::AddFromHtml(System::SharedPtr\<System::IO::Stream\>) method

Maakt dia's van HTML-tekst en voegt ze toe aan het einde van de collectie.

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::AddFromHtml(System::SharedPtr<System::IO::Stream> htmlStream)=0
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| htmlStream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Een Stream-object dat zal worden gebruikt als bron van een HTML-bestand. |

### Retourwaarde

Toegevoegde dia's

## Zie ook

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ISlide](../../islide/)
* Class [String](../../../system/string/)
* Class [IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)
* Class [ISlideCollection](../)
* Class [TextReader](../../../system.io/textreader/)
* Class [Stream](../../../system.io/stream/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)