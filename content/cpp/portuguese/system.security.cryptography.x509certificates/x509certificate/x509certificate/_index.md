---
title: X509Certificate()
second_title: Referência da API Aspose.Slides para C++
description: 
type: docs
weight: 1
url: /pt/system.security.cryptography.x509certificates/x509certificate/x509certificate/
---
## X509Certificate::X509Certificate(const X509Certificate\&) construtor




```cpp
System::Security::Cryptography::X509Certificates::X509Certificate::X509Certificate(const X509Certificate &)=delete
```

## X509Certificate::X509Certificate() construtor


Construtor.

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate::X509Certificate()
```

## X509Certificate::X509Certificate(const ByteArrayPtr\&) construtor


Construtor.

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate::X509Certificate(const ByteArrayPtr &data)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Sequência de bytes que representa o certificado codificado. |

## X509Certificate::X509Certificate(const String\&) construtor


Construtor.

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate::X509Certificate(const String &filename)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | Arquivo de onde carregar o certificado. |

## X509Certificate::X509Certificate(const SharedPtr\<X509Certificate\>\&) construtor


Construtor.

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate::X509Certificate(const SharedPtr<X509Certificate> &cert)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| cert | const [SharedPtr](../../../system/sharedptr/)\<[X509Certificate](../)\>\& | Um certificado usado para inicializar este objeto. |

## X509Certificate::X509Certificate(const ByteArrayPtr\&, const String\&) construtor


Construtor.

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate::X509Certificate(const ByteArrayPtr &raw_data, const String &password)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| raw_data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Sequência de bytes que representa o certificado codificado. |
| password | const [String](../../../system/string/)\& | Senha usada para acessar os dados do certificado. |

## X509Certificate::X509Certificate(const ByteArrayPtr\&, const SecureStringPtr\&) construtor


Construtor.

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate::X509Certificate(const ByteArrayPtr &raw_data, const SecureStringPtr &password)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| raw_data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Sequência de bytes que representa o certificado codificado. |
| password | const [SecureStringPtr](../../../system.security/securestringptr/)\& | Senha usada para acessar os dados do certificado. |

## X509Certificate::X509Certificate(const String\&, const String\&) construtor


Construtor.

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate::X509Certificate(const String &filename, const String &password)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | Arquivo de onde carregar o certificado. |
| password | const [String](../../../system/string/)\& | Senha usada para acessar os dados do certificado. |

## X509Certificate::X509Certificate(const String\&, const SecureStringPtr\&) construtor


Construtor.

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate::X509Certificate(const String &filename, const SecureStringPtr &password)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | Arquivo de onde carregar o certificado. |
| password | const [SecureStringPtr](../../../system.security/securestringptr/)\& | Senha usada para acessar os dados do certificado. |

## X509Certificate::X509Certificate(const ByteArrayPtr\&, const String\&, X509KeyStorageFlags) construtor


Construtor.

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate::X509Certificate(const ByteArrayPtr &raw_data, const String &password, X509KeyStorageFlags key_storage_flags)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| raw_data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Sequência de bytes que representa o certificado codificado. |
| password | const [String](../../../system/string/)\& | Senha usada para acessar os dados do certificado. |
| key_storage_flags | [X509KeyStorageFlags](../../x509keystorageflags/) | Flags que indicam como armazenar a chave. |

## X509Certificate::X509Certificate(const ByteArrayPtr\&, const SecureStringPtr\&, X509KeyStorageFlags) construtor


Construtor.

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate::X509Certificate(const ByteArrayPtr &raw_data, const SecureStringPtr &password, X509KeyStorageFlags key_storage_flags)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| raw_data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Sequência de bytes que representa o certificado codificado. |
| password | const [SecureStringPtr](../../../system.security/securestringptr/)\& | Senha usada para acessar os dados do certificado. |
| key_storage_flags | [X509KeyStorageFlags](../../x509keystorageflags/) | Flags que indicam como armazenar a chave. |

## X509Certificate::X509Certificate(const String\&, const String\&, X509KeyStorageFlags) construtor


Construtor.

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate::X509Certificate(const String &filename, const String &password, X509KeyStorageFlags key_storage_flags)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | Arquivo de onde carregar o certificado. |
| password | const [String](../../../system/string/)\& | Senha usada para acessar os dados do certificado. |
| key_storage_flags | [X509KeyStorageFlags](../../x509keystorageflags/) | Flags que indicam como armazenar a chave. |

## X509Certificate::X509Certificate(const String\&, const SecureStringPtr\&, X509KeyStorageFlags) construtor


Construtor.

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate::X509Certificate(const String &filename, const SecureStringPtr &password, X509KeyStorageFlags key_storage_flags)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | Arquivo de onde carregar o certificado. |
| password | const [SecureStringPtr](../../../system.security/securestringptr/)\& | Senha usada para acessar os dados do certificado. |
| key_storage_flags | [X509KeyStorageFlags](../../x509keystorageflags/) | Flags que indicam como armazenar a chave. |

## X509Certificate::X509Certificate(const ByteArrayPtr\&, const ByteArrayPtr\&, X509KeyStorageFlags) construtor


Construtor.

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate::X509Certificate(const ByteArrayPtr &raw_data, const ByteArrayPtr &private_key, X509KeyStorageFlags key_storage_flags)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| raw_data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Sequência de bytes que representa o certificado codificado (parte pública). |
| private_key | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Sequência de bytes que representa a chave privada. |
| key_storage_flags | [X509KeyStorageFlags](../../x509keystorageflags/) | Flags que indicam como armazenar a chave. |

## Veja Também

* Enum [X509KeyStorageFlags](../../x509keystorageflags/)
* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [SecureStringPtr](../../../system.security/securestringptr/)
* Class [X509Certificate](../)
* Class [String](../../../system/string/)
* Namespace [System::Security::Cryptography::X509Certificates](../../)
* Library [Aspose.Slides](../../../)