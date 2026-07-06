---
title: AsArgumentOfFunction
second_title: Aspose.Sildes cho .NET Tham chiếu API
description: Thực hiện hàm được chỉ định, sử dụng thể hiện này làm đối số
type: docs
weight: 20
url: /vi/aspose.slides.mathtext/imathelement/asargumentoffunction/
---
## AsArgumentOfFunction(IMathElement) {#asargumentoffunction}

Thực hiện hàm đã chỉ định, sử dụng thể hiện này làm đối số

```csharp
public IMathFunction AsArgumentOfFunction(IMathElement functionName)
```

| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| functionName | IMathElement | Tên hàm |

### Giá trị trả về

Phần tử toán học mới loại [`IMathFunction`](../../imathfunction)

### Ví dụ

Ví dụ:

```csharp
[C#]
IMathElement functionName = new MathematicalText("sin");
IMathElement functionArg = new MathematicalText("x");
IMathFunction func = functionArg.AsArgumentOfFunction(functionName);
```

### Xem thêm

* giao diện [IMathFunction](../../imathfunction)
* giao diện [IMathElement](../../imathelement)
* không gian tên [Aspose.Slides.MathText](../../imathelement)
* tập hợp [Aspose.Slides](../../../)

---

## AsArgumentOfFunction(string) {#asargumentoffunction_4}

Thực hiện hàm đã chỉ định, sử dụng thể hiện này làm đối số

```csharp
public IMathFunction AsArgumentOfFunction(string functionName)
```

| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| functionName | String | Tên hàm |

### Giá trị trả về

Phần tử toán học mới loại [`IMathFunction`](../../imathfunction)

### Ví dụ

Ví dụ:

```csharp
[C#]
IMathElement functionArg = new MathematicalText("x");
IMathFunction func = functionArg.AsArgumentOfFunction("cos");
```

### Xem thêm

* giao diện [IMathFunction](../../imathfunction)
* giao diện [IMathElement](../../imathelement)
* không gian tên [Aspose.Slides.MathText](../../imathelement)
* tập hợp [Aspose.Slides](../../../)

---

## AsArgumentOfFunction(MathFunctionsOfOneArgument) {#asargumentoffunction_1}

Thực hiện hàm đã chỉ định, sử dụng thể hiện này làm đối số

```csharp
public IMathFunction AsArgumentOfFunction(MathFunctionsOfOneArgument functionType)
```

| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| functionType | MathFunctionsOfOneArgument | Một trong các loại hàm chung có một đối số |

### Giá trị trả về

Phần tử toán học mới loại [`IMathFunction`](../../imathfunction)

### Ví dụ

Ví dụ:

```csharp
[C#]
IMathElement functionArg = new MathematicalText("x");
IMathFunction func = functionArg.AsArgumentOfFunction(MathFunctionsOfOneArgument.ArcSin);
```

### Xem thêm

* giao diện [IMathFunction](../../imathfunction)
* enum [MathFunctionsOfOneArgument](../../mathfunctionsofoneargument)
* giao diện [IMathElement](../../imathelement)
* không gian tên [Aspose.Slides.MathText](../../imathelement)
* tập hợp [Aspose.Slides](../../../)

---

## AsArgumentOfFunction(MathFunctionsOfTwoArguments, IMathElement) {#asargumentoffunction_2}

Thực hiện hàm đã chỉ định, sử dụng thể hiện này làm đối số và thêm đối số bổ sung đã chỉ định

```csharp
public IMathFunction AsArgumentOfFunction(MathFunctionsOfTwoArguments functionType, 
    IMathElement additionalArgument)
```

| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| functionType | MathFunctionsOfTwoArguments | Một trong các loại hàm chung có hai đối số: Log, Lim, Min, Max |
| additionalArgument | IMathElement | Đối số bổ sung tùy thuộc vào loại hàm |

### Giá trị trả về

Phần tử toán học mới loại [`IMathFunction`](../../imathfunction)

### Ví dụ

Ví dụ:

```csharp
[C#]
IMathElement functionArg = new MathematicalText("x");
IMathElement logarithmBase = new MathematicalText("5");
IMathFunction func = functionArg.AsArgumentOfFunction(MathFunctionsOfTwoArguments.Log, logarithmBase); // Trả về logarit của 'x' với cơ số '5'
```

### Xem thêm

* giao diện [IMathFunction](../../imathfunction)
* enum [MathFunctionsOfTwoArguments](../../mathfunctionsoftwoarguments)
* giao diện [IMathElement](../../imathelement)
* không gian tên [Aspose.Slides.MathText](../../imathelement)
* tập hợp [Aspose.Slides](../../../)

---

## AsArgumentOfFunction(MathFunctionsOfTwoArguments, string) {#asargumentoffunction_3}

Thực hiện hàm đã chỉ định, sử dụng thể hiện này làm đối số và thêm đối số bổ sung đã chỉ định

```csharp
public IMathFunction AsArgumentOfFunction(MathFunctionsOfTwoArguments functionType, 
    string additionalArgument)
```

| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| functionType | MathFunctionsOfTwoArguments | Một trong các loại hàm chung có hai đối số: Log, Lim, Min, Max |
| additionalArgument | String | Đối số bổ sung tùy thuộc vào loại hàm |

### Giá trị trả về

Phần tử toán học mới loại [`IMathFunction`](../../imathfunction)

### Ví dụ

Ví dụ:

```csharp
[C#]
IMathElement functionArg = new MathematicalText("x");
IMathFunction func = functionArg.AsArgumentOfFunction(MathFunctionsOfTwoArguments.Log, "5"); // Trả về logarit của 'x' với cơ số '5'
```

### Xem thêm

* giao diện [IMathFunction](../../imathfunction)
* enum [MathFunctionsOfTwoArguments](../../mathfunctionsoftwoarguments)
* giao diện [IMathElement](../../imathelement)
* không gian tên [Aspose.Slides.MathText](../../imathelement)
* tập hợp [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->