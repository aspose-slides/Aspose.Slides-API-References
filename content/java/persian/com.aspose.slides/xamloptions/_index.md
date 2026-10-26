---
title: XamlOptions
second_title: Aspose.Slides برای مرجع API جاوا
description: گزینه‌هایی که نحوه ذخیره‌سازی سند XAML را کنترل می‌کنند.
type: docs
url: /fa/com.aspose.slides/xamloptions/
---
**وراثت:**
java.lang.Object, [com.aspose.slides.SaveOptions](../../com.aspose.slides/saveoptions)

**تمام رابط‌های پیاده‌سازی شده:**
[com.aspose.slides.IXamlOptions](../../com.aspose.slides/ixamloptions)
```
public class XamlOptions extends SaveOptions implements IXamlOptions
```

گزینه‌هایی که نحوه ذخیره‌سازی سند XAML را کنترل می‌کنند.

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      XamlOptions xamlOptions = new XamlOptions();
>      xamlOptions.setExportHiddenSlides(true);
> 
>      pres.save(xamlOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```
## سازنده‌ها

| سازنده | توضیح |
| --- | --- |
| [XamlOptions()](#XamlOptions--) | یک نمونه XamlOptions ایجاد می‌کند. |
## متدها

| متد | توضیح |
| --- | --- |
| [getExportHiddenSlides()](#getExportHiddenSlides--) | مشخص می‌کند آیا اسلایدهای مخفی صادر شوند یا نه. |
| [setExportHiddenSlides(boolean value)](#setExportHiddenSlides-boolean-) | مشخص می‌کند آیا اسلایدهای مخفی صادر شوند یا نه. |
| [getOutputSaver()](#getOutputSaver--) | نمایانگر یک پیاده‌سازی از رابط IOutputSaver است. |
| [setOutputSaver(IXamlOutputSaver value)](#setOutputSaver-com.aspose.slides.IXamlOutputSaver-) | نمایانگر یک پیاده‌سازی از رابط IOutputSaver است. |
### XamlOptions() {#XamlOptions--}
```
public XamlOptions()
```


یک نمونه XamlOptions ایجاد می‌کند.

### getExportHiddenSlides() {#getExportHiddenSlides--}
```
public final boolean getExportHiddenSlides()
```


مشخص می‌کند آیا اسلایدهای مخفی صادر شوند یا نه.

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      XamlOptions xamlOptions = new XamlOptions();
>      xamlOptions.setExportHiddenSlides(true);
> 
>      pres.save(xamlOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**بازگشت:**
boolean
### setExportHiddenSlides(boolean value) {#setExportHiddenSlides-boolean-}
```
public final void setExportHiddenSlides(boolean value)
```


مشخص می‌کند آیا اسلایدهای مخفی صادر شوند یا نه.

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      XamlOptions xamlOptions = new XamlOptions();
>      xamlOptions.setExportHiddenSlides(true);
> 
>      pres.save(xamlOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### getOutputSaver() {#getOutputSaver--}
```
public final IXamlOutputSaver getOutputSaver()
```


نمایانگر یک پیاده‌سازی از رابط IOutputSaver است.

**بازگشت:**
[IXamlOutputSaver](../../com.aspose.slides/ixamloutputsaver)
### setOutputSaver(IXamlOutputSaver value) {#setOutputSaver-com.aspose.slides.IXamlOutputSaver-}
```
public final void setOutputSaver(IXamlOutputSaver value)
```


نمایانگر یک پیاده‌سازی از رابط IOutputSaver است.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | [IXamlOutputSaver](../../com.aspose.slides/ixamloutputsaver) |  |