---
title: ISummaryZoomSection
second_title: Aspose.Slides สำหรับ Android ผ่านการอ้างอิง API ของ Java
description: เป็นอ็อบเจ็กต์ Summary Zoom Section ในกรอบ Summary Zoom
type: docs
url: /th/com.aspose.slides/isummaryzoomsection/
---
**ทุกอินเทอร์เฟซที่นำไปใช้:**
[com.aspose.slides.ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe)
```
public interface ISummaryZoomSection extends ISectionZoomFrame
```

เป็นอ็อบเจ็กต์ Summary Zoom Section ในกรอบ Summary Zoom
## เมธอด

| Method | Description |
| --- | --- |
| [getTitle()](#getTitle--) | ส่งคืนชื่อข้อความของอ็อบเจ็กต์ Summary Zoom Section |
| [setTitle(String value)](#setTitle-java.lang.String-) | ส่งคืนชื่อข้อความของอ็อบเจ็กต์ Summary Zoom Section |
| [getDescription()](#getDescription--) | ส่งคืนคำอธิบายข้อความของอ็อบเจ็กต์ Summary Zoom Section |
| [setDescription(String value)](#setDescription-java.lang.String-) | ส่งคืนคำอธิบายข้อความของอ็อบเจ็กต์ Summary Zoom Section |
### getTitle() {#getTitle--}
```
public abstract String getTitle()
```

ส่งคืนชื่อข้อความของอ็อบเจ็กต์ Summary Zoom Section

--------------------

> ```
> Example:
>  
>  ISummaryZoomSection zoomSection = zoomFrame.getSummaryZoomCollection().get_Item(1);
>  zoomSection.setTitle("Title");
> ```

**คืนค่า:**
java.lang.String
### setTitle(String value) {#setTitle-java.lang.String-}
```
public abstract void setTitle(String value)
```

ส่งคืนชื่อข้อความของอ็อบเจ็กต์ Summary Zoom Section

--------------------

> ```
> Example:
>  
>  ISummaryZoomSection zoomSection = zoomFrame.getSummaryZoomCollection().get_Item(1);
>  zoomSection.setTitle("Title");
> ```

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |
### getDescription() {#getDescription--}
```
public abstract String getDescription()
```

ส่งคืนคำอธิบายข้อความของอ็อบเจ็กต์ Summary Zoom Section

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

ส่งคืนคำอธิบายข้อความของอ็อบเจ็กต์ Summary Zoom Section

--------------------

> ```
> Example:
>  
>  ISummaryZoomSection zoomSection = zoomFrame.getSummaryZoomCollection().get_Item(1);
>  zoomSection.setDescription("Description");
> ```

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |