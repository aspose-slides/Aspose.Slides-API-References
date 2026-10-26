---
title: GetEnvironmentVariable()
second_title: Aspose.Slides pro C++ – reference API
description: Vrací hodnotu zadané proměnné prostředí spojené s aktuálním procesem.
type: docs
weight: 287
url: /cs/system/environment/getenvironmentvariable/
---
## Environment::GetEnvironmentVariable(const String\&) metoda

Vrací hodnotu určené proměnné prostředí spojené s aktuálním procesem.

```cpp
static String System::Environment::GetEnvironmentVariable(const String &variable)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| variable | const [String](../../string/)\& | Řetězec obsahující název proměnné, kterou je třeba získat |

### Návratová hodnota

Hodnota určené proměnné

## Environment::GetEnvironmentVariable(const String\&, EnvironmentVariableTarget) metoda

Vrací hodnotu určené proměnné prostředí ze specifikovaného umístění.

```cpp
static String System::Environment::GetEnvironmentVariable(const String &variable, EnvironmentVariableTarget target)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| variable | const [String](../../string/)\& | Řetězec obsahující název proměnné, kterou je třeba získat |
| target | [EnvironmentVariableTarget](../../environmentvariabletarget/) | Umístění proměnné |

### Návratová hodnota

Hodnota určené proměnné

## Viz také

* Výčet [EnvironmentVariableTarget](../../environmentvariabletarget/)
* Třída [String](../../string/)
* Struktura [Environment](../)
* Jmenný prostor [System](../../)
* Knihovna [Aspose.Slides](../../../)