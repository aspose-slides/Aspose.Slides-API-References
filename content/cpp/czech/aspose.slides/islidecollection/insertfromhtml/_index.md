---
title: InsertFromHtml()
second_title: Aspose.Slides pro C++ – reference API
description: Vytváří snímky z HTML textu a vkládá je do kolekce na zadanou pozici.
type: docs
weight: 157
url: /cs/aspose.slides/islidecollection/insertfromhtml/
---
## ISlideCollection::InsertFromHtml(int32_t, System::String, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String) metoda

Vytváří snímky z HTML textu a vkládá je do kolekce na zadanou pozici.

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::InsertFromHtml(int32_t index, System::String htmlText, System::SharedPtr<Import::IExternalResourceResolver> resolver, System::String uri)=0
```

### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| index | **int32_t** | Pozice pro vložení. |
| htmlText | [System::String](../../../system/string/) | HTML k přidání. |
| resolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | Objekt zpětného volání používaný k načtení externích objektů. Pokud je tento parametr null, všechny externí objekty budou ignorovány. |
| uri | [System::String](../../../system/string/) | URI zadaného HTML. Používá se k řešení relativních odkazů. |

### Návratová hodnota

Přidané snímky.

## ISlideCollection::InsertFromHtml(int32_t, System::String) metoda

Vytváří snímky z HTML textu a vkládá je do kolekce na zadanou pozici.

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::InsertFromHtml(int32_t index, System::String htmlText)=0
```

### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| index | **int32_t** | Pozice pro vložení. |
| htmlText | [System::String](../../../system/string/) | HTML k přidání. |

### Návratová hodnota

Přidané snímky

## ISlideCollection::InsertFromHtml(int32_t, System::SharedPtr\<System::IO::TextReader\>, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String) metoda

Vytváří snímky z HTML textu a vkládá je do kolekce na zadanou pozici.

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::InsertFromHtml(int32_t index, System::SharedPtr<System::IO::TextReader> htmlReader, System::SharedPtr<Import::IExternalResourceResolver> resolver, System::String uri)=0
```

### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| index | **int32_t** | Pozice pro vložení. |
| htmlReader | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::TextReader](../../../system.io/textreader/)\> | Objekt TextReader, který bude použit jako zdroj HTML souboru. |
| resolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | Objekt zpětného volání používaný k načtení externích objektů. Pokud je tento parametr null, všechny externí objekty budou ignorovány. |
| uri | [System::String](../../../system/string/) | URI zadaného HTML. Používá se k řešení relativních odkazů. |

### Návratová hodnota

Přidané snímky.

## ISlideCollection::InsertFromHtml(int32_t, System::SharedPtr\<System::IO::TextReader\>) metoda

Vytváří snímky z HTML textu a vkládá je do kolekce na zadanou pozici.

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::InsertFromHtml(int32_t index, System::SharedPtr<System::IO::TextReader> htmlReader)=0
```

### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| index | **int32_t** | Pozice pro vložení. |
| htmlReader | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::TextReader](../../../system.io/textreader/)\> | Objekt TextReader, který bude použit jako zdroj HTML souboru. |

### Návratová hodnota

Přidané snímky

## ISlideCollection::InsertFromHtml(int32_t, System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String) metoda

Vytváří snímky z HTML textu a vkládá je do kolekce na zadanou pozici.

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::InsertFromHtml(int32_t index, System::SharedPtr<System::IO::Stream> htmlStream, System::SharedPtr<Import::IExternalResourceResolver> resolver, System::String uri)=0
```

### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| index | **int32_t** | Pozice pro vložení. |
| htmlStream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Objekt Stream, který bude použit jako zdroj HTML souboru. |
| resolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | Objekt zpětného volání používaný k načtení externích objektů. Pokud je tento parametr null, všechny externí objekty budou ignorovány. |
| uri | [System::String](../../../system/string/) | URI zadaného HTML. Používá se k řešení relativních odkazů. |

### Návratová hodnota

Přidané snímky.

## ISlideCollection::InsertFromHtml(int32_t, System::SharedPtr\<System::IO::Stream\>) metoda

Vytváří snímky z HTML textu a vkládá je do kolekce na zadanou pozici.

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::InsertFromHtml(int32_t index, System::SharedPtr<System::IO::Stream> htmlStream)=0
```

### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| index | **int32_t** | Pozice pro vložení. |
| htmlStream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Objekt Stream, který bude použit jako zdroj HTML souboru. |

