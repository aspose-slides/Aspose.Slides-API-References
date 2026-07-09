---
title: ShapeCollection
second_title: Aspose.Sildes for .NET API 레퍼런스
description: 쉐이프 컬렉션을 나타냅니다.
type: docs
weight: 9860
url: /ko/aspose.slides/shapecollection/
---
## ShapeCollection 클래스

쉐이프 컬렉션을 나타냅니다.

```csharp
public sealed class ShapeCollection : DomObject<GroupShape>, IShapeCollection
```

## 속성

| 이름 | 설명 |
| --- | --- |
| [Count](../../aspose.slides/shapecollection/count) { get; } | 컬렉션에 실제로 포함된 요소 수를 가져옵니다. 읽기 전용 Int32. |
| [IsSynchronized](../../aspose.slides/shapecollection/issynchronized) { get; } | 컬렉션에 대한 접근이 동기화(스레드 안전)되는지 여부를 나타내는 값을 반환합니다. 읽기 전용 Boolean. |
| [Item](../../aspose.slides/shapecollection/item) { get; } | 지정된 인덱스의 요소를 가져옵니다. 읽기 전용 [`IShape`](../ishape). |
| [ParentGroup](../../aspose.slides/shapecollection/parentgroup) { get; } | 쉐이프 컬렉션의 상위 그룹 쉐이프 객체를 가져옵니다. 읽기 전용 [`IGroupShape`](../igroupshape). |
| [SyncRoot](../../aspose.slides/shapecollection/syncroot) { get; } | 동기화 루트를 반환합니다. 읽기 전용 Object. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| [AddAudioFrameCD](../../aspose.slides/shapecollection/addaudioframecd)(float, float, float, float) | 새 오디오 프레임을 CD 트랙에 연결하여 생성하고 쉐이프 컬렉션 끝에 추가합니다. |
| [AddAudioFrameEmbedded](../../aspose.slides/shapecollection/addaudioframeembedded#addaudioframeembedded)(float, float, float, float, IAudio) | 기존 Presentation.Audios 목록에 있는 오디오 객체를 사용하여 새 오디오 프레임을 생성하고 쉐이프 컬렉션 끝에 추가합니다. |
| [AddAudioFrameEmbedded](../../aspose.slides/shapecollection/addaudioframeembedded#addaudioframeembedded_1)(float, float, float, float, Stream) | 임베드된 WAV 파일을 포함하는 새 오디오 프레임을 생성하고 쉐이프 컬렉션 끝에 추가합니다. 임베드된 오디오가 Presentation.Audios 컬렉션에 추가됩니다. |
| [AddAudioFrameLinked](../../aspose.slides/shapecollection/addaudioframelinked)(float, float, float, float, string) | 외부 오디오 파일에 연결된 새 오디오 프레임을 생성하고 쉐이프 컬렉션 끝에 추가합니다. |
| [AddAutoShape](../../aspose.slides/shapecollection/addautoshape#addautoshape)(ShapeType, float, float, float, float) | 기본 서식이 적용된 새 자동 쉐이프를 생성하고 쉐이프 컬렉션 끝에 추가합니다. |
| [AddAutoShape](../../aspose.slides/shapecollection/addautoshape#addautoshape_1)(ShapeType, float, float, float, float, bool) | 새 자동 쉐이프를 생성하고 쉐이프 컬렉션 끝에 추가하며, 선택적으로 기본 템플릿 서식으로 초기화합니다. |
| [AddChart](../../aspose.slides/shapecollection/addchart#addchart)(ChartType, float, float, float, float) | 새 차트를 생성하고 샘플 시리즈 데이터와 설정으로 초기화한 뒤 쉐이프 컬렉션 끝에 추가합니다. |
| [AddChart](../../aspose.slides/shapecollection/addchart#addchart_1)(ChartType, float, float, float, float, bool) | 새 차트를 생성하고 샘플 시리즈 데이터와 설정으로 초기화한 뒤 쉐이프 컬렉션 끝에 추가합니다. |
| [AddClone](../../aspose.slides/shapecollection/addclone#addclone)(IShape) | 지정된 쉐이프의 복사본을 생성하고 쉐이프 컬렉션 끝에 추가합니다. 복제된 쉐이프는 원본의 위치와 크기를 유지합니다. |
| [AddClone](../../aspose.slides/shapecollection/addclone#addclone_1)(IShape, float, float) | 지정된 쉐이프의 복사본을 생성하고 쉐이프 컬렉션 끝에 추가합니다. 새 쉐이프는 *sourceShape*의 너비와 높이를 유지합니다. |
| [AddClone](../../aspose.slides/shapecollection/addclone#addclone_2)(IShape, float, float, float, float) | 지정된 쉐이프의 복사본을 생성하고 쉐이프 컬렉션 끝에 추가합니다. |
| [AddConnector](../../aspose.slides/shapecollection/addconnector#addconnector)(ShapeType, float, float, float, float) | 기본 템플릿 스타일이 적용된 새 연결자 쉐이프를 생성하고 쉐이프 컬렉션 끝에 추가합니다. |
| [AddConnector](../../aspose.slides/shapecollection/addconnector#addconnector_1)(ShapeType, float, float, float, float, bool) | 새 연결자 쉐이프를 생성하고 쉐이프 컬렉션 끝에 추가하며, 선택적으로 기본 템플릿 스타일을 적용합니다. |
| [AddGroupShape](../../aspose.slides/shapecollection/addgroupshape#addgroupshape)() | 새 빈 그룹 쉐이프를 생성하고 쉐이프 컬렉션 끝에 추가합니다. 그룹 프레임은 추가된 모든 쉐이프에 맞게 자동으로 조정됩니다. |
| [AddGroupShape](../../aspose.slides/shapecollection/addgroupshape#addgroupshape_1)(ISvgImage, float, float, float, float) | 새 그룹 쉐이프를 생성하고 지정된 SVG 이미지를 개별 쉐이프로 변환한 뒤 결과 그룹을 쉐이프 컬렉션 끝에 추가합니다. |
| [AddMathShape](../../aspose.slides/shapecollection/addmathshape)(float, float, float, float) | 수학 콘텐츠를 호스팅하기 위한 새 사각형 자동 쉐이프를 생성하고 쉐이프 컬렉션 끝에 추가합니다. |
| [AddOleObjectFrame](../../aspose.slides/shapecollection/addoleobjectframe#addoleobjectframe)(float, float, float, float, IOleEmbeddedDataInfo) | 새 OLE 객체 프레임을 생성하고 쉐이프 컬렉션 끝에 추가합니다. |
| [AddOleObjectFrame](../../aspose.slides/shapecollection/addoleobjectframe#addoleobjectframe_1)(float, float, float, float, string, string) | 새 OLE 객체 프레임을 생성하고 쉐이프 컬렉션 끝에 추가합니다. |
| [AddPictureFrame](../../aspose.slides/shapecollection/addpictureframe)(ShapeType, float, float, float, float, IPPImage) | 지정된 이미지를 포함하는 새 그림 프레임을 생성하고 쉐이프 컬렉션 끝에 추가합니다. |
| [AddSectionZoomFrame](../../aspose.slides/shapecollection/addsectionzoomframe#addsectionzoomframe)(float, float, float, float, ISection) | 새 Section Zoom 프레임을 생성하고 쉐이프 컬렉션 끝에 추가합니다. |
| [AddSectionZoomFrame](../../aspose.slides/shapecollection/addsectionzoomframe#addsectionzoomframe_1)(float, float, float, float, ISection, IPPImage) | 미리 정의된 이미지를 사용한 새 Section Zoom 프레임을 생성하고 쉐이프 컬렉션 끝에 추가합니다. |
| [AddSmartArt](../../aspose.slides/shapecollection/addsmartart)(float, float, float, float, SmartArtLayoutType) | SmartArt 다이어그램을 생성하고 쉐이프 컬렉션 끝에 추가합니다. |
| [AddSummaryZoomFrame](../../aspose.slides/shapecollection/addsummaryzoomframe)(float, float, float, float) | 새 Summary Zoom 프레임을 생성하고 쉐이프 컬렉션 끝에 추가합니다. |
| [AddTable](../../aspose.slides/shapecollection/addtable)(float, float, double[], double[]) | 새 테이블을 생성하고 쉐이프 컬렉션 끝에 추가합니다. |
| [AddVideoFrame](../../aspose.slides/shapecollection/addvideoframe#addvideoframe)(float, float, float, float, IVideo) | 새 비디오 프레임을 생성하고 쉐이프 컬렉션 끝에 추가합니다. |
| [AddVideoFrame](../../aspose.slides/shapecollection/addvideoframe#addvideoframe_1)(float, float, float, float, string) | 새 비디오 프레임을 생성하고 쉐이프 컬렉션 끝에 추가합니다. |
| [AddZoomFrame](../../aspose.slides/shapecollection/addzoomframe#addzoomframe)(float, float, float, float, ISlide) | 새 Zoom 프레임을 생성하고 쉐이프 컬렉션 끝에 추가합니다. |
| [AddZoomFrame](../../aspose.slides/shapecollection/addzoomframe#addzoomframe_1)(float, float, float, float, ISlide, IPPImage) | 새 Zoom 프레임을 생성하고 쉐이프 컬렉션 끝에 추가합니다. |
| [Clear](../../aspose.slides/shapecollection/clear)() | 쉐이프 컬렉션의 모든 쉐이프를 제거합니다. |
| [CopyTo](../../aspose.slides/shapecollection/copyto)(Array, int) | 컬렉션의 모든 요소를 지정된 배열에 복사합니다. |
| [GetEnumerator](../../aspose.slides/shapecollection/getenumerator)() | 컬렉션을 순회하는 열거자를 반환합니다. |
| [IndexOf](../../aspose.slides/shapecollection/indexof)(IShape) | 지정된 쉐이프가 컬렉션에 처음 나타나는 인덱스(0부터 시작)를 반환합니다. |
| [InsertAudioFrameCD](../../aspose.slides/shapecollection/insertaudioframecd)(int, float, float, float, float) | 새 오디오 프레임을 CD 트랙에 연결하여 생성하고 지정된 인덱스에 삽입합니다. |
| [InsertAudioFrameEmbedded](../../aspose.slides/shapecollection/insertaudioframeembedded#insertaudioframeembedded)(int, float, float, float, float, IAudio) | 기존 Presentation.Audios 목록에 있는 오디오 객체를 사용하여 새 오디오 프레임을 생성하고 지정된 인덱스에 삽입합니다. |
| [InsertAudioFrameEmbedded](../../aspose.slides/shapecollection/insertaudioframeembedded#insertaudioframeembedded_1)(int, float, float, float, float, Stream) | 임베드된 WAV 파일을 포함하는 새 오디오 프레임을 생성하고 지정된 인덱스에 삽입합니다. 임베드된 오디오가 Presentation.Audios 컬렉션에 추가됩니다. |
| [InsertAudioFrameLinked](../../aspose.slides/shapecollection/insertaudioframelinked)(int, float, float, float, float, string) | 새 오디오 프레임을 외부 오디오 파일에 연결하여 생성하고 지정된 인덱스에 삽입합니다. |
| [InsertAutoShape](../../aspose.slides/shapecollection/insertautoshape#insertautoshape)(int, ShapeType, float, float, float, float) | 기본 템플릿 서식이 적용된 새 자동 쉐이프를 생성하고 지정된 인덱스에 삽입합니다. |
| [InsertAutoShape](../../aspose.slides/shapecollection/insertautoshape#insertautoshape_1)(int, ShapeType, float, float, float, float, bool) | 새 자동 쉐이프를 생성하고 지정된 인덱스에 삽입하며, 선택적으로 기본 템플릿 스타일로 초기화합니다. |
| [InsertChart](../../aspose.slides/shapecollection/insertchart#insertchart)(ChartType, float, float, float, float, int) | 새 차트를 생성하고 샘플 시리즈 데이터와 설정으로 초기화한 뒤 지정된 인덱스에 삽입합니다. |
| [InsertChart](../../aspose.slides/shapecollection/insertchart#insertchart_1)(ChartType, float, float, float, float, int, bool) | 새 차트를 생성하고 샘플 시리즈 데이터와 설정으로 초기화한 뒤 지정된 인덱스에 삽입합니다. |
| [InsertClone](../../aspose.slides/shapecollection/insertclone#insertclone)(int, IShape) | 지정된 쉐이프의 복사본을 생성하고 지정된 인덱스에 삽입합니다. 복제된 쉐이프는 원본의 위치와 크기를 유지합니다. |
| [InsertClone](../../aspose.slides/shapecollection/insertclone#insertclone_1)(int, IShape, float, float) | 지정된 쉐이프의 복사본을 생성하고 지정된 인덱스에 삽입합니다. 새 쉐이프는 *sourceShape*의 너비와 높이를 유지합니다. |
| [InsertClone](../../aspose.slides/shapecollection/insertclone#insertclone_2)(int, IShape, float, float, float, float) | 지정된 쉐이프의 복사본을 생성하고 지정된 인덱스에 삽입합니다. |
| [InsertConnector](../../aspose.slides/shapecollection/insertconnector#insertconnector)(int, ShapeType, float, float, float, float) | 새 연결자 쉐이프를 생성하고 지정된 인덱스에 삽입하며 기본 템플릿 스타일을 적용합니다. |
| [InsertConnector](../../aspose.slides/shapecollection/insertconnector#insertconnector_1)(int, ShapeType, float, float, float, float, bool) | 새 연결자 쉐이프를 생성하고 지정된 인덱스에 삽입하며, 선택적으로 기본 템플릿 스타일을 적용합니다. |
| [InsertGroupShape](../../aspose.slides/shapecollection/insertgroupshape)(int) | 새 빈 그룹 쉐이프를 생성하고 지정된 인덱스에 삽입합니다. 그룹 프레임은 추가된 모든 쉐이프에 맞게 자동으로 조정됩니다. |
| [InsertOleObjectFrame](../../aspose.slides/shapecollection/insertoleobjectframe#insertoleobjectframe)(int, float, float, float, float, IOleEmbeddedDataInfo) | 새 OLE 객체 프레임을 생성하고 지정된 인덱스에 삽입합니다. |
| [InsertOleObjectFrame](../../aspose.slides/shapecollection/insertoleobjectframe#insertoleobjectframe_1)(int, float, float, float, float, string, string) | 새 OLE 객체 프레임을 생성하고 지정된 인덱스에 삽입합니다. |
| [InsertPictureFrame](../../aspose.slides/shapecollection/insertpictureframe)(int, ShapeType, float, float, float, float, IPPImage) | 지정된 이미지를 포함하는 새 그림 프레임을 생성하고 지정된 인덱스에 삽입합니다. |
| [InsertSectionZoomFrame](../../aspose.slides/shapecollection/insertsectionzoomframe#insertsectionzoomframe)(int, float, float, float, float, ISection) | 새 Section Zoom 프레임을 생성하고 지정된 인덱스에 삽입합니다. |
| [InsertSectionZoomFrame](../../aspose.slides/shapecollection/insertsectionzoomframe#insertsectionzoomframe_1)(int, float, float, float, float, ISection, IPPImage) | 미리 정의된 이미지를 사용한 새 Section Zoom 프레임을 생성하고 지정된 인덱스에 삽입합니다. |
| [InsertSummaryZoomFrame](../../aspose.slides/shapecollection/insertsummaryzoomframe)(int, float, float, float, float) | 새 Summary Zoom 프레임을 생성하고 지정된 인덱스에 삽입합니다. |
| [InsertTable](../../aspose.slides/shapecollection/inserttable)(int, float, float, double[], double[]) | 새 테이블을 생성하고 지정된 인덱스에 삽입합니다. |
| [InsertVideoFrame](../../aspose.slides/shapecollection/insertvideoframe)(int, float, float, float, float, string) | 새 비디오 프레임을 생성하고 지정된 인덱스에 삽입합니다. |
| [InsertZoomFrame](../../aspose.slides/shapecollection/insertzoomframe#insertzoomframe)(int, float, float, float, float, ISlide) | 새 Zoom 프레임을 생성하고 지정된 인덱스에 삽입합니다. |
| [InsertZoomFrame](../../aspose.slides/shapecollection/insertzoomframe#insertzoomframe_1)(int, float, float, float, float, ISlide, IPPImage) | 미리 정의된 이미지를 사용한 새 Zoom 프레임을 생성하고 지정된 인덱스에 삽입합니다. |
| [Remove](../../aspose.slides/shapecollection/remove)(IShape) | 지정된 쉐이프를 컬렉션에서 처음 발견되는 위치에서 제거합니다. |
| [RemoveAt](../../aspose.slides/shapecollection/removeat)(int) | 지정된 인덱스에 있는 쉐이프를 컬렉션에서 제거합니다. |
| [Reorder](../../aspose.slides/shapecollection/reorder#reorder)(int, IShape) | 지정된 쉐이프를 컬렉션 내 새로운 위치로 이동합니다. |
| [Reorder](../../aspose.slides/shapecollection/reorder#reorder_1)(int, params IShape[]) | 지정된 쉐이프들을 컬렉션 내에서 이동시키며, 주어진 인덱스부터 배치합니다. |
| [ToArray](../../aspose.slides/shapecollection/toarray#toarray)() | 모든 쉐이프를 포함하는 배열을 생성하여 반환합니다. |
| [ToArray](../../aspose.slides/shapecollection/toarray#toarray_1)(int, int) | 지정된 범위의 모든 쉐이프를 포함하는 배열을 생성하여 반환합니다. |

### 또 다른 보기

* 클래스 [DomObject&lt;TParent&gt;](../domobject-1)
* 클래스 [GroupShape](../groupshape)
* 인터페이스 [IShapeCollection](../ishapecollection)
* 네임스페이스 [Aspose.Slides](../../aspose.slides)
* 어셈블리 [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->