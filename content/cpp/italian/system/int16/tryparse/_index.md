---
title: TryParse()
second_title: Riferimento API di Aspose.Slides per C++
description: Converte la stringa specificata contenente la rappresentazione testuale di un numero nell'intero con segno a 16-bit equivalente.
type: docs
weight: 14
url: /it/system/int16/tryparse/
---
## Int16::TryParse(const String&, int16_t&) metodo


Converte la stringa specificata contenente la rappresentazione testuale di un numero nell'intero con segno a 16 bit equivalente.

```cpp
static bool System::Int16::TryParse(const String &value, int16_t &result)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | const [String](../../string/)\& | La stringa da convertire. |
| result | **int16_t**\& | Il riferimento a una variabile intera con segno a 16 bit dove viene inserito il risultato della conversione. |

### Valore restituito

True se la conversione è riuscita, altrimenti - false.

## Int16::TryParse(const String&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&, int16_t&) metodo


Converte la stringa specificata contenente la rappresentazione testuale di un numero nell'intero con segno a 16 bit equivalente utilizzando le informazioni di formattazione e lo stile numerico forniti.

```cpp
static bool System::Int16::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider, int16_t &result)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | const [String](../../string/)\& | La stringa da convertire. |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | Una combinazione bitwise dei valori dell'enumerazione NumberStyles che specifica lo stile consentito della rappresentazione testuale di un numero. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Un puntatore a un oggetto che contiene le informazioni sul formato della stringa. |
| result | **int16_t**\& | Il riferimento a una variabile intera con segno a 16 bit dove viene inserito il risultato della conversione. |

### Valore restituito

True se la conversione è riuscita, altrimenti - false.

## Int16::TryParse(const String&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&, int16_t&) metodo




```cpp
static bool System::Int16::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture, int16_t &result)
```

## Int16::TryParse(const String&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&, int16_t&) metodo




```cpp
static bool System::Int16::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi, int16_t &result)
```

## Int16::TryParse(const String&, Globalization::NumberStyles, std::nullptr_t, int16_t&) metodo




```cpp
static bool System::Int16::TryParse(const String &value, Globalization::NumberStyles styles, std::nullptr_t, int16_t &result)
```

## Vedi anche

* Enum [NumberStyles](../../../system.globalization/numberstyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Classe [String](../../string/)
* Classe [Int16](../)
* Classe [IFormatProvider](../../iformatprovider/)
* Classe [CultureInfo](../../../system.globalization/cultureinfo/)
* Classe [NumberFormatInfo](../../../system.globalization/numberformatinfo/)
* Spazio dei nomi [System](../../)
* Library [Aspose.Slides](../../../)