---
title: AddFromHtml()
second_title: Aspose.Slides C++ API referencia
description: Diákat hoz létre HTML szövegből, és a gyűjtemény végéhez adja hozzá.
type: docs
weight: 196
url: /hu/aspose.slides/slidecollection/addfromhtml/
---
## SlideCollection::AddFromHtml(System::String, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String) metódus

Diákat hoz létre HTML szövegből, és a gyűjtemény végéhez adja hozzá.

```cpp
System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::SlideCollection::AddFromHtml(System::String htmlText, System::SharedPtr<Import::IExternalResourceResolver> resolver, System::String uri) override
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| htmlText | [System::String](../../../system/string/) | A hozzáadandó HTML. |
| resolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | Egy visszahívási objektum külső objektumok lekérdezéséhez. Ha ez a paraméter null, minden külső objektum figyelmen kívül marad. |
| uri | [System::String](../../../system/string/) | A megadott HTML URI-ja. Relatív hivatkozások feloldásához használatos. |

### Visszatérési érték

Hozzáadott diákok.

## SlideCollection::AddFromHtml(System::String) metódus

Diákat hoz létre HTML szövegből, és a gyűjtemény végéhez adja hozzá.

```cpp
System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::SlideCollection::AddFromHtml(System::String htmlText) override
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| htmlText | [System::String](../../../system/string/) | A hozzáadandó HTML. |

### Visszatérési érték

Hozzáadott diákok

## SlideCollection::AddFromHtml(System::SharedPtr\<System::IO::TextReader\>, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String) metódus

Diákat hoz létre HTML szövegből, és a gyűjtemény végéhez adja hozzá.

```cpp
System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::SlideCollection::AddFromHtml(System::SharedPtr<System::IO::TextReader> htmlReader, System::SharedPtr<Import::IExternalResourceResolver> resolver, System::String uri) override
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| htmlReader | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::TextReader](../../../system.io/textreader/)\> | A TextReader objektum, amely a HTML fájl forrásaként szolgál. |
| resolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | Egy visszahívási objektum külső objektumok lekérdezéséhez. Ha ez a paraméter null, minden külső objektum figyelmen kívül marad. |
| uri | [System::String](../../../system/string/) | A megadott HTML URI-ja. Relatív hivatkozások feloldásához használatos. |

### Visszatérési érték

Hozzáadott diákok.

## SlideCollection::AddFromHtml(System::SharedPtr\<System::IO::TextReader\>) metódus

Diákat hoz létre HTML szövegből, és a gyűjtemény végéhez adja hozzá.

```cpp
System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::SlideCollection::AddFromHtml(System::SharedPtr<System::IO::TextReader> htmlReader) override
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| htmlReader | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::TextReader](../../../system.io/textreader/)\> | A TextReader objektum, amely a HTML fájl forrásaként szolgál. |

### Visszatérési érték

Hozzáadott diákok

## SlideCollection::AddFromHtml(System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String) metódus

Diákat hoz létre HTML szövegből, és a gyűjtemény végéhez adja hozzá.

```cpp
System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::SlideCollection::AddFromHtml(System::SharedPtr<System::IO::Stream> htmlStream, System::SharedPtr<Import::IExternalResourceResolver> resolver, System::String uri) override
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| htmlStream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | A Stream objektum, amely a HTML fájl forrásaként szolgál. |
| resolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | Egy visszahívási objektum külső objektumok lekérdezéséhez. Ha ez a paraméter null, minden külső objektum figyelmen kívül marad. |
| uri | [System::String](../../../system/string/) | A megadott HTML URI-ja. Relatív hivatkozások feloldásához használatos. |

### Visszatérési érték

Hozzáadott diákok.

## SlideCollection::AddFromHtml(System::SharedPtr\<System::IO::Stream\>) metódus

Diákat hoz létre HTML szövegből, és a gyűjtemény végéhez adja hozzá.

```cpp
System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::SlideCollection::AddFromHtml(System::SharedPtr<System::IO::Stream> htmlStream) override
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| htmlStream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | A Stream objektum, amely a HTML fájl forrásaként szolgál. |

### Visszatérési érték

Hozzáadott diákok

## Megjegyzések

```cpp
// Hozzon létre egy példányt a Presentation osztályból.
auto presentation = System::MakeObject<Presentation>();

{
    auto htmlStream = System::IO::File::OpenRead(u"page.html");

    // Hívja meg az AddFromHtml metódust, és adja át a HTML fájlt.
    presentation->get_Slides()->AddFromHtml(htmlStream);
}

// Használja a Save metódust a fájl PowerPoint dokumentumként történő mentéséhez.
presentation->Save(u"MyPresentation.pptx", SaveFormat::Pptx);
```

## Lásd még

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [ISlide](../../islide/)
* Osztály [String](../../../system/string/)
* Osztály [IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)
* Osztály [SlideCollection](../)
* Osztály [TextReader](../../../system.io/textreader/)
* Osztály [Stream](../../../system.io/stream/)
* Névtér [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)