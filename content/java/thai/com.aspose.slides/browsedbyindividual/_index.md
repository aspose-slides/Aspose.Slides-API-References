---
title: BrowsedByIndividual
second_title: เอกสารอ้างอิง API ของ Aspose.Slides สำหรับ Java
description: หน้าต่างการเรียกดูโดยบุคคล
type: docs
url: /th/com.aspose.slides/browsedbyindividual/
---
**การสืบทอด:**
java.lang.Object, [com.aspose.slides.SlideShowType](../../com.aspose.slides/slideshowtype)
```
public class BrowsedByIndividual extends SlideShowType
```

เรียกดูโดยบุคคล (หน้าต่าง)

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      pres.getSlideShowSettings().setSlideShowType(new BrowsedByIndividual());
>      pres.save("pres.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```
## ตัวสร้าง

| คอนสตรัคเตอร์ | คำอธิบาย |
| --- | --- |
| [BrowsedByIndividual()](#BrowsedByIndividual--) | สร้างอินสแตนซ์ใหม่ของคลาส BrowsedByIndividual |
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getShowScrollbar()](#getShowScrollbar--) | แสดงแถบเลื่อนในหน้าต่าง |
| [setShowScrollbar(boolean value)](#setShowScrollbar-boolean-) | แสดงแถบเลื่อนในหน้าต่าง |
### BrowsedByIndividual() {#BrowsedByIndividual--}
```
public BrowsedByIndividual()
```


สร้างอินสแตนซ์ใหม่ของคลาส BrowsedByIndividual

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      pres.getSlideShowSettings().setSlideShowType(new BrowsedByIndividual());
>      pres.save("pres.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

### getShowScrollbar() {#getShowScrollbar--}
```
public final boolean getShowScrollbar()
```


แสดงแถบเลื่อนในหน้าต่าง

**คืนค่า:**
boolean
### setShowScrollbar(boolean value) {#setShowScrollbar-boolean-}
```
public final void setShowScrollbar(boolean value)
```


แสดงแถบเลื่อนในหน้าต่าง

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |