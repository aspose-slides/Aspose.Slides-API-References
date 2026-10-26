---
title: CreateMathBorderBox()
second_title: Referensi API Aspose.Slides untuk C++
description: Membuat kotak batas matematika dengan menerapkannya pada elemen
type: docs
weight: 1
url: /id/aspose.slides.mathtext/mathborderboxfactory/createmathborderbox/
---
## MathBorderBoxFactory::CreateMathBorderBox(System::SharedPtr\<IMathElement\>) metode

Membuat kotak batas matematika dengan menerapkannya pada elemen

```cpp
System::SharedPtr<IMathBorderBox> Aspose::Slides::MathText::MathBorderBoxFactory::CreateMathBorderBox(System::SharedPtr<IMathElement> element) override
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | elemen matematika untuk menerapkan kotak batas |

### Nilai Kembalian

elemen kotak batas baru

## MathBorderBoxFactory::CreateMathBorderBox(System::SharedPtr\<IMathElement\>, bool, bool, bool, bool, bool, bool, bool, bool) metode

Membuat kotak batas matematika dengan menerapkannya pada elemen

```cpp
System::SharedPtr<IMathBorderBox> Aspose::Slides::MathText::MathBorderBoxFactory::CreateMathBorderBox(System::SharedPtr<IMathElement> element, bool hideTop, bool hideBottom, bool hideLeft, bool hideRight, bool strikethroughHorizontal, bool strikethroughVertical, bool strikethroughBottomLeftToTopRight, bool strikethroughTopLeftToBottomRight) override
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | elemen matematika untuk menerapkan kotak batas |
| hideTop | **bool** | Sembunyikan tepi atas |
| hideBottom | **bool** | Sembunyikan tepi bawah |
| hideLeft | **bool** | Sembunyikan tepi kiri |
| hideRight | **bool** | Sembunyikan tepi kanan |
| strikethroughHorizontal | **bool** | Garis coret horizontal kotak batas |
| strikethroughVertical | **bool** | Garis coret vertikal kotak batas |
| strikethroughBottomLeftToTopRight | **bool** | Garis coret kotak batas dari kiri-bawah ke kanan-atas |
| strikethroughTopLeftToBottomRight | **bool** | Garis coret kotak batas dari kiri-atas ke kanan-bawah |

### Nilai Kembalian

elemen kotak batas baru

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IMathBorderBox](../../imathborderbox/)
* Class [IMathElement](../../imathelement/)
* Class [MathBorderBoxFactory](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)