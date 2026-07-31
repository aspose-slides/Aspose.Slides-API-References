---
title: get_DelimiterShape()
second_title: Referensi API Aspose.Slides untuk C++
description: "Menentukan bentuk delimiter dalam objek delimiter. Ketika MathDelimiterShape::Centered, delimiter dipusatkan di sekitar sumbu matematika dari teks matematis dan tetap dibuat agar sesuai dengan seluruh tinggi kontennya. Ketika MathDelimiterShape::Match, tinggi dan bentuknya diubah agar tepat sesuai dengan kontennya."
type: docs
weight: 118
url: /id/aspose.slides.mathtext/mathdelimiter/get_delimitershape/
---
## MathDelimiter::get_DelimiterShape() metode


Menentukan bentuk delimiter dalam objek delimiter. Ketika [MathDelimiterShape::Centered](../../mathdelimitershape/), delimiter dipusatkan di sekitar sumbu matematika dari teks matematis dan tetap dibuat agar sesuai dengan seluruh tinggi kontennya. Ketika [MathDelimiterShape::Match](../../mathdelimitershape/), tinggi dan bentuknya diubah agar tepat sesuai dengan kontennya.

```cpp
MathDelimiterShape Aspose::Slides::MathText::MathDelimiter::get_DelimiterShape() override
```

## Catatan


Contoh: 
```cpp
auto delimiter = System::MakeObject<MathematicalText>(u"x")->Divide(u"y")->Enclose();
delimiter->set_DelimiterShape(MathDelimiterShape::Match);
```

## Lihat Juga

* Enum [MathDelimiterShape](../../mathdelimitershape/)
* Kelas [MathDelimiter](../)
* Ruang Nama [Aspose::Slides::MathText](../../)
* Perpustakaan [Aspose.Slides](../../../)