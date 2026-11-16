---
title: Save
second_title: Aspose.Sildes ل .NET مرجع API
description: يحفظ جميع الشرائح في عرض تقديمي إلى ملف بالتنسيق المحدد.
type: docs
weight: 390
url: /ar/aspose.slides/ipresentation/save/
---
## Save(string, SaveFormat) {#save_5}

يحفظ جميع الشرائح في عرض تقديمي إلى ملف بالتنسيق المحدد.

```csharp
public void Save(string fname, SaveFormat format)
```

| المعلمة | النوع | الوصف |
| --- | --- | --- |
| fname | String | المسار إلى الملف الذي تم إنشاؤه. |
| format | SaveFormat | تنسيق البيانات المصدرة. |

### انظر أيضًا

* عدد [SaveFormat](../../../aspose.slides.export/saveformat)
* واجهة [IPresentation](../../ipresentation)
* نطاق [Aspose.Slides](../../ipresentation)
* تجميع [Aspose.Slides](../../../)

---

## Save(Stream, SaveFormat) {#save_1}

يحفظ جميع الشرائح في عرض تقديمي إلى تدفق بالتنسيق المحدد.

```csharp
public void Save(Stream stream, SaveFormat format)
```

| المعلمة | النوع | الوصف |
| --- | --- | --- |
| stream | Stream | تدفق الإخراج. |
| format | SaveFormat | تنسيق البيانات المصدرة. |

### انظر أيضًا

* عدد [SaveFormat](../../../aspose.slides.export/saveformat)
* واجهة [IPresentation](../../ipresentation)
* نطاق [Aspose.Slides](../../ipresentation)
* تجميع [Aspose.Slides](../../../)

---

## Save(string, SaveFormat, ISaveOptions) {#save_6}

يحفظ جميع الشرائح في عرض تقديمي إلى ملف بالتنسيق المحدد ومع خيارات إضافية.

```csharp
public void Save(string fname, SaveFormat format, ISaveOptions options)
```

| المعلمة | النوع | الوصف |
| --- | --- | --- |
| fname | String | المسار إلى الملف الذي تم إنشاؤه. |
| format | SaveFormat | تنسيق البيانات المصدرة. |
| options | ISaveOptions | خيارات تنسيق إضافية. |

### انظر أيضًا

* عدد [SaveFormat](../../../aspose.slides.export/saveformat)
* واجهة [ISaveOptions](../../../aspose.slides.export/isaveoptions)
* واجهة [IPresentation](../../ipresentation)
* نطاق [Aspose.Slides](../../ipresentation)
* تجميع [Aspose.Slides](../../../)

---

## Save(Stream, SaveFormat, ISaveOptions) {#save_2}

يحفظ جميع الشرائح في عرض تقديمي إلى تدفق بالتنسيق المحدد ومع خيارات إضافية.

```csharp
public void Save(Stream stream, SaveFormat format, ISaveOptions options)
```

| المعلمة | النوع | الوصف |
| --- | --- | --- |
| stream | Stream | تدفق الإخراج. |
| format | SaveFormat | تنسيق البيانات المصدرة. |
| options | ISaveOptions | خيارات تنسيق إضافية. |

### الاستثناءات

| الاستثناء | الشرط |
| --- | --- |
| NotSupportedException | إذا حاولت حفظ ملف مشفر بتنسيق ليس من Office 2007-2010 |

### انظر أيضًا

* عدد [SaveFormat](../../../aspose.slides.export/saveformat)
* واجهة [ISaveOptions](../../../aspose.slides.export/isaveoptions)
* واجهة [IPresentation](../../ipresentation)
* نطاق [Aspose.Slides](../../ipresentation)
* تجميع [Aspose.Slides](../../../)

---

## Save(string, int[], SaveFormat) {#save_7}

يحفظ الشرائح المحددة في عرض تقديمي إلى ملف بالتنسيق المحدد.

```csharp
public void Save(string fname, int[] slides, SaveFormat format)
```

| المعلمة | النوع | الوصف |
| --- | --- | --- |
| fname | String | المسار إلى الملف الذي تم إنشاؤه. |
| slides | Int32[] | مصفوفة تحتوي على مواضع الشرائح، بدءًا من 1. |
| format | SaveFormat | تنسيق البيانات المصدرة. |

### الاستثناءات

| الاستثناء | الشرط |
| --- | --- |
| ArgumentNullException | عند كون معلمة الـ stream أو slides فارغة (null). |
| ArgumentOutOfRangeException | عند احتواء معلمة slides على أرقام صفحات غير صحيحة. |
| InvalidOperationException | عند استخدام تنسيق SaveFormat غير مدعوم، مثل PPTX, PPTM, PPSX, PPSM, POTX, POTM, PPT, ODP. |

### انظر أيضًا

* عدد [SaveFormat](../../../aspose.slides.export/saveformat)
* واجهة [IPresentation](../../ipresentation)
* نطاق [Aspose.Slides](../../ipresentation)
* تجميع [Aspose.Slides](../../../)

