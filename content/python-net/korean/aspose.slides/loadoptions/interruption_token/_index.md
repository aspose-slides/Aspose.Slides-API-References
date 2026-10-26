---
title: interruption_token property
second_title: Aspose.Slides for Python via .NET API 레퍼런스
description: 
type: docs
url: /ko/aspose.slides/loadoptions/interruption_token/
weight: 90
---
## interruption_token 속성
중단 요청을 모니터링하기 위한 토큰입니다.
            
            이 토큰은 전체 [`IPresentation`](/slides/python-net/ko/aspose.slides/ipresentation) 인스턴스 수명을 관리합니다. 프레젠테이션을 로드하거나 저장하는 등 장기 실행 작업은 [`InterruptionTokenSource`](/slides/python-net/ko/aspose.slides/interruptiontokensource)의 [`InterruptionTokenSource.interrupt`](/slides/python-net/ko/aspose.slides/interruptiontokensource/interrupt) 메서드를 호출하여 중단됩니다.

### 정의:
```python
@property
def interruption_token(self):
    ...

@interruption_token.setter
def interruption_token(self, value):
    ...
```


### 참조
* 클래스 [`InterruptionTokenSource`](/slides/python-net/ko/aspose.slides/interruptiontokensource)
* 클래스 [`IPresentation`](/slides/python-net/ko/aspose.slides/ipresentation)
* 클래스 [`LoadOptions`](/slides/python-net/ko/aspose.slides/loadoptions)
* 모듈 [`aspose.slides`](/slides/python-net/ko/aspose.slides)
* 라이브러리 [`Aspose.Slides`](/slides/python-net)