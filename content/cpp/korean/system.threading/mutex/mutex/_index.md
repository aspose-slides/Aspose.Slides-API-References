---
title: Mutex()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 소유되지 않은 뮤텍스를 생성합니다.
type: docs
weight: 1
url: /ko/system.threading/mutex/mutex/
---
## Mutex::Mutex() 생성자

소유되지 않은 뮤텍스를 생성합니다.

```cpp
System::Threading::Mutex::Mutex()
```

## Mutex::Mutex(bool) 생성자

생성자.

```cpp
System::Threading::Mutex::Mutex(bool initiallyOwned)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| initiallyOwned | **bool** | true이면, 생성되는 뮤텍스가 처음에 소유됩니다. |

## Mutex::Mutex(bool, const String\&) 생성자

생성자.

```cpp
System::Threading::Mutex::Mutex(bool initiallyOwned, const String &name)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| initiallyOwned | **bool** | true이면, 생성되는 뮤텍스가 처음에 소유됩니다. |
| name | const [String](../../../system/string/)\& | 뮤텍스의 이름. |

## 참고

* Class [Mutex](../)
* Class [String](../../../system/string/)
* Namespace [System::Threading](../../)
* Library [Aspose.Slides](../../../)