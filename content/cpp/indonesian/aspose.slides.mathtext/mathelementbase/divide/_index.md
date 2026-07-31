---
title: Divide()
second_title: Referensi API Aspose.Slides untuk C++
description: Membuat fraksi dengan pembilang ini dan penyebut yang ditentukan
type: docs
weight: 14
url: /id/aspose.slides.mathtext/mathelementbase/divide/
---
## MathElementBase::Divide(System::SharedPtr\<IMathElement\>) metode

Membuat fraksi dengan pembilang ini dan penyebut yang ditentukan

```cpp
System::SharedPtr<IMathFraction> Aspose::Slides::MathText::MathElementBase::Divide(System::SharedPtr<IMathElement> denominator) override
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| denominator | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Penyebut |

### Nilai Kembali

fraksi baru
## Catatan



Contoh: 
```cpp
auto numerator = System::MakeObject<MathematicalText>(u"x");
auto denumerator = System::MakeObject<MathematicalText>(u"y");
auto fraction = numerator->Divide(denumerator);
```

## MathElementBase::Divide(System::String) metode

Membuat fraksi dengan pembilang ini dan penyebut yang ditentukan

```cpp
System::SharedPtr<IMathFraction> Aspose::Slides::MathText::MathElementBase::Divide(System::String denominator) override
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| denominator | [System::String](../../../system/string/) | Penyebut |

### Nilai Kembali

fraksi baru
## Catatan



Contoh: 
```cpp
auto numerator = System::MakeObject<MathematicalText>(u"x");
auto fraction = numerator->Divide(u"y");
```

## MathElementBase::Divide(System::SharedPtr\<IMathElement\>, MathFractionTypes) metode

Membuat fraksi dengan tipe yang ditentukan menggunakan pembilang ini dan penyebut yang ditentukan

```cpp
System::SharedPtr<IMathFraction> Aspose::Slides::MathText::MathElementBase::Divide(System::SharedPtr<IMathElement> denominator, MathFractionTypes fractionType) override
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| denominator | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Penyebut |
| fractionType | [MathFractionTypes](../../mathfractiontypes/) | Tipe fraksi: Bar, NoBar, Skewed, Linear |

### Nilai Kembali

fraksi baru
## Catatan



Contoh: 
```cpp
auto numerator = System::MakeObject<MathematicalText>(u"x");
auto denumerator = System::MakeObject<MathematicalText>(u"y");
auto fraction = numerator->Divide(denumerator, MathFractionTypes::Linear);
```

## MathElementBase::Divide(System::String, MathFractionTypes) metode

Membuat fraksi dengan tipe yang ditentukan menggunakan pembilang ini dan penyebut yang ditentukan

```cpp
System::SharedPtr<IMathFraction> Aspose::Slides::MathText::MathElementBase::Divide(System::String denominator, MathFractionTypes fractionType) override
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| denominator | [System::String](../../../system/string/) | Penyebut |
| fractionType | [MathFractionTypes](../../mathfractiontypes/) | Tipe fraksi: Bar, NoBar, Skewed, Linear |

### Nilai Kembali

fraksi baru
## Catatan



Contoh: 
```cpp
auto numerator = System::MakeObject<MathematicalText>(u"x");
auto fraction = numerator->Divide(u"y", MathFractionTypes::Linear);
```

## Lihat Juga

* Enum [MathFractionTypes](../../mathfractiontypes/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [IMathFraction](../../imathfraction/)
* Kelas [IMathElement](../../imathelement/)
* Kelas [MathElementBase](../)
* Kelas [String](../../../system/string/)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)