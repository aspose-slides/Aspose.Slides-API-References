---
title: AsArgumentOfFunction()
second_title: Aspose.Slides สำหรับ C++ อ้างอิง API
description: ใช้ฟังก์ชันที่ระบุโดยใช้อินสแตนซ์นี้เป็นอาร์กิวเมนต์
type: docs
weight: 66
url: /th/aspose.slides.mathtext/imathelement/asargumentoffunction/
---
## IMathElement::AsArgumentOfFunction(System::SharedPtr\<IMathElement\>) เมธอด

ใช้ฟังก์ชันที่ระบุโดยใช้อินสแตนซ์นี้เป็นอาร์กิวเมนต์

```cpp
virtual System::SharedPtr<IMathFunction> Aspose::Slides::MathText::IMathElement::AsArgumentOfFunction(System::SharedPtr<IMathElement> functionName)=0
```

### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| functionName | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | ชื่อฟังก์ชัน |

### ค่าที่ส่งกลับ

องค์ประกอบคณิตศาสตร์ใหม่ชนิด [IMathFunction](../../imathfunction/)
## หมายเหตุ



ตัวอย่าง: 
```cpp
auto functionName = System::MakeObject<MathematicalText>(u"sin");
auto functionArg = System::MakeObject<MathematicalText>(u"x");
auto func = functionArg->AsArgumentOfFunction(functionName);
```

## IMathElement::AsArgumentOfFunction(System::String) เมธอด


ใช้ฟังก์ชันที่ระบุโดยใช้อินสแตนซ์นี้เป็นอาร์กิวเมนต์

```cpp
virtual System::SharedPtr<IMathFunction> Aspose::Slides::MathText::IMathElement::AsArgumentOfFunction(System::String functionName)=0
```

### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| functionName | [System::String](../../../system/string/) | ชื่อฟังก์ชัน |

### ค่าที่ส่งกลับ

องค์ประกอบคณิตศาสตร์ใหม่ชนิด [IMathFunction](../../imathfunction/)
## หมายเหตุ



ตัวอย่าง: 
```cpp
auto functionArg = System::MakeObject<MathematicalText>(u"x");
auto func = functionArg->AsArgumentOfFunction(u"cos");
```

## IMathElement::AsArgumentOfFunction(MathFunctionsOfOneArgument) เมธอด


ใช้ฟังก์ชันที่ระบุโดยใช้อินสแตนซ์นี้เป็นอาร์กิวเมนต์

```cpp
virtual System::SharedPtr<IMathFunction> Aspose::Slides::MathText::IMathElement::AsArgumentOfFunction(MathFunctionsOfOneArgument functionType)=0
```

### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| functionType | [MathFunctionsOfOneArgument](../../mathfunctionsofoneargument/) | หนึ่งในประเภทฟังก์ชันทั่วไปของอาร์กิวเมนต์หนึ่ง |

### ค่าที่ส่งกลับ

องค์ประกอบคณิตศาสตร์ใหม่ชนิด [IMathFunction](../../imathfunction/)
## หมายเหตุ



ตัวอย่าง: 
```cpp
auto functionArg = System::MakeObject<MathematicalText>(u"x");
auto func = functionArg->AsArgumentOfFunction(MathFunctionsOfOneArgument::ArcSin);
```

## IMathElement::AsArgumentOfFunction(MathFunctionsOfTwoArguments, System::SharedPtr\<IMathElement\>) เมธอด


ใช้ฟังก์ชันที่ระบุโดยใช้อินสแตนซ์นี้เป็นอาร์กิวเมนต์และอาร์กิวเมนต์เพิ่มเติมที่ระบุ

```cpp
virtual System::SharedPtr<IMathFunction> Aspose::Slides::MathText::IMathElement::AsArgumentOfFunction(MathFunctionsOfTwoArguments functionType, System::SharedPtr<IMathElement> additionalArgument)=0
```

### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| functionType | [MathFunctionsOfTwoArguments](../../mathfunctionsoftwoarguments/) | หนึ่งในประเภทฟังก์ชันทั่วไปของอาร์กิวเมนต์สอง: Log, Lim, Min, Max |
| additionalArgument | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | อาร์กิวเมนต์เพิ่มเติมขึ้นอยู่กับประเภทของฟังก์ชัน |

### ค่าที่ส่งกลับ

องค์ประกอบคณิตศาสตร์ใหม่ชนิด [IMathFunction](../../imathfunction/)
## หมายเหตุ



ตัวอย่าง: 
```cpp
auto functionArg = System::MakeObject<MathematicalText>(u"x");
auto logarithmBase = System::MakeObject<MathematicalText>(u"5");
auto func = functionArg->AsArgumentOfFunction(MathFunctionsOfTwoArguments::Log, logarithmBase);
// คืนค่าลอการิทึมของ 'x' ไปยังฐาน '5'
```

## IMathElement::AsArgumentOfFunction(MathFunctionsOfTwoArguments, System::String) เมธอด


ใช้ฟังก์ชันที่ระบุโดยใช้อินสแตนซ์นี้เป็นอาร์กิวเมนต์และอาร์กิวเมนต์เพิ่มเติมที่ระบุ

```cpp
virtual System::SharedPtr<IMathFunction> Aspose::Slides::MathText::IMathElement::AsArgumentOfFunction(MathFunctionsOfTwoArguments functionType, System::String additionalArgument)=0
```

### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| functionType | [MathFunctionsOfTwoArguments](../../mathfunctionsoftwoarguments/) | หนึ่งในประเภทฟังก์ชันทั่วไปของอาร์กิวเมนต์สอง: Log, Lim, Min, Max |
| additionalArgument | [System::String](../../../system/string/) | อาร์กิวเมนต์เพิ่มเติมขึ้นอยู่กับประเภทของฟังก์ชัน |

### ค่าที่ส่งกลับ

องค์ประกอบคณิตศาสตร์ใหม่ชนิด [IMathFunction](../../imathfunction/)
## หมายเหตุ



ตัวอย่าง: 
```cpp
auto functionArg = System::MakeObject<MathematicalText>(u"x");
auto func = functionArg->AsArgumentOfFunction(MathFunctionsOfTwoArguments::Log, u"5");
// คืนค่าลอการิทึมของ 'x' ไปยังฐาน '5'
```

## ดูเพิ่มเติม

* Enum [MathFunctionsOfOneArgument](../../mathfunctionsofoneargument/)
* Enum [MathFunctionsOfTwoArguments](../../mathfunctionsoftwoarguments/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IMathFunction](../../imathfunction/)
* Class [IMathElement](../)
* Class [String](../../../system/string/)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)