---
title: setter_post_increment_wrap()
second_title: Aspose.Slides für C++ API-Referenz
description: Der Übersetzer übersetzt C#-Postinkrementausdrücke, die sich auf die Eigenschaft einer Klasse beziehen, für die Setter und Getter definiert sind, in einen Aufruf dieser Funktion.
type: docs
weight: 2848
url: /de/system/setter_post_increment_wrap/
---
## System::setter_post_increment_wrap(T(*)(), void(*)(T)) Funktion

Der Übersetzer übersetzt C#-Postinkrementausdrücke, die sich auf die Eigenschaft einer Klasse beziehen, für die setter und getter definiert sind, in einen Aufruf dieser Funktion.

```cpp
template<typename T> T System::setter_post_increment_wrap(T(*pGetter)(), void(*pSetter)(T))
```

### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| T | Der Typ der Eigenschaft |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| pGetter | T(*)() | Funktionszeiger, der auf die freie getter-Funktion der Eigenschaft zeigt |
| pSetter | void(*)(T) | Funktionszeiger, der auf die freie setter-Funktion der Eigenschaft zeigt |

### Rückgabewert

Der Wert der Eigenschaft vor dem Inkrementieren

## System::setter_post_increment_wrap(Host *const, T(HostGet::*)(), void(HostSet::*)(T)) Funktion

Der Übersetzer übersetzt C#-Postinkrementausdrücke, die sich auf die Instanz-Eigenschaft beziehen, für die setter und getter definiert sind, in einen Aufruf dieser Funktion (Überladung für nicht-konstante getter).

```cpp
template<typename T,typename Host,typename HostGet,typename HostSet> std::enable_if<std::is_base_of<HostGet, Host>::value &&std::is_base_of<HostSet, Host>::value, T>::type System::setter_post_increment_wrap(Host *const host, T(HostGet::*pGetter)(), void(HostSet::*pSetter)(T))
```

### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| T | Der Typ der Eigenschaft. |
| Host | - Klasse der zu ändernden Instanz |
| HostGet | - Host selbst oder dessen Basistyp, in dem der getter der Eigenschaft definiert ist |
| HostSet | - Host selbst oder dessen Basistyp, in dem der setter der Eigenschaft definiert ist |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| host | Host *const | Instanz, für die getter und setter aufgerufen werden. |
| pGetter | T(HostGet::*)() | Funktionszeiger, der auf die getter-Funktion der Eigenschaft zeigt |
| pSetter | void(HostSet::*)(T) | Funktionszeiger, der auf die setter-Funktion der Eigenschaft zeigt |

### Rückgabewert

Der Wert der Eigenschaft vor dem Inkrementieren

## System::setter_post_increment_wrap(Host *const, T(HostConstGet::*)() const, void(HostSet::*)(T)) Funktion

Der Übersetzer übersetzt C#-Postinkrementausdrücke, die sich auf die Instanz-Eigenschaft beziehen, für die setter und getter definiert sind, in einen Aufruf dieser Funktion (Überladung für konstante getter).

```cpp
template<typename T,typename Host,typename HostConstGet,typename HostSet> std::enable_if<std::is_base_of<HostConstGet, Host>::value &&std::is_base_of<HostSet, Host>::value, T>::type System::setter_post_increment_wrap(Host *const host, T(HostConstGet::*pGetter)() const, void(HostSet::*pSetter)(T))
```

### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| T | Der Typ der Eigenschaft. |
| Host | - Klasse der zu ändernden Instanz |
| HostConstGet | - Host selbst oder dessen Basistyp, in dem der getter der Eigenschaft definiert ist |
| HostSet | - Host selbst oder dessen Basistyp, in dem der setter der Eigenschaft definiert ist |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| host | Host *const | Instanz, für die getter und setter aufgerufen werden. |
| pGetter | T(HostConstGet::*)() const | Funktionszeiger, der auf die getter-Funktion der Eigenschaft zeigt |
| pSetter | void(HostSet::*)(T) | Funktionszeiger, der auf die setter-Funktion der Eigenschaft zeigt |

### Rückgabewert

Der Wert der Eigenschaft vor dem Inkrementieren

## Siehe Auch

* Namensraum [System](../)
* Bibliothek [Aspose.Slides](../../)