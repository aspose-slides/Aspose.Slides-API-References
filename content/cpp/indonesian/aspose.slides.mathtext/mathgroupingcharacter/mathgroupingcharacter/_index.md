---
title: MathGroupingCharacter()
second_title: Referensi API Aspose.Slides untuk C++
description: Menginisialisasi instance baru dari kelas MathGroupingCharacter dengan karakter pengelompokkan default U+23DF (BOTTOM CURLY BRACKET)
type: docs
weight: 92
url: /id/aspose.slides.mathtext/mathgroupingcharacter/mathgroupingcharacter/
---
## MathGroupingCharacter::MathGroupingCharacter(System::SharedPtr\<IMathElement\>) konstruktor

Menginisialisasi instance baru dari kelas [MathGroupingCharacter](../) dengan karakter pengelompokkan default U+23DF (BOTTOM CURLY BRACKET)

```cpp
Aspose::Slides::MathText::MathGroupingCharacter::MathGroupingCharacter(System::SharedPtr<IMathElement> element)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Elemen dasar tempat bar diterapkan |

## Catatan

Contoh: 
```cpp
auto groupingCharacter = System::MakeObject<MathGroupingCharacter>(System::MakeObject<MathematicalText>(u"abc"));
```

## MathGroupingCharacter::MathGroupingCharacter(System::SharedPtr\<IMathElement\>, char16_t, MathTopBotPositions, MathTopBotPositions) konstruktor

Menginisialisasi instance baru dari kelas [MathGroupingCharacter](../).

```cpp
Aspose::Slides::MathText::MathGroupingCharacter::MathGroupingCharacter(System::SharedPtr<IMathElement> element, char16_t character, MathTopBotPositions position, MathTopBotPositions verticalJustification)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Elemen dasar tempat bar diterapkan |
| character | char16_t | Karakter Pengelompokkan |
| position | [MathTopBotPositions](../../mathtopbotpositions/) | Posisi karakter pengelompokan |
| verticalJustification | [MathTopBotPositions](../../mathtopbotpositions/) | Justifikasi vertikal karakter grup |

## Catatan

Contoh: 
```cpp
auto groupingCharacter = System::MakeObject<MathGroupingCharacter>(System::MakeObject<MathematicalText>(u"abc"), u'_', MathTopBotPositions::Top, MathTopBotPositions::Bottom);
```

## Lihat Juga

* Enum [MathTopBotPositions](../../mathtopbotpositions/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [IMathElement](../../imathelement/)
* Kelas [MathGroupingCharacter](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)