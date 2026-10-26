---
title: "System::TestPredicates::TypeTraits"
second_title: Aspose.Slides สำหรับ C++ API Reference
description: 
type: docs
weight: 963
url: /th/system.testpredicates.typetraits/
---
## โครงสร้าง

| โครงสร้าง | คำอธิบาย |
| --- | --- |
| [has_data_method](./has_data_method/) | ตรวจสอบว่าชนิดมีเมธอด data() หรือไม่ หากมี จะสืบทอด std::true_type มิฉะนั้นจะสืบทอด std::false_type. |
| [has_data_method< System::Collections::BitArray, void >](./has_data_method_tmpl_system_collections_bitarray__void__end_tmpl/) | การกำหนดเฉพาะสำหรับชนิด BitArray ที่ให้ boost type ซึ่งไม่สามารถเข้าถึงได้ที่นั่น. |
| [has_print_to_method](./has_print_to_method/) | ตรวจสอบการโอเวอร์โหลดของฟังก์ชัน PrintTo ที่รับชนิดที่กำหนดเป็นอาร์กิวเมนต์แรก หากมีการโอเวอร์โหลด จะสืบทอด std::true_type มิฉะนั้นจะสืบทอด std::false_type. |
| [IsCppContainer](./iscppcontainer/) | ตรวจสอบว่าชนิดเฉพาะเป็นคอนเทนเนอร์แบบ STL หรือไม่ เพื่อทำเช่นนั้นจะตรวจสอบการมีอยู่ของสมาชิกประเภท iterator และ const_iterator หากทั้งสองมีอยู่ จะสืบทอด std::true_type มิฉะนั้นจะสืบทอด std::false_type. |
| [IsEnumerable](./isenumerable/) | ตรวจสอบว่าชนิดมีการกำหนดเฉพาะ [System::Collections::Generic::IEnumerable](../system.collections.generic/ienumerable/) เป็นฐานหรือไม่ หากใช่ ค่าสมาชิก value จะตั้งเป็น true มิฉะนั้นจะตั้งเป็น false. |
| [LargestFPType](./largestfptype/) | ให้นามแฝงสำหรับชนิด floating point ที่ยาวที่สุดที่มีอยู่ จะละเลยชนิดที่ไม่ใช่ floating point. |
## การนิยามชนิด

| การนิยามชนิด | คำอธิบาย |
| --- | --- |
| [AreFPandArithmetic](./arefpandarithmetic/) | ตรวจสอบว่า **T1** เป็นประเภทเลขคณิตและ **T2** เป็น floating point หรือกลับกัน หากใช่ จะตั้งค่าสมาชิก value เป็น true มิฉะนั้นจะเป็น false. |
| [AnyOfDecimal](./anyofdecimal/) | ตรวจสอบว่ามีอาร์กิวเมนต์ชนิดอย่างน้อยหนึ่งที่เป็น [System::Decimal](../system/decimal/) หรือไม่ หากใช่ จะตั้งค่าสมาชิก value เป็น true มิฉะนั้นจะเป็น false. |
| [IsArray](./isarray/) | ตรวจสอบว่าชนิดเป็นการกำหนดเฉพาะ [System::Array](../system/array/) หรือไม่ หากใช่ ค่าสมาชิก value จะตั้งเป็น true มิฉะนั้นจะตั้งเป็น false. |
| [IsList](./islist/) | ตรวจสอบว่าชนิดเป็นการกำหนดเฉพาะ [System::Collections::Generic::List](../system.collections.generic/list/) หรือไม่ หากใช่ ค่าสมาชิก value จะตั้งเป็น true มิฉะนั้นจะตั้งเป็น false. |
| [BothArrayOrList](./botharrayorlist/) | ตรวจสอบว่าทั้งสองอาร์กิวเมนต์ชนิดเป็นอาร์เรย์หรือรายการหรือไม่ หากใช่ ค่าสมาชิก value จะตั้งเป็น true มิฉะนั้นจะตั้งเป็น false. |
| [BothEnumerable](./bothenumerable/) | ตรวจสอบว่าทั้งสองอาร์กิวเมนต์ชนิดเป็น IEnumerable หรือไม่ หากใช่ ค่าสมาชิก value จะตั้งเป็น true มิฉะนั้นจะตั้งเป็น false. |