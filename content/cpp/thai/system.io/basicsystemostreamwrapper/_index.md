---
title: BasicSystemOStreamWrapper
second_title: Aspose.Slides สำหรับเอกสารอ้างอิง API ของ C++
description: "เป็นตัวห่อที่มีลักษณะคล้าย std::ostream ซึ่งใช้ BasicSystemIOStreamBuf เป็นบัฟเฟอร์ภายใน."
type: docs
weight: 79
url: /th/system.io/basicsystemostreamwrapper/
---
## BasicSystemOStreamWrapper คลาส


เป็นตัวห่อที่มีลักษณะคล้าย std::ostream ซึ่งใช้ [BasicSystemIOStreamBuf](../basicsystemiostreambuf/) เป็นบัฟเฟอร์ภายใน.

```cpp
template<typename Elem,typename Traits>class BasicSystemOStreamWrapper : public std::basic_ostream<Elem, std::char_traits<Elem>>
```

## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| void [AssignRV](./assignrv/)([BasicSystemOStreamWrapper](./)\&&) | ใช้ในคอนสตรัคเตอร์แบบย้ายและตัวดำเนินการกำหนดค่าแบบย้ายเพื่อรีเซ็ตพอยเตอร์และเรียก [swap()](./swap/). |
|  [BasicSystemOStreamWrapper](./basicsystemostreamwrapper/)([SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>, [SystemIOStreamWrappingMode](../systemiostreamwrappingmode/)) | สร้างอินสแตนซ์ใหม่ของ [BasicSystemOStreamWrapper](./). |
|  [BasicSystemOStreamWrapper](./basicsystemostreamwrapper/)(const [BasicSystemOStreamWrapper](./)\&) | คอนสตรัคเตอร์คัดลอก. ถูกลบ. |
|  [BasicSystemOStreamWrapper](./basicsystemostreamwrapper/)([BasicSystemOStreamWrapper](./)\&&) | คอนสตรัคเตอร์แบบย้าย. |
| [BasicSystemOStreamWrapper](./)\& [operator=](./operator_equal/)(const [BasicSystemOStreamWrapper](./)\&) | ตัวดำเนินการกำหนดค่าสำเนา. ถูกลบ. |
| [BasicSystemOStreamWrapper](./)\& [operator=](./operator_equal/)([BasicSystemOStreamWrapper](./)\&&) | ตัวดำเนินการกำหนดค่าแบบย้าย. |
| void [swap](./swap/)([BasicSystemOStreamWrapper](./)\&) | เรียกเพื่อสลับ *this และ **right** หากพวกมันไม่เท่ากัน. |

## การนิยามประเภท

| การนิยามประเภท | คำอธิบาย |
| --- | --- |
| [char_type](./char_type/) |  |
| [traits_type](./traits_type/) |  |
| [Mybase](./mybase/) |  |
| [Mysb](./mysb/) |  |

## ดูเพิ่มเติม

* เนมสเปซ [System::IO](../)
* ไลบรารี [Aspose.Slides](../../)