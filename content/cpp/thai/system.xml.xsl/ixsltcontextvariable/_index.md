---
title: IXsltContextVariable
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: ให้ส่วนต่อประสานกับตัวแปรที่กำหนดในสไตล์ชีตระหว่างการทำงานของ runtime
type: docs
weight: 40
url: /th/system.xml.xsl/ixsltcontextvariable/
---
## IXsltContextVariable class

ให้ส่วนต่อประสานกับตัวแปรที่กำหนดไว้ในสไตล์ชีตระหว่างการทำงานของ runtime

```cpp
class IXsltContextVariable : public virtual System::Object
```

## Methods

| เมธอด | คำอธิบาย |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | เปรียบเทียบวัตถุโดยใช้ semantics ของ C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบวัตถุประเภทอ้างอิงในสไตล์ของ C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบวัตถุประเภทค่าในสไตล์ของ C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | จำลองการเปรียบเทียบเลขทศนิยมสไตล์ C# ซึ่งสอง NaN จะถือว่าเท่ากันแม้ว่าตาม IEC 60559:1989 NaN จะไม่เท่ากับค่าใด ๆ รวมถึง NaN อีกด้วย. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | จำลองการเปรียบเทียบเลขทศนิยมสไตล์ C# ซึ่งสอง NaN จะถือว่าเท่ากันแม้ว่าตาม IEC 60559:1989 NaN จะไม่เท่ากับค่าใด ๆ รวมถึง NaN อีกด้วย. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [Evaluate](./evaluate/)([SharedPtr](../../system/sharedptr/)\<[XsltContext](../xsltcontext/)\>) | ประเมินค่าตัวแปรใน runtime และคืนวัตถุที่แสดงค่าของตัวแปรนั้น. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | ใช้สำหรับการทำงานภายในเท่านั้น. |
| virtual **bool** [get_IsLocal](./get_islocal/)() | คืนค่าแสดงว่าตัวแปรเป็นแบบ local หรือไม่. |
| virtual **bool** [get_IsParam](./get_isparam/)() | คืนค่าแสดงว่าตัวแปรเป็นพารามิเตอร์ของ Extensible Stylesheet Language Transformations (XSLT) หรือไม่ ซึ่งอาจเป็นพารามิเตอร์ของสไตล์ชีตหรือเทมเพลต. |
| virtual [System::Xml::XPath::XPathResultType](../../system.xml.xpath/xpathresulttype/) [get_VariableType](./get_variabletype/)() | คืนค่า XPathResultType ที่แสดงประเภทของ XML Path Language ([XPath](../../system.xml.xpath/)) ของตัวแปร. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ดึงโครงสร้างข้อมูลตัวนับการอ้างอิงที่เชื่อมกับวัตถุ |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | แนวคิดคล้ายกับเมธอด C# [Object.GetHashCode()](../../system/object/gethashcode/) ซึ่งทำให้สามารถทำแฮชวัตถุแบบกำหนดเองได้. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | ดึงประเภทจริงของวัตถุ ซึ่งเป็นแนวคิดคล้ายการเรียก C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | ตรวจสอบว่าวัตถุเป็นอินสแตนซ์ของประเภทที่อธิบายโดย targetType หรือไม่ ซึ่งเป็นแนวคิดคล้ายกับโอเปอเรเตอร์ 'is' ของ C#. |
| void [Lock](../../system/object/lock/)() | ทำตามคำสั่ง lock() ของ C# เพื่อทำการล็อค เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | แนวคิดคล้ายกับเมธอด C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) ซึ่งทำให้สามารถทำสำเนาประเภทที่กำหนดเองได้. |
|  [Object](../../system/object/object/)() | สร้างวัตถุและเริ่มต้นโครงสร้างข้อมูลภายในทั้งหมด. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | คอนสตรัคเตอร์คัดลอก ไม่ได้คัดลอกอะไรเลย เพียงแค่เริ่มต้นวัตถุใหม่และเปิดให้สามารถคัดลอกสร้างซับคลาสได้. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | ตัวดำเนินการกำหนดค่า ไม่ได้คัดลอกอะไร เพียงเริ่มต้นวัตถุใหม่และเปิดให้สามารถคัดลอกสร้างซับคลาสได้. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | เปรียบเทียบวัตถุโดยอ้างอิง. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | เปรียบเทียบวัตถุโดยอ้างอิง. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | เปรียบเทียบอ้างอิงวัตถุประเภทค่า กับ nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | การระบุชนิดพิเศษของ [Object::ReferenceEquals](../../system/object/referenceequals/) ในกรณีของสตริงและ nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | การระบุชนิดพิเศษของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริง. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | ลดค่า shared reference count ด้วยค่าที่ระบุ. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | ตั้งค่าอาร์กิวเมนต์เทมเพลตที่ n ให้เป็น weak pointer (แทน shared) เพื่อให้สามารถสลับ pointer ในคอนเทนเนอร์เป็นโหมด weak ได้. |
| int [SharedCount](../../system/object/sharedcount/)() const | ดึงค่าปัจจุบันของ shared reference counter. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | เพิ่มค่า shared reference count ไม่ควรเรียกโดยตรง ควรใช้ smart pointers หรือ ThisProtector แทน. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ลดค่าและคืนค่า shared reference count ไม่ควรเรียกโดยตรง ควรใช้ smart pointers หรือ ThisProtector แทน. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | แนวคิดคล้ายกับเมธอด C# [Object.ToString()](../../system/object/tostring/) ซึ่งทำให้สามารถแปลงวัตถุที่กำหนดเองเป็นสตริงได้. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ทำตามโครงสร้าง typeof([System.Object](../../system/object/)) ของ C#. |
| void [Unlock](../../system/object/unlock/)() | ทำตามคำสั่ง lock() ของ C# เพื่อปลดล็อค เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | เพิ่มค่า weak reference count ไม่ควรเรียกโดยตรง ควรใช้ smart pointers หรือ ThisProtector แทน. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ลดค่า weak reference count ไม่ควรเรียกโดยตรง ควรใช้ smart pointers หรือ ThisProtector แทน. |
| virtual  [~Object](../../system/object/~object/)() | ทำลายวัตถุและคืนพื้นที่โครงสร้างข้อมูลภายในทั้งหมด. |

## See Also

* คลาส [Object](../../system/object/)
* เนมสเปซ [System::Xml::Xsl](../)
* ไลบรารี [Aspose.Slides](../../)