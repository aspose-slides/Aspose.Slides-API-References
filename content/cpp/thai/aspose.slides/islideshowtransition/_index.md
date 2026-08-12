---
title: ISlideShowTransition
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: เป็นตัวแทนของการเปลี่ยนสไลด์โชว์.
type: docs
weight: 3810
url: /th/aspose.slides/islideshowtransition/
---
## ISlideShowTransition คลาส


Represents slide show transition.

```cpp
class ISlideShowTransition : public virtual System::Object
```

## เมธอด

| Method | คำอธิบาย |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | เปรียบเทียบอ็อบเจ็กต์โดยใช้ความหมายของ C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจ็กต์ประเภทอ้างอิงในสไตล์ C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจ็กต์ประเภทค่าในสไตล์ C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | จำลองการเปรียบเทียบจุดลอยตามสไตล์ C# ที่ NaN สองค่าถือว่าเท่ากันแม้ว่าตาม IEC 60559:1989 NaN ไม่เท่ากับค่าใด ๆ รวมถึง NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | จำลองการเปรียบเทียบจุดลอยตามสไตล์ C# ที่ NaN สองค่าถือว่าเท่ากันแม้ว่าตาม IEC 60559:1989 NaN ไม่เท่ากับค่าใด ๆ รวมถึง NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | เพื่อใช้ภายในเท่านั้น. |
| virtual **bool** [get_AdvanceAfter](./get_advanceafter/)() | แอตทริบิวต์นี้ระบุว่าการแสดงสไลด์จะย้ายไปสไลด์ถัดไปหลังจากระยะเวลาใดเวลาหนึ่งหรือไม่. อ่าน **bool**. |
| virtual **uint32_t** [get_AdvanceAfterTime](./get_advanceaftertime/)() | ระบุเวลาเป็นมิลลิวินาทีที่การเปลี่ยนจะเริ่มต้น การตั้งค่านี้อาจใช้ร่วมกับแอตทริบิวต์ advClick หากแอตทริบิวต์นี้ไม่ได้ระบุ จะถือว่าไม่มีการเลื่อนอัตโนมัติ. อ่าน **uint32_t**. |
| virtual **bool** [get_AdvanceOnClick](./get_advanceonclick/)() | ระบุว่าการคลิกเมาส์จะเลื่อนสไลด์หรือไม่ หากแอตทริบิวต์นี้ไม่ได้ระบุ จะถือค่าจริง. อ่าน **bool**. |
| virtual **int32_t** [get_Duration](./get_duration/)() | รับระยะเวลาเอฟเฟกต์การเปลี่ยนสไลด์เป็นมิลลิวินาที. อ่าน **int32_t**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IAudio](../iaudio/)\> [get_Sound](./get_sound/)() | คืนค่าข้อมูลเสียงที่ฝังไว้. อ่าน [IAudio](../iaudio/). |
| virtual **bool** [get_SoundIsBuiltIn](./get_soundisbuiltin/)() | ระบุว่าเสียงนี้เป็นเสียงในตัวหรือไม่ หากตั้งค่าเป็น true แอปพลิเคชันที่สร้างจะตรวจสอบแอตทริบิวต์ name ของเสียงนี้ในรายการเสียงในตัวและอาจแสดงชื่อหรือ UI ที่กำหนดเองตามต้องการ. อ่าน **bool**. |
| virtual **bool** [get_SoundLoop](./get_soundloop/)() | แอตทริบิวต์นี้ระบุว่าเสียงจะลูปจนกว่าจะเกิดเหตุการณ์เสียงถัดไปในสไลด์โชว์. อ่าน **bool**. |
| virtual [SlideShow::TransitionSoundMode](../../aspose.slides.slideshow/transitionsoundmode/) [get_SoundMode](./get_soundmode/)() | ตั้งค่าหรือคืนค่าโหมดเสียงสำหรับการเปลี่ยนสไลด์. อ่าน [TransitionSoundMode](../../aspose.slides.slideshow/transitionsoundmode/). |
| virtual [System::String](../../system/string/) [get_SoundName](./get_soundname/)() | ระบุชื่อที่มนุษย์อ่านได้สำหรับเสียงของการเปลี่ยน. ต้องกำหนดค่า [ISlideShowTransition::set_Sound](./set_sound/) เพื่อรับหรือกำหนดชื่อเสียง. อ่าน [System::String](../../system/string/). |
| virtual [SlideShow::TransitionSpeed](../../aspose.slides.slideshow/transitionspeed/) [get_Speed](./get_speed/)() | ระบุความเร็วของการเปลี่ยนที่ใช้เมื่อเปลี่ยนจากสไลด์ปัจจุบันไปยังสไลด์ถัดไป. อ่าน [TransitionSpeed](../../aspose.slides.slideshow/transitionspeed/). |
| virtual [SlideShow::TransitionType](../../aspose.slides.slideshow/transitiontype/) [get_Type](./get_type/)() | ประเภทของการเปลี่ยน. อ่าน [TransitionType](../../aspose.slides.slideshow/transitiontype/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[SlideShow::ITransitionValueBase](../../aspose.slides.slideshow/itransitionvaluebase/)\> [get_Value](./get_value/)() | [Slide](../slide/) แสดงค่าการเปลี่ยนสไลด์. อ่านอย่างเดียว [SlideShow::ITransitionValueBase](../../aspose.slides.slideshow/itransitionvaluebase/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | รับโครงสร้างข้อมูลตัวนับอ้างอิงที่เชื่อมโยงกับอ็อบเจ็กต์. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog of C# [Object.GetHashCode()](../../system/object/gethashcode/) method. Enables hashing of custom objects. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | รับประเภทจริงของอ็อบเจ็กต์. Analog of C# [System.Object.GetType()](../../system/object/gettype/) call. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | ตรวจสอบว่าอ็อบเจ็กต์เป็นอินสแตนซ์ของประเภทที่อธิบายโดย targetType หรือไม่. Analog of C# 'is' operator. |
| void [Lock](../../system/object/lock/)() | Implements C# lock() statement locking. Call directly or use [LockContext](../../system/lockcontext/) sentry object. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog of C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) method. Enables cloning custom types. |
|  [Object](../../system/object/object/)() | สร้างอ็อบเจ็กต์. เริ่มต้นโครงสร้างข้อมูลภายในทั้งหมด. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | ตัวสร้างสำเนา. ไม่ได้คัดลอกอะไรจริง ๆ แต่เพียงเริ่มต้นอ็อบเจ็กต์ใหม่และเปิดใช้งานการสร้างสำเนาสำหรับคลาสย่อย. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | ตัวดำเนินการกำหนดค่า. ไม่ได้คัดลอกอะไรจริง ๆ แต่เพียงเริ่มต้นอ็อบเจ็กต์ใหม่และเปิดใช้งานการสร้างสำเนาสำหรับคลาสย่อย. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | เปรียบเทียบอ็อบเจ็กต์โดยอ้างอิง. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | เปรียบเทียบอ็อบเจ็กต์โดยอ้างอิง. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | เปรียบเทียบอ้างอิงอ็อบเจ็กต์ประเภทค่ากับ nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | การทำพิเศษของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริงและ nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | การทำพิเศษของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริง. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | ลดค่าตัวนับอ้างอิงที่แชร์โดยค่าที่ระบุ. |
| virtual void [set_AdvanceAfter](./set_advanceafter/)(**bool**) | แอตทริบิวต์นี้ระบุว่าการแสดงสไลด์จะย้ายไปสไลด์ถัดไปหลังจากระยะเวลาใดเวลาหนึ่งหรือไม่. เขียน **bool**. |
| virtual void [set_AdvanceAfterTime](./set_advanceaftertime/)(**uint32_t**) | ระบุเวลาเป็นมิลลิวินาทีที่การเปลี่ยนจะเริ่มต้น การตั้งค่านี้อาจใช้ร่วมกับแอตทริบิวต์ advClick หากแอตทริบิวต์นี้ไม่ได้ระบุ จะถือว่าไม่มีการเลื่อนอัตโนมัติ. เขียน **uint32_t**. |
| virtual void [set_AdvanceOnClick](./set_advanceonclick/)(**bool**) | ระบุว่าการคลิกเมาส์จะเลื่อนสไลด์หรือไม่ หากแอตทริบิวต์นี้ไม่ได้ระบุ จะถือค่าจริง. เขียน **bool**. |
| virtual void [set_Duration](./set_duration/)(**int32_t**) | ตั้งระยะเวลาเอฟเฟกต์การเปลี่ยนสไลด์เป็นมิลลิวินาที. เขียน **int32_t**. |
| virtual void [set_Sound](./set_sound/)([System::SharedPtr](../../system/sharedptr/)\<[IAudio](../iaudio/)\>) | ตั้งค่าข้อมูลเสียงที่ฝังไว้. เขียน [IAudio](../iaudio/). |
| virtual void [set_SoundIsBuiltIn](./set_soundisbuiltin/)(**bool**) | ระบุว่าเสียงนี้เป็นเสียงในตัวหรือไม่ หากตั้งค่าเป็น true แอปพลิเคชันที่สร้างจะตรวจสอบแอตทริบิวต์ name ของเสียงนี้ในรายการเสียงในตัวและอาจแสดงชื่อหรือ UI ที่กำหนดเองตามต้องการ. เขียน **bool**. |
| virtual void [set_SoundLoop](./set_soundloop/)(**bool**) | แอตทริบิวต์นี้ระบุว่าเสียงจะลูปจนกว่าจะเกิดเหตุการณ์เสียงถัดไปในสไลด์โชว์. เขียน **bool**. |
| virtual void [set_SoundMode](./set_soundmode/)([SlideShow::TransitionSoundMode](../../aspose.slides.slideshow/transitionsoundmode/)) | ตั้งค่าหรือคืนค่าโหมดเสียงสำหรับการเปลี่ยนสไลด์. เขียน [TransitionSoundMode](../../aspose.slides.slideshow/transitionsoundmode/). |
| virtual void [set_SoundName](./set_soundname/)([System::String](../../system/string/)) | ระบุชื่อที่มนุษย์อ่านได้สำหรับเสียงของการเปลี่ยน. ต้องกำหนดค่า [ISlideShowTransition::set_Sound](./set_sound/) เพื่อรับหรือกำหนดชื่อเสียง. เขียน [System::String](../../system/string/). |
| virtual void [set_Speed](./set_speed/)([SlideShow::TransitionSpeed](../../aspose.slides.slideshow/transitionspeed/)) | ระบุความเร็วของการเปลี่ยนที่ใช้เมื่อเปลี่ยนจากสไลด์ปัจจุบันไปยังสไลด์ถัดไป. เขียน [TransitionSpeed](../../aspose.slides.slideshow/transitionspeed/). |
| virtual void [set_Type](./set_type/)([SlideShow::TransitionType](../../aspose.slides.slideshow/transitiontype/)) | ประเภทของการเปลี่ยน. เขียน [TransitionType](../../aspose.slides.slideshow/transitiontype/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | ตั้งค่าเทมเพลตอาร์กิวเมนต์ที่ n ให้เป็น weak pointer (แทน shared). อนุญาตให้สลับพอยน์เตอร์ในคอนเทนเนอร์เป็นโหมด weak. |
| int [SharedCount](../../system/object/sharedcount/)() const | รับค่าปัจจุบันของตัวนับอ้างอิงที่แชร์. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | เพิ่มตัวนับอ้างอิงที่แชร์. ไม่ควรเรียกโดยตรง; ใช้ smart pointers หรือ ThisProtector แทน. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ลดและคืนค่าตัวนับอ้างอิงที่แชร์. ไม่ควรเรียกโดยตรง; ใช้ smart pointers หรือ ThisProtector แทน. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog of C# [Object.ToString()](../../system/object/tostring/) method. Enables converting custom objects to string. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implements C# typeof([System.Object](../../system/object/)) construct. |
| void [Unlock](../../system/object/unlock/)() | Implements C# lock() statement unlocking. Call directly or use [LockContext](../../system/lockcontext/) sentry object. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | เพิ่มตัวนับอ้างอิงแบบ weak. ไม่ควรเรียกโดยตรง; ใช้ smart pointers หรือ ThisProtector แทน. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ลดตัวนับอ้างอิงแบบ weak. ไม่ควรเรียกโดยตรง; ใช้ smart pointers หรือ ThisProtector แทน. |
| virtual  [~Object](../../system/object/~object/)() | ทำลายอ็อบเจ็กต์. ปลดปล่อยโครงสร้างข้อมูลภายในทั้งหมด. |
## ดูเพิ่มเติม

* คลาส [Object](../../system/object/)
* เนมสเปซ [Aspose::Slides](../)
* ไลบรารี [Aspose.Slides](../../)