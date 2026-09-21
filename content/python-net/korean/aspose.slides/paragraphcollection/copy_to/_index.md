---
title: copy_to method
second_title: Aspose.Slides for Python via .NET API 참조
description: 
type: docs
url: /ko/aspose.slides/paragraphcollection/copy_to/
weight: 50
---
## copy_to(self, array, array_index) {#listiparagraph-int}
**System.Collections.Generic.ICollection`1**의 요소를 **System.Array**에 복사합니다. 복사는 특정 **System.Array** 인덱스에서 시작합니다.

```python
def copy_to(self, array, array_index):
    ...
```

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| array | **List[IParagraph]** | 복사된 요소들이 **System.Collections.Generic.ICollection`1**에서 복사되어 들어가는 일차원 **System.Array**입니다. **System.Array**는 0 기반 인덱스를 가져야 합니다. |
| array_index | **int** | `array`에서 복사가 시작되는 0 기반 인덱스입니다. |

### 예외

| 예외 | 설명 |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | `array`가 None입니다. |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | `array_index`가 0보다 작습니다. |
| **RuntimeError(Proxy error(ArgumentException))** | 소스 **System.Collections.Generic.ICollection`1**의 요소 수가 `array_index`부터 대상 `array` 끝까지의 사용 가능한 공간보다 큽니다. |

### 참고
* 클래스 [`ParagraphCollection`](/slides/python-net/ko/aspose.slides/paragraphcollection)
* 모듈 [`aspose.slides`](/slides/python-net/ko/aspose.slides)
* 라이브러리 [`Aspose.Slides`](/slides/python-net)