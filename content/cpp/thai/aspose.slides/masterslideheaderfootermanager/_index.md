---
title: MasterSlideHeaderFooterManager
second_title: เอกสารอ้างอิง API ของ Aspose.Slides สำหรับ C++
description: แสดงถึงผู้จัดการที่รักษาพฤติกรรมของตัวกรอกรูปแบบส่วนท้ายสไลด์แม่, วันที่-เวลา, ตัวกรอกรูปแบบเลขหน้าและตัวกรอกรูปแบบเด็ทั้งหมด. ตัวกรอกรูปแบบเด็หมายถึงตัวกรอกรูปแบบที่อยู่บนสไลด์เลย์เอาต์ที่ขึ้นอยู่และสไลด์ที่ขึ้นอยู่. สไลด์เลย์เอาต์ที่ขึ้นอยู่และสไลด์ใช้และพึ่งพาสไลด์แม่.
type: docs
weight: 4499
url: /th/aspose.slides/masterslideheaderfootermanager/
---
## MasterSlideHeaderFooterManager คลาส

แสดงถึงผู้จัดการที่รักษาพฤติกรรมของตัวกรอกรูปแบบส่วนท้ายสไลด์แม่, วันที่-เวลา, ตัวกรอกรูปแบบเลขหน้าและตัวกรอกรูปแบบเด็ทั้งหมด. ตัวกรอกรูปแบบเด็หมายถึงตัวกรอกรูปแบบที่อยู่บนสไลด์เลย์เอาต์ที่ขึ้นอยู่และสไลด์ที่ขึ้นอยู่. สไลด์เลย์เอาต์ที่ขึ้นอยู่และสไลด์ใช้และพึ่งพาสไลด์แม่.

```cpp
class MasterSlideHeaderFooterManager : public Aspose::Slides::BaseSlideHeaderFooterManager,
                                       public Aspose::Slides::IMasterSlideHeaderFooterManager
```

## เมธอด

