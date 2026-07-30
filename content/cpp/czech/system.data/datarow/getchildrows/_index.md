---
title: GetChildRows()
second_title: Aspose.Slides pro C++ – reference API
description: Získává řádky, které jsou považovány za podřízené prostřednictvím zadaného vztahu.
type: docs
weight: 27
url: /cs/system.data/datarow/getchildrows/
---
## DataRow::GetChildRows(const System::SharedPtr\<System::Data::DataRelation\>\&) metoda


Získává řádky, které jsou považovány za podřízené prostřednictvím zadaného vztahu.

```cpp
System::ArrayPtr<System::SharedPtr<System::Data::DataRow>> System::Data::DataRow::GetChildRows(const System::SharedPtr<System::Data::DataRelation> &relation)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| relation | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Data::DataRelation](../../datarelation/)\>\& | Objekt vztahu pro určení vztahu rodič-řádek - podřízený řádek. |

### Návratová hodnota

[Array](../../../system/array/) podřízených řádků.

## Viz také

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [DataRow](../)
* Třída [DataRelation](../../datarelation/)
* Jmenný prostor [System::Data](../../)
* Knihovna [Aspose.Slides](../../../)