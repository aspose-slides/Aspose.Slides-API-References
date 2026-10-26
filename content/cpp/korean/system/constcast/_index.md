---
title: ConstCast()
second_title: Aspose.Slides for C++ API 참조
description: 더 이상 사용되지 않는 캐스트의 끝.
type: docs
weight: 2575
url: /ko/system/constcast/
---
## System::ConstCast(const SmartPtr\<TFrom\>\&) 함수


더 이상 사용되지 않는 캐스트의 끝.

```cpp
template<typename TTo,typename TFrom> CastResult<TTo>::type System::ConstCast(const SmartPtr<TFrom> &obj)
```


### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| TTo | 대상 포인티 유형. |
| TFrom | 소스 포인티 유형. |

### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| obj | const [SmartPtr](../smartptr/)\<TFrom\>\& | 소스 포인터. |

### 반환값

캐스트가 허용되면 캐스트 결과를 반환하고, 그렇지 않으면 nullptr를 반환합니다.

## 비고


[SmartPtr](../smartptr/) 객체에 대해 const 캐스트를 수행합니다. 

## 참고

* 클래스 [SmartPtr](../smartptr/)
* 구조체 [CastResult](../castresult/)
* 네임스페이스 [System](../)
* 라이브러리 [Aspose.Slides](../../)