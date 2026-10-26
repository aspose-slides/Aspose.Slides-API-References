---
title: Nary()
second_title: Referensi API Aspose.Slides untuk C++
description: Membuat operator N-ary
type: docs
weight: 170
url: /id/aspose.slides.mathtext/imathelement/nary/
---
## IMathElement::Nary(MathNaryOperatorTypes, System::SharedPtr\<IMathElement\>, System::SharedPtr\<IMathElement\>) metode


Membuat operator N-ary

```cpp
virtual System::SharedPtr<IMathNaryOperator> Aspose::Slides::MathText::IMathElement::Nary(MathNaryOperatorTypes type, System::SharedPtr<IMathElement> lowerLimit, System::SharedPtr<IMathElement> upperLimit)=0
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| type | [MathNaryOperatorTypes](../../mathnaryoperatortypes/) | Jenis operator N-ary |
| lowerLimit | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | Batas bawah |
| upperLimit | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | Batas atas |

### Nilai Kembali

Instansi baru tipe [IMathNaryOperator](../../imathnaryoperator/)
## Catatan



Contoh: 
```cpp
System::SharedPtr<IMathElement> baseElement = System::MakeObject<MathematicalText>(u"i-1");
System::SharedPtr<IMathElement> lowerLimit = System::MakeObject<MathematicalText>(u"i=0");
System::SharedPtr<IMathElement> upperLimit = System::MakeObject<MathematicalText>(u"\U0001d45b");
auto naryOperator = baseElement->Nary(MathNaryOperatorTypes::Summation, lowerLimit, upperLimit);
```

## IMathElement::Nary(MathNaryOperatorTypes, System::String, System::String) metode


Membuat operator N-ary

```cpp
virtual System::SharedPtr<IMathNaryOperator> Aspose::Slides::MathText::IMathElement::Nary(MathNaryOperatorTypes type, System::String lowerLimit, System::String upperLimit)=0
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| type | [MathNaryOperatorTypes](../../mathnaryoperatortypes/) | Jenis operator N-ary |
| lowerLimit | [System::String](../../../system/string/) | Batas bawah |
| upperLimit | [System::String](../../../system/string/) | Batas atas |

### Nilai Kembali

Instansi baru tipe [IMathNaryOperator](../../imathnaryoperator/)
## Catatan



Contoh: 
```cpp
auto naryOperator = System::MakeObject<MathematicalText>(u"i")->Nary(MathNaryOperatorTypes::Summation, u"i=0", u"\U0001d45b");
```

## Lihat Juga

* Enum [MathNaryOperatorTypes](../../mathnaryoperatortypes/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [IMathNaryOperator](../../imathnaryoperator/)
* Kelas [IMathElement](../)
* Kelas [String](../../../system/string/)
* Ruang Nama [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)