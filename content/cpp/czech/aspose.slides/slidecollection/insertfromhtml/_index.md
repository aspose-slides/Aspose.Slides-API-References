---
title: InsertFromHtml()
second_title: Aspose.Slides pro C++ – API reference
description: Vytvoří snímky z HTML textu a vloží je do kolekce na zadanou pozici.
type: docs
weight: 209
url: /cs/aspose.slides/slidecollection/insertfromhtml/
---
## SlideCollection::InsertFromHtml(int32_t, System::String, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String) metoda


Vytvoří snímky z HTML textu a vloží je do kolekce na zadanou pozici.

```cpp
System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::SlideCollection::InsertFromHtml(int32_t index, System::String htmlText, System::SharedPtr<Import::IExternalResourceResolver> resolver, System::String uri) override
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| index | **int32_t** | Pozice pro vložení. |
| htmlText | [System::String](../../../system/string/) | HTML k přidání. |
| resolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | Objekt zpětného volání používaný k načtení externích objektů. Pokud je tento parametr null, všechny externí objekty budou ignorovány. |
| uri | [System::String](../../../system/string/) | URI zadaného HTML. Používá se k řešení relativních odkazů. |

### Návratová hodnota

Přidané snímky.

## SlideCollection::InsertFromHtml(int32_t, System::String, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String, bool) metoda


Vytvoří snímky z HTML textu a vloží je do kolekce na zadanou pozici.

```cpp
System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::SlideCollection::InsertFromHtml(int32_t index, System::String htmlText, System::SharedPtr<Import::IExternalResourceResolver> resolver, System::String uri, bool useSlideWithIndexAsStart) override
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| index | **int32_t** | Pozice pro vložení. |
| htmlText | [System::String](../../../system/string/) | HTML k přidání. |
| resolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | Objekt zpětného volání používaný k načtení externích objektů. Pokud je tento parametr null, všechny externí objekty budou ignorovány. |
| uri | [System::String](../../../system/string/) | URI zadaného HTML. Používá se k řešení relativních odkazů. |
| useSlideWithIndexAsStart | **bool** | Tento příznak určuje, jak zahájit vložení: od nového snímku nebo od snímku s určeným indexem. Pokud je **true**, vložení dat začne na volném místě ve snímku s určeným indexem. Pokud je **false**, data budou přidána do vytvořených snímků. |

### Návratová hodnota

Přidané snímky.

## SlideCollection::InsertFromHtml(int32_t, System::String) metoda


Vytvoří snímky z HTML textu a vloží je do kolekce na zadanou pozici.

```cpp
System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::SlideCollection::InsertFromHtml(int32_t index, System::String htmlText) override
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| index | **int32_t** | Pozice pro vložení. |
| htmlText | [System::String](../../../system/string/) | HTML k přidání. |

### Návratová hodnota

Přidané snímky

## SlideCollection::InsertFromHtml(int32_t, System::String, bool) metoda


Vytvoří snímky z HTML textu a vloží je do kolekce na zadanou pozici.

```cpp
System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::SlideCollection::InsertFromHtml(int32_t index, System::String htmlText, bool useSlideWithIndexAsStart) override
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| index | **int32_t** | Pozice pro vložení. |
| htmlText | [System::String](../../../system/string/) | HTML k přidání. |
| useSlideWithIndexAsStart | **bool** | Tento příznak určuje, jak zahájit vložení: od nového snímku nebo od snímku s určeným indexem. Pokud je **true**, vložení dat začne na volném místě ve snímku s určeným indexem. Pokud je **false**, data budou přidána do vytvořených snímků. |

### Návratová hodnota

Přidané snímky

## SlideCollection::InsertFromHtml(int32_t, System::SharedPtr\<System::IO::TextReader\>, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String) metoda


Vytvoří snímky z HTML textu a vloží je do kolekce na zadanou pozici.

```cpp
System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::SlideCollection::InsertFromHtml(int32_t index, System::SharedPtr<System::IO::TextReader> htmlReader, System::SharedPtr<Import::IExternalResourceResolver> resolver, System::String uri) override
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| index | **int32_t** | Pozice pro vložení. |
| htmlReader | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::TextReader](../../../system.io/textreader/)\> | Objekt TextReader, který bude použit jako zdroj HTML souboru. |
| resolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | Objekt zpětného volání používaný k načtení externích objektů. Pokud je tento parametr null, všechny externí objekty budou ignorovány. |
| uri | [System::String](../../../system/string/) | URI zadaného HTML. Používá se k řešení relativních odkazů. |

### Návratová hodnota

Přidané snímky.

## SlideCollection::InsertFromHtml(int32_t, System::SharedPtr\<System::IO::TextReader\>) metoda


Vytvoří snímky z HTML textu a vloží je do kolekce na zadanou pozici.

```cpp
System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::SlideCollection::InsertFromHtml(int32_t index, System::SharedPtr<System::IO::TextReader> htmlReader) override
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| index | **int32_t** | Pozice pro vložení. |
| htmlReader | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::TextReader](../../../system.io/textreader/)\> | Objekt TextReader, který bude použit jako zdroj HTML souboru. |

