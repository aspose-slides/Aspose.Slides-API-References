---
title: GetHashCode()
second_title: Referencia de la API de Aspose.Slides para C++
description: Análogo al método C# Object.GetHashCode(). Permite el hashing de objetos personalizados.
type: docs
weight: 53
url: /es/system.net.http.headers/namevalueheadervalue/gethashcode/
---
## NameValueHeaderValue::GetHashCode() const método


Análogo al método C# [Object.GetHashCode()](../../../system/object/gethashcode/). Habilita el hashing de objetos personalizados.

```cpp
int32_t System::Net::Http::Headers::NameValueHeaderValue::GetHashCode() const override
```


### Valor devuelto

Valor del código hash calculado por la clase correspondiente.

## NameValueHeaderValue::GetHashCode(System::SharedPtr\<ObjectCollection\<System::SharedPtr\<NameValueHeaderValue\>\>\>) método


Devuelve un código hash de todos los elementos de la colección.

```cpp
static int32_t System::Net::Http::Headers::NameValueHeaderValue::GetHashCode(System::SharedPtr<ObjectCollection<System::SharedPtr<NameValueHeaderValue>>> values)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| values | [System::SharedPtr](../../../system/sharedptr/)\<[ObjectCollection](../../objectcollection/)\<[System::SharedPtr](../../../system/sharedptr/)\<[NameValueHeaderValue](../)\>\>\> | La colección de instancias de la clase NameValueHeaderValue. |

### Valor devuelto

Un código hash de todos los elementos de la colección.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [NameValueHeaderValue](../)
* Class [ObjectCollection](../../objectcollection/)
* Namespace [System::Net::Http::Headers](../../)
* Library [Aspose.Slides](../../../)