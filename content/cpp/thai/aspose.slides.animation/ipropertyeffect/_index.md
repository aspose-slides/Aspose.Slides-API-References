---
title: IPropertyEffect
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: แสดงพฤติกรรมของเอฟเฟกต์คุณสมบัติ.
type: docs
weight: 339
url: /th/aspose.slides.animation/ipropertyeffect/
---
## IPropertyEffect คลาส

แสดงพฤติกรรมของเอฟเฟกต์คุณสมบัติ

```cpp
class IPropertyEffect : public virtual Aspose::Slides::Animation::IBehavior
```

## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | เปรียบเทียบอ็อบเจกต์โดยใช้เซมานติกของ C# [Object.Equals](../../system/object/equals/) |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจกต์ประเภทอ้างอิงในสไตล์ของ C# |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจกต์ประเภทค่าในสไตล์ของ C# |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | จำลองการเปรียบเทียบแบบจุดลอยของ C# ที่สองค่า NaN ถูกพิจารณาเท่ากันแม้ว่าตาม IEC 60559:1989 NaN ไม่เท่ากับค่าทั้งหมด รวมถึง NaN ด้วย |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | จำลองการเปรียบเทียบแบบจุดลอยของ C# ที่สองค่า NaN ถูกพิจารณาเท่ากันแม้ว่าตาม IEC 60559:1989 NaN ไม่เท่ากับค่าทั้งหมด รวมถึง NaN ด้วย |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | เพื่อการใช้งานภายในเท่านั้น |
| virtual [NullableBool](../../aspose.slides/nullablebool/) [get_Accumulate](../ibehavior/get_accumulate/)() | แสดงว่าพฤติกรรมการเคลื่อนไหวถูกสะสมหรือไม่ อ่าน [NullableBool](../../aspose.slides/nullablebool/) |
| virtual [BehaviorAdditiveType](../behavioradditivetype/) [get_Additive](../ibehavior/get_additive/)() | แสดงว่าพฤติกรรมการเคลื่อนไหวปัจจุบันถูกผสานกับการเคลื่อนไหวอื่นที่กำลังทำงานหรือไม่ อ่าน [BehaviorAdditiveType](../behavioradditivetype/) |
| virtual [System::String](../../system/string/) [get_By](./get_by/)() | ระบุค่าการเลื่อนตำแหน่งเชิงสัมพันธ์สำหรับการเคลื่อนไหวเทียบกับตำแหน่งก่อนเริ่มการเคลื่อนไหว อ่าน [System::String](../../system/string/) |
| virtual [PropertyCalcModeType](../propertycalcmodetype/) [get_CalcMode](./get_calcmode/)() | ระบุโหมดการแทรกค่ากลางสำหรับการเคลื่อนไหว อ่าน [PropertyCalcModeType](../propertycalcmodetype/) |
| virtual [System::String](../../system/string/) [get_From](./get_from/)() | ระบุค่าตั้งต้นของการเคลื่อนไหว อ่าน [System::String](../../system/string/) |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPoint](../ipoint/)\> [get_Point](./get_point/)(**int32_t**) | คืนค่าจุดของการเคลื่อนไหวที่ตำแหน่งที่ระบุ |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPointCollection](../ipointcollection/)\> [get_Points](./get_points/)() | ระบุจุดของการเคลื่อนไหว อ่าน [IPointCollection](../ipointcollection/) |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBehaviorPropertyCollection](../ibehaviorpropertycollection/)\> [get_Properties](../ibehavior/get_properties/)() | แสดงคุณสมบัติของพฤติกรรม อ่านอย่างเดียว [IBehaviorPropertyCollection](../ibehaviorpropertycollection/) |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ITiming](../itiming/)\> [get_Timing](../ibehavior/get_timing/)() | แสดงคุณสมบัติการจัดเวลาสำหรับพฤติกรรมเอฟเฟกต์ อ่าน [ITiming](../itiming/) |
| virtual [System::String](../../system/string/) [get_To](./get_to/)() | ระบุค่าครบของการเคลื่อนไหว อ่าน [System::String](../../system/string/) |
| virtual [PropertyValueType](../propertyvaluetype/) [get_ValueType](./get_valuetype/)() | ระบุประเภทของค่าคุณสมบัติ อ่าน [PropertyValueType](../propertyvaluetype/) |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | รับโครงสร้างข้อมูลตัวนับอ้างอิงที่เชื่อมโยงกับอ็อบเจกต์ |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | เป็นฟังก์ชันคล้ายกับ C# [Object.GetHashCode()](../../system/object/gethashcode/). เปิดการทำแฮชของอ็อบเจกต์ที่กำหนดเอง |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | รับประเภทจริงของอ็อบเจกต์. คล้ายกับการเรียก C# [System.Object.GetType()](../../system/object/gettype/) |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | ตรวจสอบว่าอ็อบเจกต์เป็นอินสแตนซ์ของประเภทที่อธิบายโดย targetType หรือไม่. คล้ายกับตัวดำเนินการ 'is' ของ C# |
| void [Lock](../../system/object/lock/)() | ทำหน้าที่ล็อกตามคำสั่ง lock() ของ C#. เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/) |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | คล้ายกับเมธอด C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). เปิดการทำสำเนาประเภทที่กำหนดเอง |
|  [Object](../../system/object/object/)() | สร้างอ็อบเจกต์. เริ่มต้นโครงสร้างข้อมูลภายในทั้งหมด |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | คอนสตรัคเตอร์สำเนา. จริง ๆ ไม่ได้คัดลอกอะไร เพียงเริ่มต้นอ็อบเจกต์ใหม่และเปิดให้สร้างสำเนาในคลาสย่อย |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | ตัวดำเนินการกำหนดค่า. จริง ๆ ไม่ได้คัดลอกอะไร เพียงเริ่มต้นอ็อบเจกต์ใหม่และเปิดให้สร้างสำเนาในคลาสย่อย |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | เปรียบเทียบอ็อบเจกต์ตามการอ้างอิง |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | เปรียบเทียบอ็อบเจกต์ตามการอ้างอิง |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | เปรียบเทียบการอ้างอิงของอ็อบเจกต์ประเภทค่า กับ nullptr |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | การปรับเป็นพิเศษของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริงและ nullptr |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | การปรับเป็นพิเศษของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริง |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | ลดค่าเคาน์เตอร์อ้างอิงที่แชร์ลงตามค่าที่ระบุ |
| virtual void [set_Accumulate](../ibehavior/set_accumulate/)([NullableBool](../../aspose.slides/nullablebool/)) | แสดงว่าพฤติกรรมการเคลื่อนไหวถูกสะสมหรือไม่ เขียน [NullableBool](../../aspose.slides/nullablebool/) |
| virtual void [set_Additive](../ibehavior/set_additive/)([BehaviorAdditiveType](../behavioradditivetype/)) | แสดงว่าพฤติกรรมการเคลื่อนไหวปัจจุบันถูกผสานกับการเคลื่อนไหวอื่นที่กำลังทำงานหรือไม่ เขียน [BehaviorAdditiveType](../behavioradditivetype/) |
| virtual void [set_By](./set_by/)([System::String](../../system/string/)) | ระบุค่าการเลื่อนตำแหน่งเชิงสัมพันธ์สำหรับการเคลื่อนไหวเทียบกับตำแหน่งก่อนเริ่มการเคลื่อนไหว เขียน [System::String](../../system/string/) |
| virtual void [set_CalcMode](./set_calcmode/)([PropertyCalcModeType](../propertycalcmodetype/)) | ระบุโหมดการแทรกค่ากลางสำหรับการเคลื่อนไหว เขียน [PropertyCalcModeType](../propertycalcmodetype/) |
| virtual void [set_From](./set_from/)([System::String](../../system/string/)) | ระบุค่าตั้งต้นของการเคลื่อนไหว เขียน [System::String](../../system/string/) |
| virtual void [set_Points](./set_points/)([System::SharedPtr](../../system/sharedptr/)\<[IPointCollection](../ipointcollection/)\>) | ระบุจุดของการเคลื่อนไหว เขียน [IPointCollection](../ipointcollection/) |
| virtual void [set_Timing](../ibehavior/set_timing/)([System::SharedPtr](../../system/sharedptr/)\<[ITiming](../itiming/)\>) | แสดงคุณสมบัติการจัดเวลาสำหรับพฤติกรรมเอฟเฟกต์ เขียน [ITiming](../itiming/) |
| virtual void [set_To](./set_to/)([System::String](../../system/string/)) | ระบุค่าครบของการเคลื่อนไหว เขียน [System::String](../../system/string/) |
| virtual void [set_ValueType](./set_valuetype/)([PropertyValueType](../propertyvaluetype/)) | ระบุประเภทของค่าคุณสมบัติ เขียน [PropertyValueType](../propertyvaluetype/) |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | ตั้งเทมเพลตอาร์กิวเมนต์ที่ n เป็น weak pointer (แทนการใช้ shared). อนุญาตให้สลับพอยน์เตอร์ในคอนเทนเนอร์เป็นโหมด weak |
| int [SharedCount](../../system/object/sharedcount/)() const | รับค่าปัจจุบันของเคาน์เตอร์อ้างอิงที่แชร์ |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | เพิ่มค่าเคาน์เตอร์อ้างอิงที่แชร์ขึ้น. ไม่ควรเรียกโดยตรง; ควรใช้สมาร์ทพอยน์เตอร์หรือ ThisProtector |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ลดค่าเคาน์เตอร์อ้างอิงที่แชร์ลงและคืนค่า. ไม่ควรเรียกโดยตรง; ควรใช้สมาร์ทพอยน์เตอร์หรือ ThisProtector |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | คล้ายกับเมธอด C# [Object.ToString()](../../system/object/tostring/). เปิดการแปลงอ็อบเจกต์ที่กำหนดเองเป็นสตริง |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ทำหน้าที่คล้ายกับ typeof([System.Object](../../system/object/)) ของ C# |
| void [Unlock](../../system/object/unlock/)() | ทำหน้าที่ปลดล็อกตามคำสั่ง lock() ของ C#. เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/) |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | เพิ่มค่าเคาน์เตอร์อ้างอิงแบบ weak ขึ้น. ไม่ควรเรียกโดยตรง; ควรใช้สมาร์ทพอยน์เตอร์หรือ ThisProtector |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ลดค่าเคาน์เตอร์อ้างอิงแบบ weak ลง. ไม่ควรเรียกโดยตรง; ควรใช้สมาร์ทพอยน์เตอร์หรือ ThisProtector |
| virtual  [~Object](../../system/object/~object/)() | ทำลายอ็อบเจกต์. ปล่อยโครงสร้างข้อมูลภายในทั้งหมด |

## ดูเพิ่มเติม

* คลาส [IBehavior](../ibehavior/)
* เนมสเปซ [Aspose::Slides::Animation](../)
* ไลบรารี [Aspose.Slides](../../)