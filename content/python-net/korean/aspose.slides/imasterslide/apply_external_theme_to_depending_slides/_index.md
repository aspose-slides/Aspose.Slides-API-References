---
title: apply_external_theme_to_depending_slides method
second_title: Aspose.Slides Python용 .NET API 레퍼런스
description: 
type: docs
url: /ko/aspose.slides/imasterslide/apply_external_theme_to_depending_slides/
weight: 10
---
## apply_external_theme_to_depending_slides(self, fname) {#str}
현재 슬라이드를 기반으로 새 마스터 슬라이드를 생성하고 외부 테마를 적용한 뒤, 생성된 마스터 슬라이드를 모든 종속 슬라이드에 적용합니다.

### 반환값

New themed MasterSlide.



```python
def apply_external_theme_to_depending_slides(self, fname):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| fname | **str** | 외부 테마 파일(.thmx)의 경로. |

### 예외

| Exception | Description |
| :- | :- |
| [`PptxReadException`](/slides/python-net/ko/aspose.slides/pptxreadexception) | 외부 테마를 적용할 수 없을 때. |



### 참고
* 클래스 [`IMasterSlide`](/slides/python-net/ko/aspose.slides/imasterslide)
* 클래스 [`PptxReadException`](/slides/python-net/ko/aspose.slides/pptxreadexception)
* 모듈 [`aspose.slides`](/slides/python-net/ko/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)