---
title: Unbox()
second_title: Aspose.Slides für C++ API-Referenz
description: Entpackt Werttypen nach der Konvertierung zu Object. Implementierung für Enum-Typen.
type: docs
weight: 53
url: /de/system/objectext/unbox/
---
## ObjectExt::Unbox(const SmartPtr\<Object\>\&) Methode

Entpackt Werttypen nach der Konvertierung zu [Object](../../object/). Implementierung für Enum-Typen.

```cpp
template<typename T> static std::enable_if<std::is_enum<T>::value, T>::type System::ObjectExt::Unbox(const SmartPtr<Object> &obj)
```

### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| T | [Enum](../../enum/) Typ. |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| obj | const [SmartPtr](../../smartptr/)\<[Object](../../object/)\>\& | [Object](../../object/) zum Entpacken. |

### Rückgabewert

[Enum](../../enum/) Wert.

## ObjectExt::Unbox(const SmartPtr\<Object\>\&) Methode

Entpackt Werttypen nach der Konvertierung zu [Object](../../object/). Implementierung für nicht-Enum & nicht-nullbare Typen.

```cpp
template<class T> static std::enable_if<!std::is_enum<T>::value &&detail::has_operator_equal<T>::value, T>::type System::ObjectExt::Unbox(const SmartPtr<Object> &obj)
```

### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| T | Werttyp. |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| obj | const [SmartPtr](../../smartptr/)\<[Object](../../object/)\>\& | [Object](../../object/) zum Entpacken. |

### Rückgabewert

Entpackter Wert.

## ObjectExt::Unbox(const SmartPtr\<Object\>\&) Methode

Entpackt Werttypen nach der Konvertierung zu [Object](../../object/). Implementierung für nicht-Enum & nicht-nullbare Typen.

```cpp
template<class T> static std::enable_if<!std::is_enum<T>::value &&!detail::has_operator_equal<T>::value, T>::type System::ObjectExt::Unbox(const SmartPtr<Object> &obj)
```

### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| T | Werttyp. |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| obj | const [SmartPtr](../../smartptr/)\<[Object](../../object/)\>\& | [Object](../../object/) zum Entpacken. |

### Rückgabewert

Entpackter Wert.

## ObjectExt::Unbox(E) Methode

Entpackt Enum-Typen zu Ganzzahl.

```cpp
template<class T,class E> static std::enable_if<std::is_enum<E>::value &&std::numeric_limits<T>::is_integer, T>::type System::ObjectExt::Unbox(E e)
```

### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| T | Ziel-Ganzzahltyp. |
| E | Quell-Enum-Typ. |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| e | E | Wert zum Entpacken. |

### Rückgabewert

Ganzzahldarstellung des Enums.

## ObjectExt::Unbox(E) Methode

Konvertiert Enum-Typen.

```cpp
template<class T,class E> static std::enable_if<std::is_enum<E>::value &&std::is_enum<T>::value, T>::type System::ObjectExt::Unbox(E e)
```

### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| T | Ziel-Enum-Typ. |
| E | Quell-Enum-Typ. |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| e | E | Wert zum Entpacken. |

### Rückgabewert

Konvertierter Enum-Wert.

## ObjectExt::Unbox(const SmartPtr\<Object\>\&) Methode

Entpackt Zeichenkettenwerte.

```cpp
String System::ObjectExt::Unbox(const SmartPtr<Object> &obj)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| obj | const [SmartPtr](../../smartptr/)\<[Object](../../object/)\>\& | [Object](../../object/) zum Entpacken |

### Rückgabewert

[String](../../string/) Darstellung der verpackten Zeichenkette, kann null sein, wenn die verpackte Zeichenkette null war.

## Siehe auch

* Klasse [SmartPtr](../../smartptr/)
* Klasse [Object](../../object/)
* Klasse [ObjectExt](../)
* Klasse [String](../../string/)
* Namensraum [System](../../)
* Bibliothek [Aspose.Slides](../../../)