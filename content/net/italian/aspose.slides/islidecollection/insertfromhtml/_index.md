---
title: InsertFromHtml
second_title: Aspose.Sildes per .NET Riferimento API
description: Crea diapositive dal testo HTML e le inserisce nella raccolta nella posizione specificata.
type: docs
weight: 90
url: /it/aspose.slides/islidecollection/insertfromhtml/
---
## InsertFromHtml(int, string, IExternalResourceResolver, string) {#insertfromhtml_7}

Crea diapositive dal testo HTML e le inserisce nella raccolta nella posizione specificata.

```csharp
public ISlide[] InsertFromHtml(int index, string htmlText, IExternalResourceResolver resolver, 
    string uri)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | Int32 | Posizione in cui inserire. |
| htmlText | String | HTML da aggiungere. |
| resolver | IExternalResourceResolver | Un oggetto di callback usato per recuperare oggetti esterni. Se questo parametro è null tutti gli oggetti esterni verranno ignorati. |
| uri | String | Un URI dell'HTML specificato. Usato per risolvere i collegamenti relativi. |

### Valore restituito

Diapositive aggiunte.

### Vedi anche

* interfaccia [ISlide](../../islide)
* interfaccia [IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver)
* interfaccia [ISlideCollection](../../islidecollection)
* spazio dei nomi [Aspose.Slides](../../islidecollection)
* assembly [Aspose.Slides](../../../)

---

## InsertFromHtml(int, string) {#insertfromhtml_6}

Crea diapositive dal testo HTML e le inserisce nella raccolta nella posizione specificata.

```csharp
public ISlide[] InsertFromHtml(int index, string htmlText)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | Int32 | Posizione in cui inserire. |
| htmlText | String | HTML da aggiungere. |

### Valore restituito

Diapositive aggiunte

### Vedi anche

* interfaccia [ISlide](../../islide)
* interfaccia [ISlideCollection](../../islidecollection)
* spazio dei nomi [Aspose.Slides](../../islidecollection)
* assembly [Aspose.Slides](../../../)

---

## InsertFromHtml(int, TextReader, IExternalResourceResolver, string) {#insertfromhtml_5}

Crea diapositive dal testo HTML e le inserisce nella raccolta nella posizione specificata.

```csharp
public ISlide[] InsertFromHtml(int index, TextReader htmlReader, 
    IExternalResourceResolver resolver, string uri)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | Int32 | Posizione in cui inserire. |
| htmlReader | TextReader | Oggetto TextReader che verrà usato come sorgente di un file HTML. |
| resolver | IExternalResourceResolver | Un oggetto di callback usato per recuperare oggetti esterni. Se questo parametro è null tutti gli oggetti esterni verranno ignorati. |
| uri | String | Un URI dell'HTML specificato. Usato per risolvere i collegamenti relativi. |

### Valore restituito

Diapositive aggiunte.

### Vedi anche

* interfaccia [ISlide](../../islide)
* interfaccia [IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver)
* interfaccia [ISlideCollection](../../islidecollection)
* spazio dei nomi [Aspose.Slides](../../islidecollection)
* assembly [Aspose.Slides](../../../)

---

## InsertFromHtml(int, TextReader) {#insertfromhtml_4}

Crea diapositive dal testo HTML e le inserisce nella raccolta nella posizione specificata.

```csharp
public ISlide[] InsertFromHtml(int index, TextReader htmlReader)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | Int32 | Posizione in cui inserire. |
| htmlReader | TextReader | Oggetto TextReader che verrà usato come sorgente di un file HTML. |

### Valore restituito

Diapositive aggiunte

### Vedi anche

* interfaccia [ISlide](../../islide)
* interfaccia [ISlideCollection](../../islidecollection)
* spazio dei nomi [Aspose.Slides](../../islidecollection)
* assembly [Aspose.Slides](../../../)

---

## InsertFromHtml(int, Stream, IExternalResourceResolver, string) {#insertfromhtml_1}

Crea diapositive dal testo HTML e le inserisce nella raccolta nella posizione specificata.

```csharp
public ISlide[] InsertFromHtml(int index, Stream htmlStream, IExternalResourceResolver resolver, 
    string uri)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | Int32 | Posizione in cui inserire. |
| htmlStream | Stream | Oggetto Stream che verrà usato come sorgente di un file HTML. |
| resolver | IExternalResourceResolver | Un oggetto di callback usato per recuperare oggetti esterni. Se questo parametro è null tutti gli oggetti esterni verranno ignorati. |
| uri | String | Un URI dell'HTML specificato. Usato per risolvere i collegamenti relativi. |

### Valore restituito

Diapositive aggiunte.

### Vedi anche

* interfaccia [ISlide](../../islide)
* interfaccia [IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver)
* interfaccia [ISlideCollection](../../islidecollection)
* spazio dei nomi [Aspose.Slides](../../islidecollection)
* assembly [Aspose.Slides](../../../)

---

## InsertFromHtml(int, Stream) {#insertfromhtml}

Crea diapositive dal testo HTML e le inserisce nella raccolta nella posizione specificata.

```csharp
public ISlide[] InsertFromHtml(int index, Stream htmlStream)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | Int32 | Posizione in cui inserire. |
| htmlStream | Stream | Oggetto Stream che verrà usato come sorgente di un file HTML. |

