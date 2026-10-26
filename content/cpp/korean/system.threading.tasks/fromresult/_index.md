---
title: FromResult()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 지정된 결과와 함께 성공적으로 완료된 작업을 생성합니다.
type: docs
weight: 144
url: /ko/system.threading.tasks/fromresult/
---
## System::Threading::Tasks::FromResult(TResult) 함수

지정된 결과와 함께 성공적으로 완료된 작업을 생성합니다.

```cpp
template<typename TResult> RTaskPtr<TResult> System::Threading::Tasks::FromResult(TResult result)
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| TResult | 작업 결과의 유형입니다. |

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| result | TResult | 작업을 완료할 결과 값입니다. |

### 반환값

성공적으로 완료된 작업입니다.

## 또 보기

* Typedef [RTaskPtr](../../system/rtaskptr/)
* 네임스페이스 [System::Threading::Tasks](../)
* 라이브러리 [Aspose.Slides](../../)