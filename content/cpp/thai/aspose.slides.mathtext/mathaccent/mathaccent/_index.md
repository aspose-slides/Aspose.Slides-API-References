---
title: MathAccent()
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: สร้างเครื่องหมายสำเนียงคณิตศาสตร์ที่ใช้กับองค์ประกอบคณิตศาสตร์ที่ระบุโดยใช้ค่าตัวอักษรสำเนียงเริ่มต้น
type: docs
weight: 40
url: /th/aspose.slides.mathtext/mathaccent/mathaccent/
---
## MathAccent::MathAccent(System::SharedPtr\<IMathElement\>) คอนสตรักเตอร์


สร้างเครื่องหมายสำเนียงคณิตศาสตร์ที่ใช้กับองค์ประกอบคณิตศาสตร์ที่ระบุโดยใช้ค่าตัวอักษรสำเนียงเริ่มต้น

```cpp
Aspose::Slides::MathText::MathAccent::MathAccent(System::SharedPtr<IMathElement> element)
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | องค์ประกอบคณิตศาสตร์ที่ต้องการใส่สำเนียง |
## หมายเหตุ



ตัวอย่าง: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"x");
auto accent = System::MakeObject<MathAccent>(baseElement);
```

## MathAccent::MathAccent(System::SharedPtr\<IMathElement\>, char16_t) คอนสตรักเตอร์


สร้างเครื่องหมายสำเนียงคณิตศาสตร์ที่ใช้กับองค์ประกอบคณิตศาสตร์ที่ระบุ

```cpp
Aspose::Slides::MathText::MathAccent::MathAccent(System::SharedPtr<IMathElement> element, char16_t accentCharacter)
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | องค์ประกอบคณิตศาสตร์ที่ต้องการใส่สำเนียง |
| accentCharacter | char16_t | ตัวอักษรสำเนียง |
## หมายเหตุ



ตัวอย่าง: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"x");
auto accent = System::MakeObject<MathAccent>(baseElement, u'~');
```

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IMathElement](../../imathelement/)
* Class [MathAccent](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)