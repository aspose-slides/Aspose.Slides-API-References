---
title: setter_increment_wrap()
second_title: Aspose.Slides für C++ API-Referenz
description: Der Übersetzer wandelt C#-Inkrementausdrücke, die auf die Eigenschaft einer Klasse mit definierten Setter und Getter abzielen, in einen Aufruf dieser Funktion um.
type: docs
weight: 2835
url: /de/system/setter_increment_wrap/
---
## System::setter_increment_wrap(T(*)(), void(*)(T)) Funktion

Der Übersetzer wandelt C#-Inkrementausdrücke, die auf die Eigenschaft einer Klasse mit definierten Setter und Getter abzielen, in einen Aufruf dieser Funktion um.

```cpp
template<typename T> T System::setter_increment_wrap(T(*pGetter)(), void(*pSetter)(T))
```

### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| T | Der Typ der Eigenschaft |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| pGetter | T(*)() | Funktionszeiger, der auf die freie Getter-Funktion der Eigenschaft zeigt |
| pSetter | void(*)(T) | Funktionszeiger, der auf die freie Setter-Funktion der Eigenschaft zeigt |

### Rückgabewert

Der inkrementierte Wert der Eigenschaft

## System::setter_increment_wrap(Host *const, T(HostGet::*)(), void(HostSet::*)(T)) Funktion

Der Übersetzer wandelt C#-Inkrementausdrücke, die auf die Eigenschaft einer Klasse mit definierten Setter und Getter abzielen, in einen Aufruf dieser Funktion um.

```cpp
template<typename T,typename Host,typename HostGet,typename HostSet> std::enable_if<std::is_base_of<HostGet, Host>::value &&std::is_base_of<HostSet, Host>::value, T>::type System::setter_increment_wrap(Host *const host, T(HostGet::*pGetter)(), void(HostSet::*pSetter)(T))
```

### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| T | Der Typ der Eigenschaft |
| Host | – Klasse der zu ändernden Instanz |
| HostGet | – Host selbst oder dessen Basistyp, in dem der Getter der Eigenschaft definiert ist |
| HostSet | – Host selbst oder dessen Basistyp, in dem der Setter der Eigenschaft definiert ist |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| host | Host *const | Zeiger auf das Objekt, dessen Eigenschaft inkrementiert werden soll |
| pGetter | T(HostGet::*)() | Funktionszeiger, der auf die Getter-Methode der Eigenschaft zeigt |
| pSetter | void(HostSet::*)(T) | Funktionszeiger, der auf die Setter-Methode der Eigenschaft zeigt |

### Rückgabewert

Der inkrementierte Wert der Eigenschaft

## Siehe auch

* Namespace [System](../)
* Library [Aspose.Slides](../../)