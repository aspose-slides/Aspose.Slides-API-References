---
title: ZoomObject
second_title: Aspose.Sildes for .NET API 레퍼런스
description: 슬라이드에서 Zoom 객체를 나타냅니다.
type: docs
weight: 11870
url: /ko/aspose.slides/zoomobject/
---
## ZoomObject 클래스

슬라이드에서 Zoom 객체를 나타냅니다.

```csharp
public class ZoomObject : GraphicalObject, IZoomObject
```

## 속성

| 이름 | 설명 |
| --- | --- |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | 형태와 연결된 대체 텍스트를 반환하거나 설정합니다. 읽기/쓰기 String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | 형태와 연결된 대체 텍스트의 제목을 반환하거나 설정합니다. 읽기/쓰기 String. |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | 속성은 형태가 흑백 디스플레이 모드에서 어떻게 렌더링되는지를 지정합니다. 읽기/쓰기 [`BlackWhiteMode`](../blackwhitemode). |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | 형태의 연결 지점 수를 반환합니다. 읽기 전용 Int32. |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | 형태의 사용자 정의 데이터를 반환합니다. 읽기 전용 [`ICustomData`](../icustomdata). |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | 형태에 적용된 픽셀 효과를 포함하는 EffectFormat 객체를 반환합니다. 참고: 효과 속성이 없는 특정 유형의 형태에 대해서는 null을 반환할 수 있습니다. 읽기 전용 [`IEffectFormat`](../ieffectformat). |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | 형태에 대한 채우기 서식 속성을 포함하는 FillFormat 객체를 반환합니다. 참고: 채우기 속성이 없는 특정 유형의 형태에 대해서는 null을 반환할 수 있습니다. 읽기 전용 [`IFillFormat`](../ifillformat). |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | 형태 프레임의 속성을 반환하거나 설정합니다. 읽기/쓰기 [`IShapeFrame`](../ishapeframe). |
| [GraphicalObjectLock](../../aspose.slides/graphicalobject/graphicalobjectlock) { get; } | 형태의 잠금을 반환합니다. 읽기 전용 [`IGraphicalObjectLock`](../igraphicalobjectlock). |
| [Height](../../aspose.slides/shape/height) { get; set; } | 포인트 단위로 측정된 형태의 높이를 가져오거나 설정합니다. 읽기/쓰기 Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | 형태가 숨겨져 있는지를 결정합니다. 읽기/쓰기 Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | 마우스 클릭에 정의된 하이퍼링크를 반환하거나 설정합니다. 읽기/쓰기 [`IHyperlink`](../ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | 하이퍼링크 관리자를 반환합니다. 읽기 전용 [`IHyperlinkManager`](../ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | 마우스 오버에 정의된 하이퍼링크를 반환하거나 설정합니다. 읽기/쓰기 [`IHyperlink`](../ihyperlink). |
| [ImageType](../../aspose.slides/zoomobject/imagetype) { get; set; } | Zoom 객체의 이미지 종류를 가져오거나 설정합니다. 읽기/쓰기 [`ZoomImageType`](../zoomimagetype). 기본값: Preview |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | 장식용으로 표시 옵션을 가져오거나 설정합니다. 읽기/쓰기 Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | 형태가 그룹화되어 있는지를 결정합니다. 읽기 전용 Boolean. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | 형태가 TextHolder_PPT인지 여부를 결정합니다. 읽기 전용 Boolean. |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | 형태에 대한 선 서식 속성을 포함하는 LineFormat 객체를 반환합니다. 참고: 선 속성이 없는 특정 유형의 형태에 대해서는 null을 반환할 수 있습니다. 읽기 전용 [`ILineFormat`](../ilineformat). |
| [Name](../../aspose.slides/shape/name) { get; set; } | 형태의 이름을 반환하거나 설정합니다. null이 될 수 없습니다. 필요하면 빈 문자열을 사용하십시오. 읽기/쓰기 String. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | 형태의 수명 동안 일정하게 유지되는 슬라이드 범위 고유 식별자를 반환하며, PowerPoint 또는 인터롭 코드가 문서 어디서든 해당 형태를 신뢰성 있게 참조할 수 있게 합니다. 읽기 전용 UInt32. 또한 [`UniqueId`](../shape/uniqueid)를 참조하십시오. |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | 형태가 그룹화되어 있으면 상위 GroupShape 객체를 반환합니다. 그렇지 않으면 null을 반환합니다. 읽기 전용 [`IGroupShape`](../igroupshape). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | 형태의 자리표시자를 반환합니다. 형태에 자리표시자가 없으면 null을 반환합니다. 읽기 전용 [`IPlaceholder`](../iplaceholder). |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | 슬라이드의 상위 프레젠테이션을 반환합니다. 읽기 전용 [`IPresentation`](../ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | 원시 형태 프레임의 속성을 반환하거나 설정합니다. 읽기/쓰기 [`IShapeFrame`](../ishapeframe). |
| [ReturnToParent](../../aspose.slides/zoomobject/returntoparent) { get; set; } | 슬라이드쇼에서 네비게이션 동작을 가져오거나 설정합니다. 읽기/쓰기 Boolean. 기본값: false |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | 지정된 형태가 z축을 중심으로 회전한 각도를 반환하거나 설정합니다. 양수 값은 시계 방향 회전을 의미하고, 음수 값은 반시계 방향 회전을 의미합니다. 읽기/쓰기 Single. |
| [ShapeLock](../../aspose.slides/graphicalobject/shapelock) { get; } | 형태의 잠금을 반환합니다. 읽기 전용 [`IGraphicalObjectLock`](../igraphicalobjectlock). (2개 속성) |
| [ShowBackground](../../aspose.slides/zoomobject/showbackground) { get; set; } | Zoom이 대상 슬라이드의 배경을 사용할지 여부를 지정하는 값을 가져오거나 설정합니다. 읽기/쓰기 Boolean. 기본값: true |
| [Slide](../../aspose.slides/shape/slide) { get; } | 형태의 상위 슬라이드를 반환합니다. 읽기 전용 [`IBaseSlide`](../ibaseslide). |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | 형태의 3D 효과 속성을 포함하는 ThreeDFormat 객체를 반환합니다. 참고: 3D 속성이 없는 특정 유형의 형태에 대해서는 null을 반환할 수 있습니다. 읽기 전용 [`IThreeDFormat`](../ithreedformat). |
| [TransitionDuration](../../aspose.slides/zoomobject/transitionduration) { get; set; } | Zoom과 슬라이드 사이 전환 지속 시간을 가져오거나 설정합니다. 읽기/쓰기 Single. 기본값: 1.0f |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | 애드인이나 기타 코드에서 사용하도록 설계된 내부 프레젠테이션 범위 식별자를 반환합니다. 이 값은 사용자 또는 프로그램에 의해 재할당될 수 있으므로 지속적인 고유 키로 취급해서는 안 됩니다. 읽기 전용 UInt32. 또한 [`OfficeInteropShapeId`](../shape/officeinteropshapeid)를 참조하십시오. |
| [Width](../../aspose.slides/shape/width) { get; set; } | 포인트 단위로 측정된 형태의 너비를 가져오거나 설정합니다. 읽기/쓰기 Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | 포인트 단위로 측정된 형태 좌측 상단 모서리의 x좌표를 가져오거나 설정합니다. 읽기/쓰기 Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | 포인트 단위로 측정된 형태 좌측 상단 모서리의 y좌표를 가져오거나 설정합니다. 읽기/쓰기 Single. |
| [ZoomImage](../../aspose.slides/zoomobject/zoomimage) { get; set; } | Zoom 객체의 이미지를 가져오거나 설정합니다. 읽기/쓰기 [`IPPImage`](../ippimage). |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | z-순서에서 형태의 위치를 반환합니다. Shapes[0]은 z-순서 뒤쪽에 있는 형태를 반환하고, Shapes[Shapes.Count - 1]은 앞쪽에 있는 형태를 반환합니다. 읽기 전용 Int32. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | 새 자리표시자가 없을 경우 새 자리표시자를 추가하고 지정된 자리표시자에 속성을 설정합니다. |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | 기본 자리표시자 형태를 반환합니다(현재 형태가 상속받은 레이아웃 및/또는 마스터 슬라이드의 형태). 현재 형태가 상속받지 않은 경우 null을 반환합니다. |
| [GetImage](../../aspose.slides/shape/getimage)() | 형태 썸네일을 반환합니다. 기본적으로 ShapeThumbnailBounds.Shape 형태 썸네일 경계 유형이 사용됩니다. |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | 형태 썸네일을 반환합니다. |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | 렌더링된 콘텐츠를 기반으로 계산된 형태의 시각적 경계를 가져옵니다. |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | 이 형태가 자리표시자가 아님을 정의합니다. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | 형태의 내용을 SVG 파일로 저장합니다. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | 형태의 내용을 SVG 파일로 저장합니다. |

### 참조

* 클래스 [GraphicalObject](../graphicalobject)
* 인터페이스 [IZoomObject](../izoomobject)
* 네임스페이스 [Aspose.Slides](../../aspose.slides)
* 어셈블리 [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->