---
title: set_OperatorEmulator()
second_title: Aspose.Slides untuk Referensi API C++
description: "Operator Emulator. Ketika bernilai true, kotak dan isinya berperilaku sebagai satu operator tunggal dan mewarisi properti sebuah operator. Ini berarti, misalnya, bahwa karakter dapat berfungsi sebagai titik untuk pemutusan baris dan dapat diselaraskan dengan operator lain. Operator Emulator sering digunakan ketika satu atau lebih glyph digabung menjadi sebuah operator, seperti '=='. Nilai default: false"
type: docs
weight: 27
url: /id/aspose.slides.mathtext/mathbox/set_operatoremulator/
---
## MathBox::set_OperatorEmulator(bool) metode

Operator Emulator. Ketika bernilai true, kotak dan isinya berperilaku sebagai satu operator tunggal dan mewarisi properti dari sebuah operator. Ini berarti, misalnya, bahwa karakter dapat berfungsi sebagai titik untuk pemutusan baris dan dapat disejajarkan dengan operator lain. Operator Emulator sering digunakan ketika satu atau lebih glyph digabungkan menjadi sebuah operator, seperti '=='. Nilai default: false

```cpp
void Aspose::Slides::MathText::MathBox::set_OperatorEmulator(bool value) override
```

## Catatan


Contoh: 
```cpp
auto box = System::MakeObject<MathBox>(System::MakeObject<MathematicalText>(u"=="));
box->set_OperatorEmulator(true);
```

## Lihat Juga

* Kelas [MathBox](../)
* Ruang Nama [Aspose::Slides::MathText](../../)
* Perpustakaan [Aspose.Slides](../../../)