---
title: IXamlOptions
second_title: Aspose.Slides for Android عبر مرجع API جافا
description: الخيارات التي تتحكم في كيفية حفظ مستند XAML.
type: docs
url: /ar/com.aspose.slides/ixamloptions/
---
**جميع الواجهات المنفذة:**
[com.aspose.slides.ISaveOptions](../../com.aspose.slides/isaveoptions)
```
public interface IXamlOptions extends ISaveOptions
```

الخيارات التي تتحكم في كيفية حفظ مستند XAML.

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
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getExportHiddenSlides()](#getExportHiddenSlides--) | يحدد ما إذا كانت الشرائح المخفية سيتم تصديرها. |
| [setExportHiddenSlides(boolean value)](#setExportHiddenSlides-boolean-) | يحدد ما إذا كانت الشرائح المخفية سيتم تصديرها. |
| [getOutputSaver()](#getOutputSaver--) | يمثل تنفيذًا لواجهة IOutputSaver. |
| [setOutputSaver(IXamlOutputSaver value)](#setOutputSaver-com.aspose.slides.IXamlOutputSaver-) | يمثل تنفيذًا لواجهة IOutputSaver. |
### getExportHiddenSlides() {#getExportHiddenSlides--}
```
public abstract boolean getExportHiddenSlides()
```

يحدد ما إذا كانت الشرائح المخفية سيتم تصديرها.

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

**القيمة المرجعة:**  
boolean
### setExportHiddenSlides(boolean value) {#setExportHiddenSlides-boolean-}
```
public abstract void setExportHiddenSlides(boolean value)
```

يحدد ما إذا كانت الشرائح المخفية سيتم تصديرها.

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

**المعلمات:**
| معاملة | نوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getOutputSaver() {#getOutputSaver--}
```
public abstract IXamlOutputSaver getOutputSaver()
```

يمثل تنفيذًا لواجهة IOutputSaver.

**القيمة المرجعة:**  
[IXamlOutputSaver](../../com.aspose.slides/ixamloutputsaver)
### setOutputSaver(IXamlOutputSaver value) {#setOutputSaver-com.aspose.slides.IXamlOutputSaver-}
```
public abstract void setOutputSaver(IXamlOutputSaver value)
```

يمثل تنفيذًا لواجهة IOutputSaver.

**المعلمات:**
| معاملة | نوع | الوصف |
| --- | --- | --- |
| value | [IXamlOutputSaver](../../com.aspose.slides/ixamloutputsaver) |  |