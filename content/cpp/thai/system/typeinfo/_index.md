---
title: TypeInfo
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: แสดงถึงประเภทเฉพาะและให้ข้อมูลเกี่ยวกับประเภทนั้น
type: docs
weight: 1379
url: /th/system/typeinfo/
---
## TypeInfo คลาส

Represents a particular type and provides information about it.

```cpp
class TypeInfo
```

## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| void [AddAttribute](./addattribute/)(const [ObjectPtr](../smartptr/)\&) | เพิ่มแอตทริบิวต์ที่ระบุลงในรายการแอตทริบิวต์ของประเภท |
| void [AddDefaultConstructor](./adddefaultconstructor/)() | ตั้งค่าตัวสร้างค่าเริ่มต้นสำหรับประเภท T |
| void [AddDefaultConstructor](./adddefaultconstructor/)([DefaultConstructor](./defaultconstructor/)) | ตั้งค่าตัวสร้างค่าเริ่มต้นโดยฟันก์เตอร์ที่สร้างอินสแตนซ์ของคลาส |
| void [AddMember](./addmember/)(const [SharedPtr](../sharedptr/)\<[System::Reflection::MemberInfo](../../system.reflection/memberinfo/)\>\&) | เพิ่มสมาชิกที่ระบุลงในรายการสมาชิกของประเภท |
| static const [TypeInfo](./)\& [BoxedValueType](./boxedvaluetype/)() | ให้โครงสร้าง [TypeInfo](./) ไม่ซ้ำสำหรับประเภท **BoxedValue** เพื่อใช้ร่วมกับหลายคลาส Boxed* |
| **bool** [Equals](./equals/)(const [TypeInfo](./)\&) const |  |
| [System::SharedPtr](../sharedptr/)\<[System::Reflection::Assembly](../../system.reflection/assembly/)\> [get_Assembly](./get_assembly/)() const | ยังไม่ได้ดำเนินการ. คืนค่าพอยน์เตอร์ไปยัง assembly ที่ประกาศประเภทที่วัตถุปัจจุบันแทน |
| [String](../string/) [get_AssemblyQualifiedName](./get_assemblyqualifiedname/)() const | ยังไม่ได้ดำเนินการ. คืนค่าชื่อเต็มรวมถึงชื่อ assembly ของประเภทที่วัตถุปัจจุบันแทน |
| [TypeInfo](./) [get_BaseType](./get_basetype/)() const | คืนค่าตัวบรรยายประเภทฐาน |
| **bool** [get_ContainsGenericParameters](./get_containsgenericparameters/)() const | รับค่าที่ระบุว่าวัตถุ Type ปัจจุบันมีพารามิเตอร์ประเภทที่ยังไม่ได้แทนที่ด้วยประเภทเฉพาะหรือไม่ |
| [ArrayPtr](../arrayptr/)\<[SharedPtr](../sharedptr/)\<[System::Reflection::MemberInfo](../../system.reflection/memberinfo/)\>\> [get_DeclaredMember](./get_declaredmember/)(const [String](../string/)\&) const | รับรายการของสมาชิกที่มีชื่อที่ระบุ |
| [String](../string/) [get_FullName](./get_fullname/)() const | คืนค่าชื่อเต็ม (แต่ไม่มีชื่อ assembly) ของประเภทที่วัตถุปัจจุบันแทน |
| [ArrayPtr](../arrayptr/)\<[TypeInfo](./)\> [get_GenericTypeArguments](./get_generictypearguments/)() const | รับอาร์เรย์ของอาร์กิวเมนต์ประเภททั่วไปสำหรับประเภทนี้ |
| **bool** [get_IsAbstract](./get_isabstract/)() const | รับค่าที่บ่งชี้ว่า Type เป็นแบบแอบสแตรกต์และต้องถูก Override |
| **bool** [get_IsArray](./get_isarray/)() const | รับค่าที่บ่งชี้ว่าประเภทเป็นอาร์เรย์ |
| **bool** [get_IsClass](./get_isclass/)() const | รับค่าที่บ่งชี้ว่า Type เป็นคลาสหรือดีลเกต; คือ ไม่ใช่ประเภทค่า หรือ อินเทอร์เฟซ |
| **bool** [get_IsEnum](./get_isenum/)() const | รับค่าที่บ่งชี้ว่า Type ปัจจุบันเป็นการนับค่า (enumeration) |
| **bool** [get_IsGenericType](./get_isgenerictype/)() const |  |
| **bool** [get_IsGenericTypeDefinition](./get_isgenerictypedefinition/)() const | รับค่าที่บ่งชี้ว่า Type ปัจจุบันเป็นการกำหนดประเภททั่วไป ที่สามารถสร้างประเภททั่วไปอื่นจากมันได้ |
| **bool** [get_IsInterface](./get_isinterface/)() const | รับค่าที่บ่งชี้ว่า Type เป็นอินเทอร์เฟซ; คือไม่ใช่คลาสหรือประเภทค่า |
| **bool** [get_IsSealed](./get_issealed/)() const | รับค่าที่บ่งชี้ว่า Type ถูกประกาศเป็น sealed |
| **bool** [get_IsValueType](./get_isvaluetype/)() const | รับค่าที่บ่งชี้ว่า Type เป็นประเภทค่า |
| **bool** [get_IsVisible](./get_isvisible/)() const | รับค่าที่บ่งชี้ว่า Type สามารถเข้าถึงโดยโค้ดภายนอก assembly |
| [String](../string/) [get_Name](./get_name/)() const | คืนค่าชื่อของประเภทที่วัตถุปัจจุบันแทน |
| [String](../string/) [get_Namespace](./get_namespace/)() const | รับเนมสเปซของ Type |
| [SharedPtr](../sharedptr/)\<[System::Reflection::ConstructorInfo](../../system.reflection/constructorinfo/)\> [GetConstructor](./getconstructor/)(const [ArrayPtr](../arrayptr/)\<[TypeInfo](./)\>\&) const | ค้นหาตัวสร้างอินสแตนซ์สาธารณะที่พารามิเตอร์ตรงกับประเภทในอาร์เรย์ที่ระบุ |
| [ArrayPtr](../arrayptr/)\<[SharedPtr](../sharedptr/)\<[System::Reflection::ConstructorInfo](../../system.reflection/constructorinfo/)\>\> [GetConstructors](./getconstructors/)([System::Reflection::BindingFlags](../../system.reflection/bindingflags/)) const | ค้นหาตัวสร้างที่กำหนดไว้สำหรับ Type ปัจจุบัน, โดยใช้ BindingFlags ที่ระบุ |
| [ArrayPtr](../arrayptr/)\<[SharedPtr](../sharedptr/)\<[System::Reflection::ConstructorInfo](../../system.reflection/constructorinfo/)\>\> [GetConstructors](./getconstructors/)() const | คืนค่าตัวสร้างสาธารณะทั้งหมดที่กำหนดไว้สำหรับ Type ปัจจุบัน |
| [ObjectPtr](../smartptr/) [GetCustomAttribute](./getcustomattribute/)(const [TypeInfo](./)\&) const | ค้นหาแอตทริบิวต์แบบกำหนดเองที่มีประเภทที่ระบุและนำไปใช้กับประเภทที่วัตถุปัจจุบันแทน |
| [ArrayPtr](../arrayptr/)\<[ObjectPtr](../smartptr/)\> [GetCustomAttributes](./getcustomattributes/)() const | คืนค่าอาร์เรย์ที่บรรจุอ็อบเจ็กต์ที่แสดงถึงแอตทริบิวต์แบบกำหนดเองทั้งหมดที่นำไปใช้กับประเภท |
| [ArrayPtr](../arrayptr/)\<[ObjectPtr](../smartptr/)\> [GetCustomAttributes](./getcustomattributes/)(const [TypeInfo](./)\&, **bool**) const | คืนค่าอาร์เรย์ที่บรรจุอ็อบเจ็กต์ที่แสดงถึงแอตทริบิวต์เฉพาะที่นำไปใช้กับประเภท |
| [TypeInfo](./) [GetElementType](./getelementtype/)() const | ยังไม่ได้ดำเนินการ. |
| [SharedPtr](../sharedptr/)\<[System::Reflection::FieldInfo](../../system.reflection/fieldinfo/)\> [GetField](./getfield/)(const [System::String](../string/)\&, [System::Reflection::BindingFlags](../../system.reflection/bindingflags/)) const | ค้นหาฟิลด์ที่ระบุ, โดยใช้ข้อจำกัดการผูกที่ระบุ |
| [ArrayPtr](../arrayptr/)\<[SharedPtr](../sharedptr/)\<[System::Reflection::FieldInfo](../../system.reflection/fieldinfo/)\>\> [GetFields](./getfields/)([System::Reflection::BindingFlags](../../system.reflection/bindingflags/)) const | ค้นหาฟิลด์ที่กำหนดไว้สำหรับ Type ปัจจุบัน, โดยใช้ข้อจำกัดการผูกที่ระบุ |
| [ArrayPtr](../arrayptr/)\<[TypeInfo](./)\> [GetGenericArguments](./getgenericarguments/)() const | รับอาร์เรย์ของอาร์กิวเมนต์ประเภททั่วไปสำหรับประเภทนี้ |
| int [GetHashCode](./gethashcode/)() const | คืนค่า hash code ที่เชื่อมโยงกับอินสแตนซ์นี้ |
| [ArrayPtr](../arrayptr/)\<[TypeInfo](./)\> [GetInterfaces](./getinterfaces/)() const | รับอินเทอร์เฟซทั้งหมดที่ถูกทำให้เป็นหรือสืบทอดโดย Type ปัจจุบัน |
| [ArrayPtr](../arrayptr/)\<[SharedPtr](../sharedptr/)\<[System::Reflection::MemberInfo](../../system.reflection/memberinfo/)\>\> [GetMember](./getmember/)(const [String](../string/)\&) const | รับรายการของสมาชิกที่มีชื่อที่ระบุ |
| [SharedPtr](../sharedptr/)\<[System::Reflection::MethodInfo](../../system.reflection/methodinfo/)\> [GetMethod](./getmethod/)(const [String](../string/)\&) const | รับเมธอดที่มีชื่อที่ระบุ |
| [ArrayPtr](../arrayptr/)\<[SharedPtr](../sharedptr/)\<[System::Reflection::PropertyInfo](../../system.reflection/propertyinfo/)\>\> [GetProperties](./getproperties/)() const | คืนค่าคุณสมบัติสาธารณะทั้งหมดของ Type ปัจจุบัน |
| [ArrayPtr](../arrayptr/)\<[SharedPtr](../sharedptr/)\<[System::Reflection::PropertyInfo](../../system.reflection/propertyinfo/)\>\> [GetProperties](./getproperties/)([System::Reflection::BindingFlags](../../system.reflection/bindingflags/)) const | ค้นหาคุณสมบัติของ Type ปัจจุบัน, โดยใช้ข้อจำกัดการผูกที่ระบุ |
| [TypeInfo](./) [GetTemplParamType](./gettemplparamtype/)() const | รับตัวบรรยายประเภทพารามิเตอร์เทมเพลต |
| **uint32_t** [Hash](./hash/)() const | คืนค่า hash value ที่เชื่อมโยงกับประเภทที่วัตถุปัจจุบันแทน |
| **bool** [IsAssignableFrom](./isassignablefrom/)(const [TypeInfo](./)\&) const | กำหนดว่าตัวอย่างของประเภทที่ระบุสามารถกำหนดให้กับตัวแปรของประเภทปัจจุบันได้หรือไม่ |
| **bool** [IsDefined](./isdefined/)(const [TypeInfo](./)\&, **bool**) const | ยังไม่ได้ดำเนินการ. ระบุว่ามีแอตทริบิวต์หนึ่งหรือหลายของประเภทที่ระบุหรือประเภทที่สืบทอดจากมันถูกนำไปใช้กับสมาชิกนี้หรือไม่ |
| **bool** [IsInstanceOfType](./isinstanceoftype/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&) const | กำหนดว่าวัตถุที่ระบุเป็นอินสแตนซ์ของประเภทปัจจุบันหรือไม่ |
| **bool** [IsSubclassOf](./issubclassof/)(const [TypeInfo](./)\&) const | กำหนดว่าประเภทที่วัตถุปัจจุบันแทนเป็นคลาสย่อยของคลาสที่ระบุหรือไม่ |
| **bool** [operator!=](./operator_not_equal/)(const [TypeInfo](./)\&) const | กำหนดว่าวัตถุ [TypeInfo](./) ปัจจุบันและที่ระบุไม่เท่ากันหรือไม่ |
| **bool** [operator!=](./operator_not_equal/)(std::nullptr_t) const | กำหนดว่าวัตถุ [TypeInfo](./) ปัจจุบันไม่ใช่วัตถุ null, คือ แทนประเภทใดประเภทหนึ่งหรือไม่ |
| **bool** [operator==](./operator_equal_equal/)(const [TypeInfo](./)\&) const | กำหนดว่าวัตถุ [TypeInfo](./) ปัจจุบันและที่ระบุเท่ากันหรือไม่ |
| **bool** [operator==](./operator_equal_equal/)(std::nullptr_t) const | กำหนดว่าวัตถุ [TypeInfo](./) ปัจจุบันเป็นวัตถุ null หรือไม่, คือ ไม่แทนประเภทใด |
| void [reset](./reset/)() | ตั้งค่า [TypeInfo](./) เป็น null |
| void [set_IsValueType](./set_isvaluetype/)(**bool**) | ตั้งค่าที่บ่งชี้ว่า Type เป็นประเภทค่า |
| void [SetBaseType](./setbasetype/)(GetTypeInfoFunPtr) | ตั้งค่าตัวบรรยายประเภทฐาน |
| void [SetTemplParamType](./settemplparamtype/)(const [TypeInfo](./)\&) | ตั้งค่าตัวบรรยายประเภทพารามิเตอร์เทมเพลต |
| static **uint32_t** [StringHash](./stringhash/)(const char_t *) | คำนวณ hash สำหรับสตริงที่ระบุ |
| [String](../string/) [ToString](./tostring/)() const | คืนค่าสตริงที่บรรจุชื่อของประเภทที่วัตถุปัจจุบันแทน |
| static const [TypeInfo](./)\& [Type](./type/)() | คืนอ็อบเจ็กต์ [TypeInfo](./) ที่แทนคลาส [TypeInfo](./) |
|  [TypeInfo](./typeinfo/)() | ตัวสร้างค่าเริ่มต้น (ไม่มีการตั้งค่าประเภท) |
|  [TypeInfo](./typeinfo/)(std::nullptr_t) | ตัวสร้างวัตถุ null (ไม่มีการตั้งค่าประเภท) |
|  [TypeInfo](./typeinfo/)(const char_t *) | ตัวสร้าง |
|  [TypeInfo](./typeinfo/)(const char_t *, **uint32_t**) | ตัวสร้าง |
|  [TypeInfo](./typeinfo/)(const std::type_info\&) | ตัวสร้าง |

## ฟิลด์

| ฟิลด์ | คำอธิบาย |
| --- | --- |
| static [EmptyType](./emptytype/) | ค่าคงที่ที่แทนรายการว่างของ [TypeInfo](./) |
| static [EmptyTypes](./emptytypes/) | ค่าคงที่ที่แทนรายการว่างของ [TypeInfo](./) |

## การกำหนดชื่อชนิด

| คำจำกัดความประเภท | คำอธิบาย |
| --- | --- |
| [DefaultConstructor](./defaultconstructor/) | พอยน์เตอร์ฟังก์ชันเพื่อสร้างประเภท |

## ดูเพิ่มเติม

* Namespace [System](../)
* Library [Aspose.Slides](../../)