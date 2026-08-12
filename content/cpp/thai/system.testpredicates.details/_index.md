---
title: "System::TestPredicates::Details"
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: 
type: docs
weight: 937
url: /th/system.testpredicates.details/
---
## ฟังก์ชัน

| ฟังก์ชัน | คำอธิบาย |
| --- | --- |
| std::enable_if_t<\![TypeTraits::IsEnumerable](../system.testpredicates.typetraits/isenumerable/)\<T\>::value, std::string\> [PrintToString](./printtostring/)(const T\&) | พิมพ์วัตถุเป็นสตริงโดยเลือกฟังก์ชันตัวแปลงข้อมูลที่เหมาะสม. |
| std::enable_if_t\<[TypeTraits::IsEnumerable](../system.testpredicates.typetraits/isenumerable/)\<T\>::value, std::string\> [PrintToString](./printtostring/)(const T\&) | พิมพ์คอนเทนเนอร์สไตล์ ICollection เป็นสตริงโดยพิมพ์องค์ประกอบของมัน (ไม่เกิน 32). |
| std::string [PrintToString](./printtostring/)(std::nullptr_t) | พิมพ์ nullptr เป็นสตริง. |
| std::string [PrintToString](./printtostring/)(const [Collections::Generic::IEnumerable](../system.collections.generic/ienumerable/)\<**bool**\>\&) | พิมพ์คอลเลกชัน [IEnumerable<bool>](../system.collections.generic/ienumerable/) เป็นสตริงโดยพิมพ์องค์ประกอบของมัน (ไม่เกิน 32). |
| std::enable_if\<System::Details::HasToString\<T\>::value, std::string\>::type [PrintToStringImpl](./printtostringimpl/)(const [SharedPtr](../system/sharedptr/)\<T\>\&, long long) | พิมพ์ซับคลาส [System::Object](../system/object/) เป็นสตริงโดยใช้เมธอด ToString(). |
| std::enable_if\<System::Details::HasToString\<T\>::value, std::string\>::type [PrintToStringImpl](./printtostringimpl/)(const [WeakPtr](../system/weakptr/)\<T\>\&, long long) | พิมพ์ซับคลาส [System::Object](../system/object/) เป็นสตริงโดยใช้เมธอด ToString(). |
| std::enable_if<\![TypeTraits::has_print_to_method](../system.testpredicates.typetraits/has_print_to_method/)\<T\>::value\&&System::Details::HasToString\<T\>::value, std::string\>::type [PrintToStringImpl](./printtostringimpl/)(const T\&, long long) | พิมพ์วัตถุเป็นสตริงโดยใช้เมธอด ToString(). |
| std::enable_if\<[TypeTraits::has_print_to_method](../system.testpredicates.typetraits/has_print_to_method/)\<T\>::value\&&\![TypeTraits::IsEnumerable](../system.testpredicates.typetraits/isenumerable/)\<T\>::value, std::string\>::type [PrintToStringImpl](./printtostringimpl/)(const T\&, long long) | พิมพ์วัตถุเป็นสตริงโดยใช้เมธอด PrintTo. |
| std::enable_if\<[TypeTraits::has_print_to_method](../system.testpredicates.typetraits/has_print_to_method/)\<T\>::value\&&[TypeTraits::IsEnumerable](../system.testpredicates.typetraits/isenumerable/)\<T\>::value, std::string\>::type [PrintToStringImpl](./printtostringimpl/)(const T\&, long long) | พิมพ์วัตถุเป็นสตริงโดยใช้เมธอด PrintTo. |
| std::string [PrintToStringImpl](./printtostringimpl/)(const std::pair\<T1, T2\>\&, long long) | พิมพ์คู่เป็นสตริง. |
| std::string [PrintToStringImpl](./printtostringimpl/)(const [Collections::Generic::KeyValuePair](../system.collections.generic/keyvaluepair/)\<T1, T2\>\&, long long) | พิมพ์คู่เป็นสตริง. |
| std::enable_if\<[TypeTraits::IsCppContainer](../system.testpredicates.typetraits/iscppcontainer/)\<T\>::value\&&\!std::is_base_of\<[Object](../system/object/), T\>::value, std::string\>::type [PrintToStringImpl](./printtostringimpl/)(const T\&, long long) | พิมพ์คอนเทนเนอร์สไตล์ STL เป็นสตริงโดยพิมพ์องค์ประกอบของมัน (ไม่เกิน 32). |
| std::string [PrintToStringImpl](./printtostringimpl/)(const T\&, int) | พิมพ์ชนิดอื่นเป็นสตริงโดยใช้ฟังก์ชันที่ gtest จัดหาไว้. |
| testing::AssertionResult [EqFailure](./eqfailure/)(const char *, const char *, T1\&, T2\&) | จัดรูปแบบข้อผิดพลาดการอ้างอิง == เพื่อแสดงผล. |
| testing::AssertionResult [NotEqFailure](./noteqfailure/)(const char *, const char *, T1\&, T2\&) | จัดรูปแบบข้อผิดพลาดการอ้างอิง != เพื่อแสดงผล. |
| testing::AssertionResult [SameFailure](./samefailure/)(const char *, const char *, T1\&, T2\&) | จัดรูปแบบข้อผิดพลาดการอ้างอิง 'same' เพื่อแสดงผล. |
| testing::AssertionResult [NotSameFailure](./notsamefailure/)(const char *, const char *, T1\&, T2\&) | จัดรูปแบบข้อผิดพลาดการอ้างอิง 'not same' เพื่อแสดงผล. |