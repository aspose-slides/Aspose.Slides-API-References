---
title: Function()
second_title: Referensi API Aspose.Slides untuk C++
description: Mengambil fungsi dengan argumen menggunakan instance ini sebagai nama fungsi
type: docs
weight: 53
url: /id/aspose.slides.mathtext/imathelement/function/
---
## IMathElement::Function(System::SharedPtr\<IMathElement\>) metode


Mengambil fungsi dengan argumen menggunakan instance ini sebagai nama fungsi

```cpp
virtual System::SharedPtr<IMathFunction> Aspose::Slides::MathText::IMathElement::Function(System::SharedPtr<IMathElement> functionArgument)=0
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| functionArgument | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | Sebuah argumen dari fungsi |

### Nilai Kembalian

Elemen matematika baru bertipe [IMathFunction](../../imathfunction/)
## Catatan



Contoh:
```cpp
auto functionName = System::MakeObject<MathematicalText>(u"sin");
auto functionArg = System::MakeObject<MathematicalText>(u"x");
auto func = functionName->Function(functionArg);
```

## IMathElement::Function(System::String) metode


Mengambil fungsi dengan argumen menggunakan instance ini sebagai nama fungsi

```cpp
virtual System::SharedPtr<IMathFunction> Aspose::Slides::MathText::IMathElement::Function(System::String functionArgument)=0
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| functionArgument | [System::String](../../../system/string/) | Sebuah argumen dari fungsi |

### Nilai Kembalian

Elemen matematika baru bertipe [IMathFunction](../../imathfunction/)
## Catatan



Contoh:
```cpp
auto functionName = System::MakeObject<MathematicalText>(u"sin");
auto func = functionName->Function(u"x");
```

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IMathFunction](../../imathfunction/)
* Class [IMathElement](../)
* Class [String](../../../system/string/)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)