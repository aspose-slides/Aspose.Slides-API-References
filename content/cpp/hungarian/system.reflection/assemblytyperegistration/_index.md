---
title: AssemblyTypeRegistration
second_title: Aspose.Slides C++ API referenciája
description: Singleton a típus regisztrálásához a végrehajtó assembly-ben.
type: docs
weight: 27
url: /hu/system.reflection/assemblytyperegistration/
---
## AssemblyTypeRegistration osztály

Singleton a típus regisztrálásához a végrehajtó assembly-ben.

```cpp
template<typename T>class AssemblyTypeRegistration : public System::Reflection::AssemblyTypeRegistrationBase
```

### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| T | Regisztrálandó típus. |
## Metódusok

| Metódus | Leírás |
| --- | --- |
|  [AssemblyTypeRegistration](./assemblytyperegistration/)() | Létrehoz egy singleton példányt, ezáltal regisztrálja a típust a végrehajtó assembly-ben. |
|  [AssemblyTypeRegistration](./assemblytyperegistration/)(const [SharedPtr](../../system/sharedptr/)\<[Assembly](../assembly/)\>\&) | Létrehoz egy singleton példányt, ezáltal regisztrálja a típust a megadott assembly-ben. |

## Lásd még

* Osztály [AssemblyTypeRegistrationBase](../assemblytyperegistrationbase/)
* Névtér [System::Reflection](../)
* Könyvtár [Aspose.Slides](../../)