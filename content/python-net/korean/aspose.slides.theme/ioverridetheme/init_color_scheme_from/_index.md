---
title: init_color_scheme_from method
second_title: Aspose.Slides for Python via .NET API 참조
description: 
type: docs
url: /ko/aspose.slides.theme/ioverridetheme/init_color_scheme_from/
weight: 40
---
## init_color_scheme_from(self, color_scheme) {#icolorscheme}
InheritedTheme의 ColorScheme을 오버라이드하기 위해 새로운 객체로 ColorScheme을 초기화합니다.

```python
def init_color_scheme_from(self, color_scheme):
    ...
```

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| color_scheme | [`IColorScheme`](/slides/python-net/ko/aspose.slides.theme/icolorscheme) | 초기화에 사용할 데이터. |

### 예외

| 예외 | 설명 |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | ColorScheme이 이미 초기화된 경우( None이 아닌 경우) 발생합니다. |
| **RuntimeError(Proxy error(ArgumentNullException))** | colorScheme 매개변수가 None인 경우 발생합니다. |

### 참고
* 클래스 [`IColorScheme`](/slides/python-net/ko/aspose.slides.theme/icolorscheme)
* 클래스 [`IOverrideTheme`](/slides/python-net/ko/aspose.slides.theme/ioverridetheme)
* 모듈 [`aspose.slides.theme`](/slides/python-net/ko/aspose.slides.theme)
* 라이브러리 [`Aspose.Slides`](/slides/python-net)