---
title: X509Certificate2()
second_title: Referência da API Aspose.Slides para C++
description: Constrói um X509Certificate2 vazio.
type: docs
weight: 1
url: /pt/system.security.cryptography.x509certificates/x509certificate2/x509certificate2/
---
## X509Certificate2::X509Certificate2() construtor


Construtor vazio [X509Certificate2](../).

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate2::X509Certificate2()
```

## X509Certificate2::X509Certificate2(const String\&) construtor


Construtor.

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate2::X509Certificate2(const String &filename)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | Arquivo para carregar o certificado. |

## X509Certificate2::X509Certificate2(const SharedPtr\<X509Certificate\>\&) construtor


Construtor.

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate2::X509Certificate2(const SharedPtr<X509Certificate> &cert)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| cert | const [SharedPtr](../../../system/sharedptr/)\<[X509Certificate](../../x509certificate/)\>\& | Um objeto [X509Certificate](../../x509certificate/). |

## X509Certificate2::X509Certificate2(const ByteArrayPtr\&) construtor


Construtor.

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate2::X509Certificate2(const ByteArrayPtr &raw_data)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| raw_data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Sequência de bytes que representa o certificado codificado. |

## X509Certificate2::X509Certificate2(const ByteArrayPtr\&, const String\&) construtor


Construtor.

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate2::X509Certificate2(const ByteArrayPtr &raw_data, const String &password)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| raw_data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Sequência de bytes que representa o certificado codificado. |
| password | const [String](../../../system/string/)\& | Senha do certificado. |

## X509Certificate2::X509Certificate2(const ByteArrayPtr\&, const SecureStringPtr\&) construtor


Construtor.

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate2::X509Certificate2(const ByteArrayPtr &raw_data, const SecureStringPtr &password)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| raw_data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Sequência de bytes que representa o certificado codificado. |
| password | const [SecureStringPtr](../../../system.security/securestringptr/)\& | Senha do certificado. |

## X509Certificate2::X509Certificate2(const ByteArrayPtr\&, const String\&, X509KeyStorageFlags) construtor


Construtor.

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate2::X509Certificate2(const ByteArrayPtr &raw_data, const String &password, X509KeyStorageFlags key_storage_flags)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| raw_data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Sequência de bytes que representa o certificado codificado. |
| password | const [String](../../../system/string/)\& | Senha do certificado. |
| key_storage_flags | [X509KeyStorageFlags](../../x509keystorageflags/) | Flags que indicam como armazenar a chave. |

## X509Certificate2::X509Certificate2(const ByteArrayPtr\&, const SecureStringPtr\&, X509KeyStorageFlags) construtor


Construtor.

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate2::X509Certificate2(const ByteArrayPtr &raw_data, const SecureStringPtr &password, X509KeyStorageFlags key_storage_flags)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| raw_data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Sequência de bytes que representa o certificado codificado. |
| password | const [SecureStringPtr](../../../system.security/securestringptr/)\& | Senha do certificado. |
| key_storage_flags | [X509KeyStorageFlags](../../x509keystorageflags/) | Flags que indicam como armazenar a chave. |

## X509Certificate2::X509Certificate2(const String\&, const String\&) construtor


Construtor.

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate2::X509Certificate2(const String &filename, const String &password)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | Arquivo para carregar o certificado. |
| password | const [String](../../../system/string/)\& | Senha do certificado. |

## X509Certificate2::X509Certificate2(const String\&, const SecureStringPtr\&) construtor


Construtor.

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate2::X509Certificate2(const String &filename, const SecureStringPtr &password)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | Arquivo para carregar o certificado. |
| password | const [SecureStringPtr](../../../system.security/securestringptr/)\& | Senha do certificado. |

## X509Certificate2::X509Certificate2(const String\&, const String\&, X509KeyStorageFlags) construtor


Construtor.

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate2::X509Certificate2(const String &filename, const String &password, X509KeyStorageFlags key_storage_flags)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | Arquivo para carregar o certificado. |
| password | const [String](../../../system/string/)\& | Senha do certificado. |
| key_storage_flags | [X509KeyStorageFlags](../../x509keystorageflags/) | Flags que indicam como armazenar a chave. |

## X509Certificate2::X509Certificate2(const String\&, const SecureStringPtr\&, X509KeyStorageFlags) construtor


Construtor.

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate2::X509Certificate2(const String &filename, const SecureStringPtr &password, X509KeyStorageFlags key_storage_flags)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | Arquivo para carregar o certificado. |
| password | const [SecureStringPtr](../../../system.security/securestringptr/)\& | Senha do certificado. |
| key_storage_flags | [X509KeyStorageFlags](../../x509keystorageflags/) | Flags que indicam como armazenar a chave. |

## X509Certificate2::X509Certificate2(const ByteArrayPtr\&, const ByteArrayPtr\&, X509KeyStorageFlags) construtor


Construtor.

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate2::X509Certificate2(const ByteArrayPtr &raw_data, const ByteArrayPtr &private_key, X509KeyStorageFlags key_storage_flags)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| raw_data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Sequência de bytes que representa o certificado codificado (parte pública). |
| private_key | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Sequência de bytes que representa a chave privada. |
| key_storage_flags | [X509KeyStorageFlags](../../x509keystorageflags/) | Flags que indicam como armazenar a chave. |

## Ver Também

* Enum [X509KeyStorageFlags](../../x509keystorageflags/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Typedef [SecureStringPtr](../../../system.security/securestringptr/)
* Class [X509Certificate2](../)
* Class [String](../../../system/string/)
* Class [X509Certificate](../../x509certificate/)
* Namespace [System::Security::Cryptography::X509Certificates](../../)
* Library [Aspose.Slides](../../../)