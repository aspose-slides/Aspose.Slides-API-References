---
title: IShapeCollection
second_title: Aspose.Slides for Java API 참조
description: 도형 컬렉션을 나타냅니다.
type: docs
url: /ko/com.aspose.slides/ishapecollection/
---
**구현된 모든 인터페이스:**
com.aspose.slides.IGenericCollection
```
public interface IShapeCollection extends IGenericCollection<IShape>
```

도형 컬렉션을 나타냅니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | 지정된 인덱스의 요소를 가져옵니다. |
| [getParentGroup()](#getParentGroup--) | 도형 컬렉션의 상위 그룹 도형 객체를 가져옵니다. |
| [addChart(int type, float x, float y, float width, float height)](#addChart-int-float-float-float-float-) | 새 차트를 생성하고 샘플 시리즈 데이터와 설정으로 초기화한 다음 도형 컬렉션 끝에 추가합니다. |
| [addChart(int type, float x, float y, float width, float height, boolean initWithSample)](#addChart-int-float-float-float-float-boolean-) | 새 차트를 생성하고 샘플 시리즈 데이터와 설정으로 초기화한 다음 도형 컬렉션 끝에 추가합니다. |
| [addSmartArt(float x, float y, float width, float height, int layoutType)](#addSmartArt-float-float-float-float-int-) | SmartArt 다이어그램을 생성하고 도형 컬렉션 끝에 추가합니다. |
| [insertChart(int type, float x, float y, float width, float height, int index)](#insertChart-int-float-float-float-float-int-) | 새 차트를 생성하고 샘플 시리즈 데이터와 설정으로 초기화한 다음 지정된 인덱스에 도형 컬렉션에 삽입합니다. |
| [insertChart(int type, float x, float y, float width, float height, int index, boolean initWithSample)](#insertChart-int-float-float-float-float-int-boolean-) | 새 차트를 생성하고 샘플 시리즈 데이터와 설정으로 초기화한 다음 지정된 인덱스에 도형 컬렉션에 삽입합니다. |
| [addOleObjectFrame(float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo)](#addOleObjectFrame-float-float-float-float-com.aspose.slides.IOleEmbeddedDataInfo-) | 새 OLE 개체 프레임을 생성하고 도형 컬렉션 끝에 추가합니다. |
| [addOleObjectFrame(float x, float y, float width, float height, String className, String path)](#addOleObjectFrame-float-float-float-float-java.lang.String-java.lang.String-) | 새 OLE 개체 프레임을 생성하고 도형 컬렉션 끝에 추가합니다. |
| [insertOleObjectFrame(int index, float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo)](#insertOleObjectFrame-int-float-float-float-float-com.aspose.slides.IOleEmbeddedDataInfo-) | 새 OLE 개체 프레임을 생성하고 지정된 인덱스에 도형 컬렉션에 삽입합니다. |
| [insertOleObjectFrame(int index, float x, float y, float width, float height, String className, String path)](#insertOleObjectFrame-int-float-float-float-float-java.lang.String-java.lang.String-) | 새 OLE 개체 프레임을 생성하고 지정된 인덱스에 도형 컬렉션에 삽입합니다. |
| [addZoomFrame(float x, float y, float width, float height, ISlide slide)](#addZoomFrame-float-float-float-float-com.aspose.slides.ISlide-) | 새 줌 프레임을 생성하고 도형 컬렉션 끝에 추가합니다. |
| [addZoomFrame(float x, float y, float width, float height, ISlide slide, IPPImage image)](#addZoomFrame-float-float-float-float-com.aspose.slides.ISlide-com.aspose.slides.IPPImage-) | 새 줌 프레임을 생성하고 도형 컬렉션 끝에 추가합니다. |
| [insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide)](#insertZoomFrame-int-float-float-float-float-com.aspose.slides.ISlide-) | 새 줌 프레임을 생성하고 지정된 인덱스에 도형 컬렉션에 삽입합니다. |
| [insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide, IPPImage image)](#insertZoomFrame-int-float-float-float-float-com.aspose.slides.ISlide-com.aspose.slides.IPPImage-) | 미리 정의된 이미지를 사용해 새 줌 프레임을 생성하고 지정된 인덱스에 도형 컬렉션에 삽입합니다. |
| [addSectionZoomFrame(float x, float y, float width, float height, ISection section)](#addSectionZoomFrame-float-float-float-float-com.aspose.slides.ISection-) | 새 섹션 줌 프레임을 생성하고 도형 컬렉션 끝에 추가합니다. |
| [addSectionZoomFrame(float x, float y, float width, float height, ISection section, IPPImage image)](#addSectionZoomFrame-float-float-float-float-com.aspose.slides.ISection-com.aspose.slides.IPPImage-) | 미리 정의된 이미지를 사용해 새 섹션 줌 프레임을 생성하고 도형 컬렉션 끝에 추가합니다. |
| [insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section)](#insertSectionZoomFrame-int-float-float-float-float-com.aspose.slides.ISection-) | 새 섹션 줌 프레임을 생성하고 지정된 인덱스에 도형 컬렉션에 삽입합니다. |
| [insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section, IPPImage image)](#insertSectionZoomFrame-int-float-float-float-float-com.aspose.slides.ISection-com.aspose.slides.IPPImage-) | 미리 정의된 이미지를 사용해 새 섹션 줌 프레임을 생성하고 지정된 인덱스에 도형 컬렉션에 삽입합니다. |
| [addSummaryZoomFrame(float x, float y, float width, float height)](#addSummaryZoomFrame-float-float-float-float-) | 새 요약 줌 프레임을 생성하고 도형 컬렉션 끝에 추가합니다. |
| [insertSummaryZoomFrame(int index, float x, float y, float width, float height)](#insertSummaryZoomFrame-int-float-float-float-float-) | 새 요약 줌 프레임을 생성하고 지정된 인덱스에 도형 컬렉션에 삽입합니다. |
| [addVideoFrame(float x, float y, float width, float height, String fname)](#addVideoFrame-float-float-float-float-java.lang.String-) | 새 비디오 프레임을 생성하고 도형 컬렉션 끝에 추가합니다. |
| [addVideoFrame(float x, float y, float width, float height, IVideo video)](#addVideoFrame-float-float-float-float-com.aspose.slides.IVideo-) | 새 비디오 프레임을 생성하고 도형 컬렉션 끝에 추가합니다. |
| [insertVideoFrame(int index, float x, float y, float width, float height, String fname)](#insertVideoFrame-int-float-float-float-float-java.lang.String-) | 새 비디오 프레임을 생성하고 지정된 인덱스에 도형 컬렉션에 삽입합니다. |
| [addAudioFrameCD(float x, float y, float width, float height)](#addAudioFrameCD-float-float-float-float-) | CD 트랙에 연결된 새 오디오 프레임을 생성하고 도형 컬렉션 끝에 추가합니다. |
| [insertAudioFrameCD(int index, float x, float y, float width, float height)](#insertAudioFrameCD-int-float-float-float-float-) | CD 트랙에 연결된 새 오디오 프레임을 생성하고 지정된 인덱스에 도형 컬렉션에 삽입합니다. |
| [addAudioFrameLinked(float x, float y, float width, float height, String fname)](#addAudioFrameLinked-float-float-float-float-java.lang.String-) | 외부 오디오 파일에 연결된 새 오디오 프레임을 생성하고 도형 컬렉션 끝에 추가합니다. |
| [insertAudioFrameLinked(int index, float x, float y, float width, float height, String fname)](#insertAudioFrameLinked-int-float-float-float-float-java.lang.String-) | 외부 오디오 파일에 연결된 새 오디오 프레임을 생성하고 지정된 인덱스에 도형 컬렉션에 삽입합니다. |
| [addAudioFrameEmbedded(float x, float y, float width, float height, InputStream audio_stream)](#addAudioFrameEmbedded-float-float-float-float-java.io.InputStream-) | 내장된 WAV 파일이 있는 새 오디오 프레임을 생성하고 도형 컬렉션 끝에 추가합니다. |
| [addAudioFrameEmbedded(float x, float y, float width, float height, IAudio audio)](#addAudioFrameEmbedded-float-float-float-float-com.aspose.slides.IAudio-) | Presentation.Audios 목록의 기존 오디오 객체를 사용해 새 오디오 프레임을 생성하고 도형 컬렉션 끝에 추가합니다. |
| [insertAudioFrameEmbedded(int index, float x, float y, float width, float height, InputStream audio_stream)](#insertAudioFrameEmbedded-int-float-float-float-float-java.io.InputStream-) | 내장된 WAV 파일이 있는 새 오디오 프레임을 생성하고 지정된 인덱스에 도형 컬렉션에 삽입합니다. |
| [insertAudioFrameEmbedded(int index, float x, float y, float width, float height, IAudio audio)](#insertAudioFrameEmbedded-int-float-float-float-float-com.aspose.slides.IAudio-) | Presentation.Audios 목록의 기존 오디오 객체를 사용해 새 오디오 프레임을 생성하고 지정된 인덱스에 도형 컬렉션에 삽입합니다. |
| [indexOf(IShape shape)](#indexOf-com.aspose.slides.IShape-) | 컬렉션에서 지정된 도형이 처음 나타나는 0 기반 인덱스를 반환합니다. |
| [toArray()](#toArray--) | 모든 도형을 포함하는 배열을 생성하고 반환합니다. |
| [toArray(int startIndex, int count)](#toArray-int-int-) | 지정된 범위의 모든 도형을 포함하는 배열을 생성하고 반환합니다. |
| [reorder(int index, IShape shape)](#reorder-int-com.aspose.slides.IShape-) | 지정된 도형을 컬렉션 내 새로운 위치로 이동합니다. |
| [reorder(int index, IShape[] shapes)](#reorder-int-com.aspose.slides.IShape...-) | 지정된 도형들을 컬렉션 내에서 이동하여 주어진 인덱스부터 배치합니다. |
| [addAutoShape(int shapeType, float x, float y, float width, float height)](#addAutoShape-int-float-float-float-float-) | 기본 서식이 적용된 새 자동 도형을 생성하고 도형 컬렉션 끝에 추가합니다. |
| [addAutoShape(int shapeType, float x, float y, float width, float height, boolean createFromTemplate)](#addAutoShape-int-float-float-float-float-boolean-) | 새 자동 도형을 생성하고 도형 컬렉션 끝에 추가합니다. 옵션으로 기본 템플릿 서식으로 초기화할 수 있습니다. |
| [addMathShape(float x, float y, float width, float height)](#addMathShape-float-float-float-float-) | 수학 콘텐츠를 담을 새 사각형 자동 도형을 생성하고 도형 컬렉션 끝에 추가합니다. |
| [insertAutoShape(int index, int shapeType, float x, float y, float width, float height)](#insertAutoShape-int-int-float-float-float-float-) | 새 자동 도형을 생성하고 지정된 인덱스에 도형 컬렉션에 삽입하며 기본 템플릿 서식을 적용합니다. |
| [insertAutoShape(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate)](#insertAutoShape-int-int-float-float-float-float-boolean-) | 새 자동 도형을 생성하고 지정된 인덱스에 도형 컬렉션에 삽입합니다. 옵션으로 기본 템플릿 스타일로 초기화할 수 있습니다. |
| [addGroupShape()](#addGroupShape--) | 새 빈 그룹 도형을 생성하고 도형 컬렉션 끝에 추가합니다. |
| [addGroupShape(ISvgImage svgImage, float x, float y, float width, float height)](#addGroupShape-com.aspose.slides.ISvgImage-float-float-float-float-) | 새 그룹 도형을 생성하고 지정된 SVG 이미지를 개별 도형으로 변환한 후 결과 그룹을 도형 컬렉션 끝에 추가합니다. |
| [insertGroupShape(int index)](#insertGroupShape-int-) | 새 빈 그룹 도형을 생성하고 지정된 인덱스에 도형 컬렉션에 삽입합니다. |
| [addConnector(int shapeType, float x, float y, float width, float height)](#addConnector-int-float-float-float-float-) | 기본 템플릿 스타일이 적용된 새 연결 도형을 생성하고 도형 컬렉션 끝에 추가합니다. |
| [addConnector(int shapeType, float x, float y, float width, float height, boolean createFromTemplate)](#addConnector-int-float-float-float-float-boolean-) | 새 연결 도형을 생성하고 도형 컬렉션 끝에 추가합니다. 옵션으로 기본 템플릿 스타일을 적용할 수 있습니다. |
| [insertConnector(int index, int shapeType, float x, float y, float width, float height)](#insertConnector-int-int-float-float-float-float-) | 새 연결 도형을 생성하고 지정된 인덱스에 도형 컬렉션에 삽입하며 기본 템플릿 스타일을 적용합니다. |
| [insertConnector(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate)](#insertConnector-int-int-float-float-float-float-boolean-) | 새 연결 도형을 생성하고 지정된 인덱스에 도형 컬렉션에 삽입합니다. 옵션으로 기본 템플릿 스타일을 적용할 수 있습니다. |
| [addPictureFrame(int shapeType, float x, float y, float width, float height, IPPImage image)](#addPictureFrame-int-float-float-float-float-com.aspose.slides.IPPImage-) | 지정된 이미지를 포함하는 새 그림 프레임을 생성하고 도형 컬렉션 끝에 추가합니다. |
| [insertPictureFrame(int index, int shapeType, float x, float y, float width, float height, IPPImage image)](#insertPictureFrame-int-int-float-float-float-float-com.aspose.slides.IPPImage-) | 지정된 이미지를 포함하는 새 그림 프레임을 생성하고 지정된 인덱스에 도형 컬렉션에 삽입합니다. |
| [addTable(float x, float y, double[] columnWidths, double[] rowHeights)](#addTable-float-float-double---double---) | 새 표를 생성하고 도형 컬렉션 끝에 추가합니다. |
| [insertTable(int index, float x, float y, double[] columnWidths, double[] rowHeights)](#insertTable-int-float-float-double---double---) | 새 표를 생성하고 지정된 인덱스에 도형 컬렉션에 삽입합니다. |
| [removeAt(int index)](#removeAt-int-) | 지정된 인덱스에 있는 도형을 도형 컬렉션에서 제거합니다. |
| [remove(IShape shape)](#remove-com.aspose.slides.IShape-) | 지정된 도형이 컬렉션에서 처음 나타난 것을 제거합니다. |
| [clear()](#clear--) | 도형 컬렉션의 모든 도형을 제거합니다. |
| [addClone(IShape sourceShape, float x, float y, float width, float height)](#addClone-com.aspose.slides.IShape-float-float-float-float-) | 지정된 도형의 복사본을 생성하고 도형 컬렉션 끝에 추가합니다. |
| [addClone(IShape sourceShape, float x, float y)](#addClone-com.aspose.slides.IShape-float-float-) | 지정된 도형의 복사본을 생성하고 도형 컬렉션 끝에 추가합니다. |
| [addClone(IShape sourceShape)](#addClone-com.aspose.slides.IShape-) | 지정된 도형의 복사본을 생성하고 도형 컬렉션 끝에 추가합니다. |
| [insertClone(int index, IShape sourceShape, float x, float y, float width, float height)](#insertClone-int-com.aspose.slides.IShape-float-float-float-float-) | 지정된 도형의 복사본을 생성하고 지정된 인덱스에 도형 컬렉션에 삽입합니다. |
| [insertClone(int index, IShape sourceShape, float x, float y)](#insertClone-int-com.aspose.slides.IShape-float-float-) | 지정된 도형의 복사본을 생성하고 지정된 인덱스에 도형 컬렉션에 삽입합니다. |
| [insertClone(int index, IShape sourceShape)](#insertClone-int-com.aspose.slides.IShape-) | 지정된 도형의 복사본을 생성하고 지정된 인덱스에 도형 컬렉션에 삽입합니다. |

### get_Item(int index) {#get-Item-int-}
```
public abstract IShape get_Item(int index)
```

지정된 인덱스의 요소를 가져옵니다. 읽기 전용 [IShape](../../com.aspose.slides/ishape).

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| index | int |  |

**반환:**
[IShape](../../com.aspose.slides/ishape)

### getParentGroup() {#getParentGroup--}
```
public abstract IGroupShape getParentGroup()
```

도형 컬렉션의 상위 그룹 도형 객체를 가져옵니다. 읽기 전용 [IGroupShape](../../com.aspose.slides/igroupshape).

**반환:**
[IGroupShape](../../com.aspose.slides/igroupshape)

### addChart(int type, float x, float y, float width, float height) {#addChart-int-float-float-float-float-}
```
public abstract IChart addChart(int type, float x, float y, float width, float height)
```

새 차트를 생성하고 샘플 시리즈 데이터와 설정으로 초기화한 다음 도형 컬렉션 끝에 추가합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| type | int | 추가할 차트 유형. |
| x | float | 새 차트의 x 좌표(포인트 단위). |
| y | float | 새 차트의 y 좌표(포인트 단위). |
| width | float | 차트의 너비(포인트 단위). |
| height | float | 차트의 높이(포인트 단위). |

**반환:**
[IChart](../../com.aspose.slides/ichart) - 새로 생성된 [IChart](../../com.aspose.slides/ichart).

### addChart(int type, float x, float y, float width, float height, boolean initWithSample) {#addChart-int-float-float-float-float-boolean-}
```
public abstract IChart addChart(int type, float x, float y, float width, float height, boolean initWithSample)
```

새 차트를 생성하고 샘플 시리즈 데이터와 설정으로 초기화한 다음 도형 컬렉션 끝에 추가합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| type | int | 추가할 차트 유형. |
| x | float | 새 차트의 x 좌표(포인트 단위). |
| y | float | 새 차트의 y 좌표(포인트 단위). |
| width | float | 차트의 너비(포인트 단위). |
| height | float | 차트의 높이(포인트 단위). |
| initWithSample | boolean | 새 차트를 샘플 시리즈 데이터와 설정으로 초기화하려면 true, 시리즈 없이 최소 설정만으로 차트를 생성하여 생성 속도를 높이려면 false. |

**반환:**
[IChart](../../com.aspose.slides/ichart) - 새로 생성된 [IChart](../../com.aspose.slides/ichart).

### addSmartArt(float x, float y, float width, float height, int layoutType) {#addSmartArt-float-float-float-float-int-}
```
public abstract ISmartArt addSmartArt(float x, float y, float width, float height, int layoutType)
```

SmartArt 다이어그램을 생성하고 도형 컬렉션 끝에 추가합니다.

---

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>       ISlide slide = pres.getSlides().get_Item(0);
>       ISmartArt smart = slide.getShapes().addSmartArt(0, 0, 400, 400, SmartArtLayoutType.BasicBlockList);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| x | float | 다이어그램 프레임의 x 좌표(포인트 단위). |
| y | float | 다이어그램 프레임의 y 좌표(포인트 단위). |
| width | float | 다이어그램 프레임의 너비(포인트 단위). |
| height | float | 다이어그램 프레임의 높이(포인트 단위). |
| layoutType | int | SmartArt 레이아웃 유형. |

**반환:**
[ISmartArt](../../com.aspose.slides/ismartart) - 새로 생성된 [ISmartArt](../../com.aspose.slides/ismartart).

### insertChart(int type, float x, float y, float width, float height, int index) {#insertChart-int-float-float-float-float-int-}
```
public abstract IChart insertChart(int type, float x, float y, float width, float height, int index)
```

새 차트를 생성하고 샘플 시리즈 데이터와 설정으로 초기화한 다음 지정된 인덱스에 도형 컬렉션에 삽입합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| type | int | 생성할 차트 유형. |
| x | float | 새 차트의 x 좌표(포인트 단위). |
| y | float | 새 차트의 y 좌표(포인트 단위). |
| width | float | 새 차트의 너비(포인트 단위). |
| height | float | 새 차트의 높이(포인트 단위). |
| index | int | 새 차트를 도형 컬렉션에 삽입할 0 기반 인덱스. |

**반환:**
[IChart](../../com.aspose.slides/ichart) - 새로 생성된 [IChart](../../com.aspose.slides/ichart).

### insertChart(int type, float x, float y, float width, float height, int index, boolean initWithSample) {#insertChart-int-float-float-float-float-int-boolean-}
```
public abstract IChart insertChart(int type, float x, float y, float width, float height, int index, boolean initWithSample)
```

새 차트를 생성하고 샘플 시리즈 데이터와 설정으로 초기화한 다음 지정된 인덱스에 도형 컬렉션에 삽입합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| type | int | 생성할 차트 유형. |
| x | float | 새 차트의 x 좌표(포인트 단위). |
| y | float | 새 차트의 y 좌표(포인트 단위). |
| width | float | 새 차트의 너비(포인트 단위). |
| height | float | 새 차트의 높이(포인트 단위). |
| index | int | 새 차트를 도형 컬렉션에 삽입할 0 기반 인덱스. |
| initWithSample | boolean | 새 차트를 샘플 시리즈 데이터와 설정으로 초기화하려면 true, 시리즈 없이 최소 설정만으로 차트를 생성하여 생성 속도를 높이려면 false. |
| initWithSample | boolean | 새 차트를 샘플 시리즈 데이터와 설정으로 초기화하려면 true; 시리즈 없이 최소 설정만으로 차트를 만들려면 false, 이렇게 하면 생성 속도가 빨라집니다. |

**반환값:**  
[IChart](../../com.aspose.slides/ichart) - 새로 생성된 [IChart](../../com.aspose.slides/ichart).

### addOleObjectFrame(float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo) {#addOleObjectFrame-float-float-float-float-com.aspose.slides.IOleEmbeddedDataInfo-}
```
public abstract IOleObjectFrame addOleObjectFrame(float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo)
```

새 OLE 개체 프레임을 생성하고 모양 컬렉션의 끝에 추가합니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| x | float | 새 OLE 프레임의 x 좌표(포인트 단위). |
| y | float | 새 OLE 프레임의 y 좌표(포인트 단위). |
| width | float | 새 OLE 프레임의 너비(포인트 단위). |
| height | float | 새 OLE 프레임의 높이(포인트 단위). |
| dataInfo | [IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo) | 내장된 OLE 데이터 정보([IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo)). |

**반환값:**  
[IOleObjectFrame](../../com.aspose.slides/ioleobjectframe) - 새로 생성된 [IOleObjectFrame](../../com.aspose.slides/ioleobjectframe).

### addOleObjectFrame(float x, float y, float width, float height, String className, String path) {#addOleObjectFrame-float-float-float-float-java.lang.String-java.lang.String-}
```
public abstract IOleObjectFrame addOleObjectFrame(float x, float y, float width, float height, String className, String path)
```

새 OLE 개체 프레임을 생성하고 모양 컬렉션의 끝에 추가합니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| x | float | 새 OLE 프레임의 x 좌표(포인트 단위). |
| y | float | 새 OLE 프레임의 y 좌표(포인트 단위). |
| width | float | 새 OLE 프레임의 너비(포인트 단위). |
| height | float | 새 OLE 프레임의 높이(포인트 단위). |
| className | java.lang.String | OLE 개체의 클래스 이름. |
| path | java.lang.String | 링크된 파일의 경로. 이 경로는 프레젠테이션에 그대로 저장됩니다. 상대 경로를 지정하면 다른 디렉터리에서 프레젠테이션을 열 때 파일에 접근할 수 없습니다. |

**반환값:**  
[IOleObjectFrame](../../com.aspose.slides/ioleobjectframe) - 새로 생성된 [IOleObjectFrame](../../com.aspose.slides/ioleobjectframe).

### insertOleObjectFrame(int index, float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo) {#insertOleObjectFrame-int-float-float-float-float-com.aspose.slides.IOleEmbeddedDataInfo-}
```
public abstract IOleObjectFrame insertOleObjectFrame(int index, float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo)
```

새 OLE 개체 프레임을 생성하고 지정된 인덱스에 모양 컬렉션에 삽입합니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| index | int | OLE 개체 프레임을 삽입할 0부터 시작하는 인덱스. |
| x | float | 새 OLE 프레임의 x 좌표(포인트 단위). |
| y | float | 새 OLE 프레임의 y 좌표(포인트 단위). |
| width | float | 새 OLE 프레임의 너비(포인트 단위). |
| height | float | 새 OLE 프레임의 높이(포인트 단위). |
| dataInfo | [IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo) | 내장된 OLE 데이터 정보([IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo)). |

**반환값:**  
[IOleObjectFrame](../../com.aspose.slides/ioleobjectframe) - 새로 생성된 [IOleObjectFrame](../../com.aspose.slides/ioleobjectframe).

### insertOleObjectFrame(int index, float x, float y, float width, float height, String className, String path) {#insertOleObjectFrame-int-float-float-float-float-java.lang.String-java.lang.String-}
```
public abstract IOleObjectFrame insertOleObjectFrame(int index, float x, float y, float width, float height, String className, String path)
```

새 OLE 개체 프레임을 생성하고 지정된 인덱스에 모양 컬렉션에 삽입합니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| index | int | OLE 개체 프레임을 삽입할 0부터 시작하는 인덱스. |
| x | float | 새 OLE 프레임의 x 좌표(포인트 단위). |
| y | float | 새 OLE 프레임의 y 좌표(포인트 단위). |
| width | float | 새 OLE 프레임의 너비(포인트 단위). |
| height | float | 새 OLE 프레임의 높이(포인트 단위). |
| className | java.lang.String | OLE 개체의 클래스 이름. |
| path | java.lang.String | 링크된 파일의 경로. 이 경로는 프레젠테이션에 그대로 저장됩니다. 상대 경로를 지정하면 다른 디렉터리에서 프레젠테이션을 열 때 파일에 접근할 수 없습니다. |

**반환값:**  
[IOleObjectFrame](../../com.aspose.slides/ioleobjectframe) - 새로 생성된 [IOleObjectFrame](../../com.aspose.slides/ioleobjectframe).

### addZoomFrame(float x, float y, float width, float height, ISlide slide) {#addZoomFrame-float-float-float-float-com.aspose.slides.ISlide-}
```
public abstract IZoomFrame addZoomFrame(float x, float y, float width, float height, ISlide slide)
```

새 Zoom 프레임을 생성하고 모양 컬렉션의 끝에 추가합니다.

--------------------

> ```
> This example demonstrates adding a Zoom object to the end of a collection
>  (assume that there are at least two slides in the "Presentation.pptx" presentation):
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addZoomFrame(150, 20, 50, 50, pres.getSlides().get_Item(1));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| x | float | 새 Zoom 프레임의 x 좌표(포인트 단위). |
| y | float | 새 Zoom 프레임의 y 좌표(포인트 단위). |
| width | float | 새 Zoom 프레임의 너비(포인트 단위). |
| height | float | 새 Zoom 프레임의 높이(포인트 단위). |
| slide | [ISlide](../../com.aspose.slides/islide) | [ISlide](../../com.aspose.slides/islide)을(를) 참조하는 Zoom 프레임; 이 프레젠테이션에 속해야 합니다. |

**반환값:**  
[IZoomFrame](../../com.aspose.slides/izoomframe) - 새로 생성된 [IZoomFrame](../../com.aspose.slides/izoomframe).

### addZoomFrame(float x, float y, float width, float height, ISlide slide, IPPImage image) {#addZoomFrame-float-float-float-float-com.aspose.slides.ISlide-com.aspose.slides.IPPImage-}
```
public abstract IZoomFrame addZoomFrame(float x, float y, float width, float height, ISlide slide, IPPImage image)
```

새 Zoom 프레임을 생성하고 모양 컬렉션의 끝에 추가합니다.

--------------------

> ```
> 이 예제는 컬렉션 끝에 Zoom 개체를 추가하는 방법을 보여줍니다.
>  ("Presentation.pptx" 프레젠테이션에 슬라이드가 최소 두 개 이상 있다고 가정합니다):
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      IPPImage image = pres.getImages().addImage(imageBytes);
>      IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addZoomFrame(150, 20, 50, 50, pres.getSlides().get_Item(1), image);
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| x | float | 새 Zoom 프레임의 x 좌표(포인트 단위). |
| y | float | 새 Zoom 프레임의 y 좌표(포인트 단위). |
| width | float | 새 Zoom 프레임의 너비(포인트 단위). |
| height | float | 새 Zoom 프레임의 높이(포인트 단위). |
| slide | [ISlide](../../com.aspose.slides/islide) | [ISlide](../../com.aspose.slides/islide)을(를) 참조하는 Zoom 프레임; 이 프레젠테이션에 속해야 합니다. |
| image | [IPPImage](../../com.aspose.slides/ippimage) | 참조된 슬라이드 [IPPImage](../../com.aspose.slides/ippimage)의 이미지. |

**반환값:**  
[IZoomFrame](../../com.aspose.slides/izoomframe) - 새로 생성된 [IZoomFrame](../../com.aspose.slides/izoomframe).

### insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide) {#insertZoomFrame-int-float-float-float-float-com.aspose.slides.ISlide-}
```
public abstract IZoomFrame insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide)
```

새 Zoom 프레임을 생성하고 지정된 인덱스에 모양 컬렉션에 삽입합니다.

--------------------

> ```
> This example demonstrates creation and inserting a Zoom object at the specified index of a collection
>  (assume that there are at least two slides in the "Presentation.pptx" presentation):
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().insertZoomFrame(2, 150, 20, 50, 50, pres.getSlides().get_Item(1));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| index | int | Zoom 프레임을 삽입할 0부터 시작하는 인덱스. |
| x | float | 새 Zoom 프레임의 x 좌표(포인트 단위). |
| y | float | 새 Zoom 프레임의 y 좌표(포인트 단위). |
| width | float | 새 Zoom 프레임의 너비(포인트 단위). |
| height | float | 새 Zoom 프레임의 높이(포인트 단위). |
| slide | [ISlide](../../com.aspose.slides/islide) | [ISlide](../../com.aspose.slides/islide)을(를) 참조하는 Zoom 프레임. |

**반환값:**  
[IZoomFrame](../../com.aspose.slides/izoomframe) - 새로 생성된 [IZoomFrame](../../com.aspose.slides/izoomframe).

### insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide, IPPImage image) {#insertZoomFrame-int-float-float-float-float-com.aspose.slides.ISlide-com.aspose.slides.IPPImage-}
```
public abstract IZoomFrame insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide, IPPImage image)
```

새 Zoom 프레임을 생성하고 지정된 인덱스에 모양 컬렉션에 삽입합니다.

--------------------

> ```
> 이 예제는 컬렉션의 지정된 인덱스에 Zoom 개체를 생성하고 삽입하는 방법을 보여줍니다
>  ("Presentation.pptx" 프레젠테이션에 슬라이드가 최소 두 개 이상 있다고 가정합니다):
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      IPPImage image = pres.getImages().addImage(imageBytes);
>      IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().insertZoomFrame(2, 150, 20, 50, 50, pres.getSlides().get_Item(1), image);
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| index | int | Zoom 프레임을 삽입할 0부터 시작하는 인덱스. |
| x | float | 새 Zoom 프레임의 x 좌표(포인트 단위). |
| y | float | 새 Zoom 프레임의 y 좌표(포인트 단위). |
| width | float | 새 Zoom 프레임의 너비(포인트 단위). |
| height | float | 새 Zoom 프레임의 높이(포인트 단위). |
| slide | [ISlide](../../com.aspose.slides/islide) | [ISlide](../../com.aspose.slides/islide)을(를) 참조하는 Zoom 프레임. |
| image | [IPPImage](../../com.aspose.slides/ippimage) | 참조된 슬라이드 [IPPImage](../../com.aspose.slides/ippimage)의 이미지. |

**반환값:**  
[IZoomFrame](../../com.aspose.slides/izoomframe) - 새로 생성된 [IZoomFrame](../../com.aspose.slides/izoomframe).

### addSectionZoomFrame(float x, float y, float width, float height, ISection section) {#addSectionZoomFrame-float-float-float-float-com.aspose.slides.ISection-}
```
public abstract ISectionZoomFrame addSectionZoomFrame(float x, float y, float width, float height, ISection section)
```

새 Section Zoom 프레임을 생성하고 모양 컬렉션의 끝에 추가합니다.

--------------------

> ```
> 이 예제는 컬렉션 끝에 Section Zoom 개체를 추가하는 방법을 보여줍니다.
>  ("Presentation.pptx" 프레젠테이션에 섹션이 최소 두 개 이상 있다고 가정합니다):
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      ISectionZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addSectionZoomFrame(150, 20, 50, 50, pres.getSections().get_Item(1));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| x | float | 새 Section Zoom 프레임의 x 좌표(포인트 단위). |
| y | float | 새 Section Zoom 프레임의 y 좌표(포인트 단위). |
| width | float | 새 Section Zoom 프레임의 너비(포인트 단위). |
| height | float | 새 Section Zoom 프레임의 높이(포인트 단위). |
| section | [ISection](../../com.aspose.slides/isection) | [ISection](../../com.aspose.slides/isection)을(를) 참조하는 Section Zoom 프레임; 이 프레젠테이션에 속하고 최소 하나의 슬라이드를 포함해야 합니다. |

**반환값:**  
[ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe) - 새로 생성된 [ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe).

### addSectionZoomFrame(float x, float y, float width, float height, ISection section, IPPImage image) {#addSectionZoomFrame-float-float-float-float-com.aspose.slides.ISection-com.aspose.slides.IPPImage-}
```
public abstract ISectionZoomFrame addSectionZoomFrame(float x, float y, float width, float height, ISection section, IPPImage image)
```

새 Section Zoom 프레임을 생성하고 모양 컬렉션의 끝에 추가합니다.

--------------------

> ```
> 이 예제는 컬렉션 끝에 Section Zoom 개체를 추가하는 방법을 보여줍니다.
>  ("Presentation.pptx" 프레젠테이션에 섹션이 최소 두 개 이상 있다고 가정합니다):
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      IPPImage image = pres.getImages().addImage(Files.readAllBytes(Paths.get("image.png")));
>      ISectionZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addSectionZoomFrame(150, 20, 50, 50, pres.getSections().get_Item(1), image);
>  } catch (IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| x | float | 새 Section Zoom 프레임의 x 좌표(포인트 단위). |
| y | float | 새 Section Zoom 프레임의 y 좌표(포인트 단위). |
| width | float | 새 Section Zoom 프레임의 너비(포인트 단위). |
| height | float | 새 Section Zoom 프레임의 높이(포인트 단위). |
| section | [ISection](../../com.aspose.slides/isection) | [ISection](../../com.aspose.slides/isection)을(를) 참조하는 Section Zoom 프레임; 이 프레젠테이션에 속하고 최소 하나의 슬라이드를 포함해야 합니다. |
| image | [IPPImage](../../com.aspose.slides/ippimage) | [IPPImage](../../com.aspose.slides/ippimage)를 표시하기 위한 이미지. |

**반환값:**  
[ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe) - 새로 생성된 [ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe).

### insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section) {#insertSectionZoomFrame-int-float-float-float-float-com.aspose.slides.ISection-}
```
public abstract ISectionZoomFrame insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section)
```

새 Section Zoom 프레임을 생성하고 지정된 인덱스에 모양 컬렉션에 삽입합니다.

--------------------

> ```
> 이 예제는 컬렉션의 지정된 인덱스에 Section Zoom 개체를 생성하고 삽입하는 방법을 보여줍니다
>  ("Presentation.pptx" 프레젠테이션에 섹션이 최소 두 개 이상 있다고 가정합니다):
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      ISectionZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().insertSectionZoomFrame(2, 150, 20, 50, 50, pres.getSections().get_Item(1));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| index | int | Section Zoom 프레임을 삽입할 0부터 시작하는 인덱스. |
| x | float | 새 Section Zoom 프레임의 x 좌표(포인트 단위). |
| y | float | 새 Section Zoom 프레임의 y 좌표(포인트 단위). |
| width | float | 새 Section Zoom 프레임의 너비(포인트 단위). |
| height | float | 새 Section Zoom 프레임의 높이(포인트 단위). |
| section | [ISection](../../com.aspose.slides/isection) | [ISection](../../com.aspose.slides/isection)을(를) 참조하는 Section Zoom 프레임; 이 프레젠테이션에 속하고 최소 하나의 슬라이드를 포함해야 합니다. |

**반환값:**  
[ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe) - 새로 생성된 [ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe).

### insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section, IPPImage image) {#insertSectionZoomFrame-int-float-float-float-float-com.aspose.slides.ISection-com.aspose.slides.IPPImage-}
```
public abstract ISectionZoomFrame insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section, IPPImage image)
```

새 Section Zoom 프레임을 생성하고 지정된 인덱스에 모양 컬렉션에 삽입합니다.

--------------------

> ```
> 이 예제는 컬렉션의 지정된 인덱스에 Section Zoom 개체를 생성하고 삽입하는 방법을 보여줍니다
>  ("Presentation.pptx" 프레젠테이션에 섹션이 최소 두 개 이상 있다고 가정합니다):
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      IPPImage image = pres.getImages().addImage(Files.readAllBytes(Paths.get("image.png")));
>      ISectionZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().insertSectionZoomFrame(2, 150, 20, 50, 50, pres.getSections().get_Item(1), image);
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| index | int | Section Zoom 프레임을 삽입할 0부터 시작하는 인덱스. |
| x | float | 새 Section Zoom 프레임의 x 좌표(포인트 단위). |
| y | float | 새 Section Zoom 프레임의 y 좌표(포인트 단위). |
| width | float | 새 Section Zoom 프레임의 너비(포인트 단위). |
| height | float | 새 Section Zoom 프레임의 높이(포인트 단위). |
| section | [ISection](../../com.aspose.slides/isection) | [ISection](../../com.aspose.slides/isection)을(를) 참조하는 Section Zoom 프레임; 이 프레젠테이션에 속하고 최소 하나의 슬라이드를 포함해야 합니다. |
| image | [IPPImage](../../com.aspose.slides/ippimage) | Section Zoom 프레임 내에 표시할 이미지. |

**반환값:**  
[ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe) - 새로 생성된 [ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe).

### addSummaryZoomFrame(float x, float y, float width, float height) {#addSummaryZoomFrame-float-float-float-float-}
```
public abstract ISummaryZoomFrame addSummaryZoomFrame(float x, float y, float width, float height)
```

새 Summary Zoom 프레임을 생성하고 모양 컬렉션의 끝에 추가합니다.

--------------------

> ```
> 이 예제는 컬렉션 끝에 Summary Zoom 개체를 추가하는 방법을 보여줍니다.
>  ("Presentation.pptx" 프레젠테이션에 섹션이 최소 두 개 이상 있다고 가정합니다):
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      ISummaryZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addSummaryZoomFrame(150, 20, 500, 250);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| x | float | 새 Summary Zoom 프레임의 x 좌표(포인트 단위). |
| y | float | 새 Summary Zoom 프레임의 y 좌표(포인트 단위). |
| width | float | 새 Summary Zoom 프레임의 너비(포인트 단위). |
| height | float | 새 Summary Zoom 프레임의 높이(포인트 단위). |
이 메서드는 프레젠테이션의 모든 섹션에 대한 summary 링크를 집계하는 Summary Zoom frame을 생성합니다. |

**반환값:**
[ISummaryZoomFrame](../../com.aspose.slides/isummaryzoomframe) - 새로 생성된 [ISummaryZoomFrame](../../com.aspose.slides/isummaryzoomframe).
### insertSummaryZoomFrame(int index, float x, float y, float width, float height) {#insertSummaryZoomFrame-int-float-float-float-float-}
```
public abstract ISummaryZoomFrame insertSummaryZoomFrame(int index, float x, float y, float width, float height)
```


새 Summary Zoom frame을 생성하고 지정된 인덱스에 shape 컬렉션에 삽입합니다.

--------------------

> ```
> 이 예제는 컬렉션의 지정된 인덱스에 Summary Zoom 개체를 생성하고 삽입하는 방법을 보여줍니다
>  ("Presentation.pptx" 프레젠테이션에 섹션이 최소 두 개 이상 있다고 가정합니다):
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      ISummaryZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().insertSummaryZoomFrame(2, 150, 20, 50, 50);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| index | int | Summary Zoom frame을 삽입할 zero-based 인덱스. |
| x | float | 새 Summary Zoom frame의 x 좌표(포인트 단위). |
| y | float | 새 Summary Zoom frame의 y 좌표(포인트 단위). |
| width | float | 새 Summary Zoom frame의 너비(포인트 단위). |
| height | float | 새 Summary Zoom frame의 높이(포인트 단위). |

--------------------

이 메서드는 프레젠테이션의 모든 섹션에 대한 summary 링크를 집계하는 Summary Zoom frame을 생성합니다. |

**반환값:**
[ISummaryZoomFrame](../../com.aspose.slides/isummaryzoomframe) - 새로 생성된 [ISummaryZoomFrame](../../com.aspose.slides/isummaryzoomframe).
### addVideoFrame(float x, float y, float width, float height, String fname) {#addVideoFrame-float-float-float-float-java.lang.String-}
```
public abstract IVideoFrame addVideoFrame(float x, float y, float width, float height, String fname)
```


새 video frame을 생성하고 shape 컬렉션 끝에 추가합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| x | float | 새 video frame의 x 좌표(포인트 단위). |
| y | float | 새 video frame의 y 좌표(포인트 단위). |
| width | float | 새 video frame의 너비(포인트 단위). |
| height | float | 새 video frame의 높이(포인트 단위). |
| fname | java.lang.String | 삽입할 비디오 파일의 경로나 이름. |

**반환값:**
[IVideoFrame](../../com.aspose.slides/ivideoframe) - 새로 생성된 [IVideoFrame](../../com.aspose.slides/ivideoframe).
### addVideoFrame(float x, float y, float width, float height, IVideo video) {#addVideoFrame-float-float-float-float-com.aspose.slides.IVideo-}
```
public abstract IVideoFrame addVideoFrame(float x, float y, float width, float height, String fname)
```


새 video frame을 생성하고 shape 컬렉션 끝에 추가합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| x | float | 새 video frame의 x 좌표(포인트 단위). |
| y | float | 새 video frame의 y 좌표(포인트 단위). |
| width | float | 새 video frame의 너비(포인트 단위). |
| height | float | 새 video frame의 높이(포인트 단위). |
| video | [IVideo](../../com.aspose.slides/ivideo) | video frame에 삽입할 [IVideo](../../com.aspose.slides/ivideo). |

**반환값:**
[IVideoFrame](../../com.aspose.slides/ivideoframe) - 새로 생성된 [IVideoFrame](../../com.aspose.slides/ivideoframe).
### insertVideoFrame(int index, float x, float y, float width, float height, String fname) {#insertVideoFrame-int-float-float-float-float-java.lang.String-}
```
public abstract IVideoFrame insertVideoFrame(int index, float x, float y, float width, float height, String fname)
```


새 video frame을 생성하고 지정된 인덱스에 shape 컬렉션에 삽입합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| index | int | video frame을 삽입할 zero-based 인덱스. |
| x | float | 새 video frame의 x 좌표(포인트 단위). |
| y | float | 새 video frame의 y 좌표(포인트 단위). |
| width | float | 새 video frame의 너비(포인트 단위). |
| height | float | 새 video frame의 높이(포인트 단위). |
| fname | java.lang.String | 삽입할 비디오 파일의 경로나 이름. |

**반환값:**
[IVideoFrame](../../com.aspose.slides/ivideoframe) - 새로 생성된 [IVideoFrame](../../com.aspose.slides/ivideoframe).
### addAudioFrameCD(float x, float y, float width, float height) {#addAudioFrameCD-float-float-float-float-}
```
public abstract IAudioFrame addAudioFrameCD(float x, float y, float width, float height)
```


새 audio frame을 CD 트랙에 연결하고 shape 컬렉션 끝에 추가합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| x | float | 새 audio frame의 x 좌표(포인트 단위). |
| y | float | 새 audio frame의 y 좌표(포인트 단위). |
| width | float | 새 audio frame의 너비(포인트 단위). |
| height | float | 새 audio frame의 높이(포인트 단위). |

**반환값:**
[IAudioFrame](../../com.aspose.slides/iaudioframe) - 새로 생성된 [IAudioFrame](../../com.aspose.slides/iaudioframe).
### insertAudioFrameCD(int index, float x, float y, float width, float height) {#insertAudioFrameCD-int-float-float-float-float-}
```
public abstract IAudioFrame insertAudioFrameCD(int index, float x, float y, float width, float height)
```


새 audio frame을 CD 트랙에 연결하고 지정된 인덱스에 shape 컬렉션에 삽입합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| index | int | audio frame을 삽입할 zero-based 인덱스. |
| x | float | 새 audio frame의 x 좌표(포인트 단위). |
| y | float | 새 audio frame의 y 좌표(포인트 단위). |
| width | float | 새 audio frame의 너비(포인트 단위). |
| height | float | 새 audio frame의 높이(포인트 단위). |

**반환값:**
[IAudioFrame](../../com.aspose.slides/iaudioframe) - 새로 생성된 [IAudioFrame](../../com.aspose.slides/iaudioframe).
### addAudioFrameLinked(float x, float y, float width, float height, String fname) {#addAudioFrameLinked-float-float-float-float-java.lang.String-}
```
public abstract IAudioFrame addAudioFrameLinked(float x, float y, float width, float height, String fname)
```


새 audio frame을 외부 오디오 파일에 연결하고 shape 컬렉션 끝에 추가합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| x | float | 새 audio frame의 x 좌표(포인트 단위). |
| y | float | 새 audio frame의 y 좌표(포인트 단위). |
| width | float | 새 audio frame의 너비(포인트 단위). |
| height | float | 새 audio frame의 높이(포인트 단위). |
| fname | java.lang.String | 연결할 외부 오디오 파일의 경로나 이름. |

**반환값:**
[IAudioFrame](../../com.aspose.slides/iaudioframe) - 새로 생성된 [IAudioFrame](../../com.aspose.slides/iaudioframe).
### insertAudioFrameLinked(int index, float x, float y, float width, float height, String fname) {#insertAudioFrameLinked-int-float-float-float-float-java.lang.String-}
```
public abstract IAudioFrame insertAudioFrameLinked(int index, float x, float y, float width, float height, String fname)
```


새 audio frame을 외부 오디오 파일에 연결하고 지정된 인덱스에 shape 컬렉션에 삽입합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| index | int | audio frame을 삽입할 zero-based 인덱스. |
| x | float | 새 audio frame의 x 좌표(포인트 단위). |
| y | float | 새 audio frame의 y 좌표(포인트 단위). |
| width | float | 새 audio frame의 너비(포인트 단위). |
| height | float | 새 audio frame의 높이(포인트 단위). |
| fname | java.lang.String | 연결할 외부 오디오 파일의 경로나 이름. |

**반환값:**
[IAudioFrame](../../com.aspose.slides/iaudioframe) - 새로 생성된 [IAudioFrame](../../com.aspose.slides/iaudioframe).
### addAudioFrameEmbedded(float x, float y, float width, float height, InputStream audio_stream) {#addAudioFrameEmbedded-float-float-float-float-java.io.InputStream-}
```
public abstract IAudioFrame addAudioFrameEmbedded(float x, float y, float width, float height, InputStream audio_stream)
```


새 audio frame을 생성하고 임베드된 WAV 파일을 사용해 shape 컬렉션 끝에 추가합니다. 임베드된 오디오가 Presentation.Audios 컬렉션에 추가됩니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| x | float | 새 audio frame의 x 좌표(포인트 단위). |
| y | float | 새 audio frame의 y 좌표(포인트 단위). |
| width | float | 새 audio frame의 너비(포인트 단위). |
| height | float | 새 audio frame의 높이(포인트 단위). |
| audio_stream | java.io.InputStream | 임베드할 WAV 오디오 데이터를 포함하는 입력 스트림. |

**반환값:**
[IAudioFrame](../../com.aspose.slides/iaudioframe) - 새로 생성된 [IAudioFrame](../../com.aspose.slides/iaudioframe).
### addAudioFrameEmbedded(float x, float y, float width, float height, IAudio audio) {#addAudioFrameEmbedded-float-float-float-float-com.aspose.slides.IAudio-}
```
public abstract IAudioFrame addAudioFrameEmbedded(float x, float y, float width, float height, IAudio audio)
```


새 audio frame을 생성하고 Presentation.Audios 목록에 있는 기존 audio 객체를 사용해 shape 컬렉션 끝에 추가합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| x | float | 새 audio frame의 x 좌표(포인트 단위). |
| y | float | 새 audio frame의 y 좌표(포인트 단위). |
| width | float | 새 audio frame의 너비(포인트 단위). |
| height | float | 새 audio frame의 높이(포인트 단위). |
| audio | [IAudio](../../com.aspose.slides/iaudio) | Presentation.Audios 컬렉션에서 가져온 [IAudio](../../com.aspose.slides/iaudio) 인스턴스. |

**반환값:**
[IAudioFrame](../../com.aspose.slides/iaudioframe) - 새로 생성된 [IAudioFrame](../../com.aspose.slides/iaudioframe).
### insertAudioFrameEmbedded(int index, float x, float y, float width, float height, InputStream audio_stream) {#insertAudioFrameEmbedded-int-float-float-float-float-java.io.InputStream-}
```
public abstract IAudioFrame insertAudioFrameEmbedded(int index, float x, float y, float width, float height, InputStream audio_stream)
```


임베드된 WAV 파일을 포함하는 새 audio frame을 생성하고 지정된 인덱스에 shape 컬렉션에 삽입합니다. 임베드된 오디오가 Presentation.Audios 컬렉션에 추가됩니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| index | int | audio frame을 삽입할 zero-based 인덱스. |
| x | float | 새 audio frame의 x 좌표(포인트 단위). |
| y | float | 새 audio frame의 y 좌표(포인트 단위). |
| width | float | 새 audio frame의 너비(포인트 단위). |
| height | float | 새 audio frame의 높이(포인트 단위). |
| audio_stream | java.io.InputStream | 임베드할 WAV 오디오 데이터를 포함하는 입력 스트림. |

**반환값:**
[IAudioFrame](../../com.aspose.slides/iaudioframe) - 새로 생성된 [IAudioFrame](../../com.aspose.slides/iaudioframe).
### insertAudioFrameEmbedded(int index, float x, float y, float width, float height, IAudio audio) {#insertAudioFrameEmbedded-int-float-float-float-float-com.aspose.slides.IAudio-}
```
public abstract IAudioFrame insertAudioFrameEmbedded(int index, float x, float y, float width, float height, IAudio audio)
```


기존 audio 객체를 사용해 지정된 인덱스에 새 audio frame을 삽입합니다. 해당 audio 객체는 Presentation.Audios 컬렉션에 포함됩니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| index | int | audio frame을 삽입할 zero-based 인덱스. |
| x | float | 새 audio frame의 x 좌표(포인트 단위). |
| y | float | 새 audio frame의 y 좌표(포인트 단위). |
| width | float | 새 audio frame의 너비(포인트 단위). |
| height | float | 새 audio frame의 높이(포인트 단위). |
| audio | [IAudio](../../com.aspose.slides/iaudio) | Presentation.Audios 컬렉션에서 가져온 [IAudio](../../com.aspose.slides/iaudio) 인스턴스. |

**반환값:**
[IAudioFrame](../../com.aspose.slides/iaudioframe) - 새로 생성된 [IAudioFrame](../../com.aspose.slides/iaudioframe).
### indexOf(IShape shape) {#indexOf-com.aspose.slides.IShape-}
```
public abstract int indexOf(IShape shape)
```


컬렉션에서 지정된 shape이 처음 나타나는 zero-based 인덱스를 반환합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| shape | [IShape](../../com.aspose.slides/ishape) | 컬렉션에서 찾을 shape. |

**반환값:**
int - 찾은 경우 shape 컬렉션에서 shape이 처음 나타나는 zero-based 인덱스; 찾지 못한 경우 \\u20131.
### toArray() {#toArray--}
```
public abstract IShape[] toArray()
```


모든 shape을 포함하는 배열을 생성하고 반환합니다.

**반환값:**
com.aspose.slides.IShape[] - [IShape](../../com.aspose.slides/ishape) 객체 배열.
### toArray(int startIndex, int count) {#toArray-int-int-}
```
public abstract IShape[] toArray(int startIndex, int count)
```


지정된 범위에 포함된 shape을 모두 포함하는 배열을 생성하고 반환합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| startIndex | int | 반환할 첫 번째 shape의 인덱스. |
| count | int | 반환할 shape의 개수. |

**반환값:**
com.aspose.slides.IShape[] - [IShape](../../com.aspose.slides/ishape) 객체 배열.
### reorder(int index, IShape shape) {#reorder-int-com.aspose.slides.IShape-}
```
public abstract void reorder(int index, IShape shape)
```


지정된 shape을 shape 컬렉션 내 새로운 위치로 이동합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| index | int | shape이 배치될 zero-based 대상 인덱스. |
| shape | [IShape](../../com.aspose.slides/ishape) | 컬렉션 내에서 이동할 [IShape](../../com.aspose.slides/ishape). |

### reorder(int index, IShape[] shapes) {#reorder-int-com.aspose.slides.IShape...-}
```
public abstract void reorder(int index, IShape[] shapes)
```


지정된 shape들을 shape 컬렉션 내에서 이동시키며, 지정된 인덱스부터 순차적으로 배치합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| index | int | 첫 번째 지정된 shape이 배치될 zero-based 대상 인덱스; 이후 shape은 제공된 순서대로 이어 배치됩니다. |
| shapes | [IShape\[\]](../../com.aspose.slides/ishape) | 컬렉션 내에서 이동할 하나 이상의 [IShape](../../com.aspose.slides/ishape) 인스턴스. |

### addAutoShape(int shapeType, float x, float y, float width, float height) {#addAutoShape-int-float-float-float-float-}
```
public abstract IAutoShape addAutoShape(int shapeType, float x, float y, float width, float height)
```


기본 서식이 적용된 새 auto shape을 생성하고 shape 컬렉션 끝에 추가합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| shapeType | int | 추가할 auto shape의 [ShapeType](../../com.aspose.slides/shapetype).
| x | float | 형상 프레임의 x 좌표(포인트). |
| y | float | 형상 프레임의 y 좌표(포인트). |
| width | float | 형상 프레임의 너비(포인트). |
| height | float | 형상 프레임의 높이(포인트). |

**반환값:**
[IAutoShape](../../com.aspose.slides/iautoshape) - 새로 생성된 [IAutoShape](../../com.aspose.slides/iautoshape).
### addAutoShape(int shapeType, float x, float y, float width, float height, boolean createFromTemplate) {#addAutoShape-int-float-float-float-float-boolean-}
```
public abstract IAutoShape addAutoShape(int shapeType, float x, float y, float width, float height, boolean createFromTemplate)
```

새 자동 모양을 생성하고 모양 컬렉션 끝에 추가합니다. 선택적으로 기본 템플릿 서식으로 초기화할 수 있습니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| shapeType | int | 추가할 자동 모양의 [ShapeType](../../com.aspose.slides/shapetype). |
| x | float | 형상 프레임의 x 좌표(포인트). |
| y | float | 형상 프레임의 y 좌표(포인트). |
| width | float | 형상 프레임의 너비(포인트). |
| height | float | 형상 프레임의 높이(포인트). |
| createFromTemplate | boolean | 새 모양에 기본 템플릿 스타일(단순 스타일, 중앙 정렬 텍스트, 비어 있지 않은 이름)을 적용하려면 true, 모든 속성을 기본값으로 설정한 모양을 만들려면 false. |

**반환값:**
[IAutoShape](../../com.aspose.slides/iautoshape) - 새로 생성된 [IAutoShape](../../com.aspose.slides/iautoshape).
### addMathShape(float x, float y, float width, float height) {#addMathShape-float-float-float-float-}
```
public abstract IAutoShape addMathShape(float x, float y, float width, float height)
```

수학 콘텐츠를 담는 새로운 사각형 자동 모양을 생성하고 모양 컬렉션 끝에 추가합니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| x | float | 형상 프레임의 x 좌표(포인트). |
| y | float | 형상 프레임의 y 좌표(포인트). |
| width | float | 형상 프레임의 너비(포인트). |
| height | float | 형상 프레임의 높이(포인트). |

**반환값:**
[IAutoShape](../../com.aspose.slides/iautoshape) - 새로 생성된 [IAutoShape](../../com.aspose.slides/iautoshape).
### insertAutoShape(int index, int shapeType, float x, float y, float width, float height) {#insertAutoShape-int-int-float-float-float-float-}
```
public abstract IAutoShape insertAutoShape(int index, int shapeType, float x, float y, float width, float height)
```

새 자동 모양을 생성하고 지정된 인덱스에 삽입하며 기본 템플릿 서식을 적용합니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| index | int | 새 자동 모양을 삽입할 0 기반 인덱스. |
| shapeType | int | 삽입할 자동 모양의 [ShapeType](../../com.aspose.slides/shapetype). |
| x | float | 형상 프레임의 x 좌표(포인트). |
| y | float | 형상 프레임의 y 좌표(포인트). |
| width | float | 형상 프레임의 너비(포인트). |
| height | float | 형상 프레임의 높이(포인트). |

**반환값:**
[IAutoShape](../../com.aspose.slides/iautoshape) - 새로 생성된 [IAutoShape](../../com.aspose.slides/iautoshape).
### insertAutoShape(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate) {#insertAutoShape-int-int-float-float-float-float-boolean-}
```
public abstract IAutoShape insertAutoShape(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate)
```

새 자동 모양을 생성하고 지정된 인덱스에 삽입하며, 필요한 경우 기본 템플릿 스타일로 초기화합니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| index | int | 자동 모양을 삽입할 0 기반 인덱스. |
| shapeType | int | 삽입할 자동 모양의 [ShapeType](../../com.aspose.slides/shapetype). |
| x | float | 형상 프레임의 x 좌표(포인트). |
| y | float | 형상 프레임의 y 좌표(포인트). |
| width | float | 형상 프레임의 너비(포인트). |
| height | float | 형상 프레임의 높이(포인트). |
| createFromTemplate | boolean | 기본 템플릿 스타일(비어 있지 않은 이름, 단순 스타일, 중앙 정렬 텍스트)을 적용하려면 true, 모든 속성을 기본값으로 설정한 모양을 만들려면 false. |

**반환값:**
[IAutoShape](../../com.aspose.slides/iautoshape) - 새로 생성된 [IAutoShape](../../com.aspose.slides/iautoshape).
### addGroupShape() {#addGroupShape--}
```
public abstract IGroupShape addGroupShape()
```

새 빈 그룹 모양을 생성하고 모양 컬렉션 끝에 추가합니다. 그룹의 프레임은 추가된 모든 모양에 맞게 자동으로 조정됩니다.

**반환값:**
[IGroupShape](../../com.aspose.slides/igroupshape) - 새로 생성된 [IGroupShape](../../com.aspose.slides/igroupshape).
### addGroupShape(ISvgImage svgImage, float x, float y, float width, float height) {#addGroupShape-com.aspose.slides.ISvgImage-float-float-float-float-}
```
public abstract IGroupShape addGroupShape(ISvgImage svgImage, float x, float y, float width, float height)
```

새 그룹 모양을 생성하고 지정된 SVG 이미지를 개별 모양으로 변환한 뒤, 결과 그룹을 모양 컬렉션 끝에 추가합니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| svgImage | [ISvgImage](../../com.aspose.slides/isvgimage) | [ISvgImage](../../com.aspose.slides/isvgimage)에 포함된 벡터 콘텐츠를 모양으로 변환합니다. |
| x | float | 그룹 프레임의 x 좌표(포인트). |
| y | float | 그룹 프레임의 y 좌표(포인트). |
| width | float | 그룹 프레임의 너비(포인트). |
| height | float | 그룹 프레임의 높이(포인트). |

**반환값:**
[IGroupShape](../../com.aspose.slides/igroupshape) - 새로 생성된 [IGroupShape](../../com.aspose.slides/igroupshape).
### insertGroupShape(int index) {#insertGroupShape-int-}
```
public abstract IGroupShape insertGroupShape(int index)
```

새 빈 그룹 모양을 생성하고 지정된 인덱스에 삽입합니다. 그룹의 프레임은 추가된 모든 모양에 맞게 자동으로 조정됩니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| index | int | 그룹 모양을 삽입할 0 기반 인덱스. |

**반환값:**
[IGroupShape](../../com.aspose.slides/igroupshape) - 새로 생성된 [IGroupShape](../../com.aspose.slides/igroupshape).
### addConnector(int shapeType, float x, float y, float width, float height) {#addConnector-int-float-float-float-float-}
```
public abstract IConnector addConnector(int shapeType, float x, float y, float width, float height)
```

기본 템플릿 스타일이 적용된 새로운 커넥터 모양을 생성하고 모양 컬렉션 끝에 추가합니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| shapeType | int | 추가할 커넥터 모양의 [ShapeType](../../com.aspose.slides/shapetype). |
| x | float | 커넥터 프레임의 x 좌표(포인트). |
| y | float | 커넥터 프레임의 y 좌표(포인트). |
| width | float | 커넥터 프레임의 너비(포인트). |
| height | float | 커넥터 프레임의 높이(포인트). |

**반환값:**
[IConnector](../../com.aspose.slides/iconnector) - 새로 생성된 [IConnector](../../com.aspose.slides/iconnector).
### addConnector(int shapeType, float x, float y, float width, float height, boolean createFromTemplate) {#addConnector-int-float-float-float-float-boolean-}
```
public abstract IConnector addConnector(int shapeType, float x, float y, float width, float height, boolean createFromTemplate)
```

새 커넥터 모양을 생성하고 모양 컬렉션 끝에 추가하며, 필요한 경우 기본 템플릿 스타일을 적용합니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| shapeType | int | 생성할 커넥터 모양의 [ShapeType](../../com.aspose.slides/shapetype). |
| x | float | 커넥터 프레임의 x 좌표(포인트). |
| y | float | 커넥터 프레임의 y 좌표(포인트). |
| width | float | 커넥터 프레임의 너비(포인트). |
| height | float | 커넥터 프레임의 높이(포인트). |
| createFromTemplate | boolean | 기본 템플릿 스타일(비어 있지 않은 이름, 단순 스타일)을 적용하려면 true, 기본 속성 값으로 커넥터를 만들려면 false. |

**반환값:**
[IConnector](../../com.aspose.slides/iconnector) - 새로 생성된 [IConnector](../../com.aspose.slides/iconnector).
### insertConnector(int index, int shapeType, float x, float y, float width, float height) {#insertConnector-int-int-float-float-float-float-}
```
public abstract IConnector insertConnector(int index, int shapeType, float x, float y, float width, float height)
```

새 커넥터 모양을 생성하고 지정된 인덱스에 삽입하며 기본 템플릿 스타일을 적용합니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| index | int | 커넥터 모양을 삽입할 0 기반 인덱스. |
| shapeType | int | 삽입할 커넥터 모양의 [ShapeType](../../com.aspose.slides/shapetype). |
| x | float | 커넥터 프레임의 x 좌표(포인트). |
| y | float | 커넥터 프레임의 y 좌표(포인트). |
| width | float | 커넥터 프레임의 너비(포인트). |
| height | float | 커넥터 프레임의 높이(포인트). |

**반환값:**
[IConnector](../../com.aspose.slides/iconnector) - 새로 생성된 [IConnector](../../com.aspose.slides/iconnector).
### insertConnector(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate) {#insertConnector-int-int-float-float-float-float-boolean-}
```
public abstract IConnector insertConnector(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate)
```

새 커넥터 모양을 생성하고 지정된 인덱스에 삽입하며, 필요한 경우 기본 템플릿 스타일을 적용합니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| index | int | 커넥터 모양을 삽입할 0 기반 인덱스. |
| shapeType | int | 삽입할 커넥터 모양의 [ShapeType](../../com.aspose.slides/shapetype). |
| x | float | 커넥터 프레임의 x 좌표(포인트). |
| y | float | 커넥터 프레임의 y 좌표(포인트). |
| width | float | 커넥터 프레임의 너비(포인트). |
| height | float | 커넥터 프레임의 높이(포인트). |
| createFromTemplate | boolean | 기본 템플릿 스타일(비어 있지 않은 이름, 단순 스타일)을 적용하려면 true, 기본 속성 값으로 커넥터를 만들려면 false. |

**반환값:**
[IConnector](../../com.aspose.slides/iconnector) - 새로 생성된 [IConnector](../../com.aspose.slides/iconnector).
### addPictureFrame(int shapeType, float x, float y, float width, float height, IPPImage image) {#addPictureFrame-int-float-float-float-float-com.aspose.slides.IPPImage-}
```
public abstract IPictureFrame addPictureFrame(int shapeType, float x, float y, float width, float height, IPPImage image)
```

지정된 이미지를 포함하는 새 그림 프레임을 생성하고 모양 컬렉션 끝에 추가합니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| shapeType | int | [ShapeType](../../com.aspose.slides/shapetype)에 포함된 모양 유형을 지정합니다. 단, 모든 종류의 선은 제외합니다:<br>ShapeType.Line,<br>ShapeType.StraightConnector1,<br>ShapeType.BentConnector2,<br>ShapeType.BentConnector3,<br>ShapeType.BentConnector4,<br>ShapeType.BentConnector5,<br>ShapeType.CurvedConnector2,<br>ShapeType.CurvedConnector3,<br>ShapeType.CurvedConnector4,<br>ShapeType.CurvedConnector5. |
| x | float | 그림 프레임의 x 좌표(포인트). |
| y | float | 그림 프레임의 y 좌표(포인트). |
| width | float | 그림 프레임의 너비(포인트). |
| height | float | 그림 프레임의 높이(포인트). |
| image | [IPPImage](../../com.aspose.slides/ippimage) | 그림 프레임에 표시할 [IPPImage](../../com.aspose.slides/ippimage). |

**반환값:**
[IPictureFrame](../../com.aspose.slides/ipictureframe) - 새로 생성된 [IPictureFrame](../../com.aspose.slides/ipictureframe).
### insertPictureFrame(int index, int shapeType, float x, float y, float width, float height, IPPImage image) {#insertPictureFrame-int-int-float-float-float-float-com.aspose.slides.IPPImage-}
```
public abstract IPictureFrame insertPictureFrame(int index, int shapeType, float x, float y, float width, float height, IPPImage image)
```

지정된 이미지를 포함하는 새 그림 프레임을 생성하고 지정된 인덱스에 삽입합니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| index | int | 그림 프레임을 삽입할 0 기반 인덱스. |
| shapeType | int | [ShapeType](../../com.aspose.slides/shapetype)에 포함된 모양 유형을 지정합니다. 단, 모든 종류의 선은 제외합니다:<br>ShapeType.Line,<br>ShapeType.StraightConnector1,<br>ShapeType.BentConnector2,<br>ShapeType.BentConnector3,<br>ShapeType.BentConnector4,<br>ShapeType.BentConnector5,<br>ShapeType.CurvedConnector2,<br>ShapeType.CurvedConnector3,<br>ShapeType.CurvedConnector4,<br>ShapeType.CurvedConnector5. |
| x | float | 그림 프레임의 x 좌표(포인트). |
| y | float | 그림 프레임의 y 좌표(포인트). |
| width | float | 그림 프레임의 너비(포인트). |
| height | float | 그림 프레임의 높이(포인트). |
| image | [IPPImage](../../com.aspose.slides/ippimage) | 그림 프레임에 표시할 [IPPImage](../../com.aspose.slides/ippimage). |

**반환값:**
[IPictureFrame](../../com.aspose.slides/ipictureframe) - 새로 생성된 [IPictureFrame](../../com.aspose.slides/ipictureframe).
### addTable(float x, float y, double[] columnWidths, double[] rowHeights) {#addTable-float-float-double---double---}
```
public abstract ITable addTable(float x, float y, double[] columnWidths, double[] rowHeights)
```

새 테이블을 생성하고 모양 컬렉션 끝에 추가합니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| x | float | 테이블의 x 좌표(포인트). |
| y | float | 테이블의 y 좌표(포인트). |
| columnWidths | double[] | 테이블 열의 너비를 포인트 단위로 나타내는 double 배열. |
| rowHeights | double[] | 테이블 행의 높이를 포인트 단위로 나타내는 double 배열. |

**반환값:**
[ITable](../../com.aspose.slides/itable) - 새로 생성된 [ITable](../../com.aspose.slides/itable).
### insertTable(int index, float x, float y, double[] columnWidths, double[] rowHeights) {#insertTable-int-float-float-double---double---}
```
public abstract ITable insertTable(int index, float x, float y, double[] columnWidths, double[] rowHeights)
```
Creates a new table and inserts it into the shape collection at the specified index.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| index | int | 테이블을 삽입할 0부터 시작하는 인덱스입니다. |
| x | float | 포인트 단위의 테이블 x 좌표입니다. |
| y | float | 포인트 단위의 테이블 y 좌표입니다. |
| columnWidths | double[] | 포인트 단위로 테이블 열의 너비를 나타내는 double 배열입니다. |
| rowHeights | double[] | 포인트 단위로 테이블 행의 높이를 나타내는 double 배열입니다. |

**Returns:**
[ITable](../../com.aspose.slides/itable) - The newly created [ITable](../../com.aspose.slides/itable).
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```


Removes the shape at the specified index from the shape collection.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| index | int | 제거할 shape의 0부터 시작하는 인덱스입니다. |

### remove(IShape shape) {#remove-com.aspose.slides.IShape-}
```
public abstract void remove(IShape shape)
```


Removes the first occurrence of the specified shape from the shape collection.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| shape | [IShape](../../com.aspose.slides/ishape) | 제거할 [IShape](../../com.aspose.slides/ishape)입니다. |

### clear() {#clear--}
```
public abstract void clear()
```


Removes all shapes from the shape collection.

### addClone(IShape sourceShape, float x, float y, float width, float height) {#addClone-com.aspose.slides.IShape-float-float-float-float-}
```
public abstract IShape addClone(IShape sourceShape, float x, float y, float width, float height)
```


Creates a copy of the specified shape and adds it to the end of the shape collection.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | 복제할 shape입니다. |
| x | float | 복제된 shape 프레임의 x 좌표(포인트)입니다. |
| y | float | 복제된 shape 프레임의 y 좌표(포인트)입니다. |
| width | float | 복제된 shape 프레임의 너비(포인트)입니다. |
| height | float | 복제된 shape 프레임의 높이(포인트)입니다. |

**Returns:**
[IShape](../../com.aspose.slides/ishape) - The newly created [IShape](../../com.aspose.slides/ishape).
### addClone(IShape sourceShape, float x, float y) {#addClone-com.aspose.slides.IShape-float-float-}
```
public abstract IShape addClone(IShape sourceShape, float x, float y)
```


Creates a copy of the specified shape and adds it to the end of the shape collection. The new shape retains the width and height of the  sourceShape .

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | 복제할 [IShape](../../com.aspose.slides/ishape)입니다. |
| x | float | 복제된 shape 프레임의 x 좌표(포인트)입니다. |
| y | float | 복제된 shape 프레임의 y 좌표(포인트)입니다. |

**Returns:**
[IShape](../../com.aspose.slides/ishape) - The newly created [IShape](../../com.aspose.slides/ishape).
### addClone(IShape sourceShape) {#addClone-com.aspose.slides.IShape-}
```
public abstract IShape addClone(IShape sourceShape)
```


Creates a copy of the specified shape and adds it to the end of the shape collection. The cloned shape retains the original's position and size.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | 복제할 [IShape](../../com.aspose.slides/ishape)입니다. |

**Returns:**
[IShape](../../com.aspose.slides/ishape) - The newly created [IShape](../../com.aspose.slides/ishape).
### insertClone(int index, IShape sourceShape, float x, float y, float width, float height) {#insertClone-int-com.aspose.slides.IShape-float-float-float-float-}
```
public abstract IShape insertClone(int index, IShape sourceShape, float x, float y, float width, float height)
```


Creates a copy of the specified shape and inserts it into the shape collection at the specified index.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| index | int | 복제된 shape을 삽입할 0부터 시작하는 인덱스입니다. |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | 복제할 [IShape](../../com.aspose.slides/ishape)입니다. |
| x | float | 복제된 shape 프레임의 x 좌표(포인트)입니다. |
| y | float | 복제된 shape 프레임의 y 좌표(포인트)입니다. |
| width | float | 복제된 shape 프레임의 너비(포인트)입니다. |
| height | float | 복제된 shape 프레임의 높이(포인트)입니다. |

**Returns:**
[IShape](../../com.aspose.slides/ishape) - The newly created [IShape](../../com.aspose.slides/ishape).
### insertClone(int index, IShape sourceShape, float x, float y) {#insertClone-int-com.aspose.slides.IShape-float-float-}
```
public abstract IShape insertClone(int index, IShape sourceShape, float x, float y)
```


Creates a copy of the specified shape and inserts it into the shape collection at the specified index. The new shape retains the width and height of the  sourceShape .

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| index | int | 복제된 shape을 삽입할 0부터 시작하는 인덱스입니다. |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | 복제할 [IShape](../../com.aspose.slides/ishape)입니다. |
| x | float | 복제된 shape 프레임의 x 좌표(포인트)입니다. |
| y | float | 복제된 shape 프레임의 y 좌표(포인트)입니다. |

**Returns:**
[IShape](../../com.aspose.slides/ishape) - The newly created [IShape](../../com.aspose.slides/ishape).
### insertClone(int index, IShape sourceShape) {#insertClone-int-com.aspose.slides.IShape-}
```
public abstract IShape insertClone(int index, IShape sourceShape)
```


Creates a copy of the specified shape and inserts it into the shape collection at the specified index. The cloned shape retains the original's position and size.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| index | int | 복제된 shape을 삽입할 0부터 시작하는 인덱스입니다. |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | 복제할 [IShape](../../com.aspose.slides/ishape)입니다. |

**Returns:**
[IShape](../../com.aspose.slides/ishape) - The newly created [IShape](../../com.aspose.slides/ishape).