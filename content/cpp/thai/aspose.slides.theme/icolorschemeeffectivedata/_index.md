---
title: IColorSchemeEffectiveData
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: อ็อบเจ็กต์ที่ไม่เปลี่ยนแปลงซึ่งบรรจุคุณสมบัติโทนสีที่มีผล.
type: docs
weight: 157
url: /th/aspose.slides.theme/icolorschemeeffectivedata/
---
## IColorSchemeEffectiveData คลาส

อ็อบเจ็กต์ที่ไม่เปลี่ยนแปลงซึ่งบรรจุคุณสมบัติโทนสีที่มีผล

```cpp
class IColorSchemeEffectiveData : public virtual System::Object
```

## เมธอด

| Method | คำอธิบาย |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | เปรียบเทียบอ็อบเจ็กต์โดยใช้หลักการของ C# [Object.Equals](../../system/object/equals/) |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจ็กต์ประเภทอ้างอิงในสไตล์ของ C# |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจ็กต์ประเภทค่าในสไตล์ของ C# |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | จำลองการเปรียบเทียบจำนวนจริงแบบ C#-style ที่ NaN สองค่าเทียบเท่ากัน แม้ว่าตาม IEC 60559:1989 NaN จะไม่เท่ากับค่าใด ๆ รวมถึง NaN ด้วย |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | จำลองการเปรียบเทียบจำนวนจริงแบบ C#-style ที่ NaN สองค่าเทียบเท่ากัน แม้ว่าตาม IEC 60559:1989 NaN จะไม่เท่ากับค่าใด ๆ รวมถึง NaN ด้วย |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | ใช้เพื่อวัตถุประสงค์ภายในเท่านั้น |
| virtual [System::Drawing::Color](../../system.drawing/color/) [get_Accent1](./get_accent1/)() | สีเน้นแรกในสเกม. อ่านอย่างเดียว [System::Drawing::Color](../../system.drawing/color/) |
| virtual [System::Drawing::Color](../../system.drawing/color/) [get_Accent2](./get_accent2/)() | สีเน้นที่สองในสเกม. อ่านอย่างเดียว [System::Drawing::Color](../../system.drawing/color/) |
| virtual [System::Drawing::Color](../../system.drawing/color/) [get_Accent3](./get_accent3/)() | สีเน้นที่สามในสเกม. อ่านอย่างเดียว [System::Drawing::Color](../../system.drawing/color/) |
| virtual [System::Drawing::Color](../../system.drawing/color/) [get_Accent4](./get_accent4/)() | สีเน้นที่สี่ในสเกม. อ่านอย่างเดียว [System::Drawing::Color](../../system.drawing/color/) |
| virtual [System::Drawing::Color](../../system.drawing/color/) [get_Accent5](./get_accent5/)() | สีเน้นที่ห้าในสเกม. อ่านอย่างเดียว [System::Drawing::Color](../../system.drawing/color/) |
| virtual [System::Drawing::Color](../../system.drawing/color/) [get_Accent6](./get_accent6/)() | สีเน้นที่หกในสเกม. อ่านอย่างเดียว [System::Drawing::Color](../../system.drawing/color/) |
| virtual [System::Drawing::Color](../../system.drawing/color/) [get_Dark1](./get_dark1/)() | สีเข้มแรกในสเกม. อ่านอย่างเดียว [System::Drawing::Color](../../system.drawing/color/) |
| virtual [System::Drawing::Color](../../system.drawing/color/) [get_Dark2](./get_dark2/)() | สีเข้มที่สองในสเกม. อ่านอย่างเดียว [System::Drawing::Color](../../system.drawing/color/) |
| virtual [System::Drawing::Color](../../system.drawing/color/) [get_FollowedHyperlink](./get_followedhyperlink/)() | สีสำหรับลิงก์ที่เคยเยี่ยมชม. อ่านอย่างเดียว [System::Drawing::Color](../../system.drawing/color/) |
| virtual [System::Drawing::Color](../../system.drawing/color/) [get_Hyperlink](./get_hyperlink/)() | สีสำหรับลิงก์. อ่านอย่างเดียว [System::Drawing::Color](../../system.drawing/color/) |
| virtual [System::Drawing::Color](../../system.drawing/color/) [get_Light1](./get_light1/)() | สีอ่อนแรกในสเกม. อ่านอย่างเดียว [System::Drawing::Color](../../system.drawing/color/) |
| virtual [System::Drawing::Color](../../system.drawing/color/) [get_Light2](./get_light2/)() | สีอ่อนที่สองในสเกม. อ่านอย่างเดียว [System::Drawing::Color](../../system.drawing/color/) |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | รับโครงสร้างข้อมูลตัวนับอ้างอิงที่เชื่อมโยงกับอ็อบเจ็กต์ |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | เป็นความคล้ายของเมธอด C# [Object.GetHashCode()](../../system/object/gethashcode/). เปิดใช้งานการแฮชอ็อบเจ็กต์ที่กำหนดเอง |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | รับประเภทแท้ของอ็อบเจ็กต์. เป็นความคล้ายของการเรียก C# [System.Object.GetType()](../../system/object/gettype/) |
| virtual [System::Drawing::Color](../../system.drawing/color/) [idx_get](./idx_get/)([ColorSchemeIndex](../../aspose.slides/colorschemeindex/)) | รับองค์ประกอบที่ตำแหน่งที่ระบุ. อ่านอย่างเดียว [System::Drawing::Color](../../system.drawing/color/) |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | ตรวจสอบว่าอ็อบเจ็กต์เป็นอินสแตนซ์ของประเภทที่อธิบายโดย targetType หรือไม่. เป็นความคล้ายของตัวดำเนินการ 'is' ของ C# |
| void [Lock](../../system/object/lock/)() | ทำงานตามคำสั่ง lock() ของ C# เพื่อทำการล็อค. เรียกโดยตรงหรือใช้ [LockContext](../../system/lockcontext/) sentinel object |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | เป็นความคล้ายของเมธอด C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). เปิดใช้งานการโคลนประเภทที่กำหนดเอง |
|  [Object](../../system/object/object/)() | สร้างอ็อบเจ็กต์. เขียนค่าเริ่มต้นให้กับโครงสร้างข้อมูลภายในทั้งหมด |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | คอนสตรัคเตอร์คัดลอก. จริง ๆ แล้วไม่ได้คัดลอกอะไรเลย เพียงแค่สร้างอ็อบเจ็กต์ใหม่และเปิดใช้งานการคัดลอกสร้างซับคลาส |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | ตัวดำเนินการกำหนดค่า. จริง ๆ แล้วไม่ได้คัดลอกอะไรเลย เพียงแค่สร้างอ็อบเจ็กต์ใหม่และเปิดใช้งานการคัดลอกสร้างซับคลาส |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | เปรียบเทียบอ็อบเจ็กต์โดยอ้างอิง |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | เปรียบเทียบอ็อบเจ็กต์โดยอ้างอิง |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | เปรียบเทียบอ็อบเจ็กต์ประเภทค่ากับ nullptr โดยอ้างอิง |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | การทำพิเศษของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริงและ nullptr |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | การทำพิเศษของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริง |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | ลดจำนวนการอ้างอิงที่แชร์โดยค่าที่ระบุ |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | ตั้งอาร์กิวเมนต์เทมเพลตที่ n ให้เป็น weak pointer (แทนที่ shared). อนุญาตให้สลับพอยน์เตอร์ในคอนเทนเนอร์เป็นโหมด weak |
| int [SharedCount](../../system/object/sharedcount/)() const | รับค่าปัจจุบันของตัวนับอ้างอิงที่แชร์ |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | เพิ่มจำนวนการอ้างอิงที่แชร์. ไม่ควรเรียกโดยตรง; ควรใช้ smart pointers หรือ ThisProtector |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ลดจำนวนและคืนค่าตัวนับอ้างอิงที่แชร์. ไม่ควรเรียกโดยตรง; ควรใช้ smart pointers หรือ ThisProtector |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | เป็นความคล้ายของเมธอด C# [Object.ToString()](../../system/object/tostring/). เปิดใช้งานการแปลงอ็อบเจ็กต์ที่กำหนดเองเป็นสตริง |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ทำงานตามการสร้าง C# typeof([System.Object](../../system/object/)) |
| void [Unlock](../../system/object/unlock/)() | ทำงานตามคำสั่ง lock() ของ C# เพื่อปลดล็อค. เรียกโดยตรงหรือใช้ [LockContext](../../system/lockcontext/) sentinel object |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | เพิ่มจำนวนการอ้างอิงแบบ weak. ไม่ควรเรียกโดยตรง; ควรใช้ smart pointers หรือ ThisProtector |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ลดจำนวนการอ้างอิงแบบ weak. ไม่ควรเรียกโดยตรง; ควรใช้ smart pointers หรือ ThisProtector |
| virtual  [~Object](../../system/object/~object/)() | ทำลายอ็อบเจ็กต์. ปล่อยโครงสร้างข้อมูลภายในทั้งหมด |

## หมายเหตุ

คลาสนี้ใช้เป็นส่วนหนึ่งของ [IThemeEffectiveData](../ithemeeffectivedata/).

## ดูเพิ่มเติม

* คลาส [Object](../../system/object/)
* เนมสเปซ [Aspose::Slides::Theme](../)
* ไลบรารี [Aspose.Slides](../../)