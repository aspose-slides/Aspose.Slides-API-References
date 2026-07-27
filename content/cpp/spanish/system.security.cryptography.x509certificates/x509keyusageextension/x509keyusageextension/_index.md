---
title: X509KeyUsageExtension()
second_title: Referencia de la API de Aspose.Slides para C++
description: Constructor por defecto.
type: docs
weight: 1
url: /es/system.security.cryptography.x509certificates/x509keyusageextension/x509keyusageextension/
---
## X509KeyUsageExtension::X509KeyUsageExtension() constructor

Constructor predeterminado.

```cpp
System::Security::Cryptography::X509Certificates::X509KeyUsageExtension::X509KeyUsageExtension()
```

## X509KeyUsageExtension::X509KeyUsageExtension(const SharedPtr\<AsnEncodedData\>\&, bool) constructor

Constructor.

```cpp
System::Security::Cryptography::X509Certificates::X509KeyUsageExtension::X509KeyUsageExtension(const SharedPtr<AsnEncodedData> &encoded_key_usage, bool critical)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| encoded_key_usage | const [SharedPtr](../../../system/sharedptr/)\<[AsnEncodedData](../../../system.security.cryptography/asnencodeddata/)\>\& | Datos codificados de los usos de clave. |
| critical | **bool** | Indicador de criticidad. |

## X509KeyUsageExtension::X509KeyUsageExtension(X509KeyUsageFlags, bool) constructor

Constructor.

```cpp
System::Security::Cryptography::X509Certificates::X509KeyUsageExtension::X509KeyUsageExtension(X509KeyUsageFlags key_usages, bool critical)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| key_usages | [X509KeyUsageFlags](../../x509keyusageflags/) | Usos de clave. |
| critical | **bool** | Indicador de criticidad. |

## Véase también

* Enumeración [X509KeyUsageFlags](../../x509keyusageflags/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [X509KeyUsageExtension](../)
* Clase [AsnEncodedData](../../../system.security.cryptography/asnencodeddata/)
* Espacio de nombres [System::Security::Cryptography::X509Certificates](../../)
* Biblioteca [Aspose.Slides](../../../)