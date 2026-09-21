---
title: add_clone method
second_title: Aspose.Slides for Python via .NET API 레퍼런스
description: 
type: docs
url: /ko/aspose.slides/igloballayoutslidecollection/add_clone/
weight: 20
---
## add_clone(self, source_layout) {#ilayoutslide}
지정된 레이아웃 슬라이드의 복사본을 프레젠테이션에 추가합니다.

### 반환값
추가된 슬라이드.

```python
def add_clone(self, source_layout):
    ...
```

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| source_layout | [`ILayoutSlide`](/slides/python-net/ko/aspose.slides/ilayoutslide) | 복제할 슬라이드. |

### 비고
다른 프레젠테이션 간에 레이아웃을 복제할 때 레이아웃의 마스터도 복제되어 원본 형식을 유지할 수 있습니다.
내부 레지스트리를 사용하여 자동으로 복제된 마스터를 추적하고 동일한 마스터 슬라이드의 다중 복제를 방지합니다.
마스터 슬라이드의 수동 복제는 방지되지 않으며 레지스트리에 기록되지 않습니다.

## add_clone(self, source_layout, dest_master) {#ilayoutslide-imasterslide}
지정된 레이아웃 슬라이드의 복사본을 프레젠테이션에 추가합니다.

### 반환값
추가된 슬라이드.

```python
def add_clone(self, source_layout, dest_master):
    ...
```

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| source_layout | [`ILayoutSlide`](/slides/python-net/ko/aspose.slides/ilayoutslide) | 복제할 슬라이드. |
| dest_master | [`IMasterSlide`](/slides/python-net/ko/aspose.slides/imasterslide) | 새 레이아웃의 마스터 슬라이드. |

### 비고
새 레이아웃은 대상 프레젠테이션에 정의된 마스터와 연결됩니다.
따라서 PowerPoint에서 "대상 테마 사용" 옵션을 선택한 복사/붙여넣기와 동일한 동작입니다.

### 참조
* 클래스 [`IGlobalLayoutSlideCollection`](/slides/python-net/ko/aspose.slides/igloballayoutslidecollection)
* 클래스 [`ILayoutSlide`](/slides/python-net/ko/aspose.slides/ilayoutslide)
* 클래스 [`IMasterSlide`](/slides/python-net/ko/aspose.slides/imasterslide)
* 모듈 [`aspose.slides`](/slides/python-net/ko/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)