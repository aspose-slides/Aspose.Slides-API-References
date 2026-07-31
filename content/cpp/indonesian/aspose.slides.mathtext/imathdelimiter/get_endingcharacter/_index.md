---
title: get_EndingCharacter()
second_title: Aspose.Slides untuk Referensi API C++
description: "Delimiter Ending Character menentukan karakter delimiter akhir, atau penutup. Delimiters matematika adalah karakter yang menyertakan seperti tanda kurung, kurung siku, dan kurung kurawal. Nilai default: ')'."
type: docs
weight: 66
url: /id/aspose.slides.mathtext/imathdelimiter/get_endingcharacter/
---
## IMathDelimiter::get_EndingCharacter() metode


Delimiter Ending Character menentukan karakter delimiter akhir, atau penutup. Delimiters matematika adalah karakter yang menyertakan seperti tanda kurung, kurung siku, dan kurung kurawal. Nilai default: ')'.

```cpp
virtual char16_t Aspose::Slides::MathText::IMathDelimiter::get_EndingCharacter()=0
```

## Catatan


Contoh: 
```cpp
auto delimiter = System::ExplicitCast<IMathElement>(System::MakeObject<MathematicalText>(u"x")->Join(u"y"))->Enclose();
delimiter->set_EndingCharacter(u']');
```

## Lihat Juga

* Kelas [IMathDelimiter](../)
* Namespace [Aspose::Slides::MathText](../../)
* Perpustakaan [Aspose.Slides](../../../)