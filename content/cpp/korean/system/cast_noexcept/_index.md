---
title: Cast_noexcept()
second_title: Aspose.Slides for C++ API 레퍼런스
description: SmartPtr 객체에 대한 캐스트를 수행합니다.
type: docs
weight: 2497
url: /ko/system/cast_noexcept/
---
## System::Cast_noexcept(SmartPtr\<TFrom\> const\&) function


[SmartPtr](../smartptr/) 객체에 대한 캐스트를 수행합니다.

```cpp
template<typename TTo,typename TFrom> std::enable_if<!IsExceptionWrapper<TTo>::value, typenameCastResult<TTo>::type>::type System::Cast_noexcept(SmartPtr<TFrom> const &obj)
```


### 템플릿 매개변수

| Parameter | Description |
| --- | --- |
| TTo | 대상 포인티 타입. |
| TFrom | 소스 포인티 타입. |

### 인수

| Parameter | Type | Description |
| --- | --- | --- |
| obj | [SmartPtr](../smartptr/)\<TFrom\> const\& | 소스 포인터. |

### 반환값

캐스트가 허용되면 캐스트 결과를 반환하고, 그렇지 않으면 nullptr를 반환합니다.

## 관련 항목

* 클래스 [SmartPtr](../smartptr/)
* 구조체 [IsExceptionWrapper](../isexceptionwrapper/)
* 네임스페이스 [System](../)
* 라이브러리 [Aspose.Slides](../../)