### Návratová hodnota

Přidané snímky

## ISlideCollection::InsertFromHtml(int32_t, System::String, bool) metoda

Vytváří snímky z HTML textu a vkládá je do kolekce na zadanou pozici.

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::InsertFromHtml(int32_t index, System::String htmlText, bool useSlideWithIndexAsStart)=0
```

### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| index | **int32_t** | Pozice pro vložení. |
| htmlText | [System::String](../../../system/string/) | HTML k přidání. |
| useSlideWithIndexAsStart | **bool** | Tento příznak určuje, jak zahájit vkládání: od nového snímku nebo od snímku se zadaným indexem. Pokud je **true**, vkládání dat začne na prázdném prostoru ve snímku se zadaným indexem. Pokud je **false**, data budou přidána k vytvořeným snímkům. |

### Návratová hodnota

Přidané snímky

## ISlideCollection::InsertFromHtml(int32_t, System::String, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String, bool) metoda

Vytváří snímky z HTML textu a vkládá je do kolekce na zadanou pozici.

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::InsertFromHtml(int32_t index, System::String htmlText, System::SharedPtr<Import::IExternalResourceResolver> resolver, System::String uri, bool useSlideWithIndexAsStart)=0
```

### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| index | **int32_t** | Pozice pro vložení. |
| htmlText | [System::String](../../../system/string/) | HTML k přidání. |
| resolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | Objekt zpětného volání používaný k načtení externích objektů. Pokud je tento parametr null, všechny externí objekty budou ignorovány. |
| uri | [System::String](../../../system/string/) | URI zadaného HTML. Používá se k řešení relativních odkazů. |
| useSlideWithIndexAsStart | **bool** | Tento příznak určuje, jak zahájit vkládání: od nového snímku nebo od snímku se zadaným indexem. Pokud je **true**, vkládání dat začne na prázdném prostoru ve snímku se zadaným indexem. Pokud je **false**, data budou přidána k vytvořeným snímkům. |

### Návratová hodnota

Přidané snímky.

## ISlideCollection::InsertFromHtml(int32_t, System::SharedPtr\<System::IO::Stream\>, bool) metoda

Vytváří snímky z HTML textu a vkládá je do kolekce na zadanou pozici.

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::InsertFromHtml(int32_t index, System::SharedPtr<System::IO::Stream> htmlStream, bool useSlideWithIndexAsStart)=0
```

### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| index | **int32_t** | Pozice pro vložení. |
| htmlStream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Objekt Stream, který bude použit jako zdroj HTML souboru. |
| useSlideWithIndexAsStart | **bool** | Tento příznak určuje, jak zahájit vkládání: od nového snímku nebo od snímku se zadaným indexem. Pokud je **true**, vkládání dat začne na prázdném prostoru ve snímku se zadaným indexem. Pokud je **false**, data budou přidána k vytvořeným snímkům. |

### Návratová hodnota

Přidané snímky

## ISlideCollection::InsertFromHtml(int32_t, System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String, bool) metoda

Vytváří snímky z HTML textu a vkládá je do kolekce na zadanou pozici.

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::InsertFromHtml(int32_t index, System::SharedPtr<System::IO::Stream> htmlStream, System::SharedPtr<Import::IExternalResourceResolver> resolver, System::String uri, bool useSlideWithIndexAsStart)=0
```

### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| index | **int32_t** | Pozice pro vložení. |
| htmlStream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Objekt Stream, který bude použit jako zdroj HTML souboru. |
| resolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | Objekt zpětného volání používaný k načtení externích objektů. Pokud je tento parametr null, všechny externí objekty budou ignorovány. |
| uri | [System::String](../../../system/string/) | URI zadaného HTML. Používá se k řešení relativních odkazů. |
| useSlideWithIndexAsStart | **bool** | Tento příznak určuje, jak zahájit vkládání: od nového snímku nebo od snímku se zadaným indexem. Pokud je **true**, vkládání dat začne na prázdném prostoru ve snímku se zadaným indexem. Pokud je **false**, data budou přidána k vytvořeným snímkům. |

### Návratová hodnota

Přidané snímky.

## Viz také

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [ISlide](../../islide/)
* Třída [String](../../../system/string/)
* Třída [IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)
* Třída [ISlideCollection](../)
* Třída [TextReader](../../../system.io/textreader/)
* Třída [Stream](../../../system.io/stream/)
* Jmenný prostor [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)