---
title: CachedEnumerable()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 
type: docs
weight: 1
url: /ko/system.linq.details/cachedenumerable/cachedenumerable/
---
## CachedEnumerable::CachedEnumerable(System::Func\<bool\>) 생성자



```cpp
System::Linq::Details::CachedEnumerable<TItem>::CachedEnumerable(System::Func<bool> requestNext)
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| requestNext | [System::Func](../../../system/func/)\<**bool**\> | 다음 항목이 필요할 때 호출되는 콜백입니다. 더 이상 항목이 없을 때 false를 반환하고 다음 항목을 삽입하려면 Add 메서드를 사용해야 합니다. |

## 참조

* 클래스 [Func](../../../system/func/)
* 클래스 [CachedEnumerable](../)
* 네임스페이스 [System::Linq::Details](../../)
* 라이브러리 [Aspose.Slides](../../../)