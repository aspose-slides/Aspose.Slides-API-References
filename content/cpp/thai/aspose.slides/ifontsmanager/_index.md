---
title: IFontsManager
second_title: Aspose.Slides สำหรับ C++ API อ้างอิง
description: จัดการแบบอักษรทั่วทั้งงานนำเสนอ.
type: docs
weight: 2250
url: /th/aspose.slides/ifontsmanager/
---
## IFontsManager คลาส

จัดการแบบอักษรทั่วทั้งงานนำเสนอ.

```cpp
class IFontsManager : public virtual System::Object
```

## เมธอด

| เมธอด | รายละเอียด |
| --- | --- |
| virtual void [AddEmbeddedFont](./addembeddedfont/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\>, [Export::EmbedFontCharacters](../../aspose.slides.export/embedfontcharacters/)) | เพิ่มแบบอักษรที่ฝังไว้. |
| virtual void [AddEmbeddedFont](./addembeddedfont/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, [Export::EmbedFontCharacters](../../aspose.slides.export/embedfontcharacters/)) | เพิ่มแบบอักษรที่ฝังไว้ |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | เปรียบเทียบวัตถุโดยใช้แนวคิดของ C# [Object.Equals](../../system/object/equals/) |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบวัตถุประเภทอ้างอิงในสไตล์ C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบวัตถุประเภทค่าในสไตล์ C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | จำลองการเปรียบเทียบค่าทศนิยมแบบ C#-style โดยที่ NaN สองค่าถูกถือว่าเท่ากัน แม้ว่าตาม IEC 60559:1989 NaN จะไม่เท่ากับค่าใด ๆ รวมถึง NaN ด้วย. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | จำลองการเปรียบเทียบค่าทศนิยมแบบ C#-style โดยที่ NaN สองค่าถูกถือว่าเท่ากัน แม้ว่าตาม IEC 60559:1989 NaN จะไม่เท่ากับค่าใด ๆ รวมถึง NaN ด้วย. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | เพื่อวัตถุประสงค์ภายในเท่านั้น. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFontFallBackRule](../ifontfallbackrule/)\> [get_FontFallBackRule](./get_fontfallbackrule/)(**int32_t**) | คืนค่ากฎที่ตำแหน่งที่ระบุสำหรับการทดแทนที่เหมาะสมโดยฟังก์ชัน fallback. อ่านอย่างเดียว [Aspose::Slides::IFontFallBackRule](../ifontfallbackrule/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFontFallBackRulesCollection](../ifontfallbackrulescollection/)\> [get_FontFallBackRulesCollection](./get_fontfallbackrulescollection/)() | แสดงคอลเลกชันของผู้ใช้สำหรับกฎ FontFallBack เพื่อจัดการคอลเลกชันของแบบอักษรสำหรับการทดแทนที่เหมาะสมโดยฟังก์ชัน fallback อ่าน [IFontFallBackRulesCollection](../ifontfallbackrulescollection/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFontSubstRule](../ifontsubstrule/)\> [get_FontSubstRule](./get_fontsubstrule/)(**int32_t**) | คืนค่ากฎการทดแทนแบบอักษรที่ตำแหน่งที่ระบุเพื่อใช้เมื่อเรนเดอร์. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFontSubstRuleCollection](../ifontsubstrulecollection/)\> [get_FontSubstRuleList](./get_fontsubstrulelist/)() | การทดแทนแบบอักษรที่ใช้เมื่อเรนเดอร์ อ่าน [IFontSubstRuleCollection](../ifontsubstrulecollection/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | รับโครงสร้างข้อมูลตัวนับอ้างอิงที่เชื่อมโยงกับวัตถุ. |
| virtual [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\>\> [GetEmbeddedFonts](./getembeddedfonts/)() | คืนค่าแบบอักษรที่ฝังอยู่ในงานนำเสนอ |
| virtual [System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [GetFontBytes](./getfontbytes/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\>, [FontStyleType](../fontstyletype/)) | ดึงอาเรย์ไบต์ที่แสดงข้อมูลแบบอักษรสำหรับสไตล์แบบอักษรและข้อมูลแบบอักษรที่กำหนด. |
| virtual [EmbeddingLevel](../embeddinglevel/) [GetFontEmbeddingLevel](./getfontembeddinglevel/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, [System::String](../../system/string/)) | กำหนดระดับการฝังของแบบอักษรจากอาเรย์ไบต์และชื่อแบบอักษรที่ให้. |
| virtual [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\>\> [GetFonts](./getfonts/)() | คืนค่าแบบอักษรที่ใช้ในงานนำเสนอ |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | เป็นอานาล็อกจากเมธอด C# [Object.GetHashCode()](../../system/object/gethashcode/). เปิดใช้งานการแฮชของอ็อบเจ็กต์ที่กำหนดเอง. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<[System::SharedPtr](../../system/sharedptr/)\<[FontSubstitutionInfo](../fontsubstitutioninfo/)\>\>\> [GetSubstitutions](./getsubstitutions/)() | รับข้อมูลเกี่ยวกับแบบอักษรที่จะถูกแทนที่ในการเรนเดอร์ของงานนำเสนอ. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<[System::SharedPtr](../../system/sharedptr/)\<[FontSubstitutionInfo](../fontsubstitutioninfo/)\>\>\> [GetSubstitutions](./getsubstitutions/)([System::ArrayPtr](../../system/arrayptr/)\<**int32_t**\>) | รับข้อมูลเกี่ยวกับแบบอักษรที่จะถูกแทนที่ในระหว่างการเรนเดอร์ของสไลด์ที่ระบุ. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | รับประเภทจริงของวัตถุ. เป็นอานาล็อกจากการเรียก C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | ตรวจสอบว่าวัตถุเป็นอินสแตนซ์ของประเภทที่อธิบายโดย targetType หรือไม่. เป็นอานาล็อกจากตัวดำเนินการ 'is' ของ C#. |
| void [Lock](../../system/object/lock/)() | ทำงานตามคำสั่ง lock() ของ C# เพื่อทำการล็อก. เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | เป็นอานาล็อกจากเมธอด C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). เปิดใช้งานการโคลนของประเภทที่กำหนดเอง. |
|  [Object](../../system/object/object/)() | สร้างอ็อบเจ็กต์. กำหนดค่าโครงสร้างข้อมูลภายในทั้งหมด. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | คอนสตรัคเตอร์สำเนา. ไม่ทำการคัดลอกใด ๆ จริง ๆ เพียงกำหนดค่าอ็อบเจ็กต์ใหม่และเปิดใช้งานการสร้างสำเนาแบบโครงสร้างย่อย. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | ตัวดำเนินการกำหนดค่า. ไม่ทำการคัดลอกใด ๆ จริง ๆ เพียงกำหนดค่าอ็อบเจ็กต์ใหม่และเปิดใช้งานการสร้างสำเนาแบบโครงสร้างย่อย. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | เปรียบเทียบวัตถุโดยอ้างอิง. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | เปรียบเทียบวัตถุโดยอ้างอิง. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | เปรียบเทียบอ้างอิงวัตถุประเภทค่ากับ nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | เป็นการเฉพาะสำหรับ [Object::ReferenceEquals](../../system/object/referenceequals/) ในกรณีของสตริงและ nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | เป็นการเฉพาะสำหรับ [Object::ReferenceEquals](../../system/object/referenceequals/) ในกรณีของสตริงหลายตัว. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | ลดจำนวนตัวนับอ้างอิงร่วมตามค่าที่ระบุ. |
| virtual void [RemoveEmbeddedFont](./removeembeddedfont/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\>) | ลบแบบอักษรที่ฝังไว้ |
| virtual void [ReplaceFont](./replacefont/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\>, [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\>) | แทนที่แบบอักษรในงานนำเสนอ |
| virtual void [ReplaceFont](./replacefont/)([System::SharedPtr](../../system/sharedptr/)\<[IFontSubstRule](../ifontsubstrule/)\>) | แทนที่แบบอักษรในงานนำเสนอโดยใช้ข้อมูลที่ให้ใน [IFontSubstRule](../ifontsubstrule/) |
| virtual void [ReplaceFont](./replacefont/)([System::SharedPtr](../../system/sharedptr/)\<[IFontSubstRuleCollection](../ifontsubstrulecollection/)\>) | แทนที่แบบอักษรในงานนำเสนอโดยใช้ข้อมูลที่ให้ในคอลเลกชันของ [IFontSubstRule](../ifontsubstrule/) |
| virtual void [set_FontFallBackRulesCollection](./set_fontfallbackrulescollection/)([System::SharedPtr](../../system/sharedptr/)\<[IFontFallBackRulesCollection](../ifontfallbackrulescollection/)\>) | แสดงคอลเลกชันของผู้ใช้สำหรับกฎ FontFallBack เพื่อจัดการคอลเลกชันของแบบอักษรสำหรับการทดแทนที่เหมาะสมโดยฟังก์ชัน fallback เขียน [IFontFallBackRulesCollection](../ifontfallbackrulescollection/). |
| virtual void [set_FontSubstRuleList](./set_fontsubstrulelist/)([System::SharedPtr](../../system/sharedptr/)\<[IFontSubstRuleCollection](../ifontsubstrulecollection/)\>) | การทดแทนแบบอักษรที่ใช้เมื่อเรนเดอร์ เขียน [IFontSubstRuleCollection](../ifontsubstrulecollection/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | ตั้งค่าเทมเพลตอาร์กิวเมนต์ที่ n ให้เป็น weak pointer (แทนที่ shared). อนุญาตให้สลับ pointer ใน container ไปเป็นโหมด weak. |
| int [SharedCount](../../system/object/sharedcount/)() const | รับค่าปัจจุบันของตัวนับอ้างอิงร่วม. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | เพิ่มจำนวนตัวนับอ้างอิงร่วม. ไม่ควรเรียกโดยตรง; แทนที่จะใช้ smart pointer หรือ ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ลดจำนวนและคืนค่าตัวนับอ้างอิงร่วม. ไม่ควรเรียกโดยตรง; แทนที่จะใช้ smart pointer หรือ ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | เป็นอานาล็อกจากเมธอด C# [Object.ToString()](../../system/object/tostring/). เปิดใช้งานการแปลงอ็อบเจ็กต์ที่กำหนดเองเป็นสตริง. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ทำงานตามคำสั่ง typeof([System.Object](../../system/object/)) ของ C#. |
| void [Unlock](../../system/object/unlock/)() | ทำงานตามคำสั่ง lock() ของ C# เพื่อปลดล็อก. เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | เพิ่มจำนวนตัวนับอ้างอิงแบบ weak. ไม่ควรเรียกโดยตรง; แทนที่จะใช้ smart pointer หรือ ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ลดจำนวนตัวนับอ้างอิงแบบ weak. ไม่ควรเรียกโดยตรง; แทนที่จะใช้ smart pointer หรือ ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | ทำลายอ็อบเจ็กต์. ปล่อยโครงสร้างข้อมูลภายในทั้งหมด. |

## ดูเพิ่มเติม

* คลาส [Object](../../system/object/)
* เนมสเปซ [Aspose::Slides](../)
* ไลบรารี [Aspose.Slides](../../)