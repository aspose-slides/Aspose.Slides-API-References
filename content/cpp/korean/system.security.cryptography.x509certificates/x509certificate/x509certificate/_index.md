---
title: X509Certificate()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 
type: docs
weight: 1
url: /ko/system.security.cryptography.x509certificates/x509certificate/x509certificate/
---
## X509Certificate::X509Certificate(const X509Certificate\&) 생성자




```cpp
System::Security::Cryptography::X509Certificates::X509Certificate::X509Certificate(const X509Certificate &)=delete
```

## X509Certificate::X509Certificate() 생성자


생성자.

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate::X509Certificate()
```

## X509Certificate::X509Certificate(const ByteArrayPtr\&) 생성자


생성자.

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate::X509Certificate(const ByteArrayPtr &data)
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | 인코딩된 인증서를 나타내는 바이트 시퀀스. |

## X509Certificate::X509Certificate(const String\&) 생성자


생성자.

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate::X509Certificate(const String &filename)
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | 인증서를 로드할 파일. |

## X509Certificate::X509Certificate(const SharedPtr\<X509Certificate\>\&) 생성자


생성자.

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate::X509Certificate(const SharedPtr<X509Certificate> &cert)
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| cert | const [SharedPtr](../../../system/sharedptr/)\<[X509Certificate](../)\>\& | 이 객체를 초기화하는 데 사용되는 인증서. |

## X509Certificate::X509Certificate(const ByteArrayPtr\&, const String\&) 생성자


생성자.

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate::X509Certificate(const ByteArrayPtr &raw_data, const String &password)
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| raw_data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | 인코딩된 인증서를 나타내는 바이트 시퀀스. |
| password | const [String](../../../system/string/)\& | 인증서 데이터에 접근하기 위한 비밀번호. |

## X509Certificate::X509Certificate(const ByteArrayPtr\&, const SecureStringPtr\&) 생성자


생성자.

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate::X509Certificate(const ByteArrayPtr &raw_data, const SecureStringPtr &password)
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| raw_data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | 인코딩된 인증서를 나타내는 바이트 시퀀스. |
| password | const [SecureStringPtr](../../../system.security/securestringptr/)\& | 인증서 데이터에 접근하기 위한 비밀번호. |

## X509Certificate::X509Certificate(const String\&, const String\&) 생성자


생성자.

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate::X509Certificate(const String &filename, const String &password)
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | 인증서를 로드할 파일. |
| password | const [String](../../../system/string/)\& | 인증서 데이터에 접근하기 위한 비밀번호. |

## X509Certificate::X509Certificate(const String\&, const SecureStringPtr\&) 생성자


생성자.

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate::X509Certificate(const String &filename, const SecureStringPtr &password)
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | 인증서를 로드할 파일. |
| password | const [SecureStringPtr](../../../system.security/securestringptr/)\& | 인증서 데이터에 접근하기 위한 비밀번호. |

## X509Certificate::X509Certificate(const ByteArrayPtr\&, const String\&, X509KeyStorageFlags) 생성자


생성자.

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate::X509Certificate(const ByteArrayPtr &raw_data, const String &password, X509KeyStorageFlags key_storage_flags)
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| raw_data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | 인코딩된 인증서를 나타내는 바이트 시퀀스. |
| password | const [String](../../../system/string/)\& | 인증서 데이터에 접근하기 위한 비밀번호. |
| key_storage_flags | [X509KeyStorageFlags](../../x509keystorageflags/) | 키를 저장하는 방법을 나타내는 플래그. |

## X509Certificate::X509Certificate(const ByteArrayPtr\&, const SecureStringPtr\&, X509KeyStorageFlags) 생성자


생성자.

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate::X509Certificate(const ByteArrayPtr &raw_data, const SecureStringPtr &password, X509KeyStorageFlags key_storage_flags)
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| raw_data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | 인코딩된 인증서를 나타내는 바이트 시퀀스. |
| password | const [SecureStringPtr](../../../system.security/securestringptr/)\& | 인증서 데이터에 접근하기 위한 비밀번호. |
| key_storage_flags | [X509KeyStorageFlags](../../x509keystorageflags/) | 키를 저장하는 방법을 나타내는 플래그. |

## X509Certificate::X509Certificate(const String\&, const String\&, X509KeyStorageFlags) 생성자


생성자.

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate::X509Certificate(const String &filename, const String &password, X509KeyStorageFlags key_storage_flags)
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | 인증서를 로드할 파일. |
| password | const [String](../../../system/string/)\& | 인증서 데이터에 접근하기 위한 비밀번호. |
| key_storage_flags | [X509KeyStorageFlags](../../x509keystorageflags/) | 키를 저장하는 방법을 나타내는 플래그. |

## X509Certificate::X509Certificate(const String\&, const SecureStringPtr\&, X509KeyStorageFlags) 생성자


생성자.

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate::X509Certificate(const String &filename, const SecureStringPtr &password, X509KeyStorageFlags key_storage_flags)
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | 인증서를 로드할 파일. |
| password | const [SecureStringPtr](../../../system.security/securestringptr/)\& | 인증서 데이터에 접근하기 위한 비밀번호. |
| key_storage_flags | [X509KeyStorageFlags](../../x509keystorageflags/) | 키를 저장하는 방법을 나타내는 플래그. |

## X509Certificate::X509Certificate(const ByteArrayPtr\&, const ByteArrayPtr\&, X509KeyStorageFlags) 생성자


생성자.

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate::X509Certificate(const ByteArrayPtr &raw_data, const ByteArrayPtr &private_key, X509KeyStorageFlags key_storage_flags)
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| raw_data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | 인코딩된 인증서를 나타내는 바이트 시퀀스(공개 부분). |
| private_key | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | 개인 키를 나타내는 바이트 시퀀스. |
| key_storage_flags | [X509KeyStorageFlags](../../x509keystorageflags/) | 키를 저장하는 방법을 나타내는 플래그. |

## 참고

* 열거형 [X509KeyStorageFlags](../../x509keystorageflags/)
* 타입정의 [ByteArrayPtr](../../../system/bytearrayptr/)
* 타입정의 [SharedPtr](../../../system/sharedptr/)
* 타입정의 [SecureStringPtr](../../../system.security/securestringptr/)
* 클래스 [X509Certificate](../)
* 클래스 [String](../../../system/string/)
* 네임스페이스 [System::Security::Cryptography::X509Certificates](../../)
* 라이브러리 [Aspose.Slides](../../../)