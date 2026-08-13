---
title: ForceStaticCast()
second_title: Aspose.Slides for C++ API 참조
description: SmartPtr 객체에 실제 정적 캐스트를 수행합니다.
type: docs
weight: 2588
url: /ko/system/forcestaticcast/
---
## System::ForceStaticCast(SmartPtr\<TFrom\> const\&) 함수


실제 정적 캐스트를 [SmartPtr](../smartptr/) 객체에 수행합니다.

```cpp
template<typename TTo,typename TFrom> CastResult<TTo>::type System::ForceStaticCast(SmartPtr<TFrom> const &obj)
```


### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| TTo | Target pointee type. |
| TFrom | Source pointee type. |

### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| obj | [SmartPtr](../smartptr/)\<TFrom\> const\& | Source pointer. |

### 반환 값

캐스트가 허용되면 캐스트 결과를 반환하고, 그렇지 않으면 동작은 정의되지 않습니다.

## 관련 항목

* 클래스 [SmartPtr](../smartptr/)
* 구조체 [CastResult](../castresult/)
* 네임스페이스 [System](../)
* 라이브러리 [Aspose.Slides](../../)