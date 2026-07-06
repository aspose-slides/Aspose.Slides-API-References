---
title: GeometryShape
second_title: Aspose.Sildes .NET API 레퍼런스
description: 모든 기하학적 도형의 상위 클래스를 나타냅니다.
type: docs
weight: 4970
url: /ko/aspose.slides/geometryshape/
---
## GeometryShape 클래스

모든 기하학적 도형에 대한 상위 클래스를 나타냅니다.

```csharp
public abstract class GeometryShape : Shape, IGeometryShape
```

## Properties

| Name | Description |
| --- | --- |
| [Adjustments](../../aspose.slides/geometryshape/adjustments) { get; } | 도형의 조정 값 컬렉션을 반환합니다. 읽기 전용 [`IAdjustValueCollection`](../iadjustvaluecollection). |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | 도형에 연결된 대체 텍스트를 반환하거나 설정합니다. 읽기/쓰기 String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | 도형에 연결된 대체 텍스트의 제목을 반환하거나 설정합니다. 읽기/쓰기 String. |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | 도형이 흑백 표시 모드에서 어떻게 렌더링되는지를 지정하는 속성입니다. 읽기/쓰기 [`BlackWhiteMode`](../blackwhitemode). |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | 도형의 연결 지점 수를 반환합니다. 읽기 전용 Int32. |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | 도형의 사용자 지정 데이터를 반환합니다. 읽기 전용 [`ICustomData`](../icustomdata). |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | 도형에 적용된 픽셀 효과를 포함하는 EffectFormat 개체를 반환합니다. 참고: 효과 속성이 없는 특정 유형의 도형에 대해 null을 반환할 수 있습니다. 읽기 전용 [`IEffectFormat`](../ieffectformat). |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | 도형의 채우기 서식 속성을 포함하는 FillFormat 개체를 반환합니다. 참고: 채우기 속성이 없는 특정 유형의 도형에 대해 null을 반환할 수 있습니다. 읽기 전용 [`IFillFormat`](../ifillformat). |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | 도형 프레임의 속성을 반환하거나 설정합니다. 읽기/쓰기 [`IShapeFrame`](../ishapeframe). |
| [Height](../../aspose.slides/shape/height) { get; set; } | 도형의 높이를 포인트 단위로 반환하거나 설정합니다. 읽기/쓰기 Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | 도형이 숨겨져 있는지 여부를 결정합니다. 읽기/쓰기 Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | 마우스 클릭에 정의된 하이퍼링크를 반환하거나 설정합니다. 읽기/쓰기 [`IHyperlink`](../ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | 하이퍼링크 관리자를 반환합니다. 읽기 전용 [`IHyperlinkManager`](../ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | 마우스 오버에 정의된 하이퍼링크를 반환하거나 설정합니다. 읽기/쓰기 [`IHyperlink`](../ihyperlink). |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | '장식용으로 표시' 옵션을 가져오거나 설정합니다. 읽기/쓰기 Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | 도형이 그룹화되어 있는지 여부를 결정합니다. 읽기 전용 Boolean. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | 도형이 TextHolder_PPT인지 여부를 결정합니다. 읽기 전용 Boolean. |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | 도형의 선 서식 속성을 포함하는 LineFormat 개체를 반환합니다. 참고: 선 속성이 없는 특정 유형의 도형에 대해 null을 반환할 수 있습니다. 읽기 전용 [`ILineFormat`](../ilineformat). |
| [Name](../../aspose.slides/shape/name) { get; set; } | 도형의 이름을 반환하거나 설정합니다. null이 아니어야 합니다. 필요한 경우 빈 문자열 값을 사용하세요. 읽기/쓰기 String. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | 슬라이드 범위 내에서 고유한 식별자를 반환합니다(문서 전체에서 일정하게 유지). 읽기 전용 UInt32. 또한 [`UniqueId`](../shape/uniqueid)를 참조하세요. |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | 도형이 그룹화된 경우 상위 GroupShape 개체를 반환합니다. 그렇지 않으면 null을 반환합니다. 읽기 전용 [`IGroupShape`](../igroupshape). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | 도형의 자리표시자를 반환합니다. 자리표시자가 없으면 null을 반환합니다. 읽기 전용 [`IPlaceholder`](../iplaceholder). |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | 슬라이드의 상위 프레젠테이션을 반환합니다. 읽기 전용 [`IPresentation`](../ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | 원시 도형 프레임의 속성을 반환하거나 설정합니다. 읽기/쓰기 [`IShapeFrame`](../ishapeframe). |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | 도형이 z축을 중심으로 회전된 각도를 반환하거나 설정합니다. 양수 값은 시계 방향 회전을 의미하고, 음수 값은 반시계 방향 회전을 의미합니다. 읽기/쓰기 Single. |
| [ShapeLock](../../aspose.slides/shape/shapelock) { get; } | 도형의 잠금 상태를 반환합니다. 읽기 전용 [`IBaseShapeLock`](../ibaseshapelock). |
| [ShapeStyle](../../aspose.slides/geometryshape/shapestyle) { get; } | 도형의 스타일 개체를 반환합니다. 읽기 전용 [`IShapeStyle`](../ishapestyle). |
| virtual [ShapeType](../../aspose.slides/geometryshape/shapetype) { get; set; } | 기하학 프리셋 유형을 반환하거나 설정합니다. 참고: 값이 변경되면 모든 조정 값이 기본값으로 재설정됩니다. 읽기/쓰기 [`ShapeType`](../shapetype). |
| [Slide](../../aspose.slides/shape/slide) { get; } | 도형의 상위 슬라이드를 반환합니다. 읽기 전용 [`IBaseSlide`](../ibaseslide). |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | 도형의 3D 효과 속성을 포함하는 ThreeDFormat 개체를 반환합니다. 참고: 3D 속성이 없는 특정 유형의 도형에 대해 null을 반환할 수 있습니다. 읽기 전용 [`IThreeDFormat`](../ithreedformat). |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | 애드인 또는 기타 코드에서 사용하기 위한 프레젠테이션 범위 내부 식별자를 반환합니다. 이 값은 사용자나 프로그램에 의해 재할당될 수 있으므로 영구적인 고유 키로 사용하면 안 됩니다. 읽기 전용 UInt32. 또한 [`OfficeInteropShapeId`](../shape/officeinteropshapeid)를 참조하세요. |
| [Width](../../aspose.slides/shape/width) { get; set; } | 도형의 너비를 포인트 단위로 반환하거나 설정합니다. 읽기/쓰기 Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | 도형 좌측 상단 모서리의 x 좌표를 포인트 단위로 반환하거나 설정합니다. 읽기/쓰기 Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | 도형 좌측 상단 모서리의 y 좌표를 포인트 단위로 반환하거나 설정합니다. 읽기/쓰기 Single. |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | 도형의 Z 순서 위치를 반환합니다. Shapes[0]은 Z 순서 가장 뒤에 있는 도형을, Shapes[Shapes.Count - 1]은 가장 앞에 있는 도형을 반환합니다. 읽기 전용 Int32. |

## Methods

| Name | Description |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | 자리표시자가 없을 경우 새 자리표시자를 추가하고 지정된 자리표시자에 속성을 설정합니다. |
| [CreateShapeElements](../../aspose.slides/geometryshape/createshapeelements)() | 도형 요소 배열을 생성하고 반환합니다. |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | 현재 도형이 상속받은 레이아웃 또는 마스터 슬라이드의 기본 자리표시자 도형을 반환합니다. 상속되지 않은 경우 null을 반환합니다. |
| [GetGeometryPaths](../../aspose.slides/geometryshape/getgeometrypaths)() | 기하학 도형 경로의 복사본을 반환합니다. 좌표는 도형의 좌측 상단 모서리를 기준으로 합니다. |
| [GetImage](../../aspose.slides/shape/getimage)() | 도형 썸네일을 반환합니다. 기본적으로 ShapeThumbnailBounds.Shape 도형 썸네일 경계 유형이 사용됩니다. |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | 도형 썸네일을 반환합니다. |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | 렌더링된 콘텐츠를 기준으로 계산된 도형의 시각적 경계를 가져옵니다. |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | 이 도형이 자리표시자가 아님을 정의합니다. |
| [SetGeometryPath](../../aspose.slides/geometryshape/setgeometrypath)(IGeometryPath) | [`IGeometryPath`](../igeometrypath) 객체에서 도형 기하학을 업데이트합니다. 좌표는 도형의 좌측 상단 모서리를 기준으로 해야 합니다. 도형 유형([`ShapeType`](./shapetype))을 Custom으로 변경합니다. |
| [SetGeometryPaths](../../aspose.slides/geometryshape/setgeometrypaths)(IGeometryPath[]) | [`IGeometryPath`](../igeometrypath) 배열에서 도형 기하학을 업데이트합니다. 좌표는 도형의 좌측 상단 모서리를 기준으로 해야 합니다. 도형 유형([`ShapeType`](./shapetype))을 Custom으로 변경합니다. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | 도형의 내용을 SVG 파일로 저장합니다. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | 도형의 내용을 SVG 파일로 저장합니다. |

### 참고

* 클래스 [Shape](../shape)
* 인터페이스 [IGeometryShape](../igeometryshape)
* 네임스페이스 [Aspose.Slides](../../aspose.slides)
* 어셈블리 [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->