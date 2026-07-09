---
title: VideoFrame
second_title: Aspose.Sildes for .NET API 레퍼런스
description: 슬라이드에 있는 비디오 클립을 나타냅니다.
type: docs
weight: 11720
url: /ko/aspose.slides/videoframe/
---
## VideoFrame 클래스

슬라이드에 있는 비디오 클립을 나타냅니다.

```csharp
public class VideoFrame : PictureFrame, IVideoFrame
```

## 속성

| 이름 | 설명 |
| --- | --- |
| [Adjustments](../../aspose.slides/geometryshape/adjustments) { get; } | 형상의 조정값 컬렉션을 반환합니다. 읽기 전용 [`IAdjustValueCollection`](../iadjustvaluecollection). |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | 형상에 연결된 대체 텍스트를 반환하거나 설정합니다. 읽기/쓰기 String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | 형상에 연결된 대체 텍스트의 제목을 반환하거나 설정합니다. 읽기/쓰기 String. |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | 형상이 흑백 표시 모드에서 렌더링되는 방식을 지정하는 속성입니다. 읽기/쓰기 [`BlackWhiteMode`](../blackwhitemode). |
| [CaptionTracks](../../aspose.slides/videoframe/captiontracks) { get; } | 비디오 프레임에 연결된 폐쇄 캡션 컬렉션을 가져옵니다. 이 속성은 읽기 전용이며 모든 캡션 트랙을 포함하는 [`ICaptionsCollection`](../icaptionscollection)를 반환합니다. |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | 형상의 연결 지점 수를 반환합니다. 읽기 전용 Int32. |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | 형상의 사용자 정의 데이터를 반환합니다. 읽기 전용 [`ICustomData`](../icustomdata). |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | 형상에 적용된 픽셀 효과를 포함하는 EffectFormat 객체를 반환합니다. 참고: 효과 속성이 없는 특정 형상 유형의 경우 null을 반환할 수 있습니다. 읽기 전용 [`IEffectFormat`](../ieffectformat). |
| [EmbeddedVideo](../../aspose.slides/videoframe/embeddedvideo) { get; set; } | 내장 비디오 객체를 반환하거나 설정합니다. 읽기/쓰기 [`IVideo`](../ivideo). |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | 형상의 채우기 서식 속성을 포함하는 FillFormat 객체를 반환합니다. 참고: 채우기 속성이 없는 특정 형상 유형의 경우 null을 반환할 수 있습니다. 읽기 전용 [`IFillFormat`](../ifillformat). |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | 형상 프레임의 속성을 반환하거나 설정합니다. 읽기/쓰기 [`IShapeFrame`](../ishapeframe). |
| [FullScreenMode](../../aspose.slides/videoframe/fullscreenmode) { get; set; } | 비디오가 전체 화면 모드로 표시되는지를 결정합니다. 읽기/쓰기 Boolean. |
| [Height](../../aspose.slides/shape/height) { get; set; } | 형상의 높이를 포인트 단위로 가져오거나 설정합니다. 읽기/쓰기 Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | 형상이 숨겨져 있는지를 결정합니다. 읽기/쓰기 Boolean. |
| [HideAtShowing](../../aspose.slides/videoframe/hideatshowing) { get; set; } | VideoFrame이 숨겨져 있는지를 결정합니다. 읽기/쓰기 Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | 마우스 클릭에 정의된 하이퍼링크를 반환하거나 설정합니다. 읽기/쓰기 [`IHyperlink`](../ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | 하이퍼링크 관리자를 반환합니다. 읽기 전용 [`IHyperlinkManager`](../ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | 마우스 오버에 정의된 하이퍼링크를 반환하거나 설정합니다. 읽기/쓰기 [`IHyperlink`](../ihyperlink). |
| [IsCameo](../../aspose.slides/pictureframe/iscameo) { get; } | PictureFrame이 Cameo 객체인지 여부를 결정합니다. 읽기 전용 Boolean. |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | ‘장식용으로 표시’ 옵션을 가져오거나 설정합니다. 읽기/쓰기 Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | 형상이 그룹화되어 있는지를 결정합니다. 읽기 전용 Boolean. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | 형상이 TextHolder_PPT인지 여부를 결정합니다. 읽기 전용 Boolean. |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | 형상의 선 서식 속성을 포함하는 LineFormat 객체를 반환합니다. 참고: 선 속성이 없는 특정 형상 유형의 경우 null을 반환할 수 있습니다. 읽기 전용 [`ILineFormat`](../ilineformat). |
| [LinkPathLong](../../aspose.slides/videoframe/linkpathlong) { get; set; } | VideoFrame에 연결된 비디오 파일의 이름을 반환하거나 설정합니다. 읽기/쓰기 String. |
| [Name](../../aspose.slides/shape/name) { get; set; } | 형상의 이름을 반환하거나 설정합니다. null이 아니어야 합니다. 필요하면 빈 문자열을 사용하세요. 읽기/쓰기 String. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | 슬라이드 범위 내에서 형상의 수명 동안 일정하게 유지되는 고유 식별자를 반환합니다. 이를 통해 PowerPoint 또는 인터옵 코드가 문서 어디서든 형상을 안정적으로 참조할 수 있습니다. 읽기 전용 UInt32. 또한 [`UniqueId`](../shape/uniqueid)을 참조하십시오. |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | 형상이 그룹화된 경우 상위 GroupShape 객체를 반환합니다. 그렇지 않으면 null을 반환합니다. 읽기 전용 [`IGroupShape`](../igroupshape). |
| [PictureFormat](../../aspose.slides/pictureframe/pictureformat) { get; } | 그림 프레임에 대한 PictureFillFormat 객체를 반환합니다. 읽기 전용 [`IPictureFillFormat`](../ipicturefillformat). |
| [PictureFrameLock](../../aspose.slides/pictureframe/pictureframelock) { get; } | 형상의 잠금을 반환합니다. 읽기 전용 [`IPictureFrameLock`](../ipictureframelock). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | 형상의 자리표시자를 반환합니다. 형태에 자리표시자가 없으면 null을 반환합니다. 읽기 전용 [`IPlaceholder`](../iplaceholder). |
| [PlayLoopMode](../../aspose.slides/videoframe/playloopmode) { get; set; } | 비디오가 반복 재생되는지를 결정합니다. 읽기/쓰기 Boolean. |
| [PlayMode](../../aspose.slides/videoframe/playmode) { get; set; } | 비디오 재생 모드를 반환하거나 설정합니다. 읽기/쓰기 [`VideoPlayModePreset`](../videoplaymodepreset). |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | 슬라이드의 상위 프레젠테이션을 반환합니다. 읽기 전용 [`IPresentation`](../ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | 원시 형상 프레임 속성을 반환하거나 설정합니다. 읽기/쓰기 [`IShapeFrame`](../ishapeframe). |
| [RelativeScaleHeight](../../aspose.slides/pictureframe/relativescaleheight) { get; set; } | 그림 프레임의 높이 비율(원본 이미지 크기에 대한 비율)을 반환하거나 설정합니다. 값 1.0은 100%에 해당합니다. 읽기/쓰기 Single. |
| [RelativeScaleWidth](../../aspose.slides/pictureframe/relativescalewidth) { get; set; } | 그림 프레임의 너비 비율(원본 이미지 크기에 대한 비율)을 반환하거나 설정합니다. 값 1.0은 100%에 해당합니다. 읽기/쓰기 Single. |
| [RewindVideo](../../aspose.slides/videoframe/rewindvideo) { get; set; } | 동영상 재생이 끝난 직후 비디오가 자동으로 처음으로 되감기 되는지를 결정합니다. 읽기/쓰기 Boolean. |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | 특정 형상이 Z축을 중심으로 회전한 각도를 반환하거나 설정합니다. 양수 값은 시계 방향 회전을, 음수 값은 반시계 방향 회전을 나타냅니다. 읽기/쓰기 Single. |
| [ShapeLock](../../aspose.slides/pictureframe/shapelock) { get; } | 형상의 잠금을 반환합니다. 읽기 전용 [`IPictureFrameLock`](../ipictureframelock). (2개의 속성) |
| [ShapeStyle](../../aspose.slides/geometryshape/shapestyle) { get; } | 형상의 스타일 객체를 반환합니다. 읽기 전용 [`IShapeStyle`](../ishapestyle). |
| override [ShapeType](../../aspose.slides/pictureframe/shapetype) { get; set; } | PictureFrame의 AutoShape 유형을 반환하거나 설정합니다. [`ShapeType`](../shapetype) 집합의 모든 항목이 허용되지만, 모든 종류의 선은 제외됩니다: |
| [Slide](../../aspose.slides/shape/slide) { get; } | 형상의 상위 슬라이드를 반환합니다. 읽기 전용 [`IBaseSlide`](../ibaseslide). |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | 형상의 3D 효과 속성을 포함하는 ThreeDFormat 객체를 반환합니다. 참고: 3D 속성이 없는 특정 형상 유형의 경우 null을 반환할 수 있습니다. 읽기 전용 [`IThreeDFormat`](../ithreedformat). |
| [TrimFromEnd](../../aspose.slides/videoframe/trimfromend) { get; set; } | 끝 자르기 [ms] |
| [TrimFromStart](../../aspose.slides/videoframe/trimfromstart) { get; set; } | 시작 자르기 [ms] |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | 애드인이나 기타 코드에서 사용할 수 있도록 내부적으로 제공되는, 프레젠테이션 범위 식별자를 반환합니다. 이 값은 사용자나 프로그램에 의해 재할당될 수 있으므로 영구적인 고유 키로 취급해서는 안 됩니다. 읽기 전용 UInt32. 또한 [`OfficeInteropShapeId`](../shape/officeinteropshapeid)을 참조하십시오. |
| [Volume](../../aspose.slides/videoframe/volume) { get; set; } | 오디오 볼륨을 반환하거나 설정합니다. 읽기/쓰기 [`AudioVolumeMode`](../audiovolumemode). |
| [Width](../../aspose.slides/shape/width) { get; set; } | 형상의 너비를 포인트 단위로 가져오거나 설정합니다. 읽기/쓰기 Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | 형상의 좌상단 모서리의 x 좌표를 포인트 단위로 가져오거나 설정합니다. 읽기/쓰기 Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | 형상의 좌상단 모서리의 y 좌표를 포인트 단위로 가져오거나 설정합니다. 읽기/쓰기 Single. |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | z-순서에서 형상의 위치를 반환합니다. Shapes[0]은 z-순서 뒤쪽에 있는 형상을 반환하고, Shapes[Shapes.Count - 1]은 앞쪽에 있는 형상을 반환합니다. 읽기 전용 Int32. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | 플레이스홀더가 없을 경우 새 플레이스홀더를 추가하고 지정된 플레이스홀더의 속성을 설정합니다. |
| [CreateShapeElements](../../aspose.slides/geometryshape/createshapeelements)() | 형상의 요소 배열을 생성하여 반환합니다. |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | 기본 플레이스홀더 형상을 반환합니다(현재 형상이 상속받은 레이아웃 또는 마스터 슬라이드의 형상). 현재 형상이 상속받지 않은 경우 null을 반환합니다. |
| [GetGeometryPaths](../../aspose.slides/geometryshape/getgeometrypaths)() | 지오메트리 형상의 경로 복사본을 반환합니다. 좌표는 형상의 왼쪽 상단 모서를 기준으로 합니다. |
| [GetImage](../../aspose.slides/shape/getimage)() | 형상의 썸네일을 반환합니다. 기본적으로 ShapeThumbnailBounds.Shape 형상의 썸네일 경계 타입이 사용됩니다. |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | 형상의 썸네일을 반환합니다. |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | 렌더링된 콘텐츠를 기반으로 계산된 형상의 시각적 경계를 가져옵니다. |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | 이 형상이 플레이스홀더가 아님을 정의합니다. |
| [SetGeometryPath](../../aspose.slides/geometryshape/setgeometrypath)(IGeometryPath) | [`IGeometryPath`](../igeometrypath) 객체에서 형상 지오메트리를 업데이트합니다. 좌표는 형상의 왼쪽 상단 모서를 기준으로 해야 합니다. 형상의 유형([`ShapeType`](../geometryshape/shapetype))을 Custom으로 변경합니다. |
| [SetGeometryPaths](../../aspose.slides/geometryshape/setgeometrypaths)(IGeometryPath[]) | [`IGeometryPath`](../igeometrypath) 배열에서 형상 지오메트리를 업데이트합니다. 좌표는 형상의 왼쪽 상단 모서를 기준으로 해야 합니다. 형상의 유형([`ShapeType`](../geometryshape/shapetype))을 Custom으로 변경합니다. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | 형상의 콘텐츠를 SVG 파일로 저장합니다. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | 형상의 콘텐츠를 SVG 파일로 저장합니다. |

### 참조

* 클래스 [PictureFrame](../pictureframe)
* 인터페이스 [IVideoFrame](../ivideoframe)
* 네임스페이스 [Aspose.Slides](../../aspose.slides)
* 어셈블리 [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->