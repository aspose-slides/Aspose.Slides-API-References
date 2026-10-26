---
title: Enclose()
second_title: Referensi API Aspose.Slides untuk C++
description: Membungkus elemen matematika dalam tanda kurung
type: docs
weight: 40
url: /id/aspose.slides.mathtext/imathelement/enclose/
---
## IMathElement::Enclose() metode


Membungkus elemen matematika dalam tanda kurung

```cpp
virtual System::SharedPtr<IMathDelimiter> Aspose::Slides::MathText::IMathElement::Enclose()=0
```


### Nilai Kembalian

Elemen matematika berjenis [IMathDelimiter](../../imathdelimiter/) yang mencakup tanda kurung
## Catatan



Contoh: 
```cpp
auto element = System::MakeObject<MathematicalText>(u"x");
auto delimiter = element->Enclose();
```

## IMathElement::Enclose(char16_t, char16_t) metode


Membungkus elemen ini dengan karakter yang ditentukan seperti tanda kurung atau karakter lain sebagai bingkai

```cpp
virtual System::SharedPtr<IMathDelimiter> Aspose::Slides::MathText::IMathElement::Enclose(char16_t beginningCharacter, char16_t endingCharacter)=0
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| beginningCharacter | char16_t | Karakter awal (biasanya kurung kiri) |
| endingCharacter | char16_t | Karakter akhir (biasanya kurung kanan) |

### Nilai Kembalian

Elemen matematika berjenis [IMathDelimiter](../../imathdelimiter/) yang mencakup karakter yang ditentukan sebagai bingkai
## Catatan



Contoh: 
```cpp
auto element = System::MakeObject<MathematicalText>(u"x");
auto delimiter = element->Enclose(u'[', u']');
```

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [IMathDelimiter](../../imathdelimiter/)
* Kelas [IMathElement](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)