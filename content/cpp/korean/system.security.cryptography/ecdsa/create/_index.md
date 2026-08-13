---
title: Create()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 기본 ECDSA 알고리즘 구현을 생성합니다.
type: docs
weight: 131
url: /ko/system.security.cryptography/ecdsa/create/
---
## ECDsa::Create() 메서드

기본 ECDSA 알고리즘 구현을 생성합니다.

```cpp
static SharedPtr<ECDsa> System::Security::Cryptography::ECDsa::Create()
```

### 반환 값

ECDSA 알고리즘 객체.

## ECDsa::Create(const ECCurve\&) 메서드

지정된 곡선 위에 새로 생성된 키를 사용하여 기본 ECDSA 알고리즘 구현을 생성합니다.

```cpp
static SharedPtr<ECDsa> System::Security::Cryptography::ECDsa::Create(const ECCurve &curve)
```

### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| curve | const [ECCurve](../../eccurve/)\& | 키 생성을 위해 사용할 곡선. |

### 반환 값

ECDSA 알고리즘 객체.

## ECDsa::Create(const ECParameters\&) 메서드

지정된 매개변수를 사용하여 기본 ECDSA 알고리즘 구현을 생성합니다.

```cpp
static SharedPtr<ECDsa> System::Security::Cryptography::ECDsa::Create(const ECParameters &parameters)
```

### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| parameters | const [ECParameters](../../ecparameters/)\& | 키를 나타내는 매개변수. |

### 반환 값

ECDSA 알고리즘 객체.

## ECDsa::Create(const String\&) 메서드

지정된 ECDSA 알고리즘 구현을 생성합니다.

```cpp
static SharedPtr<ECDsa> System::Security::Cryptography::ECDsa::Create(const String &algorithm)
```

### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| algorithm | const [String](../../../system/string/)\& | 알고리즘 이름. |

### 반환 값

ECDSA 알고리즘 객체.

## 참고

* Typedef [SharedPtr](../../../system/sharedptr/)
* 클래스 [ECDsa](../)
* 클래스 [String](../../../system/string/)
* 구조체 [ECCurve](../../eccurve/)
* 구조체 [ECParameters](../../ecparameters/)
* 네임스페이스 [System::Security::Cryptography](../../)
* 라이브러리 [Aspose.Slides](../../../)