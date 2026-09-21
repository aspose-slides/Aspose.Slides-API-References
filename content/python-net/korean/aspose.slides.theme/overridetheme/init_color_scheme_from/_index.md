---
title: init_color_scheme_from method
second_title: Aspose.Slides for Python용 .NET API 레퍼런스
description: 
type: docs
url: /ko/aspose.slides.theme/overridetheme/init_color_scheme_from/
weight: 40
---
## init_color_scheme_from(self, color_scheme) {#icolorscheme}
새 객체로 ColorScheme을 초기화하여 InheritedTheme의 ColorScheme을 재정의합니다.

```python
def init_color_scheme_from(self, color_scheme):
    ...
```

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| color_scheme | [`IColorScheme`](/slides/python-net/ko/aspose.slides.theme/icolorscheme) | 초기화에 사용할 데이터. |

### 예외

| 예외 | 설명 |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | ColorScheme이 이미 초기화된 경우(값이 None이 아님) 발생합니다. |
| **RuntimeError(Proxy error(ArgumentNullException))** | colorScheme 매개변수가 None인 경우 발생합니다. |

### 참고
* 클래스 [`IColorScheme`](/slides/python-net/ko/aspose.slides.theme/icolorscheme)
* 클래스 [`OverrideTheme`](/slides/python-net/ko/aspose.slides.theme/overridetheme)
* 모듈 [`aspose.slides.theme`](/slides/python-net/ko/aspose.slides.theme)
* 라이브러리 [`Aspose.Slides`](/slides/python-net)