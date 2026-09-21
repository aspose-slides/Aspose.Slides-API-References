---
title: path_types property
second_title: Aspose.Slides for Python via .NET API 레퍼런스
description: 
type: docs
url: /ko/aspose.slides/shapeelement/path_types/
weight: 40
---
## path_types 속성
요소의 경로에 있는 각 점의 유형을 지정하는 바이트 값 배열을 가져옵니다.
            
**0** 해당 점이 도형의 시작임을 나타냅니다.

**1** 해당 점이 선의 두 끝점 중 하나임을 나타냅니다.

**3** 해당 점이 3차 베지어 스플라인의 끝점 또는 제어점임을 나타냅니다.

**7** 점 유형을 나타내는 세 개의 저순위 비트를 제외한 모든 비트를 마스킹합니다.

**16** 해당 세그먼트가 점선임을 지정합니다.

**32** 해당 점이 마커임을 지정합니다.

**128** 해당 점이 닫힌 하위 경로(도형)의 마지막 점임을 지정합니다.

**129** 해당 점이 선 세그먼트의 끝점이면서 닫힌 하위 경로의 마지막 점인 데이터 포인트임을 나타냅니다.

### 정의:
```python
@property
def path_types(self):
    ...
```

### 참고
* 클래스 [`ShapeElement`](/slides/python-net/ko/aspose.slides/shapeelement)
* 모듈 [`aspose.slides`](/slides/python-net/ko/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)