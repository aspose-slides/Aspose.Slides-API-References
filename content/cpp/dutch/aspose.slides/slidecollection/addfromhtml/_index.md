---
title: AddFromHtml()
second_title: Aspose.Slides voor C++ API-referentie
description: Maakt dia's aan vanuit HTML-tekst en voegt ze toe aan het einde van de collectie.
type: docs
weight: 196
url: /nl/aspose.slides/slidecollection/addfromhtml/
---
## SlideCollection::AddFromHtml(System::String, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String) method


Maakt dia's vanuit HTML-tekst en voegt ze toe aan het einde van de collectie.

```cpp
System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::SlideCollection::AddFromHtml(System::String htmlText, System::SharedPtr<Import::IExternalResourceResolver> resolver, System::String uri) override
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| htmlText | [System::String](../../../system/string/) | Html om toe te voegen. |
| resolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | Een callback-object dat wordt gebruikt om externe objecten op te halen. Als deze parameter nul is, worden alle externe objecten genegeerd. |
| uri | [System::String](../../../system/string/) | Een URI van de opgegeven HTML. Wordt gebruikt om relatieve koppelingen op te lossen. |

### Retourwaarde

Toegevoegde dia's.

## SlideCollection::AddFromHtml(System::String) method


Maakt dia's vanuit HTML-tekst en voegt ze toe aan het einde van de collectie.

```cpp
System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::SlideCollection::AddFromHtml(System::String htmlText) override
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| htmlText | [System::String](../../../system/string/) | Html om toe te voegen. |

### Retourwaarde

Toegevoegde dia's

## SlideCollection::AddFromHtml(System::SharedPtr\<System::IO::TextReader\>, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String) method


Maakt dia's vanuit HTML-tekst en voegt ze toe aan het einde van de collectie.

```cpp
System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::SlideCollection::AddFromHtml(System::SharedPtr<System::IO::TextReader> htmlReader, System::SharedPtr<Import::IExternalResourceResolver> resolver, System::String uri) override
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| htmlReader | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::TextReader](../../../system.io/textreader/)\> | TextReader-object dat wordt gebruikt als bron van een HTML-bestand. |
| resolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | Een callback-object dat wordt gebruikt om externe objecten op te halen. Als deze parameter nul is, worden alle externe objecten genegeerd. |
| uri | [System::String](../../../system/string/) | Een URI van de opgegeven HTML. Wordt gebruikt om relatieve koppelingen op te lossen. |

### Retourwaarde

Toegevoegde dia's.

## SlideCollection::AddFromHtml(System::SharedPtr\<System::IO::TextReader\>) method


Maakt dia's vanuit HTML-tekst en voegt ze toe aan het einde van de collectie.

```cpp
System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::SlideCollection::AddFromHtml(System::SharedPtr<System::IO::TextReader> htmlReader) override
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| htmlReader | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::TextReader](../../../system.io/textreader/)\> | TextReader-object dat wordt gebruikt als bron van een HTML-bestand. |

### Retourwaarde

Toegevoegde dia's

## SlideCollection::AddFromHtml(System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String) method


Maakt dia's vanuit HTML-tekst en voegt ze toe aan het einde van de collectie.

```cpp
System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::SlideCollection::AddFromHtml(System::SharedPtr<System::IO::Stream> htmlStream, System::SharedPtr<Import::IExternalResourceResolver> resolver, System::String uri) override
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| htmlStream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Een Stream-object dat wordt gebruikt als bron van een HTML-bestand. |
| resolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | Een callback-object dat wordt gebruikt om externe objecten op te halen. Als deze parameter nul is, worden alle externe objecten genegeerd. |
| uri | [System::String](../../../system/string/) | Een URI van de opgegeven HTML. Wordt gebruikt om relatieve koppelingen op te lossen. |

### Retourwaarde

Toegevoegde dia's.

## SlideCollection::AddFromHtml(System::SharedPtr\<System::IO::Stream\>) method


Maakt dia's vanuit HTML-tekst en voegt ze toe aan het einde van de collectie.

```cpp
System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::SlideCollection::AddFromHtml(System::SharedPtr<System::IO::Stream> htmlStream) override
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| htmlStream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Een Stream-object dat wordt gebruikt als bron van een HTML-bestand. |

### Retourwaarde

Toegevoegde dia's
## Opmerkingen




```cpp
// Maak een instantie van de Presentation-klasse.
auto presentation = System::MakeObject<Presentation>();

{
    auto htmlStream = System::IO::File::OpenRead(u"page.html");

    // Roep de AddFromHtml-methode aan en geef het HTML-bestand door.
    presentation->get_Slides()->AddFromHtml(htmlStream);
}

// Gebruik de Save-methode om het bestand op te slaan als een PowerPoint-document.
presentation->Save(u"MyPresentation.pptx", SaveFormat::Pptx);
```

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