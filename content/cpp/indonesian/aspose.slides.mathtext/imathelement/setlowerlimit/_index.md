---
title: SetLowerLimit()
second_title: Referensi API Aspose.Slides untuk C++
description: Mengambil batas bawah
type: docs
weight: 157
url: /id/aspose.slides.mathtext/imathelement/setlowerlimit/
---
## IMathElement::SetLowerLimit(System::SharedPtr\<IMathElement\>) method

Mengambil batas bawah

```cpp
virtual System::SharedPtr<IMathLimit> Aspose::Slides::MathText::IMathElement::SetLowerLimit(System::SharedPtr<IMathElement> limit)=0
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| limit | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | limit |

### Nilai Kembali

Instansi baru dari tipe [IMathLimit](../../imathlimit/)

## Catatan

Contoh:
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"lim");
auto limitValue = System::MakeObject<MathematicalText>(u"\U0001d45b→∞");
auto limitElement = baseElement->SetLowerLimit(limitValue);
```

## IMathElement::SetLowerLimit(System::String) method

Mengambil batas bawah

```cpp
virtual System::SharedPtr<IMathLimit> Aspose::Slides::MathText::IMathElement::SetLowerLimit(System::String limit)=0
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| limit | [System::String](../../../system/string/) | limit |

### Nilai Kembali

Instansi baru dari tipe [IMathLimit](../../imathlimit/)

## Catatan

Contoh:
```cpp
System::SharedPtr<IMathElement> baseElement = System::MakeObject<MathematicalText>(u"lim");
auto limitElement = baseElement->SetLowerLimit(u"\U0001d45b→∞");
```

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [IMathLimit](../../imathlimit/)
* Kelas [IMathElement](../)
* Kelas [String](../../../system/string/)
* Namespace [Aspose::Slides::MathText](../../)
* Perpustakaan [Aspose.Slides](../../../)