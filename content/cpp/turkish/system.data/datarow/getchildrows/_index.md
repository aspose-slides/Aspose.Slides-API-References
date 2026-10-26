---
title: GetChildRows()
second_title: Aspose.Slides C++ için API Referansı
description: Belirtilen ilişki aracılığıyla çocuk olarak kabul edilen satırları alır.
type: docs
weight: 27
url: /tr/system.data/datarow/getchildrows/
---
## DataRow::GetChildRows(const System::SharedPtr\<System::Data::DataRelation\>\&) method

Belirtilen ilişki aracılığıyla çocuk olarak kabul edilen satırları alır.

```cpp
System::ArrayPtr<System::SharedPtr<System::Data::DataRow>> System::Data::DataRow::GetChildRows(const System::SharedPtr<System::Data::DataRelation> &relation)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| relation | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Data::DataRelation](../../datarelation/)\>\& | Üst satır - alt satır ilişkisinin belirtilmesi için ilişki nesnesi. |

### Dönüş Değeri

[Array](../../../system/array/) alınan çocuk satırların.

## Ayrıca Bakınız

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [DataRow](../)
* Class [DataRelation](../../datarelation/)
* Namespace [System::Data](../../)
* Library [Aspose.Slides](../../../)