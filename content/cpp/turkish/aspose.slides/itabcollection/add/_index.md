---
title: Add()
second_title: Aspose.Slides için C++ API Referansı
description: Koleksiyona bir Tab ekler.
type: docs
weight: 14
url: /tr/aspose.slides/itabcollection/add/
---
## ITabCollection::Add(double, TabAlignment) metodu

[Tab](../../tab/) öğesini koleksiyona ekler.

```cpp
virtual System::SharedPtr<ITab> Aspose::Slides::ITabCollection::Add(double position, TabAlignment align)=0
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| position | **double** | [Tab](../../tab/) konumu. |
| align | [TabAlignment](../../tabalignment/) | [Tab](../../tab/) hizalama. |

### Dönüş Değeri

Eklenen sekme.

## ITabCollection::Add(System::SharedPtr\<ITab\>) metodu

[Tab](../../tab/) öğesini koleksiyona ekler.

```cpp
virtual int32_t Aspose::Slides::ITabCollection::Add(System::SharedPtr<ITab> value)=0
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[ITab](../../itab/)\> | Koleksiyonun sonuna eklenecek [Tab](../../tab/) nesnesi. |

### Dönüş Değeri

Sekmenin eklendiği indeks.

## Ayrıca Bakınız

* Enum [TabAlignment](../../tabalignment/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [ITab](../../itab/)
* Sınıf [ITabCollection](../)
* İsim Alanı [Aspose::Slides](../../)
* Kütüphane [Aspose.Slides](../../../)