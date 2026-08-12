---
title: LayoutSlideHeaderFooterManager
second_title: Aspose.Slides สำหรับ C++ อ้างอิง API
description: เป็นตัวจัดการที่เก็บพฤติกรรมของตัวครอบส่วนท้ายสไลด์เลย์เอาต์, ตัวครอบวัน-เวลา, ตัวครอบเลขหน้า และตัวครอบลูกทั้งหมด. ตัวครอบลูกหมายถึงตัวครอบที่อยู่บนสไลด์ที่ขึ้นอยู่. สไลด์ที่ขึ้นอยู่ใช้และอิงกับสไลด์เลย์เอาต์.
type: docs
weight: 4317
url: /th/aspose.slides/layoutslideheaderfootermanager/
---
## LayoutSlideHeaderFooterManager คลาส


เป็นตัวจัดการที่เก็บพฤติกรรมของตารางส่วนท้ายสไลด์เลย์เอาต์, ตัวครอบวัน-เวลา, ตัวครอบเลขหน้า และตัวครอบลูกทั้งหมด. ตัวครอบลูกหมายถึงตัวครอบที่อยู่ในสไลด์ที่ขึ้นอยู่. สไลด์ที่ขึ้นอยู่ใช้และอิงกับสไลด์เลย์เอาต์.

```cpp
class LayoutSlideHeaderFooterManager : public Aspose::Slides::BaseSlideHeaderFooterManager,
                                       public Aspose::Slides::ILayoutSlideHeaderFooterManager
```

## เมธอด

