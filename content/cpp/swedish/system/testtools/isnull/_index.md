---
title: IsNull()
second_title: Aspose.Slides för C++ API-referens
description: Kontrollerar om ett specifikt värde är null. Version för aritmetiska och enum-typer.
type: docs
weight: 1
url: /sv/system/testtools/isnull/
---
## TestTools::IsNull(T) metod

Kontrollerar om specifikt värde är null. [Version](../../version/) för aritmetiska och enum-typer.

```cpp
template<typename T> static std::enable_if<std::is_arithmetic<T>::value||std::is_enum<T>::value, bool>::type System::TestTools::IsNull(T obj)
```

### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| T | Typ av värde som kontrolleras. |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| obj | T | Värde att kontrollera för null. |

### Returvärde

Returnerar alltid falskt.

## TestTools::IsNull(const T\&) metod

Kontrollerar om specifikt värde är null. [Version](../../version/) för icke-aritmetiska och icke-enum-värdetyper.

```cpp
template<typename T> static std::enable_if<!std::is_arithmetic<T>::value &&!std::is_enum<T>::value, bool>::type System::TestTools::IsNull(const T &obj)
```

### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| T | Typ av värde som kontrolleras. |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| obj | const T\& | Värde att kontrollera för null. |

### Returvärde

Sant om objektet jämförs med nullptr som sant, annars falskt.

## TestTools::IsNull(const SharedPtr\<T\>\&) metod

Kontrollerar om specifikt värde är null. [Version](../../version/) för icke-aritmetiska värdetyper.

```cpp
template<typename T> static bool System::TestTools::IsNull(const SharedPtr<T> &obj)
```

### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| T | Typ av värde som kontrolleras. |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| obj | const [SharedPtr](../../sharedptr/)\<T\>\& | Värde att kontrollera för null. |

### Returvärde

Sant om objektet jämförs med nullptr som sant, annars falskt.

## TestTools::IsNull(System::Collections::Generic::KeyValuePair\<K, V\>\&) metod

Kontrollerar om specifikt värde är null. [Version](../../version/) för nyckel-värde-par.

```cpp
template<typename K,typename V> static bool System::TestTools::IsNull(System::Collections::Generic::KeyValuePair<K, V> &kvp)
```

### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| K | Nyckeltyp. |
| V | Värdetyp. |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| kvp | [System::Collections::Generic::KeyValuePair](../../../system.collections.generic/keyvaluepair/)\<K, V\>\& | Par-objekt. |

### Returvärde

Sant om par anses vara null, annars falskt.

## TestTools::IsNull(const System::String\&) metod

Kontrollerar om strängen är null.

```cpp
static bool System::TestTools::IsNull(const System::String &str)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| str | const [System::String](../../string/)\& | [String](../../string/) att kontrollera. |

### Returvärde

Sant om strängen anses vara null, annars falskt.

## Se även

* Typedef [SharedPtr](../../sharedptr/)
* Klass [KeyValuePair](../../../system.collections.generic/keyvaluepair/)
* Klass [String](../../string/)
* Struct [TestTools](../)
* Namnrymd [System](../../)
* Library [Aspose.Slides](../../../)