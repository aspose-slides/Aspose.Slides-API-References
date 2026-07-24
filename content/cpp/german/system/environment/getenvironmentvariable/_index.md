---
title: GetEnvironmentVariable()
second_title: Aspose.Slides für C++ API-Referenz
description: Gibt den Wert der angegebenen Umgebungsvariable zurück, die dem aktuellen Prozess zugeordnet ist.
type: docs
weight: 287
url: /de/system/environment/getenvironmentvariable/
---
## Environment::GetEnvironmentVariable(const String\&) Methode

Gibt den Wert der angegebenen Umgebungsvariable zurück, die dem aktuellen Prozess zugeordnet ist.

```cpp
static String System::Environment::GetEnvironmentVariable(const String &variable)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| variable | const [String](../../string/)\& | Die Zeichenkette, die den Namen der abzurufenden Variable enthält |

### Rückgabewert

Der Wert der angegebenen Variable

## Environment::GetEnvironmentVariable(const String\&, EnvironmentVariableTarget) Methode

Gibt den Wert der angegebenen Umgebungsvariable aus dem angegebenen Speicherort zurück.

```cpp
static String System::Environment::GetEnvironmentVariable(const String &variable, EnvironmentVariableTarget target)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| variable | const [String](../../string/)\& | Die Zeichenkette, die den Namen der abzurufenden Variable enthält |
| target | [EnvironmentVariableTarget](../../environmentvariabletarget/) | Der Speicherort der Variable |

### Rückgabewert

Der Wert der angegebenen Variable

## Siehe auch

* Aufzählung [EnvironmentVariableTarget](../../environmentvariabletarget/)
* Klasse [String](../../string/)
* Struktur [Environment](../)
* Namensraum [System](../../)
* Bibliothek [Aspose.Slides](../../../)