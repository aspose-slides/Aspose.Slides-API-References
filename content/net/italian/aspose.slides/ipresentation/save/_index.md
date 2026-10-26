---
title: Save
second_title: Aspose.Sildes per .NET Riferimento API
description: Salva tutte le diapositive di una presentazione in un file con il formato specificato.
type: docs
weight: 380
url: /it/aspose.slides/ipresentation/save/
---
## Save(string, SaveFormat) {#save_5}

Salva tutte le diapositive di una presentazione in un file con il formato specificato.

```csharp
public void Save(string fname, SaveFormat format)
```

| Parameter | Type | Description |
| --- | --- | --- |
| fname | String | Percorso del file creato. |
| format | SaveFormat | Formato dei dati esportati. |

### See Also

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* interface [IPresentation](../../ipresentation)
* namespace [Aspose.Slides](../../ipresentation)
* assembly [Aspose.Slides](../../../)

---

## Save(Stream, SaveFormat) {#save_1}

Salva tutte le diapositive di una presentazione in uno stream nel formato specificato.

```csharp
public void Save(Stream stream, SaveFormat format)
```

| Parameter | Type | Description |
| --- | --- | --- |
| stream | Stream | Stream di output. |
| format | SaveFormat | Formato dei dati esportati. |

### See Also

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* interface [IPresentation](../../ipresentation)
* namespace [Aspose.Slides](../../ipresentation)
* assembly [Aspose.Slides](../../../)

---

## Save(string, SaveFormat, ISaveOptions) {#save_6}

Salva tutte le diapositive di una presentazione in un file con il formato specificato e con opzioni aggiuntive.

```csharp
public void Save(string fname, SaveFormat format, ISaveOptions options)
```

| Parameter | Type | Description |
| --- | --- | --- |
| fname | String | Percorso del file creato. |
| format | SaveFormat | Formato dei dati esportati. |
| options | ISaveOptions | Opzioni di formato aggiuntive. |

### See Also

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* interface [ISaveOptions](../../../aspose.slides.export/isaveoptions)
* interface [IPresentation](../../ipresentation)
* namespace [Aspose.Slides](../../ipresentation)
* assembly [Aspose.Slides](../../../)

---

## Save(Stream, SaveFormat, ISaveOptions) {#save_2}

Salva tutte le diapositive di una presentazione in uno stream nel formato specificato e con opzioni aggiuntive.

```csharp
public void Save(Stream stream, SaveFormat format, ISaveOptions options)
```

| Parameter | Type | Description |
| --- | --- | --- |
| stream | Stream | Stream di output. |
| format | SaveFormat | Formato dei dati esportati. |
| options | ISaveOptions | Opzioni di formato aggiuntive. |

### Exceptions

| exception | condition |
| --- | --- |
| NotSupportedException | Se si tenta di salvare un file crittografato in un formato non Office 2007-2010 |

### See Also

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* interface [ISaveOptions](../../../aspose.slides.export/isaveoptions)
* interface [IPresentation](../../ipresentation)
* namespace [Aspose.Slides](../../ipresentation)
* assembly [Aspose.Slides](../../../)

---

## Save(string, int[], SaveFormat) {#save_7}

Salva le diapositive specificate di una presentazione in un file con il formato specificato.

```csharp
public void Save(string fname, int[] slides, SaveFormat format)
```

| Parameter | Type | Description |
| --- | --- | --- |
| fname | String | Percorso del file creato. |
| slides | Int32[] | Array con le posizioni delle diapositive, a partire da 1. |
| format | SaveFormat | Formato dei dati esportati. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | Quando il parametro stream o slides è null. |
| ArgumentOutOfRangeException | Quando il parametro slides contiene numeri di pagina errati. |
| InvalidOperationException | Quando viene utilizzato un SaveFormat non supportato, ad es. PPTX, PPTM, PPSX, PPSM, POTX, POTM, PPT, ODP. |

### See Also

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* interface [IPresentation](../../ipresentation)
* namespace [Aspose.Slides](../../ipresentation)
* assembly [Aspose.Slides](../../../)

