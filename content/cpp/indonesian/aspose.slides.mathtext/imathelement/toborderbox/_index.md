---
title: ToBorderBox()
second_title: Referensi API Aspose.Slides untuk C++
description: Menempatkan elemen ini dalam kotak batas
type: docs
weight: 261
url: /id/aspose.slides.mathtext/imathelement/toborderbox/
---
## IMathElement::ToBorderBox() metode

Menempatkan elemen ini dalam kotak batas

```cpp
virtual System::SharedPtr<IMathBorderBox> Aspose::Slides::MathText::IMathElement::ToBorderBox()=0
```

### Nilai Kembalian

Kotak batas dengan elemen ini ditempatkan di dalamnya
## Catatan



Contoh: 
```cpp
auto borderBox = System::MakeObject<MathematicalText>(u"x+y+z")->ToBorderBox();
```

## IMathElement::ToBorderBox(bool, bool, bool, bool, bool, bool, bool, bool) metode


Menempatkan elemen ini dalam kotak batas

```cpp
virtual System::SharedPtr<IMathBorderBox> Aspose::Slides::MathText::IMathElement::ToBorderBox(bool hideTop, bool hideBottom, bool hideLeft, bool hideRight, bool strikethroughHorizontal, bool strikethroughVertical, bool strikethroughBottomLeftToTopRight, bool strikethroughTopLeftToBottomRight)=0
```


### Argumen

| Parameter | Type | Description |
| --- | --- | --- |
| hideTop | **bool** | Sembunyikan Tepi Atas |
| hideBottom | **bool** | Sembunyikan Tepi Bawah |
| hideLeft | **bool** | Sembunyikan Tepi Kiri |
| hideRight | **bool** | Sembunyikan Tepi Kanan |
| strikethroughHorizontal | **bool** | Garis Coret Horizontal pada Kotak Batas |
| strikethroughVertical | **bool** | Garis Coret Vertikal pada Kotak Batas |
| strikethroughBottomLeftToTopRight | **bool** | Garis Coret Kotak Batas dari Kiri-Bawah ke Kanan-Atas |
| strikethroughTopLeftToBottomRight | **bool** | Garis Coret Kotak Batas dari Kiri-Atas ke Kanan-Bawah |

### Nilai Kembalian

Kotak batas dengan elemen ini ditempatkan di dalamnya
## Catatan



Contoh: 
```cpp
auto borderBox = System::MakeObject<MathematicalText>(u"x+y+z")->ToBorderBox(false, false, true, true, false, false, false, false);
```

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [IMathBorderBox](../../imathborderbox/)
* Kelas [IMathElement](../)
* Ruang nama [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)