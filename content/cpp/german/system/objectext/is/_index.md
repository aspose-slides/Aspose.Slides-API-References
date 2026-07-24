---
title: Is()
second_title: Aspose.Slides für C++ API-Referenz
description: Implementiert die Übersetzung des 'is'-Operators. Spezialisierung für boxbare (Wert-)Typen, die genau das sind, was sie sind.
type: docs
weight: 92
url: /de/system/objectext/is/
---
## ObjectExt::Is(const T&) Methode

Implementiert die Übersetzung des 'is'-Operators. Spezialisierung für boxbare (Wert-)Typen, die genau das sind.

```cpp
template<class T> static std::enable_if<System::IsBoxable<T>::value, bool>::type System::ObjectExt::Is(const T &obj)
```

### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| T | Zieltyp. |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| obj | const T\& | [Object](../../object/) zum Testen des 'is'-Operators. Ignoriert. |

### Rückgabewert

Immer true

## ObjectExt::Is(const U&) Methode

Implementiert die Übersetzung des 'is'-Operators. Spezialisierung für Zeigertypen, optimiert für 'final'-Klassen.

```cpp
template<class T,class U> static std::enable_if<std::is_convertible<T, Object>::value &&std::is_final<T>::value &&!System::IsBoxable<T>::value &&System::IsSmartPtr<U>::value, bool>::type System::ObjectExt::Is(const U &obj)
```

### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| T | Zieltyp. |
| U | Getesteter Typ. |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| obj | const U\& | [Object](../../object/) zum Testen des 'is'-Operators. |

### Rückgabewert

True, wenn 'is' true zurückgibt, sonst false.

## ObjectExt::Is(const U&) Methode

Implementiert die Übersetzung des 'is'-Operators. Spezialisierung für Zeigertypen.

```cpp
template<class T,class U> static std::enable_if<std::is_convertible<T, Object>::value &&!std::is_final<T>::value &&!System::IsBoxable<T>::value &&System::IsSmartPtr<U>::value, bool>::type System::ObjectExt::Is(const U &obj)
```

### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| T | Zieltyp. |
| U | Getesteter Typ. |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| obj | const U\& | [Object](../../object/) zum Testen des 'is'-Operators. |

### Rückgabewert

True, wenn 'is' true zurückgibt, sonst false.

## ObjectExt::Is(const Object&) Methode

Implementiert die Übersetzung des 'is'-Operators. Spezialisierung für Werttypen.

```cpp
template<class T> static std::enable_if<std::is_convertible<T, Object>::value, bool>::type System::ObjectExt::Is(const Object &obj)
```

### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| T | Zieltyp. |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| obj | const [Object](../../object/)\& | [Object](../../object/) zum Testen des 'is'-Operators. |

### Rückgabewert

True, wenn 'is' true zurückgibt, sonst false.

## ObjectExt::Is(const Object&) Methode

Implementiert die Übersetzung des 'is'-Operators. Spezialisierung für nicht konvertierbare Typen.

```cpp
template<class T> static std::enable_if<!std::is_convertible<T, Object>::value, bool>::type System::ObjectExt::Is(const Object &obj)
```

### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| T | Zieltyp. |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| obj | const [Object](../../object/)\& | [Object](../../object/) zum Testen des 'is'-Operators. |

### Rückgabewert

Gibt immer false zurück, da Typen nicht konvertierbar sind.

## ObjectExt::Is(const SmartPtr\<U\>\&) Methode

Implementiert die Übersetzung des 'is'-Operators. Spezialisierung für Zeigertypen.

```cpp
template<class T,class U> static std::enable_if<IsSmartPtr<T>::value, bool>::type System::ObjectExt::Is(const SmartPtr<U> &obj)
```

### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| T | Zieltyp. |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| obj | const [SmartPtr](../../smartptr/)\<U\>\& | [Object](../../object/) zum Testen des 'is'-Operators. |

### Rückgabewert

True, wenn 'is' true zurückgibt, sonst false.

## ObjectExt::Is(const ExceptionWrapper\<U\>\&) Methode

Implementiert die Übersetzung des 'is'-Operators. Spezialisierung für Ausnahme-Wrapper-Typen.

```cpp
template<class T,class U> static std::enable_if<IsExceptionWrapper<T>::value, bool>::type System::ObjectExt::Is(const ExceptionWrapper<U> &obj)
```

### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| T | Zieltyp. |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| obj | const [ExceptionWrapper](../../exceptionwrapper/)\<U\>\& | [Object](../../object/) zum Testen des 'is'-Operators. |

### Rückgabewert

True, wenn 'is' true zurückgibt, sonst false.

## ObjectExt::Is(const SmartPtr\<Object\>\&) Methode

Implementiert die Übersetzung des 'is'-Operators. Spezialisierung für nullable Typen.

```cpp
template<class T> static std::enable_if<IsNullable<T>::value, bool>::type System::ObjectExt::Is(const SmartPtr<Object> &obj)
```

### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| T | Zieltyp. |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| obj | const [SmartPtr](../../smartptr/)\<[Object](../../object/)\>\& | [Object](../../object/) zum Testen des 'is'-Operators. |

### Rückgabewert

True, wenn 'is' true zurückgibt, sonst false.

## ObjectExt::Is(const SmartPtr\<Object\>\&) Methode

Implementiert die Übersetzung des 'is'-Operators. Spezialisierung für boxbare Typen mit definiertem ==-Operator.

