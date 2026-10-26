---
title: Bitmap
second_title: Aspose.Slides สำหรับ API ของ C++
description: "แทนภาพบิทแมพ GDI+ การสร้างอ็อบเจ็กต์ของคลาสนี้ควรทำเฉพาะโดยใช้ฟังก์ชัน System::MakeObject() เท่านั้น. อย่าสร้างอินสแตนซ์ของประเภทนี้บนสแตกหรือโดยใช้ operator new เนื่องจากจะทำให้เกิดข้อผิดพลาดขณะรันไทม์และ/หรือการตรวจสอบข้อผิดพลาด. ควรห่อหุ้มคลาสนี้ด้วยพอยน์เตอร์ System::SmartPtr และใช้พอยน์เตอร์นี้เพื่อส่งเป็นอาร์กิวเมนท์ให้กับฟังก์ชัน."
type: docs
weight: 1
url: /th/system.drawing/bitmap/
---
## คลาส Bitmap

แสดงถึงภาพบิทแมพ GDI+ ตัววัตถุของคลาสนี้ควรจะจัดสรรด้วยฟังก์ชัน [System::MakeObject()](../../system/makeobject/) เท่านั้น. อย่าสร้างอินสแตนซ์ของประเภทนี้บนสแตกหรือโดยใช้ operator new เนื่องจากจะทำให้เกิดข้อผิดพลาดระหว่างทำงานและ/หรือการตรวจสอบข้อผิดพลาด. ควรห่อหุ้มคลาสนี้ด้วยพอยน์เตอร์ [System::SmartPtr](../../system/smartptr/) และใช้พอยน์เตอร์นี้เพื่อส่งเป็นอาร์กิวเมนท์ให้กับฟังก์ชัน.

```cpp
class Bitmap : public System::Drawing::Image
```

## เมธอด

