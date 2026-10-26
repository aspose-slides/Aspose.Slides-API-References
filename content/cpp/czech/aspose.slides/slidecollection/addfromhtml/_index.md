---
title: AddFromHtml()
second_title: Aspose.Slides pro C++ API Reference
description: Vytvoří snímky z HTML textu a přidá je na konec kolekce.
type: docs
weight: 196
url: /cs/aspose.slides/slidecollection/addfromhtml/
---
## SlideCollection::AddFromHtml(System::String, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String) method


Vytvoří snímky z HTML textu a přidá je na konec kolekce.

```cpp
System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::SlideCollection::AddFromHtml(System::String htmlText, System::SharedPtr<Import::IExternalResourceResolver> resolver, System::String uri) override
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| htmlText | [System::String](../../../system/string/) | HTML k přidání. |
| resolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | Objekt zpětného volání používaný k načtení externích objektů. Pokud je tento parametr null, všechny externí objekty budou ignorovány. |
| uri | [System::String](../../../system/string/) | URI specifikovaného HTML. Používá se k řešení relativních odkazů. |

### Návratová hodnota

Přidané snímky.

## SlideCollection::AddFromHtml(System::String) method


Vytvoří snímky z HTML textu a přidá je na konec kolekce.

```cpp
System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::SlideCollection::AddFromHtml(System::String htmlText) override
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| htmlText | [System::String](../../../system/string/) | HTML k přidání. |

### Návratová hodnota

Přidané snímky

## SlideCollection::AddFromHtml(System::SharedPtr\<System::IO::TextReader\>, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String) method


Vytvoří snímky z HTML textu a přidá je na konec kolekce.

```cpp
System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::SlideCollection::AddFromHtml(System::SharedPtr<System::IO::TextReader> htmlReader, System::SharedPtr<Import::IExternalResourceResolver> resolver, System::String uri) override
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| htmlReader | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::TextReader](../../../system.io/textreader/)\> | Objekt TextReader, který bude použit jako zdroj HTML souboru. |
| resolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | Objekt zpětného volání používaný k načtení externích objektů. Pokud je tento parametr null, všechny externí objekty budou ignorovány. |
| uri | [System::String](../../../system/string/) | URI specifikovaného HTML. Používá se k řešení relativních odkazů. |

### Návratová hodnota

Přidané snímky.

## SlideCollection::AddFromHtml(System::SharedPtr\<System::IO::TextReader\>) method


Vytvoří snímky z HTML textu a přidá je na konec kolekce.

```cpp
System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::SlideCollection::AddFromHtml(System::SharedPtr<System::IO::TextReader> htmlReader) override
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| htmlReader | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::TextReader](../../../system.io/textreader/)\> | Objekt TextReader, který bude použit jako zdroj HTML souboru. |

### Návratová hodnota

Přidané snímky

## SlideCollection::AddFromHtml(System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String) method


Vytvoří snímky z HTML textu a přidá je na konec kolekce.

```cpp
System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::SlideCollection::AddFromHtml(System::SharedPtr<System::IO::Stream> htmlStream, System::SharedPtr<Import::IExternalResourceResolver> resolver, System::String uri) override
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| htmlStream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Objekt Stream, který bude použit jako zdroj HTML souboru. |
| resolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | Objekt zpětného volání používaný k načtení externích objektů. Pokud je tento parametr null, všechny externí objekty budou ignorovány. |
| uri | [System::String](../../../system/string/) | URI specifikovaného HTML. Používá se k řešení relativních odkazů. |

### Návratová hodnota

Přidané snímky.

## SlideCollection::AddFromHtml(System::SharedPtr\<System::IO::Stream\>) method


Vytvoří snímky z HTML textu a přidá je na konec kolekce.

```cpp
System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::SlideCollection::AddFromHtml(System::SharedPtr<System::IO::Stream> htmlStream) override
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| htmlStream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Objekt Stream, který bude použit jako zdroj HTML souboru. |

### Návratová hodnota

Přidané snímky
## Poznámky




```cpp
// Vytvořte instanci třídy Presentation.
auto presentation = System::MakeObject<Presentation>();

{
    auto htmlStream = System::IO::File::OpenRead(u"page.html");

    // Zavolejte metodu AddFromHtml a předáte soubor HTML.
    presentation->get_Slides()->AddFromHtml(htmlStream);
}

// Použijte metodu Save k uložení souboru jako dokument PowerPoint.
presentation->Save(u"MyPresentation.pptx", SaveFormat::Pptx);
```

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