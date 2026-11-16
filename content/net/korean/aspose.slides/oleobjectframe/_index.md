---
title: OleObjectFrame
second_title: Aspose.Sildes for .NET API 참조
description: 슬라이드에 있는 OLE 개체를 나타냅니다.
type: docs
weight: 9250
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
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | 도형과 연결된 대체 텍스트를 반환하거나 설정합니다. Read/write String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | 도형과 연결된 대체 텍스트의 제목을 반환하거나 설정합니다. Read/write String. |
| [AsIGraphicalObject](../../aspose.slides/oleobjectframe/asigraphicalobject) { get; } | 기본 IGraphicalObject 인터페이스를 가져올 수 있습니다. Read-only [`IGraphicalObject`](../igraphicalobject). |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | 속성은 도형이 흑백 디스플레이 모드에서 렌더링되는 방식을 지정합니다. Read/write [`BlackWhiteMode`](../blackwhitemode). |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | 도형의 연결 지점 수를 반환합니다. Read-only Int32. |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | 도형의 사용자 지정 데이터를 반환합니다. Read-only [`ICustomData`](../icustomdata). |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | 도형에 적용된 픽셀 효과를 포함하는 EffectFormat 개체를 반환합니다. 특정 유형의 도형은 효과 속성이 없으므로 null을 반환할 수 있습니다. Read-only [`IEffectFormat`](../ieffectformat). |
| [EmbeddedData](../../aspose.slides/oleobjectframe/embeddeddata) { get; } | OLE 임베드 데이터에 대한 정보를 가져오거나 설정합니다. Read/write [`IOleEmbeddedDataInfo`](../ioleembeddeddatainfo). |
| [EmbeddedFileLabel](../../aspose.slides/oleobjectframe/embeddedfilelabel) { get; } | 임베드된 OLE 개체의 파일 이름을 반환합니다. |
| [EmbeddedFileName](../../aspose.slides/oleobjectframe/embeddedfilename) { get; } | 임베드된 OLE 개체의 경로를 반환합니다. |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | 도형의 채우기 서식 속성을 포함하는 FillFormat 개체를 반환합니다. 특정 유형의 도형은 채우기 속성이 없으므로 null을 반환할 수 있습니다. Read-only [`IFillFormat`](../ifillformat). |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | 도형 프레임의 속성을 반환하거나 설정합니다. Read/write [`IShapeFrame`](../ishapeframe). |
| [GraphicalObjectLock](../../aspose.slides/graphicalobject/graphicalobjectlock) { get; } | 도형의 잠금을 반환합니다. Read-only [`IGraphicalObjectLock`](../igraphicalobjectlock). |
| [Height](../../aspose.slides/shape/height) { get; set; } | 도형의 높이를 포인트 단위로 가져오거나 설정합니다. Read/write Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | 도형이 숨겨져 있는지 여부를 결정합니다. Read/write Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | 마우스 클릭에 정의된 하이퍼링크를 반환하거나 설정합니다. Read/write [`IHyperlink`](../ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | 하이퍼링크 관리자를 반환합니다. Read-only [`IHyperlinkManager`](../ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | 마우스 오버에 정의된 하이퍼링크를 반환하거나 설정합니다. Read/write [`IHyperlink`](../ihyperlink). |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | ‘Mark as decorative’ 옵션을 가져오거나 설정합니다. Reed/write Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | 도형이 그룹화되어 있는지 여부를 결정합니다. Read-only Boolean. |
| [IsObjectIcon](../../aspose.slides/oleobjectframe/isobjecticon) { get; set; } | 개체를 아이콘으로 표시할지 여부를 결정합니다. Read/write Boolean. |
| [IsObjectLink](../../aspose.slides/oleobjectframe/isobjectlink) { get; } | 개체가 외부 파일에 연결되어 있는지 여부를 반환합니다. Read-only Boolean. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | 도형이 TextHolder_PPT인지 여부를 반환합니다. Read-only Boolean. |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | 도형의 선 서식 속성을 포함하는 LineFormat 개체를 반환합니다. 특정 유형의 도형은 선 속성이 없으므로 null을 반환할 수 있습니다. Read-only [`ILineFormat`](../ilineformat). |
| [LinkFileName](../../aspose.slides/oleobjectframe/linkfilename) { get; } | 연결된 파일의 전체 경로를 반환합니다. 짧은 파일 이름이 사용됩니다. Read-only String. |
| [LinkPathLong](../../aspose.slides/oleobjectframe/linkpathlong) { get; set; } | 연결된 파일의 전체 경로를 반환하거나 설정합니다. 긴 파일 이름이 사용됩니다. Read/write String. |
| [LinkPathRelative](../../aspose.slides/oleobjectframe/linkpathrelative) { get; } | 연결된 파일이 있는 경우 상대 경로를 반환하고, 없으면 빈 문자열을 반환합니다. Readonly String. |
| [Name](../../aspose.slides/shape/name) { get; set; } | 도형의 이름을 반환하거나 설정합니다. null이 될 수 없으며 필요 시 빈 문자열을 사용하십시오. Read/write String. |
| [ObjectName](../../aspose.slides/oleobjectframe/objectname) { get; set; } | 개체의 이름을 반환하거나 설정합니다. Read/write String. |
| [ObjectProgId](../../aspose.slides/oleobjectframe/objectprogid) { get; set; } | 개체의 ProgID를 반환합니다. Read only String. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | 도형 수명 동안 일정하게 유지되는 슬라이드 범위 고유 식별자를 반환합니다. PowerPoint 또는 interop 코드가 문서 어디에서든 도형을 신뢰성 있게 참조할 수 있습니다. Read-only UInt32. See also [`UniqueId`](../shape/uniqueid). |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | 도형이 그룹화된 경우 상위 GroupShape 개체를 반환합니다. 그렇지 않으면 null을 반환합니다. Read-only [`IGroupShape`](../igroupshape). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | 도형의 플레이스홀더를 반환합니다. 플레이스홀더가 없으면 null을 반환합니다. Read-only [`IPlaceholder`](../iplaceholder). |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | 슬라이드의 상위 프레젠테이션을 반환합니다. Read-only [`IPresentation`](../ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | 원시 도형 프레임의 속성을 반환하거나 설정합니다. Read/write [`IShapeFrame`](../ishapeframe). |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | 지정된 도형이 Z축을 중심으로 회전된 각도를 반환하거나 설정합니다. 양수 값은 시계 방향 회전을, 음수 값은 반시계 방향 회전을 나타냅니다. Read/write Single. |
| [ShapeLock](../../aspose.slides/graphicalobject/shapelock) { get; } | 도형의 잠금을 반환합니다. Read-only [`IGraphicalObjectLock`](../igraphicalobjectlock). (2 properties) |
| [Slide](../../aspose.slides/shape/slide) { get; } | 도형의 상위 슬라이드를 반환합니다. Read-only [`IBaseSlide`](../ibaseslide). |
| [SubstitutePictureFormat](../../aspose.slides/oleobjectframe/substitutepictureformat) { get; } | OleObject 이미지 채우기 속성 개체를 반환합니다. Read-only [`IPictureFillFormat`](../ipicturefillformat). |
| [SubstitutePictureTitle](../../aspose.slides/oleobjectframe/substitutepicturetitle) { get; set; } | OleObject 아이콘의 제목을 반환하거나 설정합니다. Read/write String. |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | 도형의 3D 효과 속성을 포함하는 ThreeDFormat 개체를 반환합니다. 특정 유형의 도형은 3D 속성이 없으므로 null을 반환할 수 있습니다. Read-only [`IThreeDFormat`](../ithreedformat). |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | 애드인 또는 기타 코드에서 사용하기 위한 프레젠테이션 범위 내부 식별자를 반환합니다. 이 값은 사용자 또는 프로그램에 의해 재할당될 수 있으므로 지속적인 고유 키로 취급해서는 안 됩니다. Read-only UInt32. See also [`OfficeInteropShapeId`](../shape/officeinteropshapeid). |
| [UpdateAutomatic](../../aspose.slides/oleobjectframe/updateautomatic) { get; set; } | 프레젠테이션이 열리거나 인쇄될 때 연결된 임베드 개체가 자동으로 업데이트되는지 여부를 결정합니다. Read/write Boolean. |
| [Width](../../aspose.slides/shape/width) { get; set; } | 도형의 너비를 포인트 단위로 가져오거나 설정합니다. Read/write Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | 도형 왼쪽 상단 모서리의 x 좌표를 포인트 단위로 가져오거나 설정합니다. Read/write Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | 도형 왼쪽 상단 모서리의 y 좌표를 포인트 단위로 가져오거나 설정합니다. Read/write Single. |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | 도형의 Z 순서에서 위치를 반환합니다. Shapes[0]은 Z 순서의 뒤쪽 도형을, Shapes[Shapes.Count - 1]은 앞쪽 도형을 반환합니다. Read-only Int32. |

## Methods

| 이름 | 설명 |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | 새 자리표시자가 없을 경우 추가하고 지정된 자리표시자에 대한 속성을 설정합니다. |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | 기본 자리표시자 도형을 반환합니다 (현재 도형이 상속받은 레이아웃 및/또는 마스터 슬라이드의 도형). 현재 도형이 상속받지 않은 경우 null을 반환합니다. |
| [GetImage](../../aspose.slides/shape/getimage)() | 도형 썸네일을 반환합니다. 기본값으로 ShapeThumbnailBounds.Shape 도형 썸네일 경계 유형이 사용됩니다. |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | 도형 썸네일을 반환합니다. |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | 렌더링된 콘텐츠에서 계산된 도형의 시각적 경계를 가져옵니다. |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | 이 도형이 자리표시자가 아님을 정의합니다. |
| [SetEmbeddedData](../../aspose.slides/oleobjectframe/setembeddeddata)(IOleEmbeddedDataInfo) | OLE 임베드 데이터에 대한 정보를 설정합니다.  이 메서드는 객체의 속성을 새로운 데이터에 맞게 변경하고 IsObjectLink 플래그를 false로 설정하여 OLE 개체가 임베드됨을 나타냅니다. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | 도형의 내용을 SVG 파일로 저장합니다. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | 도형의 내용을 SVG 파일로 저장합니다. |

### 예제

다음 예제는 OLE 객체 프레임에 접근하는 방법을 보여줍니다.

```csharp
[C#]
// PPTX 파일을 프레젠테이션 객체에 로드합니다
using (Presentation pres = new Presentation("AccessingOLEObjectFrame.pptx"))
{
    // 첫 번째 슬라이드에 접근합니다
    ISlide sld = pres.Slides[0];
    // 도형을 OleObjectFrame으로 캐스팅합니다
    OleObjectFrame oleObjectFrame = sld.Shapes[0] as OleObjectFrame;
    // OLE 개체를 읽어 디스크에 씁니다
    if (oleObjectFrame != null)
    {
        // 임베드된 파일 데이터를 가져옵니다
        byte[] data = oleObjectFrame.EmbeddedData.EmbeddedFileData;
        // 임베드된 파일 확장자를 가져옵니다
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

### 참고

* 클래스 [GraphicalObject](../graphicalobject)
* 인터페이스 [IOleObjectFrame](../ioleobjectframe)
* 네임스페이스 [Aspose.Slides](../../aspose.slides)
* 어셈블리 [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->