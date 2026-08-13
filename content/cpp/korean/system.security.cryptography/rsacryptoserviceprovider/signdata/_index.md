---
title: SignData()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 지정된 입력 값의 서명을 계산합니다.
type: docs
weight: 183
url: /ko/system.security.cryptography/rsacryptoserviceprovider/signdata/
---
## RSACryptoServiceProvider::SignData(const ByteArrayPtr\&, const SharedPtr\<Object\>\&) method

지정된 입력 값의 서명을 계산합니다.

```cpp
ByteArrayPtr System::Security::Cryptography::RSACryptoServiceProvider::SignData(const ByteArrayPtr &buffer, const SharedPtr<Object> &halg)
```

### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| buffer | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | [Buffer](../../../system/buffer/) 로부터 입력 데이터를 읽기 위한 버퍼. |
| halg | const [SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\& | 사용할 해시 알고리즘. |

### 반환 값

[RSA](../../rsa/) 지정된 데이터에 대한 서명.

## RSACryptoServiceProvider::SignData(const SharedPtr\<IO::Stream\>\&, const SharedPtr\<Object\>\&) method

지정된 입력 값의 서명을 계산합니다.

```cpp
ByteArrayPtr System::Security::Cryptography::RSACryptoServiceProvider::SignData(const SharedPtr<IO::Stream> &input_stream, const SharedPtr<Object> &halg)
```

### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| input_stream | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | 서명되는 데이터를 읽기 위한 스트림. |
| halg | const [SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\& | 사용할 해시 알고리즘. |

### 반환 값

[RSA](../../rsa/) 지정된 데이터에 대한 서명.

## RSACryptoServiceProvider::SignData(const ByteArrayPtr\&, int32_t, int32_t, const SharedPtr\<Object\>\&) method

지정된 입력 값의 서명을 계산합니다.

```cpp
ByteArrayPtr System::Security::Cryptography::RSACryptoServiceProvider::SignData(const ByteArrayPtr &buffer, int32_t offset, int32_t count, const SharedPtr<Object> &halg)
```

### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| buffer | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | [Buffer](../../../system/buffer/) 로부터 입력 데이터를 읽기 위한 버퍼. |
| offset | **int32_t** | 입력 버퍼 슬라이스 시작 인덱스. |
| count | **int32_t** | 입력 버퍼 슬라이스 크기. |
| halg | const [SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\& | 사용할 해시 알고리즘. |

### 반환 값

[RSA](../../rsa/) 지정된 데이터에 대한 서명.

## 또 보기

* 타입 정의 [ByteArrayPtr](../../../system/bytearrayptr/)
* 타입 정의 [SharedPtr](../../../system/sharedptr/)
* 클래스 [Object](../../../system/object/)
* 클래스 [RSACryptoServiceProvider](../)
* 클래스 [Stream](../../../system.io/stream/)
* 네임스페이스 [System::Security::Cryptography](../../)
* 라이브러리 [Aspose.Slides](../../../)