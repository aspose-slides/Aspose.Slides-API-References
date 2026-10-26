---
title: get_font_embedding_level method
second_title: Aspose.Slides for Python via .NET API 레퍼런스
description: 
type: docs
url: /ko/aspose.slides/ifontsmanager/get_font_embedding_level/
weight: 40
---
## get_font_embedding_level(self, font_bytes, font_name) {#bytes-str}
지정된 바이트 배열과 폰트 이름을 사용하여 폰트의 임베딩 레벨을 결정합니다.

### 반환값

지정된 폰트의 임베딩 레벨입니다.



```python
def get_font_embedding_level(self, font_bytes, font_name):
    ...
```


| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| font_bytes | **bytes** | 폰트 데이터를 포함하는 바이트 배열. |
| font_name | **str** | 폰트의 이름. |

### 예외

| 예외 | 설명 |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | `font_bytes`가 None인 경우 발생합니다. |



### 참고
* 열거형 [`EmbeddingLevel`](/slides/python-net/ko/aspose.slides/embeddinglevel)
* 클래스 [`IFontsManager`](/slides/python-net/ko/aspose.slides/ifontsmanager)
* 모듈 [`aspose.slides`](/slides/python-net/ko/aspose.slides)
* 라이브러리 [`Aspose.Slides`](/slides/python-net)