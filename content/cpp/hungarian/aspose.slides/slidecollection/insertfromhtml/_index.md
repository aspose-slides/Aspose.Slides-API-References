---
title: InsertFromHtml()
second_title: Aspose.Slides C++ API-referencia
description: Diákat hoz létre HTML szövegből, és a megadott pozícióban illeszti be a gyűjteménybe.
type: docs
weight: 209
url: /hu/aspose.slides/slidecollection/insertfromhtml/
---
## SlideCollection::InsertFromHtml(int32_t, System::String, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String) metódus

Diákat hoz létre HTML szövegből, és a megadott pozícióban illeszti be a gyűjteménybe.

```cpp
System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::SlideCollection::InsertFromHtml(int32_t index, System::String htmlText, System::SharedPtr<Import::IExternalResourceResolver> resolver, System::String uri) override
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | **int32_t** | A beszúrás helye. |
| htmlText | [System::String](../../../system/string/) | A hozzáadandó HTML. |
| resolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | Egy visszahívási objektum, amely a külső objektumok lekérésére szolgál. Ha ez a paraméter null, akkor az összes külső objektum figyelmen kívül marad. |
| uri | [System::String](../../../system/string/) | A megadott HTML URI-ja. A relatív hivatkozások feloldásához használható. |

### Visszatérési érték

Hozzáadott diák.

## SlideCollection::InsertFromHtml(int32_t, System::String, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String, bool) metódus

Diákat hoz létre HTML szövegből, és a megadott pozícióban illeszti be a gyűjteménybe.

```cpp
System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::SlideCollection::InsertFromHtml(int32_t index, System::String htmlText, System::SharedPtr<Import::IExternalResourceResolver> resolver, System::String uri, bool useSlideWithIndexAsStart) override
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | **int32_t** | A beszúrás helye. |
| htmlText | [System::String](../../../system/string/) | A hozzáadandó HTML. |
| resolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | Egy visszahívási objektum, amely a külső objektumok lekérésére szolgál. Ha ez a paraméter null, akkor az összes külső objektum figyelmen kívül marad. |
| uri | [System::String](../../../system/string/) | A megadott HTML URI-ja. A relatív hivatkozások feloldásához használható. |
| useSlideWithIndexAsStart | **bool** | Ez a jelző határozza meg, hogyan kezdődjön a beszúrás: egy új diáktól vagy a megadott indexű diától. Ha **true**, akkor az adatbeszúrás egy üres helyről indul a megadott indexű dián. Ha **false**, az adatok a létrehozott diákhoz kerülnek hozzáadásra. |

### Visszatérési érték

Hozzáadott diák.

## SlideCollection::InsertFromHtml(int32_t, System::String) metódus

Diákat hoz létre HTML szövegből, és a megadott pozícióban illeszti be a gyűjteménybe.

```cpp
System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::SlideCollection::InsertFromHtml(int32_t index, System::String htmlText) override
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | **int32_t** | A beszúrás helye. |
| htmlText | [System::String](../../../system/string/) | A hozzáadandó HTML. |

### Visszatérési érték

Hozzáadott diák

## SlideCollection::InsertFromHtml(int32_t, System::String, bool) metódus

Diákat hoz létre HTML szövegből, és a megadott pozícióban illeszti be a gyűjteménybe.

```cpp
System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::SlideCollection::InsertFromHtml(int32_t index, System::String htmlText, bool useSlideWithIndexAsStart) override
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | **int32_t** | A beszúrás helye. |
| htmlText | [System::String](../../../system/string/) | A hozzáadandó HTML. |
| useSlideWithIndexAsStart | **bool** | Ez a jelző határozza meg, hogyan kezdődjön a beszúrás: egy új diáktól vagy a megadott indexű diától. Ha **true**, akkor az adatbeszúrás egy üres helyről indul a megadott indexű dián. Ha **false**, az adatok a létrehozott diákhoz kerülnek hozzáadásra. |

### Visszatérési érték

Hozzáadott diák

## SlideCollection::InsertFromHtml(int32_t, System::SharedPtr\<System::IO::TextReader\>, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String) metódus

Diákat hoz létre HTML szövegből, és a megadott pozícióban illeszti be a gyűjteménybe.

