---
title: GetEnvironmentVariable()
second_title: Riferimento API di Aspose.Slides per C++
description: Restituisce il valore della variabile d'ambiente specificata associata al processo corrente.
type: docs
weight: 287
url: /it/system/environment/getenvironmentvariable/
---
## Environment::GetEnvironmentVariable(const String\&) metodo

Restituisce il valore della variabile d'ambiente specificata associata al processo corrente.

```cpp
static String System::Environment::GetEnvironmentVariable(const String &variable)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| variable | const [String](../../string/)\& | La stringa contenente il nome della variabile da recuperare |

### Valore restituito

Il valore della variabile specificata

## Environment::GetEnvironmentVariable(const String\&, EnvironmentVariableTarget) metodo

Restituisce il valore della variabile d'ambiente specificata dalla posizione specificata.

```cpp
static String System::Environment::GetEnvironmentVariable(const String &variable, EnvironmentVariableTarget target)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| variable | const [String](../../string/)\& | La stringa contenente il nome della variabile da recuperare |
| target | [EnvironmentVariableTarget](../../environmentvariabletarget/) | La posizione della variabile |

### Valore restituito

Il valore della variabile specificata

## Vedi anche

* Enum [EnvironmentVariableTarget](../../environmentvariabletarget/)
* Classe [String](../../string/)
* Struct [Environment](../)
* Namespace [System](../../)
* Libreria [Aspose.Slides](../../../)