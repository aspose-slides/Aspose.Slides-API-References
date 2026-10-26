---
title: interruption_token property
second_title: Aspose.Slides for Python via .NET API 참조
description: 
type: docs
url: /ko/aspose.slides/iloadoptions/interruption_token/
weight: 80
---
## interruption_token 속성
중단 요청을 감시하기 위한 토큰입니다.

이 토큰은 전체 [`IPresentation`](/slides/python-net/ko/aspose.slides/ipresentation) 인스턴스 수명 주기를 관리합니다. 프레젠테이션 로드 또는 저장과 같은 장기 실행 작업은 [`IInterruptionTokenSource.interrupt`](/slides/python-net/ko/aspose.slides/iinterruptiontokensource/interrupt) 메서드를 호출하여 [`IInterruptionTokenSource`](/slides/python-net/ko/aspose.slides/iinterruptiontokensource)에 의해 중단됩니다.

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
* 클래스 [`IInterruptionTokenSource`](/slides/python-net/ko/aspose.slides/iinterruptiontokensource)
* 클래스 [`ILoadOptions`](/slides/python-net/ko/aspose.slides/iloadoptions)
* 클래스 [`IPresentation`](/slides/python-net/ko/aspose.slides/ipresentation)
* 모듈 [`aspose.slides`](/slides/python-net/ko/aspose.slides)
* 라이브러리 [`Aspose.Slides`](/slides/python-net)