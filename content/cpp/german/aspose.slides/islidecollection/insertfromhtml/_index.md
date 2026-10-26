---
title: InsertFromHtml()
second_title: Aspose.Slides für C++ API-Referenz
description: Erstellt Folien aus HTML-Text und fügt sie an der angegebenen Position in die Sammlung ein.
type: docs
weight: 157
url: /de/aspose.slides/islidecollection/insertfromhtml/
---
## ISlideCollection::InsertFromHtml(int32_t, System::String, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String) Methode


Erstellt Folien aus HTML-Text und fügt sie an der angegebenen Position in die Sammlung ein.

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::InsertFromHtml(int32_t index, System::String htmlText, System::SharedPtr<Import::IExternalResourceResolver> resolver, System::String uri)=0
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | **int32_t** | Position zum Einfügen. |
| htmlText | [System::String](../../../system/string/) | HTML zum Hinzufügen. |
| resolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | Ein Rückruffunktionsobjekt, das zum Abrufen externer Objekte verwendet wird. Wenn dieser Parameter null ist, werden alle externen Objekte ignoriert. |
| uri | [System::String](../../../system/string/) | Ein URI des angegebenen HTML. Wird zum Auflösen relativer Links verwendet. |

### Rückgabewert

Hinzugefügte Folien.

## ISlideCollection::InsertFromHtml(int32_t, System::String) Methode


Erstellt Folien aus HTML-Text und fügt sie an der angegebenen Position in die Sammlung ein.

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::InsertFromHtml(int32_t index, System::String htmlText)=0
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | **int32_t** | Position zum Einfügen. |
| htmlText | [System::String](../../../system/string/) | HTML zum Hinzufügen. |

### Rückgabewert

Hinzugefügte Folien

## ISlideCollection::InsertFromHtml(int32_t, System::SharedPtr\<System::IO::TextReader\>, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String) Methode


Erstellt Folien aus HTML-Text und fügt sie an der angegebenen Position in die Sammlung ein.

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::InsertFromHtml(int32_t index, System::SharedPtr<System::IO::TextReader> htmlReader, System::SharedPtr<Import::IExternalResourceResolver> resolver, System::String uri)=0
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | **int32_t** | Position zum Einfügen. |
| htmlReader | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::TextReader](../../../system.io/textreader/)\> | TextReader-Objekt, das als Quelle einer HTML-Datei verwendet wird. |
| resolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | Ein Rückruffunktionsobjekt, das zum Abrufen externer Objekte verwendet wird. Wenn dieser Parameter null ist, werden alle externen Objekte ignoriert. |
| uri | [System::String](../../../system/string/) | Ein URI des angegebenen HTML. Wird zum Auflösen relativer Links verwendet. |

### Rückgabewert

Hinzugefügte Folien.

## ISlideCollection::InsertFromHtml(int32_t, System::SharedPtr\<System::IO::TextReader\>) Methode


Erstellt Folien aus HTML-Text und fügt sie an der angegebenen Position in die Sammlung ein.

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::InsertFromHtml(int32_t index, System::SharedPtr<System::IO::TextReader> htmlReader)=0
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | **int32_t** | Position zum Einfügen. |
| htmlReader | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::TextReader](../../../system.io/textreader/)\> | TextReader-Objekt, das als Quelle einer HTML-Datei verwendet wird. |

### Rückgabewert

Hinzugefügte Folien

## ISlideCollection::InsertFromHtml(int32_t, System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String) Methode


Erstellt Folien aus HTML-Text und fügt sie an der angegebenen Position in die Sammlung ein.

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::InsertFromHtml(int32_t index, System::SharedPtr<System::IO::Stream> htmlStream, System::SharedPtr<Import::IExternalResourceResolver> resolver, System::String uri)=0
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | **int32_t** | Position zum Einfügen. |
| htmlStream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Ein Stream-Objekt, das als Quelle einer HTML-Datei verwendet wird. |
| resolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | Ein Rückruffunktionsobjekt, das zum Abrufen externer Objekte verwendet wird. Wenn dieser Parameter null ist, werden alle externen Objekte ignoriert. |
| uri | [System::String](../../../system/string/) | Ein URI des angegebenen HTML. Wird zum Auflösen relativer Links verwendet. |

### Rückgabewert

Hinzugefügte Folien.

## ISlideCollection::InsertFromHtml(int32_t, System::SharedPtr\<System::IO::Stream\>) Methode


Erstellt Folien aus HTML-Text und fügt sie an der angegebenen Position in die Sammlung ein.

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::InsertFromHtml(int32_t index, System::SharedPtr<System::IO::Stream> htmlStream)=0
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | **int32_t** | Position zum Einfügen. |
| htmlStream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Ein Stream-Objekt, das als Quelle einer HTML-Datei verwendet wird. |

