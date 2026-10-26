---
title: ToString()
second_title: Referencia de la API de Aspose.Slides para C++
description: Análogo del método Object.ToString() de C#. Permite convertir objetos personalizados a cadena.
type: docs
weight: 79
url: /es/system.net.http.headers/namevalueheadervalue/tostring/
---
## NameValueHeaderValue::ToString() const método


Análogo del método [Object.ToString()](../../../system/object/tostring/) de C#. Permite convertir objetos personalizados a cadena.

```cpp
String System::Net::Http::Headers::NameValueHeaderValue::ToString() const override
```


### Valor de retorno

[String](../../../system/string/) representación tal como la proporciona la clase final.

## NameValueHeaderValue::ToString(System::SharedPtr\<ObjectCollection\<System::SharedPtr\<NameValueHeaderValue\>\>\>, char16_t, bool, System::SharedPtr\<Text::StringBuilder\>) método


Devuelve una representación en cadena de la colección de instancias de la clase NameValueHeaderValue.

```cpp
static void System::Net::Http::Headers::NameValueHeaderValue::ToString(System::SharedPtr<ObjectCollection<System::SharedPtr<NameValueHeaderValue>>> values, char16_t separator, bool leadingSeparator, System::SharedPtr<Text::StringBuilder> destination)
```


### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| values | [System::SharedPtr](../../../system/sharedptr/)\<[ObjectCollection](../../objectcollection/)\<[System::SharedPtr](../../../system/sharedptr/)\<[NameValueHeaderValue](../)\>\>\> | La colección de instancias de la clase NameValueHeaderValue. |
| separator | char16_t | Un separador de cadena. |
| leadingSeparator | **bool** | El valor que indica si el separador de cadena debe agregarse antes del primer elemento de la colección. |
| destination | [System::SharedPtr](../../../system/sharedptr/)\<[Text::StringBuilder](../../../system.text/stringbuilder/)\> | Una instancia donde se asignará una representación en cadena. |

## NameValueHeaderValue::ToString(System::SharedPtr\<ObjectCollection\<System::SharedPtr\<NameValueHeaderValue\>\>\>, char16_t, bool) método


Devuelve una representación en cadena de la colección de instancias de la clase NameValueHeaderValue.

```cpp
static String System::Net::Http::Headers::NameValueHeaderValue::ToString(System::SharedPtr<ObjectCollection<System::SharedPtr<NameValueHeaderValue>>> values, char16_t separator, bool leadingSeparator)
```


### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| values | [System::SharedPtr](../../../system/sharedptr/)\<[ObjectCollection](../../objectcollection/)\<[System::SharedPtr](../../../system/sharedptr/)\<[NameValueHeaderValue](../)\>\>\> | La colección de instancias de la clase NameValueHeaderValue. |
| separator | char16_t | Un separador de cadena. |
| leadingSeparator | **bool** | El valor que indica si el separador de cadena debe agregarse antes del primer elemento de la colección. |

### Valor de retorno

Una representación en cadena de la colección de instancias de la clase NameValueHeaderValue.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [String](../../../system/string/)
* Clase [NameValueHeaderValue](../)
* Clase [ObjectCollection](../../objectcollection/)
* Clase [StringBuilder](../../../system.text/stringbuilder/)
* Espacio de nombres [System::Net::Http::Headers](../../)
* Biblioteca [Aspose.Slides](../../../)