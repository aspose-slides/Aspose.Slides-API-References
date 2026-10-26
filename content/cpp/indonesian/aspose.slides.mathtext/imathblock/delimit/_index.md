---
title: Delimit()
second_title: Referensi API Aspose.Slides untuk C++
description: Membatasi semua elemen anak dengan karakter pemisah (tanpa kurung)
type: docs
weight: 1
url: /id/aspose.slides.mathtext/imathblock/delimit/
---
## IMathBlock::Delimit(char16_t) metode

Membatasi semua elemen anak dengan karakter pemisah (tanpa kurung)

```cpp
virtual System::SharedPtr<IMathDelimiter> Aspose::Slides::MathText::IMathBlock::Delimit(char16_t separatorCharacter)=0
```

### Argumen

| Parameter | Type | Description |
| --- | --- | --- |
| separatorCharacter | char16_t | Karakter yang digunakan sebagai pemisah |

### Nilai Kembalian

Instansi elemen [IMathDelimiter](../../imathdelimiter/)

## Keterangan



Contoh: 
```cpp
auto mathBlock = System::MakeObject<MathematicalText>(u"x")->Join(u"y");
auto delimiterElement = mathBlock->Delimit(u'|');
```

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [IMathDelimiter](../../imathdelimiter/)
* Kelas [IMathBlock](../)
* Ruang Nama [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)