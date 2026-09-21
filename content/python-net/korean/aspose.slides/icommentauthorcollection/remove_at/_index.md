---
title: remove_at method
second_title: Aspose.Slides for Python via .NET API 레퍼런스
description: 
type: docs
url: /ko/aspose.slides/icommentauthorcollection/remove_at/
weight: 60
---
## remove_at(self, index) {#int}
컬렉션에서 지정된 인덱스에 있는 저자를 제거합니다.

```python
def remove_at(self, index):
    ...
```

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| index | **int** | 제거할 요소의 0 기반 인덱스 |

### 예외

| 예외 | 설명 |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | 인덱스가 0보다 작거나 인덱스가 Count와 같거나 그보다 큽니다 |
| [`PptxEditException`](/slides/python-net/ko/aspose.slides/pptxeditexception) | 작성자가 이미 제거된 경우 발생합니다 |

### 참조
* 클래스 [`ICommentAuthorCollection`](/slides/python-net/ko/aspose.slides/icommentauthorcollection)
* 클래스 [`PptxEditException`](/slides/python-net/ko/aspose.slides/pptxeditexception)
* 모듈 [`aspose.slides`](/slides/python-net/ko/aspose.slides)
* 라이브러리 [`Aspose.Slides`](/slides/python-net)