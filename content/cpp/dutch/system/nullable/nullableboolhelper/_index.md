---
title: NullableBoolHelper()
second_title: Aspose.Slides voor C++ API-referentie
description: Helperfunctie om te controleren of this en other beide geen nulls zijn en een lambda aan te roepen indien dat het geval is. Wordt gebruikt in implementaties.
type: docs
weight: 105
url: /nl/system/nullable/nullableboolhelper/
---
## Nullable::NullableBoolHelper(const T1\&, const std::function\<bool()>\&, bool) const method


Helperfunctie om te controleren of dit en **other** beide geen null zijn en een lambda aan te roepen indien dat het geval is. Wordt gebruikt in implementaties.

```cpp
template<typename T1> bool System::Nullable<T>::NullableBoolHelper(const T1 &other, const std::function<bool()> &f, bool default_if_both_are_null=false) const
```


### Sjabloonparameters

| Parameter | Description |
| --- | --- |
| T1 | Ander nullable type. |

### Argumenten

| Parameter | Type | Description |
| --- | --- | --- |
| other | const T1\& | Andere nullable waarde om mee te vergelijken. |
| f | const std::function\<**bool**()>\& | Lambda die wordt aangeroepen als zowel **this** als **other** geen null zijn. |
| default_if_both_are_null | **bool** | Retourwaarde als beide waarden null zijn. |

### Retourwaarde

false als **this** of **other** null is; **default_if_both_are_null** als beide null zijn; resultaat van **f**-aanroep als beide niet null zijn.

## Zie ook

* Class [Nullable](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)