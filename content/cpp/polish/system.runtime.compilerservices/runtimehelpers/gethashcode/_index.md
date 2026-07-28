---
title: GetHashCode()
second_title: Aspose.Slides dla C++ – odniesienie API
description: "Pobiera kod skrótu dla dowolnego typu. Wywołuje Object::GetHashCode(), aby to zrobić."
type: docs
weight: 1
url: /pl/system.runtime.compilerservices/runtimehelpers/gethashcode/
---
## RuntimeHelpers::GetHashCode(SmartPtr\<T\> const\&) metoda

Pobiera kod skrótu dla dowolnego typu. Wywołuje [Object::GetHashCode()](../../../system/object/gethashcode/) w tym celu.

```cpp
template<typename T> static int System::Runtime::CompilerServices::RuntimeHelpers::GetHashCode(SmartPtr<T> const &obj)
```

### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| T | Typ, dla którego pobierany jest kod skrótu. |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| obj | [SmartPtr](../../../system/smartptr/)\<T\> const\& | [Object](../../../system/object/) do pobrania informacji z. |

### Wartość zwracana

Wartość kodu skrótu, obliczona przez docelową implementację.

## Zobacz także

* Klasa [SmartPtr](../../../system/smartptr/)
* Klasa [RuntimeHelpers](../)
* Przestrzeń nazw [System::Runtime::CompilerServices](../../)
* Biblioteka [Aspose.Slides](../../../)