---
title: set_BeginningCharacter()
second_title: Referensi API Aspose.Slides untuk C++
description: "Delimiter Beginning Character menentukan karakter delimiter awal, atau pembuka. Delimiter matematis adalah karakter penutup seperti tanda kurung, siku, dan kurung kurawal. Nilai default: '('."
type: docs
weight: 27
url: /id/aspose.slides.mathtext/mathdelimiter/set_beginningcharacter/
---
## MathDelimiter::set_BeginningCharacter(char16_t) metode

Delimiter Beginning Character menentukan karakter delimiter awal, atau pembuka. Delimiter matematis merupakan karakter penutup seperti tanda kurung, siku, dan kurung kurawal. Nilai default: '('.

```cpp
void Aspose::Slides::MathText::MathDelimiter::set_BeginningCharacter(char16_t value) override
```

## Keterangan

Contoh:
```cpp
auto delimiter = System::ExplicitCast<IMathElement>(System::MakeObject<MathematicalText>(u"x")->Join(u"y"))->Enclose();
delimiter->set_BeginningCharacter(u'[');
```

## Lihat Juga

* Kelas [MathDelimiter](../)
* Ruang Nama [Aspose::Slides::MathText](../../)
* Pustaka [Aspose.Slides](../../../)