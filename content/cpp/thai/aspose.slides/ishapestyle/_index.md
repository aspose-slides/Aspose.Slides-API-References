---
title: IShapeStyle
second_title: Aspose.Slides สำหรับการอ้างอิง API ของ C++
description: แสดงการอ้างอิงสไตล์ของรูปร่าง
type: docs
weight: 3719
url: /th/aspose.slides/ishapestyle/
---
## IShapeStyle คลาส


แสดงการอ้างอิงสไตล์ของรูปร่าง

```cpp
class IShapeStyle : public virtual System::Object
```

## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | เปรียบเทียบอ็อบเจ็กต์โดยใช้หลักการของ C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจ็กต์ประเภทอ้างอิงในสไตล์ C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจ็กต์ประเภทค่าในสไตล์ C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | จำลองการเปรียบเทียบจุดทศนิยมแบบ C# โดยที่ NaN สองค่าถือว่าสมเท่า แม้ว่าตามมาตรฐาน IEC 60559:1989 NaN จะไม่เท่ากับค่าใด ๆ รวมถึง NaN ด้วย. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | จำลองการเปรียบเทียบจุดทศนิยมแบบ C# โดยที่ NaN สองค่าถือว่าสมเท่า แม้ว่าตามมาตรฐาน IEC 60559:1989 NaN จะไม่เท่ากับค่าใด ๆ รวมถึง NaN ด้วย. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | เพื่อการใช้งานภายในเท่านั้น. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IColorFormat](../icolorformat/)\> [get_EffectColor](./get_effectcolor/)() | คืนค่าสีเอฟเฟกต์ของรูปร่าง อ่านอย่างเดียว [IColorFormat](../icolorformat/). |
| virtual **uint32_t** [get_EffectStyleIndex](./get_effectstyleindex/)() | คืนค่าดัชนีคอลัมน์เอฟเฟกต์ของรูปร่างในเมทริกซ์สไตล์ อ่าน **uint32_t**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IColorFormat](../icolorformat/)\> [get_FillColor](./get_fillcolor/)() | คืนค่าสีเติมของรูปร่าง อ่านอย่างเดียว [IColorFormat](../icolorformat/). |
| virtual **int16_t** [get_FillStyleIndex](./get_fillstyleindex/)() | คืนค่าดัชนีคอลัมน์เติมของรูปร่างในเมทริกซ์สไตล์ 0 หมายถึงไม่มีการเติม ค่าเป็นบวก - ดัชนีในสไตล์การเติมของธีม ค่าเป็นลบ - ดัชนีในสไตล์พื้นหลังของธีม อ่าน **int16_t**. |
| virtual [Aspose::Slides::FontCollectionIndex](../fontcollectionindex/) [get_FontCollectionIndex](./get_fontcollectionindex/)() | คืนค่าดัชนีฟอนต์ของรูปร่างในคอลเลกชันฟอนต์ อ่าน [Slides::FontCollectionIndex](../fontcollectionindex/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IColorFormat](../icolorformat/)\> [get_FontColor](./get_fontcolor/)() | คืนค่าสีฟอนต์ของรูปร่าง อ่านอย่างเดียว [IColorFormat](../icolorformat/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IColorFormat](../icolorformat/)\> [get_LineColor](./get_linecolor/)() | คืนค่าสีขอบของรูปร่าง อ่านอย่างเดียว [IColorFormat](../icolorformat/). |
| virtual **uint16_t** [get_LineStyleIndex](./get_linestyleindex/)() | คืนค่าดัชนีคอลัมน์ของเส้นในเมทริกซ์สไตล์ อ่าน **uint16_t**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | รับโครงสร้างข้อมูลตัวนับการอ้างอิงที่เชื่อมโยงกับอ็อบเจ็กต์. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | คล้ายกับเมธอด C# [Object.GetHashCode()](../../system/object/gethashcode/) ทำให้สามารถแฮชอ็อบเจ็กต์ที่กำหนดเองได้. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | รับประเภทจริงของอ็อบเจ็กต์ คล้ายการเรียก C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | ตรวจสอบว่าอ็อบเจ็กต์เป็นอินสแตนซ์ของประเภทที่อธิบายโดย targetType หรือไม่ คล้ายกับโอเปอร์าเตอร์ 'is' ของ C#. |
| void [Lock](../../system/object/lock/)() | ทำหน้าที่ล็อกตามคำสั่ง C# lock() เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | คล้ายกับเมธอด C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) ทำให้สามารถคล cloning ชนิดที่กำหนดเองได้. |
|  [Object](../../system/object/object/)() | สร้างอ็อบเจ็กต์ เริ่มต้นโครงสร้างข้อมูลภายในทั้งหมด. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | คอนสตรัคเตอร์คัดลอก ไม่ได้คัดลอกอะไรจริง ๆ เพียงเริ่มต้นอ็อบเจ็กต์ใหม่และทำให้สามารถสร้างคัดลอกซับคลาสได้. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | โอเปอเรเตอร์การกำหนดค่า ไม่ได้คัดลอกอะไรจริง ๆ เพียงเริ่มต้นอ็อบเจ็กต์ใหม่และทำให้สามารถสร้างคัดลอกซับคลาสได้. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | เปรียบเทียบอ็อบเจ็กต์ตามการอ้างอิง. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | เปรียบเทียบอ็อบเจ็กต์ตามการอ้างอิง. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | เปรียบเทียบการอ้างอิงอ็อบเจ็กต์ประเภทค่า กับ nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | เฉพาะกรณีของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับสตริงและ nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | เฉพาะกรณีของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับสตริง. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | ลดจำนวนการอ้างอิงที่แชร์โดยค่าที่ระบุ. |
| virtual void [set_EffectStyleIndex](./set_effectstyleindex/)(**uint32_t**) | ตั้งค่าดัชนีคอลัมน์เอฟเฟกต์ของรูปร่างในเมทริกซ์สไตล์ เขียน **uint32_t**. |
| virtual void [set_FillStyleIndex](./set_fillstyleindex/)(**int16_t**) | ตั้งค่าดัชนีคอลัมน์เติมของรูปร่างในเมทริกซ์สไตล์ 0 หมายถึงไม่มีการเติม ค่าเป็นบวก - ดัชนีในสไตล์การเติมของธีม ค่าเป็นลบ - ดัชนีในสไตล์พื้นหลังของธีม เขียน **int16_t**. |
| virtual void [set_FontCollectionIndex](./set_fontcollectionindex/)([Aspose::Slides::FontCollectionIndex](../fontcollectionindex/)) | ตั้งค่าดัชนีฟอนต์ของรูปร่างในคอลเลกชันฟอนต์ เขียน [Slides::FontCollectionIndex](../fontcollectionindex/). |
| virtual void [set_LineStyleIndex](./set_linestyleindex/)(**uint16_t**) | ตั้งค่าดัชนีคอลัมน์ของเส้นในเมทริกซ์สไตล์ เขียน **uint16_t**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | ตั้งค่าอาร์กิวเมนต์เทมเพลตที่ n เป็น weak pointer (แทนที่ shared) อนุญาตให้สลับพอยน์เตอร์ในคอนเทนเนอร์เป็นโหมด weak. |
| int [SharedCount](../../system/object/sharedcount/)() const | รับค่าปัจจุบันของตัวนับการอ้างอิงที่แชร์. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | เพิ่มจำนวนการอ้างอิงที่แชร์ ไม่ควรเรียกโดยตรง; ใช้ smart pointer หรือ ThisProtector แทน. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ลดจำนวนและคืนค่าตัวนับการอ้างอิงที่แชร์ ไม่ควรเรียกโดยตรง; ใช้ smart pointer หรือ ThisProtector แทน. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | คล้ายกับเมธอด C# [Object.ToString()](../../system/object/tostring/) ทำให้สามารถแปลงอ็อบเจ็กต์ที่กำหนดเองเป็นสตริงได้. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ทำหน้าที่ typeof([System.Object](../../system/object/)) ของ C#. |
| void [Unlock](../../system/object/unlock/)() | ทำหน้าที่ปลดล็อกตามคำสั่ง C# lock() เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | เพิ่มจำนวนการอ้างอิงแบบ weak ไม่ควรเรียกโดยตรง; ใช้ smart pointer หรือ ThisProtector แทน. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ลดจำนวนการอ้างอิงแบบ weak ไม่ควรเรียกโดยตรง; ใช้ smart pointer หรือ ThisProtector แทน. |
| virtual  [~Object](../../system/object/~object/)() | ทำลายอ็อบเจ็กต์ ปลดปล่อยโครงสร้างข้อมูลภายในทั้งหมด. |

## ดูเพิ่มเติม

* คลาส [Object](../../system/object/)
* เนมสเปซ [Aspose::Slides](../)
* ไลบรารี [Aspose.Slides](../../)