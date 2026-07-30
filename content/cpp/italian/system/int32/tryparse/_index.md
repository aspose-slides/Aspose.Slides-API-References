---
title: TryParse()
second_title: Riferimento API di Aspose.Slides per C++
description: Converte la stringa specificata contenente la rappresentazione testuale di un numero nell'intero con segno a 32 bit equivalente.
type: docs
weight: 14
url: /it/system/int32/tryparse/
---
## Int32::TryParse(const String\&, int32_t\&) method


Converte la stringa specificata contenente la rappresentazione testuale di un numero nell’intero con segno a 32 bit equivalente.

```cpp
static bool System::Int32::TryParse(const String &value, int32_t &result)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | const [String](../../string/)\& | La stringa da convertire. |
| result | **int32_t**\& | Il riferimento a una variabile intera con segno a 32 bit in cui viene inserito il risultato della conversione. |

### Valore restituito

True se la conversione è riuscita, altrimenti - false.

## Int32::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&, int32_t\&) method


Converte la stringa specificata contenente la rappresentazione testuale di un numero nell’intero con segno a 32 bit equivalente, utilizzando le informazioni di formattazione e lo stile numerico forniti.

```cpp
static bool System::Int32::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider, int32_t &result)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | const [String](../../string/)\& | La stringa da convertire. |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | Una combinazione bitwise dei valori dell’enumerazione NumberStyles che specifica lo stile consentito della rappresentazione testuale di un numero. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Un puntatore a un oggetto che contiene le informazioni sul formato della stringa. |
| result | **int32_t**\& | Il riferimento a una variabile intera con segno a 32 bit in cui viene inserito il risultato della conversione. |

### Valore restituito

True se la conversione è riuscita, altrimenti - false.

## Int32::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&, int32_t\&) method




```cpp
static bool System::Int32::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture, int32_t &result)
```

## Int32::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&, int32_t\&) method




```cpp
static bool System::Int32::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi, int32_t &result)
```

## Int32::TryParse(const String\&, Globalization::NumberStyles, std::nullptr_t, int32_t\&) method




```cpp
static bool System::Int32::TryParse(const String &value, Globalization::NumberStyles styles, std::nullptr_t, int32_t &result)
```

## Vedi anche

* Enum [NumberStyles](../../../system.globalization/numberstyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [String](../../string/)
* Class [Int32](../)
* Class [IFormatProvider](../../iformatprovider/)
* Class [CultureInfo](../../../system.globalization/cultureinfo/)
* Class [NumberFormatInfo](../../../system.globalization/numberformatinfo/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)