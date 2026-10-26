---
title: Enclose()
second_title: Referensi API Aspose.Slides untuk C++
description: Membungkus elemen anak blok ini dengan karakter yang ditentukan seperti tanda kurung atau karakter lain sebagai bingkai dan memisahkan dengan karakter pemisah
type: docs
weight: 14
url: /id/aspose.slides.mathtext/imathblock/enclose/
---
## IMathBlock::Enclose(char16_t, char16_t, char16_t) metode

Membungkus elemen anak dari blok ini dengan karakter yang ditentukan seperti tanda kurung atau karakter lain sebagai bingkai dan memisahkan dengan karakter pemisah

```cpp
virtual System::SharedPtr<IMathDelimiter> Aspose::Slides::MathText::IMathBlock::Enclose(char16_t beginningCharacter, char16_t endingCharacter, char16_t separatorCharacter)=0
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| beginningCharacter | char16_t | Karakter awal (biasanya tanda kurung kiri) |
| endingCharacter | char16_t | Karakter akhir (biasanya tanda kurung kanan) |
| separatorCharacter | char16_t | Karakter pemisah |

### Nilai Kembali

Elemen matematika tipe [IMathDelimiter](../../imathdelimiter/) yang mencakup karakter yang ditentukan sebagai bingkai dan pembatas

## Catatan

Contoh:
```cpp
auto mathBlock = System::MakeObject<MathematicalText>(u"x")->Join(u"y");
auto delimiterElement = mathBlock->Enclose(u'{', u'}', u'%');
```

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [IMathDelimiter](../../imathdelimiter/)
* Kelas [IMathBlock](../)
* Ruang Nama [Aspose::Slides::MathText](../../)
* Perpustakaan [Aspose.Slides](../../../)