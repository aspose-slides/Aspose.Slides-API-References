---
title: Hyperlink
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: แสดงถึงไฮเปอร์ลิงก์.
type: docs
weight: 1236
url: /th/aspose.slides/hyperlink/
---
## คลาส Hyperlink


แสดงถึงไฮเปอร์ลิงก์.

```cpp
class Hyperlink : public Aspose::Slides::PVIObject,
                  public Aspose::Slides::IHyperlink
```

## เมธอด

| Method | คำอธิบาย |
| --- | --- |
| **bool** [Equals](./equals/)([System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) override | กำหนดว่าตัวอย่าง [Hyperlink](./) สองตัวเท่ากันหรือไม่ |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | เปรียบเทียบอ็อบเจกต์โดยใช้ semantics ของ C# [Object.Equals](../../system/object/equals/) |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบวัตถุประเภทอ้างอิงในสไตล์ C# |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | จำลองการเปรียบเทียบค่า floating point แบบ C# ที่ NaN สองค่าได้รับการพิจารณาว่าเท่ากัน แม้ว่าตาม IEC 60559:1989 NaN จะไม่เท่ากับค่าใด ๆ รวมถึง NaN ด้วย |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | จำลองการเปรียบเทียบค่า floating point แบบ C# ที่ NaN สองค่าได้รับการพิจารณาว่าเท่ากัน แม้ว่าตาม IEC 60559:1989 NaN จะไม่เท่ากับค่าใด ๆ รวมถึง NaN ด้วย |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | สำหรับการใช้งานภายในเท่านั้น |
| [HyperlinkActionType](../hyperlinkactiontype/) [get_ActionType](./get_actiontype/)() override | คืนค่าชนิดของการกระทำของ [Hyperlink](./). อ่านอย่างเดียว [HyperlinkActionType](../hyperlinkactiontype/) |
| [HyperlinkColorSource](../hyperlinkcolorsource/) [get_ColorSource](./get_colorsource/)() override | แสดงแหล่งที่มาของสีไฮเปอร์ลิงก์ - ทั้งสไตล์หรือรูปแบบส่วน. อ่าน [HyperlinkColorSource](../hyperlinkcolorsource/) |
| static [System::SharedPtr](../../system/sharedptr/)\<[Hyperlink](./)\> [get_EndShow](./get_endshow/)() | คืนค่าไฮเปอร์ลิงก์ที่สิ้นสุดการแสดง. อ่านอย่างเดียว [Hyperlink](./) |
| [System::String](../../system/string/) [get_ExternalUrl](./get_externalurl/)() override | ระบุ URL ภายนอก. อ่านอย่างเดียว [System::String](../../system/string/) |
| [System::String](../../system/string/) [get_ExternalUrlOriginal](./get_externalurloriginal/)() override | แสดงไฮเปอร์ลิงก์ที่ตั้งค่าสำหรับส่วนนี้โดยไม่คำนึงถึงเนื้อหาจริงของส่วน |
| static [System::SharedPtr](../../system/sharedptr/)\<[Hyperlink](./)\> [get_FirstSlide](./get_firstslide/)() | คืนค่าไฮเปอร์ลิงก์ไปยังสไลด์แรกของการนำเสนอ. อ่านอย่างเดียว [Hyperlink](./) |
| **bool** [get_HighlightClick](./get_highlightclick/)() override | กำหนดว่าไฮเปอร์ลิงก์ควรไฮไลท์เมื่อคลิกหรือไม่. อ่าน **bool** |
| **bool** [get_History](./get_history/)() override | กำหนดว่าเป้าหมายของไฮเปอร์ลิงก์แม่จะถูกเพิ่มในรายการไฮเปอร์ลิงก์ที่ดูแล้วเมื่อเรียกใช้หรือไม่. อ่าน **bool** |
| static [System::SharedPtr](../../system/sharedptr/)\<[Hyperlink](./)\> [get_LastSlide](./get_lastslide/)() | คืนค่าไฮเปอร์ลิงก์ไปยังสไลด์สุดท้ายของการนำเสนอ. อ่านอย่างเดียว [Hyperlink](./) |
| static [System::SharedPtr](../../system/sharedptr/)\<[Hyperlink](./)\> [get_LastVievedSlide](./get_lastvievedslide/)() | คืนค่าไฮเปอร์ลิงก์ไปยังสไลด์ที่ดูล่าสุด. อ่านอย่างเดียว [Hyperlink](./) |
| static [System::SharedPtr](../../system/sharedptr/)\<[Hyperlink](./)\> [get_Media](./get_media/)() | คืนค่าไฮเปอร์ลิงก์พิเศษ "play mediafile". ใช้ใน [AudioFrame](../audioframe/) และ [VideoFrame](../videoframe/). อ่านอย่างเดียว [Hyperlink](./) |
| static [System::SharedPtr](../../system/sharedptr/)\<[Hyperlink](./)\> [get_NextSlide](./get_nextslide/)() | คืนค่าไฮเปอร์ลิงก์ไปยังสไลด์ถัดไป. อ่านอย่างเดียว [Hyperlink](./) |
| static [System::SharedPtr](../../system/sharedptr/)\<[Hyperlink](./)\> [get_NoAction](./get_noaction/)() | คืนค่าไฮเปอร์ลิงก์พิเศษ "do nothing". อ่านอย่างเดียว [Hyperlink](./) |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IPresentationComponent](../ipresentationcomponent/)\> [get_Parent_IPresentationComponent](../ipviobject/get_parent_ipresentationcomponent/)() | คืนค่า [IPresentationComponent](../ipresentationcomponent/) พาเรนต์. อ่านอย่างเดียว [IPresentationComponent](../ipresentationcomponent/) |
| static [System::SharedPtr](../../system/sharedptr/)\<[Hyperlink](./)\> [get_PreviousSlide](./get_previousslide/)() | คืนค่าไฮเปอร์ลิงก์ไปยังสไลด์ก่อนหน้า. อ่านอย่างเดียว [Hyperlink](./) |
| [System::SharedPtr](../../system/sharedptr/)\<[IAudio](../iaudio/)\> [get_Sound](./get_sound/)() override | แสดงเสียงที่เล่นของไฮเปอร์ลิงก์. อ่าน [IAudio](../iaudio/) |
| **bool** [get_StopSoundOnClick](./get_stopsoundonclick/)() override | กำหนดว่าเสียงควรหยุดเมื่อคลิกไฮเปอร์ลิงก์หรือไม่. อ่าน **bool** |
| [System::String](../../system/string/) [get_TargetFrame](./get_targetframe/)() override | คืนค่าเฟรมภายในชุดเฟรม HTML พาเรนต์สำหรับเป้าหมายของไฮเปอร์ลิงก์แม่เมื่อมีอยู่. อ่าน/เขียน [System::String](../../system/string/) |
| [System::SharedPtr](../../system/sharedptr/)\<[ISlide](../islide/)\> [get_TargetSlide](./get_targetslide/)() override | หาก [Hyperlink](./) ชี้เป้าไปยังสไลด์เฉพาะ จะคืนค่าสไลด์นี้. อ่านอย่างเดียว [ISlide](../islide/) |
| [System::String](../../system/string/) [get_Tooltip](./get_tooltip/)() override | คืนค่าข้อความที่อาจแสดงใน UI ที่เชื่อมโยงกับไฮเปอร์ลิงก์พาเรนต์. อ่าน [System::String](../../system/string/) |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | รับโครงสร้างข้อมูลตัวนับอ้างอิงที่เกี่ยวข้องกับอ็อบเจกต์ |
| **int32_t** [GetHashCode](./gethashcode/)() const override | ทำหน้าที่เป็นฟังก์ชันแฮชสำหรับประเภทเฉพาะ เหมาะสำหรับใช้ในอัลกอริทึมแฮชและโครงสร้างข้อมูลเช่นแฮชเทเบิล |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | รับประเภทจริงของอ็อบเจกต์. คล้ายการเรียก C# [System.Object.GetType()](../../system/object/gettype/) |
| [Hyperlink](./hyperlink/)([System::String](../../system/string/)) | สร้างอินสแตนซ์ของไฮเปอร์ลิงก์ |
| [Hyperlink](./hyperlink/)([System::SharedPtr](../../system/sharedptr/)\<[ISlide](../islide/)\>) | สร้างอินสแตนซ์ของไฮเปอร์ลิงก์ที่ชี้ไปยังสไลด์เฉพาะ. หมายเหตุ: ไฮเปอร์ลิงก์ที่สร้างควรถูกกำหนดให้กับอ็อบเจกต์จากการนำเสนอเดียวกัน, มิฉะนั้นลิงก์จะบันทึกเป็น NoAction |
| [Hyperlink](./hyperlink/)([System::SharedPtr](../../system/sharedptr/)\<[Hyperlink](./)\>, [System::String](../../system/string/), [System::String](../../system/string/), **bool**, **bool**, **bool**) | สร้างอินสแตนซ์ของไฮเปอร์ลิงก์โดยใช้ไฮเปอร์ลิงก์อื่นเป็นแหล่ง, ทำการแทนที่คุณสมบัติเซกรอง |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | ตรวจสอบว่าอ็อบเจกต์เป็นอินสแตนซ์ของประเภทที่อธิบายโดย targetType. คล้ายกับตัวดำเนินการ 'is' ของ C# |
| void [Lock](../../system/object/lock/)() | ทำการล็อกตามคำสั่ง C# lock(). เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/) |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | คล้ายกับเมธอด C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). เปิดใช้งานการโคลนประเภทที่กำหนดเอง |
| [Object](../../system/object/object/)() | สร้างอ็อบเจกต์. เริ่มต้นโครงสร้างข้อมูลภายในทั้งหมด |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | คอนสตรักเตอร์สำเนา. จริง ๆ ไม่ได้คัดลอกอะไร, เพียงเริ่มต้นอ็อบเจกต์ใหม่และเปิดใช้งานการคัดลอกสร้างซับคลาส |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | โอเปอเรเตอร์การกำหนดค่า. จริง ๆ ไม่ได้คัดลอกอะไร, เพียงเริ่มต้นอ็อบเจกต์ใหม่และเปิดใช้งานการคัดลอกสร้างซับคลาส |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | เปรียบเทียบอ็อบเจกต์โดยอ้างอิง |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | เปรียบเทียบอ็อบเจกต์โดยอ้างอิง |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | เปรียบเทียบอ้างอิงวัตถุประเภทค่า กับ nullptr |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | การใช้งานพิเศษของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริงและ nullptr |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | การใช้งานพิเศษของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริง |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | ลดจำนวนอ้างอิงที่แชร์ลงตามค่าที่ระบุ |
| void [set_ColorSource](./set_colorsource/)([HyperlinkColorSource](../hyperlinkcolorsource/)) override | แสดงแหล่งที่มาของสีไฮเปอร์ลิงก์ - ทั้งสไตล์หรือรูปแบบส่วน. เขียน [HyperlinkColorSource](../hyperlinkcolorsource/) |
| void [set_HighlightClick](./set_highlightclick/)(**bool**) override | กำหนดว่าไฮเปอร์ลิงก์ควรไฮไลท์เมื่อคลิกหรือไม่. เขียน **bool** |
| void [set_History](./set_history/)(**bool**) override | กำหนดว่าเป้าหมายของไฮเปอร์ลิงก์แม่จะถูกเพิ่มในรายการไฮเปอร์ลิงก์ที่ดูแล้วเมื่อเรียกใช้หรือไม่. เขียน **bool** |
| void [set_Sound](./set_sound/)([System::SharedPtr](../../system/sharedptr/)\<[IAudio](../iaudio/)\>) override | แสดงเสียงที่เล่นของไฮเปอร์ลิงก์. เขียน [IAudio](../iaudio/) |
| void [set_StopSoundOnClick](./set_stopsoundonclick/)(**bool**) override | กำหนดว่าเสียงควรหยุดเมื่อคลิกไฮเปอร์ลิงก์หรือไม่. เขียน **bool** |
| void [set_TargetFrame](./set_targetframe/)([System::String](../../system/string/)) override | คืนค่าเฟรมภายในชุดเฟรม HTML พาเรนต์สำหรับเป้าหมายของไฮเปอร์ลิงก์แม่เมื่อมีอยู่. อ่าน/เขียน [System::String](../../system/string/) |
| void [set_Tooltip](./set_tooltip/)([System::String](../../system/string/)) override | คืนค่าข้อความที่อาจแสดงใน UI ที่เชื่อมโยงกับไฮเปอร์ลิงก์พาเรนต์. เขียน [System::String](../../system/string/) |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | ตั้งค่าอาร์กิวเมนต์เทมเพลตที่ n ให้เป็น weak pointer (แทนที่ shared). อนุญาตสลับพอยน์เตอร์ในคอนเทนเนอร์เป็นโหมด weak |
| int [SharedCount](../../system/object/sharedcount/)() const | รับค่าปัจจุบันของตัวนับอ้างอิงที่แชร์ |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | เพิ่มจำนวนอ้างอิงที่แชร์. ไม่ควรเรียกโดยตรง; ใช้ smart pointer หรือ ThisProtector แทน |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ลดจำนวนอ้างอิงที่แชร์และคืนค่า. ไม่ควรเรียกโดยตรง; ใช้ smart pointer หรือ ThisProtector แทน |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | คล้ายเมธอด C# [Object.ToString()](../../system/object/tostring/). เปิดการแปลงอ็อบเจกต์ที่กำหนดเป็นสตริง |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ทำการสร้าง C# typeof([System.Object](../../system/object/)) |
| void [Unlock](../../system/object/unlock/)() | ทำการปลดล็อกตามคำสั่ง C# lock(). เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/) |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | เพิ่มจำนวนอ้างอิงแบบ weak. ไม่ควรเรียกโดยตรง; ใช้ smart pointer หรือ ThisProtector แทน |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ลดจำนวนอ้างอิงแบบ weak. ไม่ควรเรียกโดยตรง; ใช้ smart pointer หรือ ThisProtector แทน |
| ASPOSE_SLIDES_LOCAL_API void [WrapperLazyInitialization](../pviobject/wrapperlazyinitialization/)() const |  |
| virtual  [~Object](../../system/object/~object/)() | ทำลายอ็อบเจกต์. ปล่อยโครงสร้างข้อมูลภายในทั้งหมด |

## ดูเพิ่มเติม

* คลาส [PVIObject](../pviobject/)
* คลาส [IHyperlink](../ihyperlink/)
* เนมสเปซ [Aspose::Slides](../)
* ไลบรารี [Aspose.Slides](../../)