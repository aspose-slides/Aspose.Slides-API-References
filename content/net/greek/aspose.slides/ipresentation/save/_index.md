---
title: Save
second_title: Αναφορά API Aspose.Sildes για .NET
description: Αποθηκεύει όλες τις διαφάνειες μιας παρουσίασης σε ένα αρχείο με το καθορισμένο μορφότυπο.
type: docs
weight: 390
url: /el/aspose.slides/ipresentation/save/
---
## Save(string, SaveFormat) {#save_5}

Αποθηκεύει όλες τις διαφάνειες μιας παρουσίασης σε ένα αρχείο με το καθορισμένο μορφότυπο.

```csharp
public void Save(string fname, SaveFormat format)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| fname | String | Path to the created file. |
| format | SaveFormat | Format of the exported data. |

### See Also

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* interface [IPresentation](../../ipresentation)
* namespace [Aspose.Slides](../../ipresentation)
* assembly [Aspose.Slides](../../../)

---

## Save(Stream, SaveFormat) {#save_1}

Αποθηκεύει όλες τις διαφάνειες μιας παρουσίασης σε μια ροή με το καθορισμένο μορφότυπο.

```csharp
public void Save(Stream stream, SaveFormat format)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| stream | Stream | Output stream. |
| format | SaveFormat | Format of the exported data. |

### See Also

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* interface [IPresentation](../../ipresentation)
* namespace [Aspose.Slides](../../ipresentation)
* assembly [Aspose.Slides](../../../)

---

## Save(string, SaveFormat, ISaveOptions) {#save_6}

Αποθηκεύει όλες τις διαφάνειες μιας παρουσίασης σε ένα αρχείο με το καθορισμένο μορφότυπο και με πρόσθετες επιλογές.

```csharp
public void Save(string fname, SaveFormat format, ISaveOptions options)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| fname | String | Path to the created file. |
| format | SaveFormat | Format of the exported data. |
| options | ISaveOptions | Additional format options. |

### See Also

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* interface [ISaveOptions](../../../aspose.slides.export/isaveoptions)
* interface [IPresentation](../../ipresentation)
* namespace [Aspose.Slides](../../ipresentation)
* assembly [Aspose.Slides](../../../)

---

## Save(Stream, SaveFormat, ISaveOptions) {#save_2}

Αποθηκεύει όλες τις διαφάνειες μιας παρουσίασης σε μια ροή με το καθορισμένο μορφότυπο και με πρόσθετες επιλογές.

```csharp
public void Save(Stream stream, SaveFormat format, ISaveOptions options)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| stream | Stream | Output stream. |
| format | SaveFormat | Format of the exported data. |
| options | ISaveOptions | Additional format options. |

### Exceptions

| Εξαίρεση | Συνθήκη |
| --- | --- |
| NotSupportedException | If you try to save encrypted file in none Office 2007-2010 format |

### See Also

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* interface [ISaveOptions](../../../aspose.slides.export/isaveoptions)
* interface [IPresentation](../../ipresentation)
* namespace [Aspose.Slides](../../ipresentation)
* assembly [Aspose.Slides](../../../)

---

## Save(string, int[], SaveFormat) {#save_7}

Αποθηκεύει τις καθορισμένες διαφάνειες μιας παρουσίασης σε ένα αρχείο με το καθορισμένο μορφότυπο.

```csharp
public void Save(string fname, int[] slides, SaveFormat format)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| fname | String | Path to the created file. |
| slides | Int32[] | Array with slide positions, starting from 1. |
| format | SaveFormat | Format of the exported data. |

### Exceptions

| Εξαίρεση | Συνθήκη |
| --- | --- |
| ArgumentNullException | When stream or slides parameter is null. |
| ArgumentOutOfRangeException | When slides parameter contains wrong page numbers. |
| InvalidOperationException | When an unsupported SaveFormat is used, e.g. PPTX, PPTM, PPSX, PPSM, POTX, POTM, PPT, ODP. |

### See Also

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* interface [IPresentation](../../ipresentation)
* namespace [Aspose.Slides](../../ipresentation)
* assembly [Aspose.Slides](../../../)

---

## Save(string, int[], SaveFormat, ISaveOptions) {#save_8}

Αποθηκεύει τις καθορισμένες διαφάνειες μιας παρουσίασης σε ένα αρχείο με το καθορισμένο μορφότυπο.

```csharp
public void Save(string fname, int[] slides, SaveFormat format, ISaveOptions options)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| fname | String | Path to the created file. |
| slides | Int32[] | Array with slide positions, starting from 1. |
| format | SaveFormat | Format of the exported data. |
| options | ISaveOptions | Additional format options. |

