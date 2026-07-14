---
title: IBiLevelEffectiveData
second_title: Aspose.Slides สำหรับ Android ผ่านเอกสารอ้างอิง Java API
description: วัตถุที่ไม่เปลี่ยนแปลงซึ่งเป็นตัวแทนของเอฟเฟกต์ Bi-Level สีดำ/สีขาว.
type: docs
url: /th/com.aspose.slides/ibileveleffectivedata/
---
**อินเทอร์เฟซที่ทำการใช้งานทั้งหมด:**
[com.aspose.slides.IEffectEffectiveData](../../com.aspose.slides/ieffecteffectivedata)
```
public interface IBiLevelEffectiveData extends IEffectEffectiveData
```

วัตถุที่ไม่เปลี่ยนแปลงซึ่งเป็นตัวแทนของเอฟเฟกต์ Bi-Level (black/white) ค่าสีอินพุตที่ความสว่างต่ำกว่าค่าขีดจำกัดที่ระบุจะถูกเปลี่ยนเป็นสีดำ ค่าสีอินพุตที่ความสว่างเท่ากับหรือสูงกว่าค่าที่ระบุจะถูกตั้งเป็นสีขาว ค่าผลกระทบอัลฟ่าไม่ได้รับผลกระทบจากเอฟเฟกต์นี้.
## เมธอด

| Method | Description |
| --- | --- |
| [getThreshold()](#getThreshold--) | คืนค่าขีดจำกัด. |
### getThreshold() {#getThreshold--}
```
public abstract float getThreshold()
```


คืนค่าขีดจำกัด. float แบบอ่านอย่างเดียว.

**คืนค่า:**
float