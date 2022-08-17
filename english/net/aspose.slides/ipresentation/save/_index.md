---
title: Save
second_title: Aspose.Sildes for .NET API Reference
description: Saves all slides of a presentation to a file with the specified format.
type: docs
weight: 340
url: /net/aspose.slides/ipresentation/save/
---
## Save(string, SaveFormat) {#save_5}

Saves all slides of a presentation to a file with the specified format.

```csharp
public void Save(string fname, SaveFormat format)
```

| Parameter | Type | Description |
| --- | --- | --- |
| fname | String | Path to the created file. |
| format | SaveFormat | Format of the exported data. |

### See Also

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* interface [IPresentation](../../ipresentation)
* namespace [Aspose.Slides](../../ipresentation)
* assembly [Aspose.Slides](../../../)

---

## Save(Stream, SaveFormat) {#save_1}

Saves all slides of a presentation to a stream in the specified format.

```csharp
public void Save(Stream stream, SaveFormat format)
```

| Parameter | Type | Description |
| --- | --- | --- |
| stream | Stream | Output stream. |
| format | SaveFormat | Format of the exported data. |

### See Also

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* interface [IPresentation](../../ipresentation)
* namespace [Aspose.Slides](../../ipresentation)
* assembly [Aspose.Slides](../../../)

---

## Save(string, SaveFormat, ISaveOptions) {#save_6}

Saves all slides of a presentation to a file with the specified format and with additional options.

```csharp
public void Save(string fname, SaveFormat format, ISaveOptions options)
```

| Parameter | Type | Description |
| --- | --- | --- |
| fname | String | Path to the created file. |
| format | SaveFormat | Format of the exported data. |
| options | ISaveOptions | Additional format options. |

### See Also

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* interface [ISaveOptions](../../../aspose.slides.export/isaveoptions)
* interface [IPresentation](../../ipresentation)
* namespace [Aspose.Slides](../../ipresentation)
* assembly [Aspose.Slides](../../../)

---

## Save(Stream, SaveFormat, ISaveOptions) {#save_2}

Saves all slides of a presentation to a stream in the specified format and with additional options.

```csharp
public void Save(Stream stream, SaveFormat format, ISaveOptions options)
```

| Parameter | Type | Description |
| --- | --- | --- |
| stream | Stream | Output stream. |
| format | SaveFormat | Format of the exported data. |
| options | ISaveOptions | Additional format options. |

### Exceptions

| exception | condition |
| --- | --- |
| NotSupportedException | If you try to save encrypted file in none Office 2007-2010 format |

### See Also

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* interface [ISaveOptions](../../../aspose.slides.export/isaveoptions)
* interface [IPresentation](../../ipresentation)
* namespace [Aspose.Slides](../../ipresentation)
* assembly [Aspose.Slides](../../../)

---

## Save(string, int[], SaveFormat) {#save_9}

Saves specified slides of a presentation to a file with the specified format.

```csharp
public void Save(string fname, int[] slides, SaveFormat format)
```

| Parameter | Type | Description |
| --- | --- | --- |
| fname | String | Path to the created file. |
| slides | Int32[] | Array with slide positions, starting from 1. |
| format | SaveFormat | Format of the exported data. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | When stream or slides parameter is null. |
| ArgumentOutOfRangeException | When slides parameter contains wrong page numbers. |
| InvalidOperationException | When an unsupported SaveFormat is used, e.g. PPTX, PPTM, PPSX, PPSM, POTX, POTM, PPT, ODP. |

### See Also

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* interface [IPresentation](../../ipresentation)
* namespace [Aspose.Slides](../../ipresentation)
* assembly [Aspose.Slides](../../../)

---

## Save(string, int[], SaveFormat, ISaveOptions) {#save_10}

Saves specified slides of a presentation to a file with the specified format.

```csharp
public void Save(string fname, int[] slides, SaveFormat format, ISaveOptions options)
```

| Parameter | Type | Description |
| --- | --- | --- |
| fname | String | Path to the created file. |
| slides | Int32[] | Array with slide positions, starting from 1. |
| format | SaveFormat | Format of the exported data. |
| options | ISaveOptions | Additional format options. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | When stream or slides parameter is null. |
| ArgumentOutOfRangeException | When slides parameter contains wrong page numbers. |
| InvalidOperationException | When an unsupported SaveFormat is used, e.g. PPTX, PPTM, PPSX, PPSM, POTX, POTM, PPT, ODP. |

