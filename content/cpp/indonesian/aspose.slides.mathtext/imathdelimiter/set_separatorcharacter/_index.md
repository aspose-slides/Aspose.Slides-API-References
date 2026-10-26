---
title: set_SeparatorCharacter()
second_title: Referensi API Aspose.Slides untuk C++
description: "Karakter Pemisah Delimiter menentukan karakter yang memisahkan argumen dalam objek delimiter. Nilai bawaan: '|'."
type: docs
weight: 53
url: /id/aspose.slides.mathtext/imathdelimiter/set_separatorcharacter/
---
## IMathDelimiter::set_SeparatorCharacter(char16_t) metode

Karakter Pemisah Delimiter menentukan karakter yang memisahkan argumen dalam objek delimiter. Nilai bawaan: '|'.

```cpp
virtual void Aspose::Slides::MathText::IMathDelimiter::set_SeparatorCharacter(char16_t value)=0
```

## Catatan

Contoh:
```cpp
auto delimiter = System::ExplicitCast<IMathElement>(System::MakeObject<MathematicalText>(u"x")->Join(u"y"))->Enclose();
delimiter->set_SeparatorCharacter(u'$');
```

## Lihat Juga

* Kelas [IMathDelimiter](../)
* Ruang Nama [Aspose::Slides::MathText](../../)
* Pustaka [Aspose.Slides](../../../)