---
title: AsArgumentOfFunction
second_title: Aspose.Sildes untuk Referensi API .NET
description: Mengambil fungsi yang ditentukan dengan menggunakan instance ini sebagai argumen
type: docs
weight: 20
url: /id/aspose.slides.mathtext/mathelementbase/asargumentoffunction/
---
## AsArgumentOfFunction(IMathElement) {#asargumentoffunction}

Mengambil fungsi yang ditentukan dengan menggunakan instance ini sebagai argumen

```csharp
public IMathFunction AsArgumentOfFunction(IMathElement functionName)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| functionName | IMathElement | Function name |

### Nilai Kembalian

Elemen matematika baru dengan tipe [`IMathFunction`](../../imathfunction)

### Contoh

```csharp
[C#]
IMathElement functionName = new MathematicalText("sin");
IMathElement functionArg = new MathematicalText("x");
IMathFunction func = functionArg.AsArgumentOfFunction(functionName);
```

### Lihat Juga

* antarmuka [IMathFunction](../../imathfunction)
* antarmuka [IMathElement](../../imathelement)
* kelas [MathElementBase](../../mathelementbase)
* ruang nama [Aspose.Slides.MathText](../../mathelementbase)
* rakitan [Aspose.Slides](../../../)

---

## AsArgumentOfFunction(string) {#asargumentoffunction_4}

Mengambil fungsi yang ditentukan dengan menggunakan instance ini sebagai argumen

```csharp
public IMathFunction AsArgumentOfFunction(string functionName)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| functionName | String | Function name |

### Nilai Kembalian

Elemen matematika baru dengan tipe [`IMathFunction`](../../imathfunction)

### Contoh

```csharp
[C#]
IMathElement functionArg = new MathematicalText("x");
IMathFunction func = functionArg.AsArgumentOfFunction("cos");
```

### Lihat Juga

* antarmuka [IMathFunction](../../imathfunction)
* kelas [MathElementBase](../../mathelementbase)
* ruang nama [Aspose.Slides.MathText](../../mathelementbase)
* rakitan [Aspose.Slides](../../../)

---

## AsArgumentOfFunction(MathFunctionsOfOneArgument) {#asargumentoffunction_1}

Mengambil fungsi yang ditentukan dengan menggunakan instance ini sebagai argumen

```csharp
public IMathFunction AsArgumentOfFunction(MathFunctionsOfOneArgument functionType)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| functionType | MathFunctionsOfOneArgument | Salah satu tipe fungsi umum dengan satu argumen |

### Nilai Kembalian

Elemen matematika baru dengan tipe [`IMathFunction`](../../imathfunction)

### Contoh

```csharp
[C#]
IMathElement functionName = new MathematicalText("sin");
IMathElement functionArg = new MathematicalText("x");
IMathFunction func = functionArg.AsArgumentOfFunction(functionName);
```

### Lihat Juga

* antarmuka [IMathFunction](../../imathfunction)
* enum [MathFunctionsOfOneArgument](../../mathfunctionsofoneargument)
* kelas [MathElementBase](../../mathelementbase)
* ruang nama [Aspose.Slides.MathText](../../mathelementbase)
* rakitan [Aspose.Slides](../../../)

---

## AsArgumentOfFunction(MathFunctionsOfTwoArguments, IMathElement) {#asargumentoffunction_2}

Mengambil fungsi yang ditentukan dengan menggunakan instance ini sebagai argumen dan argumen tambahan yang ditentukan

```csharp
public IMathFunction AsArgumentOfFunction(MathFunctionsOfTwoArguments functionType, 
    IMathElement additionalArgument)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| functionType | MathFunctionsOfTwoArguments | Salah satu tipe fungsi umum dengan dua argumen: Log, Lim, Min, Max |
| additionalArgument | IMathElement | Argumen tambahan tergantung pada tipe fungsi |

### Nilai Kembalian

Elemen matematika baru dengan tipe [`IMathFunction`](../../imathfunction)

### Contoh

```csharp
[C#]
IMathElement functionArg = new MathematicalText("x");
IMathElement logarithmBase = new MathematicalText("5");
IMathFunction func = functionArg.AsArgumentOfFunction(MathFunctionsOfTwoArguments.Log, logarithmBase); // Mengembalikan logaritma dari 'x' dengan basis '5'
```

### Lihat Juga

* antarmuka [IMathFunction](../../imathfunction)
* enum [MathFunctionsOfTwoArguments](../../mathfunctionsoftwoarguments)
* antarmuka [IMathElement](../../imathelement)
* kelas [MathElementBase](../../mathelementbase)
* ruang nama [Aspose.Slides.MathText](../../mathelementbase)
* rakitan [Aspose.Slides](../../../)

---

## AsArgumentOfFunction(MathFunctionsOfTwoArguments, string) {#asargumentoffunction_3}

Mengambil fungsi yang ditentukan dengan menggunakan instance ini sebagai argumen dan argumen tambahan yang ditentukan

```csharp
public IMathFunction AsArgumentOfFunction(MathFunctionsOfTwoArguments functionType, 
    string additionalArgument)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| functionType | MathFunctionsOfTwoArguments | Salah satu tipe fungsi umum dengan dua argumen: Log, Lim, Min, Max |
| additionalArgument | String | Argumen tambahan tergantung pada tipe fungsi |

### Nilai Kembalian

Elemen matematika baru dengan tipe [`IMathFunction`](../../imathfunction)

### Contoh

```csharp
[C#]
IMathElement functionArg = new MathematicalText("x");
IMathFunction func = functionArg.AsArgumentOfFunction(MathFunctionsOfTwoArguments.Log, "5"); // Mengembalikan logaritma dari 'x' dengan basis '5'
```

### Lihat Juga

* antarmuka [IMathFunction](../../imathfunction)
* enum [MathFunctionsOfTwoArguments](../../mathfunctionsoftwoarguments)
* kelas [MathElementBase](../../mathelementbase)
* ruang nama [Aspose.Slides.MathText](../../mathelementbase)
* rakitan [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->