---

## Save(string, int[], SaveFormat, ISaveOptions) {#save_8}

يحفظ الشرائح المحددة في عرض تقديمي إلى ملف بالتنسيق المحدد.

```csharp
public void Save(string fname, int[] slides, SaveFormat format, ISaveOptions options)
```

| المعلمة | النوع | الوصف |
| --- | --- | --- |
| fname | String | المسار إلى الملف الذي تم إنشاؤه. |
| slides | Int32[] | مصفوفة تحتوي على مواضع الشرائح، بدءًا من 1. |
| format | SaveFormat | تنسيق البيانات المصدرة. |
| options | ISaveOptions | خيارات تنسيق إضافية. |

### الاستثناءات

| الاستثناء | الشرط |
| --- | --- |
| ArgumentNullException | عند كون معلمة الـ stream أو slides فارغة (null). |
| ArgumentOutOfRangeException | عند احتواء معلمة slides على أرقام صفحات غير صحيحة. |
| InvalidOperationException | عند استخدام تنسيق SaveFormat غير مدعوم، مثل PPTX, PPTM, PPSX, PPSM, POTX, POTM, PPT, ODP. |

### انظر أيضًا

* عدد [SaveFormat](../../../aspose.slides.export/saveformat)
* واجهة [ISaveOptions](../../../aspose.slides.export/isaveoptions)
* واجهة [IPresentation](../../ipresentation)
* نطاق [Aspose.Slides](../../ipresentation)
* تجميع [Aspose.Slides](../../../)

---

## Save(Stream, int[], SaveFormat) {#save_3}

يحفظ الشرائح المحددة في عرض تقديمي إلى تدفق بالتنسيق المحدد.

```csharp
public void Save(Stream stream, int[] slides, SaveFormat format)
```

| المعلمة | النوع | الوصف |
| --- | --- | --- |
| stream | Stream | تدفق الإخراج. |
| slides | Int32[] | مصفوفة تحتوي على مواضع الشرائح، بدءًا من 1. |
| format | SaveFormat | تنسيق البيانات المصدرة. |

### الاستثناءات

| الاستثناء | الشرط |
| --- | --- |
| ArgumentNullException | عند كون معلمة الـ stream أو slides فارغة (null). |
| ArgumentOutOfRangeException | عند احتواء معلمة slides على أرقام صفحات غير صحيحة. |
| InvalidOperationException | عند استخدام تنسيق SaveFormat غير مدعوم، مثل PPTX, PPTM, PPSX, PPSM, POTX, POTM, PPT, ODP. |

### انظر أيضًا

* عدد [SaveFormat](../../../aspose.slides.export/saveformat)
* واجهة [IPresentation](../../ipresentation)
* نطاق [Aspose.Slides](../../ipresentation)
* تجميع [Aspose.Slides](../../../)

---

## Save(Stream, int[], SaveFormat, ISaveOptions) {#save_4}

يحفظ الشرائح المحددة في عرض تقديمي إلى تدفق بالتنسيق المحدد ومع خيارات إضافية.

```csharp
public void Save(Stream stream, int[] slides, SaveFormat format, ISaveOptions options)
```

| المعلمة | النوع | الوصف |
| --- | --- | --- |
| stream | Stream | تدفق الإخراج. |
| slides | Int32[] | مصفوفة تحتوي على مواضع الشرائح، بدءًا من 1. |
| format | SaveFormat | تنسيق البيانات المصدرة. |
| options | ISaveOptions | خيارات تنسيق إضافية. |

### الاستثناءات

| الاستثناء | الشرط |
| --- | --- |
| ArgumentNullException | عند كون معلمة الـ stream أو slides فارغة (null). |
| ArgumentOutOfRangeException | عند احتواء معلمة slides على أرقام صفحات غير صحيحة. |
| InvalidOperationException | عند استخدام تنسيق SaveFormat غير مدعوم، مثل PPTX, PPTM, PPSX, PPSM, POTX, POTM, PPT, ODP. |

### انظر أيضًا

* عدد [SaveFormat](../../../aspose.slides.export/saveformat)
* واجهة [ISaveOptions](../../../aspose.slides.export/isaveoptions)
* واجهة [IPresentation](../../ipresentation)
* نطاق [Aspose.Slides](../../ipresentation)
* تجميع [Aspose.Slides](../../../)

---

## Save(IXamlOptions) {#save}

يحفظ جميع الشرائح في عرض تقديمي إلى مجموعة من الملفات التي تمثل ترميز XAML.

```csharp
public void Save(IXamlOptions options)
```

| المعلمة | النوع | الوصف |
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

* واجهة [IXamlOptions](../../../aspose.slides.export.xaml/ixamloptions)
* واجهة [IPresentation](../../ipresentation)
* نطاق [Aspose.Slides](../../ipresentation)
* تجميع [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->