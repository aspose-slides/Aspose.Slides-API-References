---
title: SmartArtNode class
second_title: Aspose.Slides for Python via .NET API 레퍼런스
description: 
type: docs
url: /ko/aspose.slides.smartart/smartartnode/
---
## SmartArtNode 클래스

SmartArt 객체의 노드를 나타냅니다

SmartArtNode 형식은 다음 멤버를 노출합니다:

## 속성

| Property | Description |
| :- | :- |
| [`child_nodes`](/slides/python-net/ko/aspose.slides.smartart/smartartnode/child_nodes/) | 현재 노드의 모든 자식 노드 컬렉션을 반환합니다.<br/>읽기 전용 [`ISmartArtNodeCollection`](/slides/python-net/ko/aspose.slides.smartart/ismartartnodecollection). |
| [`shapes`](/slides/python-net/ko/aspose.slides.smartart/smartartnode/shapes/) | 노드와 연관된 모든 도형의 컬렉션을 반환합니다.<br/>읽기 전용 [`ISmartArtShapeCollection`](/slides/python-net/ko/aspose.slides.smartart/ismartartshapecollection). |
| [`text_frame`](/slides/python-net/ko/aspose.slides.smartart/smartartnode/text_frame/) | 노드의 텍스트 프레임을 반환합니다.<br/>읽기 전용 [`ITextFrame`](/slides/python-net/ko/aspose.slides/itextframe). |
| [`is_assistant`](/slides/python-net/ko/aspose.slides.smartart/smartartnode/is_assistant/) | 노드를 보조 노드로 반환하거나 설정합니다.<br/>읽기/쓰기 **bool**. |
| [`level`](/slides/python-net/ko/aspose.slides.smartart/smartartnode/level/) | 노드의 중첩 수준을 반환합니다.<br/>읽기 전용 **int**. |
| [`bullet_fill_format`](/slides/python-net/ko/aspose.slides.smartart/smartartnode/bullet_fill_format/) | 노드 불릿의 채우기 서식 속성을 포함하는 FillFormat 객체를 반환합니다.<br/>참고: 특정 유형의 SmartArt 레이아웃에서는 노드에 불릿을 제공하지 않아 None을 반환할 수 있습니다.<br/>읽기 전용 [`IFillFormat`](/slides/python-net/ko/aspose.slides/ifillformat). |
| [`position`](/slides/python-net/ko/aspose.slides.smartart/smartartnode/position/) | 형제 노드 중에서 노드의 0 기반 위치를 반환하거나 설정합니다.<br/>읽기/쓰기 **int**. |
| [`is_hidden`](/slides/python-net/ko/aspose.slides.smartart/smartartnode/is_hidden/) | 데이터 모델에서 이 노드가 숨겨진 노드이면 true를 반환합니다.<br/>읽기 전용 **bool**. |
| [`organization_chart_layout`](/slides/python-net/ko/aspose.slides.smartart/smartartnode/organization_chart_layout/) | 현재 노드와 연관된 조직도 레이아웃 유형을 반환하거나 설정합니다.<br/>읽기/쓰기 [`OrganizationChartLayoutType`](/slides/python-net/ko/aspose.slides.smartart/organizationchartlayouttype). |

## 메서드

| Method | Description |
| :- | :- |
| [`remove(self)`](/slides/python-net/ko/aspose.slides.smartart/smartartnode/remove/#) | 현재 노드를 제거합니다. |

### 참조
* 모듈 [`aspose.slides.smartart`](/slides/python-net/ko/aspose.slides.smartart)
* 라이브러리 [`Aspose.Slides`](/slides/python-net)