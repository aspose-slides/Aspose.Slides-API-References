---
title: InsertFromHtml()
second_title: Riferimento API di Aspose.Slides per C++
description: Crea diapositive dal testo HTML e le inserisce nella raccolta nella posizione specificata.
type: docs
weight: 157
url: /it/aspose.slides/islidecollection/insertfromhtml/
---
## ISlideCollection::InsertFromHtml(int32_t, System::String, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String) method


Crea diapositive dal testo HTML e le inserisce nella raccolta nella posizione specificata.

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::InsertFromHtml(int32_t index, System::String htmlText, System::SharedPtr<Import::IExternalResourceResolver> resolver, System::String uri)=0
```


### Argomenti

| Parameter | Type | Description |
| --- | --- | --- |
| index | **int32_t** | Posizione in cui inserire. |
| htmlText | [System::String](../../../system/string/) | HTML da aggiungere. |
| resolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | Un oggetto callback usato per recuperare oggetti esterni. Se questo parametro è null tutti gli oggetti esterni saranno ignorati. |
| uri | [System::String](../../../system/string/) | Un URI dell'HTML specificato. Usato per risolvere i collegamenti relativi. |

### Valore di ritorno

Diapositive aggiunte.

## ISlideCollection::InsertFromHtml(int32_t, System::String) method


Crea diapositive dal testo HTML e le inserisce nella raccolta nella posizione specificata.

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::InsertFromHtml(int32_t index, System::String htmlText)=0
```


### Argomenti

| Parameter | Type | Description |
| --- | --- | --- |
| index | **int32_t** | Posizione in cui inserire. |
| htmlText | [System::String](../../../system/string/) | HTML da aggiungere. |

### Valore di ritorno

Diapositive aggiunte

## ISlideCollection::InsertFromHtml(int32_t, System::SharedPtr\<System::IO::TextReader\>, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String) method


Crea diapositive dal testo HTML e le inserisce nella raccolta nella posizione specificata.

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::InsertFromHtml(int32_t index, System::SharedPtr<System::IO::TextReader> htmlReader, System::SharedPtr<Import::IExternalResourceResolver> resolver, System::String uri)=0
```


### Argomenti

| Parameter | Type | Description |
| --- | --- | --- |
| index | **int32_t** | Posizione in cui inserire. |
| htmlReader | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::TextReader](../../../system.io/textreader/)\> | Oggetto TextReader che verrà usato come sorgente di un file HTML. |
| resolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | Un oggetto callback usato per recuperare oggetti esterni. Se questo parametro è null tutti gli oggetti esterni saranno ignorati. |
| uri | [System::String](../../../system/string/) | Un URI dell'HTML specificato. Usato per risolvere i collegamenti relativi. |

### Valore di ritorno

Diapositive aggiunte.

## ISlideCollection::InsertFromHtml(int32_t, System::SharedPtr\<System::IO::TextReader\>) method


Crea diapositive dal testo HTML e le inserisce nella raccolta nella posizione specificata.

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::InsertFromHtml(int32_t index, System::SharedPtr<System::IO::TextReader> htmlReader)=0
```


### Argomenti

| Parameter | Type | Description |
| --- | --- | --- |
| index | **int32_t** | Posizione in cui inserire. |
| htmlReader | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::TextReader](../../../system.io/textreader/)\> | Oggetto TextReader che verrà usato come sorgente di un file HTML. |

### Valore di ritorno

Diapositive aggiunte

## ISlideCollection::InsertFromHtml(int32_t, System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String) method


Crea diapositive dal testo HTML e le inserisce nella raccolta nella posizione specificata.

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::InsertFromHtml(int32_t index, System::SharedPtr<System::IO::Stream> htmlStream, System::SharedPtr<Import::IExternalResourceResolver> resolver, System::String uri)=0
```


### Argomenti

| Parameter | Type | Description |
| --- | --- | --- |
| index | **int32_t** | Posizione in cui inserire. |
| htmlStream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Un oggetto Stream che verrà usato come sorgente di un file HTML. |
| resolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | Un oggetto callback usato per recuperare oggetti esterni. Se questo parametro è null tutti gli oggetti esterni saranno ignorati. |
| uri | [System::String](../../../system/string/) | Un URI dell'HTML specificato. Usato per risolvere i collegamenti relativi. |

### Valore di ritorno

Diapositive aggiunte.

## ISlideCollection::InsertFromHtml(int32_t, System::SharedPtr\<System::IO::Stream\>) method


Crea diapositive dal testo HTML e le inserisce nella raccolta nella posizione specificata.

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::InsertFromHtml(int32_t index, System::SharedPtr<System::IO::Stream> htmlStream)=0
```


### Argomenti

