---
title: GeometryPath
second_title: Aspose.Slides สำหรับ API อ้างอิง C++
description: แสดงเส้นทางเรขาคณิตของ GeometryShape
type: docs
weight: 1067
url: /th/aspose.slides/geometrypath/
---
## GeometryPath คลาส

Represents geometry path of [GeometryShape](../geometryshape/)

```cpp
class GeometryPath : public Aspose::Slides::IGeometryPath
```

## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| void [ArcTo](./arcto/)(**float**, **float**, **float**, **float**) override | เพิ่มส่วนโค้งที่ระบุลงในเส้นทาง |
| void [CloseFigure](./closefigure/)() override | ปิดรูปร่างปัจจุบันของเส้นทางนี้ |
| void [CubicBezierTo](./cubicbezierto/)([System::Drawing::PointF](../../system.drawing/pointf/), [System::Drawing::PointF](../../system.drawing/pointf/), [System::Drawing::PointF](../../system.drawing/pointf/)) override | เพิ่มเส้นโค้งบีเซอร์ระดับคิวบิกที่ตำแหน่งท้ายของเส้นทาง |
| void [CubicBezierTo](./cubicbezierto/)(**float**, **float**, **float**, **float**, **float**, **float**) override | เพิ่มเส้นโค้งบีเซอร์ระดับคิวบิกที่ตำแหน่งท้ายของเส้นทาง |
| void [CubicBezierTo](./cubicbezierto/)([System::Drawing::PointF](../../system.drawing/pointf/), [System::Drawing::PointF](../../system.drawing/pointf/), [System::Drawing::PointF](../../system.drawing/pointf/), **uint32_t**) override | เพิ่มเส้นโค้งบีเซอร์ระดับคิวบิกที่ตำแหน่งที่ระบุของเส้นทาง |
| void [CubicBezierTo](./cubicbezierto/)(**float**, **float**, **float**, **float**, **float**, **float**, **uint32_t**) override | เพิ่มเส้นโค้งบีเซอร์ระดับคิวบิกที่ตำแหน่งที่ระบุของเส้นทาง |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | เปรียบเทียบอ็อบเจกต์โดยใช้การทำงานของ C# [Object.Equals](../../system/object/equals/) |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจกต์ประเภทอ้างอิงในสไตล์ของ C# |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจกต์ประเภทค่าในสไตล์ของ C# |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | จำลองการเปรียบเทียบตัวเลขแบบ floating point ตามสไตล์ C# โดยที่ NaN สองค่าได้รับการพิจารณาว่าเท่ากัน แม้ว่าตามมาตรฐาน IEC 60559:1989 NaN จะไม่เท่ากับค่าใดๆ รวมถึง NaN เอง |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | จำลองการเปรียบเทียบตัวเลขแบบ floating point ตามสไตล์ C# โดยที่ NaN สองค่าได้รับการพิจารณาว่าเท่ากันแม้ว่าตามมาตรฐาน IEC 60559:1989 NaN จะไม่เท่ากับค่าใดๆ รวมถึง NaN เอง |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | ใช้เพื่อการภายในเท่านั้น |
|  [GeometryPath](./geometrypath/)() | สร้างอินสแตนซ์ของ [GeometryPath](./) |
| [PathFillModeType](../pathfillmodetype/) [get_FillMode](./get_fillmode/)() override | ตั้งค่าโหมดการเติม |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IPathSegment](../ipathsegment/)\>\> [get_PathData](./get_pathdata/)() override | คืนค่าเส้นทางเรขาคณิตของ [GeometryShape](../geometryshape/) เป็นอาเรย์ของส่วนเส้นทาง |
| **bool** [get_Stroke](./get_stroke/)() override | ตั้งค่าการแสดงผลเส้นขีด |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | รับโครงสร้างข้อมูลตัวนับอ้างอิงที่เชื่อมโยงกับอ็อบเจกต์ |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | เป็นแนวคิดคล้ายกับเมธอด C# [Object.GetHashCode()](../../system/object/gethashcode/). ช่วยให้สามารถทำแฮชอ็อบเจกต์ที่กำหนดเองได้ |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | รับประเภทจริงของอ็อบเจกต์. เป็นแนวคิดคล้ายกับการเรียก C# [System.Object.GetType()](../../system/object/gettype/) |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | ตรวจสอบว่าอ็อบเจกต์เป็นอินสแตนซ์ของประเภทที่อธิบายด้วย targetType หรือไม่. เป็นแนวคิดคล้ายกับโอเปอเรเตอร์ 'is' ของ C# |
| void [LineTo](./lineto/)([System::Drawing::PointF](../../system.drawing/pointf/)) override | เพิ่มเส้นตรงที่ตำแหน่งท้ายของเส้นทาง |
| void [LineTo](./lineto/)(**float**, **float**) override | เพิ่มเส้นตรงที่ตำแหน่งท้ายของเส้นทาง |
| void [LineTo](./lineto/)([System::Drawing::PointF](../../system.drawing/pointf/), **uint32_t**) override | เพิ่มเส้นตรงที่ตำแหน่งที่ระบุของเส้นทาง |
| void [LineTo](./lineto/)(**float**, **float**, **uint32_t**) override | เพิ่มเส้นตรงที่ตำแหน่งที่ระบุของเส้นทาง |
| void [Lock](../../system/object/lock/)() | ทำการล็อกตามคำสั่ง lock() ของ C#. เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/) |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | เป็นแนวคิดคล้ายกับเมธอด C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). ช่วยให้สามารถโคลนประเภทที่กำหนดเองได้ |
| void [MoveTo](./moveto/)([System::Drawing::PointF](../../system.drawing/pointf/)) override | ตั้งตำแหน่งจุดถัดไป |
| void [MoveTo](./moveto/)(**float**, **float**) override | ตั้งตำแหน่งจุดถัดไป |
|  [Object](../../system/object/object/)() | สร้างอ็อบเจกต์. เริ่มต้นโครงสร้างข้อมูลภายในทั้งหมด |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | คอนสตรัคเตอร์คัดลอก. จริงๆ แล้วไม่ได้คัดลอกอะไรเลย เพียงแค่เริ่มต้นอ็อบเจกต์ใหม่และเปิดใช้งานการคัดลอกสร้างซับคลาส |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | โอเปอเรเตอร์การมอบหมายค่า. จริงๆ แล้วไม่ได้คัดลอกอะไรเลย เพียงแค่เริ่มต้นอ็อบเจกต์ใหม่และเปิดใช้งานการคัดลอกสร้างซับคลาส |
| void [QuadraticBezierTo](./quadraticbezierto/)([System::Drawing::PointF](../../system.drawing/pointf/), [System::Drawing::PointF](../../system.drawing/pointf/)) override | เพิ่มเส้นโค้งบีเซอร์ระดับควาดราติกที่ตำแหน่งท้ายของเส้นทาง |
| void [QuadraticBezierTo](./quadraticbezierto/)(**float**, **float**, **float**, **float**) override | เพิ่มเส้นโค้งบีเซอร์ระดับควาดราติกที่ตำแหน่งท้ายของเส้นทาง |
| void [QuadraticBezierTo](./quadraticbezierto/)([System::Drawing::PointF](../../system.drawing/pointf/), [System::Drawing::PointF](../../system.drawing/pointf/), **uint32_t**) override | เพิ่มเส้นโค้งบีเซอร์ระดับควาดราติกที่ตำแหน่งที่ระบุของเส้นทาง |
| void [QuadraticBezierTo](./quadraticbezierto/)(**float**, **float**, **float**, **float**, **uint32_t**) override | เพิ่มเส้นโค้งบีเซอร์ระดับควาดราติกที่ตำแหน่งที่ระบุของเส้นทาง |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | เปรียบเทียบอ็อบเจกต์โดยอ้างอิง |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | เปรียบเทียบอ็อบเจกต์โดยอ้างอิง |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | เปรียบเทียบอ็อบเจกต์ประเภทค่ากับ nullptr โดยอ้างอิง |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | การแปรรูปพิเศษของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตリングและ nullptr |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | การแปรรูปพิเศษของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริงหลายรายการ |
| void [RemoveAt](./removeat/)(**int32_t**) override | ลบส่วนที่ตำแหน่งดัชนีที่ระบุของเส้นทางเรขาคณิต |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | ลดจำนวนตัวนับอ้างอิงที่แชร์โดยค่าที่ระบุ |
| void [set_FillMode](./set_fillmode/)([PathFillModeType](../pathfillmodetype/)) override | ตั้งค่าโหมดการเติม |
| void [set_Stroke](./set_stroke/)(**bool**) override | ตั้งค่าการแสดงผลเส้นขีด |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | ตั้งค่าอากิวเมนต์เทมเพลตที่ n ให้เป็น weak pointer (แทนที่จะแชร์). อนุญาตให้สลับพอยน์เตอร์ในคอนเทนเนอร์เป็นโหมด weak |
| int [SharedCount](../../system/object/sharedcount/)() const | รับค่าปัจจุบันของตัวนับอ้างอิงที่แชร์ |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | เพิ่มตัวนับอ้างอิงที่แชร์. ไม่ควรเรียกโดยตรง; ควรใช้สมาร์ทพอยน์เตอร์หรือ ThisProtector |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ลดและคืนค่าตัวนับอ้างอิงที่แชร์. ไม่ควรเรียกโดยตรง; ควรใช้สมาร์ทพอยน์เตอร์หรือ ThisProtector |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | เป็นแนวคิดคล้ายกับเมธอด C# [Object.ToString()](../../system/object/tostring/). ช่วยแปลงอ็อบเจกต์ที่กำหนดเองเป็นสตริง |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ทำการสร้าง typeof([System.Object](../../system/object/)) ของ C# |
| void [Unlock](../../system/object/unlock/)() | ทำการปลดล็อกตามคำสั่ง lock() ของ C#. เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/) |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | เพิ่มตัวนับอ้างอิงแบบ weak. ไม่ควรเรียกโดยตรง; ควรใช้สมาร์ทพอยน์เตอร์หรือ ThisProtector |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ลดตัวนับอ้างอิงแบบ weak. ไม่ควรเรียกโดยตรง; ควรใช้สมาร์ทพอยน์เตอร์หรือ ThisProtector |
| virtual  [~Object](../../system/object/~object/)() | ทำลายอ็อบเจกต์. ปล่อยโครงสร้างข้อมูลภายในทั้งหมด |

## ดูเพิ่มเติม

* คลาส [IGeometryPath](../igeometrypath/)
* เนมสเปซ [Aspose::Slides](../)
* ไลบรารี [Aspose.Slides](../../)