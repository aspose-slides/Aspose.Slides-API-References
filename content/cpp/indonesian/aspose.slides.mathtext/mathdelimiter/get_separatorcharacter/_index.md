---
title: get_SeparatorCharacter()
second_title: Referensi API Aspose.Slides untuk C++
description: "Delimiter Separator Character menentukan karakter yang memisahkan argumen dalam objek delimiter. Default: '|'."
type: docs
weight: 40
url: /id/aspose.slides.mathtext/mathdelimiter/get_separatorcharacter/
---
## MathDelimiter::get_SeparatorCharacter() metode

Delimiter Separator Character menentukan karakter yang memisahkan argumen dalam objek delimiter. Default: '|'.

```cpp
char16_t Aspose::Slides::MathText::MathDelimiter::get_SeparatorCharacter() override
```

## Catatan

Contoh:
```cpp
auto delimiter = System::ExplicitCast<IMathElement>(System::MakeObject<MathematicalText>(u"x")->Join(u"y"))->Enclose();
delimiter->set_SeparatorCharacter(u'$');
```

## Lihat Juga

* Kelas [MathDelimiter](../)
* Ruang nama [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)