---
title: SoapHeaderAttribute
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: "ระบุส่วนหัว SOAP ที่วิธีการบริการเว็บ XML หรือไคลเอนต์บริการเว็บ XML สามารถประมวลผลได้ วัตถุของคลาสนี้ควรจัดสรรเท่านั้นโดยใช้ฟังก์ชัน System::MakeObject() ไม่ควรสร้างอินสแตนซ์ของประเภทนี้บนสแตกหรือโดยใช้ตัวดำเนินการ new เนื่องจากจะทำให้เกิดข้อผิดพลาดเวลาเรียกใช้และ/หรือข้อผิดพลาดการตรวจสอบ ควรห่อคลาสนี้ด้วยตัวชี้ System::SmartPtr และใช้ตัวชี้นี้เพื่อส่งผ่านเป็นอาร์กิวเมนต์ให้กับฟังก์ชัน"
type: docs
weight: 92
url: /th/system.web.services.protocols/soapheaderattribute/
---
## SoapHeaderAttribute คลาส

ระบุส่วนหัว SOAP ที่วิธีบริการ XML [Web](../../system.web/) หรือไคลเอ็นต์บริการ XML [Web](../../system.web/) สามารถประมวลผลได้ วัตถุของคลาสนี้ควรจัดสรรโดยใช้ฟังก์ชัน [System::MakeObject()](../../system/makeobject/) เท่านั้น ไม่ควรสร้างอินสแตนซ์ของประเภทนี้บนสแต็กหรือโดยใช้ตัวดำเนินการ new เนื่องจากจะทำให้เกิดข้อผิดพลาดเวลาเรียกใช้งานและ/หรือข้อผิดพลาดการตรวจสอบ ควรห่อคลาสนี้ด้วยตัวชี้ [System::SmartPtr](../../system/smartptr/) และใช้ตัวชี้นี้เพื่อส่งผ่านเป็นอาร์กิวเมนต์ให้กับฟังก์ชัน

```cpp
class SoapHeaderAttribute : public System::Attribute
```

## วิธีการ

