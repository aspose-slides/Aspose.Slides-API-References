---
title: name property
second_title: Aspose.Slides for Python via .NET API 참조
description: 
type: docs
url: /ko/aspose.slides/color/name/
weight: 190
---
## name 속성
이 색상의 이름을 가져옵니다.<br/>            이름이 지정된 색상( `Color.red`와 같은 이름이 지정된 상수이거나 [`from_name`](/slides/python-net/ko/aspose.slides/color/from_name/) 로 생성된 색상) 에 대해 .NET 이름이 반환됩니다, e.g. `"Red"` 또는 `"LightBlue"`.<br/>            다른 모든 색상에 대해서는 ARGB 값이 앞에 0을 채우지 않은 소문자 16진수 문자열로 반환됩니다, e.g. `"ffff0000"`. `Color.empty.name` 은 `"0"` 입니다.            읽기 전용 **str**.

### 정의:
```python
@property
def name(self):
    ...
```

### 참조
* 클래스 [`Color`](/slides/python-net/ko/aspose.slides/color)
* 모듈 [`aspose.slides`](/slides/python-net/ko/aspose.slides)
* 라이브러리 [`Aspose.Slides`](/slides/python-net)