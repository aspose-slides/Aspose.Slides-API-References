---
title: IOleEmbeddedDataInfo
second_title: Aspose.Slides for Android via Java API Reference
description: แสดงข้อมูลฝังของอ็อบเจกต์ OLE.
type: docs
url: /th/com.aspose.slides/ioleembeddeddatainfo/
---```
public interface IOleEmbeddedDataInfo
```

แสดงข้อมูลฝังของอ็อบเจกต์ OLE.
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getEmbeddedFileData()](#getEmbeddedFileData--) | ส่งคืนข้อมูลไฟล์ของอ็อบเจกต์ OLE ที่ฝังอยู่ อ่านอย่างเดียว byte[]. |
| [getEmbeddedFileExtension()](#getEmbeddedFileExtension--) | ส่งคืนส่วนขยายไฟล์สำหรับอ็อบเจกต์ OLE ที่ฝังอยู่ในปัจจุบัน อ่านอย่างเดียว String. |
### getEmbeddedFileData() {#getEmbeddedFileData--}
```
public abstract byte[] getEmbeddedFileData()
```

ส่งคืนข้อมูลไฟล์ของอ็อบเจกต์ OLE ที่ฝังอยู่ อ่านอย่างเดียว byte[].

**ผลลัพธ์:**
byte[]
### getEmbeddedFileExtension() {#getEmbeddedFileExtension--}
```
public abstract String getEmbeddedFileExtension()
```

ส่งคืนส่วนขยายไฟล์สำหรับอ็อบเจกต์ OLE ที่ฝังอยู่ในปัจจุบัน อ่านอย่างเดียว String.

**ผลลัพธ์:**
java.lang.String