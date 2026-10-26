---
title: setter_post_decrement_wrap()
second_title: Aspose.Slides für C++ API-Referenz
description: Der Übersetzer übersetzt C#-Postdekrementausdrücke, die auf die Eigenschaft einer Klasse abzielen, die Setter und Getter definiert hat, in einen Aufruf dieser Funktion.
type: docs
weight: 2874
url: /de/system/setter_post_decrement_wrap/
---
## System::setter_post_decrement_wrap(T(*)(), void(*)(T)) Funktion

Der Übersetzer übersetzt C#-Postdekrementausdrücke, die auf die Eigenschaft einer Klasse abzielen, die Setter und Getter definiert hat, in einen Aufruf dieser Funktion.

```cpp
template<typename T> T System::setter_post_decrement_wrap(T(*pGetter)(), void(*pSetter)(T))
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

Der Wert der Eigenschaft vor dem Inkrementieren

## System::setter_post_decrement_wrap(Host *const, T(HostGet::*)(), void(HostSet::*)(T)) Funktion

Der Übersetzer übersetzt C#-Postdekrementausdrücke, die auf die Eigenschaft einer Instanz abzielen, die Setter und Getter definiert hat, in einen Aufruf dieser Funktion (Überladung für nicht-konstanten Getter).

```cpp
template<typename T,typename Host,typename HostGet,typename HostSet> std::enable_if<std::is_base_of<HostGet, Host>::value &&std::is_base_of<HostSet, Host>::value, T>::type System::setter_post_decrement_wrap(Host *const host, T(HostGet::*pGetter)(), void(HostSet::*pSetter)(T))
```

### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| T | Der Typ der Eigenschaft. |
| Host | - Klasse der zu modifizierenden Instanz |
| HostGet | - Host selbst oder sein Basistyp, in dem der Getter der Eigenschaft definiert ist |
| HostSet | - Host selbst oder sein Basistyp, in dem der Setter der Eigenschaft definiert ist |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| host | Host *const | Instanz, für die Getter und Setter aufgerufen werden. |
| pGetter | T(HostGet::*)() | Funktionszeiger, der auf die Getter-Funktion der Eigenschaft zeigt |
| pSetter | void(HostSet::*)(T) | Funktionszeiger, der auf die Setter-Funktion der Eigenschaft zeigt |

### Rückgabewert

Der Wert der Eigenschaft vor dem Inkrementieren

## System::setter_post_decrement_wrap(Host *const, T(HostConstGet::*)() const, void(HostSet::*)(T)) Funktion

Der Übersetzer übersetzt C#-Postdekrementausdrücke, die auf die Eigenschaft einer Instanz abzielen, die Setter und Getter definiert hat, in einen Aufruf dieser Funktion (Überladung für konstanten Getter).

```cpp
template<typename T,typename Host,typename HostConstGet,typename HostSet> std::enable_if<std::is_base_of<HostConstGet, Host>::value &&std::is_base_of<HostSet, Host>::value, T>::type System::setter_post_decrement_wrap(Host *const host, T(HostConstGet::*pGetter)() const, void(HostSet::*pSetter)(T))
```

### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| T | Der Typ der Eigenschaft. |
| Host | - Klasse der zu modifizierenden Instanz |
| HostConstGet | - Host selbst oder sein Basistyp, in dem der Getter der Eigenschaft definiert ist |
| HostSet | - Host selbst oder sein Basistyp, in dem der Setter der Eigenschaft definiert ist |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| host | Host *const | Instanz, für die Getter und Setter aufgerufen werden. |
| pGetter | T(HostConstGet::*)() const | Funktionszeiger, der auf die Getter-Funktion der Eigenschaft zeigt |
| pSetter | void(HostSet::*)(T) | Funktionszeiger, der auf die Setter-Funktion der Eigenschaft zeigt |

### Rückgabewert

Der Wert der Eigenschaft vor dem Inkrementieren

## Siehe auch

* Namensraum [System](../)
* Bibliothek [Aspose.Slides](../../)