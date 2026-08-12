---
title: TextureBrush
second_title: "Aspose.Slides สำหรับ C++ อ้างอิง API"
description: "แทนที่แปรงที่ใช้รูปภาพเพื่อเติมเนื้อในของรูปร่าง. วัตถุของคลาสนี้ควรจัดสรรโดยใช้ฟังก์ชัน System::MakeObject() . อย่าสร้างอินสแตนซ์ของประเภทนี้บนสแตกหรือโดยใช้ตัวดำเนินการ new เพราะจะทำให้เกิดข้อผิดพลาดรันไทม์และ/หรือข้อผิดพลาดการยืนยัน. ควรห่อคลาสนี้ด้วยพอยน์เตอร์ System::SmartPtr แล้วใช้พอยน์เตอร์นี้เพื่อส่งผ่านเป็นอากิวเมนต์ให้ฟังก์ชัน."
type: docs
weight: 352
url: /th/system.drawing/texturebrush/
---
## TextureBrush คลาส

แทนที่แปรงที่ใช้รูปภาพเพื่อเติมเนื้อในของรูปร่าง. วัตถุของคลาสนี้ควรจัดสรรเท่านั้นโดยใช้ฟังก์ชัน [System::MakeObject()](../../system/makeobject/). อย่าสร้างอินสแตนซ์ของประเภทนี้บนสแตกหรือโดยใช้ตัวดำเนินการ new เพราะจะทำให้เกิดข้อผิดพลาดรันไทม์และ/หรือข้อผิดพลาดการยืนยัน. ห่อตัวคลาสนี้ด้วยตัวชี้ [System::SmartPtr](../../system/smartptr/) และใช้ตัวชี้นี้เพื่อส่งผ่านเป็นอากิวเมนต์ให้ฟังก์ชัน.

```cpp
class TextureBrush : public System::Drawing::Brush
```

## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [Clone](./clone/)() override | สร้างสำเนาของอ็อบเจ็กต์ปัจจุบัน. |
| virtual void [Dispose](../../system/idisposable/dispose/)() | ไม่มีการทำอะไร. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | เปรียบเทียบอ็อบเจ็กต์โดยใช้แนวคิดของ C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจ็กต์ประเภทอ้างอิงในสไตล์ของ C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจ็กต์ประเภทค่าในสไตล์ของ C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | จำลองการเปรียบเทียบจำนวนทศนิยมสไตล์ C# ที่พิจารณา NaN สองค่าให้เท่ากัน แม้ว่า IEC 60559:1989 จะระบุว่า NaN ไม่เท่ากับค่าใดๆ รวมถึง NaN ด้วย. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | จำลองการเปรียบเทียบจำนวนทศนิยมสไตล์ C# ที่พิจารณา NaN สองค่าให้เท่ากัน แม้ว่า IEC 60559:1989 จะระบุว่า NaN ไม่เท่ากับค่าใดๆ รวมถึง NaN ด้วย. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | สำหรับการใช้งานภายในเท่านั้น. |
| [SharedPtr](../../system/sharedptr/)\<[Image](../image/)\> [get_Image](./get_image/)() | ส่งคืนรูปภาพที่ใช้โดยอ็อบเจ็กต์ [TextureBrush](./) ปัจจุบัน. |
| [System::SharedPtr](../../system/sharedptr/)\<[Drawing2D::Matrix](../../system.drawing.drawing2d/matrix/)\> [get_Transform](./get_transform/)() | ส่งคืนสำเนาของอ็อบเจ็กต์ Matrix ที่ระบุการแปลงเชิงเรขาคณิตสำหรับแปรงที่แสดงโดยอ็อบเจ็กต์ปัจจุบัน. |
| [Drawing2D::WrapMode](../../system.drawing.drawing2d/wrapmode/) [get_WrapMode](./get_wrapmode/)() | ส่งค่าว่าการทำกระเบื้องของแปรงที่แสดงโดยอ็อบเจ็กต์ปัจจุบันเป็นอย่างไร. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ดึงโครงสร้างข้อมูลตัวนับอ้างอิงที่เชื่อมโยงกับอ็อบเจ็กต์. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | เป็นเวอร์ชันคล้ายเมธอด C# [Object.GetHashCode()](../../system/object/gethashcode/). ทำให้สามารถแฮชอ็อบเจ็กต์แบบกำหนดเองได้. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | ดึงประเภทจริงของอ็อบเจ็กต์. เป็นเวอร์ชันคล้ายการเรียก C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | ตรวจสอบว่าอ็อบเจ็กต์เป็นอินสแตนซ์ของประเภทที่ targetType ระบุหรือไม่. เป็นเวอร์ชันคล้ายอปเปอเรเตอร์ 'is' ของ C#. |
| void [Lock](../../system/object/lock/)() | ทำงานเหมือนคำสั่ง lock() ของ C# เพื่อทำการล็อค. เรียกโดยตรงหรือใช้วัตถุ [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | เป็นเวอร์ชันคล้ายเมธอด C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). ทำให้สามารถโคลนประเภทกำหนดเองได้. |
| void [MultiplyTransform](./multiplytransform/)(const [SharedPtr](../../system/sharedptr/)\<[Drawing2D::Matrix](../../system.drawing.drawing2d/matrix/)\>\&, [Drawing2D::MatrixOrder](../../system.drawing.drawing2d/matrixorder/)) | คูณเมทริกซ์การแปลงของอ็อบเจ็กต์ปัจจุบันด้วยเมทริกซ์ที่ระบุ. |
|  [Object](../../system/object/object/)() | สร้างอ็อบเจ็กต์. เริ่มต้นโครงสร้างข้อมูลภายในทั้งหมด. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | คอนสทรัคเตอร์คัดลอก. ไม่ได้คัดลอกอะไรจริงๆ เพียงแต่เริ่มต้นอ็อบเจ็กต์ใหม่และเปิดใช้งานการคัดลอกสร้างซับคลาส. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | ตัวดำเนินการกำหนดค่า. ไม่ได้คัดลอกอะไรจริงๆ เพียงแต่เริ่มต้นอ็อบเจ็กต์ใหม่และเปิดใช้งานการคัดลอกสร้างซับคลาส. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | เปรียบเทียบอ็อบเจ็กต์โดยอ้างอิง. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | เปรียบเทียบอ็อบเจ็กต์โดยอ้างอิง. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | เปรียบเทียบอ็อบเจ็กต์ประเภทค่าโดยอ้างอิงกับ nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | การทำพิเศษของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริงและ nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | การทำพิเศษของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริง. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | ลดจำนวนตัวนับอ้างอิงร่วมโดยค่าที่ระบุ. |
| void [ResetTransform](./resettransform/)() | รีเซ็ตเมทริกซ์การแปลงของอ็อบเจ็กต์ปัจจุบันให้เป็นเมทริกซ์เอกลักษณ์. |
| void [RotateTransform](./rotatetransform/)(**float**, [Drawing2D::MatrixOrder](../../system.drawing.drawing2d/matrixorder/)) | หมุนการแปลงเชิงเรขาคณิตท้องถิ่นโดยมุมที่ระบุตามลำดับที่ระบุ. |
| void [ScaleTransform](./scaletransform/)(**float**, **float**, [Drawing2D::MatrixOrder](../../system.drawing.drawing2d/matrixorder/)) | สเกลการแปลงเชิงเรขาคณิตท้องถิ่นโดยปัจจัยที่ระบุตามลำดับที่ระบุ. |
| void [set_Transform](./set_transform/)(const [System::SharedPtr](../../system/sharedptr/)\<[Drawing2D::Matrix](../../system.drawing.drawing2d/matrix/)\>\&) | ตั้งค่าอ็อบเจ็กต์ Matrix ที่ระบุการแปลงเชิงเรขาคณิตย์สำหรับแปรงที่แสดงโดยอ็อบเจ็กต์ปัจจุบัน. |
| void [set_WrapMode](./set_wrapmode/)([Drawing2D::WrapMode](../../system.drawing.drawing2d/wrapmode/)) | ตั้งค่าที่กำหนดว่าการทำกระเบื้องของแปรงที่แสดงโดยอ็อบเจ็กต์ปัจจุบันเป็นอย่างไร. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | ตั้งอาร์กิวเมนต์เทมเพลตที่ n ให้เป็น weak pointer (แทน shared). อนุญาตให้สลับพอยเทอร์ตในคอนเทนเนอร์เป็นโหมด weak. |
| int [SharedCount](../../system/object/sharedcount/)() const | ดึงค่าปัจจุบันของตัวนับอ้างอิงร่วม. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | เพิ่มค่าตัวนับอ้างอิงร่วม. ไม่ควรเรียกโดยตรง; แทนใช้ smart pointer หรือ ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ลดค่าและคืนค่าตัวนับอ้างอิงร่วม. ไม่ควรเรียกโดยตรง; แทนใช้ smart pointer หรือ ThisProtector. |
|  [TextureBrush](./texturebrush/)(const [SharedPtr](../../system/sharedptr/)\<[Image](../image/)\>\&, [Drawing2D::WrapMode](../../system.drawing.drawing2d/wrapmode/)) | สร้างอินสแตนซ์ใหม่ของคลาส [TextureBrush](./) ที่ใช้รูปภาพที่ระบุ. |
|  [TextureBrush](./texturebrush/)(const [SharedPtr](../../system/sharedptr/)\<[Image](../image/)\>\&, [RectangleF](../rectanglef/), const [SharedPtr](../../system/sharedptr/)\<[Imaging::ImageAttributes](../../system.drawing.imaging/imageattributes/)\>\&) | สร้างอินสแตนซ์ใหม่ของคลาส [TextureBrush](./) ที่ใช้รูปภาพที่ระบุ. |
|  [TextureBrush](./texturebrush/)(const [SharedPtr](../../system/sharedptr/)\<[Image](../image/)\>\&, [Rectangle](../rectangle/), const [SharedPtr](../../system/sharedptr/)\<[Imaging::ImageAttributes](../../system.drawing.imaging/imageattributes/)\>\&) | สร้างอินสแตนซ์ใหม่ของคลาส [TextureBrush](./) ที่ใช้รูปภาพที่ระบุ. |
|  [TextureBrush](./texturebrush/)(const [SharedPtr](../../system/sharedptr/)\<[Image](../image/)\>\&, [Drawing2D::WrapMode](../../system.drawing.drawing2d/wrapmode/), [RectangleF](../rectanglef/)) | สร้างอินสแตนซ์ใหม่ของคลาส [TextureBrush](./) ที่ใช้รูปภาพที่ระบุ. |
|  [TextureBrush](./texturebrush/)(const [SharedPtr](../../system/sharedptr/)\<[Image](../image/)\>\&, [Drawing2D::WrapMode](../../system.drawing.drawing2d/wrapmode/), [Rectangle](../rectangle/)) | สร้างอินสแตนซ์ใหม่ของคลาส [TextureBrush](./) ที่ใช้รูปภาพที่ระบุ. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | เป็นเวอร์ชันคล้ายเมธอด C# [Object.ToString()](../../system/object/tostring/). ทำให้สามารถแปลงอ็อบเจ็กต์กำหนดเองเป็นสตริงได้. |
| void [TranslateTransform](./translatetransform/)(**float**, **float**, [Drawing2D::MatrixOrder](../../system.drawing.drawing2d/matrixorder/)) | ย้ายการแปลงเชิงเรขาคณิตท้องถิ่นโดยมิติที่ระบุตามลำดับที่ระบุ. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ทำงานคล้ายการสร้าง typeof([System.Object](../../system/object/)) ของ C#. |
| void [Unlock](../../system/object/unlock/)() | ทำงานคล้ายคำสั่ง lock() ของ C# เพื่อปลดล็อค. เรียกโดยตรงหรือใช้วัตถุ [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | เพิ่มค่าตัวนับ weak reference. ไม่ควรเรียกโดยตรง; แทนใช้ smart pointer หรือ ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ลดค่าตัวนับ weak reference. ไม่ควรเรียกโดยตรง; แทนใช้ smart pointer หรือ ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | ทำลายอ็อบเจ็กต์. ปลดปล่อยโครงสร้างข้อมูลภายในทั้งหมด. |
| virtual  [~TextureBrush](./~texturebrush/)() | ดีสทักเตอร์. |

## ดูเพิ่มเติม

* คลาส [Brush](../brush/)
* เนมสเปซ [System::Drawing](../)
* ไลบรารี [Aspose.Slides](../../)