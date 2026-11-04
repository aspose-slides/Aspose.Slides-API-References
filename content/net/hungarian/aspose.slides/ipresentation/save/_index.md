---
title: Save
second_title: Aspose.Sildes .NET API Referenciája
description: Ment minden diát a prezentációból a megadott formátumú fájlba.
type: docs
weight: 390
url: /hu/aspose.slides/ipresentation/save/
---
## Save(string, SaveFormat) {#save_5}

Ment minden diát a prezentációból a megadott formátumú fájlba.

```csharp
public void Save(string fname, SaveFormat format)
```

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| fname | String | Az elkészített fájl elérési útja. |
| format | SaveFormat | Az exportált adat formátuma. |

### Lásd még

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* interfész [IPresentation](../../ipresentation)
* névtér [Aspose.Slides](../../ipresentation)
* összeállítás [Aspose.Slides](../../../)

---

## Save(Stream, SaveFormat) {#save_1}

Ment minden diát a prezentációból a megadott formátumú adatfolyamba.

```csharp
public void Save(Stream stream, SaveFormat format)
```

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| stream | Stream | Kimeneti adatfolyam. |
| format | SaveFormat | Az exportált adat formátuma. |

### Lásd még

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* interfész [IPresentation](../../ipresentation)
* névtér [Aspose.Slides](../../ipresentation)
* összeállítás [Aspose.Slides](../../../)

---

## Save(string, SaveFormat, ISaveOptions) {#save_6}

Ment minden diát a prezentációból a megadott formátumú fájlba, további beállításokkal.

```csharp
public void Save(string fname, SaveFormat format, ISaveOptions options)
```

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| fname | String | Az elkészített fájl elérési útja. |
| format | SaveFormat | Az exportált adat formátuma. |
| options | ISaveOptions | További formátumbeállítások. |

### Lásd még

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* interfész [ISaveOptions](../../../aspose.slides.export/isaveoptions)
* interfész [IPresentation](../../ipresentation)
* névtér [Aspose.Slides](../../ipresentation)
* összeállítás [Aspose.Slides](../../../)

---

## Save(Stream, SaveFormat, ISaveOptions) {#save_2}

Ment minden diát a prezentációból a megadott formátumú adatfolyamba, további beállításokkal.

```csharp
public void Save(Stream stream, SaveFormat format, ISaveOptions options)
```

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| stream | Stream | Kimeneti adatfolyam. |
| format | SaveFormat | Az exportált adat formátuma. |
| options | ISaveOptions | További formátumbeállítások. |

### Kivétel

| kivétel | feltétel |
| --- | --- |
| NotSupportedException | Ha titkosított fájlt próbál menteni olyan formátumban, amely nem Office 2007-2010 |

### Lásd még

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* interfész [ISaveOptions](../../../aspose.slides.export/isaveoptions)
* interfész [IPresentation](../../ipresentation)
* névtér [Aspose.Slides](../../ipresentation)
* összeállítás [Aspose.Slides](../../../)

---

## Save(string, int[], SaveFormat) {#save_7}

Ment megadott diákat a prezentációból a megadott formátumú fájlba.

```csharp
public void Save(string fname, int[] slides, SaveFormat format)
```

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| fname | String | Az elkészített fájl elérési útja. |
| slides | Int32[] | A diák pozícióit tartalmazó tömb, 1-től kezdve. |
| format | SaveFormat | Az exportált adat formátuma. |

### Kivétel

| kivétel | feltétel |
| --- | --- |
| ArgumentNullException | Ha a stream vagy a slides paraméter null. |
| ArgumentOutOfRangeException | Ha a slides paraméter hibás oldalszámokat tartalmaz. |
| InvalidOperationException | Ha nem támogatott SaveFormat kerül felhasználásra, például PPTX, PPTM, PPSX, PPSM, POTX, POTM, PPT, ODP. |

### Lásd még

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* interfész [IPresentation](../../ipresentation)
* névtér [Aspose.Slides](../../ipresentation)
* összeállítás [Aspose.Slides](../../../)

---

## Save(string, int[], SaveFormat, ISaveOptions) {#save_8}

