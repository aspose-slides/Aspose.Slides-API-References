---
title: SetSubscript()
second_title: Referensi API Aspose.Slides untuk C++
description: Membuat subskrip
type: docs
weight: 79
url: /id/aspose.slides.mathtext/imathelement/setsubscript/
---
## IMathElement::SetSubscript(System::SharedPtr\<IMathElement\>) metode

Membuat subskrip

```cpp
virtual System::SharedPtr<IMathSubscriptElement> Aspose::Slides::MathText::IMathElement::SetSubscript(System::SharedPtr<IMathElement> subscript)=0
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| subscript | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | Subscript (lower index on the right) |

### Nilai Kembali

New math element of type [IMathSubscriptElement](../../imathsubscriptelement/)

## Catatan

Contoh: 
```cpp
auto element = System::MakeObject<MathematicalText>(u"N");
auto index = System::MakeObject<MathematicalText>(u"i");
auto subscript = element->SetSubscript(index);
```

## IMathElement::SetSubscript(System::String) metode

Membuat subskrip

```cpp
virtual System::SharedPtr<IMathSubscriptElement> Aspose::Slides::MathText::IMathElement::SetSubscript(System::String subscript)=0
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| subscript | [System::String](../../../system/string/) | Subscript (lower index on the right) |

### Nilai Kembali

New math element of type [IMathSubscriptElement](../../imathsubscriptelement/)

## Catatan

Contoh: 
```cpp
auto element = System::MakeObject<MathematicalText>(u"N");
auto subscript = element->SetSubscript(u"i");
```

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [IMathSubscriptElement](../../imathsubscriptelement/)
* Kelas [IMathElement](../)
* Kelas [String](../../../system/string/)
* Ruang Nama [Aspose::Slides::MathText](../../)
* Perpustakaan [Aspose.Slides](../../../)