```cpp
System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::SlideCollection::InsertFromHtml(int32_t index, System::SharedPtr<System::IO::TextReader> htmlReader, System::SharedPtr<Import::IExternalResourceResolver> resolver, System::String uri) override
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | **int32_t** | A beszúrás helye. |
| htmlReader | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::TextReader](../../../system.io/textreader/)\> | A TextReader objektum, amely a HTML fájl forrásaként szolgál. |
| resolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | Egy visszahívási objektum, amely a külső objektumok lekérésére szolgál. Ha ez a paraméter null, akkor az összes külső objektum figyelmen kívül marad. |
| uri | [System::String](../../../system/string/) | A megadott HTML URI-ja. A relatív hivatkozások feloldásához használható. |

### Visszatérési érték

Hozzáadott diák.

## SlideCollection::InsertFromHtml(int32_t, System::SharedPtr\<System::IO::TextReader\>) metódus

Diákat hoz létre HTML szövegből, és a megadott pozícióban illeszti be a gyűjteménybe.

```cpp
System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::SlideCollection::InsertFromHtml(int32_t index, System::SharedPtr<System::IO::TextReader> htmlReader) override
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | **int32_t** | A beszúrás helye. |
| htmlReader | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::TextReader](../../../system.io/textreader/)\> | A TextReader objektum, amely a HTML fájl forrásaként szolgál. |

### Visszatérési érték

Hozzáadott diák

## SlideCollection::InsertFromHtml(int32_t, System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String) metódus

Diákat hoz létre HTML szövegből, és a megadott pozícióban illeszti be a gyűjteménybe.

```cpp
System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::SlideCollection::InsertFromHtml(int32_t index, System::SharedPtr<System::IO::Stream> htmlStream, System::SharedPtr<Import::IExternalResourceResolver> resolver, System::String uri) override
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | **int32_t** | A beszúrás helye. |
| htmlStream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | A Stream objektum, amely a HTML fájl forrásaként szolgál. |
| resolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | Egy visszahívási objektum, amely a külső objektumok lekérésére szolgál. Ha ez a paraméter null, akkor az összes külső objektum figyelmen kívül marad. |
| uri | [System::String](../../../system/string/) | A megadott HTML URI-ja. A relatív hivatkozások feloldásához használható. |

### Visszatérési érték

Hozzáadott diák.

## SlideCollection::InsertFromHtml(int32_t, System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String, bool) metódus

Diákat hoz létre HTML szövegből, és a megadott pozícióban illeszti be a gyűjteménybe.

```cpp
System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::SlideCollection::InsertFromHtml(int32_t index, System::SharedPtr<System::IO::Stream> htmlStream, System::SharedPtr<Import::IExternalResourceResolver> resolver, System::String uri, bool useSlideWithIndexAsStart) override
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | **int32_t** | A beszúrás helye. |
| htmlStream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | A Stream objektum, amely a HTML fájl forrásaként szolgál. |
| resolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | Egy visszahívási objektum, amely a külső objektumok lekérésére szolgál. Ha ez a paraméter null, akkor az összes külső objektum figyelmen kívül marad. |
| uri | [System::String](../../../system/string/) | A megadott HTML URI-ja. A relatív hivatkozások feloldásához használható. |
| useSlideWithIndexAsStart | **bool** | Ez a jelző határozza meg, hogyan kezdődjön a beszúrás: egy új diáktól vagy a megadott indexű diától. Ha **true**, akkor az adatbeszúrás egy üres helyről indul a megadott indexű dián. Ha **false**, az adatok a létrehozott diákhoz kerülnek hozzáadásra. |

### Visszatérési érték

Hozzáadott diák.

## SlideCollection::InsertFromHtml(int32_t, System::SharedPtr\<System::IO::Stream\>) metódus

Diákat hoz létre HTML szövegből, és a megadott pozícióban illeszti be a gyűjteménybe.

```cpp
System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::SlideCollection::InsertFromHtml(int32_t index, System::SharedPtr<System::IO::Stream> htmlStream) override
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | **int32_t** | A beszúrás helye. |
| htmlStream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | A Stream objektum, amely a HTML fájl forrásaként szolgál. |

### Visszatérési érték

Hozzáadott diák

## SlideCollection::InsertFromHtml(int32_t, System::SharedPtr\<System::IO::Stream\>, bool) metódus

Diákat hoz létre HTML szövegből, és a megadott pozícióban illeszti be a gyűjteménybe.

```cpp
System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::SlideCollection::InsertFromHtml(int32_t index, System::SharedPtr<System::IO::Stream> htmlStream, bool useSlideWithIndexAsStart) override
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | **int32_t** | A beszúrás helye. |
| htmlStream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | A Stream objektum, amely a HTML fájl forrásaként szolgál. |
| useSlideWithIndexAsStart | **bool** | Ez a jelző határozza meg, hogyan kezdődjön a beszúrás: egy új diáktól vagy a megadott indexű diától. Ha **true**, akkor az adatbeszúrás egy üres helyről indul a megadott indexű dián. Ha **false**, az adatok a létrehozott diákhoz kerülnek hozzáadásra. |

### Visszatérési érték

Hozzáadott diák

## Lásd még

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