---
title: get_InkEffectImages()
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: รับคอลเลกชันของภาพที่กำหนดเองที่ใช้เพื่อจำลองเอฟเฟกต์ภาพสำหรับแปรงหมึก ภาพเหล่านี้จะถูกใช้เมื่อแสดงผลหมึกด้วยค่า InkEffectType เฉพาะ เช่น Galaxy, Rainbow เป็นต้น โดยการให้ภาพของคุณเอง คุณสามารถควบคุมว่าทุกเอฟเฟกต์หมึกจะแสดงอย่างไร
type: docs
weight: 14
url: /th/aspose.slides.ink/ink/get_inkeffectimages/
---
## Ink::get_InkEffectImages() เมธอด

รับคอลเลกชันของภาพที่กำหนดเองที่ใช้เพื่อจำลองเอฟเฟกต์ภาพสำหรับแปรงหมึก ภาพเหล่านี้จะถูกใช้เมื่อแสดงผลหมึกกับค่า [InkEffectType](../../inkeffecttype/) เฉพาะ เช่น Galaxy, Rainbow เป็นต้น โดยการให้ภาพของคุณเอง คุณสามารถควบคุมว่าทุกเอฟเฟกต์หมึกจะแสดงอย่างไร

```cpp
static System::SharedPtr<System::Collections::Generic::IDictionary<InkEffectType, System::SharedPtr<IImage>>> Aspose::Slides::Ink::Ink::get_InkEffectImages()
```

## หมายเหตุ

คุณสมบัตินี้ทำให้สามารถแทนที่พื้นผิวเอฟเฟกต์หมึกเริ่มต้นด้วยสิ่งที่กำหนดโดยผู้ใช้ ซึ่งเป็นประโยชน์อย่างมากเมื่อแอสเซทเริ่มต้นถูกจำกัดโดยลิขสิทธิ์หรือไม่มีให้ใช้งานในระหว่างการทำงาน แต่ละรายการในพจนานุกรมต้องเชื่อมโยงค่า [InkEffectType](../../inkeffecttype/) กับวัตถุ [IImage](../../../aspose.slides/iimage/) ที่สอดคล้องกัน (เช่น Bitmap หรืออินเทอร์เฟซภาพ **Aspose**)

```cpp
System::SharedPtr<IImage> image = Images::FromFile(u"image.png");
Ink::get_InkEffectImages()->Add(InkEffectType::Galaxy, image);
```

## ดูเพิ่มเติม

* Enum [InkEffectType](../../inkeffecttype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [IDictionary](../../../system.collections.generic/idictionary/)
* คลาส [IImage](../../../aspose.slides/iimage/)
* คลาส [Ink](../)
* เนมสเปซ [Aspose::Slides::Ink](../../)
* Library [Aspose.Slides](../../../)