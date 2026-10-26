---
title: ToString()
second_title: Referência da API Aspose.Slides para C++
description: Análogo ao método Object.ToString() do C#. Permite converter objetos personalizados para string.
type: docs
weight: 79
url: /pt/system.net.http.headers/namevalueheadervalue/tostring/
---
## NameValueHeaderValue::ToString() const método


Analógico do método C# [Object.ToString()](../../../system/object/tostring/). Permite converter objetos personalizados para string.

```cpp
String System::Net::Http::Headers::NameValueHeaderValue::ToString() const override
```


### Valor de retorno

[String](../../../system/string/) representação conforme fornecida pela classe final.

## NameValueHeaderValue::ToString(System::SharedPtr\<ObjectCollection\<System::SharedPtr\<NameValueHeaderValue\>\>\>, char16_t, bool, System::SharedPtr\<Text::StringBuilder\>) método


Retorna uma representação em string da coleção das instâncias da classe NameValueHeaderValue.

```cpp
static void System::Net::Http::Headers::NameValueHeaderValue::ToString(System::SharedPtr<ObjectCollection<System::SharedPtr<NameValueHeaderValue>>> values, char16_t separator, bool leadingSeparator, System::SharedPtr<Text::StringBuilder> destination)
```


### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| values | [System::SharedPtr](../../../system/sharedptr/)\<[ObjectCollection](../../objectcollection/)\<[System::SharedPtr](../../../system/sharedptr/)\<[NameValueHeaderValue](../)\>\>\> | A coleção das instâncias da classe NameValueHeaderValue. |
| separator | char16_t | Um separador de string. |
| leadingSeparator | **bool** | O valor que indica se o separador de string deve ser adicionado antes do primeiro item da coleção. |
| destination | [System::SharedPtr](../../../system/sharedptr/)\<[Text::StringBuilder](../../../system.text/stringbuilder/)\> | Uma instância onde será atribuída a representação em string. |

## NameValueHeaderValue::ToString(System::SharedPtr\<ObjectCollection\<System::SharedPtr\<NameValueHeaderValue\>\>\>, char16_t, bool) método


Retorna uma representação em string da coleção das instâncias da classe NameValueHeaderValue.

```cpp
static String System::Net::Http::Headers::NameValueHeaderValue::ToString(System::SharedPtr<ObjectCollection<System::SharedPtr<NameValueHeaderValue>>> values, char16_t separator, bool leadingSeparator)
```


### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| values | [System::SharedPtr](../../../system/sharedptr/)\<[ObjectCollection](../../objectcollection/)\<[System::SharedPtr](../../../system/sharedptr/)\<[NameValueHeaderValue](../)\>\>\> | A coleção das instâncias da classe NameValueHeaderValue. |
| separator | char16_t | Um separador de string. |
| leadingSeparator | **bool** | O valor que indica se o separador de string deve ser adicionado antes do primeiro item da coleção. |

### Valor de retorno

Uma representação em string da coleção das instâncias da classe NameValueHeaderValue.

## Ver Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [String](../../../system/string/)
* Class [NameValueHeaderValue](../)
* Class [ObjectCollection](../../objectcollection/)
* Class [StringBuilder](../../../system.text/stringbuilder/)
* Namespace [System::Net::Http::Headers](../../)
* Library [Aspose.Slides](../../../)