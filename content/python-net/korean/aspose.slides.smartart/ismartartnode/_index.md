---
title: ISmartArtNode class
second_title: Aspose.Slides for Python via .NET API 레퍼런스
description: 
type: docs
url: /ko/aspose.slides.smartart/ismartartnode/
---
## ISmartArtNode 클래스

SmartArt 다이어그램의 노드를 나타냅니다.

ISmartArtNode 형식은 다음 멤버를 노출합니다:

## 속성

| 속성 | 설명 |
| :- | :- |
| [`child_nodes`](/slides/python-net/ko/aspose.slides.smartart/ismartartnode/child_nodes/) | 현재 노드의 모든 하위 노드 컬렉션을 반환합니다.<br/>            읽기 전용 [`ISmartArtNodeCollection`](/slides/python-net/ko/aspose.slides.smartart/ismartartnodecollection). |
| [`shapes`](/slides/python-net/ko/aspose.slides.smartart/ismartartnode/shapes/) | 노드와 연관된 모든 도형의 컬렉션을 반환합니다.<br/>            읽기 전용 [`ISmartArtShapeCollection`](/slides/python-net/ko/aspose.slides.smartart/ismartartshapecollection). |
| [`text_frame`](/slides/python-net/ko/aspose.slides.smartart/ismartartnode/text_frame/) | 노드의 텍스트를 반환하거나 설정합니다.<br/>            읽기 전용 [`ITextFrame`](/slides/python-net/ko/aspose.slides/itextframe). |
| [`is_assistant`](/slides/python-net/ko/aspose.slides.smartart/ismartartnode/is_assistant/) | 노드를 보조 노드로 반환하거나 설정합니다.<br/>            읽기/쓰기 **bool**. |
| [`level`](/slides/python-net/ko/aspose.slides.smartart/ismartartnode/level/) | 노드의 중첩 수준을 반환합니다.<br/>            읽기 전용 **int**. |
| [`bullet_fill_format`](/slides/python-net/ko/aspose.slides.smartart/ismartartnode/bullet_fill_format/) | 노드 글머리표에 대한 채우기 서식 속성을 포함하는 FillFormat 객체를 반환합니다.<br/>            참고: 노드에 글머리표를 제공하지 않는 특정 SmartArt 레이아웃 유형의 경우 None을 반환할 수 있습니다.<br/>            읽기 전용 [`IFillFormat`](/slides/python-net/ko/aspose.slides/ifillformat). |
| [`position`](/slides/python-net/ko/aspose.slides.smartart/ismartartnode/position/) | 형제 노드 사이에서 노드의 0 기반 위치를 반환하거나 설정합니다.<br/>            읽기/쓰기 **int**. |
| [`is_hidden`](/slides/python-net/ko/aspose.slides.smartart/ismartartnode/is_hidden/) | 이 노드가 데이터 모델에서 숨겨진 노드인 경우 true를 반환합니다.<br/>            읽기 전용 **bool**. |
| [`organization_chart_layout`](/slides/python-net/ko/aspose.slides.smartart/ismartartnode/organization_chart_layout/) | 현재 노드와 연관된 조직도 레이아웃 유형을 반환하거나 설정합니다.<br/>            읽기/쓰기 [`OrganizationChartLayoutType`](/slides/python-net/ko/aspose.slides.smartart/organizationchartlayouttype). |

## 메서드

| 메서드 | 설명 |
| :- | :- |
| [`remove(self)`](/slides/python-net/ko/aspose.slides.smartart/ismartartnode/remove/#) | 현재 노드를 제거합니다. |

### 참조
* 모듈 [`aspose.slides.smartart`](/slides/python-net/ko/aspose.slides.smartart)
* 라이브러리 [`Aspose.Slides`](/slides/python-net)