---
title: IShapeCollection
second_title: Aspose.Sildes for .NET API 참조
description: 도형 컬렉션을 나타냅니다.
type: docs
weight: 6980
url: /ko/aspose.slides/ishapecollection/
---
## IShapeCollection 인터페이스

도형 컬렉션을 나타냅니다.

```csharp
public interface IShapeCollection : IGenericCollection<IShape>
```

## 속성

| 이름 | 설명 |
| --- | --- |
| [Item](../../aspose.slides/ishapecollection/item) { get; } | 지정된 인덱스에 있는 요소를 가져옵니다. 읽기 전용 [`IShape`](../ishape). |
| [ParentGroup](../../aspose.slides/ishapecollection/parentgroup) { get; } | 도형 컬렉션의 상위 그룹 도형 객체를 가져옵니다. 읽기 전용 [`IGroupShape`](../igroupshape). |

## 메서드

| 이름 | 설명 |
| --- | --- |
| [AddAudioFrameCD](../../aspose.slides/ishapecollection/addaudioframecd)(float, float, float, float) | 새 오디오 프레임을 CD 트랙에 연결하여 생성하고 도형 컬렉션 끝에 추가합니다. |
| [AddAudioFrameEmbedded](../../aspose.slides/ishapecollection/addaudioframeembedded#addaudioframeembedded)(float, float, float, float, IAudio) | Presentation.Audios 목록에 있는 기존 오디오 개체를 사용하여 새 오디오 프레임을 생성하고 도형 컬렉션 끝에 추가합니다. |
| [AddAudioFrameEmbedded](../../aspose.slides/ishapecollection/addaudioframeembedded#addaudioframeembedded_1)(float, float, float, float, Stream) | 임베드된 WAV 파일로 새 오디오 프레임을 생성하고 도형 컬렉션 끝에 추가합니다. 임베드된 오디오는 Presentation.Audios 컬렉션에 추가됩니다. |
| [AddAudioFrameLinked](../../aspose.slides/ishapecollection/addaudioframelinked)(float, float, float, float, string) | 외부 오디오 파일에 연결된 새 오디오 프레임을 생성하고 도형 컬렉션 끝에 추가합니다. |
| [AddAutoShape](../../aspose.slides/ishapecollection/addautoshape#addautoshape)(ShapeType, float, float, float, float) | 기본 서식이 적용된 새 자동 도형을 생성하고 도형 컬렉션 끝에 추가합니다. |
| [AddAutoShape](../../aspose.slides/ishapecollection/addautoshape#addautoshape_1)(ShapeType, float, float, float, float, bool) | 새 자동 도형을 생성하고 도형 컬렉션 끝에 추가합니다. 선택적으로 기본 템플릿 서식으로 초기화할 수 있습니다. |
| [AddChart](../../aspose.slides/ishapecollection/addchart#addchart)(ChartType, float, float, float, float) | 새 차트를 생성하고 샘플 시리즈 데이터와 설정으로 초기화한 뒤 도형 컬렉션 끝에 추가합니다. |
| [AddChart](../../aspose.slides/ishapecollection/addchart#addchart_1)(ChartType, float, float, float, float, bool) | 새 차트를 생성하고 샘플 시리즈 데이터와 설정으로 초기화한 뒤 도형 컬렉션 끝에 추가합니다. |
| [AddClone](../../aspose.slides/ishapecollection/addclone#addclone)(IShape) | 지정된 도형을 복사하여 도형 컬렉션 끝에 추가합니다. 복제된 도형은 원본의 위치와 크기를 유지합니다. |
| [AddClone](../../aspose.slides/ishapecollection/addclone#addclone_1)(IShape, float, float) | 지정된 도형을 복사하여 도형 컬렉션 끝에 추가합니다. 새 도형은 *sourceShape*의 너비와 높이를 유지합니다. |
| [AddClone](../../aspose.slides/ishapecollection/addclone#addclone_2)(IShape, float, float, float, float) | 지정된 도형을 복사하여 도형 컬렉션 끝에 추가합니다. |
| [AddConnector](../../aspose.slides/ishapecollection/addconnector#addconnector)(ShapeType, float, float, float, float) | 기본 템플릿 스타일이 적용된 새 연결 도형을 생성하고 도형 컬렉션 끝에 추가합니다. |
| [AddConnector](../../aspose.slides/ishapecollection/addconnector#addconnector_1)(ShapeType, float, float, float, float, bool) | 새 연결 도형을 생성하고 도형 컬렉션 끝에 추가합니다. 선택적으로 기본 템플릿 스타일을 적용할 수 있습니다. |
| [AddGroupShape](../../aspose.slides/ishapecollection/addgroupshape#addgroupshape)() | 새 빈 그룹 도형을 생성하고 도형 컬렉션 끝에 추가합니다. 그룹의 프레임은 추가되는 모든 도형에 맞게 자동으로 조정됩니다. |
| [AddGroupShape](../../aspose.slides/ishapecollection/addgroupshape#addgroupshape_1)(ISvgImage, float, float, float, float) | 새 그룹 도형을 생성하고 지정된 SVG 이미지를 개별 도형으로 변환한 뒤, 결과 그룹을 도형 컬렉션 끝에 추가합니다. |
| [AddMathShape](../../aspose.slides/ishapecollection/addmathshape)(float, float, float, float) | 수학 콘텐츠를 담을 새 직사각형 자동 도형을 생성하고 도형 컬렉션 끝에 추가합니다. |
| [AddOleObjectFrame](../../aspose.slides/ishapecollection/addoleobjectframe#addoleobjectframe)(float, float, float, float, IOleEmbeddedDataInfo) | 새 OLE 개체 프레임을 생성하고 도형 컬렉션 끝에 추가합니다. |
| [AddOleObjectFrame](../../aspose.slides/ishapecollection/addoleobjectframe#addoleobjectframe_1)(float, float, float, float, string, string) | 새 OLE 개체 프레임을 생성하고 도형 컬렉션 끝에 추가합니다. |
| [AddPictureFrame](../../aspose.slides/ishapecollection/addpictureframe)(ShapeType, float, float, float, float, IPPImage) | 지정된 이미지를 포함하는 새 그림 프레임을 생성하고 도형 컬렉션 끝에 추가합니다. |
| [AddSectionZoomFrame](../../aspose.slides/ishapecollection/addsectionzoomframe#addsectionzoomframe)(float, float, float, float, ISection) | 새 섹션 확대 프레임을 생성하고 도형 컬렉션 끝에 추가합니다. |
| [AddSectionZoomFrame](../../aspose.slides/ishapecollection/addsectionzoomframe#addsectionzoomframe_1)(float, float, float, float, ISection, IPPImage) | 미리 정의된 이미지가 있는 새 섹션 확대 프레임을 생성하고 도형 컬렉션 끝에 추가합니다. |
| [AddSmartArt](../../aspose.slides/ishapecollection/addsmartart)(float, float, float, float, SmartArtLayoutType) | SmartArt 다이어그램을 생성하고 도형 컬렉션 끝에 추가합니다. |
| [AddSummaryZoomFrame](../../aspose.slides/ishapecollection/addsummaryzoomframe)(float, float, float, float) | 새 요약 확대 프레임을 생성하고 도형 컬렉션 끝에 추가합니다. |
| [AddTable](../../aspose.slides/ishapecollection/addtable)(float, float, double[], double[]) | 새 표를 생성하고 도형 컬렉션 끝에 추가합니다. |
| [AddVideoFrame](../../aspose.slides/ishapecollection/addvideoframe#addvideoframe)(float, float, float, float, IVideo) | 새 비디오 프레임을 생성하고 도형 컬렉션 끝에 추가합니다. |
| [AddVideoFrame](../../aspose.slides/ishapecollection/addvideoframe#addvideoframe_1)(float, float, float, float, string) | 새 비디오 프레임을 생성하고 도형 컬렉션 끝에 추가합니다. |
| [AddZoomFrame](../../aspose.slides/ishapecollection/addzoomframe#addzoomframe)(float, float, float, float, ISlide) | 새 확대 프레임을 생성하고 도형 컬렉션 끝에 추가합니다. |
| [AddZoomFrame](../../aspose.slides/ishapecollection/addzoomframe#addzoomframe_1)(float, float, float, float, ISlide, IPPImage) | 새 확대 프레임을 생성하고 도형 컬렉션 끝에 추가합니다. |
| [Clear](../../aspose.slides/ishapecollection/clear)() | 도형 컬렉션의 모든 도형을 제거합니다. |
| [IndexOf](../../aspose.slides/ishapecollection/indexof)(IShape) | 컬렉션에서 지정된 도형이 처음 나타나는 0 기반 인덱스를 반환합니다. |
| [InsertAudioFrameCD](../../aspose.slides/ishapecollection/insertaudioframecd)(int, float, float, float, float) | 새 오디오 프레임을 CD 트랙에 연결하고 지정된 인덱스에 도형 컬렉션에 삽입합니다. |
| [InsertAudioFrameEmbedded](../../aspose.slides/ishapecollection/insertaudioframeembedded#insertaudioframeembedded)(int, float, float, float, float, IAudio) | 새 오디오 프레임을 생성하고 Presentation.Audios 목록에 있는 기존 오디오 객체를 사용하여 지정된 인덱스에 도형 컬렉션에 삽입합니다. |
| [InsertAudioFrameEmbedded](../../aspose.slides/ishapecollection/insertaudioframeembedded#insertaudioframeembedded_1)(int, float, float, float, float, Stream) | 임베드된 WAV 파일을 사용하여 새 오디오 프레임을 생성하고 지정된 인덱스에 도형 컬렉션에 삽입합니다. 임베드된 오디오는 Presentation.Audios 컬렉션에 추가됩니다. |
| [InsertAudioFrameLinked](../../aspose.slides/ishapecollection/insertaudioframelinked)(int, float, float, float, float, string) | 외부 오디오 파일에 연결된 새 오디오 프레임을 생성하고 지정된 인덱스에 도형 컬렉션에 삽입합니다. |
| [InsertAutoShape](../../aspose.slides/ishapecollection/insertautoshape#insertautoshape)(int, ShapeType, float, float, float, float) | 새 자동 도형을 생성하고 기본 템플릿 서식을 적용하여 지정된 인덱스에 도형 컬렉션에 삽입합니다. |
| [InsertAutoShape](../../aspose.slides/ishapecollection/insertautoshape#insertautoshape_1)(int, ShapeType, float, float, float, float, bool) | 새 자동 도형을 생성하고 선택적으로 기본 템플릿 서식을 적용하여 지정된 인덱스에 도형 컬렉션에 삽입합니다. |
| [InsertChart](../../aspose.slides/ishapecollection/insertchart#insertchart)(ChartType, float, float, float, float, int) | 새 차트를 생성하고 샘플 시리즈 데이터와 설정으로 초기화한 뒤 지정된 인덱스에 도형 컬렉션에 삽입합니다. |
| [InsertChart](../../aspose.slides/ishapecollection/insertchart#insertchart_1)(ChartType, float, float, float, float, int, bool) | 새 차트를 생성하고 샘플 시리즈 데이터와 설정으로 초기화한 뒤 선택적으로 기본 템플릿 서식을 적용하여 지정된 인덱스에 도형 컬렉션에 삽입합니다. |
| [InsertClone](../../aspose.slides/ishapecollection/insertclone#insertclone)(int, IShape) | 지정된 도형을 복사하고 지정된 인덱스에 도형 컬렉션에 삽입합니다. 복제된 도형은 원본의 위치와 크기를 유지합니다. |
| [InsertClone](../../aspose.slides/ishapecollection/insertclone#insertclone_1)(int, IShape, float, float) | 지정된 도형을 복사하고 지정된 인덱스에 도형 컬렉션에 삽입합니다. 새 도형은 *sourceShape*의 너비와 높이를 유지합니다. |
| [InsertClone](../../aspose.slides/ishapecollection/insertclone#insertclone_2)(int, IShape, float, float, float, float) | 지정된 도형을 복사하고 지정된 인덱스에 도형 컬렉션에 삽입합니다. |
| [InsertConnector](../../aspose.slides/ishapecollection/insertconnector#insertconnector)(int, ShapeType, float, float, float, float) | 새 연결 도형을 생성하고 기본 템플릿 스타일을 적용하여 지정된 인덱스에 도형 컬렉션에 삽입합니다. |
| [InsertConnector](../../aspose.slides/ishapecollection/insertconnector#insertconnector_1)(int, ShapeType, float, float, float, float, bool) | 새 연결 도형을 생성하고 선택적으로 기본 템플릿 스타일을 적용하여 지정된 인덱스에 도형 컬렉션에 삽입합니다. |
| [InsertGroupShape](../../aspose.slides/ishapecollection/insertgroupshape)(int) | 새 빈 그룹 도형을 생성하고 지정된 인덱스에 도형 컬렉션에 삽입합니다. 그룹의 프레임은 추가되는 모든 도형에 맞게 자동으로 조정됩니다. |
| [InsertOleObjectFrame](../../aspose.slides/ishapecollection/insertoleobjectframe#insertoleobjectframe)(int, float, float, float, float, IOleEmbeddedDataInfo) | 새 OLE 개체 프레임을 생성하고 지정된 인덱스에 도형 컬렉션에 삽입합니다. |
| [InsertOleObjectFrame](../../aspose.slides/ishapecollection/insertoleobjectframe#insertoleobjectframe_1)(int, float, float, float, float, string, string) | 새 OLE 개체 프레임을 생성하고 지정된 인덱스에 도형 컬렉션에 삽입합니다. |
| [InsertPictureFrame](../../aspose.slides/ishapecollection/insertpictureframe)(int, ShapeType, float, float, float, float, IPPImage) | 지정된 이미지를 포함하는 새 그림 프레임을 생성하고 지정된 인덱스에 도형 컬렉션에 삽입합니다. |
| [InsertSectionZoomFrame](../../aspose.slides/ishapecollection/insertsectionzoomframe#insertsectionzoomframe)(int, float, float, float, float, ISection) | 새 섹션 확대 프레임을 생성하고 지정된 인덱스에 도형 컬렉션에 삽입합니다. |
| [InsertSectionZoomFrame](../../aspose.slides/ishapecollection/insertsectionzoomframe#insertsectionzoomframe_1)(int, float, float, float, float, ISection, IPPImage) | 미리 정의된 이미지가 있는 새 섹션 확대 프레임을 생성하고 지정된 인덱스에 도형 컬렉션에 삽입합니다. |
| [InsertSummaryZoomFrame](../../aspose.slides/ishapecollection/insertsummaryzoomframe)(int, float, float, float, float) | 새 요약 확대 프레임을 생성하고 지정된 인덱스에 도형 컬렉션에 삽입합니다. |
| [InsertTable](../../aspose.slides/ishapecollection/inserttable)(int, float, float, double[], double[]) | 새 표를 생성하고 지정된 인덱스에 도형 컬렉션에 삽입합니다. |
| [InsertVideoFrame](../../aspose.slides/ishapecollection/insertvideoframe)(int, float, float, float, float, string) | 새 비디오 프레임을 생성하고 지정된 인덱스에 도형 컬렉션에 삽입합니다. |
| [InsertZoomFrame](../../aspose.slides/ishapecollection/insertzoomframe#insertzoomframe)(int, float, float, float, float, ISlide) | 새 확대 프레임을 생성하고 지정된 인덱스에 도형 컬렉션에 삽입합니다. |
| [InsertZoomFrame](../../aspose.slides/ishapecollection/insertzoomframe#insertzoomframe_1)(int, float, float, float, float, ISlide, IPPImage) | 미리 정의된 이미지가 있는 새 확대 프레임을 생성하고 지정된 인덱스에 도형 컬렉션에 삽입합니다. |
| [Remove](../../aspose.slides/ishapecollection/remove)(IShape) | 도형 컬렉션에서 지정된 도형의 첫 번째 발생을 제거합니다. |
| [RemoveAt](../../aspose.slides/ishapecollection/removeat)(int) | 도형 컬렉션에서 지정된 인덱스에 있는 도형을 제거합니다. |
| [Reorder](../../aspose.slides/ishapecollection/reorder#reorder)(int, IShape) | 도형 컬렉션 내에서 지정된 도형을 새 위치로 이동합니다. |
| [Reorder](../../aspose.slides/ishapecollection/reorder#reorder_1)(int, params IShape[]) | 도형 컬렉션에서 지정된 도형들을 주어진 인덱스부터 시작하여 이동합니다. |
| [ToArray](../../aspose.slides/ishapecollection/toarray#toarray)() | 모든 도형을 포함하는 배열을 생성하고 반환합니다. |
| [ToArray](../../aspose.slides/ishapecollection/toarray#toarray_1)(int, int) | 지정된 범위에 있는 모든 도형을 포함하는 배열을 생성하고 반환합니다. |

### 참조

* 인터페이스 [IGenericCollection&lt;T&gt;](../igenericcollection-1)
* 인터페이스 [IShape](../ishape)
* 네임스페이스 [Aspose.Slides](../../aspose.slides)
* 어셈블리 [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->