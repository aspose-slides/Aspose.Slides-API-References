---
title: AudioFrame
second_title: Aspose.Slides for C++ API 레퍼런스
description: 슬라이드에 있는 오디오 클립을 나타냅니다.
type: docs
weight: 53
url: /ko/aspose.slides/audioframe/
---
## AudioFrame 클래스

슬라이드의 오디오 클립을 나타냅니다.

```cpp
class AudioFrame : public Aspose::Slides::PictureFrame,
                   public Aspose::Slides::IAudioFrame
```

## 메서드

| Method | Description |
| --- | --- |
| [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\> [AddPlaceholder](../shape/addplaceholder/)([System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\>) override | 새 자리표시자가 없으면 추가하고, 자리표시자 속성을 지정된 것으로 설정합니다. |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IShapeElement](../ishapeelement/)\>\> [CreateShapeElements](../geometryshape/createshapeelements/)() override | 모양의 요소 배열을 생성하고 반환합니다. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) 의미를 사용하여 객체를 비교합니다. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# 스타일로 참조형 객체를 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# 스타일로 값형 객체를 비교합니다. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | IEC 60559:1989에 따르면 NaN은 어떤 값과도(NaN 포함) 같지 않지만, C# 스타일 부동소수점 비교를 모방하여 두 NaN을 동일하게 간주합니다. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | IEC 60559:1989에 따르면 NaN은 어떤 값과도(NaN 포함) 같지 않지만, C# 스타일 부동소수점 비교를 모방하여 두 NaN을 동일하게 간주합니다. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 내부 용도 전용입니다. |
| [System::SharedPtr](../../system/sharedptr/)\<[IAdjustValue](../iadjustvalue/)\> [get_Adjustment](../geometryshape/get_adjustment/)(**int32_t**) override | 지정된 인덱스에서 모양의 조정값을 반환합니다. |
| [System::SharedPtr](../../system/sharedptr/)\<[IAdjustValueCollection](../iadjustvaluecollection/)\> [get_Adjustments](../geometryshape/get_adjustments/)() override | 모양의 조정값 컬렉션을 반환합니다. 읽기 전용 [IAdjustValueCollection](../iadjustvaluecollection/). |
| [System::String](../../system/string/) [get_AlternativeText](../shape/get_alternativetext/)() override | 모양에 연결된 대체 텍스트를 반환합니다. 읽기 [System::String](../../system/string/). |
| [System::String](../../system/string/) [get_AlternativeTextTitle](../shape/get_alternativetexttitle/)() override | 모양에 연결된 대체 텍스트의 제목을 반환합니다. 읽기 [System::String](../../system/string/). |
| **int32_t** [get_AudioCdEndTrack](./get_audiocdendtrack/)() override | 마지막 트랙 인덱스를 반환합니다. 읽기 **int32_t**. |
| **int32_t** [get_AudioCdEndTrackTime](./get_audiocdendtracktime/)() override | 마지막 트랙 시간을 반환합니다. 읽기 **int32_t**. |
| **int32_t** [get_AudioCdStartTrack](./get_audiocdstarttrack/)() override | 시작 트랙 인덱스를 반환합니다. 읽기 **int32_t**. |
| **int32_t** [get_AudioCdStartTrackTime](./get_audiocdstarttracktime/)() override | 시작 트랙 시간을 반환합니다. 읽기 **int32_t**. |
| [Aspose::Slides::BlackWhiteMode](../blackwhitemode/) [get_BlackWhiteMode](../shape/get_blackwhitemode/)() override | 모양이 흑백 표시 모드에서 어떻게 렌더링되는지 지정합니다. 읽기 [Slides::BlackWhiteMode](../blackwhitemode/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ICaptionsCollection](../icaptionscollection/)\> [get_CaptionTracks](./get_captiontracks/)() override | 오디오 프레임에 연결된 폐쇄 캡션 컬렉션을 가져옵니다. 이 속성은 읽기 전용이며 모든 캡션 트랙을 포함하는 [ICaptionsCollection](../icaptionscollection/)을 반환합니다. |
| **int32_t** [get_ConnectionSiteCount](../shape/get_connectionsitecount/)() override | 모양의 연결 지점 수를 반환합니다. 읽기 전용 **int32_t**. |
| [System::SharedPtr](../../system/sharedptr/)\<[ICustomData](../icustomdata/)\> [get_CustomData](../shape/get_customdata/)() override | 모양의 사용자 지정 데이터를 반환합니다. 읽기 전용 [ICustomData](../icustomdata/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IEffectFormat](../ieffectformat/)\> [get_EffectFormat](../shape/get_effectformat/)() override | 모양에 적용된 픽셀 효과를 포함하는 [EffectFormat](../effectformat/) 객체를 반환합니다. 효과 속성이 없는 일부 모양의 경우 null을 반환할 수 있습니다. 읽기 전용 [IEffectFormat](../ieffectformat/). |
| **bool** [get_Embedded](./get_embedded/)() override | 사운드가 프레젠테이션에 포함되어 있는지 결정합니다. 읽기 전용 **bool**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IAudio](../iaudio/)\> [get_EmbeddedAudio](./get_embeddedaudio/)() override | 포함된 오디오 객체를 반환합니다. 읽기 [IAudio](../iaudio/). |
| **float** [get_FadeInDuration](./get_fadeinduration/)() override | 미디어의 초기 페이드인 지속 시간을 밀리초 단위로 지정합니다. 읽기 **float**. |
| **float** [get_FadeOutDuration](./get_fadeoutduration/)() override | 미디어의 종료 페이드아웃 지속 시간을 밀리초 단위로 지정합니다. 읽기 **float**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../ifillformat/)\> [get_FillFormat](../shape/get_fillformat/)() override | 모양의 채우기 서식 속성을 포함하는 [FillFormat](../fillformat/) 객체를 반환합니다. 채우기 속성이 없는 일부 모양의 경우 null을 반환할 수 있습니다. 읽기 전용 [IFillFormat](../ifillformat/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\> [get_Frame](../shape/get_frame/)() override | 모양 프레임의 속성을 반환합니다. 읽기 [IShapeFrame](../ishapeframe/). |
| **float** [get_Height](../shape/get_height/)() override | 포인트 단위로 측정된 모양의 높이를 가져옵니다. 읽기 **float**. |
| **bool** [get_Hidden](../shape/get_hidden/)() override | 모양이 숨겨져 있는지 결정합니다. 읽기 **bool**. |
| **bool** [get_HideAtShowing](./get_hideatshowing/)() override | [AudioFrame](./)가 숨겨져 있는지 결정합니다. 읽기 **bool**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkClick](../shape/get_hyperlinkclick/)() override | 마우스 클릭에 정의된 하이퍼링크를 반환합니다. 읽기 [IHyperlink](../ihyperlink/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlinkManager](../ihyperlinkmanager/)\> [get_HyperlinkManager](../shape/get_hyperlinkmanager/)() override | 하이퍼링크 관리자를 반환합니다. 읽기 전용 [IHyperlinkManager](../ihyperlinkmanager/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkMouseOver](../shape/get_hyperlinkmouseover/)() override | 마우스 오버에 정의된 하이퍼링크를 반환합니다. 읽기 [IHyperlink](../ihyperlink/). |
| **bool** [get_IsCameo](../pictureframe/get_iscameo/)() | [PictureFrame](../pictureframe/)가 Cameo 객체인지 여부를 결정합니다. 읽기 전용 **bool**. |
| **bool** [get_IsDecorative](../shape/get_isdecorative/)() override | '장식용으로 표시' 옵션을 가져옵니다. 읽기/쓰기 **bool**. |
| **bool** [get_IsGrouped](../shape/get_isgrouped/)() override | 모양이 그룹화되어 있는지 결정합니다. 읽기 전용 **bool**. |
| **bool** [get_IsTextHolder](../shape/get_istextholder/)() override | 모양이 TextHolder_PPT인지 결정합니다. 읽기 전용 **bool**. |
| [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../ilineformat/)\> [get_LineFormat](../shape/get_lineformat/)() override | 모양의 선 서식 속성을 포함하는 [LineFormat](../lineformat/) 객체를 반환합니다. 선 속성이 없는 일부 모양의 경우 null을 반환할 수 있습니다. 읽기 전용 [ILineFormat](../ilineformat/). |
| [System::String](../../system/string/) [get_LinkPathLong](./get_linkpathlong/)() override | [AudioFrame](./)에 연결된 오디오 파일 이름을 반환합니다. 읽기 [System::String](../../system/string/). |
| [System::String](../../system/string/) [get_Name](../shape/get_name/)() override | 모양의 이름을 반환합니다. null이 될 수 없습니다. 필요하면 빈 문자열을 사용하십시오. 읽기 [System::String](../../system/string/). |
| **uint32_t** [get_OfficeInteropShapeId](../shape/get_officeinteropshapeid/)() override | 슬라이드 범위 내에서 모양의 수명 동안 일정하게 유지되는 고유 식별자를 반환합니다. 이 식별자를 사용하면 PowerPoint 또는 상호 운용 코드가 문서 어디에서든 모양을 안정적으로 참조할 수 있습니다. 읽기 전용 **uint32_t**. 또한 [Shape::get_UniqueId](../shape/get_uniqueid/)를 참조하십시오. |
| [System::SharedPtr](../../system/sharedptr/)\<[IGroupShape](../igroupshape/)\> [get_ParentGroup](../shape/get_parentgroup/)() override | 모양이 그룹화된 경우 상위 [GroupShape](../groupshape/) 객체를 반환합니다. 그렇지 않으면 null을 반환합니다. 읽기 전용 [IGroupShape](../igroupshape/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IPictureFillFormat](../ipicturefillformat/)\> [get_PictureFormat](../pictureframe/get_pictureformat/)() override | 그림 프레임에 대한 [PictureFillFormat](../picturefillformat/) 객체를 반환합니다. 읽기 전용 [IPictureFillFormat](../ipicturefillformat/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IPictureFrameLock](../ipictureframelock/)\> [get_PictureFrameLock](../pictureframe/get_pictureframelock/)() override | 모양의 잠금을 반환합니다. 읽기 전용 [IPictureFrameLock](../ipictureframelock/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\> [get_Placeholder](../shape/get_placeholder/)() override | 모양의 자리표시자를 반환합니다. 자리표시자가 없으면 null을 반환합니다. 읽기 전용 [IPlaceholder](../iplaceholder/). |
| **bool** [get_PlayAcrossSlides](./get_playacrossslides/)() override | 오디오가 슬라이드 전역에서 재생되는지 여부를 결정합니다. 읽기 **bool**. |
| **bool** [get_PlayLoopMode](./get_playloopmode/)() override | 오디오가 반복 재생되는지 여부를 결정합니다. 읽기 **bool**. |
| [AudioPlayModePreset](../audioplaymodepreset/) [get_PlayMode](./get_playmode/)() override | 오디오 재생 모드를 반환합니다. 읽기 [AudioPlayModePreset](../audioplaymodepreset/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../ipresentation/)\> [get_Presentation](../shape/get_presentation/)() override | 슬라이드의 상위 프레젠테이션을 반환합니다. 읽기 전용 [IPresentation](../ipresentation/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\> [get_RawFrame](../shape/get_rawframe/)() override | 원시 모양 프레임 속성을 반환합니다. 읽기 [IShapeFrame](../ishapeframe/). |
| **float** [get_RelativeScaleHeight](../pictureframe/get_relativescaleheight/)() override | 그림 프레임의 높이(원본 이미지 크기에 대한 비율) 스케일을 반환합니다. 값 1.0은 100%에 해당합니다. 읽기 **float**. |
| **float** [get_RelativeScaleWidth](../pictureframe/get_relativescalewidth/)() override | 그림 프레임의 너비(원본 이미지 크기에 대한 비율) 스케일을 반환합니다. 값 1.0은 100%에 해당합니다. 읽기 **float**. |
| **bool** [get_RewindAudio](./get_rewindaudio/)() override | 재생이 끝난 후 오디오가 자동으로 시작 위치로 되감겨지는지 여부를 결정합니다. 읽기 **bool**. |
| **float** [get_Rotation](../shape/get_rotation/)() override | 지정된 모양이 z축을 중심으로 회전된 각도를 반환합니다. 양수는 시계 방향, 음수는 반시계 방향을 나타냅니다. 읽기 **float**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IBaseShapeLock](../ibaseshapelock/)\> [get_ShapeLock](../shape/get_shapelock/)() override | 모양의 잠금을 반환합니다. 읽기 전용 [IBaseShapeLock](../ibaseshapelock/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IShapeStyle](../ishapestyle/)\> [get_ShapeStyle](../geometryshape/get_shapestyle/)() override | 모양의 스타일 객체를 반환합니다. 읽기 전용 [IShapeStyle](../ishapestyle/). |
| [Aspose::Slides::ShapeType](../shapetype/) [get_ShapeType](../pictureframe/get_shapetype/)() override |  |
| [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../ibaseslide/)\> [get_Slide](../shape/get_slide/)() override | 모양의 상위 슬라이드를 반환합니다. 읽기 전용 [IBaseSlide](../ibaseslide/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IThreeDFormat](../ithreedformat/)\> [get_ThreeDFormat](../shape/get_threedformat/)() override | 모양에 대한 3D 효과 속성을 포함하는 [ThreeDFormat](../threedformat/) 객체를 반환합니다. 3D 속성이 없는 일부 모양의 경우 null을 반환할 수 있습니다. 읽기 전용 [IThreeDFormat](../ithreedformat/). |
| **float** [get_TrimFromEnd](./get_trimfromend/)() override | 재생 중 미디어 끝부분에서 제거할 시간(밀리초)을 지정합니다. 읽기 **float**. |
| **float** [get_TrimFromStart](./get_trimfromstart/)() override | 재생 중 미디어 시작 부분에서 제거할 시간(밀리초)을 지정합니다. 읽기 **float**. |
| **uint32_t** [get_UniqueId](../shape/get_uniqueid/)() override | 애드인이나 기타 코드가 사용할 수 있도록 프레젠테이션 범위 내부 식별자를 반환합니다. 사용자가 또는 프로그램이 재할당할 수 있으므로 영구적인 고유 키로 간주해서는 안 됩니다. 읽기 전용 **uint32_t**. 또한 [Shape::get_OfficeInteropShapeId](../shape/get_officeinteropshapeid/)를 참조하십시오. |
| [AudioVolumeMode](../audiovolumemode/) [get_Volume](./get_volume/)() override | 오디오 볼륨을 반환합니다. 읽기 [AudioVolumeMode](../audiovolumemode/). |
| **float** [get_VolumeValue](./get_volumevalue/)() override | 오디오 볼륨을 퍼센트 단위로 반환합니다. 읽기 **float**. |
| **float** [get_Width](../shape/get_width/)() override | 포인트 단위로 측정된 모양의 너비를 가져옵니다. 읽기 **float**. |
| **float** [get_X](../shape/get_x/)() override | 포인트 단위로 측정된 모양 좌측 상단 모서리의 x 좌표를 가져옵니다. 읽기 **float**. |
| **float** [get_Y](../shape/get_y/)() override | 포인트 단위로 측정된 모양 좌측 상단 모서리의 y 좌표를 가져옵니다. 읽기 **float**. |
| **int32_t** [get_ZOrderPosition](../shape/get_zorderposition/)() override | Z-순서에서 모양의 위치를 반환합니다. Shapes[0]은 Z-순서 뒤쪽의 모양을, Shapes[Shapes.Count - 1]은 앞쪽의 모양을 반환합니다. 읽기 전용 **int32_t**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IShape](../ishape/)\> [GetBasePlaceholder](../shape/getbaseplaceholder/)() override | 현재 모양이 상속받은 레이아웃 및/또는 마스터 슬라이드의 기본 자리표시자 모양을 반환합니다. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 객체와 연결된 레퍼런스 카운터 데이터 구조를 가져옵니다. |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IGeometryPath](../igeometrypath/)\>\> [GetGeometryPaths](../geometryshape/getgeometrypaths/)() override | 기하학적 모양 경로 복사본을 반환합니다. 좌표는 모양의 좌측 상단 모서리를 기준으로 합니다. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) 메서드와 동일합니다. 사용자 정의 객체의 해싱을 가능하게 합니다. |
| [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](../shape/getimage/)() override | 모양 썸네일을 반환합니다. 기본적으로 [ShapeThumbnailBounds::Shape](../shapethumbnailbounds/) 모양 썸네일 경계 유형이 사용됩니다. |
| [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](../shape/getimage/)([ShapeThumbnailBounds](../shapethumbnailbounds/), **float**, **float**) override | 모양 썸네일을 반환합니다. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 객체의 실제 유형을 가져옵니다. C# [System.Object.GetType()](../../system/object/gettype/) 호출과 동일합니다. |
| [System::Drawing::RectangleF](../../system.drawing/rectanglef/) [GetVisualBounds](../shape/getvisualbounds/)() | 렌더링된 콘텐츠를 기반으로 계산된 모양의 시각적 경계를 가져옵니다. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 객체가 targetType이 설명하는 유형의 인스턴스인지 확인합니다. C# ‘is’ 연산자와 동일합니다. |
| void [Lock](../../system/object/lock/)() | C# lock() 구문의 잠금 구현을 제공합니다. 직접 호출하거나 [LockContext](../../system/lockcontext/) 감시 객체를 사용하십시오. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 메서드와 동일합니다. 사용자 정의 유형을 복제할 수 있게 합니다. |
|  [Object](../../system/object/object/)() | 객체를 생성합니다. 모든 내부 데이터 구조를 초기화합니다. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 복사 생성자. 실제로는 아무것도 복사하지 않으며, 새로운 객체를 초기화하고 하위 클래스의 복사 생성을 가능하게 합니다. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 할당 연산자. 실제로는 아무것도 복사하지 않으며, 새로운 객체를 초기화하고 하위 클래스의 복사 생성을 가능하게 합니다. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 레퍼런스로 객체를 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 레퍼런스로 객체를 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 값형 객체를 nullptr와 레퍼런스로 비교합니다. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | 문자열과 nullptr 경우에 대한 [Object::ReferenceEquals](../../system/object/referenceequals/) 특수화입니다. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | 문자열들의 경우에 대한 [Object::ReferenceEquals](../../system/object/referenceequals/) 특수화입니다. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 지정된 값만큼 공유 레퍼런스 카운트를 감소시킵니다. |
| void [RemovePlaceholder](../shape/removeplaceholder/)() override | 이 모양이 자리표시자가 아님을 정의합니다. |
| void [set_AlternativeText](../shape/set_alternativetext/)([System::String](../../system/string/)) override | 모양에 연결된 대체 텍스트를 설정합니다. 쓰기 [System::String](../../system/string/). |
| void [set_AlternativeTextTitle](../shape/set_alternativetexttitle/)([System::String](../../system/string/)) override | 모양에 연결된 대체 텍스트의 제목을 설정합니다. 쓰기 [System::String](../../system/string/). |
| void [set_AudioCdEndTrack](./set_audiocdendtrack/)(**int32_t**) override | 마지막 트랙 인덱스를 설정합니다. 쓰기 **int32_t**. |
| void [set_AudioCdEndTrackTime](./set_audiocdendtracktime/)(**int32_t**) override | 마지막 트랙 시간을 설정합니다. 쓰기 **int32_t**. |
| void [set_AudioCdStartTrack](./set_audiocdstarttrack/)(**int32_t**) override | 시작 트랙 인덱스를 설정합니다. 쓰기 **int32_t**. |
| void [set_AudioCdStartTrackTime](./set_audiocdstarttracktime/)(**int32_t**) override | 시작 트랙 시간을 설정합니다. 쓰기 **int32_t**. |
| void [set_BlackWhiteMode](../shape/set_blackwhitemode/)([Aspose::Slides::BlackWhiteMode](../blackwhitemode/)) override | 모양이 흑백 표시 모드에서 어떻게 렌더링되는지 지정합니다. 쓰기 [Slides::BlackWhiteMode](../blackwhitemode/). |
| void [set_EmbeddedAudio](./set_embeddedaudio/)([System::SharedPtr](../../system/sharedptr/)\<[IAudio](../iaudio/)\>) override | 포함된 오디오 객체를 설정합니다. 쓰기 [IAudio](../iaudio/). |
| void [set_FadeInDuration](./set_fadeinduration/)(**float**) override | 미디어의 초기 페이드인 지속 시간을 밀리초 단위로 지정합니다. 쓰기 **float**. |
| void [set_FadeOutDuration](./set_fadeoutduration/)(**float**) override | 미디어의 종료 페이드아웃 지속 시간을 밀리초 단위로 지정합니다. 쓰기 **float**. |
| void [set_Frame](../shape/set_frame/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\>) override | 모양 프레임 속성을 설정합니다. 쓰기 [IShapeFrame](../ishapeframe/). |
| void [set_Height](../shape/set_height/)(**float**) override | 포인트 단위로 모양의 높이를 설정합니다. 쓰기 **float**. |
| void [set_Hidden](../shape/set_hidden/)(**bool**) override | 모양이 숨겨져 있는지 여부를 설정합니다. 쓰기 **bool**. |
| void [set_HideAtShowing](./set_hideatshowing/)(**bool**) override | [AudioFrame](./)가 숨겨져 있는지 여부를 설정합니다. 쓰기 **bool**. |
| void [set_HyperlinkClick](../shape/set_hyperlinkclick/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) override | 마우스 클릭에 정의된 하이퍼링크를 설정합니다. 쓰기 [IHyperlink](../ihyperlink/). |
| void [set_HyperlinkMouseOver](../shape/set_hyperlinkmouseover/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) override | 마우스 오버에 정의된 하이퍼링크를 설정합니다. 쓰기 [IHyperlink](../ihyperlink/). |
| void [set_IsDecorative](../shape/set_isdecorative/)(**bool**) override | '장식용으로 표시' 옵션을 설정합니다. 읽기/쓰기 **bool**. |
| void [set_LinkPathLong](./set_linkpathlong/)([System::String](../../system/string/)) override | [AudioFrame](./)에 연결된 오디오 파일 이름을 설정합니다. 쓰기 [System::String](../../system/string/). |
| void [set_Name](../shape/set_name/)([System::String](../../system/string/)) override | 모양의 이름을 설정합니다. null이 될 수 없습니다. 필요하면 빈 문자열을 사용하십시오. 쓰기 [System::String](../../system/string/). |
| void [set_PlayAcrossSlides](./set_playacrossslides/)(**bool**) override | 오디오가 슬라이드 전역에서 재생되는지 여부를 설정합니다. 쓰기 **bool**. |
| void [set_PlayLoopMode](./set_playloopmode/)(**bool**) override | 오디오가 반복 재생되는지 여부를 설정합니다. 쓰기 **bool**. |
| void [set_PlayMode](./set_playmode/)([AudioPlayModePreset](../audioplaymodepreset/)) override | 오디오 재생 모드를 설정합니다. 쓰기 [AudioPlayModePreset](../audioplaymodepreset/). |
| void [set_RawFrame](../shape/set_rawframe/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\>) override | 원시 모양 프레임 속성을 설정합니다. 쓰기 [IShapeFrame](../ishapeframe/). |
| void [set_RelativeScaleHeight](../pictureframe/set_relativescaleheight/)(**float**) override | 그림 프레임의 높이(원본 이미지 크기에 대한 비율) 스케일을 설정합니다. 값 1.0은 100%에 해당합니다. 쓰기 **float**. |
| void [set_RelativeScaleWidth](../pictureframe/set_relativescalewidth/)(**float**) override | 그림 프레임의 너비(원본 이미지 크기에 대한 비율) 스케일을 설정합니다. 값 1.0은 100%에 해당합니다. 쓰기 **float**. |
| void [set_RewindAudio](./set_rewindaudio/)(**bool**) override | 재생이 끝난 후 오디오가 자동으로 시작 위치로 되감겨지는지 여부를 설정합니다. 쓰기 **bool**. |
| void [set_Rotation](../shape/set_rotation/)(**float**) override | 지정된 모양이 z축을 중심으로 회전된 각도를 설정합니다. 양수는 시계 방향, 음수는 반시계 방향을 나타냅니다. 쓰기 **float**. |
| void [set_ShapeType](../pictureframe/set_shapetype/)([Aspose::Slides::ShapeType](../shapetype/)) override |  |
| void [set_TrimFromEnd](./set_trimfromend/)(**float**) override | 재생 중 미디어 끝부분에서 제거할 시간을 밀리초 단위로 지정합니다. 쓰기 **float**. |
| void [set_TrimFromStart](./set_trimfromstart/)(**float**) override | 재생 중 미디어 시작 부분에서 제거할 시간을 밀리초 단위로 지정합니다. 쓰기 **float**. |
| void [set_Volume](./set_volume/)([AudioVolumeMode](../audiovolumemode/)) override | 오디오 볼륨을 설정합니다. 쓰기 [AudioVolumeMode](../audiovolumemode/). |
| void [set_VolumeValue](./set_volumevalue/)(**float**) override | 오디오 볼륨을 퍼센트 단위로 설정합니다. 쓰기 **float**. |
| void [set_Width](../shape/set_width/)(**float**) override | 모양의 너비를 포인트 단위로 설정합니다. 쓰기 **float**. |
| void [set_X](../shape/set_x/)(**float**) override | 모양 좌측 상단 모서리의 x 좌표를 포인트 단위로 설정합니다. 쓰기 **float**. |
| void [set_Y](../shape/set_y/)(**float**) override | 모양 좌측 상단 모서리의 y 좌표를 포인트 단위로 설정합니다. 쓰기 **float**. |
| void [SetGeometryPath](../geometryshape/setgeometrypath/)([System::SharedPtr](../../system/sharedptr/)\<[IGeometryPath](../igeometrypath/)\>) override | [IGeometryPath](../igeometrypath/) 객체에서 모양 기하학을 업데이트합니다. 좌표는 모양 좌측 상단 모서리를 기준으로 해야 합니다. 모양 유형([ShapeType](../shapetype/))을 [ShapeType::Custom](../shapetype/)로 변경합니다. |
| void [SetGeometryPaths](../geometryshape/setgeometrypaths/)([System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IGeometryPath](../igeometrypath/)\>\>) override | [IGeometryPath](../igeometrypath/) 배열에서 모양 기하학을 업데이트합니다. 좌표는 모양 좌측 상단 모서리를 기준으로 해야 합니다. 모양 유형([ShapeType](../shapetype/))을 [ShapeType::Custom](../shapetype/)로 변경합니다. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n번째 템플릿 인수를 약한 포인터(공유 포인터가 아닌)로 설정합니다. 컨테이너 내 포인터를 약한 모드로 전환할 수 있습니다. |
| int [SharedCount](../../system/object/sharedcount/)() const | 현재 공유 레퍼런스 카운터 값을 가져옵니다. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 공유 레퍼런스 카운트를 증가시킵니다. 직접 호출해서는 안 되며, 스마트 포인터 또는 ThisProtector를 사용하십시오. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 공유 레퍼런스 카운트를 감소시키고 반환합니다. 직접 호출해서는 안 되며, 스마트 포인터 또는 ThisProtector를 사용하십시오. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) 메서드와 동일합니다. 사용자 정의 객체를 문자열로 변환할 수 있게 합니다. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) 구문을 구현합니다. |
| void [Unlock](../../system/object/unlock/)() | C# lock() 구문의 잠금 해제를 구현합니다. 직접 호출하거나 [LockContext](../../system/lockcontext/) 감시 객체를 사용하십시오. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 약한 레퍼런스 카운트를 증가시킵니다. 직접 호출해서는 안 되며, 스마트 포인터 또는 ThisProtector를 사용하십시오. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 약한 레퍼런스 카운트를 감소시킵니다. 직접 호출해서는 안 되며, 스마트 포인터 또는 ThisProtector를 사용하십시오. |
| void [WriteAsSvg](../shape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>) override | [Shape](../shape/) 내용을 SVG 파일로 저장합니다. |
| void [WriteAsSvg](../shape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>, [System::SharedPtr](../../system/sharedptr/)\<[Export::ISVGOptions](../../aspose.slides.export/isvgoptions/)\>) override | [Shape](../shape/) 내용을 SVG 파일로 저장합니다. |
| virtual  [~Object](../../system/object/~object/)() | 객체를 파괴합니다. 모든 내부 데이터 구조를 해제합니다. |
## 비고

