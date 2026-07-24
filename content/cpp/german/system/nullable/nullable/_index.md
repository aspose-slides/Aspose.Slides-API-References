---
title: Nullable()
second_title: Aspose.Slides für C++ API-Referenz
description: Erstellt eine Instanz, die einen Nullwert darstellt.
type: docs
weight: 1
url: /de/system/nullable/nullable/
---
## Nullable::Nullable() Konstruktor

Erstellt eine Instanz, die einen Nullwert darstellt.

```cpp
System::Nullable<T>::Nullable()
```

## Nullable::Nullable(std::nullptr_t) Konstruktor

Erstellt eine Instanz, die null darstellt.

```cpp
System::Nullable<T>::Nullable(std::nullptr_t)
```

## Nullable::Nullable(const T1\&) Konstruktor

Erstellt eine Instanz der [Nullable](../) Klasse, die den angegebenen Wert darstellt, der (falls erforderlich) in den Wert des zugrunde liegenden Typs T konvertiert wird.

```cpp
template<typename T1> System::Nullable<T>::Nullable(const T1 &value)
```

### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| T1 | Der Typ des angegebenen Werts |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | const T1\& | Eine konstante Referenz auf den Wert, der vom neu erstellten [Nullable](../) Objekt dargestellt wird |

## Nullable::Nullable(const Nullable\<T1\>\&) Konstruktor

Erstellt eine Instanz, die einen Wert darstellt, der durch das angegebene [Nullable](../) Objekt repräsentiert wird. Das angegebene nullable Objekt kann einen Wert eines anderen Typs als den zugrunde liegenden Typ der erstellten Instanz repräsentieren; in diesem Fall wird der dargestellte Wert in einen Wert des Typs T konvertiert.

```cpp
template<typename T1> System::Nullable<T>::Nullable(const Nullable<T1> &value)
```

### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| T1 | Der Typ des Werts, der durch das angegebene [Nullable](../) Objekt dargestellt wird |

## Siehe auch

* Klasse [Nullable](../)
* Namensraum [System](../../)
* Bibliothek [Aspose.Slides](../../../)