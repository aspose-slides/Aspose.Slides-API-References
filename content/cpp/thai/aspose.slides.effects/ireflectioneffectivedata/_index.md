---
title: IReflectionEffectiveData
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: อ็อบเจ็กต์ที่ไม่เปลี่ยนแปลงซึ่งเป็นตัวแทนของเอฟเฟกต์การสะท้อน.
type: docs
weight: 950
url: /th/aspose.slides.effects/ireflectioneffectivedata/
---
## IReflectionEffectiveData คลาส

อ็อบเจ็กต์ที่ไม่เปลี่ยนแปลงซึ่งเป็นตัวแทนของเอฟเฟกต์ [Reflection](../reflection/).

```cpp
class IReflectionEffectiveData : public virtual Aspose::Slides::Effects::IEffectEffectiveData
```

## เมธอด

| Method | Description |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | เปรียบเทียบอ็อบเจ็กต์โดยใช้หลักการของ C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจ็กต์ประเภทอ้างอิงในสไตล์ของ C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจ็กต์ประเภทค่าในสไตล์ของ C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | จำลองการเปรียบเทียบจุดลอยแบบ C# ที่ NaN สองค่าเป็นเท่ากันแม้ว่าตาม IEC 60559:1989 NaN จะไม่เท่ากับค่าทั้งหมด รวมถึง NaN เอง. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | จำลองการเปรียบเทียบจุดลอยแบบ C# ที่ NaN สองค่าเป็นเท่ากันแม้ว่าตาม IEC 60559:1989 NaN จะไม่เท่ากับค่าทั้งหมด รวมถึง NaN เอง. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | สำหรับการใช้งานภายในเท่านั้น. |
| virtual **double** [get_BlurRadius](./get_blurradius/)() | รัศมี [Blur](../blur/). อ่านอย่างเดียว **double**. |
| virtual **float** [get_Direction](./get_direction/)() | ทิศทางของการสะท้อน. อ่านอย่างเดียว **float**. |
| virtual **double** [get_Distance](./get_distance/)() | ระยะทางของการสะท้อน. อ่านอย่างเดียว **double**. |
| virtual **float** [get_EndPosAlpha](./get_endposalpha/)() | ระบุตำแหน่งสุดท้าย (ตามรอบกราดิเอนต์อัลฟา) ของค่าความโปร่งใสอัลฟาสุดท้าย (เปอร์เซ็นต์). อ่านอย่างเดียว **float**. |
| virtual **float** [get_EndReflectionOpacity](./get_endreflectionopacity/)() | ความทึบของการสะท้อนสุดท้าย (เปอร์เซ็นต์). อ่านอย่างเดียว **float**. |
| virtual **float** [get_FadeDirection](./get_fadedirection/)() | ระบุทิศทางเพื่อชิดการสะท้อน (มุม). อ่านอย่างเดียว **float**. |
| virtual [RectangleAlignment](../../aspose.slides/rectanglealignment/) [get_RectangleAlign](./get_rectanglealign/)() | การจัดตำแหน่งสี่เหลี่ยม. อ่านอย่างเดียว [RectangleAlignment](../../aspose.slides/rectanglealignment/). |
| virtual **bool** [get_RotateShadowWithShape](./get_rotateshadowwithshape/)() | ระบุว่าการสะท้อนควรหมุนตามรูปร่างหรือไม่หากรูปร่างถูกหมุน. อ่านอย่างเดียว **bool**. |
| virtual **double** [get_ScaleHorizontal](./get_scalehorizontal/)() | ระบุตัวคูณการสเกลแนวนอน, การสเกลเชิงลบทำให้พลิก. (เปอร์เซ็นต์) อ่านอย่างเดียว **double**. |
| virtual **double** [get_ScaleVertical](./get_scalevertical/)() | ระบุตัวคูณการสเกลแนวตั้ง, การสเกลเชิงลบทำให้พลิก. (เปอร์เซ็นต์) อ่านอย่างเดียว **double**. |
| virtual **double** [get_SkewHorizontal](./get_skewhorizontal/)() | ระบุมุมการเอียงแนวนอน. อ่านอย่างเดียว **double**. |
| virtual **double** [get_SkewVertical](./get_skewvertical/)() | ระบุมุมการเอียงแนวตั้ง. อ่านอย่างเดียว **double**. |
| virtual **float** [get_StartPosAlpha](./get_startposalpha/)() | ระบุตำแหน่งเริ่มต้น (ตามรอบกราดิเอนต์อัลฟา) ของค่าความโปร่งใสอัลฟ่าเริ่มต้น (เปอร์เซ็นต์). อ่านอย่างเดียว **float**. |
| virtual **float** [get_StartReflectionOpacity](./get_startreflectionopacity/)() | ความทึบของการสะท้อนเริ่มต้น (เปอร์เซ็นต์). อ่านอย่างเดียว **float**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | รับโครงสร้างข้อมูลตัวนับอ้างอิงที่เชื่อมโยงกับอ็อบเจ็กต์. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | เหมือนเมธอด C# [Object.GetHashCode()](../../system/object/gethashcode/). เปิดใช้งานการแฮชของอ็อบเจ็กต์ที่กำหนดเอง. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | รับประเภทจริงของอ็อบเจ็กต์. เหมือนการเรียก C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | ตรวจสอบว่าอ็อบเจ็กต์เป็นอินสแตนซ์ของประเภทที่อธิบายโดย targetType หรือไม่. เหมือนตัวดำเนินการ 'is' ของ C#. |
| void [Lock](../../system/object/lock/)() | ดำเนินการล็อกตามคำสั่ง lock() ของ C#. เรียกโดยตรงหรือใช้วัตถุกันอุ่น [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | เหมือนเมธอด C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). เปิดใช้งานการทำสำเนาของประเภทที่กำหนดเอง. |
|  [Object](../../system/object/object/)() | สร้างอ็อบเจ็กต์. เริ่มต้นโครงสร้างข้อมูลภายในทั้งหมด. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | คอนสตรัคเตอร์สำเนา. จริง ๆ แล้วไม่ได้คัดลอกอะไรเลย เพียงเริ่มต้นอ็อบเจ็กต์ใหม่และเปิดใช้งานการคัดลอกสร้างซับคลาส. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | ตัวดำเนินการกำหนดค่า. จริง ๆ แล้วไม่ได้คัดลอกอะไรเลย เพียงเริ่มต้นอ็อบเจ็กต์ใหม่และเปิดใช้งานการคัดลอกสร้างซับคลาส. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | เปรียบเทียบอ็อบเจ็กต์โดยอ้างอิง. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | เปรียบเทียบอ็อบเจ็กต์โดยอ้างอิง. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | เปรียบเทียบอ็อบเจ็กต์ประเภทค่าโดยอ้างอิงกับ nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | การเฉพาะของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริงและ nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | การเฉพาะของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริง. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | ลดจำนวนตัวนับอ้างอิงที่แชร์ลงโดยค่าที่ระบุ. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | ตั้งอาร์กิวเมนต์เทมเพลตที่ n เป็น weak pointer (แทน shared). อนุญาตให้สลับพอยน์เตอร์ในคอนเทนเนอร์เป็นโหมด weak. |
| int [SharedCount](../../system/object/sharedcount/)() const | รับค่าปัจจุบันของตัวนับอ้างอิงที่แชร์. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | เพิ่มจำนวนตัวนับอ้างอิงที่แชร์. ไม่ควรเรียกโดยตรง; ให้ใช้สมาร์ทพอยน์เตอร์หรือ ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ลดจำนวนและคืนค่าตัวนับอ้างอิงที่แชร์. ไม่ควรเรียกโดยตรง; ให้ใช้สมาร์ทพอยน์เตอร์หรือ ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | เหมือนเมธอด C# [Object.ToString()](../../system/object/tostring/). เปิดใช้งานการแปลงอ็อบเจ็กต์ที่กำหนดเองเป็นสตริง. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ดำเนินการสร้าง typeof([System.Object](../../system/object/)) ของ C#. |
| void [Unlock](../../system/object/unlock/)() | ดำเนินการปลดล็อกตามคำสั่ง lock() ของ C#. เรียกโดยตรงหรือใช้วัตถุกันอุ่น [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | เพิ่มจำนวนตัวนับอ้างอิงแบบ weak. ไม่ควรเรียกโดยตรง; ให้ใช้สมาร์ทพอยน์เตอร์หรือ ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ลดจำนวนตัวนับอ้างอิงแบบ weak. ไม่ควรเรียกโดยตรง; ให้ใช้สมาร์ทพอยน์เตอร์หรือ ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | ทำลายอ็อบเจ็กต์. ปล่อยโครงสร้างข้อมูลภายในทั้งหมด. |

## ดูเพิ่มเติม

* คลาส [IEffectEffectiveData](../ieffecteffectivedata/)
* เนมส페ซ [Aspose::Slides::Effects](../)
* ไลบรารี [Aspose.Slides](../../)