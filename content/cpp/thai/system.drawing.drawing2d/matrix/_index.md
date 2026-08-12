---
title: Matrix
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: "แสดงเมทริกซ์ขนาด 3x3 ที่กำหนดการแปลงรูปแบบการทำงาน. อ็อบเจ็กต์ของคลาสนี้ควรสร้างขึ้นโดยใช้ฟังก์ชัน System::MakeObject() เท่านั้น. อย่าสร้างอินสแตนซ์ของประเภทนี้บนสแตกหรือโดยใช้ตัวดำเนินการ new เนื่องจากจะทำให้เกิดข้อผิดพลาดเวลารันและ/หรือการขัดจังหวะข้อกำหนด. ควรหุ้มคลาสนี้ด้วยพอยน์เตอร์ System::SmartPtr และใช้พอยน์เตอร์นี้เพื่อส่งเป็นอาร์กิวเมนต์ให้กับฟังก์ชัน."
type: docs
weight: 118
url: /th/system.drawing.drawing2d/matrix/
---
## คลาส Matrix

Represents a 3x3 matrix that defines transform operations. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class Matrix : public System::Object
```

## Methods

| วิธีการ | คำอธิบาย |
| --- | --- |
| [SharedPtr](../../system/sharedptr/)\<[Matrix](./)\> [Clone](./clone/)() const | สร้างสำเนาของอ็อบเจ็กต์ปัจจุบัน |
| void [Dispose](./dispose/)() | ปล่อยทรัพยากรระบบปฏิบัติการทั้งหมดที่อ็อบเจ็กต์ปัจจุบันได้รับมา |
| **bool** [Equals](./equals/)([ptr](../../system/object/ptr/)) override | ทดสอบว่าอ็อบเจ็กต์ที่ระบุเป็น [Matrix](./) และเหมือนกับอ็อบเจ็กต์นี้หรือไม่ |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจ็กต์ประเภทอ้างอิงในรูปแบบ C# |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | จำลองการเปรียบเทียบเลขทศนิยมแบบ C# ซึ่ง NaN สองค่าถูกถือว่าเท่ากัน แม้ว่าตาม IEC 60559:1989 NaN ไม่เท่ากับค่าใด ๆ รวมถึง NaN เอง |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | จำลองการเปรียบเทียบเลขทศนิยมแบบ C# ซึ่ง NaN สองค่าถูกถือว่าเท่ากัน แม้ว่าตาม IEC 60559:1989 NaN ไม่เท่ากับค่าใด ๆ รวมถึง NaN เอง |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | เพื่อวัตถุประสงค์ภายในเท่านั้น |
| [System::ArrayPtr](../../system/arrayptr/)\<**float**\> [get_Elements](./get_elements/)() const | ส่งกลับอาเรย์ที่บรรจุองค์ประกอบของเมทริกซ์ตามลำดับต่อไปนี้: m11, m12, m21, m22, dx, dy |
| **bool** [get_IsIdentity](./get_isidentity/)() const | ตรวจสอบว่าเมทริกซ์ที่แสดงโดยอ็อบเจ็กต์ปัจจุบันเป็นเมทริกซ์เอกลักษณ์หรือไม่ |
| **bool** [get_IsInvertible](./get_isinvertible/)() const | ตรวจสอบว่าเมทริกซ์ที่แสดงโดยอ็อบเจ็กต์ปัจจุบันสามารถกลับได้หรือไม่ |
| **float** [get_OffsetX](./get_offsetx/)() const | ส่งกลับค่าการแปล X ของเมทริกซ์ที่แสดงโดยอ็อบเจ็กต์ปัจจุบัน |
| **float** [get_OffsetY](./get_offsety/)() const | ส่งกลับค่าการแปล Y ของเมทริกซ์ที่แสดงโดยอ็อบเจ็กต์ปัจจุบัน |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | รับโครงสร้างข้อมูลตัวนับอ้างอิงที่เชื่อมโยงกับอ็อบเจ็กต์ |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | คล้ายกับเมธอด C# [Object.GetHashCode()](../../system/object/gethashcode/). ทำให้สามารถแฮชอ็อบเจ็กต์ที่กำหนดเองได้ |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | รับประเภทจริงของอ็อบเจ็กต์. คล้ายกับการเรียก C# [System.Object.GetType()](../../system/object/gettype/) |
| void [Invert](./invert/)() | กลับเมทริกซ์ที่แสดงโดยอ็อบเจ็กต์ปัจจุบัน |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | ตรวจสอบว่าอ็อบเจ็กต์เป็นอินสแตนซ์ของประเภทที่อธิบายโดย targetType หรือไม่. คล้ายกับตัวดำเนินการ 'is' ของ C# |
| void [Lock](../../system/object/lock/)() | ทำการล็อกตามคำสั่ง lock() ของ C#. เรียกโดยตรงหรือใช้อ็อบเจ็กต์ sentinel [LockContext](../../system/lockcontext/) |
|  [Matrix](./matrix/)() | สร้างอินสแตนซ์ใหม่ของคลาส [Matrix](./) ที่เป็นเมทริกซ์เอกลักษณ์ |
|  [Matrix](./matrix/)(**float**, **float**, **float**, **float**, **float**, **float**) | สร้างอินสแตนซ์ใหม่ของคลาส [Matrix](./) และกำหนดค่าเริ่มต้นด้วยค่าที่ระบุ |
|  [Matrix](./matrix/)(const [Rectangle](../../system.drawing/rectangle/)\&, const [ArrayPtr](../../system/arrayptr/)\<[Point](../../system.drawing/point/)\>\&) | สร้างอินสแตนซ์ใหม่ของคลาส [Matrix](./) เพื่อการแปลงเชิงเรขาคณิตที่กำหนดโดยสี่เหลี่ยมและอาเรย์ของจุดที่ระบุ |
|  [Matrix](./matrix/)(const [RectangleF](../../system.drawing/rectanglef/)\&, const [ArrayPtr](../../system/arrayptr/)\<[PointF](../../system.drawing/pointf/)\>\&) | สร้างอินสแตนซ์ใหม่ของคลาส [Matrix](./) เพื่อการแปลงเชิงเรขาคณิตที่กำหนดโดยสี่เหลี่ยมและอาเรย์ของจุดที่ระบุ |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | คล้ายกับเมธอด C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). ทำให้สามารถโคลนประเภทที่กำหนดเองได้ |
| void [Multiply](./multiply/)(const [SharedPtr](../../system/sharedptr/)\<[Matrix](./)\>\&) | คูณเมทริกซ์ที่แสดงโดยอ็อบเจ็กต์ปัจจุบันด้วยเมทริกซ์ที่ระบุ |
| void [Multiply](./multiply/)(const [SharedPtr](../../system/sharedptr/)\<[Matrix](./)\>\&, [MatrixOrder](../matrixorder/)) | คูณเมทริกซ์ที่แสดงโดยอ็อบเจ็กต์ปัจจุบันด้วยเมทริกซ์ที่ระบุ |
|  [Object](../../system/object/object/)() | สร้างอ็อบเจ็กต์. เริ่มต้นโครงสร้างข้อมูลภายในทั้งหมด |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | คอนสตรัคเตอร์คัดลอก. จริง ๆ แล้วไม่ได้คัดลอกอะไรเลย เพียงแค่เริ่มต้นอ็อบเจ็กต์ใหม่และเปิดใช้งานการคัดลอกคอนสตรัคเตอร์ของคลาสย่อย |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | โอเปอเรเตอร์การกำหนดค่า. จริง ๆ แล้วไม่ได้คัดลอกอะไรเลย เพียงแค่เริ่มต้นอ็อบเจ็กต์ใหม่และเปิดใช้งานการคัดลอกคอนสตรัคเตอร์ของคลาสย่อย |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | เปรียบเทียบอ็อบเจ็กต์โดยอ้างอิง |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | เปรียบเทียบอ็อบเจ็กต์โดยอ้างอิง |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | เปรียบเทียบอ็อบเจ็กต์ประเภทค่าโดยอ้างอิงกับ nullptr |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | การเฉพาะเจาะจงของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริงและ nullptr |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | การเฉพาะเจาะจงของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริง |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | ลดจำนวนอ้างอิงที่แชร์ลงตามค่าที่ระบุ |
| void [Reset](./reset/)() | รีเซ็ตเมทริกซ์ที่แสดงโดยอ็อบเจ็กต์ปัจจุบันให้กลายเป็นเมทริกซ์เอกลักษณ์ |
| void [Rotate](./rotate/)(**float**) | หมุนเมทริกซ์ที่แสดงโดยอ็อบเจ็กต์ปัจจุบันตามเข็มนาฬิกาตามมุมที่ระบุ |
| void [Rotate](./rotate/)(**float**, [MatrixOrder](../matrixorder/)) | หมุนเมทริกซ์ที่แสดงโดยอ็อบเจ็กต์ปัจจุบันตามเข็มนาฬิการอบจุดกำเนิดตามมุมที่ระบุ |
| void [RotateAt](./rotateat/)(**float**, const [PointF](../../system.drawing/pointf/)\&) | หมุนเมทริกซ์ที่แสดงโดยอ็อบเจ็กต์ปัจจุบันตามเข็มนาฬิการอบจุดที่ระบุตามมุมที่ระบุ |
| void [RotateAt](./rotateat/)(**float**, const [PointF](../../system.drawing/pointf/)\&, [MatrixOrder](../matrixorder/)) | หมุนเมทริกซ์ที่แสดงโดยอ็อบเจ็กต์ปัจจุบันตามเข็มนาฬิการอบจุดที่ระบุตามมุมที่ระบุ |
| void [Scale](./scale/)(**float**, **float**) | ใช้เวกเตอร์สเกลที่ระบุกับเมทริกซ์ที่แสดงโดยอ็อบเจ็กต์ปัจจุบัน |
| void [Scale](./scale/)(**float**, **float**, [MatrixOrder](../matrixorder/)) | ใช้เวกเตอร์สเกลที่ระบุกับเมทริกซ์ที่แสดงโดยอ็อบเจ็กต์ปัจจุบัน |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | ตั้งค่าอาร์กิวเมนต์เทมเพลตที่ n ให้เป็น weak pointer (แทน shared). อนุญาตให้สลับพอยน์เตอร์ในคอนเทนเนอร์เป็นโหมด weak |
| int [SharedCount](../../system/object/sharedcount/)() const | รับค่าปัจจุบันของตัวนับอ้างอิงที่แชร์ |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | เพิ่มจำนวนอ้างอิงที่แชร์. ไม่ควรเรียกโดยตรง; ควรใช้ smart pointer หรือ ThisProtector |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ลดจำนวนอ้างอิงที่แชร์และส่งกลับค่า. ไม่ควรเรียกโดยตรง; ควรใช้ smart pointer หรือ ThisProtector |
| void [Shear](./shear/)(**float**, **float**) | ใช้เวกเตอร์ shear ที่ระบุกับเมทริกซ์ที่แสดงโดยอ็อบเจ็กต์ปัจจุบัน |
| void [Shear](./shear/)(**float**, **float**, [MatrixOrder](../matrixorder/)) | ใช้เวกเตอร์ shear ที่ระบุกับเมทริกซ์ที่แสดงโดยอ็อบเจ็กต์ปัจจุบัน |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | คล้ายกับเมธอด C# [Object.ToString()](../../system/object/tostring/). ทำให้สามารถแปลงอ็อบเจ็กต์ที่กำหนดเองเป็นสตริงได้ |
| void [TransformPoints](./transformpoints/)(const [ArrayPtr](../../system/arrayptr/)\<[Point](../../system.drawing/point/)\>\&) | ใช้การแปลงเชิงเรขาคณิตที่กำหนดโดยเมทริกซ์ที่แสดงโดยอ็อบเจ็กต์ปัจจุบันกับจุดที่ระบุ |
| void [TransformPoints](./transformpoints/)(const System::Details::ArrayView\<[Point](../../system.drawing/point/)\>\&) | ใช้การแปลงเชิงเรขาคณิตที่กำหนดโดยเมทริกซ์ที่แสดงโดยอ็อบเจ็กต์ปัจจุบันกับจุดที่ระบุ |
| void [TransformPoints](./transformpoints/)(const [ArrayPtr](../../system/arrayptr/)\<[PointF](../../system.drawing/pointf/)\>\&) | ใช้การแปลงเชิงเรขาคณิตที่กำหนดโดยเมทริกซ์ที่แสดงโดยอ็อบเจ็กต์ปัจจุบันกับจุดที่ระบุ |
| void [TransformPoints](./transformpoints/)(const System::Details::ArrayView\<[PointF](../../system.drawing/pointf/)\>\&) | ใช้การแปลงเชิงเรขาคณิตที่กำหนดโดยเมทริกซ์ที่แสดงโดยอ็อบเจ็กต์ปัจจุบันกับจุดที่ระบุ |
| void [TransformVectors](./transformvectors/)(const [ArrayPtr](../../system/arrayptr/)\<[Point](../../system.drawing/point/)\>\&) | ใช้เฉพาะส่วนสเกลและการหมุนของเมทริกซ์ที่แสดงโดยอ็อบเจ็กต์ปัจจุบันกับจุดที่ระบุ |
| void [TransformVectors](./transformvectors/)(const System::Details::ArrayView\<[Point](../../system.drawing/point/)\>\&) | ใช้เฉพาะส่วนสเกลและการหมุนของเมทริกซ์ที่แสดงโดยอ็อบเจ็กต์ปัจจุบันกับจุดที่ระบุ |
| void [TransformVectors](./transformvectors/)(const [ArrayPtr](../../system/arrayptr/)\<[PointF](../../system.drawing/pointf/)\>\&) | ใช้เฉพาะส่วนสเกลและการหมุนของเมทริกซ์ที่แสดงโดยอ็อบเจ็กต์ปัจจุบันกับจุดที่ระบุ |
| void [TransformVectors](./transformvectors/)(const System::Details::ArrayView\<[PointF](../../system.drawing/pointf/)\>\&) | ใช้เฉพาะส่วนสเกลและการหมุนของเมทริกซ์ที่แสดงโดยอ็อบเจ็กต์ปัจจุบันกับจุดที่ระบุ |
| void [Translate](./translate/)(**float**, **float**) | ใช้เวกเตอร์การแปลที่ระบุกับเมทริกซ์ที่แสดงโดยอ็อบเจ็กต์ปัจจุบัน |
| void [Translate](./translate/)(**float**, **float**, [MatrixOrder](../matrixorder/)) | ใช้เวกเตอร์การแปลที่ระบุกับเมทริกซ์ที่แสดงโดยอ็อบเจ็กต์ปัจจุบัน |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ทำให้รองรับโครงสร้าง typeof([System.Object](../../system/object/)) ของ C# |
| void [Unlock](../../system/object/unlock/)() | ทำการปลดล็อกตามคำสั่ง lock() ของ C#. เรียกโดยตรงหรือใช้อ็อบเจ็กต์ sentinel [LockContext](../../system/lockcontext/) |
| void [VectorTransformPoints](./vectortransformpoints/)(const [ArrayPtr](../../system/arrayptr/)\<[Point](../../system.drawing/point/)\>\&) | คูณแต่ละเวกเตอร์ในอาเรย์ด้วยเมทริกซ์ที่แสดงโดยอ็อบเจ็กต์ปัจจุบัน |
| void [VectorTransformPoints](./vectortransformpoints/)(const System::Details::ArrayView\<[Point](../../system.drawing/point/)\>\&) | คูณแต่ละเวกเตอร์ในอาเรย์ด้วยเมทริกซ์ที่แสดงโดยอ็อบเจ็กต์ปัจจุบัน |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | เพิ่มจำนวนอ้างอิงแบบ weak. ไม่ควรเรียกโดยตรง; ควรใช้ smart pointer หรือ ThisProtector |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ลดจำนวนอ้างอิงแบบ weak. ไม่ควรเรียกโดยตรง; ควรใช้ smart pointer หรือ ThisProtector |
| virtual  [~Matrix](./~matrix/)() | ตัวทำลาย |
| virtual  [~Object](../../system/object/~object/)() | ทำลายอ็อบเจ็กต์. ปลดปล่อยโครงสร้างข้อมูลภายในทั้งหมด |

## ดูเพิ่มเติม

* คลาส [Object](../../system/object/)
* เนมสเปซ [System::Drawing::Drawing2D](../)
* ไลบรารี [Aspose.Slides](../../)