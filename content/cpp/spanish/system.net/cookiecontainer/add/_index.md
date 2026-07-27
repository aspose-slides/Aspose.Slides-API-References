---
title: Add()
second_title: Referencia de API de Aspose.Slides para C++
description: Agrega una cookie a la colección.
type: docs
weight: 105
url: /es/system.net/cookiecontainer/add/
---
## CookieContainer::Add(System::SharedPtr\<Cookie\>) método

Agrega una cookie a la colección.

```cpp
void System::Net::CookieContainer::Add(System::SharedPtr<Cookie> cookie)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| cookie | [System::SharedPtr](../../../system/sharedptr/)\<[Cookie](../../cookie/)\> | La cookie que se agrega. |

## CookieContainer::Add(System::SharedPtr\<Cookie\>, bool) método

Agrega una cookie a la colección.

```cpp
void System::Net::CookieContainer::Add(System::SharedPtr<Cookie> cookie, bool throwOnError)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| cookie | [System::SharedPtr](../../../system/sharedptr/)\<[Cookie](../../cookie/)\> | La cookie que se agrega. |
| throwOnError | **bool** | Un valor que indica si se lanzará una excepción cuando ocurra un error. |

## CookieContainer::Add(System::SharedPtr\<CookieCollection\>) método

Copia cookies de la colección especificada a la actual.

```cpp
void System::Net::CookieContainer::Add(System::SharedPtr<CookieCollection> cookies)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| cookies | [System::SharedPtr](../../../system/sharedptr/)\<[CookieCollection](../../cookiecollection/)\> | La colección de la que se copiarán las cookies. |

## CookieContainer::Add(System::SharedPtr\<Uri\>, System::SharedPtr\<Cookie\>) método

Agrega una cookie para la URI especificada.

```cpp
void System::Net::CookieContainer::Add(System::SharedPtr<Uri> uri, System::SharedPtr<Cookie> cookie)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| uri | [System::SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | Una URI de la cookie. |
| cookie | [System::SharedPtr](../../../system/sharedptr/)\<[Cookie](../../cookie/)\> | La cookie que se agrega. |

## CookieContainer::Add(System::SharedPtr\<Uri\>, System::SharedPtr\<CookieCollection\>) método

Copia cookies de la colección especificada para la URI especificada a la colección actual.

```cpp
void System::Net::CookieContainer::Add(System::SharedPtr<Uri> uri, System::SharedPtr<CookieCollection> cookies)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| uri | [System::SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | Una URI de la cookie. |
| cookies | [System::SharedPtr](../../../system/sharedptr/)\<[CookieCollection](../../cookiecollection/)\> | Una colección de cookies de la que se copiarán las cookies. |

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [Cookie](../../cookie/)
* Clase [CookieContainer](../)
* Clase [CookieCollection](../../cookiecollection/)
* Clase [Uri](../../../system/uri/)
* Espacio de nombres [System::Net](../../)
* Biblioteca [Aspose.Slides](../../../)