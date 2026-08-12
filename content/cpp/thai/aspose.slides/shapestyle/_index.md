---
title: ShapeStyle
second_title: เอกสารอ้างอิง API ของ Aspose.Slides สำหรับ C++
description: อ้างอิงสไตล์ของรูปร่าง
type: docs
weight: 5149
url: /th/aspose.slides/shapestyle/
---
## ShapeStyle คลาส

Represent shape's style reference.

```cpp
class ShapeStyle : public Aspose::Slides::DomObject<System::SharedPtr<Aspose::Slides::Shape>>,
                   public Aspose::Slides::IShapeStyle
```

## เมธอด

| เมธอด | รายละเอียด |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | เปรียบเทียบอ็อบเจ็กต์โดยใช้ semantics ของ C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจ็กต์ประเภทอ้างอิงในสไตล์ C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจ็กต์ประเภทค่าในสไตล์ C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | จำลองการเปรียบเทียบจำนวนจริงแบบ C#-style ที่ NaN สองค่าถูกพิจารณาเท่ากันแม้ตาม IEC 60559:1989 NaN ไม่เท่ากับค่าใด ๆ รวมถึง NaN ด้วย |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | จำลองการเปรียบเทียบจำนวนจริงแบบ C#-style ที่ NaN สองค่าถูกพิจารณาเท่ากันแม้ตาม IEC 60559:1989 NaN ไม่เท่ากับค่าใด ๆ รวมถึง NaN ด้วย |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | สำหรับการใช้ภายในเท่านั้น. |
| [System::SharedPtr](../../system/sharedptr/)\<[IColorFormat](../icolorformat/)\> [get_EffectColor](./get_effectcolor/)() override | คืนค่าสีเอฟเฟ็กต์ของรูปร่าง อ่านอย่างเดียว [IColorFormat](../icolorformat/). |
| **uint32_t** [get_EffectStyleIndex](./get_effectstyleindex/)() override | คืนค่าดัชนีคอลัมน์เอฟเฟ็กต์ของรูปร่างในเมทริกซ์สไตล์ อ่าน **uint32_t**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IColorFormat](../icolorformat/)\> [get_FillColor](./get_fillcolor/)() override | คืนค่าสีเติมของรูปร่าง อ่านอย่างเดียว [IColorFormat](../icolorformat/). |
| **int16_t** [get_FillStyleIndex](./get_fillstyleindex/)() override | คืนค่าดัชนีคอลัมน์เติมของรูปร่างในเมทริกซ์สไตล์ 0 หมายถึงไม่มีการเติม ค่าเป็นบวก - ดัชนีในสไตล์เติมของธีม, ค่าเป็นลบ - ดัชนีในสไตล์พื้นหลังของธีม อ่าน **int16_t**. |
| [Aspose::Slides::FontCollectionIndex](../fontcollectionindex/) [get_FontCollectionIndex](./get_fontcollectionindex/)() override | คืนค่าดัชนีฟอนต์ของรูปร่างในคอลเลกชันฟอนต์ อ่าน [Slides::FontCollectionIndex](../fontcollectionindex/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IColorFormat](../icolorformat/)\> [get_FontColor](./get_fontcolor/)() override | คืนค่าสีกลุ่มฟอนต์ของรูปร่าง อ่านอย่างเดียว [IColorFormat](../icolorformat/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IColorFormat](../icolorformat/)\> [get_LineColor](./get_linecolor/)() override | คืนค่าสีเค้าโครงของรูปร่าง อ่านอย่างเดียว [IColorFormat](../icolorformat/). |
| **uint16_t** [get_LineStyleIndex](./get_linestyleindex/)() override | คืนค่าดัชนีคอลัมน์ของเส้นในเมทริกซ์สไตล์ อ่าน **uint16_t**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | รับโครงสร้างข้อมูลตัวนับอ้างอิงที่เชื่อมโยงกับอ็อบเจ็กต์. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | แอนะล็อกของเมธอด C# [Object.GetHashCode()](../../system/object/gethashcode/) ทำให้สามารถแฮชอ็อบเจ็กต์ที่กำหนดเองได้. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | รับประเภทจริงของอ็อบเจ็กต์ แอนะล็อกของการเรียก C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | ตรวจสอบว่าอ็อบเจ็กต์เป็นอินสแตนซ์ของประเภทที่ระบุโดย targetType หรือไม่ แอนะล็อกของตัวดำเนินการ 'is' ของ C#. |
| void [Lock](../../system/object/lock/)() | ทำหน้าที่ล็อกตามคำสั่ง C# lock() เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | แอนะล็อกของเมธอด C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) ทำให้สามารถโคลนประเภทที่กำหนดเองได้. |
|  [Object](../../system/object/object/)() | สร้างอ็อบเจ็กต์ เริ่มต้นโครงสร้างข้อมูลภายในทั้งหมด. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | คอนสตรัคเตอร์คัดลอก ไม่ได้คัดลอกอะไรเลย จริง ๆ เพียงเริ่มต้นอ็อบเจ็กต์ใหม่และเปิดให้สร้างสำเนาในซับคลาสได้. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | ตัวดำเนินการกำหนดค่า ไม่ได้คัดลอกอะไรเลย จริง ๆ เพียงเริ่มต้นอ็อบเจ็กต์ใหม่และเปิดให้สร้างสำเนาในซับคลาสได้. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | เปรียบเทียบอ็อบเจ็กต์โดยอ้างอิง. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | เปรียบเทียบอ็อบเจ็กต์โดยอ้างอิง. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | เปรียบเทียบอ็อบเจ็กต์ประเภทค่าโดยอ้างอิงกับ nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | การพิเศษของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริงและ nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | การพิเศษของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริงหลายค่า. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | ลดค่าตัวนับอ้างอิงที่แชร์ลงตามค่าที่ระบุ. |
| void [set_EffectStyleIndex](./set_effectstyleindex/)(**uint32_t**) override | ตั้งค่าดัชนีคอลัมน์เอฟเฟ็กต์ของรูปร่างในเมทริกซ์สไตล์ เขียน **uint32_t**. |
| void [set_FillStyleIndex](./set_fillstyleindex/)(**int16_t**) override | ตั้งค่าดัชนีคอลัมน์เติมของรูปร่างในเมทริกซ์สไตล์ 0 หมายถึงไม่มีการเติม ค่าเป็นบวก - ดัชนีในสไตล์เติมของธีม, ค่าเป็นลบ - ดัชนีในสไตล์พื้นหลังของธีม เขียน **int16_t**. |
| void [set_FontCollectionIndex](./set_fontcollectionindex/)([Aspose::Slides::FontCollectionIndex](../fontcollectionindex/)) override | ตั้งค่าดัชนีฟอนต์ของรูปร่างในคอลเลกชันฟอนต์ เขียน [Slides::FontCollectionIndex](../fontcollectionindex/). |
| void [set_LineStyleIndex](./set_linestyleindex/)(**uint16_t**) override | ตั้งค่าดัชนีคอลัมน์ของเส้นในเมทริกซ์สไตล์ เขียน **uint16_t**. |
| void [SetTemplateWeakPtr](./settemplateweakptr/)(**uint32_t**) override | ตั้งค่าพารามิเตอร์แม่แบบที่ n ให้เป็น weak pointer (แทนที่จะแชร์) อนุญาตให้เปลี่ยนพอยน์เตอร์ในคอนเทนเนอร์เป็นโหมด weak. |
| int [SharedCount](../../system/object/sharedcount/)() const | รับค่าปัจจุบันของตัวนับอ้างอิงที่แชร์. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | เพิ่มตัวนับอ้างอิงที่แชร์ ควรไม่เรียกโดยตรง; ใช้ smart pointers หรือ ThisProtector แทน. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ลดค่าและคืนค่าตัวนับอ้างอิงที่แชร์ ควรไม่เรียกโดยตรง; ใช้ smart pointers หรือ ThisProtector แทน. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | แอนะล็อกของเมธอด C# [Object.ToString()](../../system/object/tostring/) ทำให้สามารถแปลงอ็อบเจ็กต์ที่กำหนดเองเป็นสตริงได้. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ทำหน้าที่ typeof([System.Object](../../system/object/)) ของ C#. |
| void [Unlock](../../system/object/unlock/)() | ทำหน้าที่ปลดล็อกตามคำสั่ง C# lock() เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | เพิ่มตัวนับ weak reference ควรไม่เรียกโดยตรง; ใช้ smart pointers หรือ ThisProtector แทน. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ลดค่าตัวนับ weak reference ควรไม่เรียกโดยตรง; ใช้ smart pointers หรือ ThisProtector แทน. |
| virtual  [~Object](../../system/object/~object/)() | ทำลายอ็อบเจ็กต์ ปล่อยโครงสร้างข้อมูลภายในทั้งหมด. |

## ดูเพิ่มเติม

* คลาส [DomObject](../domobject/)
* คลาส [IShapeStyle](../ishapestyle/)
* เนมสเปซ [Aspose::Slides](../)
* ไลบรารี [Aspose.Slides](../../)