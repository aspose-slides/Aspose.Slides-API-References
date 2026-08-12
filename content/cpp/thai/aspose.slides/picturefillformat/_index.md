---
title: PictureFillFormat
second_title: Aspose.Slides สำหรับ API Reference ของ C++
description: แทนสไตล์การเติมรูปภาพ.
type: docs
weight: 4720
url: /th/aspose.slides/picturefillformat/
---
## PictureFillFormat คลาส


Represents a picture fill style.

```cpp
class PictureFillFormat : public Aspose::Slides::PVIObject,
                          public Aspose::Slides::IPictureFillFormat
```

## เมธอด

| Method | คำอธิบาย |
| --- | --- |
| **bool** [CompressImage](./compressimage/)(**bool**, [Export::PicturesCompression](../../aspose.slides.export/picturescompression/)) override | บีบอัดภาพโดยลดขนาดตามขนาดของรูปร่างและความละเอียดที่กำหนด ตัวเลือกเพิ่มเติมคือจะลบพื้นที่ที่ถูกครอปออกด้วย |
| **bool** [CompressImage](./compressimage/)(**bool**, **float**) override | บีบอัดภาพโดยลดขนาดตามขนาดของรูปร่างและความละเอียดที่กำหนด ตัวเลือกเพิ่มเติมคือจะลบพื้นที่ที่ถูกครอปออกด้วย |
| [System::SharedPtr](../../system/sharedptr/)\<[IPPImage](../ippimage/)\> [DeletePictureCroppedAreas](./deletepicturecroppedareas/)() override | ลบพื้นที่ที่ถูกครอปของการเติม [Picture](../picture/). |
| **bool** [Equals](../pviobject/equals/)([System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) override | เปรียบเทียบกับอ็อบเจ็กต์ที่ระบุ. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | เปรียบเทียบอ็อบเจ็กต์โดยใช้แนวคิดของ C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจ็กต์ประเภทอ้างอิงในสไตล์ C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | จำลองการเปรียบเทียบจำนวนทศนิยมสไตล์ C# โดยที่ NaN สองค่าจะถือว่าเท่ากันแม้ว่าตามมาตรฐาน IEC 60559:1989 NaN จะไม่เท่ากับค่าตัวใด ๆ รวมถึง NaN ด้วย |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | จำลองการเปรียบเทียบจำนวนทศนิยมสไตล์ C# โดยที่ NaN สองค่าจะถือว่าเท่ากันแม้ว่าตามมาตรฐาน IEC 60559:1989 NaN จะไม่เท่ากับค่าตัวใด ๆ รวมถึง NaN ด้วย |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | เพื่อการใช้งานภายในเท่านั้น. |
| **float** [get_CropBottom](./get_cropbottom/)() override | ส่งคืนจำนวนเปอร์เซ็นต์ของความสูงภาพจริงที่ถูกครอบออกจากด้านล่างของรูปภาพ อ่าน **float**. |
| **float** [get_CropLeft](./get_cropleft/)() override | ส่งคืนจำนวนเปอร์เซ็นต์ของความกว้างภาพจริงที่ถูกครอบออกจากด้านซ้ายของรูปภาพ อ่าน **float**. |
| **float** [get_CropRight](./get_cropright/)() override | ส่งคืนจำนวนเปอร์เซ็นต์ของความกว้างภาพจริงที่ถูกครอบออกจากด้านขวาของรูปภาพ อ่าน **float**. |
| **float** [get_CropTop](./get_croptop/)() override | ส่งคืนจำนวนเปอร์เซ็นต์ของความสูงภาพจริงที่ถูกครอบออกจากด้านบนของรูปภาพ อ่าน **float**. |
| **int32_t** [get_Dpi](./get_dpi/)() override | ส่งคืนค่า dpi ที่ใช้ในการเติมรูปภาพ อ่าน **int32_t**. |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IDOMObject](../idomobject/)\> [get_Parent_Immediate](../idomobject/get_parent_immediate/)() | ส่งคืนอ็อบเจ็กต์ Parent_Immediate. อ่านอย่างเดียว [IDOMObject](../idomobject/). |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IPresentationComponent](../ipresentationcomponent/)\> [get_Parent_IPresentationComponent](../ipviobject/get_parent_ipresentationcomponent/)() | ส่งคืนพาเรนท์ [IPresentationComponent](../ipresentationcomponent/). อ่านอย่างเดียว [IPresentationComponent](../ipresentationcomponent/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ISlidesPicture](../islidespicture/)\> [get_Picture](./get_picture/)() override | ส่งคืนรูปภาพ. อ่านอย่างเดียว [ISlidesPicture](../islidespicture/). |
| [Aspose::Slides::PictureFillMode](../picturefillmode/) [get_PictureFillMode](./get_picturefillmode/)() override | ส่งคืนโหมดการเติมรูปภาพ. อ่าน [Slides::PictureFillMode](../picturefillmode/). |
| **float** [get_StretchOffsetBottom](./get_stretchoffsetbottom/)() override | ส่งคืนขอบด้านล่างของสี่เหลี่ยมเติมที่กำหนดโดยออฟเซ็ตเปอร์เซ็นต์จากขอบล่างของกรอบล้อมรูปร่าง ค่าร้อยละบวกระบุการฝังเข้า ส่วนค่าร้อยละลบระบุการขยายออก อ่าน **float**. |
| **float** [get_StretchOffsetLeft](./get_stretchoffsetleft/)() override | ส่งคืนขอบด้านซ้ายของสี่เหลี่ยมเติมที่กำหนดโดยออฟเซ็ตเปอร์เซ็นต์จากขอบซ้ายของกรอบล้อมรูปร่าง ค่าร้อยละบวกระบุการฝังเข้า ส่วนค่าร้อยละลบระบุการขยายออก อ่าน **float**. |
| **float** [get_StretchOffsetRight](./get_stretchoffsetright/)() override | ส่งคืนขอบด้านขวาของสี่เหลี่ยมเติมที่กำหนดโดยออฟเซ็ตเปอร์เซ็นต์จากขอบขวาของกรอบล้อมรูปร่าง ค่าร้อยละบวกระบุการฝังเข้า ส่วนค่าร้อยละลบระบุการขยายออก อ่าน **float**. |
| **float** [get_StretchOffsetTop](./get_stretchoffsettop/)() override | ส่งคืนขอบด้านบนของสี่เหลี่ยมเติมที่กำหนดโดยออฟเซ็ตเปอร์เซ็นต์จากขอบบนของกรอบล้อมรูปร่าง ค่าร้อยละบวกระบุการฝังเข้า ส่วนค่าร้อยละลบระบุการขยายออก อ่าน **float**. |
| [RectangleAlignment](../rectanglealignment/) [get_TileAlignment](./get_tilealignment/)() override | ส่งคืนวิธีการจัดตำแหน่งเทกเจอร์ภายในรูปร่าง การตั้งค่านี้ควบคุมจุดเริ่มต้นของลวดลายเทกเจอร์และการทำซ้ำของมันทั่วรูปร่าง อ่าน [RectangleAlignment](../rectanglealignment/). |
| [Aspose::Slides::TileFlip](../tileflip/) [get_TileFlip](./get_tileflip/)() override | พลิกแผ่นเทกเจอร์ตามแนวแกนแนวนอน แนวตั้ง หรือทั้งสองแกน อ่าน [Slides::TileFlip](../tileflip/). |
| **float** [get_TileOffsetX](./get_tileoffsetx/)() override | ส่งคืนออฟเซ็ตแนวนอนของเทกเจอร์จากต้นจุดของรูปร่างเป็นหน่วยจุด ค่าบวกจะย้ายเทกเจอร์ไปทางขวา ค่าลบจะย้ายไปทางซ้าย อ่าน **float**. |
| **float** [get_TileOffsetY](./get_tileoffsety/)() override | ส่งคืนออฟเซ็ตแนวตั้งของเทกเจอร์จากต้นจุดของรูปร่างเป็นหน่วยจุด ค่าบวกจะย้ายเทกเจอร์ลงด้านล่าง ค่าลบจะย้ายขึ้นด้านบน อ่าน **float**. |
| **float** [get_TileScaleX](./get_tilescalex/)() override | ส่งคืนสเกลแนวนอนสำหรับการเติมเทกเจอร์เป็นเปอร์เซ็นต์ อ่าน **float**. |
| **float** [get_TileScaleY](./get_tilescaley/)() override | ส่งคืนสเกลแนวตั้งสำหรับการเติมเทกเจอร์เป็นเปอร์เซ็นต์ อ่าน **float**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | รับโครงสร้างข้อมูลตัวนับอ้างอิงที่เชื่อมโยงกับอ็อบเจ็กต์. |
| **int32_t** [GetHashCode](../pviobject/gethashcode/)() const override | ส่งคืนค่าแฮชโค้ด. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | รับประเภทจริงของอ็อบเจ็กต์ เป็นการเทียบเคียงกับการเรียกของ C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | ตรวจสอบว่าอ็อบเจ็กต์เป็นอินสแตนซ์ของประเภทที่อธิบายโดย targetType หรือไม่ เป็นการเทียบเคียงกับตัวดำเนินการ 'is' ของ C#. |
| void [Lock](../../system/object/lock/)() | ทำหน้าที่ล็อกตามคำสั่ง lock() ของ C#. เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | เป็นการเทียบเคียงกับเมธอด [Object.MemberwiseClone()](../../system/object/memberwiseclone/) ของ C# ทำให้สามารถคล cloned ประเภทที่กำหนดเองได้. |
|  [Object](../../system/object/object/)() | สร้างอ็อบเจ็กต์ เริ่มต้นโครงสร้างข้อมูลภายในทั้งหมด. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | คอนสตรักเตอร์คัดลอก ไม่ได้คัดลอกอะไรจริง ๆ เพียงแค่เริ่มต้นอ็อบเจ็กต์ใหม่และเปิดใช้งานการคัดลอกสร้างซับคลาส. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | โอเปอเรเตอร์กำหนดค่า ไม่ได้คัดลอกอะไรจริง ๆ เพียงแค่เริ่มต้นอ็อบเจ็กต์ใหม่และเปิดใช้งานการคัดลอกสร้างซับคลาส. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | เปรียบเทียบอ็อบเจ็กต์โดยอ้างอิง. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | เปรียบเทียบอ็อบเจ็กต์โดยอ้างอิง. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | เปรียบเทียบอ็อบเจ็กต์ชนิดค่าโดยอ้างอิงกับ nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | การพิเศษของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีสตริงและ nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | การพิเศษของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีสตริง. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | ลดจำนวนตัวนับอ้างอิงร่วมตามค่าที่ระบุ. |
| void [set_CropBottom](./set_cropbottom/)(**float**) override | ตั้งค่าจำนวนเปอร์เซ็นต์ของความสูงภาพจริงที่ครอบออกจากด้านล่างของรูปภาพ เขียน **float**. |
| void [set_CropLeft](./set_cropleft/)(**float**) override | ตั้งค่าจำนวนเปอร์เซ็นต์ของความกว้างภาพจริงที่ครอบออกจากด้านซ้ายของรูปภาพ เขียน **float**. |
| void [set_CropRight](./set_cropright/)(**float**) override | ตั้งค่าจำนวนเปอร์เซ็นต์ของความกว้างภาพจริงที่ครอบออกจากด้านขวาของรูปภาพ เขียน **float**. |
| void [set_CropTop](./set_croptop/)(**float**) override | ตั้งค่าจำนวนเปอร์เซ็นต์ของความสูงภาพจริงที่ครอบออกจากด้านบนของรูปภาพ เขียน **float**. |
| void [set_Dpi](./set_dpi/)(**int32_t**) override | ตั้งค่าค่า dpi ที่ใช้ในการเติมรูปภาพ เขียน **int32_t**. |
| void [set_PictureFillMode](./set_picturefillmode/)([Aspose::Slides::PictureFillMode](../picturefillmode/)) override | ตั้งค่าโหมดการเติมรูปภาพ เขียน [Slides::PictureFillMode](../picturefillmode/). |
| void [set_StretchOffsetBottom](./set_stretchoffsetbottom/)(**float**) override | ตั้งค่าขอบด้านล่างของสี่เหลี่ยมเติมที่กำหนดโดยออฟเซ็ตเปอร์เซ็นต์จากขอบล่างของกรอบล้อมรูปร่าง ค่าบวกระบุการฝังเข้า ค่าลบระบุการขยายออก เขียน **float**. |
| void [set_StretchOffsetLeft](./set_stretchoffsetleft/)(**float**) override | ตั้งค่าขอบด้านซ้ายของสี่เหลี่ยมเติมที่กำหนดโดยออฟเซ็ตเปอร์เซ็นต์จากขอบซ้ายของกรอบล้อมรูปร่าง ค่าบวกระบุการฝังเข้า ค่าลบระบุการขยายออก เขียน **float**. |
| void [set_StretchOffsetRight](./set_stretchoffsetright/)(**float**) override | ตั้งค่าขอบด้านขวาของสี่เหลี่ยมเติมที่กำหนดโดยออฟเซ็ตเปอร์เซ็นต์จากขอบขวาของกรอบล้อมรูปร่าง ค่าบวกระบุการฝังเข้า ค่าลบระบุการขยายออก เขียน **float**. |
| void [set_StretchOffsetTop](./set_stretchoffsettop/)(**float**) override | ตั้งค่าขอบด้านบนของสี่เหลี่ยมเติมที่กำหนดโดยออฟเซ็ตเปอร์เซ็นต์จากขอบบนของกรอบล้อมรูปร่าง ค่าบวกระบุการฝังเข้า ค่าลบระบุการขยายออก เขียน **float**. |
| void [set_TileAlignment](./set_tilealignment/)([RectangleAlignment](../rectanglealignment/)) override | ตั้งค่าการจัดตำแหน่งเทกเจอร์ภายในรูปร่าง การตั้งค่านี้ควบคุมจุดเริ่มต้นของลวดลายเทกเจอร์และการทำซ้ำของมันทั่วรูปร่าง เขียน [RectangleAlignment](../rectanglealignment/). |
| void [set_TileFlip](./set_tileflip/)([Aspose::Slides::TileFlip](../tileflip/)) override | พลิกแผ่นเทกเจอร์ตามแนวแกนแนวนอน แนวตั้ง หรือทั้งสองแกน เขียน [Slides::TileFlip](../tileflip/). |
| void [set_TileOffsetX](./set_tileoffsetx/)(**float**) override | ตั้งค่าออฟเซ็ตแนวนอนของเทกเจอร์จากต้นจุดของรูปร่างเป็นหน่วยจุด ค่าบวกจะย้ายเทกเจอร์ไปทางขวา ค่าลบจะย้ายไปทางซ้าย เขียน **float**. |
| void [set_TileOffsetY](./set_tileoffsety/)(**float**) override | ตั้งค่าออฟเซ็ตแนวตั้งของเทกเจอร์จากต้นจุดของรูปร่างเป็นหน่วยจุด ค่าบวกจะย้ายเทกเจอร์ลงด้านล่าง ค่าลบจะย้ายขึ้นด้านบน เขียน **float**. |
| void [set_TileScaleX](./set_tilescalex/)(**float**) override | ตั้งค่าสเกลแนวนอนสำหรับการเติมเทกเจอร์เป็นเปอร์เซ็นต์ เขียน **float**. |
| void [set_TileScaleY](./set_tilescaley/)(**float**) override | ตั้งค่าสเกลแนวตั้งสำหรับการเติมเทกเจอร์เป็นเปอร์เซ็นต์ เขียน **float**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | ตั้งค่าอาร์กิวเมนต์เทมเพลตที่ n เป็น weak pointer (แทนที่ shared) อนุญาตให้สลับพอยน์เตอร์ในคอนเทนเนอร์เป็นโหมด weak. |
| int [SharedCount](../../system/object/sharedcount/)() const | รับค่าปัจจุบันของตัวนับอ้างอิงร่วม. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | เพิ่มตัวนับอ้างอิงร่วม ควรไม่เรียกโดยตรง; แทนนั้นใช้ smart pointers หรือ ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ลดตัวนับอ้างอิงร่วมและส่งคืนค่า ควรไม่เรียกโดยตรง; แทนนั้นใช้ smart pointers หรือ ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | เป็นการเทียบเคียงกับเมธอด [Object.ToString()](../../system/object/tostring/) ของ C# ทำให้สามารถแปลงอ็อบเจ็กต์ที่กำหนดเองเป็นสตริงได้. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ทำหน้าที่เป็นโครงสร้าง typeof([System.Object](../../system/object/)) ของ C#. |
| void [Unlock](../../system/object/unlock/)() | ทำหน้าที่ปลดล็อกตามคำสั่ง lock() ของ C#. เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | เพิ่มตัวนับอ้างอิงแบบ weak ควรไม่เรียกโดยตรง; แทนนั้นใช้ smart pointers หรือ ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ลดตัวนับอ้างอิงแบบ weak ควรไม่เรียกโดยตรง; แทนนั้นใช้ smart pointers หรือ ThisProtector. |
| ASPOSE_SLIDES_LOCAL_API void [WrapperLazyInitialization](../pviobject/wrapperlazyinitialization/)() const |  |
| virtual  [~Object](../../system/object/~object/)() | ทำลายอ็อบเจ็กต์ ปล่อยโครงสร้างข้อมูลภายในทั้งหมด. |
## ดูเพิ่มเติม

* คลาส [PVIObject](../pviobject/)
* คลาส [IPictureFillFormat](../ipicturefillformat/)
* เนมสเปซ [Aspose::Slides](../)
* ไลบรารี [Aspose.Slides](../../)