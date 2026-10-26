---
title: set_GrowToMatchOperandHeight()
second_title: Referensi API Aspose.Slides untuk C++
description: Menentukan pertumbuhan BeginningCharacter, SeparatorCharacter, EndingCharacter. Ketika true, delimiter tumbuh secara vertikal untuk menyesuaikan tinggi operannya. Nilai default adalah true
type: docs
weight: 105
url: /id/aspose.slides.mathtext/imathdelimiter/set_growtomatchoperandheight/
---
## IMathDelimiter::set_GrowToMatchOperandHeight(bool) metode


Menentukan pertumbuhan BeginningCharacter, SeparatorCharacter, EndingCharacter. Ketika true, delimiter tumbuh secara vertikal untuk menyesuaikan tinggi operandnya. Nilai default adalah true

```cpp
virtual void Aspose::Slides::MathText::IMathDelimiter::set_GrowToMatchOperandHeight(bool value)=0
```

## Catatan


Contoh: 
```cpp
auto delimiter = System::MakeObject<MathematicalText>(u"x")->Divide(u"y")->Enclose();
delimiter->set_GrowToMatchOperandHeight(false);
```

## Lihat Juga

* Kelas [IMathDelimiter](../)
* Ruang Nama [Aspose::Slides::MathText](../../)
* Perpustakaan [Aspose.Slides](../../../)