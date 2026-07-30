---
title: ToDouble()
second_title: Riferimento API di Aspose.Slides per C++
description: Converte il valore booleano specificato in un numero a virgola mobile a doppia precisione equivalente.
type: docs
weight: 222
url: /it/system/convert/todouble/
---
## Convert::ToDouble(bool) metodo


Converte il valore booleano specificato in un numero a virgola mobile a doppia precisione equivalente.

```cpp
static constexpr double System::Convert::ToDouble(bool value)
```

## Convert::ToDouble(uint8_t) metodo


Converte l'intero senza segno a 8 bit specificato in un numero a virgola mobile a doppia precisione equivalente.

```cpp
static constexpr double System::Convert::ToDouble(uint8_t value)
```

## Convert::ToDouble(int8_t) metodo


Converte l'intero con segno a 8 bit specificato in un numero a virgola mobile a doppia precisione equivalente.

```cpp
static constexpr double System::Convert::ToDouble(int8_t value)
```

## Convert::ToDouble(uint16_t) metodo


Converte l'intero senza segno a 16 bit specificato in un numero a virgola mobile a doppia precisione equivalente.

```cpp
static constexpr double System::Convert::ToDouble(uint16_t value)
```

## Convert::ToDouble(int16_t) metodo


Converte l'intero con segno a 16 bit specificato in un numero a virgola mobile a doppia precisione equivalente.

```cpp
static constexpr double System::Convert::ToDouble(int16_t value)
```

## Convert::ToDouble(uint32_t) metodo


Converte l'intero senza segno a 32 bit specificato in un numero a virgola mobile a doppia precisione equivalente.

```cpp
static constexpr double System::Convert::ToDouble(uint32_t value)
```

## Convert::ToDouble(int32_t) metodo


Converte l'intero con segno a 32 bit specificato in un numero a virgola mobile a doppia precisione equivalente.

```cpp
static constexpr double System::Convert::ToDouble(int32_t value)
```

## Convert::ToDouble(uint64_t) metodo


Converte l'intero senza segno a 64 bit specificato in un numero a virgola mobile a doppia precisione equivalente.

```cpp
static constexpr double System::Convert::ToDouble(uint64_t value)
```

## Convert::ToDouble(int64_t) metodo


Converte l'intero con segno a 64 bit specificato in un numero a virgola mobile a doppia precisione equivalente.

```cpp
static constexpr double System::Convert::ToDouble(int64_t value)
```

## Convert::ToDouble(float) metodo


Converte il numero a precisione singola specificato in un numero a virgola mobile a doppia precisione equivalente.

```cpp
static constexpr double System::Convert::ToDouble(float value)
```

## Convert::ToDouble(double) metodo


Restituisce il numero double specificato.

```cpp
static constexpr double System::Convert::ToDouble(double value)
```

## Convert::ToDouble(const Decimal\&) metodo


Converte il numero decimale specificato in un numero a virgola mobile a doppia precisione equivalente.

```cpp
static double System::Convert::ToDouble(const Decimal &value)
```

## Convert::ToDouble(char_t) metodo


La conversione non è supportata. Lancia sempre InvalidCastException.

```cpp
static double System::Convert::ToDouble(char_t value)
```

## Convert::ToDouble(DateTime) metodo


La conversione non è supportata. Lancia sempre InvalidCastException.

```cpp
static double System::Convert::ToDouble(DateTime value)
```

## Convert::ToDouble(std::nullptr_t) metodo


Converte la stringa nulla specificata nel valore a virgola mobile a doppia precisione equivalente.

```cpp
static constexpr double System::Convert::ToDouble(std::nullptr_t)
```


### Valore di ritorno

Zero.

## Convert::ToDouble(const char_t *) metodo


Converte la c-string specificata contenente la rappresentazione testuale di un numero nel valore a virgola mobile a doppia precisione equivalente.

