---
title: BasicSystemIStreamWrapper
second_title: Aspose.Slides สำหรับ C++ API Reference
description: "แทนการทำงานของ wrapper ที่มีลักษณะคล้าย std::istream ซึ่งใช้ BasicSystemIOStreamBuf เป็นบัฟเฟอร์ภายใน."
type: docs
weight: 66
url: /th/system.io/basicsystemistreamwrapper/
---
## BasicSystemIStreamWrapper คลาส

แทนการทำงานของ wrapper ที่มีลักษณะคล้าย std::istream ซึ่งใช้ [BasicSystemIOStreamBuf](../basicsystemiostreambuf/) เป็นบัฟเฟอร์ภายใน.

```cpp
template<typename Elem,typename Traits>class BasicSystemIStreamWrapper : public std::basic_istream<Elem, std::char_traits<Elem>>
```

## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| void [AssignRV](./assignrv/)([BasicSystemIStreamWrapper](./)\&&) | ใช้ในคอนสตรัคเตอร์การย้ายและโอเปอเรเตอร์การกำหนดค่าแบบย้ายเพื่อรีเซ็ตพอยน์เตอร์และเรียก [swap()](./swap/). |
|  [BasicSystemIStreamWrapper](./basicsystemistreamwrapper/)([SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>, [SystemIOStreamWrappingMode](../systemiostreamwrappingmode/)) | สร้างอินสแตนซ์ใหม่ของ [BasicSystemIStreamWrapper](./). |
|  [BasicSystemIStreamWrapper](./basicsystemistreamwrapper/)(const [BasicSystemIStreamWrapper](./)\&) | คอนสตรัคเตอร์คัดลอก ถูกลบ. |
|  [BasicSystemIStreamWrapper](./basicsystemistreamwrapper/)([BasicSystemIStreamWrapper](./)\&&) | คอนสตรัคเตอร์การย้าย. |
| [BasicSystemIStreamWrapper](./)\& [operator=](./operator_equal/)(const [BasicSystemIStreamWrapper](./)\&) | โอเปอเรเตอร์การกำหนดค่าคัดลอก ถูกลบ. |
| [BasicSystemIStreamWrapper](./)\& [operator=](./operator_equal/)([BasicSystemIStreamWrapper](./)\&&) | โอเปอเรเตอร์การกำหนดค่าการย้าย. |
| void [swap](./swap/)([BasicSystemIStreamWrapper](./)\&) | เรียกสลับ *this และ **right** หากไม่เท่ากัน. |
## การนิยามประเภท

| การนิยาม | คำอธิบาย |
| --- | --- |
| [char_type](./char_type/) |  |
| [traits_type](./traits_type/) |  |
| [Mybase](./mybase/) |  |
| [Mysb](./mysb/) |  |
## ดูเพิ่มเติม

* เนมสเปซ [System::IO](../)
* ไลบรารี [Aspose.Slides](../../)