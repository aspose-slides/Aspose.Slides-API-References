---
title: IMasterSlideHeaderFooterManager
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: เป็นตัวจัดการที่กำหนดพฤติกรรมของตัวแทนส่วนท้ายของสไลด์หลัก, ตัวแทนวันและเวลา, ตัวแทนหมายเลขหน้า และตัวแทนทั้งหมดของสไลด์ลูก. ตัวแทนสไลด์ลูกหมายถึงตัวแทนที่อยู่บนสไลด์เลย์เอาต์ที่ขึ้นอยู่และสไลด์ที่ขึ้นอยู่. สไลด์เลย์เอาต์ที่ขึ้นอยู่และสไลด์เหล่านั้นใช้และพึ่งพาสไลด์หลัก.
type: docs
weight: 2952
url: /th/aspose.slides/imasterslideheaderfootermanager/
---
## IMasterSlideHeaderFooterManager คลาส

Represents manager which holds behavior of the master slide footer, date-time, page number placeholders and all child placeholders. Child placeholders mean placeholders are contained on depending layout slides and depending slides. Depending layout slides and slides use and depend on master slide.

```cpp
class IMasterSlideHeaderFooterManager : public virtual Aspose::Slides::IBaseSlideHeaderFooterManager
```

## เมธอด

| Method | Description |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | เปรียบเทียบวัตถุโดยใช้ความหมายของ C# [Object.Equals](../../system/object/equals/) |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบวัตถุประเภทอ้างอิงในสไตล์ C# |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบวัตถุประเภทค่าในสไตล์ C# |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | เลียนแบบการเปรียบเทียบจุดลอยของสไตล์ C# ที่ NaN สองค่าได้รับการถือว่าเท่ากัน แม้ว่าตาม IEC 60559:1989 NaN จะไม่เท่ากับค่าใด ๆ รวมถึง NaN ด้วย |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | เลียนแบบการเปรียบเทียบจุดลอยของสไตล์ C# ที่ NaN สองค่าได้รับการถือว่าเท่ากัน แม้ว่าตาม IEC 60559:1989 NaN จะไม่เท่ากับค่าใด ๆ รวมถึง NaN ด้วย |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | เพื่อการใช้งานภายในเท่านั้น |
| virtual **bool** [get_IsDateTimeVisible](../ibaseslideheaderfootermanager/get_isdatetimevisible/)() | รับค่าที่บ่งบอกว่ามีตัวแทนวันและเวลาอยู่. Read**bool**. |
| virtual **bool** [get_IsFooterVisible](../ibaseslideheaderfootermanager/get_isfootervisible/)() | รับค่าที่บ่งบอกว่ามีตัวแทนส่วนท้ายอยู่. Read **bool**. |
| virtual **bool** [get_IsSlideNumberVisible](../ibaseslideheaderfootermanager/get_isslidenumbervisible/)() | รับค่าที่บ่งบอกว่ามีตัวแทนหมายเลขหน้าว่างอยู่. Read**bool**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | รับโครงสร้างข้อมูลตัวนับการอ้างอิงที่เชื่อมโยงกับวัตถุ |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | เป็นการทำงานแบบเดียวกับเมธอด C# [Object.GetHashCode()](../../system/object/gethashcode/). เปิดใช้งานการแฮชของวัตถุที่กำหนดเอง |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | รับชนิดจริงของวัตถุ. เป็นการทำงานแบบเดียวกับการเรียก C# [System.Object.GetType()](../../system/object/gettype/) |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | ตรวจสอบว่าวัตถุเป็นอินสแตนซ์ของชนิดที่อธิบายโดย targetType หรือไม่. เป็นการทำงานแบบเดียวกับออเปอเรเตอร์ 'is' ของ C# |
| void [Lock](../../system/object/lock/)() | ดำเนินการล็อกตามคำสั่ง lock() ของ C#. เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/) |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | เป็นการทำงานแบบเดียวกับเมธอด C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). เปิดใช้งานการโคลนของประเภทที่กำหนดเอง |
|  [Object](../../system/object/object/)() | สร้างวัตถุ. เริ่มต้นโครงสร้างข้อมูลภายในทั้งหมด |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | คอนสตรัคเตอร์คัดลอก. จริง ๆ แล้วไม่ได้คัดลอกอะไรเลย เพียงแค่เริ่มต้นวัตถุใหม่และเปิดใช้งานการคัดลอกสำหรับคลาสย่อย |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | โอเปอเรเตอร์การกำหนดค่า. จริง ๆ แล้วไม่ได้คัดลอกอะไรเลย เพียงแค่เริ่มต้นวัตถุใหม่และเปิดใช้งานการคัดลอกสำหรับคลาสย่อย |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | เปรียบเทียบวัตถุโดยอ้างอิง |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | เปรียบเทียบวัตถุโดยอ้างอิง |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | เปรียบเทียบการอ้างอิงของวัตถุประเภทค่ากับ nullptr |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | การปรับใช้พิเศษของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริงและ nullptr |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | การปรับใช้พิเศษของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริง |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | ลดจำนวนการอ้างอิงที่แชร์ลงตามค่าที่ระบุ |
| virtual void [SetDateTimeAndChildDateTimesText](./setdatetimeandchilddatetimestext/)([System::String](../../system/string/)) | ตั้งข้อความให้กับตัวแทนวันและเวลาในสไลด์หลักและตัวแทนวันและเวลาของสไลด์ลูกทั้งหมด. ตัวแทนสไลด์ลูกหมายถึงตัวแทนที่อยู่บนสไลด์เลย์เอาต์ที่ขึ้นอยู่และสไลด์ที่ขึ้นอยู่. สไลด์เลย์เอาต์ที่ขึ้นอยู่และสไลด์เหล่านั้นใช้และพึ่งพาสไลด์หลัก |
| virtual void [SetDateTimeAndChildDateTimesVisibility](./setdatetimeandchilddatetimesvisibility/)(**bool**) | เปลี่ยนการมองเห็นของตัวแทนวันและเวลาในสไลด์หลักและตัวแทนวันและเวลาของสไลด์ลูก. ตัวแทนสไลด์ลูกหมายถึงตัวแทนที่อยู่บนสไลด์เลย์เอาต์ที่ขึ้นอยู่และสไลด์ที่ขึ้นอยู่. สไลด์เลย์เอาต์ที่ขึ้นอยู่และสไลด์เหล่านั้นใช้และพึ่งพาสไลด์หลัก |
| virtual void [SetDateTimeText](../ibaseslideheaderfootermanager/setdatetimetext/)([System::String](../../system/string/)) | ตั้งข้อความให้กับตัวแทนวันและเวลาของสไลด์ |
| virtual void [SetDateTimeVisibility](../ibaseslideheaderfootermanager/setdatetimevisibility/)(**bool**) | เปลี่ยนการมองเห็นของตัวแทนวันและเวลาของสไลด์ |
| virtual void [SetFooterAndChildFootersText](./setfooterandchildfooterstext/)([System::String](../../system/string/)) | ตั้งข้อความให้กับตัวแทนส่วนท้ายในสไลด์หลักและตัวแทนส่วนท้ายของสไลด์ลูกทั้งหมด. ตัวแทนสไลด์ลูกหมายถึงตัวแทนที่อยู่บนสไลด์เลย์เอาต์ที่ขึ้นอยู่และสไลด์ที่ขึ้นอยู่. สไลด์เลย์เอาต์ที่ขึ้นอยู่และสไลด์เหล่านั้นใช้และพึ่งพาสไลด์หลัก |
| virtual void [SetFooterAndChildFootersVisibility](./setfooterandchildfootersvisibility/)(**bool**) | เปลี่ยนการมองเห็นของตัวแทนส่วนท้ายในสไลด์หลักและตัวแทนส่วนท้ายของสไลด์ลูกทั้งหมด. ตัวแทนสไลด์ลูกหมายถึงตัวแทนที่อยู่บนสไลด์เลย์เอาต์ที่ขึ้นอยู่และสไลด์ที่ขึ้นอยู่. สไลด์เลย์เอาต์ที่ขึ้นอยู่และสไลด์เหล่านั้นใช้และพึ่งพาสไลด์หลัก |
| virtual void [SetFooterText](../ibaseslideheaderfootermanager/setfootertext/)([System::String](../../system/string/)) | ตั้งข้อความให้กับตัวแทนส่วนท้ายของสไลด์ |
| virtual void [SetFooterVisibility](../ibaseslideheaderfootermanager/setfootervisibility/)(**bool**) | เปลี่ยนการมองเห็นของตัวแทนส่วนท้ายของสไลด์ |
| virtual void [SetSlideNumberAndChildSlideNumbersVisibility](./setslidenumberandchildslidenumbersvisibility/)(**bool**) | เปลี่ยนการมองเห็นของตัวแทนหมายเลขหน้าสไลด์หลักและตัวแทนหมายเลขหน้าของสไลด์ลูกทั้งหมด. ตัวแทนสไลด์ลูกหมายถึงตัวแทนที่อยู่บนสไลด์เลย์เอาต์ที่ขึ้นอยู่และสไลด์ที่ขึ้นอยู่. สไลด์เลย์เอาต์ที่ขึ้นอยู่และสไลด์เหล่านั้นใช้และพึ่งพาสไลด์หลัก |
| virtual void [SetSlideNumberVisibility](../ibaseslideheaderfootermanager/setslidenumbervisibility/)(**bool**) | เปลี่ยนการมองเห็นของตัวแทนหมายเลขหน้าสไลด์ |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | ตั้งเทมเพลตอาร์กิวเมนต์ที่ n'th เป็น weak pointer (แทนที่เป็น shared). อนุญาตให้สลับ pointer ในคอนเทนเนอร์เป็นโหมด weak |
| int [SharedCount](../../system/object/sharedcount/)() const | รับค่าปัจจุบันของตัวนับการอ้างอิงที่แชร์ |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | เพิ่มตัวนับการอ้างอิงที่แชร์. ไม่ควรเรียกโดยตรง; ให้ใช้ smart pointers หรือ ThisProtector แทน |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ลดและคืนค่าตัวนับการอ้างอิงที่แชร์. ไม่ควรเรียกโดยตรง; ให้ใช้ smart pointers หรือ ThisProtector แทน |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | เป็นการทำงานแบบเดียวกับเมธอด C# [Object.ToString()](../../system/object/tostring/). เปิดใช้งานการแปลงวัตถุที่กำหนดเองเป็นสตริง |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ดำเนินการสร้าง typeof([System.Object](../../system/object/)) ของ C# |
| void [Unlock](../../system/object/unlock/)() | ดำเนินการปลดล็อกตามคำสั่ง lock() ของ C#. เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/) |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | เพิ่มตัวนับการอ้างอิงแบบ weak. ไม่ควรเรียกโดยตรง; ให้ใช้ smart pointers หรือ ThisProtector แทน |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ลดตัวนับการอ้างอิงแบบ weak. ไม่ควรเรียกโดยตรง; ให้ใช้ smart pointers หรือ ThisProtector แทน |
| virtual  [~Object](../../system/object/~object/)() | ทำลายวัตถุ. ปล่อยโครงสร้างข้อมูลภายในทั้งหมด |

## ดูเพิ่มเติม

* คลาส [IBaseSlideHeaderFooterManager](../ibaseslideheaderfootermanager/)
* เนมสเปซ [Aspose::Slides](../)
* ไลบรารี [Aspose.Slides](../../)