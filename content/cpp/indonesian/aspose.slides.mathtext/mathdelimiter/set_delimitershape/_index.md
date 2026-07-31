---
title: set_DelimiterShape()
second_title: Referensi API Aspose.Slides untuk C++
description: "Menentukan bentuk delimiter dalam objek delimiter. Ketika MathDelimiterShape::Centered, delimiter dipusatkan di sekitar sumbu matematika dari teks matematika dan masih dibuat agar sesuai dengan tinggi keseluruhan isi mereka. Ketika MathDelimiterShape::Match, tinggi dan bentuknya diubah agar tepat mencocokkan isi mereka."
type: docs
weight: 131
url: /id/aspose.slides.mathtext/mathdelimiter/set_delimitershape/
---
## MathDelimiter::set_DelimiterShape(MathDelimiterShape) metode


Menentukan bentuk delimiter dalam objek delimiter. Ketika [MathDelimiterShape::Centered](../../mathdelimitershape/), delimiter dipusatkan di sekitar sumbu matematika dari teks matematika dan masih dibuat agar sesuai dengan tinggi keseluruhan isi mereka. Ketika [MathDelimiterShape::Match](../../mathdelimitershape/), tinggi dan bentuknya diubah agar tepat mencocokkan isi mereka.

```cpp
void Aspose::Slides::MathText::MathDelimiter::set_DelimiterShape(MathDelimiterShape value) override
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
* Library [Aspose.Slides](../../../)