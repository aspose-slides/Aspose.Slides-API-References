---
title: GetEnvironmentVariable()
second_title: Aspose.Slides för C++ API-referens
description: Returnerar värdet på den angivna miljövariabeln som är kopplad till den aktuella processen.
type: docs
weight: 287
url: /sv/system/environment/getenvironmentvariable/
---
## Environment::GetEnvironmentVariable(const String\&) metod

Returnerar värdet på den angivna miljövariabeln som är associerad med den aktuella processen.

```cpp
static String System::Environment::GetEnvironmentVariable(const String &variable)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| variable | const [String](../../string/)\& | Strängen som innehåller namnet på variabeln som ska hämtas |

### Returvärde

Värdet på den angivna variabeln

## Environment::GetEnvironmentVariable(const String\&, EnvironmentVariableTarget) metod

Returnerar värdet på den angivna miljövariabeln från den angivna platsen.

```cpp
static String System::Environment::GetEnvironmentVariable(const String &variable, EnvironmentVariableTarget target)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| variable | const [String](../../string/)\& | Strängen som innehåller namnet på variabeln som ska hämtas |
| target | [EnvironmentVariableTarget](../../environmentvariabletarget/) | Platsen för variabeln |

### Returvärde

Värdet på den angivna variabeln

## Se även

* Enum [EnvironmentVariableTarget](../../environmentvariabletarget/)
* Klass [String](../../string/)
* Struktur [Environment](../)
* Namnrymd [System](../../)
* Bibliotek [Aspose.Slides](../../../)