---
title: AddFromHtml()
second_title: Aspose.Slides für C++ API-Referenz
description: Erstellt Folien aus HTML-Text und fügt sie am Ende der Sammlung hinzu.
type: docs
weight: 196
url: /de/aspose.slides/slidecollection/addfromhtml/
---
## SlideCollection::AddFromHtml(System::String, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String) Methode

Erstellt Folien aus HTML-Text und fügt sie am Ende der Sammlung hinzu.

```cpp
System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::SlideCollection::AddFromHtml(System::String htmlText, System::SharedPtr<Import::IExternalResourceResolver> resolver, System::String uri) override
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| htmlText | [System::String](../../../system/string/) | Html to add. |
| resolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | A callback object used to fetch external objects. If this parameter is null all external objects will be ignored. |
| uri | [System::String](../../../system/string/) | An URI of the specified HTML. Used to resolve relative links. |

### Rückgabewert

Added slides.

## SlideCollection::AddFromHtml(System::String) Methode

Erstellt Folien aus HTML-Text und fügt sie am Ende der Sammlung hinzu.

```cpp
System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::SlideCollection::AddFromHtml(System::String htmlText) override
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| htmlText | [System::String](../../../system/string/) | Html to add. |

### Rückgabewert

Added slides

## SlideCollection::AddFromHtml(System::SharedPtr\<System::IO::TextReader\>, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String) Methode

Erstellt Folien aus HTML-Text und fügt sie am Ende der Sammlung hinzu.

```cpp
System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::SlideCollection::AddFromHtml(System::SharedPtr<System::IO::TextReader> htmlReader, System::SharedPtr<Import::IExternalResourceResolver> resolver, System::String uri) override
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| htmlReader | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::TextReader](../../../system.io/textreader/)\> | TextReader object which will be used as a source of a HTML file. |
| resolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | A callback object used to fetch external objects. If this parameter is null all external objects will be ignored. |
| uri | [System::String](../../../system/string/) | An URI of the specified HTML. Used to resolve relative links. |

### Rückgabewert

Added slides.

## SlideCollection::AddFromHtml(System::SharedPtr\<System::IO::TextReader\>) Methode

Erstellt Folien aus HTML-Text und fügt sie am Ende der Sammlung hinzu.

```cpp
System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::SlideCollection::AddFromHtml(System::SharedPtr<System::IO::TextReader> htmlReader) override
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| htmlReader | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::TextReader](../../../system.io/textreader/)\> | TextReader object which will be used as a source of a HTML file. |

### Rückgabewert

Added slides

## SlideCollection::AddFromHtml(System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String) Methode

Erstellt Folien aus HTML-Text und fügt sie am Ende der Sammlung hinzu.

```cpp
System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::SlideCollection::AddFromHtml(System::SharedPtr<System::IO::Stream> htmlStream, System::SharedPtr<Import::IExternalResourceResolver> resolver, System::String uri) override
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| htmlStream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | A Stream object which will be used as a source of a HTML file. |
| resolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | A callback object used to fetch external objects. If this parameter is null all external objects will be ignored. |
| uri | [System::String](../../../system/string/) | An URI of the specified HTML. Used to resolve relative links. |

### Rückgabewert

Added slides.

## SlideCollection::AddFromHtml(System::SharedPtr\<System::IO::Stream\>) Methode

Erstellt Folien aus HTML-Text und fügt sie am Ende der Sammlung hinzu.

```cpp
System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::SlideCollection::AddFromHtml(System::SharedPtr<System::IO::Stream> htmlStream) override
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| htmlStream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | A Stream object which will be used as a source of a HTML file. |

### Rückgabewert

Added slides
## Hinweise

```cpp
// Erstelle eine Instanz der Presentation-Klasse.
auto presentation = System::MakeObject<Presentation>();

{
    auto htmlStream = System::IO::File::OpenRead(u"page.html");

    // Rufe die AddFromHtml-Methode auf und übergebe die HTML-Datei.
    presentation->get_Slides()->AddFromHtml(htmlStream);
}

// Verwende die Save-Methode, um die Datei als PowerPoint-Dokument zu speichern.
presentation->Save(u"MyPresentation.pptx", SaveFormat::Pptx);
```

## Siehe auch

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [ISlide](../../islide/)
* Klasse [String](../../../system/string/)
* Klasse [IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)
* Klasse [SlideCollection](../)
* Klasse [TextReader](../../../system.io/textreader/)
* Klasse [Stream](../../../system.io/stream/)
* Namensraum [Aspose::Slides](../../)
* Bibliothek [Aspose.Slides](../../../)