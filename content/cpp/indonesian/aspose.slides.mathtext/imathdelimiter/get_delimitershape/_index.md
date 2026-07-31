---
title: get_DelimiterShape()
second_title: Referensi API Aspose.Slides untuk C++
description: "Menentukan bentuk pembatas dalam objek pembatas. Ketika MathDelimiterShape::Centered, pembatas diposisikan di tengah sumbu matematika teks matematika dan masih dapat disesuaikan untuk memenuhi seluruh tinggi kontennya. Ketika MathDelimiterShape::Match, tinggi dan bentuknya diubah agar tepat sesuai dengan kontennya."
type: docs
weight: 118
url: /id/aspose.slides.mathtext/imathdelimiter/get_delimitershape/
---
## IMathDelimiter::get_DelimiterShape() metode

Menentukan bentuk pembatas dalam objek pembatas. Ketika [MathDelimiterShape::Centered](../../mathdelimitershape/), pembatas diposisikan di tengah sumbu matematika teks matematika dan masih dapat disesuaikan untuk memenuhi seluruh tinggi kontennya. Ketika [MathDelimiterShape::Match](../../mathdelimitershape/), tinggi dan bentuknya diubah agar tepat cocok dengan kontennya.

```cpp
virtual MathDelimiterShape Aspose::Slides::MathText::IMathDelimiter::get_DelimiterShape()=0
```

## Keterangan

Contoh: 
```cpp
auto delimiter = System::MakeObject<MathematicalText>(u"x")->Divide(u"y")->Enclose();
delimiter->set_DelimiterShape(MathDelimiterShape::Match);
```

## Lihat Juga

* Enum [MathDelimiterShape](../../mathdelimitershape/)
* Kelas [IMathDelimiter](../)
* Ruang nama [Aspose::Slides::MathText](../../)
* Pustaka [Aspose.Slides](../../../)