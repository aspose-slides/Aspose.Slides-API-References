---
title: AsArgumentOfFunction
second_title: Aspose.Sildes สำหรับ .NET API Reference
description: รับฟังก์ชันที่ระบุโดยใช้อินสแตนซ์นี้เป็นอาร์กิวเมนต์
type: docs
weight: 20
url: /th/aspose.slides.mathtext/imathelement/asargumentoffunction/
---
## AsArgumentOfFunction(IMathElement) {#asargumentoffunction}

รับฟังก์ชันที่ระบุโดยใช้อินสแตนซ์นี้เป็นอาร์กิวเมนต์

```csharp
public IMathFunction AsArgumentOfFunction(IMathElement functionName)
```

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| functionName | IMathElement | ชื่อฟังก์ชัน |

### ค่าที่ส่งกลับ

อิลิเมนต์คณิตศาสตร์ใหม่ประเภท [`IMathFunction`](../../imathfunction)

### ตัวอย่าง

ตัวอย่าง:

```csharp
[C#]
IMathElement functionName = new MathematicalText("sin");
IMathElement functionArg = new MathematicalText("x");
IMathFunction func = functionArg.AsArgumentOfFunction(functionName);
```

### ดูเพิ่มเติม

* อินเทอร์เฟซ [IMathFunction](../../imathfunction)
* อินเทอร์เฟซ [IMathElement](../../imathelement)
* เนมสเปซ [Aspose.Slides.MathText](../../imathelement)
* แอสเซมบลี [Aspose.Slides](../../../)

---

## AsArgumentOfFunction(string) {#asargumentoffunction_4}

รับฟังก์ชันที่ระบุโดยใช้อินสแตนซ์นี้เป็นอาร์กิวเมนต์

```csharp
public IMathFunction AsArgumentOfFunction(string functionName)
```

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| functionName | String | ชื่อฟังก์ชัน |

### ค่าที่ส่งกลับ

อิลิเมนต์คณิตศาสตร์ใหม่ประเภท [`IMathFunction`](../../imathfunction)

### ตัวอย่าง

ตัวอย่าง:

```csharp
[C#]
IMathElement functionArg = new MathematicalText("x");
IMathFunction func = functionArg.AsArgumentOfFunction("cos");
```

### ดูเพิ่มเติม

* อินเทอร์เฟซ [IMathFunction](../../imathfunction)
* อินเทอร์เฟซ [IMathElement](../../imathelement)
* เนมสเปซ [Aspose.Slides.MathText](../../imathelement)
* แอสเซมบลี [Aspose.Slides](../../../)

---

## AsArgumentOfFunction(MathFunctionsOfOneArgument) {#asargumentoffunction_1}

รับฟังก์ชันที่ระบุโดยใช้อินสแตนซ์นี้เป็นอาร์กิวเมนต์

```csharp
public IMathFunction AsArgumentOfFunction(MathFunctionsOfOneArgument functionType)
```

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| functionType | MathFunctionsOfOneArgument | หนึ่งในประเภทฟังก์ชันทั่วไปที่รับอาร์กิวเมนต์เดียว |

### ค่าที่ส่งกลับ

อิลิเมนต์คณิตศาสตร์ใหม่ประเภท [`IMathFunction`](../../imathfunction)

### ตัวอย่าง

ตัวอย่าง:

```csharp
[C#]
IMathElement functionArg = new MathematicalText("x");
IMathFunction func = functionArg.AsArgumentOfFunction(MathFunctionsOfOneArgument.ArcSin);
```

### ดูเพิ่มเติม

* อินเทอร์เฟซ [IMathFunction](../../imathfunction)
* แบบนับ [MathFunctionsOfOneArgument](../../mathfunctionsofoneargument)
* อินเทอร์เฟซ [IMathElement](../../imathelement)
* เนมสเปซ [Aspose.Slides.MathText](../../imathelement)
* แอสเซมบลี [Aspose.Slides](../../../)

---

## AsArgumentOfFunction(MathFunctionsOfTwoArguments, IMathElement) {#asargumentoffunction_2}

รับฟังก์ชันที่ระบุโดยใช้อินสแตนซ์นี้เป็นอาร์กิวเมนต์และอาร์กิวเมนต์เพิ่มเติมที่ระบุ

```csharp
public IMathFunction AsArgumentOfFunction(MathFunctionsOfTwoArguments functionType, 
    IMathElement additionalArgument)
```

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| functionType | MathFunctionsOfTwoArguments | หนึ่งในประเภทฟังก์ชันทั่วไปที่รับอาร์กิวเมนต์สองตัว: Log, Lim, Min, Max |
| additionalArgument | IMathElement | อาร์กิวเมนต์เพิ่มเติมขึ้นอยู่กับประเภทของฟังก์ชัน |

### ค่าที่ส่งกลับ

อิลิเมนต์คณิตศาสตร์ใหม่ประเภท [`IMathFunction`](../../imathfunction)

### ตัวอย่าง

ตัวอย่าง:

```csharp
[C#]
IMathElement functionArg = new MathematicalText("x");
IMathElement logarithmBase = new MathematicalText("5");
IMathFunction func = functionArg.AsArgumentOfFunction(MathFunctionsOfTwoArguments.Log, logarithmBase); // คืนค่าลอการิทึมของ 'x' ฐาน '5'
```

### ดูเพิ่มเติม

* อินเทอร์เฟซ [IMathFunction](../../imathfunction)
* แบบนับ [MathFunctionsOfTwoArguments](../../mathfunctionsoftwoarguments)
* อินเทอร์เฟซ [IMathElement](../../imathelement)
* เนมสเปซ [Aspose.Slides.MathText](../../imathelement)
* แอสเซมบลี [Aspose.Slides](../../../)

---

## AsArgumentOfFunction(MathFunctionsOfTwoArguments, string) {#asargumentoffunction_3}

รับฟังก์ชันที่ระบุโดยใช้อินสแตนซ์นี้เป็นอาร์กิวเมนต์และอาร์กิวเมนต์เพิ่มเติมที่ระบุ

```csharp
public IMathFunction AsArgumentOfFunction(MathFunctionsOfTwoArguments functionType, 
    string additionalArgument)
```

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| functionType | MathFunctionsOfTwoArguments | หนึ่งในประเภทฟังก์ชันทั่วไปที่รับอาร์กิวเมนต์สองตัว: Log, Lim, Min, Max |
| additionalArgument | String | อาร์กิวเมนต์เพิ่มเติมขึ้นอยู่กับประเภทของฟังก์ชัน |

### ค่าที่ส่งกลับ

อิลิเมนต์คณิตศาสตร์ใหม่ประเภท [`IMathFunction`](../../imathfunction)

### ตัวอย่าง

ตัวอย่าง:

```csharp
[C#]
IMathElement functionArg = new MathematicalText("x");
IMathFunction func = functionArg.AsArgumentOfFunction(MathFunctionsOfTwoArguments.Log, "5"); // คืนค่าลอการิทึมของ 'x' ฐาน '5'
```

### ดูเพิ่มเติม

* อินเทอร์เฟซ [IMathFunction](../../imathfunction)
* แบบนับ [MathFunctionsOfTwoArguments](../../mathfunctionsoftwoarguments)
* อินเทอร์เฟซ [IMathElement](../../imathelement)
* เนมสเปซ [Aspose.Slides.MathText](../../imathelement)
* แอสเซมบลี [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->