| Method | Description |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | เปรียบเทียบวัตถุโดยใช้หลักการของ C# [Object.Equals](../../system/object/equals/) |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบวัตถุแบบอ้างอิงในสไตล์ C# |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบวัตถุประเภทค่าในสไตล์ C# |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | จำลองการเปรียบเทียบจำนวนจริงแบบ C#-style ที่ NaN สองค่าถือเท่ากันแม้ว่าตาม IEC 60559:1989 NaN จะไม่เท่ากับค่าใด รวมถึง NaN เองด้วย |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | จำลองการเปรียบเทียบจำนวนจริงแบบ C#-style ที่ NaN สองค่า ถือเท่ากันแม้ว่าตาม IEC 60559:1989 NaN จะไม่เท่ากับค่าใด รวมถึง NaN เองด้วย |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | สำหรับการใช้งานภายในเท่านั้น |
| **bool** [get_IsDateTimeVisible](../baseslideheaderfootermanager/get_isdatetimevisible/)() override | รับค่าที่บ่งชี้ว่ามีตัวกรอกรูปแบบวันที่และเวลาอยู่. อ่าน**bool** |
| **bool** [get_IsFooterVisible](../baseslideheaderfootermanager/get_isfootervisible/)() override | รับค่าที่บ่งชี้ว่ามีตัวกรอกรูปแบบส่วนท้ายอยู่. อ่าน **bool** |
| **bool** [get_IsSlideNumberVisible](../baseslideheaderfootermanager/get_isslidenumbervisible/)() override | รับค่าที่บ่งชี้ว่ามีตัวกรอกรูปแบบเลขหน้าตัวอยู่. อ่าน**bool** |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | รับโครงสร้างข้อมูลตัวนับอ้างอิงที่เชื่อมโยงกับวัตถุ |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | เป็นแบบจำลองของเมธอด C# [Object.GetHashCode()](../../system/object/gethashcode/). เปิดใช้งานการแฮชของวัตถุที่กำหนดเอง |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | รับประเภทจริงของวัตถุ. เป็นแบบจำลองของการเรียก C# [System.Object.GetType()](../../system/object/gettype/) |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | ตรวจสอบว่าวัตถุเป็นอินสแตนซ์ของประเภทที่อธิบายโดย targetType หรือไม่. เป็นแบบจำลองของตัวดำเนินการ 'is' ของ C# |
| void [Lock](../../system/object/lock/)() | ทำงานตามคำสั่ง lock() ของ C# เพื่อทำการล็อค. เรียกโดยตรงหรือใช้วัตถุเซนท์รี [LockContext](../../system/lockcontext/) |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | เป็นแบบจำลองของเมธอด C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). เปิดการทำสำเนาชนิดที่กำหนดเอง |
|  [Object](../../system/object/object/)() | สร้างวัตถุ. เริ่มต้นโครงสร้างข้อมูลภายในทั้งหมด |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | คอนสตรัคเตอร์คัดลอก. จริง ๆ ไม่ได้คัดลอกอะไรเลย เพียงเริ่มต้นวัตถุใหม่และเปิดใช้งานการคัดลอกสำหรับซับคลาส |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | โอเปอเรเตอร์การกำหนดค่า. จริง ๆ ไม่ได้คัดลอกอะไรเลย เพียงเริ่มต้นวัตถุใหม่และเปิดใช้งานการคัดลอกสำหรับซับคลาส |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | เปรียบเทียบวัตถุโดยอ้างอิง |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | เปรียบเทียบวัตถุโดยอ้างอิง |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | เปรียบเทียบโดยอ้างอิงวัตถุประเภทค่า กับ nullptr |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | การเฉพาะเจาะจงของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริงและ nullptr |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | การเฉพาะเจาะจงของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริง |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | ลดจำนวนตัวนับอ้างอิงที่ใช้ร่วมกันโดยค่าที่ระบุ |
| void [SetDateTimeAndChildDateTimesText](./setdatetimeandchilddatetimestext/)([System::String](../../system/string/)) override | กำหนดข้อความให้กับตัวกรอกรูปแบบวันที่และเวลาในสไลด์แม่และตัวกรอกรูปแบบวันที่และเวลาเด็ทั้งหมด. ตัวกรอกรูปแบบเด็หมายถึงตัวกรอกรูปแบบที่อยู่บนสไลด์เลย์เอาต์ที่ขึ้นอยู่และสไลด์ที่ขึ้นอยู่. สไลด์เลย์เอาต์ที่ขึ้นอยู่และสไลด์ใช้และพึ่งพาสไลด์แม่ |
| void [SetDateTimeAndChildDateTimesVisibility](./setdatetimeandchilddatetimesvisibility/)(**bool**) override | ทำการเปลี่ยนการมองเห็นของตัวกรอกรูปแบบวันที่และเวลาในสไลด์แม่และตัวกรอกรูปแบบวันที่และเวลาเด็ทั้งหมด. ตัวกรอกรูปแบบเด็หมายถึงตัวกรอกรูปแบบที่อยู่บนสไลด์เลย์เอาต์ที่ขึ้นอยู่และสไลด์ที่ขึ้นอยู่. สไลด์เลย์เอาต์ที่ขึ้นอยู่และสไลด์ใช้และพึ่งพาสไลด์แม่ |
| void [SetDateTimeText](../baseslideheaderfootermanager/setdatetimetext/)([System::String](../../system/string/)) override | กำหนดข้อความให้กับตัวกรอกรูปแบบวันที่และเวลาในสไลด์ |
| void [SetDateTimeVisibility](../baseslideheaderfootermanager/setdatetimevisibility/)(**bool**) override | เปลี่ยนการมองเห็นของตัวกรอกรูปแบบวันที่และเวลาในสไลด์ |
| void [SetFooterAndChildFootersText](./setfooterandchildfooterstext/)([System::String](../../system/string/)) override | กำหนดข้อความให้กับตัวกรอกรูปแบบส่วนท้ายในสไลด์แม่และตัวกรอกรูปแบบส่วนท้ายเด็ทั้งหมด. ตัวกรอักษรเด็หมายถึงตัวกรอกรูปแบบที่อยู่บนสไลด์เลย์เอาต์ที่ขึ้นอยู่และสไลด์ที่ขึ้นอยู่. สไลด์เลย์เอาต์ที่ขึ้นอยู่และสไลด์ใช้และพึ่งพาสไลด์แม่ |
| void [SetFooterAndChildFootersVisibility](./setfooterandchildfootersvisibility/)(**bool**) override | ทำการเปลี่ยนการมองเห็นของตัวกรอกรูปแบบส่วนท้ายในสไลด์แม่และตัวกรอกรูปแบบส่วนท้ายเด็ทั้งหมด. ตัวกรอกรูปแบบเด็หมายถึงตัวกรอกรูปแบบที่อยู่บนสไลด์เลย์เอาต์ที่ขึ้นอยู่และสไลด์ที่ขึ้นอยู่. สไลด์เลย์เอาต์ที่ขึ้นอยู่และสไลด์ใช้และพึ่งพาสไลด์แม่ |
| void [SetFooterText](../baseslideheaderfootermanager/setfootertext/)([System::String](../../system/string/)) override | กำหนดข้อความให้กับตัวกรอกรูปแบบส่วนท้ายในสไลด์ |
| void [SetFooterVisibility](../baseslideheaderfootermanager/setfootervisibility/)(**bool**) override | เปลี่ยนการมองเห็นของตัวกรอกรูปแบบส่วนท้ายในสไลด์ |
| void [SetSlideNumberAndChildSlideNumbersVisibility](./setslidenumberandchildslidenumbersvisibility/)(**bool**) override | ทำการเปลี่ยนการมองเห็นของตัวกรอกรูปแบบเลขหน้าในสไลด์แม่และตัวกรอกรูปแบบเลขหน้าเด็ทั้งหมด. ตัวกรอกรูปแบบเด็หมายถึงตัวกรอกรูปแบบที่อยู่บนสไลด์เลย์เอาต์ที่ขึ้นอยู่และสไลด์ที่ขึ้นอยู่. สไลด์เลย์เอาต์ที่ขึ้นอยู่และสไลด์ใช้และพึ่งพาสไลด์แม่ |
| void [SetSlideNumberVisibility](../baseslideheaderfootermanager/setslidenumbervisibility/)(**bool**) override | เปลี่ยนการมองเห็นของตัวกรอกรูปแบบเลขหน้าในสไลด์ |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | ตั้งอาร์กิวเมนต์เทมเพลตที่ n ให้เป็น weak pointer (แทนที่ shared). อนุญาตให้สลับ pointer ในคอนเทนเนอร์เป็นโหมด weak |
| int [SharedCount](../../system/object/sharedcount/)() const | รับค่าปัจจุบันของตัวนับอ้างอิงที่ใช้ร่วมกัน |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | เพิ่มจำนวนตัวนับอ้างอิงที่ใช้ร่วมกัน. ไม่ควรเรียกโดยตรง; ควรใช้ smart pointers หรือ ThisProtector |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ลดและคืนค่าตัวนับอ้างอิงที่ใช้ร่วมกัน. ไม่ควรเรียกโดยตรง; ควรใช้ smart pointers หรือ ThisProtector |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | เป็นแบบจำลองของเมธอด C# [Object.ToString()](../../system/object/tostring/). เปิดใช้งานการแปลงวัตถุที่กำหนดเองเป็นสตริง |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ทำงานตามโครงสร้าง typeof([System.Object](../../system/object/)) ของ C# |
| void [Unlock](../../system/object/unlock/)() | ทำงานตามคำสั่ง lock() ของ C# เพื่อปลดล็อค. เรียกโดยตรงหรือใช้วัตถุเซนท์รี [LockContext](../../system/lockcontext/) |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | เพิ่มจำนวนตัวนับ weak reference. ไม่ควรเรียกโดยตรง; ควรใช้ smart pointers หรือ ThisProtector |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ลดจำนวนตัวนับ weak reference. ไม่ควรเรียกโดยตรง; ควรใช้ smart pointers หรือ ThisProtector |
| virtual  [~Object](../../system/object/~object/)() | ทำลายวัตถุ. ปล่อยโครงสร้างข้อมูลภายในทั้งหมด |

## ดูเพิ่มเติม

* คลาส [BaseSlideHeaderFooterManager](../baseslideheaderfootermanager/)
* คลาส [IMasterSlideHeaderFooterManager](../imasterslideheaderfootermanager/)
* เนมสเปซ [Aspose::Slides](../)
* ไลบรารี [Aspose.Slides](../../)