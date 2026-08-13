---
title: ShapeCollection
second_title: Aspose.Slides for C++ API 레퍼런스
description: 도형 컬렉션을 나타냅니다.
type: docs
weight: 5110
url: /ko/aspose.slides/shapecollection/
---
## ShapeCollection 클래스

도형 컬렉션을 나타냅니다.

```cpp
class ShapeCollection : public Aspose::Slides::DomObject<System::SharedPtr<Aspose::Slides::GroupShape>>,
                        public Aspose::Slides::IShapeCollection
```

## 메서드

| 메서드 | 설명 |
| --- | --- |
| [System::SharedPtr](../../system/sharedptr/)\<[IAudioFrame](../iaudioframe/)\> [AddAudioFrameCD](./addaudioframecd/)(**float**, **float**, **float**, **float**) override | 새 오디오 프레임을 CD 트랙에 연결하고 도형 컬렉션의 끝에 추가합니다. |
| [System::SharedPtr](../../system/sharedptr/)\<[IAudioFrame](../iaudioframe/)\> [AddAudioFrameEmbedded](./addaudioframeembedded/)(**float**, **float**, **float**, **float**, [System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>) override | 새 오디오 프레임을 내장 WAV 파일과 함께 생성하고 도형 컬렉션의 끝에 추가합니다. 내장 오디오는 [Presentation::get_Audios](../presentation/get_audios/) 컬렉션에 추가됩니다. |
| [System::SharedPtr](../../system/sharedptr/)\<[IAudioFrame](../iaudioframe/)\> [AddAudioFrameEmbedded](./addaudioframeembedded/)(**float**, **float**, **float**, **float**, [System::SharedPtr](../../system/sharedptr/)\<[IAudio](../iaudio/)\>) override | 새 오디오 프레임을 생성하고 [Presentation::get_Audios](../presentation/get_audios/) 목록의 기존 오디오 객체를 사용하여 도형 컬렉션의 끝에 추가합니다. |
| [System::SharedPtr](../../system/sharedptr/)\<[IAudioFrame](../iaudioframe/)\> [AddAudioFrameLinked](./addaudioframelinked/)(**float**, **float**, **float**, **float**, [System::String](../../system/string/)) override | 새 오디오 프레임을 외부 오디오 파일에 연결하고 도형 컬렉션의 끝에 추가합니다. |
| [System::SharedPtr](../../system/sharedptr/)\<[IAutoShape](../iautoshape/)\> [AddAutoShape](./addautoshape/)([ShapeType](../shapetype/), **float**, **float**, **float**, **float**) override | 기본 서식이 적용된 새 자동 도형을 생성하고 도형 컬렉션의 끝에 추가합니다. |
| [System::SharedPtr](../../system/sharedptr/)\<[IAutoShape](../iautoshape/)\> [AddAutoShape](./addautoshape/)([ShapeType](../shapetype/), **float**, **float**, **float**, **float**, **bool**) override | 새 자동 도형을 생성하고 도형 컬렉션의 끝에 추가합니다. 필요에 따라 기본 템플릿 서식으로 초기화할 수 있습니다. |
| [System::SharedPtr](../../system/sharedptr/)\<[Charts::IChart](../../aspose.slides.charts/ichart/)\> [AddChart](./addchart/)([Charts::ChartType](../../aspose.slides.charts/charttype/), **float**, **float**, **float**, **float**) override | 새 차트를 생성하고 샘플 시리즈 데이터와 설정으로 초기화한 뒤 도형 컬렉션의 끝에 추가합니다. |
| [System::SharedPtr](../../system/sharedptr/)\<[Charts::IChart](../../aspose.slides.charts/ichart/)\> [AddChart](./addchart/)([Charts::ChartType](../../aspose.slides.charts/charttype/), **float**, **float**, **float**, **float**, **bool**) override | 새 차트를 생성하고 샘플 시리즈 데이터와 설정으로 초기화한 뒤 도형 컬렉션의 끝에 추가합니다. |
| [System::SharedPtr](../../system/sharedptr/)\<[IShape](../ishape/)\> [AddClone](./addclone/)([System::SharedPtr](../../system/sharedptr/)\<[IShape](../ishape/)\>, **float**, **float**, **float**, **float**) override | 지정된 도형의 복사본을 생성하고 도형 컬렉션의 끝에 추가합니다. |
| [System::SharedPtr](../../system/sharedptr/)\<[IShape](../ishape/)\> [AddClone](./addclone/)([System::SharedPtr](../../system/sharedptr/)\<[IShape](../ishape/)\>, **float**, **float**) override | 지정된 도형의 복사본을 생성하고 도형 컬렉션의 끝에 추가합니다. 새 도형은 *sourceShape* 의 너비와 높이를 유지합니다. |
| [System::SharedPtr](../../system/sharedptr/)\<[IShape](../ishape/)\> [AddClone](./addclone/)([System::SharedPtr](../../system/sharedptr/)\<[IShape](../ishape/)\>) override | 복제된 도형은 원본\\u2019s 위치와 크기를 유지합니다. |
| [System::SharedPtr](../../system/sharedptr/)\<[IConnector](../iconnector/)\> [AddConnector](./addconnector/)([ShapeType](../shapetype/), **float**, **float**, **float**, **float**) override | 기본 템플릿 스타일이 적용된 새 연결 도형을 생성하고 도형 컬렉션의 끝에 추가합니다. |
| [System::SharedPtr](../../system/sharedptr/)\<[IConnector](../iconnector/)\> [AddConnector](./addconnector/)([ShapeType](../shapetype/), **float**, **float**, **float**, **float**, **bool**) override | 새 연결 도형을 생성하고 도형 컬렉션의 끝에 추가합니다. 필요에 따라 기본 템플릿 스타일을 적용할 수 있습니다. |
| [System::SharedPtr](../../system/sharedptr/)\<[IGroupShape](../igroupshape/)\> [AddGroupShape](./addgroupshape/)() override | 새 빈 그룹 도형을 생성하고 도형 컬렉션의 끝에 추가합니다. 그룹\\u2019s 프레임은 추가된 모든 도형에 맞게 자동으로 조정됩니다. |
| [System::SharedPtr](../../system/sharedptr/)\<[IGroupShape](../igroupshape/)\> [AddGroupShape](./addgroupshape/)([System::SharedPtr](../../system/sharedptr/)\<[ISvgImage](../isvgimage/)\>, **float**, **float**, **float**, **float**) override | 새 그룹 도형을 생성하고 지정된 SVG 이미지를 개별 도형으로 변환한 뒤, 결과 그룹을 도형 컬렉션의 끝에 추가합니다. |
| [System::SharedPtr](../../system/sharedptr/)\<[IAutoShape](../iautoshape/)\> [AddMathShape](./addmathshape/)(**float**, **float**, **float**, **float**) override | 수학 콘텐츠를 담을 새 사각형 자동 도형을 생성하고 도형 컬렉션의 끝에 추가합니다. |
| [System::SharedPtr](../../system/sharedptr/)\<[IOleObjectFrame](../ioleobjectframe/)\> [AddOleObjectFrame](./addoleobjectframe/)(**float**, **float**, **float**, **float**, [System::SharedPtr](../../system/sharedptr/)\<[IOleEmbeddedDataInfo](../ioleembeddeddatainfo/)\>) override | 새 OLE 객체 프레임을 생성하고 도형 컬렉션의 끝에 추가합니다. |
| [System::SharedPtr](../../system/sharedptr/)\<[IOleObjectFrame](../ioleobjectframe/)\> [AddOleObjectFrame](./addoleobjectframe/)(**float**, **float**, **float**, **float**, [System::String](../../system/string/), [System::String](../../system/string/)) override | 새 OLE 객체 프레임을 생성하고 도형 컬렉션의 끝에 추가합니다. |
| [System::SharedPtr](../../system/sharedptr/)\<[IPictureFrame](../ipictureframe/)\> [AddPictureFrame](./addpictureframe/)([ShapeType](../shapetype/), **float**, **float**, **float**, **float**, [System::SharedPtr](../../system/sharedptr/)\<[IPPImage](../ippimage/)\>) override | 지정된 이미지를 포함하는 새 그림 프레임을 생성하고 도형 컬렉션의 끝에 추가합니다. |
| [System::SharedPtr](../../system/sharedptr/)\<[ISectionZoomFrame](../isectionzoomframe/)\> [AddSectionZoomFrame](./addsectionzoomframe/)(**float**, **float**, **float**, **float**, [System::SharedPtr](../../system/sharedptr/)\<[ISection](../isection/)\>) override | 새 [Section](../section/) Zoom 프레임을 생성하고 도형 컬렉션의 끝에 추가합니다. |
| [System::SharedPtr](../../system/sharedptr/)\<[ISectionZoomFrame](../isectionzoomframe/)\> [AddSectionZoomFrame](./addsectionzoomframe/)(**float**, **float**, **float**, **float**, [System::SharedPtr](../../system/sharedptr/)\<[ISection](../isection/)\>, [System::SharedPtr](../../system/sharedptr/)\<[IPPImage](../ippimage/)\>) override | 미리 정의된 이미지가 있는 새 [Section](../section/) Zoom 프레임을 생성하고 도형 컬렉션의 끝에 추가합니다. |
| [System::SharedPtr](../../system/sharedptr/)\<[SmartArt::ISmartArt](../../aspose.slides.smartart/ismartart/)\> [AddSmartArt](./addsmartart/)(**float**, **float**, **float**, **float**, [SmartArt::SmartArtLayoutType](../../aspose.slides.smartart/smartartlayouttype/)) override | [SmartArt](../../aspose.slides.smartart/) 다이어그램을 생성하고 도형 컬렉션의 끝에 추가합니다. |
| [System::SharedPtr](../../system/sharedptr/)\<[ISummaryZoomFrame](../isummaryzoomframe/)\> [AddSummaryZoomFrame](./addsummaryzoomframe/)(**float**, **float**, **float**, **float**) override | 새 Summary Zoom 프레임을 생성하고 도형 컬렉션의 끝에 추가합니다. |
| [System::SharedPtr](../../system/sharedptr/)\<[ITable](../itable/)\> [AddTable](./addtable/)(**float**, **float**, [System::ArrayPtr](../../system/arrayptr/)\<**double**\>, [System::ArrayPtr](../../system/arrayptr/)\<**double**\>) override | 새 테이블을 생성하고 도형 컬렉션의 끝에 추가합니다. |
| [System::SharedPtr](../../system/sharedptr/)\<[IVideoFrame](../ivideoframe/)\> [AddVideoFrame](./addvideoframe/)(**float**, **float**, **float**, **float**, [System::String](../../system/string/)) override | 새 비디오 프레임을 생성하고 도형 컬렉션의 끝에 추가합니다. |
| [System::SharedPtr](../../system/sharedptr/)\<[IVideoFrame](../ivideoframe/)\> [AddVideoFrame](./addvideoframe/)(**float**, **float**, **float**, **float**, [System::SharedPtr](../../system/sharedptr/)\<[IVideo](../ivideo/)\>) override | 새 비디오 프레임을 생성하고 도형 컬렉션의 끝에 추가합니다. |
| [System::SharedPtr](../../system/sharedptr/)\<[IZoomFrame](../izoomframe/)\> [AddZoomFrame](./addzoomframe/)(**float**, **float**, **float**, **float**, [System::SharedPtr](../../system/sharedptr/)\<[ISlide](../islide/)\>) override | 새 Zoom 프레임을 생성하고 도형 컬렉션의 끝에 추가합니다. |
| [System::SharedPtr](../../system/sharedptr/)\<[IZoomFrame](../izoomframe/)\> [AddZoomFrame](./addzoomframe/)(**float**, **float**, **float**, **float**, [System::SharedPtr](../../system/sharedptr/)\<[ISlide](../islide/)\>, [System::SharedPtr](../../system/sharedptr/)\<[IPPImage](../ippimage/)\>) override | 새 Zoom 프레임을 생성하고 도형 컬렉션의 끝에 추가합니다. |
| [iterator](./iterator/) [begin](./begin/)() | 컬렉션의 첫 번째 요소(있는 경우)를 가리키는 반복자를 가져옵니다. |
| [const_iterator](./const_iterator/) [begin](./begin/)() const | 컬렉션의 const 한정 인스턴스에서 첫 번째 요소(있는 경우)를 가리키는 반복자를 가져옵니다. |
| [const_iterator](./const_iterator/) [cbegin](./cbegin/)() const | 컬렉션에서 첫 번째 const 한정 요소(있는 경우)를 가리키는 반복자를 가져옵니다. |
| [const_iterator](./const_iterator/) [cend](./cend/)() const | 컬렉션에서 마지막 const 한정 요소(있는 경우) 바로 뒤를 가리키는 반복자를 가져옵니다. |
| void [Clear](./clear/)() override | 도형 컬렉션의 모든 도형을 제거합니다. |
| void [CopyTo](./copyto/)([System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IShape](../ishape/)\>\>, **int32_t**) override | 컬렉션의 모든 요소를 지정된 배열에 복사합니다. |
| virtual void [CopyTo](../igenericcollection/copyto/)([System::ArrayPtr](../../system/arrayptr/)\<T\>, **int32_t**) | 컬렉션의 모든 요소를 지정된 배열에 복사합니다. |
| [iterator](./iterator/) [end](./end/)() | 컬렉션에서 마지막 요소(있는 경우) 바로 뒤를 가리키는 반복자를 가져옵니다. |
| [const_iterator](./const_iterator/) [end](./end/)() const | 컬렉션의 const 한정 인스턴스에서 마지막 요소(있는 경우) 바로 뒤를 가리키는 반복자를 가져옵니다. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) 의미를 사용하여 객체를 비교합니다. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# 스타일로 참조 형식 객체를 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# 스타일로 값 형식 객체를 비교합니다. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | IEC 60559:1989에 따르면 NaN은 어떤 값과도 같지 않지만, 두 NaN을 동일하게 간주하는 C# 스타일 부동소수점 비교를 에뮬레이션합니다. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | IEC 60559:1989에 따르면 NaN은 어떤 값과도 같지 않지만, 두 NaN을 동일하게 간주하는 C# 스타일 부동소수점 비교를 에뮬레이션합니다. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 내부 용도 전용입니다. |
| **int32_t** [get_Count](./get_count/)() override | 컬렉션에 실제 포함된 요소 수를 가져옵니다. 읽기 전용 **int32_t**. |
| **bool** [get_IsSynchronized](./get_issynchronized/)() override | 컬렉션에 대한 접근이 동기화(스레드 안전)되는지 여부를 나타내는 값을 반환합니다. 읽기 전용 **bool**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IGroupShape](../igroupshape/)\> [get_ParentGroup](./get_parentgroup/)() override | 도형 컬렉션의 상위 그룹 도형 객체를 가져옵니다. 읽기 전용 [IGroupShape](../igroupshape/). |
| [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\> [get_SyncRoot](./get_syncroot/)() override | 동기화 루트를 반환합니다. 읽기 전용 [System::Object](../../system/object/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 객체와 연결된 참조 카운터 데이터 구조를 가져옵니다. |
| [System::SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::IEnumerator](../../system.collections.generic/ienumerator/)\<[System::SharedPtr](../../system/sharedptr/)\<[IShape](../ishape/)\>\>\> [GetEnumerator](./getenumerator/)() override | 컬렉션을 순회하는 열거자를 반환합니다. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) 메서드와 유사합니다. 사용자 정의 객체의 해싱을 가능하게 합니다. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 객체의 실제 유형을 가져옵니다. C# [System.Object.GetType()](../../system/object/gettype/) 호출과 유사합니다. |
| [System::SharedPtr](../../system/sharedptr/)\<[IShape](../ishape/)\> [idx_get](./idx_get/)(**int32_t**) override | 지정된 인덱스의 요소를 가져옵니다. 읽기 전용 [IShape](../ishape/). |
| **int32_t** [IndexOf](./indexof/)([System::SharedPtr](../../system/sharedptr/)\<[IShape](../ishape/)\>) override | 컬렉션에서 지정된 도형이 처음 나타나는 0부터 시작하는 인덱스를 반환합니다. |
| [System::SharedPtr](../../system/sharedptr/)\<[IAudioFrame](../iaudioframe/)\> [InsertAudioFrameCD](./insertaudioframecd/)(**int32_t**, **float**, **float**, **float**, **float**) override | 새 오디오 프레임을 CD 트랙에 연결하고 지정된 인덱스에 도형 컬렉션에 삽입합니다. |
| [System::SharedPtr](../../system/sharedptr/)\<[IAudioFrame](../iaudioframe/)\> [InsertAudioFrameEmbedded](./insertaudioframeembedded/)(**int32_t**, **float**, **float**, **float**, **float**, [System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>) override | 새 오디오 프레임을 내장 WAV 파일과 함께 생성하고 지정된 인덱스에 도형 컬렉션에 삽입합니다. 내장 오디오는 [Presentation::get_Audios](../presentation/get_audios/) 컬렉션에 추가됩니다. |
| [System::SharedPtr](../../system/sharedptr/)\<[IAudioFrame](../iaudioframe/)\> [InsertAudioFrameEmbedded](./insertaudioframeembedded/)(**int32_t**, **float**, **float**, **float**, **float**, [System::SharedPtr](../../system/sharedptr/)\<[IAudio](../iaudio/)\>) override | 새 오디오 프레임을 생성하고 [Presentation::get_Audios](../presentation/get_audios/) 목록의 기존 오디오 객체를 사용하여 지정된 인덱스에 도형 컬렉션에 삽입합니다. |
| [System::SharedPtr](../../system/sharedptr/)\<[IAudioFrame](../iaudioframe/)\> [InsertAudioFrameLinked](./insertaudioframelinked/)(**int32_t**, **float**, **float**, **float**, **float**, [System::String](../../system/string/)) override | 새 오디오 프레임을 외부 오디오 파일에 연결하고 지정된 인덱스에 도형 컬렉션에 삽입합니다. |
| [System::SharedPtr](../../system/sharedptr/)\<[IAutoShape](../iautoshape/)\> [InsertAutoShape](./insertautoshape/)(**int32_t**, [ShapeType](../shapetype/), **float**, **float**, **float**, **float**) override | 새 자동 도형을 생성하고 기본 템플릿 서식을 적용하여 지정된 인덱스에 도형 컬렉션에 삽입합니다. |
| [System::SharedPtr](../../system/sharedptr/)\<[IAutoShape](../iautoshape/)\> [InsertAutoShape](./insertautoshape/)(**int32_t**, [ShapeType](../shapetype/), **float**, **float**, **float**, **float**, **bool**) override | 새 자동 도형을 생성하고 필요에 따라 기본 템플릿 스타일로 초기화하여 지정된 인덱스에 도형 컬렉션에 삽입합니다. |
| [System::SharedPtr](../../system/sharedptr/)\<[Charts::IChart](../../aspose.slides.charts/ichart/)\> [InsertChart](./insertchart/)([Charts::ChartType](../../aspose.slides.charts/charttype/), **float**, **float**, **float**, **float**, **int32_t**) override | 새 차트를 생성하고 샘플 시리즈 데이터와 설정으로 초기화한 뒤 지정된 인덱스에 도형 컬렉션에 삽입합니다. |
| [System::SharedPtr](../../system/sharedptr/)\<[Charts::IChart](../../aspose.slides.charts/ichart/)\> [InsertChart](./insertchart/)([Charts::ChartType](../../aspose.slides.charts/charttype/), **float**, **float**, **float**, **float**, **int32_t**, **bool**) override | 새 차트를 생성하고 샘플 시리즈 데이터와 설정으로 초기화한 뒤 지정된 인덱스에 도형 컬렉션에 삽입합니다. |
| [System::SharedPtr](../../system/sharedptr/)\<[IShape](../ishape/)\> [InsertClone](./insertclone/)(**int32_t**, [System::SharedPtr](../../system/sharedptr/)\<[IShape](../ishape/)\>, **float**, **float**, **float**, **float**) override | 지정된 도형의 복사본을 생성하고 지정된 인덱스에 도형 컬렉션에 삽입합니다. |
| [System::SharedPtr](../../system/sharedptr/)\<[IShape](../ishape/)\> [InsertClone](./insertclone/)(**int32_t**, [System::SharedPtr](../../system/sharedptr/)\<[IShape](../ishape/)\>, **float**, **float**) override | 지정된 모양의 복사본을 만들고 지정된 인덱스에 모양 컬렉션에 삽입합니다. 새 모양은 *sourceShape* 의 너비와 높이를 유지합니다. |
| [System::SharedPtr](../../system/sharedptr/)\<[IShape](../ishape/)\> [InsertClone](./insertclone/)(**int32_t**, [System::SharedPtr](../../system/sharedptr/)\<[IShape](../ishape/)\>) override | 지정된 모양의 복사본을 만들고 지정된 인덱스에 모양 컬렉션에 삽입합니다. 복제된 모양은 original\\u2019s 위치와 크기를 유지합니다. |
| [System::SharedPtr](../../system/sharedptr/)\<[IConnector](../iconnector/)\> [InsertConnector](./insertconnector/)(**int32_t**, [ShapeType](../shapetype/), **float**, **float**, **float**, **float**) override | 새 연결자 모양을 만들고 지정된 인덱스에 모양 컬렉션에 삽입하며 기본 템플릿 스타일을 적용합니다. |
| [System::SharedPtr](../../system/sharedptr/)\<[IConnector](../iconnector/)\> [InsertConnector](./insertconnector/)(**int32_t**, [ShapeType](../shapetype/), **float**, **float**, **float**, **float**, **bool**) override | 새 연결자 모양을 만들고 지정된 인덱스에 모양 컬렉션에 삽입하며, 선택적으로 기본 템플릿 스타일을 적용합니다. |
| [System::SharedPtr](../../system/sharedptr/)\<[IGroupShape](../igroupshape/)\> [InsertGroupShape](./insertgroupshape/)(**int32_t**) override | 새 빈 그룹 모양을 만들고 지정된 인덱스에 모양 컬렉션에 삽입합니다. 그룹\\u2019s 프레임은 추가된 모든 모양에 맞게 자동으로 조정됩니다. |
| [System::SharedPtr](../../system/sharedptr/)\<[IOleObjectFrame](../ioleobjectframe/)\> [InsertOleObjectFrame](./insertoleobjectframe/)(**int32_t**, **float**, **float**, **float**, **float**, [System::SharedPtr](../../system/sharedptr/)\<[IOleEmbeddedDataInfo](../ioleembeddeddatainfo/)\>) override | 새 OLE 객체 프레임을 만들고 지정된 인덱스에 모양 컬렉션에 삽입합니다. |
| [System::SharedPtr](../../system/sharedptr/)\<[IOleObjectFrame](../ioleobjectframe/)\> [InsertOleObjectFrame](./insertoleobjectframe/)(**int32_t**, **float**, **float**, **float**, **float**, [System::String](../../system/string/), [System::String](../../system/string/)) override | 새 OLE 객체 프레임을 만들고 지정된 인덱스에 모양 컬렉션에 삽입합니다. |
| [System::SharedPtr](../../system/sharedptr/)\<[IPictureFrame](../ipictureframe/)\> [InsertPictureFrame](./insertpictureframe/)(**int32_t**, [ShapeType](../shapetype/), **float**, **float**, **float**, **float**, [System::SharedPtr](../../system/sharedptr/)\<[IPPImage](../ippimage/)\>) override | 지정된 이미지를 포함하는 새 사진 프레임을 만들고 지정된 인덱스에 모양 컬렉션에 삽입합니다. |
| [System::SharedPtr](../../system/sharedptr/)\<[ISectionZoomFrame](../isectionzoomframe/)\> [InsertSectionZoomFrame](./insertsectionzoomframe/)(**int32_t**, **float**, **float**, **float**, **float**, [System::SharedPtr](../../system/sharedptr/)\<[ISection](../isection/)\>) override | 새 [Section](../section/) Zoom 프레임을 만들고 지정된 인덱스에 모양 컬렉션에 삽입합니다. |
| [System::SharedPtr](../../system/sharedptr/)\<[ISectionZoomFrame](../isectionzoomframe/)\> [InsertSectionZoomFrame](./insertsectionzoomframe/)(**int32_t**, **float**, **float**, **float**, **float**, [System::SharedPtr](../../system/sharedptr/)\<[ISection](../isection/)\>, [System::SharedPtr](../../system/sharedptr/)\<[IPPImage](../ippimage/)\>) override | 미리 정의된 이미지가 있는 새 [Section](../section/) Zoom 프레임을 만들고 지정된 인덱스에 모양 컬렉션에 삽입합니다. |
| [System::SharedPtr](../../system/sharedptr/)\<[ISummaryZoomFrame](../isummaryzoomframe/)\> [InsertSummaryZoomFrame](./insertsummaryzoomframe/)(**int32_t**, **float**, **float**, **float**, **float**) override | 새 Summary Zoom 프레임을 만들고 지정된 인덱스에 모양 컬렉션에 삽입합니다. |
| [System::SharedPtr](../../system/sharedptr/)\<[ITable](../itable/)\> [InsertTable](./inserttable/)(**int32_t**, **float**, **float**, [System::ArrayPtr](../../system/arrayptr/)\<**double**\>, [System::ArrayPtr](../../system/arrayptr/)\<**double**\>) override | 새 테이블을 만들고 지정된 인덱스에 모양 컬렉션에 삽입합니다. |
| [System::SharedPtr](../../system/sharedptr/)\<[IVideoFrame](../ivideoframe/)\> [InsertVideoFrame](./insertvideoframe/)(**int32_t**, **float**, **float**, **float**, **float**, [System::String](../../system/string/)) override | 새 비디오 프레임을 만들고 지정된 인덱스에 모양 컬렉션에 삽입합니다. |
| [System::SharedPtr](../../system/sharedptr/)\<[IZoomFrame](../izoomframe/)\> [InsertZoomFrame](./insertzoomframe/)(**int32_t**, **float**, **float**, **float**, **float**, [System::SharedPtr](../../system/sharedptr/)\<[ISlide](../islide/)\>) override | 새 Zoom 프레임을 만들고 지정된 인덱스에 모양 컬렉션에 삽입합니다. |
| [System::SharedPtr](../../system/sharedptr/)\<[IZoomFrame](../izoomframe/)\> [InsertZoomFrame](./insertzoomframe/)(**int32_t**, **float**, **float**, **float**, **float**, [System::SharedPtr](../../system/sharedptr/)\<[ISlide](../islide/)\>, [System::SharedPtr](../../system/sharedptr/)\<[IPPImage](../ippimage/)\>) override | 미리 정의된 이미지가 있는 새 Zoom 프레임을 만들고 지정된 인덱스에 모양 컬렉션에 삽입합니다. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 객체가 targetType에 의해 설명된 유형의 인스턴스를 나타내는지 확인합니다. C# 'is' 연산자와 유사합니다. |
| T [LINQ_Aggregate](../../system.collections.generic/ienumerable/linq_aggregate/)(const [Func](../../system/func/)\<T, T, T\>\&) | 시퀀스에 누산기 함수를 적용합니다. |
| **bool** [LINQ_All](../../system.collections.generic/ienumerable/linq_all/)(std::function\<**bool**(T)>) | 시퀀스의 모든 요소가 조건을 만족하는지 여부를 판단합니다. |
| **bool** [LINQ_Any](../../system.collections.generic/ienumerable/linq_any/)() | 시퀀스에 요소가 하나라도 있는지 여부를 판단합니다. |
| **bool** [LINQ_Any](../../system.collections.generic/ienumerable/linq_any/)(std::function\<**bool**(T)>) | 시퀀스에 요소가 존재하거나 조건을 만족하는지 여부를 판단합니다. |
| T [LINQ_Average](../../system.collections.generic/ienumerable/linq_average/)() | 수치 값 시퀀스의 평균을 계산합니다. |
| ResultType [LINQ_Average](../../system.collections.generic/ienumerable/linq_average/)(const [Func](../../system/func/)\<T, ResultType\>\&) | 입력 시퀀스의 각 요소에 변환 함수를 호출하여 얻은 값들의 시퀀스 평균을 계산합니다. |
| ResultType [LINQ_Average](../../system.collections.generic/ienumerable/linq_average/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_Cast](../../system.collections.generic/ienumerable/linq_cast/)() | 요소들을 지정된 타입으로 변환합니다. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_Cast](../../system.collections.generic/ienumerable/linq_cast/)() |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Concat](../../system.collections.generic/ienumerable/linq_concat/)([SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\>) | 두 시퀀스를 연결합니다. |
| **bool** [LINQ_Contains](../../system.collections.generic/ienumerable/linq_contains/)(T) | 시퀀스에 지정된 값이 포함되는지 여부를 판단합니다. |
| int [LINQ_Count](../../system.collections.generic/ienumerable/linq_count/)() | 시퀀스의 요소 개수를 반환합니다(직접 계산). |
| int [LINQ_Count](../../system.collections.generic/ienumerable/linq_count/)(const [Func](../../system/func/)\<T, **bool**\>\&) | 지정된 조건을 만족하는 시퀀스 요소의 개수를 반환합니다. |
| T [LINQ_ElementAt](../../system.collections.generic/ienumerable/linq_elementat/)(int) | 시퀀스에서 지정된 인덱스에 있는 요소를 반환합니다. |
| T [LINQ_ElementAtOrDefault](../../system.collections.generic/ienumerable/linq_elementatordefault/)(int) | 시퀀스에서 지정된 인덱스에 있는 요소를 반환합니다. |
| T [LINQ_First](../../system.collections.generic/ienumerable/linq_first/)() | 시퀀스의 첫 번째 요소를 반환합니다. |
| T [LINQ_First](../../system.collections.generic/ienumerable/linq_first/)(const [Func](../../system/func/)\<T, **bool**\>\&) | 지정된 조건을 만족하는 시퀀스의 첫 번째 요소를 반환합니다. |
| T [LINQ_FirstOrDefault](../../system.collections.generic/ienumerable/linq_firstordefault/)() | 시퀀스의 첫 번째 요소를 반환하거나, 시퀀스가 비어있을 경우 기본값을 반환합니다. |
| T [LINQ_FirstOrDefault](../../system.collections.generic/ienumerable/linq_firstordefault/)(std::function\<**bool**(T)>) | 조건을 만족하는 시퀀스의 첫 번째 요소를 반환하며, 요소가 없을 경우 기본값을 반환합니다. |
| [System::SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[System::SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, T\>\>\>\>\> [LINQ_GroupBy](../../system.collections.generic/ienumerable/linq_groupby/)([System::Func](../../system/func/)\<T, Key\>) | 시퀀스의 요소들을 그룹화합니다. |
| [System::SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[System::SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Element\>\>\>\>\> [LINQ_GroupBy](../../system.collections.generic/ienumerable/linq_groupby/)([System::Func](../../system/func/)\<T, Key\>, [System::Func](../../system/func/)\<T, Element\>) | 시퀀스의 요소들을 그룹화합니다. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Source\>\>\>\> [LINQ_GroupBy](../../system.collections.generic/ienumerable/linq_groupby/)([System::Func](../../system/func/)\<Source, Key\>) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Element\>\>\>\> [LINQ_GroupBy](../../system.collections.generic/ienumerable/linq_groupby/)([System::Func](../../system/func/)\<Source, Key\>, [System::Func](../../system/func/)\<Source, Element\>) |  |
| T [LINQ_Last](../../system.collections.generic/ienumerable/linq_last/)() | 시퀀스의 마지막 요소를 반환합니다. |
| T [LINQ_LastOrDefault](../../system.collections.generic/ienumerable/linq_lastordefault/)() | 시퀀스의 마지막 요소를 반환하거나, 시퀀스가 비어있을 경우 기본값을 반환합니다. |
| ResultType [LINQ_Max](../../system.collections.generic/ienumerable/linq_max/)(const [Func](../../system/func/)\<T, ResultType\>\&) | 일반 시퀀스의 각 요소에 변환 함수를 호출하고, 최대 결과값을 반환합니다. |
| ResultType [LINQ_Max](../../system.collections.generic/ienumerable/linq_max/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| ResultType [LINQ_Min](../../system.collections.generic/ienumerable/linq_min/)(const [Func](../../system/func/)\<T, ResultType\>\&) | 일반 시퀀스의 각 요소에 변환 함수를 호출하고, 최소 결과값을 반환합니다. |
| ResultType [LINQ_Min](../../system.collections.generic/ienumerable/linq_min/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_OfType](../../system.collections.generic/ienumerable/linq_oftype/)() | 지정된 타입에 따라 시퀀스의 요소들을 필터링합니다. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_OfType](../../system.collections.generic/ienumerable/linq_oftype/)() |  |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<T\>\> [LINQ_OrderBy](../../system.collections.generic/ienumerable/linq_orderby/)(const [Func](../../system/func/)\<T, Key\>\&) | keySelector가 선택한 키 값에 따라 시퀀스의 요소들을 오름차순으로 정렬합니다. |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<Source\>\> [LINQ_OrderBy](../../system.collections.generic/ienumerable/linq_orderby/)(const [Func](../../system/func/)\<Source, Key\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<T\>\> [LINQ_OrderByDescending](../../system.collections.generic/ienumerable/linq_orderbydescending/)(const [Func](../../system/func/)\<T, Key\>\&) | keySelector가 선택한 키 값에 따라 시퀀스의 요소들을 내림차순으로 정렬합니다. |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<Source\>\> [LINQ_OrderByDescending](../../system.collections.generic/ienumerable/linq_orderbydescending/)(const [Func](../../system/func/)\<Source, Key\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Reverse](../../system.collections.generic/ienumerable/linq_reverse/)() | 시퀀스의 요소 순서를 반전시킵니다. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../../system/func/)\<T, ResultType\>\&) | 시퀀스의 요소들을 변환합니다. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../../system/func/)\<T, **int32_t**, ResultType\>\&) | 요소의 인덱스를 포함하여 시퀀스의 각 요소를 새로운 형태로 변환합니다. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../../system/func/)\<Source, Result\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../../system/func/)\<Source, **int32_t**, Result\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_SelectMany](../../system.collections.generic/ienumerable/linq_selectmany/)(const [Func](../../system/func/)\<T, [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\>\>\&) | 시퀀스의 각 요소를 투영하고, 결과 시퀀스를 하나의 시퀀스로 결합합니다. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_SelectMany](../../system.collections.generic/ienumerable/linq_selectmany/)(const [Func](../../system/func/)\<Source, [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\>\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Skip](../../system.collections.generic/ienumerable/linq_skip/)(**int32_t**) | 시퀀스 시작부터 지정된 개수만큼 연속된 요소를 건너뛰고 나머지를 반환합니다. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Take](../../system.collections.generic/ienumerable/linq_take/)(**int32_t**) | 시퀀스 시작부터 지정된 개수만큼 연속된 요소들을 반환합니다. |
| [System::ArrayPtr](../../system/arrayptr/)\<T\> [LINQ_ToArray](../../system.collections.generic/ienumerable/linq_toarray/)() | 시퀀스로부터 배열을 생성합니다. |
| [SharedPtr](../../system/sharedptr/)\<[List](../../system.collections.generic/list/)\<T\>\> [LINQ_ToList](../../system.collections.generic/ienumerable/linq_tolist/)() | 시퀀스로부터 List<T>를 생성합니다. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Where](../../system.collections.generic/ienumerable/linq_where/)(std::function\<**bool**(T)>) | 지정된 프레디케이트에 따라 시퀀스를 필터링합니다. |
| void [Lock](../../system/object/lock/)() | C# lock() 문을 구현합니다. 직접 호출하거나 [LockContext](../../system/lockcontext/) 감시 객체를 사용하십시오. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 메서드와 유사합니다. 사용자 정의 타입 복제를 가능하게 합니다. |
|  [Object](../../system/object/object/)() | 객체를 생성합니다. 모든 내부 데이터 구조를 초기화합니다. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 복사 생성자. 실제로 아무 것도 복사하지 않고, 새 객체를 초기화하며 하위 클래스의 복사 생성을 가능하게 합니다. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 대입 연산자. 실제로 아무 것도 복사하지 않고, 새 객체를 초기화하며 하위 클래스의 복사 생성을 가능하게 합니다. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 참조에 따라 객체를 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 참조에 따라 객체를 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 값 타입 객체와 nullptr를 참조 비교합니다. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/)의 문자열과 nullptr 경우에 대한 특수화입니다. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/)의 문자열 경우에 대한 특수화입니다. |
| void [Remove](./remove/)([System::SharedPtr](../../system/sharedptr/)\<[IShape](../ishape/)\>) override | 지정된 모양의 첫 번째 발생을 모양 컬렉션에서 제거합니다. |
| void [RemoveAt](./removeat/)(**int32_t**) override | 지정된 인덱스에 있는 모양을 모양 컬렉션에서 제거합니다. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 공유 참조 카운트를 지정된 값만큼 감소시킵니다. |
| void [Reorder](./reorder/)(**int32_t**, [System::SharedPtr](../../system/sharedptr/)\<[IShape](../ishape/)\>) override | 지정된 모양을 모양 컬렉션 내의 새로운 위치로 이동합니다. |
| void [Reorder](./reorder/)(**int32_t**, const [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IShape](../ishape/)\>\>\&) override | 지정된 모양들을 모양 컬렉션 내에서 이동시키며, 주어진 인덱스부터 배치합니다. |
| void [SetTemplateWeakPtr](./settemplateweakptr/)(**uint32_t**) override | n번째 템플릿 인수를 공유 대신 약한 포인터로 설정합니다. 컨테이너의 포인터를 약한 모드로 전환할 수 있습니다. |
| int [SharedCount](../../system/object/sharedcount/)() const | 공유 참조 카운터의 현재 값을 가져옵니다. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 공유 참조 카운트를 증가시킵니다. 직접 호출하지 말고 스마트 포인터나 ThisProtector를 사용하십시오. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 공유 참조 카운트를 감소시키고 반환합니다. 직접 호출하지 말고 스마트 포인터나 ThisProtector를 사용하십시오. |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IShape](../ishape/)\>\> [ToArray](./toarray/)() override | 모든 모양을 포함하는 배열을 생성하고 반환합니다. |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IShape](../ishape/)\>\> [ToArray](./toarray/)(**int32_t**, **int32_t**) override | 지정된 범위의 모든 모양을 포함하는 배열을 생성하고 반환합니다. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) 메서드와 유사합니다. 사용자 정의 객체를 문자열로 변환할 수 있게 합니다. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) 구문을 구현합니다. |
| void [Unlock](../../system/object/unlock/)() | C# lock() 문을 잠금 해제하도록 구현합니다. 직접 호출하거나 [LockContext](../../system/lockcontext/) 감시자 객체를 사용하세요. |
| [virtualized_iterator](./virtualized_iterator/) * [virtualizeBeginConstIterator](./virtualizebeginconstiterator/)() const override | 컬렉션의 const 한정 인스턴스에서 첫 번째 요소를 가리키는 반복자를 가져옵니다(있는 경우). |
| [virtualized_iterator](./virtualized_iterator/) * [virtualizeBeginIterator](./virtualizebeginiterator/)() override | 컬렉션에서 첫 번째 요소를 가리키는 반복자를 가져옵니다(있는 경우). |
| [virtualized_iterator](./virtualized_iterator/) * [virtualizeEndConstIterator](./virtualizeendconstiterator/)() const override | 컬렉션의 const 한정 인스턴스에서 마지막 요소 바로 다음을 가리키는 반복자를 가져옵니다(있는 경우). |
| [virtualized_iterator](./virtualized_iterator/) * [virtualizeEndIterator](./virtualizeenditerator/)() override | 컬렉션에서 마지막 요소 바로 다음을 가리키는 반복자를 가져옵니다(있는 경우). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 약한 참조 카운트를 증가시킵니다. 직접 호출하면 안 되며, 대신 스마트 포인터나 ThisProtector를 사용하세요. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 약한 참조 카운트를 감소시킵니다. 직접 호출하면 안 되며, 대신 스마트 포인터나 ThisProtector를 사용하세요. |
| virtual  [~Object](../../system/object/~object/)() | 객체를 파괴합니다. 모든 내부 데이터 구조를 해제합니다. |
## 타입 정의

| 타입 정의 | 설명 |
| --- | --- |
| [iterator_holder_type](./iterator_holder_type/) | 현재 컬렉션에서 반복자 유형으로 사용되는 컬렉션 타입입니다. |
| [iterator](./iterator/) | 반복자 타입. |
| [const_iterator](./const_iterator/) | 상수 반복자 타입. |
| [virtualized_iterator_element](./virtualized_iterator_element/) | 가상화된 요소 타입. |
| [virtualized_iterator](./virtualized_iterator/) | 가상화된 타입. |
## 참고

* 클래스 [DomObject](../domobject/)
* 클래스 [IShapeCollection](../ishapecollection/)
* 네임스페이스 [Aspose::Slides](../)
* 라이브러리 [Aspose.Slides](../../)