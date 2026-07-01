---
title: Save
second_title: Riferimento API di Aspose.Sildes per .NET
description: Salva tutte le diapositive di una presentazione in un file con il formato specificato.
type: docs
weight: 390
url: /it/aspose.slides/presentation/save/
---
## Save(string, SaveFormat) {#save_5}

Salva tutte le diapositive di una presentazione in un file con il formato specificato.

```csharp
public void Save(string fname, SaveFormat format)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| fname | String | Percorso del file creato. |
| format | SaveFormat | Formato dei dati esportati. |

### Vedi anche

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* classe [Presentation](../../presentation)
* spazio dei nomi [Aspose.Slides](../../presentation)
* assembly [Aspose.Slides](../../../)

---

## Save(Stream, SaveFormat) {#save_1}

Salva tutte le diapositive di una presentazione su uno stream nel formato specificato.

```csharp
public void Save(Stream stream, SaveFormat format)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| stream | Stream | Stream di output. |
| format | SaveFormat | Formato dei dati esportati. |

### Vedi anche

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* classe [Presentation](../../presentation)
* spazio dei nomi [Aspose.Slides](../../presentation)
* assembly [Aspose.Slides](../../../)

---

## Save(string, SaveFormat, ISaveOptions) {#save_6}

```csharp
public void Save(string fname, SaveFormat format, ISaveOptions options)
```

### Vedi anche

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* interfaccia [ISaveOptions](../../../aspose.slides.export/isaveoptions)
* classe [Presentation](../../presentation)
* spazio dei nomi [Aspose.Slides](../../presentation)
* assembly [Aspose.Slides](../../../)

---

## Save(Stream, SaveFormat, ISaveOptions) {#save_2}

Salva tutte le diapositive di una presentazione su uno stream nel formato specificato e con opzioni aggiuntive.

```csharp
public void Save(Stream stream, SaveFormat format, ISaveOptions options)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| stream | Stream | Stream di output. |
| format | SaveFormat | Formato dei dati esportati. |
| options | ISaveOptions | Opzioni di formato aggiuntive. |

### Eccezioni

| eccezione | condizione |
| --- | --- |
| NotSupportedException | Se si tenta di salvare un file crittografato in un formato diverso da Office 2007-2010 |

### Vedi anche

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* interfaccia [ISaveOptions](../../../aspose.slides.export/isaveoptions)
* classe [Presentation](../../presentation)
* spazio dei nomi [Aspose.Slides](../../presentation)
* assembly [Aspose.Slides](../../../)

---

## Save(IXamlOptions) {#save}

Salva tutte le diapositive di una presentazione in un insieme di file che rappresentano il markup XAML.

```csharp
public void Save(IXamlOptions options)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| options | IXamlOptions | Le opzioni del formato XAML. |

### Esempi

```csharp
[C#]
using (Presentation pres = new Presentation("pres.pptx"))
{
	pres.Save(new XamlOptions { ExportHiddenSlides = true });
}
```

### Vedi anche

* interfaccia [IXamlOptions](../../../aspose.slides.export.xaml/ixamloptions)
* classe [Presentation](../../presentation)
* spazio dei nomi [Aspose.Slides](../../presentation)
* assembly [Aspose.Slides](../../../)

---

## Save(string, int[], SaveFormat) {#save_7}

Salva le diapositive specificate di una presentazione in un file con il formato specificato mantenendo il numero di pagina.

```csharp
public void Save(string fname, int[] slides, SaveFormat format)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| fname | String | Percorso del file creato. |
| slides | Int32[] | Array con le posizioni delle diapositive, a partire da 1. |
| format | SaveFormat | Formato dei dati esportati. |

### Eccezioni

| eccezione | condizione |
| --- | --- |
| ArgumentNullException | Quando il parametro stream o slides è null. |
| ArgumentOutOfRangeException | Quando il parametro slides contiene numeri di pagina errati. |
| InvalidOperationException | Quando viene utilizzato un SaveFormat non supportato, ad es. PPTX, PPTM, PPSX, PPSM, POTX, POTM, PPT, ODP. |

### Vedi anche

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* classe [Presentation](../../presentation)
* spazio dei nomi [Aspose.Slides](../../presentation)
* assembly [Aspose.Slides](../../../)

---

## Save(string, int[], SaveFormat, ISaveOptions) {#save_8}

Salva le diapositive specificate di una presentazione in un file con il formato specificato mantenendo il numero di pagina.

```csharp
public void Save(string fname, int[] slides, SaveFormat format, ISaveOptions options)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| fname | String | Percorso del file creato. |
| slides | Int32[] | Array con le posizioni delle diapositive, a partire da 1. |
| format | SaveFormat | Formato dei dati esportati. |
| options | ISaveOptions | Opzioni di formato aggiuntive. |

