---
title: OverrideTheme
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: แสดงถึงธีมที่ถูก overriding.
type: docs
weight: 547
url: /th/aspose.slides.theme/overridetheme/
---
## คลาส OverrideTheme

แสดงถึงธีมที่ถูก override

```cpp
class OverrideTheme : public Aspose::Slides::Theme::Theme,
                      public Aspose::Slides::Theme::IOverrideTheme
```

## เมธอด

| Method | คำอธิบาย |
| --- | --- |
| void [Clear](./clear/)() override | ตั้งค่า [ColorScheme](../colorscheme/), [FontScheme](../fontscheme/), [FormatScheme](../formatscheme/) เป็น null เพื่อปิดการ overriding ใดๆ ด้วยวัตถุธีมนี้ |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | เปรียบเทียบอ็อบเจ็กต์โดยใช้ semantics ของ C# [Object.Equals](../../system/object/equals/) |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจ็กต์ประเภทอ้างอิงในสไตล์ C# |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจ็กต์ประเภทค่าในสไตล์ C# |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | จำลองการเปรียบเทียบจุดลอยแบบ C#-style ที่ NaN สองค่าถูกพิจารณาเท่ากันแม้ว่าตาม IEC 60559:1989 NaN ไม่เท่ากับค่าต่างๆ รวมถึง NaN ด้วย |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | จำลองการเปรียบเทียบจุดลอยแบบ C#-style ที่ NaN สองค่าถูกพิจารณาเท่ากันแม้ว่าตาม IEC 60559:1989 NaN ไม่เท่ากับค่าต่างๆ รวมถึง NaN ด้วย |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | ใช้เพื่อจุดประสงค์ภายในเท่านั้น |
| [System::SharedPtr](../../system/sharedptr/)\<[IColorFormat](../../aspose.slides/icolorformat/)\> [get_ColorFormat](./get_colorformat/)([ColorSchemeIndex](../../aspose.slides/colorschemeindex/)) override |  |
| [System::SharedPtr](../../system/sharedptr/)\<[IColorScheme](../icolorscheme/)\> [get_ColorScheme](./get_colorscheme/)() override | คืนค่าโครงสร้างสี. อ่านอย่างเดียว [IColorScheme](../icolorscheme/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IFontScheme](../ifontscheme/)\> [get_FontScheme](./get_fontscheme/)() override | คืนค่าโครงสร้างฟอนต์. อ่านอย่างเดียว [IFontScheme](../ifontscheme/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IFormatScheme](../iformatscheme/)\> [get_FormatScheme](./get_formatscheme/)() override | คืนค่าโครงสร้างรูปแบบรูปร่าง. อ่านอย่างเดียว [IFormatScheme](../iformatscheme/). |
| **bool** [get_IsEmpty](./get_isempty/)() override | ค่า true หมายความว่า [ColorScheme](../colorscheme/), [FontScheme](../fontscheme/), [FormatScheme](../formatscheme/) เป็น null และการ overriding ใดๆ ด้วยวัตถุธีมนี้ถูกปิดการทำงาน. อ่านอย่างเดียว **bool**. |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IPresentationComponent](../../aspose.slides/ipresentationcomponent/)\> [get_Parent_IPresentationComponent](../../aspose.slides/ipviobject/get_parent_ipresentationcomponent/)() | คืนค่าพาเรนท์ [IPresentationComponent](../../aspose.slides/ipresentationcomponent/). อ่านอย่างเดียว [IPresentationComponent](../../aspose.slides/ipresentationcomponent/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../../aspose.slides/ipresentation/)\> [get_Presentation](../theme/get_presentation/)() override | คืนค่าสไลด์พาเรนท์. อ่านอย่างเดียว [IPresentation](../../aspose.slides/ipresentation/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | รับโครงสร้างข้อมูลตัวนับอ้างอิงที่เชื่อมโยงกับอ็อบเจ็กต์ |
| [System::SharedPtr](../../system/sharedptr/)\<[IThemeEffectiveData](../ithemeeffectivedata/)\> [GetEffective](../theme/geteffective/)() override | รับข้อมูลธีมที่มีผลพร้อมการสืบทอดที่ใช้ |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | เทียบเคียงกับเมธอด C# [Object.GetHashCode()](../../system/object/gethashcode/). ทำให้สามารถแฮชอ็อบเจ็กต์ที่กำหนดเองได้ |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | รับประเภทจริงของอ็อบเจ็กต์. เทียบเคียงกับการเรียก C# [System.Object.GetType()](../../system/object/gettype/) |
| void [InitColorScheme](./initcolorscheme/)() override | เริ่มต้น [ColorScheme](../colorscheme/) ด้วยอ็อบเจ็กต์ใหม่สำหรับการ overriding [ColorScheme](../colorscheme/) ของ InheritedTheme |
| void [InitColorSchemeFrom](./initcolorschemefrom/)([System::SharedPtr](../../system/sharedptr/)\<[IColorScheme](../icolorscheme/)\>) override | เริ่มต้น [ColorScheme](../colorscheme/) ด้วยอ็อบเจ็กต์ใหม่สำหรับการ overriding [ColorScheme](../colorscheme/) ของ InheritedTheme |
| void [InitColorSchemeFromInherited](./initcolorschemefrominherited/)() override | เริ่มต้น [ColorScheme](../colorscheme/) ด้วยอ็อบเจ็กต์ใหม่สำหรับการ overriding [ColorScheme](../colorscheme/) ของ InheritedTheme. และเริ่มต้นข้อมูลของอ็อบเจ็กต์ใหม่ด้วยข้อมูลของ [ColorScheme](../colorscheme/) ของ InheritedTheme |
| void [InitFontScheme](./initfontscheme/)() override | เริ่มต้น [FontScheme](../fontscheme/) ด้วยอ็อบเจ็กต์ใหม่สำหรับการ overriding [FontScheme](../fontscheme/) ของ InheritedTheme |
| void [InitFontSchemeFrom](./initfontschemefrom/)([System::SharedPtr](../../system/sharedptr/)\<[IFontScheme](../ifontscheme/)\>) override | เริ่มต้น [FontScheme](../fontscheme/) ด้วยอ็อบเจ็กต์ใหม่สำหรับการ overriding [FontScheme](../fontscheme/) ของ InheritedTheme |
| void [InitFontSchemeFromInherited](./initfontschemefrominherited/)() override | เริ่มต้น [FontScheme](../fontscheme/) ด้วยอ็อบเจ็กต์ใหม่สำหรับการ overriding [FontScheme](../fontscheme/) ของ InheritedTheme. และเริ่มต้นข้อมูลของอ็อบเจ็กต์ใหม่ด้วยข้อมูลของ [FontScheme](../fontscheme/) ของ InheritedTheme |
| void [InitFormatScheme](./initformatscheme/)() override | เริ่มต้น [FormatScheme](../formatscheme/) ด้วยอ็อบเจ็กต์ใหม่สำหรับการ overriding [FormatScheme](../formatscheme/) ของ InheritedTheme |
| void [InitFormatSchemeFrom](./initformatschemefrom/)([System::SharedPtr](../../system/sharedptr/)\<[IFormatScheme](../iformatscheme/)\>) override | เริ่มต้น [FormatScheme](../formatscheme/) ด้วยอ็อบเจ็กต์ใหม่สำหรับการ overriding [FormatScheme](../formatscheme/) ของ InheritedTheme |
| void [InitFormatSchemeFromInherited](./initformatschemefrominherited/)() override | เริ่มต้น [FormatScheme](../formatscheme/) ด้วยอ็อบเจ็กต์ใหม่สำหรับการ overriding [FormatScheme](../formatscheme/) ของ InheritedTheme. และเริ่มต้นข้อมูลของอ็อบเจ็กต์ใหม่ด้วยข้อมูลของ [FormatScheme](../formatscheme/) ของ InheritedTheme |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | ตรวจสอบว่าอ็อบเจ็กต์เป็นอินสแตนซ์ของประเภทที่อธิบายโดย targetType. เทียบเคียงกับตัวดำเนินการ 'is' ของ C# |
| void [Lock](../../system/object/lock/)() | ทำหน้าที่เป็นการล็อกตามคำสั่ง lock() ของ C#. เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/) |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | เทียบเคียงกับเมธอด C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). ทำให้สามารถโคลนประเภทที่กำหนดเองได้ |
|  [Object](../../system/object/object/)() | สร้างอ็อบเจ็กต์. เริ่มต้นโครงสร้างข้อมูลภายในทั้งหมด |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | คอนสตรัคเตอร์คัดลอก. ไม่ได้คัดลอกอะไรเลย จริงๆ แล้วเพียงเริ่มต้นอ็อบเจ็กต์ใหม่และเปิดให้ซับคลาสสามารถคัดลอกได้ |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | ตัวดำเนินการกำหนดค่า. ไม่ได้คัดลอกอะไรเลย จริงๆ แล้วเพียงเริ่มต้นอ็อบเจ็กต์ใหม่และเปิดให้ซับคลาสสามารถคัดลอกได้ |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | เปรียบเทียบอ็อบเจ็กต์โดยอ้างอิง |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | เปรียบเทียบอ็อบเจ็กต์โดยอ้างอิง |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | เปรียบเทียบอ็อบเจ็กต์ประเภทค่ากับ nullptr โดยอ้างอิง |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | เฉพาะสำหรับ [Object::ReferenceEquals](../../system/object/referenceequals/) ในกรณีของสตริงและ nullptr |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | เฉพาะสำหรับ [Object::ReferenceEquals](../../system/object/referenceequals/) ในกรณีของสตริง |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | ลดจำนวนการอ้างอิงแบบแชร์ลงตามค่าที่ระบุ |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | ตั้งค่าเทมเพลตอาร์กิวเมนต์ที่ n เป็น weak pointer (แทนที่ shared). อนุญาตให้สลับพอยน์เตอร์ในคอนเทนเนอร์เป็นโหมด weak |
| int [SharedCount](../../system/object/sharedcount/)() const | รับค่าปัจจุบันของตัวนับการอ้างอิงแบบแชร์ |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | เพิ่มจำนวนการอ้างอิงแบบแชร์. ไม่ควรเรียกโดยตรง; ควรใช้ smart pointer หรือ ThisProtector |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ลดจำนวนการอ้างอิงแบบแชร์และคืนค่า. ไม่ควรเรียกโดยตรง; ควรใช้ smart pointer หรือ ThisProtector |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | เทียบเคียงกับเมธอด C# [Object.ToString()](../../system/object/tostring/). ทำให้สามารถแปลงอ็อบเจ็กต์ที่กำหนดเองเป็นสตริงได้ |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ทำหน้าที่เป็นโครงสร้าง typeof([System.Object](../../system/object/)) ของ C# |
| void [Unlock](../../system/object/unlock/)() | ทำหน้าที่เป็นการปลดล็อกตามคำสั่ง lock() ของ C#. เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/) |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | เพิ่มจำนวนการอ้างอิงแบบ weak. ไม่ควรเรียกโดยตรง; ควรใช้ smart pointer หรือ ThisProtector |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ลดจำนวนการอ้างอิงแบบ weak. ไม่ควรเรียกโดยตรง; ควรใช้ smart pointer หรือ ThisProtector |
| virtual  [~Object](../../system/object/~object/)() | ทำลายอ็อบเจ็กต์. ปล่อยโครงสร้างข้อมูลภายในทั้งหมด |

## ดูเพิ่มเติม

* คลาส [Theme](../theme/)
* คลาส [IOverrideTheme](../ioverridetheme/)
* เนมสเปซ [Aspose::Slides::Theme](../)
* ไลบรารี [Aspose.Slides](../../)