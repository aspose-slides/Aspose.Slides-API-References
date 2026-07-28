---
title: IsNull()
second_title: Aspose.Slides dla C++ – odniesienie do API
description: Sprawdza, czy określona wartość jest nullem. Wersja dla typów arytmetycznych i wyliczeniowych.
type: docs
weight: 1
url: /pl/system/testtools/isnull/
---
## TestTools::IsNull(T) metoda

Sprawdza, czy określona wartość jest nullem. [Version](../../version/) dla typów arytmetycznych i wyliczeniowych.

```cpp
template<typename T> static std::enable_if<std::is_arithmetic<T>::value||std::is_enum<T>::value, bool>::type System::TestTools::IsNull(T obj)
```

### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| T | Typ sprawdzanej wartości. |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| obj | T | Wartość do sprawdzenia pod kątem null. |

### Wartość zwracana

Zawsze zwraca false.

## TestTools::IsNull(const T\&) metoda

Sprawdza, czy określona wartość jest nullem. [Version](../../version/) dla typów niearytmetycznych i niewyliczeniowych.

```cpp
template<typename T> static std::enable_if<!std::is_arithmetic<T>::value &&!std::is_enum<T>::value, bool>::type System::TestTools::IsNull(const T &obj)
```

### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| T | Typ sprawdzanej wartości. |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| obj | const T\& | Wartość do sprawdzenia pod kątem null. |

### Wartość zwracana

True jeśli obiekt jest porównany do nullptr jako true, false w przeciwnym razie.

## TestTools::IsNull(const SharedPtr\<T\>\&) metoda

Sprawdza, czy określona wartość jest nullem. [Version](../../version/) dla typów niearytmetycznych.

```cpp
template<typename T> static bool System::TestTools::IsNull(const SharedPtr<T> &obj)
```

### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| T | Typ sprawdzanej wartości. |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| obj | const [SharedPtr](../../sharedptr/)\<T\>\& | Wartość do sprawdzenia pod kątem null. |

### Wartość zwracana

True jeśli obiekt jest porównany do nullptr jako true, false w przeciwnym razie.

## TestTools::IsNull(System::Collections::Generic::KeyValuePair\<K, V\>\&) metoda

Sprawdza, czy określona wartość jest nullem. [Version](../../version/) dla par klucz-wartość.

```cpp
template<typename K,typename V> static bool System::TestTools::IsNull(System::Collections::Generic::KeyValuePair<K, V> &kvp)
```

### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| K | Typ klucza. |
| V | Typ wartości. |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| kvp | [System::Collections::Generic::KeyValuePair](../../../system.collections.generic/keyvaluepair/)\<K, V\>\& | Obiekt pary. |

### Wartość zwracana

True jeśli para jest uznawana za null, false w przeciwnym razie.

## TestTools::IsNull(const System::String\&) metoda

Sprawdza, czy ciąg jest nullem.

```cpp
static bool System::TestTools::IsNull(const System::String &str)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| str | const [System::String](../../string/)\& | [String](../../string/) do sprawdzenia. |

### Wartość zwracana

True jeśli ciąg jest uznawany za null, false w przeciwnym razie.

## Zobacz także

* Typedef [SharedPtr](../../sharedptr/)
* Class [KeyValuePair](../../../system.collections.generic/keyvaluepair/)
* Class [String](../../string/)
* Struct [TestTools](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)