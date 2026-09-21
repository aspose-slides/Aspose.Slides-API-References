---
title: presentation_locking_behavior property
second_title: Aspose.Slides for Python via .NET API 참조
description: 
type: docs
url: /ko/aspose.slides/iblobmanagementoptions/presentation_locking_behavior/
weight: 30
---
## presentation_locking_behavior 속성
이 속성은 Presentation 클래스의 인스턴스가 수명 동안 소스(파일 또는 스트림)의 소유자가 될 수 있는지를 정의합니다. 인스턴스가 소유자인 경우 소스를 잠급니다. 이는 BLOB를 사용할 때 메모리 사용량과 성능을 개선하는 데 도움이 되지만, 소스(스트림 또는 파일)는 Presentation 인스턴스의 수명 동안 변경할 수 없습니다. 다음은 예시입니다:

### 정의:
```python
@property
def presentation_locking_behavior(self):
    ...

@presentation_locking_behavior.setter
def presentation_locking_behavior(self, value):
    ...
```

### 참고
* 클래스 [`IBlobManagementOptions`](/slides/python-net/ko/aspose.slides/iblobmanagementoptions)
* 모듈 [`aspose.slides`](/slides/python-net/ko/aspose.slides)
* 라이브러리 [`Aspose.Slides`](/slides/python-net)