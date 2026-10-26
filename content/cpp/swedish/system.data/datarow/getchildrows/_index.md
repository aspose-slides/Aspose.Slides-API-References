---
title: GetChildRows()
second_title: Aspose.Slides för C++ API-referens
description: Hämtar rader som betraktas som barn genom angiven relation.
type: docs
weight: 27
url: /sv/system.data/datarow/getchildrows/
---
## DataRow::GetChildRows(const System::SharedPtr\<System::Data::DataRelation\>\&) metod

Hämtar rader som betraktas som barn genom den specificerade relationen.

```cpp
System::ArrayPtr<System::SharedPtr<System::Data::DataRow>> System::Data::DataRow::GetChildRows(const System::SharedPtr<System::Data::DataRelation> &relation)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| relation | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Data::DataRelation](../../datarelation/)\>\& | Relationsobjekt för att specificera föräldrad- och barnrad-relation. |

### Returvärde

[Array](../../../system/array/) av barnrader hämtade.

## Se även

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [DataRow](../)
* Klass [DataRelation](../../datarelation/)
* Namnrymd [System::Data](../../)
* Bibliotek [Aspose.Slides](../../../)