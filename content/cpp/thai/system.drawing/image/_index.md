---
title: Image
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: "เป็นคลาสฐานสำหรับคลาส System::Drawing::Bitmap และ System::Drawing::Metafile ที่ให้ฟังก์ชันพื้นฐาน วัตถุของคลาสนี้ควรจัดสรรโดยใช้ฟังก์ชัน System::MakeObject() เท่านั้น ไม่ควรสร้างอินสแตนซ์ของประเภทนี้บนสแตกหรือโดยใช้ตัวดำเนินการ new เพราะจะทำให้เกิดข้อผิดพลาดรันไทม์และ/หรือการตรวจสอบข้อเรียกร้อง เสมอห่อคลาสนี้ด้วยตัวชี้ System::SmartPtr และใช้ตัวชี้นี้เพื่อส่งเป็นอาร์กิวเมนต์ให้กับฟังก์ชัน"
type: docs
weight: 144
url: /th/system.drawing/image/
---
## คลาส Image

เป็นคลาสฐานสำหรับ [System::Drawing::Bitmap](../bitmap/) และคลาส System::Drawing::Metafile ที่ให้ฟังก์ชันพื้นฐาน วัตถุของคลาสนี้ควรถูกจัดสรรด้วยฟังก์ชัน [System::MakeObject()](../../system/makeobject/) เท่านั้น อย่าสร้างอินสแตนซ์ของประเภทนี้บนสแตกหรือด้วยตัวดำเนินการ new เพราะจะทำให้เกิดข้อผิดพลาดรันไทม์และ/หรือการตรวจสอบข้อเรียกร้อง เสมอห่อคลาสนี้ด้วยตัวชี้ [System::SmartPtr](../../system/smartptr/) และใช้ตัวชี้นี้เพื่อส่งเป็นอาร์กิวเมนต์ให้กับฟังก์ชัน

```cpp
class Image : public virtual System::IDisposable
```

## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| virtual [SharedPtr](../../system/sharedptr/)\<[Image](./)\> [Clone](./clone/)() | สร้างสำเนาของอ็อบเจ็กต์ปัจจุบัน. |
| void [Dispose](./dispose/)() override | ปล่อยทรัพยากรทั้งหมดที่อ็อบเจ็กต์ปัจจุบันได้ครอบครอง. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | เปรียบเทียบอ็อบเจ็กต์โดยใช้เซมานติกของ C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจ็กต์ประเภทอ้างอิงตามสไตล์ของ C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจ็กต์ประเภทค่าแบบสไตล์ C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | จำลองการเปรียบเทียบเลขทศนิยมแบบ C# โดยที่ NaN สองค่าถือว่าเท่ากัน แม้ตามมาตรฐาน IEC 60559:1989 NaN จะไม่เท่ากับค่าใด ๆ รวมถึง NaN ด้วย. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | จำลองการเปรียบเทียบเลขทศนิยมแบบ C# โดยที่ NaN สองค่าถือว่าเท่ากัน แม้ตามมาตรฐาน IEC 60559:1989 NaN จะไม่เท่ากับค่าใด ๆ รวมถึง NaN ด้วย. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | เพื่อวัตถุประสงค์ภายในเท่านั้น. |
| static [SharedPtr](../../system/sharedptr/)\<[Image](./)\> [FromFile](./fromfile/)(const [String](../../system/string/)\&, **bool**) | สร้างอ็อบเจ็กต์ [Image](./) จากไฟล์ที่ระบุ. |
| static [SharedPtr](../../system/sharedptr/)\<[Bitmap](../bitmap/)\> [FromHbitmap](./fromhbitmap/)(IntPtr) | สร้างอ็อบเจ็กต์ [Bitmap](../bitmap/) จาก GDI bitmap ที่ระบุ. |
| static [SharedPtr](../../system/sharedptr/)\<[Image](./)\> [FromStream](./fromstream/)(const [SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>\&, **bool**, **bool**) | สร้างอ็อบเจ็กต์ [Image](./) จากสตรีมที่ระบุ. |
| virtual **int32_t** [get_Flags](./get_flags/)() const | คืนค่าการรวมแบบบิทของค่า enum ImageFlags ที่แสดงคุณลักษณะของรูปภาพ. |
| [ArrayPtr](../../system/arrayptr/)\<[Guid](../../system/guid/)\> [get_FrameDimensionsList](./get_framedimensionslist/)() const | คืนค่าอาเรย์ของ GUID ที่แสดงมิติของเฟรมภายในรูปภาพที่อ็อบเจ็กต์ปัจจุบันแทน. |
| virtual int [get_Height](./get_height/)() const | คืนค่าความสูงของรูปภาพเป็นพิกเซล. |
| **float** [get_HorizontalResolution](./get_horizontalresolution/)() const | คืนค่าความละเอียดแนวนอนของรูปภาพที่อ็อบเจ็กต์ปัจจุบันเป็นพิกเซลต่ออินช์. |
| virtual [Imaging::ColorPalettePtr](../../system.drawing.imaging/colorpaletteptr/) [get_Palette](./get_palette/)() const | คืนค่าพาเลตสีที่ใช้โดยรูปภาพที่อ็อบเจ็กต์ปัจจุบัน. |
| virtual [Imaging::PixelFormat](../../system.drawing.imaging/pixelformat/) [get_PixelFormat](./get_pixelformat/)() const | คืนค่าฟอร์แมตพิกเซลของรูปภาพที่อ็อบเจ็กต์ปัจจุบัน. |
| virtual [ArrayPtr](../../system/arrayptr/)\<int\> [get_PropertyIdList](./get_propertyidlist/)() const | รับ ID ของรายการคุณสมบัติที่เก็บไว้ในรูปภาพนี้. |
| virtual [ArrayPtr](../../system/arrayptr/)\<[SharedPtr](../../system/sharedptr/)\<[Imaging::PropertyItem](../../system.drawing.imaging/propertyitem/)\>\> [get_PropertyItems](./get_propertyitems/)() const | รับรายการคุณสมบัติต่าง ๆ (เมทาดาต้า) ที่เก็บไว้ในรูปภาพนี้ทั้งหมด. |
| virtual [Imaging::ImageFormatPtr](../../system.drawing.imaging/imageformatptr/) [get_RawFormat](./get_rawformat/)() const | คืนค่ารูปแบบไฟล์ของรูปภาพที่อ็อบเจ็กต์ปัจจุบัน. |
| [Size](../size/) [get_Size](./get_size/)() const | คืนค่าอ็อบเจ็กต์ [Size](../size/) ที่แสดงความกว้างและความสูงของรูปภาพเป็นพิกเซล. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\> [get_Tag](./get_tag/)() const | รับอ็อบเจ็กต์ที่ให้ข้อมูลเพิ่มเติมเกี่ยวกับรูปภาพ. |
| **float** [get_VerticalResolution](./get_verticalresolution/)() const | คืนค่าความละเอียดแนวตั้งของรูปภาพที่อ็อบเจ็กต์ปัจจุบันเป็นพิกเซลต่ออินช์. |
| virtual int [get_Width](./get_width/)() const | คืนค่าความกว้างของรูปภาพเป็นพิกเซล. |
| [RectangleF](../rectanglef/) [GetBounds](./getbounds/)([GraphicsUnit](../graphicsunit/)\&) | คืนค่าขอบเขตของรูปภาพในหน่วยการวัดที่ระบุ. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | รับโครงสร้างข้อมูลตัวนับการอ้างอิงที่เชื่อมโยงกับอ็อบเจ็กต์. |
| int [GetFrameCount](./getframecount/)(const [Imaging::FrameDimensionPtr](../../system.drawing.imaging/framedimensionptr/)\&) | คืนค่าจำนวนเฟรมของมิติเฟรมที่ระบุ. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | เป็นเสมือนเมธอด C# [Object.GetHashCode()](../../system/object/gethashcode/). เปิดการทำแฮชของอ็อบเจ็กต์ที่กำหนดเอง. |
| static int [GetPixelFormatSize](./getpixelformatsize/)([Imaging::PixelFormat](../../system.drawing.imaging/pixelformat/)) | คืนค่าจำนวนบิตที่ใช้แสดงความลึกสีในฟอร์แมตพิกเซลที่ระบุ. |
| virtual const SkBitmap * [GetSkBitmap](./getskbitmap/)() const | คืนค่าอ็อบเจ็กต์ SkBitmap พื้นฐาน. |
| [SharedPtr](../../system/sharedptr/)\<[Image](./)\> [GetThumbnailImage](./getthumbnailimage/)(int, int, [Image::GetThumbnailImageAbort](./getthumbnailimageabort/), IntPtr) | รับภาพย่อของอ็อบเจ็กต์ [System::Drawing::Image](./) นี้. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | รับประเภทจริงของอ็อบเจ็กต์. เป็นเสมือนการเรียก C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | ตรวจสอบว่าอ็อบเจ็กต์เป็นอินสแตนซ์ของประเภทที่อธิบายโดย targetType. เป็นเสมือนโอเปอเรเตอร์ 'is' ของ C#. |
| static **bool** [IsAlphaPixelFormat](./isalphapixelformat/)([Imaging::PixelFormat](../../system.drawing.imaging/pixelformat/)) | กำหนดว่าฟอร์แมตพิกเซลที่ระบุมีข้อมูลอัลฟาหรือไม่. |
| virtual **bool** [IsMultiImage](./ismultiimage/)() const | คืนค่าว่าเฟอร์แมตต้นฉบับเป็นภาพหลายรูปหรือไม่. |
| void [Lock](../../system/object/lock/)() | ทำหน้าที่ล็อกตามคำสั่ง lock() ของ C#. เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | เป็นเสมือนเมธอด C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). เปิดใช้งานการโคลนประเภทที่กำหนดเอง. |
|  [Object](../../system/object/object/)() | สร้างอ็อบเจ็กต์. เริ่มต้นโครงสร้างข้อมูลภายในทั้งหมด. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | คอนสตรักเตอร์คัดลอก. จริง ๆ แล้วไม่ได้คัดลอกอะไรเลย เพียงเริ่มต้นอ็อบเจ็กต์ใหม่และเปิดใช้งานการคัดลอกสร้างคลาสย่อย. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | โอเปอเรเตอร์กำหนดค่า. จริง ๆ แล้วไม่ได้คัดลอกอะไรเลย เพียงเริ่มต้นอ็อบเจ็กต์ใหม่และเปิดใช้งานการคัดลอกสร้างคลาสย่อย. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | เปรียบเทียบอ็อบเจ็กต์โดยอ้างอิง. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | เปรียบเทียบอ็อบเจ็กต์โดยอ้างอิง. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | เปรียบเทียบอ็อบเจ็กต์ประเภทค่ากับ nullptr ด้วยการอ้างอิง. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | การเฉพาะสำหรับ [Object::ReferenceEquals](../../system/object/referenceequals/) ในกรณีของสตริงและ nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | การเฉพาะสำหรับ [Object::ReferenceEquals](../../system/object/referenceequals/) ในกรณีของสตริงหลายตัว. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | ลดค่าตัวนับอ้างอิงที่แชร์ลงตามค่าที่ระบุ. |
| virtual void [RotateFlip](./rotateflip/)([RotateFlipType](../rotatefliptype/)) | หมุนรูปภาพเป็นหลายของ 90 องศาและพลิก. |
| void [Save](./save/)(const [String](../../system/string/)\&) | บันทึกรูปภาพที่อ็อบเจ็กต์ปัจจุบันแทนเป็นไฟล์ที่ระบุในรูปแบบ PNG. |
| void [Save](./save/)(const [String](../../system/string/)\&, const [Imaging::ImageFormatPtr](../../system.drawing.imaging/imageformatptr/)\&) | บันทึกรูปภาพที่อ็อบเจ็กต์ปัจจุบันแทนเป็นไฟล์ที่ระบุในรูปแบบที่กำหนด. |
| void [Save](./save/)(const [SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>\&, const [Imaging::ImageFormatPtr](../../system.drawing.imaging/imageformatptr/)\&) | บันทึกรูปภาพที่อ็อบเจ็กต์ปัจจุบันแทนเป็นสตรีมที่ระบุในรูปแบบที่กำหนด. |
| void [Save](./save/)(const [String](../../system/string/)\&, const [Imaging::ImageCodecInfoPtr](../../system.drawing.imaging/imagecodecinfoptr/)\&, const [Imaging::EncoderParametersPtr](../../system.drawing.imaging/encoderparametersptr/)\&) | บันทึกรูปภาพที่อ็อบเจ็กต์ปัจจุบันแทนเป็นไฟล์ที่ระบุโดยใช้ encoder และพารามิเตอร์ encoder ที่ระบุ. |
| void [Save](./save/)(const [SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>\&, const [Imaging::ImageCodecInfoPtr](../../system.drawing.imaging/imagecodecinfoptr/)\&, const [Imaging::EncoderParametersPtr](../../system.drawing.imaging/encoderparametersptr/)\&) | บันทึกรูปภาพที่อ็อบเจ็กต์ปัจจุบันแทนเป็นสตรีมที่ระบุโดยใช้ encoder และพารามิเตอร์ encoder ที่ระบุ. |
| void [SaveAdd](./saveadd/)(const [Imaging::EncoderParametersPtr](../../system.drawing.imaging/encoderparametersptr/)\&) | เพิ่มเฟรมลงในไฟล์หรือสตรีมที่ระบุในการเรียกเมธอด [Save()](./save/) ก่อนหน้า. |
| void [SaveAdd](./saveadd/)(const [SharedPtr](../../system/sharedptr/)\<[Image](./)\>\&, const [Imaging::EncoderParametersPtr](../../system.drawing.imaging/encoderparametersptr/)\&) | เพิ่มเฟรมลงในไฟล์หรือสตรีมที่ระบุในการเรียกเมธอด [Save()](./save/) ก่อนหน้า. |
| int [SelectActiveFrame](./selectactiveframe/)(const [Imaging::FrameDimensionPtr](../../system.drawing.imaging/framedimensionptr/)\&, int) | เลือกเฟรมที่ระบุ. |
| virtual void [set_Palette](./set_palette/)([Imaging::ColorPalettePtr](../../system.drawing.imaging/colorpaletteptr/)) | ตั้งค่าพาเลตสีที่รูปภาพที่อ็อบเจ็กต์ปัจจุบันแทนใช้. |
| virtual void [set_Tag](./set_tag/)(const [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) | ตั้งค่าอ็อบเจ็กต์ที่ให้ข้อมูลเพิ่มเติมเกี่ยวกับรูปภาพ. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | ตั้งเทมเพลตอาร์กิวเมนต์ที่ n ให้เป็น weak pointer (แทน shared). อนุญาตให้สลับพอยน์เตอร์ในคอนเทนเนอร์เป็นโหมด weak. |
| int [SharedCount](../../system/object/sharedcount/)() const | รับค่าปัจจุบันของตัวนับอ้างอิงที่แชร์. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | เพิ่มตัวนับอ้างอิงที่แชร์. ไม่ควรเรียกโดยตรง; ให้ใช้ smart pointers หรือ ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ลดและคืนค่าตัวนับอ้างอิงที่แชร์. ไม่ควรเรียกโดยตรง; ให้ใช้ smart pointers หรือ ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | เป็นเสมือนเมธอด C# [Object.ToString()](../../system/object/tostring/). เปิดการแปลงอ็อบเจ็กต์ที่กำหนดเองเป็นสตริง. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ทำหน้าที่เหมือน construct typeof([System.Object](../../system/object/)) ของ C#. |
| void [Unlock](../../system/object/unlock/)() | ทำหน้าที่ปลดล็อกตามคำสั่ง lock() ของ C#. เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | เพิ่มตัวนับอ้างอิงแบบ weak. ไม่ควรเรียกโดยตรง; ให้ใช้ smart pointers หรือ ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ลดตัวนับอ้างอิงแบบ weak. ไม่ควรเรียกโดยตรง; ให้ใช้ smart pointers หรือ ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | ทำลายอ็อบเจ็กต์. คืนค่าทั้งหมดของโครงสร้างข้อมูลภายใน. |

## ชนิดนิยาม

| ชนิดนิยาม | คำอธิบาย |
| --- | --- |
| [GetThumbnailImageAbort](./getthumbnailimageabort/) | คอลแบ็กเพื่อยกเลิกการทำงานของ GetThumbnailImage. |

## ดูเพิ่มเติม

* คลาส [IDisposable](../../system/idisposable/)
* เนมสเปซ [System::Drawing](../)
* ไลบรารี [Aspose.Slides](../../)