---

## Save(string, int[], SaveFormat, ISaveOptions) {#save_8}

Salva le diapositive specificate di una presentazione in un file con il formato specificato.

```csharp
public void Save(string fname, int[] slides, SaveFormat format, ISaveOptions options)
```

| Parameter | Type | Description |
| --- | --- | --- |
| fname | String | Percorso del file creato. |
| slides | Int32[] | Array con le posizioni delle diapositive, a partire da 1. |
| format | SaveFormat | Formato dei dati esportati. |
| options | ISaveOptions | Opzioni di formato aggiuntive. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | Quando il parametro stream o slides è null. |
| ArgumentOutOfRangeException | Quando il parametro slides contiene numeri di pagina errati. |
| InvalidOperationException | Quando viene utilizzato un SaveFormat non supportato, ad es. PPTX, PPTM, PPSX, PPSM, POTX, POTM, PPT, ODP. |

### See Also

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* interface [ISaveOptions](../../../aspose.slides.export/isaveoptions)
* interface [IPresentation](../../ipresentation)
* namespace [Aspose.Slides](../../ipresentation)
* assembly [Aspose.Slides](../../../)

---

## Save(Stream, int[], SaveFormat) {#save_3}

Salva le diapositive specificate di una presentazione in uno stream nel formato specificato.

```csharp
public void Save(Stream stream, int[] slides, SaveFormat format)
```

| Parameter | Type | Description |
| --- | --- | --- |
| stream | Stream | Stream di output. |
| slides | Int32[] | Array con le posizioni delle diapositive, a partire da 1. |
| format | SaveFormat | Formato dei dati esportati. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | Quando il parametro stream o slides è null. |
| ArgumentOutOfRangeException | Quando il parametro slides contiene numeri di pagina errati. |
| InvalidOperationException | Quando viene utilizzato un SaveFormat non supportato, ad es. PPTX, PPTM, PPSX, PPSM, POTX, POTM, PPT, ODP. |

### See Also

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* interface [IPresentation](../../ipresentation)
* namespace [Aspose.Slides](../../ipresentation)
* assembly [Aspose.Slides](../../../)

---

## Save(Stream, int[], SaveFormat, ISaveOptions) {#save_4}

Salva le diapositive specificate di una presentazione in uno stream nel formato specificato.

```csharp
public void Save(Stream stream, int[] slides, SaveFormat format, ISaveOptions options)
```

| Parameter | Type | Description |
| --- | --- | --- |
| stream | Stream | Stream di output. |
| slides | Int32[] | Array con le posizioni delle diapositive, a partire da 1. |
| format | SaveFormat | Formato dei dati esportati. |
| options | ISaveOptions | Opzioni di formato aggiuntive. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | Quando il parametro stream o slides è null. |
| ArgumentOutOfRangeException | Quando il parametro slides contiene numeri di pagina errati. |
| InvalidOperationException | Quando viene utilizzato un SaveFormat non supportato, ad es. PPTX, PPTM, PPSX, PPSM, POTX, POTM, PPT, ODP. |

### See Also

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* interface [ISaveOptions](../../../aspose.slides.export/isaveoptions)
* interface [IPresentation](../../ipresentation)
* namespace [Aspose.Slides](../../ipresentation)
* assembly [Aspose.Slides](../../../)

---

## Save(IXamlOptions) {#save}

Salva tutte le diapositive di una presentazione in un insieme di file che rappresentano il markup XAML.

```csharp
public void Save(IXamlOptions options)
```

| Parameter | Type | Description |
| --- | --- | --- |
| options | IXamlOptions | Le opzioni del formato XAML. |

### Examples

```csharp
[C#]
using (Presentation pres = new Presentation("pres.pptx"))
{
	pres.Save(new XamlOptions { ExportHiddenSlides = true });
}
```

### See Also

* interface [IXamlOptions](../../../aspose.slides.export.xaml/ixamloptions)
* interface [IPresentation](../../ipresentation)
* namespace [Aspose.Slides](../../ipresentation)
* assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->