---
title: Parse()
second_title: Riferimento API Aspose.Slides per C++
description: Converte la stringa specificata contenente la rappresentazione testuale di un numero nel valore a virgola mobile a precisione singola equivalente.
type: docs
weight: 1
url: /it/system/single/parse/
---
## Single::Parse(const String\&) metodo

Converte la stringa specificata contenente la rappresentazione testuale di un numero nel valore a virgola mobile a precisione singola equivalente.

```cpp
static float System::Single::Parse(const String &value)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | const [String](../../string/)\& | La stringa da convertire. |

### Valore di ritorno

Il valore a virgola mobile a precisione singola equivalente al numero rappresentato dalla stringa specificata.

## Single::Parse(const String\&, const SharedPtr\<IFormatProvider\>\&) metodo

Converte la stringa specificata contenente la rappresentazione testuale di un numero nel valore a virgola mobile a precisione singola equivalente utilizzando le informazioni di formattazione fornite.

```cpp
static float System::Single::Parse(const String &value, const SharedPtr<IFormatProvider> &provider)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | const [String](../../string/)\& | La stringa da convertire. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Un puntatore a un oggetto che contiene le informazioni di formattazione della stringa. |

### Valore di ritorno

Il valore a virgola mobile a precisione singola equivalente al numero rappresentato dalla stringa specificata.

## Single::Parse(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) metodo




```cpp
static float System::Single::Parse(const String &value, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Single::Parse(const String\&, const SharedPtr\<Globalization::NumberFormatInfo\>\&) metodo




```cpp
static float System::Single::Parse(const String &value, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Single::Parse(const String\&, std::nullptr_t) metodo




```cpp
static float System::Single::Parse(const String &value, std::nullptr_t)
```

## Single::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&) metodo

Converte la stringa specificata contenente la rappresentazione testuale di un numero nel valore a virgola mobile a precisione singola equivalente utilizzando le informazioni di formattazione e lo stile numerico forniti.

```cpp
static float System::Single::Parse(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | const [String](../../string/)\& | La stringa da convertire. |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | Una combinazione bitwise dei valori dell'enum NumberStyles che specifica lo stile consentito della rappresentazione testuale di un numero. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Un puntatore a un oggetto che contiene le informazioni di formattazione della stringa. |

### Valore di ritorno

Il valore a virgola mobile a precisione singola equivalente al numero rappresentato dalla stringa specificata.

## Single::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&) metodo




```cpp
static float System::Single::Parse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Single::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&) metodo




```cpp
static float System::Single::Parse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Single::Parse(const String\&, Globalization::NumberStyles, std::nullptr_t) metodo




```cpp
static float System::Single::Parse(const String &value, Globalization::NumberStyles styles, std::nullptr_t=nullptr)
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