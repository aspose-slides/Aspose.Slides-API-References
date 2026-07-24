---
title: InsertFromHtml()
second_title: Aspose.Slides für C++ API-Referenz
description: Erstellt Folien aus HTML-Text und fügt sie an der angegebenen Position in die Sammlung ein.
type: docs
weight: 209
url: /de/aspose.slides/slidecollection/insertfromhtml/
---
## SlideCollection::InsertFromHtml(int32_t, System::String, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String) Methode


Erstellt Folien aus HTML-Text und fügt sie an der angegebenen Position in die Sammlung ein.

```cpp
System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::SlideCollection::InsertFromHtml(int32_t index, System::String htmlText, System::SharedPtr<Import::IExternalResourceResolver> resolver, System::String uri) override
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | **int32_t** | Position zum Einfügen. |
| htmlText | [System::String](../../../system/string/) | Hinzuzufügender HTML. |
| resolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | Ein Callback-Objekt, das zum Abrufen externer Objekte verwendet wird. Wenn dieser Parameter null ist, werden alle externen Objekte ignoriert. |
| uri | [System::String](../../../system/string/) | Eine URI des angegebenen HTML. Wird zum Auflösen relativer Links verwendet. |

### Rückgabewert

Hinzugefügte Folien.

## SlideCollection::InsertFromHtml(int32_t, System::String, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String, bool) Methode


Erstellt Folien aus HTML-Text und fügt sie an der angegebenen Position in die Sammlung ein.

```cpp
System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::SlideCollection::InsertFromHtml(int32_t index, System::String htmlText, System::SharedPtr<Import::IExternalResourceResolver> resolver, System::String uri, bool useSlideWithIndexAsStart) override
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | **int32_t** | Position zum Einfügen. |
| htmlText | [System::String](../../../system/string/) | Hinzuzufügender HTML. |
| resolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | Ein Callback-Objekt, das zum Abrufen externer Objekte verwendet wird. Wenn dieser Parameter null ist, werden alle externen Objekte ignoriert. |
| uri | [System::String](../../../system/string/) | Eine URI des angegebenen HTML. Wird zum Auflösen relativer Links verwendet. |
| useSlideWithIndexAsStart | **bool** | Dieses Flag bestimmt, wie das Einfügen gestartet wird: von einer neuen Folie oder von der Folie mit dem angegebenen Index. Wenn **true**, beginnt das Einfügen in einem leeren Bereich der Folie mit dem angegebenen Index. Wenn **false**, werden die Daten zu den erstellten Folien hinzugefügt. |

### Rückgabewert

Hinzugefügte Folien.

## SlideCollection::InsertFromHtml(int32_t, System::String) Methode


Erstellt Folien aus HTML-Text und fügt sie an der angegebenen Position in die Sammlung ein.

```cpp
System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::SlideCollection::InsertFromHtml(int32_t index, System::String htmlText) override
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | **int32_t** | Position zum Einfügen. |
| htmlText | [System::String](../../../system/string/) | Hinzuzufügender HTML. |

### Rückgabewert

Hinzugefügte Folien

## SlideCollection::InsertFromHtml(int32_t, System::String, bool) Methode


Erstellt Folien aus HTML-Text und fügt sie an der angegebenen Position in die Sammlung ein.

```cpp
System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::SlideCollection::InsertFromHtml(int32_t index, System::String htmlText, bool useSlideWithIndexAsStart) override
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | **int32_t** | Position zum Einfügen. |
| htmlText | [System::String](../../../system/string/) | Hinzuzufügender HTML. |
| useSlideWithIndexAsStart | **bool** | Dieses Flag bestimmt, wie das Einfügen gestartet wird: von einer neuen Folie oder von der Folie mit dem angegebenen Index. Wenn **true**, beginnt das Einfügen in einem leeren Bereich der Folie mit dem angegebenen Index. Wenn **false**, werden die Daten zu den erstellten Folien hinzugefügt. |

### Rückgabewert

Hinzugefügte Folien

## SlideCollection::InsertFromHtml(int32_t, System::SharedPtr\<System::IO::TextReader\>, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String) Methode


Erstellt Folien aus HTML-Text und fügt sie an der angegebenen Position in die Sammlung ein.

