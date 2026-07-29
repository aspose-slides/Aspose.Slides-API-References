---
title: InsertFromHtml()
second_title: Aspose.Slides för C++ API-referens
description: Skapar bildspel från HTML-text och infogar dem i samlingen på den angivna positionen.
type: docs
weight: 209
url: /sv/aspose.slides/slidecollection/insertfromhtml/
---
## SlideCollection::InsertFromHtml(int32_t, System::String, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String) method

Skapar bildspel från HTML-text och infogar dem i samlingen på den angivna positionen.

```cpp
System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::SlideCollection::InsertFromHtml(int32_t index, System::String htmlText, System::SharedPtr<Import::IExternalResourceResolver> resolver, System::String uri) override
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | **int32_t** | Position att infoga. |
| htmlText | [System::String](../../../system/string/) | HTML att lägga till. |
| resolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | Ett återuppringningsobjekt som används för att hämta externa objekt. Om den här parametern är null kommer alla externa objekt att ignoreras. |
| uri | [System::String](../../../system/string/) | En URI för den angivna HTML-en. Används för att lösa relativa länkar. |

### Returvärde

Tillagda bildspel.

## SlideCollection::InsertFromHtml(int32_t, System::String, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String, bool) method

Skapar bildspel från HTML-text och infogar dem i samlingen på den angivna positionen.

```cpp
System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::SlideCollection::InsertFromHtml(int32_t index, System::String htmlText, System::SharedPtr<Import::IExternalResourceResolver> resolver, System::String uri, bool useSlideWithIndexAsStart) override
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | **int32_t** | Position att infoga. |
| htmlText | [System::String](../../../system/string/) | HTML att lägga till. |
| resolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | Ett återuppringningsobjekt som används för att hämta externa objekt. Om den här parametern är null kommer alla externa objekt att ignoreras. |
| uri | [System::String](../../../system/string/) | En URI för den angivna HTML-en. Används för att lösa relativa länkar. |
| useSlideWithIndexAsStart | **bool** | Denna flagga bestämmer hur infogningen ska startas: från ett nytt bildspel eller från bildspelet med det angivna indexet. Om **true** startar datainförandet från ett tomt utrymme i bildspelet med det angivna indexet. Om **false** kommer data att läggas till i de skapade bildspelen. |

### Returvärde

Tillagda bildspel.

## SlideCollection::InsertFromHtml(int32_t, System::String) method

Skapar bildspel från HTML-text och infogar dem i samlingen på den angivna positionen.

```cpp
System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::SlideCollection::InsertFromHtml(int32_t index, System::String htmlText) override
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | **int32_t** | Position att infoga. |
| htmlText | [System::String](../../../system/string/) | HTML att lägga till. |

### Returvärde

Tillagda bildspel

## SlideCollection::InsertFromHtml(int32_t, System::String, bool) method

Skapar bildspel från HTML-text och infogar dem i samlingen på den angivna positionen.

```cpp
System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::SlideCollection::InsertFromHtml(int32_t index, System::String htmlText, bool useSlideWithIndexAsStart) override
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | **int32_t** | Position att infoga. |
| htmlText | [System::String](../../../system/string/) | HTML att lägga till. |
| useSlideWithIndexAsStart | **bool** | Denna flagga bestämmer hur infogningen ska startas: från ett nytt bildspel eller från bildspelet med det angivna indexet. Om **true** startar datainförandet från ett tomt utrymme i bildspelet med det angivna indexet. Om **false** kommer data att läggas till i de skapade bildspelen. |

### Returvärde

Tillagda bildspel

## SlideCollection::InsertFromHtml(int32_t, System::SharedPtr\<System::IO::TextReader\>, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String) method

Skapar bildspel från HTML-text och infogar dem i samlingen på den angivna positionen.

```cpp
System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::SlideCollection::InsertFromHtml(int32_t index, System::SharedPtr<System::IO::TextReader> htmlReader, System::SharedPtr<Import::IExternalResourceResolver> resolver, System::String uri) override
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | **int32_t** | Position att infoga. |
| htmlReader | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::TextReader](../../../system.io/textreader/)\> | TextReader-objekt som kommer att användas som källa för en HTML-fil. |
| resolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | Ett återuppringningsobjekt som används för att hämta externa objekt. Om den här parametern är null kommer alla externa objekt att ignoreras. |
| uri | [System::String](../../../system/string/) | En URI för den angivna HTML-en. Används för att lösa relativa länkar. |

### Returvärde

Tillagda bildspel.

## SlideCollection::InsertFromHtml(int32_t, System::SharedPtr\<System::IO::TextReader\>) method

Skapar bildspel från HTML-text och infogar dem i samlingen på den angivna positionen.

```cpp
System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::SlideCollection::InsertFromHtml(int32_t index, System::SharedPtr<System::IO::TextReader> htmlReader) override
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | **int32_t** | Position att infoga. |
| htmlReader | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::TextReader](../../../system.io/textreader/)\> | TextReader-objekt som kommer att användas som källa för en HTML-fil. |

