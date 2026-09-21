---
title: copy_to method
second_title: Aspose.Slides for Python via .NET API 레퍼런스
description: 
type: docs
url: /ko/aspose.slides.animation/behaviorcollection/copy_to/
weight: 40
---
## copy_to(self, array, array_index) {#listibehavior-int}
**System.Collections.Generic.ICollection`1**의 요소를 **System.Array**에 복사하며, 특정 **System.Array** 인덱스에서 시작합니다.

```python
def copy_to(self, array, array_index):
    ...
```

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| array | **List[IBehavior]** | 복사된 **System.Collections.Generic.ICollection`1** 요소들의 대상이 되는 1차원 **System.Array**입니다. **System.Array**는 0부터 시작하는 인덱스를 가져야 합니다. |
| array_index | **int** | `array`에서 복사가 시작되는 0 기반 인덱스입니다. |

### 예외

| 예외 | 설명 |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | `array`는 None입니다. |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | `array_index`는 0보다 작습니다. |
| **RuntimeError(Proxy error(ArgumentException))** | 소스 **System.Collections.Generic.ICollection`1**의 요소 수가 대상 `array`의 `array_index`부터 끝까지 사용 가능한 공간보다 큽니다. |

### 참고
* 클래스 [`BehaviorCollection`](/slides/python-net/ko/aspose.slides.animation/behaviorcollection)
* 모듈 [`aspose.slides.animation`](/slides/python-net/ko/aspose.slides.animation)
* 라이브러리 [`Aspose.Slides`](/slides/python-net)