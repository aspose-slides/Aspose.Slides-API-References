---
title: IReflection
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: เป็นเอฟเฟกต์การสะท้อน.
type: docs
weight: 937
url: /th/aspose.slides.effects/ireflection/
---
## IReflection คลาส

Represents a reflection effect.

```cpp
class IReflection : public virtual Aspose::Slides::Effects::IImageTransformOperation,
                    public Aspose::Slides::IAccessiblePVIObject<System::SharedPtr<Aspose::Slides::Effects::IReflectionEffectiveData>>
```

## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | เปรียบเทียบวัตถุโดยใช้ลักษณะการทำงานของ C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบวัตถุประเภทอ้างอิงในสไตล์ C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบวัตถุประเภทค่าในสไตล์ C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | จำลองการเปรียบเทียบแบบ float ของ C# ที่ถือว่า NaN สองค่าเท่ากัน แม้ว่าตาม IEC 60559:1989 NaN จะไม่เท่ากับค่าใด ๆ รวมถึง NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | จำลองการเปรียบเทียบแบบ double ของ C# ที่ถือว่า NaN สองค่าเท่ากัน แม้ว่าตาม IEC 60559:1989 NaN จะไม่เท่ากับค่าใด ๆ รวมถึง NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | สำหรับการใช้ภายในเท่านั้น. |
| virtual **double** [get_BlurRadius](./get_blurradius/)() | [Blur](../blur/) รัศมี. อ่าน **double**. |
| virtual **float** [get_Direction](./get_direction/)() | ทิศทางของการสะท้อน. อ่าน **float**. |
| virtual **double** [get_Distance](./get_distance/)() | ระยะการสะท้อน. อ่าน **double**. |
| virtual **float** [get_EndPosAlpha](./get_endposalpha/)() | ระบุตำแหน่งสุดท้าย (ตามระดับความชันกราเดียนต์อัลฟ่า) ของค่าความโปร่งแสงอัลฟ่าสุดท้าย (เปอร์เซนต์). อ่าน **float**. |
| virtual **float** [get_EndReflectionOpacity](./get_endreflectionopacity/)() | ความทึบของการสะท้อนสุดท้าย (เปอร์เซนต์). อ่าน **float**. |
| virtual **float** [get_FadeDirection](./get_fadedirection/)() | ระบุทิศทางสำหรับการชิดการสะท้อน (มุม). อ่าน **float**. |
| virtual [RectangleAlignment](../../aspose.slides/rectanglealignment/) [get_RectangleAlign](./get_rectanglealign/)() | การจัดตำแหน่งสี่เหลี่ยม. อ่าน [RectangleAlignment](../../aspose.slides/rectanglealignment/). |
| virtual **bool** [get_RotateShadowWithShape](./get_rotateshadowwithshape/)() | ระบุว่าการสะท้อนควรหมุนตามรูปร่างเมื่อรูปร่างถูกหมุนหรือไม่. อ่าน **bool**. |
| virtual **double** [get_ScaleHorizontal](./get_scalehorizontal/)() | ระบุปัจจัยการสเกลแนวนอน, การสเกลเชิงลบทำให้พลิกรูป (เปอร์เซ็นต์). อ่าน **double**. |
| virtual **double** [get_ScaleVertical](./get_scalevertical/)() | ระบุปัจจัยการสเกลแนวตั้ง, การสเกลเชิงลบทำให้พลิกรูป (เปอร์เซ็นต์). อ่าน **double**. |
| virtual **double** [get_SkewHorizontal](./get_skewhorizontal/)() | ระบุมุมการบิดแนวนอน. อ่าน **double**. |
| virtual **double** [get_SkewVertical](./get_skewvertical/)() | ระบุมุมการบิดแนวตั้ง. อ่าน **double**. |
| virtual **float** [get_StartPosAlpha](./get_startposalpha/)() | ระบุตำแหน่งเริ่มต้น (ตามระดับความชันกราเดียนต์อัลฟ่า) ของค่าความโปร่งแสงอัลฟ่าเริ่มต้น (เปอร์เซ็นต์). อ่าน **float**. |
| virtual **float** [get_StartReflectionOpacity](./get_startreflectionopacity/)() | ความทึบของการสะท้อนเริ่มต้น (เปอร์เซ็นต์). อ่าน **float**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | รับโครงสร้างข้อมูลตัวนับอ้างอิงที่เชื่อมโยงกับวัตถุ. |
| virtual T [GetEffective](../../aspose.slides/iaccessiblepviobject/geteffective/)() | รับข้อมูลที่มีผลกับการสืบทอดที่นำไปใช้. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | คล้ายเมธอด C# [Object.GetHashCode()](../../system/object/gethashcode/). เปิดใช้งานการแฮชวัตถุที่กำหนดเอง. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | รับประเภทจริงของวัตถุ. คล้ายการเรียก C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | ตรวจสอบว่าวัตถุเป็นอินสแตนซ์ของประเภทที่ระบุโดย targetType หรือไม่. คล้ายตัวดำเนินการ 'is' ของ C#. |
| void [Lock](../../system/object/lock/)() | ใช้การล็อก C# lock() statement. เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | คล้ายเมธอด C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). เปิดใช้งานการทำสำเนาประเภทที่กำหนดเอง. |
|  [Object](../../system/object/object/)() | สร้างวัตถุ. เริ่มต้นโครงสร้างข้อมูลภายในทั้งหมด. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | ตัวสร้างคัดลอก. ไม่ได้คัดลอกอะไรเลย, เพียงเริ่มต้นวัตถุใหม่และเปิดใช้งานการคัดลอกสำหรับซับคลาส. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | ตัวดำเนินการกำหนดค่า. ไม่ได้คัดลอกอะไรเลย, เพียงเริ่มต้นวัตถุใหม่และเปิดใช้งานการคัดลอกสำหรับซับคลาส. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | เปรียบเทียบวัตถุโดยอ้างอิง. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | เปรียบเทียบวัตถุโดยอ้างอิง. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | เปรียบเทียบออบเจ็กต์ประเภทค่าโดยอ้างอิงกับ nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | การพิเศษของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของ string และ nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | การพิเศษของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริง. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | ลดจำนวนการอ้างอิงร่วมโดยค่าที่ระบุ. |
| virtual void [set_BlurRadius](./set_blurradius/)(**double**) | [Blur](../blur/) รัศมี. เขียน **double**. |
| virtual void [set_Direction](./set_direction/)(**float**) | ทิศทางของการสะท้อน. เขียน **float**. |
| virtual void [set_Distance](./set_distance/)(**double**) | ระยะการสะท้อน. เขียน **double**. |
| virtual void [set_EndPosAlpha](./set_endposalpha/)(**float**) | ระบุตำแหน่งสุดท้าย (ตามระดับความชันกราเดียนต์อัลฟ่า) ของค่าความโปร่งแสงอัลฟ่าสุดท้าย (เปอร์เซ็นต์). เขียน **float**. |
| virtual void [set_EndReflectionOpacity](./set_endreflectionopacity/)(**float**) | ความทึบของการสะท้อนสุดท้าย (เปอร์เซ็นต์). เขียน **float**. |
| virtual void [set_FadeDirection](./set_fadedirection/)(**float**) | ระบุทิศทางสำหรับการชิดการสะท้อน (มุม). เขียน **float**. |
| virtual void [set_RectangleAlign](./set_rectanglealign/)([RectangleAlignment](../../aspose.slides/rectanglealignment/)) | การจัดตำแหน่งสี่เหลี่ยม. เขียน [RectangleAlignment](../../aspose.slides/rectanglealignment/). |
| virtual void [set_RotateShadowWithShape](./set_rotateshadowwithshape/)(**bool**) | ระบุว่าการสะท้อนควรหมุนตามรูปร่างเมื่อรูปร่างถูกหมุนหรือไม่. เขียน **bool**. |
| virtual void [set_ScaleHorizontal](./set_scalehorizontal/)(**double**) | ระบุปัจจัยการสเกลแนวนอน, การสเกลเชิงลบทำให้พลิกรูป (เปอร์เซ็นต์). เขียน **double**. |
| virtual void [set_ScaleVertical](./set_scalevertical/)(**double**) | ระบุปัจจัยการสเกลแนวตั้ง, การสเกลเชิงลบทำให้พลิกรูป (เปอร์เซ็นต์). เขียน **double**. |
| virtual void [set_SkewHorizontal](./set_skewhorizontal/)(**double**) | ระบุมุมการบิดแนวนอน. เขียน **double**. |
| virtual void [set_SkewVertical](./set_skewvertical/)(**double**) | ระบุมุมการบิดแนวตั้ง. เขียน **double**. |
| virtual void [set_StartPosAlpha](./set_startposalpha/)(**float**) | ระบุตำแหน่งเริ่มต้น (ตามระดับความชันกราเดียนต์อัลฟ่า) ของค่าความโปร่งแสงอัลฟ่าเริ่มต้น (เปอร์เซ็นต์). เขียน **float**. |
| virtual void [set_StartReflectionOpacity](./set_startreflectionopacity/)(**float**) | ความทึบของการสะท้อนเริ่มต้น (เปอร์เซ็นต์). เขียน **float**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | ตั้งค่าเทมเพลตอาร์กิวเมนต์ที่ n เป็น weak pointer (แทน shared). อนุญาตให้สลับพอยน์เตอร์ในคอนเทนเนอร์เป็นโหมด weak. |
| int [SharedCount](../../system/object/sharedcount/)() const | รับค่าปัจจุบันของตัวนับอ้างอิงร่วม. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | เพิ่มจำนวนการอ้างอิงร่วม. ไม่ควรเรียกโดยตรง; ใช้ smart pointer หรือ ThisProtector แทน. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ลดจำนวนการอ้างอิงร่วมและคืนค่า. ไม่ควรเรียกโดยตรง; ใช้ smart pointer หรือ ThisProtector แทน. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | คล้ายเมธอด C# [Object.ToString()](../../system/object/tostring/). เปิดใช้งานการแปลงวัตถุที่กำหนดเองเป็นสตริง. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ใช้โครงสร้าง C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | ปลดล็อก C# lock() statement. เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | เพิ่มจำนวนการอ้างอิง weak. ไม่ควรเรียกโดยตรง; ใช้ smart pointer หรือ ThisProtector แทน. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ลดจำนวนการอ้างอิง weak. ไม่ควรเรียกโดยตรง; ใช้ smart pointer หรือ ThisProtector แทน. |
| virtual  [~Object](../../system/object/~object/)() | ทำลายวัตถุ. ปลดปล่อยโครงสร้างข้อมูลภายในทั้งหมด. |

## ดูเพิ่มเติม

* คลาส [IImageTransformOperation](../iimagetransformoperation/)
* คลาส [IAccessiblePVIObject](../../aspose.slides/iaccessiblepviobject/)
* เนมสเปซ [Aspose::Slides::Effects](../)
* ไลบรารี [Aspose.Slides](../../)