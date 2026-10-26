---
title: BasicSystemIOStreamBuf
second_title: Aspose.Slides สำหรับ C++ API Reference
description: "เป็นบัฟเฟอร์ที่ห่อหุ้มสตรีมแบบ System::IO::Stream และทำให้สามารถใช้เป็นบัฟเฟอร์ภายในของสตรีมแบบ std::iostream"
type: docs
weight: 40
url: /th/system.io/basicsystemiostreambuf/
---
## BasicSystemIOStreamBuf คลาส

Represents a buffer that wraps [System::IO::Stream](../stream/)-like streams and allows them to be used as an std::iostream-like streams internal buffer.

```cpp
template<typename Elem,typename Traits>class BasicSystemIOStreamBuf : public std::basic_streambuf<Elem, std::char_traits<Elem>>
```

## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| void [AssignRV](./assignrv/)([BasicSystemIOStreamBuf](./)\&&) | Used in move constructor and move assignment operator to reset pointers and call [swap()](./swap/). |
| explicit  [BasicSystemIOStreamBuf](./basicsystemiostreambuf/)() | Constructs a new instance of the [BasicSystemIOStreamBuf](./). |
| explicit  [BasicSystemIOStreamBuf](./basicsystemiostreambuf/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>\&, [SystemIOStreamWrappingMode](../systemiostreamwrappingmode/), const std::locale\&) | Constructs a new instance of the [BasicSystemIOStreamBuf](./). |
|  [BasicSystemIOStreamBuf](./basicsystemiostreambuf/)(const [BasicSystemIOStreamBuf](./)\&) | Copy constructor. Deleted. |
|  [BasicSystemIOStreamBuf](./basicsystemiostreambuf/)([BasicSystemIOStreamBuf](./)\&&) | Move constructor. |
| [BasicSystemIOStreamBuf](./)\& [operator=](./operator_equal/)(const [BasicSystemIOStreamBuf](./)\&) | Copy assignment operator. Deleted. |
| [BasicSystemIOStreamBuf](./)\& [operator=](./operator_equal/)([BasicSystemIOStreamBuf](./)\&&) | Move assignment operator. |
| void [swap](./swap/)([BasicSystemIOStreamBuf](./)\&) | Call to swap *this and right, if they are not equal. |
|  [~BasicSystemIOStreamBuf](./~basicsystemiostreambuf/)() override | Destructor. |
## การกำหนดประเภท

| การกำหนดประเภท | คำอธิบาย |
| --- | --- |
| [char_type](./char_type/) |  |
| [traits_type](./traits_type/) |  |
| [Mysb](./mysb/) |  |
| [int_type](./int_type/) |  |
| [pos_type](./pos_type/) |  |
| [off_type](./off_type/) |  |
## ดูเพิ่มเติม

* เนมสเปซ [System::IO](../)
* ไลบรารี [Aspose.Slides](../../)