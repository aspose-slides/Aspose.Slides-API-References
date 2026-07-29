---
title: ToString()
second_title: Aspose.Slides för C++ API-referens
description: Konverterar alla värden i den angivna bytearrayen till deras hexadecimala strängrepresentation. Skiftläge för bokstäver som ska användas i hexadecimal notation och avskiljare som sätts in mellan varje par av intilliggande byte specificeras via motsvarande argument.
type: docs
weight: 157
url: /sv/system/bitconverter/tostring/
---
## BitConverter::ToString(const ArrayPtr\<uint8_t\>\&, bool, const String\&) metod


Konverterar alla värden i den angivna bytearrayen till deras hexadecimala strängrepresentation. Skiftläge för bokstäver som används i hexadecimal notation och avskiljare som sätts in mellan varje par av intilliggande byte anges via motsvarande argument.

```cpp
static String System::BitConverter::ToString(const ArrayPtr<uint8_t> &value, bool uppercase=1, const String &separator=u"-")
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | const [ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | [Array](../../array/) som innehåller byte att konvertera |
| uppercase | **bool** | Anger bokstavens skiftläge som ska användas i den resulterande hexadecimala representationen |
| separator | const [String](../../string/)\& | En sträng som används som avskiljare som sätts in mellan varje par av intilliggande byte i den resulterande strängen |

### Returvärde

[String](../../string/) som innehåller den hexadecimala representationen av den angivna bytearrayen

## BitConverter::ToString(const ArrayPtr\<uint8_t\>\&, int) metod


Konverterar värdena i den angivna bytearrayen till deras hexadecimala strängrepresentation med start vid angivet index.

```cpp
static String System::BitConverter::ToString(const ArrayPtr<uint8_t> &value, int startIndex)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | const [ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | [Array](../../array/) som innehåller byte att konvertera |
| startIndex | int | [Index](../../index/) i den angivna arrayen där konverteringen ska börja |

### Returvärde

[String](../../string/) som innehåller den hexadecimala representationen av det angivna intervallet av element i den angivna arrayen

## BitConverter::ToString(const ArrayPtr\<uint8_t\>\&, int, int) metod


Konverterar ett intervall av värden i den angivna bytearrayen till deras hexadecimala strängrepresentation.

```cpp
static String System::BitConverter::ToString(const ArrayPtr<uint8_t> &value, int startIndex, int length)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | const [ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | [Array](../../array/) som innehåller byte att konvertera |
| startIndex | int | [Index](../../index/) i den angivna arrayen där intervallet av bytearrayens element att konvertera börjar |
| length | int | Längden på intervallet av bytearrayens element att konvertera |

### Returvärde

[String](../../string/) som innehåller den hexadecimala representationen av det angivna intervallet av element i den angivna arrayen

## Se även

* Typedef [ArrayPtr](../../arrayptr/)
* Klass [String](../../string/)
* Klass [BitConverter](../)
* Namnrymd [System](../../)
* Bibliotek [Aspose.Slides](../../../)