---
title: set_DelimiterShape()
second_title: Referensi API Aspose.Slides untuk C++
description: "Menentukan bentuk pembatas dalam objek delimiter. Ketika adalah MathDelimiterShape::Centered, pembatas diposisikan di tengah sumbu matematika dari teks matematis dan tetap dibuat agar menyesuaikan seluruh tinggi isi mereka. Ketika adalah MathDelimiterShape::Match, tinggi dan bentuknya diubah agar tepat cocok dengan isi mereka."
type: docs
weight: 131
url: /id/aspose.slides.mathtext/imathdelimiter/set_delimitershape/
---
## IMathDelimiter::set_DelimiterShape(MathDelimiterShape) metode

Menentukan bentuk pembatas dalam objek delimiter. Ketika [MathDelimiterShape::Centered](../../mathdelimitershape/), pembatas diposisikan di tengah sumbu matematika dari teks matematis dan tetap dibuat agar menyesuaikan seluruh tinggi isi mereka. Ketika [MathDelimiterShape::Match](../../mathdelimitershape/), tinggi dan bentuknya diubah agar tepat cocok dengan isi mereka.

```cpp
virtual void Aspose::Slides::MathText::IMathDelimiter::set_DelimiterShape(MathDelimiterShape value)=0
```

## Catatan

Contoh:
```cpp
auto delimiter = System::MakeObject<MathematicalText>(u"x")->Divide(u"y")->Enclose();
delimiter->set_DelimiterShape(MathDelimiterShape::Match);
```

## Lihat Juga

* Enum [MathDelimiterShape](../../mathdelimitershape/)
* Kelas [IMathDelimiter](../)
* Ruang nama [Aspose::Slides::MathText](../../)
* Perpustakaan [Aspose.Slides](../../../)