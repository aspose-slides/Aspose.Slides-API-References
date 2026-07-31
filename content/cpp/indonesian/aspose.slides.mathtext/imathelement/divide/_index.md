---
title: Divide()
second_title: Referensi API Aspose.Slides untuk C++
description: Membuat pecahan dengan pembilang ini dan penyebut yang ditentukan
type: docs
weight: 27
url: /id/aspose.slides.mathtext/imathelement/divide/
---
## IMathElement::Divide(System::SharedPtr\<IMathElement\>) metode


Membuat pecahan dengan pembilang ini dan penyebut yang ditentukan

```cpp
virtual System::SharedPtr<IMathFraction> Aspose::Slides::MathText::IMathElement::Divide(System::SharedPtr<IMathElement> denominator)=0
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| denominator | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | Penyebut |

### Nilai Kembalian

pecahan baru
## Catatan



Contoh: 
```cpp
auto numerator = System::MakeObject<MathematicalText>(u"x");
auto denumerator = System::MakeObject<MathematicalText>(u"y");
auto fraction = numerator->Divide(denumerator);
```

## IMathElement::Divide(System::String) metode


Membuat pecahan dengan pembilang ini dan penyebut yang ditentukan

```cpp
virtual System::SharedPtr<IMathFraction> Aspose::Slides::MathText::IMathElement::Divide(System::String denominator)=0
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| denominator | [System::String](../../../system/string/) | Penyebut |

### Nilai Kembalian

pecahan baru
## Catatan



Contoh: 
```cpp
System::SharedPtr<IMathElement> numerator = System::MakeObject<MathematicalText>(u"x");
auto fraction = numerator->Divide(u"y");
```

## IMathElement::Divide(System::SharedPtr\<IMathElement\>, MathFractionTypes) metode


Membuat pecahan tipe tertentu dengan pembilang ini dan penyebut yang ditentukan

```cpp
virtual System::SharedPtr<IMathFraction> Aspose::Slides::MathText::IMathElement::Divide(System::SharedPtr<IMathElement> denominator, MathFractionTypes fractionType)=0
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| denominator | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | Penyebut |
| fractionType | [MathFractionTypes](../../mathfractiontypes/) | Jenis pecahan: Bar, NoBar, Skewed, Linear |

### Nilai Kembalian

pecahan baru
## Catatan



Contoh: 
```cpp
auto numerator = System::MakeObject<MathematicalText>(u"x");
auto denumerator = System::MakeObject<MathematicalText>(u"y");
auto fraction = numerator->Divide(denumerator, MathFractionTypes::Linear);
```

## IMathElement::Divide(System::String, MathFractionTypes) metode


Membuat pecahan tipe tertentu dengan pembilang ini dan penyebut yang ditentukan

```cpp
virtual System::SharedPtr<IMathFraction> Aspose::Slides::MathText::IMathElement::Divide(System::String denominator, MathFractionTypes fractionType)=0
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| denominator | [System::String](../../../system/string/) | Penyebut |
| fractionType | [MathFractionTypes](../../mathfractiontypes/) | Jenis pecahan: Bar, NoBar, Skewed, Linear |

### Nilai Kembalian

pecahan baru
## Catatan



Contoh: 
```cpp
auto numerator = System::MakeObject<MathematicalText>(u"x");
auto fraction = numerator->Divide(u"y", MathFractionTypes::Linear);
```

## Lihat Juga

* Enum [MathFractionTypes](../../mathfractiontypes/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IMathFraction](../../imathfraction/)
* Class [IMathElement](../)
* Class [String](../../../system/string/)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)