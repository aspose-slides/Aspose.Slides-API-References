---
title: MathBorderBox()
second_title: Referensi API Aspose.Slides untuk C++
description: Membuat elemen MathBorderBox dengan border persegi panjang
type: docs
weight: 222
url: /id/aspose.slides.mathtext/mathborderbox/mathborderbox/
---
## MathBorderBox::MathBorderBox(System::SharedPtr\<IMathElement\>) konstruktor


Membuat [MathBorderBox](../) elemen dengan border persegi panjang

```cpp
Aspose::Slides::MathText::MathBorderBox::MathBorderBox(System::SharedPtr<IMathElement> element)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Elemen dasar tempat border box diterapkan. Dapat bernilai null. |
## Catatan



Contoh: 
```cpp
auto borderBox = System::MakeObject<MathBorderBox>(System::MakeObject<MathematicalText>(u"x"));
```

## MathBorderBox::MathBorderBox(System::SharedPtr\<IMathElement\>, bool, bool, bool, bool, bool, bool, bool, bool) konstruktor


Membuat [MathBorderBox](../) elemen

```cpp
Aspose::Slides::MathText::MathBorderBox::MathBorderBox(System::SharedPtr<IMathElement> element, bool hideTop, bool hideBottom, bool hideLeft, bool hideRight, bool strikethroughHorizontal, bool strikethroughVertical, bool strikethroughBottomLeftToTopRight, bool strikethroughTopLeftToBottomRight)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Elemen dasar tempat border box diterapkan |
| hideTop | **bool** | Sembunyikan Tepi Atas |
| hideBottom | **bool** | Sembunyikan Tepi Bawah |
| hideLeft | **bool** | Sembunyikan Tepi Kiri |
| hideRight | **bool** | Sembunyikan Tepi Kanan |
| strikethroughHorizontal | **bool** | Garis coret Horizontal |
| strikethroughVertical | **bool** | Garis coret Vertikal |
| strikethroughBottomLeftToTopRight | **bool** | Garis coret dari Bawah-Kiri ke Atas-Kanan |
| strikethroughTopLeftToBottomRight | **bool** | Garis coret dari Atas-Kiri ke Bawah-Kanan |
## Catatan



Contoh: 
```cpp
auto borderBox = System::MakeObject<MathBorderBox>(System::MakeObject<MathematicalText>(u"x"), true, true, true, false, true, true, true, true);
```

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IMathElement](../../imathelement/)
* Class [MathBorderBox](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)