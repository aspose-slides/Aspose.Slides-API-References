---
title: ShapeElement class
second_title: Aspose.Slides for Python via .NET API 레퍼런스
description: 
type: docs
url: /ko/aspose.slides/shapeelement/
---
## ShapeElement 클래스

동일한 윤곽선 및 채우기 속성을 가진 모양의 일부를 나타냅니다.

ShapeElement 형식은 다음 멤버를 노출합니다:

## 속성

| 속성 | 설명 |
| :- | :- |
| [`parent_shape`](/slides/python-net/ko/aspose.slides/shapeelement/parent_shape/) | 요소가 생성된 Shape_PPT를 반환합니다.<br/>            읽기 전용 [`Shape`](/slides/python-net/ko/aspose.slides/shape). |
| [`path_points`](/slides/python-net/ko/aspose.slides/shapeelement/path_points/) | 요소 경로의 기하학을 정의하는 점들의 배열을 가져옵니다. |
| [`path_types`](/slides/python-net/ko/aspose.slides/shapeelement/path_types/) | 요소 경로의 각 점 유형을 지정하는 바이트 값 배열을 가져옵니다. <br/>            <br/>**0**  점이 도형의 시작임을 나타냅니다.<br/><br/><br/>**1**  점이 선의 두 끝점 중 하나임을 나타냅니다.<br/><br/><br/>**3**  점이 3차 베지어 스플라인의 끝점 또는 제어점임을 나타냅니다.<br/><br/><br/>**7**  점 유형을 나타내는 세 개의 하위 비트를 제외한 모든 비트를 마스킹합니다.<br/><br/><br/>**16**  해당 구간이 점선임을 지정합니다.<br/><br/><br/>**32**  점이 마커임을 지정합니다.<br/><br/><br/>**128**  점이 닫힌 하위 경로(도형)의 마지막 점임을 지정합니다.<br/><br/><br/>**129**  점이 선 구간의 끝점이면서 닫힌 하위 경로의 마지막 점인 데이터 포인트임을 나타냅니다. |
| [`fill_source`](/slides/python-net/ko/aspose.slides/shapeelement/fill_source/) | 요소를 채우는 방법에 대한 정보를 반환합니다.<br/>            읽기 전용 [`ShapeElementFillSource`](/slides/python-net/ko/aspose.slides/shapeelementfillsource). |
| [`stroke_source`](/slides/python-net/ko/aspose.slides/shapeelement/stroke_source/) | 요소를 윤곽선 처리하는 방법에 대한 정보를 반환합니다.<br/>            읽기 전용 [`ShapeElementStrokeSource`](/slides/python-net/ko/aspose.slides/shapeelementstrokesource). |

### 참조
* 모듈 [`aspose.slides`](/slides/python-net/ko/aspose.slides)
* 라이브러리 [`Aspose.Slides`](/slides/python-net)