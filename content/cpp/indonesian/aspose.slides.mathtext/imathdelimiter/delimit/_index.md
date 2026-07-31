---
title: Delimit()
second_title: Aspose.Slides untuk Referensi API C++
description: Membedakan argumen menggunakan karakter pemisah yang ditentukan
type: docs
weight: 144
url: /id/aspose.slides.mathtext/imathdelimiter/delimit/
---
## IMathDelimiter::Delimit(char16_t) metode


Membedakan argumen menggunakan karakter pemisah yang ditentukan

```cpp
virtual System::SharedPtr<IMathDelimiter> Aspose::Slides::MathText::IMathDelimiter::Delimit(char16_t separatorCharacter)=0
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| separatorCharacter | char16_t | karakter pemisah |

### Nilai Kembali

Objek ini setelah menerapkan karakter pemisah
## Catatan



Contoh: 
```cpp
auto delimiter = System::ExplicitCast<IMathElement>(System::MakeObject<MathematicalText>(u"x")->Join(u"y"))->Enclose();
delimiter->Delimit(u'|');
```

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [IMathDelimiter](../)
* Ruang Nama [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)