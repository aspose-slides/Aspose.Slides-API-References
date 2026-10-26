---
title: AudioFrame
second_title: Aspose.Sildes for .NET API 참조
description: 슬라이드에 있는 오디오 클립을 나타냅니다.
type: docs
weight: 870
url: /ko/aspose.slides/audioframe/
---
## AudioFrame 클래스

슬라이드에 있는 오디오 클립을 나타냅니다.

```csharp
public class AudioFrame : PictureFrame, IAudioFrame
```

## 속성

| 이름 | 설명 |
| --- | --- |
| [Adjustments](../../aspose.slides/geometryshape/adjustments) { get; } | shape의 조정값 컬렉션을 반환합니다. 읽기 전용 [`IAdjustValueCollection`](../iadjustvaluecollection). |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | shape와 연결된 대체 텍스트를 반환하거나 설정합니다. 읽기/쓰기 String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | shape와 연결된 대체 텍스트의 제목을 반환하거나 설정합니다. 읽기/쓰기 String. |
| [AudioCdEndTrack](../../aspose.slides/audioframe/audiocdendtrack) { get; set; } | 마지막 트랙 인덱스를 반환하거나 설정합니다. 읽기/쓰기 Int32. |
| [AudioCdEndTrackTime](../../aspose.slides/audioframe/audiocdendtracktime) { get; set; } | 마지막 트랙 시간을 반환하거나 설정합니다. 읽기/쓰기 Int32. |
| [AudioCdStartTrack](../../aspose.slides/audioframe/audiocdstarttrack) { get; set; } | 시작 트랙 인덱스를 반환하거나 설정합니다. 읽기/쓰기 Int32. |
| [AudioCdStartTrackTime](../../aspose.slides/audioframe/audiocdstarttracktime) { get; set; } | 시작 트랙 시간을 반환하거나 설정합니다. 읽기/쓰기 Int32. |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | shape가 흑백 표시 모드에서 렌더링되는 방식을 지정하는 속성입니다. 읽기/쓰기 [`BlackWhiteMode`](../blackwhitemode). |
| [CaptionTracks](../../aspose.slides/audioframe/captiontracks) { get; } | 오디오 프레임과 연결된 폐쇄 캡션 컬렉션을 가져옵니다. 이 속성은 읽기 전용이며 모든 캡션 트랙을 포함하는 [`ICaptionsCollection`](../icaptionscollection)를 반환합니다. |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | shape의 연결 지점 수를 반환합니다. 읽기 전용 Int32. |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | shape의 사용자 지정 데이터를 반환합니다. 읽기 전용 [`ICustomData`](../icustomdata). |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | shape에 적용된 픽셀 효과를 포함하는 EffectFormat 객체를 반환합니다. 참고: 효과 속성이 없는 특정 shape 유형의 경우 null을 반환할 수 있습니다. 읽기 전용 [`IEffectFormat`](../ieffectformat). |
| [Embedded](../../aspose.slides/audioframe/embedded) { get; } | 사운드가 프레젠테이션에 포함되어 있는지 여부를 확인합니다. 읽기 전용 Boolean. |
| [EmbeddedAudio](../../aspose.slides/audioframe/embeddedaudio) { get; set; } | 삽입된 오디오 객체를 반환하거나 설정합니다. 읽기/쓰기 [`IAudio`](../iaudio). |
| [FadeInDuration](../../aspose.slides/audioframe/fadeinduration) { get; set; } | 미디어의 초기 페이드 인 지속 시간을 밀리초 단위로 지정합니다. 읽기/쓰기 Single. |
| [FadeOutDuration](../../aspose.slides/audioframe/fadeoutduration) { get; set; } | 미디어의 종료 페이드 아웃 지속 시간을 밀리초 단위로 지정합니다. 읽기/쓰기 Single. |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | shape의 채우기 서식 속성을 포함하는 FillFormat 객체를 반환합니다. 참고: 채우기 속성이 없는 특정 shape 유형의 경우 null을 반환할 수 있습니다. 읽기 전용 [`IFillFormat`](../ifillformat). |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | shape 프레임의 속성을 반환하거나 설정합니다. 읽기/쓰기 [`IShapeFrame`](../ishapeframe). |
| [Height](../../aspose.slides/shape/height) { get; set; } | shape의 높이를 포인트 단위로 가져오거나 설정합니다. 읽기/쓰기 Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | shape가 숨겨져 있는지 여부를 결정합니다. 읽기/쓰기 Boolean. |
| [HideAtShowing](../../aspose.slides/audioframe/hideatshowing) { get; set; } | AudioFrame이 숨겨져 있는지 여부를 결정합니다. 읽기/쓰기 Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | 마우스 클릭에 정의된 하이퍼링크를 반환하거나 설정합니다. 읽기/쓰기 [`IHyperlink`](../ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | 하이퍼링크 관리자를 반환합니다. 읽기 전용 [`IHyperlinkManager`](../ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | 마우스 오버에 정의된 하이퍼링크를 반환하거나 설정합니다. 읽기/쓰기 [`IHyperlink`](../ihyperlink). |
| [IsCameo](../../aspose.slides/pictureframe/iscameo) { get; } | PictureFrame이 Cameo 객체인지 여부를 확인합니다. 읽기 전용 Boolean. |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | 'Mark as decorative' 옵션을 가져오거나 설정합니다. 읽기/쓰기 Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | shape가 그룹화되어 있는지 여부를 확인합니다. 읽기 전용 Boolean. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | shape가 TextHolder_PPT인지 여부를 확인합니다. 읽기 전용 Boolean. |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | shape의 선 서식 속성을 포함하는 LineFormat 객체를 반환합니다. 참고: 선 속성이 없는 특정 shape 유형의 경우 null을 반환할 수 있습니다. 읽기 전용 [`ILineFormat`](../ilineformat). |
| [LinkPathLong](../../aspose.slides/audioframe/linkpathlong) { get; set; } | AudioFrame에 연결된 오디오 파일의 이름을 반환하거나 설정합니다. 읽기/쓰기 String. |
| [Name](../../aspose.slides/shape/name) { get; set; } | shape의 이름을 반환하거나 설정합니다. null이 될 수 없습니다. 필요한 경우 빈 문자열을 사용하세요. 읽기/쓰기 String. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | shape의 수명 동안 일정하게 유지되는 슬라이드 범위 고유 식별자를 반환하며, PowerPoint나 인터옵 코드가 문서 어디에서든 shape를 신뢰성 있게 참조할 수 있게 합니다. 읽기 전용 UInt32. 또한 [`UniqueId`](../shape/uniqueid)를 참조하세요. |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | shape가 그룹화된 경우 상위 GroupShape 객체를 반환합니다. 그렇지 않으면 null을 반환합니다. 읽기 전용 [`IGroupShape`](../igroupshape). |
| [PictureFormat](../../aspose.slides/pictureframe/pictureformat) { get; } | picture frame에 대한 PictureFillFormat 객체를 반환합니다. 읽기 전용 [`IPictureFillFormat`](../ipicturefillformat). |
| [PictureFrameLock](../../aspose.slides/pictureframe/pictureframelock) { get; } | shape의 잠금을 반환합니다. 읽기 전용 [`IPictureFrameLock`](../ipictureframelock). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | shape의 플레이스홀더를 반환합니다. shape에 플레이스홀더가 없으면 null을 반환합니다. 읽기 전용 [`IPlaceholder`](../iplaceholder). |
| [PlayAcrossSlides](../../aspose.slides/audioframe/playacrossslides) { get; set; } | 오디오가 슬라이드 전역으로 재생되는지 여부를 결정합니다. 읽기/쓰기 Boolean. |
| [PlayLoopMode](../../aspose.slides/audioframe/playloopmode) { get; set; } | 오디오가 반복 재생되는지 여부를 결정합니다. 읽기/쓰기 Boolean. |
| [PlayMode](../../aspose.slides/audioframe/playmode) { get; set; } | 오디오 재생 모드를 반환하거나 설정합니다. 읽기/쓰기 [`AudioPlayModePreset`](../audioplaymodepreset). |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | 슬라이드의 상위 프레젠테이션을 반환합니다. 읽기 전용 [`IPresentation`](../ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | 원시 shape 프레임의 속성을 반환하거나 설정합니다. 읽기/쓰기 [`IShapeFrame`](../ishapeframe). |
| [RelativeScaleHeight](../../aspose.slides/pictureframe/relativescaleheight) { get; set; } | picture frame의 높이 스케일(원본 이미지 크기에 대한 비율)을 반환하거나 설정합니다. 값 1.0은 100%에 해당합니다. 읽기/쓰기 Single. |
| [RelativeScaleWidth](../../aspose.slides/pictureframe/relativescalewidth) { get; set; } | picture frame의 너비 스케일(원본 이미지 크기에 대한 비율)을 반환하거나 설정합니다. 값 1.0은 100%에 해당합니다. 읽기/쓰기 Single. |
| [RewindAudio](../../aspose.slides/audioframe/rewindaudio) { get; set; } | 오디오가 재생 후 자동으로 시작 지점으로 되감기되는지 여부를 결정합니다. 읽기/쓰기 Boolean. |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | 지정된 shape가 z축을 중심으로 회전된 각도를 반환하거나 설정합니다. 양수 값은 시계 방향 회전을, 음수 값은 반시계 방향 회전을 나타냅니다. 읽기/쓰기 Single. |
| [ShapeLock](../../aspose.slides/pictureframe/shapelock) { get; } | shape의 잠금을 반환합니다. 읽기 전용 [`IPictureFrameLock`](../ipictureframelock). (2개의 속성) |
| [ShapeStyle](../../aspose.slides/geometryshape/shapestyle) { get; } | shape의 스타일 객체를 반환합니다. 읽기 전용 [`IShapeStyle`](../ishapestyle). |
| override [ShapeType](../../aspose.slides/pictureframe/shapetype) { get; set; } | PictureFrame에 대한 AutoShape 유형을 반환하거나 설정합니다. [`ShapeType`](../shapetype) 집합의 모든 항목이 허용되지만, 모든 종류의 선은 제외됩니다: |
| [Slide](../../aspose.slides/shape/slide) { get; } | shape의 상위 슬라이드를 반환합니다. 읽기 전용 [`IBaseSlide`](../ibaseslide). |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | shape의 3D 효과 속성을 포함하는 ThreeDFormat 객체를 반환합니다. 참고: 3D 속성이 없는 특정 shape 유형의 경우 null을 반환할 수 있습니다. 읽기 전용 [`IThreeDFormat`](../ithreedformat). |
| [TrimFromEnd](../../aspose.slides/audioframe/trimfromend) { get; set; } | 재생 중 미디어 끝에서 제거할 지속 시간을 밀리초 단위로 지정합니다. 읽기/쓰기 Single. |
| [TrimFromStart](../../aspose.slides/audioframe/trimfromstart) { get; set; } | 재생 중 미디어 시작에서 제거할 지속 시간을 밀리초 단위로 지정합니다. 읽기/쓰기 Single. |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | 플러그인이나 기타 코드에서 사용하도록 의도된 내부 프레젠테이션 범위 식별자를 반환합니다. 이 값은 사용자나 프로그램에 의해 재할당될 수 있으므로 지속적인 고유 키로 취급해서는 안 됩니다. 읽기 전용 UInt32. 또한 [`OfficeInteropShapeId`](../shape/officeinteropshapeid)를 참고하세요. |
| [Volume](../../aspose.slides/audioframe/volume) { get; set; } | 오디오 볼륨을 반환하거나 설정합니다. 읽기/쓰기 [`AudioVolumeMode`](../audiovolumemode). |
| [VolumeValue](../../aspose.slides/audioframe/volumevalue) { get; set; } | 오디오 볼륨을 퍼센트 단위로 반환하거나 설정합니다. 읽기/쓰기 Single. |
| [Width](../../aspose.slides/shape/width) { get; set; } | shape의 너비를 포인트 단위로 가져오거나 설정합니다. 읽기/쓰기 Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | shape의 왼쪽 위 모서리의 x좌표를 포인트 단위로 가져오거나 설정합니다. 읽기/쓰기 Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | shape의 왼쪽 위 모서리의 y좌표를 포인트 단위로 가져오거나 설정합니다. 읽기/쓰기 Single. |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | shape의 z-순서 위치를 반환합니다. Shapes[0]은 z-순서 뒤쪽에 있는 shape를 반환하고, Shapes[Shapes.Count - 1]은 앞쪽에 있는 shape를 반환합니다. 읽기 전용 Int32. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | 플레이스홀더가 없을 경우 새 플레이스홀더를 추가하고 지정된 플레이스홀더의 속성을 설정합니다. |
| [CreateShapeElements](../../aspose.slides/geometryshape/createshapeelements)() | shape 요소들의 배열을 생성하고 반환합니다. |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | 기본 플레이스홀더 shape를 반환합니다(현재 shape가 상속받은 레이아웃 또는 마스터 슬라이드의 shape). 현재 shape가 상속받지 않은 경우 null을 반환합니다. |
| [GetGeometryPaths](../../aspose.slides/geometryshape/getgeometrypaths)() | geometry shape의 경로 복사본을 반환합니다. 좌표는 shape의 왼쪽 위 모서리를 기준으로 합니다. |
| [GetImage](../../aspose.slides/shape/getimage)() | shape 썸네일을 반환합니다. 기본적으로 ShapeThumbnailBounds.Shape shape 썸네일 경계 유형이 사용됩니다. |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | shape 썸네일을 반환합니다. |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | 렌더링된 콘텐츠를 기준으로 계산된 shape의 시각적 경계를 가져옵니다. |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | 이 shape가 플레이스홀더가 아님을 정의합니다. |
| [SetGeometryPath](../../aspose.slides/geometryshape/setgeometrypath)(IGeometryPath) | [`IGeometryPath`](../igeometrypath) 객체에서 shape 기하학을 업데이트합니다. 좌표는 shape의 왼쪽 위 모서리를 기준으로 해야 합니다. shape 유형([`ShapeType`](../geometryshape/shapetype))을 Custom으로 변경합니다. |
| [SetGeometryPaths](../../aspose.slides/geometryshape/setgeometrypaths)(IGeometryPath[]) | [`IGeometryPath`](../igeometrypath) 배열에서 shape 기하학을 업데이트합니다. 좌표는 shape의 왼쪽 위 모서리를 기준으로 해야 합니다. shape 유형([`ShapeType`](../geometryshape/shapetype))을 Custom으로 변경합니다. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | Shape의 콘텐츠를 SVG 파일로 저장합니다. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | Shape의 콘텐츠를 SVG 파일로 저장합니다. |

### 예제

다음 예제는 Audio Play Options를 변경하는 방법을 보여줍니다.

```csharp
[C#]
using (Presentation pres = new Presentation("AudioFrameEmbed_out.pptx"))
{
    // AudioFrame shape를 가져옵니다
    AudioFrame audioFrame = (AudioFrame)pres.Slides[0].Shapes[0];
    // 재생 모드를 클릭 시 재생으로 설정합니다
    audioFrame.PlayMode = AudioPlayModePreset.OnClick;
    // 볼륨을 Low로 설정합니다
    audioFrame.Volume = AudioVolumeMode.Low;
    // 오디오를 슬라이드 전체에서 재생하도록 설정합니다
    audioFrame.PlayAcrossSlides = true;
    // 오디오 루프를 비활성화합니다
    audioFrame.PlayLoopMode = false;
    // 슬라이드 쇼 중 AudioFrame을 숨깁니다
    audioFrame.HideAtShowing = true;
    // 재생 후 오디오를 시작점으로 되감습니다
    audioFrame.RewindAudio = true;
    // PowerPoint 파일을 디스크에 저장합니다
    pres.Save("AudioFrameEmbed_changed.pptx", SaveFormat.Pptx);
}
```

### 참조

* 클래스 [PictureFrame](../pictureframe)
* 인터페이스 [IAudioFrame](../iaudioframe)
* 네임스페이스 [Aspose.Slides](../../aspose.slides)
* 어셈블리 [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->