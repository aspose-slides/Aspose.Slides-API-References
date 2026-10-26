---
title: Equals()
second_title: Aspose.Slides für C++ API-Referenz
description: Vergleicht Objekte unter Verwendung der C# Object.Equals-Semantik.
type: docs
weight: 157
url: /de/system/object/equals/
---
## Object::Equals(ptr) Methode

Vergleicht Objekte unter Verwendung der C# [Object.Equals](./) Semantik.

```cpp
virtual bool System::Object::Equals(ptr obj)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| obj | [ptr](../ptr/) | [Object](../) um das aktuelle zu vergleichen. |

### Rückgabewert

True, wenn Objekte als gleich betrachtet werden, sonst false.

## Object::Equals(T1 const\&, T2 const\&) Methode

Vergleicht Referenztyp-Objekte im C#-Stil.

```cpp
template<typename T1,typename T2> static std::enable_if<IsSmartPtr<T1>::value &&IsSmartPtr<T2>::value, bool>::type System::Object::Equals(T1 const &objA, T2 const &objB)
```

### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| T1 | Typ des ersten zu vergleichenden Objekts. |
| T2 | Typ des zweiten zu vergleichenden Objekts. |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| objA | T1 const\& | Erstes zu vergleichendes Objekt. |
| objB | T2 const\& | Zweites zu vergleichendes Objekt. |

### Rückgabewert

True, wenn Objekte entweder per Referenz oder semantisch (durch einen [Object.Equals](./)-ähnlichen Vergleich) übereinstimmen, sonst false.

## Object::Equals(T1 const\&, T2 const\&) Methode

Vergleicht Werttyp-Objekte im C#-Stil.

```cpp
template<typename T1,typename T2> static std::enable_if<!IsSmartPtr<T1>::value &&!IsSmartPtr<T2>::value, bool>::type System::Object::Equals(T1 const &objA, T2 const &objB)
```

### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| T1 | Typ des ersten zu vergleichenden Objekts. |
| T2 | Typ des zweiten zu vergleichenden Objekts. |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| objA | T1 const\& | Erstes zu vergleichendes Objekt. |
| objB | T2 const\& | Zweites zu vergleichendes Objekt. |

### Rückgabewert

True, wenn Objekte als gleich betrachtet werden, weil der Gleichheitsoperator verfügbar ist, sonst false.

## Object::Equals(float const\&, float const\&) Methode

Emuliert den C#-artigen Gleitkommavergleich, bei dem zwei NaNs als gleich betrachtet werden, obwohl nach IEC 60559:1989 NaN zu keinem Wert, einschließlich NaN, gleich ist.

```cpp
bool System::Object::Equals(float const &objA, float const &objB)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| objA | **float** const\& | Linker Gleitkommawert. |
| objB | **float** const\& | Rechter Gleitkommawert. |

### Rückgabewert

True, wenn **objA** und **objB** beide NaN sind oder gleich sind, sonst false.

## Object::Equals(double const\&, double const\&) Methode

Emuliert den C#-artigen Gleitkommavergleich, bei dem zwei NaNs als gleich betrachtet werden, obwohl nach IEC 60559:1989 NaN zu keinem Wert, einschließlich NaN, gleich ist.

```cpp
bool System::Object::Equals(double const &objA, double const &objB)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| objA | **double** const\& | Linker Gleitkommawert. |
| objB | **double** const\& | Rechter Gleitkommawert. |

### Rückgabewert

True, wenn **objA** und **objB** beide NaN sind oder gleich sind, sonst false.

## Siehe auch

* Typedef [ptr](../ptr/)
* Class [Object](../)
* Struct [IsSmartPtr](../../issmartptr/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)