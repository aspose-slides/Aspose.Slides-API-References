---
title: operator==()
second_title: Aspose.Slides för C++ API-referens
description: 
type: docs
weight: 2042
url: /sv/system/operator_equal_equal/
---
## System::operator==(ArraySegment\<T\>, ArraySegment\<T\>) funktion




```cpp
template<typename T> bool System::operator==(ArraySegment<T> a, ArraySegment<T> b)
```

## System::operator==(std::nullptr_t, DateTime) funktion




```cpp
constexpr bool System::operator==(std::nullptr_t, DateTime)
```

## System::operator==(std::nullptr_t, const DateTimeOffset\&) funktion




```cpp
constexpr bool System::operator==(std::nullptr_t, const DateTimeOffset &)
```

## System::operator==(std::nullptr_t, const Nullable\<T\>\&) funktion


Bestämmer om det angivna [Nullable](../nullable/)-objektet representerar ett värde som är lika med null.

```cpp
template<typename T> bool System::operator==(std::nullptr_t, const Nullable<T> &other)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| other | std::nullptr_t | En konstant referens till ett [Nullable](../nullable/)-objekt att testa |

### Returvärde

Sant om det angivna objektet representerar ett null-värde, annars falskt

## System::operator==(const T1\&, const Nullable\<T2\>\&) funktion


Bestämmer om det angivna värdet är lika med värdet som representeras av det angivna [Nullable](../nullable/)-objektet genom att tillämpa [operator==()](./) på dessa värden.

```cpp
template<typename T1,typename T2> std::enable_if<!IsNullable<T1>::value, bool>::type System::operator==(const T1 &some, const Nullable<T2> &other)
```


### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| T1 | Typen för det första jämförelsevärdet |
| T2 | Den underliggande typen för [Nullable](../nullable/)-objektet som representerar det andra jämförelsevärdet |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| some | const T1\& | En konstant referens till värdet som ska användas som det första jämförelsevärdet |
| other | const [Nullable](../nullable/)\<T2\>\& | En konstant referens till [Nullable](../nullable/)-objektet vars representerade värde ska användas som det andra jämförelsevärdet |

### Returvärde

Sant om jämförelsevärdena är lika, annars falskt

## System::operator==(const SmartPtr\<X\>\&, const SmartPtr\<Y\>\&) funktion


Jämför lika två smarta pekare.

```cpp
template<class X,class Y> bool System::operator==(const SmartPtr<X> &x, const SmartPtr<Y> &y)
```


### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| X | Typen för den pekade typen för den första pekaren. |
| Y | Typen för den pekade typen för den andra pekaren. |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| x | const [SmartPtr](../smartptr/)\<X\>\& | Den första pekaren att jämföra. |
| y | const [SmartPtr](../smartptr/)\<Y\>\& | Den andra pekaren att jämföra. |

### Returvärde

Sant om pekarna matchar, annars falskt

## System::operator==(std::nullptr_t, SmartPtr\<X\> const\&) funktion


Kontrollerar om smart pekare är null.

```cpp
template<class X> bool System::operator==(std::nullptr_t, SmartPtr<X> const &x)
```


### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| X | Typen för den pekade typen för pekaren. |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| x | std::nullptr_t | Pekare att kontrollera. |

### Returvärde

Sant om pekaren är null, annars falskt.

## System::operator==(const SmartPtr\<X\>\&, const Y *) funktion


Jämförelse av likhet mellan smart pekare och enkel (C) pekare.

```cpp
template<class X,class Y> std::enable_if<std::is_base_of<Object, Y>::value &&detail::has_no_operator_equal<X, Y>::value, bool>::type System::operator==(const SmartPtr<X> &x, const Y *y)
```


### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| X | typ av smart pekare. |
| Y | typ av enkel pekare. |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| x | const [SmartPtr](../smartptr/)\<X\>\& | smart pekare att jämföra (vänster). |
| y | const Y * | pekare att jämföra (höger). |

### Returvärde

Sant om pekarna matchar, annars falskt.

## System::operator==(const X *, const SmartPtr\<Y\>\&) funktion


Jämförelse av likhet mellan smart pekare och enkel (C) pekare.

```cpp
template<class X,class Y> std::enable_if<std::is_base_of<Object, X>::value &&detail::has_no_operator_equal<X, Y>::value, bool>::type System::operator==(const X *x, const SmartPtr<Y> &y)
```


### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| X | typ av enkel pekare. |
| Y | typ av smart pekare. |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| x | const X * | pekare att jämföra (höger). |
| y | const [SmartPtr](../smartptr/)\<Y\>\& | smart pekare att jämföra (vänster). |

### Returvärde

Sant om pekarna matchar, annars falskt.

## System::operator==(T const\&, std::nullptr_t) funktion


Kontrollerar om värdetypobjekt (översatt C#-struktur etc.) är null.

```cpp
template<class T> std::enable_if<!std::is_scalar<T>::value &&!std::is_pointer<T>::value &&!std::is_array<T>::value &&detail::has_method_is_null<T>::value, bool>::type System::operator==(T const &x, std::nullptr_t)
```


### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| T | Värdetyp. |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| x | T const\& | [Object](../object/) att kontrollera. |

### Returvärde

Sant om objektet är null, annars falskt.

## System::operator==(std::nullptr_t, T const\&) funktion


Kontrollerar om värdetypobjekt (översatt C#-struktur etc.) är null.

```cpp
template<class T> std::enable_if<!std::is_scalar<T>::value &&!std::is_pointer<T>::value &&!std::is_array<T>::value &&detail::has_method_is_null<T>::value, bool>::type System::operator==(std::nullptr_t, T const &x)
```


### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| T | Värdetyp. |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| x | std::nullptr_t | [Object](../object/) att kontrollera. |

### Returvärde

Sant om objektet är null, annars falskt.

## System::operator==(Chars\&, const String\&) funktion


[String](../string/) jämförelse.

```cpp
template<class Chars,typename std::enable_if< IsStringLiteral< Chars, char_t >::value >::type *> bool System::operator==(Chars &left, const String &right)
```


### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| Chars | [String](../string/) literaltyp. |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| left | Chars\& | [String](../string/) literal att jämföra. |
| right | const [String](../string/)\& | [String](../string/) att jämföra. |

### Returvärde

sant om strängarna matchar, annars falskt.

## System::operator==(T\&, const String\&) funktion


[String](../string/) jämförelse.

```cpp
template<class T,typename std::enable_if< IsStringPointer< T, char_t >::value >::type *> bool System::operator==(T &left, const String &right)
```


### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| T | [String](../string/) pekartyp. |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| left | T\& | [String](../string/) pekare att jämföra. |
| right | const [String](../string/)\& | [String](../string/) att jämföra. |

### Returvärde

sant om strängarna matchar, annars falskt.

## System::operator==(const SharedPtr\<Object\>\&, const String\&) funktion


[Object](../object/) och strängjämförelse.

```cpp
bool System::operator==(const SharedPtr<Object> &left, const String &right)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| left | const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\& | [Object](../object/) att konvertera till sträng och jämföra. |
| right | const [String](../string/)\& | [String](../string/) att jämföra. |

