---
title: SlideShowTransition
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: แสดงถึงการเปลี่ยนสไลด์โชว์.
type: docs
weight: 404
url: /th/aspose.slides.slideshow/slideshowtransition/
---
## SlideShowTransition คลาส

แสดงถึงการเปลี่ยนสไลด์โชว์

```cpp
class SlideShowTransition : public Aspose::Slides::DomObject<System::SharedPtr<Aspose::Slides::BaseSlide>>,
                            public Aspose::Slides::ISlideShowTransition
```

## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| **bool** [Equals](./equals/)([System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) override | กำหนดว่าตัวอย่าง [SlideShowTransition](./) สองอินสแตนซ์เท่ากันหรือไม่. อ่าน/เขียน **bool**. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | เปรียบเทียบอ็อบเจกต์โดยใช้ความหมายของ C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจกต์ประเภทอ้างอิงในสไตล์ C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | จำลองการเปรียบเทียบจุดลอยแบบ C# ที่ NaN สองค่าเท่ากัน แม้ว่าตาม IEC 60559:1989 NaN ไม่เท่ากับค่าใด ๆ รวมถึง NaN ด้วย. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | จำลองการเปรียบเทียบจุดลอยแบบ C# ที่ NaN สองค่าเท่ากัน แม้ว่าตาม IEC 60559:1989 NaN ไม่เท่ากับค่าใด ๆ รวมถึง NaN ด้วย. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | สำหรับการใช้งานภายในเท่านั้น. |
| **bool** [get_AdvanceAfter](./get_advanceafter/)() override | แอตทริบิวต์นี้ระบุว่าการแสดงสไลด์จะย้ายไปสไลด์ต่อไปหลังจากเวลาที่กำหนดหรือไม่. อ่าน **bool**. |
| **uint32_t** [get_AdvanceAfterTime](./get_advanceaftertime/)() override | ระบุเวลาเป็นมิลลิวินาทีหลังจากนั้นการเปลี่ยนสไลด์จะเริ่ม. การตั้งค่านี้อาจใช้ร่วมกับแอตทริบิวต์ advClick. หากไม่ได้ระบุแอตทริบิวต์นี้ จะถือว่าไม่มีการเลื่อนอัตโนมัติ. อ่าน **uint32_t**. |
| **bool** [get_AdvanceOnClick](./get_advanceonclick/)() override | ระบุว่าการคลิกเมาส์จะเลื่อนสไลด์ต่อหรือไม่. หากไม่ได้ระบุ จะสันนิษฐานว่าค่าจริง. อ่าน **bool**. |
| **int32_t** [get_Duration](./get_duration/)() override | รับระยะเวลาของเอฟเฟ็กต์การเปลี่ยนสไลด์เป็นมิลลิวินาที. อ่าน **int32_t**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IAudio](../../aspose.slides/iaudio/)\> [get_Sound](./get_sound/)() override | คืนค่าข้อมูลเสียงที่ฝังอยู่. อ่าน [IAudio](../../aspose.slides/iaudio/). |
| **bool** [get_SoundIsBuiltIn](./get_soundisbuiltin/)() override | ระบุว่าเสียงนี้เป็นเสียงในตัวหรือไม่. หากแอตทริบิวต์นี้ตั้งค่าเป็น true แอปพลิเคชันที่สร้างจะได้รับการแจ้งให้ตรวจสอบแอตทริบิวต์ name ที่ระบุสำหรับเสียงนี้ในรายการเสียงในตัวและสามารถแสดงชื่อหรือ UI ที่กำหนดเองได้ตามต้องการ. อ่าน **bool**. |
| **bool** [get_SoundLoop](./get_soundloop/)() override | แอตทริบิวต์นี้ระบุว่าเสียงจะวนซ้ำจนกว่าจะเกิดเหตุการณ์เสียงถัดไปในสไลด์โชว์. อ่าน **bool**. |
| [TransitionSoundMode](../transitionsoundmode/) [get_SoundMode](./get_soundmode/)() override | ตั้งค่าหรือคืนค่าโหมดเสียงสำหรับการเปลี่ยนสไลด์. อ่าน [TransitionSoundMode](../transitionsoundmode/). |
| [System::String](../../system/string/) [get_SoundName](./get_soundname/)() override | ระบุชื่อที่อ่านเข้าใจได้สำหรับเสียงของการเปลี่ยน. ต้องกำหนด [ISlideShowTransition::set_Sound](../../aspose.slides/islideshowtransition/set_sound/) เพื่อรับหรือกำหนดชื่อเสียง. อ่าน [System::String](../../system/string/). |
| [TransitionSpeed](../transitionspeed/) [get_Speed](./get_speed/)() override | ระบุความเร็วของการเปลี่ยนที่จะใช้เมื่อเปลี่ยนจากสไลด์ปัจจุบันไปยังสไลด์ต่อไป. อ่าน [TransitionSpeed](../transitionspeed/). |
| [TransitionType](../transitiontype/) [get_Type](./get_type/)() override | ประเภทของการเปลี่ยน. อ่าน [TransitionType](../transitiontype/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ITransitionValueBase](../itransitionvaluebase/)\> [get_Value](./get_value/)() override | [Slide](../../aspose.slides/slide/) ค่าการแสดงการเปลี่ยน. อ่านอย่างเดียว [ITransitionValueBase](../itransitionvaluebase/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | รับโครงสร้างข้อมูลตัวนับอ้างอิงที่เกี่ยวข้องกับอ็อบเจกต์. |
| **int32_t** [GetHashCode](./gethashcode/)() const override | ทำหน้าที่เป็นฟังก์ชันแฮชสำหรับประเภทเฉพาะ, เหมาะสำหรับการใช้งานในอัลกอริทึมแฮชและโครงสร้างข้อมูลเช่นตารางแฮช. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | รับประเภทจริงของอ็อบเจกต์. คล้ายการเรียก C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | ตรวจสอบว่าอ็อบเจกต์เป็นอินสแตนซ์ของประเภทที่อธิบายโดย targetType หรือไม่. คล้ายกับตัวดำเนินการ 'is' ของ C#. |
| void [Lock](../../system/object/lock/)() | ทำงานตามคำสั่ง lock() ของ C# เพื่อทำล๊อค. เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | คล้ายเมธอด C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). ทำให้สามารถโคลนประเภทที่กำหนดเองได้. |
| [Object](../../system/object/object/)() | สร้างอ็อบเจกต์. เริ่มต้นโครงสร้างข้อมูลภายในทั้งหมด. |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | คอนสตรัคเตอร์คัดลอก. จริง ๆ แล้วไม่ได้คัดลอ้อะไร, เพียงเริ่มต้นอ็อบเจกต์ใหม่และเปิดใช้งานการคัดลอกสร้างซับคลาส. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | โอเปอเรเตอร์การกำหนดค่า. จริง ๆ แล้วไม่ได้คัดลอ้อะไร, เพียงเริ่มต้นอ็อบเจกต์ใหม่และเปิดใช้งานการคัดลอกสร้างซับคลาส. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | เปรียบเทียบอ็อบเจกต์โดยอ้างอิง. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | เปรียบเทียบอ็อบเจกต์โดยอ้างอิง. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | เปรียบเทียบอ้างอิงออบเจกต์ประเภทค่า กับ nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | การเฉพาะเจาะจงของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณี string และ nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | การเฉพาะเจาะจงของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของ strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | ลดจำนวนการอ้างอิงที่แชร์ลงโดยค่าที่ระบุ. |
| void [set_AdvanceAfter](./set_advanceafter/)(**bool**) override | แอตทริบิวต์นี้ระบุว่าการแสดงสไลด์จะย้ายไปสไลด์ต่อไปหลังจากเวลาที่กำหนดหรือไม่. เขียน **bool**. |
| void [set_AdvanceAfterTime](./set_advanceaftertime/)(**uint32_t**) override | ระบุเวลาเป็นมิลลิวินาทีหลังจากนั้นการเปลี่ยนสไลด์จะเริ่ม. การตั้งค่านี้อาจใช้ร่วมกับแอตทริบิวต์ advClick. หากไม่ได้ระบุแอตทริบิวต์นี้ จะถือว่าไม่มีการเลื่อนอัตโนมัติ. เขียน **uint32_t**. |
| void [set_AdvanceOnClick](./set_advanceonclick/)(**bool**) override | ระบุว่าการคลิกเมาส์จะเลื่อนสไลด์ต่อหรือไม่. หากไม่ได้ระบุ จะสันนิษฐานว่าค่าจริง. เขียน **bool**. |
| void [set_Duration](./set_duration/)(**int32_t**) override | ตั้งค่าระยะเวลาของเอฟเฟ็กต์การเปลี่ยนสไลด์เป็นมิลลิวินาที. เขียน **int32_t**. |
| void [set_Sound](./set_sound/)([System::SharedPtr](../../system/sharedptr/)\<[IAudio](../../aspose.slides/iaudio/)\>) override | ตั้งค่าข้อมูลเสียงที่ฝังอยู่. เขียน [IAudio](../../aspose.slides/iaudio/). |
| void [set_SoundIsBuiltIn](./set_soundisbuiltin/)(**bool**) override | ระบุว่าเสียงนี้เป็นเสียงในตัวหรือไม่. หากแอตทริบิวต์นี้ตั้งค่าเป็น true แอปพลิเคชันที่สร้างจะได้รับการแจ้งให้ตรวจสอบแอตทริบิวต์ name ที่ระบุสำหรับเสียงนี้ในรายการเสียงในตัวและสามารถแสดงชื่อหรือ UI ที่กำหนดเองได้ตามต้องการ. เขียน **bool**. |
| void [set_SoundLoop](./set_soundloop/)(**bool**) override | แอตทริบิวต์นี้ระบุว่าเสียงจะวนซ้ำจนกว่าจะเกิดเหตุการณ์เสียงถัดไปในสไลด์โชว์. เขียน **bool**. |
| void [set_SoundMode](./set_soundmode/)([TransitionSoundMode](../transitionsoundmode/)) override | ตั้งค่าหรือคืนค่าโหมดเสียงสำหรับการเปลี่ยนสไลด์. เขียน [TransitionSoundMode](../transitionsoundmode/). |
| void [set_SoundName](./set_soundname/)([System::String](../../system/string/)) override | ระบุชื่อที่อ่านเข้าใจได้สำหรับเสียงของการเปลี่ยน. ต้องกำหนด [ISlideShowTransition::set_Sound](../../aspose.slides/islideshowtransition/set_sound/) เพื่อรับหรือกำหนดชื่อเสียง. เขียน [System::String](../../system/string/). |
| void [set_Speed](./set_speed/)([TransitionSpeed](../transitionspeed/)) override | ระบุความเร็วของการเปลี่ยนที่จะใช้เมื่อเปลี่ยนจากสไลด์ปัจจุบันไปสไลด์ต่อไป. เขียน [TransitionSpeed](../transitionspeed/). |
| void [set_Type](./set_type/)([TransitionType](../transitiontype/)) override | ประเภทของการเปลี่ยน. เขียน [TransitionType](../transitiontype/). |
| void [SetTemplateWeakPtr](./settemplateweakptr/)(**uint32_t**) override | ตั้งค่าเทมเพลตอาร์กิวเมนต์ที่ n ให้เป็น weak pointer (แทน shared). อนุญาตให้สลับ pointer ในคอนเทนเนอร์เป็นโหมด weak. |
| int [SharedCount](../../system/object/sharedcount/)() const | รับค่าปัจจุบันของตัวนับการอ้างอิงที่แชร์. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | เพิ่มจำนวนการอ้างอิงที่แชร์. ไม่ควรเรียกโดยตรง; ใช้ smart pointers หรือ ThisProtector แทน. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ลดและคืนค่าตัวนับการอ้างอิงที่แชร์. ไม่ควรเรียกโดยตรง; ใช้ smart pointers หรือ ThisProtector แทน. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | คล้ายเมธอด C# [Object.ToString()](../../system/object/tostring/). ทำให้สามารถแปลงอ็อบเจกต์ที่กำหนดเองเป็นสตริงได้. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ทำงานตามคอนสตรัคต์ C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | ทำงานตามคำสั่ง lock() ของ C# เพื่อปลดล็อค. เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | เพิ่มจำนวนการอ้างอิงแบบ weak. ไม่ควรเรียกโดยตรง; ใช้ smart pointers หรือ ThisProtector แทน. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ลดจำนวนการอ้างอิงแบบ weak. ไม่ควรเรียกโดยตรง; ใช้ smart pointers หรือ ThisProtector แทน. |
| virtual [~Object](../../system/object/~object/)() | ทำลายอ็อบเจกต์. ปล่อยโครงสร้างข้อมูลภายในทั้งหมด. |

## ดูเพิ่มเติม

* คลาส [DomObject](../../aspose.slides/domobject/)
* คลาส [ISlideShowTransition](../../aspose.slides/islideshowtransition/)
* เนมสเปซ [Aspose::Slides::SlideShow](../)
* ไลบรารี [Aspose.Slides](../../)