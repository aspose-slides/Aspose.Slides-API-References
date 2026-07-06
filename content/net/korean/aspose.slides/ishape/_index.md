---
title: IShape
second_title: Aspose.Sildes for .NET API 레퍼런스
description: 슬라이드의 도형을 나타냅니다.
type: docs
weight: 6950
url: /ko/aspose.slides/ishape/
---
## IShape 인터페이스

슬라이드에 있는 도형을 나타냅니다.

```csharp
public interface IShape : IHyperlinkContainer, ISlideComponent
```

## 속성

| 이름 | 설명 |
| --- | --- |
| [AlternativeText](../../aspose.slides/ishape/alternativetext) { get; set; } | 도형과 연결된 대체 텍스트를 반환하거나 설정합니다. 읽기/쓰기 String. |
| [AlternativeTextTitle](../../aspose.slides/ishape/alternativetexttitle) { get; set; } | 도형과 연결된 대체 텍스트의 제목을 반환하거나 설정합니다. 읽기/쓰기 String. |
| [AsIHyperlinkContainer](../../aspose.slides/ishape/asihyperlinkcontainer) { get; } | 기본 IHyperlinkContainer 인터페이스를 가져올 수 있습니다. 읽기 전용 [`IHyperlinkContainer`](../ihyperlinkcontainer). |
| [AsISlideComponent](../../aspose.slides/ishape/asislidecomponent) { get; } | 기본 ISlideComponent 인터페이스를 가져올 수 있습니다. 읽기 전용 [`ISlideComponent`](../islidecomponent). |
| [BlackWhiteMode](../../aspose.slides/ishape/blackwhitemode) { get; set; } | 속성은 도형이 흑백 디스플레이 모드에서 렌더링되는 방식을 지정합니다. 읽기/쓰기 [`BlackWhiteMode`](../blackwhitemode). |
| [ConnectionSiteCount](../../aspose.slides/ishape/connectionsitecount) { get; } | 도형의 연결 지점 수를 반환합니다. 읽기 전용 Int32. |
| [CustomData](../../aspose.slides/ishape/customdata) { get; } | 도형의 커스텀 데이터를 반환합니다. 읽기 전용 [`ICustomData`](../icustomdata). |
| [EffectFormat](../../aspose.slides/ishape/effectformat) { get; } | 도형에 적용된 픽셀 효과를 포함하는 EffectFormat 객체를 반환합니다. 읽기 전용 [`IEffectFormat`](../ieffectformat). |
| [FillFormat](../../aspose.slides/ishape/fillformat) { get; } | 도형의 채우기 서식 속성을 포함하는 FillFormat 객체를 반환합니다. 읽기 전용 [`IFillFormat`](../ifillformat). |
| [Frame](../../aspose.slides/ishape/frame) { get; set; } | 도형 프레임의 속성을 반환하거나 설정합니다. 읽기/쓰기 [`IShapeFrame`](../ishapeframe). |
| [Height](../../aspose.slides/ishape/height) { get; set; } | 도형의 높이를 포인트 단위로 가져오거나 설정합니다. 읽기/쓰기 Single. |
| [Hidden](../../aspose.slides/ishape/hidden) { get; set; } | 도형이 숨김 상태인지 여부를 결정합니다. 읽기/쓰기 Boolean. |
| [IsDecorative](../../aspose.slides/ishape/isdecorative) { get; set; } | ‘장식용으로 표시’ 옵션을 가져오거나 설정합니다. 읽기/쓰기 Boolean. |
| [IsGrouped](../../aspose.slides/ishape/isgrouped) { get; } | 도형이 그룹화되어 있는지 여부를 결정합니다. 읽기 전용 Boolean. |
| [IsTextHolder](../../aspose.slides/ishape/istextholder) { get; } | 도형이 TextHolder인지 여부를 결정합니다. 읽기 전용 Boolean. |
| [LineFormat](../../aspose.slides/ishape/lineformat) { get; } | 도형의 선 서식 속성을 포함하는 LineFormat 객체를 반환합니다. 읽기 전용 [`ILineFormat`](../ilineformat). |
| [Name](../../aspose.slides/ishape/name) { get; set; } | 도형의 이름을 반환하거나 설정합니다. 읽기/쓰기 String. |
| [OfficeInteropShapeId](../../aspose.slides/ishape/officeinteropshapeid) { get; } | 도형의 수명 동안 일정하게 유지되는 슬라이드 범위 고유 식별자를 반환하며, PowerPoint 또는 인터옵 코드가 문서 어디에서든 도형을 안정적으로 참조할 수 있게 합니다. 읽기 전용 UInt32. 또한 [`UniqueId`](./uniqueid)를 참조하십시오. |
| [ParentGroup](../../aspose.slides/ishape/parentgroup) { get; } | 도형이 그룹화된 경우 상위 GroupShape 객체를 반환합니다. 그렇지 않으면 null을 반환합니다. 읽기 전용 [`IGroupShape`](../igroupshape). |
| [Placeholder](../../aspose.slides/ishape/placeholder) { get; } | 도형에 대한 자리표시자를 반환합니다. 읽기 전용 [`IPlaceholder`](../iplaceholder). |
| [RawFrame](../../aspose.slides/ishape/rawframe) { get; set; } | 원시 도형 프레임의 속성을 반환하거나 설정합니다. 읽기/쓰기 [`IShapeFrame`](../ishapeframe). |
| [Rotation](../../aspose.slides/ishape/rotation) { get; set; } | 지정된 도형이 z축을 중심으로 회전된 각도를 반환하거나 설정합니다. 양수 값은 시계 방향 회전을 나타내고, 음수 값은 반시계 방향 회전을 나타냅니다. 읽기/쓰기 Single. |
| [ShapeLock](../../aspose.slides/ishape/shapelock) { get; } | 도형의 잠금을 반환합니다. 읽기 전용 [`IBaseShapeLock`](../ibaseshapelock). |
| [ThreeDFormat](../../aspose.slides/ishape/threedformat) { get; } | 도형의 선 서식 속성을 포함하는 ThreeDFormat 객체를 반환합니다. 읽기 전용 [`IThreeDFormat`](../ithreedformat). |
| [UniqueId](../../aspose.slides/ishape/uniqueid) { get; } | 부가 기능이나 기타 코드에서 사용하도록 의도된 내부 프레젠테이션 범위 식별자를 반환합니다. 이 값은 사용자 또는 프로그래밍에 의해 재할당될 수 있으므로 지속적인 고유 키로 취급해서는 안 됩니다. 읽기 전용 UInt32. 또한 [`OfficeInteropShapeId`](./officeinteropshapeid)를 참조하십시오. |
| [Width](../../aspose.slides/ishape/width) { get; set; } | 도형의 너비를 포인트 단위로 가져오거나 설정합니다. 읽기/쓰기 Single. |
| [X](../../aspose.slides/ishape/x) { get; set; } | 도형의 왼쪽 위 모서리의 x좌표를 포인트 단위로 가져오거나 설정합니다. 읽기/쓰기 Single. |
| [Y](../../aspose.slides/ishape/y) { get; set; } | 도형의 왼쪽 위 모서리의 y좌표를 포인트 단위로 가져오거나 설정합니다. 읽기/쓰기 Single. |
| [ZOrderPosition](../../aspose.slides/ishape/zorderposition) { get; } | z-순서에서 도형의 위치를 반환합니다. Shapes[0]은 z-순서의 뒤쪽에 있는 도형을 반환하고, Shapes[Shapes.Count - 1]은 앞쪽에 있는 도형을 반환합니다. 읽기 전용 Int32. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/ishape/addplaceholder)(IPlaceholder) | 새 자리표시자가 없을 경우 새 자리표시자를 추가하고 지정된 자리표시자에 대한 속성을 설정합니다. |
| [GetBasePlaceholder](../../aspose.slides/ishape/getbaseplaceholder)() | 기본 자리표시자 도형을 반환합니다 (현재 도형이 상속받은 레이아웃 및/또는 마스터 슬라이드의 도형). 현재 도형이 상속받지 않은 경우 null을 반환합니다. |
| [GetImage](../../aspose.slides/ishape/getimage#getimage)() | 도형 썸네일을 반환합니다. 기본값으로 ShapeThumbnailBounds.Shape 도형 썸네일 경계 유형이 사용됩니다. |
| [GetImage](../../aspose.slides/ishape/getimage#getimage_1)(ShapeThumbnailBounds, float, float) | 도형 썸네일을 반환합니다. |
| [RemovePlaceholder](../../aspose.slides/ishape/removeplaceholder)() | 이 도형이 자리표시자가 아님을 정의합니다. |
| [WriteAsSvg](../../aspose.slides/ishape/writeassvg#writeassvg)(Stream) | 도형의 내용을 SVG 파일로 저장합니다. |
| [WriteAsSvg](../../aspose.slides/ishape/writeassvg#writeassvg_1)(Stream, ISVGOptions) | 도형의 내용을 SVG 파일로 저장합니다. |

### 참조

* 인터페이스 [IHyperlinkContainer](../ihyperlinkcontainer)
* 인터페이스 [ISlideComponent](../islidecomponent)
* 네임스페이스 [Aspose.Slides](../../aspose.slides)
* 어셈블리 [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->