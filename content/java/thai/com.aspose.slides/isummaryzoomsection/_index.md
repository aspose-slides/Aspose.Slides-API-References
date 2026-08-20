---
title: ISummaryZoomSection
second_title: Aspose.Slides สำหรับ Java API Reference
description: เป็นอ็อบเจ็กต์ Summary Zoom Section ในกรอบ Summary Zoom
type: docs
url: /th/com.aspose.slides/isummaryzoomsection/
---
**อินเทอร์เฟซที่ทำทั้งหมด:**
[com.aspose.slides.ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe)
```
public interface ISummaryZoomSection extends ISectionZoomFrame
```

เป็นอ็อบเจ็กต์ Summary Zoom Section ในกรอบ Summary Zoom
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getTitle()](#getTitle--) | คืนค่าส่วนหัวข้อความของอ็อบเจ็กต์ Summary Zoom Section |
| [setTitle(String value)](#setTitle-java.lang.String-) | คืนค่าส่วนหัวข้อความของอ็อบเจ็กต์ Summary Zoom Section |
| [getDescription()](#getDescription--) | คืนค่าคำอธิบายข้อความของอ็อบเจ็กต์ Summary Zoom Section |
| [setDescription(String value)](#setDescription-java.lang.String-) | คืนค่าคำอธิบายข้อความของอ็อบเจ็กต์ Summary Zoom Section |
### getTitle() {#getTitle--}
```
public abstract String getTitle()
```


คืนค่าส่วนหัวข้อความของอ็อบเจ็กต์ Summary Zoom Section

--------------------

> ```
> Example:
>  
>  ISummaryZoomSection zoomSection = zoomFrame.getSummaryZoomCollection().get_Item(1);
>  zoomSection.setTitle("Title");
>  ```

**คืนค่า:**
java.lang.String
### setTitle(String value) {#setTitle-java.lang.String-}
```
public abstract void setTitle(String value)
```


คืนค่าส่วนหัวข้อความของอ็อบเจ็กต์ Summary Zoom Section

--------------------

> ```
> Example:
>  
>  ISummaryZoomSection zoomSection = zoomFrame.getSummaryZoomCollection().get_Item(1);
>  zoomSection.setTitle("Title");
>  ```

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | java.lang.String |  |

### getDescription() {#getDescription--}
```
public abstract String getDescription()
```


คืนค่าคำอธิบายข้อความของอ็อบเจ็กต์ Summary Zoom Section

--------------------

> ```
> Example:
>  
>  ISummaryZoomSection zoomSection = zoomFrame.getSummaryZoomCollection().get_Item(1);
>  zoomSection.setDescription("Description");
> ```

**คืนค่า:**
java.lang.String
### setDescription(String value) {#setDescription-java.lang.String-}
```
public abstract void setDescription(String value)
```


คืนค่าคำอธิบายข้อความของอ็อบเจ็กต์ Summary Zoom Section

--------------------

> ```
> Example:
>  
>  ISummaryZoomSection zoomSection = zoomFrame.getSummaryZoomCollection().get_Item(1);
>  zoomSection.setDescription("Description");
> ```

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | java.lang.String |  |