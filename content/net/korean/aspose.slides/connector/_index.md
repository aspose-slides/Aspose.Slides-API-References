---
title: Connector
second_title: Aspose.Sildes for .NET API 레퍼런스
description: 커넥터를 나타냅니다.
type: docs
weight: 2670
url: /ko/aspose.slides/connector/
---
## Connector 클래스

연결자를 나타냅니다.

```csharp
public class Connector : GeometryShape, IConnector
```

## 속성

| Name | Description |
| --- | --- |
| [Adjustments](../../aspose.slides/geometryshape/adjustments) { get; } | shape의 조정 값 컬렉션을 반환합니다. 읽기 전용 [`IAdjustValueCollection`](../iadjustvaluecollection). |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | shape와 연결된 대체 텍스트를 반환하거나 설정합니다. 읽기/쓰기 문자열. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | shape와 연결된 대체 텍스트의 제목을 반환하거나 설정합니다. 읽기/쓰기 문자열. |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | shape가 흑백 표시 모드에서 렌더링되는 방식을 지정합니다. 읽기/쓰기 [`BlackWhiteMode`](../blackwhitemode). |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | shape의 연결 지점 수를 반환합니다. 읽기 전용 Int32. |
| [ConnectorLock](../../aspose.slides/connector/connectorlock) { get; } | 커넥터의 잠금을 반환합니다. 읽기 전용 [`IConnectorLock`](../iconnectorlock). |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | shape의 사용자 정의 데이터를 반환합니다. 읽기 전용 [`ICustomData`](../icustomdata). |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | shape에 적용된 픽셀 효과를 포함하는 EffectFormat 객체를 반환합니다. 참고: 효과 속성이 없는 특정 shape 유형의 경우 null을 반환할 수 있습니다. 읽기 전용 [`IEffectFormat`](../ieffectformat). |
| [EndShapeConnectedTo](../../aspose.slides/connector/endshapeconnectedto) { get; set; } | 커넥터 끝을 연결할 shape를 반환하거나 설정합니다. 읽기/쓰기 [`IShape`](../ishape). |
| [EndShapeConnectionSiteIndex](../../aspose.slides/connector/endshapeconnectionsiteindex) { get; set; } | 끝 shape의 연결 지점 인덱스를 반환하거나 설정합니다. 읽기/쓰기 UInt32. |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | shape의 채우기 형식 속성을 포함하는 FillFormat 객체를 반환합니다. 참고: 채우기 속성이 없는 특정 shape 유형의 경우 null을 반환할 수 있습니다. 읽기 전용 [`IFillFormat`](../ifillformat). |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | shape 프레임의 속성을 반환하거나 설정합니다. 읽기/쓰기 [`IShapeFrame`](../ishapeframe). |
| [Height](../../aspose.slides/shape/height) { get; set; } | shape의 높이를 포인트 단위로 반환하거나 설정합니다. 읽기/쓰기 Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | shape가 숨겨져 있는지 여부를 결정합니다. 읽기/쓰기 Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | 마우스 클릭에 정의된 하이퍼링크를 반환하거나 설정합니다. 읽기/쓰기 [`IHyperlink`](../ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | 하이퍼링크 관리자를 반환합니다. 읽기 전용 [`IHyperlinkManager`](../ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | 마우스 오버에 정의된 하이퍼링크를 반환하거나 설정합니다. 읽기/쓰기 [`IHyperlink`](../ihyperlink). |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | 'Mark as decorative' 옵션을 가져오거나 설정합니다. 읽기/쓰기 Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | shape가 그룹화되어 있는지 여부를 결정합니다. 읽기 전용 Boolean. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | shape가 TextHolder_PPT인지 여부를 결정합니다. 읽기 전용 Boolean. |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | shape의 선 형식 속성을 포함하는 LineFormat 객체를 반환합니다. 참고: 선 속성이 없는 특정 shape 유형의 경우 null을 반환할 수 있습니다. 읽기 전용 [`ILineFormat`](../ilineformat). |
| [Name](../../aspose.slides/shape/name) { get; set; } | shape의 이름을 반환하거나 설정합니다. null이 될 수 없습니다. 필요한 경우 빈 문자열을 사용합니다. 읽기/쓰기 String. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | shape의 수명 동안 일정하게 유지되는 슬라이드 범위 고유 식별자를 반환하며, PowerPoint 또는 인터옵 코드가 문서 어디서든 shape를 신뢰하게 참조할 수 있게 합니다. 읽기 전용 UInt32. 또한 [`UniqueId`](../shape/uniqueid)을(를) 참조하십시오. |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | shape가 그룹화된 경우 상위 GroupShape 객체를 반환합니다. 그렇지 않으면 null을 반환합니다. 읽기 전용 [`IGroupShape`](../igroupshape). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | shape에 대한 플레이스홀더를 반환합니다. shape에 플레이스홀더가 없으면 null을 반환합니다. 읽기 전용 [`IPlaceholder`](../iplaceholder). |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | 슬라이드의 상위 프레젠테이션을 반환합니다. 읽기 전용 [`IPresentation`](../ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | 원시 shape 프레임의 속성을 반환하거나 설정합니다. 읽기/쓰기 [`IShapeFrame`](../ishapeframe). |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | 지정된 shape가 z축을 중심으로 회전된 각도를 반환하거나 설정합니다. 양수 값은 시계 방향 회전을, 음수 값은 반시계 방향 회전을 나타냅니다. 읽기/쓰기 Single. |
| [ShapeLock](../../aspose.slides/connector/shapelock) { get; } | shape의 잠금을 반환합니다. 읽기 전용 [`IConnectorLock`](../iconnectorlock). (2 속성) |
| [ShapeStyle](../../aspose.slides/geometryshape/shapestyle) { get; } | shape의 스타일 객체를 반환합니다. 읽기 전용 [`IShapeStyle`](../ishapestyle). |
| override [ShapeType](../../aspose.slides/connector/shapetype) { get; set; } | AutoShape 유형을 반환하거나 설정합니다. 읽기/쓰기 [`ShapeType`](../shapetype). |
| [Slide](../../aspose.slides/shape/slide) { get; } | shape의 상위 슬라이드를 반환합니다. 읽기 전용 [`IBaseSlide`](../ibaseslide). |
| [StartShapeConnectedTo](../../aspose.slides/connector/startshapeconnectedto) { get; set; } | 커넥터 시작을 연결할 shape를 반환하거나 설정합니다. 읽기/쓰기 [`IShape`](../ishape). |
| [StartShapeConnectionSiteIndex](../../aspose.slides/connector/startshapeconnectionsiteindex) { get; set; } | 시작 shape의 연결 지점 인덱스를 반환하거나 설정합니다. 읽기/쓰기 UInt32. |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | shape의 3D 효과 속성을 포함하는 ThreeDFormat 객체를 반환합니다. 참고: 3D 속성이 없는 특정 shape 유형의 경우 null을 반환할 수 있습니다. 읽기 전용 [`IThreeDFormat`](../ithreedformat). |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | 애드인 또는 기타 코드에서 사용하도록 설계된 내부 프레젠테이션 범위 식별자를 반환합니다. 이 값은 사용자 또는 프로그래밍 방식으로 재할당될 수 있으므로 지속적인 고유 키로 취급해서는 안 됩니다. 읽기 전용 UInt32. 또한 [`OfficeInteropShapeId`](../shape/officeinteropshapeid)을(를) 참조하십시오. |
| [Width](../../aspose.slides/shape/width) { get; set; } | shape의 너비를 포인트 단위로 반환하거나 설정합니다. 읽기/쓰기 Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | shape의 좌상단 모서리 x좌표를 포인트 단위로 반환하거나 설정합니다. 읽기/쓰기 Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | shape의 좌상단 모서리 y좌표를 포인트 단위로 반환하거나 설정합니다. 읽기/쓰기 Single. |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | z-순서에서 shape의 위치를 반환합니다. Shapes[0]은 z-순서의 맨 뒤에 있는 shape를 반환하고, Shapes[Shapes.Count - 1]은 앞쪽에 있는 shape를 반환합니다. 읽기 전용 Int32. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | 새 플레이스홀더가 없을 경우 새 플레이스홀더를 추가하고 지정된 플레이스홀더에 속성을 설정합니다. |
| [CreateShapeElements](../../aspose.slides/geometryshape/createshapeelements)() | shape의 요소 배열을 생성하고 반환합니다. |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | 기본 플레이스홀더 shape를 반환합니다(현재 shape가 상속받은 레이아웃 및/또는 마스터 슬라이드의 shape). 현재 shape가 상속받지 않은 경우 null을 반환합니다. |
| [GetGeometryPaths](../../aspose.slides/geometryshape/getgeometrypaths)() | 지오메트리 shape의 경로 복사본을 반환합니다. 좌표는 shape의 왼쪽 상단 모서리를 기준으로 합니다. |
| [GetImage](../../aspose.slides/shape/getimage)() | shape 썸네일을 반환합니다. 기본적으로 ShapeThumbnailBounds.Shape shape 썸네일 경계 유형이 사용됩니다. |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | shape 썸네일을 반환합니다. |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | rendered content에서 계산된 shape의 시각적 경계를 가져옵니다. |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | 이 shape가 플레이스홀더가 아님을 정의합니다. |
| [Reroute](../../aspose.slides/connector/reroute)() | 커넥터가 연결된 shape 사이의 가능한 가장 짧은 경로를 취하도록 재경로 설정합니다. |
| [SetGeometryPath](../../aspose.slides/geometryshape/setgeometrypath)(IGeometryPath) | shape 지오메트리를 [`IGeometryPath`](../igeometrypath) 객체에서 업데이트합니다. 좌표는 shape의 왼쪽 상단 모서리를 기준으로 해야 합니다. shape 유형([`ShapeType`](../geometryshape/shapetype))을 Custom으로 변경합니다. |
| [SetGeometryPaths](../../aspose.slides/geometryshape/setgeometrypaths)(IGeometryPath[]) | shape 지오메트리를 [`IGeometryPath`](../igeometrypath) 배열에서 업데이트합니다. 좌표는 shape의 왼쪽 상단 모서리를 기준으로 해야 합니다. shape 유형([`ShapeType`](../geometryshape/shapetype))을 Custom으로 변경합니다. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | Shape의 내용을 SVG 파일로 저장합니다. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | Shape의 내용을 SVG 파일로 저장합니다. |

### 참고

* 클래스 [GeometryShape](../geometryshape)
* 인터페이스 [IConnector](../iconnector)
* 네임스페이스 [Aspose.Slides](../../aspose.slides)
* 어셈블리 [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->