---
title: OleEmbeddedDataInfo
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ Java
description: เป็นตัวแทนของข้อมูลฝังสำหรับวัตถุ OLE.
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

เป็นตัวแทนของข้อมูลฝังสำหรับวัตถุ OLE.

## คอนสตรัคเตอร์

| คอนสตรัคเตอร์ | คำอธิบาย |
| --- | --- |
| [OleEmbeddedDataInfo()](#OleEmbeddedDataInfo--) | สร้างข้อมูลฝังใหม่สำหรับวัตถุ OLE. |
| [OleEmbeddedDataInfo(byte[] embeddedFileData, String embeddedFileExtension)](#OleEmbeddedDataInfo-byte---java.lang.String-) | สร้างอินสแตนซ์ใหม่ของข้อมูลฝังสำหรับวัตถุ OLE. |

## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getEmbeddedFileData()](#getEmbeddedFileData--) | ส่งคืนข้อมูลไฟล์ของวัตถุ OLE ที่ฝังไว้ อ่านได้อย่างเดียว byte[]. |
| [getEmbeddedFileExtension()](#getEmbeddedFileExtension--) | ส่งคืนส่วนขยายไฟล์สำหรับวัตถุ OLE ที่ฝังอยู่ในปัจจุบัน อ่านได้อย่างเดียว String. |

### OleEmbeddedDataInfo() {#OleEmbeddedDataInfo--}
```
public OleEmbeddedDataInfo()
```

สร้างข้อมูลฝังใหม่สำหรับวัตถุ OLE.

### OleEmbeddedDataInfo(byte[] embeddedFileData, String embeddedFileExtension) {#OleEmbeddedDataInfo-byte---java.lang.String-}
```
public OleEmbeddedDataInfo(byte[] embeddedFileData, String embeddedFileExtension)
```

สร้างอินสแตนซ์ใหม่ของข้อมูลฝังสำหรับวัตถุ OLE.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| embeddedFileData | byte[] | ข้อมูลไฟล์ของวัตถุ OLE ที่ฝังไว้ byte[]. |
| embeddedFileExtension | java.lang.String | ส่วนขยายไฟล์สำหรับวัตถุ OLE ที่ฝังอยู่ในปัจจุบัน String. |

### getEmbeddedFileData() {#getEmbeddedFileData--}
```
public final byte[] getEmbeddedFileData()
```

ส่งคืนข้อมูลไฟล์ของวัตถุ OLE ที่ฝังไว้ อ่านได้อย่างเดียว byte[].

**ค่าที่ส่งคืน:**
byte[]

### getEmbeddedFileExtension() {#getEmbeddedFileExtension--}
```
public final String getEmbeddedFileExtension()
```

ส่งคืนส่วนขยายไฟล์สำหรับวัตถุ OLE ที่ฝังอยู่ในปัจจุบัน อ่านได้อย่างเดียว String.

**ค่าที่ส่งคืน:**
java.lang.String