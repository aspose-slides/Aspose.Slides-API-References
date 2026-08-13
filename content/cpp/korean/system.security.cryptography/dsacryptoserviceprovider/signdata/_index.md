---
title: SignData()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 지정된 입력 값의 서명을 계산합니다.
type: docs
weight: 183
url: /ko/system.security.cryptography/dsacryptoserviceprovider/signdata/
---
## DSACryptoServiceProvider::SignData(const ByteArrayPtr\&) method


지정된 입력 값의 서명을 계산합니다.

```cpp
ByteArrayPtr System::Security::Cryptography::DSACryptoServiceProvider::SignData(const ByteArrayPtr &buffer)
```


### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| buffer | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | [Buffer](../../../system/buffer/)에서 입력 데이터를 읽기 위해. |

### 반환값

[DSA](../../dsa/) 지정된 데이터에 대한 서명.

## DSACryptoServiceProvider::SignData(const SharedPtr\<IO::Stream\>\&) method


지정된 입력 값의 서명을 계산합니다.

```cpp
ByteArrayPtr System::Security::Cryptography::DSACryptoServiceProvider::SignData(const SharedPtr<IO::Stream> &input_stream)
```


### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| input_stream | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | 서명되는 데이터를 읽기 위한 스트림. |

### 반환값

[DSA](../../dsa/) 지정된 데이터에 대한 서명.

## DSACryptoServiceProvider::SignData(const ByteArrayPtr\&, int32_t, int32_t) method


지정된 입력 값의 서명을 계산합니다.

```cpp
ByteArrayPtr System::Security::Cryptography::DSACryptoServiceProvider::SignData(const ByteArrayPtr &buffer, int32_t offset, int32_t count)
```


### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| buffer | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | [Buffer](../../../system/buffer/)에서 입력 데이터를 읽기 위해. |
| offset | **int32_t** | 입력 버퍼 슬라이스 시작 인덱스. |
| count | **int32_t** | 입력 버퍼 슬라이스 크기. |

### 반환값

[DSA](../../dsa/) 지정된 데이터에 대한 서명.

## DSACryptoServiceProvider::SignData(const ByteArrayPtr\&, const HashAlgorithmName\&) method


지정된 해시 알고리즘을 사용하여 지정된 데이터 배열의 해시 값을 계산하고, 결과에 서명합니다.

```cpp
ByteArrayPtr System::Security::Cryptography::DSA::SignData(const ByteArrayPtr &data, const HashAlgorithmName &hash_algorithm)
```


### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | 입력 데이터 배열. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | 해시 알고리즘. 입력 데이터에 대한 [DSA](../../dsa/) 서명을 반환합니다. |

## DSACryptoServiceProvider::SignData(const ByteArrayPtr\&, int32_t, int32_t, const HashAlgorithmName\&) method


지정된 해시 알고리즘을 사용하여 지정된 데이터 배열의 해시 값을 계산하고, 결과에 서명합니다.

```cpp
ByteArrayPtr System::Security::Cryptography::DSA::SignData(const ByteArrayPtr &data, int32_t offset, int32_t count, const HashAlgorithmName &hash_algorithm)
```


### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | 입력 데이터 배열. |
| offset | **int32_t** | **data** 내 오프셋. |
| count | **int32_t** | 입력 데이터로 사용할 바이트 수. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | 해시 알고리즘. 입력 데이터에 대한 [DSA](../../dsa/) 서명을 반환합니다. |

## DSACryptoServiceProvider::SignData(const StreamPtr\&, const HashAlgorithmName\&) method


지정된 해시 알고리즘을 사용하여 지정된 이진 스트림의 해시 값을 계산하고, 결과에 서명합니다.

```cpp
ByteArrayPtr System::Security::Cryptography::DSA::SignData(const StreamPtr &stream, const HashAlgorithmName &hash_algorithm)
```


### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| stream | const [StreamPtr](../../../system/streamptr/)\& | 이진 스트림. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | 해시 알고리즘. 입력 데이터에 대한 [DSA](../../dsa/) 서명을 반환합니다. |

## 관련 항목

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [StreamPtr](../../../system/streamptr/)
* 클래스 [DSACryptoServiceProvider](../)
* 클래스 [Stream](../../../system.io/stream/)
* 구조체 [HashAlgorithmName](../../hashalgorithmname/)
* 네임스페이스 [System::Security::Cryptography](../../)
* 라이브러리 [Aspose.Slides](../../../)