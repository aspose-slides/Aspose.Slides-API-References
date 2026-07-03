---
title: Save
second_title: Aspose.Sildes برای .NET مرجع API
description: تمام اسلایدهای یک ارائه را در فایلی با فرمت مشخص ذخیره می‌کند.
type: docs
weight: 390
url: /fa/aspose.slides/presentation/save/
---
## Save(string, SaveFormat) {#save_5}

تمام اسلایدهای یک ارائه را در یک فایل با فرمت مشخص ذخیره می‌کند.

```csharp
public void Save(string fname, SaveFormat format)
```

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| fname | String | مسیر فایل ایجاد شده. |
| format | SaveFormat | فرمت داده‌های صادر شده. |

### موارد مرتبط

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* کلاس [Presentation](../../presentation)
* فضای‌نام [Aspose.Slides](../../presentation)
* اسمبلی [Aspose.Slides](../../../)

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
* کلاس [Presentation](../../presentation)
* فضای‌نام [Aspose.Slides](../../presentation)
* اسمبلی [Aspose.Slides](../../../)

---

## Save(string, SaveFormat, ISaveOptions) {#save_6}

```csharp
public void Save(string fname, SaveFormat format, ISaveOptions options)
```

### موارد مرتبط

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* رابط [ISaveOptions](../../../aspose.slides.export/isaveoptions)
* کلاس [Presentation](../../presentation)
* فضای‌نام [Aspose.Slides](../../presentation)
* اسمبلی [Aspose.Slides](../../../)

---

## Save(Stream, SaveFormat, ISaveOptions) {#save_2}

تمام اسلایدهای یک ارائه را در قالب مشخص به یک جریان ذخیره می‌کند و گزینه‌های اضافی را اعمال می‌نماید.

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
| NotSupportedException | اگر سعی کنید فایلی رمزگذاری‌شده را در قالبی غیر از Office 2007-2010 ذخیره کنید |

### موارد مرتبط

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* رابط [ISaveOptions](../../../aspose.slides.export/isaveoptions)
* کلاس [Presentation](../../presentation)
* فضای‌نام [Aspose.Slides](../../presentation)
* اسمبلی [Aspose.Slides](../../../)

---

## Save(IXamlOptions) {#save}

تمام اسلایدهای یک ارائه را در مجموعه‌ای از فایل‌ها که نشانگر نشانه‌گذاری XAML هستند ذخیره می‌کند.

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

* رابط [IXamlOptions](../../../aspose.slides.export.xaml/ixamloptions)
* کلاس [Presentation](../../presentation)
* فضای‌نام [Aspose.Slides](../../presentation)
* اسمبلی [Aspose.Slides](../../../)

---

## Save(string, int[], SaveFormat) {#save_7}

اسلایدهای مشخص‌شدهٔ یک ارائه را در فایلی با فرمت مشخص و حفظ شماره صفحه ذخیره می‌کند.

```csharp
public void Save(string fname, int[] slides, SaveFormat format)
```

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| fname | String | مسیر فایل ایجاد شده. |
| slides | Int32[] | آرایه‌ای با موقعیت‌های اسلاید، شروع از ۱. |
| format | SaveFormat | فرمت داده‌های صادر شده. |

### استثناها

| استثنا | شرط |
| --- | --- |
| ArgumentNullException | زمانی که پارامتر stream یا slides مقدار Null داشته باشد |
| ArgumentOutOfRangeException | زمانی که پارامتر slides شامل شماره‌های صفحهٔ نادرست باشد |
| InvalidOperationException | زمانی که از یک SaveFormat پشتیبانی‌نشده استفاده شود، مثلا PPTX، PPTM، PPSX، PPSM، POTX، POTM، PPT، ODP |

### موارد مرتبط

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* کلاس [Presentation](../../presentation)
* فضای‌نام [Aspose.Slides](../../presentation)
* اسمبلی [Aspose.Slides](../../../)

---

## Save(string, int[], SaveFormat, ISaveOptions) {#save_8}

اسلایدهای مشخص‌شدهٔ یک ارائه را در فایلی با فرمت مشخص و حفظ شماره صفحه ذخیره می‌کند و گزینه‌های فرمت اضافی را اعمال می‌نماید.

```csharp
public void Save(string fname, int[] slides, SaveFormat format, ISaveOptions options)
```

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| fname | String | مسیر فایل ایجاد شده. |
| slides | Int32[] | آرایه‌ای با موقعیت‌های اسلاید، شروع از ۱. |
| format | SaveFormat | فرمت داده‌های صادر شده. |
| options | ISaveOptions | گزینه‌های فرمت اضافی. |

### موارد مرتبط

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* رابط [ISaveOptions](../../../aspose.slides.export/isaveoptions)
* کلاس [Presentation](../../presentation)
* فضای‌نام [Aspose.Slides](../../presentation)
* اسمبلی [Aspose.Slides](../../../)

---

## Save(Stream, int[], SaveFormat) {#save_3}

اسلایدهای مشخص‌شدهٔ یک ارائه را در قالب مشخص به یک جریان ذخیره می‌کند و شماره صفحه را حفظ می‌نماید.

```csharp
public void Save(Stream stream, int[] slides, SaveFormat format)
```

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| stream | Stream | جریان خروجی. |
| slides | Int32[] | آرایه‌ای با موقعیت‌های اسلاید، شروع از ۱. |
| format | SaveFormat | فرمت داده‌های صادر شده. |

### موارد مرتبط

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* کلاس [Presentation](../../presentation)
* فضای‌نام [Aspose.Slides](../../presentation)
* اسمبلی [Aspose.Slides](../../../)

---

## Save(Stream, int[], SaveFormat, ISaveOptions) {#save_4}

اسلایدهای مشخص‌شدهٔ یک ارائه را در قالب مشخص به یک جریان ذخیره می‌کند، شماره صفحه را حفظ می‌کند و گزینه‌های فرمت اضافی را اعمال می‌نماید.

```csharp
public void Save(Stream stream, int[] slides, SaveFormat format, ISaveOptions options)
```

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| stream | Stream | جریان خروجی. |
| slides | Int32[] | آرایه‌ای با موقعیت‌های اسلاید، شروع از ۱. |
| format | SaveFormat | فرمت داده‌های صادر شده. |
| options | ISaveOptions | گزینه‌های فرمت اضافی. |

### استثناها

| استثنا | شرط |
| --- | --- |
| ArgumentNullException | زمانی که پارامتر stream یا slides مقدار Null داشته باشد |
| ArgumentOutOfRangeException | زمانی که پارامتر slides شامل شماره‌های صفحهٔ نادرست باشد |
| InvalidOperationException | زمانی که از یک SaveFormat پشتیبانی‌نشده استفاده شود، مثلا PPTX، PPTM، PPSX، PPSM، POTX، POTM، PPT، ODP |

### مثال‌ها

مثال زیر نشان می‌دهد چگونه PowerPoint را به PNG تبدیل کنید.

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

مثال زیر نشان می‌دهد چگونه PowerPoint را به PNG با ابعاد سفارشی تبدیل کنید.

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

مثال زیر نشان می‌دهد چگونه PowerPoint را به PNG با اندازهٔ سفارشی تبدیل کنید.

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

### موارد مرتبط

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* رابط [ISaveOptions](../../../aspose.slides.export/isaveoptions)
* کلاس [Presentation](../../presentation)
* فضای‌نام [Aspose.Slides](../../presentation)
* اسمبلی [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->