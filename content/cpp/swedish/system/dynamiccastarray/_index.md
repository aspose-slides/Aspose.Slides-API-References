---
title: DynamicCastArray()
second_title: Aspose.Slides för C++ API-referens
description: Utför omvandling av element i den specificerade arrayen till en annan typ.
type: docs
weight: 2991
url: /sv/system/dynamiccastarray/
---
## System::DynamicCastArray(const SharedPtr\<Array\<From\>\>\&) funktion


Utför omvandling av element i den specificerade arrayen till en annan typ.

```cpp
template<class To,class From> SharedPtr<Array<To>> System::DynamicCastArray(const SharedPtr<Array<From>> &from)
```


### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| To | Typen att omvandla elementen i den specificerade arrayen till |
| From | Typen av element i arrayen vars element som ska omvandlas |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| from | const [SharedPtr](../sharedptr/)\<[Array](../array/)\<From\>\>\& | Delad pekare till arrayen som innehåller elementen som ska omvandlas |

### Returvärde

En pekare till en ny array som innehåller element av typen **To** motsvarande elementen i **from**

Föråldrad
:   Läggs till för bakåtkompatibilitet. Använd ExplicitCast istället.

## Se även

* Typedef [SharedPtr](../sharedptr/)
* Klass [Array](../array/)
* Namnrymd [System](../)
* Bibliotek [Aspose.Slides](../../)