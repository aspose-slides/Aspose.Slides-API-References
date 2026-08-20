---
title: IAlphaBiLevelEffectiveData
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ Java
description: อ็อบเจกต์ที่ไม่สามารถเปลี่ยนแปลงได้ซึ่งแสดงถึงเอฟเฟกต์ Alpha Bi-Level
type: docs
url: /th/com.aspose.slides/ialphabileveleffectivedata/
---
**ทุกอินเทอร์เฟซที่ทำการใช้งาน:**
[com.aspose.slides.IEffectEffectiveData](../../com.aspose.slides/ieffecteffectivedata)
```
public interface IAlphaBiLevelEffectiveData extends IEffectEffectiveData
```

Immutable object which represents an Alpha Bi-Level effect. Alpha (Opacity) values less than the threshold are changed to 0 (fully transparent) and alpha values greater than or equal to the threshold are changed to 100% (fully opaque).
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getThreshold()](#getThreshold--) | คืนค่าเกณฑ์ของเอฟเฟกต์. |
### getThreshold() {#getThreshold--}
```
public abstract float getThreshold()
```


คืนค่าเกณฑ์ของเอฟเฟกต์. Read-only float.

**คืนค่า:**
float