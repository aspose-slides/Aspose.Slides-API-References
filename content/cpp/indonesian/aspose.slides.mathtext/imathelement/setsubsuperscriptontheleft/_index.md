---
title: SetSubSuperscriptOnTheLeft()
second_title: Referensi API Aspose.Slides untuk C++
description: Membuat subskrip dan superskrip di sebelah kiri
type: docs
weight: 118
url: /id/aspose.slides.mathtext/imathelement/setsubsuperscriptontheleft/
---
## IMathElement::SetSubSuperscriptOnTheLeft(System::SharedPtr\<IMathElement\>, System::SharedPtr\<IMathElement\>) metode

Membuat subskrip dan superskrip di sebelah kiri

```cpp
virtual System::SharedPtr<IMathLeftSubSuperscriptElement> Aspose::Slides::MathText::IMathElement::SetSubSuperscriptOnTheLeft(System::SharedPtr<IMathElement> subscript, System::SharedPtr<IMathElement> superscript)=0
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| subscript | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | Subskrip (indeks bawah di sebelah kiri) |
| superscript | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | Superskrip (indeks atas di sebelah kiri) |

### Nilai Kembalian

Elemen matematika baru tipe [IMathLeftSubSuperscriptElement](../../imathleftsubsuperscriptelement/)
## Catatan



Contoh: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"N");
auto subscript = System::MakeObject<MathematicalText>(u"i");
auto superscript = System::MakeObject<MathematicalText>(u"j");
auto leftSubsuperscript = baseElement->SetSubSuperscriptOnTheLeft(subscript, superscript);
```

## IMathElement::SetSubSuperscriptOnTheLeft(System::String, System::String) metode

Membuat subskrip dan superskrip di sebelah kiri

```cpp
virtual System::SharedPtr<IMathLeftSubSuperscriptElement> Aspose::Slides::MathText::IMathElement::SetSubSuperscriptOnTheLeft(System::String subscript, System::String superscript)=0
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| subscript | [System::String](../../../system/string/) | Subskrip (indeks bawah di sebelah kiri) |
| superscript | [System::String](../../../system/string/) | Superskrip (indeks atas di sebelah kiri) |

### Nilai Kembalian

Elemen matematika baru tipe [IMathLeftSubSuperscriptElement](../../imathleftsubsuperscriptelement/)
## Catatan



Contoh: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"N");
auto leftSubsuperscript = baseElement->SetSubSuperscriptOnTheLeft(u"i", u"j");
```

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [IMathLeftSubSuperscriptElement](../../imathleftsubsuperscriptelement/)
* Kelas [IMathElement](../)
* Kelas [String](../../../system/string/)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)