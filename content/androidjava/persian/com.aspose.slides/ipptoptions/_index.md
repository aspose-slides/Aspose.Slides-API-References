---
title: IPptOptions
second_title: Aspose.Slides برای Android از طریق مرجع API جاوا
description: گزینه‌هایی را فراهم می‌کند که نحوه ذخیره‌سازی ارائه در قالب PPT را کنترل می‌کند.
type: docs
url: /fa/com.aspose.slides/ipptoptions/
---
**تمام اینترفیس‌های پیاده‌سازی‌شده:**
[com.aspose.slides.ISaveOptions](../../com.aspose.slides/isaveoptions)
```
public interface IPptOptions extends ISaveOptions
```

گزینه‌هایی را فراهم می‌کند که نحوه ذخیره‌سازی ارائه در قالب PPT را کنترل می‌کند.
## متدها

| متد | توضیح |
| --- | --- |
| [getRootDirectoryClsid()](#getRootDirectoryClsid--) | نشان‌دهنده GUID کلاس شیء (CLSID) که در ورودی ریشهٔ دایرکتوری ذخیره شده است. |
| [setRootDirectoryClsid(UUID value)](#setRootDirectoryClsid-java.util.UUID-) | نشان‌دهنده GUID کلاس شیء (CLSID) که در ورودی ریشهٔ دایرکتوری ذخیره شده است. |
### getRootDirectoryClsid() {#getRootDirectoryClsid--}
```
public abstract UUID getRootDirectoryClsid()
```

نشان‌دهنده GUID کلاس شیء (CLSID) که در ورودی ریشهٔ دایرکتوری ذخیره شده است. می‌تواند برای فعال‌سازی COM برنامهٔ سند استفاده شود. مقدار پیش‌فرض '64818D11-4F9B-11CF-86EA-00AA00B929E8' است که مربوط به 'Microsoft Powerpoint.Slide.8' می‌باشد.

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      PptOptions pptOptions = new PptOptions();
> 
>      /// تنظیم CLSID به 'Microsoft Powerpoint.Show.8'
>      pptOptions.setRootDirectoryClsid(UUID.fromString("64818D10-4F9B-11CF-86EA-00AA00B929E8"));
> 
>      pres.save("pres.ppt", SaveFormat.Ppt, pptOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**بازگرداندن:**
java.util.UUID
### setRootDirectoryClsid(UUID value) {#setRootDirectoryClsid-java.util.UUID-}
```
public abstract void setRootDirectoryClsid(UUID value)
```

نشان‌دهنده GUID کلاس شیء (CLSID) که در ورودی ریشهٔ دایرکتوری ذخیره شده است. می‌تواند برای فعال‌سازی COM برنامهٔ سند استفاده شود. مقدار پیش‌فرض '64818D11-4F9B-11CF-86EA-00AA00B929E8' است که مربوط به 'Microsoft Powerpoint.Slide.8' می‌باشد.

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      PptOptions pptOptions = new PptOptions();
> 
>      /// تنظیم CLSID به 'Microsoft Powerpoint.Show.8'
>      pptOptions.setRootDirectoryClsid(UUID.fromString("64818D10-4F9B-11CF-86EA-00AA00B929E8"));
> 
>      pres.save("pres.ppt", SaveFormat.Ppt, pptOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | java.util.UUID |  |