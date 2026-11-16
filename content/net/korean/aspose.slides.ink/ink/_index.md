---
title: Ink
second_title: Aspose.Sildes for .NET API 레퍼런스
description: 슬라이드의 잉크 객체를 나타냅니다.
type: docs
weight: 7570
url: /ko/aspose.slides.ink/ink/
---
## Ink 클래스

슬라이드의 잉크 객체를 나타냅니다.

```csharp
public class Ink : GraphicalObject, IInk
```

## 속성

| Name | Description |
| --- | --- |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | shape와 연결된 대체 텍스트를 반환하거나 설정합니다. Read/write String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | shape와 연결된 대체 텍스트의 제목을 반환하거나 설정합니다. Read/write String. |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | 속성은 shape가 흑백 디스플레이 모드에서 어떻게 렌더링되는지 지정합니다. Read/write [`BlackWhiteMode`](../../aspose.slides/blackwhitemode). |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | shape의 연결 지점 수를 반환합니다. Read-only Int32. |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | shape의 사용자 정의 데이터를 반환합니다. Read-only [`ICustomData`](../../aspose.slides/icustomdata). |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | shape에 적용된 픽셀 효과를 포함하는 EffectFormat 객체를 반환합니다. Note: can return null for certain types of shapes which don't have effect properties. Read-only [`IEffectFormat`](../../aspose.slides/ieffectformat). |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | shape에 적용된 채우기 서식 속성을 포함하는 FillFormat 객체를 반환합니다. Note: can return null for certain types of shapes which don't have fill properties. Read-only [`IFillFormat`](../../aspose.slides/ifillformat). |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | shape 프레임의 속성을 반환하거나 설정합니다. Read/write [`IShapeFrame`](../../aspose.slides/ishapeframe). |
| [GraphicalObjectLock](../../aspose.slides/graphicalobject/graphicalobjectlock) { get; } | shape의 잠금을 반환합니다. Read-only [`IGraphicalObjectLock`](../../aspose.slides/igraphicalobjectlock). |
| [Height](../../aspose.slides/shape/height) { get; set; } | shape의 높이를 포인트 단위로 가져오거나 설정합니다. Read/write Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | shape가 숨겨져 있는지 여부를 결정합니다. Read/write Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | 마우스 클릭에 정의된 하이퍼링크를 반환하거나 설정합니다. Read/write [`IHyperlink`](../../aspose.slides/ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | 하이퍼링크 관리자를 반환합니다. Read-only [`IHyperlinkManager`](../../aspose.slides/ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | 마우스 오버에 정의된 하이퍼링크를 반환하거나 설정합니다. Read/write [`IHyperlink`](../../aspose.slides/ihyperlink). |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | 'Mark as decorative' 옵션을 가져오거나 설정합니다. Reed/write Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | shape가 그룹화되어 있는지 여부를 결정합니다. Read-only Boolean. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | shape가 TextHolder_PPT인지 여부를 결정합니다. Read-only Boolean. |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | shape에 대한 라인 서식 속성을 포함하는 LineFormat 객체를 반환합니다. Note: can return null for certain types of shapes which don't have line properties. Read-only [`ILineFormat`](../../aspose.slides/ilineformat). |
| [Name](../../aspose.slides/shape/name) { get; set; } | shape의 이름을 반환하거나 설정합니다. null이 될 수 없습니다. 필요하면 빈 문자열 값을 사용하세요. Read/write String. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | 슬라이드 범위의 고유 식별자를 반환합니다. 이 식별자는 shape 수명 동안 일정하게 유지되어 PowerPoint 또는 인터옵 코드가 문서 어디서든 shape를 안정적으로 참조할 수 있게 합니다. Read-only UInt32. See also [`UniqueId`](../../aspose.slides/shape/uniqueid). |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | shape가 그룹화되어 있으면 상위 GroupShape 객체를 반환합니다. 그렇지 않으면 null을 반환합니다. Read-only [`IGroupShape`](../../aspose.slides/igroupshape). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | shape에 대한 placeholder를 반환합니다. placeholder가 없으면 null을 반환합니다. Read-only [`IPlaceholder`](../../aspose.slides/iplaceholder). |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | 슬라이드의 상위 프레젠테이션을 반환합니다. Read-only [`IPresentation`](../../aspose.slides/ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | 원시 shape 프레임의 속성을 반환하거나 설정합니다. Read/write [`IShapeFrame`](../../aspose.slides/ishapeframe). |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | 지정된 shape가 z축을 중심으로 회전되는 각도를 반환하거나 설정합니다. 양수 값은 시계 방향 회전을 나타내고, 음수 값은 반시계 방향 회전을 나타냅니다. Read/write Single. |
| [ShapeLock](../../aspose.slides/graphicalobject/shapelock) { get; } | shape의 잠금을 반환합니다. Read-only [`IGraphicalObjectLock`](../../aspose.slides/igraphicalobjectlock). (2 properties) |
| [Slide](../../aspose.slides/shape/slide) { get; } | shape의 상위 슬라이드를 반환합니다. Read-only [`IBaseSlide`](../../aspose.slides/ibaseslide). |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | shape에 대한 3D 효과 속성을 포함하는 ThreeDFormat 객체를 반환합니다. Note: can return null for certain types of shapes which don't have 3d properties. Read-only [`IThreeDFormat`](../../aspose.slides/ithreedformat). |
| [Traces](../../aspose.slides.ink/ink/traces) { get; } | IInk 요소 [`IInkTrace`](../iinktrace)에 포함된 모든 trace를 가져옵니다. Read-only. |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | 애드인 또는 기타 코드에서 사용하도록 의도된 내부 프레젠테이션 범위 식별자를 반환합니다. 이 값은 사용자 또는 프로그램에 의해 재할당될 수 있으므로 영구적인 고유 키로 취급해서는 안 됩니다. Read-only UInt32. See also [`OfficeInteropShapeId`](../../aspose.slides/shape/officeinteropshapeid). |
| [Width](../../aspose.slides/shape/width) { get; set; } | shape의 너비를 포인트 단위로 가져오거나 설정합니다. Read/write Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | shape의 왼쪽 위 모서리의 x 좌표를 포인트 단위로 가져오거나 설정합니다. Read/write Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | shape의 왼쪽 위 모서리의 y 좌표를 포인트 단위로 가져오거나 설정합니다. Read/write Single. |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | z-순서에서 shape의 위치를 반환합니다. Shapes[0]은 z-순서 뒤쪽에 있는 shape를 반환하고, Shapes[Shapes.Count - 1]은 앞쪽에 있는 shape를 반환합니다. Read-only Int32. |
| static [InkEffectImages](../../aspose.slides.ink/ink/inkeffectimages) { get; } | 잉크 브러시의 시각 효과를 시뮬레이션하는 데 사용되는 사용자 정의 이미지 컬렉션을 가져옵니다. 이러한 이미지는 Galaxy, Rainbow 등과 같은 특정 [`InkEffectType`](../inkeffecttype) 값으로 잉크를 렌더링할 때 사용됩니다. 자체 이미지를 제공하면 각 잉크 효과가 표시되는 방식을 제어할 수 있습니다. |

## 메서드

| Name | Description |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | 새로운 placeholder가 없을 경우 추가하고 지정된 placeholder의 속성을 설정합니다. |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | 현재 shape가 상속받은 레이아웃 및/또는 마스터 슬라이드의 shape를 반환합니다. 현재 shape가 상속되지 않은 경우 null을 반환합니다. |
| [GetImage](../../aspose.slides/shape/getimage)() | shape 썸네일을 반환합니다. 기본적으로 ShapeThumbnailBounds.Shape shape 썸네일 경계 유형이 사용됩니다. |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | shape 썸네일을 반환합니다. |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | 렌더링된 콘텐츠를 기준으로 계산된 shape의 시각적 경계를 가져옵니다. |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | 이 shape가 placeholder가 아님을 정의합니다. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | shape의 내용을 SVG 파일로 저장합니다. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | shape의 내용을 SVG 파일로 저장합니다. |

### 참조

* 클래스 [GraphicalObject](../../aspose.slides/graphicalobject)
* 인터페이스 [IInk](../iink)
* 네임스페이스 [Aspose.Slides.Ink](../../aspose.slides.ink)
* 어셈블리 [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->