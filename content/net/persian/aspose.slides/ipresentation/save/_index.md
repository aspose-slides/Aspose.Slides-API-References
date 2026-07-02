---
title: Save
second_title: مرجع API Aspose.Sildes برای .NET
description: تمام اسلایدهای یک ارائه را با فرمت مشخص به یک فایل ذخیره می‌کند.
type: docs
weight: 380
url: /fa/aspose.slides/ipresentation/save/
---
## Save(string, SaveFormat) {#save_5}

تمام اسلایدهای یک ارائه را با فرمت مشخص به یک فایل ذخیره می‌کند.

```csharp
public void Save(string fname, SaveFormat format)
```

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| fname | String | مسیر فایل ایجاد شده. |
| format | SaveFormat | فرمت داده‌های صادر شده. |

### موارد مرتبط

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* interface [IPresentation](../../ipresentation)
* namespace [Aspose.Slides](../../ipresentation)
* assembly [Aspose.Slides](../../../)

---

## Save(Stream, SaveFormat) {#save_1}

تمام اسلایدهای یک ارائه را در قالب مشخص به یک جریان ذخیره می‌کند.

```csharp
public void Save(Stream stream, SaveFormat format)
```

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| stream | Stream | جریان خروجی. |
| format | SaveFormat | فرمت داده‌های صادر شده. |

### موارد مرتبط

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* interface [IPresentation](../../ipresentation)
* namespace [Aspose.Slides](../../ipresentation)
* assembly [Aspose.Slides](../../../)

---

## Save(string, SaveFormat, ISaveOptions) {#save_6}

تمام اسلایدهای یک ارائه را با فرمت مشخص و با گزینه‌های اضافی به یک فایل ذخیره می‌کند.

```csharp
public void Save(string fname, SaveFormat format, ISaveOptions options)
```

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| fname | String | مسیر فایل ایجاد شده. |
| format | SaveFormat | فرمت داده‌های صادر شده. |
| options | ISaveOptions | گزینه‌های فرمت اضافی. |

### موارد مرتبط

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* interface [ISaveOptions](../../../aspose.slides.export/isaveoptions)
* interface [IPresentation](../../ipresentation)
* namespace [Aspose.Slides](../../ipresentation)
* assembly [Aspose.Slides](../../../)

---

## Save(Stream, SaveFormat, ISaveOptions) {#save_2}

تمام اسلایدهای یک ارائه را در قالب مشخص و با گزینه‌های اضافی به یک جریان ذخیره می‌کند.

```csharp
public void Save(Stream stream, SaveFormat format, ISaveOptions options)
```

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| stream | Stream | جریان خروجی. |
| format | SaveFormat | فرمت داده‌های صادر شده. |
| options | ISaveOptions | گزینه‌های فرمت اضافی. |

### استثناها

| استثنا | شرط |
| --- | --- |
| NotSupportedException | اگر سعی کنید فایلی رمزگذاری شده را در قالبی غیر از Office 2007-2010 ذخیره کنید |

### موارد مرتبط

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* interface [ISaveOptions](../../../aspose.slides.export/isaveoptions)
* interface [IPresentation](../../ipresentation)
* namespace [Aspose.Slides](../../ipresentation)
* assembly [Aspose.Slides](../../../)

---

## Save(string, int[], SaveFormat) {#save_7}

اسلایدهای مشخص شدهٔ یک ارائه را با فرمت مشخص به یک فایل ذخیره می‌کند.

```csharp
public void Save(string fname, int[] slides, SaveFormat format)
```

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| fname | String | مسیر فایل ایجاد شده. |
| slides | Int32[] | آرایه‌ای شامل موقعیت‌های اسلاید، شروع از ۱. |
| format | SaveFormat | فرمت داده‌های صادر شده. |

### استثناها

| استثنا | شرط |
| --- | --- |
| ArgumentNullException | وقتی پارامتر stream یا slides مقدار null داشته باشد. |
| ArgumentOutOfRangeException | وقتی پارامتر slides شامل شماره‌های صفحهٔ نادرست باشد. |
| InvalidOperationException | وقتی از SaveFormat پشتیبانی نشده‌ای استفاده شود، مثلاً PPTX، PPTM، PPSX، PPSM، POTX، POTM، PPT، ODP. |

### موارد مرتبط

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* interface [IPresentation](../../ipresentation)
* namespace [Aspose.Slides](../../ipresentation)
* assembly [Aspose.Slides](../../../)

---

## Save(string, int[], SaveFormat, ISaveOptions) {#save_8}

اسلایدهای مشخص شدهٔ یک ارائه را با فرمت مشخص و گزینه‌های اضافی به یک فایل ذخیره می‌کند.

