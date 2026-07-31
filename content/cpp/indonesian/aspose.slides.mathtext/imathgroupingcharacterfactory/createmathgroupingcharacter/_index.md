---
title: CreateMathGroupingCharacter()
second_title: Referensi API Aspose.Slides untuk C++
description: Membuat karakter pengelompokan matematika
type: docs
weight: 1
url: /id/aspose.slides.mathtext/imathgroupingcharacterfactory/createmathgroupingcharacter/
---
## IMathGroupingCharacterFactory::CreateMathGroupingCharacter(System::SharedPtr\<IMathElement\>, char16_t, MathTopBotPositions, MathTopBotPositions) metode


Membuat karakter pengelompokan matematika

```cpp
virtual System::SharedPtr<IMathGroupingCharacter> Aspose::Slides::MathText::IMathGroupingCharacterFactory::CreateMathGroupingCharacter(System::SharedPtr<IMathElement> element, char16_t character, MathTopBotPositions position, MathTopBotPositions verticalJustification)=0
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | elemen matematika untuk menerapkan karakter pengelompokan |
| character | char16_t | karakter pengelompokan |
| position | [MathTopBotPositions](../../mathtopbotpositions/) | posisi karakter pengelompokan |
| verticalJustification | [MathTopBotPositions](../../mathtopbotpositions/) | justifikasi vertikal |

### Nilai Kembalian

elemen karakter pengelompokan baru

## IMathGroupingCharacterFactory::CreateMathGroupingCharacter(System::SharedPtr\<IMathElement\>) metode


Membuat karakter pengelompokan matematika

```cpp
virtual System::SharedPtr<IMathGroupingCharacter> Aspose::Slides::MathText::IMathGroupingCharacterFactory::CreateMathGroupingCharacter(System::SharedPtr<IMathElement> element)=0
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | elemen matematika untuk menerapkan karakter pengelompokan |

### Nilai Kembalian

elemen karakter pengelompokan baru

## Lihat Juga

* Enum [MathTopBotPositions](../../mathtopbotpositions/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [IMathGroupingCharacter](../../imathgroupingcharacter/)
* Kelas [IMathElement](../../imathelement/)
* Kelas [IMathGroupingCharacterFactory](../)
* Ruang Nama [Aspose::Slides::MathText](../../)
* Perpustakaan [Aspose.Slides](../../../)