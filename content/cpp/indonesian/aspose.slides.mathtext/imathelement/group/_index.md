---
title: Group()
second_title: Referensi API Aspose.Slides untuk C++
description: Menempatkan elemen ini dalam grup menggunakan tanda kurung kurawal bawah
type: docs
weight: 248
url: /id/aspose.slides.mathtext/imathelement/group/
---
## IMathElement::Group() method

Menempatkan elemen ini dalam grup menggunakan tanda kurung kurawal bawah

```cpp
virtual System::SharedPtr<IMathGroupingCharacter> Aspose::Slides::MathText::IMathElement::Group()=0
```

### Nilai Kembali

Instansi baru dari tipe [IMathGroupingCharacter](../../imathgroupingcharacter/)

## Catatan



Contoh: 
```cpp
auto groupingElement = System::MakeObject<MathematicalText>(u"x;y;z")->Group();
```

## IMathElement::Group(char16_t, MathTopBotPositions, MathTopBotPositions) metode

Menempatkan elemen ini dalam grup menggunakan karakter pengelompokan seperti tanda kurung kurawal bawah atau yang lain

```cpp
virtual System::SharedPtr<IMathGroupingCharacter> Aspose::Slides::MathText::IMathElement::Group(char16_t character, MathTopBotPositions position, MathTopBotPositions verticalJustification)=0
```

### Argumen

| Parameter | Type | Description |
| --- | --- | --- |
| character | char16_t | Karakter pengelompokan seperti BOTTOM CURLY BRACKET (U+23DF) atau yang lain |
| position | [MathTopBotPositions](../../mathtopbotpositions/) | Posisi karakter pengelompokan |
| verticalJustification | [MathTopBotPositions](../../mathtopbotpositions/) | Justifikasi vertikal karakter grup. Menentukan perataan objek relatif terhadap garis dasar. Misalnya, ketika karakter grup berada di atas objek, VerticalJustification of Top berarti bahwa bagian atas objek berada pada garis dasar; ketika VerticalJustification disetel ke Bottom, bagian bawah objek berada pada garis dasar |

### Nilai Kembali

Instansi baru dari tipe [IMathGroupingCharacter](../../imathgroupingcharacter/)

## Catatan



Contoh: 
```cpp
auto groupingElement = System::MakeObject<MathematicalText>(u"x;y;z")->Group(u'\u23E1', MathTopBotPositions::Bottom, MathTopBotPositions::Top);
```

## Lihat Juga

* Enum [MathTopBotPositions](../../mathtopbotpositions/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [IMathGroupingCharacter](../../imathgroupingcharacter/)
* Kelas [IMathElement](../)
* Ruang Nama [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)