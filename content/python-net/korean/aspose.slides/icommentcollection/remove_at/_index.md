---
title: remove_at method
second_title: Aspose.Slides for Python via .NET API 레퍼런스
description: 
type: docs
url: /ko/aspose.slides/icommentcollection/remove_at/
weight: 70
---
## remove_at(self, index) {#int}
컬렉션에서 지정된 인덱스에 있는 요소를 제거합니다.


```python
def remove_at(self, index):
    ...
```


| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| index | **int** | 제거할 요소의 0부터 시작하는 인덱스입니다. |

### 예외

| 예외 | 설명 |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | 인덱스가 0보다 작거나 인덱스가 Count보다 크거나 같습니다 |
| [`PptxEditException`](/slides/python-net/ko/aspose.slides/pptxeditexception) | 이미 댓글이 제거된 경우 발생합니다. |



### 참고
* 클래스 [`ICommentCollection`](/slides/python-net/ko/aspose.slides/icommentcollection)
* 클래스 [`PptxEditException`](/slides/python-net/ko/aspose.slides/pptxeditexception)
* 모듈 [`aspose.slides`](/slides/python-net/ko/aspose.slides)
* 라이브러리 [`Aspose.Slides`](/slides/python-net)