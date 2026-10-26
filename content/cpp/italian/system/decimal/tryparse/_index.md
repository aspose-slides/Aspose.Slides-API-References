---
title: TryParse()
second_title: Riferimento API di Aspose.Slides per C++
description: Converte la stringa specificata contenente la rappresentazione testuale di un numero nel valore Decimal equivalente.
type: docs
weight: 482
url: /it/system/decimal/tryparse/
---
## Decimal::TryParse(const String\&, Decimal\&) metodo


Converte la stringa specificata contenente la rappresentazione testuale di un numero nel valore [Decimal](../) equivalente.

```cpp
static bool System::Decimal::TryParse(const String &value, Decimal &result)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | const [String](../../string/)\& | La stringa da convertire |
| result | [Decimal](../)\& | Il riferimento a una variabile [Decimal](../) dove viene inserito il risultato della conversione |

### Valore restituito

True se la conversione ha avuto successo, altrimenti - false

## Decimal::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&, Decimal\&) metodo


Converte la stringa specificata contenente la rappresentazione testuale di un numero nel valore [Decimal](../) equivalente utilizzando le informazioni di formattazione fornite e lo stile del numero.

```cpp
static bool System::Decimal::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider, Decimal &result)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | const [String](../../string/)\& | La stringa da convertire |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | Una combinazione bitwise dei valori dell'enumerazione NumberStyles che specifica lo stile consentito della rappresentazione testuale di un numero |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Un puntatore a un oggetto che contiene le informazioni di formattazione della stringa |
| result | [Decimal](../)\& | Un argomento di output; contiene il risultato della conversione |

### Valore restituito

True se la conversione ha avuto successo, altrimenti - false

## Vedi anche

* Enum [NumberStyles](../../../system.globalization/numberstyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Classe [String](../../string/)
* Classe [Decimal](../)
* Classe [IFormatProvider](../../iformatprovider/)
* Spazio dei nomi [System](../../)
* Library [Aspose.Slides](../../../)