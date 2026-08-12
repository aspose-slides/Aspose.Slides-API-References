---
title: XmlAtomicValue
second_title: เอกสารอ้างอิง API ของ Aspose.Slides สำหรับ C++
description: เป็นตัวแทนของค่าที่มีประเภทขององค์ประกอบหรือแอตทริบิวต์ XML ที่ตรวจสอบแล้ว. คลาส XmlAtomicValue ไม่สามารถสืบทอดได้.
type: docs
weight: 66
url: /th/system.xml.schema/xmlatomicvalue/
---
## XmlAtomicValue คลาส

เป็นตัวแทนของค่าที่มีประเภทขององค์ประกอบหรือแอตทริบิวต์ XML ที่ตรวจสอบแล้ว. คลาส [XmlAtomicValue](./) ไม่สามารถสืบทอดได้.

```cpp
class XmlAtomicValue : public System::Xml::XPath::XPathItem
```

## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [SharedPtr](../../system/sharedptr/)\<[XmlAtomicValue](./)\> [Clone](./clone/)() | ส่งคืนสำเนาของอ็อบเจ็กต์ [XmlAtomicValue](./) นี้ |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | เปรียบเทียบอ็อบเจ็กต์โดยใช้เซมานติกของ C# [Object.Equals](../../system/object/equals/) |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจ็กต์ประเภทอ้างอิงในสไตล์ C# |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจ็กต์ประเภทค่าในสไตล์ C# |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | เลียนแบบการเปรียบเทียบจุดลอยตามสไตล์ C# ที่ NaN สองค่าเท่ากันแม้ว่าตาม IEC 60559:1989 NaN จะไม่เท่ากับค่าใด ๆ รวมถึง NaN ด้วย |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | เลียนแบบการเปรียบเทียบจุดลอยตามสไตล์ C# ที่ NaN สองค่าเท่ากันแม้ว่าตาม IEC 60559:1989 NaN จะไม่เท่ากับค่าใด ๆ รวมถึง NaN ด้วย |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | สำหรับการใช้งานภายในเท่านั้น |
| **bool** [get_IsNode](./get_isnode/)() override | ส่งคืนค่าที่บ่งชี้ว่าองค์ประกอบหรือแอตทริบิวต์ XML ที่ตรวจสอบแล้วเป็นโหนด [XPath](../../system.xml.xpath/) หรือเป็นค่าธาตุ |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [get_TypedValue](./get_typedvalue/)() override | ส่งคืนองค์ประกอบหรือแอตทริบิวต์ XML ที่ตรวจสอบแล้วในขณะนี้เป็นอ็อบเจ็กต์บ็อกซ์ของประเภทที่เหมาะสมที่สุดตามชนิดสคีม่า |
| [String](../../system/string/) [get_Value](./get_value/)() override | ส่งคืนค่า [String](../../system/string/) ขององค์ประกอบหรือแอตทริบิวต์ XML ที่ตรวจสอบแล้ว |
| **bool** [get_ValueAsBoolean](./get_valueasboolean/)() override | ส่งคืนค่าขององค์ประกอบหรือแอตทริบิวต์ XML ที่ตรวจสอบแล้วเป็น [Boolean](../../system/boolean/) |
| [DateTime](../../system/datetime/) [get_ValueAsDateTime](./get_valueasdatetime/)() override | ส่งคืนค่าขององค์ประกอบหรือแอตทริบิวต์ XML ที่ตรวจสอบแล้วเป็น [DateTime](../../system/datetime/) |
| **double** [get_ValueAsDouble](./get_valueasdouble/)() override | ส่งคืนค่าขององค์ประกอบหรือแอตทริบิวต์ XML ที่ตรวจสอบแล้วเป็น [Double](../../system/double/) |
| **int32_t** [get_ValueAsInt](./get_valueasint/)() override | ส่งคืนค่าขององค์ประกอบหรือแอตทริบิวต์ XML ที่ตรวจสอบแล้วเป็น [Int32](../../system/int32/) |
| **int64_t** [get_ValueAsLong](./get_valueaslong/)() override | ส่งคืนค่าขององค์ประกอบหรือแอตทริบิวต์ XML ที่ตรวจสอบแล้วเป็น [Int64](../../system/int64/) |
| [TypeInfo](../../system/typeinfo/) [get_ValueType](./get_valuetype/)() override | ส่งคืนประเภทขององค์ประกอบหรือแอตทริบิวต์ XML ที่ตรวจสอบแล้ว |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaType](../xmlschematype/)\> [get_XmlType](./get_xmltype/)() override | ส่งคืน [XmlSchemaType](../xmlschematype/) สำหรับองค์ประกอบหรือแอตทริบิวต์ XML ที่ตรวจสอบแล้ว |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | รับโครงสร้างข้อมูลตัวนับอ้างอิงที่เชื่อมโยงกับอ็อบเจ็กต์ |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | เป็นอนาล็อกของเมธอด C# [Object.GetHashCode()](../../system/object/gethashcode/). ให้การทำแฮชของอ็อบเจ็กต์ที่กำหนดเอง |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | รับประเภทที่แท้จริงของอ็อบเจ็กต์. เป็นอนาล็อกของการเรียก C# [System.Object.GetType()](../../system/object/gettype/) |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | ตรวจสอบว่าอ็อบเจ็กต์เป็นอินสแตนซ์ของประเภทที่อธิบายโดย targetType. เป็นอนาล็อกของอ็อปเรเตอร์ C# 'is' |
| void [Lock](../../system/object/lock/)() | implements C# lock() statement locking. Call directly or use [LockContext](../../system/lockcontext/) sentry object. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | เป็นอนาล็อกของเมธอด C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). ให้การคัดลอกประเภทที่กำหนดเอง |
|  [Object](../../system/object/object/)() | สร้างอ็อบเจ็กต์. เริ่มต้นโครงสร้างข้อมูลภายในทั้งหมด |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | ตัวสร้างสำเนา. ไม่ได้คัดลอกข้อมูลจริง ๆ เพียงแค่เริ่มต้นอ็อบเจ็กต์ใหม่และเปิดให้สร้างสำเนาของคลาสย่อย |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | ตัวดำเนินการกำหนดค่า. ไม่ได้คัดลอกข้อมูลจริง ๆ เพียงแค่เริ่มต้นอ็อบเจ็กต์ใหม่และเปิดให้สร้างสำเนาของคลาสย่อย |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | เปรียบเทียบอ็อบเจ็กต์โดยอ้างอิง |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | เปรียบเทียบอ็อบเจ็กต์โดยอ้างอิง |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | อ้างอิง-เปรียบเทียบอ็อบเจ็กต์ประเภทค่ากับ nullptr |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | การทำพิเศษของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริงและ nullptr |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | การทำพิเศษของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริง |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | ลดค่าตัวนับอ้างอิงที่แชร์ลงตามค่าที่ระบุ |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | ตั้งค่าอาร์กิวเมนต์เทมเพลตที่ n ให้เป็น weak pointer (แทนที่ shared). อนุญาตให้สลับ pointer ในคอนเทนเนอร์เป็นโหมด weak |
| int [SharedCount](../../system/object/sharedcount/)() const | รับค่าปัจจุบันของตัวนับอ้างอิงที่แชร์ |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | เพิ่มค่าตัวนับอ้างอิงที่แชร์. ไม่ควรเรียกโดยตรง; แทนที่ใช้ smart pointer หรือ ThisProtector |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ลดค่าตัวนับอ้างอิงที่แชร์และคืนค่า. ไม่ควรเรียกโดยตรง; แทนที่ใช้ smart pointer หรือ ThisProtector |
| [String](../../system/string/) [ToString](./tostring/)() const override | ส่งคืนค่า [String](../../system/string/) ขององค์ประกอบหรือแอตทริบิวต์ XML ที่ตรวจสอบแล้ว |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | implements C# typeof([System.Object](../../system/object/)) construct |
| void [Unlock](../../system/object/unlock/)() | implements C# lock() statement unlocking. Call directly or use [LockContext](../../system/lockcontext/) sentry object |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ValueAs](./valueas/)(const [TypeInfo](../../system/typeinfo/)\&, [SharedPtr](../../system/sharedptr/)\<[IXmlNamespaceResolver](../../system.xml/ixmlnamespaceresolver/)\>) override | ส่งคืนค่าขององค์ประกอบหรือแอตทริบิวต์ XML ที่ตรวจสอบแล้วเป็นประเภทที่ระบุโดยใช้วัตถุ [IXmlNamespaceResolver](../../system.xml/ixmlnamespaceresolver/) ที่กำหนดเพื่อแก้ชื่อเนมสเปซ |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ValueAs](../../system.xml.xpath/xpathitem/valueas/)(const [TypeInfo](../../system/typeinfo/)\&) | ส่งคืนค่ารายการเป็นประเภทที่ระบุ |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | เพิ่มค่าตัวนับอ้างอิงที่ weak. ไม่ควรเรียกโดยตรง; แทนที่ใช้ smart pointer หรือ ThisProtector |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ลดค่าตัวนับอ้างอิงที่ weak. ไม่ควรเรียกโดยตรง; แทนที่ใช้ smart pointer หรือ ThisProtector |
| virtual  [~Object](../../system/object/~object/)() | ทำลายอ็อบเจ็กต์. ปล่อยโครงสร้างข้อมูลภายในทั้งหมด |

## การกำหนดชนิด

| ชนิดนิยาม | คำอธิบาย |
| --- | --- |
| [Ptr](./ptr/) | อัลิอาสสำหรับ shared pointer ไปยังอินสแตนซ์ของคลาสนี้ |

## หมายเหตุ

อ็อบเจ็กต์ของคลาสนี้ควรสร้างเฉพาะด้วยฟังก์ชัน [System::MakeObject()](../../system/makeobject/). ไม่ควรสร้างอินสแตนซ์ของประเภทนี้บนสแตกหรือโดยใช้ operator new เนื่องจากจะทำให้เกิดข้อผิดพลาดรันไทม์และ/หรือการทำ assertion fault. ควรห่อคลาสนี้ใน pointer [System::SmartPtr](../../system/smartptr/) แล้วใช้ pointer นี้ส่งต่อเป็นอาร์กิวเมนต์ให้กับฟังก์ชันต่าง ๆ

## ดูเพิ่มเติม

* คลาส [XPathItem](../../system.xml.xpath/xpathitem/)
* เนมสเปซ [System::Xml::Schema](../)
* ไลบรารี [Aspose.Slides](../../)