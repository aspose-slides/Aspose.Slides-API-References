---
title: Delimit()
second_title: Referensi API Aspose.Slides untuk C++
description: Membatasi elemen anak dengan karakter pemisah (tanpa kurung)
type: docs
weight: 209
url: /id/aspose.slides.mathtext/mathblock/delimit/
---
## MathBlock::Delimit(char16_t) metode


Membatasi elemen anak dengan karakter pemisah (tanpa kurung)

```cpp
System::SharedPtr<IMathDelimiter> Aspose::Slides::MathText::MathBlock::Delimit(char16_t separatorCharacter) override
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| separatorCharacter | char16_t | Karakter pemisah |

### Nilai Kembalian

Elemen matematika berjenis [IMathDelimiter](../../imathdelimiter/)
## Keterangan



Contoh: 
```cpp
auto mathBlock = System::MakeObject<MathematicalText>(u"x")->Join(u"y");
auto delimiterElement = mathBlock->Delimit(u'|');
```

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [IMathDelimiter](../../imathdelimiter/)
* Kelas [MathBlock](../)
* Namespace [Aspose::Slides::MathText](../../)
* Perpustakaan [Aspose.Slides](../../../)