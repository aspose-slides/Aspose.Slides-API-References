---
title: Function()
second_title: Referensi API Aspose.Slides untuk C++
description: Mengambil fungsi dari sebuah argumen menggunakan instance ini sebagai nama fungsi
type: docs
weight: 40
url: /id/aspose.slides.mathtext/mathelementbase/function/
---
## MathElementBase::Function(System::SharedPtr\<IMathElement\>) metode


Mengambil fungsi dari sebuah argumen menggunakan instance ini sebagai nama fungsi

```cpp
System::SharedPtr<IMathFunction> Aspose::Slides::MathText::MathElementBase::Function(System::SharedPtr<IMathElement> functionArgument) override
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| functionArgument | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Sebuah argumen dari fungsi |

### Nilai Kembali

Elemen matematika baru dengan tipe [IMathFunction](../../imathfunction/)
## Keterangan



Contoh: 
```cpp
auto functionName = System::MakeObject<MathematicalText>(u"sin");
auto functionArg = System::MakeObject<MathematicalText>(u"x");
auto func = functionName->Function(functionArg);
```

## MathElementBase::Function(System::String) metode


Mengambil fungsi dari sebuah argumen menggunakan instance ini sebagai nama fungsi

```cpp
System::SharedPtr<IMathFunction> Aspose::Slides::MathText::MathElementBase::Function(System::String functionArgument) override
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| functionArgument | [System::String](../../../system/string/) | Sebuah argumen dari fungsi |

### Nilai Kembali

Elemen matematika baru dengan tipe [IMathFunction](../../imathfunction/)
## Keterangan



Contoh: 
```cpp
auto functionName = System::MakeObject<MathematicalText>(u"sin");
auto func = functionName->Function(u"x");
```

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IMathFunction](../../imathfunction/)
* Class [IMathElement](../../imathelement/)
* Class [MathElementBase](../)
* Class [String](../../../system/string/)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)