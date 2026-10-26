---
title: Concat()
second_title: Aspose.Slides för C++ API-referens
description: Konkatenar en strängarray.
type: docs
weight: 1
url: /sv/system.stringextra/concat/
---
## System::StringExtra::Concat(const ArrayPtr\<String\>\&) function

Konkatenar en strängarray.

```cpp
String System::StringExtra::Concat(const ArrayPtr<String> &parts)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| parts | const [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\>\& | [Array](../../system/array/) av strängar att sammanfoga. |

### Returvärde

Sammanfogad sträng.

## System::StringExtra::Concat(const String\&, const String\&) function

Konkatenar strängar.

```cpp
String System::StringExtra::Concat(const String &str0, const String &str1)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| str0 | const [String](../../system/string/)\& | Första strängen att sammanfoga. |
| str1 | const [String](../../system/string/)\& | Andra strängen att sammanfoga. |

### Returvärde

Sammanfogade parametersträngar.

## System::StringExtra::Concat(const String\&, const String\&, const String\&) function

Konkatenar strängar.

```cpp
String System::StringExtra::Concat(const String &str0, const String &str1, const String &str2)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| str0 | const [String](../../system/string/)\& | Första strängen att sammanfoga. |
| str1 | const [String](../../system/string/)\& | Andra strängen att sammanfoga. |
| str2 | const [String](../../system/string/)\& | Tredje strängen att sammanfoga. |

### Returvärde

Sammanfogade parametersträngar.

## System::StringExtra::Concat(const String\&, const String\&, const String\&, const String\&) function

Konkatenar strängar.

```cpp
String System::StringExtra::Concat(const String &str0, const String &str1, const String &str2, const String &str3)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| str0 | const [String](../../system/string/)\& | Första strängen att sammanfoga. |
| str1 | const [String](../../system/string/)\& | Andra strängen att sammanfoga. |
| str2 | const [String](../../system/string/)\& | Tredje strängen att sammanfoga. |
| str3 | const [String](../../system/string/)\& | Fjärde strängen att sammanfoga. |

### Returvärde

Sammanfogade parametersträngar.

## System::StringExtra::Concat(const ArrayPtr\<T\>\&) function

Konverterar flera objekt till sträng och konkatenar de resulterande strängarna. Specialisering för [SmartPtr](../../system/smartptr/)-typer.

```cpp
template<typename T> std::enable_if_t<IsSmartPtr<T>::value, String> System::StringExtra::Concat(const ArrayPtr<T> &args)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| args | const [ArrayPtr](../../system/arrayptr/)\<T\>\& | [Object](../../system/object/) för att konvertera och sammanfoga. |

### Returvärde

[String](../../system/string/) värde sammansatt från strängrepresentationerna av alla överförda objekt.

## System::StringExtra::Concat(const ArrayPtr\<T\>\&) function

Konverterar flera objekt till sträng och konkatenar de resulterande strängarna. Specialisering för aritmetiska typer.

```cpp
template<typename T> std::enable_if_t<std::is_arithmetic<T>::value, String> System::StringExtra::Concat(const ArrayPtr<T> &args)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| args | const [ArrayPtr](../../system/arrayptr/)\<T\>\& | [Object](../../system/object/) för att konvertera och sammanfoga. |

### Returvärde

[String](../../system/string/) värde sammansatt från strängrepresentationerna av alla överförda objekt.

## System::StringExtra::Concat(const ArrayPtr\<T\>\&) function

Konverterar flera objekt till sträng och konkatenar de resulterande strängarna. Specialisering för strukturer och andra värdetyper.

```cpp
template<typename T> std::enable_if_t<!IsSmartPtr<T>::value &&!std::is_arithmetic<T>::value, String> System::StringExtra::Concat(const ArrayPtr<T> &args)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| args | const [ArrayPtr](../../system/arrayptr/)\<T\>\& | [Object](../../system/object/) för att konvertera och sammanfoga. |

### Returvärde

[String](../../system/string/) värde sammansatt från strängrepresentationerna av alla överförda objekt.

## Se även

* Typedef [ArrayPtr](../../system/arrayptr/)
* Klass [String](../../system/string/)
* Struktur [IsSmartPtr](../../system/issmartptr/)
* Namnrymd [System::StringExtra](../)
* Bibliotek [Aspose.Slides](../../)