---
title: X509Certificate2()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 빈 X509Certificate2를 생성합니다.
type: docs
weight: 1
url: /ko/system.security.cryptography.x509certificates/x509certificate2/x509certificate2/
---
## X509Certificate2::X509Certificate2() 생성자

빈 [X509Certificate2](../)를 생성합니다.

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate2::X509Certificate2()
```

## X509Certificate2::X509Certificate2(const String\&) 생성자

생성자.

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate2::X509Certificate2(const String &filename)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | 인증서를 로드할 파일입니다. |

## X509Certificate2::X509Certificate2(const SharedPtr\<X509Certificate\>\&) 생성자

생성자.

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate2::X509Certificate2(const SharedPtr<X509Certificate> &cert)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| cert | const [SharedPtr](../../../system/sharedptr/)\<[X509Certificate](../../x509certificate/)\>\& | [X509Certificate](../../x509certificate/) 객체입니다. |

## X509Certificate2::X509Certificate2(const ByteArrayPtr\&) 생성자

생성자.

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate2::X509Certificate2(const ByteArrayPtr &raw_data)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| raw_data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | 인코딩된 인증서를 나타내는 바이트 시퀀스입니다. |

## X509Certificate2::X509Certificate2(const ByteArrayPtr\&, const String\&) 생성자

생성자.

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate2::X509Certificate2(const ByteArrayPtr &raw_data, const String &password)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| raw_data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | 인코딩된 인증서를 나타내는 바이트 시퀀스입니다. |
| password | const [String](../../../system/string/)\& | 인증서 비밀번호입니다. |

## X509Certificate2::X509Certificate2(const ByteArrayPtr\&, const SecureStringPtr\&) 생성자

생성자.

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate2::X509Certificate2(const ByteArrayPtr &raw_data, const SecureStringPtr &password)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| raw_data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | 인코딩된 인증서를 나타내는 바이트 시퀀스입니다. |
| password | const [SecureStringPtr](../../../system.security/securestringptr/)\& | 인증서 비밀번호입니다. |

## X509Certificate2::X509Certificate2(const ByteArrayPtr\&, const String\&, X509KeyStorageFlags) 생성자

생성자.

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate2::X509Certificate2(const ByteArrayPtr &raw_data, const String &password, X509KeyStorageFlags key_storage_flags)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| raw_data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | 인코딩된 인증서를 나타내는 바이트 시퀀스입니다. |
| password | const [String](../../../system/string/)\& | 인증서 비밀번호입니다. |
| key_storage_flags | [X509KeyStorageFlags](../../x509keystorageflags/) | 키를 저장하는 방법을 나타내는 플래그입니다. |

## X509Certificate2::X509Certificate2(const ByteArrayPtr\&, const SecureStringPtr\&, X509KeyStorageFlags) 생성자

생성자.

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate2::X509Certificate2(const ByteArrayPtr &raw_data, const SecureStringPtr &password, X509KeyStorageFlags key_storage_flags)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| raw_data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | 인코딩된 인증서를 나타내는 바이트 시퀀스입니다. |
| password | const [SecureStringPtr](../../../system.security/securestringptr/)\& | 인증서 비밀번호입니다. |
| key_storage_flags | [X509KeyStorageFlags](../../x509keystorageflags/) | 키를 저장하는 방법을 나타내는 플래그입니다. |

## X509Certificate2::X509Certificate2(const String\&, const String\&) 생성자

생성자.

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate2::X509Certificate2(const String &filename, const String &password)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | 인증서를 로드할 파일입니다. |
| password | const [String](../../../system/string/)\& | 인증서 비밀번호입니다. |

## X509Certificate2::X509Certificate2(const String\&, const SecureStringPtr\&) 생성자

생성자.

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate2::X509Certificate2(const String &filename, const SecureStringPtr &password)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | 인증서를 로드할 파일입니다. |
| password | const [SecureStringPtr](../../../system.security/securestringptr/)\& | 인증서 비밀번호입니다. |

## X509Certificate2::X509Certificate2(const String\&, const String\&, X509KeyStorageFlags) 생성자

생성자.

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate2::X509Certificate2(const String &filename, const String &password, X509KeyStorageFlags key_storage_flags)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | 인증서를 로드할 파일입니다. |
| password | const [String](../../../system/string/)\& | 인증서 비밀번호입니다. |
| key_storage_flags | [X509KeyStorageFlags](../../x509keystorageflags/) | 키를 저장하는 방법을 나타내는 플래그입니다. |

## X509Certificate2::X509Certificate2(const String\&, const SecureStringPtr\&, X509KeyStorageFlags) 생성자

생성자.

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate2::X509Certificate2(const String &filename, const SecureStringPtr &password, X509KeyStorageFlags key_storage_flags)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | 인증서를 로드할 파일입니다. |
| password | const [SecureStringPtr](../../../system.security/securestringptr/)\& | 인증서 비밀번호입니다. |
| key_storage_flags | [X509KeyStorageFlags](../../x509keystorageflags/) | 키를 저장하는 방법을 나타내는 플래그입니다. |

## X509Certificate2::X509Certificate2(const ByteArrayPtr\&, const ByteArrayPtr\&, X509KeyStorageFlags) 생성자

생성자.

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate2::X509Certificate2(const ByteArrayPtr &raw_data, const ByteArrayPtr &private_key, X509KeyStorageFlags key_storage_flags)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| raw_data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | 인코딩된 인증서(공개 부분)를 나타내는 바이트 시퀀스입니다. |
| private_key | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | 개인 키를 나타내는 바이트 시퀀스입니다. |
| key_storage_flags | [X509KeyStorageFlags](../../x509keystorageflags/) | 키를 저장하는 방법을 나타내는 플래그입니다. |

## 참고

* Enum [X509KeyStorageFlags](../../x509keystorageflags/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Typedef [SecureStringPtr](../../../system.security/securestringptr/)
* Class [X509Certificate2](../)
* Class [String](../../../system/string/)
* Class [X509Certificate](../../x509certificate/)
* Namespace [System::Security::Cryptography::X509Certificates](../../)
* Library [Aspose.Slides](../../../)