### Exceptions

| Εξαίρεση | Συνθήκη |
| --- | --- |
| ArgumentNullException | When stream or slides parameter is null. |
| ArgumentOutOfRangeException | When slides parameter contains wrong page numbers. |
| InvalidOperationException | When an unsupported SaveFormat is used, e.g. PPTX, PPTM, PPSX, PPSM, POTX, POTM, PPT, ODP. |

### See Also

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* interface [ISaveOptions](../../../aspose.slides.export/isaveoptions)
* interface [IPresentation](../../ipresentation)
* namespace [Aspose.Slides](../../ipresentation)
* assembly [Aspose.Slides](../../../)

---

## Save(Stream, int[], SaveFormat) {#save_3}

Αποθηκεύει τις καθορισμένες διαφάνειες μιας παρουσίασης σε μια ροή με το καθορισμένο μορφότυπο.

```csharp
public void Save(Stream stream, int[] slides, SaveFormat format)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| stream | Stream | Output stream. |
| slides | Int32[] | Array with slide positions, starting from 1. |
| format | SaveFormat | Format of the exported data. |

### Exceptions

| Εξαίρεση | Συνθήκη |
| --- | --- |
| ArgumentNullException | When stream or slides parameter is null. |
| ArgumentOutOfRangeException | When slides parameter contains wrong page numbers. |
| InvalidOperationException | When an unsupported SaveFormat is used, e.g. PPTX, PPTM, PPSX, PPSM, POTX, POTM, PPT, ODP. |

### See Also

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* interface [IPresentation](../../ipresentation)
* namespace [Aspose.Slides](../../ipresentation)
* assembly [Aspose.Slides](../../../)

---

## Save(Stream, int[], SaveFormat, ISaveOptions) {#save_4}

Αποθηκεύει τις καθορισμένες διαφάνειες μιας παρουσίασης σε μια ροή με το καθορισμένο μορφότυπο.

```csharp
public void Save(Stream stream, int[] slides, SaveFormat format, ISaveOptions options)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| stream | Stream | Output stream. |
| slides | Int32[] | Array with slide positions, starting from 1. |
| format | SaveFormat | Format of the exported data. |
| options | ISaveOptions | Additional format options. |

### Exceptions

| Εξαίρεση | Συνθήκη |
| --- | --- |
| ArgumentNullException | When stream or slides parameter is null. |
| ArgumentOutOfRangeException | When slides parameter contains wrong page numbers. |
| InvalidOperationException | When an unsupported SaveFormat is used, e.g. PPTX, PPTM, PPSX, PPSM, POTX, POTM, PPT, ODP. |

### See Also

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* interface [ISaveOptions](../../../aspose.slides.export/isaveoptions)
* interface [IPresentation](../../ipresentation)
* namespace [Aspose.Slides](../../ipresentation)
* assembly [Aspose.Slides](../../../)

---

## Save(IXamlOptions) {#save}

Αποθηκεύει όλες τις διαφάνειες μιας παρουσίασης σε ένα σύνολο αρχείων που αντιπροσωπεύουν το σήμανση XAML.

```csharp
public void Save(IXamlOptions options)
```

| Παράμετρος | Τύπος | Περιγραφή |
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

* interface [IXamlOptions](../../../aspose.slides.export.xaml/ixamloptions)
* interface [IPresentation](../../ipresentation)
* namespace [Aspose.Slides](../../ipresentation)
* assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->