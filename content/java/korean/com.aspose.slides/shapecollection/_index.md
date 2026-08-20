---
title: ShapeCollection
second_title: Aspose.Slides for Java API 레퍼런스
description: 도형 컬렉션을 나타냅니다.
type: docs
url: /ko/com.aspose.slides/shapecollection/
---
**상속:**  
java.lang.Object, com.aspose.slides.DomObject

**구현된 모든 인터페이스:**  
[com.aspose.slides.IShapeCollection](../../com.aspose.slides/ishapecollection)  
```
public final class ShapeCollection extends DomObject<GroupShape> implements IShapeCollection
```

도형 컬렉션을 나타냅니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [size()](#size--) | 컬렉션에 실제로 포함된 요소 수를 가져옵니다. |
| [get_Item(int index)](#get-Item-int-) | 지정된 인덱스에 있는 요소를 가져옵니다. |
| [addChart(int type, float x, float y, float width, float height)](#addChart-int-float-float-float-float-) | 새 차트를 생성하고 샘플 시리즈 데이터와 설정으로 초기화한 다음 도형 컬렉션의 끝에 추가합니다. |
| [addChart(int type, float x, float y, float width, float height, boolean initWithSample)](#addChart-int-float-float-float-float-boolean-) | 새 차트를 생성하고 샘플 시리즈 데이터와 설정으로 초기화한 다음 도형 컬렉션의 끝에 추가합니다. |
| [addSmartArt(float x, float y, float width, float height, int layoutType)](#addSmartArt-float-float-float-float-int-) | SmartArt 다이어그램을 생성하고 도형 컬렉션의 끝에 추가합니다. |
| [insertChart(int type, float x, float y, float width, float height, int index)](#insertChart-int-float-float-float-float-int-) | 새 차트를 생성하고 샘플 시리즈 데이터와 설정으로 초기화한 다음 지정된 인덱스에 도형 컬렉션에 삽입합니다. |
| [insertChart(int type, float x, float y, float width, float height, int index, boolean initWithSample)](#insertChart-int-float-float-float-float-int-boolean-) | 새 차트를 생성하고 샘플 시리즈 데이터와 설정으로 초기화한 다음 지정된 인덱스에 도형 컬렉션에 삽입합니다. |
| [addZoomFrame(float x, float y, float width, float height, ISlide slide)](#addZoomFrame-float-float-float-float-com.aspose.slides.ISlide-) | 새 Zoom 프레임을 생성하고 도형 컬렉션의 끝에 추가합니다. |
| [addZoomFrame(float x, float y, float width, float height, ISlide slide, IPPImage image)](#addZoomFrame-float-float-float-float-com.aspose.slides.ISlide-com.aspose.slides.IPPImage-) | 새 Zoom 프레임을 생성하고 도형 컬렉션의 끝에 추가합니다. |
| [insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide)](#insertZoomFrame-int-float-float-float-float-com.aspose.slides.ISlide-) | 새 Zoom 프레임을 생성하고 지정된 인덱스에 도형 컬렉션에 삽입합니다. |
| [insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide, IPPImage image)](#insertZoomFrame-int-float-float-float-float-com.aspose.slides.ISlide-com.aspose.slides.IPPImage-) | 미리 정의된 이미지가 있는 새 Zoom 프레임을 생성하고 지정된 인덱스에 도형 컬렉션에 삽입합니다. |
| [addSectionZoomFrame(float x, float y, float width, float height, ISection section)](#addSectionZoomFrame-float-float-float-float-com.aspose.slides.ISection-) | 새 Section Zoom 프레임을 생성하고 도형 컬렉션의 끝에 추가합니다. |
| [addSectionZoomFrame(float x, float y, float width, float height, ISection section, IPPImage image)](#addSectionZoomFrame-float-float-float-float-com.aspose.slides.ISection-com.aspose.slides.IPPImage-) | 미리 정의된 이미지가 있는 새 Section Zoom 프레임을 생성하고 도형 컬렉션의 끝에 추가합니다. |
| [insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section)](#insertSectionZoomFrame-int-float-float-float-float-com.aspose.slides.ISection-) | 새 Section Zoom 프레임을 생성하고 지정된 인덱스에 도형 컬렉션에 삽입합니다. |
| [insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section, IPPImage image)](#insertSectionZoomFrame-int-float-float-float-float-com.aspose.slides.ISection-com.aspose.slides.IPPImage-) | 미리 정의된 이미지가 있는 새 Section Zoom 프레임을 생성하고 지정된 인덱스에 도형 컬렉션에 삽입합니다. |
| [addSummaryZoomFrame(float x, float y, float width, float height)](#addSummaryZoomFrame-float-float-float-float-) | 새 Summary Zoom 프레임을 생성하고 도형 컬렉션의 끝에 추가합니다. |
| [insertSummaryZoomFrame(int index, float x, float y, float width, float height)](#insertSummaryZoomFrame-int-float-float-float-float-) | 새 Summary Zoom 프레임을 생성하고 지정된 인덱스에 도형 컬렉션에 삽입합니다. |
| [addOleObjectFrame(float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo)](#addOleObjectFrame-float-float-float-float-com.aspose.slides.IOleEmbeddedDataInfo-) | 새 OLE 객체 프레임을 생성하고 도형 컬렉션의 끝에 추가합니다. |
| [addOleObjectFrame(float x, float y, float width, float height, String className, String path)](#addOleObjectFrame-float-float-float-float-java.lang.String-java.lang.String-) | 새 OLE 객체 프레임을 생성하고 도형 컬렉션의 끝에 추가합니다. |
| [insertOleObjectFrame(int index, float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo)](#insertOleObjectFrame-int-float-float-float-float-com.aspose.slides.IOleEmbeddedDataInfo-) | 새 OLE 객체 프레임을 생성하고 지정된 인덱스에 도형 컬렉션에 삽입합니다. |
| [insertOleObjectFrame(int index, float x, float y, float width, float height, String className, String path)](#insertOleObjectFrame-int-float-float-float-float-java.lang.String-java.lang.String-) | 새 OLE 객체 프레임을 생성하고 지정된 인덱스에 도형 컬렉션에 삽입합니다. |
| [addVideoFrame(float x, float y, float width, float height, String fname)](#addVideoFrame-float-float-float-float-java.lang.String-) | 새 비디오 프레임을 생성하고 도형 컬렉션의 끝에 추가합니다. |
| [addVideoFrame(float x, float y, float width, float height, IVideo video)](#addVideoFrame-float-float-float-float-com.aspose.slides.IVideo-) | 새 비디오 프레임을 생성하고 도형 컬렉션의 끝에 추가합니다. |
| [insertVideoFrame(int index, float x, float y, float width, float height, String fname)](#insertVideoFrame-int-float-float-float-float-java.lang.String-) | 새 비디오 프레임을 생성하고 지정된 인덱스에 도형 컬렉션에 삽입합니다. |
| [addAudioFrameCD(float x, float y, float width, float height)](#addAudioFrameCD-float-float-float-float-) | CD 트랙에 연결된 새 오디오 프레임을 생성하고 도형 컬렉션의 끝에 추가합니다. |
| [insertAudioFrameCD(int index, float x, float y, float width, float height)](#insertAudioFrameCD-int-float-float-float-float-) | CD 트랙에 연결된 새 오디오 프레임을 생성하고 지정된 인덱스에 도형 컬렉션에 삽입합니다. |
| [addAudioFrameLinked(float x, float y, float width, float height, String fname)](#addAudioFrameLinked-float-float-float-float-java.lang.String-) | 외부 오디오 파일에 연결된 새 오디오 프레임을 생성하고 도형 컬렉션의 끝에 추가합니다. |
| [insertAudioFrameLinked(int index, float x, float y, float width, float height, String fname)](#insertAudioFrameLinked-int-float-float-float-float-java.lang.String-) | 외부 오디오 파일에 연결된 새 오디오 프레임을 생성하고 지정된 인덱스에 도형 컬렉션에 삽입합니다. |
| [addAudioFrameEmbedded(float x, float y, float width, float height, InputStream audio_stream)](#addAudioFrameEmbedded-float-float-float-float-java.io.InputStream-) | 임베디드 WAV 파일이 포함된 새 오디오 프레임을 생성하고 도형 컬렉션의 끝에 추가합니다. |
| [insertAudioFrameEmbedded(int index, float x, float y, float width, float height, InputStream audio_stream)](#insertAudioFrameEmbedded-int-float-float-float-float-java.io.InputStream-) | 임베디드 WAV 파일이 포함된 새 오디오 프레임을 생성하고 지정된 인덱스에 도형 컬렉션에 삽입합니다. |
| [addAudioFrameEmbedded(float x, float y, float width, float height, IAudio audio)](#addAudioFrameEmbedded-float-float-float-float-com.aspose.slides.IAudio-) | Presentation.Audios 목록에 있는 기존 오디오 객체를 사용하여 새 오디오 프레임을 생성하고 도형 컬렉션의 끝에 추가합니다. |
| [insertAudioFrameEmbedded(int index, float x, float y, float width, float height, IAudio audio)](#insertAudioFrameEmbedded-int-float-float-float-float-com.aspose.slides.IAudio-) | Presentation.Audios 목록에 있는 기존 오디오 객체를 사용하여 새 오디오 프레임을 생성하고 지정된 인덱스에 도형 컬렉션에 삽입합니다. |
| [indexOf(IShape shape)](#indexOf-com.aspose.slides.IShape-) | 컬렉션에서 지정된 도형이 처음 나타나는 0 기반 인덱스를 반환합니다. |
| [toArray()](#toArray--) | 모든 도형을 포함하는 배열을 생성하고 반환합니다. |
| [toArray(int startIndex, int count)](#toArray-int-int-) | 지정된 범위의 모든 도형을 포함하는 배열을 생성하고 반환합니다. |
| [reorder(int index, IShape shape)](#reorder-int-com.aspose.slides.IShape-) | 지정된 도형을 도형 컬렉션 내의 새 위치로 이동합니다. |
| [reorder(int index, IShape[] shapes)](#reorder-int-com.aspose.slides.IShape...-) | 도형 컬렉션 내에서 지정된 도형들을 이동시키며, 주어진 인덱스부터 배치합니다. |
| [addAutoShape(int shapeType, float x, float y, float width, float height)](#addAutoShape-int-float-float-float-float-) | 기본 서식이 적용된 새 자동 도형을 생성하고 도형 컬렉션의 끝에 추가합니다. |
| [addAutoShape(int shapeType, float x, float y, float width, float height, boolean createFromTemplate)](#addAutoShape-int-float-float-float-float-boolean-) | 새 자동 도형을 생성하고 도형 컬렉션의 끝에 추가합니다. 선택적으로 기본 템플릿 서식으로 초기화할 수 있습니다. |
| [addMathShape(float x, float y, float width, float height)](#addMathShape-float-float-float-float-) | 수학 콘텐츠를 호스트할 새 직사각형 자동 도형을 생성하고 도형 컬렉션의 끝에 추가합니다. |
| [insertAutoShape(int index, int shapeType, float x, float y, float width, float height)](#insertAutoShape-int-int-float-float-float-float-) | 새 자동 도형을 생성하고 지정된 인덱스에 도형 컬렉션에 삽입하며 기본 템플릿 서식을 적용합니다. |
| [insertAutoShape(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate)](#insertAutoShape-int-int-float-float-float-float-boolean-) | 새 자동 도형을 생성하고 지정된 인덱스에 도형 컬렉션에 삽입하며, 선택적으로 기본 템플릿 스타일로 초기화할 수 있습니다. |
| [addGroupShape()](#addGroupShape--) | 새 빈 그룹 도형을 생성하고 도형 컬렉션의 끝에 추가합니다. |
| [addGroupShape(ISvgImage svgImage, float x, float y, float width, float height)](#addGroupShape-com.aspose.slides.ISvgImage-float-float-float-float-) | 새 그룹 도형을 생성하고 지정된 SVG 이미지를 개별 도형으로 변환한 뒤, 결과 그룹을 도형 컬렉션의 끝에 추가합니다. |
| [insertGroupShape(int index)](#insertGroupShape-int-) | 새 빈 그룹 도형을 생성하고 지정된 인덱스에 도형 컬렉션에 삽입합니다. |
| [addConnector(int shapeType, float x, float y, float width, float height)](#addConnector-int-float-float-float-float-) | 기본 템플릿 스타일이 적용된 새 커넥터 도형을 생성하고 도형 컬렉션의 끝에 추가합니다. |
| [addConnector(int shapeType, float x, float y, float width, float height, boolean createFromTemplate)](#addConnector-int-float-float-float-float-boolean-) | 새 커넥터 도형을 생성하고 도형 컬렉션의 끝에 추가합니다. 선택적으로 기본 템플릿 스타일을 적용할 수 있습니다. |
| [insertConnector(int index, int shapeType, float x, float y, float width, float height)](#insertConnector-int-int-float-float-float-float-) | 새 커넥터 도형을 생성하고 지정된 인덱스에 도형 컬렉션에 삽입하며 기본 템플릿 스타일을 적용합니다. |
| [insertConnector(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate)](#insertConnector-int-int-float-float-float-float-boolean-) | 새 커넥터 도형을 생성하고 지정된 인덱스에 도형 컬렉션에 삽입하며, 선택적으로 기본 템플릿 스타일을 적용합니다. |
| [addPictureFrame(int shapeType, float x, float y, float width, float height, IPPImage image)](#addPictureFrame-int-float-float-float-float-com.aspose.slides.IPPImage-) | 지정된 이미지를 포함하는 새 그림 프레임을 생성하고 도형 컬렉션의 끝에 추가합니다. |
| [insertPictureFrame(int index, int shapeType, float x, float y, float width, float height, IPPImage image)](#insertPictureFrame-int-int-float-float-float-float-com.aspose.slides.IPPImage-) | 지정된 이미지를 포함하는 새 그림 프레임을 생성하고 지정된 인덱스에 도형 컬렉션에 삽입합니다. |
| [addTable(float x, float y, double[] columnWidths, double[] rowHeights)](#addTable-float-float-double---double---) | 새 테이블을 생성하고 도형 컬렉션의 끝에 추가합니다. |
| [insertTable(int index, float x, float y, double[] columnWidths, double[] rowHeights)](#insertTable-int-float-float-double---double---) | 새 테이블을 생성하고 지정된 인덱스에 도형 컬렉션에 삽입합니다. |
| [removeAt(int index)](#removeAt-int-) | 지정된 인덱스에 있는 도형을 도형 컬렉션에서 제거합니다. |
| [remove(IShape shape)](#remove-com.aspose.slides.IShape-) | 지정된 도형이 컬렉션에서 처음 나타나는 것을 제거합니다. |
| [clear()](#clear--) | 도형 컬렉션의 모든 도형을 제거합니다. |
| [iterator()](#iterator--) | 컬렉션을 순회하는 열거자를 반환합니다. |
| [iteratorJava()](#iteratorJava--) | 전체 컬렉션에 대한 java iterator를 반환합니다. |
| [getParentGroup()](#getParentGroup--) | 도형 컬렉션에 대한 상위 그룹 도형 객체를 가져옵니다. |
| [addClone(IShape sourceShape, float x, float y, float width, float height)](#addClone-com.aspose.slides.IShape-float-float-float-float-) | 지정된 도형의 복사본을 생성하고 도형 컬렉션의 끝에 추가합니다. |
| [addClone(IShape sourceShape, float x, float y)](#addClone-com.aspose.slides.IShape-float-float-) | 지정된 도형의 복사본을 생성하고 도형 컬렉션의 끝에 추가합니다. |
| [addClone(IShape sourceShape)](#addClone-com.aspose.slides.IShape-) | 지정된 도형의 복사본을 생성하고 도형 컬렉션의 끝에 추가합니다. |
| [insertClone(int index, IShape sourceShape, float x, float y, float width, float height)](#insertClone-int-com.aspose.slides.IShape-float-float-float-float-) | 지정된 도형의 복사본을 생성하고 지정된 인덱스에 도형 컬렉션에 삽입합니다. |
| [insertClone(int index, IShape sourceShape, float x, float y)](#insertClone-int-com.aspose.slides.IShape-float-float-) | 지정된 도형의 복사본을 생성하고 지정된 인덱스에 도형 컬렉션에 삽입합니다. |
| [insertClone(int index, IShape sourceShape)](#insertClone-int-com.aspose.slides.IShape-) | 지정된 도형의 복사본을 생성하고 지정된 인덱스에 도형 컬렉션에 삽입합니다. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | 컬렉션의 모든 요소를 지정된 배열에 복사합니다. |
| [isSynchronized()](#isSynchronized--) | 컬렉션에 대한 액세스가 동기화(스레드 안전)인지 여부를 나타내는 값을 반환합니다. |
| [getSyncRoot()](#getSyncRoot--) | 동기화 루트를 반환합니다. |
### size() {#size--}
```
public final int size()
```

컬렉션에 실제로 포함된 요소 수를 가져옵니다. 읽기 전용 int .

**반환:**  
int
### get_Item(int index) {#get-Item-int-}
```
public final IShape get_Item(int index)
```

지정된 인덱스에 있는 요소를 가져옵니다. 읽기 전용 [IShape](../../com.aspose.slides/ishape).

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| index | int |  |

**반환:**  
[IShape](../../com.aspose.slides/ishape)
### addChart(int type, float x, float y, float width, float height) {#addChart-int-float-float-float-float-}
```
public final IChart addChart(int type, float x, float y, float width, float height)
```

새 차트를 생성하고 샘플 시리즈 데이터와 설정으로 초기화한 다음 도형 컬렉션의 끝에 추가합니다.

--------------------

> ```
> The following example shows how to create Chart in PowerPoint Presentation.
>  
>  // PPTX 파일을 나타내는 Presentation 클래스를 인스턴스화합니다
>  Presentation pres = new Presentation();
>  try {
>      // 첫 번째 슬라이드에 접근합니다
>      ISlide sld = pres.getSlides().get_Item(0);
>      // 기본 데이터로 차트를 추가합니다
>      IChart chart = sld.getShapes().addChart(ChartType.ClusteredColumn, 0, 0, 500, 500);
>      // 차트 제목을 설정합니다
>      chart.getChartTitle().addTextFrameForOverriding("Sample Title");
>      chart.getChartTitle().getTextFrameForOverriding().getTextFrameFormat().setCenterText(NullableBool.True);
>      chart.getChartTitle().setHeight(20);
>      chart.setTitle(true);
>      // 첫 번째 시리즈가 값을 표시하도록 설정합니다
>      chart.getChartData().getSeries().get_Item(0).getLabels().getDefaultDataLabelFormat().setShowValue(true);
>      // 차트 데이터 시트의 인덱스를 설정합니다
>      int defaultWorksheetIndex = 0;
>      // 차트 데이터 워크시트를 가져옵니다
>      IChartDataWorkbook fact = chart.getChartData().getChartDataWorkbook();
>      // 기본 생성된 시리즈와 범주를 삭제합니다
>      chart.getChartData().getSeries().clear();
>      chart.getChartData().getCategories().clear();
>      // 새로운 시리즈를 추가합니다
>      chart.getChartData().getSeries().add(fact.getCell(defaultWorksheetIndex, 0, 1, "Series 1"), chart.getType());
>      chart.getChartData().getSeries().add(fact.getCell(defaultWorksheetIndex, 0, 2, "Series 2"), chart.getType());
>      // 새로운 범주를 추가합니다
>      chart.getChartData().getCategories().add(fact.getCell(defaultWorksheetIndex, 1, 0, "Caetegoty 1"));
>      chart.getChartData().getCategories().add(fact.getCell(defaultWorksheetIndex, 2, 0, "Caetegoty 2"));
>      chart.getChartData().getCategories().add(fact.getCell(defaultWorksheetIndex, 3, 0, "Caetegoty 3"));
>      // 첫 번째 차트 시리즈를 가져옵니다
>      IChartSeries series = chart.getChartData().getSeries().get_Item(0);
>      // 시리즈 데이터를 채웁니다
>      series.getDataPoints().addDataPointForBarSeries(fact.getCell(defaultWorksheetIndex, 1, 1, 20));
>      series.getDataPoints().addDataPointForBarSeries(fact.getCell(defaultWorksheetIndex, 2, 1, 50));
>      series.getDataPoints().addDataPointForBarSeries(fact.getCell(defaultWorksheetIndex, 3, 1, 30));
>      // 시리즈의 채우기 색상을 설정합니다
>      series.getFormat().getFill().setFillType(FillType.Solid);
>      series.getFormat().getFill().getSolidFillColor().setColor(Color.RED);
>      // 두 번째 차트 시리즈를 가져옵니다
>      series = chart.getChartData().getSeries().get_Item(1);
>      // 시리즈 데이터를 채웁니다
>      series.getDataPoints().addDataPointForBarSeries(fact.getCell(defaultWorksheetIndex, 1, 2, 30));
>      series.getDataPoints().addDataPointForBarSeries(fact.getCell(defaultWorksheetIndex, 2, 2, 10));
>      series.getDataPoints().addDataPointForBarSeries(fact.getCell(defaultWorksheetIndex, 3, 2, 60));
>      // 시리즈의 채우기 색상을 설정합니다
>      series.getFormat().getFill().setFillType(FillType.Solid);
>      series.getFormat().getFill().getSolidFillColor().setColor(Color.GREEN);
>      // 첫 번째 레이블에 카테고리 이름을 표시하도록 설정합니다
>      IDataLabel lbl = series.getDataPoints().get_Item(0).getLabel();
>      lbl.getDataLabelFormat().setShowCategoryName(true);
>      lbl = series.getDataPoints().get_Item(1).getLabel();
>      lbl.getDataLabelFormat().setShowSeriesName(true);
>      // 세 번째 레이블에 값을 표시하도록 시리즈를 설정합니다
>      lbl = series.getDataPoints().get_Item(2).getLabel();
>      lbl.getDataLabelFormat().setShowValue(true);
>      lbl.getDataLabelFormat().setShowSeriesName(true);
>      lbl.getDataLabelFormat().setSeparator("/");
>      // PPTP 파일을 디스크에 저장합니다
>      pres.save("AsposeChart_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


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
public final IChart addChart(int type, float x, float y, float width, float height, boolean initWithSample)
```

새 차트를 생성하고 샘플 시리즈 데이터와 설정으로 초기화한 다음 도형 컬렉션의 끝에 추가합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| type | int | 추가할 차트 유형. |
| x | float | 새 차트의 x 좌표(포인트 단위). |
| y | float | 새 차트의 y 좌표(포인트 단위). |
| width | float | 차트의 너비(포인트 단위). |
| height | float | 차트의 높이(포인트 단위). |
| initWithSample | boolean | 샘플 시리즈 데이터와 설정으로 차트를 초기화하려면 true; 시리즈 없이 최소 설정만으로 차트를 생성하여 생성 속도를 높이려면 false. |

**반환:**  
[IChart](../../com.aspose.slides/ichart) - 새로 생성된 [IChart](../../com.aspose.slides/ichart).
### addSmartArt(float x, float y, float width, float height, int layoutType) {#addSmartArt-float-float-float-float-int-}
```
public final ISmartArt addSmartArt(float x, float y, float width, float height, int layoutType)
```

SmartArt 다이어그램을 생성하고 도형 컬렉션의 끝에 추가합니다.

--------------------

> ```
> The following example shows how to add smart shape in PowerPoint Presentation.
>  
>  Presentation pres = new Presentation();
>  try {
>      ISlide slide = pres.getSlides().get_Item(0);
>      ISmartArt smart = slide.getShapes().addSmartArt(0, 0, 400, 400, SmartArtLayoutType.BasicBlockList);
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
public final IChart insertChart(int type, float x, float y, float width, float height, int index)
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
public final IChart insertChart(int type, float x, float y, float width, float height, int index, boolean initWithSample)
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
| initWithSample | boolean | 샘플 시리즈 데이터와 설정으로 차트를 초기화하려면 true; 시리즈 없이 최소 설정만으로 차트를 생성하여 생성 속도를 높이려면 false. |
| x | float | 새 차트의 x 좌표, 포인트 단위. |
| y | float | 새 차트의 y 좌표, 포인트 단위. |
| width | float | 새 차트의 너비, 포인트 단위. |
| height | float | 새 차트의 높이, 포인트 단위. |
| index | int | shape 컬렉션에 새 차트를 삽입할 0부터 시작하는 인덱스. |
| initWithSample | boolean | true이면 샘플 시리즈 데이터와 설정으로 새 차트를 초기화하고, false이면 시리즈 없이 최소 설정만으로 차트를 생성하여 생성 속도를 높입니다. |

**반환값:**  
[IChart](../../com.aspose.slides/ichart) - 새로 생성된 [IChart](../../com.aspose.slides/ichart).

### addZoomFrame(float x, float y, float width, float height, ISlide slide) {#addZoomFrame-float-float-float-float-com.aspose.slides.ISlide-}
```
public final IZoomFrame addZoomFrame(float x, float y, float width, float height, ISlide slide)
```

새 Zoom 프레임을 생성하고 shape 컬렉션의 끝에 추가합니다.

--------------------

> ```
> 이 예제는 컬렉션 끝에 Zoom 객체를 추가하는 방법을 보여줍니다
>  ("Presentation.pptx" 프레젠테이션에 슬라이드가 최소 두 개 있다고 가정합니다):
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addZoomFrame(150, 20, 50, 50, pres.getSlides().get_Item(1));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**매개변수:**  
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| x | float | 새 Zoom 프레임의 x 좌표, 포인트 단위. |
| y | float | 새 Zoom 프레임의 y 좌표, 포인트 단위. |
| width | float | 새 Zoom 프레임의 너비, 포인트 단위. |
| height | float | 새 Zoom 프레임의 높이, 포인트 단위. |
| slide | [ISlide](../../com.aspose.slides/islide) | Zoom 프레임이 참조하는 [ISlide](../../com.aspose.slides/islide); 이 프레젠테이션에 속해야 합니다. |

**반환값:**  
[IZoomFrame](../../com.aspose.slides/izoomframe) - 새로 생성된 [IZoomFrame](../../com.aspose.slides/izoomframe).

### addZoomFrame(float x, float y, float width, float height, ISlide slide, IPPImage image) {#addZoomFrame-float-float-float-float-com.aspose.slides.ISlide-com.aspose.slides.IPPImage-}
```
public final IZoomFrame addZoomFrame(float x, float y, float width, float height, ISlide slide, IPPImage image)
```

새 Zoom 프레임을 생성하고 shape 컬렉션의 끝에 추가합니다.

--------------------

> ```
> 이 예제는 컬렉션 끝에 Zoom 객체를 추가하는 방법을 보여줍니다
>  ("Presentation.pptx" 프레젠테이션에 슬라이드가 최소 두 개 있다고 가정합니다):
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      IPPImage image = pres.getImages().addImage(imageBytes);
>      IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addZoomFrame(150, 20, 50, 50, pres.getSlides().get_Item(1), image);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**매개변수:**  
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| x | float | 새 Zoom 프레임의 x 좌표, 포인트 단위. |
| y | float | 새 Zoom 프레임의 y 좌표, 포인트 단위. |
| width | float | 새 Zoom 프레임의 너비, 포인트 단위. |
| height | float | 새 Zoom 프레임의 높이, 포인트 단위. |
| slide | [ISlide](../../com.aspose.slides/islide) | Zoom 프레임이 참조하는 [ISlide](../../com.aspose.slides/islide); 이 프레젠테이션에 속해야 합니다. |
| image | [IPPImage](../../com.aspose.slides/ippimage) | 참조된 슬라이드 [IPPImage](../../com.aspose.slides/ippimage)의 이미지. |

**반환값:**  
[IZoomFrame](../../com.aspose.slides/izoomframe) - 새로 생성된 [IZoomFrame](../../com.aspose.slides/izoomframe).

### insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide) {#insertZoomFrame-int-float-float-float-float-com.aspose.slides.ISlide-}
```
public final IZoomFrame insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide)
```

새 Zoom 프레임을 생성하고 지정된 인덱스에 shape 컬렉션에 삽입합니다.

--------------------

> ```
> 이 예제는 컬렉션의 지정된 인덱스에 Zoom 객체를 생성하고 삽입하는 방법을 보여줍니다
>  ("Presentation.pptx" 프레젠테이션에 슬라이드가 최소 두 개 있다고 가정합니다):
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().insertZoomFrame(2, 150, 20, 50, 50, pres.getSlides().get_Item(1));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**매개변수:**  
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| index | int | Zoom 프레임을 삽입할 0부터 시작하는 인덱스. |
| x | float | 새 Zoom 프레임의 x 좌표, 포인트 단위. |
| y | float | 새 Zoom 프레임의 y 좌표, 포인트 단위. |
| width | float | 새 Zoom 프레임의 너비, 포인트 단위. |
| height | float | 새 Zoom 프레임의 높이, 포인트 단위. |
| slide | [ISlide](../../com.aspose.slides/islide) | Zoom 프레임이 참조하는 [ISlide](../../com.aspose.slides/islide). |

**반환값:**  
[IZoomFrame](../../com.aspose.slides/izoomframe) - 새로 생성된 [IZoomFrame](../../com.aspose.slides/izoomframe).

### insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide, IPPImage image) {#insertZoomFrame-int-float-float-float-float-com.aspose.slides.ISlide-com.aspose.slides.IPPImage-}
```
public final IZoomFrame insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide, IPPImage image)
```

미리 정의된 이미지를 사용해 새 Zoom 프레임을 생성하고 지정된 인덱스에 shape 컬렉션에 삽입합니다.

--------------------

> ```
> 이 예제는 컬렉션의 지정된 인덱스에 Zoom 객체를 생성하고 삽입하는 방법을 보여줍니다
>  ("Presentation.pptx" 프레젠테이션에 슬라이드가 최소 두 개 있다고 가정합니다):
>  
  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      IPPImage image = pres.getImages().addImage(imageBytes);
>      IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().insertZoomFrame(2, 150, 20, 50, 50, pres.getSlides().get_Item(1), image);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**매개변수:**  
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| index | int | Zoom 프레임을 삽입할 0부터 시작하는 인덱스. |
| x | float | 새 Zoom 프레임의 x 좌표, 포인트 단위. |
| y | float | 새 Zoom 프레임의 y 좌표, 포인트 단위. |
| width | float | 새 Zoom 프레임의 너비, 포인트 단위. |
| height | float | 새 Zoom 프레임의 높이, 포인트 단위. |
| slide | [ISlide](../../com.aspose.slides/islide) | Zoom 프레임이 참조하는 [ISlide](../../com.aspose.slides/islide). |
| image | [IPPImage](../../com.aspose.slides/ippimage) | 참조된 슬라이드 [IPPImage](../../com.aspose.slides/ippimage)의 이미지. |

**반환값:**  
[IZoomFrame](../../com.aspose.slides/izoomframe) - 새로 생성된 [IZoomFrame](../../com.aspose.slides/izoomframe).

### addSectionZoomFrame(float x, float y, float width, float height, ISection section) {#addSectionZoomFrame-float-float-float-float-com.aspose.slides.ISection-}
```
public final ISectionZoomFrame addSectionZoomFrame(float x, float y, float width, float height, ISection section)
```

새 Section Zoom 프레임을 생성하고 shape 컬렉션의 끝에 추가합니다.

--------------------

> ```
> 이 예제는 컬렉션 끝에 Section Zoom 객체를 추가하는 방법을 보여줍니다
>  ("Presentation.pptx" 프레젠테이션에 섹션이 최소 두 개 있다고 가정합니다):
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      ISectionZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addSectionZoomFrame(150, 20, 50, 50, pres.getSections().get_Item(1));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**매개변수:**  
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| x | float | 새 Section Zoom 프레임의 x 좌표, 포인트 단위. |
| y | float | 새 Section Zoom 프레임의 y 좌표, 포인트 단위. |
| width | float | 새 Section Zoom 프레임의 너비, 포인트 단위. |
| height | float | 새 Section Zoom 프레임의 높이, 포인트 단위. |
| section | [ISection](../../com.aspose.slides/isection) | Section Zoom 프레임이 참조하는 [ISection](../../com.aspose.slides/isection); 이 프레젠테이션에 속하고 최소 하나의 슬라이드를 포함해야 합니다. |

**반환값:**  
[ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe) - 새로 생성된 [ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe).

### addSectionZoomFrame(float x, float y, float width, float height, ISection section, IPPImage image) {#addSectionZoomFrame-float-float-float-float-com.aspose.slides.ISection-com.aspose.slides.IPPImage-}
```
public final ISectionZoomFrame addSectionZoomFrame(float x, float y, float width, float height, ISection section, IPPImage image)
```

미리 정의된 이미지를 사용해 새 Section Zoom 프레임을 생성하고 shape 컬렉션의 끝에 추가합니다.

--------------------

> ```
> 이 예제는 컬렉션 끝에 Section Zoom 객체를 추가하는 방법을 보여줍니다
>  ("Presentation.pptx" 프레젠테이션에 섹션이 최소 두 개 있다고 가정합니다):
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
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| x | float | 새 Section Zoom 프레임의 x 좌표, 포인트 단위. |
| y | float | 새 Section Zoom 프레임의 y 좌표, 포인트 단위. |
| width | float | 새 Section Zoom 프레임의 너비, 포인트 단위. |
| height | float | 새 Section Zoom 프레임의 높이, 포인트 단위. |
| section | [ISection](../../com.aspose.slides/isection) | Section Zoom 프레임이 참조하는 [ISection](../../com.aspose.slides/isection); 이 프레젠테이션에 속하고 최소 하나의 슬라이드를 포함해야 합니다. |
| image | [IPPImage](../../com.aspose.slides/ippimage) | Section Zoom 프레임 내에 표시할 [IPPImage](../../com.aspose.slides/ippimage). |

**반환값:**  
[ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe) - 새로 생성된 [ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe).

### insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section) {#insertSectionZoomFrame-int-float-float-float-float-com.aspose.slides.ISection-}
```
public final ISectionZoomFrame insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section)
```

새 Section Zoom 프레임을 생성하고 지정된 인덱스에 shape 컬렉션에 삽입합니다.

--------------------

> ```
> 이 예제는 컬렉션의 지정된 인덱스에 Section Zoom 객체를 생성하고 삽입하는 방법을 보여줍니다
>  ("Presentation.pptx" 프레젠테이션에 섹션이 최소 두 개 있다고 가정합니다):
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      ISectionZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().insertSectionZoomFrame(2, 150, 20, 50, 50, pres.getSections().get_Item(1));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**매개변수:**  
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| index | int | Section Zoom 프레임을 삽입할 0부터 시작하는 인덱스. |
| x | float | 새 Section Zoom 프레임의 x 좌표, 포인트 단위. |
| y | float | 새 Section Zoom 프레임의 y 좌표, 포인트 단위. |
| width | float | 새 Section Zoom 프레임의 너비, 포인트 단위. |
| height | float | 새 Section Zoom 프레임의 높이, 포인트 단위. |
| section | [ISection](../../com.aspose.slides/isection) | Section Zoom 프레임이 참조하는 [ISection](../../com.aspose.slides/isection); 이 프레젠테이션에 속하고 최소 하나의 슬라이드를 포함해야 합니다. |

**반환값:**  
[ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe) - 새로 생성된 [ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe).

### insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section, IPPImage image) {#insertSectionZoomFrame-int-float-float-float-float-com.aspose.slides.ISection-com.aspose.slides.IPPImage-}
```
public final ISectionZoomFrame insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section, IPPImage image)
```

미리 정의된 이미지를 사용해 새 Section Zoom 프레임을 생성하고 지정된 인덱스에 shape 컬렉션에 삽입합니다.

--------------------

> ```
> 이 예제는 컬렉션의 지정된 인덱스에 Section Zoom 객체를 생성하고 삽입하는 방법을 보여줍니다
>  ("Presentation.pptx" 프레젠테이션에 섹션이 최소 두 개 있다고 가정합니다):
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      IPPImage image = pres.getImages().addImage(Files.readAllBytes(Paths.get("image.png")));
>      ISectionZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().insertSectionZoomFrame(2, 150, 20, 50, 50, pres.getSections().get_Item(1), image);
>  } catch (IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**매개변수:**  
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| index | int | Section Zoom 프레임을 삽입할 0부터 시작하는 인덱스. |
| x | float | 새 Section Zoom 프레임의 x 좌표, 포인트 단위. |
| y | float | 새 Section Zoom 프레임의 y 좌표, 포인트 단위. |
| width | float | 새 Section Zoom 프레임의 너비, 포인트 단위. |
| height | float | 새 Section Zoom 프레임의 높이, 포인트 단위. |
| section | [ISection](../../com.aspose.slides/isection) | Section Zoom 프레임이 참조하는 [ISection](../../com.aspose.slides/isection); 이 프레젠테이션에 속하고 최소 하나의 슬라이드를 포함해야 합니다. |
| image | [IPPImage](../../com.aspose.slides/ippimage) | Section Zoom 프레임 내에 표시할 이미지. |

**반환값:**  
[ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe) - 새로 생성된 [ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe).

### addSummaryZoomFrame(float x, float y, float width, float height) {#addSummaryZoomFrame-float-float-float-float-}
```
public final ISummaryZoomFrame addSummaryZoomFrame(float x, float y, float width, float height)
```

새 Summary Zoom 프레임을 생성하고 shape 컬렉션의 끝에 추가합니다.

--------------------

> ```
> 이 예제는 컬렉션 끝에 Summary Zoom 객체를 추가하는 방법을 보여줍니다
>  ("Presentation.pptx" 프레젠테이션에 섹션이 최소 두 개 있다고 가정합니다):
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      ISummaryZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addSummaryZoomFrame(150, 20, 500, 250);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**매개변수:**  
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| x | float | 새 Summary Zoom 프레임의 x 좌표, 포인트 단위. |
| y | float | 새 Summary Zoom 프레임의 y 좌표, 포인트 단위. |
| width | float | 새 Summary Zoom 프레임의 너비, 포인트 단위. |
| height | float | 새 Summary Zoom 프레임의 높이, 포인트 단위. |

이 메서드는 새로운 Summary Zoom을 생성하고 이 프레젠테이션의 모든 섹션에 대한 객체 컬렉션을 넣습니다.

**반환값:**  
[ISummaryZoomFrame](../../com.aspose.slides/isummaryzoomframe) - 새로 생성된 [ISummaryZoomFrame](../../com.aspose.slides/isummaryzoomframe).

### insertSummaryZoomFrame(int index, float x, float y, float width, float height) {#insertSummaryZoomFrame-int-float-float-float-float-}
```
public final ISummaryZoomFrame insertSummaryZoomFrame(int index, float x, float y, float width, float height)
```

새 Summary Zoom 프레임을 생성하고 지정된 인덱스에 shape 컬렉션에 삽입합니다.

--------------------

> ```
> 이 예제는 컬렉션의 지정된 인덱스에 Summary Zoom 객체를 생성하고 삽입하는 방법을 보여줍니다
>  ("Presentation.pptx" 프레젠테이션에 섹션이 최소 두 개 있다고 가정합니다):
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
| index | int | Summary Zoom 프레임을 삽입할 0부터 시작하는 인덱스. |
| x | float | 새 Summary Zoom 프레임의 x 좌표, 포인트 단위. |
| y | float | 새 Summary Zoom 프레임의 y 좌표, 포인트 단위. |
| width | float | 새 Summary Zoom 프레임의 너비, 포인트 단위. |
| height | float | 새 Summary Zoom 프레임의 높이, 포인트 단위. |

이 메서드는 프레젠테이션의 모든 섹션에 대한 요약 링크를 집계하는 Summary Zoom 프레임을 생성합니다.

**반환값:**  
[ISummaryZoomFrame](../../com.aspose.slides/isummaryzoomframe) - 새로 생성된 [ISummaryZoomFrame](../../com.aspose.slides/isummaryzoomframe).

### addOleObjectFrame(float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo) {#addOleObjectFrame-float-float-float-float-com.aspose.slides.IOleEmbeddedDataInfo-}
```
public final IOleObjectFrame addOleObjectFrame(float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo)
```

새 OLE 객체 프레임을 생성하고 shape 컬렉션의 끝에 추가합니다.

--------------------

> ```
> 다음 예제는 PowerPoint 프레젠테이션 슬라이드에 OLE 객체 프레임을 추가하는 방법을 보여줍니다.
>  
>  // PPTX를 나타내는 Presentation 클래스를 인스턴스화합니다
>  Presentation pres = new Presentation();
>  try
>  {
>      // 첫 번째 슬라이드에 접근합니다
>      ISlide sld = pres.getSlides().get_Item(0);
> 
>      // 셀 파일을 스트림으로 로드합니다
>      FileInputStream fs = new FileInputStream("book1.xlsx");
>      ByteArrayOutputStream mstream = new ByteArrayOutputStream();
>      byte[] buf = new byte[4096];
> 
>      while (true)
>      {
>          int bytesRead = fs.read(buf, 0, buf.length);
>          if (bytesRead <= 0)
>              break;
>          mstream.write(buf, 0, bytesRead);
>      }
>      // 삽입용 데이터 객체를 생성합니다
>      IOleEmbeddedDataInfo dataInfo = new OleEmbeddedDataInfo(mstream.toByteArray(), "xlsx");
> 
>      // Ole 객체 프레임 쉐이프를 추가합니다
>      IOleObjectFrame oleObjectFrame = sld.getShapes().addOleObjectFrame(0, 0, (float)pres.getSlideSize().getSize().getWidth(),
>              (float)pres.getSlideSize().getSize().getHeight(), dataInfo);
> 
>      // PPTX를 디스크에 저장합니다
>      pres.save("OleEmbed_out.pptx", SaveFormat.Pptx);
>  }
>  catch (IOException e) { }
>  finally
>  {
>      if (pres != null) pres.dispose();
>  }
> ```


**매개변수:**  
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| x | float | 새 OLE 프레임의 x 좌표, 포인트 단위. |
| y | float | 새 OLE 프레임의 y 좌표, 포인트 단위. |
| width | float | 새 OLE 프레임의 너비, 포인트 단위. |
| height | float | 새 OLE 프레임의 높이, 포인트 단위. |
| dataInfo | [IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo) | 임베드된 OLE 데이터에 대한 정보 ([IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo)). |

**반환값:**  
[IOleObjectFrame](../../com.aspose.slides/ioleobjectframe) - 새로 생성된 [IOleObjectFrame](../../com.aspose.slides/ioleobjectframe).

### addOleObjectFrame(float x, float y, float width, float height, String className, String path) {#addOleObjectFrame-float-float-float-float-java.lang.String-java.lang.String-}
```
public final IOleObjectFrame addOleObjectFrame(float x, float y, float width, float height, String className, String path)
```

새 OLE 객체 프레임을 생성하고 shape 컬렉션의 끝에 추가합니다.

**매개변수:**  
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| x | float | 새 OLE 프레임의 x 좌표, 포인트 단위. |
| y | float | 새 OLE 프레임의 y 좌표, 포인트 단위. |
| width | float | 새 OLE 프레임의 너비, 포인트 단위. |
| height | float | 새 OLE 프레임의 높이, 포인트 단위. |
| className | java.lang.String | OLE 객체의 클래스 이름. |
| path | java.lang.String | 링크된 파일의 경로. 이 경로는 프레젠테이션에 그대로 저장됩니다. 상대 경로를 지정하면 다른 디렉터리에서 프레젠테이션을 열 때 파일에 접근할 수 없습니다. |

**반환값:**  
[IOleObjectFrame](../../com.aspose.slides/ioleobjectframe) - 새로 생성된 [IOleObjectFrame](../../com.aspose.slides/ioleobjectframe).

### insertOleObjectFrame(int index, float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo) {#insertOleObjectFrame-int-float-float-float-float-com.aspose.slides.IOleEmbeddedDataInfo-}
```
public final IOleObjectFrame insertOleObjectFrame(int index, float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo)
```

새 OLE 객체 프레임을 생성하고 지정된 인덱스에 shape 컬렉션에 삽입합니다.

--------------------

> ```
> 이 예제는 두 번째 인덱스에 OLE 객체를 삽입하는 방법을 보여줍니다:
>  
>  byte[] fileData = Files.readAllBytes(Paths.get("test.zip"));
>  IOleDataInfo dataInfo = new OleDataInfo(fileData, "zip");
>  IOleObjectFrame oleObjectFrame = slides.getShapes().addOleObjectFrame(2, 150, 20, 50, 50, dataInfo);
> ```

**매개변수:**  
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| index | int | OLE 객체 프레임을 삽입할 0부터 시작하는 인덱스. |
| x | float | 새 OLE 프레임의 x 좌표(포인트 단위). |
| y | float | 새 OLE 프레임의 y 좌표(포인트 단위). |
| width | float | 새 OLE 프레임의 너비(포인트 단위). |
| height | float | 새 OLE 프레임의 높이(포인트 단위). |
| dataInfo | [IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo) | 내장된 OLE 데이터 정보([IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo)). |

**반환값:**
[IOleObjectFrame](../../com.aspose.slides/ioleobjectframe) - 새로 생성된 [IOleObjectFrame](../../com.aspose.slides/ioleobjectframe).
### insertOleObjectFrame(int index, float x, float y, float width, float height, String className, String path) {#insertOleObjectFrame-int-float-float-float-float-java.lang.String-java.lang.String-}
```
public final IOleObjectFrame insertOleObjectFrame(int index, float x, float y, float width, float height, String className, String path)
```

새 OLE 개체 프레임을 생성하고 지정된 인덱스에 shape 컬렉션에 삽입합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| index | int | OLE 개체 프레임을 삽입할 0 기반 인덱스. |
| x | float | 새 OLE 프레임의 x 좌표(포인트 단위). |
| y | float | 새 OLE 프레임의 y 좌표(포인트 단위). |
| width | float | 새 OLE 프레임의 너비(포인트 단위). |
| height | float | 새 OLE 프레임의 높이(포인트 단위). |
| className | java.lang.String | OLE 개체의 클래스 이름. |
| path | java.lang.String | 링크된 파일의 경로. |

이 경로는 프레젠테이션에 그대로 저장됩니다. 상대 경로가 지정된 경우, 다른 디렉터리에서 프레젠테이션을 열면 파일에 접근할 수 없습니다.

**반환값:**
[IOleObjectFrame](../../com.aspose.slides/ioleobjectframe) - 새로 생성된 OLE 개체 프레임.
### addVideoFrame(float x, float y, float width, float height, String fname) {#addVideoFrame-float-float-float-float-java.lang.String-}
```
public final IVideoFrame addVideoFrame(float x, float y, float width, float height, String fname)
```

새 비디오 프레임을 생성하고 shape 컬렉션의 끝에 추가합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| x | float | 새 비디오 프레임의 x 좌표(포인트 단위). |
| y | float | 새 비디오 프레임의 y 좌표(포인트 단위). |
| width | float | 새 비디오 프레임의 너비(포인트 단위). |
| height | float | 새 비디오 프레임의 높이(포인트 단위). |
| fname | java.lang.String | 삽입할 비디오 파일의 경로 또는 이름. |

**반환값:**
[IVideoFrame](../../com.aspose.slides/ivideoframe) - 새로 생성된 [IVideoFrame](../../com.aspose.slides/ivideoframe).
### addVideoFrame(float x, float y, float width, float height, IVideo video) {#addVideoFrame-float-float-float-float-com.aspose.slides.IVideo-}
```
public final IVideoFrame addVideoFrame(float x, float y, float width, float height, IVideo video)
```

새 비디오 프레임을 생성하고 shape 컬렉션의 끝에 추가합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| x | float | 새 비디오 프레임의 x 좌표(포인트 단위). |
| y | float | 새 비디오 프레임의 y 좌표(포인트 단위). |
| width | float | 새 비디오 프레임의 너비(포인트 단위). |
| height | float | 새 비디오 프레임의 높이(포인트 단위). |
| video | [IVideo](../../com.aspose.slides/ivideo) | 비디오 프레임에 삽입할 [IVideo](../../com.aspose.slides/ivideo). |

**반환값:**
[IVideoFrame](../../com.aspose.slides/ivideoframe) - 새로 생성된 [IVideoFrame](../../com.aspose.slides/ivideoframe).
### insertVideoFrame(int index, float x, float y, float width, float height, String fname) {#insertVideoFrame-int-float-float-float-float-java.lang.String-}
```
public final IVideoFrame insertVideoFrame(int index, float x, float y, float width, float height, String fname)
```

새 비디오 프레임을 생성하고 지정된 인덱스에 shape 컬렉션에 삽입합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| index | int | 비디오 프레임을 삽입할 0 기반 인덱스. |
| x | float | 새 비디오 프레임의 x 좌표(포인트 단위). |
| y | float | 새 비디오 프레임의 y 좌표(포인트 단위). |
| width | float | 새 비디오 프레임의 너비(포인트 단위). |
| height | float | 새 비디오 프레임의 높이(포인트 단위). |
| fname | java.lang.String | 삽입할 비디오 파일의 경로 또는 이름. |

**반환값:**
[IVideoFrame](../../com.aspose.slides/ivideoframe) - 새로 생성된 [IVideoFrame](../../com.aspose.slides/ivideoframe).
### addAudioFrameCD(float x, float y, float width, float height) {#addAudioFrameCD-float-float-float-float-}
```
public final IAudioFrame addAudioFrameCD(float x, float y, float width, float height)
```

CD 트랙에 연결된 새 오디오 프레임을 생성하고 shape 컬렉션의 끝에 추가합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| x | float | 새 오디오 프레임의 x 좌표(포인트 단위). |
| y | float | 새 오디오 프레임의 y 좌표(포인트 단위). |
| width | float | 새 오디오 프레임의 너비(포인트 단위). |
| height | float | 새 오디오 프레임의 높이(포인트 단위). |

**반환값:**
[IAudioFrame](../../com.aspose.slides/iaudioframe) - 새로 생성된 [IAudioFrame](../../com.aspose.slides/iaudioframe).
### insertAudioFrameCD(int index, float x, float y, float width, float height) {#insertAudioFrameCD-int-float-float-float-float-}
```
public final IAudioFrame insertAudioFrameCD(int index, float x, float y, float width, float height)
```

CD 트랙에 연결된 새 오디오 프레임을 생성하고 지정된 인덱스에 shape 컬렉션에 삽입합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| index | int | 오디오 프레임을 삽입할 0 기반 인덱스. |
| x | float | 새 오디오 프레임의 x 좌표(포인트 단위). |
| y | float | 새 오디오 프레임의 y 좌표(포인트 단위). |
| width | float | 새 오디오 프레임의 너비(포인트 단위). |
| height | float | 새 오디오 프레임의 높이(포인트 단위). |

**반환값:**
[IAudioFrame](../../com.aspose.slides/iaudioframe) - 새로 생성된 [IAudioFrame](../../com.aspose.slides/iaudioframe).
### addAudioFrameLinked(float x, float y, float width, float height, String fname) {#addAudioFrameLinked-float-float-float-float-java.lang.String-}
```
public final IAudioFrame addAudioFrameLinked(float x, float y, float width, float height, String fname)
```

외부 오디오 파일에 연결된 새 오디오 프레임을 생성하고 shape 컬렉션의 끝에 추가합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| x | float | 새 오디오 프레임의 x 좌표(포인트 단위). |
| y | float | 새 오디오 프레임의 y 좌표(포인트 단위). |
| width | float | 새 오디오 프레임의 너비(포인트 단위). |
| height | float | 새 오디오 프레임의 높이(포인트 단위). |
| fname | java.lang.String | 링크할 외부 오디오 파일의 경로 또는 이름. |

**반환값:**
[IAudioFrame](../../com.aspose.slides/iaudioframe) - 새로 생성된 [IAudioFrame](../../com.aspose.slides/iaudioframe).
### insertAudioFrameLinked(int index, float x, float y, float width, float height, String fname) {#insertAudioFrameLinked-int-float-float-float-float-java.lang.String-}
```
public final IAudioFrame insertAudioFrameLinked(int index, float x, float y, float width, float height, String fname)
```

외부 오디오 파일에 연결된 새 오디오 프레임을 생성하고 지정된 인덱스에 shape 컬렉션에 삽입합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| index | int | 오디오 프레임을 삽입할 0 기반 인덱스. |
| x | float | 새 오디오 프레임의 x 좌표(포인트 단위). |
| y | float | 새 오디오 프레임의 y 좌표(포인트 단위). |
| width | float | 새 오디오 프레임의 너비(포인트 단위). |
| height | float | 새 오디오 프레임의 높이(포인트 단위). |
| fname | java.lang.String | 링크할 외부 오디오 파일의 경로 또는 이름. |

**반환값:**
[IAudioFrame](../../com.aspose.slides/iaudioframe) - 새로 생성된 [IAudioFrame](../../com.aspose.slides/iaudioframe).
### addAudioFrameEmbedded(float x, float y, float width, float height, InputStream audio_stream) {#addAudioFrameEmbedded-float-float-float-float-java.io.InputStream-}
```
public final IAudioFrame addAudioFrameEmbedded(float x, float y, float width, float height, InputStream audio_stream)
```

내장된 WAV 파일이 있는 새 오디오 프레임을 생성하고 shape 컬렉션의 끝에 추가합니다. 내장된 오디오는 Presentation.Audios 컬렉션에 추가됩니다.

--------------------

> ```
> 다음 예제는 오디오 프레임을 생성하는 방법을 보여줍니다.
>  
>  // 프레젠테이션 파일을 나타내는 Presentation 클래스를 인스턴스화합니다
>  Presentation pres = new Presentation();
>  try {
>      // 첫 번째 슬라이드를 가져옵니다
>      ISlide sld = pres.getSlides().get_Item(0);
>      // wav 사운드 파일을 스트림으로 로드합니다
>      FileInputStream fstr = new FileInputStream("sampleaudio.wav");
>      try {
>          // 오디오 프레임을 추가합니다
>          IAudioFrame audioFrame = sld.getShapes().addAudioFrameEmbedded(50, 150, 100, 100, fstr);
>          // 오디오의 재생 모드와 볼륨을 설정합니다
>          audioFrame.setPlayMode(AudioPlayModePreset.Auto);
>          audioFrame.setVolume(AudioVolumeMode.Loud);
>      } finally {
>          if (fstr != null) fstr.close();
>      }
>      // PowerPoint 파일을 디스크에 저장합니다
>      pres.save("AudioFrameEmbed_out.pptx", SaveFormat.Pptx);
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| x | float | 새 오디오 프레임의 x 좌표(포인트 단위). |
| y | float | 새 오디오 프레임의 y 좌표(포인트 단위). |
| width | float | 새 오디오 프레임의 너비(포인트 단위). |
| height | float | 새 오디오 프레임의 높이(포인트 단위). |
| audio_stream | java.io.InputStream | WAV 오디오 데이터를 포함하는 입력 스트림. |

**반환값:**
[IAudioFrame](../../com.aspose.slides/iaudioframe) - 새로 생성된 [IAudioFrame](../../com.aspose.slides/iaudioframe).
### insertAudioFrameEmbedded(int index, float x, float y, float width, float height, InputStream audio_stream) {#insertAudioFrameEmbedded-int-float-float-float-float-java.io.InputStream-}
```
public final IAudioFrame insertAudioFrameEmbedded(int index, float x, float y, float width, float height, InputStream audio_stream)
```

내장된 WAV 파일이 있는 새 오디오 프레임을 생성하고 지정된 인덱스에 shape 컬렉션에 삽입합니다. 내장된 오디오는 Presentation.Audios 컬렉션에 추가됩니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| index | int | 오디오 프레임을 삽입할 0 기반 인덱스. |
| x | float | 새 오디오 프레임의 x 좌표(포인트 단위). |
| y | float | 새 오디오 프레임의 y 좌표(포인트 단위). |
| width | float | 새 오디오 프레임의 너비(포인트 단위). |
| height | float | 새 오디오 프레임의 높이(포인트 단위). |
| audio_stream | java.io.InputStream | WAV 오디오 데이터를 포함하는 입력 스트림. |

**반환값:**
[IAudioFrame](../../com.aspose.slides/iaudioframe) - 새로 생성된 [IAudioFrame](../../com.aspose.slides/iaudioframe).
### addAudioFrameEmbedded(float x, float y, float width, float height, IAudio audio) {#addAudioFrameEmbedded-float-float-float-float-com.aspose.slides.IAudio-}
```
public final IAudioFrame addAudioFrameEmbedded(float x, float y, float width, float height, IAudio audio)
```

Presentation.Audios 목록에서 기존 오디오 객체를 사용하여 새 오디오 프레임을 생성하고 shape 컬렉션의 끝에 추가합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| x | float | 새 오디오 프레임의 x 좌표(포인트 단위). |
| y | float | 새 오디오 프레임의 y 좌표(포인트 단위). |
| width | float | 새 오디오 프레임의 너비(포인트 단위). |
| height | float | 새 오디오 프레임의 높이(포인트 단위). |
| audio | [IAudio](../../com.aspose.slides/iaudio) | Presentation.Audios 컬렉션의 [IAudio](../../com.aspose.slides/iaudio) 인스턴스. |

**반환값:**
[IAudioFrame](../../com.aspose.slides/iaudioframe) - 새로 생성된 [IAudioFrame](../../com.aspose.slides/iaudioframe).
### insertAudioFrameEmbedded(int index, float x, float y, float width, float height, IAudio audio) {#insertAudioFrameEmbedded-int-float-float-float-float-com.aspose.slides.IAudio-}
```
public final IAudioFrame insertAudioFrameEmbedded(int index, float x, float y, float width, float height, IAudio audio)
```

Presentation.Audios 목록에서 기존 오디오 객체를 사용하여 지정된 인덱스에 shape 컬렉션에 삽입합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| index | int | 오디오 프레임을 삽입할 0 기반 인덱스. |
| x | float | 새 오디오 프레임의 x 좌표(포인트 단위). |
| y | float | 새 오디오 프레임의 y 좌표(포인트 단위). |
| width | float | 새 오디오 프레임의 너비(포인트 단위). |
| height | float | 새 오디오 프레임의 높이(포인트 단위). |
| audio | [IAudio](../../com.aspose.slides/iaudio) | Presentation.Audios 컬렉션에서 삽입할 [IAudio](../../com.aspose.slides/iaudio) 인스턴스. |

**반환값:**
[IAudioFrame](../../com.aspose.slides/iaudioframe) - 새로 생성된 [IAudioFrame](../../com.aspose.slides/iaudioframe).
### indexOf(IShape shape) {#indexOf-com.aspose.slides.IShape-}
```
public final int indexOf(IShape shape)
```

지정된 shape이 컬렉션에 처음 나타나는 0 기반 인덱스를 반환합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| shape | [IShape](../../com.aspose.slides/ishape) | 컬렉션에서 찾을 shape. |

**반환값:**
int - 찾은 경우 shape 컬렉션에서 shape이 처음 나타나는 0 기반 인덱스; 찾지 못한 경우 \\u20131.
### toArray() {#toArray--}
```
public final IShape[] toArray()
```

모든 shape을 포함하는 배열을 생성하고 반환합니다.

**반환값:**
com.aspose.slides.IShape[] - [IShape](../../com.aspose.slides/ishape) 객체 배열.
### toArray(int startIndex, int count) {#toArray-int-int-}
```
public final IShape[] toArray(int startIndex, int count)
```

지정된 범위에 있는 모든 shape을 포함하는 배열을 생성하고 반환합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| startIndex | int | 반환할 첫 번째 shape의 인덱스. |
| count | int | 반환할 shape 수. |

**반환값:**
com.aspose.slides.IShape[] - [IShape](../../com.aspose.slides/ishape) 객체 배열.
### reorder(int index, IShape shape) {#reorder-int-com.aspose.slides.IShape-}
```
public final void reorder(int index, IShape shape)
```

지정된 shape을 shape 컬렉션 내 새 위치로 이동합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| index | int | shape이 배치될 0 기반 목표 인덱스. |
| shape | [IShape](../../com.aspose.slides/ishape) | 컬렉션 내에서 이동할 [IShape](../../com.aspose.slides/ishape). |

### reorder(int index, IShape[] shapes) {#reorder-int-com.aspose.slides.IShape...-}
```
public final void reorder(int index, IShape[] shapes)
```

지정된 shape 배열을 shape 컬렉션 내에서 이동시키며, 지정된 인덱스부터 배치합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| index | int | 첫 번째 지정된 shape이 배치될 0 기반 목표 인덱스; 이후 shape은 제공된 순서대로 배치됩니다. |
| 도형 | [IShape\[\]](../../com.aspose.slides/ishape) | 컬렉션 내에서 이동할 수 있는 하나 이상의 [IShape](../../com.aspose.slides/ishape) 인스턴스. |

### addAutoShape(int shapeType, float x, float y, float width, float height) {#addAutoShape-int-float-float-float-float-}
```
public final IAutoShape addAutoShape(int shapeType, float x, float y, float width, float height)
```

새 자동 도형을 기본 서식으로 생성하고 도형 컬렉션의 끝에 추가합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| shapeType | int | 추가할 자동 도형의 [ShapeType](../../com.aspose.slides/shapetype). |
| x | float | 도형 프레임의 x 좌표(포인트 단위). |
| y | float | 도형 프레임의 y 좌표(포인트 단위). |
| width | float | 도형 프레임의 너비(포인트 단위). |
| height | float | 도형 프레임의 높이(포인트 단위). |

**반환값:**
[IAutoShape](../../com.aspose.slides/iautoshape) - 새로 생성된 [IAutoShape](../../com.aspose.slides/iautoshape).

### addAutoShape(int shapeType, float x, float y, float width, float height, boolean createFromTemplate) {#addAutoShape-int-float-float-float-float-boolean-}
```
public final IAutoShape addAutoShape(int shapeType, float x, float y, float width, float height, boolean createFromTemplate)
```

새 자동 도형을 생성하고 도형 컬렉션의 끝에 추가하며, 필요에 따라 기본 템플릿 서식으로 초기화합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| shapeType | int | 추가할 자동 도형의 [ShapeType](../../com.aspose.slides/shapetype). |
| x | float | 도형 프레임의 x 좌표(포인트 단위). |
| y | float | 도형 프레임의 y 좌표(포인트 단위). |
| width | float | 도형 프레임의 너비(포인트 단위). |
| height | float | 도형 프레임의 높이(포인트 단위). |
| createFromTemplate | boolean | true이면 기본 템플릿 스타일(단순 스타일, 중앙 정렬 텍스트, 비어 있지 않은 이름)을 새 도형에 적용하고, false이면 모든 속성을 기본값으로 설정하여 도형을 생성합니다. |

**반환값:**
[IAutoShape](../../com.aspose.slides/iautoshape) - 새로 생성된 [IAutoShape](../../com.aspose.slides/iautoshape).

### addMathShape(float x, float y, float width, float height) {#addMathShape-float-float-float-float-}
```
public final IAutoShape addMathShape(float x, float y, float width, float height)
```

수학 콘텐츠를 담을 새 사각형 자동 도형을 생성하고 도형 컬렉션의 끝에 추가합니다.

--------------------

> ```
> 다음 예제는 PowerPoint 프레젠테이션에 수학 방정식을 추가하는 방법을 보여줍니다.
>  
>  Presentation pres = new Presentation();
>  try {
>      IAutoShape mathShape = pres.getSlides().get_Item(0).getShapes().addMathShape(0, 0, 720, 150);
>      IMathParagraph mathParagraph = ((MathPortion)mathShape.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0)).getMathParagraph();
>      IMathFraction fraction = new MathematicalText("x").divide("y");
>      mathParagraph.add(new MathBlock(fraction));
>      IMathBlock mathBlock = new MathematicalText("c")
>          .setSuperscript("2")
>          .join("=")
>          .join(new MathematicalText("a").setSuperscript("2"))
>          .join("+")
>          .join(new MathematicalText("b").setSuperscript("2"));
>      mathParagraph.add(mathBlock);
>      pres.save("math.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| x | float | 도형 프레임의 x 좌표(포인트 단위). |
| y | float | 도형 프레임의 y 좌표(포인트 단위). |
| width | float | 도형 프레임의 너비(포인트 단위). |
| height | float | 도형 프레임의 높이(포인트 단위). |

**반환값:**
[IAutoShape](../../com.aspose.slides/iautoshape) - 새로 생성된 [IAutoShape](../../com.aspose.slides/iautoshape).

### insertAutoShape(int index, int shapeType, float x, float y, float width, float height) {#insertAutoShape-int-int-float-float-float-float-}
```
public final IAutoShape insertAutoShape(int index, int shapeType, float x, float y, float width, float height)
```

새 자동 도형을 생성하고 지정된 인덱스에 삽입하면서 기본 템플릿 서식을 적용합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| index | int | 새 자동 도형을 삽입할 0 기반 인덱스. |
| shapeType | int | 삽입할 자동 도형의 [ShapeType](../../com.aspose.slides/shapetype). |
| x | float | 도형 프레임의 x 좌표(포인트 단위). |
| y | float | 도형 프레임의 y 좌표(포인트 단위). |
| width | float | 도형 프레임의 너비(포인트 단위). |
| height | float | 도형 프레임의 높이(포인트 단위). |

**반환값:**
[IAutoShape](../../com.aspose.slides/iautoshape) - 새로 생성된 [IAutoShape](../../com.aspose.slides/iautoshape).

### insertAutoShape(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate) {#insertAutoShape-int-int-float-float-float-float-boolean-}
```
public final IAutoShape insertAutoShape(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate)
```

새 자동 도형을 생성하고 지정된 인덱스에 삽입하며, 필요에 따라 기본 템플릿 스타일로 초기화합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| index | int | 자동 도형을 삽입할 0 기반 인덱스. |
| shapeType | int | 삽입할 자동 도형의 [ShapeType](../../com.aspose.slides/shapetype). |
| x | float | 도형 프레임의 x 좌표(포인트 단위). |
| y | float | 도형 프레임의 y 좌표(포인트 단위). |
| width | float | 도형 프레임의 너비(포인트 단위). |
| height | float | 도형 프레임의 높이(포인트 단위). |
| createFromTemplate | boolean | true이면 기본 템플릿 스타일(비어 있지 않은 이름, 단순 스타일, 중앙 정렬 텍스트)을 적용하고, false이면 모든 속성을 기본값으로 설정하여 도형을 생성합니다. |

**반환값:**
[IAutoShape](../../com.aspose.slides/iautoshape) - 새로 생성된 [IAutoShape](../../com.aspose.slides/iautoshape).

### addGroupShape() {#addGroupShape--}
```
public final IGroupShape addGroupShape()
```

새 빈 그룹 도형을 생성하고 도형 컬렉션의 끝에 추가합니다. 그룹의 프레임은 추가된 모든 도형에 맞게 자동으로 조정됩니다.

--------------------

> ```
> 다음 예제는 PowerPoint 프레젠테이션 슬라이드에 그룹 도형을 추가하는 방법을 보여줍니다.
>  
>  // Presentation 클래스를 인스턴스화합니다
>  Presentation pres = new Presentation();
>  try {
>      // 첫 번째 슬라이드를 가져옵니다
>      ISlide sld = pres.getSlides().get_Item(0);
>      // 슬라이드의 도형 컬렉션에 접근합니다
>      IShapeCollection slideShapes = sld.getShapes();
>      // 슬라이드에 그룹 도형을 추가합니다
>      IGroupShape groupShape = slideShapes.addGroupShape();
>      // 추가된 그룹 도형 내부에 도형을 추가합니다
>      groupShape.getShapes().addAutoShape(ShapeType.Rectangle, 300, 100, 100, 100);
>      groupShape.getShapes().addAutoShape(ShapeType.Rectangle, 500, 100, 100, 100);
>      groupShape.getShapes().addAutoShape(ShapeType.Rectangle, 300, 300, 100, 100);
>      groupShape.getShapes().addAutoShape(ShapeType.Rectangle, 500, 300, 100, 100);
>      // 그룹 도형 프레임을 추가합니다
>      groupShape.setFrame(new ShapeFrame(100, 300, 500, 40, NullableBool.False, NullableBool.False, 0));
>      // PPTX 파일을 디스크에 저장합니다
>      pres.save("GroupShape_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**반환값:**
[IGroupShape](../../com.aspose.slides/igroupshape) - 새로 생성된 [IGroupShape](../../com.aspose.slides/igroupshape).

### addGroupShape(ISvgImage svgImage, float x, float y, float width, float height) {#addGroupShape-com.aspose.slides.ISvgImage-float-float-float-float-}
```
public final IGroupShape addGroupShape(ISvgImage svgImage, float x, float y, float width, float height)
```

새 그룹 도형을 생성하고 지정된 SVG 이미지를 개별 도형으로 변환한 뒤, 결과 그룹을 도형 컬렉션의 끝에 추가합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| svgImage | [ISvgImage](../../com.aspose.slides/isvgimage) | 도형으로 변환할 벡터 콘텐츠가 포함된 [ISvgImage](../../com.aspose.slides/isvgimage). |
| x | float | 그룹 프레임의 x 좌표(포인트 단위). |
| y | float | 그룹 프레임의 y 좌표(포인트 단위). |
| width | float | 그룹 프레임의 너비(포인트 단위). |
| height | float | 그룹 프레임의 높이(포인트 단위). |

**반환값:**
[IGroupShape](../../com.aspose.slides/igroupshape) - 새로 생성된 [IGroupShape](../../com.aspose.slides/igroupshape).

### insertGroupShape(int index) {#insertGroupShape-int-}
```
public final IGroupShape insertGroupShape(int index)
```

새 빈 그룹 도형을 생성하고 지정된 인덱스에 삽입합니다. 그룹의 프레임은 추가된 모든 도형에 맞게 자동으로 조정됩니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| index | int | 그룹 도형을 삽입할 0 기반 인덱스. |

**반환값:**
[IGroupShape](../../com.aspose.slides/igroupshape) - 새로 생성된 [IGroupShape](../../com.aspose.slides/igroupshape).

### addConnector(int shapeType, float x, float y, float width, float height) {#addConnector-int-float-float-float-float-}
```
public final IConnector addConnector(int shapeType, float x, float y, float width, float height)
```

기본 템플릿 스타일을 적용한 새 연결 도형을 생성하고 도형 컬렉션의 끝에 추가합니다.

--------------------

> ```
> The following example shows how to add a connector (a bent connector) between two shapes (an ellipse and rectangle) in PowerPoint Presentation.
>  
>  // Instantiates a presentation class that represents a PPTX file
>  Presentation pres = new Presentation();
>  try {
>      // Accesses the shapes collection for a specific slide
>      IShapeCollection shapes = pres.getSlides().get_Item(0).getShapes();
>      // Adds an Ellipse autoshape
>      IAutoShape ellipse = shapes.addAutoShape(ShapeType.Ellipse, 0, 100, 100, 100);
>      // Adds a Rectangle autoshape
>      IAutoShape rectangle = shapes.addAutoShape(ShapeType.Rectangle, 100, 300, 100, 100);
>      // Adds a connector shape to the slide shape collection
>      IConnector connector = shapes.addConnector(ShapeType.BentConnector2, 0, 0, 10, 10);
>      // Connects the shapes using the connector
>      connector.setStartShapeConnectedTo(ellipse);
>      connector.setEndShapeConnectedTo(rectangle);
>      // Calls reroute that sets the automatic shortest path between shapes
>      connector.reroute();
>      // Saves the presentation
>      pres.save("Shapes-connector.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| shapeType | int | 추가할 연결 도형의 [ShapeType](../../com.aspose.slides/shapetype). |
| x | float | 연결 도형 프레임의 x 좌표(포인트 단위). |
| y | float | 연결 도형 프레임의 y 좌표(포인트 단위). |
| width | float | 연결 도형 프레임의 너비(포인트 단위). |
| height | float | 연결 도형 프레임의 높이(포인트 단위). |

**반환값:**
[IConnector](../../com.aspose.slides/iconnector) - 새로 생성된 [IConnector](../../com.aspose.slides/iconnector).

### addConnector(int shapeType, float x, float y, float width, float height, boolean createFromTemplate) {#addConnector-int-float-float-float-float-boolean-}
```
public final IConnector addConnector(int shapeType, float x, float y, float width, float height, boolean createFromTemplate)
```

새 연결 도형을 생성하고 도형 컬렉션의 끝에 추가하며, 필요에 따라 기본 템플릿 스타일을 적용합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| shapeType | int | 생성할 연결 도형의 [ShapeType](../../com.aspose.slides/shapetype). |
| x | float | 연결 도형 프레임의 x 좌표(포인트 단위). |
| y | float | 연결 도형 프레임의 y 좌표(포인트 단위). |
| width | float | 연결 도형 프레임의 너비(포인트 단위). |
| height | float | 연결 도형 프레임의 높이(포인트 단위). |
| createFromTemplate | boolean | true이면 기본 템플릿 스타일(비어 있지 않은 이름, 단순 스타일)을 적용하고, false이면 기본 속성 값으로 연결 도형을 생성합니다. |

**반환값:**
[IConnector](../../com.aspose.slides/iconnector) - 새로 생성된 [IConnector](../../com.aspose.slides/iconnector).

### insertConnector(int index, int shapeType, float x, float y, float width, float height) {#insertConnector-int-int-float-float-float-float-}
```
public final IConnector insertConnector(int index, int shapeType, float x, float y, float width, float height)
```

새 연결 도형을 생성하고 지정된 인덱스에 삽입하면서 기본 템플릿 스타일을 적용합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| index | int | 연결 도형을 삽입할 0 기반 인덱스. |
| shapeType | int | 삽입할 연결 도형의 [ShapeType](../../com.aspose.slides/shapetype). |
| x | float | 연결 도형 프레임의 x 좌표(포인트 단위). |
| y | float | 연결 도형 프레임의 y 좌표(포인트 단위). |
| width | float | 연결 도형 프레임의 너비(포인트 단위). |
| height | float | 연결 도형 프레임의 높이(포인트 단위). |

**반환값:**
[IConnector](../../com.aspose.slides/iconnector) - 새로 생성된 [IConnector](../../com.aspose.slides/iconnector).

### insertConnector(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate) {#insertConnector-int-int-float-float-float-float-boolean-}
```
public final IConnector insertConnector(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate)
```

새 연결 도형을 생성하고 지정된 인덱스에 삽입하며, 필요에 따라 기본 템플릿 스타일을 적용합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| index | int | 연결 도형을 삽입할 0 기반 인덱스. |
| shapeType | int | 삽입할 연결 도형의 [ShapeType](../../com.aspose.slides/shapetype). |
| x | float | 연결 도형 프레임의 x 좌표(포인트 단위). |
| y | float | 연결 도형 프레임의 y 좌표(포인트 단위). |
| width | float | 연결 도형 프레임의 너비(포인트 단위). |
| height | float | 연결 도형 프레임의 높이(포인트 단위). |
| createFromTemplate | boolean | true이면 기본 템플릿 스타일(비어 있지 않은 이름, 단순 스타일)을 적용하고, false이면 기본 속성 값으로 연결 도형을 생성합니다. |

**반환값:**
[IConnector](../../com.aspose.slides/iconnector) - 새로 생성된 [IConnector](../../com.aspose.slides/iconnector).

### addPictureFrame(int shapeType, float x, float y, float width, float height, IPPImage image) {#addPictureFrame-int-float-float-float-float-com.aspose.slides.IPPImage-}
```
public final IPictureFrame addPictureFrame(int shapeType, float x, float y, float width, float height, IPPImage image)
```

지정된 이미지를 포함하는 새 사진 프레임을 생성하고 도형 컬렉션의 끝에 추가합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| shapeType | int | [ShapeType](../../com.aspose.slides/shapetype)에 포함된 도형 유형을 지정합니다. 단, 다음과 같은 모든 종류의 선은 제외합니다: ShapeType.Line, ShapeType.StraightConnector1, ShapeType.BentConnector2, ShapeType.BentConnector3, ShapeType.BentConnector4, ShapeType.BentConnector5, ShapeType.CurvedConnector2, ShapeType.CurvedConnector3, ShapeType.CurvedConnector4, ShapeType.CurvedConnector5. |
| x | float | 사진 프레임의 x 좌표(포인트 단위). |
| y | float | 사진 프레임의 y 좌표(포인트 단위). |
| width | float | 사진 프레임의 너비(포인트 단위). |
| height | float | 사진 프레임의 높이(포인트 단위). |
| image | [IPPImage](../../com.aspose.slides/ippimage) | 사진 프레임에 표시할 [IPPImage](../../com.aspose.slides/ippimage). |

**반환값:**
[IPictureFrame](../../com.aspose.slides/ipictureframe) - 새로 생성된 [IPictureFrame](../../com.aspose.slides/ipictureframe).

### insertPictureFrame(int index, int shapeType, float x, float y, float width, float height, IPPImage image) {#insertPictureFrame-int-int-float-float-float-float-com.aspose.slides.IPPImage-}
```
public final IPictureFrame insertPictureFrame(int index, int shapeType, float x, float y, float width, float height, IPPImage image)
```

새 사진 프레임을 생성하고 지정된 이미지를 포함한 뒤, 지정된 인덱스에 삽입합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| index | int | 사진 프레임을 삽입할 0 기반 인덱스. |
| shapeType | int | [ShapeType](../../com.aspose.slides/shapetype)에 포함된 도형 유형을 지정합니다. 단, 다음과 같은 모든 종류의 선은 제외합니다: ShapeType.Line, ShapeType.StraightConnector1, ShapeType.BentConnector2, ShapeType.BentConnector3, ShapeType.BentConnector4, ShapeType.BentConnector5, ShapeType.CurvedConnector2, ShapeType.CurvedConnector3, ShapeType.CurvedConnector4, ShapeType.CurvedConnector5. |
| x | float | 사진 프레임의 x 좌표(포인트 단위). |
| y | float | 사진 프레임의 y 좌표(포인트 단위). |
| width | float | 사진 프레임의 너비(포인트 단위). |
| height | float | 사진 프레임의 높이(포인트 단위). |
| image | [IPPImage](../../com.aspose.slides/ippimage) | 사진 프레임에 표시할 [IPPImage](../../com.aspose.slides/ippimage). |

**반환값:**
[IPictureFrame](../../com.aspose.slides/ipictureframe) - 새로 생성된 [IPictureFrame](../../com.aspose.slides/ipictureframe).

### addTable(float x, float y, double[] columnWidths, double[] rowHeights) {#addTable-float-float-double---double---}
```
public final ITable addTable(float x, float y, double[] columnWidths, double[] rowHeights)
```

새 테이블을 생성하고 도형 컬렉션의 끝에 추가합니다.

--------------------

> ```
> 다음 예제는 PowerPoint 프레젠테이션에 테이블을 추가하는 방법을 보여줍니다.
>  
>  // PPTX 파일을 나타내는 Presentation 클래스를 인스턴스화합니다
>  Presentation pres = new Presentation();
>  try
>  {
>      // 첫 번째 슬라이드에 접근합니다
>      ISlide sld = pres.getSlides().get_Item(0);
> 
>      // 열의 너비와 행의 높이를 정의합니다
>      double[] dblCols = {50, 50, 50};
>      double[] dblRows = {50, 30, 30, 30, 30};
> 
>      // 슬라이드에 테이블 도형을 추가합니다
>      ITable tbl = sld.getShapes().addTable(100, 50, dblCols, dblRows);
> 
>      // 각 셀에 대한 테두리 형식을 설정합니다
>      for (int row = 0; row < tbl.getRows().size(); row++)
>      {
>          for (int cell = 0; cell < tbl.getRows().get_Item(row).size(); cell++)
>          {
>              tbl.get_Item(cell, row).getCellFormat().getBorderTop().getFillFormat().setFillType(FillType.Solid);
>              tbl.get_Item(cell, row).getCellFormat().getBorderTop().getFillFormat().getSolidFillColor().setColor(Color.RED);
>              tbl.get_Item(cell, row).getCellFormat().getBorderTop().setWidth(5);
> 
>              tbl.get_Item(cell, row).getCellFormat().getBorderBottom().getFillFormat().setFillType((FillType.Solid));
>              tbl.get_Item(cell, row).getCellFormat().getBorderBottom().getFillFormat().getSolidFillColor().setColor(Color.RED);
>              tbl.get_Item(cell, row).getCellFormat().getBorderBottom().setWidth(5);
> 
>              tbl.get_Item(cell, row).getCellFormat().getBorderLeft().getFillFormat().setFillType(FillType.Solid);
>              tbl.get_Item(cell, row).getCellFormat().getBorderLeft().getFillFormat().getSolidFillColor().setColor(Color.RED);
>              tbl.get_Item(cell, row).getCellFormat().getBorderLeft().setWidth(5);
> 
>              tbl.get_Item(cell, row).getCellFormat().getBorderRight().getFillFormat().setFillType(FillType.Solid);
>              tbl.get_Item(cell, row).getCellFormat().getBorderRight().getFillFormat().getSolidFillColor().setColor(Color.RED);
>              tbl.get_Item(cell, row).getCellFormat().getBorderRight().setWidth(5);
>          }
>      }
>      // 1행의 셀 1과 2를 병합합니다
>      tbl.mergeCells(tbl.get_Item(0, 0), tbl.get_Item(1, 1), false);
> 
>      // 병합된 셀에 텍스트를 추가합니다
>      tbl.get_Item(0, 0).getTextFrame().setText("Merged Cells");
> 
>      // PPTX를 디스크에 저장합니다
>      pres.save("table.pptx", SaveFormat.Pptx);
>  }
>  finally
>  {
>      if (pres != null) pres.dispose();
>  }
> ```

**매개변수:**
| Parameter | Type | Description |
| --- | --- | --- |
| x | float | 테이블의 x 좌표(포인트 단위)입니다. |
| y | float | 테이블의 y 좌표(포인트 단위)입니다. |
| columnWidths | double[] | 테이블 열의 너비를 포인트 단위로 나타낸 double 배열입니다. |
| rowHeights | double[] | 테이블 행의 높이를 포인트 단위로 나타낸 double 배열입니다. |

**반환값:**
[ITable](../../com.aspose.slides/itable) - 새로 생성된 [ITable](../../com.aspose.slides/itable).
### insertTable(int index, float x, float y, double[] columnWidths, double[] rowHeights) {#insertTable-int-float-float-double---double---}
```
public final ITable insertTable(int index, float x, float y, double[] columnWidths, double[] rowHeights)
```

새 테이블을 만들고 지정된 인덱스에 shape 컬렉션에 삽입합니다.

**매개변수:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | 테이블을 삽입할 0부터 시작하는 인덱스입니다. |
| x | float | 테이블의 x 좌표(포인트 단위)입니다. |
| y | float | 테이블의 y 좌표(포인트 단위)입니다. |
| columnWidths | double[] | 테이블 열의 너비를 포인트 단위로 나타낸 double 배열입니다. |
| rowHeights | double[] | 테이블 행의 높이를 포인트 단위로 나타낸 double 배열입니다. |

**반환값:**
[ITable](../../com.aspose.slides/itable) - 새로 생성된 [ITable](../../com.aspose.slides/itable).
### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

지정된 인덱스에 있는 shape을 shape 컬렉션에서 제거합니다.

**매개변수:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | 제거할 shape의 0부터 시작하는 인덱스입니다. |

### remove(IShape shape) {#remove-com.aspose.slides.IShape-}
```
public final void remove(IShape shape)
```

지정된 shape의 첫 번째 항목을 shape 컬렉션에서 제거합니다.

**매개변수:**
| Parameter | Type | Description |
| --- | --- | --- |
| shape | [IShape](../../com.aspose.slides/ishape) | 제거할 [IShape](../../com.aspose.slides/ishape). |

### clear() {#clear--}
```
public final void clear()
```

shape 컬렉션의 모든 shape을 제거합니다.

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IShape> iterator()
```

컬렉션을 순회하는 열거자를 반환합니다.

**반환값:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IShape> - 컬렉션을 순회하는 데 사용할 수 있는 IGenericEnumerator입니다.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IShape> iteratorJava()
```

전체 컬렉션에 대한 java iterator를 반환합니다.

**반환값:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IShape> - 전체 컬렉션에 대한 java.util.Iterator입니다.
### getParentGroup() {#getParentGroup--}
```
public final IGroupShape getParentGroup()
```

shape 컬렉션에 대한 상위 그룹 shape 객체를 가져옵니다. 읽기 전용 [IGroupShape](../../com.aspose.slides/igroupshape).

**반환값:**
[IGroupShape](../../com.aspose.slides/igroupshape)
### addClone(IShape sourceShape, float x, float y, float width, float height) {#addClone-com.aspose.slides.IShape-float-float-float-float-}
```
public final IShape addClone(IShape sourceShape, float x, float y, float width, float height)
```

지정된 shape의 복사본을 만들고 shape 컬렉션 끝에 추가합니다.

**매개변수:**
| Parameter | Type | Description |
| --- | --- | --- |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | 복제할 shape. |
| x | float | 새 shape의 프레임 x 좌표(포인트 단위)입니다. |
| y | float | 새 shape의 프레임 y 좌표(포인트 단위)입니다. |
| width | float | 새 shape의 프레임 너비(포인트 단위)입니다. |
| height | float | 새 shape의 프레임 높이(포인트 단위)입니다. |

**반환값:**
[IShape](../../com.aspose.slides/ishape) - 새로 생성된 [IShape](../../com.aspose.slides/ishape).
### addClone(IShape sourceShape, float x, float y) {#addClone-com.aspose.slides.IShape-float-float-}
```
public final IShape addClone(IShape sourceShape, float x, float y)
```

지정된 shape의 복사본을 만들고 shape 컬렉션 끝에 추가합니다. 새 shape은 sourceShape의 너비와 높이를 유지합니다.

**매개변수:**
| Parameter | Type | Description |
| --- | --- | --- |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | 복제할 shape. |
| x | float | 새 shape의 프레임 x 좌표(포인트 단위)입니다. |
| y | float | 새 shape의 프레임 y 좌표(포인트 단위)입니다. |

**반환값:**
[IShape](../../com.aspose.slides/ishape) - 새로 생성된 [IShape](../../com.aspose.slides/ishape).
### addClone(IShape sourceShape) {#addClone-com.aspose.slides.IShape-}
```
public final IShape addClone(IShape sourceShape)
```

지정된 shape의 복사본을 만들고 shape 컬렉션 끝에 추가합니다. 복제된 shape은 원본의 위치와 크기를 유지합니다.

**매개변수:**
| Parameter | Type | Description |
| --- | --- | --- |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | 복제할 [IShape](../../com.aspose.slides/ishape). |

**반환값:**
[IShape](../../com.aspose.slides/ishape) - 새로 생성된 [IShape](../../com.aspose.slides/ishape).
### insertClone(int index, IShape sourceShape, float x, float y, float width, float height) {#insertClone-int-com.aspose.slides.IShape-float-float-float-float-}
```
public final IShape insertClone(int index, IShape sourceShape, float x, float y, float width, float height)
```

지정된 shape의 복사본을 만들고 지정된 인덱스에 shape 컬렉션에 삽입합니다.

**매개변수:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | 클론된 shape을 삽입할 0부터 시작하는 인덱스입니다. |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | 복제할 [IShape](../../com.aspose.slides/ishape). |
| x | float | 클론된 shape의 프레임 x 좌표(포인트 단위)입니다. |
| y | float | 클론된 shape의 프레임 y 좌표(포인트 단위)입니다. |
| width | float | 클론된 shape의 프레임 너비(포인트 단위)입니다. |
| height | float | 클론된 shape의 프레임 높이(포인트 단위)입니다. |

**반환값:**
[IShape](../../com.aspose.slides/ishape) - 새로 생성된 [IShape](../../com.aspose.slides/ishape).
### insertClone(int index, IShape sourceShape, float x, float y) {#insertClone-int-com.aspose.slides.IShape-float-float-}
```
public final IShape insertClone(int index, IShape sourceShape, float x, float y)
```

지정된 shape의 복사본을 만들고 지정된 인덱스에 shape 컬렉션에 삽입합니다. 새 shape은 sourceShape의 너비와 높이를 유지합니다.

**매개변수:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | 클론된 shape을 삽입할 0부터 시작하는 인덱스입니다. |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | 복제할 [IShape](../../com.aspose.slides/ishape). |
| x | float | 클론된 shape의 프레임 x 좌표(포인트 단위)입니다. |
| y | float | 클론된 shape의 프레임 y 좌표(포인트 단위)입니다. |

**반환값:**
[IShape](../../com.aspose.slides/ishape) - 새로 생성된 [IShape](../../com.aspose.slides/ishape).
### insertClone(int index, IShape sourceShape) {#insertClone-int-com.aspose.slides.IShape-}
```
public final IShape insertClone(int index, IShape sourceShape)
```

지정된 shape의 복사본을 만들고 지정된 인덱스에 shape 컬렉션에 삽입합니다. 복제된 shape은 원본의 위치와 크기를 유지합니다.

**매개변수:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | 클론된 shape을 삽입할 0부터 시작하는 인덱스입니다. |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | 복제할 [IShape](../../com.aspose.slides/ishape). |

**반환값:**
[IShape](../../com.aspose.slides/ishape) - 새로 생성된 [IShape](../../com.aspose.slides/ishape).
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

컬렉션의 모든 요소를 지정된 배열에 복사합니다.

**매개변수:**
| Parameter | Type | Description |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | 대상 배열. |
| index | int | 대상 배열의 시작 인덱스. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

컬렉션에 대한 접근이 동기화(스레드 안전)되어 있는지 여부를 나타내는 값을 반환합니다. 읽기 전용 boolean.

**반환값:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

동기화 루트를 반환합니다. 읽기 전용 Object.

**반환값:**
java.lang.Object