---
title: InsertFromHtml()
second_title: Riferimento API di Aspose.Slides per C++
description: Crea diapositive dal testo HTML e le inserisce nella collezione nella posizione specificata.
type: docs
weight: 209
url: /it/aspose.slides/slidecollection/insertfromhtml/
---
## SlideCollection::InsertFromHtml(int32_t, System::String, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String) metodo

Crea diapositive dal testo HTML e le inserisce nella collezione nella posizione specificata.

```cpp
System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::SlideCollection::InsertFromHtml(int32_t index, System::String htmlText, System::SharedPtr<Import::IExternalResourceResolver> resolver, System::String uri) override
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | **int32_t** | Posizione in cui inserire. |
| htmlText | [System::String](../../../system/string/) | Html da aggiungere. |
| resolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | Un oggetto di callback utilizzato per recuperare oggetti esterni. Se questo parametro è nullo, tutti gli oggetti esterni saranno ignorati. |
| uri | [System::String](../../../system/string/) | Un URI dell'HTML specificato. Usato per risolvere i collegamenti relativi. |

### Valore restituito

Diapositive aggiunte.

## SlideCollection::InsertFromHtml(int32_t, System::String, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String, bool) metodo

Crea diapositive dal testo HTML e le inserisce nella collezione nella posizione specificata.

```cpp
System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::SlideCollection::InsertFromHtml(int32_t index, System::String htmlText, System::SharedPtr<Import::IExternalResourceResolver> resolver, System::String uri, bool useSlideWithIndexAsStart) override
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | **int32_t** | Posizione in cui inserire. |
| htmlText | [System::String](../../../system/string/) | Html da aggiungere. |
| resolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | Un oggetto di callback utilizzato per recuperare oggetti esterni. Se questo parametro è nullo, tutti gli oggetti esterni saranno ignorati. |
| uri | [System::String](../../../system/string/) | Un URI dell'HTML specificato. Usato per risolvere i collegamenti relativi. |
| useSlideWithIndexAsStart | **bool** | Questa flag determina come avviare l'inserimento: da una nuova diapositiva o dalla diapositiva con l'indice specificato. Se **true**, l'inserimento dei dati inizierà da uno spazio vuoto sulla diapositiva con l'indice specificato. Se **false**, i dati saranno aggiunti alle diapositive create. |

### Valore restituito

Diapositive aggiunte.

## SlideCollection::InsertFromHtml(int32_t, System::String) metodo

Crea diapositive dal testo HTML e le inserisce nella collezione nella posizione specificata.

```cpp
System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::SlideCollection::InsertFromHtml(int32_t index, System::String htmlText) override
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | **int32_t** | Posizione in cui inserire. |
| htmlText | [System::String](../../../system/string/) | Html da aggiungere. |

### Valore restituito

Diapositive aggiunte

## SlideCollection::InsertFromHtml(int32_t, System::String, bool) metodo

Crea diapositive dal testo HTML e le inserisce nella collezione nella posizione specificata.

```cpp
System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::SlideCollection::InsertFromHtml(int32_t index, System::String htmlText, bool useSlideWithIndexAsStart) override
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | **int32_t** | Posizione in cui inserire. |
| htmlText | [System::String](../../../system/string/) | Html da aggiungere. |
| useSlideWithIndexAsStart | **bool** | Questa flag determina come avviare l'inserimento: da una nuova diapositiva o dalla diapositiva con l'indice specificato. Se **true**, l'inserimento dei dati inizierà da uno spazio vuoto sulla diapositiva con l'indice specificato. Se **false**, i dati saranno aggiunti alle diapositive create. |

### Valore restituito

Diapositive aggiunte

## SlideCollection::InsertFromHtml(int32_t, System::SharedPtr\<System::IO::TextReader\>, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String) metodo

Crea diapositive dal testo HTML e le inserisce nella collezione nella posizione specificata.

