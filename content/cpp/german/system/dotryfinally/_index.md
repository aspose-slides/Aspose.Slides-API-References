---
title: DoTryFinally()
second_title: Aspose.Slides für C++ API-Referenz
description: Die einzelne Funktion, die das Verhalten der try[-catch]-finally-Anweisung von C# nachahmt. Während der Übersetzung der try[-catch]-finally-Anweisung von C# mit der Übersetzer-Option finally_statement_as_lambda, die auf true gesetzt ist, wird die Anweisung in den Aufruf dieser Methode übersetzt.
type: docs
weight: 2445
url: /de/system/dotryfinally/
---
## System::DoTryFinally(T\&&, F\&&) Funktion

Die einzelne Funktion, die das Verhalten der try[-catch]-finally-Anweisung von C# nachahmt. Während der Übersetzung der try[-catch]-finally-Anweisung von C# mit der Übersetzer-Option finally_statement_as_lambda, die auf true gesetzt ist, wird die Anweisung in den Aufruf dieser Methode übersetzt.

```cpp
template<typename T,typename F> std::enable_if_t<Details::is_lambda_void_void<T>::value> System::DoTryFinally(T &&tryBlock, F &&finallyBlock)
```

### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| T | Der Typ des Funktionsobjekts, das den try[-catch]-Teil der try[-catch]-finally-Anweisung implementiert, die emuliert wird |
| F | Der Typ des Funktionsobjekts, das den finally-Teil der try[-catch]-finally-Anweisung implementiert, die emuliert wird |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| tryBlock | T\&& | Das Funktionsobjekt, dessen Körper die Implementierung des try[-catch]-Teils der try[-catch]-finally-Anweisung enthält, die emuliert wird |
| finallyBlock | F\&& | Das Funktionsobjekt, dessen Körper die Implementierung des finally-Teils der try[-catch]-finally-Anweisung enthält, die emuliert wird |

## System::DoTryFinally(T\&&, F\&&) Funktion

Die einzelne Funktion, die das Verhalten der try[-catch]-finally-Anweisung von C# nachahmt. Während der Übersetzung der try[-catch]-finally-Anweisung von C# mit der Übersetzer-Option finally_statement_as_lambda, die auf true gesetzt ist, wird die Anweisung in den Aufruf dieser Methode übersetzt. Diese Überladung behandelt den Fall, dass der Rückgabewert des Funktionsobjekts, das den try[-catch]-Teil der try[-catch]-finally-Anweisung implementiert, ein bool ist.

```cpp
template<typename T,typename F> std::enable_if_t<Details::is_lambda_void_boolref<T>::value, bool> System::DoTryFinally(T &&tryBlock, F &&finallyBlock)
```

### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| T | Der Typ des Funktionsobjekts, das den try[-catch]-Teil der try[-catch]-finally-Anweisung implementiert, die emuliert wird |
| F | Der Typ des Funktionsobjekts, das den finally-Teil der try[-catch]-finally-Anweisung implementiert, die emuliert wird |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| tryBlock | T\&& | Das Funktionsobjekt, dessen Körper die Implementierung des try[-catch]-Teils der try[-catch]-finally-Anweisung enthält, die emuliert wird |
| finallyBlock | F\&& | Das Funktionsobjekt, dessen Körper die Implementierung des finally-Teils der try[-catch]-finally-Anweisung enthält, die emuliert wird |

## System::DoTryFinally(T\&&, F\&&) Funktion

Die einzelne Funktion, die das Verhalten der try[-catch]-finally-Anweisung von C# nachahmt. Während der Übersetzung der try[-catch]-finally-Anweisung von C# mit der Übersetzer-Option finally_statement_as_lambda, die auf true gesetzt ist, wird die Anweisung in den Aufruf dieser Methode übersetzt. Diese Überladung behandelt den Fall, dass der Rückgabewert des Funktionsobjekts, das den try[-catch]-Teil der try[-catch]-finally-Anweisung implementiert, ein bool& ist.

```cpp
template<typename T,typename F> std::enable_if_t<Details::is_lambda_nonovoid_boolref<T>::value, std::optional<Details::ResultOf<T, bool &>>> System::DoTryFinally(T &&tryBlock, F &&finallyBlock)
```

### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| T | Der Typ des Funktionsobjekts, das den try[-catch]-Teil der try[-catch]-finally-Anweisung implementiert, die emuliert wird |
| F | Der Typ des Funktionsobjekts, das den finally-Teil der try[-catch]-finally-Anweisung implementiert, die emuliert wird |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| tryBlock | T\&& | Das Funktionsobjekt, dessen Körper die Implementierung des try[-catch]-Teils der try[-catch]-finally-Anweisung enthält, die emuliert wird |
| finallyBlock | F\&& | Das Funktionsobjekt, dessen Körper die Implementierung des finally-Teils der try[-catch]-finally-Anweisung enthält, die emuliert wird |

## Siehe auch

* Namensraum [System](../)
* Bibliothek [Aspose.Slides](../../)