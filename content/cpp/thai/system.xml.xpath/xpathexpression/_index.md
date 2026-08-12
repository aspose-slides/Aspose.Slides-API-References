---
title: XPathExpression
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: ให้คลาสที่มีประเภทที่เป็นตัวแทนของนิพจน์ XPath ที่คอมไพล์แล้ว.
type: docs
weight: 40
url: /th/system.xml.xpath/xpathexpression/
---
## XPathExpression คลาส

ให้คลาสที่มีประเภทที่เป็นตัวแทนของนิพจน์ [XPath](../) ที่คอมไพล์แล้ว.

```cpp
class XPathExpression : public System::Object
```

## เมธอด

| Method | Description |
| --- | --- |
| virtual void [AddSort](./addsort/)([SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>, [SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IComparer](../../system.collections.generic/icomparer/)\<[SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\>\>) | เมื่อทำการโอเวอร์ไรด์ในคลาสที่สืบทอด, จัดเรียงโหนดที่เลือกโดยนิพจน์ [XPath](../) ตามอ็อบเจกต์ IComparer ที่ระบุ |
| virtual void [AddSort](./addsort/)([SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>, [XmlSortOrder](../xmlsortorder/), [XmlCaseOrder](../xmlcaseorder/), [String](../../system/string/), [XmlDataType](../xmldatatype/)) | เมื่อทำการโอเวอร์ไรด์ในคลาสที่สืบทอด, จัดเรียงโหนดที่เลือกโดยนิพจน์ [XPath](../) ตามพารามิเตอร์ที่ให้มา |
| virtual [SharedPtr](../../system/sharedptr/)\<[XPathExpression](./)\> [Clone](./clone/)() | เมื่อทำการโอเวอร์ไรด์ในคลาสที่สืบทอด, คืนค่าคลอนของ [XPathExpression](./) นี้ |
| static [SharedPtr](../../system/sharedptr/)\<[XPathExpression](./)\> [Compile](./compile/)(const [String](../../system/string/)\&) | คอมไพล์นิพจน์ [XPath](../) ที่ระบุและคืนค่าอ็อบเจกต์ [XPathExpression](./) ที่แสดงถึงนิพจน์ [XPath](../) |
| static [SharedPtr](../../system/sharedptr/)\<[XPathExpression](./)\> [Compile](./compile/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[IXmlNamespaceResolver](../../system.xml/ixmlnamespaceresolver/)\>\&) | คอมไพล์นิพจน์ [XPath](../) ที่ระบุ, โดยใช้อ็อบเจกต์ [IXmlNamespaceResolver](../../system.xml/ixmlnamespaceresolver/) ที่ระบุสำหรับการแก้ไขเนมสเปซ, และคืนค่าอ็อบเจกต์ [XPathExpression](./) ที่แสดงถึงนิพจน์ [XPath](../) |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | เปรียบเทียบอ็อบเจกต์โดยใช้เซมานติกของ C# [Object.Equals](../../system/object/equals/) |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจกต์แบบอ้างอิงในสไตล์ของ C# |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจกต์แบบค่าในสไตล์ของ C# |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | จำลองการเปรียบเทียบเลขทศนิยมแบบ C# ที่ NaN สองค่าถือว่าเท่ากันแม้ว่าตาม IEC 60559:1989 NaN จะไม่เท่ากับค่าใด ๆ รวมถึง NaN |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | จำลองการเปรียบเทียบเลขทศนิยมแบบ C# ที่ NaN สองค่าถือว่าเท่ากันแม้ว่าตาม IEC 60559:1989 NaN จะไม่เท่ากับค่าใด ๆ รวมถึง NaN |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | ใช้เพื่อวัตถุประสงค์ภายในเท่านั้น |
| virtual [String](../../system/string/) [get_Expression](./get_expression/)() | เมื่อทำการโอเวอร์ไรด์ในคลาสที่สืบทอด, จะรับการแสดงผลเป็น **string** ของ [XPathExpression](./) |
| virtual [XPathResultType](../xpathresulttype/) [get_ReturnType](./get_returntype/)() | เมื่อทำการโอเวอร์ไรด์ในคลาสที่สืบทอด, จะรับประเภทผลลัพธ์ของนิพจน์ [XPath](../) |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | รับโครงสร้างข้อมูลตัวนับอ้างอิงที่เชื่อมโยงกับอ็อบเจกต์ |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | อนุพันธ์ของเมธอด C# [Object.GetHashCode()](../../system/object/gethashcode/). เปิดใช้งานการทำแฮชของอ็อบเจกต์ที่กำหนดเอง |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | รับประเภทจริงของอ็อบเจกต์. อนุพันธ์ของการเรียก C# [System.Object.GetType()](../../system/object/gettype/) |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | ตรวจสอบว่าอ็อบเจกต์เป็นอินสแตนซ์ของประเภทที่อธิบายโดย targetType หรือไม่. อนุพันธ์ของโอเปอเรเตอร์ 'is' ของ C# |
| void [Lock](../../system/object/lock/)() | ทำการล็อกตามคำสั่ง lock() ของ C#. เรียกโดยตรงหรือใช้อ็อบเจกต์ sentinel [LockContext](../../system/lockcontext/) |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | อนุพันธ์ของเมธอด C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). เปิดใช้งานการทำคลอนของประเภทที่กำหนดเอง |
|  [Object](../../system/object/object/)() | สร้างอ็อบเจกต์. เริ่มต้นโครงสร้างข้อมูลภายในทั้งหมด |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | คอนสตรัคเตอร์คัดลอก. จริง ๆ แล้วไม่ได้คัดลอกอะไร, เพียงเริ่มต้นอ็อบเจกต์ใหม่และเปิดใช้งานการสร้างคัดลอกของซับคลาส |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | โอเปอเรเตอร์การมอบหมาย. จริง ๆ แล้วไม่ได้คัดลอกอะไร, เพียงเริ่มต้นอ็อบเจกต์ใหม่และเปิดใช้งานการสร้างคัดลอกของซับคลาส |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | เปรียบเทียบอ็อบเจกต์โดยอ้างอิง |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | เปรียบเทียบอ็อบเจกต์โดยอ้างอิง |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | เปรียบเทียบอ้างอิงของอ็อบเจกต์แบบค่า กับ nullptr |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | การจำเพาะของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของ string และ nullptr |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | การจำเพาะของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของ strings |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | ลดจำนวนการอ้างอิงที่แชร์ลงตามค่าที่ระบุ |
| virtual void [SetContext](./setcontext/)([SharedPtr](../../system/sharedptr/)\<[XmlNamespaceManager](../../system.xml/xmlnamespacemanager/)\>) | เมื่อทำการโอเวอร์ไรด์ในคลาสที่สืบทอด, ระบุอ็อบเจกต์ [XmlNamespaceManager](../../system.xml/xmlnamespacemanager/) ที่ใช้สำหรับการแก้ไขเนมสเปซ |
| virtual void [SetContext](./setcontext/)([SharedPtr](../../system/sharedptr/)\<[IXmlNamespaceResolver](../../system.xml/ixmlnamespaceresolver/)\>) | เมื่อทำการโอเวอร์ไรด์ในคลาสที่สืบทอด, ระบุอ็อบเจกต์ [IXmlNamespaceResolver](../../system.xml/ixmlnamespaceresolver/) ที่ใช้สำหรับการแก้ไขเนมสเปซ |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | ตั้งอาร์กิวเมนต์เทมเพลตที่ n ให้เป็น weak pointer (แทนที่ shared). อนุญาตให้สลับพอยน์เตอร์ในคอนเทนเนอร์เป็นโหมด weak |
| int [SharedCount](../../system/object/sharedcount/)() const | รับค่าปัจจุบันของตัวนับอ้างอิงที่แชร์ |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | เพิ่มจำนวนการอ้างอิงที่แชร์. ไม่ควรเรียกโดยตรง; ให้ใช้สมาร์ทพอยน์เตอร์หรือ ThisProtector |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ลดจำนวนและคืนค่าการอ้างอิงที่แชร์. ไม่ควรเรียกโดยตรง; ให้ใช้สมาร์ทพอยน์เตอร์หรือ ThisProtector |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | อนุพันธ์ของเมธอด C# [Object.ToString()](../../system/object/tostring/). เปิดใช้งานการแปลงอ็อบเจกต์ที่กำหนดเองเป็น string |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ทำการดำเนินการคอนสตรัคต์ typeof([System.Object](../../system/object/)) ของ C# |
| void [Unlock](../../system/object/unlock/)() | ทำการปลดล็อกตามคำสั่ง lock() ของ C#. เรียกโดยตรงหรือใช้อ็อบเจกต์ sentinel [LockContext](../../system/lockcontext/) |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | เพิ่มจำนวนการอ้างอิงแบบ weak. ไม่ควรเรียกโดยตรง; ให้ใช้สมาร์ทพอยน์เตอร์หรือ ThisProtector |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ลดจำนวนการอ้างอิงแบบ weak. ไม่ควรเรียกโดยตรง; ให้ใช้สมาร์ทพอยน์เตอร์หรือ ThisProtector |
| virtual  [~Object](../../system/object/~object/)() | ทำลายอ็อบเจกต์. ปล่อยโครงสร้างข้อมูลภายในทั้งหมด |
## ประเภทนิยาม

| Typedef | Description |
| --- | --- |
| [Ptr](./ptr/) | นามแฝงสำหรับ shared pointer ไปยังอินสแตนซ์ของคลาสนี้ |
## ดูเพิ่มเติม

* คลาส [Object](../../system/object/)
* เนมสเปซ [System::Xml::XPath](../)
* ไลบรารี [Aspose.Slides](../../)