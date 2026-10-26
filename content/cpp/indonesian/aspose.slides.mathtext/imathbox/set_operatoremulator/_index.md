---
title: set_OperatorEmulator()
second_title: Referensi API Aspose.Slides untuk C++
description: "Emulator Operator. Ketika true, kotak dan isinya berperilaku sebagai satu operator dan mewarisi properti sebuah operator. Ini berarti, misalnya, bahwa karakter dapat berfungsi sebagai titik untuk pemutusan baris dan dapat disejajarkan dengan operator lain. Emulator Operator sering digunakan ketika satu atau lebih glyph digabungkan menjadi satu operator, seperti '=='. Nilai default: false"
type: docs
weight: 27
url: /id/aspose.slides.mathtext/imathbox/set_operatoremulator/
---
## IMathBox::set_OperatorEmulator(bool) metode

Emulator Operator. Ketika true, kotak dan isinya berperilaku sebagai satu operator dan mewarisi properti sebuah operator. Ini berarti, misalnya, bahwa karakter dapat berfungsi sebagai titik untuk pemutusan baris dan dapat disejajarkan dengan operator lain. Emulator Operator sering digunakan ketika satu atau lebih glyph digabungkan menjadi satu operator, seperti '=='. Nilai default: false

```cpp
virtual void Aspose::Slides::MathText::IMathBox::set_OperatorEmulator(bool value)=0
```

## Catatan

Contoh:
```cpp
auto box = System::MakeObject<MathematicalText>(u"==")->ToBox();
box->set_OperatorEmulator(true);
```

## Lihat Juga

* Kelas [IMathBox](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)