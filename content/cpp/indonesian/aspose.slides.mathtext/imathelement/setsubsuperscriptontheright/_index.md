---
title: SetSubSuperscriptOnTheRight()
second_title: Referensi API Aspose.Slides untuk C++
description: Membuat subskrip dan superskrip di sebelah kanan
type: docs
weight: 105
url: /id/aspose.slides.mathtext/imathelement/setsubsuperscriptontheright/
---
## IMathElement::SetSubSuperscriptOnTheRight(System::SharedPtr\<IMathElement\>, System::SharedPtr\<IMathElement\>) metode

Membuat subskrip dan superskrip di sebelah kanan

```cpp
virtual System::SharedPtr<IMathRightSubSuperscriptElement> Aspose::Slides::MathText::IMathElement::SetSubSuperscriptOnTheRight(System::SharedPtr<IMathElement> subscript, System::SharedPtr<IMathElement> superscript)=0
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| subscript | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | Subskrip (indeks bawah di sebelah kanan) |
| superscript | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | Superskrip (indeks atas di sebelah kanan) |

### Nilai Kembali

Elemen matematika baru dengan tipe [IMathRightSubSuperscriptElement](../../imathrightsubsuperscriptelement/)

## Catatan

Contoh: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"N");
auto subscript = System::MakeObject<MathematicalText>(u"i");
auto superscript = System::MakeObject<MathematicalText>(u"j");
auto subsuperscript = baseElement->SetSubSuperscriptOnTheRight(subscript, superscript);
```

## IMathElement::SetSubSuperscriptOnTheRight(System::String, System::String) metode

Membuat subskrip dan superskrip di sebelah kanan

```cpp
virtual System::SharedPtr<IMathRightSubSuperscriptElement> Aspose::Slides::MathText::IMathElement::SetSubSuperscriptOnTheRight(System::String subscript, System::String superscript)=0
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| subscript | [System::String](../../../system/string/) | Subskrip (indeks bawah di sebelah kanan) |
| superscript | [System::String](../../../system/string/) | Superskrip (indeks atas di sebelah kanan) |

### Nilai Kembali

Elemen matematika baru dengan tipe [IMathRightSubSuperscriptElement](../../imathrightsubsuperscriptelement/)

## Catatan

Contoh: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"N");
auto subsuperscript = baseElement->SetSubSuperscriptOnTheRight(u"i", u"j");
```

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [IMathRightSubSuperscriptElement](../../imathrightsubsuperscriptelement/)
* Kelas [IMathElement](../)
* Kelas [String](../../../system/string/)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)