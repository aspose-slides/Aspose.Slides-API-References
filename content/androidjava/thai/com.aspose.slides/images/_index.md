---
title: Images
second_title: Aspose.Slides สำหรับ Android ผ่าน Java API Reference
description: เมธอดสำหรับสร้างและทำงานกับ .
type: docs
url: /th/com.aspose.slides/images/
---
**การสืบทอด:**
java.lang.Object
```
public class Images
```

เมธอดสำหรับสร้างและทำงานกับ [IImage](../../com.aspose.slides/iimage).
## คอนสตรัคเตอร์

| คอนสตรัคเตอร์ | คำอธิบาย |
| --- | --- |
| [Images()](#Images--) |  |
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [fromData(byte[] imageData)](#fromData-byte---) | สร้างภาพจากอาร์เรย์ไบต์ |
| [fromFile(String filename)](#fromFile-java.lang.String-) |  |
| [fromStream(InputStream stream)](#fromStream-java.io.InputStream-) |  |
### Images() {#Images--}
```
public Images()
```


### fromData(byte[] imageData) {#fromData-byte---}
```
public static IImage fromData(byte[] imageData)
```


สร้างภาพจากอาร์เรย์ไบต์.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| imageData | byte[] |  |

**คืนค่า:**
[IImage](../../com.aspose.slides/iimage)
### fromFile(String filename) {#fromFile-java.lang.String-}
```
public static IImage fromFile(String filename)
```


สร้างภาพจากไฟล์.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| filename | java.lang.String |  |

**คืนค่า:**
[IImage](../../com.aspose.slides/iimage)
### fromStream(InputStream stream) {#fromStream-java.io.InputStream-}
```
public static IImage fromStream(InputStream stream)
```


สร้างภาพจากสตรีม.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| stream | java.io.InputStream |  |

**คืนค่า:**
[IImage](../../com.aspose.slides/iimage)