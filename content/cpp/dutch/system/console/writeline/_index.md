---
title: WriteLine()
second_title: Aspose.Slides voor C++ API-referentie
description: Schrijft de huidige regeleinde naar de standaard uitvoerstream.
type: docs
weight: 14
url: /nl/system/console/writeline/
---
## Console::WriteLine() methode

Schrijft de huidige regeleinde naar de standaard uitvoerstream.

```cpp
static void System::Console::WriteLine()
```

## Console::WriteLine(const SharedPtr\<T\>\&) methode

Schrijft de tekenreeksrepresentatie van het opgegeven object, gevolgd door de huidige regeleinde, naar de standaard uitvoerstream.

```cpp
template<class T> static void System::Console::WriteLine(const SharedPtr<T> &object)
```

### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| T | Type van het object dat moet worden uitgegeven |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| object | const [SharedPtr](../../sharedptr/)\<T\>\& | [Object](../../object/) om uit te voeren |

## Console::WriteLine(bool) methode

Schrijft de tekenreeksrepresentatie van een bool-waarde, gevolgd door de huidige regeleinde, naar de standaard uitvoerstream.

```cpp
static void System::Console::WriteLine(bool value)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | **bool** | De waarde die moet worden uitgegeven |

## Console::WriteLine(char_t) methode

Schrijft de opgegeven tekenwaarde, gevolgd door de huidige regeleinde, naar de standaard uitvoerstream.

```cpp
static void System::Console::WriteLine(char_t value)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | char_t | De waarde die moet worden uitgegeven |

## Console::WriteLine(const ArrayPtr\<char_t\>\&) methode

Schrijft de tekenreeksrepresentatie van de opgegeven tekenreeks-array, gevolgd door de huidige regeleinde, naar de standaard uitvoerstream.

```cpp
static void System::Console::WriteLine(const ArrayPtr<char_t> &buffer)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../arrayptr/)\<char_t\>\& | De array die moet worden uitgegeven |

## Console::WriteLine(const Decimal\&) methode

Schrijft de tekenreeksrepresentatie van [Decimal](../../decimal/)-waarde, gevolgd door de huidige regeleinde, naar de standaard uitvoerstream.

```cpp
static void System::Console::WriteLine(const Decimal &value)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | const [Decimal](../../decimal/)\& | De waarde die moet worden uitgegeven |

## Console::WriteLine(double) methode

Schrijft de tekenreeksrepresentatie van een double-precisie floating-pointwaarde, gevolgd door de huidige regeleinde, naar de standaard uitvoerstream.

```cpp
static void System::Console::WriteLine(double value)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | **double** | De waarde die moet worden uitgegeven |

## Console::WriteLine(float) methode

Schrijft de tekenreeksrepresentatie van een single-precisie floating-pointwaarde, gevolgd door de huidige regeleinde, naar de standaard uitvoerstream.

```cpp
static void System::Console::WriteLine(float value)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | **float** | De waarde die moet worden uitgegeven |

## Console::WriteLine(int32_t) methode

Schrijft de tekenreeksrepresentatie van een 32-bit gehele getalwaarde, gevolgd door de huidige regeleinde, naar de standaard uitvoerstream.

```cpp
static void System::Console::WriteLine(int32_t value)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | **int32_t** | De waarde die moet worden uitgegeven |

## Console::WriteLine(int64_t) methode

Schrijft de tekenreeksrepresentatie van een 64-bit gehele getalwaarde, gevolgd door de huidige regeleinde, naar de standaard uitvoerstream.

```cpp
static void System::Console::WriteLine(int64_t value)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | **int64_t** | De waarde die moet worden uitgegeven |

## Console::WriteLine(const String\&) methode

Schrijft het opgegeven string-object, gevolgd door de huidige regeleinde, naar de standaard uitvoerstream.

```cpp
static void System::Console::WriteLine(const String &value)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | const [String](../../string/)\& | Het string-object dat moet worden uitgegeven |

## Console::WriteLine(const char_t *) methode

Schrijft de opgegeven c-string, gevolgd door de huidige regeleinde, naar de standaard uitvoerstream.

```cpp
static void System::Console::WriteLine(const char_t *value)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | const char_t * | De c-string die moet worden uitgegeven |

## Console::WriteLine(const TypeInfo\&) methode

Schrijft de tekenreeksrepresentatie van [TypeInfo](../../typeinfo/)-waarde, gevolgd door de huidige regeleinde, naar de standaard uitvoerstream.

```cpp
static void System::Console::WriteLine(const TypeInfo &value)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | const [TypeInfo](../../typeinfo/)\& | De waarde die moet worden uitgegeven |

## Console::WriteLine(uint32_t) methode

Schrijft de tekenreeksrepresentatie van een unsigned 32-bit gehele getalwaarde, gevolgd door de huidige regeleinde, naar de standaard uitvoerstream.

```cpp
static void System::Console::WriteLine(uint32_t value)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | **uint32_t** | De waarde die moet worden uitgegeven |

## Console::WriteLine(uint64_t) methode

Schrijft de tekenreeksrepresentatie van een unsigned 64-bit gehele getalwaarde, gevolgd door de huidige regeleinde, naar de standaard uitvoerstream.

```cpp
static void System::Console::WriteLine(uint64_t value)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | **uint64_t** | De waarde die moet worden uitgegeven |

## Console::WriteLine(const ArrayPtr\<char_t\>\&, int, int) methode

Schrijft de tekenreeksrepresentatie van het opgegeven bereik van de opgegeven tekenreeks-array, gevolgd door de huidige regeleinde, naar de standaard uitvoerstream.

```cpp
static void System::Console::WriteLine(const ArrayPtr<char_t> &buffer, int index, int count)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../arrayptr/)\<char_t\>\& | De tekenreeks-array |
| index | int | De index in de array waar het uit te voeren bereik begint |
| count | int | Het aantal elementen in het uit te voeren bereik |

## Console::WriteLine(const Exception\&) methode

Schrijft de tekenreeksrepresentatie van het opgegeven Exception-object, gevolgd door de huidige regeleinde, naar de standaard uitvoerstream.

```cpp
static void System::Console::WriteLine(const Exception &e)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| e | const [Exception](../../exception/)\& | De waarde die moet worden uitgegeven |

## Console::WriteLine(const String\&, Args\&&...) methode

Schrijft de tekenreeksrepresentatie van de opgegeven argumenten, geformatteerd volgens het opgegeven formaat, gevolgd door de huidige regeleinde, naar de standaard uitvoerstream.

```cpp
template<class...> static void System::Console::WriteLine(const String &format, Args &&... args)
```

### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| The | typen van de waarden die moeten worden uitgegeven |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| format | const [String](../../string/)\& | Het string-formaat |
| args | Args\&&... | De waarden die moeten worden uitgegeven |

## Console::WriteLine(const char *) methode




```cpp
static void System::Console::WriteLine(const char *)=delete
```

## Zie ook

* Typedef [SharedPtr](../../sharedptr/)
* Typedef [ArrayPtr](../../arrayptr/)
* Typedef [Exception](../../exception/)
* Klasse [Console](../)
* Klasse [Decimal](../../decimal/)
* Klasse [String](../../string/)
* Klasse [TypeInfo](../../typeinfo/)
* Naamruimte [System](../../)
* Library [Aspose.Slides](../../../)