---
title: Save
second_title: مرجع API Aspose.Sildes لـ .NET
description: يحفظ جميع الشرائح في عرض تقديمي إلى ملف بالصيغة المحددة.
type: docs
weight: 380
url: /ar/aspose.slides/ipresentation/save/
---
## Save(string, SaveFormat) {#save_5}

يحفظ جميع الشرائح في عرض تقديمي إلى ملف بالصيغة المحددة.

```csharp
public void Save(string fname, SaveFormat format)
```

| Parameter | Type | Description |
| --- | --- | --- |
| fname | String | مسار الملف الذي تم إنشاؤه. |
| format | SaveFormat | صيغة البيانات المصدرة. |

### See Also

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* interface [IPresentation](../../ipresentation)
* namespace [Aspose.Slides](../../ipresentation)
* assembly [Aspose.Slides](../../../)

---

## Save(Stream, SaveFormat) {#save_1}

يحفظ جميع الشرائح في عرض تقديمي إلى تدفق بالصيغة المحددة.

```csharp
public void Save(Stream stream, SaveFormat format)
```

| Parameter | Type | Description |
| --- | --- | --- |
| stream | Stream | تدفق الإخراج. |
| format | SaveFormat | صيغة البيانات المصدرة. |

### See Also

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* interface [IPresentation](../../ipresentation)
* namespace [Aspose.Slides](../../ipresentation)
* assembly [Aspose.Slides](../../../)

---

## Save(string, SaveFormat, ISaveOptions) {#save_6}

يحفظ جميع الشرائح في عرض تقديمي إلى ملف بالصيغة المحددة مع خيارات إضافية.

```csharp
public void Save(string fname, SaveFormat format, ISaveOptions options)
```

| Parameter | Type | Description |
| --- | --- | --- |
| fname | String | مسار الملف الذي تم إنشاؤه. |
| format | SaveFormat | صيغة البيانات المصدرة. |
| options | ISaveOptions | خيارات صيغة إضافية. |

### See Also

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* interface [ISaveOptions](../../../aspose.slides.export/isaveoptions)
* interface [IPresentation](../../ipresentation)
* namespace [Aspose.Slides](../../ipresentation)
* assembly [Aspose.Slides](../../../)

---

## Save(Stream, SaveFormat, ISaveOptions) {#save_2}

يحفظ جميع الشرائح في عرض تقديمي إلى تدفق بالصيغة المحددة مع خيارات إضافية.

```csharp
public void Save(Stream stream, SaveFormat format, ISaveOptions options)
```

| Parameter | Type | Description |
| --- | --- | --- |
| stream | Stream | تدفق الإخراج. |
| format | SaveFormat | صيغة البيانات المصدرة. |
| options | ISaveOptions | خيارات صيغة إضافية. |

### Exceptions

| exception | condition |
| --- | --- |
| NotSupportedException | إذا حاولت حفظ ملف مشفر بصيغة غير Office 2007-2010 |

### See Also

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* interface [ISaveOptions](../../../aspose.slides.export/isaveoptions)
* interface [IPresentation](../../ipresentation)
* namespace [Aspose.Slides](../../ipresentation)
* assembly [Aspose.Slides](../../../)

---

## Save(string, int[], SaveFormat) {#save_7}

يحفظ الشرائح المحددة في عرض تقديمي إلى ملف بالصيغة المحددة.

```csharp
public void Save(string fname, int[] slides, SaveFormat format)
```

| Parameter | Type | Description |
| --- | --- | --- |
| fname | String | مسار الملف الذي تم إنشاؤه. |
| slides | Int32[] | مصفوفة بمواقع الشرائح، تبدأ من 1. |
| format | SaveFormat | صيغة البيانات المصدرة. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | عندما يكون معامل stream أو slides بقيمة null. |
| ArgumentOutOfRangeException | عندما يحتوي معامل slides على أرقام صفحات غير صحيحة. |
| InvalidOperationException | عندما يتم استخدام SaveFormat غير مدعوم، مثل PPTX, PPTM, PPSX, PPSM, POTX, POTM, PPT, ODP. |

