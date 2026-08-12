---
title: StringBuilder
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: "บัฟเฟอร์สำหรับสะสมส่วนของสตริงเป็นช่วง ๆ ชนิดนี้สามารถจัดสรรได้ทั้งในสแตกเป็นประเภทค่า หรือในฮีปโดยใช้ฟังก์ชัน System::MakeObject() เมื่ออ็อบเจกต์ถูกจัดสรรแล้ว อย่าสับสนระหว่างการใช้สองกรณีนี้: การมีตัวชี้ SmartPtr ไปยังอ็อบเจกต์ที่จัดสรรในสแตกเป็นสิ่งต้องห้ามอย่างเคร่งครัด."
type: docs
weight: 326
url: /th/system.text/stringbuilder/
---
## StringBuilder คลาส

[Buffer](../../system/buffer/) เพื่อสะสมส่วนของสตริงเป็นช่วง ๆ. ชนิดนี้สามารถจัดสรรได้ทั้งในสแตกเป็นประเภทค่า หรือในฮีปโดยใช้ฟังก์ชัน [System::MakeObject()](../../system/makeobject/). เมื่ออ็อบเจกต์ถูกจัดสรรแล้ว อย่าสับสนระหว่างการใช้สองกรณีนี้: การมีตัวชี้ [SmartPtr](../../system/smartptr/) ไปยังอ็อบเจกต์ที่จัดสรรในสแตกเป็นสิ่งต้องห้ามอย่างเคร่งครัด.

```cpp
class StringBuilder : public System::Object
```

## เมธอด

