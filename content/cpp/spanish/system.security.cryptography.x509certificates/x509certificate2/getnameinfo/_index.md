---
title: GetNameInfo()
second_title: Referencia de la API de Aspose.Slides para C++
description: Obtiene el nombre del sujeto o del emisor del certificado.
type: docs
weight: 248
url: /es/system.security.cryptography.x509certificates/x509certificate2/getnameinfo/
---
## X509Certificate2::GetNameInfo(X509NameType, bool) const método

Obtiene el nombre del sujeto o del emisor del certificado.

```cpp
String System::Security::Cryptography::X509Certificates::X509Certificate2::GetNameInfo(X509NameType name_type, bool for_issuer) const
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| name_type | [X509NameType](../../x509nametype/) | Opciones de formato de nombre. |
| for_issuer | **bool** | Si es true, devuelve el nombre del emisor; de lo contrario, devuelve el nombre del sujeto. |

### Valor de retorno

Nombre de emisor o sujeto formateado.

## Ver también

* Enumeración [X509NameType](../../x509nametype/)
* Clase [String](../../../system/string/)
* Clase [X509Certificate2](../)
* Espacio de nombres [System::Security::Cryptography::X509Certificates](../../)
* Biblioteca [Aspose.Slides](../../../)