| Parameter | Type | Description |
| --- | --- | --- |
| index | **int32_t** | Posizione in cui inserire. |
| htmlStream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Un oggetto Stream che verrà usato come sorgente di un file HTML. |

### Valore di ritorno

Diapositive aggiunte

## ISlideCollection::InsertFromHtml(int32_t, System::String, bool) method


Crea diapositive dal testo HTML e le inserisce nella raccolta nella posizione specificata.

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::InsertFromHtml(int32_t index, System::String htmlText, bool useSlideWithIndexAsStart)=0
```


### Argomenti

| Parameter | Type | Description |
| --- | --- | --- |
| index | **int32_t** | Posizione in cui inserire. |
| htmlText | [System::String](../../../system/string/) | HTML da aggiungere. |
| useSlideWithIndexAsStart | **bool** | Questo flag determina come avviare l'inserimento: da una nuova diapositiva o dalla diapositiva con l'indice specificato. Se **true**, l'inserimento dei dati inizierà da uno spazio vuoto nella diapositiva con l'indice specificato. Se **false**, i dati saranno aggiunti alle diapositive create. |

### Valore di ritorno

Diapositive aggiunte

## ISlideCollection::InsertFromHtml(int32_t, System::String, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String, bool) method


Crea diapositive dal testo HTML e le inserisce nella raccolta nella posizione specificata.

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::InsertFromHtml(int32_t index, System::String htmlText, System::SharedPtr<Import::IExternalResourceResolver> resolver, System::String uri, bool useSlideWithIndexAsStart)=0
```


### Argomenti

| Parameter | Type | Description |
| --- | --- | --- |
| index | **int32_t** | Posizione in cui inserire. |
| htmlText | [System::String](../../../system/string/) | HTML da aggiungere. |
| resolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | Un oggetto callback usato per recuperare oggetti esterni. Se questo parametro è null tutti gli oggetti esterni saranno ignorati. |
| uri | [System::String](../../../system/string/) | Un URI dell'HTML specificato. Usato per risolvere i collegamenti relativi. |
| useSlideWithIndexAsStart | **bool** | Questo flag determina come avviare l'inserimento: da una nuova diapositiva o dalla diapositiva con l'indice specificato. Se **true**, l'inserimento dei dati inizierà da uno spazio vuoto nella diapositiva con l'indice specificato. Se **false**, i dati saranno aggiunti alle diapositive create. |

### Valore di ritorno

Diapositive aggiunte.

## ISlideCollection::InsertFromHtml(int32_t, System::SharedPtr\<System::IO::Stream\>, bool) method


Crea diapositive dal testo HTML e le inserisce nella raccolta nella posizione specificata.

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::InsertFromHtml(int32_t index, System::SharedPtr<System::IO::Stream> htmlStream, bool useSlideWithIndexAsStart)=0
```


### Argomenti

| Parameter | Type | Description |
| --- | --- | --- |
| index | **int32_t** | Posizione in cui inserire. |
| htmlStream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Un oggetto Stream che verrà usato come sorgente di un file HTML. |
| useSlideWithIndexAsStart | **bool** | Questo flag determina come avviare l'inserimento: da una nuova diapositiva o dalla diapositiva con l'indice specificato. Se **true**, l'inserimento dei dati inizierà da uno spazio vuoto nella diapositiva con l'indice specificato. Se **false**, i dati saranno aggiunti alle diapositive create. |

### Valore di ritorno

Diapositive aggiunte

## ISlideCollection::InsertFromHtml(int32_t, System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String, bool) method


Crea diapositive dal testo HTML e le inserisce nella raccolta nella posizione specificata.

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::InsertFromHtml(int32_t index, System::SharedPtr<System::IO::Stream> htmlStream, System::SharedPtr<Import::IExternalResourceResolver> resolver, System::String uri, bool useSlideWithIndexAsStart)=0
```


### Argomenti

| Parameter | Type | Description |
| --- | --- | --- |
| index | **int32_t** | Posizione in cui inserire. |
| htmlStream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Un oggetto Stream che verrà usato come sorgente di un file HTML. |
| resolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | Un oggetto callback usato per recuperare oggetti esterni. Se questo parametro è null tutti gli oggetti esterni saranno ignorati. |
| uri | [System::String](../../../system/string/) | Un URI dell'HTML specificato. Usato per risolvere i collegamenti relativi. |
| useSlideWithIndexAsStart | **bool** | Questo flag determina come avviare l'inserimento: da una nuova diapositiva o dalla diapositiva con l'indice specificato. Se **true**, l'inserimento dei dati inizierà da uno spazio vuoto nella diapositiva con l'indice specificato. Se **false**, i dati saranno aggiunti alle diapositive create. |

### Valore di ritorno

Diapositive aggiunte.

## Vedi anche

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