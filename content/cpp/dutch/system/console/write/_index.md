---
title: Write()
second_title: Aspose.Slides voor C++ API-referentie
description: Schrijft de tekenreeksrepresentatie van het opgegeven object naar de standaard uitvoerstroom.
type: docs
weight: 1
url: /nl/system/console/write/
---
## Console::Write(const SharedPtr\<T\>\&) methode


Schrijft de tekenreeksrepresentatie van het opgegeven object naar de standaard uitvoerstroom.

```cpp
template<class T> static void System::Console::Write(const SharedPtr<T> &object)
```


### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| T | Type van het object om uit te voeren |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| object | const [SharedPtr](../../sharedptr/)\<T\>\& | [Object](../../object/) om uit te voeren |


## Console::Write(bool) methode


Schrijft de tekenreeksrepresentatie van een bool-waarde naar de standaard uitvoerstroom.

```cpp
static void System::Console::Write(bool value)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | **bool** | De waarde om uit te voeren |


## Console::Write(char_t) methode


Schrijft de opgegeven tekenwaarde naar de standaard uitvoerstroom.

```cpp
static void System::Console::Write(char_t value)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | char_t | De waarde om uit te voeren |


## Console::Write(const ArrayPtr\<char_t\>\&) methode


Schrijft de tekenreeksrepresentatie van de opgegeven tekenarray naar de standaard uitvoerstroom.

```cpp
static void System::Console::Write(const ArrayPtr<char_t> &buffer)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../arrayptr/)\<char_t\>\& | De array om uit te voeren |


## Console::Write(const Decimal\&) methode


Schrijft de tekenreeksrepresentatie van [Decimal](../../decimal/)-waarde naar de standaard uitvoerstroom.

```cpp
static void System::Console::Write(const Decimal &value)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | const [Decimal](../../decimal/)\& | De waarde om uit te voeren |


## Console::Write(double) methode


Schrijft de tekenreeksrepresentatie van een double-precisie floating-point-waarde naar de standaard uitvoerstroom.

```cpp
static void System::Console::Write(double value)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | **double** | De waarde om uit te voeren |


## Console::Write(float) methode


Schrijft de tekenreeksrepresentatie van een single-precisie floating-point-waarde naar de standaard uitvoerstroom.

```cpp
static void System::Console::Write(float value)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | **float** | De waarde om uit te voeren |


## Console::Write(int32_t) methode


Schrijft de tekenreeksrepresentatie van een 32-bit gehele-getalwaarde naar de standaard uitvoerstroom.

```cpp
static void System::Console::Write(int32_t value)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | **int32_t** | De waarde om uit te voeren |


## Console::Write(int64_t) methode


Schrijft de tekenreeksrepresentatie van een 64-bit gehele-getalwaarde naar de standaard uitvoerstroom.

```cpp
static void System::Console::Write(int64_t value)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | **int64_t** | De waarde om uit te voeren |


## Console::Write(const String\&) methode


Schrijft het opgegeven string-object naar de standaard uitvoerstroom.

```cpp
static void System::Console::Write(const String &value)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | const [String](../../string/)\& | Het string-object om uit te voeren |


## Console::Write(const char_t *) methode


Schrijft de opgegeven c-string naar de standaard uitvoerstroom.

```cpp
static void System::Console::Write(const char_t *value)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | const char_t * | De c-string om uit te voeren |


## Console::Write(const TypeInfo\&) methode


Schrijft de tekenreeksrepresentatie van [TypeInfo](../../typeinfo/)-waarde naar de standaard uitvoerstroom.

```cpp
static void System::Console::Write(const TypeInfo &value)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | const [TypeInfo](../../typeinfo/)\& | De waarde om uit te voeren |


## Console::Write(uint32_t) methode


Schrijft de tekenreeksrepresentatie van een unsigned 32-bit gehele-getalwaarde naar de standaard uitvoerstroom.

```cpp
static void System::Console::Write(uint32_t value)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | **uint32_t** | De waarde om uit te voeren |


## Console::Write(uint64_t) methode


Schrijft de tekenreeksrepresentatie van een unsigned 64-bit gehele-getalwaarde naar de standaard uitvoerstroom.

```cpp
static void System::Console::Write(uint64_t value)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | **uint64_t** | De waarde om uit te voeren |


## Console::Write(const ArrayPtr\<char_t\>\&, int32_t, int32_t) methode


Schrijft de tekenreeksrepresentatie van het opgegeven bereik van de opgegeven tekenarray naar de standaard uitvoerstroom.

```cpp
static void System::Console::Write(const ArrayPtr<char_t> &buffer, int32_t index, int32_t count)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../arrayptr/)\<char_t\>\& | De tekenarray |
| index | **int32_t** | De index in de array waar het uit te voeren bereik begint |
| count | **int32_t** | Het aantal elementen in het uit te voeren bereik |


## Console::Write(const String\&, Args\&&...) methode


Schrijft de tekenreeksrepresentatie van de opgegeven argumenten, geformatteerd volgens het opgegeven formaat, naar de standaard uitvoerstroom.

```cpp
template<class...> static void System::Console::Write(const String &format, Args &&... args)
```


### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| De | typen van de waarden die moeten worden uitgegeven |


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| format | const [String](../../string/)\& | Het string-formaat |
| args | Args\&&... | De waarden om uit te voeren |


## Console::Write(const char *) methode




```cpp
static void System::Console::Write(const char *)=delete
```

## Zie ook

* Typedef [SharedPtr](../../sharedptr/)
* Typedef [ArrayPtr](../../arrayptr/)
* Class [Console](../)
* Class [Decimal](../../decimal/)
* Class [String](../../string/)
* Class [TypeInfo](../../typeinfo/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)