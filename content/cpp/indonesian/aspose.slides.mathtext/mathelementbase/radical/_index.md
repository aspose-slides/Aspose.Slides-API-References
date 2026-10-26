---
title: Radical()
second_title: Aspose.Slides untuk Referensi API C++
description: Menentukan akar matematika dengan derajat yang diberikan dari argumen yang ditentukan.
type: docs
weight: 118
url: /id/aspose.slides.mathtext/mathelementbase/radical/
---
## MathElementBase::Radical(System::SharedPtr\<IMathElement\>) metode

Menentukan akar matematika dengan derajat yang diberikan dari argumen yang ditentukan.

```cpp
System::SharedPtr<IMathRadical> Aspose::Slides::MathText::MathElementBase::Radical(System::SharedPtr<IMathElement> degree) override
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| degree | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Argumen Radical |

### Nilai Kembalian

Instansi baru bertipe [IMathRadical](../../imathradical/)

## Catatan



Contoh: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"2px");
auto degree = System::MakeObject<MathematicalText>(u"y");
auto radical = baseElement->Radical(degree);
```

## MathElementBase::Radical(System::String) metode

Menentukan akar matematika dengan derajat yang diberikan dari argumen yang ditentukan.

```cpp
System::SharedPtr<IMathRadical> Aspose::Slides::MathText::MathElementBase::Radical(System::String degree) override
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| degree | [System::String](../../../system/string/) | Argumen Radical |

### Nilai Kembalian

Instansi baru bertipe [IMathRadical](../../imathradical/)

## Catatan



Contoh: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"2px");
auto radical = baseElement->Radical(u"3");
```

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [IMathRadical](../../imathradical/)
* Kelas [IMathElement](../../imathelement/)
* Kelas [MathElementBase](../)
* Kelas [String](../../../system/string/)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)