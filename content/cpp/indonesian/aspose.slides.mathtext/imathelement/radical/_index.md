---
title: Radical()
second_title: Referensi API Aspose.Slides untuk C++
description: Menentukan akar matematika dengan derajat yang diberikan dari argumen yang ditentukan.
type: docs
weight: 131
url: /id/aspose.slides.mathtext/imathelement/radical/
---
## IMathElement::Radical(System::SharedPtr\<IMathElement\>) metode


Menentukan akar matematika dengan derajat yang diberikan dari argumen yang ditentukan.

```cpp
virtual System::SharedPtr<IMathRadical> Aspose::Slides::MathText::IMathElement::Radical(System::SharedPtr<IMathElement> degree)=0
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| degree | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | Argumen dari Radical |

### Nilai Kembali

Instansi baru dari tipe [IMathRadical](../../imathradical/)
## Catatan



Contoh: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"2px");
auto degree = System::MakeObject<MathematicalText>(u"y");
auto radical = baseElement->Radical(degree);
```

## IMathElement::Radical(System::String) metode


Menentukan akar matematika dengan derajat yang diberikan dari argumen yang ditentukan.

```cpp
virtual System::SharedPtr<IMathRadical> Aspose::Slides::MathText::IMathElement::Radical(System::String degree)=0
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| degree | [System::String](../../../system/string/) | Argumen dari Radical |

### Nilai Kembali

Instansi baru dari tipe [IMathRadical](../../imathradical/)
## Catatan



Contoh: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"2px");
auto radical = baseElement->Radical(u"3");
```

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [IMathRadical](../../imathradical/)
* Kelas [IMathElement](../)
* Kelas [String](../../../system/string/)
* Ruang Nama [Aspose::Slides::MathText](../../)
* Perpustakaan [Aspose.Slides](../../../)