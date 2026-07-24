---
title: operator=()
second_title: Aspose.Slides für C++ API-Referenz
description: 
type: docs
weight: 92
url: /de/system/valuetuple/operator_equal/
---
## ValueTuple::operator=(const ValueTuple\<OtherArgs...\>\&) Methode

```cpp
template<typename ...> ValueTuple & System::ValueTuple<Args>::operator=(const ValueTuple<OtherArgs...> &otherTuple)
```

## ValueTuple::operator=(const SharedPtr\<T\>\&) Methode

Dekonstruiert das Objekt zu diesem ValueTuple.

```cpp
template<typename T> ValueTuple & System::ValueTuple<Args>::operator=(const SharedPtr<T> &deconstructiblePtr)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| deconstructiblePtr | const [SharedPtr](../../sharedptr/)\<T\>\& | Ein Objekt zum Dekonstruieren |

## Siehe auch

* Typedef [SharedPtr](../../sharedptr/)
* Klasse [ValueTuple](../)
* Namensraum [System](../../)
* Bibliothek [Aspose.Slides](../../../)