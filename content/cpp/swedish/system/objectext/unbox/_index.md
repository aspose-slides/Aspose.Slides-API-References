---
title: Unbox()
second_title: Aspose.Slides för C++ API-referens
description: Packar upp värdetyper efter konvertering till Object. Implementation för enum-typer.
type: docs
weight: 53
url: /sv/system/objectext/unbox/
---
## ObjectExt::Unbox(const SmartPtr\<Object\>\&) metod

Packar upp värdetyper efter konvertering till [Object](../../object/). Implementation för enum-typer.

```cpp
template<typename T> static std::enable_if<std::is_enum<T>::value, T>::type System::ObjectExt::Unbox(const SmartPtr<Object> &obj)
```

### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| T | [Enum](../../enum/) typ. |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| obj | const [SmartPtr](../../smartptr/)\<[Object](../../object/)\>\& | [Object](../../object/) att packa upp. |

### Returvärde

[Enum](../../enum/) värde.

## ObjectExt::Unbox(const SmartPtr\<Object\>\&) metod

Packar upp värdetyper efter konvertering till [Object](../../object/). Implementation för icke-enum och icke-nullbara typer.

```cpp
template<class T> static std::enable_if<!std::is_enum<T>::value &&detail::has_operator_equal<T>::value, T>::type System::ObjectExt::Unbox(const SmartPtr<Object> &obj)
```

### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| T | Value type. |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| obj | const [SmartPtr](../../smartptr/)\<[Object](../../object/)\>\& | [Object](../../object/) att packa upp. |

### Returvärde

Utpaketat värde.

## ObjectExt::Unbox(const SmartPtr\<Object\>\&) metod

Packar upp värdetyper efter konvertering till [Object](../../object/). Implementation för icke-enum och icke-nullbara typer.

```cpp
template<class T> static std::enable_if<!std::is_enum<T>::value &&!detail::has_operator_equal<T>::value, T>::type System::ObjectExt::Unbox(const SmartPtr<Object> &obj)
```

### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| T | Value type. |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| obj | const [SmartPtr](../../smartptr/)\<[Object](../../object/)\>\& | [Object](../../object/) att packa upp. |

### Returvärde

Utpaketat värde.

## ObjectExt::Unbox(E) metod

Packar upp enum-typer till heltal.

```cpp
template<class T,class E> static std::enable_if<std::is_enum<E>::value &&std::numeric_limits<T>::is_integer, T>::type System::ObjectExt::Unbox(E e)
```

### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| T | Destination integer type. |
| E | Source enum type. |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| e | E | Värde att packa upp. |

### Returvärde

Heltalsrepresentation av enum.

## ObjectExt::Unbox(E) metod

Konverterar enum-typer.

```cpp
template<class T,class E> static std::enable_if<std::is_enum<E>::value &&std::is_enum<T>::value, T>::type System::ObjectExt::Unbox(E e)
```

### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| T | Destination enum type. |
| E | Source enum type. |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| e | E | Värde att packa upp. |

### Returvärde

Konverterat enum-värde.

## ObjectExt::Unbox(const SmartPtr\<Object\>\&) metod

Packar upp strängvärden.

```cpp
String System::ObjectExt::Unbox(const SmartPtr<Object> &obj)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| obj | const [SmartPtr](../../smartptr/)\<[Object](../../object/)\>\& | [Object](../../object/) att packa upp |

### Returvärde

[String](../../string/) representation av inbäddad sträng, kan vara null om inbäddad sträng var null.

## Se även

* Klass [SmartPtr](../../smartptr/)
* Klass [Object](../../object/)
* Klass [ObjectExt](../)
* Klass [String](../../string/)
* Namnrymd [System](../../)
* Bibliotek [Aspose.Slides](../../../)