---
title: PresentationHeaderFooterManager
second_title: Aspose.Slides สำหรับ C++ การอ้างอิง API
description: เป็นตัวจัดการที่เก็บพฤติกรรมของส่วนตำแหน่ง footer, วันที่-เวลา และหมายเลขหน้า ของการนำเสนอทั้งหมด.
type: docs
weight: 4863
url: /th/aspose.slides/presentationheaderfootermanager/
---
## PresentationHeaderFooterManager คลาส

แทนตัวผู้จัดการที่เก็บพฤติกรรมของส่วนท้าย, วันที่-เวลา และหมายเลขหน้าของการนำเสนอทั้งหมด.

```cpp
class PresentationHeaderFooterManager : public Aspose::Slides::BaseHeaderFooterManager,
                                        public Aspose::Slides::IPresentationHeaderFooterManager
```

## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | เปรียบเทียบอ็อบเจ็กต์โดยใช้การทำงานของ C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจ็กต์แบบอ้างอิงในสไตล์ C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจ็กต์แบบค่าในสไตล์ C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | จำลองการเปรียบเทียบแบบจุดลอยของ C# เมื่อ NaN สองค่าถือว่าเท่ากัน แม้ว่า ตาม IEC 60559:1989 NaN จะไม่เท่ากับค่าใด ๆ รวมถึง NaN ด้วย. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | จำลองการเปรียบเทียบแบบจุดลอยของ C# เมื่อ NaN สองค่าถือว่าเท่ากัน แม้ว่า ตาม IEC 60559:1989 NaN จะไม่เท่ากับค่าใด ๆ รวมถึง NaN ด้วย. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | เพื่อวัตถุประสงค์ในการใช้งานภายในเท่านั้น. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | รับโครงสร้างข้อมูลตัวนับอ้างอิงที่เชื่อมโยงกับอ็อบเจ็กต์. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | เป็นเมธอดที่เทียบเท่ากับเมธอด C# [Object.GetHashCode()](../../system/object/gethashcode/). เปิดใช้งานการทำแฮชของอ็อบเจ็กต์กำหนดเอง. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | รับชนิดจริงของอ็อบเจ็กต์. เป็นเมธอดที่เทียบเท่ากับการเรียก C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | ตรวจสอบว่าอ็อบเจ็กต์เป็นอินสแตนซ์ของชนิดที่อธิบายโดย targetType. เทียบเท่ากับตัวดำเนินการ 'is' ของ C#. |
| void [Lock](../../system/object/lock/)() | ดำเนินการล็อกตามคำสั่ง lock() ของ C#. เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | เป็นเมธอดที่เทียบเท่ากับ C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). เปิดใช้งานการคัดลอกแบบคลอนของชนิดกำหนดเอง. |
|  [Object](../../system/object/object/)() | สร้างอ็อบเจ็กต์. เริ่มต้นโครงสร้างข้อมูลภายในทั้งหมด. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | คอนสตรัคเตอร์คัดลอก. จริง ๆ แล้วไม่ได้คัดลอกรายการใด ๆ เพียงเริ่มต้นอ็อบเจ็กต์ใหม่และเปิดใช้งานการคัดลอกของคลาสย่อย. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | ตัวดำเนินการกำหนดค่า. จริง ๆ แล้วไม่ได้คัดลอกรายการใด ๆ เพียงเริ่มต้นอ็อบเจ็กต์ใหม่และเปิดใช้งานการคัดลอกของคลาสย่อย. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | เปรียบเทียบอ็อบเจ็กต์โดยอ้างอิง. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | เปรียบเทียบอ็อบเจ็กต์โดยอ้างอิง. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | เปรียบเทียบอ้างอิงอ็อบเจ็กต์แบบค่า กับ nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | เป็นการจำเพาะของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริงและ nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | เป็นการจำเพาะของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริง. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | ลดค่าตัวนับอ้างอิงที่แชร์ลงตามค่าที่ระบุ. |
| void [SetAllDateTimesText](./setalldatetimestext/)([System::String](../../system/string/)) override | ตั้งค่าข้อความให้กับส่วนตำแหน่งวันที่-เวลาทั้งหมด รวมถึงสไลด์มาสเตอร์, สไลด์เลเอาต์, สไลด์, โน้ตมาสเตอร์, โน้ตสไลด์ และฮันดเอาท์มาสเตอร์. |
| void [SetAllDateTimesVisibility](./setalldatetimesvisibility/)(**bool**) override | เปลี่ยนการมองเห็นของส่วนตำแหน่งวันที่-เวลา ทั้งหมด รวมถึงสไลด์มาสเตอร์, สไลด์เลเอาต์, สไลด์, โน้ตมาสเตอร์, โน้ตสไลด์ และฮันดเอาท์มาสเตอร์. |
| void [SetAllFootersText](./setallfooterstext/)([System::String](../../system/string/)) override | ตั้งค่าข้อความให้กับส่วนตำแหน่ง footer ทั้งหมด รวมถึงสไลด์มาสเตอร์, สไลด์เลเอาต์, สไลด์, โน้ตมาสเตอร์, โน้ตสไลด์ และฮันดเอาท์มาสเตอร์. |
| void [SetAllFootersVisibility](./setallfootersvisibility/)(**bool**) override | เปลี่ยนการมองเห็นของส่วนตำแหน่ง footer ทั้งหมด รวมถึงสไลด์มาสเตอร์, สไลด์เลเอาต์, สไลด์, โน้ตมาสเตอร์, โน้ตสไลด์ และฮันดเอาท์มาสเตอร์. |
| void [SetAllHeadersText](./setallheaderstext/)([System::String](../../system/string/)) override | ตั้งค่าข้อความให้กับส่วนตำแหน่ง header ทั้งหมด รวมถึงโน้ตมาสเตอร์, โน้ตสไลด์ และฮันดเอาท์มาสเตอร์. |
| void [SetAllHeadersVisibility](./setallheadersvisibility/)(**bool**) override | เปลี่ยนการมองเห็นของส่วนตำแหน่ง header ทั้งหมด รวมถึงโน้ตมาสเตอร์, โน้ตสไลด์ และฮันดเอาท์มาสเตอร์. |
| void [SetAllSlideNumbersVisibility](./setallslidenumbersvisibility/)(**bool**) override | เปลี่ยนการมองเห็นของส่วนตำแหน่ง page number ทั้งหมด รวมถึงสไลด์มาสเตอร์, สไลด์เลเอาต์, สไลด์, โน้ตมาสเตอร์, โน้ตสไลด์ และฮันดเอาท์มาสเตอร์. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | ตั้งค่าเทมเพลตอาร์กิวเมนต์ที่ n เป็น weak pointer (แทนที่จะแบ่งปัน). อนุญาตให้สลับพอยน์เตอร์ในคอนเทนเนอร์เป็นโหมด weak. |
| void [SetVisibilityOnAllTitleSlides](./setvisibilityonalltitleslides/)(**bool**) override | เปลี่ยนการมองเห็นของส่วนตำแหน่ง footer, วันที่-เวลา และหมายเลขหน้า สำหรับสไลด์หัวเรื่องทั้งหมดและสไลด์เลเอาต์แรก. สไลด์หัวเรื่อง \\u2013 สไลด์ที่อิงจากสไลด์เลเอาต์แรก (ไม่คำนึงถึงชนิดของเลเอาต์แรกนี้). |
| int [SharedCount](../../system/object/sharedcount/)() const | รับค่าปัจจุบันของตัวนับอ้างอิงที่แชร์. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | เพิ่มค่าตัวนับอ้างอิงที่แชร์. ไม่ควรเรียกโดยตรง; แทนใช้ smart pointer หรือ ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ลดค่าตัวนับอ้างอิงที่แชร์และคืนค่า. ไม่ควรเรียกโดยตรง; แทนใช้ smart pointer หรือ ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | เป็นเมธอดที่เทียบเท่ากับ C# [Object.ToString()](../../system/object/tostring/). เปิดใช้งานการแปลงอ็อบเจ็กต์กำหนดเองเป็นสตริง. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ดำเนินการโครงสร้าง C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | ดำเนินการปลดล็อกตามคำสั่ง lock() ของ C#. เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | เพิ่มค่าตัวนับอ้างอิงแบบ weak. ไม่ควรเรียกโดยตรง; แทนใช้ smart pointer หรือ ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ลดค่าตัวนับอ้างอิงแบบ weak. ไม่ควรเรียกโดยตรง; แทนใช้ smart pointer หรือ ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | ทำลายอ็อบเจ็กต์. ปล่อยโครงสร้างข้อมูลภายในทั้งหมด. |

## ดูเพิ่มเติม

* คลาส [BaseHeaderFooterManager](../baseheaderfootermanager/)
* คลาส [IPresentationHeaderFooterManager](../ipresentationheaderfootermanager/)
* เนมสเปซ [Aspose::Slides](../)
* ไลบรารี [Aspose.Slides](../../)