다음 예제는 [Audio](../audio/) 재생 옵션을 변경하는 방법을 보여줍니다. 
```cpp
auto pres = System::MakeObject<Presentation>(u"AudioFrameEmbed_out.pptx");

// Gets the AudioFrame shape
System::SharedPtr<AudioFrame> audioFrame = System::ExplicitCast<AudioFrame>(pres->get_Slides()->idx_get(0)->get_Shapes()->idx_get(0));
// Sets the Play mode to play on click
audioFrame->set_PlayMode(AudioPlayModePreset::OnClick);
// Sets the volume to Low
audioFrame->set_Volume(AudioVolumeMode::Low);
// Sets the audio to play across slides
audioFrame->set_PlayAcrossSlides(true);
// Disables loop for the audio
audioFrame->set_PlayLoopMode(false);
// Hides the AudioFrame during the slide show
audioFrame->set_HideAtShowing(true);
// Rewinds the audio to start after playing
audioFrame->set_RewindAudio(true);
// Saves the PowerPoint file to disk
pres->Save(u"AudioFrameEmbed_changed.pptx", SaveFormat::Pptx);
```

## 참고

* 클래스 [PictureFrame](../pictureframe/)
* 클래스 [IAudioFrame](../iaudioframe/)
* 네임스페이스 [Aspose::Slides](../)
* 라이브러리 [Aspose.Slides](../../)