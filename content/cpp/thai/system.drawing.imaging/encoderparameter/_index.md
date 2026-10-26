---
title: EncoderParameter
second_title: Aspose.Slides สำหรับ C++ API Reference
description: "ทำหน้าที่เป็นคอนเทนเนอร์ที่ใช้ส่งค่าไปยังตัวเข้ารหัสภาพ วัตถุของคลาสนี้ควรจัดสรรเฉพาะโดยใช้ฟังก์ชัน System::MakeObject() เท่านั้น อย่าสร้างอินสแตนซ์ของประเภทนี้บนสแตกหรือโดยใช้ตัวดำเนินการ new เพราะจะทำให้เกิดข้อผิดพลาดขณะรันและ/หรือข้อบกพร่องการตรวจสอบค่า ควรห่อคลาสนี้ด้วยตัวชี้ System::SmartPtr และใช้ตัวชี้นี้ส่งผ่านเป็นอาร์กิวเมนต์ให้กับฟังก์ชันต่าง ๆ"
type: docs
weight: 66
url: /th/system.drawing.imaging/encoderparameter/
---
## EncoderParameter คลาส

ทำหน้าที่เป็นคอนเทนเนอร์ที่ใช้ส่งค่าไปยังตัวเข้ารหัสภาพ ข้อมูลของคลาสนี้ควรจัดสรรเฉพาะโดยใช้ฟังก์ชัน [System::MakeObject()](../../system/makeobject/) เท่านั้น อย่าสร้างอินสแตนซ์ของประเภทนี้บนสแตกหรือโดยใช้ตัวดำเนินการ new เพราะจะทำให้เกิดข้อผิดพลาดขณะรันหรือข้อบกพร่องในการตรวจสอบค่า ควรห่อคลาสนี้ด้วยตัวชี้ [System::SmartPtr](../../system/smartptr/) และใช้ตัวชี้นี้ส่งผ่านเป็นอาร์กิวเมนต์ให้กับฟังก์ชันต่าง ๆ

```cpp
class EncoderParameter : public System::Object
```

## เมธอด