### See Also

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* interface [IPresentation](../../ipresentation)
* namespace [Aspose.Slides](../../ipresentation)
* assembly [Aspose.Slides](../../../)

---

## Save(string, int[], SaveFormat, ISaveOptions) {#save_8}

يحفظ الشرائح المحددة في عرض تقديمي إلى ملف بالصيغة المحددة.

```csharp
public void Save(string fname, int[] slides, SaveFormat format, ISaveOptions options)
```

| Parameter | Type | Description |
| --- | --- | --- |
| fname | String | مسار الملف الذي تم إنشاؤه. |
| slides | Int32[] | مصفوفة بمواقع الشرائح، تبدأ من 1. |
| format | SaveFormat | صيغة البيانات المصدرة. |
| options | ISaveOptions | خيارات صيغة إضافية. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | عندما يكون معامل stream أو slides بقيمة null. |
| ArgumentOutOfRangeException | عندما يحتوي معامل slides على أرقام صفحات غير صحيحة. |
| InvalidOperationException | عندما يتم استخدام SaveFormat غير مدعوم، مثل PPTX, PPTM, PPSX, PPSM, POTX, POTM, PPT, ODP. |

### See Also

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* interface [ISaveOptions](../../../aspose.slides.export/isaveoptions)
* interface [IPresentation](../../ipresentation)
* namespace [Aspose.Slides](../../ipresentation)
* assembly [Aspose.Slides](../../../)

---

## Save(Stream, int[], SaveFormat) {#save_3}

يحفظ الشرائح المحددة في عرض تقديمي إلى تدفق بالصيغة المحددة.

```csharp
public void Save(Stream stream, int[] slides, SaveFormat format)
```

| Parameter | Type | Description |
| --- | --- | --- |
| stream | Stream | تدفق الإخراج. |
| slides | Int32[] | مصفوفة بمواقع الشرائح، تبدأ من 1. |
| format | SaveFormat | صيغة البيانات المصدرة. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | عندما يكون معامل stream أو slides بقيمة null. |
| ArgumentOutOfRangeException | عندما يحتوي معامل slides على أرقام صفحات غير صحيحة. |
| InvalidOperationException | عندما يتم استخدام SaveFormat غير مدعوم، مثل PPTX, PPTM, PPSX, PPSM, POTX, POTM, PPT, ODP. |

### See Also

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* interface [IPresentation](../../ipresentation)
* namespace [Aspose.Slides](../../ipresentation)
* assembly [Aspose.Slides](../../../)

---

## Save(Stream, int[], SaveFormat, ISaveOptions) {#save_4}

يحفظ الشرائح المحددة في عرض تقديمي إلى تدفق بالصيغة المحددة.

```csharp
public void Save(Stream stream, int[] slides, SaveFormat format, ISaveOptions options)
```

| Parameter | Type | Description |
| --- | --- | --- |
| stream | Stream | تدفق الإخراج. |
| slides | Int32[] | مصفوفة بمواقع الشرائح، تبدأ من 1. |
| format | SaveFormat | صيغة البيانات المصدرة. |
| options | ISaveOptions | خيارات صيغة إضافية. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | عندما يكون معامل stream أو slides بقيمة null. |
| ArgumentOutOfRangeException | عندما يحتوي معامل slides على أرقام صفحات غير صحيحة. |
| InvalidOperationException | عندما يتم استخدام SaveFormat غير مدعوم، مثل PPTX, PPTM, PPSX, PPSM, POTX, POTM, PPT, ODP. |

### See Also

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* interface [ISaveOptions](../../../aspose.slides.export/isaveoptions)
* interface [IPresentation](../../ipresentation)
* namespace [Aspose.Slides](../../ipresentation)
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
* interface [IPresentation](../../ipresentation)
* namespace [Aspose.Slides](../../ipresentation)
* assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->