---
title: MemberwiseClone()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 복사 생성자를 사용하여 멤버별 복제를 수행합니다.
type: docs
weight: 2601
url: /ko/system/memberwiseclone/
---
## System::MemberwiseClone(T *) 함수

복사 생성자를 사용하여 멤버별 복제를 수행합니다.

```cpp
template<typename T> SmartPtr<Object> System::MemberwiseClone(T *ptr)
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| T | 복사 생성될 클래스. 하위 클래스 정보는 손실됩니다. |

### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| ptr | T * | 복제할 객체에 대한 포인터. |

### 반환값

복제된 객체에 대한 포인터.

## 참조

* 클래스 [SmartPtr](../smartptr/)
* 클래스 [Object](../object/)
* 네임스페이스 [System](../)
* 라이브러리 [Aspose.Slides](../../)