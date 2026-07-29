---
title: Equals()
second_title: Aspose.Slides för C++ API-referens
description: 
type: docs
weight: 14
url: /sv/system/objectext/equals/
---
## ObjectExt::Equals(const T\&, const T2\&) method




```cpp
template<typename T,typename T2> static std::enable_if<IsExceptionWrapper<T>::value, bool>::type System::ObjectExt::Equals(const T &obj, const T2 &another)
```

## ObjectExt::Equals(const T\&, const T2\&) method


Ersättning för C# [Object.Equals](../../object/equals/) anrop som fungerar för alla typer i C++. Överlagring för smarta pekartyper.

```cpp
template<typename T,typename T2> static std::enable_if<IsSmartPtr<T>::value, bool>::type System::ObjectExt::Equals(const T &obj, const T2 &another)
```


### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| T | Första objekttypen. |
| T2 | Andra objekttypen. |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| obj | const T\& | Första objektet. |
| another | const T2\& | Andra objektet. |

### Returvärde

Sant om objekten anses vara lika, annars falskt.

## ObjectExt::Equals(T, const T2\&) method


Ersättning för C# [Object.Equals](../../object/equals/) anrop som fungerar för alla typer i C++. Överlagring för strukturt typer.

```cpp
template<typename T,typename T2> static std::enable_if<!IsExceptionWrapper<T>::value &&!IsSmartPtr<T>::value &&!std::is_scalar<T>::value, bool>::type System::ObjectExt::Equals(T obj, const T2 &another)
```


### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| T | Första objekttypen. |
| T2 | Andra objekttypen. |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| obj | T | Första objektet. |
| another | const T2\& | Andra objektet. |

### Returvärde

Sant om objekten anses vara lika, annars falskt.

## ObjectExt::Equals(const T\&, const T2\&) method


Ersättning för C# [Object.Equals](../../object/equals/) anrop som fungerar för alla typer i C++. Överlagring för skalära typer.

```cpp
template<typename T,typename T2> static std::enable_if<!IsSmartPtr<T>::value &&std::is_scalar<T>::value, bool>::type System::ObjectExt::Equals(const T &obj, const T2 &another)
```


### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| T | Första objekttypen. |
| T2 | Andra objekttypen. |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| obj | const T\& | Första objektet. |
| another | const T2\& | Andra objektet. |

### Returvärde

Sant om objekten anses vara lika, annars falskt.

## ObjectExt::Equals(const char_t(&), String) method


Ersättning för C# [Object.Equals](../../object/equals/) anrop som fungerar för alla typer i C++. Överlagring för strängliteral med strängjämförelse.

```cpp
template<size_t> static bool System::ObjectExt::Equals(const char_t(&obj)[N], String another)
```


### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| N | [String](../../string/) literalens storlek. |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| obj | const char_t(&) | [String](../../string/) literal. |
| another | [String](../../string/) | [String](../../string/). |

### Returvärde

Sant om strängarna matchar, annars falskt.

## ObjectExt::Equals(const float\&, const float\&) method


Emulerar C#-stil flyttalsjämförelse där två NaN-värden anses lika även om IEC 60559:1989 säger att NaN inte är lika med något värde, inklusive NaN.

```cpp
bool System::ObjectExt::Equals(const float &obj, const float &another)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| obj | const **float**\& | Vänster sida flyttalsvärde. |
| another | const **float**\& | Höger sida flyttalsvärde. |

### Returvärde

Sant om **obj** och **another** båda är NaN eller lika, annars falskt.

## ObjectExt::Equals(const double\&, const double\&) method


Emulerar C#-stil flyttalsjämförelse där två NaN-värden anses lika även om IEC 60559:1989 säger att NaN inte är lika med något värde, inklusive NaN.

```cpp
bool System::ObjectExt::Equals(const double &obj, const double &another)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| obj | const **double**\& | Vänster sida flyttalsvärde. |
| another | const **double**\& | Höger sida flyttalsvärde. |

### Returvärde

Sant om **obj** och **another** båda är NaN eller lika, annars falskt.

## See Also

* Class [ObjectExt](../)
* Class [String](../../string/)
* Struct [IsExceptionWrapper](../../isexceptionwrapper/)
* Struct [IsSmartPtr](../../issmartptr/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)