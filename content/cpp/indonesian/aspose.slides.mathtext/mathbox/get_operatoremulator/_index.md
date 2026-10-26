---
title: get_OperatorEmulator()
second_title: Referensi API Aspose.Slides untuk C++
description: "Emulator Operator. Ketika bernilai true, kotak dan isinya berperilaku sebagai satu operator dan mewarisi properti sebuah operator. Ini berarti, misalnya, bahwa karakter dapat berfungsi sebagai titik pemisah baris dan dapat disejajarkan dengan operator lain. Emulator Operator sering digunakan ketika satu atau lebih glyph digabungkan menjadi sebuah operator, seperti '=='. Nilai default: false"
type: docs
weight: 14
url: /id/aspose.slides.mathtext/mathbox/get_operatoremulator/
---
## MathBox::get_OperatorEmulator() metode

Emulator Operator. Ketika bernilai true, kotak dan isinya berperilaku sebagai satu operator dan mewarisi properti sebuah operator. Ini berarti, misalnya, bahwa karakter dapat berfungsi sebagai titik pemisah baris dan dapat disejajarkan dengan operator lain. Emulator Operator sering digunakan ketika satu atau lebih glyph digabungkan membentuk sebuah operator, seperti '=='. Nilai default: false

```cpp
bool Aspose::Slides::MathText::MathBox::get_OperatorEmulator() override
```

## Catatan

Contoh:
```cpp
auto box = System::MakeObject<MathBox>(System::MakeObject<MathematicalText>(u"=="));
box->set_OperatorEmulator(true);
```

## Lihat Juga

* Kelas [MathBox](../)
* Ruang nama [Aspose::Slides::MathText](../../)
* Pustaka [Aspose.Slides](../../../)