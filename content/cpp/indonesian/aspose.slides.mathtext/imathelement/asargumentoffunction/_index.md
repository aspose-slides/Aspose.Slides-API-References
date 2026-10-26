---
title: AsArgumentOfFunction()
second_title: Referensi API Aspose.Slides untuk C++
description: Menggunakan fungsi yang ditentukan dengan instance ini sebagai argumen
type: docs
weight: 66
url: /id/aspose.slides.mathtext/imathelement/asargumentoffunction/
---
## IMathElement::AsArgumentOfFunction(System::SharedPtr\<IMathElement\>) metode

Menggunakan fungsi yang ditentukan dengan instance ini sebagai argumen

```cpp
virtual System::SharedPtr<IMathFunction> Aspose::Slides::MathText::IMathElement::AsArgumentOfFunction(System::SharedPtr<IMathElement> functionName)=0
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| functionName | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | Nama fungsi |

### Nilai Kembali

Elemen matematika baru dengan tipe [IMathFunction](../../imathfunction/)

## Keterangan

Contoh: 
```cpp
auto functionName = System::MakeObject<MathematicalText>(u"sin");
auto functionArg = System::MakeObject<MathematicalText>(u"x");
auto func = functionArg->AsArgumentOfFunction(functionName);
```

## IMathElement::AsArgumentOfFunction(System::String) metode

Menggunakan fungsi yang ditentukan dengan instance ini sebagai argumen

```cpp
virtual System::SharedPtr<IMathFunction> Aspose::Slides::MathText::IMathElement::AsArgumentOfFunction(System::String functionName)=0
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| functionName | [System::String](../../../system/string/) | Nama fungsi |

### Nilai Kembali

Elemen matematika baru dengan tipe [IMathFunction](../../imathfunction/)

## Keterangan

Contoh: 
```cpp
auto functionArg = System::MakeObject<MathematicalText>(u"x");
auto func = functionArg->AsArgumentOfFunction(u"cos");
```

## IMathElement::AsArgumentOfFunction(MathFunctionsOfOneArgument) metode

Menggunakan fungsi yang ditentukan dengan instance ini sebagai argumen

```cpp
virtual System::SharedPtr<IMathFunction> Aspose::Slides::MathText::IMathElement::AsArgumentOfFunction(MathFunctionsOfOneArgument functionType)=0
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| functionType | [MathFunctionsOfOneArgument](../../mathfunctionsofoneargument/) | Salah satu tipe fungsi umum dengan satu argumen |

### Nilai Kembali

Elemen matematika baru dengan tipe [IMathFunction](../../imathfunction/)

## Keterangan

Contoh: 
```cpp
auto functionArg = System::MakeObject<MathematicalText>(u"x");
auto func = functionArg->AsArgumentOfFunction(MathFunctionsOfOneArgument::ArcSin);
```

## IMathElement::AsArgumentOfFunction(MathFunctionsOfTwoArguments, System::SharedPtr\<IMathElement\>) metode

Menggunakan fungsi yang ditentukan dengan instance ini sebagai argumen serta argumen tambahan yang ditentukan

```cpp
virtual System::SharedPtr<IMathFunction> Aspose::Slides::MathText::IMathElement::AsArgumentOfFunction(MathFunctionsOfTwoArguments functionType, System::SharedPtr<IMathElement> additionalArgument)=0
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| functionType | [MathFunctionsOfTwoArguments](../../mathfunctionsoftwoarguments/) | Salah satu tipe fungsi umum dengan dua argumen: Log, Lim, Min, Max |
| additionalArgument | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | Argumen tambahan tergantung pada tipe fungsi |

### Nilai Kembali

Elemen matematika baru dengan tipe [IMathFunction](../../imathfunction/)

## Keterangan

Contoh: 
```cpp
auto functionArg = System::MakeObject<MathematicalText>(u"x");
auto logarithmBase = System::MakeObject<MathematicalText>(u"5");
auto func = functionArg->AsArgumentOfFunction(MathFunctionsOfTwoArguments::Log, logarithmBase);
// Mengembalikan logaritma 'x' dengan basis '5'
```

## IMathElement::AsArgumentOfFunction(MathFunctionsOfTwoArguments, System::String) metode

Menggunakan fungsi yang ditentukan dengan instance ini sebagai argumen serta argumen tambahan yang ditentukan

```cpp
virtual System::SharedPtr<IMathFunction> Aspose::Slides::MathText::IMathElement::AsArgumentOfFunction(MathFunctionsOfTwoArguments functionType, System::String additionalArgument)=0
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| functionType | [MathFunctionsOfTwoArguments](../../mathfunctionsoftwoarguments/) | Salah satu tipe fungsi umum dengan dua argumen: Log, Lim, Min, Max |
| additionalArgument | [System::String](../../../system/string/) | Argumen tambahan tergantung pada tipe fungsi |

### Nilai Kembali

Elemen matematika baru dengan tipe [IMathFunction](../../imathfunction/)

## Keterangan

Contoh: 
```cpp
auto functionArg = System::MakeObject<MathematicalText>(u"x");
auto func = functionArg->AsArgumentOfFunction(MathFunctionsOfTwoArguments::Log, u"5");
// Mengembalikan logaritma 'x' dengan basis '5'
```

## Lihat Juga

* Enum [MathFunctionsOfOneArgument](../../mathfunctionsofoneargument/)
* Enum [MathFunctionsOfTwoArguments](../../mathfunctionsoftwoarguments/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [IMathFunction](../../imathfunction/)
* Kelas [IMathElement](../)
* Kelas [String](../../../system/string/)
* Ruang Nama [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)