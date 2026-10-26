---
title: set_BeginningCharacter()
second_title: Referensi API Aspose.Slides untuk C++
description: "Delimiter Beginning Character menentukan karakter pembatas awal, atau pembuka. Delimiter matematika adalah karakter pembungkus seperti tanda kurung, kurung siku, dan kurung kurawal. Nilai default: '('."
type: docs
weight: 27
url: /id/aspose.slides.mathtext/imathdelimiter/set_beginningcharacter/
---
## IMathDelimiter::set_BeginningCharacter(char16_t) metode


Delimiter Beginning Character menentukan karakter pembatas awal, atau pembuka. Delimiter matematika adalah karakter pembungkus seperti tanda kurung, kurung siku, dan kurung kurawal. Nilai default: '('.

```cpp
virtual void Aspose::Slides::MathText::IMathDelimiter::set_BeginningCharacter(char16_t value)=0
```

## Catatan


Contoh: 
```cpp
auto delimiter = System::ExplicitCast<IMathElement>(System::MakeObject<MathematicalText>(u"x")->Join(u"y"))->Enclose();
delimiter->set_BeginningCharacter(u'[');
```

## Lihat Juga

* Kelas [IMathDelimiter](../)
* Ruang Nama [Aspose::Slides::MathText](../../)
* Pustaka [Aspose.Slides](../../../)