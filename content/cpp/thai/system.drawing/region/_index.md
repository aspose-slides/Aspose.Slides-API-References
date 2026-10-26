---
title: Region
second_title: Aspose.Slides สำหรับการอ้างอิง API ของ C++
description: "แสดงถึงภายในของรูปร่างกราฟิก อ็อบเจ็กต์ของคลาสนี้ควรสร้างด้วยฟังก์ชัน System::MakeObject() เท่านั้น ไม่ควรสร้างอินสแตนซ์ของประเภทนี้บนสแตกหรือใช้ operator new เนื่องจากจะทำให้เกิดข้อผิดพลาดขณะรันไทม์และ/หรือข้อผิดพลาดการตรวจสอบ ควรห่อคลาสนี้ด้วยพอยน์เตอร์ System::SmartPtr และใช้พอยน์เตอร์นี้เพื่อส่งเป็นอาร์กิวเมนต์ให้กับฟังก์ชัน"
type: docs
weight: 261
url: /th/system.drawing/region/
---
## Region คลาส


แสดงถึงภายในของรูปร่างกราฟิก อ็อบเจ็กต์ของคลาสนี้ควรสร้างโดยใช้ฟังก์ชัน [System::MakeObject()](../../system/makeobject/) เท่านั้น ไม่ควรสร้างอินสแตนซ์ของประเภทนี้บนสแตกหรือใช้ operator new เพราะจะทำให้เกิดข้อผิดพลาดรันไทม์และ/หรือข้อศีลนิรภัย ควรห่อคลาสนี้ด้วยพอยน์เตอร์ [System::SmartPtr](../../system/smartptr/) และใช้พอยน์เตอร์นี้เพื่อส่งผ่านเป็นอาร์กิวเมนต์ให้ฟังก์ชัน

```cpp
class Region : public System::Object
```

## เมธอด

