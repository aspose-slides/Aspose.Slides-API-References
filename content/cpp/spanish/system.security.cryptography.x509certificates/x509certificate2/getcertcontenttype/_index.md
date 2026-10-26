---
title: GetCertContentType()
second_title: Referencia de API de Aspose.Slides para C++
description: Obtiene el tipo de certificado contenido en la matriz de bytes especificada.
type: docs
weight: 391
url: /es/system.security.cryptography.x509certificates/x509certificate2/getcertcontenttype/
---
## X509Certificate2::GetCertContentType(const ByteArrayPtr\&) método


Obtiene el tipo de certificado contenido en la matriz de bytes especificada.

```cpp
static X509ContentType System::Security::Cryptography::X509Certificates::X509Certificate2::GetCertContentType(const ByteArrayPtr &raw_data)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| raw_data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Datos del certificado. |

### Valor de retorno

Tipo de certificado X.509.

## X509Certificate2::GetCertContentType(const String\&) método


Obtiene el tipo de certificado contenido en el archivo especificado.

```cpp
static X509ContentType System::Security::Cryptography::X509Certificates::X509Certificate2::GetCertContentType(const String &filename)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | Nombre del archivo de certificado. |

### Valor de retorno

Tipo de certificado X.509.

## Ver también

* Enum [X509ContentType](../../x509contenttype/)
* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Clase [X509Certificate2](../)
* Clase [String](../../../system/string/)
* Espacio de nombres [System::Security::Cryptography::X509Certificates](../../)
* Biblioteca [Aspose.Slides](../../../)