---
title: "System::BoxedValueDetail"
second_title: "อ้างอิง API ของ Aspose.Slides สำหรับ C++"
description: 
type: docs
weight: 287
url: /th/system.boxedvaluedetail/
---
## คลาส

| คลาส | คำอธิบาย |
| --- | --- |
| [Comparable](./comparable/) | การดำเนินการอย่างง่ายของ IComparable<> |
| [NonComparable](./noncomparable/) | ประเภทฐานจำลองสำหรับประเภทที่บรรจุซึ่งไม่ได้ทำการใช้งาน IComparable<> |
## โครงสร้าง

| โครงสร้าง | คำอธิบาย |
| --- | --- |
| [ImplementsInterface](./implementsinterface/) | เทมเพลตพรีดิเคตที่ตรวจสอบว่าวัตถุที่บรรจุควรทำการใช้งานอินเทอร์เฟซที่กำหนดโดยตนเองหรือไม่. |
| [ImplementsInterface< String, IComparable< String > >](./implementsinterface_tmpl_string__icomparable_tmpl_string__end_tmpl__end_tmpl/) | [String](../system/string/) ทำการใช้งาน [IComparable](../system/icomparable/). |
| [ImplementsInterface< T, IComparable< T > >](./implementsinterface_tmpl_t__icomparable_tmpl_t__end_tmpl__end_tmpl/) | เทมเพลตพรีดิเคตที่ตรวจสอบว่าวัตถุที่บรรจุควรทำการใช้งานอินเทอร์เฟซ [IComparable](../system/icomparable/) โดยตนเองหรือไม่. |
## ฟังก์ชัน

| ฟังก์ชัน | คำอธิบาย |
| --- | --- |
| std::enable_if\<detail::has_operator_equal\<T\>::value, **bool**\>::type [Equals](./equals/)(T, T) | กำหนดความเท่ากันของค่าที่ระบุโดยใช้ [operator==()](../system/operator_equal_equal/). |
| std::enable_if\<detail::has_only_method_equals\<T\>::value, **bool**\>::type [Equals](./equals/)(T, T) | กำหนดความเท่ากันของค่าที่ระบุโดยใช้เมธอด [System::Object::Equals()](../system/object/equals/). |
| **bool** [Equals< float >](./equals_less_float__greater/)(**float**, **float**) | เปรียบเทียบค่าจุดลอยแบบความแม่นยำเดียวสองค่า. |
| **bool** [Equals< double >](./equals_less_double__greater/)(**double**, **double**) | เปรียบเทียบค่าจุดลอยแบบความแม่นยำคู่สองค่า. |