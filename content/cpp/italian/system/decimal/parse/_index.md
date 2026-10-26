---
title: Parse()
second_title: Riferimento API di Aspose.Slides per C++
description: Converte la rappresentazione testuale di un numero decimale in un'istanza equivalente della classe Decimal.
type: docs
weight: 469
url: /it/system/decimal/parse/
---
## Decimal::Parse(const String\&) metodo

Converte la rappresentazione testuale di un numero decimale in un'istanza equivalente della classe [Decimal](../).

```cpp
static Decimal System::Decimal::Parse(const String &s)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| s | const [String](../../string/)\& | La rappresentazione testuale di un numero |

### Valore restituito

Una nuova istanza della classe [Decimal](../) che rappresenta un valore equivalente a quello rappresentato dalla stringa specificata.

## Decimal::Parse(const String\&, Globalization::NumberStyles) metodo

Converte la rappresentazione testuale di un numero decimale in un'istanza equivalente della classe [Decimal](../) utilizzando lo stile specificato.

```cpp
static Decimal System::Decimal::Parse(const String &s, Globalization::NumberStyles styles)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| s | const [String](../../string/)\& | La rappresentazione testuale di un valore decimale da convertire |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | Una combinazione bitwise dei valori dell'enumerazione che fornisce informazioni aggiuntive su **s**, sugli elementi di stile che possono essere presenti in **s**, o sulla conversione da **s** a un oggetto [Decimal](../) |

### Valore restituito

Una nuova istanza della classe [Decimal](../) che rappresenta un valore equivalente a quello rappresentato dalla stringa specificata.

## Decimal::Parse(const String\&, const SharedPtr\<IFormatProvider\>\&) metodo

Converte la rappresentazione testuale di un numero decimale in un'istanza equivalente della classe [Decimal](../) utilizzando il provider di formato specificato.

```cpp
static Decimal System::Decimal::Parse(const String &s, const SharedPtr<IFormatProvider> &provider)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| s | const [String](../../string/)\& | La rappresentazione testuale di un valore decimale da convertire |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Provider di formato |

### Valore restituito

Una nuova istanza della classe [Decimal](../) che rappresenta un valore equivalente a quello rappresentato dalla stringa specificata.

## Decimal::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&) metodo

Converte la rappresentazione testuale di un numero decimale in un'istanza equivalente della classe [Decimal](../) utilizzando lo stile e il provider di formato specificati.

```cpp
static Decimal System::Decimal::Parse(const String &s, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| s | const [String](../../string/)\& | La rappresentazione testuale di un valore decimale da convertire |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | Una combinazione bitwise dei valori dell'enumerazione che fornisce informazioni aggiuntive su **s**, sugli elementi di stile che possono essere presenti in **s**, o sulla conversione da **s** a un oggetto [Decimal](../) |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Provider di formato |

### Valore restituito

Una nuova istanza della classe [Decimal](../) che rappresenta un valore equivalente a quello rappresentato dalla stringa specificata.

## Vedi anche

* Enum [NumberStyles](../../../system.globalization/numberstyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Classe [Decimal](../)
* Classe [String](../../string/)
* Classe [IFormatProvider](../../iformatprovider/)
* Spazio dei nomi [System](../../)
* Library [Aspose.Slides](../../../)