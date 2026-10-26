---
title: CreateHttp()
second_title: Referencia de API de Aspose.Slides para C++
description: Crea una nueva instancia de la clase WebRequest usando el URI especificado.
type: docs
weight: 79
url: /es/system.net/webrequest/createhttp/
---
## WebRequest::CreateHttp(String) método


Crea una nueva instancia de la clase [WebRequest](../) usando el URI especificado.

```cpp
static System::SharedPtr<HttpWebRequest> System::Net::WebRequest::CreateHttp(String requestUriString)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| requestUriString | [String](../../../system/string/) | El URI que se usa para crear una nueva instancia de la clase [WebRequest](../). |

### Valor devuelto

Una instancia recién creada de la clase WebRequest.
## Observaciones



Se lanzará NotSupportedException cuando el URI especificado comience con cualquier esquema excepto [http://](http://) o [https://](https://). 

## WebRequest::CreateHttp(System::SharedPtr\<Uri\>) método


Crea una nueva instancia de la clase [WebRequest](../) usando el URI especificado.

```cpp
static System::SharedPtr<HttpWebRequest> System::Net::WebRequest::CreateHttp(System::SharedPtr<Uri> requestUri)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| requestUri | [System::SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | El URI que se usa para crear una nueva instancia de la clase [WebRequest](../). |

### Valor devuelto

Una instancia recién creada de la clase WebRequest.
## Observaciones



Se lanzará NotSupportedException cuando el URI especificado comience con cualquier esquema excepto [http://](http://) o [https://](https://). 

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [HttpWebRequest](../../httpwebrequest/)
* Clase [String](../../../system/string/)
* Clase [WebRequest](../)
* Clase [Uri](../../../system/uri/)
* Espacio de nombres [System::Net](../../)
* Biblioteca [Aspose.Slides](../../../)