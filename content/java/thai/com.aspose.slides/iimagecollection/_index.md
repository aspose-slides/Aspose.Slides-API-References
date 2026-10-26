---
title: IImageCollection
second_title: Aspose.Slides สำหรับ Java API Reference
description: แสดงถึงคอลเลกชันของ PPImage.
type: docs
url: /th/com.aspose.slides/iimagecollection/
---
**อินเทอร์เฟซที่ทำการ Implement ทั้งหมด:**
com.aspose.slides.IGenericCollection
```
public interface IImageCollection extends IGenericCollection<IPPImage>
```

เป็นการแสดงถึงคอลเลกชันของ PPImage.
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | ส่งคืนภาพตามดัชนีของมัน. |
| [addImage(IImage image)](#addImage-com.aspose.slides.IImage-) | เพิ่มรูปภาพเข้าไปในงานนำเสนอ. |
| [addImage(InputStream stream)](#addImage-java.io.InputStream-) | เพิ่มรูปภาพเข้าไปในงานนำเสนอจากสตรีม. |
| [addImage(InputStream stream, int loadingStreamBehavior)](#addImage-java.io.InputStream-int-) | สร้างและเพิ่มรูปภาพเข้าไปในงานนำเสนอจากสตรีม. |
| [addImage(byte[] buffer)](#addImage-byte---) | เพิ่มรูปภาพเข้าไปในงานนำเสนอจากบัฟเฟอร์ที่ระบุ. |
| [addImage(IPPImage imageSource)](#addImage-com.aspose.slides.IPPImage-) | เพิ่มสำเนาภาพจากงานนำเสนออื่น. |
| [addImage(ISvgImage svgImage)](#addImage-com.aspose.slides.ISvgImage-) | เพิ่มรูปภาพเข้าไปในงานนำเสนอจากออบเจ็กต์ SVG. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IPPImage get_Item(int index)
```

ส่งคืนภาพตามดัชนีของมัน.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| index | int | ดัชนี. |

**คืนค่า:**
[IPPImage](../../com.aspose.slides/ippimage) - Image.
### addImage(IImage image) {#addImage-com.aspose.slides.IImage-}
```
public abstract IPPImage addImage(IImage image)
```

เพิ่มรูปภาพเข้าไปในงานนำเสนอ.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| image | [IImage](../../com.aspose.slides/iimage) | ภาพที่ต้องการเพิ่ม.

--------------------

เมธอดนี้แปลงไฟล์เมต้าไฟล์ WMF/EMF เป็นภาพ PNG แบบแรสเตอร์ก่อนแทรกเข้าไปในงานนำเสนอ. |

**คืนค่า:**
[IPPImage](../../com.aspose.slides/ippimage) - Added image.
### addImage(InputStream stream) {#addImage-java.io.InputStream-}
```
public abstract IPPImage addImage(InputStream stream)
```

เพิ่มรูปภาพเข้าไปในงานนำเสนอจากสตรีม.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| stream | java.io.InputStream | สตรีมที่ใช้เพิ่มรูปภาพจาก.

--------------------

เมธอดนี้สามารถเพิ่มไฟล์เมต้าไฟล์ WMF/EMF ไปยังงานนำเสนอโดยไม่ต้องแปลงเป็นภาพ PNG แบบแรสเตอร์. |

**คืนค่า:**
[IPPImage](../../com.aspose.slides/ippimage) - Added image.
### addImage(InputStream stream, int loadingStreamBehavior) {#addImage-java.io.InputStream-int-}
```
public abstract IPPImage addImage(InputStream stream, int loadingStreamBehavior)
```

สร้างและเพิ่มรูปภาพเข้าไปในงานนำเสนอจากสตรีม.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| stream | java.io.InputStream | สตรีมที่ใช้เพิ่มไฟล์รูปภาพจาก. |
| loadingStreamBehavior | int | พฤติกรรมที่ใช้กับสตรีม. |

**คืนค่า:**
[IPPImage](../../com.aspose.slides/ippimage) - Added [IPPImage](../../com.aspose.slides/ippimage).
### addImage(byte[] buffer) {#addImage-byte---}
```
public abstract IPPImage addImage(byte[] buffer)
```

เพิ่มรูปภาพเข้าไปในงานนำเสนอจากบัฟเฟอร์ที่ระบุ.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| buffer | byte[] | บัฟเฟอร์. |

**คืนค่า:**
[IPPImage](../../com.aspose.slides/ippimage) - Added image.
### addImage(IPPImage imageSource) {#addImage-com.aspose.slides.IPPImage-}
```
public abstract IPPImage addImage(IPPImage imageSource)
```

เพิ่มสำเนาภาพจากงานนำเสนออื่น.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| imageSource | [IPPImage](../../com.aspose.slides/ippimage) | แหล่งรูปภาพ. |

**คืนค่า:**
[IPPImage](../../com.aspose.slides/ippimage) - Added image.
### addImage(ISvgImage svgImage) {#addImage-com.aspose.slides.ISvgImage-}
```
public abstract IPPImage addImage(ISvgImage svgImage)
```

เพิ่มรูปภาพเข้าไปในงานนำเสนอจากออบเจ็กต์ SVG.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| svgImage | [ISvgImage](../../com.aspose.slides/isvgimage) | ออบเจ็กต์ภาพ SVG [ISvgImage](../../com.aspose.slides/isvgimage) |

**คืนค่า:**
[IPPImage](../../com.aspose.slides/ippimage) - Added image.