| Method | Description |
| --- | --- |
| **bool** [BeginPixelProcessing](./beginpixelprocessing/)(**bool**) | เปิดใช้งานโหมดการประมวลผลพิกเซล |
| [Bitmap](./bitmap/)(const [SharedPtr](../../system/sharedptr/)\<[Image](../image/)\>\&) | สร้างอ็อบเจ็กต์ [Bitmap](./) ใหม่จากภาพที่มีอยู่ที่ระบุ |
| [Bitmap](./bitmap/)(const [SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>\&, **bool**) | สร้างอ็อบเจ็กต์ [Bitmap](./) ใหม่จากสตรีมที่ระบุ |
| [Bitmap](./bitmap/)(const [String](../../system/string/)\&) | สร้างอ็อบเจ็กต์ [Bitmap](./) ใหม่จากไฟล์ที่ระบุ |
| [Bitmap](./bitmap/)(const [String](../../system/string/)\&, **bool**) | สร้างอ็อบเจ็กต์ [Bitmap](./) ใหม่จากไฟล์ที่ระบุ |
| [Bitmap](./bitmap/)(int, int, [Imaging::PixelFormat](../../system.drawing.imaging/pixelformat/)) | สร้างอ็อบเจ็กต์ [Bitmap](./) ใหม่ที่แสดงภาพบิทแมพด้วยความกว้าง, ความสูง, รูปแบบพิกเซลและข้อมูลพิกเซลที่ระบุ |
| [Bitmap](./bitmap/)(const [SharedPtr](../../system/sharedptr/)\<[Image](../image/)\>\&, const [Size](../size/)\&) | สร้างอ็อบเจ็กต์ [Bitmap](./) ใหม่จากภาพที่มีอยู่ที่ระบุโดยปรับขนาดเป็นขนาดที่ระบุ |
| [Bitmap](./bitmap/)(const [SharedPtr](../../system/sharedptr/)\<[Image](../image/)\>\&, int, int) | สร้างอ็อบเจ็กต์ [Bitmap](./) ใหม่จากภาพที่มีอยู่ที่ระบุโดยปรับความกว้างและความสูงเป็นค่าที่ระบุ |
| [SharedPtr](../../system/sharedptr/)\<[Image](../image/)\> [Clone](./clone/)() override | สร้างสำเนาของอ็อบเจ็กต์ปัจจุบัน |
| [SharedPtr](../../system/sharedptr/)\<[Bitmap](./)\> [Clone](./clone/)([Rectangle](../rectangle/), [Imaging::PixelFormat](../../system.drawing.imaging/pixelformat/)) | สร้างอ็อบเจ็กต์ [Bitmap](./) ที่เป็นสำเนาของบริเวณของภาพบิทแมพที่อ็อบเจ็กต์ปัจจุบันเป็นตัวแทน |
| [SharedPtr](../../system/sharedptr/)\<[Bitmap](./)\> [Clone](./clone/)([RectangleF](../rectanglef/), [Imaging::PixelFormat](../../system.drawing.imaging/pixelformat/)) | สร้างอ็อบเจ็กต์ [Bitmap](./) ที่เป็นสำเนาของบริเวณของภาพบิทแมพที่อ็อบเจ็กต์ปัจจุบันเป็นตัวแทน |
| [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [ComputeHash](./computehash/)() | คำนวณค่าแฮช SHA1 |
| static [SharedPtr](../../system/sharedptr/)\<[Bitmap](./)\> [ConvertToARGBImage](./converttoargbimage/)(const [SharedPtr](../../system/sharedptr/)\<[Bitmap](./)\>\&) | สร้างสำเนาของภาพบิทแมพที่ระบุโดยเปลี่ยนรูปแบบพิกเซลเป็น Format32bppArgb |
| void [Dispose](../image/dispose/)() override | ปล่อยทรัพยากรทั้งหมดที่อ็อบเจ็กต์ปัจจุบันได้จัดสรร |
| **bool** [EndPixelProcessing](./endpixelprocessing/)(**bool**) | ปิดโหมดการประมวลผลพิกเซล |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | เปรียบเทียบอ็อบเจ็กต์โดยใช้ semantics ของ C# [Object.Equals](../../system/object/equals/) |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจ็กต์ประเภทอ้างอิงในสไตล์ C# |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจ็กต์ประเภทค่าในสไตล์ C# |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | จำลองการเปรียบเทียบจำนวนจริงแบบ C# ที่ NaN สองค่าถูกถือว่าเท่ากันแม้ว่าตาม IEC 60559:1989 NaN ไม่เท่ากับค่าใด ๆ รวมถึง NaN |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | จำลองการเปรียบเทียบจำนวนจริงแบบ C# ที่ NaN สองค่าถูกถือว่าเท่ากันแม้ว่าตาม IEC 60559:1989 NaN ไม่เท่ากับค่าใด ๆ รวมถึง NaN |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | ใช้สำหรับวัตถุประสงค์ภายในเท่านั้น |
| static [SharedPtr](../../system/sharedptr/)\<[Image](../image/)\> [FromFile](../image/fromfile/)(const [String](../../system/string/)\&, **bool**) | สร้างอ็อบเจ็กต์ [Image](../image/) จากไฟล์ที่ระบุ |
| static [SharedPtr](../../system/sharedptr/)\<[Bitmap](./)\> [FromHbitmap](../image/fromhbitmap/)(IntPtr) | สร้างอ็อบเจ็กต์ [Bitmap](./) จาก GDI bitmap ที่ระบุ |
| static [SharedPtr](../../system/sharedptr/)\<[Image](../image/)\> [FromStream](../image/fromstream/)(const [SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>\&, **bool**, **bool**) | สร้างอ็อบเจ็กต์ [Image](../image/) จากสตรีมที่ระบุ |
| virtual **int32_t** [get_Flags](../image/get_flags/)() const | คืนค่าการรวมแบบบิตของค่า enum ImageFlags ที่แสดงคุณลักษณะของภาพ |
| [ArrayPtr](../../system/arrayptr/)\<[Guid](../../system/guid/)\> [get_FrameDimensionsList](../image/get_framedimensionslist/)() const | คืนค่าอาร์เรย์ของ GUID ที่แสดงมิติของเฟรมภายในภาพที่อ็อบเจ็กต์ปัจจุบันเป็นตัวแทน |
| int [get_Height](./get_height/)() const override | คืนค่าความสูงของภาพเป็นพิกเซล |
| **float** [get_HorizontalResolution](../image/get_horizontalresolution/)() const | คืนค่าความละเอียดแนวนอนของภาพที่อ็อบเจ็กต์ปัจจุบันเป็นพิกเซลต่ออินช์ |
| [Imaging::ColorPalettePtr](../../system.drawing.imaging/colorpaletteptr/) [get_Palette](./get_palette/)() const override | คืนค่าพาเล็ตสีที่ใช้โดยภาพที่อ็อบเจ็กต์ปัจจุบันเป็นตัวแทน |
| [Imaging::PixelFormat](../../system.drawing.imaging/pixelformat/) [get_PixelFormat](./get_pixelformat/)() const override | คืนค่ารูปแบบพิกเซลของภาพที่อ็อบเจ็กต์ปัจจุบันเป็นตัวแทน |
| virtual [ArrayPtr](../../system/arrayptr/)\<int\> [get_PropertyIdList](../image/get_propertyidlist/)() const | รับ ID ของรายการคุณสมบัติที่เก็บไว้ในภาพนี้ |
| virtual [ArrayPtr](../../system/arrayptr/)\<[SharedPtr](../../system/sharedptr/)\<[Imaging::PropertyItem](../../system.drawing.imaging/propertyitem/)\>\> [get_PropertyItems](../image/get_propertyitems/)() const | รับรายการคุณสมบัติทั้งหมด (ส่วนของเมตาดาต้า) ที่เก็บไว้ในภาพนี้ |
| [Imaging::ImageFormatPtr](../../system.drawing.imaging/imageformatptr/) [get_RawFormat](./get_rawformat/)() const override | คืนค่ารูปแบบไฟล์ของภาพที่อ็อบเจ็กต์ปัจจุบันเป็นตัวแทน |
| [Size](../size/) [get_Size](../image/get_size/)() const | คืนค่าอ็อบเจ็กต์ [Size](../size/) ที่แสดงความกว้างและความสูงของภาพเป็นพิกเซล |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\> [get_Tag](../image/get_tag/)() const | รับอ็อบเจ็กต์ที่ให้ข้อมูลเพิ่มเติมเกี่ยวกับภาพ |
| **float** [get_VerticalResolution](../image/get_verticalresolution/)() const | คืนค่าความละเอียดแนวตั้งของภาพที่อ็อบเจ็กต์ปัจจุบันเป็นพิกเซลต่ออินช์ |
| int [get_Width](./get_width/)() const override | คืนค่าความกว้างของภาพเป็นพิกเซล |
| [RectangleF](../rectanglef/) [GetBounds](../image/getbounds/)([GraphicsUnit](../graphicsunit/)\&) | คืนค่าขอบเขตของภาพในหน่วยวัดที่ระบุ |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | รับโครงสร้างข้อมูลตัวนับอ้างอิงที่เชื่อมโยงกับอ็อบเจ็กต์ |
| int [GetFrameCount](../image/getframecount/)(const [Imaging::FrameDimensionPtr](../../system.drawing.imaging/framedimensionptr/)\&) | คืนค่าจำนวนเฟรมของมิติเฟรมที่ระบุ |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | เป็นเทียบเท่ากับเมธอด C# [Object.GetHashCode()](../../system/object/gethashcode/). เปิดใช้งานการแฮชอ็อบเจ็กต์ที่กำหนดเอง |
| IntPtr [GetHbitmap](./gethbitmap/)() | สร้างอ็อบเจ็กต์ GDI bitmap จากบิทแมพที่อ็อบเจ็กต์ปัจจุบันเป็นตัวแทน |
| [Color](../color/) [GetPixel](./getpixel/)(int, int) | คืนค่าสีของพิกเซลที่ระบุ |
| static int [GetPixelFormatSize](../image/getpixelformatsize/)([Imaging::PixelFormat](../../system.drawing.imaging/pixelformat/)) | คืนค่าจำนวนบิตที่ใช้ในการแทนความลึกสีในรูปแบบพิกเซลที่ระบุ |
| const SkBitmap * [GetSkBitmap](./getskbitmap/)() const override | คืนพอยน์เตอร์ดิบไปยังอ็อบเจ็กต์ SkBitmap ที่อยู่ด้านล่าง |
| [SharedPtr](../../system/sharedptr/)\<[Image](../image/)\> [GetThumbnailImage](../image/getthumbnailimage/)(int, int, [Image::GetThumbnailImageAbort](../image/getthumbnailimageabort/), IntPtr) | รับภาพย่อสำหรับอ็อบเจ็กต์ [System::Drawing::Image](../image/) นี้ |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | รับประเภทจริงของอ็อบเจ็กต์. เป็นเทียบเท่ากับการเรียก C# [System.Object.GetType()](../../system/object/gettype/) |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | ตรวจสอบว่าอ็อบเจ็กต์เป็นอินสแตนซ์ของประเภทที่อธิบายโดย targetType. เป็นเทียบเท่ากับเครื่องหมาย 'is' ของ C# |
| static **bool** [IsAlphaPixelFormat](../image/isalphapixelformat/)([Imaging::PixelFormat](../../system.drawing.imaging/pixelformat/)) | กำหนดว่ารูปแบบพิกเซลที่ระบุมีข้อมูลอัลฟา |
| **bool** [IsMultiImage](./ismultiimage/)() const override | คืนค่าว่าแบบดั้งเดิมเป็นหลายภาพหรือไม่ |
| void [Lock](../../system/object/lock/)() | ดำเนินการล็อกตามคำสั่ง C# lock(). เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/) |
| [Imaging::BitmapDataPtr](../../system.drawing.imaging/bitmapdataptr/) [LockBits](./lockbits/)(const [Rectangle](../rectangle/)\&, [Imaging::ImageLockMode](../../system.drawing.imaging/imagelockmode/), [Imaging::PixelFormat](../../system.drawing.imaging/pixelformat/)) | ล็อก [Bitmap](./) เข้าไปยังหน่วยความจำของระบบ |
| [Imaging::BitmapDataPtr](../../system.drawing.imaging/bitmapdataptr/) [LockBits](./lockbits/)(const [Rectangle](../rectangle/)\&, [Imaging::ImageLockMode](../../system.drawing.imaging/imagelockmode/), [Imaging::PixelFormat](../../system.drawing.imaging/pixelformat/), const [Imaging::BitmapDataPtr](../../system.drawing.imaging/bitmapdataptr/)\&) | ล็อก [Bitmap](./) เข้าไปยังหน่วยความจำของระบบ |
| void [MakeTransparent](./maketransparent/)([Color](../color/)) | เปลี่ยนสีของพิกเซลทั้งหมดที่มีสีที่ระบุให้เป็นโปร่งใส |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | เป็นเทียบเท่ากับเมธอด C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). เปิดใช้งานการโคลนประเภทที่กำหนดเอง |
| [Object](../../system/object/object/)() | สร้างอ็อบเจ็กต์. เริ่มต้นโครงสร้างข้อมูลภายในทั้งหมด |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | คอนสตรัคเตอร์คัดลอก. จริง ๆ แล้วไม่ได้คัดลอกอะไร, เพียงเริ่มต้นอ็อบเจ็กต์ใหม่และเปิดใช้งานการคัดลอกสร้างซับคลาส |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | โอเปอเรเตอร์การกำหนดค่า. จริง ๆ แล้วไม่ได้คัดลอกอะไร, เพียงเริ่มต้นอ็อบเจ็กต์ใหม่และเปิดใช้งานการคัดลอกสร้างซับคลาส |
| void [PremultipleColors](./premultiplecolors/)() | ทำการพรีมัลติพลายสีของพิกเซลของภาพที่อ็อบเจ็กต์ปัจจุบันเป็นตัวแทน |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | เปรียบเทียบอ็อบเจ็กต์โดยอ้างอิง |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | เปรียบเทียบอ็อบเจ็กต์โดยอ้างอิง |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | เปรียบเทียบอ้างอิงของอ็อบเจ็กต์ประเภทค่า กับ nullptr |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | เฉพาะทางของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณี string และ nullptr |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | เฉพาะทางของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของ strings |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | ลดค่าตัวนับอ้างอิงที่แชร์ลงโดยค่าเฉพาะที่ระบุ |
| void [RotateFlip](./rotateflip/)([RotateFlipType](../rotatefliptype/)) override | หมุนภาพเป็นหลายของ 90 องศาและพลิก |
| void [Save](../image/save/)(const [String](../../system/string/)\&) | บันทึกภาพที่อ็อบเจ็กต์ปัจจุบันเป็นตัวแทนลงไฟล์ที่ระบุในรูปแบบ PNG |
| void [Save](../image/save/)(const [String](../../system/string/)\&, const [Imaging::ImageFormatPtr](../../system.drawing.imaging/imageformatptr/)\&) | บันทึกภาพที่อ็อบเจ็กต์ปัจจุบันเป็นตัวแทนลงไฟล์ที่ระบุในรูปแบบที่ระบุ |
| void [Save](../image/save/)(const [SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>\&, const [Imaging::ImageFormatPtr](../../system.drawing.imaging/imageformatptr/)\&) | บันทึกภาพที่อ็อบเจ็กต์ปัจจุบันเป็นตัวแทนสู่สตรีมที่ระบุในรูปแบบที่ระบุ |
| void [Save](../image/save/)(const [String](../../system/string/)\&, const [Imaging::ImageCodecInfoPtr](../../system.drawing.imaging/imagecodecinfoptr/)\&, const [Imaging::EncoderParametersPtr](../../system.drawing.imaging/encoderparametersptr/)\&) | บันทึกภาพที่อ็อบเจ็กต์ปัจจุบันเป็นตัวแทนลงไฟล์ที่ระบุโดยใช้ encoder และพารามิเตอร์ encoder ที่ระบุ |
| void [Save](../image/save/)(const [SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>\&, const [Imaging::ImageCodecInfoPtr](../../system.drawing.imaging/imagecodecinfoptr/)\&, const [Imaging::EncoderParametersPtr](../../system.drawing.imaging/encoderparametersptr/)\&) | บันทึกภาพที่อ็อบเจ็กต์ปัจจุบันเป็นตัวแทนสู่สตรีมที่ระบุโดยใช้ encoder และพารามิเตอร์ encoder ที่ระบุ |
| void [SaveAdd](../image/saveadd/)(const [Imaging::EncoderParametersPtr](../../system.drawing.imaging/encoderparametersptr/)\&) | เพิ่มเฟรมลงไฟล์หรือสตรีมที่ระบุในการเรียกเมธอด [Save()](../image/save/) ก่อนหน้า |
| void [SaveAdd](../image/saveadd/)(const [SharedPtr](../../system/sharedptr/)\<[Image](../image/)\>\&, const [Imaging::EncoderParametersPtr](../../system.drawing.imaging/encoderparametersptr/)\&) | เพิ่มเฟรมลงไฟล์หรือสตรีมที่ระบุในการเรียกเมธอด [Save()](../image/save/) ก่อนหน้า |
| int [SelectActiveFrame](../image/selectactiveframe/)(const [Imaging::FrameDimensionPtr](../../system.drawing.imaging/framedimensionptr/)\&, int) | เลือกเฟรมที่ระบุ |
| void [set_Palette](./set_palette/)([Imaging::ColorPalettePtr](../../system.drawing.imaging/colorpaletteptr/)) override | ตั้งค่าพาเล็ตสีที่ใช้โดยภาพที่อ็อบเจ็กต์ปัจจุบันเป็นตัวแทน |
| virtual void [set_Tag](../image/set_tag/)(const [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) | ตั้งค่าอ็อบเจ็กต์ที่ให้ข้อมูลเพิ่มเติมเกี่ยวกับภาพ |
| void [SetPixel](./setpixel/)(int, int, [Color](../color/)) | ตั้งค่าสีของพิกเซลที่ระบุในภาพบิทแมพที่อ็อบเจ็กต์ปัจจุบันเป็นตัวแทน |
| void [SetResolution](./setresolution/)(**float**, **float**) | ตั้งค่าความละเอียดของภาพ |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | ตั้งค่าเทมเพลตอาร์กิวเมนต์ที่ n ให้เป็น weak pointer (แทนการแชร์). อนุญาตให้สลับพอยน์เตอร์ในคอนเทนเนอร์เป็นโหมด weak |
| int [SharedCount](../../system/object/sharedcount/)() const | รับค่าปัจจุบันของตัวนับอ้างอิงที่แชร์ |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | เพิ่มตัวนับอ้างอิงที่แชร์. ไม่ควรเรียกโดยตรง; ควรใช้ smart pointers หรือ ThisProtector |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ลดและคืนค่าตัวนับอ้างอิงที่แชร์. ไม่ควรเรียกโดยตรง; ควรใช้ smart pointers หรือ ThisProtector |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | เป็นเทียบเท่ากับเมธอด C# [Object.ToString()](../../system/object/tostring/). เปิดใช้งานการแปลงอ็อบเจ็กต์ที่กำหนดเองเป็นสตริง |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ทำหน้าที่เป็นคอนสตรัคต์ C# typeof([System.Object](../../system/object/)) |
| void [Unlock](../../system/object/unlock/)() | ดำเนินการปลดล็อกตามคำสั่ง C# lock(). เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/) |
| void [UnlockBits](./unlockbits/)(const [Imaging::BitmapDataPtr](../../system.drawing.imaging/bitmapdataptr/)\&) | ปลดล็อกบิทแมพที่ระบุจากหน่วยความจำของระบบ |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | เพิ่มตัวนับอ้างอิงแบบ weak. ไม่ควรเรียกโดยตรง; ควรใช้ smart pointers หรือ ThisProtector |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ลดตัวนับอ้างอิงแบบ weak. ไม่ควรเรียกโดยตรง; ควรใช้ smart pointers หรือ ThisProtector |
| virtual  [~Object](../../system/object/~object/)() | ทำลายอ็อบเจ็กต์. ปล่อยโครงสร้างข้อมูลภายในทั้งหมด |

## ดูเพิ่มเติม

* คลาส [Image](../image/)
* เนมสเปซ [System::Drawing](../)
* ไลบรารี [Aspose.Slides](../../)