---
title: Save
second_title: Aspose.Sildes .NET API hivatkozás
description: Ment minden diát a prezentációból egy fájlba a megadott formátummal.
type: docs
weight: 380
url: /hu/aspose.slides/ipresentation/save/
---
## Save(string, SaveFormat) {#save_5}

Ment minden diát a prezentációból egy fájlba a megadott formátummal.

```csharp
public void Save(string fname, SaveFormat format)
```

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| fname | String | Az elkészített fájl elérési útja. |
| format | SaveFormat | Az exportált adatok formátuma. |

### Lásd még

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* interface [IPresentation](../../ipresentation)
* namespace [Aspose.Slides](../../ipresentation)
* assembly [Aspose.Slides](../../../)

---

## Save(Stream, SaveFormat) {#save_1}

Ment minden diát a prezentációból egy folyamra a megadott formátummal.

```csharp
public void Save(Stream stream, SaveFormat format)
```

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| stream | Stream | Kimeneti folyam. |
| format | SaveFormat | Az exportált adatok formátuma. |

### Lásd még

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* interface [IPresentation](../../ipresentation)
* namespace [Aspose.Slides](../../ipresentation)
* assembly [Aspose.Slides](../../../)

---

## Save(string, SaveFormat, ISaveOptions) {#save_6}

Ment minden diát a prezentációból egy fájlba a megadott formátummal, valamint további opciókkal.

```csharp
public void Save(string fname, SaveFormat format, ISaveOptions options)
```

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| fname | String | Az elkészített fájl elérési útja. |
| format | SaveFormat | Az exportált adatok formátuma. |
| options | ISaveOptions | További formátum opciók. |

### Lásd még

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* interface [ISaveOptions](../../../aspose.slides.export/isaveoptions)
* interface [IPresentation](../../ipresentation)
* namespace [Aspose.Slides](../../ipresentation)
* assembly [Aspose.Slides](../../../)

---

## Save(Stream, SaveFormat, ISaveOptions) {#save_2}

Ment minden diát a prezentációból egy folyamra a megadott formátummal, valamint további opciókkal.

```csharp
public void Save(Stream stream, SaveFormat format, ISaveOptions options)
```

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| stream | Stream | Kimeneti folyam. |
| format | SaveFormat | Az exportált adatok formátuma. |
| options | ISaveOptions | További formátum opciók. |

### Kivétel

| Kivétel | Feltétel |
| --- | --- |
| NotSupportedException | Ha titkosított fájlt próbál menteni olyan formátumban, amely nem Office 2007-2010 formátum |

### Lásd még

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* interface [ISaveOptions](../../../aspose.slides.export/isaveoptions)
* interface [IPresentation](../../ipresentation)
* namespace [Aspose.Slides](../../ipresentation)
* assembly [Aspose.Slides](../../../)

---

## Save(string, int[], SaveFormat) {#save_7}

Ment kijelölt diákat a prezentációból egy fájlba a megadott formátummal.

```csharp
public void Save(string fname, int[] slides, SaveFormat format)
```

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| fname | String | Az elkészített fájl elérési útja. |
| slides | Int32[] | Tömb a dia pozíciókkal, 1-től kezdve. |
| format | SaveFormat | Az exportált adatok formátuma. |

### Kivétel

| Kivétel | Feltétel |
| --- | --- |
| ArgumentNullException | Ha a stream vagy slides paraméter null. |
| ArgumentOutOfRangeException | Ha a slides paraméter hibás oldalszámokat tartalmaz. |
| InvalidOperationException | Ha nem támogatott SaveFormat használatos, például PPTX, PPTM, PPSX, PPSM, POTX, POTM, PPT, ODP. |

### Lásd még

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* interface [IPresentation](../../ipresentation)
* namespace [Aspose.Slides](../../ipresentation)
* assembly [Aspose.Slides](../../../)

---

## Save(string, int[], SaveFormat, ISaveOptions) {#save_8}

Ment kijelölt diákat a prezentációból egy fájlba a megadott formátummal, valamint további opciókkal.

