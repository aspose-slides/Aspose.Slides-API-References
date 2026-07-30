---
title: ToString()
second_title: Riferimento API di Aspose.Slides per C++
description: Analogo del metodo C# Object.ToString(). Consente di convertire oggetti personalizzati in stringa.
type: docs
weight: 79
url: /it/system.net.http.headers/namevalueheadervalue/tostring/
---
## NameValueHeaderValue::ToString() const method

Analogo del metodo C# [Object.ToString()](../../../system/object/tostring/). Consente di convertire oggetti personalizzati in stringa.

```cpp
String System::Net::Http::Headers::NameValueHeaderValue::ToString() const override
```

### Valore di ritorno

[String](../../../system/string/) representation as provided by final class.

## NameValueHeaderValue::ToString(System::SharedPtr\<ObjectCollection\<System::SharedPtr\<NameValueHeaderValue\>\>\>, char16_t, bool, System::SharedPtr\<Text::StringBuilder\>) method

Restituisce una rappresentazione stringa della collezione delle istanze della classe NameValueHeaderValue.

```cpp
static void System::Net::Http::Headers::NameValueHeaderValue::ToString(System::SharedPtr<ObjectCollection<System::SharedPtr<NameValueHeaderValue>>> values, char16_t separator, bool leadingSeparator, System::SharedPtr<Text::StringBuilder> destination)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| values | [System::SharedPtr](../../../system/sharedptr/)\<[ObjectCollection](../../objectcollection/)\<[System::SharedPtr](../../../system/sharedptr/)\<[NameValueHeaderValue](../)\>\>\> | La collezione delle istanze della classe NameValueHeaderValue. |
| separator | char16_t | Un separatore di stringa. |
| leadingSeparator | **bool** | Il valore che indica se il separatore di stringa deve essere aggiunto prima del primo elemento della collezione. |
| destination | [System::SharedPtr](../../../system/sharedptr/)\<[Text::StringBuilder](../../../system.text/stringbuilder/)\> | Un'istanza a cui sarà assegnata una rappresentazione stringa. |

## NameValueHeaderValue::ToString(System::SharedPtr\<ObjectCollection\<System::SharedPtr\<NameValueHeaderValue\>\>\>, char16_t, bool) method

Restituisce una rappresentazione stringa della collezione delle istanze della classe NameValueHeaderValue.

```cpp
static String System::Net::Http::Headers::NameValueHeaderValue::ToString(System::SharedPtr<ObjectCollection<System::SharedPtr<NameValueHeaderValue>>> values, char16_t separator, bool leadingSeparator)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| values | [System::SharedPtr](../../../system/sharedptr/)\<[ObjectCollection](../../objectcollection/)\<[System::SharedPtr](../../../system/sharedptr/)\<[NameValueHeaderValue](../)\>\>\> | La collezione delle istanze della classe NameValueHeaderValue. |
| separator | char16_t | Un separatore di stringa. |
| leadingSeparator | **bool** | Il valore che indica se il separatore di stringa deve essere aggiunto prima del primo elemento della collezione. |

### Valore di ritorno

Una rappresentazione stringa della collezione delle istanze della classe NameValueHeaderValue.

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [String](../../../system/string/)
* Classe [NameValueHeaderValue](../)
* Classe [ObjectCollection](../../objectcollection/)
* Classe [StringBuilder](../../../system.text/stringbuilder/)
* Namespace [System::Net::Http::Headers](../../)
* Library [Aspose.Slides](../../../)