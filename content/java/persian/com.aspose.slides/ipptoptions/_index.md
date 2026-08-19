---
title: IPptOptions
second_title: مرجع API Aspose.Slides برای Java
description: گزینه‌هایی را فراهم می‌کند که نحوه ذخیره‌ی یک ارائه در فرمت PPT را کنترل می‌کند.
type: docs
url: /fa/com.aspose.slides/ipptoptions/
---
**تمام رابط‌های پیاده‌سازی‌شده:**
[com.aspose.slides.ISaveOptions](../../com.aspose.slides/isaveoptions)
```
public interface IPptOptions extends ISaveOptions
```

گزینه‌هایی را فراهم می‌کند که کنترل می‌کند یک ارائه چگونه در فرمیت PPT ذخیره شود.
## متدها

| متد | توضیح |
| --- | --- |
| [getRootDirectoryClsid()](#getRootDirectoryClsid--) | نمایانگر GUID کلاس شی (CLSID) است که در ورودی دایرکتوری ریشه ذخیره شده است. |
| [setRootDirectoryClsid(UUID value)](#setRootDirectoryClsid-java.util.UUID-) | نمایانگر GUID کلاس شی (CLSID) است که در ورودی دایرکتوری ریشه ذخیره شده است. |
### getRootDirectoryClsid() {#getRootDirectoryClsid--}
```
public abstract UUID getRootDirectoryClsid()
```

نمایانگر GUID کلاس شی (CLSID) است که در ورودی دایرکتوری ریشه ذخیره شده است. می‌تواند برای فعال‌سازی COM برنامه سند استفاده شود. مقدار پیش‌فرض '64818D11-4F9B-11CF-86EA-00AA00B929E8' است که متناظر با 'Microsoft Powerpoint.Slide.8' می‌باشد.

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


**بازگشت:**
java.util.UUID
### setRootDirectoryClsid(UUID value) {#setRootDirectoryClsid-java.util.UUID-}
```
public abstract void setRootDirectoryClsid(UUID value)
```

نمایانگر GUID کلاس شی (CLSID) است که در ورودی دایرکتوری ریشه ذخیره شده است. می‌تواند برای فعال‌سازی COM برنامه سند استفاده شود. مقدار پیش‌فرض '64818D11-4F9B-11CF-86EA-00AA00B929E8' است که متناظر با 'Microsoft Powerpoint.Slide.8' می‌باشد.

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