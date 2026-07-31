---
title: set_EndingCharacter()
second_title: Referensi API Aspose.Slides untuk C++
description: "Delimiter Ending Character menentukan karakter pembatas akhir, atau penutup. Pembatas matematis adalah karakter pembungkus seperti tanda kurung, kurung siku, dan kurung kurawal. Nilai default: ')'."
type: docs
weight: 79
url: /id/aspose.slides.mathtext/imathdelimiter/set_endingcharacter/
---
## IMathDelimiter::set_EndingCharacter(char16_t) metode


Delimiter Ending Character specifies the ending, or closing, delimiter character. Mathematical delimiters are enclosing characters such as parentheses, brackets, and braces. The default: ')'.

```cpp
virtual void Aspose::Slides::MathText::IMathDelimiter::set_EndingCharacter(char16_t value)=0
```

## Catatan


Contoh: 
```cpp
auto delimiter = System::ExplicitCast<IMathElement>(System::MakeObject<MathematicalText>(u"x")->Join(u"y"))->Enclose();
delimiter->set_EndingCharacter(u']');
```

## Lihat Juga

* Kelas [IMathDelimiter](../)
* Ruang Nama [Aspose::Slides::MathText](../../)
* Pustaka [Aspose.Slides](../../../)