---
title: IsNull()
second_title: Aspose.Slides pro C++ – referenční příručka API
description: Kontroluje, zda je konkrétní hodnota null. Verze pro aritmetické a výčtové typy.
type: docs
weight: 1
url: /cs/system/testtools/isnull/
---
## TestTools::IsNull(T) metoda


Kontroluje, zda je konkrétní hodnota null. [Version](../../version/) pro aritmetické a výčtové typy.

```cpp
template<typename T> static std::enable_if<std::is_arithmetic<T>::value||std::is_enum<T>::value, bool>::type System::TestTools::IsNull(T obj)
```


### Parametry šablony

| Parametr | Popis |
| --- | --- |
| T | Type of value being checked. |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| obj | T | Value to check for null. |

### Návratová hodnota

Vždy vrací false.

## TestTools::IsNull(const T\&) metoda


Kontroluje, zda je konkrétní hodnota null. [Version](../../version/) pro nearitmetické a ne výčtové typy hodnot.

```cpp
template<typename T> static std::enable_if<!std::is_arithmetic<T>::value &&!std::is_enum<T>::value, bool>::type System::TestTools::IsNull(const T &obj)
```


### Parametry šablony

| Parametr | Popis |
| --- | --- |
| T | Type of value being checked. |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| obj | const T\& | Value to check for null. |

### Návratová hodnota

True, pokud je objekt porovnán s nullptr jako true, jinak false.

## TestTools::IsNull(const SharedPtr\<T\>\&) metoda


Kontroluje, zda je konkrétní hodnota null. [Version](../../version/) pro nearitmetické typy hodnot.

```cpp
template<typename T> static bool System::TestTools::IsNull(const SharedPtr<T> &obj)
```


### Parametry šablony

| Parametr | Popis |
| --- | --- |
| T | Type of value being checked. |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| obj | const [SharedPtr](../../sharedptr/)\<T\>\& | Value to check for null. |

### Návratová hodnota

True, pokud je objekt porovnán s nullptr jako true, jinak false.

## TestTools::IsNull(System::Collections::Generic::KeyValuePair\<K, V\>\&) metoda


Kontroluje, zda je konkrétní hodnota null. [Version](../../version/) pro páry klíč-hodnota.

```cpp
template<typename K,typename V> static bool System::TestTools::IsNull(System::Collections::Generic::KeyValuePair<K, V> &kvp)
```


### Parametry šablony

| Parametr | Popis |
| --- | --- |
| K | Key type. |
| V | Value type. |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| kvp | [System::Collections::Generic::KeyValuePair](../../../system.collections.generic/keyvaluepair/)\<K, V\>\& | Pair object. |

### Návratová hodnota

True, pokud je pár považován za null, jinak false.

## TestTools::IsNull(const System::String\&) metoda


Kontroluje, zda je řetězec null.

```cpp
static bool System::TestTools::IsNull(const System::String &str)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| str | const [System::String](../../string/)\& | [String](../../string/) ke kontrole. |

### Návratová hodnota

True, pokud je řetězec považován za null, jinak false.

## Viz také

* Typedef [SharedPtr](../../sharedptr/)
* třída [KeyValuePair](../../../system.collections.generic/keyvaluepair/)
* třída [String](../../string/)
* struktura [TestTools](../)
* jmenný prostor [System](../../)
* Library [Aspose.Slides](../../../)