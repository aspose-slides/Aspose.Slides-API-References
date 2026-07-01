---
title: AddFromHtml
second_title: Aspose.Sildes per .NET Riferimento API
description: Crea diapositive dal testo HTML e le aggiunge alla fine della raccolta.
type: docs
weight: 70
url: /it/aspose.slides/slidecollection/addfromhtml/
---
## AddFromHtml(string, IExternalResourceResolver, string) {#addfromhtml_5}

Crea diapositive dal testo HTML e le aggiunge alla fine della raccolta.

```csharp
public ISlide[] AddFromHtml(string htmlText, IExternalResourceResolver resolver, string uri)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| htmlText | String | HTML da aggiungere. |
| resolver | IExternalResourceResolver | Un oggetto di callback usato per recuperare oggetti esterni. Se questo parametro è null, tutti gli oggetti esterni verranno ignorati. |
| uri | String | Un URI dell'HTML specificato. Usato per risolvere i collegamenti relativi. |

### Valore restituito

Diapositive aggiunte.

### Vedi anche

* interfaccia [ISlide](../../islide)
* interfaccia [IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver)
* classe [SlideCollection](../../slidecollection)
* spazio dei nomi [Aspose.Slides](../../slidecollection)
* assembly [Aspose.Slides](../../../)

---

## AddFromHtml(string) {#addfromhtml_4}

Crea diapositive dal testo HTML e le aggiunge alla fine della raccolta.

```csharp
public ISlide[] AddFromHtml(string htmlText)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| htmlText | String | HTML da aggiungere. |

### Valore restituito

Diapositive aggiunte

### Vedi anche

* interfaccia [ISlide](../../islide)
* classe [SlideCollection](../../slidecollection)
* spazio dei nomi [Aspose.Slides](../../slidecollection)
* assembly [Aspose.Slides](../../../)

---

## AddFromHtml(TextReader, IExternalResourceResolver, string) {#addfromhtml_3}

Crea diapositive dal testo HTML e le aggiunge alla fine della raccolta.

```csharp
public ISlide[] AddFromHtml(TextReader htmlReader, IExternalResourceResolver resolver, string uri)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| htmlReader | TextReader | Oggetto TextReader che sarà usato come origine di un file HTML. |
| resolver | IExternalResourceResolver | Un oggetto di callback usato per recuperare oggetti esterni. Se questo parametro è null, tutti gli oggetti esterni verranno ignorati. |
| uri | String | Un URI dell'HTML specificato. Usato per risolvere i collegamenti relativi. |

### Valore restituito

Diapositive aggiunte.

### Vedi anche

* interfaccia [ISlide](../../islide)
* interfaccia [IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver)
* classe [SlideCollection](../../slidecollection)
* spazio dei nomi [Aspose.Slides](../../slidecollection)
* assembly [Aspose.Slides](../../../)

---

## AddFromHtml(TextReader) {#addfromhtml_2}

Crea diapositive dal testo HTML e le aggiunge alla fine della raccolta.

```csharp
public ISlide[] AddFromHtml(TextReader htmlReader)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| htmlReader | TextReader | Oggetto TextReader che sarà usato come origine di un file HTML. |

### Valore restituito

Diapositive aggiunte

### Vedi anche

* interfaccia [ISlide](../../islide)
* classe [SlideCollection](../../slidecollection)
* spazio dei nomi [Aspose.Slides](../../slidecollection)
* assembly [Aspose.Slides](../../../)

---

## AddFromHtml(Stream, IExternalResourceResolver, string) {#addfromhtml_1}

Crea diapositive dal testo HTML e le aggiunge alla fine della raccolta.

```csharp
public ISlide[] AddFromHtml(Stream htmlStream, IExternalResourceResolver resolver, string uri)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| htmlStream | Stream | Un oggetto Stream che sarà usato come origine di un file HTML. |
| resolver | IExternalResourceResolver | Un oggetto di callback usato per recuperare oggetti esterni. Se questo parametro è null, tutti gli oggetti esterni verranno ignorati. |
| uri | String | Un URI dell'HTML specificato. Usato per risolvere i collegamenti relativi. |

### Valore restituito

Diapositive aggiunte.

### Vedi anche

* interfaccia [ISlide](../../islide)
* interfaccia [IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver)
* classe [SlideCollection](../../slidecollection)
* spazio dei nomi [Aspose.Slides](../../slidecollection)
* assembly [Aspose.Slides](../../../)

---

## AddFromHtml(Stream) {#addfromhtml}

Crea diapositive dal testo HTML e le aggiunge alla fine della raccolta.

```csharp
public ISlide[] AddFromHtml(Stream htmlStream)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| htmlStream | Stream | Un oggetto Stream che sarà usato come origine di un file HTML. |

### Valore restituito

Diapositive aggiunte

### Esempi

```csharp
[C#]
// Crea un'istanza della classe Presentation.
using (var presentation = new Presentation())
{
    using (var htmlStream = File.OpenRead("page.html"))
    {
		// Chiama il metodo AddFromHtml e passa il file HTML.
        presentation.Slides.AddFromHtml(htmlStream);
    }
	// Usa il metodo Save per salvare il file come documento PowerPoint.
    presentation.Save("MyPresentation.pptx", SaveFormat.Pptx);
}
```

### Vedi anche

* interfaccia [ISlide](../../islide)
* classe [SlideCollection](../../slidecollection)
* spazio dei nomi [Aspose.Slides](../../slidecollection)
* assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->