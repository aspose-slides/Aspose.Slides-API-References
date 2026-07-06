---
title: AsArgumentOfFunction
second_title: Tham chiếu API Aspose.Sildes cho .NET
description: Sử dụng hàm được chỉ định, truyền đối tượng này làm đối số
type: docs
weight: 20
url: /vi/aspose.slides.mathtext/mathelementbase/asargumentoffunction/
---
## AsArgumentOfFunction(IMathElement) {#asargumentoffunction}

Sử dụng hàm được chỉ định, truyền đối tượng này làm đối số

```csharp
public IMathFunction AsArgumentOfFunction(IMathElement functionName)
```

| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| functionName | IMathElement | Function name |

### Giá trị trả về

Phần tử toán học mới loại [`IMathFunction`](../../imathfunction)

### Ví dụ

Example:

```csharp
[C#]
IMathElement functionName = new MathematicalText("sin");
IMathElement functionArg = new MathematicalText("x");
IMathFunction func = functionArg.AsArgumentOfFunction(functionName);
```

### Xem thêm

* interface [IMathFunction](../../imathfunction)
* interface [IMathElement](../../imathelement)
* class [MathElementBase](../../mathelementbase)
* namespace [Aspose.Slides.MathText](../../mathelementbase)
* assembly [Aspose.Slides](../../../)

---

## AsArgumentOfFunction(string) {#asargumentoffunction_4}

Sử dụng hàm được chỉ định, truyền đối tượng này làm đối số

```csharp
public IMathFunction AsArgumentOfFunction(string functionName)
```

| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| functionName | String | Function name |

### Giá trị trả về

Phần tử toán học mới loại [`IMathFunction`](../../imathfunction)

### Ví dụ

Example:

```csharp
[C#]
IMathElement functionArg = new MathematicalText("x");
IMathFunction func = functionArg.AsArgumentOfFunction("cos");
```

### Xem thêm

* interface [IMathFunction](../../imathfunction)
* class [MathElementBase](../../mathelementbase)
* namespace [Aspose.Slides.MathText](../../mathelementbase)
* assembly [Aspose.Slides](../../../)

---

## AsArgumentOfFunction(MathFunctionsOfOneArgument) {#asargumentoffunction_1}

Sử dụng hàm được chỉ định, truyền đối tượng này làm đối số

```csharp
public IMathFunction AsArgumentOfFunction(MathFunctionsOfOneArgument functionType)
```

| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| functionType | MathFunctionsOfOneArgument | Một trong các loại hàm phổ biến có một đối số |

### Giá trị trả về

Phần tử toán học mới loại [`IMathFunction`](../../imathfunction)

### Ví dụ

Example:

```csharp
[C#]
IMathElement functionName = new MathematicalText("sin");
IMathElement functionArg = new MathematicalText("x");
IMathFunction func = functionArg.AsArgumentOfFunction(functionName);
```

### Xem thêm

* interface [IMathFunction](../../imathfunction)
* enum [MathFunctionsOfOneArgument](../../mathfunctionsofoneargument)
* class [MathElementBase](../../mathelementbase)
* namespace [Aspose.Slides.MathText](../../mathelementbase)
* assembly [Aspose.Slides](../../../)

---

## AsArgumentOfFunction(MathFunctionsOfTwoArguments, IMathElement) {#asargumentoffunction_2}

Sử dụng hàm được chỉ định, truyền đối tượng này làm đối số và đối số bổ sung được chỉ định

```csharp
public IMathFunction AsArgumentOfFunction(MathFunctionsOfTwoArguments functionType, 
    IMathElement additionalArgument)
```

| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| functionType | MathFunctionsOfTwoArguments | Một trong các loại hàm phổ biến có hai đối số: Log, Lim, Min, Max |
| additionalArgument | IMathElement | Đối số bổ sung phụ thuộc vào loại hàm |

### Giá trị trả về

Phần tử toán học mới loại [`IMathFunction`](../../imathfunction)

### Ví dụ

Example:

```csharp
[C#]
IMathElement functionArg = new MathematicalText("x");
IMathElement logarithmBase = new MathematicalText("5");
IMathFunction func = functionArg.AsArgumentOfFunction(MathFunctionsOfTwoArguments.Log, logarithmBase); // Trả về logarit của 'x' với cơ số '5'
```

### Xem thêm

* interface [IMathFunction](../../imathfunction)
* enum [MathFunctionsOfTwoArguments](../../mathfunctionsoftwoarguments)
* interface [IMathElement](../../imathelement)
* class [MathElementBase](../../mathelementbase)
* namespace [Aspose.Slides.MathText](../../mathelementbase)
* assembly [Aspose.Slides](../../../)

---

## AsArgumentOfFunction(MathFunctionsOfTwoArguments, string) {#asargumentoffunction_3}

Sử dụng hàm được chỉ định, truyền đối tượng này làm đối số và đối số bổ sung được chỉ định

```csharp
public IMathFunction AsArgumentOfFunction(MathFunctionsOfTwoArguments functionType, 
    string additionalArgument)
```

| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| functionType | MathFunctionsOfTwoArguments | Một trong các loại hàm phổ biến có hai đối số: Log, Lim, Min, Max |
| additionalArgument | String | Đối số bổ sung phụ thuộc vào loại hàm |

### Giá trị trả về

Phần tử toán học mới loại [`IMathFunction`](../../imathfunction)

### Ví dụ

Example:

```csharp
[C#]
IMathElement functionArg = new MathematicalText("x");
IMathFunction func = functionArg.AsArgumentOfFunction(MathFunctionsOfTwoArguments.Log, "5"); // Trả về logarit của 'x' với cơ số '5'
```

### Xem thêm

* interface [IMathFunction](../../imathfunction)
* enum [MathFunctionsOfTwoArguments](../../mathfunctionsoftwoarguments)
* class [MathElementBase](../../mathelementbase)
* namespace [Aspose.Slides.MathText](../../mathelementbase)
* assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->