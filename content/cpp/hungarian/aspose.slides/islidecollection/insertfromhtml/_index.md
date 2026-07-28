---
title: InsertFromHtml()
second_title: Aspose.Slides C++ API Referencia
description: Diákat hoz létre HTML szövegből, és a megadott pozícióba illeszti be a gyűjteménybe.
type: docs
weight: 157
url: /hu/aspose.slides/islidecollection/insertfromhtml/
---
## ISlideCollection::InsertFromHtml(int32_t, System::String, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String) method


Létrehozza a diákat HTML szövegből, és a gyűjteményben a megadott pozícióra illeszti be.

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::InsertFromHtml(int32_t index, System::String htmlText, System::SharedPtr<Import::IExternalResourceResolver> resolver, System::String uri)=0
```


### Arguments

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | **int32_t** | A beszúrás pozíciója. |
| htmlText | [System::String](../../../system/string/) | A hozzáadandó HTML. |
| resolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | Egy visszahívási objektum, amely külső objektumok lekérésére szolgál. Ha ez a paraméter null, akkor az összes külső objektum figyelmen kívül lesz hagyva. |
| uri | [System::String](../../../system/string/) | A megadott HTML URI-ja. Relatív hivatkozások feloldására használható. |

### Return Value

Hozzáadott diák.

## ISlideCollection::InsertFromHtml(int32_t, System::String) method


Létrehozza a diákat HTML szövegből, és a gyűjteményben a megadott pozícióra illeszti be.

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::InsertFromHtml(int32_t index, System::String htmlText)=0
```


### Arguments

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | **int32_t** | A beszúrás pozíciója. |
| htmlText | [System::String](../../../system/string/) | A hozzáadandó HTML. |

### Return Value

Hozzáadott diák

## ISlideCollection::InsertFromHtml(int32_t, System::SharedPtr\<System::IO::TextReader\>, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String) method


Létrehozza a diákat HTML szövegből, és a gyűjteményben a megadott pozícióra illeszti be.

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::InsertFromHtml(int32_t index, System::SharedPtr<System::IO::TextReader> htmlReader, System::SharedPtr<Import::IExternalResourceResolver> resolver, System::String uri)=0
```


### Arguments

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | **int32_t** | A beszúrás pozíciója. |
| htmlReader | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::TextReader](../../../system.io/textreader/)\> | TextReader objektum, amely a HTML fájl forrásaként szolgál. |
| resolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | Egy visszahívási objektum, amely külső objektumok lekérésére szolgál. Ha ez a paraméter null, akkor az összes külső objektum figyelmen kívül lesz hagyva. |
| uri | [System::String](../../../system/string/) | A megadott HTML URI-ja. Relatív hivatkozások feloldására használható. |

### Return Value

Hozzáadott diák.

## ISlideCollection::InsertFromHtml(int32_t, System::SharedPtr\<System::IO::TextReader\>) method


Létrehozza a diákat HTML szövegből, és a gyűjteményben a megadott pozícióra illeszti be.

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::InsertFromHtml(int32_t index, System::SharedPtr<System::IO::TextReader> htmlReader)=0
```


### Arguments

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | **int32_t** | A beszúrás pozíciója. |
| htmlReader | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::TextReader](../../../system.io/textreader/)\> | TextReader objektum, amely a HTML fájl forrásaként szolgál. |

### Return Value

Hozzáadott diák

## ISlideCollection::InsertFromHtml(int32_t, System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String) method


Létrehozza a diákat HTML szövegből, és a gyűjteményben a megadott pozícióra illeszti be.

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::InsertFromHtml(int32_t index, System::SharedPtr<System::IO::Stream> htmlStream, System::SharedPtr<Import::IExternalResourceResolver> resolver, System::String uri)=0
```


### Arguments

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | **int32_t** | A beszúrás pozíciója. |
| htmlStream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Stream objektum, amely a HTML fájl forrásaként szolgál. |
| resolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | Egy visszahívási objektum, amely külső objektumok lekérésére szolgál. Ha ez a paraméter null, akkor az összes külső objektum figyelmen kívül lesz hagyva. |
| uri | [System::String](../../../system/string/) | A megadott HTML URI-ja. Relatív hivatkozások feloldására használható. |

### Return Value

Hozzáadott diák.

## ISlideCollection::InsertFromHtml(int32_t, System::SharedPtr\<System::IO::Stream\>) method


Létrehozza a diákat HTML szövegből, és a gyűjteményben a megadott pozícióra illeszti be.

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::InsertFromHtml(int32_t index, System::SharedPtr<System::IO::Stream> htmlStream)=0
```


