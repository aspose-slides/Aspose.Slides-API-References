---
title: remove method
second_title: Aspose.Slides for Python via .NET API 레퍼런스
description: 
type: docs
url: /ko/aspose.slides/icommentcollection/remove/
weight: 60
---
## remove(self, comment) {#icomment}
컬렉션에서 지정된 주석의 첫 번째 발생을 제거합니다.


```python
def remove(self, comment):
    ...
```

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| comment | [`IComment`](/slides/python-net/ko/aspose.slides/icomment) | 컬렉션에서 제거할 주석. |

### 예외

| 예외 | 설명 |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | comment가 `None`인 경우 |
| [`PptxEditException`](/slides/python-net/ko/aspose.slides/pptxeditexception) | comment가 이미 제거된 경우 발생합니다. |

### 참조
* 클래스 [`IComment`](/slides/python-net/ko/aspose.slides/icomment)
* 클래스 [`ICommentCollection`](/slides/python-net/ko/aspose.slides/icommentcollection)
* 클래스 [`PptxEditException`](/slides/python-net/ko/aspose.slides/pptxeditexception)
* 모듈 [`aspose.slides`](/slides/python-net/ko/aspose.slides)
* 라이브러리 [`Aspose.Slides`](/slides/python-net)