### Návratová hodnota

Přidané snímky

## SlideCollection::InsertFromHtml(int32_t, System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String) metoda


Vytvoří snímky z HTML textu a vloží je do kolekce na zadanou pozici.

```cpp
System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::SlideCollection::InsertFromHtml(int32_t index, System::SharedPtr<System::IO::Stream> htmlStream, System::SharedPtr<Import::IExternalResourceResolver> resolver, System::String uri) override
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| index | **int32_t** | Pozice pro vložení. |
| htmlStream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Objekt Stream, který bude použit jako zdroj HTML souboru. |
| resolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | Objekt zpětného volání používaný k načtení externích objektů. Pokud je tento parametr null, všechny externí objekty budou ignorovány. |
| uri | [System::String](../../../system/string/) | URI zadaného HTML. Používá se k řešení relativních odkazů. |

### Návratová hodnota

Přidané snímky.

## SlideCollection::InsertFromHtml(int32_t, System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String, bool) metoda


Vytvoří snímky z HTML textu a vloží je do kolekce na zadanou pozici.

```cpp
System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::SlideCollection::InsertFromHtml(int32_t index, System::SharedPtr<System::IO::Stream> htmlStream, System::SharedPtr<Import::IExternalResourceResolver> resolver, System::String uri, bool useSlideWithIndexAsStart) override
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| index | **int32_t** | Pozice pro vložení. |
| htmlStream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Objekt Stream, který bude použit jako zdroj HTML souboru. |
| resolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | Objekt zpětného volání používaný k načtení externích objektů. Pokud je tento parametr null, všechny externí objekty budou ignorovány. |
| uri | [System::String](../../../system/string/) | URI zadaného HTML. Používá se k řešení relativních odkazů. |
| useSlideWithIndexAsStart | **bool** | Tento příznak určuje, jak zahájit vložení: od nového snímku nebo od snímku s určeným indexem. Pokud je **true**, vložení dat začne na volném místě ve snímku s určeným indexem. Pokud je **false**, data budou přidána do vytvořených snímků. |

### Návratová hodnota

Přidané snímky.

## SlideCollection::InsertFromHtml(int32_t, System::SharedPtr\<System::IO::Stream\>) metoda


Vytvoří snímky z HTML textu a vloží je do kolekce na zadanou pozici.

```cpp
System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::SlideCollection::InsertFromHtml(int32_t index, System::SharedPtr<System::IO::Stream> htmlStream) override
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| index | **int32_t** | Pozice pro vložení. |
| htmlStream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Objekt Stream, který bude použit jako zdroj HTML souboru. |

### Návratová hodnota

Přidané snímky

## SlideCollection::InsertFromHtml(int32_t, System::SharedPtr\<System::IO::Stream\>, bool) metoda


Vytvoří snímky z HTML textu a vloží je do kolekce na zadanou pozici.

```cpp
System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::SlideCollection::InsertFromHtml(int32_t index, System::SharedPtr<System::IO::Stream> htmlStream, bool useSlideWithIndexAsStart) override
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| index | **int32_t** | Pozice pro vložení. |
| htmlStream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Objekt Stream, který bude použit jako zdroj HTML souboru. |
| useSlideWithIndexAsStart | **bool** | Tento příznak určuje, jak zahájit vložení: od nového snímku nebo od snímku s určeným indexem. Pokud je **true**, vložení dat začne na volném místě ve snímku s určeným indexem. Pokud je **false**, data budou přidána do vytvořených snímků. |

### Návratová hodnota

Přidané snímky

## Viz také

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [ISlide](../../islide/)
* Třída [String](../../../system/string/)
* Třída [IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)
* Třída [SlideCollection](../)
* Třída [TextReader](../../../system.io/textreader/)
* Třída [Stream](../../../system.io/stream/)
* Jmenný prostor [Aspose::Slides](../../)
* Knihovna [Aspose.Slides](../../../)