---
title: Save
second_title: Aspose.Sildes for .NET API Reference
description: 
type: docs
weight: 20
url: /net/aspose.slides/presentation/save/
---
## Presentation.Save method (1 of 9)

Saves all slides of a presentation to a set of files representing XAML markup.

```csharp
public void Save(IXamlOptions options)
```

| parameter | description |
| --- | --- |
| options | The XAML format options. |

## Examples

```csharp
[C#]
using (Presentation pres = new Presentation("pres.pptx"))
{
	pres.Save(new XamlOptions { ExportHiddenSlides = true });
}
```

### See Also

* interface [IXamlOptions](../../../aspose.slides.export.xaml/ixamloptions)
* class [Presentation](../../presentation)
* namespace [Aspose.Slides](../../presentation)
* assembly [Aspose.Slides](../../../)

---

## Presentation.Save method (2 of 9)

Saves all slides of a presentation to a stream in the specified format.

```csharp
public void Save(Stream stream, SaveFormat format)
```

| parameter | description |
| --- | --- |
| stream | Output stream. |
| format | Format of the exported data. |

### See Also

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* class [Presentation](../../presentation)
* namespace [Aspose.Slides](../../presentation)
* assembly [Aspose.Slides](../../../)

---

## Presentation.Save method (3 of 9)

Saves all slides of a presentation to a file with the specified format.

```csharp
public void Save(string fname, SaveFormat format)
```

| parameter | description |
| --- | --- |
| fname | Path to the created file. |
| format | Format of the exported data. |

### See Also

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* class [Presentation](../../presentation)
* namespace [Aspose.Slides](../../presentation)
* assembly [Aspose.Slides](../../../)

---

## Presentation.Save method (4 of 9)

Saves specified slides of a presentation to a stream in the specified format with page number keeping.

```csharp
public void Save(Stream stream, int[] slides, SaveFormat format)
```

| parameter | description |
| --- | --- |
| stream | Output stream. |
| slides | Array with slide positions, starting from 1. |
| format | Format of the exported data. |

### See Also

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* class [Presentation](../../presentation)
* namespace [Aspose.Slides](../../presentation)
* assembly [Aspose.Slides](../../../)

---

## Presentation.Save method (5 of 9)

Saves all slides of a presentation to a stream in the specified format and with additional options.

```csharp
public void Save(Stream stream, SaveFormat format, ISaveOptions options)
```

| parameter | description |
| --- | --- |
| stream | Output stream. |
| format | Format of the exported data. |
| options | Additional format options. |

## Exceptions

| exception | condition |
| --- | --- |
| NotSupportedException | If you try to save encrypted file in none Office 2007-2010 format |

### See Also

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* interface [ISaveOptions](../../../aspose.slides.export/isaveoptions)
* class [Presentation](../../presentation)
* namespace [Aspose.Slides](../../presentation)
* assembly [Aspose.Slides](../../../)

---

## Presentation.Save method (6 of 9)

Saves specified slides of a presentation to a file with the specified format with page number keeping.

```csharp
public void Save(string fname, int[] slides, SaveFormat format)
```

| parameter | description |
| --- | --- |
| fname | Path to the created file. |
| slides | Array with slide positions, starting from 1. |
| format | Format of the exported data. |

## Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | When stream or slides parameter is null. |
| ArgumentOutOfRangeException | When slides parameter contains wrong page numbers. |
| InvalidOperationException | When an unsupported SaveFormat is used, e.g. PPTX, PPTM, PPSX, PPSM, POTX, POTM, PPT, ODP. |

### See Also

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* class [Presentation](../../presentation)
* namespace [Aspose.Slides](../../presentation)
* assembly [Aspose.Slides](../../../)

---

## Presentation.Save method (7 of 9)

Saves all slides of a presentation to a file with the specified format and with additional options.

```csharp
public void Save(string fname, SaveFormat format, ISaveOptions options)
```

| parameter | description |
| --- | --- |
| fname | Path to the created file. |
| format | Format of the exported data. |
| options | Additional format options. |

### See Also

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* interface [ISaveOptions](../../../aspose.slides.export/isaveoptions)
* class [Presentation](../../presentation)
* namespace [Aspose.Slides](../../presentation)
* assembly [Aspose.Slides](../../../)

---

## Presentation.Save method (8 of 9)

Saves specified slides of a presentation to a stream in the specified format with page number keeping.

```csharp
public void Save(Stream stream, int[] slides, SaveFormat format, ISaveOptions options)
```

| parameter | description |
| --- | --- |
| stream | Output stream. |
| slides | Array with slide positions, starting from 1. |
| format | Format of the exported data. |
| options | Additional format options. |

## Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | When stream or slides parameter is null. |
| ArgumentOutOfRangeException | When slides parameter contains wrong page numbers. |
| InvalidOperationException | When an unsupported SaveFormat is used, e.g. PPTX, PPTM, PPSX, PPSM, POTX, POTM, PPT, ODP. |

### See Also

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* interface [ISaveOptions](../../../aspose.slides.export/isaveoptions)
* class [Presentation](../../presentation)
* namespace [Aspose.Slides](../../presentation)
* assembly [Aspose.Slides](../../../)

---

## Presentation.Save method (9 of 9)

Saves specified slides of a presentation to a file with the specified format with page number keeping.

```csharp
public void Save(string fname, int[] slides, SaveFormat format, ISaveOptions options)
```

| parameter | description |
| --- | --- |
| fname | Path to the created file. |
| slides | Array with slide positions, starting from 1. |
| format | Format of the exported data. |
| options | Additional format options. |

### See Also

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* interface [ISaveOptions](../../../aspose.slides.export/isaveoptions)
* class [Presentation](../../presentation)
* namespace [Aspose.Slides](../../presentation)
* assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
