---
title: SmartArt
second_title: Aspose.Sildes for .NET API 레퍼런스
description: SmartArt 다이어그램을 나타냅니다
type: docs
weight: 10600
url: /ko/aspose.slides.smartart/smartart/
---
## SmartArt 클래스

SmartArt 다이어그램을 나타냅니다

```csharp
public class SmartArt : GraphicalObject, ISmartArt
```

## 속성

| 이름 | 설명 |
| --- | --- |
| [AllNodes](../../aspose.slides.smartart/smartart/allnodes) { get; } | SmartArt 객체의 모든 노드 컬렉션을 반환합니다. 읽기 전용 [`ISmartArtNodeCollection`](../ismartartnodecollection). |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | 도형에 연결된 대체 텍스트를 반환하거나 설정합니다. 읽기/쓰기 String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | 대체 텍스트와 관련된 제목을 반환하거나 설정합니다. 읽기/쓰기 String. |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | 속성은 도형이 흑백 표시 모드에서 어떻게 렌더링되는지를 지정합니다. 읽기/쓰기 [`BlackWhiteMode`](../../aspose.slides/blackwhitemode). |
| [ColorStyle](../../aspose.slides.smartart/smartart/colorstyle) { get; set; } | SmartArt 객체의 색상 스타일을 반환하거나 설정합니다. 읽기/쓰기 [`SmartArtColorType`](../smartartcolortype). |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | 도형의 연결 지점 수를 반환합니다. 읽기 전용 Int32. |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | 도형의 사용자 정의 데이터를 반환합니다. 읽기 전용 [`ICustomData`](../../aspose.slides/icustomdata). |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | 도형에 적용된 픽셀 효과를 포함하는 EffectFormat 객체를 반환합니다. 참고: 효과 속성이 없는 특정 유형의 도형에 대해서는 null을 반환할 수 있습니다. 읽기 전용 [`IEffectFormat`](../../aspose.slides/ieffectformat). |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | 도형의 채우기 서식 속성을 포함하는 FillFormat 객체를 반환합니다. 참고: 채우기 속성이 없는 특정 유형의 도형에 대해서는 null을 반환할 수 있습니다. 읽기 전용 [`IFillFormat`](../../aspose.slides/ifillformat). |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | 도형 프레임의 속성을 반환하거나 설정합니다. 읽기/쓰기 [`IShapeFrame`](../../aspose.slides/ishapeframe). |
| [GraphicalObjectLock](../../aspose.slides/graphicalobject/graphicalobjectlock) { get; } | 도형의 잠금을 반환합니다. 읽기 전용 [`IGraphicalObjectLock`](../../aspose.slides/igraphicalobjectlock). |
| [Height](../../aspose.slides/shape/height) { get; set; } | 도형의 높이를 포인트 단위로 반환하거나 설정합니다. 읽기/쓰기 Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | 도형이 숨겨져 있는지 여부를 결정합니다. 읽기/쓰기 Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | 마우스 클릭에 정의된 하이퍼링크를 반환하거나 설정합니다. 읽기/쓰기 [`IHyperlink`](../../aspose.slides/ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | 하이퍼링크 관리자를 반환합니다. 읽기 전용 [`IHyperlinkManager`](../../aspose.slides/ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | 마우스 오버에 정의된 하이퍼링크를 반환하거나 설정합니다. 읽기/쓰기 [`IHyperlink`](../../aspose.slides/ihyperlink). |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | ‘장식용으로 표시’ 옵션을 반환하거나 설정합니다. 읽기/쓰기 Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | 도형이 그룹화되어 있는지 여부를 결정합니다. 읽기 전용 Boolean. |
| [IsReversed](../../aspose.slides.smartart/smartart/isreversed) { get; set; } | 다이어그램이 반전이 지원되는 경우 (왼쪽에서 오른쪽) LTR 또는 (오른쪽에서 왼쪽) RTL 상태를 반환하거나 설정합니다. 읽기/쓰기 Boolean. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | 도형이 TextHolder_PPT인지 여부를 결정합니다. 읽기 전용 Boolean. |
| [Layout](../../aspose.slides.smartart/smartart/layout) { get; set; } | SmartArt 객체의 레이아웃을 반환하거나 설정합니다. 읽기/쓰기 [`SmartArtLayoutType`](../smartartlayouttype). |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | 도형의 선 서식 속성을 포함하는 LineFormat 객체를 반환합니다. 참고: 선 속성이 없는 특정 유형의 도형에 대해서는 null을 반환할 수 있습니다. 읽기 전용 [`ILineFormat`](../../aspose.slides/ilineformat). |
| [Name](../../aspose.slides/shape/name) { get; set; } | 도형의 이름을 반환하거나 설정합니다. null이 되어서는 안 됩니다. 필요시 빈 문자열 값을 사용합니다. 읽기/쓰기 String. |
| [Nodes](../../aspose.slides.smartart/smartart/nodes) { get; } | SmartArt 객체의 루트 노드 컬렉션을 반환합니다. 읽기 전용 [`ISmartArtNodeCollection`](../ismartartnodecollection). |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | 슬라이드 범위 내 고유 식별자를 반환합니다. 이 값은 도형의 수명 동안 일정하게 유지되어 PowerPoint 또는 인터옵 코드가 문서 어디서든 도형을 신뢰성 있게 참조할 수 있게 합니다. 읽기 전용 UInt32. 또한 [`UniqueId`](../../aspose.slides/shape/uniqueid)을 참조하십시오. |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | 도형이 그룹화된 경우 부모 GroupShape 객체를 반환합니다. 그렇지 않으면 null을 반환합니다. 읽기 전용 [`IGroupShape`](../../aspose.slides/igroupshape). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | 도형의 자리표시자를 반환합니다. 도형에 자리표시자가 없으면 null을 반환합니다. 읽기 전용 [`IPlaceholder`](../../aspose.slides/iplaceholder). |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | 슬라이드의 상위 프레젠테이션을 반환합니다. 읽기 전용 [`IPresentation`](../../aspose.slides/ipresentation). |
| [QuickStyle](../../aspose.slides.smartart/smartart/quickstyle) { get; set; } | SmartArt 객체의 퀵 스타일을 반환하거나 설정합니다. 읽기/쓰기 [`SmartArtQuickStyleType`](../smartartquickstyletype). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | 원시 도형 프레임의 속성을 반환하거나 설정합니다. 읽기/쓰기 [`IShapeFrame`](../../aspose.slides/ishapeframe). |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | 지정된 도형이 z축을 중심으로 회전된 각도를 반환하거나 설정합니다. 양수 값은 시계 방향 회전을 나타내고, 음수 값은 반시계 방향 회전을 나타냅니다. 읽기/쓰기 Single. |
| [ShapeLock](../../aspose.slides/graphicalobject/shapelock) { get; } | 도형의 잠금을 반환합니다. 읽기 전용 [`IGraphicalObjectLock`](../../aspose.slides/igraphicalobjectlock). (2개의 속성) |
| [Slide](../../aspose.slides/shape/slide) { get; } | 도형의 상위 슬라이드를 반환합니다. 읽기 전용 [`IBaseSlide`](../../aspose.slides/ibaseslide). |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | 도형의 3D 효과 속성을 포함하는 ThreeDFormat 객체를 반환합니다. 참고: 3D 속성이 없는 특정 유형의 도형에 대해서는 null을 반환할 수 있습니다. 읽기 전용 [`IThreeDFormat`](../../aspose.slides/ithreedformat). |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | 추가 기능 또는 기타 코드에서 사용하도록 설계된 내부 프레젠테이션 범위 식별자를 반환합니다. 이 값은 사용자 또는 프로그램에 의해 재할당될 수 있으므로 영구적인 고유 키로 취급해서는 안 됩니다. 읽기 전용 UInt32. 또한 [`OfficeInteropShapeId`](../../aspose.slides/shape/officeinteropshapeid)을 참고하십시오. |
| [Width](../../aspose.slides/shape/width) { get; set; } | 도형의 너비를 포인트 단위로 반환하거나 설정합니다. 읽기/쓰기 Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | 도형의 왼쪽 위 모서리의 x 좌표를 포인트 단위로 반환하거나 설정합니다. 읽기/쓰기 Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | 도형의 왼쪽 위 모서리의 y 좌표를 포인트 단위로 반환하거나 설정합니다. 읽기/쓰기 Single. |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | 도형의 z-순서 위치를 반환합니다. Shapes[0]은 z-순서의 뒤쪽에 있는 도형을, Shapes[Shapes.Count - 1]은 앞쪽에 있는 도형을 반환합니다. 읽기 전용 Int32. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | 새로운 자리표시기가 없으면 추가하고 지정된 자리표시기의 속성을 설정합니다. |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | 기본 자리표시기 도형을 반환합니다 (현재 도형이 상속받은 레이아웃 및/또는 마스터 슬라이드의 도형). 현재 도형이 상속받지 않은 경우 null을 반환합니다. |
| [GetImage](../../aspose.slides/shape/getimage)() | 도형 썸네일을 반환합니다. 기본적으로 ShapeThumbnailBounds.Shape 도형 썸네일 경계 유형이 사용됩니다. |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | 도형 썸네일을 반환합니다. |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | 렌더링된 콘텐츠를 기반으로 계산된 도형의 시각적 경계를 가져옵니다. |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | 이 도형이 자리표시기가 아님을 정의합니다. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | 도형의 내용을 SVG 파일로 저장합니다. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | 도형의 내용을 SVG 파일로 저장합니다. |

### 참조

* 클래스 [GraphicalObject](../../aspose.slides/graphicalobject)
* 인터페이스 [ISmartArt](../ismartart)
* 네임스페이스 [Aspose.Slides.SmartArt](../../aspose.slides.smartart)
* 어셈블리 [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->