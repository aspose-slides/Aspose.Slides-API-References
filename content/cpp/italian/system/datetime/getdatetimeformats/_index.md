---
title: GetDateTimeFormats()
second_title: Riferimento API di Aspose.Slides per C++
description: Restituisce un array di stringhe in cui ogni elemento è la rappresentazione testuale dell'oggetto corrente formattato con uno dei formati standard di data e ora.
type: docs
weight: 547
url: /it/system/datetime/getdatetimeformats/
---
## DateTime::GetDateTimeFormats() const method


Restituisce un array di stringhe in cui ogni elemento è la rappresentazione testuale dell'oggetto corrente formattata con uno dei formati standard di data e ora.

```cpp
ArrayPtr<String> System::DateTime::GetDateTimeFormats() const
```

## DateTime::GetDateTimeFormats(char_t) const method


Restituisce un array di stringhe in cui ogni elemento è la rappresentazione testuale dell'oggetto corrente formattata con lo specificatore di formato di data e ora standard specificato.

```cpp
ArrayPtr<String> System::DateTime::GetDateTimeFormats(char_t format) const
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| format | char_t | Specificatore di formato di data e ora standard. |

## DateTime::GetDateTimeFormats(const SharedPtr\<IFormatProvider\>\&) const method


Restituisce un array di stringhe in cui ogni elemento è la rappresentazione testuale dell'oggetto corrente formattata con uno dei formati standard di data e ora e con il provider di formato specificato.

```cpp
ArrayPtr<String> System::DateTime::GetDateTimeFormats(const SharedPtr<IFormatProvider> &provider) const
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Fornitore di formato. |

## DateTime::GetDateTimeFormats(char_t, const SharedPtr\<IFormatProvider\>\&) const method


Restituisce un array di stringhe in cui ogni elemento è la rappresentazione testuale dell'oggetto corrente formattata con lo specificatore di formato di data e ora standard specificato e con il provider di formato.

```cpp
ArrayPtr<String> System::DateTime::GetDateTimeFormats(char_t format, const SharedPtr<IFormatProvider> &provider) const
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| format | char_t | Specificatore di formato di data e ora standard. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Fornitore di formato. |

## Vedi anche

* Typedef [ArrayPtr](../../arrayptr/)
* Typedef [SharedPtr](../../sharedptr/)
* Classe [String](../../string/)
* Classe [DateTime](../)
* Classe [IFormatProvider](../../iformatprovider/)
* Spazio dei nomi [System](../../)
* Libreria [Aspose.Slides](../../../)