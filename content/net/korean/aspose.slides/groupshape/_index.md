---
title: GroupShape
second_title: Aspose.Sildes for .NET API 레퍼런스
description: 슬라이드의 도형 그룹을 나타냅니다.
type: docs
weight: 5090
url: /ko/aspose.slides/groupshape/
---
## GroupShape 클래스

슬라이드에 있는 도형 그룹을 나타냅니다.

```csharp
public class GroupShape : Shape, IGroupShape
```

## 속성

| 이름 | 설명 |
| --- | --- |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | 모양과 연결된 대체 텍스트를 반환하거나 설정합니다. 읽기/쓰기 String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | 모양과 연결된 대체 텍스트의 제목을 반환하거나 설정합니다. 읽기/쓰기 String. |
| [AsIShape](../../aspose.slides/groupshape/asishape) { get; } | 기본 IShape 인터페이스를 가져올 수 있습니다. 읽기 전용 [`IShape`](../ishape). |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | 도형이 흑백 표시 모드에서 어떻게 렌더링되는지를 지정합니다. 읽기/쓰기 [`BlackWhiteMode`](../blackwhitemode). |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | 도형의 연결 지점 개수를 반환합니다. 읽기 전용 Int32. |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | 도형의 사용자 지정 데이터를 반환합니다. 읽기 전용 [`ICustomData`](../icustomdata). |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | 도형에 적용된 픽셀 효과를 포함하는 EffectFormat 개체를 반환합니다. 일부 도형 유형에서는 null을 반환할 수 있습니다. 읽기 전용 [`IEffectFormat`](../ieffectformat). |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | 도형에 대한 채우기 서식 속성을 포함하는 FillFormat 개체를 반환합니다. 일부 도형 유형에서는 null을 반환할 수 있습니다. 읽기 전용 [`IFillFormat`](../ifillformat). |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | 도형 프레임의 속성을 반환하거나 설정합니다. 읽기/쓰기 [`IShapeFrame`](../ishapeframe). |
| [GroupShapeLock](../../aspose.slides/groupshape/groupshapelock) { get; } | 도형의 잠금을 반환합니다. 읽기 전용 [`IGroupShapeLock`](../igroupshapelock). |
| [Height](../../aspose.slides/shape/height) { get; set; } | 도형의 높이를 포인트 단위로 가져오거나 설정합니다. 읽기/쓰기 Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | 도형이 숨겨져 있는지 여부를 결정합니다. 읽기/쓰기 Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | 마우스 클릭에 정의된 하이퍼링크를 반환하거나 설정합니다. 읽기/쓰기 [`IHyperlink`](../ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | 하이퍼링크 관리자를 반환합니다. 읽기 전용 [`IHyperlinkManager`](../ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | 마우스 오버에 정의된 하이퍼링크를 반환하거나 설정합니다. 읽기/쓰기 [`IHyperlink`](../ihyperlink). |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | ‘Mark as decorative’ 옵션을 가져오거나 설정합니다. 읽기/쓰기 Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | 도형이 그룹화되어 있는지 여부를 결정합니다. 읽기 전용 Boolean. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | 도형이 TextHolder_PPT인지 여부를 결정합니다. 읽기 전용 Boolean. |
| override [LineFormat](../../aspose.slides/groupshape/lineformat) { get; } | 도형의 선 서식 속성을 포함하는 LineFormat 개체를 반환합니다. GroupShape 개체는 선 속성이 없어 null을 반환합니다. 읽기 전용 [`ILineFormat`](../ilineformat). |
| [Name](../../aspose.slides/shape/name) { get; set; } | 도형의 이름을 반환하거나 설정합니다. null이 될 수 없으며 필요 시 빈 문자열을 사용합니다. 읽기/쓰기 String. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | 슬라이드 범위 내에서 고유한 식별자를 반환합니다. 이 식별자는 도형의 수명 동안 변하지 않으며 PowerPoint 또는 인터옵 코드가 문서 어디서든 도형을 신뢰성 있게 참조하도록 합니다. 읽기 전용 UInt32. 또한 [`UniqueId`](../shape/uniqueid)를 참조하십시오. |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | 도형이 그룹화된 경우 상위 GroupShape 객체를 반환합니다. 그렇지 않으면 null을 반환합니다. 읽기 전용 [`IGroupShape`](../igroupshape). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | 도형의 플레이스홀더를 반환합니다. 플레이스홀더가 없으면 null을 반환합니다. 읽기 전용 [`IPlaceholder`](../iplaceholder). |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | 슬라이드의 상위 프레젠테이션을 반환합니다. 읽기 전용 [`IPresentation`](../ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | 원시 도형 프레임의 속성을 반환하거나 설정합니다. 읽기/쓰기 [`IShapeFrame`](../ishapeframe). |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | 지정된 도형이 Z축을 중심으로 회전된 각도를 포인트 단위로 반환하거나 설정합니다. 양수 값은 시계 방향 회전을, 음수 값은 반시계 방향 회전을 나타냅니다. 읽기/쓰기 Single. |
| [ShapeLock](../../aspose.slides/groupshape/shapelock) { get; } | 도형의 잠금을 반환합니다. 읽기 전용 [`IGroupShapeLock`](../igroupshapelock). (속성 2개) |
| [Shapes](../../aspose.slides/groupshape/shapes) { get; } | 그룹 내부에 있는 도형 컬렉션을 반환합니다. 읽기 전용 [`IShapeCollection`](../ishapecollection). |
| [Slide](../../aspose.slides/shape/slide) { get; } | 도형이 속한 상위 슬라이드를 반환합니다. 읽기 전용 [`IBaseSlide`](../ibaseslide). |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | 도형의 3D 효과 속성을 포함하는 ThreeDFormat 개체를 반환합니다. 일부 도형 유형에서는 null을 반환할 수 있습니다. 읽기 전용 [`IThreeDFormat`](../ithreedformat). |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | 애드인이나 기타 코드에서 사용하도록 설계된 내부 프레젠테이션 범위 식별자를 반환합니다. 이 값은 사용자가 재할당하거나 프로그래밍 방식으로 변경할 수 있으므로 영구적인 고유 키로 취급하지 않아야 합니다. 읽기 전용 UInt32. 또한 [`OfficeInteropShapeId`](../shape/officeinteropshapeid)를 참조하십시오. |
| [Width](../../aspose.slides/shape/width) { get; set; } | 도형의 너비를 포인트 단위로 가져오거나 설정합니다. 읽기/쓰기 Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | 도형의 왼쪽 상단 모서리 X 좌표를 포인트 단위로 가져오거나 설정합니다. 읽기/쓰기 Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | 도형의 왼쪽 상단 모서리 Y 좌표를 포인트 단위로 가져오거나 설정합니다. 읽기/쓰기 Single. |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | Z 순서에서 도형의 위치를 반환합니다. Shapes[0]은 Z 순서의 뒤쪽에 있는 도형을, Shapes[Shapes.Count - 1]은 앞쪽에 있는 도형을 반환합니다. 읽기 전용 Int32. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | 플레이스홀더가 없을 경우 새 플레이스홀더를 추가하고 지정된 플레이스홀더 속성을 설정합니다. |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | 현재 도형이 상속된 레이아웃 또는 마스터 슬라이드의 기본 플레이스홀더 도형을 반환합니다. 상속되지 않은 경우 null을 반환합니다. |
| [GetImage](../../aspose.slides/shape/getimage)() | 도형 썸네일을 반환합니다. 기본값으로 ShapeThumbnailBounds.Shape 도형 썸네일 경계 유형이 사용됩니다. |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | 도형 썸네일을 반환합니다. |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | 렌더링된 내용으로부터 계산된 도형의 시각적 경계를 가져옵니다. |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | 이 도형이 플레이스홀더가 아님을 정의합니다. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | Shape의 내용을 SVG 파일로 저장합니다. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | Shape의 내용을 SVG 파일로 저장합니다. |

### 참고

* class [Shape](../shape)
* interface [IGroupShape](../igroupshape)
* namespace [Aspose.Slides](../../aspose.slides)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->