---
title: BrowsedByIndividual
second_title: Aspose.Slides สำหรับ Android ผ่านการอ้างอิง API ของ Java
description: หน้าต่างการเรียกดูตามบุคคล
type: docs
url: /th/com.aspose.slides/browsedbyindividual/
---
**การสืบทอด:**
java.lang.Object, [com.aspose.slides.SlideShowType](../../com.aspose.slides/slideshowtype)
```
public class BrowsedByIndividual extends SlideShowType
```

การเรียกดูโดยบุคคล (หน้าต่าง)

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
## คอนสตรัคเตอร์

| คอนสตรัคเตอร์ | คำอธิบาย |
| --- | --- |
| [BrowsedByIndividual()](#BrowsedByIndividual--) | เริ่มต้นอินสแตนซ์ใหม่ของคลาส BrowsedByIndividual |
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getShowScrollbar()](#getShowScrollbar--) | แสดงแถบเลื่อนในหน้าต่าง |
| [setShowScrollbar(boolean value)](#setShowScrollbar-boolean-) | แสดงแถบเลื่อนในหน้าต่าง |
### BrowsedByIndividual() {#BrowsedByIndividual--}
```
public BrowsedByIndividual()
```


เริ่มต้นอินสแตนซ์ใหม่ของคลาส BrowsedByIndividual

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

**ส่งคืน:**
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