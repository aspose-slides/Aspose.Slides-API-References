---
title: GetHashCode()
second_title: Aspose.Slides for C++ API Referencia
description: "Hash kódot kér le tetszőleges típusra. Ehhez az Object::GetHashCode() metódust hívja."
type: docs
weight: 1
url: /hu/system.runtime.compilerservices/runtimehelpers/gethashcode/
---
## RuntimeHelpers::GetHashCode(SmartPtr\<T\> const\&) metódus

A tetszőleges típusra lekér egy hash kódot. A [Object::GetHashCode()](../../../system/object/gethashcode/) metódust hívja meg ennek érdekében.

```cpp
template<typename T> static int System::Runtime::CompilerServices::RuntimeHelpers::GetHashCode(SmartPtr<T> const &obj)
```

### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| T | A hash kód lekérésére szolgáló típus. |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| obj | [SmartPtr](../../../system/smartptr/)\<T\> const\& | [Object](../../../system/object/) ahhoz, hogy információt kapjunk belőle. |

### Visszatérési érték

Hashkód érték, ahogy a cél implementáció számolja.

## Lásd még

* Osztály [SmartPtr](../../../system/smartptr/)
* Osztály [RuntimeHelpers](../)
* Névtér [System::Runtime::CompilerServices](../../)
* Könyvtár [Aspose.Slides](../../../)