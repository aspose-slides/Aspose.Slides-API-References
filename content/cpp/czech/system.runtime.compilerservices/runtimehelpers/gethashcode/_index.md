---
title: GetHashCode()
second_title: Aspose.Slides pro C++ API Reference
description: "Získá hash kód pro libovolný typ. K tomu zavolá Object::GetHashCode()."
type: docs
weight: 1
url: /cs/system.runtime.compilerservices/runtimehelpers/gethashcode/
---
## RuntimeHelpers::GetHashCode(SmartPtr\<T\> const\&) metoda

Získá hash kód pro libovolný typ. Zavolá [Object::GetHashCode()](../../../system/object/gethashcode/) k tomu.

```cpp
template<typename T> static int System::Runtime::CompilerServices::RuntimeHelpers::GetHashCode(SmartPtr<T> const &obj)
```

### Parametry šablony

| Parametr | Popis |
| --- | --- |
| T | Typ, pro který se získá hash kód. |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| obj | [SmartPtr](../../../system/smartptr/)\<T\> const\& | [Object](../../../system/object/) k získání informací z. |

### Návratová hodnota

Hodnota hash kódu, jak je vypočítána cílovou implementací.

## Viz také

* Třída [SmartPtr](../../../system/smartptr/)
* Třída [RuntimeHelpers](../)
* Jmenný prostor [System::Runtime::CompilerServices](../../)
* Knihovna [Aspose.Slides](../../../)