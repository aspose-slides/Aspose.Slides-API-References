---
title: Enclose()
second_title: Referensi API Aspose.Slides untuk C++
description: Membungkus elemen matematika dalam tanda kurung
type: docs
weight: 27
url: /id/aspose.slides.mathtext/mathelementbase/enclose/
---
## MathElementBase::Enclose() metode


Membungkus elemen matematika dalam tanda kurung

```cpp
System::SharedPtr<IMathDelimiter> Aspose::Slides::MathText::MathElementBase::Enclose() override
```


### Nilai Kembalian

Elemen matematika dengan tipe [IMathDelimiter](../../imathdelimiter/) yang mencakup tanda kurung
## Keterangan



Contoh: 
```cpp
auto element = System::MakeObject<MathematicalText>(u"x");
auto delimiter = element->Enclose();
```

## MathElementBase::Enclose(char16_t, char16_t) metode


Membungkus elemen matematika dalam karakter yang ditentukan seperti tanda kurung atau karakter lain sebagai bingkai

```cpp
System::SharedPtr<IMathDelimiter> Aspose::Slides::MathText::MathElementBase::Enclose(char16_t beginningCharacter, char16_t endingCharacter) override
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| beginningCharacter | char16_t | Karakter awal (biasanya kurung kiri) |
| endingCharacter | char16_t | Karakter akhir (biasanya kurung kanan) |

### Nilai Kembalian

Elemen matematika dengan tipe [IMathDelimiter](../../imathdelimiter/) yang mencakup karakter yang ditentukan sebagai bingkai
## Keterangan



Contoh: 
```cpp
auto element = System::MakeObject<MathematicalText>(u"x");
auto delimiter = element->Enclose(u'[', u']');
```

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IMathDelimiter](../../imathdelimiter/)
* Class [MathElementBase](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)