---
title: ColorMatrix
second_title: Aspose.Slides สำหรับ C++ API Reference
description: "แสดงถึงเมทริกซ์ 5x5 ที่บรรจุตำแหน่งพิกัดของพื้นที่สี RGBAW. วัตถุของคลาสนี้ควรสร้างขึ้นโดยใช้ฟังก์ชัน System::MakeObject() เท่านั้น. อย่าสร้างอินสแตนซ์ของประเภทนี้บนสแตกหรือโดยใช้ operator new เพราะจะทำให้เกิดข้อผิดพลาดขณะทำงานและ/หรือการตรวจสอบข้อขัดแย้ง. ควรห่อคลาสนี้ด้วยพอยน์เตอร์ System::SmartPtr และใช้พอยน์เตอร์นี้เพื่อส่งเป็นอาร์กิวเมนต์ให้กับฟังก์ชัน."
type: docs
weight: 27
url: /th/system.drawing.imaging/colormatrix/
---
## ColorMatrix คลาส

แสดงถึงเมทริกซ์ 5x5 ที่บรรจุตำแหน่งพิกัดสำหรับสี RGBAW. วัตถุของคลาสนี้ควรสร้างขึ้นโดยใช้ฟังก์ชัน [System::MakeObject()](../../system/makeobject/) เท่านั้น. อย่าสร้างอินสแตนซ์ของประเภทนี้บนสแตกหรือโดยใช้ operator new เพราะจะทำให้เกิดข้อผิดพลาดขณะทำงานและ/หรือการตรวจสอบข้อขัดแย้ง. ควรห่อคลาสนี้ด้วยพอยน์เตอร์ [System::SmartPtr](../../system/smartptr/) และใช้พอยน์เตอร์นี้เพื่อส่งเป็นอาร์กิวเมนต์ให้กับฟังก์ชัน.

```cpp
class ColorMatrix : public System::Object
```

## เมธอด

