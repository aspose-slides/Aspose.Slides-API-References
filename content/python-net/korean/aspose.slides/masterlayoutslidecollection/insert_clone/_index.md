---
title: insert_clone method
second_title: Aspose.Slides for Python via .NET API 레퍼런스
description: 
type: docs
url: /ko/aspose.slides/masterlayoutslidecollection/insert_clone/
weight: 50
---
## insert_clone(self, index, source_layout) {#int-ilayoutslide}
지정된 레이아웃 슬라이드의 복사본을 컬렉션의 지정된 위치에 삽입합니다.

### 반환

삽입된 슬라이드.



```python
def insert_clone(self, index, source_layout):
    ...
```


| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| index | **int** | 새 슬라이드의 인덱스. |
| source_layout | [`ILayoutSlide`](/slides/python-net/ko/aspose.slides/ilayoutslide) | 복제할 슬라이드. |

### 비고

새 레이아웃은 이 레이아웃 슬라이드 컬렉션의 상위 마스터 슬라이드와 연결됩니다. 
            따라서 이는 PowerPoint의 "Use Destination Theme" 옵션을 사용한 복사/붙여넣기와 동일합니다.



### 참조
* 클래스 [`ILayoutSlide`](/slides/python-net/ko/aspose.slides/ilayoutslide)
* 클래스 [`MasterLayoutSlideCollection`](/slides/python-net/ko/aspose.slides/masterlayoutslidecollection)
* 모듈 [`aspose.slides`](/slides/python-net/ko/aspose.slides)
* 라이브러리 [`Aspose.Slides`](/slides/python-net)