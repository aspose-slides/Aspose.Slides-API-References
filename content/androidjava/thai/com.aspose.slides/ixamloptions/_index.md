---
title: IXamlOptions
second_title: Aspose.Slides สำหรับ Android ผ่านการอ้างอิง API ของ Java
description: ตัวเลือกที่ควบคุมวิธีการบันทึกเอกสาร XAML.
type: docs
url: /th/com.aspose.slides/ixamloptions/
---
**อินเทอร์เฟซที่นำไปใช้ทั้งหมด:**
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

| เมธอด | รายละเอียด |
| --- | --- |
| [getExportHiddenSlides()](#getExportHiddenSlides--) | กำหนดว่าสไลด์ที่ซ่อนจะถูกส่งออกหรือไม่. |
| [setExportHiddenSlides(boolean value)](#setExportHiddenSlides-boolean-) | กำหนดว่าสไลด์ที่ซ่อนจะถูกส่งออกหรือไม่. |
| [getOutputSaver()](#getOutputSaver--) | แสดงการนำไปใช้ของ IOutputSaver อินเทอร์เฟซ. |
| [setOutputSaver(IXamlOutputSaver value)](#setOutputSaver-com.aspose.slides.IXamlOutputSaver-) | แสดงการนำไปใช้ของ IOutputSaver อินเทอร์เฟซ. |
### getExportHiddenSlides() {#getExportHiddenSlides--}
```
public abstract boolean getExportHiddenSlides()
```

กำหนดว่าสไลด์ที่ซ่อนจะถูกส่งออกหรือไม่.

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

กำหนดว่าสไลด์ที่ซ่อนจะถูกส่งออกหรือไม่.

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
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getOutputSaver() {#getOutputSaver--}
```
public abstract IXamlOutputSaver getOutputSaver()
```

แสดงการนำไปใช้ของ IOutputSaver อินเทอร์เฟซ.

**คืนค่า:**
[IXamlOutputSaver](../../com.aspose.slides/ixamloutputsaver)
### setOutputSaver(IXamlOutputSaver value) {#setOutputSaver-com.aspose.slides.IXamlOutputSaver-}
```
public abstract void setOutputSaver(IXamlOutputSaver value)
```

แสดงการนำไปใช้ของ IOutputSaver อินเทอร์เฟซ.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | [IXamlOutputSaver](../../com.aspose.slides/ixamloutputsaver) |  |