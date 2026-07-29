---
title: GetHashCode()
second_title: Aspose.Slides för C++ API-referens
description: "Hämtar hash-kod för en godtycklig typ. Anropar Object::GetHashCode() för att göra detta."
type: docs
weight: 1
url: /sv/system.runtime.compilerservices/runtimehelpers/gethashcode/
---
## RuntimeHelpers::GetHashCode(SmartPtr\<T\> const\&) metod

Hämtar hash-kod för en godtycklig typ. Anropar [Object::GetHashCode()](../../../system/object/gethashcode/) för att göra detta.

```cpp
template<typename T> static int System::Runtime::CompilerServices::RuntimeHelpers::GetHashCode(SmartPtr<T> const &obj)
```

### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| T | Typ att hämta hash-kod för. |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| obj | [SmartPtr](../../../system/smartptr/)\<T\> const\& | [Object](../../../system/object/) för att hämta information från. |

### Returvärde

Hash-kodvärde beräknat av målimplementeringen.

## Se även

* Klass [SmartPtr](../../../system/smartptr/)
* Klass [RuntimeHelpers](../)
* Namnrymd [System::Runtime::CompilerServices](../../)
* Bibliotek [Aspose.Slides](../../../)