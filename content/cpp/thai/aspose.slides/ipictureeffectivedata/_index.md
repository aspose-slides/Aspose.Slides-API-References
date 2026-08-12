---
title: IPictureEffectiveData
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: อ็อบเจกต์ที่ไม่เปลี่ยนแปลงซึ่งบรรจุคุณสมบัติของรูปภาพที่มีประสิทธิภาพ
type: docs
weight: 3212
url: /th/aspose.slides/ipictureeffectivedata/
---
## IPictureEffectiveData คลาส


อ็อบเจกต์ที่ไม่เปลี่ยนแปลงซึ่งบรรจุคุณสมบัติของรูปภาพที่มีประสิทธิภาพ

```cpp
class IPictureEffectiveData : public virtual System::Object
```

## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | เปรียบเทียบวัตถุโดยใช้เซมานติกของ C# [Object.Equals](../../system/object/equals/) |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบวัตถุประเภทอ้างอิงในสไตล์ C# |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบวัตถุประเภทค่าในสไตล์ C# |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | เลียนแบบการเปรียบเทียบตัวเลขจุดลอยแบบ C#-style ที่ NaN สองค่าได้รับการถือว่าเท่ากัน แม้ตาม IEC 60559:1989 NaN จะไม่เท่ากับค่าใด ๆ รวมถึง NaN เอง |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | เลียนแบบการเปรียบเทียบตัวเลขจุดลอยแบบ C#-style ที่ NaN สองค่าได้รับการถือว่าเท่ากัน แม้ตาม IEC 60559:1989 NaN จะไม่เท่ากับค่าใด ๆ รวมถึง NaN เอง |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | เพื่อการใช้งานภายในเท่านั้น |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPPImage](../ippimage/)\> [get_Image](./get_image/)() | ส่งคืนภาพที่ฝังอยู่. เฉพาะอ่าน [IPPImage](../ippimage/) |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[Effects::IImageTransformOCollectionEffectiveData](../../aspose.slides.effects/iimagetransformocollectioneffectivedata/)\> [get_ImageTransform](./get_imagetransform/)() | ส่งคืนคอลเลกชันของเอฟเฟกต์การแปลงภาพ. เฉพาะอ่าน [Effects::IImageTransformOCollectionEffectiveData](../../aspose.slides.effects/iimagetransformocollectioneffectivedata/) |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[Effects::IEffectEffectiveData](../../aspose.slides.effects/ieffecteffectivedata/)\> [get_ImageTransformEffect](./get_imagetransformeffect/)(**int32_t**) | ส่งคืนเอฟเฟกต์การแปลงภาพที่ระบุตามดัชนี |
| virtual [System::String](../../system/string/) [get_LinkPathLong](./get_linkpathlong/)() | ส่งคืน URL ของภาพที่เชื่อมโยง. เฉพาะอ่าน [System::String](../../system/string/) |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | รับโครงสร้างข้อมูลตัวนับอ้างอิงที่เชื่อมโยงกับวัตถุ |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | เป็นการจำลองของเมธอด C# [Object.GetHashCode()](../../system/object/gethashcode/). เปิดการทำแฮชของวัตถุแบบกำหนดเอง |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | รับประเภทจริงของวัตถุ. เป็นการจำลองของการเรียก C# [System.Object.GetType()](../../system/object/gettype/) |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | ตรวจสอบว่าวัตถุเป็นอินสแตนซ์ของประเภทที่อธิบายโดย targetType หรือไม่. เป็นการจำลองของออเปอเรเตอร์ 'is' ของ C# |
| void [Lock](../../system/object/lock/)() | ทำงานตามคำสั่ง lock() ของ C# เพื่อทำการล็อก. เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/) |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | เป็นการจำลองของเมธอด C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). เปิดการทำสำเนาประเภทที่กำหนดเอง |
|  [Object](../../system/object/object/)() | สร้างอ็อบเจกต์. เริ่มต้นโครงสร้างข้อมูลภายในทั้งหมด |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | คอนสตรัคเตอร์คัดลอก. จริง ๆ แล้วไม่ได้คัดลอกอะไรเลย, เพียงเริ่มต้นอ็อบเจกต์ใหม่และเปิดการคัดลอกสร้างซับคลาส |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | ตัวดำเนินการมอบหมายค่า. จริง ๆ แล้วไม่ได้คัดลอกอะไรเลย, เพียงเริ่มต้นอ็อบเจกต์ใหม่และเปิดการคัดลอกสร้างซับคลาส |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | เปรียบเทียบวัตถุโดยอ้างอิง |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | เปรียบเทียบวัตถุโดยอ้างอิง |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | เปรียบเทียบอ็อบเจกต์ประเภทค่าโดยอ้างอิงกับ nullptr |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | การจำเพาะของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริงและ nullptr |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | การจำเพาะของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริงหลายตัว |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | ลดจำนวนอ้างอิงที่แชร์ลงตามค่าที่กำหนด |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | ตั้งค่าอาร์กิวเมนต์เทมเพลตที่ n ให้เป็น weak pointer (แทน shared). อนุญาตให้สลับพอยน์เตอร์ในคอนเทนเนอร์เป็นโหมด weak |
| int [SharedCount](../../system/object/sharedcount/)() const | รับค่าปัจจุบันของตัวนับอ้างอิงที่แชร์ |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | เพิ่มจำนวนอ้างอิงที่แชร์. ไม่ควรเรียกโดยตรง; แทนให้ใช้ smart pointers หรือ ThisProtector |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ลดจำนวนอ้างอิงที่แชร์และส่งคืนค่า. ไม่ควรเรียกโดยตรง; แทนให้ใช้ smart pointers หรือ ThisProtector |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | เป็นการจำลองของเมธอด C# [Object.ToString()](../../system/object/tostring/). เปิดการแปลงอ็อบเจกต์แบบกำหนดเองเป็นสตริง |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ทำงานตามการสร้าง typeof([System.Object](../../system/object/)) ของ C# |
| void [Unlock](../../system/object/unlock/)() | ทำงานตามคำสั่ง lock() ของ C# เพื่อปลดล็อก. เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/) |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | เพิ่มจำนวน weak reference. ไม่ควรเรียกโดยตรง; แทนให้ใช้ smart pointers หรือ ThisProtector |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ลดจำนวน weak reference. ไม่ควรเรียกโดยตรง; แทนให้ใช้ smart pointers หรือ ThisProtector |
| virtual  [~Object](../../system/object/~object/)() | ทำลายอ็อบเจกต์. ปลดปล่อยโครงสร้างข้อมูลภายในทั้งหมด |

## หมายเหตุ


อินเทอร์เฟซนี้ใช้เป็นส่วนหนึ่งของ [IPictureFillFormatEffectiveData](../ipicturefillformateffectivedata/) และ [IBulletFormatEffectiveData](../ibulletformateffectivedata/). 

## ดูเพิ่มเติม

* คลาส [Object](../../system/object/)
* เนมสเปซ [Aspose::Slides](../)
* ไลบรารี [Aspose.Slides](../../)