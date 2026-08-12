---
title: IMasterNotesSlideHeaderFooterManager
second_title: Aspose.Slides สำหรับ C++ API Reference
description: เป็นตัวจัดการที่เก็บพฤติกรรมของส่วนท้ายของสไลด์บันทึกหลัก, ตัวแสดงตำแหน่งวันที่-เวลา, ตัวแสดงตำแหน่งหมายเลขหน้าและตัวแสดงตำแหน่งทั้งหมดของสไลด์ลูก. ตัวแสดงตำแหน่งลูกหมายถึงตัวแสดงตำแหน่งที่อยู่บนสไลด์บันทึกที่พึ่งพา. สไลด์บันทึกที่พึ่งพาใช้และพึ่งพาสตไลด์บันทึกหลัก.
type: docs
weight: 2900
url: /th/aspose.slides/imasternotesslideheaderfootermanager/
---
## IMasterNotesSlideHeaderFooterManager คลาส


Represents manager which holds behavior of the master notes slide footer, date-time, page number placeholders and all child placeholders. Child placeholders mean placeholders are contained on depending notes slides. Depending notes slides use and depend on master notes slide.

```cpp
class IMasterNotesSlideHeaderFooterManager : public virtual Aspose::Slides::IBaseHandoutNotesSlideHeaderFooterManag
```

## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | เปรียบเทียบวัตถุโดยใช้หลักการของ C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบวัตถุประเภทอ้างอิงในสไตล์ C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบวัตถุประเภทค่าในสไตล์ C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | จำลองการเปรียบเทียบจำนวนจริงแบบ C# ซึ่ง NaN สองค่าถูกถือว่าเท่ากัน แม้ตามมาตรฐาน IEC 60559:1989 NaN ไม่เท่ากับค่าใด ๆ รวมถึง NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | จำลองการเปรียบเทียบจำนวนจริงแบบ C# ซึ่ง NaN สองค่าถูกถือว่าเท่ากัน แม้ตามมาตรฐาน IEC 60559:1989 NaN ไม่เท่ากับค่าใด ๆ รวมถึง NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | ใช้สำหรับวัตถุประสงค์ภายในเท่านั้น. |
| virtual **bool** [get_IsDateTimeVisible](../ibaseslideheaderfootermanager/get_isdatetimevisible/)() | รับค่าที่บ่งชี้ว่ามีตัวแสดงตำแหน่งวันที่-เวลาอยู่. อ่านเป็น **bool**. |
| virtual **bool** [get_IsFooterVisible](../ibaseslideheaderfootermanager/get_isfootervisible/)() | รับค่าที่บ่งชี้ว่ามีตัวแสดงตำแหน่งส่วนท้ายอยู่. อ่านเป็น **bool**. |
| virtual **bool** [get_IsHeaderVisible](../ibasehandoutnotesslideheaderfootermanag/get_isheadervisible/)() | รับค่าที่บ่งชี้ว่ามีตัวแสดงตำแหน่งส่วนหัวอยู่. อ่านเป็น **bool**. |
| virtual **bool** [get_IsSlideNumberVisible](../ibaseslideheaderfootermanager/get_isslidenumbervisible/)() | รับค่าที่บ่งชี้ว่ามีตัวแสดงตำแหน่งหมายเลขหน้าอยู่. อ่าน**bool**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | รับโครงสร้างข้อมูลตัวนับอ้างอิงที่เชื่อมโยงกับอ็อบเจกต์. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | วิธีที่คล้ายกับ C# [Object.GetHashCode()](../../system/object/gethashcode/). เปิดใช้งานการแฮชอ็อบเจกต์ที่กำหนดเอง. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | รับชนิดจริงของอ็อบเจกต์. วิธีที่คล้ายกับการเรียก C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | ตรวจสอบว่าอ็อบเจกต์เป็นอินสแตนซ์ของชนิดที่อธิบายโดย targetType. วิธีที่คล้ายกับโอเปอเรเตอร์ 'is' ของ C#. |
| void [Lock](../../system/object/lock/)() | ทำการล็อกตามคำสั่ง lock() ของ C#. เรียกโดยตรงหรือใช้วัตถุส่งสัญญาณ [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | วิธีที่คล้ายกับ C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). เปิดใช้งานการโคลนประเภทที่กำหนดเอง. |
|  [Object](../../system/object/object/)() | สร้างอ็อบเจกต์. ตั้งค่าโครงสร้างข้อมูลภายในทั้งหมด. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | คอนสตรัคเตอร์คัดลอก. จริง ๆ แล้วไม่ได้คัดลอกอะไร เพียงตั้งค่าอ็อบเจกต์ใหม่และเปิดใช้งานการคัดลอกสร้างซับคลาส. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | โอเปอเรเตอร์การกำหนดค่า. จริง ๆ แล้วไม่ได้คัดลอกอะไร เพียงตั้งค่าอ็อบเจกต์ใหม่และเปิดใช้งานการคัดลอกสร้างซับคลาส. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | เปรียบเทียบอ็อบเจกต์โดยอ้างอิง. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | เปรียบเทียบอ็อบเจกต์โดยอ้างอิง. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | เปรียบเทียบอ้างอิงวัตถุประเภทค่า กับ nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | การทำพิเศษของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีสตริงและ nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | การทำพิเศษของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีสตริง. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | ลดค่าตัวนับอ้างอิงที่แชร์โดยค่าที่ระบุ. |
| virtual void [SetDateTimeAndChildDateTimesText](./setdatetimeandchilddatetimestext/)([System::String](../../system/string/)) | ตั้งข้อความให้กับตัวแสดงตำแหน่งวันที่-เวลาในสไลด์บันทึกหลักและตัวแสดงตำแหน่งวันที่-เวลาในสไลด์ลูกทั้งหมด. ตัวแสดงตำแหน่งลูกหมายถึงตัวแสดงตำแหน่งที่อยู่บนสไลด์บันทึกที่พึ่งพา. สไลด์บันทึกที่พึ่งพาใช้และพึ่งพาสตไลด์บันทึกหลัก. |
| virtual void [SetDateTimeAndChildDateTimesVisibility](./setdatetimeandchilddatetimesvisibility/)(**bool**) | เปลี่ยนการแสดงผลของตัวแสดงตำแหน่งวันที่-เวลาในสไลด์บันทึกหลักและตัวแสดงตำแหน่งวันที่-เวลาในสไลด์ลูกทั้งหมด. ตัวแสดงตำแหน่งลูกหมายถึงตัวแสดงตำแหน่งที่อยู่บนสไลด์บันทึกที่พึ่งพา. สไลด์บันทึกที่พึ่งพาใช้และพึ่งพาสตไลด์บันทึกหลัก. |
| virtual void [SetDateTimeText](../ibaseslideheaderfootermanager/setdatetimetext/)([System::String](../../system/string/)) | ตั้งข้อความให้กับตัวแสดงตำแหน่งวันที่-เวลาในสไลด์. |
| virtual void [SetDateTimeVisibility](../ibaseslideheaderfootermanager/setdatetimevisibility/)(**bool**) | เปลี่ยนการแสดงผลของตัวแสดงตำแหน่งวันที่-เวลาในสไลด์. |
| virtual void [SetFooterAndChildFootersText](./setfooterandchildfooterstext/)([System::String](../../system/string/)) | ตั้งข้อความให้กับตัวแสดงตำแหน่งส่วนท้ายในสไลด์บันทึกหลักและตัวแสดงตำแหน่งส่วนท้ายในสไลด์ลูกทั้งหมด. ตัวแสดงตำแหน่งลูกหมายถึงตัวแสดงตำแหน่งที่อยู่บนสไลด์บันทึกที่พึ่งพา. สไลด์บันทึกที่พึ่งพาใช้และพึ่งพาสตไลด์บันทึกหลัก. |
| virtual void [SetFooterAndChildFootersVisibility](./setfooterandchildfootersvisibility/)(**bool**) | เปลี่ยนการแสดงผลของตัวแสดงตำแหน่งส่วนท้ายในสไลด์บันทึกหลักและตัวแสดงตำแหน่งส่วนท้ายในสไลด์ลูกทั้งหมด. ตัวแสดงตำแหน่งลูกหมายถึงตัวแสดงตำแหน่งที่อยู่บนสไลด์บันทึกที่พึ่งพา. สไลด์บันทึกที่พึ่งพาใช้และพึ่งพาสตไลด์บันทึกหลัก. |
| virtual void [SetFooterText](../ibaseslideheaderfootermanager/setfootertext/)([System::String](../../system/string/)) | ตั้งข้อความให้กับตัวแสดงตำแหน่งส่วนท้ายในสไลด์. |
| virtual void [SetFooterVisibility](../ibaseslideheaderfootermanager/setfootervisibility/)(**bool**) | เปลี่ยนการแสดงผลของตัวแสดงตำแหน่งส่วนท้ายในสไลด์. |
| virtual void [SetHeaderAndChildHeadersText](./setheaderandchildheaderstext/)([System::String](../../system/string/)) | ตั้งข้อความให้กับตัวแสดงตำแหน่งส่วนหัวในสไลด์บันทึกหลักและตัวแสดงตำแหน่งส่วนหัวในสไลด์ลูกทั้งหมด. ตัวแสดงตำแหน่งลูกหมายถึงตัวแสดงตำแหน่งที่อยู่บนสไลด์บันทึกที่พึ่งพา. สไลด์บันทึกที่พึ่งพาใช้และพึ่งพาสตไลด์บันทึกหลัก. |
| virtual void [SetHeaderAndChildHeadersVisibility](./setheaderandchildheadersvisibility/)(**bool**) | เปลี่ยนการแสดงผลของตัวแสดงตำแหน่งส่วนหัวในสไลด์บันทึกหลักและตัวแสดงตำแหน่งส่วนหัวในสไลด์ลูกทั้งหมด. ตัวแสดงตำแหน่งลูกหมายถึงตัวแสดงตำแหน่งที่อยู่บนสไลด์บันทึกที่พึ่งพา. สไลด์บันทึกที่พึ่งพาใช้และพึ่งพาสตไลด์บันทึกหลัก. |
| virtual void [SetHeaderText](../ibasehandoutnotesslideheaderfootermanag/setheadertext/)([System::String](../../system/string/)) | ตั้งข้อความให้กับตัวแสดงตำแหน่งส่วนหัวในสไลด์. |
| virtual void [SetHeaderVisibility](../ibasehandoutnotesslideheaderfootermanag/setheadervisibility/)(**bool**) | เปลี่ยนการแสดงผลของตัวแสดงตำแหน่งส่วนหัวในสไลด์. |
| virtual void [SetSlideNumberAndChildSlideNumbersVisibility](./setslidenumberandchildslidenumbersvisibility/)(**bool**) | เปลี่ยนการแสดงผลของตัวแสดงตำแหน่งหมายเลขหน้าในสไลด์บันทึกหลักและตัวแสดงตำแหน่งหมายเลขหน้าในสไลด์ลูกทั้งหมด. ตัวแสดงตำแหน่งลูกหมายถึงตัวแสดงตำแหน่งที่อยู่บนสไลด์บันทึกที่พึ่งพา. สไลด์บันทึกที่พึ่งพาใช้และพึ่งพาสตไลด์บันทึกหลัก. |
| virtual void [SetSlideNumberVisibility](../ibaseslideheaderfootermanager/setslidenumbervisibility/)(**bool**) | เปลี่ยนการแสดงผลของตัวแสดงตำแหน่งหมายเลขหน้าสไลด์. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | ตั้งเทมพลิทอากิวเมนต์ที่ n ให้เป็นพอยน์เตอร์แบบ weak (แทนที่ shared). อนุญาตให้สลับพอยน์เตอร์ในคอนเทนเนอร์เป็นโหมด weak. |
| int [SharedCount](../../system/object/sharedcount/)() const | รับค่าปัจจุบันของตัวนับอ้างอิงที่แชร์. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | เพิ่มค่าตัวนับอ้างอิงที่แชร์. ไม่ควรเรียกโดยตรง; ใช้ smart pointers หรือ ThisProtector แทน. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ลดค่าตัวนับอ้างอิงที่แชร์และคืนค่า. ไม่ควรเรียกโดยตรง; ใช้ smart pointers หรือ ThisProtector แทน. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | วิธีที่คล้ายกับ C# [Object.ToString()](../../system/object/tostring/). เปิดใช้งานการแปลงอ็อบเจกต์ที่กำหนดเองเป็นสตริง. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ทำการสร้าง typeof([System.Object](../../system/object/)) ของ C#. |
| void [Unlock](../../system/object/unlock/)() | ทำการปลดล็อกตามคำสั่ง lock() ของ C#. เรียกโดยตรงหรือใช้วัตถุส่งสัญญาณ [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | เพิ่มค่าตัวนับอ้างอิงแบบ weak. ไม่ควรเรียกโดยตรง; ใช้ smart pointers หรือ ThisProtector แทน. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ลดค่าตัวนับอ้างอิงแบบ weak. ไม่ควรเรียกโดยตรง; ใช้ smart pointers หรือ ThisProtector แทน. |
| virtual  [~Object](../../system/object/~object/)() | ทำลายอ็อบเจกต์. ปล่อยโครงสร้างข้อมูลภายในทั้งหมด. |

## ดูเพิ่มเติม

* คลาส [IBaseHandoutNotesSlideHeaderFooterManag](../ibasehandoutnotesslideheaderfootermanag/)
* เนมสเปซ [Aspose::Slides](../)
* ไลบรารี [Aspose.Slides](../../)