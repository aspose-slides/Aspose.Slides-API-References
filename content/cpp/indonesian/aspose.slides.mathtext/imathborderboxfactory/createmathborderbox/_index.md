---
title: CreateMathBorderBox()
second_title: Referensi API Aspose.Slides untuk C++
description: Buat kotak batas matematika dengan menerapkannya pada elemen
type: docs
weight: 1
url: /id/aspose.slides.mathtext/imathborderboxfactory/createmathborderbox/
---
## IMathBorderBoxFactory::CreateMathBorderBox(System::SharedPtr\<IMathElement\>) method

Buat kotak batas matematika dengan menerapkannya pada elemen

```cpp
virtual System::SharedPtr<IMathBorderBox> Aspose::Slides::MathText::IMathBorderBoxFactory::CreateMathBorderBox(System::SharedPtr<IMathElement> element)=0
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | elemen matematika untuk menerapkan kotak batas |

### Nilai Kembalian

elemen kotak batas baru

## IMathBorderBoxFactory::CreateMathBorderBox(System::SharedPtr\<IMathElement\>, bool, bool, bool, bool, bool, bool, bool, bool) method

Buat kotak batas matematika dengan menerapkannya pada elemen

```cpp
virtual System::SharedPtr<IMathBorderBox> Aspose::Slides::MathText::IMathBorderBoxFactory::CreateMathBorderBox(System::SharedPtr<IMathElement> element, bool hideTop, bool hideBottom, bool hideLeft, bool hideRight, bool strikethroughHorizontal, bool strikethroughVertical, bool strikethroughBottomLeftToTopRight, bool strikethroughTopLeftToBottomRight)=0
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | elemen matematika untuk menerapkan kotak batas |
| hideTop | **bool** | Sembunyikan Tepi Atas |
| hideBottom | **bool** | Sembunyikan Tepi Bawah |
| hideLeft | **bool** | Sembunyikan Tepi Kiri |
| hideRight | **bool** | Sembunyikan Tepi Kanan |
| strikethroughHorizontal | **bool** | Garis Coret Horizontal Kotak Batas |
| strikethroughVertical | **bool** | Garis Coret Vertikal Kotak Batas |
| strikethroughBottomLeftToTopRight | **bool** | Garis Coret Kotak Batas Dari Kiri-Bawah ke Kanan-Atas |
| strikethroughTopLeftToBottomRight | **bool** | Garis Coret Kotak Batas Dari Kiri-Atas ke Kanan-Bawah |

### Nilai Kembalian

elemen kotak batas baru

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [IMathBorderBox](../../imathborderbox/)
* Kelas [IMathElement](../../imathelement/)
* Kelas [IMathBorderBoxFactory](../)
* Ruang Nama [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)