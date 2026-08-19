---
title: IXamlOptions
second_title: مرجع API Aspose.Slides برای Java
description: گزینه‌هایی که نحوه ذخیره‌سازی یک سند XAML را کنترل می‌کنند.
type: docs
url: /fa/com.aspose.slides/ixamloptions/
---
**تمام رابط‌های پیاده‌سازی‌شده:**
[com.aspose.slides.ISaveOptions](../../com.aspose.slides/isaveoptions)
```
public interface IXamlOptions extends ISaveOptions
```

گزینه‌هایی که نحوه ذخیره‌سازی یک سند XAML را کنترل می‌کنند.

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
| [getExportHiddenSlides()](#getExportHiddenSlides--) | تعیین می‌کند آیا اسلایدهای مخفی صادر شوند یا نه. |
| [setExportHiddenSlides(boolean value)](#setExportHiddenSlides-boolean-) | تعیین می‌کند آیا اسلایدهای مخفی صادر شوند یا نه. |
| [getOutputSaver()](#getOutputSaver--) | نمایانگر پیاده‌سازی رابط IOutputSaver است. |
| [setOutputSaver(IXamlOutputSaver value)](#setOutputSaver-com.aspose.slides.IXamlOutputSaver-) | نمایانگر پیاده‌سازی رابط IOutputSaver است. |
### getExportHiddenSlides() {#getExportHiddenSlides--}
```
public abstract boolean getExportHiddenSlides()
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
public abstract void setExportHiddenSlides(boolean value)
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
public abstract IXamlOutputSaver getOutputSaver()
```


نمایانگر پیاده‌سازی رابط IOutputSaver است.

**بازگشت:**  
[IXamlOutputSaver](../../com.aspose.slides/ixamloutputsaver)
### setOutputSaver(IXamlOutputSaver value) {#setOutputSaver-com.aspose.slides.IXamlOutputSaver-}
```
public abstract void setOutputSaver(IXamlOutputSaver value)
```


نمایانگر پیاده‌سازی رابط IOutputSaver است.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | [IXamlOutputSaver](../../com.aspose.slides/ixamloutputsaver) |  |