---
title: get_OperatorEmulator()
second_title: Referensi API Aspose.Slides untuk C++
description: "Operator Emulator. Ketika true, kotak dan isinya berperilaku sebagai satu operator tunggal dan mewarisi properti sebuah operator. Ini berarti, misalnya, bahwa karakter dapat berfungsi sebagai titik pemisah baris dan dapat disejajarkan dengan operator lain. Operator Emulator sering digunakan ketika satu atau beberapa glif digabung menjadi sebuah operator, seperti '=='. Nilai default: false"
type: docs
weight: 14
url: /id/aspose.slides.mathtext/imathbox/get_operatoremulator/
---
## IMathBox::get_OperatorEmulator() metode

Operator Emulator. Ketika true, kotak dan isinya berperilaku sebagai satu operator tunggal dan mewarisi properti sebuah operator. Ini berarti, misalnya, bahwa karakter dapat berfungsi sebagai titik pemisah baris dan dapat disejajarkan dengan operator lain. Operator Emulator sering digunakan ketika satu atau beberapa glif digabungkan menjadi sebuah operator, seperti '=='. Nilai default: false

```cpp
virtual bool Aspose::Slides::MathText::IMathBox::get_OperatorEmulator()=0
```

## Catatan

Contoh: 
```cpp
auto box = System::MakeObject<MathematicalText>(u"==")->ToBox();
box->set_OperatorEmulator(true);
```

## Lihat Juga

* Kelas [IMathBox](../)
* Ruang Nama [Aspose::Slides::MathText](../../)
* Perpustakaan [Aspose.Slides](../../../)