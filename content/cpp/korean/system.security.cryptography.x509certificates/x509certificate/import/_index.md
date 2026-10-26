---
title: Import()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 지정된 인증서 파일에서 정보를 가져옵니다. 구현되지 않음.
type: docs
weight: 300
url: /ko/system.security.cryptography.x509certificates/x509certificate/import/
---
## X509Certificate::Import(const String\&, const SecureStringPtr\&, X509KeyStorageFlags) 메서드

지정된 인증서 파일에서 정보를 가져옵니다. 구현되지 않음.

```cpp
virtual void System::Security::Cryptography::X509Certificates::X509Certificate::Import(const String &filename, const SecureStringPtr &password, X509KeyStorageFlags key_storage_flags)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | 인증서 파일 이름. |
| password | const [SecureStringPtr](../../../system.security/securestringptr/)\& | 인증서 데이터를 액세스하는 데 필요한 비밀번호. |
| key_storage_flags | [X509KeyStorageFlags](../../x509keystorageflags/) |  |

## X509Certificate::Import(const String\&, const String\&, X509KeyStorageFlags) 메서드

지정된 인증서 파일에서 정보를 가져옵니다. 구현되지 않음.

```cpp
virtual void System::Security::Cryptography::X509Certificates::X509Certificate::Import(const String &filename, const String &password, X509KeyStorageFlags key_storage_flags)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | 인증서 파일 이름. |
| password | const [String](../../../system/string/)\& | 인증서 데이터를 액세스하는 데 필요한 비밀번호. |
| key_storage_flags | [X509KeyStorageFlags](../../x509keystorageflags/) |  |

## X509Certificate::Import(const ByteArrayPtr\&, const SecureStringPtr\&, X509KeyStorageFlags) 메서드

지정된 인증서 데이터에서 정보를 가져옵니다. 구현되지 않음.

```cpp
virtual void System::Security::Cryptography::X509Certificates::X509Certificate::Import(const ByteArrayPtr &data, const SecureStringPtr &password, X509KeyStorageFlags key_storage_flags)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | X.509 인증서 데이터. |
| password | const [SecureStringPtr](../../../system.security/securestringptr/)\& | 인증서 데이터를 액세스하는 데 필요한 비밀번호. |
| key_storage_flags | [X509KeyStorageFlags](../../x509keystorageflags/) |  |

## X509Certificate::Import(const ByteArrayPtr\&, const String\&, X509KeyStorageFlags) 메서드

지정된 인증서 데이터에서 정보를 가져옵니다. 구현되지 않음.

```cpp
virtual void System::Security::Cryptography::X509Certificates::X509Certificate::Import(const ByteArrayPtr &data, const String &password, X509KeyStorageFlags key_storage_flags)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | 인증서 파일 이름. |
| password | const [String](../../../system/string/)\& | 인증서 데이터를 액세스하는 데 필요한 비밀번호. |
| key_storage_flags | [X509KeyStorageFlags](../../x509keystorageflags/) |  |

## X509Certificate::Import(const String\&) 메서드

지정된 인증서 파일에서 정보를 가져옵니다. 구현되지 않음.

```cpp
virtual void System::Security::Cryptography::X509Certificates::X509Certificate::Import(const String &filename)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | 인증서 파일 이름. |

## X509Certificate::Import(const ByteArrayPtr\&) 메서드

지정된 인증서 데이터에서 정보를 가져옵니다. 구현되지 않음.

```cpp
virtual void System::Security::Cryptography::X509Certificates::X509Certificate::Import(const ByteArrayPtr &data)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | 인증서 파일 이름. |

## See Also

* Enum [X509KeyStorageFlags](../../x509keystorageflags/)
* Typedef [SecureStringPtr](../../../system.security/securestringptr/)
* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Class [String](../../../system/string/)
* Class [X509Certificate](../)
* Namespace [System::Security::Cryptography::X509Certificates](../../)
* Library [Aspose.Slides](../../../)