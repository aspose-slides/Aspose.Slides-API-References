---
title: Ink
second_title: Aspose.Sildes for .NET API 참조
description: 슬라이드에 있는 잉크 객체를 나타냅니다.
type: docs
weight: 7550
url: /ko/aspose.slides.ink/ink/
---
## Ink 클래스

슬라이드에 있는 잉크 객체를 나타냅니다.

```csharp
public class Ink : GraphicalObject, IInk
```

## 속성

| 이름 | 설명 |
| --- | --- |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | 도형과 연결된 대체 텍스트를 반환하거나 설정합니다. 읽기/쓰기 String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | 도형과 연결된 대체 텍스트의 제목을 반환하거나 설정합니다. 읽기/쓰기 String. |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | 속성은 도형이 흑백 디스플레이 모드에서 렌더링되는 방식을 지정합니다. 읽기/쓰기 [`BlackWhiteMode`](../../aspose.slides/blackwhitemode). |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | 도형의 연결 지점 수를 반환합니다. 읽기 전용 Int32. |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | 도형의 사용자 정의 데이터를 반환합니다. 읽기 전용 [`ICustomData`](../../aspose.slides/icustomdata). |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | 도형에 적용된 픽셀 효과를 포함하는 EffectFormat 객체를 반환합니다. 참고: 효과 속성이 없는 특정 유형의 도형에 대해서는 null을 반환할 수 있습니다. 읽기 전용 [`IEffectFormat`](../../aspose.slides/ieffectformat). |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | 도형의 채우기 서식 속성을 포함하는 FillFormat 객체를 반환합니다. 참고: 채우기 속성이 없는 특정 유형의 도형에 대해 null을 반환할 수 있습니다. 읽기 전용 [`IFillFormat`](../../aspose.slides/ifillformat). |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | 도형 프레임의 속성을 반환하거나 설정합니다. 읽기/쓰기 [`IShapeFrame`](../../aspose.slides/ishapeframe). |
| [GraphicalObjectLock](../../aspose.slides/graphicalobject/graphicalobjectlock) { get; } | 도형의 잠금을 반환합니다. 읽기 전용 [`IGraphicalObjectLock`](../../aspose.slides/igraphicalobjectlock). |
| [Height](../../aspose.slides/shape/height) { get; set; } | 도형의 높이를 포인트 단위로 가져오거나 설정합니다. 읽기/쓰기 Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | 도형이 숨겨져 있는지 여부를 결정합니다. 읽기/쓰기 Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | 마우스 클릭에 정의된 하이퍼링크를 반환하거나 설정합니다. 읽기/쓰기 [`IHyperlink`](../../aspose.slides/ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | 하이퍼링크 관리자를 반환합니다. 읽기 전용 [`IHyperlinkManager`](../../aspose.slides/ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | 마우스 오버에 정의된 하이퍼링크를 반환하거나 설정합니다. 읽기/쓰기 [`IHyperlink`](../../aspose.slides/ihyperlink). |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | ‘데코레이션으로 표시’ 옵션을 가져오거나 설정합니다. 읽기/쓰기 Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | 도형이 그룹화되어 있는지 여부를 결정합니다. 읽기 전용 Boolean. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | 도형이 TextHolder_PPT인지 여부를 결정합니다. 읽기 전용 Boolean. |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | 도형의 선 서식 속성을 포함하는 LineFormat 객체를 반환합니다. 참고: 선 속성이 없는 특정 유형의 도형에 대해 null을 반환할 수 있습니다. 읽기 전용 [`ILineFormat`](../../aspose.slides/ilineformat). |
| [Name](../../aspose.slides/shape/name) { get; set; } | 도형의 이름을 반환하거나 설정합니다. null이 될 수 없습니다. 필요하면 빈 문자열을 사용하십시오. 읽기/쓰기 String. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | 도형의 전체 수명 동안 일정하게 유지되는 슬라이드 범위 고유 식별자를 반환합니다. 이 식별자는 PowerPoint 또는 인터옵 코드가 문서 어디에서든 도형을 신뢰성 있게 참조할 수 있게 합니다. 읽기 전용 UInt32. 또한 [`UniqueId`](../../aspose.slides/shape/uniqueid)를 참조하십시오. |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | 도형이 그룹화된 경우 상위 GroupShape 객체를 반환합니다. 그렇지 않으면 null을 반환합니다. 읽기 전용 [`IGroupShape`](../../aspose.slides/igroupshape). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | 도형의 플레이스홀더를 반환합니다. 도형에 플레이스홀더가 없으면 null을 반환합니다. 읽기 전용 [`IPlaceholder`](../../aspose.slides/iplaceholder). |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | 슬라이드의 상위 프레젠테이션을 반환합니다. 읽기 전용 [`IPresentation`](../../aspose.slides/ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | 원시 shape 프레임의 속성을 반환하거나 설정합니다. 읽기/쓰기 [`IShapeFrame`](../../aspose.slides/ishapeframe). |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | 지정된 도형이 z축을 중심으로 회전된 각도를 반환하거나 설정합니다. 양수 값은 시계 방향 회전을 나타내고, 음수 값은 반시계 방향 회전을 나타냅니다. 읽기/쓰기 Single. |
| [ShapeLock](../../aspose.slides/graphicalobject/shapelock) { get; } | 도형의 잠금을 반환합니다. 읽기 전용 [`IGraphicalObjectLock`](../../aspose.slides/igraphicalobjectlock). (2개의 속성) |
| [Slide](../../aspose.slides/shape/slide) { get; } | 도형의 상위 슬라이드를 반환합니다. 읽기 전용 [`IBaseSlide`](../../aspose.slides/ibaseslide). |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | 도형의 3D 효과 속성을 포함하는 ThreeDFormat 객체를 반환합니다. 참고: 3D 속성이 없는 특정 유형의 도형에 대해 null을 반환할 수 있습니다. 읽기 전용 [`IThreeDFormat`](../../aspose.slides/ithreedformat). |
| [Traces](../../aspose.slides.ink/ink/traces) { get; } | IInk 요소 [`IInkTrace`](../iinktrace)에 포함된 모든 트레이스를 가져옵니다. 읽기 전용. |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | 추가 기능 또는 기타 코드에서 사용하도록 설계된 내부 프레젠테이션 범위 식별자를 반환합니다. 이 값은 사용자 또는 프로그램에 의해 재할당될 수 있으므로 지속적인 고유 키로 취급해서는 안 됩니다. 읽기 전용 UInt32. 또한 [`OfficeInteropShapeId`](../../aspose.slides/shape/officeinteropshapeid)를 참조하십시오. |
| [Width](../../aspose.slides/shape/width) { get; set; } | 도형의 너비를 포인트 단위로 가져오거나 설정합니다. 읽기/쓰기 Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | 도형의 왼쪽 위 모서리의 x 좌표를 포인트 단위로 가져오거나 설정합니다. 읽기/쓰기 Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | 도형의 왼쪽 위 모서리의 y 좌표를 포인트 단위로 가져오거나 설정합니다. 읽기/쓰기 Single. |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | z-순서에서 도형의 위치를 반환합니다. Shapes[0]은 z-순서 뒤쪽에 있는 도형을 반환하고, Shapes[Shapes.Count - 1]은 앞쪽에 있는 도형을 반환합니다. 읽기 전용 Int32. |
| static [InkEffectImages](../../aspose.slides.ink/ink/inkeffectimages) { get; } | 잉크 브러시의 시각 효과를 시뮈레이션하기 위해 사용되는 사용자 정의 이미지 컬렉션을 가져옵니다. 이러한 이미지는 Galaxy, Rainbow 등과 같은 특정 [`InkEffectType`](../inkeffecttype) 값을 사용하여 잉크를 렌더링할 때 사용됩니다. 자체 이미지를 제공하면 각 잉크 효과의 표시 방식을 제어할 수 있습니다. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | 새 플레이스홀더가 없을 경우 새 플레이스홀더를 추가하고 지정된 플레이스홀더에 속성을 설정합니다. |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | 현재 도형이 상속되지 않은 경우 null을 반환하고, 현재 도형이 상속받은 레이아웃 및/또는 마스터 슬라이드의 기본 플레이스홀더 형태(모양)를 반환합니다. |
| [GetImage](../../aspose.slides/shape/getimage)() | 도형 썸네일을 반환합니다. 기본적으로 ShapeThumbnailBounds.Shape 도형 썸네일 경계 유형이 사용됩니다. |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | 도형 썸네일을 반환합니다. |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | 렌더링된 콘텐츠에서 계산된 도형의 시각적 경계를 가져옵니다. |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | 이 도형이 플레이스홀더가 아님을 정의합니다. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | Shape의 내용을 SVG 파일로 저장합니다. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | Shape의 내용을 SVG 파일로 저장합니다. |

### 참조

* 클래스 [GraphicalObject](../../aspose.slides/graphicalobject)
* 인터페이스 [IInk](../iink)
* 네임스페이스 [Aspose.Slides.Ink](../../aspose.slides.ink)
* 어셈블리 [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->