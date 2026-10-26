---
title: IXamlOptions
second_title: Aspose.Slides برای Android از طریق مرجع API جاوا
description: گزینه‌هایی که نحوه ذخیره یک سند XAML را کنترل می‌کنند.
type: docs
url: /fa/com.aspose.slides/ixamloptions/
---
**تمام رابط‌های پیاده‌سازی‌شده:**
[com.aspose.slides.ISaveOptions](../../com.aspose.slides/isaveoptions)
```
public interface IXamlOptions extends ISaveOptions
```

گزینه‌هایی که نحوه ذخیره سند XAML را کنترل می‌کنند.

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
## متدها

| متد | توضیح |
| --- | --- |
| [getExportHiddenSlides()](#getExportHiddenSlides--) | مشخص می‌کند که آیا اسلایدهای مخفی صادر شوند یا خیر. |
| [setExportHiddenSlides(boolean value)](#setExportHiddenSlides-boolean-) | مشخص می‌کند که آیا اسلایدهای مخفی صادر شوند یا خیر. |
| [getOutputSaver()](#getOutputSaver--) | نمایانگر یک پیاده‌سازی از رابط IOutputSaver. |
| [setOutputSaver(IXamlOutputSaver value)](#setOutputSaver-com.aspose.slides.IXamlOutputSaver-) | نمایانگر یک پیاده‌سازی از رابط IOutputSaver. |
### getExportHiddenSlides() {#getExportHiddenSlides--}
```
public abstract boolean getExportHiddenSlides()
```


مشخص می‌کند که آیا اسلایدهای مخفی صادر شوند یا خیر.

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

**باز می‌گردد:**
boolean
### setExportHiddenSlides(boolean value) {#setExportHiddenSlides-boolean-}
```
public abstract void setExportHiddenSlides(boolean value)
```


مشخص می‌کند که آیا اسلایدهای مخفی صادر شوند یا خیر.

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
public abstract IXamlOutputSaver getOutputSaver()
```


نمایانگر یک پیاده‌سازی از رابط IOutputSaver.

**باز می‌گردد:**
[IXamlOutputSaver](../../com.aspose.slides/ixamloutputsaver)
### setOutputSaver(IXamlOutputSaver value) {#setOutputSaver-com.aspose.slides.IXamlOutputSaver-}
```
public abstract void setOutputSaver(IXamlOutputSaver value)
```


نمایانگر یک پیاده‌سازی از رابط IOutputSaver.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | [IXamlOutputSaver](../../com.aspose.slides/ixamloutputsaver) |  |