```cpp
template<class T> static std::enable_if<System::IsBoxable<T>::value &&!IsNullable<T>::value &&!std::is_enum<T>::value &&detail::has_operator_equal<T>::value, bool>::type System::ObjectExt::Is(const SmartPtr<Object> &obj)
```

### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| T | Zieltyp. |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| obj | const [SmartPtr](../../smartptr/)\<[Object](../../object/)\>\& | [Object](../../object/) zum Testen des 'is'-Operators. |

### Rückgabewert

True, wenn 'is' true zurückgibt, sonst false.

## ObjectExt::Is(const SmartPtr\<Object\>\&) Methode

Implementiert die Übersetzung des 'is'-Operators. Spezialisierung für boxbare Typen ohne definierten ==-Operator.

```cpp
template<class T> static std::enable_if<System::IsBoxable<T>::value &&!IsNullable<T>::value &&!std::is_enum<T>::value &&!detail::has_operator_equal<T>::value, bool>::type System::ObjectExt::Is(const SmartPtr<Object> &obj)
```

### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| T | Zieltyp. |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| obj | const [SmartPtr](../../smartptr/)\<[Object](../../object/)\>\& | [Object](../../object/) zum Testen des 'is'-Operators. |

### Rückgabewert

True, wenn 'is' true zurückgibt, sonst false.

## ObjectExt::Is(const SmartPtr\<V\>\&) Methode

Implementiert die Übersetzung des 'is'-Operators. Spezialisierung für Wertetypen, die zu Schnittstellen geboxt werden.

```cpp
template<class T,class V> static std::enable_if<System::IsBoxable<T>::value &&!IsNullable<T>::value &&!std::is_enum<T>::value &&!std::is_same<V, Object>::value, bool>::type System::ObjectExt::Is(const SmartPtr<V> &obj)
```

### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| T | Zieltyp. |
| V | Typ des referenzierten Objekts. |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| obj | const [SmartPtr](../../smartptr/)\<V\>\& | [Object](../../object/) zum Testen des 'is'-Operators. |

### Rückgabewert

True, wenn 'is' true zurückgibt, sonst false.

## ObjectExt::Is(const SmartPtr\<U\>\&) Methode

Implementiert die Übersetzung des 'is'-Operators. Spezialisierung für Aufzählungstypen.

```cpp
template<class T,class U> static std::enable_if<std::is_enum<T>::value, bool>::type System::ObjectExt::Is(const SmartPtr<U> &obj)
```

### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| T | Zieltyp. |
| U | Typ des referenzierten Objekts. |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| obj | const [SmartPtr](../../smartptr/)\<U\>\& | [Object](../../object/) zum Testen des 'is'-Operators. |

### Rückgabewert

True, wenn 'is' true zurückgibt, sonst false.

## ObjectExt::Is(const WeakPtr\<U\>\&) Methode

Implementiert die Übersetzung des 'is'-Operators. Spezialisierung für Aufzählungstypen gegenüber schwachen Zeigern.

```cpp
template<class T,class U> static std::enable_if<std::is_enum<T>::value, bool>::type System::ObjectExt::Is(const WeakPtr<U> &obj)
```

### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| T | Zieltyp. |
| U | Typ des referenzierten Objekts. |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| obj | const [WeakPtr](../../weakptr/)\<U\>\& | [Object](../../object/) zum Testen des 'is'-Operators. |

### Rückgabewert

True, wenn 'is' true zurückgibt, sonst false.

## ObjectExt::Is(const Nullable\<U\>\&) Methode

Implementiert die Übersetzung des 'is'-Operators. Spezialisierung für den Typ [Nullable](../../nullable/).

```cpp
template<class T,class U> static bool System::ObjectExt::Is(const Nullable<U> &value)
```

### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| T | Zieltyp. |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | const [Nullable](../../nullable/)\<U\>\& | [Nullable](../../nullable/) Typ. |

### Rückgabewert

True, wenn 'is' true zurückgibt, sonst false.

## ObjectExt::Is(const char16_t *) Methode

Implementiert die Übersetzung des 'is'-Operators. Spezialisierung für Zeichenketten-Literal.

```cpp
template<class T> static bool System::ObjectExt::Is(const char16_t *str)
```

### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| T | Zieltyp. |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| str | const char16_t * | [String](../../string/) Literal. |

### Rückgabewert

True, wenn 'is' true zurückgibt, sonst false.

## ObjectExt::Is(int32_t) Methode

Implementiert die Übersetzung des 'is'-Operators. Spezialisierung für Ganzzahl-Literal.

```cpp
template<class T> static bool System::ObjectExt::Is(int32_t value)
```

### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| T | Zieltyp. |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | **int32_t** | **int32_t** Ganzzahl-Literal. |

### Rückgabewert

True, wenn 'is' true zurückgibt, sonst false.

## Siehe auch

* Klasse [ObjectExt](../)
* Klasse [Object](../../object/)
* Klasse [SmartPtr](../../smartptr/)
* Klasse [ExceptionWrapper](../../exceptionwrapper/)
* Klasse [WeakPtr](../../weakptr/)
* Klasse [Nullable](../../nullable/)
* Struktur [IsBoxable](../../isboxable/)
* Struktur [IsSmartPtr](../../issmartptr/)
* Struktur [IsExceptionWrapper](../../isexceptionwrapper/)
* Struktur [IsNullable](../../isnullable/)
* Namensraum [System](../../)
* Bibliothek [Aspose.Slides](../../../)