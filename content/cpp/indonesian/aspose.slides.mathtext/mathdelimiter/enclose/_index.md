---
title: Enclose()
second_title: Referensi API Aspose.Slides untuk C++
description: Membungkus elemen matematika dalam karakter yang ditentukan seperti tanda kurung atau karakter lain sebagai bingkai
type: docs
weight: 170
url: /id/aspose.slides.mathtext/mathdelimiter/enclose/
---
## MathDelimiter::Enclose(char16_t, char16_t) metode

Membungkus elemen matematika dalam karakter yang ditentukan seperti tanda kurung atau karakter lain sebagai bingkai

```cpp
System::SharedPtr<IMathDelimiter> Aspose::Slides::MathText::MathDelimiter::Enclose(char16_t beginningCharacter, char16_t endingCharacter) override
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| beginningCharacter | char16_t | Karakter awal (biasanya tanda kurung kiri) |
| endingCharacter | char16_t | Karakter akhir (biasanya tanda kurung kanan) |

### Nilai Kembalian

Jika beginningCharacter dan endingCharacter bernilai null, properti yang bersesuaian hanya diberikan nilai dan tidak ada objek baru yang dibuat (mengembalikan instance ini). Jika tidak, mengembalikan elemen matematika baru bertipe Delimiter yang mencakup karakter yang ditentukan sebagai bingkai dan instance [MathDelimiter](../) ini dibingkai di dalamnya.

## Catatan



Contoh: 
```cpp
auto innerDelimiter = System::ExplicitCast<IMathElement>(System::MakeObject<MathematicalText>(u"x")->Join(u",y"))->Enclose(u'{', u'}');
auto outerDelimiter = innerDelimiter->Enclose(u'[', u']');
```

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IMathDelimiter](../../imathdelimiter/)
* Class [MathDelimiter](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)