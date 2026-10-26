---
title: SetSubscript()
second_title: Referensi API Aspose.Slides untuk C++
description: Membuat subskrip
type: docs
weight: 66
url: /id/aspose.slides.mathtext/mathelementbase/setsubscript/
---
## MathElementBase::SetSubscript(System::SharedPtr\<IMathElement\>) metode


Membuat subskrip

```cpp
System::SharedPtr<IMathSubscriptElement> Aspose::Slides::MathText::MathElementBase::SetSubscript(System::SharedPtr<IMathElement> subscript) override
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| subscript | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Subskrip (indeks bawah di kanan) |

### Nilai Kembali

Elemen matematika baru tipe [IMathSubscriptElement](../../imathsubscriptelement/)
## Catatan



Contoh: 
```cpp
auto element = System::MakeObject<MathematicalText>(u"N");
auto index = System::MakeObject<MathematicalText>(u"i");
auto subscript = element->SetSubscript(index);
```

## MathElementBase::SetSubscript(System::String) metode


Membuat subskrip

```cpp
System::SharedPtr<IMathSubscriptElement> Aspose::Slides::MathText::MathElementBase::SetSubscript(System::String subscript) override
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| subscript | [System::String](../../../system/string/) | Subskrip (indeks bawah di kanan) |

### Nilai Kembali

Elemen matematika baru tipe [IMathSubscriptElement](../../imathsubscriptelement/)
## Catatan



Contoh: 
```cpp
auto element = System::MakeObject<MathematicalText>(u"N");
auto subscript = element->SetSubscript(u"i");
```

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [IMathSubscriptElement](../../imathsubscriptelement/)
* Kelas [IMathElement](../../imathelement/)
* Kelas [MathElementBase](../)
* Kelas [String](../../../system/string/)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)