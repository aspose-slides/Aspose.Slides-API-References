---
title: GetEnvironmentVariable()
second_title: Aspose.Slides C++ API referencia
description: Visszaadja a megadott környezeti változó értékét, amely a jelenlegi folyamathoz kapcsolódik.
type: docs
weight: 287
url: /hu/system/environment/getenvironmentvariable/
---
## Environment::GetEnvironmentVariable(const String\&) metódus


Visszaadja a megadott környezeti változó értékét, amely a jelenlegi folyamathoz kapcsolódik.

```cpp
static String System::Environment::GetEnvironmentVariable(const String &variable)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| variable | const [String](../../string/)\& | A karakterlánc, amely a lekérdezni kívánt változó nevét tartalmazza |

### Visszatérési érték

A megadott változó értéke

## Environment::GetEnvironmentVariable(const String\&, EnvironmentVariableTarget) metódus


Visszaadja a megadott környezeti változó értékét a megadott helyről.

```cpp
static String System::Environment::GetEnvironmentVariable(const String &variable, EnvironmentVariableTarget target)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| variable | const [String](../../string/)\& | A karakterlánc, amely a lekérdezni kívánt változó nevét tartalmazza |
| target | [EnvironmentVariableTarget](../../environmentvariabletarget/) | A változó helye |

### Visszatérési érték

A megadott változó értéke

## Lásd még

* Enum [EnvironmentVariableTarget](../../environmentvariabletarget/)
* Osztály [String](../../string/)
* Struktúra [Environment](../)
* Névtér [System](../../)
* Könyvtár [Aspose.Slides](../../../)