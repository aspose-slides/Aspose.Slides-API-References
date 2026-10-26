---
title: copy_to method
second_title: Aspose.Slides for Python via .NET API 레퍼런스
description: 
type: docs
url: /ko/aspose.slides/portioncollection/copy_to/
weight: 40
---
## copy_to(self, array, array_index) {#listiportion-int}
**System.Collections.Generic.ICollection`1**의 요소를 **System.Array**에 복사하며, 특정 **System.Array** 인덱스에서 시작합니다.


```python
def copy_to(self, array, array_index):
    ...
```


| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| array | **List[IPortion]** | 복사된 요소가 저장되는 일차원 **System.Array**입니다. **System.Array**는 0 기반 인덱싱을 가져야 합니다. |
| array_index | **int** | `array`에서 복사가 시작되는 0 기반 인덱스입니다. |

### 예외

| 예외 | 설명 |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | `array`가 None입니다. |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | `array_index`가 0보다 작습니다. |
| **RuntimeError(Proxy error(ArgumentException))** | 소스 **System.Collections.Generic.ICollection`1**의 요소 수가 `array_index`부터 대상 `array` 끝까지의 사용 가능한 공간보다 많습니다. |



### 참고
* 클래스 [`PortionCollection`](/slides/python-net/ko/aspose.slides/portioncollection)
* 모듈 [`aspose.slides`](/slides/python-net/ko/aspose.slides)
* 라이브러리 [`Aspose.Slides`](/slides/python-net)