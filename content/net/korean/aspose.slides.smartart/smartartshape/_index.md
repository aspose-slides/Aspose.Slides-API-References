---
title: SmartArtShape
second_title: Aspose.Sildes for .NET API 레퍼런스
description: SmartArt 도형을 나타냅니다
type: docs
weight: 10660
url: /ko/aspose.slides.smartart/smartartshape/
---
## SmartArtShape 클래스

SmartArt 도형을 나타냅니다

```csharp
public class SmartArtShape : GeometryShape, ISmartArtShape
```

## 속성

| 이름 | 설명 |
| --- | --- |
| [Adjustments](../../aspose.slides/geometryshape/adjustments) { get; } | 모양의 조정값 컬렉션을 반환합니다. 읽기 전용 [`IAdjustValueCollection`](../../aspose.slides/iadjustvaluecollection). |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | 모양에 연결된 대체 텍스트를 반환하거나 설정합니다. 읽기/쓰기 String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | 모양에 연결된 대체 텍스트의 제목을 반환하거나 설정합니다. 읽기/쓰기 String. |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | 속성은 모양이 흑백 디스플레이 모드에서 어떻게 렌더링되는지를 지정합니다. 읽기/쓰기 [`BlackWhiteMode`](../../aspose.slides/blackwhitemode). |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | 모양의 연결 지점 수를 반환합니다. 읽기 전용 Int32. |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | 모양의 사용자 지정 데이터를 반환합니다. 읽기 전용 [`ICustomData`](../../aspose.slides/icustomdata). |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | 모양에 적용된 픽셀 효과를 포함하는 EffectFormat 객체를 반환합니다. 참고: 효과 속성이 없는 특정 유형의 모양에 대해서는 null을 반환할 수 있습니다. 읽기 전용 [`IEffectFormat`](../../aspose.slides/ieffectformat). |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | 모양에 대한 채우기 서식 속성을 포함하는 FillFormat 객체를 반환합니다. 참고: 채우기 속성이 없는 특정 유형의 모양에 대해서는 null을 반환할 수 있습니다. 읽기 전용 [`IFillFormat`](../../aspose.slides/ifillformat). |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | 모양 프레임의 속성을 반환하거나 설정합니다. 읽기/쓰기 [`IShapeFrame`](../../aspose.slides/ishapeframe). |
| [Height](../../aspose.slides/shape/height) { get; set; } | 포인트 단위로 측정된 모양의 높이를 가져오거나 설정합니다. 읽기/쓰기 Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | 모양이 숨겨져 있는지 여부를 결정합니다. 읽기/쓰기 Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | 마우스 클릭에 정의된 하이퍼링크를 반환하거나 설정합니다. 읽기/쓰기 [`IHyperlink`](../../aspose.slides/ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | 하이퍼링크 관리자를 반환합니다. 읽기 전용 [`IHyperlinkManager`](../../aspose.slides/ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | 마우스 오버에 정의된 하이퍼링크를 반환하거나 설정합니다. 읽기/쓰기 [`IHyperlink`](../../aspose.slides/ihyperlink). |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | '장식용으로 표시' 옵션을 가져오거나 설정합니다. 읽기/쓰기 Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | 모양이 그룹화되어 있는지 여부를 결정합니다. 읽기 전용 Boolean. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | 모양이 TextHolder_PPT인지 여부를 결정합니다. 읽기 전용 Boolean. |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | 모양에 대한 선 서식 속성을 포함하는 LineFormat 객체를 반환합니다. 참고: 선 속성이 없는 특정 유형의 모양에 대해서는 null을 반환할 수 있습니다. 읽기 전용 [`ILineFormat`](../../aspose.slides/ilineformat). |
| [Name](../../aspose.slides/shape/name) { get; set; } | 모양의 이름을 반환하거나 설정합니다. null이 될 수 없습니다. 필요하면 빈 문자열 값을 사용하세요. 읽기/쓰기 String. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | 모양의 수명 동안 일정하게 유지되는 슬라이드 범위 고유 식별자를 반환합니다. 이를 통해 PowerPoint 또는 인터옵 코드가 문서 어디서든 모양을 안정적으로 참조할 수 있습니다. 읽기 전용 UInt32. 또한 [`UniqueId`](../../aspose.slides/shape/uniqueid)를 참조하세요. |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | 모양이 그룹화된 경우 부모 GroupShape 객체를 반환합니다. 그렇지 않으면 null을 반환합니다. 읽기 전용 [`IGroupShape`](../../aspose.slides/igroupshape). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | 모양의 플레이스홀더를 반환합니다. 모양에 플레이스홀더가 없으면 null을 반환합니다. 읽기 전용 [`IPlaceholder`](../../aspose.slides/iplaceholder). |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | 슬라이드의 부모 프레젠테이션을 반환합니다. 읽기 전용 [`IPresentation`](../../aspose.slides/ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | 원시 모양 프레임의 속성을 반환하거나 설정합니다. 읽기/쓰기 [`IShapeFrame`](../../aspose.slides/ishapeframe). |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | 지정된 모양이 z축을 중심으로 회전된 각도를 반환하거나 설정합니다. 양수 값은 시계 방향 회전을, 음수 값은 반시계 방향 회전을 나타냅니다. 읽기/쓰기 Single. |
| [ShapeLock](../../aspose.slides/shape/shapelock) { get; } | 모양의 잠금을 반환합니다. 읽기 전용 [`IBaseShapeLock`](../../aspose.slides/ibaseshapelock). |
| [ShapeStyle](../../aspose.slides/geometryshape/shapestyle) { get; } | 모양의 스타일 객체를 반환합니다. 읽기 전용 [`IShapeStyle`](../../aspose.slides/ishapestyle). |
| override [ShapeType](../../aspose.slides.smartart/smartartshape/shapetype) { get; set; } | 기하학 사전 설정 유형을 반환하거나 설정합니다. 참고: 값이 변경되면 모든 조정 값이 기본값으로 재설정됩니다. 읽기/쓰기 [`ShapeType`](../../aspose.slides/shapetype). |
| [Slide](../../aspose.slides/shape/slide) { get; } | 모양의 부모 슬라이드를 반환합니다. 읽기 전용 [`IBaseSlide`](../../aspose.slides/ibaseslide). |
| [TextFrame](../../aspose.slides.smartart/smartartshape/textframe) { get; } | SmartArt 도형의 텍스트를 반환합니다. 읽기 전용 [`ITextFrame`](../../aspose.slides/itextframe). |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | 모양에 대한 3D 효과 속성을 포함하는 ThreeDFormat 객체를 반환합니다. 참고: 3D 속성이 없는 특정 유형의 모양에 대해서는 null을 반환할 수 있습니다. 읽기 전용 [`IThreeDFormat`](../../aspose.slides/ithreedformat). |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | 추가 기능이나 기타 코드에서 사용하도록 설계된 내부 프레젠테이션 범위 식별자를 반환합니다. 이 값은 사용자나 프로그램에 의해 재할당될 수 있으므로 지속적인 고유 키로 취급해서는 안 됩니다. 읽기 전용 UInt32. 또한 [`OfficeInteropShapeId`](../../aspose.slides/shape/officeinteropshapeid)를 참조하세요. |
| [Width](../../aspose.slides/shape/width) { get; set; } | 포인트 단위로 측정된 모양의 너비를 가져오거나 설정합니다. 읽기/쓰기 Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | 포인트 단위로 측정된 모양 좌측 상단 코너의 x 좌표를 가져오거나 설정합니다. 읽기/쓰기 Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | 포인트 단위로 측정된 모양 좌측 상단 코너의 y 좌표를 가져오거나 설정합니다. 읽기/쓰기 Single. |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | z-순서에서 모양의 위치를 반환합니다. Shapes[0]은 z-순서 뒤쪽에 있는 모양을 반환하고, Shapes[Shapes.Count - 1]은 앞쪽에 있는 모양을 반환합니다. 읽기 전용 Int32. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | 새 플레이스홀더가 없을 경우 새 플레이스홀더를 추가하고 지정된 플레이스홀더의 속성을 설정합니다. |
| [CreateShapeElements](../../aspose.slides/geometryshape/createshapeelements)() | 모양 요소들의 배열을 생성하고 반환합니다. |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | 기본 플레이스홀더 모양을 반환합니다(현재 모양이 상속받은 레이아웃 및/또는 마스터 슬라이드의 모양). 현재 모양이 상속받지 않은 경우 null을 반환합니다. |
| [GetGeometryPaths](../../aspose.slides/geometryshape/getgeometrypaths)() | 기하학 모양 경로의 복사본을 반환합니다. 좌표는 모양의 좌측 상단 모서를 기준으로 합니다. |
| [GetImage](../../aspose.slides/shape/getimage)() | 모양 썸네일을 반환합니다. 기본적으로 ShapeThumbnailBounds.Shape 모양 썸네일 경계 유형이 사용됩니다. |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | 모양 썸네일을 반환합니다. |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | 렌더링된 내용으로 계산된 모양의 시각적 경계를 가져옵니다. |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | 이 모양이 플레이스홀더가 아님을 정의합니다. |
| [SetGeometryPath](../../aspose.slides/geometryshape/setgeometrypath)(IGeometryPath) | [`IGeometryPath`](../../aspose.slides/igeometrypath) 객체에서 모양 기하학을 업데이트합니다. 좌표는 모양의 좌측 상단 모서리를 기준으로 해야 합니다. 모양의 유형([`ShapeType`](../../aspose.slides/geometryshape/shapetype))을 Custom으로 변경합니다. |
| [SetGeometryPaths](../../aspose.slides/geometryshape/setgeometrypaths)(IGeometryPath[]) | [`IGeometryPath`](../../aspose.slides/igeometrypath) 배열에서 모양 기하학을 업데이트합니다. 좌표는 모양의 좌측 상단 모서리를 기준으로 해야 합니다. 모양의 유형([`ShapeType`](../../aspose.slides/geometryshape/shapetype))을 Custom으로 변경합니다. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | Shape의 내용을 SVG 파일로 저장합니다. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | Shape의 내용을 SVG 파일로 저장합니다. |

### 참조

* 클래스 [GeometryShape](../../aspose.slides/geometryshape)
* 인터페이스 [ISmartArtShape](../ismartartshape)
* 네임스페이스 [Aspose.Slides.SmartArt](../../aspose.slides.smartart)
* 어셈블리 [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->