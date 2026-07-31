---
title: get_BeginningCharacter()
second_title: Referensi API Aspose.Slides untuk C++
description: "Karakter Awal Pembatas menentukan karakter pembatas yang berada di awal, atau pembuka. Pembatas matematis adalah karakter yang mengelilingi seperti kurung, tanda kurung siku, dan kurung kurawal. Nilai default: '('."
type: docs
weight: 14
url: /id/aspose.slides.mathtext/mathdelimiter/get_beginningcharacter/
---
## MathDelimiter::get_BeginningCharacter() metode


Karakter Awal Pembatas menentukan karakter pembatas yang berada di awal, atau pembuka. Pembatas matematis adalah karakter yang mengelilingi seperti kurung, tanda kurung siku, dan kurung kurawal. Nilai default: '('.

```cpp
char16_t Aspose::Slides::MathText::MathDelimiter::get_BeginningCharacter() override
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
* Perpustakaan [Aspose.Slides](../../../)