| Method | Description |
| --- | --- |
| [StringBuilder](./) * [Append](./append/)(char_t) | เพิ่มอักขระลงใน builder. |
| [StringBuilder](./) * [Append](./append/)(char_t, int) | เพิ่มอักขระหลายตัวลงใน builder. |
| [StringBuilder](./) * [Append](./append/)(const [ArrayPtr](../../system/arrayptr/)\<char_t\>\&) | เพิ่มอาร์เรย์ของอักขระลงใน builder. |
| [StringBuilder](./) * [Append](./append/)(const [ArrayPtr](../../system/arrayptr/)\<char_t\>\&, int, int) | เพิ่มส่วนของอาร์เรย์อักขระลงใน builder. |
| [StringBuilder](./) * [Append](./append/)(const [String](../../system/string/)\&) | เพิ่มสตริงลงใน builder. |
| [StringBuilder](./) * [Append](./append/)(const [String](../../system/string/)\&, int, int) | เพิ่มส่วนของสตริงลงใน builder. |
| [StringBuilder](./) * [Append](./append/)(const [SharedPtr](../../system/sharedptr/)\<T\>\&) | เพิ่มการแสดงผลสตริงของอ็อบเจกต์ลงใน builder. |
| [StringBuilder](./) * [Append](./append/)(const [SharedPtr](../../system/sharedptr/)\<[StringBuilder](./)\>\&) | เพิ่มเนื้อหาของ builder ลงใน builder. |
| [StringBuilder](./) * [Append](./append/)(**float**) | เพิ่มค่าตัวเลขจุดลอยลงใน builder. |
| [StringBuilder](./) * [Append](./append/)(**double**) | เพิ่มค่าตัวเลขจุดลอยสองเท่าลงใน builder. |
| [StringBuilder](./) * [Append](./append/)(int) | เพิ่มค่าจำนวนเต็มลงใน builder. |
| std::enable_if\<std::is_arithmetic\<T\>::value, [StringBuilder](./) *\>::type [Append](./append/)(T) | เพิ่มค่าตัวเลขเชิงคณิตศาสตร์ลงใน builder. |
| std::enable_if\<std::is_enum\<E\>::value, [StringBuilder](./) *\>::type [Append](./append/)(E) | เพิ่มสตริงการแสดงผลของค่า enum ลงใน builder. |
| [StringBuilder](./) * [AppendFormat](./appendformat/)(const [String](../../system/string/)\&, const TArgs\&...) | เพิ่มสตริงที่ฟอร์แมตแล้วลงใน builder. |
| [StringBuilder](./) * [AppendFormat](./appendformat/)(const [SharedPtr](../../system/sharedptr/)\<[IFormatProvider](../../system/iformatprovider/)\>\&, const [String](../../system/string/)\&, const TArgs\&...) | เพิ่มสตริงที่ฟอร์แมตแล้วลงใน builder. |
| [StringBuilder](./) * [AppendLine](./appendline/)() | เพิ่มอักขระขึ้นบรรทัดใหม่ลงใน builder. |
| [StringBuilder](./) * [AppendLine](./appendline/)(const [String](../../system/string/)\&) | เพิ่มสตริงตามด้วยอักขระขึ้นบรรทัดใหม่ลงใน builder. |
| [StringBuilder](./) * [Clear](./clear/)() | ลบอักขระทั้งหมดออกจาก builder. |
| void [CopyTo](./copyto/)(int, [System::ArrayPtr](../../system/arrayptr/)\<char_t\> const\&, int, int) | คัดลอกข้อมูลของ builder ไปยังตำแหน่งอาร์เรย์ที่มีอยู่. |
| **int32_t** [EnsureCapacity](./ensurecapacity/)(**int32_t**) | ทำให้ความจุของ [System.Text.StringBuilder](./) ตัวนี้มีค่าขั้นต่ำตามค่าที่ระบุ. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | เปรียบเทียบอ็อบเจกต์โดยใช้ไวยากรณ์ของ C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจกต์ประเภทอ้างอิงแบบสไตล์ C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจกต์ประเภทค่าแบบสไตล์ C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | จำลองการเปรียบเทียบตัวเลขจุดลอยสไตล์ C# ซึ่ง NaN สองค่าเทียบเท่ากันแม้ว่าตาม IEC 60559:1989 NaN ไม่เท่ากับค่าใด ๆ รวมถึง NaN เอง. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | จำลองการเปรียบเทียบตัวเลขจุดลอยสองเท่าสไตล์ C# ซึ่ง NaN สองค่าเทียบเท่ากันแม้ว่าตาม IEC 60559:1989 NaN ไม่เท่ากับค่าใด ๆ รวมถึง NaN เอง. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | สำหรับการใช้งานภายในเท่านั้น. |
| int [get_Capacity](./get_capacity/)() const | รับความจุปัจจุบันของ string builder. |
| int [get_Length](./get_length/)() const | รับความยาวของสตริงที่อยู่ใน builder ปัจจุบัน. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | รับโครงสร้างข้อมูลตัวนับอ้างอิงที่เชื่อมโยงกับอ็อบเจกต์. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | เป็นฟังก์ชันที่คล้ายกับเมธอด C# [Object.GetHashCode()](../../system/object/gethashcode/). ทำให้สามารถแฮชอ็อบเจกต์กำหนดเองได้. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | รับประเภทจริงของอ็อบเจกต์. เป็นฟังก์ชันคล้ายกับการเรียก C# [System.Object.GetType()](../../system/object/gettype/). |
| char_t [idx_get](./idx_get/)(int) const | รับอักขระที่ตำแหน่งที่ระบุ. |
| void [idx_set](./idx_set/)(int, char_t) | ตั้งค่าอักขระที่ตำแหน่งที่ระบุ. |
| [StringBuilder](./) * [Insert](./insert/)(int, const [String](../../system/string/)\&) | แทรกสตริงลงในตำแหน่งคงที่ของ builder. |
| [StringBuilder](./) * [Insert](./insert/)(**int32_t**, const [String](../../system/string/)\&, **int32_t**) | แทรกสตริงซ้ำลงในตำแหน่งคงที่ของ builder. |
| [StringBuilder](./) * [Insert](./insert/)(int, char_t) | แทรกอักขระลงในตำแหน่งคงที่ของ builder. |
| [StringBuilder](./) * [Insert](./insert/)(int, const [System::ArrayPtr](../../system/arrayptr/)\<char_t\>\&, int, int) | แทรกอักขระหลายตัวลงในตำแหน่งคงที่ของ builder. |
| std::enable_if\<std::is_arithmetic\<T\>::value, [StringBuilder](./) *\>::type [Insert](./insert/)(int, T) | แทรกค่าเชิงคณิตศาสตร์ลงในตำแหน่งคงที่ของ builder. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | ตรวจสอบว่าอ็อบเจกต์เป็นอินสแตนซ์ของชนิดที่อธิบายโดย targetType. คล้ายกับออปเพอเรเตอร์ 'is' ของ C#. |
| void [Lock](../../system/object/lock/)() | ทำงานตามคำสั่ง lock() ของ C# เพื่อทำการล็อก. เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | เป็นฟังก์ชันที่คล้ายกับเมธอด C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). ทำให้คล cloning ชนิดกำหนดเองได้. |
|  [Object](../../system/object/object/)() | สร้างอ็อบเจกต์. เริ่มต้นโครงสร้างข้อมูลภายในทั้งหมด. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | ตัวสร้างสำเนา. ไม่ได้คัดลอกอะไรเลยจริง ๆ เพียงเริ่มต้นอ็อบเจกต์ใหม่และเปิดให้สร้างสำเนาสำหรับคลาสย่อย. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | ตัวดำเนินการกำหนดค่า. ไม่ได้คัดลอกอะไรเลยจริง ๆ เพียงเริ่มต้นอ็อบเจกต์ใหม่และเปิดให้สร้างสำเนาสำหรับคลาสย่อย. |
| char_t [operator[]](./operator[]/)(int) const | รับอักขระที่ตำแหน่งที่ระบุ. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | เปรียบเทียบอ็อบเจกต์โดยอ้างอิง. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | เปรียบเทียบอ็อบเจกต์โดยอ้างอิง. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | เปรียบเทียบอ็อบเจกต์ประเภทค่ากับ nullptr โดยอ้างอิง. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | ความพิเศษของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีสตริงและ nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | ความพิเศษของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีสตริงหลายรายการ. |
| [StringBuilder](./) * [Remove](./remove/)(int, int) | ลบส่วนของ builder. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | ลดค่าตัวนับอ้างอิงร่วมตามค่าที่ระบุ. |
| [StringBuilder](./) * [Replace](./replace/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | แทนที่ส่วนย่อยใน builder. |
| [StringBuilder](./) * [Replace](./replace/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, int, int) | แทนที่ส่วนย่อยในช่วงของ builder. |
| [StringBuilder](./) * [Replace](./replace/)(char_t, char_t) | แทนที่อักขระใน builder. |
| [StringBuilder](./) * [Replace](./replace/)(char_t, char_t, int, int) | แทนที่อักขระในช่วงของ builder. |
| void [set_Capacity](./set_capacity/)(int) | ตั้งค่าความจุปัจจุบันของ string builder. |
| void [set_Length](./set_length/)(int) | ตัดหรือขยาย string builder ไปยังความยาวที่ระบุ. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | ตั้งค่าเทมเพลตอาร์กิวเมนต์ที่ n ให้เป็น weak pointer (แทนที่จะเป็น shared). อนุญาตให้สลับ pointer ใน container เป็นโหมด weak. |
| int [SharedCount](../../system/object/sharedcount/)() const | รับค่าปัจจุบันของตัวนับอ้างอิงร่วม. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | เพิ่มค่าตัวนับอ้างอิงร่วม. ไม่ควรเรียกโดยตรง; ใช้ smart pointer หรือ ThisProtector แทน. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ลดค่าตัวนับอ้างอิงร่วมและคืนค่า. ไม่ควรเรียกโดยตรง; ใช้ smart pointer หรือ ThisProtector แทน. |
|  [StringBuilder](./stringbuilder/)() | ตัวสร้าง. |
|  [StringBuilder](./stringbuilder/)(int) | ตัวสร้าง. |
|  [StringBuilder](./stringbuilder/)(const [String](../../system/string/)\&) | ตัวสร้าง. |
|  [StringBuilder](./stringbuilder/)(const [String](../../system/string/)\&, int) | ตัวสร้าง. |
|  [StringBuilder](./stringbuilder/)(const [String](../../system/string/)\&, int, int, int) | ตัวสร้าง. |
| [String](../../system/string/) [ToString](./tostring/)() const override | รับสตริงที่อยู่ใน builder ปัจจุบัน. |
| [String](../../system/string/) [ToString](./tostring/)(int, int) const | รับส่วนย่อยของสตริงที่อยู่ใน builder ปัจจุบัน. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ทำงานคล้าย typeof([System.Object](../../system/object/)) ของ C#. |
| void [Unlock](../../system/object/unlock/)() | ทำงานตามคำสั่ง lock() ของ C# เพื่อปลดล็อก. เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | เพิ่มค่าตัวนับอ้างอิงแบบ weak. ไม่ควรเรียกโดยตรง; ใช้ smart pointer หรือ ThisProtector แทน. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ลดค่าตัวนับอ้างอิงแบบ weak. ไม่ควรเรียกโดยตรง; ใช้ smart pointer หรือ ThisProtector แทน. |
| virtual  [~Object](../../system/object/~object/)() | ทำลายอ็อบเจกต์. ปล่อยโครงสร้างข้อมูลภายในทั้งหมด. |
|  [~StringBuilder](./~stringbuilder/)() | ตัวทำลาย. |
## ดูเพิ่มเติม

* คลาส [Object](../../system/object/)
* เนมสเปซ [System::Text](../)
* ไลบรารี [Aspose.Slides](../../)