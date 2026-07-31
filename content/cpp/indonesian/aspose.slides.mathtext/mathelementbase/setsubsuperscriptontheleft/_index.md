---
title: SetSubSuperscriptOnTheLeft()
second_title: Referensi API Aspose.Slides untuk C++
description: Membuat subskrip dan superskrip di sebelah kiri
type: docs
weight: 105
url: /id/aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft/
---
## MathElementBase::SetSubSuperscriptOnTheLeft(System::SharedPtr\<IMathElement\>, System::SharedPtr\<IMathElement\>) metode

Membuat subskrip dan superskrip di sebelah kiri

```cpp
System::SharedPtr<IMathLeftSubSuperscriptElement> Aspose::Slides::MathText::MathElementBase::SetSubSuperscriptOnTheLeft(System::SharedPtr<IMathElement> subscript, System::SharedPtr<IMathElement> superscript) override
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| subscript | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Subskrip (indeks bawah di sebelah kiri) |
| superscript | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Superskrip (indeks atas di sebelah kiri) |

### Nilai Kembalian

Elemen matematika baru bertipe [IMathLeftSubSuperscriptElement](../../imathleftsubsuperscriptelement/)

## Catatan

Contoh: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"N");
auto subscript = System::MakeObject<MathematicalText>(u"i");
auto superscript = System::MakeObject<MathematicalText>(u"j");
auto leftSubsuperscript = baseElement->SetSubSuperscriptOnTheLeft(subscript, superscript);
```

## MathElementBase::SetSubSuperscriptOnTheLeft(System::String, System::String) metode

Membuat subskrip dan superskrip di sebelah kiri

```cpp
System::SharedPtr<IMathLeftSubSuperscriptElement> Aspose::Slides::MathText::MathElementBase::SetSubSuperscriptOnTheLeft(System::String subscript, System::String superscript) override
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| subscript | [System::String](../../../system/string/) | Subskrip (indeks bawah di sebelah kiri) |
| superscript | [System::String](../../../system/string/) | Superskrip (indeks atas di sebelah kiri) |

### Nilai Kembalian

Elemen matematika baru bertipe [IMathLeftSubSuperscriptElement](../../imathleftsubsuperscriptelement/)

## Catatan

Contoh: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"N");
auto leftSubsuperscript = baseElement->SetSubSuperscriptOnTheLeft(u"i", u"j");
```

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [IMathLeftSubSuperscriptElement](../../imathleftsubsuperscriptelement/)
* Kelas [IMathElement](../../imathelement/)
* Kelas [MathElementBase](../)
* Kelas [String](../../../system/string/)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)