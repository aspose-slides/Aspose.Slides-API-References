---
title: Save
second_title: مرجع API Aspose.Sildes لـ .NET
description: يحفظ جميع الشرائح في عرض تقديمي إلى ملف بالتنسيق المحدد.
type: docs
weight: 390
url: /ar/aspose.slides/presentation/save/
---
## Save(string, SaveFormat) {#save_5}

يحفظ جميع الشرائح في عرض تقديمي إلى ملف بالتنسيق المحدد.

```csharp
public void Save(string fname, SaveFormat format)
```

| المعامل | النوع | الوصف |
| --- | --- | --- |
| fname | String | مسار الملف الذي سيتم إنشاؤه. |
| format | SaveFormat | تنسيق البيانات المصدرة. |

### انظر أيضًا

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* class [Presentation](../../presentation)
* namespace [Aspose.Slides](../../presentation)
* assembly [Aspose.Slides](../../../)

---

## Save(Stream, SaveFormat) {#save_1}

يحفظ جميع الشرائح في عرض تقديمي إلى تدفق بالصيغة المحددة.

```csharp
public void Save(Stream stream, SaveFormat format)
```

| المعامل | النوع | الوصف |
| --- | --- | --- |
| stream | Stream | تدفق الإخراج. |
| format | SaveFormat | تنسيق البيانات المصدرة. |

### انظر أيضًا

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* class [Presentation](../../presentation)
* namespace [Aspose.Slides](../../presentation)
* assembly [Aspose.Slides](../../../)

---

## Save(string, SaveFormat, ISaveOptions) {#save_6}

```csharp
public void Save(string fname, SaveFormat format, ISaveOptions options)
```

### انظر أيضًا

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* interface [ISaveOptions](../../../aspose.slides.export/isaveoptions)
* class [Presentation](../../presentation)
* namespace [Aspose.Slides](../../presentation)
* assembly [Aspose.Slides](../../../)

---

## Save(Stream, SaveFormat, ISaveOptions) {#save_2}

يحفظ جميع الشرائح في عرض تقديمي إلى تدفق بالصيغة المحددة ومع خيارات إضافية.

```csharp
public void Save(Stream stream, SaveFormat format, ISaveOptions options)
```

| المعامل | النوع | الوصف |
| --- | --- | --- |
| stream | Stream | تدفق الإخراج. |
| format | SaveFormat | تنسيق البيانات المصدرة. |
| options | ISaveOptions | خيارات تنسيق إضافية. |

### الاستثناءات

| الاستثناء | الشرط |
| --- | --- |
| NotSupportedException | إذا حاولت حفظ ملف مشفر بصيغة غير صيغ Office 2007-2010 |

### انظر أيضًا

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* interface [ISaveOptions](../../../aspose.slides.export/isaveoptions)
* class [Presentation](../../presentation)
* namespace [Aspose.Slides](../../presentation)
* assembly [Aspose.Slides](../../../)

---

## Save(IXamlOptions) {#save}

يحفظ جميع الشرائح في عرض تقديمي إلى مجموعة من الملفات التي تمثل علامة XAML.

```csharp
public void Save(IXamlOptions options)
```

| المعامل | النوع | الوصف |
| --- | --- | --- |
| options | IXamlOptions | خيارات تنسيق XAML. |

### أمثلة

```csharp
[C#]
using (Presentation pres = new Presentation("pres.pptx"))
{
	pres.Save(new XamlOptions { ExportHiddenSlides = true });
}
```

### انظر أيضًا

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

| المعامل | النوع | الوصف |
| --- | --- | --- |
| fname | String | مسار الملف الذي سيتم إنشاؤه. |
| slides | Int32[] | مصفوفة بمواقع الشرائح، بدءًا من 1. |
| format | SaveFormat | تنسيق البيانات المصدرة. |

### الاستثناءات

| الاستثناء | الشرط |
| --- | --- |
| ArgumentNullException | عندما يكون stream أو slides فارغًا. |
| ArgumentOutOfRangeException | عندما تحتوي slides على أرقام صفحات غير صحيحة. |
| InvalidOperationException | عندما يتم استخدام SaveFormat غير مدعوم، مثل PPTX, PPTM, PPSX, PPSM, POTX, POTM, PPT, ODP. |

### انظر أيضًا

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

| المعامل | النوع | الوصف |
| --- | --- | --- |
| fname | String | مسار الملف الذي سيتم إنشاؤه. |
| slides | Int32[] | مصفوفة بمواقع الشرائح، بدءًا من 1. |
| format | SaveFormat | تنسيق البيانات المصدرة. |
| options | ISaveOptions | خيارات تنسيق إضافية. |

### انظر أيضًا

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

| المعامل | النوع | الوصف |
| --- | --- | --- |
| stream | Stream | تدفق الإخراج. |
| slides | Int32[] | مصفوفة بمواقع الشرائح، بدءًا من 1. |
| format | SaveFormat | تنسيق البيانات المصدرة. |

### انظر أيضًا

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

| المعامل | النوع | الوصف |
| --- | --- | --- |
| stream | Stream | تدفق الإخراج. |
| slides | Int32[] | مصفوفة بمواقع الشرائح، بدءًا من 1. |
| format | SaveFormat | تنسيق البيانات المصدرة. |
| options | ISaveOptions | خيارات تنسيق إضافية. |

### الاستثناءات

| الاستثناء | الشرط |
| --- | --- |
| ArgumentNullException | عندما يكون stream أو slides فارغًا. |
| ArgumentOutOfRangeException | عندما تحتوي slides على أرقام صفحات غير صحيحة. |
| InvalidOperationException | عندما يتم استخدام SaveFormat غير مدعوم، مثل PPTX, PPTM, PPSX, PPSM, POTX, POTM, PPT, ODP. |

### أمثلة

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

### انظر أيضًا

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* interface [ISaveOptions](../../../aspose.slides.export/isaveoptions)
* class [Presentation](../../presentation)
* namespace [Aspose.Slides](../../presentation)
* assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->