---
title: Enclose()
second_title: Referensi API Aspose.Slides untuk C++
description: Membungkus elemen anak dari blok ini dengan karakter yang ditentukan seperti tanda kurung atau karakter lain sebagai bingkai
type: docs
weight: 222
url: /id/aspose.slides.mathtext/mathblock/enclose/
---
## MathBlock::Enclose(char16_t, char16_t) method

Membungkus elemen anak dari blok ini dengan karakter yang ditentukan seperti tanda kurung atau karakter lain sebagai bingkai

```cpp
System::SharedPtr<IMathDelimiter> Aspose::Slides::MathText::MathBlock::Enclose(char16_t beginningCharacter, char16_t endingCharacter) override
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| beginningCharacter | char16_t | Beginning character (usually left bracket) |
| endingCharacter | char16_t | Ending character (usually right bracket) |

### Nilai Kembali

Elemen matematika dengan tipe [IMathDelimiter](../../imathdelimiter/) yang menyertakan karakter yang ditentukan sebagai bingkai

## Catatan

Contoh: 
```cpp
auto block = System::MakeObject<MathematicalText>(u"x")->Join(u"+y");
auto delimiter = System::ExplicitCast<IMathElement>(block)->Enclose(u'[', u']');
```

## MathBlock::Enclose(char16_t, char16_t, char16_t) method

Membungkus elemen anak dari blok ini dengan karakter yang ditentukan seperti tanda kurung atau karakter lain sebagai bingkai dan memisahkannya dengan karakter pemisah

```cpp
System::SharedPtr<IMathDelimiter> Aspose::Slides::MathText::MathBlock::Enclose(char16_t beginningCharacter, char16_t endingCharacter, char16_t separatorCharacter) override
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| beginningCharacter | char16_t | Beginning character (usually left bracket) |
| endingCharacter | char16_t | Ending character (usually right bracket) |
| separatorCharacter | char16_t | Separator character |

### Nilai Kembali

Elemen matematika dengan tipe [IMathDelimiter](../../imathdelimiter/) yang menyertakan karakter yang ditentukan sebagai bingkai dan pemisah

## Catatan

Contoh: 
```cpp
auto mathBlock = System::MakeObject<MathematicalText>(u"x")->Join(u"y");
auto delimiterElement = mathBlock->Enclose(u'{', u'}', u'%');
```

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [IMathDelimiter](../../imathdelimiter/)
* Kelas [MathBlock](../)
* Ruang Nama [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)