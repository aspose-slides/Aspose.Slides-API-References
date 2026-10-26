---
title: X509Certificate2()
second_title: Referencia de API de Aspose.Slides para C++
description: Construye un X509Certificate2 vacío.
type: docs
weight: 1
url: /es/system.security.cryptography.x509certificates/x509certificate2/x509certificate2/
---
## X509Certificate2::X509Certificate2() constructor

Construye vacío [X509Certificate2](../).

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate2::X509Certificate2()
```

## X509Certificate2::X509Certificate2(const String\&) constructor

Constructor.

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate2::X509Certificate2(const String &filename)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | Archivo del que cargar el certificado. |

## X509Certificate2::X509Certificate2(const SharedPtr\<X509Certificate\>\&) constructor

Constructor.

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate2::X509Certificate2(const SharedPtr<X509Certificate> &cert)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| cert | const [SharedPtr](../../../system/sharedptr/)\<[X509Certificate](../../x509certificate/)\>\& | Un objeto [X509Certificate](../../x509certificate/). |

## X509Certificate2::X509Certificate2(const ByteArrayPtr\&) constructor

Constructor.

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate2::X509Certificate2(const ByteArrayPtr &raw_data)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| raw_data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Secuencia de bytes que representa el certificado codificado. |

## X509Certificate2::X509Certificate2(const ByteArrayPtr\&, const String\&) constructor

Constructor.

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate2::X509Certificate2(const ByteArrayPtr &raw_data, const String &password)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| raw_data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Secuencia de bytes que representa el certificado codificado. |
| password | const [String](../../../system/string/)\& | Contraseña del certificado. |

## X509Certificate2::X509Certificate2(const ByteArrayPtr\&, const SecureStringPtr\&) constructor

Constructor.

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate2::X509Certificate2(const ByteArrayPtr &raw_data, const SecureStringPtr &password)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| raw_data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Secuencia de bytes que representa el certificado codificado. |
| password | const [SecureStringPtr](../../../system.security/securestringptr/)\& | Contraseña del certificado. |

## X509Certificate2::X509Certificate2(const ByteArrayPtr\&, const String\&, X509KeyStorageFlags) constructor

Constructor.

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate2::X509Certificate2(const ByteArrayPtr &raw_data, const String &password, X509KeyStorageFlags key_storage_flags)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| raw_data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Secuencia de bytes que representa el certificado codificado. |
| password | const [String](../../../system/string/)\& | Contraseña del certificado. |
| key_storage_flags | [X509KeyStorageFlags](../../x509keystorageflags/) | Banderas que indican cómo almacenar la clave. |

## X509Certificate2::X509Certificate2(const ByteArrayPtr\&, const SecureStringPtr\&, X509KeyStorageFlags) constructor

Constructor.

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate2::X509Certificate2(const ByteArrayPtr &raw_data, const SecureStringPtr &password, X509KeyStorageFlags key_storage_flags)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| raw_data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Secuencia de bytes que representa el certificado codificado. |
| password | const [SecureStringPtr](../../../system.security/securestringptr/)\& | Contraseña del certificado. |
| key_storage_flags | [X509KeyStorageFlags](../../x509keystorageflags/) | Banderas que indican cómo almacenar la clave. |

## X509Certificate2::X509Certificate2(const String\&, const String\&) constructor

Constructor.

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate2::X509Certificate2(const String &filename, const String &password)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | Archivo del que cargar el certificado. |
| password | const [String](../../../system/string/)\& | Contraseña del certificado. |

## X509Certificate2::X509Certificate2(const String\&, const SecureStringPtr\&) constructor

Constructor.

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate2::X509Certificate2(const String &filename, const SecureStringPtr &password)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | Archivo del que cargar el certificado. |
| password | const [SecureStringPtr](../../../system.security/securestringptr/)\& | Contraseña del certificado. |

## X509Certificate2::X509Certificate2(const String\&, const String\&, X509KeyStorageFlags) constructor

Constructor.

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate2::X509Certificate2(const String &filename, const String &password, X509KeyStorageFlags key_storage_flags)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | Archivo del que cargar el certificado. |
| password | const [String](../../../system/string/)\& | Contraseña del certificado. |
| key_storage_flags | [X509KeyStorageFlags](../../x509keystorageflags/) | Banderas que indican cómo almacenar la clave. |

## X509Certificate2::X509Certificate2(const String\&, const SecureStringPtr\&, X509KeyStorageFlags) constructor

Constructor.

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate2::X509Certificate2(const String &filename, const SecureStringPtr &password, X509KeyStorageFlags key_storage_flags)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | Archivo del que cargar el certificado. |
| password | const [SecureStringPtr](../../../system.security/securestringptr/)\& | Contraseña del certificado. |
| key_storage_flags | [X509KeyStorageFlags](../../x509keystorageflags/) | Banderas que indican cómo almacenar la clave. |

## X509Certificate2::X509Certificate2(const ByteArrayPtr\&, const ByteArrayPtr\&, X509KeyStorageFlags) constructor

Constructor.

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate2::X509Certificate2(const ByteArrayPtr &raw_data, const ByteArrayPtr &private_key, X509KeyStorageFlags key_storage_flags)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| raw_data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Secuencia de bytes que representa el certificado codificado (parte pública). |
| private_key | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Secuencia de bytes que representa la clave privada. |
| key_storage_flags | [X509KeyStorageFlags](../../x509keystorageflags/) | Banderas que indican cómo almacenar la clave. |

## Ver también

* Enum [X509KeyStorageFlags](../../x509keystorageflags/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Typedef [SecureStringPtr](../../../system.security/securestringptr/)
* Class [X509Certificate2](../)
* Class [String](../../../system/string/)
* Class [X509Certificate](../../x509certificate/)
* Namespace [System::Security::Cryptography::X509Certificates](../../)
* Library [Aspose.Slides](../../../)