---
title: OleEmbeddedDataInfo
second_title: Aspose.Slides สำหรับ Android ผ่าน Java API Reference
description: แสดงข้อมูลฝังสำหรับอ็อบเจกต์ OLE.
type: docs
url: /th/com.aspose.slides/oleembeddeddatainfo/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.slides.IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo)
```
public class OleEmbeddedDataInfo implements IOleEmbeddedDataInfo
```

แสดงข้อมูลฝังสำหรับอ็อบเจกต์ OLE.

## คอนสตรัคเตอร์

| คอนสตรัคเตอร์ | คำอธิบาย |
| --- | --- |
| [OleEmbeddedDataInfo()](#OleEmbeddedDataInfo--) | สร้างข้อมูลฝังใหม่สำหรับอ็อบเจกต์ OLE. |
| [OleEmbeddedDataInfo(byte[] embeddedFileData, String embeddedFileExtension)](#OleEmbeddedDataInfo-byte---java.lang.String-) | สร้างอินสแตนซ์ใหม่ของข้อมูลฝังสำหรับอ็อบเจกต์ OLE. |

## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getEmbeddedFileData()](#getEmbeddedFileData--) | คืนค่าข้อมูลไฟล์ของอ็อบเจกต์ OLE ที่ฝังไว้ อ่านอย่างเดียว byte[]. |
| [getEmbeddedFileExtension()](#getEmbeddedFileExtension--) | คืนค่าส่วนขยายไฟล์สำหรับอ็อบเจกต์ OLE ที่ฝังอยู่ในปัจจุบัน อ่านอย่างเดียว String. |

### OleEmbeddedDataInfo() {#OleEmbeddedDataInfo--}
```
public OleEmbeddedDataInfo()
```

สร้างข้อมูลฝังใหม่สำหรับอ็อบเจกต์ OLE.

### OleEmbeddedDataInfo(byte[] embeddedFileData, String embeddedFileExtension) {#OleEmbeddedDataInfo-byte---java.lang.String-}
```
public OleEmbeddedDataInfo(byte[] embeddedFileData, String embeddedFileExtension)
```

สร้างอินสแตนซ์ใหม่ของข้อมูลฝังสำหรับอ็อบเจกต์ OLE.

**Parameters:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| embeddedFileData | byte[] | ข้อมูลไฟล์ของอ็อบเจกต์ OLE ที่ฝังไว้ byte[]. |
| embeddedFileExtension | java.lang.String | ส่วนขยายไฟล์สำหรับอ็อบเจกต์ OLE ที่ฝังอยู่ในปัจจุบัน String. |

### getEmbeddedFileData() {#getEmbeddedFileData--}
```
public final byte[] getEmbeddedFileData()
```

คืนค่าข้อมูลไฟล์ของอ็อบเจกต์ OLE ที่ฝังไว้ อ่านอย่างเดียว byte[].

**Returns:**
byte[]

### getEmbeddedFileExtension() {#getEmbeddedFileExtension--}
```
public final String getEmbeddedFileExtension()
```

คืนค่าส่วนขยายไฟล์สำหรับอ็อบเจกต์ OLE ที่ฝังอยู่ในปัจจุบัน อ่านอย่างเดียว String.

**Returns:**
java.lang.String