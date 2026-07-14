---
title: XamlOptions
second_title: Aspose.Slides لأنظمة Android عبر مرجع API Java
description: الخيارات التي تتحكم في كيفية حفظ مستند XAML.
type: docs
url: /ar/com.aspose.slides/xamloptions/
---
**الوراثة:**
java.lang.Object, [com.aspose.slides.SaveOptions](../../com.aspose.slides/saveoptions)

**جميع الواجهات المنفذة:**
[com.aspose.slides.IXamlOptions](../../com.aspose.slides/ixamloptions)
```
public class XamlOptions extends SaveOptions implements IXamlOptions
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
## المُنشئات

| المُنشئ | الوصف |
| --- | --- |
| [XamlOptions()](#XamlOptions--) | ينشئ مثيل XamlOptions. |
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getExportHiddenSlides()](#getExportHiddenSlides--) | يحدد ما إذا كانت الشرائح المخفية ستُصدَّر. |
| [setExportHiddenSlides(boolean value)](#setExportHiddenSlides-boolean-) | يحدد ما إذا كانت الشرائح المخفية ستُصدَّر. |
| [getOutputSaver()](#getOutputSaver--) | يمثل تنفيذًا لواجهة IOutputSaver. |
| [setOutputSaver(IXamlOutputSaver value)](#setOutputSaver-com.aspose.slides.IXamlOutputSaver-) | يمثل تنفيذًا لواجهة IOutputSaver. |
### XamlOptions() {#XamlOptions--}
```
public XamlOptions()
```

ينشئ مثيل XamlOptions.

### getExportHiddenSlides() {#getExportHiddenSlides--}
```
public final boolean getExportHiddenSlides()
```

يحدد ما إذا كانت الشرائح المخفية ستُصدَّر.

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
public final void setExportHiddenSlides(boolean value)
```

يحدد ما إذا كانت الشرائح المخفية ستُصدَّر.

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
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getOutputSaver() {#getOutputSaver--}
```
public final IXamlOutputSaver getOutputSaver()
```

يمثل تنفيذًا لواجهة IOutputSaver.

**القيمة المرجعة:**
[IXamlOutputSaver](../../com.aspose.slides/ixamloutputsaver)
### setOutputSaver(IXamlOutputSaver value) {#setOutputSaver-com.aspose.slides.IXamlOutputSaver-}
```
public final void setOutputSaver(IXamlOutputSaver value)
```

يمثل تنفيذًا لواجهة IOutputSaver.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | [IXamlOutputSaver](../../com.aspose.slides/ixamloutputsaver) |  |