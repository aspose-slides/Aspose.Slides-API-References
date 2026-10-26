---
title: Add()
second_title: Aspose.Slides için C++ API Referansı
description: Koleksiyona bir Tab ekler.
type: docs
weight: 53
url: /tr/aspose.slides/tabcollection/add/
---
## TabCollection::Add(double, TabAlignment) metod

Koleksiyona bir [Tab](../../tab/) ekler.

```cpp
System::SharedPtr<ITab> Aspose::Slides::TabCollection::Add(double position, TabAlignment align) override
```

### Dönüş Değeri

Eklenen sekme.

## TabCollection::Add(System::SharedPtr\<ITab\>) metod

Koleksiyona bir [Tab](../../tab/) ekler.

```cpp
int32_t Aspose::Slides::TabCollection::Add(System::SharedPtr<ITab> value) override
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[ITab](../../itab/)\> | Koleksiyonun sonuna eklenecek [Tab](../../tab/) nesnesi. |

### Dönüş Değeri

Sekmenin eklendiği indeks.

## Ayrıca

* Enum [TabAlignment](../../tabalignment/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ITab](../../itab/)
* Class [TabCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)