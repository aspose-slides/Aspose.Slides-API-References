---
title: CompareExchange()
second_title: Aspose.Slides für C++ API Referenz
description: "Vergleicht und tauscht den Wert einer Variablen aus: prüft, ob die Variable einem bestimmten Wert entspricht, und speichert den neuen Wert nur, wenn der gespeicherte Wert dem erwarteten entspricht."
type: docs
weight: 79
url: /de/system.threading/interlocked/compareexchange/
---
## Interlocked::CompareExchange(T\&, T, T) Methode


Vergleicht und tauscht den Wert einer Variablen aus: prüft, ob die Variable einem bestimmten Wert entspricht, und speichert den neuen Wert nur, wenn der gespeicherte Wert dem erwarteten entspricht.

```cpp
template<typename T> static std::enable_if<IsSupportedInt<T>, T>::type System::Threading::Interlocked::CompareExchange(T &location1, T value, T comparand)
```


### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| T | Variablentyp. |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| location1 | T\& | Referenz auf die zu ändernde Variable. |
| value | T | Zu speichernder Wert. |
| comparand | T | Wert, mit dem der aktuelle Variablenwert vor dem Austausch verglichen wird. |

### Rückgabewert

Wert der Variablen zu Beginn der Operation, unabhängig davon, ob er geändert wurde oder nicht.

## Interlocked::CompareExchange(T\&, T, T) Methode


Vergleicht und tauscht den Wert einer Variablen aus: prüft, ob die Variable einem bestimmten Wert entspricht, und speichert den neuen Wert nur, wenn der gespeicherte Wert dem erwarteten entspricht. Nicht implementiert.

```cpp
template<typename T> static std::enable_if<!IsSupportedInt<T>, T>::type System::Threading::Interlocked::CompareExchange(T &location1, T value, T comparand)
```


### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| T | Variablentyp. |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| location1 | T\& | Referenz auf die zu ändernde Variable. |
| value | T | Zu speichernder Wert. |
| comparand | T | Wert, mit dem der aktuelle Variablenwert vor dem Austausch verglichen wird. |

### Rückgabewert

Wert der Variablen zu Beginn der Operation, unabhängig davon, ob er geändert wurde oder nicht.

## Interlocked::CompareExchange(int32_t\&, int32_t, int32_t, bool\&) Methode


Vergleicht und tauscht den Wert einer Variablen aus: prüft, ob die Variable einem bestimmten Wert entspricht, und speichert den neuen Wert nur, wenn der gespeicherte Wert dem erwarteten entspricht.

```cpp
static int32_t System::Threading::Interlocked::CompareExchange(int32_t &location1, int32_t value, int32_t comparand, bool &succeeded)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| location1 | **int32_t**\& | Referenz auf die zu ändernde Variable. |
| value | **int32_t** | Zu speichernder Wert. |
| comparand | **int32_t** | Wert, mit dem der aktuelle Variablenwert vor dem Austausch verglichen wird. |
| succeeded | **bool**\& | Referenz auf eine Variable, die auf true gesetzt wird, wenn der Austausch stattgefunden hat, und sonst auf false. |

### Rückgabewert

Wert der Variablen zu Beginn der Operation, unabhängig davon, ob er geändert wurde oder nicht.

## Siehe auch

* Klasse [Interlocked](../)
* Namensraum [System::Threading](../../)
* Bibliothek [Aspose.Slides](../../../)