---
title: AddFromHtml()
second_title: Riferimento API di Aspose.Slides per C++
description: Crea slide dal testo HTML e le aggiunge alla fine della collezione.
type: docs
weight: 196
url: /it/aspose.slides/slidecollection/addfromhtml/
---
## SlideCollection::AddFromHtml(System::String, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String) method

Crea diapositive dal testo HTML e le aggiunge alla fine della collezione.

```cpp
System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::SlideCollection::AddFromHtml(System::String htmlText, System::SharedPtr<Import::IExternalResourceResolver> resolver, System::String uri) override
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| htmlText | [System::String](../../../system/string/) | Html da aggiungere. |
| resolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | Un oggetto di callback usato per recuperare oggetti esterni. Se questo parametro è null, tutti gli oggetti esterni verranno ignorati. |
| uri | [System::String](../../../system/string/) | Un URI dell'HTML specificato. Usato per risolvere i collegamenti relativi. |

### Valore restituito

Diapositive aggiunte.

## SlideCollection::AddFromHtml(System::String) method

Crea diapositive dal testo HTML e le aggiunge alla fine della collezione.

```cpp
System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::SlideCollection::AddFromHtml(System::String htmlText) override
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| htmlText | [System::String](../../../system/string/) | Html da aggiungere. |

### Valore restituito

Diapositive aggiunte

## SlideCollection::AddFromHtml(System::SharedPtr\<System::IO::TextReader\>, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String) method

Crea diapositive dal testo HTML e le aggiunge alla fine della collezione.

```cpp
System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::SlideCollection::AddFromHtml(System::SharedPtr<System::IO::TextReader> htmlReader, System::SharedPtr<Import::IExternalResourceResolver> resolver, System::String uri) override
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| htmlReader | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::TextReader](../../../system.io/textreader/)\> | Oggetto TextReader che verrà usato come sorgente di un file HTML. |
| resolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | Un oggetto di callback usato per recuperare oggetti esterni. Se questo parametro è null, tutti gli oggetti esterni verranno ignorati. |
| uri | [System::String](../../../system/string/) | Un URI dell'HTML specificato. Usato per risolvere i collegamenti relativi. |

### Valore restituito

Diapositive aggiunte.

## SlideCollection::AddFromHtml(System::SharedPtr\<System::IO::TextReader\>) method

Crea diapositive dal testo HTML e le aggiunge alla fine della collezione.

```cpp
System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::SlideCollection::AddFromHtml(System::SharedPtr<System::IO::TextReader> htmlReader) override
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| htmlReader | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::TextReader](../../../system.io/textreader/)\> | Oggetto TextReader che verrà usato come sorgente di un file HTML. |

### Valore restituito

Diapositive aggiunte

## SlideCollection::AddFromHtml(System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String) method

Crea diapositive dal testo HTML e le aggiunge alla fine della collezione.

```cpp
System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::SlideCollection::AddFromHtml(System::SharedPtr<System::IO::Stream> htmlStream, System::SharedPtr<Import::IExternalResourceResolver> resolver, System::String uri) override
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| htmlStream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Un oggetto Stream che verrà usato come sorgente di un file HTML. |
| resolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | Un oggetto di callback usato per recuperare oggetti esterni. Se questo parametro è null, tutti gli oggetti esterni verranno ignorati. |
| uri | [System::String](../../../system/string/) | Un URI dell'HTML specificato. Usato per risolvere i collegamenti relativi. |

### Valore restituito

Diapositive aggiunte.

## SlideCollection::AddFromHtml(System::SharedPtr\<System::IO::Stream\>) method

Crea diapositive dal testo HTML e le aggiunge alla fine della collezione.

```cpp
System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::SlideCollection::AddFromHtml(System::SharedPtr<System::IO::Stream> htmlStream) override
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| htmlStream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Un oggetto Stream che verrà usato come sorgente di un file HTML. |

### Valore restituito

Diapositive aggiunte

## Osservazioni

```cpp
// Crea un'istanza della classe Presentation.
auto presentation = System::MakeObject<Presentation>();

{
    auto htmlStream = System::IO::File::OpenRead(u"page.html");

    // Chiama il metodo AddFromHtml e passa il file HTML.
    presentation->get_Slides()->AddFromHtml(htmlStream);
}

// Usa il metodo Save per salvare il file come documento PowerPoint.
presentation->Save(u"MyPresentation.pptx", SaveFormat::Pptx);
```

## Vedi anche

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [ISlide](../../islide/)
* Classe [String](../../../system/string/)
* Classe [IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)
* Classe [SlideCollection](../)
* Classe [TextReader](../../../system.io/textreader/)
* Classe [Stream](../../../system.io/stream/)
* Namespace [Aspose::Slides](../../)
* Libreria [Aspose.Slides](../../../)