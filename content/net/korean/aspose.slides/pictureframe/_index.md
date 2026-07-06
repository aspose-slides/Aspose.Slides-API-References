---
title: PictureFrame
second_title: Aspose.Sildes for .NET API 레퍼런스
description: 그 안에 그림이 포함된 프레임을 나타냅니다.
type: docs
weight: 9410
url: /ko/aspose.slides/pictureframe/
---
## PictureFrame 클래스

그 안에 그림이 포함된 프레임을 나타냅니다.

```csharp
public class PictureFrame : GeometryShape, IPictureFrame
```

## 속성

| 이름 | 설명 |
| --- | --- |
| [Adjustments](../../aspose.slides/geometryshape/adjustments) { get; } | 도형의 조정값 컬렉션을 반환합니다. 읽기 전용 [`IAdjustValueCollection`](../iadjustvaluecollection). |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | 도형에 연결된 대체 텍스트를 반환하거나 설정합니다. 읽기/쓰기 String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | 도형에 연결된 대체 텍스트의 제목을 반환하거나 설정합니다. 읽기/쓰기 String. |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | 속성은 도형이 흑백 표시 모드에서 렌더링되는 방식을 지정합니다. 읽기/쓰기 [`BlackWhiteMode`](../blackwhitemode). |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | 도형의 연결 지점 수를 반환합니다. 읽기 전용 Int32. |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | 도형의 사용자 정의 데이터를 반환합니다. 읽기 전용 [`ICustomData`](../icustomdata). |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | 도형에 적용된 픽셀 효과를 포함하는 EffectFormat 객체를 반환합니다. 참고: 효과 속성이 없는 특정 유형의 도형에 대해 null을 반환할 수 있습니다. 읽기 전용 [`IEffectFormat`](../ieffectformat). |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | 도형의 채우기 서식 속성을 포함하는 FillFormat 객체를 반환합니다. 참고: 채우기 속성이 없는 특정 유형의 도형에 대해 null을 반환할 수 있습니다. 읽기 전용 [`IFillFormat`](../ifillformat). |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | 도형 프레임의 속성을 반환하거나 설정합니다. 읽기/쓰기 [`IShapeFrame`](../ishapeframe). |
| [Height](../../aspose.slides/shape/height) { get; set; } | 도형의 높이를 포인트 단위로 가져오거나 설정합니다. 읽기/쓰기 Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | 도형이 숨겨져 있는지 여부를 결정합니다. 읽기/쓰기 Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | 마우스 클릭에 정의된 하이퍼링크를 반환하거나 설정합니다. 읽기/쓰기 [`IHyperlink`](../ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | 하이퍼링크 관리자를 반환합니다. 읽기 전용 [`IHyperlinkManager`](../ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | 마우스 오버에 정의된 하이퍼링크를 반환하거나 설정합니다. 읽기/쓰기 [`IHyperlink`](../ihyperlink). |
| [IsCameo](../../aspose.slides/pictureframe/iscameo) { get; } | PictureFrame이 Cameo 객체인지 여부를 결정합니다. 읽기 전용 Boolean. |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | 'Mark as decorative' 옵션을 가져오거나 설정합니다. 읽기/쓰기 Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | 도형이 그룹화되어 있는지 여부를 결정합니다. 읽기 전용 Boolean. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | 도형이 TextHolder_PPT인지 여부를 결정합니다. 읽기 전용 Boolean. |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | 도형의 선 서식 속성을 포함하는 LineFormat 객체를 반환합니다. 참고: 선 속성이 없는 특정 유형의 도형에 대해 null을 반환할 수 있습니다. 읽기 전용 [`ILineFormat`](../ilineformat). |
| [Name](../../aspose.slides/shape/name) { get; set; } | 도형의 이름을 반환하거나 설정합니다. null이 아니어야 합니다. 필요한 경우 빈 문자열 값을 사용하십시오. 읽기/쓰기 String. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | 도형의 수명 동안 일정하게 유지되며 PowerPoint 또는 인터옵 코드가 문서 어디서든 도형을 신뢰성 있게 참조할 수 있게 하는 슬라이드 범위 고유 식별자를 반환합니다. 읽기 전용 UInt32. 또 보기 [`UniqueId`](../shape/uniqueid). |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | 도형이 그룹화된 경우 상위 GroupShape 객체를 반환합니다. 그렇지 않으면 null을 반환합니다. 읽기 전용 [`IGroupShape`](../igroupshape). |
| [PictureFormat](../../aspose.slides/pictureframe/pictureformat) { get; } | 그림 프레임에 대한 PictureFillFormat 객체를 반환합니다. 읽기 전용 [`IPictureFillFormat`](../ipicturefillformat). |
| [PictureFrameLock](../../aspose.slides/pictureframe/pictureframelock) { get; } | 도형의 잠금을 반환합니다. 읽기 전용 [`IPictureFrameLock`](../ipictureframelock). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | 도형에 대한 자리 표시자를 반환합니다. 도형에 자리 표시자가 없으면 null을 반환합니다. 읽기 전용 [`IPlaceholder`](../iplaceholder). |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | 슬라이드의 상위 프레젠테이션을 반환합니다. 읽기 전용 [`IPresentation`](../ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | 원시 도형 프레임 속성을 반환하거나 설정합니다. 읽기/쓰기 [`IShapeFrame`](../ishapeframe). |
| [RelativeScaleHeight](../../aspose.slides/pictureframe/relativescaleheight) { get; set; } | 그림 프레임의 높이 비율(원본 이미지 크기에 대한 비율)을 반환하거나 설정합니다. 값 1.0은 100%에 해당합니다. 읽기/쓰기 Single. |
| [RelativeScaleWidth](../../aspose.slides/pictureframe/relativescalewidth) { get; set; } | 그림 프레임의 폭 비율(원본 이미지 크기에 대한 비율)을 반환하거나 설정합니다. 값 1.0은 100%에 해당합니다. 읽기/쓰기 Single. |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | 지정된 도형이 z축을 중심으로 회전한 각도를 반환하거나 설정합니다. 양수 값은 시계 방향 회전을 나타내고, 음수 값은 반시계 방향 회전을 나타냅니다. 읽기/쓰기 Single. |
| [ShapeLock](../../aspose.slides/pictureframe/shapelock) { get; } | 도형의 잠금을 반환합니다. 읽기 전용 [`IPictureFrameLock`](../ipictureframelock). (2 개 속성) |
| [ShapeStyle](../../aspose.slides/geometryshape/shapestyle) { get; } | 도형의 스타일 객체를 반환합니다. 읽기 전용 [`IShapeStyle`](../ishapestyle). |
| override [ShapeType](../../aspose.slides/pictureframe/shapetype) { get; set; } | PictureFrame의 AutoShape 유형을 반환하거나 설정합니다. [`ShapeType`](../shapetype) 집합의 모든 허용 항목이 있으며, 모든 종류의 선은 제외됩니다: |
| [Slide](../../aspose.slides/shape/slide) { get; } | 도형의 상위 슬라이드를 반환합니다. 읽기 전용 [`IBaseSlide`](../ibaseslide). |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | 도형의 3D 효과 속성을 포함하는 ThreeDFormat 객체를 반환합니다. 참고: 3D 속성이 없는 특정 유형의 도형에 대해 null을 반환할 수 있습니다. 읽기 전용 [`IThreeDFormat`](../ithreedformat). |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | 애드인이나 기타 코드에서 사용하기 위한 내부 프레젠테이션 범위 식별자를 반환합니다. 이 값은 사용자가 또는 프로그래밍 방식으로 재할당될 수 있으므로 지속적인 고유 키로 간주해서는 안 됩니다. 읽기 전용 UInt32. 또 보기 [`OfficeInteropShapeId`](../shape/officeinteropshapeid). |
| [Width](../../aspose.slides/shape/width) { get; set; } | 도형의 너비를 포인트 단위로 가져오거나 설정합니다. 읽기/쓰기 Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | 도형 왼쪽 위 모서리의 x좌표를 포인트 단위로 가져오거나 설정합니다. 읽기/쓰기 Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | 도형 왼쪽 위 모서리의 y좌표를 포인트 단위로 가져오거나 설정합니다. 읽기/쓰기 Single. |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | 도형의 z-순서 위치를 반환합니다. Shapes[0]은 z-순서의 가장 뒤에 있는 도형을 반환하고, Shapes[Shapes.Count - 1]은 가장 앞에 있는 도형을 반환합니다. 읽기 전용 Int32. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | 플래이스홀더가 없을 경우 새 플래이스홀더를 추가하고 지정된 플래이스홀더 속성을 설정합니다. |
| [CreateShapeElements](../../aspose.slides/geometryshape/createshapeelements)() | 도형 요소 배열을 생성하고 반환합니다. |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | 현재 도형이 상속받은 레이아웃 및/또는 마스터 슬라이드의 도형인 기본 플래이스홀더 도형을 반환합니다. 현재 도형이 상속받지 않은 경우 null을 반환합니다. |
| [GetGeometryPaths](../../aspose.slides/geometryshape/getgeometrypaths)() | 기하학적 도형의 경로 복사본을 반환합니다. 좌표는 도형의 왼쪽 상단 모서리를 기준으로 합니다. |
| [GetImage](../../aspose.slides/shape/getimage)() | 도형 썸네일을 반환합니다. 기본적으로 ShapeThumbnailBounds.Shape 도형 썸네일 경계 타입이 사용됩니다. |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | 도형 썸네일을 반환합니다. |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | 렌더링된 콘텐츠를 기반으로 계산된 도형의 시각적 경계를 가져옵니다. |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | 이 도형이 플래이스홀더가 아님을 정의합니다. |
| [SetGeometryPath](../../aspose.slides/geometryshape/setgeometrypath)(IGeometryPath) | [`IGeometryPath`](../igeometrypath) 객체에서 도형 기하학을 업데이트합니다. 좌표는 도형의 왼쪽 상단 모서리를 기준으로 해야 합니다. 도형 유형을 ([`ShapeType`](../geometryshape/shapetype))에서 Custom으로 변경합니다. |
| [SetGeometryPaths](../../aspose.slides/geometryshape/setgeometrypaths)(IGeometryPath[]) | [`IGeometryPath`](../igeometrypath) 배열에서 도형 기하학을 업데이트합니다. 좌표는 도형의 왼쪽 상단 모서리를 기준으로 해야 합니다. 도형 유형을 ([`ShapeType`](../geometryshape/shapetype))에서 Custom으로 변경합니다. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | 도형 내용을 SVG 파일로 저장합니다. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | 도형 내용을 SVG 파일로 저장합니다. |

### 예제

다음 예제는 Audio Frame 썸네일을 변경하는 방법을 보여줍니다.

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
    audioFrame.PictureFormat.Picture.Image = audioImage;
	//수정된 프레젠테이션을 디스크에 저장합니다.
    presentation.Save("example_out.pptx", SaveFormat.Pptx);
}
```

### 관련 항목

* 클래스 [GeometryShape](../geometryshape)
* 인터페이스 [IPictureFrame](../ipictureframe)
* 네임스페이스 [Aspose.Slides](../../aspose.slides)
* 어셈블리 [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->