| เมธอด | คำอธิบาย |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | เปรียบเทียบวัตถุโดยใช้ความหมายของ C# [Object.Equals](../../system/object/equals/) |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบวัตถุประเภทอ้างอิงในรูปแบบ C# |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบวัตถุประเภทค่าในรูปแบบ C# |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | จำลองการเปรียบเทียบค่าตัวเลขลอยแบบ C# ที่ NaN สองค่าได้รับการพิจารณาเท่ากัน แม้ว่าตาม IEC 60559:1989 NaN จะไม่เท่ากับค่าใดๆ รวมถึง NaN ด้วย |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | จำลองการเปรียบเทียบค่าตัวเลขลอยแบบ C# ที่ NaN สองค่าได้รับการพิจารณาเท่ากัน แม้ว่าตาม IEC 60559:1989 NaN จะไม่เท่ากับค่าใดๆ รวมถึง NaN ด้วย |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | สำหรับการใช้งานภายในเท่านั้น |
| [SoapHeaderDirection](../soapheaderdirection/) [get_Direction](./get_direction/)() | รับทิศทางส่วนหัว SOAP |
| [String](../../system/string/) [get_MemberName](./get_membername/)() | รับชื่อของตัวแปรสมาชิกของบริการ XML SOAP ที่ใช้ในการรับเนื้อหาส่วนหัว SOAP |
| **bool** [get_Required](./get_required/)() | รับค่าที่บ่งชี้ว่าผู้รับบริการ XML [Web](../../system.web/) หรือไคลเอ็นต์บริการ XML [Web](../../system.web/) ต้องเข้าใจและประมวลผลส่วนหัว SOAP |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | รับโครงสร้างข้อมูลตัวนับการอ้างอิงที่เชื่อมโยงกับวัตถุ |
| static [Object::ptr](../../system/object/ptr/) [GetCustomAttribute](../../system/attribute/getcustomattribute/)(const [TypeInfo](../../system/typeinfo/)\&, const [TypeInfo](../../system/typeinfo/)\&) | ส่งคืนแอตทริบิวต์กำหนดเองของประเภทที่ระบุที่ใช้กับประเภทที่ระบุ |
| static [ArrayPtr](../../system/arrayptr/)\<[Object::ptr](../../system/object/ptr/)\> [GetCustomAttributes](../../system/attribute/getcustomattributes/)(const [TypeInfo](../../system/typeinfo/)\&) | ส่งคืนแอตทริบิวต์กำหนดเองทั้งหมดที่ใช้กับประเภทที่ระบุ |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | เทียบเท่ากับเมธอด [Object.GetHashCode()](../../system/object/gethashcode/) ของ C# ทำให้สามารถแฮชวัตถุกำหนดเองได้ |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | รับประเภทจริงของวัตถุ เทียบเท่ากับการเรียก [System.Object.GetType()](../../system/object/gettype/) ของ C# |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | ตรวจสอบว่าวัตถุเป็นอินสแตนซ์ของประเภทที่อธิบายโดย targetType หรือไม่ เทียบเท่ากับตัวดำเนินการ 'is' ของ C# |
| void [Lock](../../system/object/lock/)() | ทำหน้าที่เป็นการล็อกตามคำสั่ง lock() ของ C# เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/) |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | เทียบเท่ากับเมธอด [Object.MemberwiseClone()](../../system/object/memberwiseclone/) ของ C# ทำให้สามารถโคลนประเภทกำหนดเองได้ |
|  [Object](../../system/object/object/)() | สร้างวัตถุ เริ่มต้นโครงสร้างข้อมูลภายในทั้งหมด |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | คอนสตรัคเตอร์คัดลอก ไม่ได้คัดลอกอะไรจริง ๆ เพียงเริ่มต้นวัตถุใหม่และอนุญาตให้สร้างสำเนาสำหรับคลาสย่อย |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | ตัวดำเนินการกำหนดค่า ไม่ได้คัดลอกอะไรจริง ๆ เพียงเริ่มต้นวัตถุใหม่และอนุญาตให้สร้างสำเนาสำหรับคลาสย่อย |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | เปรียบเทียบวัตถุโดยอ้างอิง |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | เปรียบเทียบวัตถุโดยอ้างอิง |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | เปรียบเทียบอ้างอิงวัตถุประเภทค่ากับ nullptr |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | การจำเพาะของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริงและ nullptr |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | การจำเพาะของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริงหลายตัว |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | ลดจำนวนการอ้างอิงร่วมโดยค่าเฉพาะที่ระบุ |
| void [set_Direction](./set_direction/)([SoapHeaderDirection](../soapheaderdirection/)) | ตั้งค่าทิศทางส่วนหัว SOAP |
| void [set_MemberName](./set_membername/)([String](../../system/string/)) | ตั้งค่าชื่อของตัวแปรสมาชิกของบริการ XML SOAP ที่ใช้ในการรับเนื้อหาส่วนหัว SOAP |
| void [set_Required](./set_required/)(**bool**) | ตั้งค่าค่าที่บ่งชี้ว่าผู้รับบริการ XML [Web](../../system.web/) หรือไคลเอ็นต์บริการ XML [Web](../../system.web/) ต้องเข้าใจและประมวลผลส่วนหัว SOAP |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | ตั้งค่าเทมเพลตอาร์กิวเมนต์ที่ n ให้เป็น weak pointer (แทน shared) อนุญาตให้สลับตัวชี้ในคอนเทนเนอร์เป็นโหมด weak |
| int [SharedCount](../../system/object/sharedcount/)() const | รับค่าปัจจุบันของตัวนับการอ้างอิงร่วม |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | เพิ่มจำนวนการอ้างอิงร่วม ไม่ควรเรียกโดยตรง; ให้ใช้ smart pointers หรือ ThisProtector แทน |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ลดจำนวนการอ้างอิงร่วมและคืนค่า ไม่ควรเรียกโดยตรง; ให้ใช้ smart pointers หรือ ThisProtector แทน |
|  [SoapHeaderAttribute](./soapheaderattribute/)([String](../../system/string/)) | สร้างอินสแตนซ์ใหม่ |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | เทียบเท่ากับเมธอด [Object.ToString()](../../system/object/tostring/) ของ C# ทำให้สามารถแปลงวัตถุกำหนดเองเป็นสตริงได้ |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ทำหน้าที่เป็นการสร้าง typeof([System.Object](../../system/object/)) ของ C# |
| void [Unlock](../../system/object/unlock/)() | ทำหน้าที่เป็นการปลดล็อกตามคำสั่ง lock() ของ C# เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/) |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | เพิ่มจำนวนการอ้างอิง weak ไม่ควรเรียกโดยตรง; ให้ใช้ smart pointers หรือ ThisProtector แทน |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ลดจำนวนการอ้างอิง weak ไม่ควรเรียกโดยตรง; ให้ใช้ smart pointers หรือ ThisProtector แทน |
| virtual  [~Object](../../system/object/~object/)() | ทำลายวัตถุ ปล่อยโครงสร้างข้อมูลภายในทั้งหมด |

## ดูเพิ่มเติม

* คลาส [Attribute](../../system/attribute/)
* เนมสเปซ [System::Web::Services::Protocols](../)
* ไลบรารี [Aspose.Slides](../../)