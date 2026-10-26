---
title: AddFromHtml()
second_title: Aspose.Slides for C++ API referencia
description: Diákat hoz létre HTML szövegből, és a gyűjtemény végére adja hozzá.
type: docs
weight: 144
url: /hu/aspose.slides/islidecollection/addfromhtml/
---
## ISlideCollection::AddFromHtml(System::String, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String) metódus

Diákat hoz létre HTML szövegből, és a gyűjtemény végére adja hozzá.

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::AddFromHtml(System::String htmlText, System::SharedPtr<Import::IExternalResourceResolver> resolver, System::String uri)=0
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| htmlText | [System::String](../../../system/string/) | Hozzáadandó HTML. |
| resolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | Egy visszahívás objektum, amely a külső objektumok lekérésére szolgál. Ha ez a paraméter null, az összes külső objektum figyelmen kívül marad. |
| uri | [System::String](../../../system/string/) | A megadott HTML URI-ja. Relatív hivatkozások feloldásához használatos. |

### Visszatérési érték

Hozzáadott diákok.

## ISlideCollection::AddFromHtml(System::String) metódus

Diákat hoz létre HTML szövegből, és a gyűjtemény végére adja hozzá.

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::AddFromHtml(System::String htmlText)=0
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| htmlText | [System::String](../../../system/string/) | Hozzáadandó HTML. |

### Visszatérési érték

Hozzáadott diákok

## ISlideCollection::AddFromHtml(System::SharedPtr\<System::IO::TextReader\>, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String) metódus

Diákat hoz létre HTML szövegből, és a gyűjtemény végére adja hozzá.

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::AddFromHtml(System::SharedPtr<System::IO::TextReader> htmlReader, System::SharedPtr<Import::IExternalResourceResolver> resolver, System::String uri)=0
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| htmlReader | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::TextReader](../../../system.io/textreader/)\> | TextReader objektum, amely a HTML fájl forrásaként szolgál. |
| resolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | Egy visszahívás objektum, amely a külső objektumok lekérésére szolgál. Ha ez a paraméter null, az összes külső objektum figyelmen kívül marad. |
| uri | [System::String](../../../system/string/) | A megadott HTML URI-ja. Relatív hivatkozások feloldásához használatos. |

### Visszatérési érték

Hozzáadott diákok.

## ISlideCollection::AddFromHtml(System::SharedPtr\<System::IO::TextReader\>) metódus

Diákat hoz létre HTML szövegből, és a gyűjtemény végére adja hozzá.

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::AddFromHtml(System::SharedPtr<System::IO::TextReader> htmlReader)=0
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| htmlReader | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::TextReader](../../../system.io/textreader/)\> | TextReader objektum, amely a HTML fájl forrásaként szolgál. |

### Visszatérési érték

Hozzáadott diákok

## ISlideCollection::AddFromHtml(System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String) metódus

Diákat hoz létre HTML szövegből, és a gyűjtemény végére adja hozzá.

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::AddFromHtml(System::SharedPtr<System::IO::Stream> htmlStream, System::SharedPtr<Import::IExternalResourceResolver> resolver, System::String uri)=0
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| htmlStream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Stream objektum, amely a HTML fájl forrásaként szolgál. |
| resolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | Egy visszahívás objektum, amely a külső objektumok lekérésére szolgál. Ha ez a paraméter null, az összes külső objektum figyelmen kívül marad. |
| uri | [System::String](../../../system/string/) | A megadott HTML URI-ja. Relatív hivatkozások feloldásához használatos. |

### Visszatérési érték

Hozzáadott diákok.

## ISlideCollection::AddFromHtml(System::SharedPtr\<System::IO::Stream\>) metódus

Diákat hoz létre HTML szövegből, és a gyűjtemény végére adja hozzá.

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::AddFromHtml(System::SharedPtr<System::IO::Stream> htmlStream)=0
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| htmlStream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Stream objektum, amely a HTML fájl forrásaként szolgál. |

### Visszatérési érték

Hozzáadott diákok

## Lásd még

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [ISlide](../../islide/)
* Osztály [String](../../../system/string/)
* Osztály [IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)
* Osztály [ISlideCollection](../)
* Osztály [TextReader](../../../system.io/textreader/)
* Osztály [Stream](../../../system.io/stream/)
* Névtere [Aspose::Slides](../../)
* Könyvtár [Aspose.Slides](../../../)