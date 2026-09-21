---
title: init_format_scheme_from method
second_title: Aspose.Slides for Python via .NET API 레퍼런스
description: 
type: docs
url: /ko/aspose.slides.theme/overridetheme/init_format_scheme_from/
weight: 100
---
## init_format_scheme_from(self, format_scheme) {#iformatscheme}
InheritedTheme의 FormatScheme을 재정의하기 위해 새 객체로 FormatScheme을 초기화합니다.

```python
def init_format_scheme_from(self, format_scheme):
    ...
```

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| format_scheme | [`IFormatScheme`](/slides/python-net/ko/aspose.slides.theme/iformatscheme) | 초기화할 데이터. |

### 예외

| 예외 | 설명 |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | FormatScheme이 이미 초기화된 경우( None이 아닌 경우) 발생합니다. |
| **RuntimeError(Proxy error(ArgumentNullException))** | formatScheme 매개변수가 None인 경우 발생합니다. |

### 참조
* 클래스 [`IFormatScheme`](/slides/python-net/ko/aspose.slides.theme/iformatscheme)
* 클래스 [`OverrideTheme`](/slides/python-net/ko/aspose.slides.theme/overridetheme)
* 모듈 [`aspose.slides.theme`](/slides/python-net/ko/aspose.slides.theme)
* 라이브러리 [`Aspose.Slides`](/slides/python-net)