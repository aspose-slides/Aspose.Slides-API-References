---
title: PptOptions
second_title: Aspose.Slides برای Android از طریق مرجع API جاوا
description: گزینه‌هایی را فراهم می‌کند که نحوه ذخیره‌سازی ارائه در قالب PPT را کنترل می‌کند.
type: docs
url: /fa/com.aspose.slides/pptoptions/
---
**ارث‌بری:**
java.lang.Object, [com.aspose.slides.SaveOptions](../../com.aspose.slides/saveoptions)

**تمام رابط‌های پیاده‌سازی شده:**
[com.aspose.slides.IPptOptions](../../com.aspose.slides/ipptoptions), java.lang.Cloneable
```
public class PptOptions extends SaveOptions implements IPptOptions, Cloneable
```

گزینه‌هایی را فراهم می‌کند که نحوه ذخیره‌سازی ارائه در قالب PPT را کنترل می‌کنند.
## سازنده‌ها

| سازنده | توضیح |
| --- | --- |
| [PptOptions()](#PptOptions--) |  |
## متدها

| متد | توضیح |
| --- | --- |
| [getRootDirectoryClsid()](#getRootDirectoryClsid--) | نماینده GUID کلاس شیء (CLSID) است که در ورودی ریشه دایرکتوری ذخیره شده است. |
| [setRootDirectoryClsid(UUID value)](#setRootDirectoryClsid-java.util.UUID-) | نماینده GUID کلاس شیء (CLSID) است که در ورودی ریشه دایرکتوری ذخیره شده است. |
### PptOptions() {#PptOptions--}
```
public PptOptions()
```

### getRootDirectoryClsid() {#getRootDirectoryClsid--}
```
public final UUID getRootDirectoryClsid()
```

نماینده GUID کلاس شیء (CLSID) است که در ورودی ریشه دایرکتوری ذخیره شده است. می‌تواند برای فعال‌سازی COM برنامه سند استفاده شود. مقدار پیش‌فرض '64818D11-4F9B-11CF-86EA-00AA00B929E8' است که به 'Microsoft Powerpoint.Slide.8' مربوط می‌شود.

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      PptOptions pptOptions = new PptOptions();
> 
>      /// CLSID را به 'Microsoft Powerpoint.Show.8' تنظیم کنید
>      pptOptions.setRootDirectoryClsid(UUID.fromString("64818D10-4F9B-11CF-86EA-00AA00B929E8"));
> 
>      pres.save("pres.ppt", SaveFormat.Ppt, pptOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
```

**بازگشت:**
java.util.UUID
### setRootDirectoryClsid(UUID value) {#setRootDirectoryClsid-java.util.UUID-}
```
public final void setRootDirectoryClsid(UUID value)
```

نماینده GUID کلاس شیء (CLSID) است که در ورودی ریشه دایرکتوری ذخیره شده است. می‌تواند برای فعال‌سازی COM برنامه سند استفاده شود. مقدار پیش‌فرض '64818D11-4F9B-11CF-86EA-00AA00B929E8' است که به 'Microsoft Powerpoint.Slide.8' مربوط می‌شود.

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      PptOptions pptOptions = new PptOptions();
> 
>      /// CLSID را به 'Microsoft Powerpoint.Show.8' تنظیم کنید
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