---
title: SetSubSuperscriptOnTheRight()
second_title: Referensi API Aspose.Slides untuk C++
description: Membuat subskrip dan superskrip di sebelah kanan
type: docs
weight: 92
url: /id/aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright/
---
## MathElementBase::SetSubSuperscriptOnTheRight(System::SharedPtr\<IMathElement\>, System::SharedPtr\<IMathElement\>) method


Membuat subskrip dan superskrip di sebelah kanan

```cpp
System::SharedPtr<IMathRightSubSuperscriptElement> Aspose::Slides::MathText::MathElementBase::SetSubSuperscriptOnTheRight(System::SharedPtr<IMathElement> subscript, System::SharedPtr<IMathElement> superscript) override
```


### Argumen

| Parameter | Type | Description |
| --- | --- | --- |
| subscript | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Subskrip (indeks bawah di sebelah kanan) |
| superscript | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Superskrip (indeks atas di sebelah kanan) |

### Nilai Kembali

Elemen matematika baru berjenis [IMathRightSubSuperscriptElement](../../imathrightsubsuperscriptelement/)
## Catatan



Contoh: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"N");
auto subscript = System::MakeObject<MathematicalText>(u"i");
auto superscript = System::MakeObject<MathematicalText>(u"j");
auto subsuperscript = baseElement->SetSubSuperscriptOnTheRight(subscript, superscript);
```

## MathElementBase::SetSubSuperscriptOnTheRight(System::String, System::String) method


Membuat subskrip dan superskrip di sebelah kanan

```cpp
System::SharedPtr<IMathRightSubSuperscriptElement> Aspose::Slides::MathText::MathElementBase::SetSubSuperscriptOnTheRight(System::String subscript, System::String superscript) override
```


### Argumen

| Parameter | Type | Description |
| --- | --- | --- |
| subscript | [System::String](../../../system/string/) | Subskrip (indeks bawah di sebelah kanan) |
| superscript | [System::String](../../../system/string/) | Superskrip (indeks atas di sebelah kanan) |

### Nilai Kembali

Elemen matematika baru berjenis [IMathRightSubSuperscriptElement](../../imathrightsubsuperscriptelement/)
## Catatan



Contoh: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"N");
auto subsuperscript = baseElement->SetSubSuperscriptOnTheRight(u"i", u"j");
```

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IMathRightSubSuperscriptElement](../../imathrightsubsuperscriptelement/)
* Class [IMathElement](../../imathelement/)
* Class [MathElementBase](../)
* Class [String](../../../system/string/)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)