---
title: ToString()
second_title: Riferimento API di Aspose.Slides per C++
description: Restituisce la rappresentazione stringa del valore di data e ora rappresentato dall'oggetto corrente utilizzando le convenzioni di formattazione definite dalla cultura corrente.
type: docs
weight: 482
url: /it/system/datetime/tostring/
---
## DateTime::ToString() const metodo


Restituisce la rappresentazione stringa del valore di data e ora rappresentato dall'oggetto corrente utilizzando le convenzioni di formattazione definite dalla cultura corrente.

```cpp
String System::DateTime::ToString() const
```


### Valore restituito

La rappresentazione stringa del valore rappresentato dall'oggetto corrente

## DateTime::ToString(const String\&) const metodo


Restituisce una rappresentazione stringa del valore di data e ora rappresentato dall'oggetto corrente utilizzando il formato specificato e le convenzioni di formattazione definite dalla cultura corrente.

```cpp
String System::DateTime::ToString(const String &format) const
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| format | const [String](../../string/)\& | Una stringa di formato |

### Valore restituito

La rappresentazione stringa del valore rappresentato dall'oggetto corrente formattata secondo il formato definito da **format** e dalla cultura corrente.

## DateTime::ToString(const SharedPtr\<IFormatProvider\>\&) const metodo


Restituisce una rappresentazione stringa del valore di data e ora rappresentato dall'oggetto corrente utilizzando le informazioni di formato specificate.

```cpp
String System::DateTime::ToString(const SharedPtr<IFormatProvider> &provider) const
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Un oggetto che rappresenta le informazioni di formato |

### Valore restituito

La rappresentazione stringa del valore rappresentato dall'oggetto corrente formattata secondo le informazioni di formato fornite da **formatProvider**.

## DateTime::ToString(const SharedPtr\<Globalization::CultureInfo\>\&) const metodo




```cpp
String System::DateTime::ToString(const SharedPtr<Globalization::CultureInfo> &culture) const
```

## DateTime::ToString(const SharedPtr\<Globalization::DateTimeFormatInfo\>\&) const metodo




```cpp
String System::DateTime::ToString(const SharedPtr<Globalization::DateTimeFormatInfo> &dtfi) const
```

## DateTime::ToString(std::nullptr_t) const metodo




```cpp
String System::DateTime::ToString(std::nullptr_t) const
```

## DateTime::ToString(const String\&, const SharedPtr\<IFormatProvider\>\&) const metodo


Restituisce una rappresentazione stringa del valore di data e ora rappresentato dall'oggetto corrente utilizzando le informazioni di formato specificate.

```cpp
String System::DateTime::ToString(const String &format, const SharedPtr<IFormatProvider> &provider) const
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| format | const [String](../../string/)\& | Una stringa di formato |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Un oggetto che rappresenta le informazioni di formato |

### Valore restituito

La rappresentazione stringa del valore rappresentato dall'oggetto corrente formattata secondo le informazioni di formato fornite da **provider** e la stringa di formato **format**.

## DateTime::ToString(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) const metodo




```cpp
String System::DateTime::ToString(const String &format, const SharedPtr<Globalization::CultureInfo> &culture) const
```

## DateTime::ToString(const String\&, const SharedPtr\<Globalization::DateTimeFormatInfo\>\&) const metodo




```cpp
String System::DateTime::ToString(const String &format, const SharedPtr<Globalization::DateTimeFormatInfo> &dtfi) const
```

## DateTime::ToString(const String\&, std::nullptr_t) const metodo 




```cpp
String System::DateTime::ToString(const String &format, std::nullptr_t) const
```

## Vedi anche

* Typedef [SharedPtr](../../sharedptr/)
* Classe [String](../../string/)
* Classe [DateTime](../)
* Classe [IFormatProvider](../../iformatprovider/)
* Classe [CultureInfo](../../../system.globalization/cultureinfo/)
* Classe [DateTimeFormatInfo](../../../system.globalization/datetimeformatinfo/)
* Namespace [System](../../)
* Libreria [Aspose.Slides](../../../)