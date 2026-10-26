---
title: IsNull()
second_title: Aspose.Slides voor C++ API-referentie
description: Controleert of een specifieke waarde null is. Versie voor rekenkundige en enum-typen.
type: docs
weight: 1
url: /nl/system/testtools/isnull/
---
## TestTools::IsNull(T) methode


Controleert of een specifieke waarde null is. [Version](../../version/) voor rekenkundige en enum-typen.

```cpp
template<typename T> static std::enable_if<std::is_arithmetic<T>::value||std::is_enum<T>::value, bool>::type System::TestTools::IsNull(T obj)
```


### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| T | Type van de te controleren waarde. |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| obj | T | Waarde die op null moet worden gecontroleerd. |

### Retourwaarde

Altijd false.

## TestTools::IsNull(const T\&) methode


Controleert of een specifieke waarde null is. [Version](../../version/) voor niet-rekenkundige en niet-enum-waarde-typen.

```cpp
template<typename T> static std::enable_if<!std::is_arithmetic<T>::value &&!std::is_enum<T>::value, bool>::type System::TestTools::IsNull(const T &obj)
```


### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| T | Type van de te controleren waarde. |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| obj | const T\& | Waarde die op null moet worden gecontroleerd. |

### Retourwaarde

True als het object met nullptr wordt vergeleken als true, anders false.

## TestTools::IsNull(const SharedPtr\<T\>\&) methode


Controleert of een specifieke waarde null is. [Version](../../version/) voor niet-rekenkundige waarde-typen.

```cpp
template<typename T> static bool System::TestTools::IsNull(const SharedPtr<T> &obj)
```


### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| T | Type van de te controleren waarde. |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| obj | const [SharedPtr](../../sharedptr/)\<T\>\& | Waarde die op null moet worden gecontroleerd. |

### Retourwaarde

True als het object met nullptr wordt vergeleken als true, anders false.

## TestTools::IsNull(System::Collections::Generic::KeyValuePair\<K, V\>\&) methode


Controleert of een specifieke waarde null is. [Version](../../version/) voor sleutel-waarde-paren.

```cpp
template<typename K,typename V> static bool System::TestTools::IsNull(System::Collections::Generic::KeyValuePair<K, V> &kvp)
```


### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| K | Typesleutel. |
| V | Typeswaarde. |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| kvp | [System::Collections::Generic::KeyValuePair](../../../system.collections.generic/keyvaluepair/)\<K, V\>\& | Paarobject. |

### Retourwaarde

True als het paar als null wordt beschouwd, anders false.

## TestTools::IsNull(const System::String\&) methode


Controleert of een string null is.

```cpp
static bool System::TestTools::IsNull(const System::String &str)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| str | const [System::String](../../string/)\& | [String](../../string/) om te controleren. |

### Retourwaarde

True als de string als null wordt beschouwd, anders false.

## Zie ook

* Typedef [SharedPtr](../../sharedptr/)
* Klasse [KeyValuePair](../../../system.collections.generic/keyvaluepair/)
* Klasse [String](../../string/)
* Struct [TestTools](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)