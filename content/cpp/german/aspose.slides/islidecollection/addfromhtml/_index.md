---
title: AddFromHtml()
second_title: Aspose.Slides für C++ API-Referenz
description: Erstellt Folien aus HTML-Text und fügt sie am Ende der Sammlung hinzu.
type: docs
weight: 144
url: /de/aspose.slides/islidecollection/addfromhtml/
---
## ISlideCollection::AddFromHtml(System::String, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String) Methode


Erstellt Folien aus HTML-Text und fügt sie am Ende der Sammlung hinzu.

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::AddFromHtml(System::String htmlText, System::SharedPtr<Import::IExternalResourceResolver> resolver, System::String uri)=0
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| htmlText | [System::String](../../../system/string/) | HTML zum Hinzufügen. |
| resolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | Ein Rückrufobjekt, das zum Abrufen externer Objekte verwendet wird. Wenn dieser Parameter null ist, werden alle externen Objekte ignoriert. |
| uri | [System::String](../../../system/string/) | Ein URI des angegebenen HTML. Wird verwendet, um relative Links aufzulösen. |

### Rückgabewert

Hinzugefügte Folien.

## ISlideCollection::AddFromHtml(System::String) Methode


Erstellt Folien aus HTML-Text und fügt sie am Ende der Sammlung hinzu.

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::AddFromHtml(System::String htmlText)=0
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| htmlText | [System::String](../../../system/string/) | HTML zum Hinzufügen. |

### Rückgabewert

Hinzugefügte Folien

## ISlideCollection::AddFromHtml(System::SharedPtr\<System::IO::TextReader\>, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String) Methode


Erstellt Folien aus HTML-Text und fügt sie am Ende der Sammlung hinzu.

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::AddFromHtml(System::SharedPtr<System::IO::TextReader> htmlReader, System::SharedPtr<Import::IExternalResourceResolver> resolver, System::String uri)=0
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| htmlReader | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::TextReader](../../../system.io/textreader/)\> | TextReader-Objekt, das als Quelle einer HTML-Datei verwendet wird. |
| resolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | Ein Rückrufobjekt, das zum Abrufen externer Objekte verwendet wird. Wenn dieser Parameter null ist, werden alle externen Objekte ignoriert. |
| uri | [System::String](../../../system/string/) | Ein URI des angegebenen HTML. Wird verwendet, um relative Links aufzulösen. |

### Rückgabewert

Hinzugefügte Folien.

## ISlideCollection::AddFromHtml(System::SharedPtr\<System::IO::TextReader\>) Methode


Erstellt Folien aus HTML-Text und fügt sie am Ende der Sammlung hinzu.

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::AddFromHtml(System::SharedPtr<System::IO::TextReader> htmlReader)=0
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| htmlReader | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::TextReader](../../../system.io/textreader/)\> | TextReader-Objekt, das als Quelle einer HTML-Datei verwendet wird. |

### Rückgabewert

Hinzugefügte Folien

## ISlideCollection::AddFromHtml(System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String) Methode


Erstellt Folien aus HTML-Text und fügt sie am Ende der Sammlung hinzu.

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::AddFromHtml(System::SharedPtr<System::IO::Stream> htmlStream, System::SharedPtr<Import::IExternalResourceResolver> resolver, System::String uri)=0
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| htmlStream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Stream-Objekt, das als Quelle einer HTML-Datei verwendet wird. |
| resolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | Ein Rückrufobjekt, das zum Abrufen externer Objekte verwendet wird. Wenn dieser Parameter null ist, werden alle externen Objekte ignoriert. |
| uri | [System::String](../../../system/string/) | Ein URI des angegebenen HTML. Wird verwendet, um relative Links aufzulösen. |

### Rückgabewert

Hinzugefügte Folien.

## ISlideCollection::AddFromHtml(System::SharedPtr\<System::IO::Stream\>) Methode


Erstellt Folien aus HTML-Text und fügt sie am Ende der Sammlung hinzu.

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::AddFromHtml(System::SharedPtr<System::IO::Stream> htmlStream)=0
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| htmlStream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Stream-Objekt, das als Quelle einer HTML-Datei verwendet wird. |

### Rückgabewert

Hinzugefügte Folien

## Siehe auch

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [ISlide](../../islide/)
* Klasse [String](../../../system/string/)
* Klasse [IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)
* Klasse [ISlideCollection](../)
* Klasse [TextReader](../../../system.io/textreader/)
* Klasse [Stream](../../../system.io/stream/)
* Namensraum [Aspose::Slides](../../)
* Bibliothek [Aspose.Slides](../../../)