```cpp
System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::SlideCollection::InsertFromHtml(int32_t index, System::SharedPtr<System::IO::TextReader> htmlReader, System::SharedPtr<Import::IExternalResourceResolver> resolver, System::String uri) override
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | **int32_t** | Posizione in cui inserire. |
| htmlReader | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::TextReader](../../../system.io/textreader/)\> | Oggetto TextReader che sarà usato come sorgente di un file HTML. |
| resolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | Un oggetto di callback utilizzato per recuperare oggetti esterni. Se questo parametro è nullo, tutti gli oggetti esterni saranno ignorati. |
| uri | [System::String](../../../system/string/) | Un URI dell'HTML specificato. Usato per risolvere i collegamenti relativi. |

### Valore restituito

Diapositive aggiunte.

## SlideCollection::InsertFromHtml(int32_t, System::SharedPtr\<System::IO::TextReader\>) metodo

Crea diapositive dal testo HTML e le inserisce nella collezione nella posizione specificata.

```cpp
System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::SlideCollection::InsertFromHtml(int32_t index, System::SharedPtr<System::IO::TextReader> htmlReader) override
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | **int32_t** | Posizione in cui inserire. |
| htmlReader | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::TextReader](../../../system.io/textreader/)\> | Oggetto TextReader che sarà usato come sorgente di un file HTML. |

### Valore restituito

Diapositive aggiunte

## SlideCollection::InsertFromHtml(int32_t, System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String) metodo

Crea diapositive dal testo HTML e le inserisce nella collezione nella posizione specificata.

```cpp
System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::SlideCollection::InsertFromHtml(int32_t index, System::SharedPtr<System::IO::Stream> htmlStream, System::SharedPtr<Import::IExternalResourceResolver> resolver, System::String uri) override
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | **int32_t** | Posizione in cui inserire. |
| htmlStream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Un oggetto Stream che sarà usato come sorgente di un file HTML. |
| resolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | Un oggetto di callback utilizzato per recuperare oggetti esterni. Se questo parametro è nullo, tutti gli oggetti esterni saranno ignorati. |
| uri | [System::String](../../../system/string/) | Un URI dell'HTML specificato. Usato per risolvere i collegamenti relativi. |

### Valore restituito

Diapositive aggiunte.

## SlideCollection::InsertFromHtml(int32_t, System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String, bool) metodo

Crea diapositive dal testo HTML e le inserisce nella collezione nella posizione specificata.

```cpp
System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::SlideCollection::InsertFromHtml(int32_t index, System::SharedPtr<System::IO::Stream> htmlStream, System::SharedPtr<Import::IExternalResourceResolver> resolver, System::String uri, bool useSlideWithIndexAsStart) override
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | **int32_t** | Posizione in cui inserire. |
| htmlStream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Un oggetto Stream che sarà usato come sorgente di un file HTML. |
| resolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | Un oggetto di callback utilizzato per recuperare oggetti esterni. Se questo parametro è nullo, tutti gli oggetti esterni saranno ignorati. |
| uri | [System::String](../../../system/string/) | Un URI dell'HTML specificato. Usato per risolvere i collegamenti relativi. |
| useSlideWithIndexAsStart | **bool** | Questa flag determina come avviare l'inserimento: da una nuova diapositiva o dalla diapositiva con l'indice specificato. Se **true**, l'inserimento dei dati inizierà da uno spazio vuoto sulla diapositiva con l'indice specificato. Se **false**, i dati saranno aggiunti alle diapositive create. |

### Valore restituito

Diapositive aggiunte.

## SlideCollection::InsertFromHtml(int32_t, System::SharedPtr\<System::IO::Stream\>) metodo

Crea diapositive dal testo HTML e le inserisce nella collezione nella posizione specificata.

```cpp
System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::SlideCollection::InsertFromHtml(int32_t index, System::SharedPtr<System::IO::Stream> htmlStream) override
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | **int32_t** | Posizione in cui inserire. |
| htmlStream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Un oggetto Stream che sarà usato come sorgente di un file HTML. |

### Valore restituito

Diapositive aggiunte

## SlideCollection::InsertFromHtml(int32_t, System::SharedPtr\<System::IO::Stream\>, bool) metodo

Crea diapositive dal testo HTML e le inserisce nella collezione nella posizione specificata.

```cpp
System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::SlideCollection::InsertFromHtml(int32_t index, System::SharedPtr<System::IO::Stream> htmlStream, bool useSlideWithIndexAsStart) override
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | **int32_t** | Posizione in cui inserire. |
| htmlStream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Un oggetto Stream che sarà usato come sorgente di un file HTML. |
| useSlideWithIndexAsStart | **bool** | Questa flag determina come avviare l'inserimento: da una nuova diapositiva o dalla diapositiva con l'indice specificato. Se **true**, l'inserimento dei dati inizierà da uno spazio vuoto sulla diapositiva con l'indice specificato. Se **false**, i dati saranno aggiunti alle diapositive create. |

### Valore restituito

Diapositive aggiunte

## Vedi anche

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