### Vedi anche

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* interfaccia [ISaveOptions](../../../aspose.slides.export/isaveoptions)
* classe [Presentation](../../presentation)
* spazio dei nomi [Aspose.Slides](../../presentation)
* assembly [Aspose.Slides](../../../)

---

## Save(Stream, int[], SaveFormat) {#save_3}

Salva le diapositive specificate di una presentazione su uno stream nel formato specificato mantenendo il numero di pagina.

```csharp
public void Save(Stream stream, int[] slides, SaveFormat format)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| stream | Stream | Stream di output. |
| slides | Int32[] | Array con le posizioni delle diapositive, a partire da 1. |
| format | SaveFormat | Formato dei dati esportati. |

### Vedi anche

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* classe [Presentation](../../presentation)
* spazio dei nomi [Aspose.Slides](../../presentation)
* assembly [Aspose.Slides](../../../)

---

## Save(Stream, int[], SaveFormat, ISaveOptions) {#save_4}

Salva le diapositive specificate di una presentazione su uno stream nel formato specificato mantenendo il numero di pagina.

```csharp
public void Save(Stream stream, int[] slides, SaveFormat format, ISaveOptions options)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| stream | Stream | Stream di output. |
| slides | Int32[] | Array con le posizioni delle diapositive, a partire da 1. |
| format | SaveFormat | Formato dei dati esportati. |
| options | ISaveOptions | Opzioni di formato aggiuntive. |

### Eccezioni

| eccezione | condizione |
| --- | --- |
| ArgumentNullException | Quando il parametro stream o slides è null. |
| ArgumentOutOfRangeException | Quando il parametro slides contiene numeri di pagina errati. |
| InvalidOperationException | Quando viene utilizzato un SaveFormat non supportato, ad es. PPTX, PPTM, PPSX, PPSM, POTX, POTM, PPT, ODP. |

### Esempi

Il seguente esempio mostra come convertire PowerPoint in PNG.

```csharp
[C#]
using (Presentation pres = new Presentation("pres.pptx"))
{
    for (var index = 0; index < pres.Slides.Count; index++)
    {
        ISlide slide = pres.Slides[index];
        slide.GetThumbnail().Save($"slide_{index}.png", ImageFormat.Png);
    }
}
```

Il seguente esempio mostra come convertire PowerPoint in PNG con dimensioni personalizzate.

```csharp
[C#]
using (Presentation pres = new Presentation("pres.pptx"))
{
    float scaleX = 2f;
    float scaleY = 2f;
    for (var index = 0; index < pres.Slides.Count; index++)
    {
        ISlide slide = pres.Slides[index];
        slide.GetThumbnail(scaleX, scaleY).Save($"slide_{index}.png", ImageFormat.Png);
    }
}
```

Il seguente esempio mostra come convertire PowerPoint in PNG con dimensione personalizzata.

```csharp
[C#]
using (Presentation pres = new Presentation("pres.pptx"))
{
    Size size = new Size(960, 720);
    for (var index = 0; index < pres.Slides.Count; index++)
    {
        ISlide slide = pres.Slides[index];
        slide.GetThumbnail(size).Save($"slide_{index}.png", ImageFormat.Png);
    }
}
```

### Vedi anche

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* interfaccia [ISaveOptions](../../../aspose.slides.export/isaveoptions)
* classe [Presentation](../../presentation)
* spazio dei nomi [Aspose.Slides](../../presentation)
* assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->