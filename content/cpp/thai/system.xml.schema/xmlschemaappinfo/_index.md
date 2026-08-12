---
title: XmlSchemaAppInfo
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: แสดงถึงองค์ประกอบ appinfo ของ World Wide Web Consortium (W3C).
type: docs
weight: 157
url: /th/system.xml.schema/xmlschemaappinfo/
---
## XmlSchemaAppInfo คลาส

แสดงถึงองค์ประกอบ **appinfo** ของ World Wide [Web](../../system.web/) Consortium (W3C).

```cpp
class XmlSchemaAppInfo : public System::Xml::Schema::XmlSchemaObject
```

## เมธอด

| เมธอด | รายละเอียด |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | เปรียบเทียบอ็อบเจกต์โดยใช้ความหมายของ C# [Object.Equals](../../system/object/equals/) |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจกต์ประเภทอ้างอิงในสไตล์ C# |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจกต์ประเภทค่าในสไตล์ C# |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | จำลองการเปรียบเทียบค่า floating point แบบ C# ที่ถือว่า NaN สองค่ามีค่าเท่ากัน แม้ว่าตามมาตรฐาน IEC 60559:1989 NaN ไม่เท่ากับค่าใด ๆ รวมถึง NaN ด้วย |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | จำลองการเปรียบเทียบค่า floating point แบบ C# ที่ถือว่า NaN สองค่ามีค่าเท่ากัน แม้ว่าตามมาตรฐาน IEC 60559:1989 NaN ไม่เท่ากับค่าใด ๆ รวมถึง NaN ด้วย |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | สำหรับการใช้ภายในเท่านั้น |
| **int32_t** [get_LineNumber](../xmlschemaobject/get_linenumber/)() | คืนค่าหมายเลขบรรทัดในไฟล์ที่องค์ประกอบ **schema** อ้างอิง |
| **int32_t** [get_LinePosition](../xmlschemaobject/get_lineposition/)() | คืนค่าตำแหน่งบรรทัดในไฟล์ที่องค์ประกอบ **schema** อ้างอิง |
| [ArrayPtr](../../system/arrayptr/)\<[SharedPtr](../../system/sharedptr/)\<[XmlNode](../../system.xml/xmlnode/)\>\> [get_Markup](./get_markup/)() | คืนค่าอาเรย์ของอ็อบเจกต์ [XmlNode](../../system.xml/xmlnode/) ที่แสดงถึงโหนดลูกของ **appinfo** |
| [SharedPtr](../../system/sharedptr/)\<[System::Xml::Serialization::XmlSerializerNamespaces](../../system.xml.serialization/xmlserializernamespaces/)\> [get_Namespaces](../xmlschemaobject/get_namespaces/)() | คืนค่า XmlSerializerNamespaces ที่ใช้กับอ็อบเจกต์ schema นี้ |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaObject](../xmlschemaobject/)\> [get_Parent](../xmlschemaobject/get_parent/)() | คืนค่าพาเรนต์ของ [XmlSchemaObject](../xmlschemaobject/) นี้ |
| [String](../../system/string/) [get_Source](./get_source/)() | คืนค่าที่มาของข้อมูลแอปพลิเคชัน |
| [String](../../system/string/) [get_SourceUri](../xmlschemaobject/get_sourceuri/)() | คืนค่าตำแหน่งที่มาของไฟล์ที่โหลด schema |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ได้รับโครงสร้างข้อมูลตัวนับอ้างอิงที่เชื่อมโยงกับอ็อบเจกต์ |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | เป็นแบบเดียวกับเมธอด C# [Object.GetHashCode()](../../system/object/gethashcode/). เปิดใช้งานการแฮชของอ็อบเจกต์แบบกำหนดเอง |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | รับประเภทจริงของอ็อบเจกต์. เป็นแบบเดียวกับการเรียก C# [System.Object.GetType()](../../system/object/gettype/) |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | ตรวจสอบว่าอ็อบเจกต์เป็นอินสแตนซ์ของประเภทที่อธิบายโดย targetType หรือไม่. เป็นแบบเดียวกับโอเปอร์เตอร์ 'is' ของ C# |
| void [Lock](../../system/object/lock/)() | ทำหน้าที่ล็อกตามคำสั่ง C# lock(). เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/) |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | เป็นแบบเดียวกับเมธอด C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). เปิดใช้งานการโคลนนิ่งของชนิดกำหนดเอง |
|  [Object](../../system/object/object/)() | สร้างอ็อบเจกต์. เริ่มต้นโครงสร้างข้อมูลภายในทั้งหมด |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | คอนสตรัคเตอร์สำเนา. จริง ๆ แล้วไม่ได้คัดลอกอะไรเลย เพียงเริ่มต้นอ็อบเจกต์ใหม่และเปิดใช้งานการคัดลอกซับคลาส |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | โอเปอร์เตอร์การกำหนดค่า. จริง ๆ แล้วไม่ได้คัดลอกอะไรเลย เพียงเริ่มต้นอ็อบเจกต์ใหม่และเปิดใช้งานการคัดลอกซับคลาส |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | เปรียบเทียบอ็อบเจกต์โดยอ้างอิง |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | เปรียบเทียบอ็อบเจกต์โดยอ้างอิง |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | เปรียบเทียบอ้างอิงกับอ็อบเจกต์ประเภทค่าโดยใช้ nullptr |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | การกำหนดพิเศษของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริงและ nullptr |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | การกำหนดพิเศษของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริง |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | ลดค่าตัวนับอ้างอิงร่วมโดยค่าที่ระบุ |
| void [set_LineNumber](../xmlschemaobject/set_linenumber/)(**int32_t**) | กำหนดหมายเลขบรรทัดในไฟล์ที่องค์ประกอบ **schema** อ้างอิง |
| void [set_LinePosition](../xmlschemaobject/set_lineposition/)(**int32_t**) | กำหนดตำแหน่งบรรทัดในไฟล์ที่องค์ประกอบ **schema** อ้างอิง |
| void [set_Markup](./set_markup/)(const [ArrayPtr](../../system/arrayptr/)\<[SharedPtr](../../system/sharedptr/)\<[XmlNode](../../system.xml/xmlnode/)\>\>\&) | กำหนดอาเรย์ของอ็อบเจกต์ [XmlNode](../../system.xml/xmlnode/) ที่แสดงถึงโหนดลูกของ **appinfo** |
| void [set_Namespaces](../xmlschemaobject/set_namespaces/)(const [SharedPtr](../../system/sharedptr/)\<[System::Xml::Serialization::XmlSerializerNamespaces](../../system.xml.serialization/xmlserializernamespaces/)\>\&) | กำหนด XmlSerializerNamespaces ที่ใช้กับอ็อบเจกต์ schema นี้ |
| void [set_Parent](../xmlschemaobject/set_parent/)(const [SharedPtr](../../system/sharedptr/)\<[XmlSchemaObject](../xmlschemaobject/)\>\&) | กำหนดพาเรนต์ของ [XmlSchemaObject](../xmlschemaobject/) นี้ |
| void [set_Source](./set_source/)(const [String](../../system/string/)\&) | กำหนดที่มาของข้อมูลแอปพลิเคชัน |
| void [set_SourceUri](../xmlschemaobject/set_sourceuri/)(const [String](../../system/string/)\&) | กำหนดตำแหน่งที่มาของไฟล์ที่โหลด schema |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | ตั้งค่าเทมเพลตอาร์กิวเมนต์ที่ n เป็น weak pointer (แทน shared). อนุญาตให้สลับ pointer ในคอนเทนเนอร์เป็นโหมด weak |
| int [SharedCount](../../system/object/sharedcount/)() const | รับค่าปัจจุบันของตัวนับอ้างอิงร่วม |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | เพิ่มตัวนับอ้างอิงร่วม. ไม่ควรเรียกโดยตรง; ใช้ smart pointer หรือ ThisProtector แทน |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ลดและคืนค่าตัวนับอ้างอิงร่วม. ไม่ควรเรียกโดยตรง; ใช้ smart pointer หรือ ThisProtector แทน |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | เป็นแบบเดียวกับเมธอด C# [Object.ToString()](../../system/object/tostring/). เปิดใช้งานการแปลงอ็อบเจกต์กำหนดเองเป็นสตริง |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ทำหน้าที่สร้าง typeof([System.Object](../../system/object/)) ของ C# |
| void [Unlock](../../system/object/unlock/)() | ทำหน้าที่ปลดล็อกตามคำสั่ง C# lock(). เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/) |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | เพิ่มตัวนับอ้างอิงแบบ weak. ไม่ควรเรียกโดยตรง; ใช้ smart pointer หรือ ThisProtector แทน |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ลดตัวนับอ้างอิงแบบ weak. ไม่ควรเรียกโดยตรง; ใช้ smart pointer หรือ ThisProtector แทน |
|  [XmlSchemaObject](../xmlschemaobject/xmlschemaobject/)() | เริ่มต้นอินสแตนซ์ใหม่ของคลาส [XmlSchemaObject](../xmlschemaobject/) |
| virtual  [~Object](../../system/object/~object/)() | ทำลายอ็อบเจกต์. ปลดปล่อยโครงสร้างข้อมูลภายในทั้งหมด |

## ชนิดนิยาม

| ชนิดนิยาม | รายละเอียด |
| --- | --- |
| [Ptr](./ptr/) | นามแฝงสำหรับ shared pointer ไปยังอินสแตนซ์ของคลาสนี้ |

## หมายเหตุ

อ็อบเจกต์ของคลาสนี้ควรจะถูกจัดสรรโดยใช้ฟังก์ชัน [System::MakeObject()](../../system/makeobject/) เท่านั้น. อย่าสร้างอินสแตนซ์ของชนิดนี้บนสแตกหรือโดยใช้ operator new เพราะจะทำให้เกิดข้อผิดพลาดเวลารันและ/หรือข้อผิดพลาดการยืนยัน. ควรห่อหุ้มคลาสนี้ด้วยพอยน์เตอร์ [System::SmartPtr](../../system/smartptr/) และใช้พอยน์เตอร์นี้ส่งต่อเป็นอาร์กิวเมนต์ให้กับฟังก์ชัน.

## ดูเพิ่มเติม

* คลาส [XmlSchemaObject](../xmlschemaobject/)
* เนมสเปซ [System::Xml::Schema](../)
* ไลบรารี [Aspose.Slides](../../)