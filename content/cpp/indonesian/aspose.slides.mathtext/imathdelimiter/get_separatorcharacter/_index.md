---
title: get_SeparatorCharacter()
second_title: Referensi API Aspose.Slides untuk C++
description: "Delimiter Separator Character menentukan karakter yang memisahkan argumen dalam objek delimiter. Nilai default: '|'."
type: docs
weight: 40
url: /id/aspose.slides.mathtext/imathdelimiter/get_separatorcharacter/
---
## IMathDelimiter::get_SeparatorCharacter() metode

Delimiter Separator Character menentukan karakter yang memisahkan argumen dalam objek delimiter. Nilai default: '|'.

```cpp
virtual char16_t Aspose::Slides::MathText::IMathDelimiter::get_SeparatorCharacter()=0
```

## Catatan

Contoh: 
```cpp
auto delimiter = System::ExplicitCast<IMathElement>(System::MakeObject<MathematicalText>(u"x")->Join(u"y"))->Enclose();
delimiter->set_SeparatorCharacter(u'$');
```

## Lihat Juga

* Kelas [IMathDelimiter](../)
* Ruang nama [Aspose::Slides::MathText](../../)
* Perpustakaan [Aspose.Slides](../../../)