| Method | Description |
| --- | --- |
|  [EncoderParameter](./encoderparameter/)() | สร้างอินสแตนซ์ใหม่ของคลาส [EncoderParameter](./) |
|  [EncoderParameter](./encoderparameter/)(const [SharedPtr](../../system/sharedptr/)\<[Encoder](../encoder/)\>\&, **uint8_t**, **bool**) | สร้างอินสแตนซ์ใหม่ของคลาส [EncoderParameter](./) |
|  [EncoderParameter](./encoderparameter/)(const [SharedPtr](../../system/sharedptr/)\<[Encoder](../encoder/)\>\&, **int16_t**) | สร้างอินสแตนซ์ใหม่ของคลาส [EncoderParameter](./) |
|  [EncoderParameter](./encoderparameter/)(const [SharedPtr](../../system/sharedptr/)\<[Encoder](../encoder/)\>\&, **int64_t**) | สร้างอินสแตนซ์ใหม่ของคลาส [EncoderParameter](./) |
|  [EncoderParameter](./encoderparameter/)(const [SharedPtr](../../system/sharedptr/)\<[Encoder](../encoder/)\>\&, **int32_t**) | สร้างอินสแตนซ์ใหม่ของคลาส [EncoderParameter](./) |
|  [EncoderParameter](./encoderparameter/)(const [SharedPtr](../../system/sharedptr/)\<[Encoder](../encoder/)\>\&, **int32_t**, **int32_t**) | สร้างอินสแตนซ์ใหม่ของคลาส [EncoderParameter](./) ที่เป็นตัวแทนของเศษส่วน |
|  [EncoderParameter](./encoderparameter/)(const [SharedPtr](../../system/sharedptr/)\<[Encoder](../encoder/)\>\&, **int64_t**, **int64_t**) | สร้างอินสแตนซ์ใหม่ของคลาส [EncoderParameter](./) ที่เป็นตัวแทนของช่วงค่าจำนวนเต็ม |
|  [EncoderParameter](./encoderparameter/)(const [SharedPtr](../../system/sharedptr/)\<[Encoder](../encoder/)\>\&, **int32_t**, **int32_t**, **int32_t**, **int32_t**) | สร้างอินสแตนซ์ใหม่ของคลาส [EncoderParameter](./) ที่เป็นตัวแทนของช่วงเศษส่วน |
|  [EncoderParameter](./encoderparameter/)(const [SharedPtr](../../system/sharedptr/)\<[Encoder](../encoder/)\>\&, const [String](../../system/string/)\&) | สร้างอินสแตนซ์ใหม่ของคลาส [EncoderParameter](./) |
|  [EncoderParameter](./encoderparameter/)(const [SharedPtr](../../system/sharedptr/)\<[Encoder](../encoder/)\>\&, const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **bool**) | สร้างอินสแตนซ์ใหม่ของคลาส [EncoderParameter](./) ที่เป็นตัวแทนของอาร์เรย์ค่าต่าง ๆ |
|  [EncoderParameter](./encoderparameter/)(const [SharedPtr](../../system/sharedptr/)\<[Encoder](../encoder/)\>\&, const [ArrayPtr](../../system/arrayptr/)\<**int16_t**\>\&) | สร้างอินสแตนซ์ใหม่ของคลาส [EncoderParameter](./) ที่เป็นตัวแทนของอาร์เรย์ค่าต่าง ๆ |
|  [EncoderParameter](./encoderparameter/)(const [SharedPtr](../../system/sharedptr/)\<[Encoder](../encoder/)\>\&, const [ArrayPtr](../../system/arrayptr/)\<**int64_t**\>\&) | สร้างอินสแตนซ์ใหม่ของคลาส [EncoderParameter](./) ที่เป็นตัวแทนของอาร์เรย์ค่าต่าง ๆ |
|  [EncoderParameter](./encoderparameter/)(const [SharedPtr](../../system/sharedptr/)\<[Encoder](../encoder/)\>\&, const [ArrayPtr](../../system/arrayptr/)\<**int32_t**\>\&, const [ArrayPtr](../../system/arrayptr/)\<**int32_t**\>\&) | สร้างอินสแตนซ์ใหม่ของคลาส [EncoderParameter](./) ที่เป็นตัวแทนของอาร์เรย์ของเศษส่วน |
|  [EncoderParameter](./encoderparameter/)(const [SharedPtr](../../system/sharedptr/)\<[Encoder](../encoder/)\>\&, const [ArrayPtr](../../system/arrayptr/)\<**int64_t**\>\&, const [ArrayPtr](../../system/arrayptr/)\<**int64_t**\>\&) | สร้างอินสแตนซ์ใหม่ของคลาส [EncoderParameter](./) ที่เป็นตัวแทนของอาร์เรย์ของช่วงจำนวนเต็ม |
|  [EncoderParameter](./encoderparameter/)(const [SharedPtr](../../system/sharedptr/)\<[Encoder](../encoder/)\>\&, const [ArrayPtr](../../system/arrayptr/)\<**int32_t**\>\&, const [ArrayPtr](../../system/arrayptr/)\<**int32_t**\>\&, const [ArrayPtr](../../system/arrayptr/)\<**int32_t**\>\&, const [ArrayPtr](../../system/arrayptr/)\<**int32_t**\>\&) | สร้างอินสแตนซ์ใหม่ของคลาส [EncoderParameter](./) ที่เป็นตัวแทนของอาร์เรย์ของช่วงเศษส่วน |
|  [EncoderParameter](./encoderparameter/)(const [SharedPtr](../../system/sharedptr/)\<[Encoder](../encoder/)\>\&, int, [EncoderParameterValueType](../encoderparametervaluetype/), void *) | สร้างอินสแตนซ์ใหม่ของคลาส [EncoderParameter](./) ที่เป็นตัวแทนของจำนวนค่าที่ระบุของประเภทที่ระบุซึ่งอ่านจากบัฟเฟอร์ที่ระบุ |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | เปรียบเทียบอ็อบเจ็กต์โดยใช้ semantics ของ C# [Object.Equals](../../system/object/equals/) |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจ็กต์แบบอ้างอิงในสไตล์ C# |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจ็กต์แบบค่าในสไตล์ C# |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | จำลองการเปรียบเทียบค่าจุดลอยแบบ C# ซึ่ง NaN สองค่าถือเท่ากันแม้ว่าตาม IEC 60559:1989 NaN จะไม่เท่ากับค่าใด ๆ รวมถึง NaN เอง |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | จำลองการเปรียบเทียบค่าจุดลอยแบบ C# ซึ่ง NaN สองค่าถือเท่ากันแม้ว่าตาม IEC 60559:1989 NaN จะไม่เท่ากับค่าใด ๆ รวมถึง NaN เอง |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | ใช้สำหรับวัตถุประสงค์ภายในเท่านั้น |
| [EncoderPtr](../encoderptr/) [get_Encoder](./get_encoder/)() const | ส่งคืนอ็อบเจ็กต์ [Encoder](../encoder/) ที่เชื่อมโยงกับอ็อบเจ็กต์ [EncoderParameter](./) ปัจจุบัน |
| int [get_NumberOfValues](./get_numberofvalues/)() const | ส่งคืนจำนวนของค่าที่แสดงโดยอ็อบเจ็กต์ปัจจุบัน |
| [EncoderParameterValueType](../encoderparametervaluetype/) [get_Type](./get_type/)() const | ส่งคืนประเภทของค่า(ค่า)ที่แสดงโดยอ็อบเจ็กต์ปัจจุบัน |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | รับโครงสร้างข้อมูลตัวนับการอ้างอิงที่เชื่อมโยงกับอ็อบเจ็กต์ |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | เป็นสูตรคล้ายเมธอด C# [Object.GetHashCode()](../../system/object/gethashcode/). เปิดใช้งานการแฮชของอ็อบเจ็กต์ที่กำหนดเอง |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | รับประเภทจริงของอ็อบเจ็กต์. เป็นสูตรคล้ายการเรียก C# [System.Object.GetType()](../../system/object/gettype/) |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | ตรวจสอบว่าอ็อบเจ็กต์เป็นอินสแตนซ์ของประเภทที่อธิบายโดย targetType. สูตรคล้ายตัวดำเนินการ 'is' ของ C# |
| void [Lock](../../system/object/lock/)() | ทำงานตามคำสั่ง lock() ของ C# เพื่อทำการล็อก. เรียกโดยตรงหรือใช้วัตถุสังเกต [LockContext](../../system/lockcontext/) |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | เป็นสูตรคล้ายเมธอด C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). เปิดใช้งานการโคลนประเภทที่กำหนดเอง |
|  [Object](../../system/object/object/)() | สร้างอ็อบเจ็กต์. เริ่มต้นโครงสร้างข้อมูลภายในทั้งหมด |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | คอนสตรัคเตอร์คัดลอก. จริง ๆ แล้วไม่คัดลอกอะไรเลย เพียงแค่เริ่มต้นอ็อบเจ็กต์ใหม่และเปิดใช้งานการคัดลอกสร้างซับคลาส |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | ตัวดำเนินการกำหนดค่า. จริง ๆ แล้วไม่คัดลอกอะไรเลย เพียงแค่เริ่มต้นอ็อบเจ็กต์ใหม่และเปิดใช้งานการคัดลอกสร้างซับคลาส |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | เปรียบเทียบอ็อบเจ็กต์โดยอ้างอิง |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | เปรียบเทียบอ็อบเจ็กต์โดยอ้างอิง |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | เปรียบเทียบอ็อบเจ็กต์ชนิดค่ากับ nullptr โดยอ้างอิง |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | การทำเฉพาะของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริงและ nullptr |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | การทำเฉพาะของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริง |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | ลดจำนวนการอ้างอิงร่วมโดยค่าที่ระบุ |
| void [set_Encoder](./set_encoder/)(const [EncoderPtr](../encoderptr/)\&) | เชื่อมโยงอ็อบเจ็กต์ [Encoder](../encoder/) ที่ระบุกับอ็อบเจ็กต์ [EncoderParameter](./) ปัจจุบัน |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | ตั้งค่าตัวชี้อ่อนสำหรับอาร์กิวเมนต์เทมเพลตที่ n (แทนที่จะแชร์). อนุญาตให้สลับตัวชี้ในคอนเทนเนอร์เป็นโหมดอ่อน |
| int [SharedCount](../../system/object/sharedcount/)() const | รับค่าปัจจุบันของตัวนับอ้างอิงร่วม |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | เพิ่มจำนวนการอ้างอิงร่วม. ไม่ควรเรียกโดยตรง; แทนที่ควรใช้ smart pointer หรือ ThisProtector |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ลดจำนวนการอ้างอิงร่วมและส่งคืนค่า. ไม่ควรเรียกโดยตรง; แทนที่ควรใช้ smart pointer หรือ ThisProtector |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | เป็นสูตรคล้ายเมธอด C# [Object.ToString()](../../system/object/tostring/). เปิดใช้งานการแปลงอ็อบเจ็กต์ที่กำหนดเองเป็นสตริง |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ทำงานตามโครงสร้าง typeof([System.Object](../../system/object/)) ของ C# |
| void [Unlock](../../system/object/unlock/)() | ทำงานตามคำสั่ง lock() ของ C# เพื่อปลดล็อก. เรียกโดยตรงหรือใช้วัตถุสังเกต [LockContext](../../system/lockcontext/) |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | เพิ่มจำนวนการอ้างอิงอ่อน. ไม่ควรเรียกโดยตรง; แทนที่ควรใช้ smart pointer หรือ ThisProtector |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ลดจำนวนการอ้างอิงอ่อน. ไม่ควรเรียกโดยตรง; แทนที่ควรใช้ smart pointer หรือ ThisProtector |
|  [~EncoderParameter](./~encoderparameter/)() | ตัวทำลาย |
| virtual  [~Object](../../system/object/~object/)() | ทำลายอ็อบเจ็กต์. ปล่อยโครงสร้างข้อมูลภายในทั้งหมด |

## ดูเพิ่มเติม

* คลาส [Object](../../system/object/)
* เนมสเปซ [System::Drawing::Imaging](../)
* ไลบรารี [Aspose.Slides](../../)