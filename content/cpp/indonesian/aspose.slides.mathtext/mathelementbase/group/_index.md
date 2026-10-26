---
title: Group()
second_title: Referensi API Aspose.Slides untuk C++
description: Menempatkan elemen ini dalam sebuah grup menggunakan tanda kurung kurawal bawah
type: docs
weight: 235
url: /id/aspose.slides.mathtext/mathelementbase/group/
---
## MathElementBase::Group() metode


Menempatkan elemen ini dalam sebuah grup menggunakan tanda kurung kurawal bawah

```cpp
System::SharedPtr<IMathGroupingCharacter> Aspose::Slides::MathText::MathElementBase::Group() override
```


### Nilai Kembali

Instansi baru dari tipe [IMathGroupingCharacter](../../imathgroupingcharacter/)
## Catatan



Contoh: 
```cpp
auto groupingElement = System::MakeObject<MathematicalText>(u"x;y;z")->Group();
```

## MathElementBase::Group(char16_t, MathTopBotPositions, MathTopBotPositions) metode


Menempatkan elemen ini dalam sebuah grup menggunakan karakter pengelompokan seperti kurung kurawal bawah atau karakter lainnya

```cpp
System::SharedPtr<IMathGroupingCharacter> Aspose::Slides::MathText::MathElementBase::Group(char16_t character, MathTopBotPositions position, MathTopBotPositions verticalJustification) override
```


### Argumen

| Parameter | Type | Deskripsi |
| --- | --- | --- |
| character | char16_t | Karakter Pengelompokan seperti BOTTOM CURLY BRACKET (U+23DF) atau lainnya |
| position | [MathTopBotPositions](../../mathtopbotpositions/) | Posisi karakter pengelompokan |
| verticalJustification | [MathTopBotPositions](../../mathtopbotpositions/) | Justifikasi vertikal dari karakter grup. Menentukan perataan objek relatif terhadap garis dasar. Sebagai contoh, ketika karakter grup berada di atas objek, VerticalJustification bernilai Top menandakan bahwa bagian atas objek berada pada garis dasar; ketika VerticalJustification diatur ke Bottom, bagian bawah objek berada pada garis dasar |

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
* Kelas [MathElementBase](../)
* Namespace [Aspose::Slides::MathText](../../)
* Perpustakaan [Aspose.Slides](../../../)