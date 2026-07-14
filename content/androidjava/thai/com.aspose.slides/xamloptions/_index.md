---
title: XamlOptions
second_title: Aspose.Slides สำหรับ Android ผ่านอ้างอิง API Java
description: ตัวเลือกที่ควบคุมวิธีการบันทึกเอกสาร XAML
type: docs
url: /th/com.aspose.slides/xamloptions/
---
**การสืบทอด:**
java.lang.Object, [com.aspose.slides.SaveOptions](../../com.aspose.slides/saveoptions)

**ทุกอินเทอร์เฟซที่ทำการใช้งาน:**
[com.aspose.slides.IXamlOptions](../../com.aspose.slides/ixamloptions)
```
public class XamlOptions extends SaveOptions implements IXamlOptions
```

ตัวเลือกที่ควบคุมวิธีการบันทึกเอกสาร XAML.

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
| [getExportHiddenSlides()](#getExportHiddenSlides--) | กำหนดว่าจะส่งออกสไลด์ที่ซ่อนหรือไม่ |
| [setExportHiddenSlides(boolean value)](#setExportHiddenSlides-boolean-) | กำหนดว่าจะส่งออกสไลด์ที่ซ่อนหรือไม่ |
| [getOutputSaver()](#getOutputSaver--) | แทนการทำงานของอินเทอร์เฟซ IOutputSaver |
| [setOutputSaver(IXamlOutputSaver value)](#setOutputSaver-com.aspose.slides.IXamlOutputSaver-) | แทนการทำงานของอินเทอร์เฟซ IOutputSaver |
### XamlOptions() {#XamlOptions--}
```
public XamlOptions()
```


สร้างอินสแตนซ์ของ XamlOptions

### getExportHiddenSlides() {#getExportHiddenSlides--}
```
public final boolean getExportHiddenSlides()
```


กำหนดว่าจะส่งออกสไลด์ที่ซ่อนหรือไม่

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

**ผลลัพธ์:**
boolean
### setExportHiddenSlides(boolean value) {#setExportHiddenSlides-boolean-}
```
public final void setExportHiddenSlides(boolean value)
```


กำหนดว่าจะส่งออกสไลด์ที่ซ่อนหรือไม่

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


แทนการทำงานของอินเทอร์เฟซ IOutputSaver

**ผลลัพธ์:**
[IXamlOutputSaver](../../com.aspose.slides/ixamloutputsaver)
### setOutputSaver(IXamlOutputSaver value) {#setOutputSaver-com.aspose.slides.IXamlOutputSaver-}
```
public final void setOutputSaver(IXamlOutputSaver value)
```


แทนการทำงานของอินเทอร์เฟซ IOutputSaver

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | [IXamlOutputSaver](../../com.aspose.slides/ixamloutputsaver) |  |