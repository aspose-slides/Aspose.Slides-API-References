---
title: IEffectFormatEffectiveData
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: อ็อบเจ็กต์ที่ไม่เปลี่ยนแปลงซึ่งมีคุณสมบัติการจัดรูปแบบเอฟเฟกต์ที่มีผล.
type: docs
weight: 2042
url: /th/aspose.slides/ieffectformateffectivedata/
---
## IEffectFormatEffectiveData คลาส


อ็อบเจ็กต์ที่ไม่เปลี่ยนแปลงซึ่งประกอบด้วยคุณสมบัติการจัดรูปแบบเอฟเฟกต์ที่มีผล

```cpp
class IEffectFormatEffectiveData : public Aspose::Slides::IEffectParamSource
```

## เมธอด

| Method | Description |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | เปรียบเทียบอ็อบเจ็กต์โดยใช้เซมานติกของ C# [Object.Equals](../../system/object/equals/) |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจ็กต์ประเภทอ้างอิงในสไตล์ C# |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจ็กต์ประเภทค่าในสไตล์ C# |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | จำลองการเปรียบเทียบเลขทศนิยมสไตล์ C# ซึ่ง NaN สองค่าถูกมองว่าเท่ากันแม้ว่า ตามมาตรฐาน IEC 60559:1989 NaN ไม่เท่ากับค่าใดๆ รวมถึง NaN ด้วย |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | จำลองการเปรียบเทียบเลขทศนิยมสองเท่าสไตล์ C# ซึ่ง NaN สองค่าถูกมองว่าเท่ากันแม้ว่า ตามมาตรฐาน IEC 60559:1989 NaN ไม่เท่ากับค่าใดๆ รวมถึง NaN ด้วย |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | สำหรับการใช้ภายในเท่านั้น |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[Effects::IBlurEffectiveData](../../aspose.slides.effects/iblureffectivedata/)\> [get_BlurEffect](./get_blureffect/)() | เอฟเฟกต์เบลอ. อ่านอย่างเดียว [Effects::IBlurEffectiveData](../../aspose.slides.effects/iblureffectivedata/) |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[Effects::IFillOverlayEffectiveData](../../aspose.slides.effects/ifilloverlayeffectivedata/)\> [get_FillOverlayEffect](./get_filloverlayeffect/)() | เอฟเฟกต์เติมการซ้อนทับ. อ่านอย่างเดียว [Effects::IFillOverlayEffectiveData](../../aspose.slides.effects/ifilloverlayeffectivedata/) |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[Effects::IGlowEffectiveData](../../aspose.slides.effects/igloweffectivedata/)\> [get_GlowEffect](./get_gloweffect/)() | เอฟเฟกต์แสงเรืองแสง. อ่านอย่างเดียว [Effects::IGlowEffectiveData](../../aspose.slides.effects/igloweffectivedata/) |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[Effects::IInnerShadowEffectiveData](../../aspose.slides.effects/iinnershadoweffectivedata/)\> [get_InnerShadowEffect](./get_innershadoweffect/)() | เงาภายใน. อ่านอย่างเดียว [Effects::IInnerShadowEffectiveData](../../aspose.slides.effects/iinnershadoweffectivedata/) |
| virtual **bool** [get_IsNoEffects](./get_isnoeffects/)() | คืนค่า true หากเอฟเฟกต์ทั้งหมดถูกปิดใช้งาน (เช่น เพิ่งสร้าง, วัตถุเริ่มต้น [EffectFormat](../effectformat/)). อ่านอย่างเดียว **bool** |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[Effects::IOuterShadowEffectiveData](../../aspose.slides.effects/ioutershadoweffectivedata/)\> [get_OuterShadowEffect](./get_outershadoweffect/)() | เงานอก. อ่านอย่างเดียว [Effects::IOuterShadowEffectiveData](../../aspose.slides.effects/ioutershadoweffectivedata/) |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[Effects::IPresetShadowEffectiveData](../../aspose.slides.effects/ipresetshadoweffectivedata/)\> [get_PresetShadowEffect](./get_presetshadoweffect/)() | เงาที่กำหนดไว้ล่วงหน้า. อ่านอย่างเดียว [Effects::IPresetShadowEffectiveData](../../aspose.slides.effects/ipresetshadoweffectivedata/) |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[Effects::IReflectionEffectiveData](../../aspose.slides.effects/ireflectioneffectivedata/)\> [get_ReflectionEffect](./get_reflectioneffect/)() | การสะท้อน. อ่านอย่างเดียว [Effects::IReflectionEffectiveData](../../aspose.slides.effects/ireflectioneffectivedata/) |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[Effects::ISoftEdgeEffectiveData](../../aspose.slides.effects/isoftedgeeffectivedata/)\> [get_SoftEdgeEffect](./get_softedgeeffect/)() | ขอบอ่อน. อ่านอย่างเดียว [Effects::ISoftEdgeEffectiveData](../../aspose.slides.effects/isoftedgeeffectivedata/) |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | รับโครงสร้างข้อมูลตัวนับอ้างอิงที่เชื่อมโยงกับอ็อบเจ็กต์ |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | ฟังก์ชันที่คล้ายกับเมธอด C# [Object.GetHashCode()](../../system/object/gethashcode/). ทำให้สามารถแฮชอ็อบเจ็กต์ที่กำหนดเองได้ |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | รับประเภทจริงของอ็อบเจ็กต์. ฟังก์ชันที่คล้ายกับการเรียก C# [System.Object.GetType()](../../system/object/gettype/) |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | ตรวจสอบว่าอ็อบเจ็กต์เป็นอินสแตนซ์ของประเภทที่อธิบายโดย targetType. ฟังก์ชันที่คล้ายกับตัวดำเนินการ 'is' ของ C# |
| void [Lock](../../system/object/lock/)() | ทำงานตามคำสั่ง lock() ของ C# เพื่อล็อก. เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/) |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | ฟังก์ชันที่คล้ายกับเมธอด C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). ทำให้สามารถคล cloning ประเภทที่กำหนดเองได้ |
|  [Object](../../system/object/object/)() | สร้างอ็อบเจ็กต์. เริ่มต้นโครงสร้างข้อมูลภายในทั้งหมด |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | คอนสตรัคเตอร์คัดลอก. จริงๆ แล้วไม่ได้คัดลอกอะไรเลย เพียงเริ่มต้นอ็อบเจ็กต์ใหม่และทำให้สามารถคัดลอกสร้างซับคลาสได้ |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | อ็อพเรเตอร์การมอบหมายค่า. จริงๆ แล้วไม่ได้คัดลอกอะไรเลย เพียงเริ่มต้นอ็อบเจ็กต์ใหม่และทำให้สามารถคัดลอกสร้างซับคลาสได้ |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | เปรียบเทียบอ็อบเจ็กต์โดยอ้างอิง |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | เปรียบเทียบอ็อบเจ็กต์โดยอ้างอิง |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | เปรียบเทียบอ้างอิงอ็อบเจ็กต์ประเภทค่ากับ nullptr |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | การจำเพาะของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริงและ nullptr |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | การจำเพาะของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริง |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | ลดจำนวนการอ้างอิงร่วมตามค่าที่ระบุ |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | ตั้งค่าอาร์กิวเมนต์เทมเพลตที่ n เป็น weak pointer (แทน shared). ทำให้สามารถสลับพอยน์เตอร์ในคอนเทนเนอร์เป็นโหมด weak ได้ |
| int [SharedCount](../../system/object/sharedcount/)() const | รับค่าปัจจุบันของตัวนับการอ้างอิงร่วม |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | เพิ่มจำนวนการอ้างอิงร่วม. ไม่ควรเรียกโดยตรง; ควรใช้ smart pointer หรือ ThisProtector |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ลดจำนวนการอ้างอิงร่วมและคืนค่า. ไม่ควรเรียกโดยตรง; ควรใช้ smart pointer หรือ ThisProtector |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | ฟังก์ชันที่คล้ายกับเมธอด C# [Object.ToString()](../../system/object/tostring/). ทำให้สามารถแปลงอ็อบเจ็กต์ที่กำหนดเองเป็นสตริงได้ |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ทำงานตามโครงสร้าง C# typeof([System.Object](../../system/object/)) |
| void [Unlock](../../system/object/unlock/)() | ทำงานตามคำสั่ง lock() ของ C# เพื่อปลดล็อก. เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/) |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | เพิ่มจำนวนการอ้างอิงแบบ weak. ไม่ควรเรียกโดยตรง; ควรใช้ smart pointer หรือ ThisProtector |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ลดจำนวนการอ้างอิงแบบ weak. ไม่ควรเรียกโดยตรง; ควรใช้ smart pointer หรือ ThisProtector |
| virtual  [~Object](../../system/object/~object/)() | ทำลายอ็อบเจ็กต์. ปลดปล่อยโครงสร้างข้อมูลภายในทั้งหมด |

## หมายเหตุ

อินเทอร์เฟซนี้ใช้ร่วมกับอินเทอร์เฟซ [IEffectFormat](../ieffectformat/) เพื่อส่งค่าการจัดรูปแบบที่มีผลโดยใช้การสืบทอด

## ดูเพิ่มเติม

* คลาส [IEffectParamSource](../ieffectparamsource/)
* เนมสเปซ [Aspose::Slides](../)
* ไลบรารี [Aspose.Slides](../../)