Ment megadott diákat a prezentációból a megadott formátumú fájlba.

```csharp
public void Save(string fname, int[] slides, SaveFormat format, ISaveOptions options)
```

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| fname | String | Az elkészített fájl elérési útja. |
| slides | Int32[] | A diák pozícióit tartalmazó tömb, 1-től kezdve. |
| format | SaveFormat | Az exportált adat formátuma. |
| options | ISaveOptions | További formátumbeállítások. |

### Kivétel

| kivétel | feltétel |
| --- | --- |
| ArgumentNullException | Ha a stream vagy a slides paraméter null. |
| ArgumentOutOfRangeException | Ha a slides paraméter hibás oldalszámokat tartalmaz. |
| InvalidOperationException | Ha nem támogatott SaveFormat kerül felhasználásra, például PPTX, PPTM, PPSX, PPSM, POTX, POTM, PPT, ODP. |

### Lásd még

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* interfész [ISaveOptions](../../../aspose.slides.export/isaveoptions)
* interfész [IPresentation](../../ipresentation)
* névtér [Aspose.Slides](../../ipresentation)
* összeállítás [Aspose.Slides](../../../)

---

## Save(Stream, int[], SaveFormat) {#save_3}

Ment megadott diákat a prezentációból a megadott formátumú adatfolyamba.

```csharp
public void Save(Stream stream, int[] slides, SaveFormat format)
```

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| stream | Stream | Kimeneti adatfolyam. |
| slides | Int32[] | A diák pozícióit tartalmazó tömb, 1-től kezdve. |
| format | SaveFormat | Az exportált adat formátuma. |

### Kivétel

| kivétel | feltétel |
| --- | --- |
| ArgumentNullException | Ha a stream vagy a slides paraméter null. |
| ArgumentOutOfRangeException | Ha a slides paraméter hibás oldalszámokat tartalmaz. |
| InvalidOperationException | Ha nem támogatott SaveFormat kerül felhasználásra, például PPTX, PPTM, PPSX, PPSM, POTX, POTM, PPT, ODP. |

### Lásd még

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* interfész [IPresentation](../../ipresentation)
* névtér [Aspose.Slides](../../ipresentation)
* összeállítás [Aspose.Slides](../../../)

---

## Save(Stream, int[], SaveFormat, ISaveOptions) {#save_4}

Ment megadott diákat a prezentációból a megadott formátumú adatfolyamba.

```csharp
public void Save(Stream stream, int[] slides, SaveFormat format, ISaveOptions options)
```

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| stream | Stream | Kimeneti adatfolyam. |
| slides | Int32[] | A diák pozícióit tartalmazó tömb, 1-től kezdve. |
| format | SaveFormat | Az exportált adat formátuma. |
| options | ISaveOptions | További formátumbeállítások. |

### Kivétel

| kivétel | feltétel |
| --- | --- |
| ArgumentNullException | Ha a stream vagy a slides paraméter null. |
| ArgumentOutOfRangeException | Ha a slides paraméter hibás oldalszámokat tartalmaz. |
| InvalidOperationException | Ha nem támogatott SaveFormat kerül felhasználásra, például PPTX, PPTM, PPSX, PPSM, POTX, POTM, PPT, ODP. |

### Lásd még

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* interfész [ISaveOptions](../../../aspose.slides.export/isaveoptions)
* interfész [IPresentation](../../ipresentation)
* névtér [Aspose.Slides](../../ipresentation)
* összeállítás [Aspose.Slides](../../../)

---

## Save(IXamlOptions) {#save}

Ment minden diát a prezentációból egy sor fájlba, amely XAML jelölést tartalmaz.

```csharp
public void Save(IXamlOptions options)
```

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| options | IXamlOptions | A XAML formátumbeállítások. |

### Példák

```csharp
[C#]
using (Presentation pres = new Presentation("pres.pptx"))
{
	pres.Save(new XamlOptions { ExportHiddenSlides = true });
}
```

### Lásd még

* interfész [IXamlOptions](../../../aspose.slides.export.xaml/ixamloptions)
* interfész [IPresentation](../../ipresentation)
* névtér [Aspose.Slides](../../ipresentation)
* összeállítás [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->