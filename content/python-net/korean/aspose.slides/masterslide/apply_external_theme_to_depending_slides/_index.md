---
title: apply_external_theme_to_depending_slides method
second_title: Aspose.Slides for Python via .NET API 레퍼런스
description: 
type: docs
url: /ko/aspose.slides/masterslide/apply_external_theme_to_depending_slides/
weight: 10
---
## apply_external_theme_to_depending_slides(self, fname) {#str}
현재 슬라이드를 기준으로 새로운 마스터 슬라이드를 생성하고 외부 테마를 적용한 뒤, 생성된 마스터 슬라이드를 모든 종속 슬라이드에 적용합니다.

### 반환값

새로운 테마가 적용된 MasterSlide.



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
| [`PptxReadException`](/slides/python-net/ko/aspose.slides/pptxreadexception) | 외부 테마를 적용할 수 없는 경우. |



### 관련 항목
* 클래스 [`IMasterSlide`](/slides/python-net/ko/aspose.slides/imasterslide)
* 클래스 [`MasterSlide`](/slides/python-net/ko/aspose.slides/masterslide)
* 클래스 [`PptxReadException`](/slides/python-net/ko/aspose.slides/pptxreadexception)
* 모듈 [`aspose.slides`](/slides/python-net/ko/aspose.slides)
* 라이브러리 [`Aspose.Slides`](/slides/python-net)