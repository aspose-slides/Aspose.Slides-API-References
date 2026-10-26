---
title: XamlOptions
second_title: Aspose.Slides برای اندروید از طریق مرجع API جاوا
description: گزینه‌هایی که نحوه ذخیره یک سند XAML را کنترل می‌کنند.
type: docs
url: /fa/com.aspose.slides/xamloptions/
---
**ارث‌بری:**
java.lang.Object, [com.aspose.slides.SaveOptions](../../com.aspose.slides/saveoptions)

**تمام رابط‌های پیاده‌سازی‌شده:**
[com.aspose.slides.IXamlOptions](../../com.aspose.slides/ixamloptions)
```
public class XamlOptions extends SaveOptions implements IXamlOptions
```

گزینه‌هایی که نحوه ذخیره یک سند XAML را کنترل می‌کنند.

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
| [XamlOptions()](#XamlOptions--) | یک نمونه از XamlOptions را ایجاد می‌کند. |
## متدها

| متد | توضیح |
| --- | --- |
| [getExportHiddenSlides()](#getExportHiddenSlides--) | تعیین می‌کند آیا اسلایدهای مخفی صادر شوند یا نه. |
| [setExportHiddenSlides(boolean value)](#setExportHiddenSlides-boolean-) | تعیین می‌کند آیا اسلایدهای مخفی صادر شوند یا نه. |
| [getOutputSaver()](#getOutputSaver--) | نمایانگر پیاده‌سازی رابط IOutputSaver است. |
| [setOutputSaver(IXamlOutputSaver value)](#setOutputSaver-com.aspose.slides.IXamlOutputSaver-) | نمایانگر پیاده‌سازی رابط IOutputSaver است. |
### XamlOptions() {#XamlOptions--}
```
public XamlOptions()
```


یک نمونه از XamlOptions را ایجاد می‌کند.

### getExportHiddenSlides() {#getExportHiddenSlides--}
```
public final boolean getExportHiddenSlides()
```


تعیین می‌کند آیا اسلایدهای مخفی صادر شوند یا نه.

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


تعیین می‌کند آیا اسلایدهای مخفی صادر شوند یا نه.

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


نمایانگر پیاده‌سازی رابط IOutputSaver است.

**بازگشت:**
[IXamlOutputSaver](../../com.aspose.slides/ixamloutputsaver)
### setOutputSaver(IXamlOutputSaver value) {#setOutputSaver-com.aspose.slides.IXamlOutputSaver-}
```
public final void setOutputSaver(IXamlOutputSaver value)
```


نمایانگر پیاده‌سازی رابط IOutputSaver است.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | [IXamlOutputSaver](../../com.aspose.slides/ixamloutputsaver) |  |