---
title: GetEnvironmentVariables()
second_title: Aspose.Slides for C++ API referencia
description: Visszaad egy szótárat, amely tartalmazza az aktuális folyamathoz kapcsolódó összes környezeti változó nevét és értékét.
type: docs
weight: 326
url: /hu/system/environment/getenvironmentvariables/
---
## Environment::GetEnvironmentVariables() metódus


Visszaad egy szótárat, amely tartalmazza az aktuális folyamathoz kapcsolódó összes környezeti változó nevét és értékét.

```cpp
static Collections::Generic::DictionaryPtr<String, String> System::Environment::GetEnvironmentVariables()
```

## Environment::GetEnvironmentVariables(EnvironmentVariableTarget) metódus


Visszaad egy szótárat, amely tartalmazza a megadott helyről származó összes környezeti változó nevét és értékét.

```cpp
static Collections::Generic::DictionaryPtr<String, String> System::Environment::GetEnvironmentVariables(EnvironmentVariableTarget target)
```


### Arguments

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| target | [EnvironmentVariableTarget](../../environmentvariabletarget/) | A változók helye |

### Visszatérési érték

Egy szótár, amely a megadott helyről származó összes környezeti változó nevét és értékét tartalmazza

## Lásd még

* Enum [EnvironmentVariableTarget](../../environmentvariabletarget/)
* Osztály [DictionaryPtr](../../../system.collections.generic/dictionaryptr/)
* Osztály [String](../../string/)
* Struct [Environment](../)
* Névtér [System](../../)
* Könyvtár [Aspose.Slides](../../../)