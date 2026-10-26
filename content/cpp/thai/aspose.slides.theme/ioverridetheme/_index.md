---
title: IOverrideTheme
second_title: Aspose.Slides สำหรับ C++ API Reference
description: แทนธีมที่ทำการแทนที่
type: docs
weight: 391
url: /th/aspose.slides.theme/ioverridetheme/
---
## IOverrideTheme คลาส


แทนธีมที่ทำการแทนที่

```cpp
class IOverrideTheme : public virtual Aspose::Slides::Theme::ITheme
```

## วิธีการ

| วิธีการ | คำอธิบาย |
| --- | --- |
| virtual void [Clear](./clear/)() | ตั้งค่า [ColorScheme](../colorscheme/), [FontScheme](../fontscheme/), [FormatScheme](../formatscheme/) เป็น null เพื่อปิดการแทนที่ใด ๆ ด้วยวัตถุธีมนี้ |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | เปรียบเทียบอ็อบเจ็กต์โดยใช้ความหมายของ C# [Object.Equals](../../system/object/equals/) |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจ็กต์ประเภทอ้างอิงในสไตล์ของ C# |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจ็กต์ประเภทค่าในสไตล์ของ C# |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | จำลองการเปรียบเทียบจำนวนจุดลอยตัวแบบ C# ซึ่ง NaN สองค่าถือว่าเท่ากัน แม้ว่าตาม IEC 60559:1989 NaN ไม่เท่ากับค่าใด ๆ รวมถึง NaN เอง |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | จำลองการเปรียบเทียบจำนวนจุดลอยตัวแบบ C# ซึ่ง NaN สองค่าถือว่าเท่ากัน แม้ว่าตาม IEC 60559:1989 NaN ไม่เท่ากับค่าใด ๆ รวมถึง NaN เอง |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | เพื่อการใช้งานภายในเท่านั้น |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IColorFormat](../../aspose.slides/icolorformat/)\> [get_ColorFormat](../itheme/get_colorformat/)([ColorSchemeIndex](../../aspose.slides/colorschemeindex/)) |  |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IColorScheme](../icolorscheme/)\> [get_ColorScheme](../itheme/get_colorscheme/)() | คืนค่าชุดสี. อ่านอย่างเดียว [IColorScheme](../icolorscheme/) |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFontScheme](../ifontscheme/)\> [get_FontScheme](../itheme/get_fontscheme/)() | คืนค่าชุดฟอนต์. อ่านอย่างเดียว [IFontScheme](../ifontscheme/) |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFormatScheme](../iformatscheme/)\> [get_FormatScheme](../itheme/get_formatscheme/)() | คืนค่าชุดรูปแบบรูปร่าง. อ่านอย่างเดียว [IFormatScheme](../iformatscheme/) |
| virtual **bool** [get_IsEmpty](./get_isempty/)() | ค่าจริงหมายความว่า [ColorScheme](../colorscheme/), [FontScheme](../fontscheme/), [FormatScheme](../formatscheme/) เป็น null และการแทนที่ใด ๆ ด้วยวัตถุธีมนี้ถูกปิดใช้งาน. อ่านอย่างเดียว **bool** |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../../aspose.slides/ipresentation/)\> [get_Presentation](../../aspose.slides/ipresentationcomponent/get_presentation/)() | คืนค่าการนำเสนอ. อ่านอย่างเดียว [IPresentation](../../aspose.slides/ipresentation/) |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | รับโครงสร้างข้อมูลตัวนับอ้างอิงที่เชื่อมโยงกับอ็อบเจ็กต์ |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IThemeEffectiveData](../ithemeeffectivedata/)\> [GetEffective](../itheme/geteffective/)() | รับข้อมูลธีมที่มีผลโดยมีการสืบทอดที่ใช้ |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | เป็นแบบเดียวกับเมธอด C# [Object.GetHashCode()](../../system/object/gethashcode/). ทำให้สามารถแฮชอ็อบเจ็กต์แบบกำหนดเองได้ |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | รับประเภทจริงของอ็อบเจ็กต์. เป็นแบบเดียวกับการเรียก C# [System.Object.GetType()](../../system/object/gettype/) |
| virtual void [InitColorScheme](./initcolorscheme/)() | เริ่มต้น [ColorScheme](../colorscheme/) ด้วยอ็อบเจ็กต์ใหม่สำหรับการแทนที่ [ColorScheme](../colorscheme/) ของ InheritedTheme |
| virtual void [InitColorSchemeFrom](./initcolorschemefrom/)([System::SharedPtr](../../system/sharedptr/)\<[IColorScheme](../icolorscheme/)\>) | เริ่มต้น [ColorScheme](../colorscheme/) ด้วยอ็อบเจ็กต์ใหม่สำหรับการแทนที่ [ColorScheme](../colorscheme/) ของ InheritedTheme |
| virtual void [InitColorSchemeFromInherited](./initcolorschemefrominherited/)() | เริ่มต้น [ColorScheme](../colorscheme/) ด้วยอ็อบเจ็กต์ใหม่สำหรับการแทนที่ [ColorScheme](../colorscheme/) ของ InheritedTheme. และกำหนดค่าข้อมูลของอ็อบเจ็กต์ใหม่นี้ด้วยข้อมูลของ [ColorScheme](../colorscheme/) ของ InheritedTheme |
| virtual void [InitFontScheme](./initfontscheme/)() | เริ่มต้น [FontScheme](../fontscheme/) ด้วยอ็อบเจ็กต์ใหม่สำหรับการแทนที่ [FontScheme](../fontscheme/) ของ InheritedTheme |
| virtual void [InitFontSchemeFrom](./initfontschemefrom/)([System::SharedPtr](../../system/sharedptr/)\<[IFontScheme](../ifontscheme/)\>) | เริ่มต้น [FontScheme](../fontscheme/) ด้วยอ็อบเจ็กต์ใหม่สำหรับการแทนที่ [FontScheme](../fontscheme/) ของ InheritedTheme |
| virtual void [InitFontSchemeFromInherited](./initfontschemefrominherited/)() | เริ่มต้น [FontScheme](../fontscheme/) ด้วยอ็อบเจ็กต์ใหม่สำหรับการแทนที่ [FontScheme](../fontscheme/) ของ InheritedTheme. และกำหนดค่าข้อมูลของอ็อบเจ็กต์ใหม่นี้ด้วยข้อมูลของ [FontScheme](../fontscheme/) ของ InheritedTheme |
| virtual void [InitFormatScheme](./initformatscheme/)() | เริ่มต้น [FormatScheme](../formatscheme/) ด้วยอ็อบเจ็กต์ใหม่สำหรับการแทนที่ [FormatScheme](../formatscheme/) ของ InheritedTheme |
| virtual void [InitFormatSchemeFrom](./initformatschemefrom/)([System::SharedPtr](../../system/sharedptr/)\<[IFormatScheme](../iformatscheme/)\>) | เริ่มต้น [FormatScheme](../formatscheme/) ด้วยอ็อบเจ็กต์ใหม่สำหรับการแทนที่ [FormatScheme](../formatscheme/) ของ InheritedTheme |
| virtual void [InitFormatSchemeFromInherited](./initformatschemefrominherited/)() | เริ่มต้น [FormatScheme](../formatscheme/) ด้วยอ็อบเจ็กต์ใหม่สำหรับการแทนที่ [FormatScheme](../formatscheme/) ของ InheritedTheme. และกำหนดค่าข้อมูลของอ็อบเจ็กต์ใหม่นี้ด้วยข้อมูลของ [FormatScheme](../formatscheme/) ของ InheritedTheme |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | ตรวจสอบว่าอ็อบเจ็กต์เป็นอินสแตนซ์ของประเภทที่อธิบายโดย targetType หรือไม่. เป็นแบบเดียวกับตัวดำเนินการ 'is' ของ C# |
| void [Lock](../../system/object/lock/)() | ทำงานตามคำสั่ง lock() ของ C# เพื่อทำการล็อก. เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/) |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | เป็นแบบเดียวกับเมธอด C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). ทำให้สามารถโคลนนิยามแบบกำหนดเองได้ |
|  [Object](../../system/object/object/)() | สร้างอ็อบเจ็กต์. เริ่มต้นโครงสร้างข้อมูลภายในทั้งหมด |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | คอนสตรัคเตอร์สำเนา. จริง ๆ แล้วไม่ได้คัดลอกอะไรเลย เพียงเริ่มต้นอ็อบเจ็กต์ใหม่และเปิดใช้งานการคัดลอกสร้างซับคลาส |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | โอเปอเรเตอร์กำหนดค่า. จริง ๆ แล้วไม่ได้คัดลอกอะไรเลย เพียงเริ่มต้นอ็อบเจ็กต์ใหม่และเปิดใช้งานการคัดลอกสร้างซับคลาส |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | เปรียบเทียบอ็อบเจ็กต์โดยอ้างอิง |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | เปรียบเทียบอ็อบเจ็กต์โดยอ้างอิง |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | อ้างอิงเปรียบเทียบอ็อบเจ็กต์ประเภทค่า กับ nullptr |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | การทำพิเศษของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริงและ nullptr |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | การทำพิเศษของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริง |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | ลดจำนวนตัวนับอ้างอิงที่แชร์ลงตามค่าที่ระบุ |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | ตั้งค่าเทมเพลตอากิวเมนต์ที่ n ให้เป็น weak pointer (แทนที่ shared). อนุญาตให้สลับ pointer ในคอนเทนเนอร์เป็นโหมด weak |
| int [SharedCount](../../system/object/sharedcount/)() const | รับค่าปัจจุบันของตัวนับอ้างอิงที่แชร์ |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | เพิ่มจำนวนตัวนับอ้างอิงที่แชร์. ไม่ควรเรียกโดยตรง; แทนที่ใช้ smart pointers หรือ ThisProtector |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ลดจำนวนตัวนับอ้างอิงที่แชร์และคืนค่า. ไม่ควรเรียกโดยตรง; แทนที่ใช้ smart pointers หรือ ThisProtector |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | เป็นแบบเดียวกับเมธอด C# [Object.ToString()](../../system/object/tostring/). ทำให้สามารถแปลงอ็อบเจ็กต์กำหนดเองเป็นสตริงได้ |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ทำงานตามโครงสร้าง typeof([System.Object](../../system/object/)) ของ C# |
| void [Unlock](../../system/object/unlock/)() | ทำงานตามคำสั่ง lock() ของ C# เพื่อปลดล็อก. เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/) |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | เพิ่มจำนวนตัวนับอ้างอิงแบบ weak. ไม่ควรเรียกโดยตรง; แทนที่ใช้ smart pointers หรือ ThisProtector |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ลดจำนวนตัวนับอ้างอิงแบบ weak. ไม่ควรเรียกโดยตรง; แทนที่ใช้ smart pointers หรือ ThisProtector |
| virtual  [~Object](../../system/object/~object/)() | ทำลายอ็อบเจ็กต์. ปล่อยโครงสร้างข้อมูลภายในทั้งหมด |

## ดูเพิ่มเติม

* คลาส [ITheme](../itheme/)
* เนมสเปซ [Aspose::Slides::Theme](../)
* ไลบรารี [Aspose.Slides](../../)