```cpp
System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::SlideCollection::InsertFromHtml(int32_t index, System::SharedPtr<System::IO::TextReader> htmlReader, System::SharedPtr<Import::IExternalResourceResolver> resolver, System::String uri) override
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | **int32_t** | Position zum Einfügen. |
| htmlReader | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::TextReader](../../../system.io/textreader/)\> | TextReader-Objekt, das als Quelle einer HTML-Datei verwendet wird. |
| resolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | Ein Callback-Objekt, das zum Abrufen externer Objekte verwendet wird. Wenn dieser Parameter null ist, werden alle externen Objekte ignoriert. |
| uri | [System::String](../../../system/string/) | Eine URI des angegebenen HTML. Wird zum Auflösen relativer Links verwendet. |

### Rückgabewert

Hinzugefügte Folien.

## SlideCollection::InsertFromHtml(int32_t, System::SharedPtr\<System::IO::TextReader\>) Methode


Erstellt Folien aus HTML-Text und fügt sie an der angegebenen Position in die Sammlung ein.

```cpp
System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::SlideCollection::InsertFromHtml(int32_t index, System::SharedPtr<System::IO::TextReader> htmlReader) override
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | **int32_t** | Position zum Einfügen. |
| htmlReader | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::TextReader](../../../system.io/textreader/)\> | TextReader-Objekt, das als Quelle einer HTML-Datei verwendet wird. |

### Rückgabewert

Hinzugefügte Folien

## SlideCollection::InsertFromHtml(int32_t, System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String) Methode


Erstellt Folien aus HTML-Text und fügt sie an der angegebenen Position in die Sammlung ein.

```cpp
System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::SlideCollection::InsertFromHtml(int32_t index, System::SharedPtr<System::IO::Stream> htmlStream, System::SharedPtr<Import::IExternalResourceResolver> resolver, System::String uri) override
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | **int32_t** | Position zum Einfügen. |
| htmlStream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Stream-Objekt, das als Quelle einer HTML-Datei verwendet wird. |
| resolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | Ein Callback-Objekt, das zum Abrufen externer Objekte verwendet wird. Wenn dieser Parameter null ist, werden alle externen Objekte ignoriert. |
| uri | [System::String](../../../system/string/) | Eine URI des angegebenen HTML. Wird zum Auflösen relativer Links verwendet. |

### Rückgabewert

Hinzugefügte Folien.

## SlideCollection::InsertFromHtml(int32_t, System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String, bool) Methode


Erstellt Folien aus HTML-Text und fügt sie an der angegebenen Position in die Sammlung ein.

```cpp
System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::SlideCollection::InsertFromHtml(int32_t index, System::SharedPtr<System::IO::Stream> htmlStream, System::SharedPtr<Import::IExternalResourceResolver> resolver, System::String uri, bool useSlideWithIndexAsStart) override
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | **int32_t** | Position zum Einfügen. |
| htmlStream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Stream-Objekt, das als Quelle einer HTML-Datei verwendet wird. |
| resolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | Ein Callback-Objekt, das zum Abrufen externer Objekte verwendet wird. Wenn dieser Parameter null ist, werden alle externen Objekte ignoriert. |
| uri | [System::String](../../../system/string/) | Eine URI des angegebenen HTML. Wird zum Auflösen relativer Links verwendet. |
| useSlideWithIndexAsStart | **bool** | Dieses Flag bestimmt, wie das Einfügen gestartet wird: von einer neuen Folie oder von der Folie mit dem angegebenen Index. Wenn **true**, beginnt das Einfügen in einem leeren Bereich der Folie mit dem angegebenen Index. Wenn **false**, werden die Daten zu den erstellten Folien hinzugefügt. |

### Rückgabewert

Hinzugefügte Folien.

## SlideCollection::InsertFromHtml(int32_t, System::SharedPtr\<System::IO::Stream\>) Methode


Erstellt Folien aus HTML-Text und fügt sie an der angegebenen Position in die Sammlung ein.

```cpp
System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::SlideCollection::InsertFromHtml(int32_t index, System::SharedPtr<System::IO::Stream> htmlStream) override
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | **int32_t** | Position zum Einfügen. |
| htmlStream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Stream-Objekt, das als Quelle einer HTML-Datei verwendet wird. |

### Rückgabewert

Hinzugefügte Folien

## SlideCollection::InsertFromHtml(int32_t, System::SharedPtr\<System::IO::Stream\>, bool) Methode


Erstellt Folien aus HTML-Text und fügt sie an der angegebenen Position in die Sammlung ein.

```cpp
System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::SlideCollection::InsertFromHtml(int32_t index, System::SharedPtr<System::IO::Stream> htmlStream, bool useSlideWithIndexAsStart) override
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | **int32_t** | Position zum Einfügen. |
| htmlStream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Stream-Objekt, das als Quelle einer HTML-Datei verwendet wird. |
| useSlideWithIndexAsStart | **bool** | Dieses Flag bestimmt, wie das Einfügen gestartet wird: von einer neuen Folie oder von der Folie mit dem angegebenen Index. Wenn **true**, beginnt das Einfügen in einem leeren Bereich der Folie mit dem angegebenen Index. Wenn **false**, werden die Daten zu den erstellten Folien hinzugefügt. |

### Rückgabewert

Hinzugefügte Folien

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
* Library [Aspose.Slides](../../../)