### Returvärde

Tillagda bildspel

## SlideCollection::InsertFromHtml(int32_t, System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String) method

Skapar bildspel från HTML-text och infogar dem i samlingen på den angivna positionen.

```cpp
System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::SlideCollection::InsertFromHtml(int32_t index, System::SharedPtr<System::IO::Stream> htmlStream, System::SharedPtr<Import::IExternalResourceResolver> resolver, System::String uri) override
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | **int32_t** | Position att infoga. |
| htmlStream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Ett Stream-objekt som kommer att användas som källa för en HTML-fil. |
| resolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | Ett återuppringningsobjekt som används för att hämta externa objekt. Om den här parametern är null kommer alla externa objekt att ignoreras. |
| uri | [System::String](../../../system/string/) | En URI för den angivna HTML-en. Används för att lösa relativa länkar. |

### Returvärde

Tillagda bildspel.

## SlideCollection::InsertFromHtml(int32_t, System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String, bool) method

Skapar bildspel från HTML-text och infogar dem i samlingen på den angivna positionen.

```cpp
System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::SlideCollection::InsertFromHtml(int32_t index, System::SharedPtr<System::IO::Stream> htmlStream, System::SharedPtr<Import::IExternalResourceResolver> resolver, System::String uri, bool useSlideWithIndexAsStart) override
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | **int32_t** | Position att infoga. |
| htmlStream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Ett Stream-objekt som kommer att användas som källa för en HTML-fil. |
| resolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | Ett återuppringningsobjekt som används för att hämta externa objekt. Om den här parametern är null kommer alla externa objekt att ignoreras. |
| uri | [System::String](../../../system/string/) | En URI för den angivna HTML-en. Används för att lösa relativa länkar. |
| useSlideWithIndexAsStart | **bool** | Denna flagga bestämmer hur infogningen ska startas: från ett nytt bildspel eller från bildspelet med det angivna indexet. Om **true** startar datainförandet från ett tomt utrymme i bildspelet med det angivna indexet. Om **false** kommer data att läggas till i de skapade bildspelen. |

### Returvärde

Tillagda bildspel.

## SlideCollection::InsertFromHtml(int32_t, System::SharedPtr\<System::IO::Stream\>) method

Skapar bildspel från HTML-text och infogar dem i samlingen på den angivna positionen.

```cpp
System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::SlideCollection::InsertFromHtml(int32_t index, System::SharedPtr<System::IO::Stream> htmlStream) override
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | **int32_t** | Position att infoga. |
| htmlStream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Ett Stream-objekt som kommer att användas som källa för en HTML-fil. |

### Returvärde

Tillagda bildspel

## SlideCollection::InsertFromHtml(int32_t, System::SharedPtr\<System::IO::Stream\>, bool) method

Skapar bildspel från HTML-text och infogar dem i samlingen på den angivna positionen.

```cpp
System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::SlideCollection::InsertFromHtml(int32_t index, System::SharedPtr<System::IO::Stream> htmlStream, bool useSlideWithIndexAsStart) override
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | **int32_t** | Position att infoga. |
| htmlStream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Ett Stream-objekt som kommer att användas som källa för en HTML-fil. |
| useSlideWithIndexAsStart | **bool** | Denna flagga bestämmer hur infogningen ska startas: från ett nytt bildspel eller från bildspelet med det angivna indexet. Om **true** startar datainförandet från ett tomt utrymme i bildspelet med det angivna indexet. Om **false** kommer data att läggas till i de skapade bildspelen. |

### Returvärde

Tillagda bildspel

## Se även

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [ISlide](../../islide/)
* Klass [String](../../../system/string/)
* Klass [IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)
* Klass [SlideCollection](../)
* Klass [TextReader](../../../system.io/textreader/)
* Klass [Stream](../../../system.io/stream/)
* Namnrymd [Aspose::Slides](../../)
* Bibliotek [Aspose.Slides](../../../)