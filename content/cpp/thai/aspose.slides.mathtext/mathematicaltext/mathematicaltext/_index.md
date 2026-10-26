---
title: MathematicalText()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: "คอนสตรัคเตอร์เริ่มต้น (สร้างค่า String::Empty)"
type: docs
weight: 40
url: /th/aspose.slides.mathtext/mathematicaltext/mathematicaltext/
---
## MathematicalText::MathematicalText() คอนสตรัคเตอร์

คอนสตรัคเตอร์เริ่มต้น (สร้างค่า String::Empty)

```cpp
Aspose::Slides::MathText::MathematicalText::MathematicalText()
```

## หมายเหตุ

ตัวอย่าง: 
```cpp
auto mathText = System::MakeObject<MathematicalText>();
```

## MathematicalText::MathematicalText(char16_t) คอนสตรัคเตอร์

สร้าง [MathText](../../) ด้วยสัญลักษณ์เดียว

```cpp
Aspose::Slides::MathText::MathematicalText::MathematicalText(char16_t mathSymbol)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| mathSymbol | char16_t | สัญลักษณ์เดียว |
## หมายเหตุ

ตัวอย่าง: 
```cpp
auto mathText = System::MakeObject<MathematicalText>(u'$');
```

## MathematicalText::MathematicalText(System::String) คอนสตรัคเตอร์

สร้าง [MathematicalText](../) จากข้อความ

```cpp
Aspose::Slides::MathText::MathematicalText::MathematicalText(System::String mathText)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| mathText | [System::String](../../../system/string/) | ค่าข้อความ |
## หมะเลย

ตัวอย่าง: 
```cpp
auto mathText = System::MakeObject<MathematicalText>(u"x+y");
```

## MathematicalText::MathematicalText(System::String, System::SharedPtr\<IPortionFormat\>) คอนสตรัคเตอร์

สร้าง [MathematicalText](../) จากข้อความและการตั้งค่าแบบฟอร์แมต

```cpp
Aspose::Slides::MathText::MathematicalText::MathematicalText(System::String mathText, System::SharedPtr<IPortionFormat> portionFormat)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| mathText | [System::String](../../../system/string/) | ค่าข้อความ |
| portionFormat | [System::SharedPtr](../../../system/sharedptr/)\<[IPortionFormat](../../../aspose.slides/iportionformat/)\> | การตั้งค่าแบบฟอร์แมตของข้อความ |
## หมายเหตุ

ตัวอย่าง: 
```cpp
auto format = [&]{ auto tmp_0 = System::MakeObject<PortionFormat>(); tmp_0->set_FontHeight(12); return tmp_0; }();
auto mathText = System::MakeObject<MathematicalText>(u"x+y", format);
```

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [MathematicalText](../)
* Class [String](../../../system/string/)
* Class [IPortionFormat](../../../aspose.slides/iportionformat/)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)