---
title: set_GrowToMatchOperandHeight()
second_title: Referensi API Aspose.Slides untuk C++
description: Menentukan pertumbuhan BeginningCharacter, SeparatorCharacter, EndingCharacter. Ketika true, pembatas tumbuh secara vertikal untuk menyesuaikan tinggi operannya. Nilai bawaan adalah true
type: docs
weight: 105
url: /id/aspose.slides.mathtext/mathdelimiter/set_growtomatchoperandheight/
---
## MathDelimiter::set_GrowToMatchOperandHeight(bool) metode


Menentukan pertumbuhan BeginningCharacter, SeparatorCharacter, EndingCharacter. Ketika true, delimiter tumbuh secara vertikal untuk menyesuaikan tinggi operannya. Nilai bawaan adalah true

```cpp
void Aspose::Slides::MathText::MathDelimiter::set_GrowToMatchOperandHeight(bool value) override
```

## Catatan


Contoh: 
```cpp
auto delimiter = System::MakeObject<MathematicalText>(u"x")->Divide(u"y")->Enclose();
delimiter->set_GrowToMatchOperandHeight(false);
```

## Lihat Juga

* Kelas [MathDelimiter](../)
* Ruang Nama [Aspose::Slides::MathText](../../)
* Pustaka [Aspose.Slides](../../../)