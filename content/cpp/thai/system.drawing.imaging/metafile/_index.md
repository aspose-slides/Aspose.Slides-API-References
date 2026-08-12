---
title: Metafile
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: "เป็นตัวแทนของ metafile กราฟิก. อ็อบเจ็กต์ของคลาสนี้ควรสร้างเท่านั้นโดยใช้ฟังก์ชัน System::MakeObject(). อย่าสร้างอินสแตนซ์ของประเภทนี้บนสแตกหรือโดยใช้ operator new เนื่องจากจะทำให้เกิดข้อผิดพลาดขณะรันไทม์และ/หรือข้อบกพร่องของการอ้างอิง. ควรห่อคลาสนี้ในพอยน์เตอร์ System::SmartPtr เสมอและใช้พอยน์เตอร์นี้เพื่อส่งผ่านเป็นอาร์กิวเมนต์ให้กับฟังก์ชัน."
type: docs
weight: 144
url: /th/system.drawing.imaging/metafile/
---
## คลาส Metafile

เป็นตัวแทนของ metafile กราฟิก. อ็อบเจ็กต์ของคลาสนี้ควรสร้างโดยใช้ฟังก์ชัน [System::MakeObject()](../../system/makeobject/) เท่านั้น. ห้ามสร้างอินสแตนซ์ของประเภทนี้บนสแตกหรือโดยใช้ operator new เนื่องจากจะทำให้เกิดข้อผิดพลาดขณะรันไทม์และ/หรือข้อบกพร่องของการอ้างอิง. ควรห่อคลาสนี้ในพอยน์เตอร์ [System::SmartPtr](../../system/smartptr/) เสมอและใช้พอยน์เตอร์นี้เพื่อส่งผ่านเป็นอาร์กิวเมนต์ให้กับฟังก์ชัน.

```cpp
class Metafile : public System::Drawing::Image
```

## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [SharedPtr](../../system/sharedptr/)\<[Image](../../system.drawing/image/)\> [Clone](./clone/)() override | ส่งคืนสำเนาของอ็อบเจ็กต์ปัจจุบัน |
| void [Dispose](../../system.drawing/image/dispose/)() override | ปลดปล่อยทรัพยากรทั้งหมดที่อ็อบเจ็กต์ปัจจุบันได้ครอบครอง |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | เปรียบเทียบอ็อบเจ็กต์โดยใช้แนวคิดของ C# [Object.Equals](../../system/object/equals/) |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจ็กต์ประเภทอ้างอิงในรูปแบบ C# |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจ็กต์ประเภทค่าในรูปแบบ C# |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | จำลองการเปรียบเทียบจุดลอยตามสไตล์ C# ที่ NaN สองค่า จะถือว่าเท่ากัน แม้ตาม IEC 60559:1989 NaN ไม่เท่ากับค่าใด ๆ รวมถึง NaN |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | จำลองการเปรียบเทียบจุดลอยตามสไตล์ C# ที่ NaN สองค่า จะถือว่าเท่ากัน แม้ตาม IEC 60559:1989 NaN ไม่เท่ากับค่าใด ๆ รวมถึง NaN |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | เพื่อวัตถุประสงค์ภายในเท่านั้น |
| static [SharedPtr](../../system/sharedptr/)\<[Image](../../system.drawing/image/)\> [FromFile](../../system.drawing/image/fromfile/)(const [String](../../system/string/)\&, **bool**) | สร้างอ็อบเจ็กต์ [Image](../../system.drawing/image/) จากไฟล์ที่กำหนด |
| static [SharedPtr](../../system/sharedptr/)\<[Bitmap](../../system.drawing/bitmap/)\> [FromHbitmap](../../system.drawing/image/fromhbitmap/)(IntPtr) | สร้างอ็อบเจ็กต์ [Bitmap](../../system.drawing/bitmap/) จาก GDI bitmap ที่กำหนด |
| static [SharedPtr](../../system/sharedptr/)\<[Image](../../system.drawing/image/)\> [FromStream](../../system.drawing/image/fromstream/)(const [SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>\&, **bool**, **bool**) | สร้างอ็อบเจ็กต์ [Image](../../system.drawing/image/) จากสตรีมที่กำหนด |
| virtual **int32_t** [get_Flags](../../system.drawing/image/get_flags/)() const | ส่งคืนการรวมแบบบิตของค่า enum ImageFlags ที่แสดงคุณลักษณะของภาพ |
| [ArrayPtr](../../system/arrayptr/)\<[Guid](../../system/guid/)\> [get_FrameDimensionsList](../../system.drawing/image/get_framedimensionslist/)() const | ส่งคืนอาร์เรย์ของ GUIDs ที่แสดงมิติของเฟรมภายในภาพที่อ็อบเจ็กต์ปัจจุบันเป็นตัวแทน |
| int [get_Height](./get_height/)() const override | ส่งคืนความสูงของภาพเป็นพิกเซล |
| **float** [get_HorizontalResolution](../../system.drawing/image/get_horizontalresolution/)() const | ส่งคืนความละเอียดแนวนอนของภาพที่อ็อบเจ็กต์ปัจจุบันเป็นพิกเซลต่ออินช์ |
| virtual [Imaging::ColorPalettePtr](../colorpaletteptr/) [get_Palette](../../system.drawing/image/get_palette/)() const | ส่งคืนพาเลตสีที่ใช้โดยภาพที่อ็อบเจ็กต์ปัจจุบันเป็นตัวแทน |
| [Imaging::PixelFormat](../pixelformat/) [get_PixelFormat](./get_pixelformat/)() const override | ส่งคืนค่าที่ระบุรูปแบบพิกเซล |
| virtual [ArrayPtr](../../system/arrayptr/)\<int\> [get_PropertyIdList](../../system.drawing/image/get_propertyidlist/)() const | รับ ID ของรายการคุณสมบัติที่เก็บไว้ในภาพนี้ |
| virtual [ArrayPtr](../../system/arrayptr/)\<[SharedPtr](../../system/sharedptr/)\<[Imaging::PropertyItem](../propertyitem/)\>\> [get_PropertyItems](../../system.drawing/image/get_propertyitems/)() const | รับคุณสมบัติต่าง ๆ (ส่วนของเมตาดาต้า) ที่เก็บในภาพนี้ |
| [Imaging::ImageFormatPtr](../imageformatptr/) [get_RawFormat](./get_rawformat/)() const override | ส่งคืนค่าที่ระบุรูปแบบภาพ |
| [Size](../../system.drawing/size/) [get_Size](../../system.drawing/image/get_size/)() const | ส่งคืนอ็อบเจ็กต์ [Size](../../system.drawing/size/) ที่แทนความกว้างและความสูงของภาพเป็นพิกเซล |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\> [get_Tag](../../system.drawing/image/get_tag/)() const | รับอ็อบเจ็กต์ที่ให้ข้อมูลเพิ่มเติมเกี่ยวกับภาพ |
| **float** [get_VerticalResolution](../../system.drawing/image/get_verticalresolution/)() const | ส่งคืนความละเอียดตามแนวตั้งของภาพที่อ็อบเจ็กต์ปัจจุบันเป็นพิกเซลต่ออินช์ |
| int [get_Width](./get_width/)() const override | ส่งคืนความกว้างของภาพเป็นพิกเซล |
| [RectangleF](../../system.drawing/rectanglef/) [GetBounds](../../system.drawing/image/getbounds/)([GraphicsUnit](../../system.drawing/graphicsunit/)\&) | ส่งคืนขอบเขตของภาพในหน่วยการวัดที่กำหนด |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | รับโครงสร้างข้อมูลตัวนับอ้างอิงที่เชื่อมโยงกับอ็อบเจ็กต์ |
| int [GetFrameCount](../../system.drawing/image/getframecount/)(const [Imaging::FrameDimensionPtr](../framedimensionptr/)\&) | ส่งคืนจำนวนเฟรมของมิติเฟรมที่กำหนด |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | เป็นเวอร์ชันของเมธอด C# [Object.GetHashCode()](../../system/object/gethashcode/). เปิดใช้งานการแฮชอ็อบเจ็กต์แบบกำหนดเอง |
| IntPtr [GetHenhmetafile](./gethenhmetafile/)() | ยังไม่ได้ดำเนินการ |
| [SharedPtr](../../system/sharedptr/)\<[MetafileHeader](../metafileheader/)\> [GetMetafileHeader](./getmetafileheader/)() | ส่งคืนส่วนหัวที่เกี่ยวข้องกับอ็อบเจ็กต์ปัจจุบัน |
| static int [GetPixelFormatSize](../../system.drawing/image/getpixelformatsize/)([Imaging::PixelFormat](../pixelformat/)) | ส่งคืนจำนวนบิตที่ใช้แสดงความลึกของสีในรูปแบบพิกเซลที่ระบุ |
| [SharedPtr](../../system/sharedptr/)\<[Image](../../system.drawing/image/)\> [GetThumbnailImage](../../system.drawing/image/getthumbnailimage/)(int, int, [Image::GetThumbnailImageAbort](../../system.drawing/image/getthumbnailimageabort/), IntPtr) | รับภาพย่อสำหรับอ็อบเจ็กต์ [System::Drawing::Image](../../system.drawing/image/) นี้ |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | รับประเภทจริงของอ็อบเจ็กต์. เป็นเวอร์ชันของการเรียก C# [System.Object.GetType()](../../system/object/gettype/) |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | ตรวจสอบว่าอ็อบเจ็กต์เป็นอินสแตนซ์ของประเภทที่อธิบายโดย targetType. เป็นเวอร์ชันของออปเรเตอร์ 'is' ของ C# |
| static **bool** [IsAlphaPixelFormat](../../system.drawing/image/isalphapixelformat/)([Imaging::PixelFormat](../pixelformat/)) | กำหนดว่ารูปแบบพิกเซลที่ระบุมีข้อมูลอัลฟา |
| virtual **bool** [IsMultiImage](../../system.drawing/image/ismultiimage/)() const | ส่งคืนว่ารูปแบบเดิมเป็นหลายภาพหรือไม่ |
| void [Lock](../../system/object/lock/)() | ทำการล็อกตามคำสั่ง lock() ของ C#. เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/) |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | เป็นเวอร์ชันของเมธอด C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). เปิดใช้งานการโคลนชนิดที่กำหนดเอง |
|  [Metafile](./metafile/)(const [System::String](../../system/string/)\&) | ยังไม่ได้ดำเนินการ |
|  [Metafile](./metafile/)(const [SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>\&) | ยังไม่ได้ดำเนินการ |
|  [Metafile](./metafile/)(const [SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>\&, IntPtr, [EmfType](../emftype/)) | ยังไม่ได้ดำเนินการ |
|  [Metafile](./metafile/)(const [SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>\&, IntPtr) | ยังไม่ได้ดำเนินการ |
|  [Metafile](./metafile/)(const [SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>\&, IntPtr, [Rectangle](../../system.drawing/rectangle/), [MetafileFrameUnit](../metafileframeunit/), [EmfType](../emftype/)) | ยังไม่ได้ดำเนินการ |
|  [Metafile](./metafile/)(const [SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>\&, IntPtr, [RectangleF](../../system.drawing/rectanglef/), [MetafileFrameUnit](../metafileframeunit/), [EmfType](../emftype/)) | ยังไม่ได้ดำเนินการ |
|  [Metafile](./metafile/)(IntPtr, [EmfType](../emftype/)) | ยังไม่ได้ดำเนินการ |
|  [Object](../../system/object/object/)() | สร้างอ็อบเจ็กต์. เริ่มต้นโครงสร้างข้อมูลภายในทั้งหมด |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | คอนสตรัคเตอร์สำเนา. จริง ๆ แล้วไม่ได้คัดลอกอะไรเลย เพียงแค่เริ่มต้นอ็อบเจ็กต์ใหม่และเปิดใช้งานการสร้างสำเนาสำหรับซับคลาส |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | โอเปอเรเตอร์กำหนดค่า. จริง ๆ แล้วไม่ได้คัดลอกอะไรเลย เพียงแค่เริ่มต้นอ็อบเจ็กต์ใหม่และเปิดใช้งานการสร้างสำเนาสำหรับซับคลาส |
| void [PlayRecord](./playrecord/)([EmfPlusRecordType](../emfplusrecordtype/), **int32_t**, **int32_t**, [System::ByteArrayPtr](../../system/bytearrayptr/)) | ยังไม่ได้ดำเนินการ |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | เปรียบเทียบอ็อบเจ็กต์โดยอ้างอิง |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | เปรียบเทียบอ็อบเจ็กต์โดยอ้างอิง |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | เปรียบเทียบอ้างอิงอ็อบเจ็กต์ประเภทค่ากับ nullptr |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | เป็นการแยกประเภทของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริงและ nullptr |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | เป็นการแยกประเภทของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริง |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | ลดจำนวนการอ้างอิงร่วมโดยค่าที่ระบุ |
| virtual void [RotateFlip](../../system.drawing/image/rotateflip/)([RotateFlipType](../../system.drawing/rotatefliptype/)) | หมุนภาพเป็นหลายของ 90 องศาและพลิก |
| void [Save](../../system.drawing/image/save/)(const [String](../../system/string/)\&) | บันทึกภาพที่อ็อบเจ็กต์ปัจจุบันเป็นตัวแทนลงไฟล์ที่กำหนดในรูปแบบ PNG |
| void [Save](../../system.drawing/image/save/)(const [String](../../system/string/)\&, const [Imaging::ImageFormatPtr](../imageformatptr/)\&) | บันทึกภาพที่อ็อบเจ็กต์ปัจจุบันเป็นตัวแทนลงไฟล์ที่กำหนดในรูปแบบที่ระบุ |
| void [Save](../../system.drawing/image/save/)(const [SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>\&, const [Imaging::ImageFormatPtr](../imageformatptr/)\&) | บันทึกภาพที่อ็อบเจ็กต์ปัจจุบันเป็นตัวแทนลงสตรีมที่กำหนดในรูปแบบที่ระบุ |
| void [Save](../../system.drawing/image/save/)(const [String](../../system/string/)\&, const [Imaging::ImageCodecInfoPtr](../imagecodecinfoptr/)\&, const [Imaging::EncoderParametersPtr](../encoderparametersptr/)\&) | บันทึกภาพที่อ็อบเจ็กต์ปัจจุบันเป็นตัวแทนลงไฟล์ที่กำหนดโดยใช้ encoder และพารามิเตอร์ encoder ที่ระบุ |
| void [Save](../../system.drawing/image/save/)(const [SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>\&, const [Imaging::ImageCodecInfoPtr](../imagecodecinfoptr/)\&, const [Imaging::EncoderParametersPtr](../encoderparametersptr/)\&) | บันทึกภาพที่อ็อบเจ็กต์ปัจจุบันเป็นตัวแทนลงสตรีมที่กำหนดโดยใช้ encoder และพารามิเตอร์ encoder ที่ระบุ |
| void [SaveAdd](../../system.drawing/image/saveadd/)(const [Imaging::EncoderParametersPtr](../encoderparametersptr/)\&) | เพิ่มเฟรมลงไฟล์หรือสตรีมที่ระบุในการเรียกก่อนหน้าของเมธอด [Save()](../../system.drawing/image/save/) |
| void [SaveAdd](../../system.drawing/image/saveadd/)(const [SharedPtr](../../system/sharedptr/)\<[Image](../../system.drawing/image/)\>\&, const [Imaging::EncoderParametersPtr](../encoderparametersptr/)\&) | เพิ่มเฟรมลงไฟล์หรือสตรีมที่ระบุในการเรียกก่อนหน้าของเมธอด [Save()](../../system.drawing/image/save/) |
| int [SelectActiveFrame](../../system.drawing/image/selectactiveframe/)(const [Imaging::FrameDimensionPtr](../framedimensionptr/)\&, int) | เลือกเฟรมที่ระบุ |
| virtual void [set_Palette](../../system.drawing/image/set_palette/)([Imaging::ColorPalettePtr](../colorpaletteptr/)) | ตั้งพาเลตสีที่ใช้โดยภาพที่อ็อบเจ็กต์ปัจจุบันเป็นตัวแทน |
| virtual void [set_Tag](../../system.drawing/image/set_tag/)(const [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) | ตั้งอ็อบเจ็กต์ที่ให้ข้อมูลเพิ่มเติมเกี่ยวกับภาพ |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | ตั้งเทมเพลตอาร์กูเมนต์ที่ n ให้เป็น weak pointer (แทนที่ shared). อนุญาตให้สลับพอยน์เตอร์ในคอนเทนเนอร์เป็นโหมด weak |
| int [SharedCount](../../system/object/sharedcount/)() const | รับค่าปัจจุบันของตัวนับการอ้างอิงร่วม |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | เพิ่มจำนวนตัวนับการอ้างอิงร่วม. ไม่ควรเรียกโดยตรง; ควรใช้ smart pointers หรือ ThisProtector |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ลดจำนวนตัวนับการอ้างอิงร่วมและคืนค่า. ไม่ควรเรียกโดยตรง; ควรใช้ smart pointers หรือ ThisProtector |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | เป็นเวอร์ชันของเมธอด C# [Object.ToString()](../../system/object/tostring/). เปิดใช้งานการแปลงอ็อบเจ็กต์แบบกำหนดเองเป็นสตริง |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ทำตามโครงสร้าง typeof([System.Object](../../system/object/)) ของ C# |
| void [Unlock](../../system/object/unlock/)() | ทำการปลดล็อกตามคำสั่ง lock() ของ C#. เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/) |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | เพิ่มจำนวนตัวนับการอ้างอิงแบบ weak. ไม่ควรเรียกโดยตรง; ควรใช้ smart pointers หรือ ThisProtector |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ลดจำนวนตัวนับการอ้างอิงแบบ weak. ไม่ควรเรียกโดยตรง; ควรใช้ smart pointers หรือ ThisProtector |
| virtual  [~Metafile](./~metafile/)() | ตัวทำลาย |
| virtual  [~Object](../../system/object/~object/)() | ทำลายอ็อบเจ็กต์. ปล่อยโครงสร้างข้อมูลภายในทั้งหมด |

## ดูเพิ่มเติม

* คลาส [Image](../../system.drawing/image/)
* เนมสเปซ [System::Drawing::Imaging](../)
* ไลบรารี [Aspose.Slides](../../)