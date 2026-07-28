---
title: GetChildRows()
second_title: Aspose.Slides dla C++ – Dokumentacja API
description: Pobiera wiersze, które są uznawane za podrzędne przez określoną relację.
type: docs
weight: 27
url: /pl/system.data/datarow/getchildrows/
---
## DataRow::GetChildRows(const System::SharedPtr\<System::Data::DataRelation\>\&) metoda

Pobiera wiersze, które są uznawane za podrzędne przez określoną relację.

```cpp
System::ArrayPtr<System::SharedPtr<System::Data::DataRow>> System::Data::DataRow::GetChildRows(const System::SharedPtr<System::Data::DataRelation> &relation)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| relation | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Data::DataRelation](../../datarelation/)\>\& | Obiekt relacji określający relację wiersza nadrzędnego - wiersza podrzędnego. |

### Wartość zwracana

[Array](../../../system/array/) wierszy podrzędnych pobranych.

## Zobacz także

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasa [DataRow](../)
* Klasa [DataRelation](../../datarelation/)
* Przestrzeń nazw [System::Data](../../)
* Library [Aspose.Slides](../../../)