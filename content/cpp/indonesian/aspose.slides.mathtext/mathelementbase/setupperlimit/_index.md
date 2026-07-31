---
title: SetUpperLimit()
second_title: Aspose.Slides untuk Referensi API C++
description: Menerima batas atas
type: docs
weight: 131
url: /id/aspose.slides.mathtext/mathelementbase/setupperlimit/
---
## MathElementBase::SetUpperLimit(System::SharedPtr\<IMathElement\>) metode


Menerima batas atas

```cpp
System::SharedPtr<IMathLimit> Aspose::Slides::MathText::MathElementBase::SetUpperLimit(System::SharedPtr<IMathElement> limit) override
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| limit | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | limit |

### Nilai Kembalian

Instansi baru tipe [IMathLimit](../../imathlimit/)
## Keterangan



Contoh: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"y");
auto limitValue = System::MakeObject<MathematicalText>(u"y?>1");
auto limitElement = baseElement->SetUpperLimit(limitValue);
```

## MathElementBase::SetUpperLimit(System::String) metode


Menerima batas atas

```cpp
System::SharedPtr<IMathLimit> Aspose::Slides::MathText::MathElementBase::SetUpperLimit(System::String limit) override
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| limit | [System::String](../../../system/string/) | limit |

### Nilai Kembalian

Instansi baru tipe [IMathLimit](../../imathlimit/)
## Keterangan



Contoh: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"y");
auto limitElement = baseElement->SetUpperLimit(u"y?>1");
```

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [IMathLimit](../../imathlimit/)
* Kelas [IMathElement](../../imathelement/)
* Kelas [MathElementBase](../)
* Kelas [String](../../../system/string/)
* Ruang Nama [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)