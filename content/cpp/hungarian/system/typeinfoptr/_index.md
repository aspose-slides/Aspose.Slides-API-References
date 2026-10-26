---
title: TypeInfoPtr
second_title: Aspose.Slides C++ API referencia
description: "A TypeInfo osztály példányára mutató pointer burkolója. Ezt a típust a veremben kell lefoglalni, és értékkel vagy referenciával kell átadni a függvényeknek. Soha ne használja a System::SmartPtr osztályt ennek a típusnak az objektumainak kezelésére."
type: docs
weight: 1951
url: /hu/system/typeinfoptr/
---
## TypeInfoPtr struct

A [TypeInfo](../typeinfo/) osztály példányára mutató pointer burkolója. Ezt a típust a veremben kell lefoglalni, és értékkel vagy referenciával kell átadni a függvényeknek. Soha ne használja a [System::SmartPtr](../smartptr/) osztályt ennek a típusnak az objektumainak kezelésére.

```cpp
class TypeInfoPtr
```

## Metódusok

| Metódus | Leírás |
| --- | --- |
|  [operator TypeInfo *](./operator_typeinfo__star/)() | Visszaad egy nyers mutatót a képviselt [TypeInfo](../typeinfo/) objektumra. |
|  [TypeInfoPtr](./typeinfoptr/)() | Alapértelmezett konstruktor. |
|  [TypeInfoPtr](./typeinfoptr/)(const std::type_info\&) | Konstruktor. |
|  [TypeInfoPtr](./typeinfoptr/)(const char_t *, **uint32_t**) | Konstruktor. |
|  [TypeInfoPtr](./typeinfoptr/)(const char_t *) | Konstruktor. |
|  [TypeInfoPtr](./typeinfoptr/)(const [String](../string/)\&) | Konstruktor. |
|  [~TypeInfoPtr](./~typeinfoptr/)() | Destruktor. |

## Lásd még

* Névtér [System](../)
* Könyvtár [Aspose.Slides](../../)