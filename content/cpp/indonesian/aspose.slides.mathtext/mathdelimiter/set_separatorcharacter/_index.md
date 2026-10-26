---
title: set_SeparatorCharacter()
second_title: Referensi API Aspose.Slides untuk C++
description: "Delimiter Separator Character menentukan karakter yang memisahkan argumen dalam objek delimiter. Defaultnya: '|'."
type: docs
weight: 53
url: /id/aspose.slides.mathtext/mathdelimiter/set_separatorcharacter/
---
## MathDelimiter::set_SeparatorCharacter(char16_t) metode

Delimiter Separator Character menentukan karakter yang memisahkan argumen dalam objek delimiter. Defaultnya: '|'.

```cpp
void Aspose::Slides::MathText::MathDelimiter::set_SeparatorCharacter(char16_t value) override
```

## Keterangan

Contoh: 
```cpp
auto delimiter = System::ExplicitCast<IMathElement>(System::MakeObject<MathematicalText>(u"x")->Join(u"y"))->Enclose();
delimiter->set_SeparatorCharacter(u'$');
```

## Lihat Juga

* Kelas [MathDelimiter](../)
* Ruang Nama [Aspose::Slides::MathText](../../)
* Perpustakaan [Aspose.Slides](../../../)