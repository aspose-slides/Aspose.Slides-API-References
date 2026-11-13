---
title: Save
second_title: Aspose.Sildes لنظام .NET - مرجع API
description: يحفظ جميع شرائح العرض التقديمي إلى ملف بالتنسيق المحدد.
type: docs
weight: 400
url: /ar/aspose.slides/presentation/save/
---
## Save(string, SaveFormat) {#save_5}

يحفظ جميع الشرائح في عرض تقديمي إلى ملف بالتنسيق المحدد.

```csharp
public void Save(string fname, SaveFormat format)
```

| Parameter | Type | Description |
| --- | --- | --- |
| fname | String | المسار إلى الملف الذي تم إنشاؤه. |
| format | SaveFormat | تنسيق البيانات المصدرة. |

### See Also

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* class [Presentation](../../presentation)
* namespace [Aspose.Slides](../../presentation)
* assembly [Aspose.Slides](../../../)

---

## Save(Stream, SaveFormat) {#save_1}

يحفظ جميع الشرائح في عرض تقديمي إلى تدفق بالتنسيق المحدد.

```csharp
public void Save(Stream stream, SaveFormat format)
```

| Parameter | Type | Description |
| --- | --- | --- |
| stream | Stream | تدفق الإخراج. |
| format | SaveFormat | تنسيق البيانات المصدرة. |

### See Also

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* class [Presentation](../../presentation)
* namespace [Aspose.Slides](../../presentation)
* assembly [Aspose.Slides](../../../)

---

## Save(string, SaveFormat, ISaveOptions) {#save_6}

```csharp
public void Save(string fname, SaveFormat format, ISaveOptions options)
```

### See Also

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* interface [ISaveOptions](../../../aspose.slides.export/isaveoptions)
* class [Presentation](../../presentation)
* namespace [Aspose.Slides](../../presentation)
* assembly [Aspose.Slides](../../../)

---

## Save(Stream, SaveFormat, ISaveOptions) {#save_2}

يحفظ جميع الشرائح في عرض تقديمي إلى تدفق بالتنسيق المحدد ومع خيارات إضافية.

```csharp
public void Save(Stream stream, SaveFormat format, ISaveOptions options)
```

| Parameter | Type | Description |
| --- | --- | --- |
| stream | Stream | تدفق الإخراج. |
| format | SaveFormat | تنسيق البيانات المصدرة. |
| options | ISaveOptions | خيارات تنسيق إضافية. |

### Exceptions

| exception | condition |
| --- | --- |
| NotSupportedException | If you try to save encrypted file in none Office 2007-2010 format |

### See Also

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* interface [ISaveOptions](../../../aspose.slides.export/isaveoptions)
* class [Presentation](../../presentation)
* namespace [Aspose.Slides](../../presentation)
* assembly [Aspose.Slides](../../../)

---

## Save(IXamlOptions) {#save}

يحفظ جميع الشرائح في عرض تقديمي إلى مجموعة من الملفات التي تمثل ترميز XAML.

```csharp
public void Save(IXamlOptions options)
```

| Parameter | Type | Description |
| --- | --- | --- |
| options | IXamlOptions | خيارات تنسيق XAML. |

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
* class [Presentation](../../presentation)
* namespace [Aspose.Slides](../../presentation)
* assembly [Aspose.Slides](../../../)

---

## Save(string, int[], SaveFormat) {#save_7}

يحفظ الشرائح المحددة في عرض تقديمي إلى ملف بالتنسيق المحدد مع الحفاظ على أرقام الصفحات.

```csharp
public void Save(string fname, int[] slides, SaveFormat format)
```

| Parameter | Type | Description |
| --- | --- | --- |
| fname | String | المسار إلى الملف الذي تم إنشاؤه. |
| slides | Int32[] | مصفوفة تحتوي على مواضع الشرائح، بدءًا من 1. |
| format | SaveFormat | تنسيق البيانات المصدرة. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | When stream or slides parameter is null. |
| ArgumentOutOfRangeException | When slides parameter contains wrong page numbers. |
| InvalidOperationException | When an unsupported SaveFormat is used, e.g. PPTX, PPTM, PPSX, PPSM, POTX, POTM, PPT, ODP. |

### See Also

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* class [Presentation](../../presentation)
* namespace [Aspose.Slides](../../presentation)
* assembly [Aspose.Slides](../../../)

---

## Save(string, int[], SaveFormat, ISaveOptions) {#save_8}

يحفظ الشرائح المحددة في عرض تقديمي إلى ملف بالتنسيق المحدد مع الحفاظ على أرقام الصفحات.

```csharp
public void Save(string fname, int[] slides, SaveFormat format, ISaveOptions options)
```

| Parameter | Type | Description |
| --- | --- | --- |
| fname | String | المسار إلى الملف الذي تم إنشاؤه. |
| slides | Int32[] | مصفوفة تحتوي على مواضع الشرائح، بدءًا من 1. |
| format | SaveFormat | تنسيق البيانات المصدرة. |
| options | ISaveOptions | خيارات تنسيق إضافية. |

### See Also

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* interface [ISaveOptions](../../../aspose.slides.export/isaveoptions)
* class [Presentation](../../presentation)
* namespace [Aspose.Slides](../../presentation)
* assembly [Aspose.Slides](../../../)

---

## Save(Stream, int[], SaveFormat) {#save_3}

يحفظ الشرائح المحددة في عرض تقديمي إلى تدفق بالتنسيق المحدد مع الحفاظ على أرقام الصفحات.

```csharp
public void Save(Stream stream, int[] slides, SaveFormat format)
```

| Parameter | Type | Description |
| --- | --- | --- |
| stream | Stream | تدفق الإخراج. |
| slides | Int32[] | مصفوفة تحتوي على مواضع الشرائح، بدءًا من 1. |
| format | SaveFormat | تنسيق البيانات المصدرة. |

### See Also

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* class [Presentation](../../presentation)
* namespace [Aspose.Slides](../../presentation)
* assembly [Aspose.Slides](../../../)

---

## Save(Stream, int[], SaveFormat, ISaveOptions) {#save_4}

يحفظ الشرائح المحددة في عرض تقديمي إلى تدفق بالتنسيق المحدد مع الحفاظ على أرقام الصفحات.

```csharp
public void Save(Stream stream, int[] slides, SaveFormat format, ISaveOptions options)
```

| Parameter | Type | Description |
| --- | --- | --- |
| stream | Stream | تدفق الإخراج. |
| slides | Int32[] | مصفوفة تحتوي على مواضع الشرائح، بدءًا من 1. |
| format | SaveFormat | تنسيق البيانات المصدرة. |
| options | ISaveOptions | خيارات تنسيق إضافية. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | When stream or slides parameter is null. |
| ArgumentOutOfRangeException | When slides parameter contains wrong page numbers. |
| InvalidOperationException | When an unsupported SaveFormat is used, e.g. PPTX, PPTM, PPSX, PPSM, POTX, POTM, PPT, ODP. |

### Examples

المثال التالي يوضح كيفية تحويل PowerPoint إلى PNG.

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

المثال التالي يوضح كيفية تحويل PowerPoint إلى PNG بأبعاد مخصصة.

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

المثال التالي يوضح كيفية تحويل PowerPoint إلى PNG بحجم مخصص.

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

### See Also

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* interface [ISaveOptions](../../../aspose.slides.export/isaveoptions)
* class [Presentation](../../presentation)
* namespace [Aspose.Slides](../../presentation)
* assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->