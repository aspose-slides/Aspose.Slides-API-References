---
title: ToBorderBox()
second_title: Referensi API Aspose.Slides untuk C++
description: Menempatkan elemen ini di dalam border-box
type: docs
weight: 248
url: /id/aspose.slides.mathtext/mathelementbase/toborderbox/
---
## MathElementBase::ToBorderBox() metode


Menempatkan elemen ini ke dalam border-box

```cpp
System::SharedPtr<IMathBorderBox> Aspose::Slides::MathText::MathElementBase::ToBorderBox() override
```


### Nilai Kembalian

Border-box dengan elemen ini ditempatkan di dalamnya
## Catatan



Contoh: 
```cpp
auto borderBox = System::MakeObject<MathematicalText>(u"x+y+z")->ToBorderBox();
```

## MathElementBase::ToBorderBox(bool, bool, bool, bool, bool, bool, bool, bool) metode


Menempatkan elemen ini ke dalam border-box

```cpp
System::SharedPtr<IMathBorderBox> Aspose::Slides::MathText::MathElementBase::ToBorderBox(bool hideTop, bool hideBottom, bool hideLeft, bool hideRight, bool strikethroughHorizontal, bool strikethroughVertical, bool strikethroughBottomLeftToTopRight, bool strikethroughTopLeftToBottomRight) override
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| hideTop | **bool** | Sembunyikan Tepi Atas |
| hideBottom | **bool** | Sembunyikan Tepi Bawah |
| hideLeft | **bool** | Sembunyikan Tepi Kiri |
| hideRight | **bool** | Sembunyikan Tepi Kanan |
| strikethroughHorizontal | **bool** | Border Box Garis Coret Horizontal |
| strikethroughVertical | **bool** | Border Box Garis Coret Vertikal |
| strikethroughBottomLeftToTopRight | **bool** | Border Box Garis Coret Dari Kiri-Bawah ke Kanan-Atas |
| strikethroughTopLeftToBottomRight | **bool** | Border Box Garis Coret Dari Kiri-Atas ke Kanan-Bawah |

### Nilai Kembalian

Border-box dengan elemen ini ditempatkan di dalamnya
## Catatan



Contoh: 
```cpp
auto borderBox = System::MakeObject<MathematicalText>(u"x+y+z")->ToBorderBox(false, false, true, true, false, false, false, false);
```

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [IMathBorderBox](../../imathborderbox/)
* Kelas [MathElementBase](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)