### Valore restituito

Diapositive aggiunte

### Vedi anche

* interfaccia [ISlide](../../islide)
* interfaccia [ISlideCollection](../../islidecollection)
* spazio dei nomi [Aspose.Slides](../../islidecollection)
* assembly [Aspose.Slides](../../../)

---

## InsertFromHtml(int, string, bool) {#insertfromhtml_9}

Crea diapositive dal testo HTML e le inserisce nella raccolta nella posizione specificata.

```csharp
public ISlide[] InsertFromHtml(int index, string htmlText, bool useSlideWithIndexAsStart)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | Int32 | Posizione in cui inserire. |
| htmlText | String | HTML da aggiungere. |
| useSlideWithIndexAsStart | Boolean | Questo flag determina come avviare l'inserimento: da una nuova diapositiva o dalla diapositiva con l'indice specificato. Se **true**, l'inserimento dei dati inizierà da uno spazio vuoto sulla diapositiva con l'indice specificato. Se **false**, i dati verranno aggiunti alle diapositive create. |

### Valore restituito

Diapositive aggiunte

### Vedi anche

* interfaccia [ISlide](../../islide)
* interfaccia [ISlideCollection](../../islidecollection)
* spazio dei nomi [Aspose.Slides](../../islidecollection)
* assembly [Aspose.Slides](../../../)

---

## InsertFromHtml(int, string, IExternalResourceResolver, string, bool) {#insertfromhtml_8}

Crea diapositive dal testo HTML e le inserisce nella raccolta nella posizione specificata.

```csharp
public ISlide[] InsertFromHtml(int index, string htmlText, IExternalResourceResolver resolver, 
    string uri, bool useSlideWithIndexAsStart)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | Int32 | Posizione in cui inserire. |
| htmlText | String | HTML da aggiungere. |
| resolver | IExternalResourceResolver | Un oggetto di callback usato per recuperare oggetti esterni. Se questo parametro è null tutti gli oggetti esterni verranno ignorati. |
| uri | String | Un URI dell'HTML specificato. Usato per risolvere i collegamenti relativi. |
| useSlideWithIndexAsStart | Boolean | Questo flag determina come avviare l'inserimento: da una nuova diapositiva o dalla diapositiva con l'indice specificato. Se **true**, l'inserimento dei dati inizierà da uno spazio vuoto sulla diapositiva con l'indice specificato. Se **false**, i dati verranno aggiunti alle diapositive create. |

### Valore restituito

Diapositive aggiunte.

### Vedi anche

* interfaccia [ISlide](../../islide)
* interfaccia [IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver)
* interfaccia [ISlideCollection](../../islidecollection)
* spazio dei nomi [Aspose.Slides](../../islidecollection)
* assembly [Aspose.Slides](../../../)

---

## InsertFromHtml(int, Stream, bool) {#insertfromhtml_3}

Crea diapositive dal testo HTML e le inserisce nella raccolta nella posizione specificata.

```csharp
public ISlide[] InsertFromHtml(int index, Stream htmlStream, bool useSlideWithIndexAsStart)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | Int32 | Posizione in cui inserire. |
| htmlStream | Stream | Oggetto Stream che verrà usato come sorgente di un file HTML. |
| useSlideWithIndexAsStart | Boolean | Questo flag determina come avviare l'inserimento: da una nuova diapositiva o dalla diapositiva con l'indice specificato. Se **true**, l'inserimento dei dati inizierà da uno spazio vuoto sulla diapositiva con l'indice specificato. Se **false**, i dati verranno aggiunti alle diapositive create. |

### Valore restituito

Diapositive aggiunte

### Vedi anche

* interfaccia [ISlide](../../islide)
* interfaccia [ISlideCollection](../../islidecollection)
* spazio dei nomi [Aspose.Slides](../../islidecollection)
* assembly [Aspose.Slides](../../../)

---

## InsertFromHtml(int, Stream, IExternalResourceResolver, string, bool) {#insertfromhtml_2}

Crea diapositive dal testo HTML e le inserisce nella raccolta nella posizione specificata.

```csharp
public ISlide[] InsertFromHtml(int index, Stream htmlStream, IExternalResourceResolver resolver, 
    string uri, bool useSlideWithIndexAsStart)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | Int32 | Posizione in cui inserire. |
| htmlStream | Stream | Oggetto Stream che verrà usato come sorgente di un file HTML. |
| resolver | IExternalResourceResolver | Un oggetto di callback usato per recuperare oggetti esterni. Se questo parametro è null tutti gli oggetti esterni verranno ignorati. |
| uri | String | Un URI dell'HTML specificato. Usato per risolvere i collegamenti relativi. |
| useSlideWithIndexAsStart | Boolean | Questo flag determina come avviare l'inserimento: da una nuova diapositiva o dalla diapositiva con l'indice specificato. Se **true**, l'inserimento dei dati inizierà da uno spazio vuoto sulla diapositiva con l'indice specificato. Se **false**, i dati verranno aggiunti alle diapositive create. |

### Valore restituito

Diapositive aggiunte.

### Vedi anche

* interfaccia [ISlide](../../islide)
* interfaccia [IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver)
* interfaccia [ISlideCollection](../../islidecollection)
* spazio dei nomi [Aspose.Slides](../../islidecollection)
* assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->