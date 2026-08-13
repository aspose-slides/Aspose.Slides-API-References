---
title: Semaphore()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 이름이 없는 세마포어를 생성합니다.
type: docs
weight: 1
url: /ko/system.threading/semaphore/semaphore/
---
## Semaphore::Semaphore(int, int) 생성자

이름이 없는 세마포어를 생성합니다.

```cpp
System::Threading::Semaphore::Semaphore(int initialCount, int maximumCount)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| initialCount | int | 활성 엔트리의 초기 개수. |
| maximumCount | int | 허용되는 최대 엔트리 개수. |

## Semaphore::Semaphore(int, int, const String\&) 생성자

이름이 지정된 세마포어를 생성합니다.

```cpp
System::Threading::Semaphore::Semaphore(int initialCount, int maximumCount, const String &name)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| initialCount | int | 활성 엔트리의 초기 개수. |
| maximumCount | int | 허용되는 최대 엔트리 개수. |
| name | const [String](../../../system/string/)\& | [Semaphore](../) 이름. |

## Semaphore::Semaphore(int, int, const String\&, bool\&) 생성자

이름이 지정된 세마포어를 생성합니다.

```cpp
System::Threading::Semaphore::Semaphore(int initialCount, int maximumCount, const String &name, bool &createdNew)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| initialCount | int | 활성 엔트리의 초기 개수. |
| maximumCount | int | 허용되는 최대 엔트리 개수. |
| name | const [String](../../../system/string/)\& | [Semaphore](../) 이름. |
| createdNew | **bool**\& | 새 세마포어가 생성되면 true, 동일한 이름의 기존 세마포어가 재사용되면 false가 설정되는 변수에 대한 참조 |

## 참고

* 클래스 [Semaphore](../)
* 클래스 [String](../../../system/string/)
* 네임스페이스 [System::Threading](../../)
* 라이브러리 [Aspose.Slides](../../../)