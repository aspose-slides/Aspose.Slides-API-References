---
title: init_format_scheme_from method
second_title: Aspose.Slides for Python via .NET API 레퍼런스
description: 
type: docs
url: /ko/aspose.slides.theme/ioverridetheme/init_format_scheme_from/
weight: 100
---
## init_format_scheme_from(self, format_scheme) {#iformatscheme}
새 객체를 사용하여 InheritedTheme의 FormatScheme을 재정의하도록 FormatScheme을 초기화합니다.


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
| **RuntimeError(Proxy error(InvalidOperationException))** | FormatScheme이 이미 초기화된 경우(None이 아님) 발생합니다. |
| **RuntimeError(Proxy error(ArgumentNullException))** | formatScheme 매개변수가 None인 경우 발생합니다. |



### 참고
* 클래스 [`IFormatScheme`](/slides/python-net/ko/aspose.slides.theme/iformatscheme)
* 클래스 [`IOverrideTheme`](/slides/python-net/ko/aspose.slides.theme/ioverridetheme)
* 모듈 [`aspose.slides.theme`](/slides/python-net/ko/aspose.slides.theme)
* 라이브러리 [`Aspose.Slides`](/slides/python-net)