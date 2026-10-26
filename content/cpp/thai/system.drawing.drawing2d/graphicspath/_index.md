---
title: GraphicsPath
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: "แทนชุดของเส้นและโค้งที่เชื่อมต่อกัน วัตถุของคลาสนี้ควรสร้างโดยใช้ฟังก์ชัน System::MakeObject() เท่านั้น อย่าสร้างอินสแตนซ์ของประเภทนี้บนสแตกหรือโดยใช้ operator new เนื่องจากจะทำให้เกิดข้อผิดพลาดเวลารันและ/หรือการตรวจสอบค่าเสมอ ควรห่อหุ้มคลาสนี้ด้วยพอยน์เตอร์ System::SmartPtr และใช้พอยน์เตอร์นี้เพื่อส่งผ่านเป็นอาร์กิวเมนต์ให้กับฟังก์ชัน"
type: docs
weight: 66
url: /th/system.drawing.drawing2d/graphicspath/
---
## GraphicsPath คลาส

แทนชุดของเส้นและโค้งที่เชื่อมต่อกัน วัตถุของคลาสนี้ควรสร้างโดยใช้ฟังก์ชัน [System::MakeObject()](../../system/makeobject/) เท่านั้น อย่าสร้างอินสแตนซ์ของประเภทนี้บนสแตกหรือโดยใช้ operator new เนื่องจากจะทำให้เกิดข้อผิดพลาดขณะรันไทม์และ/หรือข้อผิดพลาดการตรวจสอบค่าเสมอ ควรห่อหุ้มคลาสนี้ด้วยพอยน์เตอร์ [System::SmartPtr](../../system/smartptr/) และใช้พอยน์เตอร์นี้เพื่อส่งผ่านเป็นอาร์กิวเมนต์ให้กับฟังก์ชัน

```cpp
class GraphicsPath : public System::Object
```

## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| void [AddArc](./addarc/)(**float**, **float**, **float**, **float**, **float**, **float**) | เพิ่มโค้งวงรีที่ระบุไปยังพาธที่แสดงโดยวัตถุปัจจุบัน |
| void [AddArc](./addarc/)(int, int, int, int, **float**, **float**) | เพิ่มโค้งวงรีที่ระบุไปยังพาธที่แสดงโดยวัตถุปัจจุบัน |
| void [AddArc](./addarc/)(const [RectangleF](../../system.drawing/rectanglef/)\&, **float**, **float**) | เพิ่มโค้งวงรีที่ระบุไปยังพาธที่แสดงโดยวัตถุปัจจุบัน |
| void [AddArc](./addarc/)(const [Rectangle](../../system.drawing/rectangle/)\&, **float**, **float**) | เพิ่มโค้งวงรีที่ระบุไปยังพาธที่แสดงโดยวัตถุปัจจุบัน |
| void [AddBezier](./addbezier/)(const [Point](../../system.drawing/point/)\&, const [Point](../../system.drawing/point/)\&, const [Point](../../system.drawing/point/)\&, const [Point](../../system.drawing/point/)\&) | เพิ่มโค้งคิวบิก Bézier ที่ระบุไปยังพาธที่แสดงโดยวัตถุปัจจุบัน |
| void [AddBezier](./addbezier/)(const [PointF](../../system.drawing/pointf/)\&, const [PointF](../../system.drawing/pointf/)\&, const [PointF](../../system.drawing/pointf/)\&, const [PointF](../../system.drawing/pointf/)\&) | เพิ่มโค้งคิวบิก Bézier ที่ระบุไปยังพาธที่แสดงโดยวัตถุปัจจุบัน |
| void [AddBezier](./addbezier/)(int, int, int, int, int, int, int, int) | เพิ่มโค้งคิวบิก Bézier ที่ระบุไปยังพาธที่แสดงโดยวัตถุปัจจุบัน |
| void [AddBezier](./addbezier/)(**float**, **float**, **float**, **float**, **float**, **float**, **float**, **float**) | เพิ่มโค้งคิวบิก Bézier ที่ระบุไปยังพาธที่แสดงโดยวัตถุปัจจุบัน |
| void [AddBeziers](./addbeziers/)(const [ArrayPtr](../../system/arrayptr/)\<[Point](../../system.drawing/point/)\>\&) | เพิ่มลำดับของโค้งคิวบิก Bézier ที่เชื่อมต่อกันไปยังรูปปัจจุบัน |
| void [AddBeziers](./addbeziers/)(const [ArrayPtr](../../system/arrayptr/)\<[PointF](../../system.drawing/pointf/)\>\&) | เพิ่มลำดับของโค้งคิวบิก Bézier ที่เชื่อมต่อกันไปยังรูปปัจจุบัน |
| void [AddClosedCurve](./addclosedcurve/)(const [ArrayPtr](../../system/arrayptr/)\<[PointF](../../system.drawing/pointf/)\>\&, **float**) | เพิ่มโค้งปิดที่ระบุไปยังพาธที่แสดงโดยวัตถุปัจจุบัน |
| void [AddClosedCurve](./addclosedcurve/)(const [ArrayPtr](../../system/arrayptr/)\<[Point](../../system.drawing/point/)\>\&, **float**) | เพิ่มโค้งปิดที่ระบุไปยังพาธที่แสดงโดยวัตถุปัจจุบัน |
| void [AddCurve](./addcurve/)(const [ArrayPtr](../../system/arrayptr/)\<[PointF](../../system.drawing/pointf/)\>\&, **float**) | เพิ่มโค้งที่ระบุไปยังพาธที่แสดงโดยวัตถุปัจจุบัน |
| void [AddCurve](./addcurve/)(const [ArrayPtr](../../system/arrayptr/)\<[Point](../../system.drawing/point/)\>\&, **float**) | เพิ่มโค้งที่ระบุไปยังพาธที่แสดงโดยวัตถุปัจจุบัน |
| void [AddCurve](./addcurve/)(const [ArrayPtr](../../system/arrayptr/)\<[PointF](../../system.drawing/pointf/)\>\&, int, int, **float**) | เพิ่มโค้งที่ระบุไปยังพาธที่แสดงโดยวัตถุปัจจุบัน |
| void [AddCurve](./addcurve/)(const [ArrayPtr](../../system/arrayptr/)\<[Point](../../system.drawing/point/)\>\&, int, int, **float**) | เพิ่มโค้งที่ระบุไปยังพาธที่แสดงโดยวัตถุปัจจุบัน |
| void [AddEllipse](./addellipse/)(**float**, **float**, **float**, **float**) | เพิ่มวงรีที่ระบุไปยังพาธที่แสดงโดยวัตถุปัจจุบัน |
| void [AddEllipse](./addellipse/)(int, int, int, int) | เพิ่มวงรีที่ระบุไปยังพาธที่แสดงโดยวัตถุปัจจุบัน |
| void [AddEllipse](./addellipse/)(const [RectangleF](../../system.drawing/rectanglef/)\&) | เพิ่มวงรีที่ระบุไปยังพาธที่แสดงโดยวัตถุปัจจุบัน |
| void [AddEllipse](./addellipse/)(const [Rectangle](../../system.drawing/rectangle/)\&) | เพิ่มวงรีที่ระบุไปยังพาธที่แสดงโดยวัตถุปัจจุบัน |
| void [AddLine](./addline/)(const [Point](../../system.drawing/point/)\&, const [Point](../../system.drawing/point/)\&) | เพิ่มเส้นที่ระบุไปยังพาธที่แสดงโดยวัตถุปัจจุบัน |
| void [AddLine](./addline/)(const [PointF](../../system.drawing/pointf/)\&, const [PointF](../../system.drawing/pointf/)\&) | เพิ่มเส้นที่ระบุไปยังพาธที่แสดงโดยวัตถุปัจจุบัน |
| void [AddLine](./addline/)(int, int, int, int) | เพิ่มเส้นที่ระบุไปยังพาธที่แสดงโดยวัตถุปัจจุบัน |
| void [AddLine](./addline/)(**float**, **float**, **float**, **float**) | เพิ่มเส้นที่ระบุไปยังพาธที่แสดงโดยวัตถุปัจจุบัน |
| void [AddLines](./addlines/)(const [ArrayPtr](../../system/arrayptr/)\<[PointF](../../system.drawing/pointf/)\>\&) | เพิ่มลำดับของส่วนเส้นที่เชื่อมต่อกันไปยังพาธที่แสดงโดยวัตถุปัจจุบัน |
| void [AddLines](./addlines/)(const [ArrayPtr](../../system/arrayptr/)\<[Point](../../system.drawing/point/)\>\&) | เพิ่มลำดับของส่วนเส้นที่เชื่อมต่อกันไปยังพาธที่แสดงโดยวัตถุปัจจุบัน |
| void [AddPath](./addpath/)(const [SharedPtr](../../system/sharedptr/)\<[GraphicsPath](./)\>\&, **bool**) | เพิ่มพาธที่ระบุไปยังพาธที่แสดงโดยวัตถุปัจจุบัน |
| void [AddPie](./addpie/)(**float**, **float**, **float**, **float**, **float**, **float**) | เพิ่มโครงร่างของรูปพายที่ระบุไปยังพาธที่แสดงโดยวัตถุปัจจุบัน |
| void [AddPie](./addpie/)(int, int, int, int, **float**, **float**) | เพิ่มโครงร่างของรูปพายที่ระบุไปยังพาธที่แสดงโดยวัตถุปัจจุบัน |
| void [AddPie](./addpie/)(const [Rectangle](../../system.drawing/rectangle/)\&, **float**, **float**) | เพิ่มโครงร่างของรูปพายที่ระบุไปยังพาธที่แสดงโดยวัตถุปัจจุบัน |
| void [AddPolygon](./addpolygon/)(const [ArrayPtr](../../system/arrayptr/)\<[PointF](../../system.drawing/pointf/)\>\&) | เพิ่มรูปหลายเหลี่ยมที่ระบุไปยังพาธที่แสดงโดยวัตถุปัจจุบัน |
| void [AddPolygon](./addpolygon/)(const [ArrayPtr](../../system/arrayptr/)\<[Point](../../system.drawing/point/)\>\&) | เพิ่มรูปหลายเหลี่ยมที่ระบุไปยังพาธที่แสดงโดยวัตถุปัจจุบัน |
| void [AddRectangle](./addrectangle/)(const [Rectangle](../../system.drawing/rectangle/)\&) | เพิ่มสี่เหลี่ยมที่ระบุไปยังพาธที่แสดงโดยวัตถุปัจจุบัน |
| void [AddRectangle](./addrectangle/)(const [RectangleF](../../system.drawing/rectanglef/)\&) | เพิ่มสี่เหลี่ยมที่ระบุไปยังพาธที่แสดงโดยวัตถุปัจจุบัน |
| void [AddRectangles](./addrectangles/)(const [ArrayPtr](../../system/arrayptr/)\<[Rectangle](../../system.drawing/rectangle/)\>\&) | เพิ่มลำดับของสี่เหลี่ยมที่ระบุไปยังพาธที่แสดงโดยวัตถุปัจจุบัน |
| void [AddRectangles](./addrectangles/)(const [ArrayPtr](../../system/arrayptr/)\<[RectangleF](../../system.drawing/rectanglef/)\>\&) | เพิ่มลำดับของสี่เหลี่ยมที่ระบุไปยังพาธที่แสดงโดยวัตถุปัจจุบัน |
| void [AddString](./addstring/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[FontFamily](../../system.drawing/fontfamily/)\>\&, int, **float**, [Point](../../system.drawing/point/), const [SharedPtr](../../system/sharedptr/)\<[StringFormat](../../system.drawing/stringformat/)\>\&) | เพิ่มสตริงข้อความไปยังพาธที่แสดงโดยวัตถุปัจจุบัน |
| void [AddString](./addstring/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[FontFamily](../../system.drawing/fontfamily/)\>\&, int, **float**, [PointF](../../system.drawing/pointf/), const [SharedPtr](../../system/sharedptr/)\<[StringFormat](../../system.drawing/stringformat/)\>\&) | เพิ่มสตริงข้อความไปยังพาธที่แสดงโดยวัตถุปัจจุบัน |
| void [AddString](./addstring/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[FontFamily](../../system.drawing/fontfamily/)\>\&, int, **float**, [Rectangle](../../system.drawing/rectangle/), const [SharedPtr](../../system/sharedptr/)\<[StringFormat](../../system.drawing/stringformat/)\>\&) | เพิ่มสตริงข้อความไปยังพาธที่แสดงโดยวัตถุปัจจุบัน |
| void [AddString](./addstring/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[FontFamily](../../system.drawing/fontfamily/)\>\&, int, **float**, [RectangleF](../../system.drawing/rectanglef/), const [SharedPtr](../../system/sharedptr/)\<[StringFormat](../../system.drawing/stringformat/)\>\&) | เพิ่มสตริงข้อความไปยังพาธที่แสดงโดยวัตถุปัจจุบัน |
| virtual [SharedPtr](../../system/sharedptr/)\<[GraphicsPath](./)\> [Clone](./clone/)() | สร้างสำเนาของวัตถุปัจจุบัน |
| void [CloseAllFigures](./closeallfigures/)() | ปิดรูปทั้งหมดที่เปิดอยู่และเริ่มรูปใหม่ |
| void [CloseFigure](./closefigure/)() | ปิดรูปปัจจุบันและเริ่มรูปใหม่ |
| void [Dispose](./dispose/)() | ปล่อยทรัพยากรระบบปฏิบัติการทั้งหมดที่วัตถุปัจจุบันได้ครอบครอง |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | เปรียบเทียบอ็อบเจ็กต์โดยใช้เซมานติกของ C# [Object.Equals](../../system/object/equals/) |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจ็กต์ประเภทอ้างอิงในสไตล์ C# |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจ็กต์ประเภทค่าในสไตล์ C# |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | จำลองการเปรียบเทียบจุดลอยตามสไตล์ C# ซึ่ง NaN สองค่าถือว่าเท่ากันแม้ว่าตามมาตรฐาน IEC 60559:1989 NaN จะไม่เท่ากับค่าใดๆ รวมถึง NaN เอง |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | จำลองการเปรียบเทียบจุดลอยตามสไตล์ C# สำหรับ double ซึ่ง NaN สองค่าถือว่าเท่ากันแม้ตาม IEC 60559:1989 NaN จะไม่เท่ากับค่าใดๆ รวมถึง NaN เอง |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | สำหรับการใช้งานภายในเท่านั้น |
| void [Flatten](./flatten/)() | ทำให้โค้งแต่ละอันในพาธแบนลงโดยแปลงเป็นลำดับของเส้นที่เชื่อมต่อกัน ใช้ค่าความแบน 0.25 |
| void [Flatten](./flatten/)(const [MatrixPtr](../matrixptr/)\&) | ทำให้โค้งแต่ละอันในพาธแบนลงโดยแปลงเป็นลำดับของเส้นที่เชื่อมต่อกัน ใช้ค่าความแบน 0.25 |
| void [Flatten](./flatten/)(const [MatrixPtr](../matrixptr/)\&, **float**) | ทำให้โค้งแต่ละอันในพาธแบนลงโดยแปลงเป็นลำดับของเส้นที่เชื่อมต่อกัน |
| [FillMode](../fillmode/) [get_FillMode](./get_fillmode/)() | คืนค่าโหมดการเติมของวัตถุปัจจุบัน |
| [SharedPtr](../../system/sharedptr/)\<[PathData](../pathdata/)\> [get_PathData](./get_pathdata/)() | คืนอ็อบเจ็กต์ [PathData](../pathdata/) ที่บรรจุดที่ประกอบเป็นพาธที่แสดงโดยวัตถุปัจจุบันและประเภทของจุดเหล่านั้น |
| [ArrayPtr](../../system/arrayptr/)\<[PointF](../../system.drawing/pointf/)\> [get_PathPoints](./get_pathpoints/)() const | คืนอาเรย์ที่บรรจุดที่ประกอบเป็นพาธที่แสดงโดยวัตถุปัจจุบัน |
| [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [get_PathTypes](./get_pathtypes/)() const | คืนอาเรย์ที่บรรจุค่าที่แสดงประเภทของจุดที่ประกอบเป็นพาธที่แสดงโดยวัตถุปัจจุบัน |
| int [get_PointCount](./get_pointcount/)() const | คืนจำนวนจุดในพาธที่แสดงโดยวัตถุปัจจุบัน |
| [RectangleF](../../system.drawing/rectanglef/) [GetBounds](./getbounds/)(const [MatrixPtr](../matrixptr/)\&, const [SharedPtr](../../system/sharedptr/)\<[Pen](../../system.drawing/pen/)\>\&) const | คืนอ็อบเจ็กต์ [RectangleF](../../system.drawing/rectanglef/) ที่แสดงสี่เหลี่ยมที่ครอบพาธที่แสดงโดยวัตถุปัจจุบันเมื่อถูกแปลงด้วยเมทริกซ์ที่ระบุ |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | รับโครงสร้างข้อมูลตัวนับอ้างอิงที่เกี่ยวข้องกับอ็อบเจ็กต์ |
| Detail::FigureType [GetFigureFlags](./getfigureflags/)() | คืนค่าที่เป็นการผสมแบบบิตวายของค่า Detail::FigureType ที่บ่งชี้ประเภทของรูปที่อยู่ในพาธที่แสดงโดยวัตถุปัจจุบัน |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | เป็นแบบจำลองของเมธอด C# [Object.GetHashCode()](../../system/object/gethashcode/) เปิดใช้งานการสร้างแฮชของอ็อบเจ็กต์แบบกำหนดเอง |
| [PointF](../../system.drawing/pointf/) [GetLastPoint](./getlastpoint/)() const | คืนอ็อบเจ็กต์ [PointF](../../system.drawing/pointf/) ที่แสดงจุดสุดท้ายในพาธ |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | รับประเภทจริงของอ็อบเจ็กต์ แบบจำลองของการเรียก C# [System.Object.GetType()](../../system/object/gettype/) |
|  [GraphicsPath](./graphicspath/)([FillMode](../fillmode/)) | สร้างอินสแตนซ์ใหม่ของคลาส [GraphicsPath](./) ด้วยโหมดการเติมที่ระบุ |
|  [GraphicsPath](./graphicspath/)(const [ArrayPtr](../../system/arrayptr/)\<[Point](../../system.drawing/point/)\>\&, const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, [FillMode](../fillmode/)) | สร้างอินสแตนซ์ใหม่ของอ็อบเจ็กต์ [GraphicsPath](./) ที่แทนพาธที่ระบุ |
|  [GraphicsPath](./graphicspath/)(const [ArrayPtr](../../system/arrayptr/)\<[PointF](../../system.drawing/pointf/)\>\&, const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, [FillMode](../fillmode/)) | สร้างอินสแตนซ์ใหม่ของอ็อบเจ็กต์ [GraphicsPath](./) ที่แทนพาธที่ระบุ |
|  [GraphicsPath](./graphicspath/)(const SkPath\&) |  |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | ตรวจสอบว่าอ็อบเจ็กต์เป็นอินสแตนซ์ของประเภทที่อธิบายโดย targetType แบบจำลองของโอเปอเรเตอร์ C# 'is' |
| **bool** [IsOutlineVisible](./isoutlinevisible/)(const [PointF](../../system.drawing/pointf/)\&, const [SharedPtr](../../system/sharedptr/)\<[Pen](../../system.drawing/pen/)\>\&) | ระบุว่าจุดที่ระบุอยู่ภายใน (ภายใต้) โครงร่างของ [GraphicsPath](./) เมื่อวาดด้วย [Pen](../../system.drawing/pen/) หรือไม่ ไม่ได้ดำเนินการ |
| **bool** [IsVisible](./isvisible/)(const [PointF](../../system.drawing/pointf/)\&) | กำหนดว่าจุดที่ระบุอยู่ภายในพาธที่แสดงโดยวัตถุปัจจุบันหรือไม่ |
| **bool** [IsVisible](./isvisible/)(**float**, **float**) | กำหนดว่าจุดที่ระบุอยู่ภายในพาธที่แสดงโดยวัตถุปัจจุบันหรือไม่ |
| void [Lock](../../system/object/lock/)() | ดำเนินการล็อกตามคำสั่ง C# lock() เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/) |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | เป็นแบบจำลองของเมธอด C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) เปิดใช้งานการโคลนประเภทกำหนดเอง |
|  [Object](../../system/object/object/)() | สร้างอ็อบเจ็กต์ เริ่มต้นโครงสร้างข้อมูลภายในทั้งหมด |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | คอนสตรัคเตอร์คัดลอก ไม่ได้คัดลอกอะไรจริง ๆ เพียงแค่เริ่มต้นอ็อบเจ็กต์ใหม่และเปิดใช้งานการคัดลอกสร้างซับคลาส |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | โอเปอเรเตอร์การกำหนดค่า ไม่ได้คัดลอกอะไรจริง ๆ เพียงแค่เริ่มต้นอ็อบเจ็กต์ใหม่และเปิดใช้งานการคัดลอกสร้างซับคลาส |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | เปรียบเทียบอ็อบเจ็กต์โดยอ้างอิง |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | เปรียบเทียบอ็อบเจ็กต์โดยอ้างอิง |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | เปรียบเทียบอ้างอิงของอ็อบเจ็กต์ประเภทค่า กับ nullptr |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | การพิเศษของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริงและ nullptr |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | การพิเศษของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริง |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | ลดจำนวนอ้างอิงที่แชร์โดยค่าที่ระบุ |
| void [Reset](./reset/)() | ล้างพาธโดยลบจุดทั้งหมดออกจากพาธ |
| void [Reverse](./reverse/)() | กลับลำดับของจุดในอาเรย์ PathPoints ของ [GraphicsPath](./) นี้ |
| void [set_FillMode](./set_fillmode/)([FillMode](../fillmode/)) | ตั้งค่าโหมดการเติมของวัตถุปัจจุบัน |
| void [SetMarkers](./setmarkers/)() | ยังไม่ได้ดำเนินการ |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | ตั้งค่าอาร์กิวเมนต์เทมเพลตที่ n ให้เป็น weak pointer (แทนที่จะเป็น shared) อนุญาตให้สลับพอยน์เตอร์ในคอนเทนเนอร์เป็นโหมด weak |
| int [SharedCount](../../system/object/sharedcount/)() const | รับค่าปัจจุบันของตัวนับอ้างอิงที่แชร์ |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | เพิ่มจำนวนอ้างอิงที่แชร์ ไม่ควรเรียกโดยตรง; แทนใช้ smart pointer หรือ ThisProtector |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ลดและคืนค่าตัวนับอ้างอิงที่แชร์ ไม่ควรเรียกโดยตรง; แทนใช้ smart pointer หรือ ThisProtector |
| void [StartFigure](./startfigure/)() | เริ่มรูปใหม่ |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | เป็นแบบจำลองของเมธอด C# [Object.ToString()](../../system/object/tostring/) เปิดใช้งานการแปลงอ็อบเจ็กต์กำหนดเองเป็นสตริง |
| void [Transform](./transform/)(const [MatrixPtr](../matrixptr/)\&) | แปลงพาธที่แสดงโดยวัตถุปัจจุบันโดยใช้เมทริกซ์แปลงที่ระบุ |
| void [Transform](./transform/)(const SkMatrix\&) |  |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ดำเนินการสร้าง C# typeof([System.Object](../../system/object/)) |
| void [Unlock](../../system/object/unlock/)() | ดำเนินการปลดล็อกตามคำสั่ง C# lock() เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/) |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | เพิ่มจำนวนอ้างอิงแบบ weak ไม่ควรเรียกโดยตรง; แทนใช้ smart pointer หรือ ThisProtector |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ลดจำนวนอ้างอิงแบบ weak ไม่ควรเรียกโดยตรง; แทนใช้ smart pointer หรือ ThisProtector |
| void [Widen](./widen/)(const [SharedPtr](../../system/sharedptr/)\<[Pen](../../system.drawing/pen/)\>\&) | แทนที่พาธนี้ด้วยโครงรอบพาธเดิม |
|  [~GraphicsPath](./~graphicspath/)() | ตัวทำลาย |
| virtual  [~Object](../../system/object/~object/)() | ทำลายอ็อบเจ็กต์ ปล่อยโครงสร้างข้อมูลภายในทั้งหมด |

## ดูเพิ่มเติม

* คลาส [Object](../../system/object/)
* เนมสเปซ [System::Drawing::Drawing2D](../)
* ไลบรารี [Aspose.Slides](../../)