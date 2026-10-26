---
title: Import()
second_title: Referencia de la API de Aspose.Slides para C++
description: Importa información del archivo de certificado especificado.
type: docs
weight: 300
url: /es/system.security.cryptography.x509certificates/x509certificate2/import/
---
## X509Certificate2::Import(const String\&, const SecureStringPtr\&, X509KeyStorageFlags) método


Importa información del archivo de certificado especificado.

```cpp
void System::Security::Cryptography::X509Certificates::X509Certificate2::Import(const String &filename, const SecureStringPtr &password, X509KeyStorageFlags key_storage_flags) override
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | El nombre del archivo de certificado. |
| password | const [SecureStringPtr](../../../system.security/securestringptr/)\& | La contraseña requerida para acceder a los datos del certificado. |
| key_storage_flags | [X509KeyStorageFlags](../../x509keystorageflags/) |  |

## X509Certificate2::Import(const String\&, const String\&, X509KeyStorageFlags) método


Importa información del archivo de certificado especificado.

```cpp
void System::Security::Cryptography::X509Certificates::X509Certificate2::Import(const String &filename, const String &password, X509KeyStorageFlags key_storage_flags) override
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | El nombre del archivo de certificado. |
| password | const [String](../../../system/string/)\& | La contraseña requerida para acceder a los datos del certificado. |
| key_storage_flags | [X509KeyStorageFlags](../../x509keystorageflags/) |  |

## X509Certificate2::Import(const ByteArrayPtr\&, const SecureStringPtr\&, X509KeyStorageFlags) método


Importa información de los datos del certificado especificado.

```cpp
void System::Security::Cryptography::X509Certificates::X509Certificate2::Import(const ByteArrayPtr &data, const SecureStringPtr &password, X509KeyStorageFlags key_storage_flags) override
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Los datos del certificado X.509. |
| password | const [SecureStringPtr](../../../system.security/securestringptr/)\& | La contraseña requerida para acceder a los datos del certificado. |
| key_storage_flags | [X509KeyStorageFlags](../../x509keystorageflags/) |  |

## X509Certificate2::Import(const ByteArrayPtr\&, const String\&, X509KeyStorageFlags) método


Importa información de los datos del certificado especificado.

```cpp
void System::Security::Cryptography::X509Certificates::X509Certificate2::Import(const ByteArrayPtr &data, const String &password, X509KeyStorageFlags key_storage_flags) override
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | El nombre del archivo de certificado. |
| password | const [String](../../../system/string/)\& | La contraseña requerida para acceder a los datos del certificado. |
| key_storage_flags | [X509KeyStorageFlags](../../x509keystorageflags/) |  |

## X509Certificate2::Import(const String\&) método


Importa información del archivo de certificado especificado.

```cpp
void System::Security::Cryptography::X509Certificates::X509Certificate2::Import(const String &filename) override
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | El nombre del archivo de certificado. |

## X509Certificate2::Import(const ByteArrayPtr\&) método


Importa información de los datos del certificado especificado.

```cpp
void System::Security::Cryptography::X509Certificates::X509Certificate2::Import(const ByteArrayPtr &data) override
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | El nombre del archivo de certificado. |

## Véase también

* Enumeración [X509KeyStorageFlags](../../x509keystorageflags/)
* Typedef [SecureStringPtr](../../../system.security/securestringptr/)
* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Clase [String](../../../system/string/)
* Clase [X509Certificate2](../)
* Espacio de nombres [System::Security::Cryptography::X509Certificates](../../)
* Biblioteca [Aspose.Slides](../../../)