---
title: LastIndexOfAny()
second_title: Aspose.Slides för C++ API-referens
description: Söker efter något av de överförda tecknen i hela strängen baklänges. Jämför det sista tecknet i strängen med alla tecken i anyOf, sedan jämför det föregående och så vidare. Returnerar index för den första matchen som hittas.
type: docs
weight: 664
url: /sv/system/string/lastindexofany/
---
## String::LastIndexOfAny(const ArrayPtr\<char_t\>\&) const method

Söker efter någon av de angivna tecknen i hela strängen baklänges. Jämför det sista tecknet i strängen med alla tecken i anyOf, sedan jämför det föregående och så vidare. Returnerar index för den första matchen som hittas.

```cpp
int System::String::LastIndexOfAny(const ArrayPtr<char_t> &anyOf) const
```

### Argument

| Parameter | Type | Description |
| --- | --- | --- |
| anyOf | const [ArrayPtr](../../arrayptr/)\<char_t\>\& | [Array](../../array/) av tecken att söka efter. Ordningen spelar ingen roll. |

### Returvärde

[Index](../../index/) av det sista matchande tecknet eller -1 om det inte hittas.

## String::LastIndexOfAny(const ArrayPtr\<char_t\>\&, int32_t) const method

Söker efter någon av de angivna tecknen i en delsträng baklänges. Jämför det sista tecknet i strängen med alla tecken i anyOf, sedan jämför det föregående och så vidare. Returnerar index för den första matchen som hittas.

```cpp
int System::String::LastIndexOfAny(const ArrayPtr<char_t> &anyOf, int32_t startindex) const
```

### Argument

| Parameter | Type | Description |
| --- | --- | --- |
| anyOf | const [ArrayPtr](../../arrayptr/)\<char_t\>\& | [Array](../../array/) av tecken att söka efter. Ordningen spelar ingen roll. |
| startindex | **int32_t** | [Index](../../index/) för att börja söka från. |

### Returvärde

[Index](../../index/) av det sista matchande tecknet eller -1 om det inte hittas.

## String::LastIndexOfAny(const ArrayPtr\<char_t\>\&, int32_t, int32_t) const method

Söker efter någon av de angivna tecknen i en delsträng baklänges. Jämför det sista tecknet i strängen med alla tecken i anyOf, sedan jämför det föregående och så vidare. Returnerar index för den första matchen som hittas.

```cpp
int System::String::LastIndexOfAny(const ArrayPtr<char_t> &anyOf, int32_t startindex, int32_t count) const
```

### Argument

| Parameter | Type | Description |
| --- | --- | --- |
| anyOf | const [ArrayPtr](../../arrayptr/)\<char_t\>\& | [Array](../../array/) av tecken att söka efter. Ordningen spelar ingen roll. |
| startindex | **int32_t** | [Index](../../index/) för att börja söka från. |
| count | **int32_t** | Antal tecken att gå igenom. |

### Returvärde

[Index](../../index/) av det sista matchande tecknet eller -1 om det inte hittas.

## Se också

* Typedef [ArrayPtr](../../arrayptr/)
* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)