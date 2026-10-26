---
title: DefaultBoxedValue
second_title: Aspose.Slides สำหรับ C++ API อ้างอิง
description: "การดำเนินการของคลาส BoxedValue. อนุญาตให้การสร้างพิเศษ BoxingValue ถูกประกาศโดยไม่ต้องทำซ้ำโค้ดทั่วไป. อ็อบเจกต์ของคลาสนี้ควรถูกจัดสรรโดยใช้ฟังก์ชัน System::MakeObject() เท่านั้น. อย่าสร้างอินสแตนซ์ของประเภทนี้บนสแตกหรือโดยใช้ตัวโอเปอเรเตอร์ new เพราะจะทำให้เกิดข้อผิดพลาดรันไทม์และ/หรือการยืนยันค่า. ห่อหุ้มคลาสนี้ด้วยพอยน์เตอร์ System::SmartPtr เสมอและใช้พอยน์เตอร์นี้เพื่อส่งเป็นอาร์กิวเมนต์ให้ฟังก์ชัน."
type: docs
weight: 274
url: /th/system/defaultboxedvalue/
---
## DefaultBoxedValue คลาส


[BoxedValue](../boxedvalue/) คลาสการดำเนินการ. อนุญาตให้การพิเศษ BoxingValue ของมันถูกประกาศโดยไม่ต้องทำซ้ำโค้ดทั่วไป. อ็อบเจกต์ของคลาสนี้ควรถูกจัดสรรโดยใช้ฟังก์ชัน [System::MakeObject()](../makeobject/) เท่านั้น. ห้ามสร้างอินสแตนซ์ของประเภทนี้บนสแตกหรือโดยใช้ตัวโอเปอเรเตอร์ new เพราะจะทำให้เกิดข้อผิดพลาดรันไทม์และ/หรือข้อผิดพลาดการยืนยันค่า. ห่อหุ้มคลาสนี้เป็นพอยน์เตอร์ [System::SmartPtr](../smartptr/) เสมอและใช้พอยน์เตอร์นี้เพื่อส่งให้ฟังก์ชันเป็นอาร์กิวเมนต์.

```cpp
template<class T>class DefaultBoxedValue : public System::Object
```

## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
|  [DefaultBoxedValue](./defaultboxedvalue/)(const T\&) | สร้างอินสแตนซ์ใหม่ของคลาส [DefaultBoxedValue](./) ที่แสดงค่าที่ระบุ |
| **bool** [Equals](./equals/)([ptr](../object/ptr/)) override | กำหนดความเท่ากันของค่าที่บรรจุที่เป็นตัวแทนโดยอ็อบเจกต์ปัจจุบันและอ็อบเจกต์ที่ระบุ |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T1\>::value\&&[IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจกต์ประเภทอ้างอิงในสไตล์ C# |
| static **bool** [Equals](../object/equals/)(**float** const\&, **float** const\&) | จำลองการเปรียบเทียบแบบจุดลอยตามสไตล์ C# ที่ NaN สองค่าได้รับการพิจารณาเท่ากันแม้ว่า ตาม IEC 60559:1989 NaN ไม่เท่ากับค่าใด ๆ รวมถึง NaN ด้วย |
| static **bool** [Equals](../object/equals/)(**double** const\&, **double** const\&) | จำลองการเปรียบเทียบแบบจุดลอยตามสไตล์ C# ที่ NaN สองค่าได้รับการพิจารณาเท่ากันแม้ว่า ตาม IEC 60559:1989 NaN ไม่เท่ากับค่าใด ๆ รวมถึง NaN ด้วย |
| virtual **bool** [FastCast](../object/fastcast/)(const Details::FastRttiBase\&, void **) const | เพื่อการใช้งานภายในเท่านั้น |
| Detail::SmartPtrCounter * [GetCounter](../object/getcounter/)() | รับโครงสร้างข้อมูลตัวนับอ้างอิงที่เชื่อมโยงกับอ็อบเจกต์ |
| int [GetHashCode](./gethashcode/)() const override | คืนค่ารหัสแฮชสำหรับอ็อบเจกต์ปัจจุบัน |
| const [System::TypeInfo](../typeinfo/)\& [GetType](./gettype/)() const override | รับประเภทจริงของอ็อบเจกต์ |
| **bool** [is](./is/)() const | กำหนดว่าประเภทของค่าที่บรรจุซึ่งเป็นตัวแทนโดยอ็อบเจกต์ปัจจุบันคือ **V** หรือไม่ |
| virtual **bool** [Is](../object/is/)(const [TypeInfo](../typeinfo/)\&) const | ตรวจสอบว่าอ็อบเจกต์เป็นอินสแตนซ์ของประเภทที่อธิบายโดย targetType หรือไม่. ตรงกับออพอเรเตอร์ 'is' ของ C# |
| void [Lock](../object/lock/)() | ทำงานตามการล็อกของคำสั่ง C# lock(). เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../lockcontext/) |
| virtual [ptr](../object/ptr/) [MemberwiseClone](../object/memberwiseclone/)() const | เทียบเท่ากับเมธอด [Object.MemberwiseClone()](../object/memberwiseclone/) ของ C#. เปิดใช้งานการทำสำเนาของประเภทที่กำหนดเอง |
|  [Object](../object/object/)() | สร้างอ็อบเจกต์. เริ่มต้นโครงสร้างข้อมูลภายในทั้งหมด |
|  [Object](../object/object/)([Object](../object/) const\&) | คอนสตรัคเตอร์คัดลอก. ไม่ได้คัดลอกอะไรจริง ๆ เพียงแค่เริ่มต้นอ็อบเจกต์ใหม่และเปิดใช้งานการคัดลอกคอนสตรัคเตอร์ของซับคลาส |
| [Object](../object/)\& [operator=](../object/operator_equal/)([Object](../object/) const\&) | โอเปอร์เรเตอร์การมอบหมายค่า. ไม่ได้คัดลอกอะไรจริง ๆ เพียงแค่เริ่มต้นอ็อบเจกต์ใหม่และเปิดใช้งานการคัดลอกคอนสตรัคเตอร์ของซับคลาส |
| static **bool** [ReferenceEquals](../object/referenceequals/)([ptr](../object/ptr/) const\&, [ptr](../object/ptr/) const\&) | เปรียบเทียบอ็อบเจกต์โดยอ้างอิง |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, T const\&) | เปรียบเทียบอ็อบเจกต์โดยอ้างอิง |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, std::nullptr_t) | เปรียบเทียบอ้างอิงอ็อบเจกต์ประเภทค่า กับ nullptr |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, std::nullptr_t) | การพิเศษของ [Object::ReferenceEquals](../object/referenceequals/) สำหรับกรณีของสตริงและ nullptr |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, [String](../string/) const\&) | การพิเศษของ [Object::ReferenceEquals](../object/referenceequals/) สำหรับกรณีของสตริงหลายตัว |
| int [RemovedSharedRefs](../object/removedsharedrefs/)(int) | ลดจำนวนตัวนับอ้างอิงร่วมโดยค่าที่ระบุ |
| virtual void [SetTemplateWeakPtr](../object/settemplateweakptr/)(**uint32_t**) | ตั้งค่าอาร์กิวเมนต์เทมเพลตที่ n'th เป็นพอยน์เตอร์อ่อน (แทนที่เป็น shared). อนุญาตให้สลับพอยน์เตอร์ในคอนเทนเนอร์เป็นโหมดอ่อน |
| int [SharedCount](../object/sharedcount/)() const | รับค่าปัจจุบันของตัวนับอ้างอิงร่วม |
| [Object](../object/) * [SharedRefAdded](../object/sharedrefadded/)() | เพิ่มจำนวนตัวนับอ้างอิงร่วม. ไม่ควรเรียกโดยตรง; ใช้สมาร์ทพอยน์เตอร์หรือ ThisProtector แทน |
| int [SharedRefRemovedSafe](../object/sharedrefremovedsafe/)() | ลดจำนวนตัวนับอ้างอิงร่วมและคืนค่า. ไม่ควรเรียกโดยตรง; ใช้สมาร์ทพอยน์เตอร์หรือ ThisProtector แทน |
| [String](../string/) [ToString](./tostring/)() const override | คืนค่าการแสดงผลสตริงของค่าที่บรรจุ |
| static const [TypeInfo](../typeinfo/)\& [Type](../object/type/)() | ทำงานตามโครงสร้าง C# typeof([System.Object](../object/)) |
| const T\& [unbox](./unbox/)() const | ดึงค่าที่บรรจุออกจากกล่อง |
| void [Unlock](../object/unlock/)() | ทำงานตามการปลดล็อกของคำสั่ง C# lock(). เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../lockcontext/) |
| Detail::SmartPtrCounter * [WeakRefAdded](../object/weakrefadded/)() | เพิ่มจำนวนตัวนับอ้างอิงอ่อน. ไม่ควรเรียกโดยตรง; ใช้สมาร์ทพอยน์เตอร์หรือ ThisProtector แทน |
| void [WeakRefRemoved](../object/weakrefremoved/)() | ลดจำนวนตัวนับอ้างอิงอ่อน. ไม่ควรเรียกโดยตรง; ใช้สมาร์ทพอยน์เตอร์หรือ ThisProtector แทน |
| virtual  [~Object](../object/~object/)() | ทำลายอ็อบเจกต์. ปล่อยโครงสร้างข้อมูลภายในทั้งหมด |

## ดูเพิ่มเติม

* คลาส [Object](../object/)
* เนมสเปซ [System](../)
* ไลบรารี [Aspose.Slides](../../)