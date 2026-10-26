---
title: set_EndingCharacter()
second_title: Referensi API Aspose.Slides untuk C++
description: "Delimiter Ending Character menentukan karakter pembatas akhir, atau penutup. Delimiter matematika adalah karakter pembungkus seperti tanda kurung, kurung siku, dan kurung kurawal. Nilai bawaan: ')'."
type: docs
weight: 79
url: /id/aspose.slides.mathtext/mathdelimiter/set_endingcharacter/
---
## MathDelimiter::set_EndingCharacter(char16_t) metode

Delimiter Ending Character menentukan karakter pembatas akhir, atau penutup. Delimiter matematika adalah karakter pembungkus seperti tanda kurung, kurung siku, dan kurung kurawal. Nilai bawaan: ')'.

```cpp
void Aspose::Slides::MathText::MathDelimiter::set_EndingCharacter(char16_t value) override
```

## Catatan

Contoh: 
```cpp
auto delimiter = System::ExplicitCast<IMathElement>(System::MakeObject<MathematicalText>(u"x")->Join(u"y"))->Enclose();
delimiter->set_EndingCharacter(u']');
```

## Lihat Juga

* Kelas [MathDelimiter](../)
* Ruang nama [Aspose::Slides::MathText](../../)
* Perpustakaan [Aspose.Slides](../../../)