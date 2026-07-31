---
title: get_EndingCharacter()
second_title: Referensi API Aspose.Slides untuk C++
description: "Delimiter Ending Character menentukan karakter delimiter akhir, atau penutup. Delimiter matematika adalah karakter yang mengelilingi seperti kurung, tanda kurung siku, dan kurung kurawal. Nilai bawaan: ')'."
type: docs
weight: 66
url: /id/aspose.slides.mathtext/mathdelimiter/get_endingcharacter/
---
## MathDelimiter::get_EndingCharacter() metode

Delimiter Ending Character menentukan karakter delimiter akhir, atau penutup. Delimiter matematika adalah karakter yang mengelilingi seperti kurung, tanda kurung siku, dan kurung kurawal. Nilai bawaan: ')'.

```cpp
char16_t Aspose::Slides::MathText::MathDelimiter::get_EndingCharacter() override
```

## Catatan

Contoh: 
```cpp
auto delimiter = System::ExplicitCast<IMathElement>(System::MakeObject<MathematicalText>(u"x")->Join(u"y"))->Enclose();
delimiter->set_EndingCharacter(u']');
```

## Lihat Juga

* Kelas [MathDelimiter](../)
* Ruang Nama [Aspose::Slides::MathText](../../)
* Pustaka [Aspose.Slides](../../../)