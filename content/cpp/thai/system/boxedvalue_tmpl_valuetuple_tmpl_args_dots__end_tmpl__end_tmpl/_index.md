---
title: BoxedValue< ValueTuple< Args... > >
second_title: Aspose.Slides สำหรับการอ้างอิง API ของ C++
description: เวอร์ชันบรรจุของ value tuple.
type: docs
weight: 118
url: /th/system/boxedvalue_tmpl_valuetuple_tmpl_args_dots__end_tmpl__end_tmpl/
---
## BoxedValue< ValueTuple< Args... > > คลาส

เวอร์ชันบรรจุของ value tuple.

```cpp
template<typename...>class BoxedValue< ValueTuple< Args... > > : public System::Runtime::CompilerServices::ITuple
```

### พารามิเตอร์เทมเพลต

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| name | ประเภทของสมาชิกใน tuple ของ Args. |

## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
|  [BoxedValue](./boxedvalue/)(const [ValueT](../valuetuple/)\&) | สร้างอ็อบเจ็กต์ [BoxedValue](../boxedvalue/) ที่เป็นตัวแทนของค่าที่ระบุที่ถูกบ็อกซ์. |
| **bool** [Equals](./equals/)([ptr](../object/ptr/)) override | กำหนดความเท่ากันของค่าที่บ็อกซ์ที่เป็นตัวแทนโดยอ็อบเจ็กต์ปัจจุบันและอ็อบเจ็กต์ที่ระบุ. |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T1\>::value\&&[IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจ็กต์ประเภทอ้างอิงในแบบ C#. |
| static **bool** [Equals](../object/equals/)(**float** const\&, **float** const\&) | จำลองการเปรียบเทียบเลขจำนวนจริงในสไตล์ C# ที่ NaN สองค่าถูกพิจารณาว่าเท่ากัน แม้ตาม IEC 60559:1989 NaN ไม่เท่ากับค่าใดๆ รวมถึง NaN. |
| static **bool** [Equals](../object/equals/)(**double** const\&, **double** const\&) | จำลองการเปรียบเทียบเลขจำนวนจริงในสไตล์ C# ที่ NaN สองค่าถูกพิจารณาว่าเท่ากัน แม้ตาม IEC 60559:1989 NaN ไม่เท่ากับค่าใดๆ รวมถึง NaN. |
| virtual **bool** [FastCast](../object/fastcast/)(const Details::FastRttiBase\&, void **) const | สำหรับการใช้งานภายในเท่านั้น. |
| Detail::SmartPtrCounter * [GetCounter](../object/getcounter/)() | รับโครงสร้างข้อมูลตัวนับอ้างอิงที่เชื่อมโยงกับอ็อบเจ็กต์. |
| int [GetHashCode](./gethashcode/)() const override | คืนค่าแฮชโค้ดสำหรับอ็อบเจ็กต์ปัจจุบัน. |
| const [System::TypeInfo](../typeinfo/)\& [GetType](./gettype/)() const override | รับประเภทจริงของอ็อบเจ็กต์. |
| virtual [SharedPtr](../sharedptr/)\<[Object](../object/)\> [idx_get](../../system.runtime.compilerservices/ituple/idx_get/)(**int32_t**) const | คืนค่าสมาชิกที่ตำแหน่ง index. |
| virtual **bool** [Is](../object/is/)(const [TypeInfo](../typeinfo/)\&) const | ตรวจสอบว่าอ็อบเจ็กต์เป็นอินสแตนซ์ของประเภทที่อธิบายโดย targetType. เป็นมาตรการคล้ายกับตัวดำเนินการ 'is' ของ C#. |
| **bool** [is](./is/)() const | กำหนดว่าประเภทของค่าที่บ็อกซ์ที่เป็นตัวแทนโดยอ็อบเจ็กต์ปัจจุบันเป็น **V** หรือไม่. |
| void [Lock](../object/lock/)() | ทำหน้าที่ล็อกตามคำสั่ง lock() ของ C#. เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../lockcontext/). |
| virtual [ptr](../object/ptr/) [MemberwiseClone](../object/memberwiseclone/)() const | เป็นมาตรการคล้ายกับเมธอด [Object.MemberwiseClone()](../object/memberwiseclone/) ของ C#. เปิดใช้งานการโคลนประเภทที่กำหนดเอง. |
|  [Object](../object/object/)() | สร้างอ็อบเจ็กต์. เริ่มต้นโครงสร้างข้อมูลภายในทั้งหมด. |
|  [Object](../object/object/)([Object](../object/) const\&) | คอนสตรัคเตอร์คัดลอก. จริงๆ แล้วไม่มีการคัดลอกอะไรเลย เพียงแค่เริ่มต้นอ็อบเจ็กต์ใหม่และเปิดใช้งานการคัดลอกสร้างซับคลาส. |
| [Object](../object/)\& [operator=](../object/operator_equal/)([Object](../object/) const\&) | โอเปเรเตอร์การกำหนดค่า. จริงๆ แล้วไม่มีการคัดลอกอะไรเลย เพียงแค่เริ่มต้นอ็อบเจ็กต์ใหม่และเปิดใช้งานการคัดลอกสร้างซับคลาส. |
| static **bool** [ReferenceEquals](../object/referenceequals/)([ptr](../object/ptr/) const\&, [ptr](../object/ptr/) const\&) | เปรียบเทียบอ็อบเจ็กต์โดยอ้างอิง. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, T const\&) | เปรียบเทียบอ็อบเจ็กต์โดยอ้างอิง. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, std::nullptr_t) | เปรียบเทียบอ็อบเจ็กต์ประเภทค่าโดยอ้างอิงกับ nullptr. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, std::nullptr_t) | เฉพาะกรณีของ [Object::ReferenceEquals](../object/referenceequals/) สำหรับสตริงและ nullptr. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, [String](../string/) const\&) | เฉพาะกรณีของ [Object::ReferenceEquals](../object/referenceequals/) สำหรับสตริง. |
| int [RemovedSharedRefs](../object/removedsharedrefs/)(int) | ลดค่าตัวนับอ้างอิงที่แชร์ลงตามค่าที่ระบุ. |
| virtual void [SetTemplateWeakPtr](../object/settemplateweakptr/)(**uint32_t**) | ตั้งค่าอาร์กิวเมนต์เทมเพลตที่ n เป็น weak pointer (แทนที่เป็น shared). อนุญาตให้สลับ pointer ในคอนเทนเนอร์เป็นโหมด weak. |
| int [SharedCount](../object/sharedcount/)() const | รับค่าปัจจุบันของตัวนับอ้างอิงที่แชร์. |
| [Object](../object/) * [SharedRefAdded](../object/sharedrefadded/)() | เพิ่มค่าตัวนับอ้างอิงที่แชร์. ไม่ควรเรียกโดยตรง; ใช้ smart pointers หรือ ThisProtector แทน. |
| int [SharedRefRemovedSafe](../object/sharedrefremovedsafe/)() | ลดค่าตัวนับอ้างอิงที่แชร์และคืนค่า. ไม่ควรเรียกโดยตรง; ใช้ smart pointers หรือ ThisProtector แทน. |
| [String](../string/) [ToString](./tostring/)() const override | คืนค่าการแสดงผลเป็นสตริงของค่าที่บ็อกซ์. |
| static const [TypeInfo](../typeinfo/)\& [Type](../object/type/)() | ทำหน้าที่ typeof([System.Object](../object/)) ของ C#. |
| const [ValueT](../valuetuple/)\& [unbox](./unbox/)() const | ถอดบ็อกซ์ค่าที่บ็อกซ์. |
| void [Unlock](../object/unlock/)() | ทำหน้าที่ปลดล็อกตามคำสั่ง lock() ของ C#. เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../object/weakrefadded/)() | เพิ่มค่าตัวนับอ้างอิงแบบ weak. ไม่ควรเรียกโดยตรง; ใช้ smart pointers หรือ ThisProtector แทน. |
| void [WeakRefRemoved](../object/weakrefremoved/)() | ลดค่าตัวนับอ้างอิงแบบ weak. ไม่ควรเรียกโดยตรง; ใช้ smart pointers หรือ ThisProtector แทน. |
| virtual  [~Object](../object/~object/)() | ทำลายอ็อบเจ็กต์. ปล่อยโครงสร้างข้อมูลภายในทั้งหมด. |

## ดูเพิ่มเติม

* คลาส [ITuple](../../system.runtime.compilerservices/ituple/)
* เนมสเปซ [System](../)
* ไลบรารี [Aspose.Slides](../../)