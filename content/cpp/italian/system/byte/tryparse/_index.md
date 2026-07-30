---
title: TryParse()
second_title: Riferimento API di Aspose.Slides per C++
description: Converte la stringa specificata contenente la rappresentazione testuale di un numero nell'intero senza segno a 8-bit equivalente.
type: docs
weight: 14
url: /it/system/byte/tryparse/
---
## Byte::TryParse(const String\&, uint8_t\&) metodo

Converte la stringa specificata contenente la rappresentazione testuale di un numero nell'intero senza segno a 8 bit equivalente.

```cpp
static bool System::Byte::TryParse(const String &value, uint8_t &result)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | const [String](../../string/)\& | La stringa da convertire. |
| result | **uint8_t**\& | Il riferimento a una variabile intera senza segno a 8 bit dove viene inserito il risultato della conversione. |

### Valore restituito

True se la conversione ha avuto successo, altrimenti - false.

## Byte::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&, uint8_t\&) metodo

Converte la stringa specificata contenente la rappresentazione testuale di un numero nell'intero senza segno a 8 bit equivalente utilizzando le informazioni di formattazione e lo stile del numero forniti.

```cpp
static bool System::Byte::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider, uint8_t &result)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | const [String](../../string/)\& | La stringa da convertire. |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | Una combinazione bitwise dei valori dell'enum NumberStyles che specifica lo stile consentito della rappresentazione testuale di un numero. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Un puntatore a un oggetto che contiene le informazioni di formattazione della stringa. |
| result | **uint8_t**\& | Il riferimento a una variabile intera senza segno a 8 bit dove viene inserito il risultato della conversione. |

### Valore restituito

True se la conversione ha avuto successo, altrimenti - false.

## Byte::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&, uint8_t\&) metodo

```cpp
static bool System::Byte::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture, uint8_t &result)
```

## Byte::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&, uint8_t\&) metodo

```cpp
static bool System::Byte::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi, uint8_t &result)
```

## Byte::TryParse(const String\&, Globalization::NumberStyles, std::nullptr_t, uint8_t\&) metodo

```cpp
static bool System::Byte::TryParse(const String &value, Globalization::NumberStyles styles, std::nullptr_t, uint8_t &result)
```

## Vedi anche

* Enum [NumberStyles](../../../system.globalization/numberstyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [String](../../string/)
* Class [Byte](../)
* Class [IFormatProvider](../../iformatprovider/)
* Class [CultureInfo](../../../system.globalization/cultureinfo/)
* Class [NumberFormatInfo](../../../system.globalization/numberformatinfo/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)