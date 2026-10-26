---
title: IPictureFillFormat
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: เป็นตัวแทนของสไตล์การเติมรูปภาพ.
type: docs
weight: 3225
url: /th/aspose.slides/ipicturefillformat/
---
## IPictureFillFormat คลาส

เป็นตัวแทนของสไตล์การเติมรูปภาพ.

```cpp
class IPictureFillFormat : public Aspose::Slides::IFillParamSource
```

## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| virtual **bool** [CompressImage](./compressimage/)(**bool**, [Export::PicturesCompression](../../aspose.slides.export/picturescompression/)) | บีบอัดภาพโดยลดขนาดตามขนาดของรูปร่างและความละเอียดที่ระบุ หากต้องการ ยังสามารถลบพื้นที่ที่ถูกครอบได้ |
| virtual **bool** [CompressImage](./compressimage/)(**bool**, **float**) | บีบอัดภาพโดยลดขนาดตามขนาดของรูปร่างและความละเอียดที่ระบุ หากต้องการ ยังสามารถลบพื้นที่ที่ถูกครอบได้ |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPPImage](../ippimage/)\> [DeletePictureCroppedAreas](./deletepicturecroppedareas/)() | ลบพื้นที่ที่ถูกครอบของการเติม [Picture](../picture/) |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | เปรียบเทียบวัตถุโดยใช้หลักการของ C# [Object.Equals](../../system/object/equals/) |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบวัตถุประเภทอ้างอิงในรูปแบบ C# |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบวัตถุประเภทค่าในรูปแบบ C# |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | จำลองการเปรียบเทียบจำนวนทศนิยมแบบ C# โดยที่ NaN สองค่าถือว่าเท่ากัน แม้ตาม IEC 60559:1989 NaN จะไม่เท่ากับค่าใด ๆ รวมถึง NaN ด้วย |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | จำลองการเปรียบเทียบจำนวนทศนิยมแบบ C# โดยที่ NaN สองค่าถือว่าเท่ากัน แม้ตาม IEC 60559:1989 NaN จะไม่เท่ากับค่าใด ๆ รวมถึง NaN ด้วย |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | ใช้เพื่อวัตถุประสงค์ภายในเท่านั้น |
| virtual **float** [get_CropBottom](./get_cropbottom/)() | คืนค่าจำนวนเปอร์เซ็นต์ของความสูงภาพจริงที่ถูกตัดออกจากด้านล่างของรูปภาพ อ่าน **float** |
| virtual **float** [get_CropLeft](./get_cropleft/)() | คืนค่าจำนวนเปอร์เซ็นต์ของความกว้างภาพจริงที่ถูกตัดออกจากด้านซ้ายของรูปภาพ อ่าน **float** |
| virtual **float** [get_CropRight](./get_cropright/)() | คืนค่าจำนวนเปอร์เซ็นต์ของความกว้างภาพจริงที่ถูกตัดออกจากด้านขวาของรูปภาพ อ่าน **float** |
| virtual **float** [get_CropTop](./get_croptop/)() | คืนค่าจำนวนเปอร์เซ็นต์ของความสูงภาพจริงที่ถูกตัดออกจากด้านบนของรูปภาพ อ่าน **float** |
| virtual **int32_t** [get_Dpi](./get_dpi/)() | คืนค่า dpi ที่ใช้ในการเติมรูปภาพ อ่าน **int32_t** |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ISlidesPicture](../islidespicture/)\> [get_Picture](./get_picture/)() | คืนค่ารูปภาพ อ่านอย่างเดียว [ISlidesPicture](../islidespicture/) |
| virtual [Aspose::Slides::PictureFillMode](../picturefillmode/) [get_PictureFillMode](./get_picturefillmode/)() | คืนค่าโหมดการเติมรูปภาพ อ่าน [Slides::PictureFillMode](../picturefillmode/) |
| virtual **float** [get_StretchOffsetBottom](./get_stretchoffsetbottom/)() | คืนค่าขอบด้านล่างของสี่เหลี่ยมเติมที่กำหนดโดยการเลื่อนเปอร์เซ็นต์จากขอบด้านล่างของกล่องขอบเขตของรูปร่าง ค่าเปอร์เซ็นต์บวกหมายถึงการเข้าไปภายใน ส่วนค่าเปอร์เซ็นต์ลบหมายถึงการขยายออกไป อ่าน **float** |
| virtual **float** [get_StretchOffsetLeft](./get_stretchoffsetleft/)() | คืนค่าขอบด้านซ้ายของสี่เหลี่ยมเติมที่กำหนดโดยการเลื่อนเปอร์เซ็นต์จากขอบด้านซ้ายของกล่องขอบเขตของรูปร่าง ค่าเปอร์เซ็นต์บวกหมายถึงการเข้าไปภายใน ส่วนค่าเปอร์เซ็นต์ลบหมายถึงการขยายออกไป อ่าน **float** |
| virtual **float** [get_StretchOffsetRight](./get_stretchoffsetright/)() | คืนค่าขอบด้านขวาของสี่เหลี่ยมเติมที่กำหนดโดยการเลื่อนเปอร์เซ็นต์จากขอบด้านขวาของกล่องขอบเขตของรูปร่าง ค่าเปอร์เซ็นต์บวกหมายถึงการเข้าไปภายใน ส่วนค่าเปอร์เซ็นต์ลบหมายถึงการขยายออกไป อ่าน **float** |
| virtual **float** [get_StretchOffsetTop](./get_stretchoffsettop/)() | เครดิตค่าขอบด้านบนของสี่เหลี่ยมเติมที่กำหนดโดยการเลื่อนเปอร์เซ็นต์จากขอบด้านบนของกล่องขอบเขตของรูปร่าง ค่าเปอร์เซ็นต์บวกหมายถึงการเข้าไปภายใน ส่วนค่าเปอร์เซ็นต์ลบหมายถึงการขยายออกไป อ่าน **float** |
| virtual [RectangleAlignment](../rectanglealignment/) [get_TileAlignment](./get_tilealignment/)() | คืนค่าการจัดแนวเทกเจอร์ภายในรูปร่าง การตั้งค่านี้ควบคุมจุดเริ่มต้นของลายเทกเจอร์และวิธีการทำซ้ำทั่วรูปร่าง อ่าน [RectangleAlignment](../rectanglealignment/) |
| virtual [Aspose::Slides::TileFlip](../tileflip/) [get_TileFlip](./get_tileflip/)() | พลิกแผ่นเทกเจอร์ตามแนวนอน แนวตั้ง หรือทั้งสองแกน อ่าน [Slides::TileFlip](../tileflip/) |
| virtual **float** [get_TileOffsetX](./get_tileoffsetx/)() | คืนค่าการเลื่อนแนวนอนของเทกเจอร์จากจุดกำเนิดของรูปร่างเป็นหน่วยจุด ค่าเป็นบวกจะเลื่อนเทกเจอร์ไปทางขวา ค่าเป็นลบจะเลื่อนไปทางซ้าย อ่าน **float** |
| virtual **float** [get_TileOffsetY](./get_tileoffsety/)() | คืนค่าการเลื่อนแนวตั้งของเทกเจอร์จากจุดกำเนิดของรูปร่างเป็นหน่วยจุด ค่าเป็นบวกจะเลื่อนเทกเจอร์ลงด้านล่าง ค่าเป็นลบจะเลื่อนขึ้นด้านบน อ่าน **float** |
| virtual **float** [get_TileScaleX](./get_tilescalex/)() | คืนค่าการสเกลแนวนอนของการเติมเทกเจอร์เป็นเปอร์เซ็นต์ อ่าน **float** |
| virtual **float** [get_TileScaleY](./get_tilescaley/)() | คืนค่าการสเกลแนวตั้งของการเติมเทกเจอร์เป็นเปอร์เซ็นต์ อ่าน **float** |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | รับโครงสร้างข้อมูลตัวนับอ้างอิงที่เชื่อมโยงกับอ็อบเจ็กต์ |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | เป็นฟังก์ชันเทียบเคียงของ C# [Object.GetHashCode()](../../system/object/gethashcode/) เปิดใช้งานการแฮชอ็อบเจ็กต์แบบกำหนดเอง |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | รับประเภทจริงของอ็อบเจ็กต์ เป็นฟังก์ชันเทียบเคียงของการเรียก C# [System.Object.GetType()](../../system/object/gettype/) |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | ตรวจสอบว่าอ็อบเจ็กต์เป็นอินสแตนซ์ของประเภทที่อธิบายโดย targetType เทียบเคียงกับตัวดำเนินการ 'is' ของ C# |
| void [Lock](../../system/object/lock/)() | ดำเนินการล็อกตามคำสั่ง lock() ของ C# เรียกโดยตรงหรือใช้วัตถุเฝ้าระวัง [LockContext](../../system/lockcontext/) |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | เป็นฟังก์ชันเทียบเคียงของ C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) เปิดใช้งานการโคลนนิ่งประเภทที่กำหนดเอง |
|  [Object](../../system/object/object/)() | สร้างอ็อบเจ็กต์ เริ่มต้นโครงสร้างข้อมูลภายในทั้งหมด |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | คอนสตรัคเตอร์คัดลอก ไม่ได้คัดลอกอะไรจริง ๆ เพียงเริ่มต้นอ็อบเจ็กต์ใหม่และเปิดใช้งานการคัดลอกสร้างซับคลาส |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | ตัวดำเนินการกำหนดค่า ไม่ได้คัดลอกอะไรจริง ๆ เพียงเริ่มต้นอ็อบเจ็กต์ใหม่และเปิดใช้งานการคัดลอกสร้างซับคลาส |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | เปรียบเทียบอ็อบเจ็กต์โดยอ้างอิง |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | เปรียบเทียบอ็อบเจ็กต์โดยอ้างอิง |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | เปรียบเทียบอ้างอิงกับอ็อบเจ็กต์ประเภทค่าโดยใช้ nullptr |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | การเจาะจงของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริงและ nullptr |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | การเจาะจงของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริงหลายค่า |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | ลดตัวนับอ้างอิงร่วมโดยค่าที่ระบุ |
| virtual void [set_CropBottom](./set_cropbottom/)(**float**) | กำหนดจำนวนเปอร์เซ็นต์ของความสูงภาพจริงที่ถูกตัดออกจากด้านล่างของรูปภาพ เขียน **float** |
| virtual void [set_CropLeft](./set_cropleft/)(**float**) | กำหนดจำนวนเปอร์เซ็นต์ของความกว้างภาพจริงที่ถูกตัดออกจากด้านซ้ายของรูปภาพ เขียน **float** |
| virtual void [set_CropRight](./set_cropright/)(**float**) | กำหนดจำนวนเปอร์เซ็นต์ของความกว้างภาพจริงที่ถูกตัดออกจากด้านขวาของรูปภาพ เขียน **float** |
| virtual void [set_CropTop](./set_croptop/)(**float**) | กำหนดจำนวนเปอร์เซ็นต์ของความสูงภาพจริงที่ถูกตัดออกจากด้านบนของรูปภาพ เขียน **float** |
| virtual void [set_Dpi](./set_dpi/)(**int32_t**) | กำหนดค่า dpi ที่ใช้เพื่อเติมรูปภาพ เขียน **int32_t** |
| virtual void [set_PictureFillMode](./set_picturefillmode/)([Aspose::Slides::PictureFillMode](../picturefillmode/)) | กำหนดโหมดการเติมรูปภาพ เขียน [Slides::PictureFillMode](../picturefillmode/) |
| virtual void [set_StretchOffsetBottom](./set_stretchoffsetbottom/)(**float**) | กำหนดขอบด้านล่างของสี่เหลี่ยมเติมที่กำหนดโดยการเลื่อนเปอร์เซ็นต์จากขอบด้านล่างของกล่องขอบเขตของรูปร่าง ค่าเปอร์เซ็นต์บวกหมายถึงการเข้าไปภายใน ส่วนค่าเปอร์เซ็นต์ลบหมายถึงการขยายออกไป เขียน **float** |
| virtual void [set_StretchOffsetLeft](./set_stretchoffsetleft/)(**float**) | กำหนดขอบด้านซ้ายของสี่เหลี่ยมเติมที่กำหนดโดยการเลื่อนเปอร์เซ็นต์จากขอบด้านซ้ายของกล่องขอบเขตของรูปร่าง ค่าเปอร์เซ็นต์บวกหมายถึงการเข้าไปภายใน ส่วนค่าเปอร์เซ็นต์ลบหมายถึงการขยายออกไป เขียน **float** |
| virtual void [set_StretchOffsetRight](./set_stretchoffsetright/)(**float**) | กำหนดขอบด้านขวาของสี่เหลี่ยมเติมที่กำหนดโดยการเลื่อนเปอร์เซ็นต์จากขอบด้านขวาของกล่องขอบเขตของรูปร่าง ค่าเปอร์เซ็นต์บวกหมายถึงการเข้าไปภายใน ส่วนค่าเปอร์เซ็นต์ลบหมายถึงการขยายออกไป เขียน **float** |
| virtual void [set_StretchOffsetTop](./set_stretchoffsettop/)(**float**) | กำหนดขอบด้านบนของสี่เหลี่ยมเติมที่กำหนดโดยการเลื่อนเปอร์เซ็นต์จากขอบด้านบนของกล่องขอบเขตของรูปร่าง ค่าเปอร์เซ็นต์บวกหมายถึงการเข้าไปภายใน ส่วนค่าเปอร์เซ็นต์ลบหมายถึงการขยายออกไป เขียน **float** |
| virtual void [set_TileAlignment](./set_tilealignment/)([RectangleAlignment](../rectanglealignment/)) | กำหนดการจัดแนวเทกเจอร์ภายในรูปร่าง การตั้งค่านี้ควบคุมจุดเริ่มต้นของลายเทกเจอร์และวิธีการทำซ้ำทั่วรูปร่าง เขียน [RectangleAlignment](../rectanglealignment/) |
| virtual void [set_TileFlip](./set_tileflip/)([Aspose::Slides::TileFlip](../tileflip/)) | พลิกแผ่นเทกเจอร์ตามแนวนอน แนวตั้ง หรือทั้งสองแกน เขียน [Slides::TileFlip](../tileflip/) |
| virtual void [set_TileOffsetX](./set_tileoffsetx/)(**float**) | กำหนดการเลื่อนแนวนอนของเทกเจอร์จากจุดกำเนิดของรูปร่างเป็นหน่วยจุด ค่าเป็นบวกจะเลื่อนเทกเจอร์ไปทางขวา ค่าเป็นลบจะเลื่อนไปทางซ้าย เขียน **float** |
| virtual void [set_TileOffsetY](./set_tileoffsety/)(**float**) | กำหนดการเลื่อนแนวตั้งของเทกเจอร์จากจุดกำเนิดของรูปร่างเป็นหน่วยจุด ค่าเป็นบวกจะเลื่อนเทกเจอร์ลงด้านล่าง ค่าเป็นลบจะเลื่อนขึ้นด้านบน เขียน **float** |
| virtual void [set_TileScaleX](./set_tilescalex/)(**float**) | กำหนดสเกลแนวนอนของการเติมเทกเจอร์เป็นเปอร์เซ็นต์ เขียน **float** |
| virtual void [set_TileScaleY](./set_tilescaley/)(**float**) | กำหนดสเกลแนวตั้งของการเติมเทกเจอร์เป็นเปอร์เซ็นต์ เขียน **float** |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | ตั้งค่าอาร์กิวเมนต์เทมเพลตที่ n เป็น weak pointer (แทนการใช้ shared) สามารถสลับ pointer ใน container ให้เป็นโหมด weak |
| int [SharedCount](../../system/object/sharedcount/)() const | รับค่าปัจจุบันของตัวนับอ้างอิงร่วม |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | เพิ่มจำนวนตัวนับอ้างอิงร่วม ไม่ควรเรียกโดยตรง; ใช้ smart pointer หรือ ThisProtector แทน |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ลดและคืนค่าตัวนับอ้างอิงร่วม ไม่ควรเรียกโดยตรง; ใช้ smart pointer หรือ ThisProtector แทน |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | เป็นฟังก์ชันเทียบเคียงของ C# [Object.ToString()](../../system/object/tostring/) เปิดใช้งานการแปลงอ็อบเจ็กต์แบบกำหนดเองเป็นสตริง |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ทำตามโครงสร้าง typeof([System.Object](../../system/object/)) ของ C# |
| void [Unlock](../../system/object/unlock/)() | ดำเนินการปลดล็อกตามคำสั่ง lock() ของ C# เรียกโดยตรงหรือใช้วัตถุเฝ้าระวัง [LockContext](../../system/lockcontext/) |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | เพิ่มจำนวนตัวนับอ้างอิง weak ไม่ควรเรียกโดยตรง; ใช้ smart pointer หรือ ThisProtector แทน |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ลดจำนวนตัวนับอ้างอิง weak ไม่ควรเรียกโดยตรง; ใช้ smart pointer หรือ ThisProtector แทน |
| virtual  [~Object](../../system/object/~object/)() | ทำลายอ็อบเจ็กต์ ปลดปล่อยโครงสร้างข้อมูลภายในทั้งหมด |

## ดูเพิ่มเติม

* คลาส [IFillParamSource](../ifillparamsource/)
* เนมสเปซ [Aspose::Slides](../)
* ไลบรารี [Aspose.Slides](../../)