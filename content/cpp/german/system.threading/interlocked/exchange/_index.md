---
title: Exchange()
second_title: Aspose.Slides für C++ API-Referenz
description: "Wechselt den Wert einer Variablen: speichert den neuen Wert und gibt den Wert zurück, den die Variable unmittelbar vor dem Speichern hatte."
type: docs
weight: 66
url: /de/system.threading/interlocked/exchange/
---
## Interlocked::Exchange(T\&, T) Methode


Wechselt den Wert einer Variablen: speichert den neuen Wert und gibt den Wert zurück, den die Variable unmittelbar vor dem Speichern hatte.

```cpp
template<typename T> static std::enable_if<IsSupportedInt<T>, T>::type System::Threading::Interlocked::Exchange(T &location1, T value)
```


### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| T | Variablentyp. |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| location1 | T\& | Variablenreferenz zum Ändern. |
| value | T | Zu speichernder Wert. |

### Rückgabewert

Wert der Variablen unmittelbar bevor sie geändert wurde.

## Interlocked::Exchange(T\&, T) Methode


Wechselt den Wert einer Variablen: speichert den neuen Wert und gibt den Wert zurück, den die Variable unmittelbar vor dem Speichern hatte. Nicht implementiert.

```cpp
template<typename T> static std::enable_if<!IsSupportedInt<T>, T>::type System::Threading::Interlocked::Exchange(T &location1, T value)
```


### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| T | Variablentyp. |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| location1 | T\& | Variablenreferenz zum Ändern. |
| value | T | Zu speichernder Wert. |

### Rückgabewert

Wert der Variablen unmittelbar bevor sie geändert wurde.

## Siehe auch

* Klasse [Interlocked](../)
* Namensraum [System::Threading](../../)
* Bibliothek [Aspose.Slides](../../../)