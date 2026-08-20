---
title: XamlOptions
second_title: Aspose.Slides สำหรับ Java API Reference
description: ตัวเลือกที่ควบคุมวิธีการบันทึกเอกสาร XAML.
type: docs
url: /th/com.aspose.slides/xamloptions/
---
**สืบทอด:**
java.lang.Object, [com.aspose.slides.SaveOptions](../../com.aspose.slides/saveoptions)

**อินเทอร์เฟซที่นำไปใช้ทั้งหมด:**
[com.aspose.slides.IXamlOptions](../../com.aspose.slides/ixamloptions)
```
public class XamlOptions extends SaveOptions implements IXamlOptions
```

ตัวเลือกที่ควบคุมวิธีการบันทึกเอกสาร XAML

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
## คอนสตรัคเตอร์

| คอนสตรัคเตอร์ | คำอธิบาย |
| --- | --- |
| [XamlOptions()](#XamlOptions--) | สร้างอินสแตนซ์ของ XamlOptions |
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getExportHiddenSlides()](#getExportHiddenSlides--) | กำหนดว่าการนำเสนอที่ซ่อนไว้จะถูกส่งออกหรือไม่ |
| [setExportHiddenSlides(boolean value)](#setExportHiddenSlides-boolean-) | กำหนดว่าการนำเสนอที่ซ่อนไว้จะถูกส่งออกหรือไม่ |
| [getOutputSaver()](#getOutputSaver--) | แสดงถึงการนำไปใช้ของอินเทอร์เฟซ IOutputSaver |
| [setOutputSaver(IXamlOutputSaver value)](#setOutputSaver-com.aspose.slides.IXamlOutputSaver-) | แสดงถึงการนำไปใช้ของอินเทอร์เฟซ IOutputSaver |
### XamlOptions() {#XamlOptions--}
```
public XamlOptions()
```

สร้างอินสแตนซ์ของ XamlOptions

### getExportHiddenSlides() {#getExportHiddenSlides--}
```
public final boolean getExportHiddenSlides()
```

กำหนดว่าการนำเสนอที่ซ่อนไว้จะถูกส่งออกหรือไม่

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


**คืนค่า:**
boolean
### setExportHiddenSlides(boolean value) {#setExportHiddenSlides-boolean-}
```
public final void setExportHiddenSlides(boolean value)
```

กำหนดว่าการนำเสนอที่ซ่อนไว้จะถูกส่งออกหรือไม่

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

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getOutputSaver() {#getOutputSaver--}
```
public final IXamlOutputSaver getOutputSaver()
```

แสดงถึงการนำไปใช้ของอินเทอร์เฟซ IOutputSaver

**คืนค่า:**
[IXamlOutputSaver](../../com.aspose.slides/ixamloutputsaver)
### setOutputSaver(IXamlOutputSaver value) {#setOutputSaver-com.aspose.slides.IXamlOutputSaver-}
```
public final void setOutputSaver(IXamlOutputSaver value)
```

แสดงถึงการนำไปใช้ของอินเทอร์เฟซ IOutputSaver

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | [IXamlOutputSaver](../../com.aspose.slides/ixamloutputsaver) |  |