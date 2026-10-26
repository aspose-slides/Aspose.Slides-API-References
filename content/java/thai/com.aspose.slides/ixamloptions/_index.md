---
title: IXamlOptions
second_title: Aspose.Slides สำหรับการอ้างอิง API ของ Java
description: ตัวเลือกที่ควบคุมวิธีการบันทึกเอกสาร XAML.
type: docs
url: /th/com.aspose.slides/ixamloptions/
---
**อินเทอร์เฟซที่ทำการ Implement ทั้งหมด:**
[com.aspose.slides.ISaveOptions](../../com.aspose.slides/isaveoptions)
```
public interface IXamlOptions extends ISaveOptions
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
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getExportHiddenSlides()](#getExportHiddenSlides--) | กำหนดว่าจะส่งออกสไลด์ที่ซ่อนอยู่หรือไม่. |
| [setExportHiddenSlides(boolean value)](#setExportHiddenSlides-boolean-) | กำหนดว่าจะส่งออกสไลด์ที่ซ่อนอยู่หรือไม่. |
| [getOutputSaver()](#getOutputSaver--) | เป็นการนำเสนอการดำเนินการของอินเทอร์เฟซ IOutputSaver. |
| [setOutputSaver(IXamlOutputSaver value)](#setOutputSaver-com.aspose.slides.IXamlOutputSaver-) | เป็นการนำเสนอการดำเนินการของอินเทอร์เฟซ IOutputSaver. |
### getExportHiddenSlides() {#getExportHiddenSlides--}
```
public abstract boolean getExportHiddenSlides()
```


กำหนดว่าจะส่งออกสไลด์ที่ซ่อนอยู่หรือไม่.

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
public abstract void setExportHiddenSlides(boolean value)
```


กำหนดว่าจะส่งออกสไลด์ที่ซ่อนอยู่หรือไม่.

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
public abstract IXamlOutputSaver getOutputSaver()
```


เป็นการนำเสนอการดำเนินการของอินเทอร์เฟซ IOutputSaver.

**คืนค่า:**
[IXamlOutputSaver](../../com.aspose.slides/ixamloutputsaver)
### setOutputSaver(IXamlOutputSaver value) {#setOutputSaver-com.aspose.slides.IXamlOutputSaver-}
```
public abstract void setOutputSaver(IXamlOutputSaver value)
```


เป็นการนำเสนอการดำเนินการของอินเทอร์เฟซ IOutputSaver.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | [IXamlOutputSaver](../../com.aspose.slides/ixamloutputsaver) |  |