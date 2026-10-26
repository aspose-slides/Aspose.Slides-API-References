---
title: AddFromHtml()
second_title: Riferimento API di Aspose.Slides per C++ 
description: Crea slide da testo HTML e le aggiunge alla fine della raccolta.
type: docs
weight: 144
url: /it/aspose.slides/islidecollection/addfromhtml/
---
## ISlideCollection::AddFromHtml(System::String, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String) metodo


Crea slide da testo HTML e le aggiunge alla fine della raccolta.

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::AddFromHtml(System::String htmlText, System::SharedPtr<Import::IExternalResourceResolver> resolver, System::String uri)=0
```


### Argomenti

| Parameter | Type | Description |
| --- | --- | --- |
| htmlText | [System::String](../../../system/string/) | Html da aggiungere. |
| resolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | Un oggetto di callback usato per recuperare oggetti esterni. Se questo parametro è nullo tutti gli oggetti esterni saranno ignorati. |
| uri | [System::String](../../../system/string/) | Un URI dell'HTML specificato. Usato per risolvere i collegamenti relativi. |

### Valore restituito

Slide aggiunte.

## ISlideCollection::AddFromHtml(System::String) metodo


Crea slide da testo HTML e le aggiunge alla fine della raccolta.

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::AddFromHtml(System::String htmlText)=0
```


### Argomenti

| Parameter | Type | Description |
| --- | --- | --- |
| htmlText | [System::String](../../../system/string/) | Html da aggiungere. |

### Valore restituito

Slide aggiunte

## ISlideCollection::AddFromHtml(System::SharedPtr\<System::IO::TextReader\>, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String) metodo


Crea slide da testo HTML e le aggiunge alla fine della raccolta.

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::AddFromHtml(System::SharedPtr<System::IO::TextReader> htmlReader, System::SharedPtr<Import::IExternalResourceResolver> resolver, System::String uri)=0
```


### Argomenti

| Parameter | Type | Description |
| --- | --- | --- |
| htmlReader | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::TextReader](../../../system.io/textreader/)\> | Oggetto TextReader che sarà usato come fonte di un file HTML. |
| resolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | Un oggetto di callback usato per recuperare oggetti esterni. Se questo parametro è nullo tutti gli oggetti esterni saranno ignorati. |
| uri | [System::String](../../../system/string/) | Un URI dell'HTML specificato. Usato per risolvere i collegamenti relativi. |

### Valore restituito

Slide aggiunte.

## ISlideCollection::AddFromHtml(System::SharedPtr\<System::IO::TextReader\>) metodo


Crea slide da testo HTML e le aggiunge alla fine della raccolta.

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::AddFromHtml(System::SharedPtr<System::IO::TextReader> htmlReader)=0
```


### Argomenti

| Parameter | Type | Description |
| --- | --- | --- |
| htmlReader | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::TextReader](../../../system.io/textreader/)\> | Oggetto TextReader che sarà usato come fonte di un file HTML. |

### Valore restituito

Slide aggiunte

## ISlideCollection::AddFromHtml(System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String) metodo


Crea slide da testo HTML e le aggiunge alla fine della raccolta.

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::AddFromHtml(System::SharedPtr<System::IO::Stream> htmlStream, System::SharedPtr<Import::IExternalResourceResolver> resolver, System::String uri)=0
```


### Argomenti

| Parameter | Type | Description |
| --- | --- | --- |
| htmlStream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Oggetto Stream che sarà usato come fonte di un file HTML. |
| resolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | Un oggetto di callback usato per recuperare oggetti esterni. Se questo parametro è nullo tutti gli oggetti esterni saranno ignorati. |
| uri | [System::String](../../../system/string/) | Un URI dell'HTML specificato. Usato per risolvere i collegamenti relativi. |

### Valore restituito

Slide aggiunte.

## ISlideCollection::AddFromHtml(System::SharedPtr\<System::IO::Stream\>) metodo


Crea slide da testo HTML e le aggiunge alla fine della raccolta.

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::AddFromHtml(System::SharedPtr<System::IO::Stream> htmlStream)=0
```


### Argomenti

| Parameter | Type | Description |
| --- | --- | --- |
| htmlStream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Oggetto Stream che sarà usato come fonte di un file HTML. |

### Valore restituito

Slide aggiunte

## Vedi anche

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [ISlide](../../islide/)
* Classe [String](../../../system/string/)
* Classe [IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)
* Classe [ISlideCollection](../)
* Classe [TextReader](../../../system.io/textreader/)
* Classe [Stream](../../../system.io/stream/)
* Spazio dei nomi [Aspose::Slides](../../)
* Libreria [Aspose.Slides](../../../)