| Method | คำอธิบาย |
| --- | --- |
|  [ColorMatrix](./colormatrix/)() | สร้างอินสแตนซ์ใหม่ของคลาส [ColorMatrix](./) และเริ่มต้นด้วยค่าของเมทริกซ์เอกลักษณ์ |
|  [ColorMatrix](./colormatrix/)(const [System::ArrayPtr](../../system/arrayptr/)\<[System::ArrayPtr](../../system/arrayptr/)\<**float**\>\>\&) | สร้างอินสแตนซ์ใหม่ของคลาส [ColorMatrix](./) และเริ่มต้นด้วยค่าที่ระบุ |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | เปรียบเทียบวัตถุโดยใช้เซมานติกของ C# [Object.Equals](../../system/object/equals/) |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบวัตถุประเภทอ้างอิงในสไตล์ของ C# |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบวัตถุประเภทค่าในสไตล์ของ C# |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | จำลองการเปรียบเทียบจุดลอยในสไตล์ C# ที่ NaN สองค่าถือว่าเท่ากันแม้ตามมาตรฐาน IEC 60559:1989 NaN จะไม่เท่ากับค่าใด ๆ รวมถึง NaN เอง |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | จำลองการเปรียบเทียบจุดลอยในสไตล์ C# ที่ NaN สองค่าถือว่าเท่ากันแม้ตามมาตรฐาน IEC 60559:1989 NaN จะไม่เท่ากับค่าใด ๆ รวมถึง NaN เอง |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | ใช้เพื่อวัตถุประสงค์ภายในเท่านั้น |
| **float** [get_Matrix00](./get_matrix00/)() const | คืนค่าที่แถวที่ 0 และคอลัมน์ที่ 0 |
| **float** [get_Matrix01](./get_matrix01/)() const | คืนค่าที่แถวที่ 0 และคอลัมน์ที่ 1 |
| **float** [get_Matrix02](./get_matrix02/)() const | คืนค่าที่แถวที่ 0 และคอลัมน์ที่ 2 |
| **float** [get_Matrix03](./get_matrix03/)() const | คืนค่าที่แถวที่ 0 และคอลัมน์ที่ 3 |
| **float** [get_Matrix04](./get_matrix04/)() const | คืนค่าที่แถวที่ 0 และคอลัมน์ที่ 4 |
| **float** [get_Matrix10](./get_matrix10/)() const | คืนค่าที่แถวที่ 1 และคอลัมน์ที่ 0 |
| **float** [get_Matrix11](./get_matrix11/)() const | คืนค่าที่แถวที่ 1 และคอลัมน์ที่ 1 |
| **float** [get_Matrix12](./get_matrix12/)() const | คืนค่าที่แถวที่ 1 และคอลัมน์ที่ 2 |
| **float** [get_Matrix13](./get_matrix13/)() const | คืนค่าที่แถวที่ 1 และคอลัมน์ที่ 3 |
| **float** [get_Matrix14](./get_matrix14/)() const | คืนค่าที่แถวที่ 1 และคอลัมน์ที่ 4 |
| **float** [get_Matrix20](./get_matrix20/)() const | คืนค่าที่แถวที่ 2 และคอลัมน์ที่ 0 |
| **float** [get_Matrix21](./get_matrix21/)() const | คืนค่าที่แถวที่ 2 และคอลัมน์ที่ 1 |
| **float** [get_Matrix22](./get_matrix22/)() const | คืนค่าที่แถวที่ 2 และคอลัมน์ที่ 2 |
| **float** [get_Matrix23](./get_matrix23/)() const | คืนค่าที่แถวที่ 2 และคอลัมน์ที่ 3 |
| **float** [get_Matrix24](./get_matrix24/)() const | คืนค่าที่แถวที่ 2 และคอลัมน์ที่ 4 |
| **float** [get_Matrix30](./get_matrix30/)() const | คืนค่าที่แถวที่ 3 และคอลัมน์ที่ 0 |
| **float** [get_Matrix31](./get_matrix31/)() const | คืนค่าที่แถวที่ 3 และคอลัมน์ที่ 1 |
| **float** [get_Matrix32](./get_matrix32/)() const | คืนค่าที่แถวที่ 3 และคอลัมน์ที่ 2 |
| **float** [get_Matrix33](./get_matrix33/)() const | คืนค่าที่แถวที่ 3 และคอลัมน์ที่ 3 |
| **float** [get_Matrix34](./get_matrix34/)() const | คืนค่าที่แถวที่ 3 และคอลัมน์ที่ 4 |
| **float** [get_Matrix40](./get_matrix40/)() const | คืนค่าที่แถวที่ 4 และคอลัมน์ที่ 0 |
| **float** [get_Matrix41](./get_matrix41/)() const | คืนค่าที่แถวที่ 4 และคอลัมน์ที่ 1 |
| **float** [get_Matrix42](./get_matrix42/)() const | คืนค่าที่แถวที่ 4 และคอลัมน์ที่ 2 |
| **float** [get_Matrix43](./get_matrix43/)() const | คืนค่าที่แถวที่ 4 และคอลัมน์ที่ 3 |
| **float** [get_Matrix44](./get_matrix44/)() const | คืนค่าที่แถวที่ 4 และคอลัมน์ที่ 4 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | รับโครงสร้างข้อมูลตัวนับอ้างอิงที่เชื่อมโยงกับวัตถุ |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | เป็นอ analogue ของเมธอด C# [Object.GetHashCode()](../../system/object/gethashcode/). ทำให้สามารถแฮชวัตถุแบบกำหนดเองได้ |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | รับประเภทจริงของวัตถุ. เป็นอ analogue ของการเรียก C# [System.Object.GetType()](../../system/object/gettype/) |
| **float** [idx_get](./idx_get/)(int, int) | คืนค่าที่แถวและคอลัมน์ที่ระบุ |
| **float** [idx_set](./idx_set/)(int, int, **float**) | ตั้งค่าที่ตำแหน่งที่ระบุในเมทริกซ์ |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | ตรวจสอบว่าวัตถุเป็นอินสแตนซ์ของชนิดที่อธิบายโดย targetType หรือไม่. เป็นอ analogue ของออเปอร์าเตอร์ 'is' ของ C# |
| void [Lock](../../system/object/lock/)() | ทำงานเหมือนกับการล็อกของคำสั่ง C# lock(). เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/) |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | เป็นอ analogue ของเมธอด C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). ทำให้สามารถคล cloning ชนิดที่กำหนดเองได้ |
|  [Object](../../system/object/object/)() | สร้างวัตถุ. เริ่มต้นโครงสร้างข้อมูลภายในทั้งหมด |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | คอนสตรัคเตอร์คัดลอก. จริง ๆ แล้วไม่ได้คัดลอกอะไรเลย เพียงแค่เริ่มต้นวัตถุใหม่และเปิดใช้งานการสร้างสำเนาสำหรับซับคลาส |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | โอเปอเรเตอร์กำหนดค่า. จริง ๆ แล้วไม่ได้คัดลอกอะไรเลย เพียงแค่เริ่มต้นวัตถุใหม่และเปิดใช้งานการคัดลอกสำหรับซับคลาส |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | เปรียบเทียบวัตถุโดยอ้างอิง |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | เปรียบเทียบวัตถุโดยอ้างอิง |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | เปรียบเทียบอ้างอิงวัตถุประเภทค่า กับ nullptr |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | การแนะนำพิเศษของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริงและ nullptr |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | การแนะนำพิเศษของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริง |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | ลดค่าตัวนับอ้างอิงร่วมโดยค่าที่ระบุ |
| void [set_Matrix00](./set_matrix00/)(**float**) | ตั้งค่าที่แถวที่ 0 และคอลัมน์ที่ 0 |
| void [set_Matrix01](./set_matrix01/)(**float**) | ตั้งค่าที่แถวที่ 0 และคอลัมน์ที่ 1 |
| void [set_Matrix02](./set_matrix02/)(**float**) | ตั้งค่าที่แถวที่ 0 และคอลัมน์ที่ 2 |
| void [set_Matrix03](./set_matrix03/)(**float**) | ตั้งค่าที่แถวที่ 0 และคอลัมน์ที่ 3 |
| void [set_Matrix04](./set_matrix04/)(**float**) | ตั้งค่าที่แถวที่ 0 และคอลัมน์ที่ 4 |
| void [set_Matrix10](./set_matrix10/)(**float**) | ตั้งค่าที่แถวที่ 1 และคอลัมน์ที่ 0 |
| void [set_Matrix11](./set_matrix11/)(**float**) | ตั้งค่าที่แถวที่ 1 และคอลัมน์ที่ 1 |
| void [set_Matrix12](./set_matrix12/)(**float**) | ตั้งค่าที่แถวที่ 1 และคอลัมน์ที่ 2 |
| void [set_Matrix13](./set_matrix13/)(**float**) | ตั้งค่าที่แถวที่ 1 และคอลัมน์ที่ 3 |
| void [set_Matrix14](./set_matrix14/)(**float**) | ตั้งค่าที่แถวที่ 1 และคอลัมน์ที่ 4 |
| void [set_Matrix20](./set_matrix20/)(**float**) | ตั้งค่าที่แถวที่ 2 และคอลัมน์ที่ 0 |
| void [set_Matrix21](./set_matrix21/)(**float**) | ตั้งค่าที่แถวที่ 2 และคอลัมน์ที่ 1 |
| void [set_Matrix22](./set_matrix22/)(**float**) | ตั้งค่าที่แถวที่ 2 และคอลัมน์ที่ 2 |
| void [set_Matrix23](./set_matrix23/)(**float**) | ตั้งค่าที่แถวที่ 2 และคอลัมน์ที่ 3 |
| void [set_Matrix24](./set_matrix24/)(**float**) | ตั้งค่าที่แถวที่ 2 และคอลัมน์ที่ 4 |
| void [set_Matrix30](./set_matrix30/)(**float**) | ตั้งค่าที่แถวที่ 3 และคอลัมน์ที่ 0 |
| void [set_Matrix31](./set_matrix31/)(**float**) | ตั้งค่าที่แถวที่ 3 และคอลัมน์ที่ 1 |
| void [set_Matrix32](./set_matrix32/)(**float**) | ตั้งค่าที่แถวที่ 3 และคอลัมน์ที่ 2 |
| void [set_Matrix33](./set_matrix33/)(**float**) | ตั้งค่าที่แถวที่ 3 และคอลัมน์ที่ 3 |
| void [set_Matrix34](./set_matrix34/)(**float**) | ตั้งค่าที่แถวที่ 3 และคอลัมน์ที่ 4 |
| void [set_Matrix40](./set_matrix40/)(**float**) | ตั้งค่าที่แถวที่ 4 และคอลัมน์ที่ 0 |
| void [set_Matrix41](./set_matrix41/)(**float**) | ตั้งค่าที่แถวที่ 4 และคอลัมน์ที่ 1 |
| void [set_Matrix42](./set_matrix42/)(**float**) | ตั้งค่าที่แถวที่ 4 และคอลัมน์ที่ 2 |
| void [set_Matrix43](./set_matrix43/)(**float**) | ตั้งค่าที่แถวที่ 4 และคอลัมน์ที่ 3 |
| void [set_Matrix44](./set_matrix44/)(**float**) | ตั้งค่าที่แถวที่ 4 และคอลัมน์ที่ 4 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | ตั้งค่าเทมเพลตอาร์กิวเมนต์ที่ n เป็น weak pointer (แทน shared) ทำให้สามารถสลับพอยน์เตอร์ในคอนเทนเนอร์เป็นโหมด weak ได้ |
| int [SharedCount](../../system/object/sharedcount/)() const | รับค่าปัจจุบันของตัวนับอ้างอิงร่วม |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | เพิ่มค่าตัวนับอ้างอิงร่วม. ไม่ควรเรียกโดยตรง; ให้ใช้สมาร์ทพอยน์เตอร์หรือ ThisProtector แทน |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ลดค่าตัวนับอ้างอิงร่วมและคืนค่า. ไม่ควรเรียกโดยตรง; ให้ใช้สมาร์ทพอยน์เตอร์หรือ ThisProtector แทน |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | เป็นอ analogue ของเมธอด C# [Object.ToString()](../../system/object/tostring/). ทำให้แปลงวัตถุที่กำหนดเองเป็นสตริงได้ |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ทำงานเหมือนกับการสร้าง C# typeof([System.Object](../../system/object/)) |
| void [Unlock](../../system/object/unlock/)() | ทำงานเหมือนกับการปลดล็อกของคำสั่ง C# lock(). เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/) |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | เพิ่มค่าตัวนับอ้างอิง weak. ไม่ควรเรียกโดยตรง; ให้ใช้สมาร์ทพอยน์เตอร์หรือ ThisProtector แทน |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ลดค่าตัวนับอ้างอิง weak. ไม่ควรเรียกโดยตรง; ให้ใช้สมาร์ทพอยน์เตอร์หรือ ThisProtector แทน |
| virtual  [~Object](../../system/object/~object/)() | ทำลายวัตถุ. ปล่อยโครงสร้างข้อมูลภายในทั้งหมด |
## ดูเพิ่มเติม

* คลาส [Object](../../system/object/)
* เนมสเปซ [System::Drawing::Imaging](../)
* ไลบรารี [Aspose.Slides](../../)