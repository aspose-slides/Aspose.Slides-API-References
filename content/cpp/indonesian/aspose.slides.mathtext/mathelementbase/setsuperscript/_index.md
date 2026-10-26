---
title: SetSuperscript()
second_title: Referensi API Aspose.Slides untuk C++
description: Membuat superskrip
type: docs
weight: 79
url: /id/aspose.slides.mathtext/mathelementbase/setsuperscript/
---
## MathElementBase::SetSuperscript(System::SharedPtr\<IMathElement\>) metode


Membuat superskrip

```cpp
System::SharedPtr<IMathSuperscriptElement> Aspose::Slides::MathText::MathElementBase::SetSuperscript(System::SharedPtr<IMathElement> superscript) override
```


### Arguments

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| superscript | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Superskrip (indeks atas di sebelah kanan) |

### Return Value

Elemen matematika baru dengan tipe [IMathSuperscriptElement](../../imathsuperscriptelement/)
## Remarks



Contoh: 
```cpp
auto element = System::MakeObject<MathematicalText>(u"N");
auto index = System::MakeObject<MathematicalText>(u"4");
auto superscript = element->SetSuperscript(index);
```

## MathElementBase::SetSuperscript(System::String) metode


Membuat superskrip

```cpp
System::SharedPtr<IMathSuperscriptElement> Aspose::Slides::MathText::MathElementBase::SetSuperscript(System::String superscript) override
```


### Arguments

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| superscript | [System::String](../../../system/string/) | Superskrip (indeks atas di sebelah kanan) |

### Return Value

Elemen matematika baru dengan tipe [IMathSuperscriptElement](../../imathsuperscriptelement/)
## Remarks



Contoh: 
```cpp
auto element = System::MakeObject<MathematicalText>(u"N");
auto superscript = element->SetSuperscript(u"4");
```

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IMathSuperscriptElement](../../imathsuperscriptelement/)
* Class [IMathElement](../../imathelement/)
* Class [MathElementBase](../)
* Class [String](../../../system/string/)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)