### Returvärde

sant om objektets strängrepresentation är lika med strängen, annars falskt.

## System::operator==(std::nullptr_t, const String\&) funktion


Kontrollerar om strängen är null.

```cpp
bool System::operator==(std::nullptr_t, const String &str)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| str | std::nullptr_t | [String](../string/) att kontrollera. |

### Returvärde

sant om strängen är null, annars falskt.

## System::operator==(std::nullptr_t, TimeSpan) funktion




```cpp
constexpr bool System::operator==(std::nullptr_t, TimeSpan)
```

## System::operator==(const SharedPtr\<Uri\>\&, const SharedPtr\<Uri\>\&) funktion


Bestämmer om de URI:er som representeras av det aktuella och det angivna objektet är lika.

```cpp
bool System::operator==(const SharedPtr<Uri> &uri1, const SharedPtr<Uri> &uri2)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| uri1 | const [SharedPtr](../sharedptr/)\<[Uri](../uri/)\>\& | Det första [Uri](../uri/)-objektet att jämföra |
| uri2 | const [SharedPtr](../sharedptr/)\<[Uri](../uri/)\>\& | Det andra [Uri](../uri/)-objektet att jämföra |

### Returvärde

Sant om URI:erna är lika, annars falskt

## Se även

* Typedef [SharedPtr](../sharedptr/)
* Klass [ArraySegment](../arraysegment/)
* Klass [DateTime](../datetime/)
* Klass [DateTimeOffset](../datetimeoffset/)
* Klass [Nullable](../nullable/)
* Klass [SmartPtr](../smartptr/)
* Klass [Object](../object/)
* Klass [String](../string/)
* Klass [TimeSpan](../timespan/)
* Klass [Uri](../uri/)
* Struktur [IsNullable](../isnullable/)
* Namnrymd [System](../)
* Bibliotek [Aspose.Slides](../../)