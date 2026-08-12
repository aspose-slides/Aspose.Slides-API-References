---
title: BasicSystemIOStreamWrapper
second_title: Aspose.Slides สำหรับ C++ API Reference
description: "เป็นตัวห่อคล้าย std::iostream ที่ใช้ BasicSystemIOStreamBuf เป็นบัฟเฟอร์ภายใน."
type: docs
weight: 53
url: /th/system.io/basicsystemiostreamwrapper/
---
## BasicSystemIOStreamWrapper คลาส

เป็นตัวห่อคล้าย std::iostream ที่ใช้ [BasicSystemIOStreamBuf](../basicsystemiostreambuf/) เป็นบัฟเฟอร์ภายใน.

```cpp
template<typename Elem,typename Traits>class BasicSystemIOStreamWrapper : public std::basic_iostream<Elem, std::char_traits<Elem>>
```

## เมธอด

| Method | Description |
| --- | --- |
| void [AssignRV](./assignrv/)([BasicSystemIOStreamWrapper](./)\&&) | ถูกใช้ในตัวสร้างย้ายและตัวดำเนินการกำหนดค่าแบบย้ายเพื่อรีเซ็ตพอยน์เตอร์และเรียก [swap()](./swap/). |
|  [BasicSystemIOStreamWrapper](./basicsystemiostreamwrapper/)([SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>, [SystemIOStreamWrappingMode](../systemiostreamwrappingmode/)) | สร้างอินสแตนซ์ใหม่ของ [BasicSystemIOStreamWrapper](./). |
|  [BasicSystemIOStreamWrapper](./basicsystemiostreamwrapper/)(const [BasicSystemIOStreamWrapper](./)\&) | ตัวสร้างสำเนา. ถูกลบ. |
|  [BasicSystemIOStreamWrapper](./basicsystemiostreamwrapper/)([BasicSystemIOStreamWrapper](./)\&&) | ตัวสร้างย้าย. |
| [BasicSystemIOStreamWrapper](./)\& [operator=](./operator_equal/)(const [BasicSystemIOStreamWrapper](./)\&) | ตัวดำเนินการกำหนดค่าแบบสำเนา. ถูกลบ. |
| [BasicSystemIOStreamWrapper](./)\& [operator=](./operator_equal/)([BasicSystemIOStreamWrapper](./)\&&) | ตัวดำเนินการกำหนดค่าแบบย้าย. |
| void [swap](./swap/)([BasicSystemIOStreamWrapper](./)\&) | เรียกเพื่อสลับ *this และ **right** หากไม่เท่ากัน. |
## การนิยามชนิด

| Typedef | Description |
| --- | --- |
| [char_type](./char_type/) |  |
| [traits_type](./traits_type/) |  |
| [Mybase](./mybase/) |  |
| [Mysb](./mysb/) |  |
## ดูเพิ่มเติม

* เนมสเปซ [System::IO](../)
* ไลบรารี [Aspose.Slides](../../)