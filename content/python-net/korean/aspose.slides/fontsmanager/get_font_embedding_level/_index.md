---
title: get_font_embedding_level method
second_title: Aspose.Slides for Python via .NET API 레퍼런스
description: 
type: docs
url: /ko/aspose.slides/fontsmanager/get_font_embedding_level/
weight: 40
---
## get_font_embedding_level(self, font_bytes, font_name) {#bytes-str}
주어진 바이트 배열과 글꼴 이름에서 글꼴의 임베딩 레벨을 결정합니다.

### 반환값

지정된 글꼴의 임베딩 레벨.



```python
def get_font_embedding_level(self, font_bytes, font_name):
    ...
```


| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| font_bytes | **bytes** | 글꼴 데이터를 포함하는 바이트 배열. |
| font_name | **str** | 글꼴의 이름. |

### 예외

| 예외 | 설명 |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | `font_bytes`가 None인 경우 발생합니다. |



### 참고
* 열거형 [`EmbeddingLevel`](/slides/python-net/ko/aspose.slides/embeddinglevel)
* 클래스 [`FontsManager`](/slides/python-net/ko/aspose.slides/fontsmanager)
* 모듈 [`aspose.slides`](/slides/python-net/ko/aspose.slides)
* 라이브러리 [`Aspose.Slides`](/slides/python-net)