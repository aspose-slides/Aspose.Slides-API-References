---
title: IImageCollection
second_title: Aspose.Slides สำหรับ Android ผ่านการอ้างอิง API ของ Java
description: แสดงคอลเลกชันของ PPImage.
type: docs
url: /th/com.aspose.slides/iimagecollection/
---
**อินเทอร์เฟซที่นำมาใช้ทั้งหมด:**
com.aspose.slides.IGenericCollection
```
public interface IImageCollection extends IGenericCollection<IPPImage>
```

แสดงคอลเลกชันของ PPImage.
## วิธีการ

| Method | Description |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | คืนค่ารูปภาพตามดัชนีของมัน. |
| [addImage(IImage image)](#addImage-com.aspose.slides.IImage-) | เพิ่มรูปภาพไปยังงานนำเสนอ. |
| [addImage(InputStream stream)](#addImage-java.io.InputStream-) | เพิ่มรูปภาพไปยังงานนำเสนอจากสตรีม. |
| [addImage(InputStream stream, int loadingStreamBehavior)](#addImage-java.io.InputStream-int-) | สร้างและเพิ่มรูปภาพไปยังงานนำเสนอจากสตรีม. |
| [addImage(byte[] buffer)](#addImage-byte---) | เพิ่มรูปภาพไปยังงานนำเสนอจากบัฟเฟอร์ที่ระบุ. |
| [addImage(IPPImage imageSource)](#addImage-com.aspose.slides.IPPImage-) | เพิ่มสำเนารูปภาพจากงานนำเสนออื่น. |
| [addImage(ISvgImage svgImage)](#addImage-com.aspose.slides.ISvgImage-) | เพิ่มรูปภาพไปยังงานนำเสนอจากอ็อบเจกต์ SVG. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IPPImage get_Item(int index)
```

คืนค่ารูปภาพตามดัชนีของมัน.

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | ดัชนี. |

**คืนค่า:**
[IPPImage](../../com.aspose.slides/ippimage) - Image.
### addImage(IImage image) {#addImage-com.aspose.slides.IImage-}
```
public abstract IPPImage addImage(IImage image)
```

เพิ่มรูปภาพไปยังงานนำเสนอ.

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| image | [IImage](../../com.aspose.slides/iimage) | รูปภาพที่ต้องการเพิ่ม.

--------------------

วิธีนี้แปลงไฟล์เมตาไฟล์ WMF/EMF เป็นภาพ PNG แบบแรสเตอร์ก่อนแทรกลงในงานนำเสนอ. |

**คืนค่า:**
[IPPImage](../../com.aspose.slides/ippimage) - เพิ่มรูปภาพ.
### addImage(InputStream stream) {#addImage-java.io.InputStream-}
```
public abstract IPPImage addImage(InputStream stream)
```

เพิ่มรูปภาพไปยังงานนำเสนอจากสตรีม.

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.InputStream | สตรีมที่ใช้เพิ่มรูปภาพจาก.

--------------------

วิธีนี้สามารถเพิ่มไฟล์เมตาไฟล์ WMF/EMF ไปยังงานนำเสนอโดยไม่ต้องแปลงเป็นภาพ PNG แบบแรสเตอร์. |

**คืนค่า:**
[IPPImage](../../com.aspose.slides/ippimage) - เพิ่มรูปภาพ.
### addImage(InputStream stream, int loadingStreamBehavior) {#addImage-java.io.InputStream-int-}
```
public abstract IPPImage addImage(InputStream stream, int loadingStreamBehavior)
```

สร้างและเพิ่มรูปภาพไปยังงานนำเสนอจากสตรีม.

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.InputStream | สตรีมที่ใช้เพิ่มไฟล์รูปภาพจาก. |
| loadingStreamBehavior | int | พฤติกรรมที่ใช้กับสตรีม. |

**คืนค่า:**
[IPPImage](../../com.aspose.slides/ippimage) - เพิ่ม [IPPImage](../../com.aspose.slides/ippimage).
### addImage(byte[] buffer) {#addImage-byte---}
```
public abstract IPPImage addImage(byte[] buffer)
```

เพิ่มรูปภาพไปยังงานนำเสนอจากบัฟเฟอร์ที่ระบุ.

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| buffer | byte[] | บัฟเฟอร์. |

**คืนค่า:**
[IPPImage](../../com.aspose.slides/ippimage) - เพิ่มรูปภาพ.
### addImage(IPPImage imageSource) {#addImage-com.aspose.slides.IPPImage-}
```
public abstract IPPImage addImage(IPPImage imageSource)
```

เพิ่มสำเนารูปภาพจากงานนำเสนออื่น.

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| imageSource | [IPPImage](../../com.aspose.slides/ippimage) | รูปภาพต้นฉบับ. |

**คืนค่า:**
[IPPImage](../../com.aspose.slides/ippimage) - เพิ่มรูปภาพ.
### addImage(ISvgImage svgImage) {#addImage-com.aspose.slides.ISvgImage-}
```
public abstract IPPImage addImage(ISvgImage svgImage)
```

เพิ่มรูปภาพไปยังงานนำเสนอจากอ็อบเจกต์ SVG.

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| svgImage | [ISvgImage](../../com.aspose.slides/isvgimage) | อ็อบเจกต์รูปภาพ SVG [ISvgImage](../../com.aspose.slides/isvgimage) |

**คืนค่า:**
[IPPImage](../../com.aspose.slides/ippimage) - เพิ่มรูปภาพ.