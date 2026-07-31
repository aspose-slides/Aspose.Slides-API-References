---
title: SetLowerLimit()
second_title: Referensi API Aspose.Slides untuk C++
description: Mengambil batas bawah
type: docs
weight: 144
url: /id/aspose.slides.mathtext/mathelementbase/setlowerlimit/
---
## MathElementBase::SetLowerLimit(System::SharedPtr\<IMathElement\>) metode


Mengambil batas bawah

```cpp
System::SharedPtr<IMathLimit> Aspose::Slides::MathText::MathElementBase::SetLowerLimit(System::SharedPtr<IMathElement> limit) override
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| limit | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | limit |

### Nilai Kembali

New instance of type [IMathLimit](../../imathlimit/)
## Catatan



Contoh: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"lim");
auto limitValue = System::MakeObject<MathematicalText>(u"\U0001d45b→∞");
auto limitElement = baseElement->SetLowerLimit(limitValue);
```

## MathElementBase::SetLowerLimit(System::String) metode


Mengambil batas bawah

```cpp
System::SharedPtr<IMathLimit> Aspose::Slides::MathText::MathElementBase::SetLowerLimit(System::String limit) override
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| limit | [System::String](../../../system/string/) | limit |

### Nilai Kembali

New instance of type [IMathLimit](../../imathlimit/)
## Catatan



Contoh: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"lim");
auto limitElement = baseElement->SetLowerLimit(u"\U0001d45b→∞");
```

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [IMathLimit](../../imathlimit/)
* Kelas [IMathElement](../../imathelement/)
* Kelas [MathElementBase](../)
* Kelas [String](../../../system/string/)
* Ruang Nama [Aspose::Slides::MathText](../../)
* Pustaka [Aspose.Slides](../../../)