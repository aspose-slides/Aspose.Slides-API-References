---
title: XmlPreloadedResolver
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: แทนคลาสที่ใช้เพื่อเติมข้อมูลล่วงหน้าในแคชด้วย DTD หรือสตรีม XML.
type: docs
weight: 1
url: /th/system.xml.resolvers/xmlpreloadedresolver/
---
## XmlPreloadedResolver คลาส

แทนคลาสที่ใช้เพื่อเติมข้อมูลล่วงหน้าในแคชด้วย DTD หรือสตรีม XML.

```cpp
class XmlPreloadedResolver : public System::Xml::XmlResolver
```

## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| void [Add](./add/)(const [SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\>\&, const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&) | เพิ่มอาร์เรย์ไบต์ไปยังที่เก็บ [XmlPreloadedResolver](./) และแมปไปยัง URI หากที่เก็บมีการแมปสำหรับ URI เดียวกันอยู่แล้ว การแมปที่มีอยู่จะถูกแทนที่ |
| void [Add](./add/)(const [SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\>\&, const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) | เพิ่มอาร์เรย์ไบต์ไปยังที่เก็บ [XmlPreloadedResolver](./) และแมปไปยัง URI หากที่เก็บมีการแมปสำหรับ URI เดียวกันอยู่แล้ว การแมปที่มีอยู่จะถูกแทนที่ |
| void [Add](./add/)(const [SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&) | เพิ่ม Stream ไปยังที่เก็บ [XmlPreloadedResolver](./) และแมปไปยัง URI หากที่เก็บมีการแมปสำหรับ URI เดียวกันอยู่แล้ว การแมปที่มีอยู่จะถูกแทนที่ |
| void [Add](./add/)(const [SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\>\&, const [String](../../system/string/)\&) | เพิ่มสตริงที่มีข้อมูลโหลดล่วงหน้าไปยังที่เก็บ [XmlPreloadedResolver](./) และแมปไปยัง URI หากที่เก็บมีการแมปสำหรับ URI เดียวกันอยู่แล้ว การแมปที่มีอยู่จะถูกแทนที่ |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | เปรียบเทียบออบเจ็กต์โดยใช้ semantics ของ C# [Object.Equals](../../system/object/equals/) |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบออบเจ็กต์ประเภทอ้างอิงในสไตล์ของ C# |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบออบเจ็กต์ประเภทค่าในสไตล์ของ C# |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | จำลองการเปรียบเทียบจุดลอยแบบ C#-style ที่ NaN สองค่าถือว่าเท่ากันแม้ว่าในมาตรฐาน IEC 60559:1989 NaN จะไม่เท่ากับค่าต่างๆ รวมถึง NaN ด้วย |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | จำลองการเปรียบเทียบจุดลอยแบบ C#-style ที่ NaN สองค่าถือว่าเท่ากันแม้ว่าในมาตรฐาน IEC 60559:1989 NaN จะไม่เท่ากับค่าต่างๆ รวมถึง NaN ด้วย |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | สำหรับการใช้งานภายในเท่านั้น |
| [SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<[SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\>\>\> [get_PreloadedUris](./get_preloadeduris/)() | ส่งคืนคอลเลกชันของ URI ที่โหลดล่วงหน้า |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | รับโครงสร้างข้อมูลตัวนับอ้างอิงที่เชื่อมโยงกับออบเจ็กต์ |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [GetEntity](./getentity/)([SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\>, [String](../../system/string/), const [TypeInfo](../../system/typeinfo/)\&) override | แมพ URI ไปยังออบเจ็กต์ที่มีทรัพยากรจริง |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | เป็นแบบจำลองของเมธอด C# [Object.GetHashCode()](../../system/object/gethashcode/) ทำให้สามารถแฮชออบเจ็กต์แบบกำหนดเองได้ |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | รับชนิดจริงของออบเจ็กต์ เป็นแบบจำลองของการเรียก C# [System.Object.GetType()](../../system/object/gettype/) |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | ตรวจสอบว่าออบเจ็กต์เป็นอินสแตนซ์ของชนิดที่อธิบายโดย targetType หรือไม่ เป็นแบบจำลองของออเปอเรเตอร์ 'is' ของ C# |
| void [Lock](../../system/object/lock/)() | ดำเนินการล็อกตามคำสั่ง lock() ของ C# เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/) |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | เป็นแบบจำลองของเมธอด C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) ทำให้สามารถโคลนประเภทที่กำหนดเองได้ |
|  [Object](../../system/object/object/)() | สร้างออบเจ็กต์ กำหนดค่าโครงสร้างข้อมูลภายในทั้งหมด |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | คอนสตรัคเตอร์คัดลอก ไม่ได้คัดลอกอะไรจริง ๆ เพียงกำหนดค่าออบเจ็กต์ใหม่และเปิดใช้งานการคัดลอกสร้างซับคลาส |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | โอเปอเรเตอร์กำหนดค่า ไม่ได้คัดลอกอะไรจริง ๆ เพียงกำหนดค่าออบเจ็กต์ใหม่และเปิดใช้งานการคัดลอกสร้างซับคลาส |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | เปรียบเทียบออบเจ็กต์โดยอ้างอิง |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | เปรียบเทียบออบเจ็กต์โดยอ้างอิง |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | เปรียบเทียบออบเจ็กต์ประเภทค่ากับ nullptr โดยอ้างอิง |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | การพิเศษของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริงและ nullptr |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | การพิเศษของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริงหลายตัว |
| void [Remove](./remove/)(const [SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\>\&) | ลบข้อมูลที่สอดคล้องกับ URI จาก [XmlPreloadedResolver](./) |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | ลดจำนวนการอ้างอิงที่แชร์ลงโดยค่าที่ระบุ |
| [SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\> [ResolveUri](./resolveuri/)([SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\>, [String](../../system/string/)) override | แก้ไข URI แบบเต็มจากฐานและ URI เชิงสัมพันธ์ |
| void [set_Credentials](./set_credentials/)([SharedPtr](../../system/sharedptr/)\<[Net::ICredentials](../../system.net/icredentials/)\>) override | ตั้งค่าข้อมูลประจำตัวที่ใช้เพื่อพิสูจน์ตัวตนของ [Net::WebRequest](../../system.net/webrequest/) ที่อยู่ภายใต้ |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | ตั้งค่าอาร์กิวเมนต์เทมเพลตที่ n ให้เป็น weak pointer (แทนที่ shared) ทำให้สามารถสลับพอยน์เตอร์ในคอนเทนเนอร์เป็นโหมด weak |
| int [SharedCount](../../system/object/sharedcount/)() const | รับค่าปัจจุบันของตัวนับการอ้างอิงที่แชร์ |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | เพิ่มจำนวนการอ้างอิงที่แชร์ ควรไม่เรียกโดยตรง; แทนใช้ smart pointers หรือ ThisProtector |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ลดและคืนค่าตัวนับการอ้างอิงที่แชร์ ควรไม่เรียกโดยตรง; แทนใช้ smart pointers หรือ ThisProtector |
| **bool** [SupportsType](./supportstype/)([SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\>, const [TypeInfo](../../system/typeinfo/)\&) override | กำหนดว่าตัวแก้ไขสนับสนุนประเภทอื่นนอกจาก Stream หรือไม่ |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | เป็นแบบจำลองของเมธอด C# [Object.ToString()](../../system/object/tostring/) ทำให้สามารถแปลงออบเจ็กต์กำหนดเองเป็นสตริงได้ |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ดำเนินการสร้าง typeof([System.Object](../../system/object/)) ของ C# |
| void [Unlock](../../system/object/unlock/)() | ดำเนินการปลดล็อกตามคำสั่ง lock() ของ C# เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/) |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | เพิ่มจำนวนการอ้างอิงแบบ weak ควรไม่เรียกโดยตรง; แทนใช้ smart pointers หรือ ThisProtector |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ลดจำนวนการอ้างอิงแบบ weak ควรไม่เรียกโดยตรง; แทนใช้ smart pointers หรือ ThisProtector |
|  [XmlPreloadedResolver](./xmlpreloadedresolver/)() | กำหนดค่าอินสแตนซ์ใหม่ของคลาส [XmlPreloadedResolver](./) |
|  [XmlPreloadedResolver](./xmlpreloadedresolver/)([XmlKnownDtds](../xmlknowndtds/)) | กำหนดค่าอินสแตนซ์ใหม่ของคลาส [XmlPreloadedResolver](./) ด้วย DTD ที่รู้จักและโหลดล่วงหน้าที่กำหนด |
|  [XmlPreloadedResolver](./xmlpreloadedresolver/)(const [SharedPtr](../../system/sharedptr/)\<[XmlResolver](../../system.xml/xmlresolver/)\>\&) | กำหนดค่าอินสแตนซ์ใหม่ของคลาส [XmlPreloadedResolver](./) ด้วยตัวแก้ไขสำรองที่ระบุ |
|  [XmlPreloadedResolver](./xmlpreloadedresolver/)(const [SharedPtr](../../system/sharedptr/)\<[XmlResolver](../../system.xml/xmlresolver/)\>\&, [XmlKnownDtds](../xmlknowndtds/)) | กำหนดค่าอินสแตนซ์ใหม่ของคลาส [XmlPreloadedResolver](./) ด้วยตัวแก้ไขสำรองที่ระบุและ DTD ที่รู้จักและโหลดล่วงหน้า |
|  [XmlPreloadedResolver](./xmlpreloadedresolver/)(const [SharedPtr](../../system/sharedptr/)\<[XmlResolver](../../system.xml/xmlresolver/)\>\&, [XmlKnownDtds](../xmlknowndtds/), const [SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IEqualityComparer](../../system.collections.generic/iequalitycomparer/)\<[SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\>\>\>\&) | กำหนดค่าอินสแตนซ์ใหม่ของคลาส [XmlPreloadedResolver](./) ด้วยตัวแก้ไขสำรองที่ระบุ, DTD ที่รู้จักและโหลดล่วงหน้า, และตัวเปรียบเทียบความเท่าเทียมของ URI |
| virtual  [~Object](../../system/object/~object/)() | ทำลายออบเจ็กต์ ปล่อยโครงสร้างข้อมูลภายในทั้งหมด |

## นิยามชนิด

| นิยามชนิด | คำอธิบาย |
| --- | --- |
| [Ptr](./ptr/) | นามแฝงสำหรับ shared pointer ไปยังอินสแตนซ์ของคลาสนี้ |

## หมายเหตุ

ออบเจ็กต์ของคลาสนี้ควรจัดสรรเฉพาะด้วยฟังก์ชัน [System::MakeObject()](../../system/makeobject/) เท่านั้น ไม่ควรสร้างอินสแตนซ์ของประเภทนี้บนสแตกหรือด้วย operator new เนื่องจากจะทำให้เกิดข้อผิดพลาดรันไทม์และ/หรือข้อขัดแย้งการตรวจสอบ เสมอห่อคลาสนี้เข้าในพอยน์เตอร์ [System::SmartPtr](../../system/smartptr/) และใช้พอยน์เตอร์นี้เพื่อส่งต่อไปยังฟังก์ชันเป็นอาร์กิวเมนต์

## ดูเพิ่มเติม

* คลาส [XmlResolver](../../system.xml/xmlresolver/)
* เนมสเปซ [System::Xml::Resolvers](../)
* ไลบรารี [Aspose.Slides](../../)