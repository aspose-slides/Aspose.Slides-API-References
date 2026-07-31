---
title: get_BeginningCharacter()
second_title: Referensi API Aspose.Slides untuk C++
description: "Karakter Awal Pembatas menentukan karakter pembatas awal, atau pembuka. Pembatas matematis adalah karakter yang mengelilingi seperti tanda kurung, tanda kurung siku, dan kurung kurawal. Nilai baku: '('."
type: docs
weight: 14
url: /id/aspose.slides.mathtext/imathdelimiter/get_beginningcharacter/
---
## IMathDelimiter::get_BeginningCharacter() metode


Karakter Awal Pembatas menentukan karakter pembatas awal, atau pembuka. Pembatas matematis adalah karakter yang mengelilingi seperti tanda kurung, tanda kurung siku, dan kurung kurawal. Nilai baku: '('.

```cpp
virtual char16_t Aspose::Slides::MathText::IMathDelimiter::get_BeginningCharacter()=0
```

## Keterangan


Contoh: 
```cpp
auto delimiter = System::ExplicitCast<IMathElement>(System::MakeObject<MathematicalText>(u"x")->Join(u"y"))->Enclose();
delimiter->set_BeginningCharacter(u'[');
```

## Lihat Juga

* Kelas [IMathDelimiter](../)
* Ruang Nama [Aspose::Slides::MathText](../../)
* Pustaka [Aspose.Slides](../../../)