```csharp
public void Save(string fname, int[] slides, SaveFormat format, ISaveOptions options)
```

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| fname | String | Az elkészített fájl elérési útja. |
| slides | Int32[] | Tömb a dia pozíciókkal, 1-től kezdve. |
| format | SaveFormat | Az exportált adatok formátuma. |
| options | ISaveOptions | További formátum opciók. |

### Kivétel

| Kivétel | Feltétel |
| --- | --- |
| ArgumentNullException | Ha a stream vagy slides paraméter null. |
| ArgumentOutOfRangeException | Ha a slides paraméter hibás oldalszámokat tartalmaz. |
| InvalidOperationException | Ha nem támogatott SaveFormat használatos, például PPTX, PPTM, PPSX, PPSM, POTX, POTM, PPT, ODP. |

### Lásd még

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* interface [ISaveOptions](../../../aspose.slides.export/isaveoptions)
* interface [IPresentation](../../ipresentation)
* namespace [Aspose.Slides](../../ipresentation)
* assembly [Aspose.Slides](../../../)

---

## Save(Stream, int[], SaveFormat) {#save_3}

Ment kijelölt diákat a prezentációból egy folyamra a megadott formátummal.

```csharp
public void Save(Stream stream, int[] slides, SaveFormat format)
```

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| stream | Stream | Kimeneti folyam. |
| slides | Int32[] | Tömb a dia pozíciókkal, 1-től kezdve. |
| format | SaveFormat | Az exportált adatok formátuma. |

### Kivétel

| Kivétel | Feltétel |
| --- | --- |
| ArgumentNullException | Ha a stream vagy slides paraméter null. |
| ArgumentOutOfRangeException | Ha a slides paraméter hibás oldalszámokat tartalmaz. |
| InvalidOperationException | Ha nem támogatott SaveFormat használatos, például PPTX, PPTM, PPSX, PPSM, POTX, POTM, PPT, ODP. |

### Lásd még

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* interface [IPresentation](../../ipresentation)
* namespace [Aspose.Slides](../../ipresentation)
* assembly [Aspose.Slides](../../../)

---

## Save(Stream, int[], SaveFormat, ISaveOptions) {#save_4}

Ment kijelölt diákat a prezentációból egy folyamra a megadott formátummal, valamint további opciókkal.

```csharp
public void Save(Stream stream, int[] slides, SaveFormat format, ISaveOptions options)
```

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| stream | Stream | Kimeneti folyam. |
| slides | Int32[] | Tömb a dia pozíciókkal, 1-től kezdve. |
| format | SaveFormat | Az exportált adatok formátuma. |
| options | ISaveOptions | További formátum opciók. |

### Kivétel

| Kivétel | Feltétel |
| --- | --- |
| ArgumentNullException | Ha a stream vagy slides paraméter null. |
| ArgumentOutOfRangeException | Ha a slides paraméter hibás oldalszámokat tartalmaz. |
| InvalidOperationException | Ha nem támogatott SaveFormat használatos, például PPTX, PPTM, PPSX, PPSM, POTX, POTM, PPT, ODP. |

### Lásd még

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* interface [ISaveOptions](../../../aspose.slides.export/isaveoptions)
* interface [IPresentation](../../ipresentation)
* namespace [Aspose.Slides](../../ipresentation)
* assembly [Aspose.Slides](../../../)

---

## Save(IXamlOptions) {#save}

Ment minden diát a prezentációból egy XAML jelölőnyelvet reprezentáló fájlkészletbe.

```csharp
public void Save(IXamlOptions options)
```

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| options | IXamlOptions | Az XAML formátum opciói. |

### Példák

```csharp
[C#]
using (Presentation pres = new Presentation("pres.pptx"))
{
	pres.Save(new XamlOptions { ExportHiddenSlides = true });
}
```

### Lásd még

* interface [IXamlOptions](../../../aspose.slides.export.xaml/ixamloptions)
* interface [IPresentation](../../ipresentation)
* namespace [Aspose.Slides](../../ipresentation)
* assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->