| วิธีการ | คำอธิบาย |
| --- | --- |
| [SharedPtr](../../system/sharedptr/)\<[Region](./)\> [Clone](./clone/)() const | คืนสำเนาของอ็อบเจ็กต์ปัจจุบัน |
| void [Complement](./complement/)(const [RectangleF](../rectanglef/)\&) | แทนที่ภูมิภาคที่แสดงโดยอ็อบเจ็กต์ปัจจุบันด้วยส่วนของภูมิภาคที่กำหนดโดยสี่เหลี่ยมที่ระบุซึ่งไม่ตัดกับภูมิภาคนี้ |
| void [Complement](./complement/)(const [Rectangle](../rectangle/)\&) | แทนที่ภูมิภาคที่แสดงโดยอ็อบเจ็กต์ปัจจุบันด้วยส่วนของภูมิภาคที่กำหนดโดยสี่เหลี่ยมที่ระบุซึ่งไม่ตัดกับภูมิภาคนี้ |
| void [Complement](./complement/)(const [SharedPtr](../../system/sharedptr/)\<[Drawing2D::GraphicsPath](../../system.drawing.drawing2d/graphicspath/)\>\&) | แทนที่ภูมิภาคที่แสดงโดยอ็อบเจ็กต์ปัจจุบันด้วยส่วนของภูมิภาคที่กำหนดโดยเส้นทางที่ระบุซึ่งไม่ตัดกับภูมิภาคนี้ |
| void [Complement](./complement/)(const [SharedPtr](../../system/sharedptr/)\<[Region](./)\>\&) | แทนที่ภูมิภาคที่แสดงโดยอ็อบเจ็กต์ปัจจุบันด้วยส่วนของภูมิภาคที่ระบุซึ่งไม่ตัดกับภูมิภาคนี้ |
| void [Dispose](./dispose/)() | ปล่อยทรัพยากรระบบปฏิบัติการทั้งหมดที่อ็อบเจ็กต์ปัจจุบันได้เข้าถึง |
| **bool** [Equals](./equals/)(const [SharedPtr](../../system/sharedptr/)\<[Region](./)\>\&, const [SharedPtr](../../system/sharedptr/)\<[Graphics](../graphics/)\>\&) | ตรวจสอบว่าภูมิภาคที่ระบุเหมือนกับภูมิภาคที่อ็อบเจ็กต์ปัจจุบันแสดงบนพื้นผิวการวาดที่ระบุหรือไม่ |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | เปรียบเทียบอ็อบเจ็กต์โดยใช้หลักการของ C# [Object.Equals](../../system/object/equals/) |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจ็กต์ประเภทอ้างอิงในสไตล์ C# |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | จำลองการเปรียบเทียบจำนวนจริงแบบ C# ที่ NaN สองค่าถือว่าเท่ากัน แม้ตามมาตรฐาน IEC 60559:1989 NaN จะไม่เท่ากับค่าใด ๆ รวมถึง NaN เอง |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | จำลองการเปรียบเทียบจำนวนจริงแบบ C# ที่ NaN สองค่าถือว่าเท่ากัน แม้ตามมาตรฐาน IEC 60559:1989 NaN จะไม่เท่ากับค่าใด ๆ รวมถึง NaN เอง |
| void [Exclude](./exclude/)(const [RectangleF](../rectanglef/)\&) | แทนที่ภูมิภาคที่แสดงโดยอ็อบเจ็กต์ปัจจุบันด้วยผลลัพธ์ของการตัดออกของภูมิภาคที่กำหนดโดยสี่เหลี่ยมที่ระบุจากมัน |
| void [Exclude](./exclude/)(const [Rectangle](../rectangle/)\&) | แทนที่ภูมิภาคที่แสดงโดยอ็อบเจ็กต์ปัจจุบันด้วยผลลัพธ์ของการตัดออกของภูมิภาคที่กำหนดโดยสี่เหลี่ยมที่ระบุจากมัน |
| void [Exclude](./exclude/)(const [SharedPtr](../../system/sharedptr/)\<[Drawing2D::GraphicsPath](../../system.drawing.drawing2d/graphicspath/)\>\&) | แทนที่ภูมิภาคที่แสดงโดยอ็อบเจ็กต์ปัจจุบันด้วยผลลัพธ์ของการตัดออกของภูมิภาคที่กำหนดโดยเส้นทางที่ระบุจากมัน |
| void [Exclude](./exclude/)(const [SharedPtr](../../system/sharedptr/)\<[Region](./)\>\&) | แทนที่ภูมิภาคที่แสดงโดยอ็อบเจ็กต์ปัจจุบันด้วยผลลัพธ์ของการตัดออกของภูมิภาคที่ระบุจากมัน |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | ใช้เพื่อวัตถุประสงค์ภายในเท่านั้น |
| [RectangleF](../rectanglef/) [GetBounds](./getbounds/)(const [SharedPtr](../../system/sharedptr/)\<[Graphics](../graphics/)\>\&) const | รับโครงสร้าง [RectangleF](../rectanglef/) ที่แสดงสี่เหลี่ยมที่ล้อมรอบ [Region](./) นี้บนพื้นผิวการวาดของอ็อบเจ็กต์ [Graphics](../graphics/) |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | รับโครงสร้างข้อมูลตัวนับอ้างอิงที่เกี่ยวข้องกับอ็อบเจ็กต์ |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | ตรรกะเดียวกับเมธอด C# [Object.GetHashCode()](../../system/object/gethashcode/) เปิดใช้งานการแฮชของอ็อบเจ็กต์ที่กำหนดเอง |
| [SharedPtr](../../system/sharedptr/)\<[Drawing2D::RegionData](../../system.drawing.drawing2d/regiondata/)\> [GetRegionData](./getregiondata/)() const | คืนอ็อบเจ็กต์ RegionData ที่มีข้อมูลกำหนดภูมิภาคที่อ็อบเจ็กต์ปัจจุบันแสดง |
| [ArrayPtr](../../system/arrayptr/)\<[RectangleF](../rectanglef/)\> [GetRegionScans](./getregionscans/)(const [SharedPtr](../../system/sharedptr/)\<[Drawing2D::Matrix](../../system.drawing.drawing2d/matrix/)\>\&) const | คืนอาร์เรย์ของโครงสร้าง [RectangleF](../rectanglef/) ที่ประมาณ [Region](./) นี้หลังจากทำการแปลงเมทริกซ์ที่ระบุ |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | รับประเภทจริงของอ็อบเจ็กต์ ตรรกะเดียวกับการเรียก C# [System.Object.GetType()](../../system/object/gettype/) |
| void [Intersect](./intersect/)(const [RectangleF](../rectanglef/)\&) | แทนที่ภูมิภาคที่แสดงโดยอ็อบเจ็กต์ปัจจุบันด้วยผลลัพธ์ของการตัดกันระหว่างภูมิภาคนี้และภูมิภาคที่กำหนดโดยสี่เหลี่ยมที่ระบุ |
| void [Intersect](./intersect/)(const [Rectangle](../rectangle/)\&) | แทนที่ภูมิภาคที่แสดงโดยอ็อบเจ็กต์ปัจจุบันด้วยผลลัพธ์ของการตัดกันระหว่างภูมิภาคนี้และภูมิภาคที่กำหนดโดยสี่เหลี่ยมที่ระบุ |
| void [Intersect](./intersect/)(const [SharedPtr](../../system/sharedptr/)\<[Drawing2D::GraphicsPath](../../system.drawing.drawing2d/graphicspath/)\>\&) | แทนที่ภูมิภาคที่แสดงโดยอ็อบเจ็กต์ปัจจุบันด้วยผลลัพธ์ของการตัดกันระหว่างภูมิภาคนี้และภูมิภาคที่กำหนดโดยเส้นทางที่ระบุ |
| void [Intersect](./intersect/)(const [SharedPtr](../../system/sharedptr/)\<[Region](./)\>\&) | แทนที่ภูมิภาคที่แสดงโดยอ็อบเจ็กต์ปัจจุบันด้วยผลลัพธ์ของการตัดกันระหว่างภูมิภาคนี้และภูมิภาคที่ระบุ |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | ตรวจสอบว่าอ็อบเจ็กต์เป็นอินสแตนซ์ของประเภทที่อธิบายโดย targetType ตรรกะเดียวกับตัวดำเนินการ C# 'is' |
| **bool** [IsEmpty](./isempty/)(const [SharedPtr](../../system/sharedptr/)\<[Graphics](../graphics/)\>\&) const | ตรวจสอบว่าภูมิภาคที่อ็อบเจ็กต์ปัจจุบันแสดงมีภายในว่างเปล่าบนพื้นผิวการวาดที่ระบุหรือไม่ |
| **bool** [IsInfinite](./isinfinite/)(const [SharedPtr](../../system/sharedptr/)\<[Graphics](../graphics/)\>\&) const | ตรวจสอบว่าภูมิภาคที่อ็อบเจ็กต์ปัจจุบันแสดงมีภายในไม่จำกัดบนพื้นผิวการวาดที่ระบุหรือไม่ |
| **bool** [IsVisible](./isvisible/)(const [Point](../point/)\&) const | ตรวจสอบว่าจุดที่ระบุอยู่ภายในภูมิภาคที่อ็อบเจ็กต์ปัจจุบันแสดงหรือไม่ |
| **bool** [IsVisible](./isvisible/)(const [PointF](../pointf/)\&) const | ตรวจสอบว่าจุดที่ระบุอยู่ภายในภูมิภาคที่อ็อบเจ็กต์ปัจจุบันแสดงหรือไม่ |
| **bool** [IsVisible](./isvisible/)(const [Rectangle](../rectangle/)\&) | ตรวจสอบว่าบางส่วนของสี่เหลี่ยมที่ระบุอยู่ภายในภูมิภาคที่อ็อบเจ็กต์ปัจจุบันแสดงหรือไม่ |
| **bool** [IsVisible](./isvisible/)(const [RectangleF](../rectanglef/)\&) | ตรวจสอบว่าบางส่วนของสี่เหลี่ยมที่ระบุอยู่ภายในภูมิภาคที่อ็อบเจ็กต์ปัจจุบันแสดงหรือไม่ |
| **bool** [IsVisible](./isvisible/)(const [Point](../point/)\&, const [SharedPtr](../../system/sharedptr/)\<[Graphics](../graphics/)\>\&) const | ตรวจสอบว่าจุดที่ระบุอยู่ภายในภูมิภาคที่อ็อบเจ็กต์ปัจจุบันแสดงโดยใช้กราฟิกที่ระบุ |
| **bool** [IsVisible](./isvisible/)(const [PointF](../pointf/)\&, const [SharedPtr](../../system/sharedptr/)\<[Graphics](../graphics/)\>\&) const | ตรวจสอบว่าจุดที่ระบุอยู่ภายในภูมิภาคที่อ็อบเจ็กต์ปัจจุบันแสดงโดยใช้กราฟิกที่ระบุ |
| **bool** [IsVisible](./isvisible/)(const [Rectangle](../rectangle/)\&, const [SharedPtr](../../system/sharedptr/)\<[Graphics](../graphics/)\>\&) | ตรวจสอบว่าบางส่วนของสี่เหลี่ยมที่ระบุอยู่ภายในภูมิภาคที่อ็อบเจ็กต์ปัจจุบันแสดงโดยใช้กราฟิกที่ระบุ |
| **bool** [IsVisible](./isvisible/)(const [RectangleF](../rectanglef/)\&, const [SharedPtr](../../system/sharedptr/)\<[Graphics](../graphics/)\>\&) | ตรวจสอบว่าบางส่วนของสี่เหลี่ยมที่ระบุอยู่ภายในภูมิภาคที่อ็อบเจ็กต์ปัจจุบันแสดงโดยใช้กราฟิกที่ระบุ |
| **bool** [IsVisible](./isvisible/)(**float**, **float**) const | ตรวจสอบว่าจุดที่ระบุอยู่ภายในภูมิภาคที่อ็อบเจ็กต์ปัจจุบันแสดง |
| **bool** [IsVisible](./isvisible/)(**float**, **float**, const [SharedPtr](../../system/sharedptr/)\<[Graphics](../graphics/)\>\&) const | ตรวจสอบว่าจุดที่ระบุอยู่ภายในภูมิภาคที่อ็อบเจ็กต์ปัจจุบันแสดงโดยใช้กราฟิกที่ระบุ |
| void [Lock](../../system/object/lock/)() | ดำเนินการล็อกตามคำสั่ง C# lock() เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/) |
| void [MakeEmpty](./makeempty/)() | เริ่มต้นอ็อบเจ็กต์ปัจจุบันให้เป็นภายในว่างเปล่า |
| void [MakeInfinite](./makeinfinite/)() | เริ่มต้นอ็อบเจ็กต์ภูมิภาคนี้ให้เป็นภายในไม่มีที่สิ้นสุด |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | ตรรกะเดียวกับเมธอด C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) เปิดใช้งานการโคลนประเภทที่กำหนดเอง |
|  [Object](../../system/object/object/)() | สร้างอ็อบเจ็กต์ เริ่มต้นโครงสร้างข้อมูลภายในทั้งหมด |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | คอนสตรัคเตอร์คัดลอก ไม่ได้คัดลอกอะไรจริง ๆ เพียงแค่เริ่มต้นอ็อบเจ็กต์ใหม่และเปิดใช้งานการคัดลอกคอนสตรัคเตอร์สำหรับคลาสย่อย |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | ตัวดำเนินการกำหนดค่า ไม่ได้คัดลอกอะไรจริง ๆ เพียงแค่เริ่มต้นอ็อบเจ็กต์ใหม่และเปิดใช้งานการคัดลอกคอนสตรัคเตอร์สำหรับคลาสย่อย |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | เปรียบเทียบอ็อบเจ็กต์โดยอ้างอิง |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | เปรียบเทียบอ็อบเจ็กต์โดยอ้างอิง |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | เปรียบเทียบอ้างอิงระหว่างอ็อบเจ็กต์ประเภทค่าและ nullptr |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | การจำเพาะของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริงและ nullptr |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | การจำเพาะของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริง |
|  [Region](./region/)() | สร้างอินสแตนซ์ใหม่ของคลาส [Region](./) |
|  [Region](./region/)(const [RectangleF](../rectanglef/)\&) | สร้างอินสแตนซ์ใหม่ของคลาส [Region](./) ที่แสดงภูมิภาคที่กำหนดโดยสี่เหลี่ยมที่ระบุ |
|  [Region](./region/)(const [Rectangle](../rectangle/)\&) | สร้างอินสแตนซ์ใหม่ของคลาส [Region](./) ที่แสดงภูมิภาคที่กำหนดโดยสี่เหลี่ยมที่ระบุ |
|  [Region](./region/)(const [SharedPtr](../../system/sharedptr/)\<[Drawing2D::GraphicsPath](../../system.drawing.drawing2d/graphicspath/)\>\&) | สร้างอินสแตนซ์ใหม่ของคลาส [Region](./) ที่แสดงภูมิภาคที่กำหนดโดยเส้นทางที่ระบุ |
|  [Region](./region/)(const SkPath\&) |  |
|  [Region](./region/)(const [SharedPtr](../../system/sharedptr/)\<[Drawing2D::RegionData](../../system.drawing.drawing2d/regiondata/)\>\&) | สร้างอินสแตนซ์ใหม่ของคลาส [Region](./) ที่แสดงภูมิภาคที่กำหนดโดยอ็อบเจ็กต์ RegionData ที่ระบุ |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | ลดจำนวนตัวนับอ้างอิงที่แชร์ลงตามค่าที่ระบุ |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | ตั้งค่าอาร์กิวเมนต์เทมเพลตที่ n ให้เป็นพอยน์เตอร์อ่อน (แทนที่การแชร์) อนุญาตให้สลับพอยน์เตอร์ในคอนเทนเนอร์เป็นโหมดอ่อน |
| int [SharedCount](../../system/object/sharedcount/)() const | รับค่าปัจจุบันของตัวนับอ้างอิงที่แชร์ |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | เพิ่มจำนวนตัวนับอ้างอิงที่แชร์ ไม่ควรเรียกโดยตรง; ใช้สมาร์ทพอยน์เตอร์หรือ ThisProtector แทน |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ลดและคืนค่าตัวนับอ้างอิงที่แชร์ ไม่ควรเรียกโดยตรง; ใช้สมาร์ทพอยน์เตอร์หรือ ThisProtector แทน |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | ตรรกะเดียวกับเมธอด C# [Object.ToString()](../../system/object/tostring/) เปิดใช้งานการแปลงอ็อบเจ็กต์ที่กำหนดเองเป็นสตริง |
| void [Transform](./transform/)(const [SharedPtr](../../system/sharedptr/)\<[Drawing2D::Matrix](../../system.drawing.drawing2d/matrix/)\>\&) | แปลงภูมิภาคนี้โดยเมทริกซ์ที่ระบุ |
| void [Transform](./transform/)(const SkMatrix\&) | แปลงภูมิภาคนี้โดยเมทริกซ์ที่ระบุ |
| void [Translate](./translate/)(int, int) | ย้ายพิกัดของภูมิภาคตามค่าที่ระบุ |
| void [Translate](./translate/)(**float**, **float**) | ย้ายพิกัดของภูมิภาคตามค่าที่ระบุ |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ดำเนินการตามโครงสร้าง C# typeof([System.Object](../../system/object/)) |
| void [Union](./union/)(const [RectangleF](../rectanglef/)\&) | แทนที่ภูมิภาคที่อ็อบเจ็กต์ปัจจุบันด้วยผลลัพธ์ของการรวมกันของภูมิภาคนี้และภูมิภาคที่กำหนดโดยสี่เหลี่ยมที่ระบุ |
| void [Union](./union/)(const [Rectangle](../rectangle/)\&) | แทนที่ภูมิภาคที่อ็อบเจ็กต์ปัจจุบันด้วยผลลัพธ์ของการรวมกันของภูมิภาคนี้และภูมิภาคที่กำหนดโดยสี่เหลี่ยมที่ระบุ |
| void [Union](./union/)(const [SharedPtr](../../system/sharedptr/)\<[Drawing2D::GraphicsPath](../../system.drawing.drawing2d/graphicspath/)\>\&) | แทนที่ภูมิภาคที่อ็อบเจ็กต์ปัจจุบันด้วยผลลัพธ์ของการรวมกันของภูมิภาคนี้และภูมิภาคที่กำหนดโดยเส้นทางที่ระบุ |
| void [Union](./union/)(const [SharedPtr](../../system/sharedptr/)\<[Region](./)\>\&) | แทนที่ภูมิภาคที่อ็อบเจ็กต์ปัจจุบันด้วยผลลัพธ์ของการรวมกันของภูมิภาคนี้และภูมิภาคที่ระบุ |
| void [Unlock](../../system/object/unlock/)() | ดำเนินการปลดล็อกตามคำสั่ง C# lock() เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/) |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | เพิ่มจำนวนตัวนับอ้างอิงอ่อน ไม่ควรเรียกโดยตรง; ใช้สมาร์ทพอยน์เตอร์หรือ ThisProtector แทน |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ลดจำนวนตัวนับอ้างอิงอ่อน ไม่ควรเรียกโดยตรง; ใช้สมาร์ทพอยน์เตอร์หรือ ThisProtector แทน |
| void [Xor](./xor/)(const [RectangleF](../rectanglef/)\&) | แทนที่ภูมิภาคที่อ็อบเจ็กต์ปัจจุบันด้วยส่วนของภูมิภาคนี้และภูมิภาคที่กำหนดโดยสี่เหลี่ยมที่ระบุซึ่งไม่ตัดกัน |
| void [Xor](./xor/)(const [Rectangle](../rectangle/)\&) | แทนที่ภูมิภาคที่อ็อบเจ็กต์ปัจจุบันด้วยส่วนของภูมิภาคนี้และภูมิภาคที่กำหนดโดยสี่เหลี่ยมที่ระบุซึ่งไม่ตัดกัน |
| void [Xor](./xor/)(const [SharedPtr](../../system/sharedptr/)\<[Drawing2D::GraphicsPath](../../system.drawing.drawing2d/graphicspath/)\>\&) | แทนที่ภูมิภาคที่อ็อบเจ็กต์ปัจจุบันด้วยส่วนของภูมิภาคนี้และภูมิภาคที่กำหนดโดยเส้นทางที่ระบุซึ่งไม่ตัดกัน |
| void [Xor](./xor/)(const [SharedPtr](../../system/sharedptr/)\<[Region](./)\>\&) | แทนที่ภูมิภาคที่อ็อบเจ็กต์ปัจจุบันด้วยส่วนของภูมิภาคนี้และภูมิภาคที่ระบุซึ่งไม่ตัดกัน |
| virtual  [~Object](../../system/object/~object/)() | ทำลายอ็อบเจ็กต์ ปลดปล่อยโครงสร้างข้อมูลภายในทั้งหมด |
| virtual  [~Region](./~region/)() | ตัวทำลาย |
## ดูเพิ่มเติม

* คลาส [Object](../../system/object/)
* เนมสเปซ [System::Drawing](../)
* ไลบรารี [Aspose.Slides](../../)