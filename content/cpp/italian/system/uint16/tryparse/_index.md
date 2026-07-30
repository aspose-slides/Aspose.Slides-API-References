---
title: TryParse()
second_title: Riferimento API di Aspose.Slides per C++
description: Converte la stringa specificata contenente la rappresentazione testuale di un numero nell'intero senza segno a 16-bit equivalente.
type: docs
weight: 14
url: /it/system/uint16/tryparse/
---
## UInt16::TryParse(const String\&, uint16_t\&) metodo

Converte la stringa specificata contenente la rappresentazione testuale di un numero nell'intero senza segno a 16 bit equivalente.

```cpp
static bool System::UInt16::TryParse(const String &value, uint16_t &result)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | const [String](../../string/)\& | La stringa da convertire. |
| result | **uint16_t**\& | Il riferimento a una variabile intera senza segno a 16 bit dove viene inserito il risultato della conversione. |

### Valore di ritorno

True se la conversione ha avuto successo, altrimenti - false.

## UInt16::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&, uint16_t\&) metodo

Converte la stringa specificata contenente la rappresentazione testuale di un numero nell'intero senza segno a 16 bit equivalente utilizzando le informazioni di formattazione fornite e lo stile numerico.

```cpp
static bool System::UInt16::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider, uint16_t &result)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | const [String](../../string/)\& | La stringa da convertire. |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | Una combinazione bitwise dei valori dell'enumerazione NumberStyles che specifica lo stile consentito della rappresentazione testuale di un numero. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Un puntatore a un oggetto che contiene le informazioni sul formato della stringa. |
| result | **uint16_t**\& | Il riferimento a una variabile intera senza segno a 16 bit dove viene inserito il risultato della conversione. |

### Valore di ritorno

True se la conversione ha avuto successo, altrimenti - false.

## UInt16::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&, uint16_t\&) metodo

```cpp
static bool System::UInt16::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture, uint16_t &result)
```

## UInt16::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&, uint16_t\&) metodo

```cpp
static bool System::UInt16::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi, uint16_t &result)
```

## UInt16::TryParse(const String\&, Globalization::NumberStyles, std::nullptr_t, uint16_t\&) metodo

```cpp
static bool System::UInt16::TryParse(const String &value, Globalization::NumberStyles styles, std::nullptr_t, uint16_t &result)
```

## Vedi anche

* Enum [NumberStyles](../../../system.globalization/numberstyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Classe [String](../../string/)
* Classe [IFormatProvider](../../iformatprovider/)
* Classe [CultureInfo](../../../system.globalization/cultureinfo/)
* Classe [NumberFormatInfo](../../../system.globalization/numberformatinfo/)
* Struct [UInt16](../)
* Spazio dei nomi [System](../../)
* Library [Aspose.Slides](../../../)