---
title: setter_wrap()
second_title: Aspose.Slides für C++ API Referenz
description: Überladung für statische Setter-Funktionen mit Typumwandlung.
type: docs
weight: 2822
url: /de/system/setter_wrap/
---
## System::setter_wrap(void(*)(T2), T) Funktion

Überladung für statische Setter-Funktionen mit Typumwandlung.

```cpp
template<typename T,typename T2> T System::setter_wrap(void(*pSetter)(T2), T value)
```

### Vorlagenparameter

| Parameter | Beschreibung |
| --- | --- |
| T | Wertetyp. |
| T2 | Vom Setter erwarteter Typ. |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| pSetter | void(*)(T2) | Referenz auf statische Setter-Funktion. |
| value | T | Wert, der gesetzt werden soll. |

### Rückgabewert

setzt den Wert.

## System::setter_wrap(Host *const, void(HostSet::*)(T2), T) Funktion

Überladung für Instanz-Setter-Funktionen mit Typumwandlung.

```cpp
template<typename T,typename T2,typename Host,typename HostSet> std::enable_if<std::is_base_of<HostSet, Host>::value, T>::type System::setter_wrap(Host *const host, void(HostSet::*pSetter)(T2), T value)
```

### Vorlagenparameter

| Parameter | Beschreibung |
| --- | --- |
| T | Wertetyp. |
| T2 | Vom Setter erwarteter Typ. |
| Host | Instanztyp. |
| HostSet | - Host selbst oder dessen Basistyp, in dem der Setter der Eigenschaft definiert ist. |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| host | Host *const | [Object](../object/) zum Aufrufen der Setter-Funktion für. |
| pSetter | void(HostSet::*)(T2) | Referenz auf die Setter-Funktion. |
| value | T | Wert, der gesetzt werden soll. |

### Rückgabewert

setzt den Wert.

## Siehe auch

* Namensraum [System](../)
* Bibliothek [Aspose.Slides](../../)