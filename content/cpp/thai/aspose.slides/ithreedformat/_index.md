---
title: IThreeDFormat
second_title: การอ้างอิง API ของ Aspose.Slides สำหรับ C++
description: แสดงคุณสมบัติ 3-D.
type: docs
weight: 4161
url: /th/aspose.slides/ithreedformat/
---
## IThreeDFormat คลาส

แสดงคุณสมบัติ 3-D.

```cpp
class IThreeDFormat : public Aspose::Slides::IThreeDParamSource
```

## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | เปรียบเทียบอ็อบเจกต์โดยใช้แนวคิดของ C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจกต์ประเภทอ้างอิงในสไตล์ C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจกต์ประเภทค่าในสไตล์ C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | จำลองการเปรียบเทียบค่า floating point แบบ C# ที่ NaN สองค่าถือเท่ากันแม้ว่าตามมาตรฐาน IEC 60559:1989 NaN ไม่เท่ากับค่าใดๆ รวมถึง NaN ด้วย. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | จำลองการเปรียบเทียบค่า floating point แบบ C# ที่ NaN สองค่าถือเท่ากันแม้ว่าตามมาตรฐาน IEC 60559:1989 NaN ไม่เท่ากับค่าใดๆ รวมถึง NaN ด้วย. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | สำหรับการใช้ภายในเท่านั้น. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShapeBevel](../ishapebevel/)\> [get_BevelBottom](./get_bevelbottom/)() | ส่งคืนประเภทของ bevel ด้านล่าง 3D. อ่านอย่างเดียว [IShapeBevel](../ishapebevel/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShapeBevel](../ishapebevel/)\> [get_BevelTop](./get_beveltop/)() | ส่งคืนประเภทของ bevel ด้านบน 3D. อ่านอย่างเดียว [IShapeBevel](../ishapebevel/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ICamera](../icamera/)\> [get_Camera](./get_camera/)() | ส่งคืนการตั้งค่าของกล้อง. อ่านอย่างเดียว [ICamera](../icamera/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IColorFormat](../icolorformat/)\> [get_ContourColor](./get_contourcolor/)() | ส่งคืนสีของคอนทัวร์. อ่านอย่างเดียว [IColorFormat](../icolorformat/). |
| virtual **double** [get_ContourWidth](./get_contourwidth/)() | ส่งคืนความกว้างของคอนทัวร์ 3D. อ่าน **double**. |
| virtual **double** [get_Depth](./get_depth/)() | ส่งคืนความลึกของรูปทรง 3D. อ่าน **double**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IColorFormat](../icolorformat/)\> [get_ExtrusionColor](./get_extrusioncolor/)() | ส่งคืนสีของการ extrusion. อ่านอย่างเดียว [IColorFormat](../icolorformat/). |
| virtual **double** [get_ExtrusionHeight](./get_extrusionheight/)() | ส่งคืนความสูงของเอฟเฟกต์ extrusion. อ่าน **double**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ILightRig](../ilightrig/)\> [get_LightRig](./get_lightrig/)() | ส่งคืนประเภทของแสง. อ่านอย่างเดียว [ILightRig](../ilightrig/). |
| virtual [MaterialPresetType](../materialpresettype/) [get_Material](./get_material/)() | ส่งคืนประเภทของวัสดุ. อ่าน [MaterialPresetType](../materialpresettype/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ดึงโครงสร้างข้อมูลตัวนับอ้างอิงที่เชื่อมโยงกับอ็อบเจกต์. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IThreeDFormatEffectiveData](../ithreedformateffectivedata/)\> [GetEffective](./geteffective/)() | ดึงข้อมูลการจัดรูปแบบ 3D ที่มีผลโดยใช้การสืบทอด. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | คล้ายกับเมธอด C# [Object.GetHashCode()](../../system/object/gethashcode/). เปิดใช้งานการสร้างแฮชของอ็อบเจกต์ที่กำหนดเอง. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | ดึงประเภทจริงของอ็อบเจกต์. คล้ายกับการเรียก C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | ตรวจสอบว่าอ็อบเจกต์เป็นอินสแตนซ์ของประเภทที่อธิบายโดย targetType. คล้ายกับโอเปอเรเตอร์ 'is' ของ C#. |
| void [Lock](../../system/object/lock/)() | ทำหน้าที่เหมือนการล็อคของคำสั่ง C# lock(). เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | คล้ายกับเมธอด C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). เปิดใช้งานการโคลนประเภทที่กำหนดเอง. |
|  [Object](../../system/object/object/)() | สร้างอ็อบเจกต์. เริ่มต้นโครงสร้างข้อมูลภายในทั้งหมด. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | คอนสตรัคเตอร์คัดลอก. จริงๆ ไม่ได้คัดลอกอะไรเลย เพียงเริ่มต้นอ็อบเจกต์ใหม่และเปิดใช้งานการคัดลอกซับคลาส. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | โอเปอเรเตอร์การกำหนดค่า. จริงๆ ไม่ได้คัดลอกอะไรเลย เพียงเริ่มต้นอ็อบเจกต์ใหม่และเปิดใช้งานการคัดลอกซับคลาส. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | เปรียบเทียบอ็อบเจกต์โดยอ้างอิง. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | เปรียบเทียบอ็อบเจกต์โดยอ้างอิง. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | เปรียบเทียบอ้างอิงอ็อบเจกต์ประเภทค่า กับ nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | การทำพิเศษของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริงและ nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | การทำพิเศษของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริง. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | ลดตัวนับอ้างอิงที่แชร์โดยค่าที่ระบุ. |
| virtual void [set_ContourWidth](./set_contourwidth/)(**double**) | ตั้งค่าความกว้างของคอนทัวร์ 3D. เขียน **double**. |
| virtual void [set_Depth](./set_depth/)(**double**) | ตั้งค่าความลึกของรูปทรง 3D. เขียน **double**. |
| virtual void [set_ExtrusionHeight](./set_extrusionheight/)(**double**) | ตั้งค่าสูงของเอฟเฟกต์ extrusion. เขียน **double**. |
| virtual void [set_Material](./set_material/)([MaterialPresetType](../materialpresettype/)) | ตั้งค่าประเภทของวัสดุ. เขียน [MaterialPresetType](../materialpresettype/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | ตั้งค่าเทมเพลตอาร์กิวเมนต์ที่ n เป็น weak pointer (แทน shared). อนุญาตให้สลับ pointer ในคอนเทนเนอร์เป็นโหมด weak. |
| int [SharedCount](../../system/object/sharedcount/)() const | ดึงค่าปัจจุบันของตัวนับอ้างอิงที่แชร์. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | เพิ่มตัวนับอ้างอิงที่แชร์. ไม่ควรเรียกโดยตรง; ใช้ smart pointer หรือ ThisProtector แทน. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ลดและคืนค่าตัวนับอ้างอิงที่แชร์. ไม่ควรเรียกโดยตรง; ใช้ smart pointer หรือ ThisProtector แทน. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | คล้ายกับเมธอด C# [Object.ToString()](../../system/object/tostring/). เปิดใช้งานการแปลงอ็อบเจกต์ที่กำหนดเป็นสตริง. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ทำหน้าที่คล้าย typeof([System.Object](../../system/object/)) ของ C#. |
| void [Unlock](../../system/object/unlock/)() | ทำหน้าที่ปลดล็อคของคำสั่ง C# lock(). เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | เพิ่มตัวนับ weak reference. ไม่ควรเรียกโดยตรง; ใช้ smart pointer หรือ ThisProtector แทน. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ลดตัวนับ weak reference. ไม่ควรเรียกโดยตรง; ใช้ smart pointer หรือ ThisProtector แทน. |
| virtual  [~Object](../../system/object/~object/)() | ทำลายอ็อบเจกต์. ปล่อยโครงสร้างข้อมูลภายในทั้งหมด. |

## ดูเพิ่มเติม

* คลาส [IThreeDParamSource](../ithreedparamsource/)
* เนมสเปซ [Aspose::Slides](../)
* ไลบรารี [Aspose.Slides](../../)