| Method | Description |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | เปรียบเทียบอ็อบเจ็กต์โดยใช้หลักการของ C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจ็กต์ประเภทอ้างอิงในสไตล์ C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจ็กต์ประเภทค่าในสไตล์ C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | จำลองการเปรียบเทียบเลขทศนิยมสไตล์ C# ที่ NaN สองค่าถือว่าเท่ากันแม้ตามมาตรฐาน IEC 60559:1989 NaN จะไม่เท่ากับค่าใด ๆ รวมถึง NaN เอง. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | จำลองการเปรียบเทียบเลขทศนิยมสไตล์ C# ที่ NaN สองค่าถือว่าเท่ากันแม้ตามมาตรฐาน IEC 60559:1989 NaN จะไม่เท่ากับค่าใด ๆ รวมถึง NaN เอง. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | เพื่อการใช้งานภายในเท่านั้น. |
| **bool** [get_IsDateTimeVisible](../baseslideheaderfootermanager/get_isdatetimevisible/)() override | รับค่าที่ระบุว่ามีตัวครอบวัน-เวลาอยู่. อ่าน**bool**. |
| **bool** [get_IsFooterVisible](../baseslideheaderfootermanager/get_isfootervisible/)() override | รับค่าที่ระบุว่ามีตัวครอบส่วนท้ายอยู่. อ่าน **bool**. |
| **bool** [get_IsSlideNumberVisible](../baseslideheaderfootermanager/get_isslidenumbervisible/)() override | รับค่าที่ระบุว่ามีตัวครอบเลขหน้าอยู่. อ่าน**bool**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | รับโครงสร้างข้อมูลตัวนับการอ้างอิงที่เชื่อมกับอ็อบเจ็กต์. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | คล้ายเมธอด C# [Object.GetHashCode()](../../system/object/gethashcode/). เปิดใช้งานการทำแฮชของอ็อบเจ็กต์ที่กำหนดเอง. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | รับประเภทจริงของอ็อบเจ็กต์. คล้ายการเรียก C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | ตรวจสอบว่าอ็อบเจ็กต์เป็นอินสแตนซ์ของประเภทที่ targetType ระบุหรือไม่. คล้ายกับออปเรเตอร์ 'is' ของ C#. |
| void [Lock](../../system/object/lock/)() | ทำหน้าที่ล็อกตามคำสั่ง lock() ของ C#. เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | คล้ายเมธอด C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). เปิดใช้งานการโคลนประเภทที่กำหนดเอง. |
|  [Object](../../system/object/object/)() | สร้างอ็อบเจ็กต์. เริ่มต้นโครงสร้างข้อมูลภายในทั้งหมด. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | คอนสตรัคเตอร์สำเนา. จริง ๆ แล้วไม่ได้คัดลอกอะไรเลย เพียงเริ่มต้นอ็อบเจ็กต์ใหม่และเปิดใช้งานการสำเนา subclass. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | โอเปอเรเตอร์มอบหมาย. จริง ๆ แล้วไม่ได้คัดลอกอะไรเลย เพียงเริ่มต้นอ็อบเจ็กต์ใหม่และเปิดใช้งานการสำเนา subclass. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | เปรียบเทียบอ็อบเจ็กต์โดยอ้างอิง. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | เปรียบเทียบอ็อบเจ็กต์โดยอ้างอิง. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | อ้างอิงเปรียบเทียบอ็อบเจ็กต์ประเภทค่ากับ nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | การเฉพาะสำหรับ [Object::ReferenceEquals](../../system/object/referenceequals/) ในกรณีของสตริงและ nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | การเฉพาะสำหรับ [Object::ReferenceEquals](../../system/object/referenceequals/) ในกรณีของสตริงหลายตัว. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | ลดค่าตัวนับการอ้างอิงที่แชร์ลงตามค่าที่ระบุ. |
| void [SetDateTimeAndChildDateTimesText](./setdatetimeandchilddatetimestext/)([System::String](../../system/string/)) override | กำหนดข้อความให้กับตัวครอบวัน-เวลาในสไลด์เลย์เอาต์และตัวครอบวัน-เวลาของลูกทั้งหมด. ตัวครอบลูกหมายถึงตัวครอบที่อยู่ในสไลด์ที่ขึ้นอยู่. สไลด์ที่ขึ้นอยู่ใช้และอิงกับสไลด์เลย์เอาต์. |
| void [SetDateTimeAndChildDateTimesVisibility](./setdatetimeandchilddatetimesvisibility/)(**bool**) override | เปลี่ยนการมองเห็นของตัวครอบวัน-เวลาในสไลด์เลย์เอาต์และตัวครอบวัน-เวลาของลูกทั้งหมด. ตัวครอบลูกหมายถึงตัวครอบที่อยู่ในสไลด์ที่ขึ้นอยู่. สไลด์ที่ขึ้นอยู่ใช้และอิงกับสไลด์เลย์เอาต์. |
| void [SetDateTimeText](../baseslideheaderfootermanager/setdatetimetext/)([System::String](../../system/string/)) override | กำหนดข้อความให้กับตัวครอบวัน-เวลาในสไลด์. |
| void [SetDateTimeVisibility](../baseslideheaderfootermanager/setdatetimevisibility/)(**bool**) override | เปลี่ยนการมองเห็นของตัวครอบวัน-เวลาในสไลด์. |
| void [SetFooterAndChildFootersText](./setfooterandchildfooterstext/)([System::String](../../system/string/)) override | กำหนดข้อความให้กับตัวครอบส่วนท้ายในสไลด์เลย์เอาต์และตัวครอบส่วนท้ายของลูกทั้งหมด. ตัวครอบลูกหมายถึงตัวครอบที่อยู่ในสไลด์ที่ขึ้นอยู่. สไลด์ที่ขึ้นอยู่ใช้และอิงกับสไลด์เลย์เอาต์. |
| void [SetFooterAndChildFootersVisibility](./setfooterandchildfootersvisibility/)(**bool**) override | เปลี่ยนการมองเห็นของตัวครอบส่วนท้ายในสไลด์เลย์เอาต์และตัวครอบส่วนท้ายของลูกทั้งหมด. ตัวครอบลูกหมายถึงตัวครอบที่อยู่ในสไลด์ที่ขึ้นอยู่. สไลด์ที่ขึ้นอยู่ใช้และอิงกับสไลด์มาสเตอร์. |
| void [SetFooterText](../baseslideheaderfootermanager/setfootertext/)([System::String](../../system/string/)) override | กำหนดข้อความให้กับตัวครอบส่วนท้ายในสไลด์. |
| void [SetFooterVisibility](../baseslideheaderfootermanager/setfootervisibility/)(**bool**) override | เปลี่ยนการมองเห็นของตัวครอบส่วนท้ายในสไลด์. |
| void [SetSlideNumberAndChildSlideNumbersVisibility](./setslidenumberandchildslidenumbersvisibility/)(**bool**) override | เปลี่ยนการมองเห็นของตัวครอบเลขหน้าในสไลด์เลย์เอาต์และตัวครอบเลขหน้าของลูกทั้งหมด. ตัวครอบลูกหมายถึงตัวครอบที่อยู่ในสไลด์ที่ขึ้นอยู่. สไลด์ที่ขึ้นอยู่ใช้และอิงกับสไลด์เลย์เอาต์. |
| void [SetSlideNumberVisibility](../baseslideheaderfootermanager/setslidenumbervisibility/)(**bool**) override | เปลี่ยนการมองเห็นของตัวครอบเลขหน้าในสไลด์. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | กำหนดอาร์กิวเมนต์เทมเพลตที่ n เป็น weak pointer (แทนที่ shared). อนุญาตให้สลับพอยน์เตอร์ในคอนเทนเนอร์เป็นโหมด weak. |
| int [SharedCount](../../system/object/sharedcount/)() const | รับค่าปัจจุบันของตัวนับการอ้างอิงที่แชร์. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | เพิ่มค่าตัวนับการอ้างอิงที่แชร์. ไม่ควรเรียกโดยตรง; ควรใช้ smart pointer หรือ ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ลดค่าตัวนับการอ้างอิงที่แชร์และส่งค่ากลับ. ไม่ควรเรียกโดยตรง; ควรใช้ smart pointer หรือ ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | คล้ายเมธอด C# [Object.ToString()](../../system/object/tostring/). เปิดใช้งานการแปลงอ็อบเจ็กต์ที่กำหนดเองเป็นสตริง. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ทำหน้าที่ typeof([System.Object](../../system/object/)) ของ C#. |
| void [Unlock](../../system/object/unlock/)() | ทำหน้าที่ปลดล็อกตามคำสั่ง lock() ของ C#. เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | เพิ่มค่าตัวนับ weak reference. ไม่ควรเรียกโดยตรง; ควรใช้ smart pointer หรือ ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ลดค่าตัวนับ weak reference. ไม่ควรเรียกโดยตรง; ควรใช้ smart pointer หรือ ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | ทำลายอ็อบเจ็กต์. ปลดปล่อยโครงสร้างข้อมูลภายในทั้งหมด. |

## ดูเพิ่มเติม

* คลาส [BaseSlideHeaderFooterManager](../baseslideheaderfootermanager/)
* คลาส [ILayoutSlideHeaderFooterManager](../ilayoutslideheaderfootermanager/)
* เนมสเปซ [Aspose::Slides](../)
* ไลบรารี [Aspose.Slides](../../)