### Arguments

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | **int32_t** | A beszúrás pozíciója. |
| htmlStream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Stream objektum, amely a HTML fájl forrásaként szolgál. |

### Return Value

Hozzáadott diák

## ISlideCollection::InsertFromHtml(int32_t, System::String, bool) method


Létrehozza a diákat HTML szövegből, és a gyűjteményben a megadott pozícióra illeszti be.

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::InsertFromHtml(int32_t index, System::String htmlText, bool useSlideWithIndexAsStart)=0
```


### Arguments

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | **int32_t** | A beszúrás pozíciója. |
| htmlText | [System::String](../../../system/string/) | A hozzáadandó HTML. |
| useSlideWithIndexAsStart | **bool** | Ez a jelölő meghatározza, hogy a beszúrást hogyan indítsa: új diától vagy a megadott indexű diáktól. Ha **true**, akkor az adatbeszúrás a megadott indexű dián egy üres területen kezdődik. Ha **false**, akkor az adatok a létrehozott diákhoz lesznek hozzáadva. |

### Return Value

Hozzáadott diák

## ISlideCollection::InsertFromHtml(int32_t, System::String, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String, bool) method


Létrehozza a diákat HTML szövegből, és a gyűjteményben a megadott pozícióra illeszti be.

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::InsertFromHtml(int32_t index, System::String htmlText, System::SharedPtr<Import::IExternalResourceResolver> resolver, System::String uri, bool useSlideWithIndexAsStart)=0
```


### Arguments

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | **int32_t** | A beszúrás pozíciója. |
| htmlText | [System::String](../../../system/string/) | A hozzáadandó HTML. |
| resolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | Egy visszahívási objektum, amely külső objektumok lekérésére szolgál. Ha ez a paraméter null, akkor az összes külső objektum figyelmen kívül lesz hagyva. |
| uri | [System::String](../../../system/string/) | A megadott HTML URI-ja. Relatív hivatkozások feloldására használható. |
| useSlideWithIndexAsStart | **bool** | Ez a jelölő meghatározza, hogy a beszúrást hogyan indítsa: új diától vagy a megadott indexű diáktól. Ha **true**, akkor az adatbeszúrás a megadott indexű dián egy üres területen kezdődik. Ha **false**, akkor az adatok a létrehozott diákhoz lesznek hozzáadva. |

### Return Value

Hozzáadott diák.

## ISlideCollection::InsertFromHtml(int32_t, System::SharedPtr\<System::IO::Stream\>, bool) method


Létrehozza a diákat HTML szövegből, és a gyűjteményben a megadott pozícióra illeszti be.

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::InsertFromHtml(int32_t index, System::SharedPtr<System::IO::Stream> htmlStream, bool useSlideWithIndexAsStart)=0
```


### Arguments

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | **int32_t** | A beszúrás pozíciója. |
| htmlStream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Stream objektum, amely a HTML fájl forrásaként szolgál. |
| useSlideWithIndexAsStart | **bool** | Ez a jelölő meghatározza, hogy a beszúrást hogyan indítsa: új diától vagy a megadott indexű diáktól. Ha **true**, akkor az adatbeszúrás a megadott indexű dián egy üres területen kezdődik. Ha **false**, akkor az adatok a létrehozott diákhoz lesznek hozzáadva. |

### Return Value

Hozzáadott diák

## ISlideCollection::InsertFromHtml(int32_t, System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String, bool) method


Létrehozza a diákat HTML szövegből, és a gyűjteményben a megadott pozícióra illeszti be.

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::InsertFromHtml(int32_t index, System::SharedPtr<System::IO::Stream> htmlStream, System::SharedPtr<Import::IExternalResourceResolver> resolver, System::String uri, bool useSlideWithIndexAsStart)=0
```


### Arguments

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | **int32_t** | A beszúrás pozíciója. |
| htmlStream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Stream objektum, amely a HTML fájl forrásaként szolgál. |
| resolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | Egy visszahívási objektum, amely külső objektumok lekérésére szolgál. Ha ez a paraméter null, akkor az összes külső objektum figyelmen kívül lesz hagyva. |
| uri | [System::String](../../../system/string/) | A megadott HTML URI-ja. Relatív hivatkozások feloldására használható. |
| useSlideWithIndexAsStart | **bool** | Ez a jelölő meghatározza, hogy a beszúrást hogyan indítsa: új diától vagy a megadott indexű diáktól. Ha **true**, akkor az adatbeszúrás a megadott indexű dián egy üres területen kezdődik. Ha **false**, akkor az adatok a létrehozott diákhoz lesznek hozzáadva. |

### Return Value

Hozzáadott diák.

## See Also

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