---
title: AsposeAIWebClient constructor
second_title: .NET API 참조를 통한 Aspose.Slides for Python
description: 
type: docs
url: /ko/aspose.slides.ai/asposeaiwebclient/__init__/
weight: 10
---
## __init__(self) {#}
Aspose AI 웹 클라이언트의 인스턴스를 생성하며, 기본 Aspose LLM 엔드포인트에 연결합니다.
            이 클라이언트는 매개변수가 없는 **SlidesAIAgent.#ctor** 생성자에서 사용되므로,
            **Aspose.Slides.AI.SlidesAIAgent.#ctor(Aspose.Slides.A** 생성자에 직접 클라이언트를 전달할 때만
            명시적으로 생성하면 됩니다.


```python
def __init__(self):
    ...
```



## __init__(self, url) {#str}
Aspose AI 웹 클라이언트의 인스턴스를 생성하며, 사용자 정의 엔드포인트 URL에 연결합니다. 이
            오버로드는 Aspose.Slides 팀에서 제공한 URL이 있는 경우에 사용하고, 그렇지 않다면
            기본 URL을 사용하는 **AsposeAIWebClient.#ctor** 오버로드를 사용하십시오.


```python
def __init__(self, url):
    ...
```


| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| url | **str** | Aspose LLM의 엔드포인트 URL이며, Aspose.Slides 팀에서 제공합니다. |

### 예외

| 예외 | 설명 |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | URL은 None 이거나 비어 있을 수 없습니다. |



### 관련 내용
* 클래스 [`AsposeAIWebClient`](/slides/python-net/ko/aspose.slides.ai/asposeaiwebclient)
* 모듈 [`aspose.slides.ai`](/slides/python-net/ko/aspose.slides.ai)
* 라이브러리 [`Aspose.Slides`](/slides/python-net)