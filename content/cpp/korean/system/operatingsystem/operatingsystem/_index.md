---
title: OperatingSystem()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 특정 플랫폼 ID와 버전으로 지정된 운영 체제를 나타내는 인스턴스를 생성합니다.
type: docs
weight: 1
url: /ko/system/operatingsystem/operatingsystem/
---
## OperatingSystem::OperatingSystem(PlatformID, const Version\&) 생성자

특정 플랫폼 ID와 버전으로 지정된 운영 체제를 나타내는 인스턴스를 생성합니다.

```cpp
System::OperatingSystem::OperatingSystem(PlatformID platform, const Version &version)
```

### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| platform | [PlatformID](../../platformid/) | 객체가 나타내는 운영 체제의 플랫폼 식별자 |
| version | const [Version](../../version/)\& | 객체가 나타내는 운영 체제의 버전 |

## OperatingSystem::OperatingSystem(PlatformID, const Version\&, const String\&) 생성자

특정 플랫폼 ID, 버전 및 서비스 팩으로 지정된 운영 체제를 나타내는 인스턴스를 생성합니다.

```cpp
System::OperatingSystem::OperatingSystem(PlatformID platform, const Version &version, const String &service_pack)
```

### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| platform | [PlatformID](../../platformid/) | 객체가 나타내는 운영 체제의 플랫폼 식별자 |
| version | const [Version](../../version/)\& | 객체가 나타내는 운영 체제의 버전 |
| service_pack | const [String](../../string/)\& | 객체가 나타내는 운영 체제의 서비스 팩 이름 |

## 참고

* 열거형 [PlatformID](../../platformid/)
* 클래스 [Version](../../version/)
* 클래스 [OperatingSystem](../)
* 클래스 [String](../../string/)
* 네임스페이스 [System](../../)
* 라이브러리 [Aspose.Slides](../../../)