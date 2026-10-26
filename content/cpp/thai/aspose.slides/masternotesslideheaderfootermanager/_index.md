---
title: MasterNotesSlideHeaderFooterManager
second_title: Aspose.Slides สำหรับ C++ API Reference
description: เป็นตัวจัดการที่บรรจุพฤติกรรมของส่วนท้ายสไลด์โน้ตมาสเตอร์, ตัวแทนวันเวลา, ตัวแทนหมายเลขหน้าและตัวแทนทั้งหมดที่เป็นลูก. ตัวแทนลูกหมายถึงตัวแทนที่อยู่บนสไลด์โน้ตที่ขึ้นอยู่. สไลด์โน้ตที่ขึ้นอยู่ใช้และพึ่งพาสไลด์โน้ตมาสเตอร์.
type: docs
weight: 4460
url: /th/aspose.slides/masternotesslideheaderfootermanager/
---
## MasterNotesSlideHeaderFooterManager คลาส

เป็นตัวจัดการที่บรรจุพฤติกรรมของส่วนท้ายสไลด์โน้ตมาสเตอร์, ตัวแทนวันเวลา, ตัวแทนหมายเลขหน้าและตัวแทนทั้งหมดที่เป็นลูก. ตัวแทนลูกหมายถึงตัวแทนที่อยู่บนสไลด์โน้ตที่ขึ้นอยู่. สไลด์โน้ตที่ขึ้นอยู่ใช้และพึ่งพาสไลด์โน้ตมาสเตอร์.

```cpp
class MasterNotesSlideHeaderFooterManager : public Aspose::Slides::BaseHandoutNotesSlideHeaderFooterManager,
                                            public Aspose::Slides::IMasterNotesSlideHeaderFooterManager
```

## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | เปรียบเทียบอ็อบเจ็กต์โดยใช้ C# [Object.Equals](../../system/object/equals/) semantics. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจ็กต์ประเภทอ้างอิงในรูปแบบ C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจ็กต์ประเภทค่าในรูปแบบ C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | จำลองการเปรียบเทียบจำนวนทศนิยมแบบ C# โดยที่ NaN สองค่าถูกพิจารณาเท่ากัน ถึงแม้ตาม IEC 60559:1989 NaN ไม่เท่ากับค่าใด ๆ รวมถึง NaN ด้วย. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | จำลองการเปรียบเทียบจำนวนทศนิยมแบบ C# โดยที่ NaN สองค่าถูกพิจารณาเท่ากัน ถึงแม้ตาม IEC 60559:1989 NaN ไม่เท่ากับค่าใด ๆ รวมถึง NaN ด้วย. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | ใช้เพื่อวัตถุประสงค์ภายในเท่านั้น. |
| **bool** [get_IsDateTimeVisible](../baseslideheaderfootermanager/get_isdatetimevisible/)() override | รับค่าที่บ่งชี้ว่ามีตัวแทนวันเวลาอยู่. อ่าน **bool**. |
| **bool** [get_IsFooterVisible](../baseslideheaderfootermanager/get_isfootervisible/)() override | รับค่าที่บ่งชี้ว่ามีตัวแทนส่วนท้ายอยู่. อ่าน **bool**. |
| **bool** [get_IsHeaderVisible](../basehandoutnotesslideheaderfootermanager/get_isheadervisible/)() override | รับค่าที่บ่งชี้ว่ามีตัวแทนส่วนหัวอยู่. อ่าน **bool**. |
| **bool** [get_IsSlideNumberVisible](../baseslideheaderfootermanager/get_isslidenumbervisible/)() override | รับค่าที่บ่งชี้ว่ามีตัวแทนหมายเลขหน้าอยู่. อ่าน **bool**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | รับโครงสร้างข้อมูลตัวนับการอ้างอิงที่เชื่อมโยงกับอ็อบเจ็กต์. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | เป็นเทียบเท่ากับเมธอด C# [Object.GetHashCode()](../../system/object/gethashcode/). เปิดใช้งานการทำแฮชของอ็อบเจ็กต์ที่กำหนดเอง. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | รับประเภทจริงของอ็อบเจ็กต์. เทียบเท่าการเรียก C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | ตรวจสอบว่าอ็อบเจ็กต์เป็นอินสแตนซ์ของประเภทที่อธิบายโดย targetType. เทียบเท่ากับตัวดำเนินการ 'is' ของ C#. |
| void [Lock](../../system/object/lock/)() | ทำงานตามคำสั่ง lock() ของ C#. เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | เป็นเทียบเท่ากับเมธอด C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). เปิดใช้งานการโคลนประเภทที่กำหนดเอง. |
|  [Object](../../system/object/object/)() | สร้างอ็อบเจ็กต์. เริ่มต้นโครงสร้างข้อมูลภายในทั้งหมด. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | คอนสตรัคเตอร์คัดลอก. จริง ๆ ไม่ได้คัดลอกอะไร เพียงเริ่มต้นอ็อบเจ็กต์ใหม่และเปิดใช้งานการคัดลอกสร้างซับคลาส. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | โอเปอเรเตอร์การกำหนดค่า. จริง ๆ ไม่ได้คัดลอกอะไร เพียงเริ่มต้นอ็อบเจ็กต์ใหม่และเปิดใช้งานการคัดลอกสร้างซับคลาส. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | เปรียบเทียบอ็อบเจ็กต์โดยอ้างอิง. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | เปรียบเทียบอ็อบเจ็กต์โดยอ้างอิง. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | เปรียบเทียบอ็อบเจ็กต์ประเภทค่าโดยอ้างอิงกับ nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | การเฉพาะสำหรับ [Object::ReferenceEquals](../../system/object/referenceequals/) ในกรณีของสตริงและ nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | การเฉพาะสำหรับ [Object::ReferenceEquals](../../system/object/referenceequals/) ในกรณีของสตริง. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | ลดจำนวนการอ้างอิงที่แชร์ลงตามค่าที่ระบุ. |
| void [SetDateTimeAndChildDateTimesText](./setdatetimeandchilddatetimestext/)([System::String](../../system/string/)) override | ตั้งข้อความให้กับตัวแทนวันเวลาในสไลด์มาสเตอร์และตัวแทนวันเวลาในทุก placeholder ลูก. ตัวแทนลูกหมายถึง placeholder ที่อยู่บนสไลด์โน้ตที่ขึ้นอยู่. สไลด์โน้ตที่ขึ้นอยู่ใช้และพึ่งพาสไลด์โน้ตมาสเตอร์. |
| void [SetDateTimeAndChildDateTimesVisibility](./setdatetimeandchilddatetimesvisibility/)(**bool**) override | เปลี่ยนการมองเห็นของตัวแทนวันเวลาในสไลด์มาสเตอร์และตัวแทนวันเวลาในทุก placeholder ลูก. ตัวแทนลูกหมายถึง placeholder ที่อยู่บนสไลด์โน้ตที่ขึ้นอยู่. สไลด์โน้ตที่ขึ้นอยู่ใช้และพึ่งพาสไลด์โน้ตมาสเตอร์. |
| void [SetDateTimeText](../baseslideheaderfootermanager/setdatetimetext/)([System::String](../../system/string/)) override | ตั้งข้อความให้กับตัวแทนวันเวลาในสไลด์. |
| void [SetDateTimeVisibility](../baseslideheaderfootermanager/setdatetimevisibility/)(**bool**) override | เปลี่ยนการมองเห็นของตัวแทนวันเวลาในสไลด์. |
| void [SetFooterAndChildFootersText](./setfooterandchildfooterstext/)([System::String](../../system/string/)) override | ตั้งข้อความให้กับตัวแทนส่วนท้ายในสไลด์มาสเตอร์และตัวแทนส่วนท้ายในทุก placeholder ลูก. ตัวแทนลูกหมายถึง placeholder ที่อยู่บนสไลด์โน้ตที่ขึ้นอยู่. สไลด์โน้ตที่ขึ้นอยู่ใช้และพึ่งพาสไลด์โน้ตมาสเตอร์. |
| void [SetFooterAndChildFootersVisibility](./setfooterandchildfootersvisibility/)(**bool**) override | เปลี่ยนการมองเห็นของตัวแทนส่วนท้ายในสไลด์มาสเตอร์และตัวแทนส่วนท้ายในทุก placeholder ลูก. ตัวแทนลูกหมายถึง placeholder ที่อยู่บนสไลด์โน้ตที่ขึ้นอยู่. สไลด์โน้ตที่ขึ้นอยู่ใช้และพึ่งพาสไลด์โน้ตมาสเตอร์. |
| void [SetFooterText](../baseslideheaderfootermanager/setfootertext/)([System::String](../../system/string/)) override | ตั้งข้อความให้กับตัวแทนส่วนท้ายในสไลด์. |
| void [SetFooterVisibility](../baseslideheaderfootermanager/setfootervisibility/)(**bool**) override | เปลี่ยนการมองเห็นของตัวแทนส่วนท้ายในสไลด์. |
| void [SetHeaderAndChildHeadersText](./setheaderandchildheaderstext/)([System::String](../../system/string/)) override | ตั้งข้อความให้กับตัวแทนส่วนหัวในสไลด์โน้ตมาสเตอร์และตัวแทนส่วนหัวในทุก placeholder ลูก. ตัวแทนลูกหมายถึง placeholder ที่อยู่บนสไลด์โน้ตที่ขึ้นอยู่. สไลด์โน้ตที่ขึ้นอยู่ใช้และพึ่งพาสไลด์โน้ตมาสเตอร์. |
| void [SetHeaderAndChildHeadersVisibility](./setheaderandchildheadersvisibility/)(**bool**) override | เปลี่ยนการมองเห็นของตัวแทนส่วนหัวในสไลด์โน้ตมาสเตอร์และตัวแทนส่วนหัวในทุก placeholder ลูก. ตัวแทนลูกหมายถึง placeholder ที่อยู่บนสไลด์โน้ตที่ขึ้นอยู่. สไลด์โน้ตที่ขึ้นอยู่ใช้และพึ่งพาสไลด์โน้ตมาสเตอร์. |
| void [SetHeaderText](../basehandoutnotesslideheaderfootermanager/setheadertext/)([System::String](../../system/string/)) override | ตั้งข้อความให้กับตัวแทนส่วนหัวในสไลด์. |
| void [SetHeaderVisibility](../basehandoutnotesslideheaderfootermanager/setheadervisibility/)(**bool**) override | เปลี่ยนการมองเห็นของตัวแทนส่วนหัวในสไลด์. |
| void [SetSlideNumberAndChildSlideNumbersVisibility](./setslidenumberandchildslidenumbersvisibility/)(**bool**) override | เปลี่ยนการมองเห็นของตัวแทนหมายเลขหน้าในสไลด์มาสเตอร์และตัวแทนหมายเลขหน้าในทุก placeholder ลูก. ตัวแทนลูกหมายถึง placeholder ที่อยู่บนสไลด์โน้ตที่ขึ้นอยู่. สไลด์โน้ตที่ขึ้นอยู่ใช้และพึ่งพาสไลด์โน้ตมาสเตอร์. |
| void [SetSlideNumberVisibility](../baseslideheaderfootermanager/setslidenumbervisibility/)(**bool**) override | เปลี่ยนการมองเห็นของตัวแทนหมายเลขหน้าในสไลด์. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | กำหนดอาร์กิวเมนต์เท็มเพลตที่ n ให้เป็น weak pointer (แทนที่ shared). อนุญาตให้สลับพอยน์เตอร์ในคอนเทนเนอร์เป็นโหมด weak. |
| int [SharedCount](../../system/object/sharedcount/)() const | รับค่าปัจจุบันของตัวนับการอ้างอิงที่แชร์. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | เพิ่มตัวนับการอ้างอิงที่แชร์. ไม่ควรเรียกโดยตรง; ใช้ smart pointers หรือ ThisProtector แทน. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ลดตัวนับการอ้างอิงที่แชร์และคืนค่าที่ลดลง. ไม่ควรเรียกโดยตรง; ใช้ smart pointers หรือ ThisProtector แทน. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | เทียบเท่ากับเมธอด C# [Object.ToString()](../../system/object/tostring/). เปิดใช้งานการแปลงอ็อบเจ็กต์ที่กำหนดเองเป็นสตริง. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ทำงานตามโครงสร้าง typeof([System.Object](../../system/object/)) ของ C#. |
| void [Unlock](../../system/object/unlock/)() | ทำงานตามการปลดล็อกของคำสั่ง lock() ของ C#. เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | เพิ่มตัวนับการอ้างอิงแบบ weak. ไม่ควรเรียกโดยตรง; ใช้ smart pointers หรือ ThisProtector แทน. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ลดตัวนับการอ้างอิงแบบ weak. ไม่ควรเรียกโดยตรง; ใช้ smart pointers หรือ ThisProtector แทน. |
| virtual  [~Object](../../system/object/~object/)() | ทำลายอ็อบเจ็กต์. ปล่อยโครงสร้างข้อมูลภายในทั้งหมด. |

## ดูเพิ่มเติม

* คลาส [BaseHandoutNotesSlideHeaderFooterManager](../basehandoutnotesslideheaderfootermanager/)
* คลาส [IMasterNotesSlideHeaderFooterManager](../imasternotesslideheaderfootermanager/)
* เนมสเปซ [Aspose::Slides](../)
* ไลบรารี [Aspose.Slides](../../)