### Rückgabewert

Hinzugefügte Folien

## ISlideCollection::InsertFromHtml(int32_t, System::String, bool) Methode


Erstellt Folien aus HTML-Text und fügt sie an der angegebenen Position in die Sammlung ein.

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::InsertFromHtml(int32_t index, System::String htmlText, bool useSlideWithIndexAsStart)=0
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | **int32_t** | Position zum Einfügen. |
| htmlText | [System::String](../../../system/string/) | HTML zum Hinzufügen. |
| useSlideWithIndexAsStart | **bool** | Dieses Flag bestimmt, wie das Einfügen gestartet wird: entweder von einer neuen Folie oder von der Folie mit dem angegebenen Index. Wenn **true**, beginnt das Einfügen der Daten an einem leeren Platz auf der Folie mit dem angegebenen Index. Wenn **false**, werden die Daten zu den erstellten Folien hinzugefügt. |

### Rückgabewert

Hinzugefügte Folien

## ISlideCollection::InsertFromHtml(int32_t, System::String, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String, bool) Methode


Erstellt Folien aus HTML-Text und fügt sie an der angegebenen Position in die Sammlung ein.

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::InsertFromHtml(int32_t index, System::String htmlText, System::SharedPtr<Import::IExternalResourceResolver> resolver, System::String uri, bool useSlideWithIndexAsStart)=0
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | **int32_t** | Position zum Einfügen. |
| htmlText | [System::String](../../../system/string/) | HTML zum Hinzufügen. |
| resolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | Ein Rückruffunktionsobjekt, das zum Abrufen externer Objekte verwendet wird. Wenn dieser Parameter null ist, werden alle externen Objekte ignoriert. |
| uri | [System::String](../../../system/string/) | Ein URI des angegebenen HTML. Wird zum Auflösen relativer Links verwendet. |
| useSlideWithIndexAsStart | **bool** | Dieses Flag bestimmt, wie das Einfügen gestartet wird: entweder von einer neuen Folie oder von der Folie mit dem angegebenen Index. Wenn **true**, beginnt das Einfügen der Daten an einem leeren Platz auf der Folie mit dem angegebenen Index. Wenn **false**, werden die Daten zu den erstellten Folien hinzugefügt. |

### Rückgabewert

Hinzugefügte Folien.

## ISlideCollection::InsertFromHtml(int32_t, System::SharedPtr\<System::IO::Stream\>, bool) Methode


Erstellt Folien aus HTML-Text und fügt sie an der angegebenen Position in die Sammlung ein.

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::InsertFromHtml(int32_t index, System::SharedPtr<System::IO::Stream> htmlStream, bool useSlideWithIndexAsStart)=0
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | **int32_t** | Position zum Einfügen. |
| htmlStream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Ein Stream-Objekt, das als Quelle einer HTML-Datei verwendet wird. |
| useSlideWithIndexAsStart | **bool** | Dieses Flag bestimmt, wie das Einfügen gestartet wird: entweder von einer neuen Folie oder von der Folie mit dem angegebenen Index. Wenn **true**, beginnt das Einfügen der Daten an einem leeren Platz auf der Folie mit dem angegebenen Index. Wenn **false**, werden die Daten zu den erstellten Folien hinzugefügt. |

### Rückgabewert

Hinzugefügte Folien

## ISlideCollection::InsertFromHtml(int32_t, System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String, bool) Methode


Erstellt Folien aus HTML-Text und fügt sie an der angegebenen Position in die Sammlung ein.

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::InsertFromHtml(int32_t index, System::SharedPtr<System::IO::Stream> htmlStream, System::SharedPtr<Import::IExternalResourceResolver> resolver, System::String uri, bool useSlideWithIndexAsStart)=0
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | **int32_t** | Position zum Einfügen. |
| htmlStream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Ein Stream-Objekt, das als Quelle einer HTML-Datei verwendet wird. |
| resolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | Ein Rückruffunktionsobjekt, das zum Abrufen externer Objekte verwendet wird. Wenn dieser Parameter null ist, werden alle externen Objekte ignoriert. |
| uri | [System::String](../../../system/string/) | Ein URI des angegebenen HTML. Wird zum Auflösen relativer Links verwendet. |
| useSlideWithIndexAsStart | **bool** | Dieses Flag bestimmt, wie das Einfügen gestartet wird: entweder von einer neuen Folie oder von der Folie mit dem angegebenen Index. Wenn **true**, beginnt das Einfügen der Daten an einem leeren Platz auf der Folie mit dem angegebenen Index. Wenn **false**, werden die Daten zu den erstellten Folien hinzugefügt. |

### Rückgabewert

Hinzugefügte Folien.

## Siehe auch

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