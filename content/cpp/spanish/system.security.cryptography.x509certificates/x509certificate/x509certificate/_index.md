---
title: X509Certificate()
second_title: Referencia de la API de Aspose.Slides para C++
description: 
type: docs
weight: 1
url: /es/system.security.cryptography.x509certificates/x509certificate/x509certificate/
---
## X509Certificate::X509Certificate(const X509Certificate\&) constructor




```cpp
System::Security::Cryptography::X509Certificates::X509Certificate::X509Certificate(const X509Certificate &)=delete
```

## X509Certificate::X509Certificate() constructor


Constructor.

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate::X509Certificate()
```

## X509Certificate::X509Certificate(const ByteArrayPtr\&) constructor


Constructor.

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate::X509Certificate(const ByteArrayPtr &data)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Secuencia de bytes que representa el certificado codificado. |

## X509Certificate::X509Certificate(const String\&) constructor


Constructor.

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate::X509Certificate(const String &filename)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | Archivo del que cargar el certificado. |

## X509Certificate::X509Certificate(const SharedPtr\<X509Certificate\>\&) constructor


Constructor.

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate::X509Certificate(const SharedPtr<X509Certificate> &cert)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| cert | const [SharedPtr](../../../system/sharedptr/)\<[X509Certificate](../)\>\& | Un certificado utilizado para inicializar este objeto. |

## X509Certificate::X509Certificate(const ByteArrayPtr\&, const String\&) constructor


Constructor.

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate::X509Certificate(const ByteArrayPtr &raw_data, const String &password)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| raw_data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Secuencia de bytes que representa el certificado codificado. |
| password | const [String](../../../system/string/)\& | Contraseña utilizada para acceder a los datos del certificado. |

## X509Certificate::X509Certificate(const ByteArrayPtr\&, const SecureStringPtr\&) constructor


Constructor.

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate::X509Certificate(const ByteArrayPtr &raw_data, const SecureStringPtr &password)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| raw_data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Secuencia de bytes que representa el certificado codificado. |
| password | const [SecureStringPtr](../../../system.security/securestringptr/)\& | Contraseña utilizada para acceder a los datos del certificado. |

## X509Certificate::X509Certificate(const String\&, const String\&) constructor


Constructor.

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate::X509Certificate(const String &filename, const String &password)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | Archivo del que cargar el certificado. |
| password | const [String](../../../system/string/)\& | Contraseña utilizada para acceder a los datos del certificado. |

## X509Certificate::X509Certificate(const String\&, const SecureStringPtr\&) constructor


Constructor.

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate::X509Certificate(const String &filename, const SecureStringPtr &password)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | Archivo del que cargar el certificado. |
| password | const [SecureStringPtr](../../../system.security/securestringptr/)\& | Contraseña utilizada para acceder a los datos del certificado. |

## X509Certificate::X509Certificate(const ByteArrayPtr\&, const String\&, X509KeyStorageFlags) constructor


Constructor.

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate::X509Certificate(const ByteArrayPtr &raw_data, const String &password, X509KeyStorageFlags key_storage_flags)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| raw_data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Secuencia de bytes que representa el certificado codificado. |
| password | const [String](../../../system/string/)\& | Contraseña utilizada para acceder a los datos del certificado. |
| key_storage_flags | [X509KeyStorageFlags](../../x509keystorageflags/) | Indicadores que indican cómo almacenar la clave. |

## X509Certificate::X509Certificate(const ByteArrayPtr\&, const SecureStringPtr\&, X509KeyStorageFlags) constructor


Constructor.

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate::X509Certificate(const ByteArrayPtr &raw_data, const SecureStringPtr &password, X509KeyStorageFlags key_storage_flags)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| raw_data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Secuencia de bytes que representa el certificado codificado. |
| password | const [SecureStringPtr](../../../system.security/securestringptr/)\& | Contraseña utilizada para acceder a los datos del certificado. |
| key_storage_flags | [X509KeyStorageFlags](../../x509keystorageflags/) | Indicadores que indican cómo almacenar la clave. |

## X509Certificate::X509Certificate(const String\&, const String\&, X509KeyStorageFlags) constructor


Constructor.

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate::X509Certificate(const String &filename, const String &password, X509KeyStorageFlags key_storage_flags)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | Archivo del que cargar el certificado. |
| password | const [String](../../../system/string/)\& | Contraseña utilizada para acceder a los datos del certificado. |
| key_storage_flags | [X509KeyStorageFlags](../../x509keystorageflags/) | Indicadores que indican cómo almacenar la clave. |

## X509Certificate::X509Certificate(const String\&, const SecureStringPtr\&, X509KeyStorageFlags) constructor


Constructor.

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate::X509Certificate(const String &filename, const SecureStringPtr &password, X509KeyStorageFlags key_storage_flags)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | Archivo del que cargar el certificado. |
| password | const [SecureStringPtr](../../../system.security/securestringptr/)\& | Contraseña utilizada para acceder a los datos del certificado. |
| key_storage_flags | [X509KeyStorageFlags](../../x509keystorageflags/) | Indicadores que indican cómo almacenar la clave. |

## X509Certificate::X509Certificate(const ByteArrayPtr\&, const ByteArrayPtr\&, X509KeyStorageFlags) constructor


Constructor.

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate::X509Certificate(const ByteArrayPtr &raw_data, const ByteArrayPtr &private_key, X509KeyStorageFlags key_storage_flags)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| raw_data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Secuencia de bytes que representa el certificado codificado (parte pública). |
| private_key | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Secuencia de bytes que representa la clave privada. |
| key_storage_flags | [X509KeyStorageFlags](../../x509keystorageflags/) | Indicadores que indican cómo almacenar la clave. |

## Ver también

* Enum [X509KeyStorageFlags](../../x509keystorageflags/)
* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [SecureStringPtr](../../../system.security/securestringptr/)
* Class [X509Certificate](../)
* Class [String](../../../system/string/)
* Namespace [System::Security::Cryptography::X509Certificates](../../)
* Library [Aspose.Slides](../../../)