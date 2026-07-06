---
title: Table
second_title: Aspose.Sildes for .NET API 참조
description: 슬라이드에 있는 테이블을 나타냅니다.
type: docs
weight: 10860
url: /ko/aspose.slides/table/
---
## Table 클래스

Represents a table on a slide.

```csharp
public sealed class Table : GraphicalObject, ITable
```

## 속성

| 이름 | 설명 |
| --- | --- |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | 도형과 연결된 대체 텍스트를 반환하거나 설정합니다. 읽기/쓰기 String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | 도형과 연결된 대체 텍스트의 제목을 반환하거나 설정합니다. 읽기/쓰기 String. |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | 흑백 디스플레이 모드에서 도형이 렌더링되는 방식을 지정합니다. 읽기/쓰기 [`BlackWhiteMode`](../blackwhitemode). |
| [Columns](../../aspose.slides/table/columns) { get; } | 열 컬렉션을 반환합니다. 읽기 전용 [`IColumnCollection`](../icolumncollection). |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | 도형의 연결 지점 개수를 반환합니다. 읽기 전용 Int32. |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | 도형의 사용자 정의 데이터를 반환합니다. 읽기 전용 [`ICustomData`](../icustomdata). |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | 도형에 적용된 픽셀 효과를 포함하는 EffectFormat 객체를 반환합니다. 일부 도형에서는 null을 반환할 수 있습니다. 읽기 전용 [`IEffectFormat`](../ieffectformat). |
| override [FillFormat](../../aspose.slides/table/fillformat) { get; } | Table에 대한 FillFormat 객체를 포함하는 TableFormat.FillFormat를 반환합니다. 읽기 전용 [`IFillFormat`](../ifillformat). |
| [FirstCol](../../aspose.slides/table/firstcol) { get; set; } | 테이블의 첫 번째 열을 특수 서식으로 그릴지 여부를 결정합니다. 읽기/쓰기 Boolean. |
| [FirstRow](../../aspose.slides/table/firstrow) { get; set; } | 테이블의 첫 번째 행을 특수 서식으로 그릴지 여부를 결정합니다. 읽기/쓰기 Boolean. |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | 도형 프레임의 속성을 반환하거나 설정합니다. 읽기/쓰기 [`IShapeFrame`](../ishapeframe). |
| [GraphicalObjectLock](../../aspose.slides/graphicalobject/graphicalobjectlock) { get; } | 도형의 잠금 정보를 반환합니다. 읽기 전용 [`IGraphicalObjectLock`](../igraphicalobjectlock). |
| [Height](../../aspose.slides/shape/height) { get; set; } | 도형의 높이를 포인트 단위로 가져오거나 설정합니다. 읽기/쓰기 Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | 도형이 숨겨져 있는지 여부를 결정합니다. 읽기/쓰기 Boolean. |
| [HorizontalBanding](../../aspose.slides/table/horizontalbanding) { get; set; } | 짝수 행을 다른 서식으로 그릴지 여부를 결정합니다. 읽기/쓰기 Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | 마우스 클릭에 대한 하이퍼링크를 정의합니다. 읽기/쓰기 [`IHyperlink`](../ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | 하이퍼링크 관리자를 반환합니다. 읽기 전용 [`IHyperlinkManager`](../ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | 마우스 오버에 대한 하이퍼링크를 정의합니다. 읽기/쓰기 [`IHyperlink`](../ihyperlink). |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | ‘장식으로 표시’ 옵션을 가져오거나 설정합니다. 읽기/쓰기 Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | 도형이 그룹화되어 있는지 여부를 결정합니다. 읽기 전용 Boolean. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | 도형이 TextHolder_PPT인지 여부를 결정합니다. 읽기 전용 Boolean. |
| [Item](../../aspose.slides/table/item) { get; } | 지정된 열과 행 인덱스에 해당하는 셀을 반환합니다. 읽기 전용 [`Cell`](../cell). |
| [LastCol](../../aspose.slides/table/lastcol) { get; set; } | 테이블의 마지막 열을 특수 서식으로 그릴지 여부를 결정합니다. 읽기/쓰기 Boolean. |
| [LastRow](../../aspose.slides/table/lastrow) { get; set; } | 테이블의 마지막 행을 특수 서식으로 그릴지 여부를 결정합니다. 읽기/쓰기 Boolean. |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | 도형의 선 서식 속성을 포함하는 LineFormat 객체를 반환합니다. 일부 도형에서는 null을 반환할 수 있습니다. 읽기 전용 [`ILineFormat`](../ilineformat). |
| [Name](../../aspose.slides/shape/name) { get; set; } | 도형의 이름을 반환하거나 설정합니다. null이 될 수 없으며, 필요하면 빈 문자열을 사용하십시오. 읽기/쓰기 String. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | 슬라이드 범위 내에서 고유한 식별자를 반환합니다. 이 값은 도형 수명 동안 변하지 않으며, PowerPoint나 interop 코드가 문서 어디서든 도형을 신뢰성 있게 참조할 수 있게 합니다. 읽기 전용 UInt32. 또한 [`UniqueId`](../shape/uniqueid)를 참조하십시오. |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | 도형이 그룹화된 경우 상위 GroupShape 객체를 반환합니다. 그렇지 않으면 null을 반환합니다. 읽기 전용 [`IGroupShape`](../igroupshape). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | 도형에 대한 자리 표시자를 반환합니다. 자리 표시자가 없으면 null을 반환합니다. 읽기 전용 [`IPlaceholder`](../iplaceholder). |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | 슬라이드의 상위 프레젠테이션을 반환합니다. 읽기 전용 [`IPresentation`](../ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | 원시 도형 프레임의 속성을 반환하거나 설정합니다. 읽기/쓰기 [`IShapeFrame`](../ishapeframe). |
| [RightToLeft](../../aspose.slides/table/righttoleft) { get; set; } | 테이블이 오른쪽에서 왼쪽으로 읽는 순서를 가질지 여부를 결정합니다. 읽기/쓰기 Boolean. |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | 지정된 도형이 Z축을 중심으로 회전되는 각도를 반환하거나 설정합니다. 양수는 시계 방향 회전, 음수는 반시계 방향 회전을 의미합니다. 읽기/쓰기 Single. |
| [Rows](../../aspose.slides/table/rows) { get; } | 행 컬렉션을 반환합니다. 읽기 전용 [`IRowCollection`](../irowcollection). |
| [ShapeLock](../../aspose.slides/graphicalobject/shapelock) { get; } | 도형의 잠금 정보를 반환합니다. 읽기 전용 [`IGraphicalObjectLock`](../igraphicalobjectlock). (2 properties) |
| [Slide](../../aspose.slides/shape/slide) { get; } | 도형의 상위 슬라이드를 반환합니다. 읽기 전용 [`IBaseSlide`](../ibaseslide). |
| [StylePreset](../../aspose.slides/table/stylepreset) { get; set; } | 내장 테이블 스타일을 가져오거나 설정합니다. 읽기/쓰기 [`TableStylePreset`](../tablestylepreset). |
| [TableFormat](../../aspose.slides/table/tableformat) { get; } | 이 테이블에 대한 서식 속성을 포함하는 TableFormat 객체를 반환합니다. 읽기 전용 [`ITableFormat`](../itableformat). |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | 도형에 대한 3D 효과 속성을 포함하는 ThreeDFormat 객체를 반환합니다. 일부 도형에서는 null을 반환할 수 있습니다. 읽기 전용 [`IThreeDFormat`](../ithreedformat). |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | 애드인 또는 기타 코드에서 사용하기 위한 프레젠테이션 범위 내부 식별자를 반환합니다. 사용자가 또는 프로그래밍적으로 이 값을 재할당할 수 있으므로 영구적인 고유 키로 취급해서는 안 됩니다. 읽기 전용 UInt32. 또한 [`OfficeInteropShapeId`](../shape/officeinteropshapeid)를 참조하십시오. |
| [VerticalBanding](../../aspose.slides/table/verticalbanding) { get; set; } | 짝수 열을 다른 서식으로 그릴지 여부를 결정합니다. 읽기/쓰기 Boolean. |
| [Width](../../aspose.slides/shape/width) { get; set; } | 도형의 너비를 포인트 단위로 가져오거나 설정합니다. 읽기/쓰기 Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | 도형 왼쪽 상단 모서리의 X 좌표를 포인트 단위로 가져오거나 설정합니다. 읽기/쓰기 Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | 도형 왼쪽 상단 모서리의 Y 좌표를 포인트 단위로 가져오거나 설정합니다. 읽기/쓰기 Single. |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | Z 순서에서 도형의 위치를 반환합니다. Shapes[0]은 Z 순서의 뒤쪽에 있는 도형을, Shapes[Shapes.Count - 1]은 앞쪽에 있는 도형을 반환합니다. 읽기 전용 Int32. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | 자리 표시자가 없을 경우 새 자리 표시자를 추가하고 지정된 자리 표시자 속성을 설정합니다. |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | 기본 자리 표시자 도형을 반환합니다(현재 도형이 상속받은 레이아웃 또는 마스터 슬라이드의 도형). 현재 도형이 상속받지 않은 경우 null을 반환합니다. |
| [GetImage](../../aspose.slides/shape/getimage)() | 도형 썸네일을 반환합니다. 기본적으로 ShapeThumbnailBounds.Shape 썸네일 경계 유형이 사용됩니다. |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | 도형 썸네일을 반환합니다. |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | 렌더링된 콘텐츠를 기준으로 계산된 도형의 시각적 경계를 가져옵니다. |
| [MergeCells](../../aspose.slides/table/mergecells)(ICell, ICell, bool) | 인접 셀을 병합합니다. |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | 이 도형이 자리 표시자가 아님을 정의합니다. |
| [SetTextFormat](../../aspose.slides/table/settextformat#settextformat)(IParagraphFormat) | 정의된 단락 서식 속성을 모든 테이블 셀의 단락에 적용합니다. |
| [SetTextFormat](../../aspose.slides/table/settextformat#settextformat_1)(IPortionFormat) | 정의된 구간 서식 속성을 모든 테이블 셀의 구간에 적용합니다. |
| [SetTextFormat](../../aspose.slides/table/settextformat#settextformat_2)(ITextFrameFormat) | 정의된 텍스트 프레임 서식 속성을 모든 테이블 셀의 텍스트 프레임에 적용합니다. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | 도형의 내용을 SVG 파일로 저장합니다. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | 도형의 내용을 SVG 파일로 저장합니다. |

### 참고

* 클래스 [GraphicalObject](../graphicalobject)
* 인터페이스 [ITable](../itable)
* 네임스페이스 [Aspose.Slides](../../aspose.slides)
* 어셈블리 [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->