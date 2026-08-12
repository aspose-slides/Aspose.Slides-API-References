---
title: MathNaryOperator()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: สร้างอินสแตนซ์ใหม่ของคลาส MathNaryOperator
type: docs
weight: 183
url: /th/aspose.slides.mathtext/mathnaryoperator/mathnaryoperator/
---
## MathNaryOperator::MathNaryOperator(char16_t, System::SharedPtr\<IMathElement\>, System::SharedPtr\<IMathElement\>, System::SharedPtr\<IMathElement\>) คอนสตรัคเตอร์

สร้างอินสแตนซ์ใหม่ของคลาส [MathNaryOperator](../).

```cpp
Aspose::Slides::MathText::MathNaryOperator::MathNaryOperator(char16_t operatorSymbol, System::SharedPtr<IMathElement> baseArgument, System::SharedPtr<IMathElement> lowerLimit, System::SharedPtr<IMathElement> upperLimit)
```


### อาร์กิวเมนท์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| operatorSymbol | char16_t | สัญลักษณ์ตัวดำเนินการ Nary |
| baseArgument | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | อาร์กิวเมนต์พื้นฐาน |
| lowerLimit | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | ขอบล่าง |
| upperLimit | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | ขอบบน |
## หมายเหตุ



ตัวอย่าง: 
```cpp
auto naryOperator = System::MakeObject<MathNaryOperator>(u'?', System::MakeObject<MathematicalText>(u"i"), System::MakeObject<MathematicalText>(u"i=0"), System::MakeObject<MathematicalText>(u"\U0001d465"));
```

## MathNaryOperator::MathNaryOperator(char16_t, System::SharedPtr\<IMathElement\>, System::SharedPtr\<IMathElement\>) คอนสตรัคเตอร์


สร้างอินสแตนซ์ใหม่ของคลาส [MathNaryOperator](../).

```cpp
Aspose::Slides::MathText::MathNaryOperator::MathNaryOperator(char16_t operatorSymbol, System::SharedPtr<IMathElement> baseArgument, System::SharedPtr<IMathElement> lowerLimit)
```


### อาร์กิวเมนท์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| operatorSymbol | char16_t | สัญลักษณ์ตัวดำเนินการ Nary |
| baseArgument | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | อาร์กิวเมนต์พื้นฐาน |
| lowerLimit | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | ขอบล่าง |
## หมายเหตุ



ตัวอย่าง: 
```cpp
auto naryOperator = System::MakeObject<MathNaryOperator>(u'?', System::MakeObject<MathematicalText>(u"i"), System::MakeObject<MathematicalText>(u"i"));
```

## MathNaryOperator::MathNaryOperator(char16_t, System::SharedPtr\<IMathElement\>) คอนสตรัคเตอร์


สร้างอินสแตนซ์ใหม่ของคลาส [MathNaryOperator](../).

```cpp
Aspose::Slides::MathText::MathNaryOperator::MathNaryOperator(char16_t operatorSymbol, System::SharedPtr<IMathElement> baseArgument)
```


### อาร์กิวเมนท์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| operatorSymbol | char16_t | สัญลักษณ์ตัวดำเนินการ Nary |
| baseArgument | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | อาร์กิวเมนต์พื้นฐาน |
## หมายเหตุ



ตัวอย่าง: 
```cpp
auto naryOperator = System::MakeObject<MathNaryOperator>(u'?', System::MakeObject<MathematicalText>(u"i"));
```

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IMathElement](../../imathelement/)
* Class [MathNaryOperator](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)