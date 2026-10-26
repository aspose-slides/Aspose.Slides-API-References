---
title: SetUpperLimit()
second_title: Referensi API Aspose.Slides untuk C++
description: Mengambil batas atas
type: docs
weight: 144
url: /id/aspose.slides.mathtext/imathelement/setupperlimit/
---
## IMathElement::SetUpperLimit(System::SharedPtr\<IMathElement\>) metode


Mengambil batas atas

```cpp
virtual System::SharedPtr<IMathLimit> Aspose::Slides::MathText::IMathElement::SetUpperLimit(System::SharedPtr<IMathElement> limit)=0
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| limit | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | limit |

### Nilai Kembalian

Instansi baru dari tipe [IMathLimit](../../imathlimit/)
## Catatan



Contoh: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"y");
auto limitValue = System::MakeObject<MathematicalText>(u"y?>1");
auto limitElement = baseElement->SetUpperLimit(limitValue);
```

## IMathElement::SetUpperLimit(System::String) metode


Mengambil batas atas

```cpp
virtual System::SharedPtr<IMathLimit> Aspose::Slides::MathText::IMathElement::SetUpperLimit(System::String limit)=0
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| limit | [System::String](../../../system/string/) | limit |

### Nilai Kembalian

Instansi baru dari tipe [IMathLimit](../../imathlimit/)
## Catatan



Contoh: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"y");
auto limitElement = baseElement->SetUpperLimit(u"y?>1");
```

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [IMathLimit](../../imathlimit/)
* Kelas [IMathElement](../)
* Kelas [String](../../../system/string/)
* Ruang Nama [Aspose::Slides::MathText](../../)
* Perpustakaan [Aspose.Slides](../../../)