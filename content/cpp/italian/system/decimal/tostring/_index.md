---
title: ToString()
second_title: Aspose.Slides per C++ Riferimento API
description: Restituisce la rappresentazione testuale del valore rappresentato dall'oggetto.
type: docs
weight: 352
url: /it/system/decimal/tostring/
---
## Decimal::ToString() const metodo


Restituisce la rappresentazione testuale del valore rappresentato dall'oggetto.

```cpp
String System::Decimal::ToString() const
```

## Decimal::ToString(const SharedPtr\<IFormatProvider\>\&) const metodo


Converte l'oggetto corrente in una stringa utilizzando le informazioni di formattazione specifiche della cultura.

```cpp
String System::Decimal::ToString(const SharedPtr<IFormatProvider> &provider) const
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | L'oggetto [IFormatProvider](../../iformatprovider/) che fornisce le informazioni di formattazione specifiche della cultura. |

### Valore restituito

La rappresentazione testuale dell'oggetto corrente.

## Decimal::ToString(const SharedPtr\<Globalization::CultureInfo\>\&) const metodo




```cpp
String System::Decimal::ToString(const SharedPtr<Globalization::CultureInfo> &culture) const
```

## Decimal::ToString(const SharedPtr\<Globalization::NumberFormatInfo\>\&) const metodo




```cpp
String System::Decimal::ToString(const SharedPtr<Globalization::NumberFormatInfo> &nfi) const
```

## Decimal::ToString(const Decimal\&, std::nullptr_t) const metodo




```cpp
String System::Decimal::ToString(const Decimal &value, std::nullptr_t) const
```

## Decimal::ToString(const String\&, const SharedPtr\<IFormatProvider\>\&) const metodo


Converte l'oggetto corrente nella sua rappresentazione testuale utilizzando il formato stringa specificato e le informazioni di formattazione specifiche della cultura fornite dall'oggetto [IFormatProvider](../../iformatprovider/) specificato.

```cpp
String System::Decimal::ToString(const String &format, const SharedPtr<IFormatProvider> &provider) const
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| format | const [String](../../string/)\& | Il formato stringa. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | L'oggetto [IFormatProvider](../../iformatprovider/) che fornisce le informazioni di formattazione specifiche della cultura. |

### Valore restituito

La rappresentazione testuale dell'oggetto corrente.

## Decimal::ToString(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) const metodo




```cpp
String System::Decimal::ToString(const String &format, const SharedPtr<Globalization::CultureInfo> &culture) const
```

## Decimal::ToString(const String\&, const SharedPtr\<Globalization::NumberFormatInfo\>\&) const metodo




```cpp
String System::Decimal::ToString(const String &format, const SharedPtr<Globalization::NumberFormatInfo> &nfi) const
```

## Decimal::ToString(const String\&, std::nullptr_t) const metodo




```cpp
String System::Decimal::ToString(const String &format, std::nullptr_t=nullptr) const
```

## Vedi anche

* Typedef [SharedPtr](../../sharedptr/)
* Classe [String](../../string/)
* Classe [Decimal](../)
* Classe [IFormatProvider](../../iformatprovider/)
* Classe [CultureInfo](../../../system.globalization/cultureinfo/)
* Classe [NumberFormatInfo](../../../system.globalization/numberformatinfo/)
* Spazio dei nomi [System](../../)
* Libreria [Aspose.Slides](../../../)