---
title: IndexOfAny()
second_title: Aspose.Slides för C++ API-referens
description: Framåtsökning av tecken.
type: docs
weight: 638
url: /sv/system/string/indexofany/
---
## String::IndexOfAny(char_t, int) const metod


Framåtsökning av tecken.

```cpp
int System::String::IndexOfAny(char_t c, int startIndex=0) const
```


### Argument

| Parameter | Type | Description |
| --- | --- | --- |
| c | char_t | Tecken att söka efter. |
| startIndex | int | [Index](../../index/) för att starta sökningen vid. |

### Returvärde

[Index](../../index/) för den första teckenpositionen sedan startIndex eller -1 om ej hittad.

## String::IndexOfAny(const String\&, int) const metod


Söker därför efter alla tecken i str i detta objekt. Om det första tecknet hittas returneras dess position, annars fortsätter sökningen efter det andra och så vidare.

```cpp
int System::String::IndexOfAny(const String &str, int startIndex=0) const
```


### Argument

| Parameter | Type | Description |
| --- | --- | --- |
| str | const [String](../)\& | [String](../) för tecken att söka efter. Ordning av tecken spelar roll. |
| startIndex | int | Position för att starta sökningen från. |

### Returvärde

[Index](../../index/) för första hittade tecken eller -1 om inget hittas.

## String::IndexOfAny(const ArrayPtr\<char_t\>\&) const metod


Söker efter något av de överförda tecknen i hela strängen. Jämför första strängtecknet med alla tecken i anyOf, sedan jämförs nästa och så vidare. Returnerar index för det första som matchar något av måltecknen.

```cpp
int System::String::IndexOfAny(const ArrayPtr<char_t> &anyOf) const
```


### Argument

| Parameter | Type | Description |
| --- | --- | --- |
| anyOf | const [ArrayPtr](../../arrayptr/)\<char_t\>\& | [Array](../../array/) för tecken att söka efter. Ordning spelar ingen roll. |

### Returvärde

[Index](../../index/) för det första matchande tecknet eller -1 om ej hittat.

## String::IndexOfAny(const ArrayPtr\<char_t\>\&, int32_t) const metod


Söker efter något av de överförda tecknen i delsträngen. Jämför första strängtecknet med alla tecken i anyOf, sedan jämförs nästa och så vidare. Returnerar index för det första som matchar något av måltecknen.

```cpp
int System::String::IndexOfAny(const ArrayPtr<char_t> &anyOf, int32_t startindex) const
```


### Argument

| Parameter | Type | Description |
| --- | --- | --- |
| anyOf | const [ArrayPtr](../../arrayptr/)\<char_t\>\& | [Array](../../array/) för tecken att söka efter. Ordning spelar ingen roll. |
| startindex | **int32_t** | [Index](../../index/) för att starta sökningen från. |

### Returvärde

[Index](../../index/) för det första matchande tecknet eller -1 om ej hittat.

## String::IndexOfAny(const ArrayPtr\<char_t\>\&, int32_t, int32_t) const metod


Söker efter något av de överförda tecknen i delsträngen. Jämför första strängtecknet med alla tecken i anyOf, sedan jämförs nästa och så vidare. Returnerar index för det första som matchar något av måltecknen.

```cpp
int System::String::IndexOfAny(const ArrayPtr<char_t> &anyOf, int32_t startindex, int32_t count) const
```


### Argument

| Parameter | Type | Description |
| --- | --- | --- |
| anyOf | const [ArrayPtr](../../arrayptr/)\<char_t\>\& | [Array](../../array/) för tecken att söka efter. Ordning spelar ingen roll. |
| startindex | **int32_t** | [Index](../../index/) för att starta sökningen från. |
| count | **int32_t** | Antal tecken att söka igenom. |

### Returvärde

[Index](../../index/) för det första matchande tecknet eller -1 om ej hittat.

## Se även

* Typedef [ArrayPtr](../../arrayptr/)
* Klass [String](../)
* Namnrymd [System](../../)
* Library [Aspose.Slides](../../../)