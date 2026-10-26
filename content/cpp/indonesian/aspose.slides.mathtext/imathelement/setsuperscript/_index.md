---
title: SetSuperscript()
second_title: Referensi API Aspose.Slides untuk C++
description: Membuat superskrip
type: docs
weight: 92
url: /id/aspose.slides.mathtext/imathelement/setsuperscript/
---
## IMathElement::SetSuperscript(System::SharedPtr\<IMathElement\>) metode

Membuat superskrip

```cpp
virtual System::SharedPtr<IMathSuperscriptElement> Aspose::Slides::MathText::IMathElement::SetSuperscript(System::SharedPtr<IMathElement> superscript)=0
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| superscript | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | Superskrip (indeks atas di kanan) |

### Nilai Kembalian

Elemen matematika baru tipe [IMathSuperscriptElement](../../imathsuperscriptelement/)
## Catatan



Contoh: 
```cpp
auto element = System::MakeObject<MathematicalText>(u"N");
auto index = System::MakeObject<MathematicalText>(u"4");
auto superscript = element->SetSuperscript(index);
```

## IMathElement::SetSuperscript(System::String) metode

Membuat superskrip

```cpp
virtual System::SharedPtr<IMathSuperscriptElement> Aspose::Slides::MathText::IMathElement::SetSuperscript(System::String superscript)=0
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| superscript | [System::String](../../../system/string/) | Superskrip (indeks atas di kanan) |

### Nilai Kembalian

Elemen matematika baru tipe [IMathSuperscriptElement](../../imathsuperscriptelement/)
## Catatan



Contoh: 
```cpp
auto element = System::MakeObject<MathematicalText>(u"N");
auto superscript = element->SetSuperscript(u"4");
```

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [IMathSuperscriptElement](../../imathsuperscriptelement/)
* Kelas [IMathElement](../)
* Kelas [String](../../../system/string/)
* Ruang Nama [Aspose::Slides::MathText](../../)
* Pustaka [Aspose.Slides](../../../)