```cpp
static double System::Convert::ToDouble(const char_t *value)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | const char_t * | La c-string da convertire |

### Valore di ritorno

Il valore a virgola mobile a doppia precisione pari al numero rappresentato dalla c-string specificata

## Convert::ToDouble(const String\&) metodo


Converte la stringa specificata contenente la rappresentazione testuale di un numero nel valore a virgola mobile a doppia precisione equivalente.

```cpp
static double System::Convert::ToDouble(const String &value)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | const [String](../../string/)\& | La stringa da convertire |

### Valore di ritorno

Il valore a virgola mobile a doppia precisione pari al numero rappresentato dalla stringa specificata

## Convert::ToDouble(const String\&, const SharedPtr\<IFormatProvider\>\&) metodo


Converte la stringa specificata contenente la rappresentazione testuale di un numero nel valore a virgola mobile a doppia precisione equivalente utilizzando le informazioni di formattazione fornite.

```cpp
static double System::Convert::ToDouble(const String &value, const SharedPtr<IFormatProvider> &provider)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | const [String](../../string/)\& | La stringa da convertire |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Un puntatore a un oggetto che contiene le informazioni di formato della stringa |

### Valore di ritorno

Il valore a virgola mobile a doppia precisione pari al numero rappresentato dalla stringa specificata

## Convert::ToDouble(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) metodo




```cpp
static double System::Convert::ToDouble(const String &value, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Convert::ToDouble(const String\&, const SharedPtr\<Globalization::NumberFormatInfo\>\&) metodo




```cpp
static double System::Convert::ToDouble(const String &value, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Convert::ToDouble(const String\&, std::nullptr_t) metodo




```cpp
static double System::Convert::ToDouble(const String &value, std::nullptr_t)
```

## Convert::ToDouble(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&) metodo


Converte la stringa specificata contenente la rappresentazione testuale di un numero nel valore a virgola mobile a doppia precisione equivalente utilizzando le informazioni di formattazione fornite e lo stile numerico.

```cpp
static double System::Convert::ToDouble(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | const [String](../../string/)\& | La stringa da convertire |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | Una combinazione bitwise dei valori dell'enum NumberStyles che specifica lo stile consentito della rappresentazione testuale di un numero |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Un puntatore a un oggetto che contiene le informazioni di formato della stringa |

### Valore di ritorno

Il valore a virgola mobile a doppia precisione pari al numero rappresentato dalla stringa specificata

## Convert::ToDouble(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&) metodo




```cpp
static double System::Convert::ToDouble(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Convert::ToDouble(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&) metodo




```cpp
static double System::Convert::ToDouble(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Convert::ToDouble(const String\&, Globalization::NumberStyles, std::nullptr_t) metodo




```cpp
static double System::Convert::ToDouble(const String &value, Globalization::NumberStyles styles, std::nullptr_t=nullptr)
```

## Convert::ToDouble(const SharedPtr\<Object\>\&, const SharedPtr\<IFormatProvider\>\&) metodo


Converte il valore boxed specificato in un valore a virgola mobile a doppia precisione. Se il tipo del valore boxed è [String](../../string/), il formato stringa specificato viene usato durante la conversione.

```cpp
static double System::Convert::ToDouble(const SharedPtr<Object> &obj, const SharedPtr<IFormatProvider> &provider=nullptr)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| obj | const [SharedPtr](../../sharedptr/)\<[Object](../../object/)\>\& | Il puntatore condiviso all'oggetto che incapsula il valore da convertire |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Il formato stringa da utilizzare se il tipo del valore boxed è [String](../../string/) |

### Valore di ritorno

Un valore a virgola mobile a doppia precisione equivalente al valore boxed specificato

## Vedi anche

* Enum [NumberStyles](../../../system.globalization/numberstyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [Decimal](../../decimal/)
* Class [DateTime](../../datetime/)
* Class [String](../../string/)
* Class [IFormatProvider](../../iformatprovider/)
* Class [CultureInfo](../../../system.globalization/cultureinfo/)
* Class [NumberFormatInfo](../../../system.globalization/numberformatinfo/)
* Class [Object](../../object/)
* Struct [Convert](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)