---
title: Pen
second_title: อ้างอิง API Aspose.Slides สำหรับ C++
description: "แทนคุณสมบัติเช่นสี ความกว้าง ฯลฯ ของเส้นและโค้งที่กำลังวาด อ็อบเจ็กต์ของคลาสนี้ควรจัดสรรโดยใช้ฟังก์ชัน System::MakeObject() เท่านั้น ห้ามสร้างอินสแตนซ์ของประเภทนี้บนสแตกหรือโดยใช้ตัวดำเนินการ new เพราะจะทำให้เกิดข้อผิดพลาดขณะรันไทม์และ/หรือการตรวจสอบข้อผิดพลาด ควรหุ้มหรือห่อคลาสนี้ด้วยพอยน์เตอร์ System::SmartPtr และใช้พอยน์เตอร์นี้เพื่อส่งเป็นอาร์กิวเมนต์ให้กับฟังก์ชัน"
type: docs
weight: 183
url: /th/system.drawing/pen/
---
## Pen คลาส

แสดงคุณสมบัติเช่นสี ความกว้าง ฯลฯ ของเส้นและโค้งที่กำลังวาด  
อ็อบเจ็กต์ของคลาสนี้ควรจัดสรรโดยใช้ฟังก์ชัน [System::MakeObject()](../../system/makeobject/) เท่านั้น  
ห้ามสร้างอินสแตนซ์ของประเภทนี้บนสแตกหรือโดยใช้ตัวดำเนินการ new เพราะจะทำให้เกิดข้อผิดพลาดขณะรันไทม์และ/หรือการตรวจสอบข้อผิดพลาด  
ควรหุ้มหรือห่อคลาสนี้ด้วยพอยน์เตอร์ [System::SmartPtr](../../system/smartptr/) และใช้พอยน์เตอร์นี้เพื่อส่งเป็นอาร์กิวเมนต์ให้กับฟังก์ชันเสมอ  

```cpp
class Pen : public System::Object
```

## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [SharedPtr](../../system/sharedptr/)\<[Pen](./)\> [Clone](./clone/)() | ส่งคืนสำเนาของอ็อบเจ็กต์ปัจจุบัน |
| void [Dispose](./dispose/)() | ปล่อยทรัพยากรการทำงานทั้งหมดที่อ็อบเจ็กต์ปัจจุบันได้รับมา |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | เปรียบเทียบอ็อบเจ็กต์โดยใช้แนวคิดของ C# [Object.Equals](../../system/object/equals/) |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจ็กต์ประเภทอ้างอิงในรูปแบบของ C# |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจ็กต์ประเภทค่าในรูปแบบของ C# |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | จำลองการเปรียบเทียบจำนวนจริงแบบ C# ที่ NaN สองค่าถือว่าเท่ากันแม้ว่าตามมาตรฐาน IEC 60559:1989 NaN จะไม่เท่ากับค่าต่าง ๆ ใด ๆ รวมถึง NaN เอง |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | จำลองการเปรียบเทียบจำนวนจริงแบบ C# ที่ NaN สองค่าถือว่าเท่ากันแม้ว่าตามมาตรฐาน IEC 60559:1989 NaN จะไม่เท่ากับค่าต่าง ๆ ใด ๆ รวมถึง NaN เอง |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | เพื่อการใช้งานภายในเท่านั้น |
| [Drawing2D::PenAlignment](../../system.drawing.drawing2d/penalignment/) [get_Alignment](./get_alignment/)() const | ส่งคืนค่าที่บ่งบอกการจัดแนวของอ็อบเจ็กต์ [Pen](./) ปัจจุบัน |
| [SharedPtr](../../system/sharedptr/)\<[Brush](../brush/)\> [get_Brush](./get_brush/)() | ส่งคืนอ็อบเจ็กต์ [Brush](../brush/) ของปากกานี้ |
| [Color](../color/) [get_Color](./get_color/)() const | ส่งคืนสีของปากกานี้ |
| [System::ArrayPtr](../../system/arrayptr/)\<**float**\> [get_CompoundArray](./get_compoundarray/)() const | ส่งคืนอาร์เรย์ของค่าที่ระบุปากกาประกอบ |
| [Drawing2D::DashCap](../../system.drawing.drawing2d/dashcap/) [get_DashCap](./get_dashcap/)() const | ส่งคืนค่าที่บ่งบอกหัวที่ใช้ที่ทั้งสองปลายของเส้นประ |
| **float** [get_DashOffset](./get_dashoffset/)() const | ส่งคืนระยะทางจากจุดเริ่มต้นของเส้นถึงจุดเริ่มต้นของรูปแบบเส้นประ |
| [System::ArrayPtr](../../system/arrayptr/)\<**float**\> [get_DashPattern](./get_dashpattern/)() const | ส่งคืนอาร์เรย์ที่ระบุรูปแบบเส้นประที่กำหนดเองในเส้นประ |
| [Drawing2D::DashStyle](../../system.drawing.drawing2d/dashstyle/) [get_DashStyle](./get_dashstyle/)() const | ส่งคืนค่าที่บ่งบอกสไตล์ของเส้นประของอ็อบเจ็กต์ [Pen](./) ปัจจุบัน |
| [Drawing2D::LineCap](../../system.drawing.drawing2d/linecap/) [get_EndCap](./get_endcap/)() const | ส่งคืนค่าที่บ่งบอกหัวเส้นสุดท้ายของอ็อบเจ็กต์ [Pen](./) ปัจจุบัน |
| [Drawing2D::LineJoin](../../system.drawing.drawing2d/linejoin/) [get_LineJoin](./get_linejoin/)() const | ส่งคืนค่าที่บ่งบอกวิธีการเชื่อมต่อของเส้นที่วาดโดยอ็อบเจ็กต์ [Pen](./) นี้ |
| **float** [get_MiterLimit](./get_miterlimit/)() const | ส่งคืนขีดจำกัดของความหนาของการเชื่อมต่อที่มุมตัด |
| [Drawing2D::PenType](../../system.drawing.drawing2d/pentype/) [get_PenType](./get_pentype/)() const | ยังไม่ได้ทำการใช้งาน |
| [Drawing2D::LineCap](../../system.drawing.drawing2d/linecap/) [get_StartCap](./get_startcap/)() const | ส่งคืนค่าที่บ่งบอกหัวเส้นเริ่มต้นของอ็อบเจ็กต์ [Pen](./) ปัจจุบัน |
| [SharedPtr](../../system/sharedptr/)\<[Drawing2D::Matrix](../../system.drawing.drawing2d/matrix/)\> [get_Transform](./get_transform/)() | ส่งคืนสำเนาของอ็อบเจ็กต์ Matrix ที่ระบุการแปลงเชิงเรขาคณิตสำหรับปากกาที่แสดงโดยอ็อบเจ็กต์ปัจจุบัน |
| **float** [get_Width](./get_width/)() const | ส่งคืนความกว้างของอ็อบเจ็กต์ [Pen](./) ปัจจุบัน |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | รับโครงสร้างข้อมูลตัวนับอ้างอิงที่เชื่อมโยงกับอ็อบเจ็กต์ |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | เป็นอนาล็อกของเมธอด C# [Object.GetHashCode()](../../system/object/gethashcode/). เปิดใช้งานการแฮชของอ็อบเจ็กต์ที่กำหนดเอง |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | รับประเภทจริงของอ็อบเจ็กต์. เป็นอนาล็อกของการเรียก C# [System.Object.GetType()](../../system/object/gettype/) |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | ตรวจสอบว่าอ็อบเจ็กต์เป็นอินสแตนซ์ของประเภทที่อธิบายโดย targetType หรือไม่. เป็นอนาล็อกของออปเรเตอร์ C# 'is' |
| void [Lock](../../system/object/lock/)() | ดำเนินการล็อกตามคำสั่ง C# lock(). เรียกโดยตรงหรือใช้วัตถุ [LockContext](../../system/lockcontext/) |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | เป็นอนาล็อกของเมธอด C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). เปิดใช้งานการทำสำเนาประเภทที่กำหนดเอง |
| void [MultiplyTransform](./multiplytransform/)(const [SharedPtr](../../system/sharedptr/)\<[Drawing2D::Matrix](../../system.drawing.drawing2d/matrix/)\>\&, [Drawing2D::MatrixOrder](../../system.drawing.drawing2d/matrixorder/)) | คูณเมทริกซ์การแปลงของอ็อบเจ็กต์ปัจจุบันด้วยเมทริกซ์ที่ระบุ |
|  [Object](../../system/object/object/)() | สร้างอ็อบเจ็กต์. เริ่มต้นโครงสร้างข้อมูลภายในทั้งหมด |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | คอนสตรัคเตอร์คัดลอก. จริง ๆ แล้วไม่ได้คัดลอกอะไรเลย เพียงแค่เริ่มต้นอ็อบเจ็กต์ใหม่และเปิดใช้งานการคัดลอกคอนสตรัคเตอร์ของคลาสย่อย |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | โอเปอเรเตอร์การกำหนดค่า. จริง ๆ แล้วไม่ได้คัดลอกอะไรเลย เพียงแค่เริ่มต้นอ็อบเจ็กต์ใหม่และเปิดใช้งานการคัดลอกคอนสตรัคเตอร์ของคลาสย่อย |
|  [Pen](./pen/)(const [Color](../color/)\&) | สร้างอ็อบเจ็กต์ [Pen](./) ใหม่ที่แสดงสีที่ระบุ |
|  [Pen](./pen/)(const [Color](../color/)\&, **float**) | สร้างอ็อบเจ็กต์ [Pen](./) ใหม่ที่แสดงสีและความกว้างที่ระบุ |
|  [Pen](./pen/)(const [SharedPtr](../../system/sharedptr/)\<[Brush](../brush/)\>\&) | สร้างอ็อบเจ็กต์ [Pen](./) ใหม่และเริ่มต้นด้วยอ็อบเจ็กต์ [Brush](../brush/) ที่ระบุ |
|  [Pen](./pen/)(const [SharedPtr](../../system/sharedptr/)\<[Brush](../brush/)\>\&, **float**) | สร้างอ็อบเจ็กต์ [Pen](./) ใหม่และเริ่มต้นด้วยอ็อบเจ็กต์ [Brush](../brush/) ที่ระบุ |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | เปรียบเทียบอ็อบเจ็กต์โดยอ้างอิง |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | เปรียบเทียบอ็อบเจ็กต์โดยอ้างอิง |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | เปรียบเทียบอ้างอิงของอ็อบเจ็กต์ประเภทค่า กับ nullptr |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | การทำเฉพาะสำหรับ [Object::ReferenceEquals](../../system/object/referenceequals/) ในกรณีของสตริงและ nullptr |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | การทำเฉพาะสำหรับ [Object::ReferenceEquals](../../system/object/referenceequals/) ในกรณีของสตริง |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | ลดตัวนับอ้างอิงที่ใช้ร่วมกันลงตามค่าที่ระบุ |
| void [ResetTransform](./resettransform/)() | รีเซ็ตเมทริกซ์การแปลงของอ็อบเจ็กต์ปัจจุบันให้เป็นเมทริกซ์เอกลักษณ์ |
| void [RotateTransform](./rotatetransform/)(**float**, [Drawing2D::MatrixOrder](../../system.drawing.drawing2d/matrixorder/)) | หมุนการแปลงเชิงเรขาคณิตท้องถิ่นตามมุมที่ระบุในลำดับที่กำหนด |
| void [ScaleTransform](./scaletransform/)(**float**, **float**, [Drawing2D::MatrixOrder](../../system.drawing.drawing2d/matrixorder/)) | ปรับขนาดการแปลงเชิงเรขาคณิตท้องถิ่นตามอัตราส่วนที่ระบุในลำดับที่กำหนด |
| void [set_Alignment](./set_alignment/)([Drawing2D::PenAlignment](../../system.drawing.drawing2d/penalignment/)) | ตั้งค่าการจัดแนวของอ็อบเจ็กต์ [Pen](./) ปัจจุบัน |
| void [set_Brush](./set_brush/)(const [SharedPtr](../../system/sharedptr/)\<[Brush](../brush/)\>\&) | ตั้งค่าอ็อบเจ็กต์ [Brush](../brush/) ของปากกานี้ |
| void [set_Color](./set_color/)(const [Color](../color/)\&) | ตั้งค่าสีของปากกานี้ |
| void [set_CompoundArray](./set_compoundarray/)(const [System::ArrayPtr](../../system/arrayptr/)\<**float**\>\&) | ตั้งค่าอาร์เรย์ของค่าที่ระบุปากกาประกอบ |
| void [set_CustomEndCap](./set_customendcap/)(const [SharedPtr](../../system/sharedptr/)\<[Drawing2D::CustomLineCap](../../system.drawing.drawing2d/customlinecap/)\>\&) | ตั้งค่าหัวเส้นส่วนท้ายที่กำหนดเอง |
| void [set_CustomStartCap](./set_customstartcap/)(const [SharedPtr](../../system/sharedptr/)\<[Drawing2D::CustomLineCap](../../system.drawing.drawing2d/customlinecap/)\>\&) | ตั้งค่าหัวเส้นส่วนเริ่มต้นที่กำหนดเอง |
| void [set_DashCap](./set_dashcap/)([Drawing2D::DashCap](../../system.drawing.drawing2d/dashcap/)) | ตั้งค่าค่าที่ระบุหัวที่ใช้ที่ทั้งสองปลายของเส้นประ |
| void [set_DashOffset](./set_dashoffset/)(**float**) | ตั้งค่าระยะทางจากจุดเริ่มต้นของเส้นถึงจุดเริ่มต้นของรูปแบบเส้นประ |
| void [set_DashPattern](./set_dashpattern/)(const [System::ArrayPtr](../../system/arrayptr/)\<**float**\>\&) | ตั้งค่าอาร์เรย์ที่ระบุรูปแบบเส้นประที่กำหนดเองในเส้นประ. อาร์เรย์ประกอบด้วยตัวเลขที่ระบุความยาวของเส้นประและช่องว่างสลับกัน |
| void [set_DashStyle](./set_dashstyle/)([Drawing2D::DashStyle](../../system.drawing.drawing2d/dashstyle/)) | ตั้งค่าค่าที่ระบุสไตล์ของเส้นประของอ็อบเจ็กต์ [Pen](./) ปัจจุบัน |
| void [set_EndCap](./set_endcap/)([Drawing2D::LineCap](../../system.drawing.drawing2d/linecap/)) | ตั้งค่าหัวเส้นส่วนท้ายของอ็อบเจ็กต์ [Pen](./) ปัจจุบัน |
| void [set_LineJoin](./set_linejoin/)([Drawing2D::LineJoin](../../system.drawing.drawing2d/linejoin/)) | ตั้งค่าค่าที่ระบุวิธีการเชื่อมต่อของเส้นที่วาดโดยอ็อบเจ็กต์ [Pen](./) นี้ |
| void [set_MiterLimit](./set_miterlimit/)(**float**) | ตั้งค่าขีดจำกัดของความหนาของการเชื่อมต่อที่มุมตัด |
| void [set_StartCap](./set_startcap/)([Drawing2D::LineCap](../../system.drawing.drawing2d/linecap/)) | ตั้งค่าหัวเส้นเริ่มต้นของอ็อบเจ็กต์ [Pen](./) ปัจจุบัน |
| void [set_Transform](./set_transform/)(const [SharedPtr](../../system/sharedptr/)\<[Drawing2D::Matrix](../../system.drawing.drawing2d/matrix/)\>\&) | ตั้งค่าอ็อบเจ็กต์ Matrix ที่ระบุการแปลงเชิงเรขาคณิตสำหรับปากกาที่แสดงโดยอ็อบเจ็กต์ปัจจุบัน |
| void [set_Width](./set_width/)(**float**) | ตั้งค่าความกว้างของอ็อบเจ็กต์ [Pen](./) ปัจจุบัน |
| void [SetLineCap](./setlinecap/)([Drawing2D::LineCap](../../system.drawing.drawing2d/linecap/), [Drawing2D::LineCap](../../system.drawing.drawing2d/linecap/), [Drawing2D::DashCap](../../system.drawing.drawing2d/dashcap/)) | ยังไม่ได้ทำการใช้งาน |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | ตั้งเทมเพลตอาร์กิวเมนต์ที่ n เป็น weak pointer (แทน shared). อนุญาตให้สลับพอยน์เตอร์ในคอนเทนเนอร์เป็นโหมด weak |
| int [SharedCount](../../system/object/sharedcount/)() const | รับค่าปัจจุบันของตัวนับอ้างอิงที่ใช้ร่วมกัน |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | เพิ่มค่าตัวนับอ้างอิงที่ใช้ร่วมกัน. ไม่ควรเรียกโดยตรง; ให้ใช้ smart pointers หรือ ThisProtector แทน |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ลดและคืนค่าตัวนับอ้างอิงที่ใช้ร่วมกัน. ไม่ควรเรียกโดยตรง; ให้ใช้ smart pointers หรือ ThisProtector แทน |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | เป็นอนาล็อกของเมธอด C# [Object.ToString()](../../system/object/tostring/). เปิดใช้งานการแปลงอ็อบเจ็กต์ที่กำหนดเองเป็นสตริง |
| void [TranslateTransform](./translatetransform/)(**float**, **float**, [Drawing2D::MatrixOrder](../../system.drawing.drawing2d/matrixorder/)) | ย้ายการแปลงเชิงเรขาคณิตท้องถิ่นตามมิติที่ระบุในลำดับที่กำหนด |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ดำเนินการสร้าง C# typeof([System.Object](../../system/object/)) |
| void [Unlock](../../system/object/unlock/)() | ดำเนินการปลดล็อกตามคำสั่ง C# lock(). เรียกโดยตรงหรือใช้วัตถุ [LockContext](../../system/lockcontext/) |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | เพิ่มค่าตัวนับอ้างอิง weak. ไม่ควรเรียกโดยตรง; ให้ใช้ smart pointers หรือ ThisProtector แทน |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ลดค่าตัวนับอ้างอิง weak. ไม่ควรเรียกโดยตรง; ให้ใช้ smart pointers หรือ ThisProtector แทน |
| virtual  [~Object](../../system/object/~object/)() | ทำลายอ็อบเจ็กต์. ปล่อยโครงสร้างข้อมูลภายในทั้งหมด |

## ดูเพิ่มเติม

* คลาส [Object](../../system/object/)
* เนมสเปซ [System::Drawing](../)
* ไลบรารี [Aspose.Slides](../../)