### See Also

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* interface [ISaveOptions](../../../aspose.slides.export/isaveoptions)
* interface [IPresentation](../../ipresentation)
* namespace [Aspose.Slides](../../ipresentation)
* assembly [Aspose.Slides](../../../)

---

## Save(Stream, int[], SaveFormat) {#save_3}

Saves specified slides of a presentation to a stream in the specified format.

```csharp
public void Save(Stream stream, int[] slides, SaveFormat format)
```

| Parameter | Type | Description |
| --- | --- | --- |
| stream | Stream | Output stream. |
| slides | Int32[] | Array with slide positions, starting from 1. |
| format | SaveFormat | Format of the exported data. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | When stream or slides parameter is null. |
| ArgumentOutOfRangeException | When slides parameter contains wrong page numbers. |
| InvalidOperationException | When an unsupported SaveFormat is used, e.g. PPTX, PPTM, PPSX, PPSM, POTX, POTM, PPT, ODP. |

### See Also

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* interface [IPresentation](../../ipresentation)
* namespace [Aspose.Slides](../../ipresentation)
* assembly [Aspose.Slides](../../../)

---

## Save(Stream, int[], SaveFormat, ISaveOptions) {#save_4}

Saves specified slides of a presentation to a stream in the specified format.

```csharp
public void Save(Stream stream, int[] slides, SaveFormat format, ISaveOptions options)
```

| Parameter | Type | Description |
| --- | --- | --- |
| stream | Stream | Output stream. |
| slides | Int32[] | Array with slide positions, starting from 1. |
| format | SaveFormat | Format of the exported data. |
| options | ISaveOptions | Additional format options. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | When stream or slides parameter is null. |
| ArgumentOutOfRangeException | When slides parameter contains wrong page numbers. |
| InvalidOperationException | When an unsupported SaveFormat is used, e.g. PPTX, PPTM, PPSX, PPSM, POTX, POTM, PPT, ODP. |

### See Also

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* interface [ISaveOptions](../../../aspose.slides.export/isaveoptions)
* interface [IPresentation](../../ipresentation)
* namespace [Aspose.Slides](../../ipresentation)
* assembly [Aspose.Slides](../../../)

---

## Save(IXamlOptions) {#save}

Saves all slides of a presentation to a set of files representing XAML markup.

```csharp
public void Save(IXamlOptions options)
```

| Parameter | Type | Description |
| --- | --- | --- |
| options | IXamlOptions | The XAML format options. |

### Examples

```csharp
[C#]
using (Presentation pres = new Presentation("pres.pptx"))
{
	pres.Save(new XamlOptions { ExportHiddenSlides = true });
}
```

### See Also

* interface [IXamlOptions](../../../aspose.slides.export.xaml/ixamloptions)
* interface [IPresentation](../../ipresentation)
* namespace [Aspose.Slides](../../ipresentation)
* assembly [Aspose.Slides](../../../)

---

## Save(string, SaveFormat, HttpResponse, bool) {#save_8}

Sends the presentation to the client browser. This method is absent in ClientProfile versions of Aspose.Slide.

```csharp
public void Save(string fname, SaveFormat format, HttpResponse response, bool showInline)
```

| Parameter | Type | Description |
| --- | --- | --- |
| fname | String | The name for the presentation that will appear at the client browser. The name should not contain path. |
| format | SaveFormat | Format of the exported data. |
| response | HttpResponse | Response object where to save the document. |
| showInline | Boolean | True to show an option to open the presentation inside the browser. |

### See Also

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* interface [IPresentation](../../ipresentation)
* namespace [Aspose.Slides](../../ipresentation)
* assembly [Aspose.Slides](../../../)

---

## Save(string, SaveFormat, ISaveOptions, HttpResponse, bool) {#save_7}

Sends the presentation to the client browser. This method is absent in ClientProfile versions of Aspose.Slide.

```csharp
public void Save(string fname, SaveFormat format, ISaveOptions options, HttpResponse response, 
    bool showInline)
```

| Parameter | Type | Description |
| --- | --- | --- |
| fname | String | The name for the presentation that will appear at the client browser. The name should not contain path. |
| format | SaveFormat | Format of the exported data. |
| options | ISaveOptions | Additional format options. |
| response | HttpResponse | Response object where to save the document. |
| showInline | Boolean | True to show an option to open the presentation inside the browser. |

### See Also

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* interface [ISaveOptions](../../../aspose.slides.export/isaveoptions)
* interface [IPresentation](../../ipresentation)
* namespace [Aspose.Slides](../../ipresentation)
* assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
