---
title: PictureFrame
second_title: Aspose.Sildes for .NET API 참조
description: 그림이 포함된 프레임을 나타냅니다.
type: docs
weight: 9410
url: /ko/aspose.slides/pictureframe/
---
## PictureFrame 클래스

형상 내부에 그림이 포함된 프레임을 나타냅니다.

```csharp
public class PictureFrame : GeometryShape, IPictureFrame
```

## 속성

| Name | Description |
| --- | --- |
| [Adjustments](../../aspose.slides/geometryshape/adjustments) { get; } | 형상의 조정값 컬렉션을 반환합니다. 읽기 전용 [`IAdjustValueCollection`](../iadjustvaluecollection). |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | 형상과 연관된 대체 텍스트를 반환하거나 설정합니다. 읽기/쓰기 문자열. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | 형상과 연관된 대체 텍스트의 제목을 반환하거나 설정합니다. 읽기/쓰기 문자열. |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | 속성은 형상이 흑백 디스플레이 모드에서 어떻게 렌더링되는지를 지정합니다. 읽기/쓰기 [`BlackWhiteMode`](../blackwhitemode). |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | 형상의 연결 지점 수를 반환합니다. 읽기 전용 Int32. |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | 형상의 사용자 정의 데이터를 반환합니다. 읽기 전용 [`ICustomData`](../icustomdata). |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | 형상에 적용된 픽셀 효과를 포함하는 EffectFormat 객체를 반환합니다. 참고: 효과 속성이 없는 특정 형상 유형에 대해서는 null을 반환할 수 있습니다. 읽기 전용 [`IEffectFormat`](../ieffectformat). |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | 형상의 채우기 서식 속성을 포함하는 FillFormat 객체를 반환합니다. 참고: 채우기 속성이 없는 특정 형상 유형에 대해서는 null을 반환할 수 있습니다. 읽기 전용 [`IFillFormat`](../ifillformat). |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | 형상 프레임의 속성을 반환하거나 설정합니다. 읽기/쓰기 [`IShapeFrame`](../ishapeframe). |
| [Height](../../aspose.slides/shape/height) { get; set; } | 포인트 단위로 측정된 형상의 높이를 가져오거나 설정합니다. 읽기/쓰기 Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | 형상이 숨겨져 있는지 여부를 결정합니다. 읽기/쓰기 Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | 마우스 클릭에 정의된 하이퍼링크를 반환하거나 설정합니다. 읽기/쓰기 [`IHyperlink`](../ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | 하이퍼링크 관리자를 반환합니다. 읽기 전용 [`IHyperlinkManager`](../ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | 마우스 오버에 정의된 하이퍼링크를 반환하거나 설정합니다. 읽기/쓰기 [`IHyperlink`](../ihyperlink). |
| [IsCameo](../../aspose.slides/pictureframe/iscameo) { get; } | PictureFrame이 Cameo 객체인지 여부를 결정합니다. 읽기 전용 Boolean. |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | ‘장식으로 표시’ 옵션을 가져오거나 설정합니다. 읽기/쓰기 Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | 형상이 그룹화되어 있는지 여부를 결정합니다. 읽기 전용 Boolean. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | 형상이 TextHolder_PPT인지 여부를 결정합니다. 읽기 전용 Boolean. |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | 형상의 선 서식 속성을 포함하는 LineFormat 객체를 반환합니다. 참고: 선 속성이 없는 특정 형상 유형에 대해서는 null을 반환할 수 있습니다. 읽기 전용 [`ILineFormat`](../ilineformat). |
| [Name](../../aspose.slides/shape/name) { get; set; } | 형상의 이름을 반환하거나 설정합니다. null일 수 없습니다. 필요하면 빈 문자열 값을 사용하십시오. 읽기/쓰기 문자열. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | 형상의 수명 동안 일정하게 유지되는 슬라이드 범위 고유 식별자를 반환합니다. 이를 통해 PowerPoint 또는 인터옵 코드는 문서 어디서든 형상을 안정적으로 참조할 수 있습니다. 읽기 전용 UInt32. 또한 [`UniqueId`](../shape/uniqueid)를 참조하십시오. |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | 형상이 그룹화된 경우 부모 GroupShape 객체를 반환합니다. 그렇지 않으면 null을 반환합니다. 읽기 전용 [`IGroupShape`](../igroupshape). |
| [PictureFormat](../../aspose.slides/pictureframe/pictureformat) { get; } | 그림 프레임에 대한 PictureFillFormat 객체를 반환합니다. 읽기 전용 [`IPictureFillFormat`](../ipicturefillformat). |
| [PictureFrameLock](../../aspose.slides/pictureframe/pictureframelock) { get; } | 형상의 잠금을 반환합니다. 읽기 전용 [`IPictureFrameLock`](../ipictureframelock). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | 형상의 자리 표시자를 반환합니다. 형상에 자리 표시자가 없으면 null을 반환합니다. 읽기 전용 [`IPlaceholder`](../iplaceholder). |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | 슬라이드의 상위 프레젠테이션을 반환합니다. 읽기 전용 [`IPresentation`](../ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | 원시 형상 프레임 속성을 반환하거나 설정합니다. 읽기/쓰기 [`IShapeFrame`](../ishapeframe). |
| [RelativeScaleHeight](../../aspose.slides/pictureframe/relativescaleheight) { get; set; } | 그림 프레임의 높이 비율(원본 그림 크기에 대한) 스케일을 반환하거나 설정합니다. 값 1.0은 100%에 해당합니다. 읽기/쓰기 Single. |
| [RelativeScaleWidth](../../aspose.slides/pictureframe/relativescalewidth) { get; set; } | 그림 프레임의 너비 비율(원본 그림 크기에 대한) 스케일을 반환하거나 설정합니다. 값 1.0은 100%에 해당합니다. 읽기/쓰기 Single. |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | 지정된 형상이 z축을 중심으로 회전된 각도를 반환하거나 설정합니다. 양수값은 시계 방향 회전을 의미하고, 음수값은 반시계 방향 회전을 의미합니다. 읽기/쓰기 Single. |
| [ShapeLock](../../aspose.slides/pictureframe/shapelock) { get; } | 형상의 잠금을 반환합니다. 읽기 전용 [`IPictureFrameLock`](../ipictureframelock). (속성 2개) |
| [ShapeStyle](../../aspose.slides/geometryshape/shapestyle) { get; } | 형상의 스타일 객체를 반환합니다. 읽기 전용 [`IShapeStyle`](../ishapestyle). |
| override [ShapeType](../../aspose.slides/pictureframe/shapetype) { get; set; } | PictureFrame에 대한 AutoShape 유형을 반환하거나 설정합니다. [`ShapeType`](../shapetype) 집합의 모든 항목이 허용되지만, 모든 종류의 선은 제외됩니다. |
| [Slide](../../aspose.slides/shape/slide) { get; } | 형상의 상위 슬라이드를 반환합니다. 읽기 전용 [`IBaseSlide`](../ibaseslide). |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | 형상의 3D 효과 속성을 포함하는 ThreeDFormat 객체를 반환합니다. 참고: 3D 속성이 없는 특정 형상 유형에 대해서는 null을 반환할 수 있습니다. 읽기 전용 [`IThreeDFormat`](../ithreedformat). |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | 애드인 또는 기타 코드에서 사용하도록 의도된 내부 프레젠테이션 범위 식별자를 반환합니다. 이 값은 사용자 또는 프로그램에 의해 재할당될 수 있으므로 영구적인 고유 키로 취급해서는 안 됩니다. 읽기 전용 UInt32. 또한 [`OfficeInteropShapeId`](../shape/officeinteropshapeid)를 참조하십시오. |
| [Width](../../aspose.slides/shape/width) { get; set; } | 포인트 단위로 측정된 형상의 너비를 가져오거나 설정합니다. 읽기/쓰기 Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | 형상의 좌상단 모서리의 x 좌표를 포인트 단위로 가져오거나 설정합니다. 읽기/쓰기 Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | 형상의 좌상단 모서리의 y 좌표를 포인트 단위로 가져오거나 설정합니다. 읽기/쓰기 Single. |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | 형상의 z 순서 위치를 반환합니다. Shapes[0]은 z 순서의 뒤쪽에 있는 형상을 반환하고, Shapes[Shapes.Count - 1]은 앞쪽에 있는 형상을 반환합니다. 읽기 전용 Int32. |

## 메서드

| Name | Description |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | 새 자리 표시자가 없을 경우 새 자리 표시자를 추가하고 지정된 자리 표시자 속성을 설정합니다. |
| [CreateShapeElements](../../aspose.slides/geometryshape/createshapeelements)() | 형상의 요소 배열을 생성하고 반환합니다. |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | 기본 자리 표시자 형상을 반환합니다(레이아웃 및/또는 마스터 슬라이드에서 현재 형상이 상속받은 형상). 현재 형상이 상속받지 않은 경우 null을 반환합니다. |
| [GetGeometryPaths](../../aspose.slides/geometryshape/getgeometrypaths)() | 기하학 형상의 경로 복사본을 반환합니다. 좌표는 형상의 좌상단 모서리를 기준으로 상대적입니다. |
| [GetImage](../../aspose.slides/shape/getimage)() | 형상 썸네일을 반환합니다. 기본값으로 ShapeThumbnailBounds.Shape 형상 썸네일 경계 유형이 사용됩니다. |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | 형상 썸네일을 반환합니다. |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | 렌더링된 콘텐츠를 기준으로 계산된 형상의 시각적 경계를 가져옵니다. |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | 이 형상이 자리 표시자가 아님을 정의합니다. |
| [SetGeometryPath](../../aspose.slides/geometryshape/setgeometrypath)(IGeometryPath) | [`IGeometryPath`](../igeometrypath) 객체로부터 형상 기하학을 업데이트합니다. 좌표는 형상의 좌상단 모서리를 기준으로 상대적이어야 합니다. 형상의 유형([`ShapeType`](../geometryshape/shapetype))을 Custom으로 변경합니다. |
| [SetGeometryPaths](../../aspose.slides/geometryshape/setgeometrypaths)(IGeometryPath[]) | [`IGeometryPath`](../igeometrypath) 배열로부터 형상 기하학을 업데이트합니다. 좌표는 형상의 좌상단 모서리를 기준으로 상대적이어야 합니다. 형상의 유형([`ShapeType`](../geometryshape/shapetype))을 Custom으로 변경합니다. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | 형상의 내용을 SVG 파일로 저장합니다. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | 형상의 내용을 SVG 파일로 저장합니다. |

### 예제

다음 예제는 오디오 프레임 썸네일을 변경하는 방법을 보여줍니다.

```csharp
[C#]
using (var presentation = new Presentation())
{
    var slide = presentation.Slides[0];
    // 지정된 위치와 크기로 슬라이드에 오디오 프레임을 추가합니다.
    var audioStream = new FileStream("sample2.mp3", FileMode.Open, FileAccess.Read);
    var audioFrame = slide.Shapes.AddAudioFrameEmbedded(150, 100, 50, 50, audioStream);
    audioStream.Dispose();
    // 프레젠테이션 리소스에 이미지를 추가합니다.
    var imageStream = File.OpenRead("eagle.jpeg");
    var audioImage = presentation.Images.AddImage(imageStream);
    imageStream.Dispose();
    // 오디오 프레임의 이미지를 설정합니다.
	//수정된 프레젠테이션을 디스크에 저장합니다
    presentation.Save("example_out.pptx", SaveFormat.Pptx);
}
```

### 참조

* 클래스 [GeometryShape](../geometryshape)
* 인터페이스 [IPictureFrame](../ipictureframe)
* 네임스페이스 [Aspose.Slides](../../aspose.slides)
* 어셈블리 [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->