```csharp
public void Save(string fname, int[] slides, SaveFormat format, ISaveOptions options)
```

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| fname | String | مسیر فایل ایجاد شده. |
| slides | Int32[] | آرایه‌ای شامل موقعیت‌های اسلاید، شروع از ۱. |
| format | SaveFormat | فرمت داده‌های صادر شده. |
| options | ISaveOptions | گزینه‌های فرمت اضافی. |

### استثناها

| استثنا | شرط |
| --- | --- |
| ArgumentNullException | وقتی پارامتر stream یا slides مقدار null داشته باشد. |
| ArgumentOutOfRangeException | وقتی پارامتر slides شامل شماره‌های صفحهٔ نادرست باشد. |
| InvalidOperationException | وقتی از SaveFormat پشتیبانی نشده‌ای استفاده شود، مثلاً PPTX، PPTM، PPSX، PPSM، POTX، POTM، PPT، ODP. |

### موارد مرتبط

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* interface [ISaveOptions](../../../aspose.slides.export/isaveoptions)
* interface [IPresentation](../../ipresentation)
* namespace [Aspose.Slides](../../ipresentation)
* assembly [Aspose.Slides](../../../)

---

## Save(Stream, int[], SaveFormat) {#save_3}

اسلایدهای مشخص شدهٔ یک ارائه را در قالب مشخص به یک جریان ذخیره می‌کند.

```csharp
public void Save(Stream stream, int[] slides, SaveFormat format)
```

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| stream | Stream | جریان خروجی. |
| slides | Int32[] | آرایه‌ای شامل موقعیت‌های اسلاید، شروع از ۱. |
| format | SaveFormat | فرمت داده‌های صادر شده. |

### استثناها

| استثنا | شرط |
| --- | --- |
| ArgumentNullException | وقتی پارامتر stream یا slides مقدار null داشته باشد. |
| ArgumentOutOfRangeException | وقتی پارامتر slides شامل شماره‌های صفحهٔ نادرست باشد. |
| InvalidOperationException | وقتی از SaveFormat پشتیبانی نشده‌ای استفاده شود، مثلاً PPTX، PPTM، PPSX، PPSM، POTX، POTM، PPT، ODP. |

### موارد مرتبط

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* interface [IPresentation](../../ipresentation)
* namespace [Aspose.Slides](../../ipresentation)
* assembly [Aspose.Slides](../../../)

---

## Save(Stream, int[], SaveFormat, ISaveOptions) {#save_4}

اسلایدهای مشخص شدهٔ یک ارائه را در قالب مشخص و با گزینه‌های اضافی به یک جریان ذخیره می‌کند.

```csharp
public void Save(Stream stream, int[] slides, SaveFormat format, ISaveOptions options)
```

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| stream | Stream | جریان خروجی. |
| slides | Int32[] | آرایه‌ای شامل موقعیت‌های اسلاید، شروع از ۱. |
| format | SaveFormat | فرمت داده‌های صادر شده. |
| options | ISaveOptions | گزینه‌های فرمت اضافی. |

### استثناها

| استثنا | شرط |
| --- | --- |
| ArgumentNullException | وقتی پارامتر stream یا slides مقدار null داشته باشد. |
| ArgumentOutOfRangeException | وقتی پارامتر slides شامل شماره‌های صفحهٔ نادرست باشد. |
| InvalidOperationException | وقتی از SaveFormat پشتیبانی نشده‌ای استفاده شود، مثلاً PPTX، PPTM، PPSX، PPSM، POTX، POTM، PPT، ODP. |

### موارد مرتبط

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* interface [ISaveOptions](../../../aspose.slides.export/isaveoptions)
* interface [IPresentation](../../ipresentation)
* namespace [Aspose.Slides](../../ipresentation)
* assembly [Aspose.Slides](../../../)

---

## Save(IXamlOptions) {#save}

تمام اسلایدهای یک ارائه را به مجموعه‌ای از فایل‌ها که نشانگر قالب‌بندی XAML هستند، ذخیره می‌کند.

```csharp
public void Save(IXamlOptions options)
```

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| options | IXamlOptions | گزینه‌های فرمت XAML. |

### مثال‌ها

```csharp
[C#]
using (Presentation pres = new Presentation("pres.pptx"))
{
	pres.Save(new XamlOptions { ExportHiddenSlides = true });
}
```

### موارد مرتبط

* interface [IXamlOptions](../../../aspose.slides.export.xaml/ixamloptions)
* interface [IPresentation](../../ipresentation)
* namespace [Aspose.Slides](../../ipresentation)
* assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->