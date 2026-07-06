---
title: OleObjectFrame
second_title: Aspose.Sildes for .NET API 레퍼런스
description: 슬라이드에 있는 OLE 개체를 나타냅니다.
type: docs
weight: 9230
url: /ko/aspose.slides/oleobjectframe/
---
## OleObjectFrame 클래스

슬라이드에 있는 OLE 개체를 나타냅니다.

```csharp
public class OleObjectFrame : GraphicalObject, IOleObjectFrame
```

## 속성

| 이름 | 설명 |
| --- | --- |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | 모양과 연결된 대체 텍스트를 반환하거나 설정합니다. 읽기/쓰기 String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | 모양과 연결된 대체 텍스트의 제목을 반환하거나 설정합니다. 읽기/쓰기 String. |
| [AsIGraphicalObject](../../aspose.slides/oleobjectframe/asigraphicalobject) { get; } | 기본 IGraphicalObject 인터페이스를 가져올 수 있습니다. 읽기 전용 [`IGraphicalObject`](../igraphicalobject). |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | 속성은 모양이 흑백 표시 모드에서 어떻게 렌더링되는지를 지정합니다. 읽기/쓰기 [`BlackWhiteMode`](../blackwhitemode). |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | 모양의 연결 지점 수를 반환합니다. 읽기 전용 Int32. |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | 모양의 사용자 지정 데이터를 반환합니다. 읽기 전용 [`ICustomData`](../icustomdata). |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | 모양에 적용된 픽셀 효과를 포함하는 EffectFormat 객체를 반환합니다. 참고: 효과 속성이 없는 특정 유형의 모양에 대해 null을 반환할 수 있습니다. 읽기 전용 [`IEffectFormat`](../ieffectformat). |
| [EmbeddedData](../../aspose.slides/oleobjectframe/embeddeddata) { get; } | OLE 임베디드 데이터에 대한 정보를 가져오거나 설정합니다. 읽기/쓰기 [`IOleEmbeddedDataInfo`](../ioleembeddeddatainfo). |
| [EmbeddedFileLabel](../../aspose.slides/oleobjectframe/embeddedfilelabel) { get; } | 임베디드 OLE 개체의 파일 이름을 반환합니다. |
| [EmbeddedFileName](../../aspose.slides/oleobjectframe/embeddedfilename) { get; } | 임베디드 OLE 개체의 경로를 반환합니다. |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | 모양에 대한 채우기 서식 속성을 포함하는 FillFormat 객체를 반환합니다. 참고: 채우기 속성이 없는 특정 유형의 모양에 대해 null을 반환할 수 있습니다. 읽기 전용 [`IFillFormat`](../ifillformat). |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | 모양 프레임의 속성을 반환하거나 설정합니다. 읽기/쓰기 [`IShapeFrame`](../ishapeframe). |
| [GraphicalObjectLock](../../aspose.slides/graphicalobject/graphicalobjectlock) { get; } | 모양의 잠금을 반환합니다. 읽기 전용 [`IGraphicalObjectLock`](../igraphicalobjectlock). |
| [Height](../../aspose.slides/shape/height) { get; set; } | 포인트 단위로 측정된 모양의 높이를 가져오거나 설정합니다. 읽기/쓰기 Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | 모양이 숨겨져 있는지 여부를 결정합니다. 읽기/쓰기 Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | 마우스 클릭에 정의된 하이퍼링크를 반환하거나 설정합니다. 읽기/쓰기 [`IHyperlink`](../ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | 하이퍼링크 관리자를 반환합니다. 읽기 전용 [`IHyperlinkManager`](../ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | 마우스 오버에 정의된 하이퍼링크를 반환하거나 설정합니다. 읽기/쓰기 [`IHyperlink`](../ihyperlink). |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | ‘장식용으로 표시’ 옵션을 가져오거나 설정합니다. 읽기/쓰기 Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | 모양이 그룹화되어 있는지 여부를 결정합니다. 읽기 전용 Boolean. |
| [IsObjectIcon](../../aspose.slides/oleobjectframe/isobjecticon) { get; set; } | 객체가 아이콘으로 표시되는지 여부를 결정합니다. 읽기/쓰기 Boolean. |
| [IsObjectLink](../../aspose.slides/oleobjectframe/isobjectlink) { get; } | 객체가 외부 파일에 연결되어 있는지 여부를 결정합니다. 읽기 전용 Boolean. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | 모양이 TextHolder_PPT인지 여부를 결정합니다. 읽기 전용 Boolean. |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | 모양에 대한 선 서식 속성을 포함하는 LineFormat 객체를 반환합니다. 참고: 선 속성이 없는 특정 유형의 모양에 대해 null을 반환할 수 있습니다. 읽기 전용 [`ILineFormat`](../ilineformat). |
| [LinkFileName](../../aspose.slides/oleobjectframe/linkfilename) { get; } | 링크된 파일의 전체 경로를 반환합니다. 짧은 파일 이름이 사용됩니다. 읽기 전용 String. |
| [LinkPathLong](../../aspose.slides/oleobjectframe/linkpathlong) { get; set; } | 링크된 파일의 전체 경로를 반환합니다. 긴 파일 이름이 사용됩니다. 읽기/쓰기 String. |
| [LinkPathRelative](../../aspose.slides/oleobjectframe/linkpathrelative) { get; } | 존재하는 경우 링크된 파일의 상대 경로를 반환하고, 그렇지 않으면 빈 문자열을 반환합니다. 읽기 전용 String. |
| [Name](../../aspose.slides/shape/name) { get; set; } | 모양의 이름을 반환하거나 설정합니다. null이 아니어야 합니다. 필요하면 빈 문자열 값을 사용하십시오. 읽기/쓰기 String. |
| [ObjectName](../../aspose.slides/oleobjectframe/objectname) { get; set; } | 객체의 이름을 반환하거나 설정합니다. 읽기/쓰기 String. |
| [ObjectProgId](../../aspose.slides/oleobjectframe/objectprogid) { get; set; } | 객체의 ProgID를 반환합니다. 읽기 전용 String. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | 슬라이드 범위 내에서 고유 식별자를 반환합니다. 이 식별자는 모양의 수명 동안 일정하게 유지되며 PowerPoint 또는 인터롭 코드를 통해 문서 어디서든 모양을 안정적으로 참조할 수 있게 합니다. 읽기 전용 UInt32. 또한 [`UniqueId`](../shape/uniqueid)을 참조하십시오. |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | 모양이 그룹화된 경우 상위 GroupShape 객체를 반환합니다. 그렇지 않으면 null을 반환합니다. 읽기 전용 [`IGroupShape`](../igroupshape). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | 모양의 플레이스홀더를 반환합니다. 모양에 플레이스홀더가 없으면 null을 반환합니다. 읽기 전용 [`IPlaceholder`](../iplaceholder). |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | 슬라이드의 상위 프레젠테이션을 반환합니다. 읽기 전용 [`IPresentation`](../ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | 원시 모양 프레임의 속성을 반환하거나 설정합니다. 읽기/쓰기 [`IShapeFrame`](../ishapeframe). |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | 지정된 모양이 z축을 기준으로 회전된 각도를 반환하거나 설정합니다. 양수 값은 시계 방향 회전을 나타내고, 음수 값은 반시계 방향 회전을 나타냅니다. 읽기/쓰기 Single. |
| [ShapeLock](../../aspose.slides/graphicalobject/shapelock) { get; } | 모양의 잠금을 반환합니다. 읽기 전용 [`IGraphicalObjectLock`](../igraphicalobjectlock). (2개의 속성) |
| [Slide](../../aspose.slides/shape/slide) { get; } | 모양의 상위 슬라이드를 반환합니다. 읽기 전용 [`IBaseSlide`](../ibaseslide). |
| [SubstitutePictureFormat](../../aspose.slides/oleobjectframe/substitutepictureformat) { get; } | OleObject 이미지 채우기 속성 객체를 반환합니다. 읽기 전용 [`IPictureFillFormat`](../ipicturefillformat). |
| [SubstitutePictureTitle](../../aspose.slides/oleobjectframe/substitutepicturetitle) { get; set; } | OleObject 아이콘의 제목을 반환하거나 설정합니다. 읽기/쓰기 String. |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | 모양에 대한 3D 효과 속성을 포함하는 ThreeDFormat 객체를 반환합니다. 참고: 3D 속성이 없는 특정 유형의 모양에 대해 null을 반환할 수 있습니다. 읽기 전용 [`IThreeDFormat`](../ithreedformat). |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | 애드인 또는 기타 코드에서 사용하도록 설계된 내부 프레젠테이션 범위 식별자를 반환합니다. 이 값은 사용자 또는 프로그램에 의해 재할당될 수 있으므로 지속적인 고유 키로 취급해서는 안 됩니다. 읽기 전용 UInt32. 또한 [`OfficeInteropShapeId`](../shape/officeinteropshapeid)를 참조하십시오. |
| [UpdateAutomatic](../../aspose.slides/oleobjectframe/updateautomatic) { get; set; } | 프레젠테이션을 열거나 인쇄할 때 링크된 임베디드 객체가 자동으로 업데이트되는지 여부를 결정합니다. 읽기/쓰기 Boolean. |
| [Width](../../aspose.slides/shape/width) { get; set; } | 포인트 단위로 측정된 모양의 너비를 가져오거나 설정합니다. 읽기/쓰기 Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | 포인트 단위로 측정된 모양의 왼쪽 상단 모서리의 x좌표를 가져오거나 설정합니다. 읽기/쓰기 Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | 포인트 단위로 측정된 모양의 왼쪽 상단 모서리의 y좌표를 가져오거나 설정합니다. 읽기/쓰기 Single. |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | z-순서에서 모양의 위치를 반환합니다. Shapes[0]은 z-순서의 뒤쪽에 있는 모양을 반환하고, Shapes[Shapes.Count - 1]은 앞쪽에 있는 모양을 반환합니다. 읽기 전용 Int32. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | 새로운 플레이스홀더가 없을 경우 추가하고 지정된 플레이스홀더 속성을 설정합니다. |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | 레이아웃 및/또는 마스터 슬라이드에서 현재 모양이 상속받은 기본 플레이스홀더 모양을 반환합니다. 현재 모양이 상속받지 않은 경우 null을 반환합니다. |
| [GetImage](../../aspose.slides/shape/getimage)() | 모양 썸네일을 반환합니다. 기본적으로 ShapeThumbnailBounds.Shape 모양 썸네일 경계 유형이 사용됩니다. |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | 모양 썸네일을 반환합니다. |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | 렌더링된 내용으로부터 계산된 모양의 시각적 경계를 가져옵니다. |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | 이 모양이 플레이스홀더가 아님을 정의합니다. |
| [SetEmbeddedData](../../aspose.slides/oleobjectframe/setembeddeddata)(IOleEmbeddedDataInfo) | OLE 임베디드 데이터에 대한 정보를 설정합니다. 이 메서드는 객체의 속성을 새 데이터에 맞게 변경하고 IsObjectLink 플래그를 false로 설정하여 OLE 개체가 임베디드됨을 나타냅니다. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | 모양의 내용을 SVG 파일로 저장합니다. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | 모양의 내용을 SVG 파일로 저장합니다. |

### 예제

다음 예제는 OLE 개체 프레임에 접근하는 방법을 보여줍니다.

```csharp
[C#]
// PPTX를 프레젠테이션 객체로 로드합니다
using (Presentation pres = new Presentation("AccessingOLEObjectFrame.pptx"))
{
    // 첫 번째 슬라이드에 접근합니다
    ISlide sld = pres.Slides[0];
    // 모양을 OleObjectFrame으로 캐스트합니다
    OleObjectFrame oleObjectFrame = sld.Shapes[0] as OleObjectFrame;
    // OLE 개체를 읽고 디스크에 씁니다
    if (oleObjectFrame != null)
    {
        // 임베디드 파일 데이터를 가져옵니다
        byte[] data = oleObjectFrame.EmbeddedData.EmbeddedFileData;
        // 임베디드 파일 확장자를 가져옵니다
        string fileExtention = oleObjectFrame.EmbeddedData.EmbeddedFileExtension;
        // 추출된 파일을 저장할 경로를 생성합니다
        string extractedPath = "excelFromOLE_out" + fileExtention;
        // 추출된 데이터를 저장합니다
        using (FileStream fstr = new FileStream(extractedPath, FileMode.Create, FileAccess.Write))
        {
            fstr.Write(data, 0, data.Length);
        }
    }
}
```

### 참조

* 클래스 [GraphicalObject](../graphicalobject)
* 인터페이스 [IOleObjectFrame](../ioleobjectframe)
* 네임스페이스 [Aspose.Slides](../../aspose.slides)
* 어셈블리 [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->