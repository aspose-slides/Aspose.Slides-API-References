---
title: GetChildRows()
second_title: Aspose.Slides for C++ API Referencia
description: Lekéri azokat a sorokat, amelyeket a megadott kapcsolat alapján gyermeknek tekintenek.
type: docs
weight: 27
url: /hu/system.data/datarow/getchildrows/
---
## DataRow::GetChildRows(const System::SharedPtr\<System::Data::DataRelation\>\&) metódus

Lekéri azokat a sorokat, amelyeket a megadott kapcsolat alapján gyermeknek tekintenek.

```cpp
System::ArrayPtr<System::SharedPtr<System::Data::DataRow>> System::Data::DataRow::GetChildRows(const System::SharedPtr<System::Data::DataRelation> &relation)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| relation | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Data::DataRelation](../../datarelation/)\>\& | Szülő sor- gyermek sor kapcsolatot meghatározó reláció objektum. |

### Visszatérési érték

[Array](../../../system/array/) a lekért gyermek sorok.

## Lásd még

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [DataRow](../)
* Osztály [DataRelation](../../datarelation/)
* Névterület [System::Data](../../)
* Library [Aspose.Slides](../../../)