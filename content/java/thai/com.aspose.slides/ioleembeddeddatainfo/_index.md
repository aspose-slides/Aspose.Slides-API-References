---
title: IOleEmbeddedDataInfo
second_title: Aspose.Slides for Java API Reference
description: แสดงข้อมูลที่ฝังอยู่สำหรับอ็อบเจ็กต์ OLE.
type: docs
url: /th/com.aspose.slides/ioleembeddeddatainfo/
---```
public interface IOleEmbeddedDataInfo
```

แสดงข้อมูลที่ฝังอยู่สำหรับอ็อบเจ็กต์ OLE.
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getEmbeddedFileData()](#getEmbeddedFileData--) | คืนค่าข้อมูลไฟล์ของอ็อบเจ็กต์ OLE ที่ฝังอยู่ อ่านอย่างเดียว byte[]. |
| [getEmbeddedFileExtension()](#getEmbeddedFileExtension--) | คืนค่านามสกุลไฟล์สำหรับอ็อบเจ็กต์ OLE ที่ฝังอยู่ในปัจจุบัน อ่านอย่างเดียว String. |
### getEmbeddedFileData() {#getEmbeddedFileData--}
```
public abstract byte[] getEmbeddedFileData()
```

คืนค่าข้อมูลไฟล์ของอ็อบเจ็กต์ OLE ที่ฝังอยู่ อ่านอย่างเดียว byte[].

**คืนค่า:**
byte[]
### getEmbeddedFileExtension() {#getEmbeddedFileExtension--}
```
public abstract String getEmbeddedFileExtension()
```

คืนค่านามสกุลไฟล์สำหรับอ็อบเจ็กต์ OLE ที่ฝังอยู่ในปัจจุบัน อ่านอย่างเดียว String.

**คืนค่า:**
java.lang.String