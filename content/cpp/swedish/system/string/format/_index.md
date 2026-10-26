---
title: Format()
second_title: Aspose.Slides för C++ API-referens
description: Formaterar strängen i C#-stil.
type: docs
weight: 885
url: /sv/system/string/format/
---
## String::Format(const SharedPtr\<IFormatProvider\>\&, const String\&, const Args\&...) metod


Formaterar strängen i C#-stil.

```cpp
template<class...> String System::String::Format(const SharedPtr<IFormatProvider> &fp, const String &format, const Args &... args)
```


### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| Args | Argument för att formatera strängen. |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fp | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Formatleverantör att använda för att konvertera argument till strängar. |
| format | const [String](../)\& | Formatsträng. |
| args | const Args\&... | Argument för att formatera strängen. |

## String::Format(std::nullptr_t, const String\&, const Args\&...) metod


Formaterar strängen i C#-stil.

```cpp
template<class...> String System::String::Format(std::nullptr_t, const String &format, const Args &... args)
```


### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| Args | Argument för att formatera strängen. |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| format | std::nullptr_t | Formatsträng. |
| args | const [String](../)\& | Argument för att formatera strängen. |

## String::Format(std::nullptr_t, const char16_t(&), const Args\&...) metod


Formaterar strängen i C#-stil.

```cpp
template<std::size_t,class...> String System::String::Format(std::nullptr_t, const char16_t(&format)[N], const Args &... args)
```


### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| Args | Argument för att formatera strängen. |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| format | std::nullptr_t | Formatsträng. |
| args | const char16_t(&) | Argument för att formatera strängen. |

## String::Format(const String\&, const Args\&...) metod


Formaterar strängen i C#-stil.

```cpp
template<class...> String System::String::Format(const String &format, const Args &... args)
```


### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| Args | Argument för att formatera strängen. |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| format | const [String](../)\& | Formatsträng. |
| args | const Args\&... | Argument för att formatera strängen. |

## String::Format(const String\&, const System::ArrayPtr\<T\>\&) metod


Formaterar strängen i C#-stil.

```cpp
template<class T> String System::String::Format(const String &format, const System::ArrayPtr<T> &args)
```


### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| T | Argument för att formatera strängen. |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| format | const [String](../)\& | Formatsträng. |
| args | const [System::ArrayPtr](../../arrayptr/)\<T\>\& | Argument för att formatera strängen. |

## Se även

* Typedef [SharedPtr](../../sharedptr/)
* Typedef [ArrayPtr](../../arrayptr/)
* Klass [String](../)
* Klass [IFormatProvider](../../iformatprovider/)
* Namnrymd [System](../../)
* Bibliotek [Aspose.Slides](../../../)