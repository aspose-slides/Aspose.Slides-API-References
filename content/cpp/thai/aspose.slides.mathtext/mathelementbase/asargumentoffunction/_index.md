---
title: AsArgumentOfFunction()
second_title: เอกสารอ้างอิง API ของ Aspose.Slides สำหรับ C++
description: รับฟังก์ชันที่ระบุโดยใช้อินสแตนซ์นี้เป็นอาร์กิวเมนต์
type: docs
weight: 53
url: /th/aspose.slides.mathtext/mathelementbase/asargumentoffunction/
---
## MathElementBase::AsArgumentOfFunction(System::SharedPtr\<IMathElement\>) เมธอด


รับฟังก์ชันที่ระบุโดยใช้อินสแตนซ์นี้เป็นอาร์กิวเมนต์

```cpp
System::SharedPtr<IMathFunction> Aspose::Slides::MathText::MathElementBase::AsArgumentOfFunction(System::SharedPtr<IMathElement> functionName) override
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| functionName | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | ชื่อฟังก์ชัน |

### ค่าที่คืน

องค์ประกอบคณิตศาสตร์ใหม่ชนิด [IMathFunction](../../imathfunction/)
## หมายเหตุ



ตัวอย่าง: 
```cpp
auto functionName = System::MakeObject<MathematicalText>(u"sin");
auto functionArg = System::MakeObject<MathematicalText>(u"x");
auto func = functionArg->AsArgumentOfFunction(functionName);
```

## MathElementBase::AsArgumentOfFunction(System::String) เมธอด


รับฟังก์ชันที่ระบุโดยใช้อินสแตนซ์นี้เป็นอาร์กิวเมนต์

```cpp
System::SharedPtr<IMathFunction> Aspose::Slides::MathText::MathElementBase::AsArgumentOfFunction(System::String functionName) override
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| functionName | [System::String](../../../system/string/) | ชื่อฟังก์ชัน |

### ค่าที่คืน

องค์ประกอบคณิตศาสตร์ใหม่ชนิด [IMathFunction](../../imathfunction/)
## หมายเหตุ



ตัวอย่าง: 
```cpp
auto functionArg = System::MakeObject<MathematicalText>(u"x");
auto func = functionArg->AsArgumentOfFunction(u"cos");
```

## MathElementBase::AsArgumentOfFunction(MathFunctionsOfOneArgument) เมธอด


รับฟังก์ชันที่ระบุโดยใช้อินสแตนซ์นี้เป็นอาร์กิวเมนต์

```cpp
System::SharedPtr<IMathFunction> Aspose::Slides::MathText::MathElementBase::AsArgumentOfFunction(MathFunctionsOfOneArgument functionType) override
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| functionType | [MathFunctionsOfOneArgument](../../mathfunctionsofoneargument/) | หนึ่งในประเภทฟังก์ชันทั่วไปที่มีอาร์กิวเมนต์หนึ่ง |

### ค่าที่คืน

องค์ประกอบคณิตศาสตร์ใหม่ชนิด [IMathFunction](../../imathfunction/)
## หมายเหตุ



ตัวอย่าง: 
```cpp
auto functionName = System::MakeObject<MathematicalText>(u"sin");
auto functionArg = System::MakeObject<MathematicalText>(u"x");
auto func = functionArg->AsArgumentOfFunction(functionName);
```

## MathElementBase::AsArgumentOfFunction(MathFunctionsOfTwoArguments, System::SharedPtr\<IMathElement\>) เมธอด


รับฟังก์ชันที่ระบุโดยใช้อินสแตนซ์นี้เป็นอาร์กิวเมนต์และอาร์กิวเมนต์เพิ่มเติมที่ระบุ

```cpp
System::SharedPtr<IMathFunction> Aspose::Slides::MathText::MathElementBase::AsArgumentOfFunction(MathFunctionsOfTwoArguments functionType, System::SharedPtr<IMathElement> additionalArgument) override
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| functionType | [MathFunctionsOfTwoArguments](../../mathfunctionsoftwoarguments/) | หนึ่งในประเภทฟังก์ชันทั่วไปที่มีอาร์กิวเมนต์สอง: Log, Lim, Min, Max |
| additionalArgument | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | อาร์กิวเมนต์เพิ่มเติมขึ้นอยู่กับประเภทของฟังก์ชัน |

### ค่าที่คืน

องค์ประกอบคณิตศาสตร์ใหม่ชนิด [IMathFunction](../../imathfunction/)
## หมายเหตุ



ตัวอย่าง: 
```cpp
auto functionArg = System::MakeObject<MathematicalText>(u"x");
auto logarithmBase = System::MakeObject<MathematicalText>(u"5");
auto func = functionArg->AsArgumentOfFunction(MathFunctionsOfTwoArguments::Log, logarithmBase);
// คืนค่าลอการิทึมของ 'x' ฐาน '5'
```

## MathElementBase::AsArgumentOfFunction(MathFunctionsOfTwoArguments, System::String) เมธอด


รับฟังก์ชันที่ระบุโดยใช้อินสแตนซ์นี้เป็นอาร์กิวเมนต์และอาร์กิวเมนต์เพิ่มเติมที่ระบุ

```cpp
System::SharedPtr<IMathFunction> Aspose::Slides::MathText::MathElementBase::AsArgumentOfFunction(MathFunctionsOfTwoArguments functionType, System::String additionalArgument) override
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| functionType | [MathFunctionsOfTwoArguments](../../mathfunctionsoftwoarguments/) | หนึ่งในประเภทฟังก์ชันทั่วไปที่มีอาร์กิวเมนต์สอง: Log, Lim, Min, Max |
| additionalArgument | [System::String](../../../system/string/) | อาร์กิวเมนต์เพิ่มเติมขึ้นอยู่กับประเภทของฟังก์ชัน |

### ค่าที่คืน

องค์ประกอบคณิตศาสตร์ใหม่ชนิด [IMathFunction](../../imathfunction/)
## หมายเหตุ



ตัวอย่าง: 
```cpp
auto functionArg = System::MakeObject<MathematicalText>(u"x");
auto func = functionArg->AsArgumentOfFunction(MathFunctionsOfTwoArguments::Log, u"5");
// คืนค่าลอการิทึมของ 'x' ฐาน '5'
```

## ดูเพิ่มเติม

* Enum [MathFunctionsOfOneArgument](../../mathfunctionsofoneargument/)
* Enum [MathFunctionsOfTwoArguments](../../mathfunctionsoftwoarguments/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IMathFunction](../../imathfunction/)
* Class [IMathElement](../../imathelement/)
* Class [MathElementBase](../)
* Class [String](../../../system/string/)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)