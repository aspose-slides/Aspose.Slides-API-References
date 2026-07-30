---
title: TryParse()
second_title: Riferimento API di Aspose.Slides per C++
description: Converte la stringa specificata contenente la rappresentazione testuale di un numero nel valore a virgola mobile a precisione singola equivalente.
type: docs
weight: 14
url: /it/system/single/tryparse/
---
## Single::TryParse(const String\&, float\&) metodo

Converte la stringa specificata contenente la rappresentazione testuale di un numero nel valore a virgola mobile a precisione singola equivalente.

```cpp
static bool System::Single::TryParse(const String &value, float &result)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | const [String](../../string/)\& | La stringa da convertire. |
| result | **float**\& | Il riferimento a una variabile a virgola mobile a precisione singola dove viene inserito il risultato della conversione. |

### Valore di ritorno

True se la conversione è riuscita, altrimenti - false.

## Single::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&, float\&) metodo

Converte la stringa specificata contenente la rappresentazione testuale di un numero nel valore a virgola mobile a precisione singola equivalente usando le informazioni di formattazione fornite e lo stile numerico.

```cpp
static bool System::Single::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider, float &result)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | const [String](../../string/)\& | La stringa da convertire. |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | Una combinazione bitwise dei valori dell'enumerazione NumberStyles che specifica lo stile consentito della rappresentazione testuale di un numero. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Un puntatore a un oggetto che contiene le informazioni di formato della stringa. |
| result | **float**\& | Il riferimento a una variabile a virgola mobile a precisione singola dove viene inserito il risultato della conversione. |

### Valore di ritorno

True se la conversione è riuscita, altrimenti - false.

## Single::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&, float\&) metodo




```cpp
static bool System::Single::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture, float &result)
```

## Single::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&, float\&) metodo




```cpp
static bool System::Single::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi, float &result)
```

## Single::TryParse(const String\&, Globalization::NumberStyles, std::nullptr_t, float\&) metodo




```cpp
static bool System::Single::TryParse(const String &value, Globalization::NumberStyles styles, std::nullptr_t, float &result)
```

## Vedi anche

* Enum [NumberStyles](../../../system.globalization/numberstyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Classe [String](../../string/)
* Classe [IFormatProvider](../../iformatprovider/)
* Classe [CultureInfo](../../../system.globalization/cultureinfo/)
* Classe [NumberFormatInfo](../../../system.globalization/numberformatinfo/)
* Struct [Single](../)
* Spazio dei nomi [System](../../)
* Library [Aspose.Slides](../../../)