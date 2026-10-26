---
title: Presentation
second_title: Java API 레퍼런스를 통한 Android용 Aspose.Slides
description: Microsoft PowerPoint 프레젠테이션을 나타냅니다.
type: docs
url: /ko/com.aspose.slides/presentation/
---
**상속:**  
java.lang.Object

**모든 구현된 인터페이스:**  
[com.aspose.slides.IPresentation](../../com.aspose.slides/ipresentation), com.aspose.slides.IDOMObject
```
public final class Presentation implements IPresentation, IDOMObject
```

Microsoft PowerPoint 프레젠테이션을 나타냅니다.

--------------------

> ```
> The following example shows how to create PowerPoint Presentation.
>   
>  // 프레젠테이션 파일을 나타내는 Presentation 객체를 인스턴스화합니다
>  Presentation pres = new Presentation();
>  try {
>      // 첫 번째 슬라이드를 가져옵니다
>      ISlide slide = pres.getSlides().get_Item(0);
>      // 라인 타입 자동 도형을 추가합니다
>      slide.getShapes().addAutoShape(ShapeType.Line, 50, 150, 300, 0);
>      // 프레젠테이션 파일을 저장합니다.
>      pres.save("NewPresentation_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>   
>   The following example shows how to open and save Presentation.
>   
>  // 프레젠테이션에서 지원되는 모든 파일을 로드합니다. 예: ppt, pptx, odp 등
>  Presentation pres = new Presentation("Sample.odp");
>  try {
>      // 프레젠테이션 파일을 저장합니다.
>      pres.save("OutputPresenation.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

## 생성자

| 생성자 | 설명 |
| --- | --- |
| [Presentation()](#Presentation--) | 이 생성자는 새 프레젠테이션을 처음부터 생성합니다. |
| [Presentation(LoadOptions loadOptions)](#Presentation-com.aspose.slides.LoadOptions-) | 이 생성자는 새 프레젠테이션을 처음부터 생성합니다. |
| [Presentation(InputStream stream)](#Presentation-java.io.InputStream-) | 이 생성자는 기존 프레젠테이션을 읽는 주요 메커니즘입니다. |
| [Presentation(InputStream stream, LoadOptions loadOptions)](#Presentation-java.io.InputStream-com.aspose.slides.LoadOptions-) | 이 생성자는 기존 프레젠테이션을 읽는 주요 메커니즘입니다. |
| [Presentation(String file)](#Presentation-java.lang.String-) | 이 생성자는 프레젠테이션 내용이 읽히는 소스 파일 경로를 가져옵니다. |
| [Presentation(String file, LoadOptions loadOptions)](#Presentation-java.lang.String-com.aspose.slides.LoadOptions-) | 이 생성자는 프레젠테이션 내용이 읽히는 소스 파일 경로를 가져옵니다. |

## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getCurrentDateTime()](#getCurrentDateTime--) | 날짜와 시간을 반환하거나 설정합니다. 이 값은 datetime 필드의 내용을 대체합니다. |
| [setCurrentDateTime(Date value)](#setCurrentDateTime-java.util.Date-) | 날짜와 시간을 반환하거나 설정합니다. 이 값은 datetime 필드의 내용을 대체합니다. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | 실제 HeaderFooter 관리자를 반환합니다. |
| [getProtectionManager()](#getProtectionManager--) | 이 프레젠테이션에 대한 권한 관리자를 가져옵니다. |
| [getSlides()](#getSlides--) | 프레젠테이션에 정의된 모든 슬라이드의 목록을 반환합니다. |
| [getSections()](#getSections--) | 프레젠테이션에 정의된 모든 슬라이드 섹션의 목록을 반환합니다. |
| [getSlideSize()](#getSlideSize--) | 슬라이드 크기 객체를 반환합니다. |
| [getNotesSize()](#getNotesSize--) | 노트 슬라이드 크기 객체를 반환합니다. |
| [getLayoutSlides()](#getLayoutSlides--) | 프레젠테이션에 정의된 모든 레이아웃 슬라이드의 목록을 반환합니다. |
| [getMasters()](#getMasters--) | 프레젠테이션에 정의된 모든 마스터 슬라이드의 목록을 반환합니다. |
| [getMasterNotesSlideManager()](#getMasterNotesSlideManager--) | 노트 마스터 관리자를 반환합니다. |
| [getMasterHandoutSlideManager()](#getMasterHandoutSlideManager--) | 핸드아웃 마스터 관리자를 반환합니다. |
| [getFontsManager()](#getFontsManager--) | 폰트 관리자를 반환합니다. |
| [getDefaultTextStyle()](#getDefaultTextStyle--) | 도형에 대한 기본 텍스트 스타일을 반환합니다. |
| [getCommentAuthors()](#getCommentAuthors--) | 주석 작성자 컬렉션을 반환합니다. |
| [getDocumentProperties()](#getDocumentProperties--) | 표준 및 사용자 정의 문서 속성을 포함하는 DocumentProperties 객체를 반환합니다. |
| [getImages()](#getImages--) | 프레젠테이션에 포함된 모든 이미지 컬렉션을 반환합니다. |
| [getAudios()](#getAudios--) | 프레젠테이션에 포함된 모든 내장 오디오 파일 컬렉션을 반환합니다. |
| [getVideos()](#getVideos--) | 프레젠테이션에 포함된 모든 내장 비디오 파일 컬렉션을 반환합니다. |
| [getSlideShowSettings()](#getSlideShowSettings--) | 프레젠테이션의 슬라이드 쇼 설정을 반환합니다. |
| [getDigitalSignatures()](#getDigitalSignatures--) | 프레젠테이션 서명에 사용된 서명 컬렉션을 반환합니다. |
| [getCustomData()](#getCustomData--) | 프레젠테이션의 사용자 정의 데이터를 반환합니다. |
| [getAllCustomXmlParts()](#getAllCustomXmlParts--) | 프레젠테이션의 모든 사용자 정의 데이터 파트를 반환합니다. |
| [getVbaProject()](#getVbaProject--) | 프레젠테이션 매크로가 포함된 VBA 프로젝트를 가져오거나 설정합니다. |
| [setVbaProject(IVbaProject value)](#setVbaProject-com.aspose.slides.IVbaProject-) | 프레젠테이션 매크로가 포함된 VBA 프로젝트를 가져오거나 설정합니다. |
| [getHyperlinkQueries()](#getHyperlinkQueries--) | 모든 프레젠테이션 슬라이드(마스터, 레이아웃, 노트 슬라이드 제외)에 포함된 모든 하이퍼링크에 쉽게 접근할 수 있게 합니다. |
| [getViewProperties()](#getViewProperties--) | 프레젠테이션 전체 뷰 속성을 가져옵니다. |
| [getFirstSlideNumber()](#getFirstSlideNumber--) | 프레젠테이션의 첫 슬라이드 번호를 나타냅니다. |
| [setFirstSlideNumber(int value)](#setFirstSlideNumber-int-) | 프레젠테이션의 첫 슬라이드 번호를 나타냅니다. |
| [getSensitivityLabels()](#getSensitivityLabels--) | 프레젠테이션 문서에 적용된 민감도 레이블 컬렉션을 반환합니다. |
| [getSlideById(long id)](#getSlideById-long-) | Id에 따라 Slide, MasterSlide 또는 LayoutSlide를 반환합니다. |
| [getSourceFormat()](#getSourceFormat--) | 프레젠테이션이 로드된 형식에 대한 정보를 반환합니다. |
| [getMasterTheme()](#getMasterTheme--) | 마스터 테마를 반환합니다. |
| [save(String fname, int format)](#save-java.lang.String-int-) | 프레젠테이션의 모든 슬라이드를 지정된 형식의 파일에 저장합니다. |
| [save(OutputStream stream, int format)](#save-java.io.OutputStream-int-) | 프레젠테이션의 모든 슬라이드를 지정된 형식의 스트림에 저장합니다. |
| [save(String fname, int format, ISaveOptions options)](#save-java.lang.String-int-com.aspose.slides.ISaveOptions-) | 프레젠테이션의 모든 슬라이드를 지정된 형식 및 추가 옵션으로 파일에 저장합니다. |
| [save(OutputStream stream, int format, ISaveOptions options)](#save-java.io.OutputStream-int-com.aspose.slides.ISaveOptions-) | 프레젠테이션의 모든 슬라이드를 지정된 형식 및 추가 옵션으로 스트림에 저장합니다. |
| [save(IXamlOptions options)](#save-com.aspose.slides.IXamlOptions-) | 프레젠테이션의 모든 슬라이드를 XAML 마크업을 나타내는 파일 집합에 저장합니다. |
| [getImages(IRenderingOptions options)](#getImages-com.aspose.slides.IRenderingOptions-) | 프레젠테이션의 모든 슬라이드에 대한 Image 객체를 반환합니다. |
| [getImages(IRenderingOptions options, int[] slides)](#getImages-com.aspose.slides.IRenderingOptions-int---) | 지정된 슬라이드에 대한 썸네일 Image 객체를 반환합니다. |
| [getImages(IRenderingOptions options, float scaleX, float scaleY)](#getImages-com.aspose.slides.IRenderingOptions-float-float-) | 맞춤 스케일링으로 프레젠테이션의 모든 슬라이드에 대한 썸네일 Image 객체를 반환합니다. |
| [getImages(IRenderingOptions options, int[] slides, float scaleX, float scaleY)](#getImages-com.aspose.slides.IRenderingOptions-int---float-float-) | 맞춤 스케일링으로 지정된 슬라이드에 대한 썸네일 Image 객체를 반환합니다. |
| [getImages(IRenderingOptions options, Size imageSize)](#getImages-com.aspose.slides.IRenderingOptions-com.aspose.slides.android.Size-) | 지정된 크기로 프레젠테이션의 모든 슬라이드에 대한 썸네일 Image 객체를 반환합니다. |
| [getImages(IRenderingOptions options, int[] slides, Size imageSize)](#getImages-com.aspose.slides.IRenderingOptions-int---com.aspose.slides.android.Size-) | 지정된 크기로 지정된 슬라이드에 대한 썸네일 Image 객체를 반환합니다. |
| [save(String fname, int[] slides, int format)](#save-java.lang.String-int---int-) | 지정된 슬라이드를 페이지 번호를 유지하면서 지정된 형식의 파일에 저장합니다. |
| [save(String fname, int[] slides, int format, ISaveOptions options)](#save-java.lang.String-int---int-com.aspose.slides.ISaveOptions-) | 지정된 슬라이드를 페이지 번호를 유지하면서 지정된 형식의 파일에 저장합니다. |
| [save(OutputStream stream, int[] slides, int format)](#save-java.io.OutputStream-int---int-) | 지정된 슬라이드를 페이지 번호를 유지하면서 지정된 형식의 스트림에 저장합니다. |
| [save(OutputStream stream, int[] slides, int format, ISaveOptions options)](#save-java.io.OutputStream-int---int-com.aspose.slides.ISaveOptions-) | 지정된 슬라이드를 페이지 번호를 유지하면서 지정된 형식의 스트림에 저장합니다. |
| [joinPortionsWithSameFormatting()](#joinPortionsWithSameFormatting--) | 모든 슬라이드의 모든 허용된 도형 내 모든 단락에서 동일한 서식의 실행(run)을 결합합니다. |
| [dispose()](#dispose--) | 이 Presentation 객체가 사용한 모든 리소스를 해제합니다. |
| [getPresentation()](#getPresentation--) | 텍스트의 상위 프레젠테이션을 반환합니다. |
| [highlightText(String text, Integer highlightColor)](#highlightText-java.lang.String-java.lang.Integer-) | 샘플 텍스트와 일치하는 모든 항목을 지정된 색상으로 강조합니다. |
| [highlightText(String text, Integer highlightColor, ITextSearchOptions options, IFindResultCallback callback)](#highlightText-java.lang.String-java.lang.Integer-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-) | 샘플 텍스트와 일치하는 모든 항목을 지정된 색상으로 강조합니다. |
| [highlightRegex(Pattern regex, Integer highlightColor, IFindResultCallback callback)](#highlightRegex-java.util.regex.Pattern-java.lang.Integer-com.aspose.slides.IFindResultCallback-) | 정규식과 일치하는 모든 항목을 지정된 색상으로 강조합니다. |
| [replaceText(String oldText, String newText, ITextSearchOptions options, IFindResultCallback callback)](#replaceText-java.lang.String-java.lang.String-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-) | 지정된 텍스트의 모든 발생을 다른 지정된 텍스트로 바꿉니다. |
| [replaceRegex(Pattern regex, String newText, IFindResultCallback callback)](#replaceRegex-java.util.regex.Pattern-java.lang.String-com.aspose.slides.IFindResultCallback-) | 정규식과 일치하는 모든 항목을 지정된 문자열로 바꿉니다. |

### Presentation() {#Presentation--}
```
public Presentation()
```

이 생성자는 새 프레젠테이션을 처음부터 생성합니다. 생성된 프레젠테이션에는 빈 슬라이드가 하나 포함됩니다.

### Presentation(LoadOptions loadOptions) {#Presentation-com.aspose.slides.LoadOptions-}
```
public Presentation(LoadOptions loadOptions)
```

이 생성자는 새 프레젠테이션을 처음부터 생성합니다. 생성된 프레젠테이션에는 빈 슬라이드가 하나 포함됩니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| loadOptions | [LoadOptions](../../com.aspose.slides/loadoptions) | 추가 로드 옵션. |

### Presentation(InputStream stream) {#Presentation-java.io.InputStream-}
```
public Presentation(InputStream stream)
```

이 생성자는 기존 프레젠테이션을 읽는 주요 메커니즘입니다.

--------------------

> ```
> FileInputStream fis = new FileInputStream("demo.pptx");
>  Presentation pres = new Presentation(fis);
>  fis.close();
> ```


**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| stream | java.io.InputStream | 입력 스트림. |

### Presentation(InputStream stream, LoadOptions loadOptions) {#Presentation-java.io.InputStream-com.aspose.slides.LoadOptions-}
```
public Presentation(InputStream stream, LoadOptions loadOptions)
```

이 생성자는 기존 프레젠테이션을 읽는 주요 메커니즘입니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| stream | java.io.InputStream | 입력 스트림. |
| loadOptions | [LoadOptions](../../com.aspose.slides/loadoptions) | 추가 로드 옵션. |

### Presentation(String file) {#Presentation-java.lang.String-}
```
public Presentation(String file)
```

이 생성자는 프레젠테이션 내용이 읽히는 소스 파일 경로를 가져옵니다.

--------------------

> ```
> Presentation pres = new Presentation("demo.pptx");
> ```

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| file | java.lang.String | 입력 파일. |

### Presentation(String file, LoadOptions loadOptions) {#Presentation-java.lang.String-com.aspose.slides.LoadOptions-}
```
public Presentation(String file, LoadOptions loadOptions)
```

이 생성자는 프레젠테이션 내용이 읽히는 소스 파일 경로를 가져옵니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| file | java.lang.String | 입력 파일. |
| loadOptions | [LoadOptions](../../com.aspose.slides/loadoptions) | 추가 로드 옵션. |

### getCurrentDateTime() {#getCurrentDateTime--}
```
public final Date getCurrentDateTime()
```

날짜와 시간을 반환하거나 설정합니다. 이 값은 datetime 필드의 내용을 대체합니다. 기본값은 이 Presentation 객체가 생성된 시점의 시간입니다. 읽기/쓰기 java.util.Date.

**반환:**
java.util.Date

### setCurrentDateTime(Date value) {#setCurrentDateTime-java.util.Date-}
```
public final void setCurrentDateTime(Date value)
```

날짜와 시간을 반환하거나 설정합니다. 이 값은 datetime 필드의 내용을 대체합니다. 기본값은 이 Presentation 객체가 생성된 시점의 시간입니다. 읽기/쓰기 java.util.Date.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | java.util.Date |  |

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Parent_Immediate 객체를 반환합니다. 읽기 전용 IDOMObject.

**반환:**
com.aspose.slides.IDOMObject

### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public final IPresentationHeaderFooterManager getHeaderFooterManager()
```

실제 HeaderFooter 관리자를 반환합니다. 읽기 전용 [IPresentationHeaderFooterManager](../../com.aspose.slides/ipresentationheaderfootermanager).

--------------------

> ```
> The following example shows how to set footer visibility inside Slide of PowerPoint Presentation.
>  
>  Presentation pres = new Presentation("presentation.ppt");
>  try
>  {
>      IBaseSlideHeaderFooterManager headerFooterManager = pres.getSlides().get_Item(0).getHeaderFooterManager();
>      if (!headerFooterManager.isFooterVisible()) // Property IsFooterVisible 은 슬라이드 푸터 자리 표시자가 없음을 나타내는 데 사용됩니다.
>      {
>          headerFooterManager.setFooterVisibility(true); // Method SetFooterVisibility 은 슬라이드 푸터 자리 표시자를 보이게 만드는 데 사용됩니다.
>      }
>      if (!headerFooterManager.isSlideNumberVisible()) // Property IsSlideNumberVisible 은 슬라이드 페이지 번호 자리 표시자가 없음을 나타내는 데 사용됩니다.
>      {
>          headerFooterManager.setSlideNumberVisibility(true); // Method SetSlideNumberVisibility 은 슬라이드 페이지 번호 자리 표시자를 보이게 만드는 데 사용됩니다.
>      }
>      if (!headerFooterManager.isDateTimeVisible()) // Property IsDateTimeVisible 은 슬라이드 날짜-시간 자리 표시자가 없음을 나타내는 데 사용됩니다.
>      {
>          headerFooterManager.setDateTimeVisibility(true); // Method SetFooterVisibility 은 슬라이드 날짜-시간 자리 표시자를 보이게 만드는 데 사용됩니다.
>      }
>      headerFooterManager.setFooterText("Footer text"); // Method SetFooterText 은 슬라이드 푸터 자리 표시자에 텍스트를 설정하는 데 사용됩니다.
>      headerFooterManager.setDateTimeText("Date and time text"); // Method SetDateTimeText 은 슬라이드 날짜-시간 자리 표시자에 텍스트를 설정하는 데 사용됩니다.
>      pres.save("Presentation.ppt", SaveFormat.Ppt);
>  }
>  finally
>  {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to set child footer visibility inside Slide.
>  
>  Presentation pres = new Presentation("presentation.ppt");
>  try
>  {
>      IMasterSlideHeaderFooterManager headerFooterManager = pres.getMasters().get_Item(0).getHeaderFooterManager();
>      headerFooterManager.setFooterAndChildFootersVisibility(true); // Method SetFooterAndChildFootersVisibility 은 마스터 슬라이드와 모든 자식 푸터 자리 표시자를 보이게 만드는 데 사용됩니다.
>      headerFooterManager.setSlideNumberAndChildSlideNumbersVisibility(true); // Method SetSlideNumberAndChildSlideNumbersVisibility 은 마스터 슬라이드와 모든 자식 페이지 번호 자리 표시자를 보이게 만드는 데 사용됩니다.
>      headerFooterManager.setDateTimeAndChildDateTimesVisibility(true); // Method SetDateTimeAndChildDateTimesVisibility 은 마스터 슬라이드와 모든 자식 날짜-시간 자리 표시자를 보이게 만드는 데 사용됩니다.
> 
>      headerFooterManager.setFooterAndChildFootersText("Footer text"); // Method SetFooterAndChildFootersText 은 마스터 슬라이드와 모든 자식 푸터 자리 표시자에 텍스트를 설정하는 데 사용됩니다.
>      headerFooterManager.setDateTimeAndChildDateTimesText("Date and time text"); // Method SetDateTimeAndChildDateTimesText 은 마스터 슬라이드와 모든 자식 날짜-시간 자리 표시자에 텍스트를 설정하는 데 사용됩니다.
>  }
>  finally
>  {
>      if (pres != null) pres.dispose();
>  }
> ```


**반환:**
[IPresentationHeaderFooterManager](../../com.aspose.slides/ipresentationheaderfootermanager)

### getProtectionManager() {#getProtectionManager--}
```
public final IProtectionManager getProtectionManager()
```

이 프레젠테이션에 대한 권한 관리자를 가져옵니다. 읽기 전용 [IProtectionManager](../../com.aspose.slides/iprotectionmanager).

**반환:**
[IProtectionManager](../../com.aspose.slides/iprotectionmanager)

### getSlides() {#getSlides--}
```
public final ISlideCollection getSlides()
```

프레젠테이션에 정의된 모든 슬라이드의 목록을 반환합니다. 읽기 전용 [ISlideCollection](../../com.aspose.slides/islidecollection).

--------------------

> ```
> The following example shows how to set slides' background color of PowerPoint Presentation.
>  
>  // 프레젠테이션 파일을 나타내는 Presentation 클래스를 인스턴스화합니다
>  Presentation pres = new Presentation();
>  try
>  {
>      // 첫 번째 ISlide의 배경색을 파란색으로 설정합니다
>      pres.getSlides().get_Item(0).getBackground().setType(BackgroundType.OwnBackground);
>      pres.getSlides().get_Item(0).getBackground().getFillFormat().setFillType(FillType.Solid);
>      pres.getSlides().get_Item(0).getBackground().getFillFormat().getSolidFillColor().setColor(Color.BLUE);
>      pres.save("ContentBG_out.pptx", SaveFormat.Pptx);
>  }
>  finally
>  {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to set slides' background image of PowerPoint Presentation.
>  
>  // 프레젠테이션 파일을 나타내는 Presentation 클래스를 인스턴스화합니다
>  Presentation pres = new Presentation("SetImageAsBackground.pptx");
>  try {
>      // 이미지를 사용하여 배경을 설정합니다
>      pres.getSlides().get_Item(0).setBackground().setType(BackgroundType.OwnBackground);
>      pres.getSlides().get_Item(0).getBackground().getFillFormat().setFillType(FillType.Picture);
>      pres.getSlides().get_Item(0).getBackground().getFillFormat().getPictureFillFormat().setPictureFillMode(PictureFillMode.Stretch);
>      // 그림을 설정합니다
>      FileInputStream fos = null;
>      try {
>          fos = new FileInputStream("Tulips.jpg");
>          // 이미지를 프레젠테이션의 이미지 컬렉션에 추가합니다
>          IPPImage imgx = pres.getImages().addImage(fos);
>          pres.getSlides().get_Item(0).getBackground().getFillFormat().getPictureFillFormat().getPicture().setImage(imgx);
>      } finally {
>          if (fos != null) fos.close();
>      }
>      // 프레젠테이션을 디스크에 저장합니다
>      pres.save("ContentBG_Img_out.pptx", SaveFormat.Pptx);
>  } catch (IOException e) { }
>  finally
>  {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to add slide transition Presentation.
>  
>  // 소스 프레젠테이션 파일을 로드하기 위해 Presentation 클래스를 인스턴스화합니다
>  Presentation pres = new Presentation("AccessSlides.pptx");
>  try
>  {
>      // 슬라이드 1에 원형 전환을 적용합니다
>      pres.getSlides().get_Item(0).getSlideShowTransition().setType(TransitionType.Circle);
>      // 슬라이드 2에 comb 전환을 적용합니다
>      pres.getSlides().get_Item(1).getSlideShowTransition().setType(TransitionType.Comb);
>      // 프레젠테이션을 디스크에 저장합니다
>      pres.save("SampleTransition_out.pptx", SaveFormat.Pptx);
>  }
>  finally
>  {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to add advanced slide Transition.
>  
>  // 프레젠테이션 파일을 나타내는 Presentation 클래스를 인스턴스화합니다
>  Presentation pres = new Presentation("BetterSlideTransitions.pptx");
>  try
>  {
>      // 슬라이드 1에 원형 전환을 적용합니다
>      pres.getSlides().get_Item(0).getSlideShowTransition().setType(TransitionType.Circle);
>      // 전환 시간을 3초로 설정합니다
>      pres.getSlides().get_Item(0).getSlideShowTransition().setAdvanceOnClick(true);
>      pres.getSlides().get_Item(0).getSlideShowTransition().setAdvanceAfterTime(3000);
>      // 슬라이드 2에 comb 전환을 적용합니다
>      pres.getSlides().get_Item(1).getSlideShowTransition().setType(TransitionType.Comb);
>      // 전환 시간을 5초로 설정합니다
>      pres.getSlides().get_Item(1).getSlideShowTransition().setAdvanceOnClick(true);
>      pres.getSlides().get_Item(1).getSlideShowTransition().setAdvanceAfterTime(5000);
>      // 슬라이드 3에 확대 전환을 적용합니다
>      pres.getSlides().get_Item(2).getSlideShowTransition().setType(TransitionType.Zoom);
>      // 전환 시간을 7초로 설정합니다
>      pres.getSlides().get_Item(2).getSlideShowTransition().setAdvanceOnClick(true);
>      pres.getSlides().get_Item(2).getSlideShowTransition().setAdvanceAfterTime(7000);
>      // 프레젠테이션을 디스크에 저장합니다
>      pres.save("SampleTransition_out.pptx", SaveFormat.Pptx);
>  }
>  finally
>  {
>      if (pres != null) pres.dispose();
>  }
> ```


**반환:**
[ISlideCollection](../../com.aspose.slides/islidecollection)

### getSections() {#getSections--}
```
public final ISectionCollection getSections()
```

프레젠테이션에 정의된 모든 슬라이드 섹션의 목록을 반환합니다. 읽기 전용 [ISectionCollection](../../com.aspose.slides/isectioncollection).

--------------------

> ```
> The following examples shows how to create Sections in a PowerPoint Presentation.
>  
>  Presentation pres = new Presentation();
>  try {
>      ISlide defaultSlide = pres.getSlides().get_Item(0);
>      ISlide newSlide1 = pres.getSlides().addEmptySlide(pres.getLayoutSlides().get_Item(0));
>      ISlide newSlide2 = pres.getSlides().addEmptySlide(pres.getLayoutSlides().get_Item(0));
>      ISlide newSlide3 = pres.getSlides().addEmptySlide(pres.getLayoutSlides().get_Item(0));
>      ISlide newSlide4 = pres.getSlides().addEmptySlide(pres.getLayoutSlides().get_Item(0));
>      ISection section1 = pres.getSections().addSection("Section 1", newSlide1);
>      // section1은 newSlide2에서 끝나고 그 뒤에 section2가 시작됩니다
>      ISection section2 = pres.getSections().addSection("Section 2", newSlide3);
>      pres.save("pres-sections.pptx", SaveFormat.Pptx);
>      pres.getSections().reorderSectionWithSlides(section2, 0);
>      pres.save("pres-sections-moved.pptx", SaveFormat.Pptx);
>      pres.getSections().removeSectionWithSlides(section2);
>      pres.getSections().appendEmptySection("Last empty section");
>      pres.save("pres-section-with-empty.pptx",SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following examples shows how to changing the names of Sections.
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      ISection section = pres.getSections().get_Item(0);
>      section.setName("My section");
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**반환:**
[ISectionCollection](../../com.aspose.slides/isectioncollection)

### getSlideSize() {#getSlideSize--}
```
public final ISlideSize getSlideSize()
```

슬라이드 크기 객체를 반환합니다. 읽기 전용 [ISlideSize](../../com.aspose.slides/islidesize).

--------------------

> ```
> The following example shows how to change the slide size in a PowerPoint Presentation.
>  
>  Presentation pres = new Presentation("pres-4x3-aspect-ratio.pptx");
>  try {
>      pres.getSlideSize().setSize(SlideSizeType.OnScreen16x9, SlideSizeScaleType.DoNotScale);
>      pres.save("pres-4x3-aspect-ratio.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to set slide size with respect to content scaling for a PowerPoint Presentation.
>  
>  // Instantiate a Presentation object that represents a presentation file
>  Presentation presentation = new Presentation("AccessSlides.pptx");
>  try {
>      Presentation auxPresentation = new Presentation();
>      try {
>          ISlide slide = presentation.getSlides().get_Item(0);
>          // Set the slide size of generated presentations to that of source
>          presentation.getSlideSize().setSize(540, 720, SlideSizeScaleType.EnsureFit); // Method SetSize is used for set slide size with scale content to ensure fit
>          presentation.getSlideSize().setSize(SlideSizeType.A4Paper, SlideSizeScaleType.Maximize); // Method SetSize is used for set slide size with maximize size of content
>          // Save Presentation to disk
>          auxPresentation.save("Set_Size&Type_out.pptx", SaveFormat.Pptx);
>      } finally {
>          if (auxPresentation != null) auxPresentation.dispose();
>      }
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
>  
>  The following example shows how to specifying custom slide sizes in a PowerPoint Presentation.
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      pres.getSlideSize().setSize(780, 540, SlideSizeScaleType.DoNotScale); // A4 paper size
>      pres.save("pres-a4-slide-size.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**반환:**
[ISlideSize](../../com.aspose.slides/islidesize)

### getNotesSize() {#getNotesSize--}
```
public final INotesSize getNotesSize()
```

노트 슬라이드 크기 객체를 반환합니다. 읽기 전용 [INotesSize](../../com.aspose.slides/inotessize).

**반환:**
[INotesSize](../../com.aspose.slides/inotessize)

### getLayoutSlides() {#getLayoutSlides--}
```
public final IGlobalLayoutSlideCollection getLayoutSlides()
```

프레젠테이션에 정의된 모든 레이아웃 슬라이드의 목록을 반환합니다. 읽기 전용 [IGlobalLayoutSlideCollection](../../com.aspose.slides/igloballayoutslidecollection).

--------------------

대안 API를 사용하여 IMasterSlide.LayoutSlides 속성을 통해 레이아웃 슬라이드를 추가/삽입/제거/복제할 수 있습니다.

**반환:**
[IGlobalLayoutSlideCollection](../../com.aspose.slides/igloballayoutslidecollection)

### getMasters() {#getMasters--}
```
public final IMasterSlideCollection getMasters()
```

프레젠테이션에 정의된 모든 마스터 슬라이드의 목록을 반환합니다. 읽기 전용 [IMasterSlideCollection](../../com.aspose.slides/imasterslidecollection).

--------------------

> ```
> The following examples shows how to adding Images to Master Slides of PowerPoint Presentation.
>  
>  Presentation pres = new Presentation();
>  try {
>      ISlide slide = pres.getSlides().get_Item(0);
>      IMasterSlide masterSlide = slide.getLayoutSlide().getMasterSlide();
>      FileInputStream fos = null;
>      try {
>          fos = new FileInputStream("image.png");
>          IPPImage image = pres.getImages().addImage(fos);
>          masterSlide.getShapes().addPictureFrame(ShapeType.Rectangle, 10, 10, 100, 100, image);
>      } finally {
>          if (fos != null) fos.close();
>      }
>      pres.save("pres.pptx", SaveFormat.Pptx);
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following examples shows how to change the background color of the master slide of PowerPoint Presentation.
>  
>  // 프레젠테이션 파일을 나타내는 Presentation 클래스를 인스턴스화합니다
>  Presentation pres = new Presentation();
>  try
>  {
>      // 마스터 ISlide의 배경색을 포레스트 그린으로 설정합니다
>      pres.getMasters().get_Item(0).getBackground().setType(BackgroundType.OwnBackground);
>      pres.getMasters().get_Item(0).getBackground().getFillFormat().setFillType(FillType.Solid);
>      pres.getMasters().get_Item(0).getBackground().getFillFormat().getSolidFillColor().setColor(Color.GREEN);
>      // 프레젠테이션을 디스크에 저장합니다
>      pres.save("SetSlideBackgroundMaster_out.pptx", SaveFormat.Pptx);
>  }
>  finally
>  {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following examples shows how to add slide layout to PowerPoint Presentation.
>  
>  // 프레젠테이션 파일을 나타내는 Presentation 클래스를 인스턴스화합니다
>  Presentation presentation = new Presentation("AccessSlides.pptx");
>  try
>  {
>      // 레이아웃 슬라이드 유형으로 검색을 시도합니다
>      IMasterLayoutSlideCollection layoutSlides = presentation.getMasters().get_Item(0).getLayoutSlides();
>      ILayoutSlide layoutSlide = null;
>      if (layoutSlides.getByType(SlideLayoutType.TitleAndObject) != null)
>          layoutSlide = layoutSlides.getByType(SlideLayoutType.TitleAndObject);
>      else
>          layoutSlide = layoutSlides.getByType(SlideLayoutType.Title);
> 
>      if (layoutSlide == null)
>      {
>          // 프레젠테이션에 특정 유형의 레이아웃이 포함되지 않은 상황입니다.
>          // 프레젠테이션 파일에는 Blank와 Custom 레이아웃 유형만 포함됩니다.
>          // 그러나 Custom 유형의 레이아웃 슬라이드에는 다른 슬라이드 이름이 있습니다,
>          // 예: "Title", "Title and Content" 등. 그리고 이러한 이름을 사용할 수 있습니다
>          // 레이아웃 슬라이드 선택에 사용할 수 있습니다.
>          // 또한 자리 표시자 쉐이프 유형 집합을 사용할 수 있습니다. 예를 들어,
>          // Title 슬라이드에는 Title 자리 표시자 유형만 있어야 합니다, 등.
>          for (ILayoutSlide titleAndObjectLayoutSlide : (Iterable) layoutSlides)
>          {
>              if ("Title and Object".equals(titleAndObjectLayoutSlide.getName()))
>              {
>                  layoutSlide = titleAndObjectLayoutSlide;
>                  break;
>              }
>          }
>          if (layoutSlide == null)
>          {
>              for (ILayoutSlide titleLayoutSlide : (Iterable) layoutSlides)
>              {
>                  if ("Title".equals(titleLayoutSlide.getName()))
>                  {
>                      layoutSlide = titleLayoutSlide;
>                      break;
>                  }
>              }
>              if (layoutSlide == null)
>              {
>                  layoutSlide = layoutSlides.getByType(SlideLayoutType.Blank);
>                  if (layoutSlide == null)
>                  {
>                      layoutSlide = layoutSlides.add(SlideLayoutType.TitleAndObject, "Title and Object");
>                  }
>              }
>          }
>      }
>      // 추가된 레이아웃 슬라이드로 빈 슬라이드를 삽입합니다
>      presentation.getSlides().insertEmptySlide(0, layoutSlide);
>      // 프레젠테이션을 저장합니다
>      presentation.save("AddLayoutSlides_out.pptx", SaveFormat.Pptx);
>  }
>  finally
>  {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**반환:**
[IMasterSlideCollection](../../com.aspose.slides/imasterslidecollection)

### getMasterNotesSlideManager() {#getMasterNotesSlideManager--}
```
public final IMasterNotesSlideManager getMasterNotesSlideManager()
```

노트 마스터 관리자를 반환합니다. 읽기 전용 [IMasterNotesSlideManager](../../com.aspose.slides/imasternotesslidemanager).

**반환:**
[IMasterNotesSlideManager](../../com.aspose.slides/imasternotesslidemanager)

### getMasterHandoutSlideManager() {#getMasterHandoutSlideManager--}
```
public final IMasterHandoutSlide  {
```

핸드아웃 마스터 관리자를 반환합니다. 읽기 전용 [IMasterHandoutSlideManager](../../com.aspose.slides/imasterhandoutslidemanager).

**반환:**
[IMasterHandoutSlideManager](../../com.aspose.slides/imasterhandoutslidemanager)

### getFontsManager() {#getFontsManager--}
```
public final IFontsManager getFontsManager()
```

폰트 관리자를 반환합니다. 읽기 전용 [IFontsManager](../../com.aspose.slides/ifontsmanager).

--------------------

> ```
> The following example shows how to add embedded fonts to PowerPoint Presentation.
>  
>  // 프레젠테이션을 로드합니다
>  Presentation pres = new Presentation("Fonts.pptx");
>  try {
>      // 교체될 원본 폰트를 로드합니다
>      IFontData sourceFont = new FontData("Arial");
>      IFontData[] allFonts = pres.getFontsManager().getFonts();
>      for (IFontData font : allFonts)
>      {
>          boolean fontAlreadyEmbedded = false;
>          IFontData[] embeddedFonts = pres.getFontsManager().getEmbeddedFonts();
>          for (int i = 0; i < embeddedFonts.length; i++)
>          {
>              if (embeddedFonts[i].equals(font))
>              {
>                  fontAlreadyEmbedded = true;
>                  break;
>              }
>          }
>          if (!fontAlreadyEmbedded) {
>              pres.getFontsManager().addEmbeddedFont(font, EmbedFontCharacters.All);
>          }
>      }
>      // 프레젠테이션을 저장합니다
>      pres.save("AddEmbeddedFont_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**반환:**
[IFontsManager](../../com.aspose.slides/ifontsmanager)

### getDefaultTextStyle() {#getDefaultTextStyle--}
```
public final ITextStyle getDefaultTextStyle()
```

도형에 대한 기본 텍스트 스타일을 반환합니다. 읽기 전용 [ITextStyle](../../com.aspose.slides/itextstyle).

**반환:**
[ITextStyle](../../com.aspose.slides/itextstyle)

### getCommentAuthors() {#getCommentAuthors--}
```
public final ICommentAuthorCollection getCommentAuthors()
```

주석 작성자 컬렉션을 반환합니다. 읽기 전용 [ICommentAuthorCollection](../../com.aspose.slides/icommentauthorcollection).

**반환:**
[ICommentAuthorCollection](../../com.aspose.slides/icommentauthorcollection)

### getDocumentProperties() {#getDocumentProperties--}
```
public final IDocumentProperties getDocumentProperties()
```

표준 및 사용자 정의 문서 속성을 포함하는 DocumentProperties 객체를 반환합니다. 읽기 전용 [IDocumentProperties](../../com.aspose.slides/idocumentproperties).

**반환:**
[IDocumentProperties](../../com.aspose.slides/idocumentproperties)

### getImages() {#getImages--}
```
public final IImageCollection getImages()
```

프레젠테이션에 포함된 모든 이미지 컬렉션을 반환합니다. 읽기 전용 [IImageCollection](../../com.aspose.slides/iimagecollection).

--------------------

> ```
> The following examples shows how to add image as BLOB in PowerPoint Presentation.
>  
>  // 이미지가 추가될 새 프레젠테이션을 생성합니다.
>  Presentation pres = new Presentation();
>  try
>  {
>      // 프레젠테이션에 포함하려는 큰 이미지 파일이 있다고 가정합니다
>      FileInputStream fip = new FileInputStream("large_image.jpg");
>      try
>      {
>          // 이미지를 프레젠테이션에 추가합니다 - KeepLocked 동작을 선택합니다 왜냐하면 우리는
>          // "largeImage.png" 파일에 접근하려 하지 않습니다.
>          IPPImage img = pres.getImages().addImage(fip, LoadingStreamBehavior.KeepLocked);
>          pres.getSlides().get_Item(0).getShapes().addPictureFrame(ShapeType.Rectangle, 0, 0, 300, 200, img);
>          // 프레젠테이션을 저장합니다. 대용량 프레젠테이션이 출력되는 동안, 메모리 사용량은
>          // pres 객체의 전체 수명 주기 동안 낮게 유지됩니다.
>          pres.save("presentationWithLargeImage.pptx", SaveFormat.Pptx);
>      }
>      finally
>      {
>          fip.close();
>      }
>  }
>  catch (java.io.IOException e) { }
>  finally
>  {
>      pres.dispose();
>  }
>  
>  The following examples add a hyperlink to an image in a PowerPoint Presentation.
>  
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream fos = null;
>      try {
>          fos = new FileInputStream("image.png");
>          // 이미지를 프레젠테이션에 추가합니다
>          IPPImage image = pres.getImages().addImage(fos);
>          // 이전에 추가된 이미지를 기반으로 슬라이드 1에 그림 프레임을 생성합니다
>          IPictureFrame pictureFrame = pres.getSlides().get_Item(0).getShapes().addPictureFrame(ShapeType.Rectangle, 10, 10, 100, 100, image);
>          pictureFrame.setHyperlinkClick(new Hyperlink("https://www.aspose.com/"));
>          pictureFrame.getHyperlinkClick().setTooltip("More than 70% Fortune 100 companies trust Aspose APIs");
>      } finally {
>          if (fos != null) fos.close();
>      }
>      pres.save("pres-out.pptx", SaveFormat.Pptx);
>  } catch (IOException e){ }
>  finally
>  {
>      if (pres != null) pres.dispose();
>  }
> ```


**반환:**
[IImageCollection](../../com.aspose.slides/iimagecollection)

### getAudios() {#getAudios--}
```
public final IAudioCollection getAudios()
```

프레젠테이션에 포함된 모든 내장 오디오 파일 컬렉션을 반환합니다. 읽기 전용 [IAudioCollection](../../com.aspose.slides/iaudiocollection).

--------------------

> ```
> The following examples shows how to add a hyperlink to an audio file.
>  
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream fos = null;
>      try {
>          fos = new FileInputStream("audio.mp3");
>          IAudio audio = pres.getAudios().addAudio(fos);
>          IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(10, 10, 100, 100, audio);
>          audioFrame.setHyperlinkClick(new Hyperlink("https://www.aspose.com/"));
>          audioFrame.getHyperlinkClick().setTooltip("More than 70% Fortune 100 companies trust Aspose APIs");
>      } finally {
>          if (fos != null) fos.close();
>      }
>      pres.save("pres-out.pptx", SaveFormat.Pptx);
>  }
>  catch (IOException e) {}
>  finally
>  {
>      if (pres != null) pres.dispose();
>  }
> ```


**반환:**
[IAudioCollection](../../com.aspose.slides/iaudiocollection)

### getVideos() {#getVideos--}
```
public final IVideoCollection getVideos()
```

프레젠테이션에 포함된 모든 내장 비디오 파일 컬렉션을 반환합니다. 읽기 전용 [IVideoCollection](../../com.aspose.slides/ivideocollection).

--------------------

> ```
> The following examples shows how to create embedded Video Frame in a PowerPoint Presentation.
>  
>  // Instantiate Presentation class that represents the PPTX
>  Presentation pres = new Presentation();
>  try {
>      // Get the first slide
>      ISlide sld = pres.getSlides().get_Item(0);
>      // Embedd vide inside presentation
>      IVideo vid = pres.getVideos().addVideo(new FileInputStream("Wildlife.mp4"));
>      // Add Video Frame
>      IVideoFrame vf = sld.getShapes().addVideoFrame(50, 150, 300, 350, vid);
>      // Set video to Video Frame
>      vf.setEmbeddedVideo(vid);
>      // Set Play Mode and Volume of the Video
>      vf.setPlayMode(VideoPlayModePreset.Auto);
>      vf.setVolume(AudioVolumeMode.Loud);
>      // Write the PPTX file to disk
>      pres.save("VideoFrame_out.pptx", SaveFormat.Pptx);
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following examples shows how to add a video passing path to the video file directly into AddVideoFrame method for PowerPoint Presentation.
>  
>  Presentation pres = new Presentation();
>  try {
>      ISlide sld = pres.getSlides().get_Item(0);
>      IVideoFrame vf = sld.getShapes().addVideoFrame(50, 150, 300, 150, "video1.avi");
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following examples shows how to add large file through BLOB to a Presentation.
>  
>  // Creates a new presentation to which the video will be added
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream fileStream = new FileInputStream("veryLargeVideo.avi");
>      try {
>          // Let's add the video to the presentation - we chose the KeepLocked behavior because we do
>          //not intend to access the "veryLargeVideo.avi" file.
>          IVideo video = pres.getVideos().addVideo(fileStream, LoadingStreamBehavior.KeepLocked);
>          pres.getSlides().get_Item(0).getShapes().addVideoFrame(0, 0, 480, 270, video);
>          // Saves the presentation. While a large presentation gets outputted, the memory consumption
>          // stays low through the pres object's lifecycle
>          pres.save("presentationWithLargeVideo.pptx", SaveFormat.Pptx);
>      } finally {
>          if (fileStream != null) fileStream.close();
>      }
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following examples shows how to export large file through BLOB from PowerPoint Presentation.
>  
>  LoadOptions loadOptions = new LoadOptions();
>  // Locks the source file and does NOT load it into memory
>  loadOptions.getBlobManagementOptions().setPresentationLockingBehavior(PresentationLockingBehavior.KeepLocked);
>  // Creates a Presentation's instance, locks the "hugePresentationWithAudiosAndVideos.pptx" file.
>  Presentation pres = new Presentation("Large  Video File Test1.pptx", loadOptions);
>  try {
>      // Let's save each video to a file. To prevent high memory usage, we need a buffer that will be used
>      // to transfer the data from the presentation's video stream to a stream for a newly created video file.
>      byte[] buffer = new byte[81024];
>      // Iterates through the videos
>      for (int index = 0; index < pres.getVideos().size(); index++) {
>          IVideo video = pres.getVideos().get_Item(index);
>          // Opens the presentation video stream. Please, note that we intentionally avoided accessing properties
>          // like video.BinaryData - because this property returns a byte array containing a full video, which then
>          // causes bytes to be loaded into memory. We use video.GetStream, which will return Stream - and does NOT
>          //  require us to load the whole video into the memory.
>          InputStream presVideoStream = video.getStream();
>          try {
>              FileOutputStream outputFileStream = new FileOutputStream("video{index}.avi");
>              try {
>                  int bytesRead;
>                  while ((bytesRead = presVideoStream.read(buffer, 0, buffer.length)) > 0) {
>                      outputFileStream.write(buffer, 0, bytesRead);
>                  }
>              } finally {
>                  if (outputFileStream != null) outputFileStream.close();
>              }
>          } finally {
>              if (presVideoStream != null) presVideoStream.close();
>          }
>          // Memory consumption will remain low regardless of the size of the video or presentation,
>      }
>      // If necessary, you can apply the same steps for audio files.
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following examples shows how to add a hyperlink to a video in a PowerPoint Presentation.
>  
>  Presentation pres = new Presentation();
>  try {
>      IVideo video = pres.getVideos().addVideo(Files.readAllBytes(Paths.get("video.avi")));
>      IVideoFrame videoFrame = pres.getSlides().get_Item(0).getShapes().addVideoFrame(10, 10, 100, 100, video);
>      videoFrame.setHyperlinkClick(new Hyperlink("https://www.aspose.com/"));
>      videoFrame.getHyperlinkClick().setTooltip("More than 70% Fortune 100 companies trust Aspose APIs");
>      pres.save("pres-out.pptx", SaveFormat.Pptx);
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following examples shows how to create Video Frame with Video from Web Source in a PowerPoint Presentation.
>  
>  public static void run()
>  {
>      Presentation pres = new Presentation();
>      try {
>          addVideoFromYouTube(pres, "Tj75Arhq5ho");
>          pres.save("AddVideoFrameFromWebSource_out.pptx", SaveFormat.Pptx);
>      } catch(IOException e) {
>      } finally {
>          if (pres != null) pres.dispose();
>      }
>  }
>  private static void addVideoFromYouTube(Presentation pres, String videoId) throws IOException
>  {
>      //add videoFrame
>      IVideoFrame videoFrame = pres.getSlides().get_Item(0).getShapes().addVideoFrame(10, 10, 427, 240, "https://www.youtube.com/embed/" + videoId);
>      videoFrame.setPlayMode(VideoPlayModePreset.Auto);
> 
>      //load thumbnail
>      String thumbnailUri = "http://img.youtube.com/vi/" + videoId + "/hqdefault.jpg";
>      URL url = new URL(thumbnailUri);
>      URLConnection connection = url.openConnection();
>      connection.setConnectTimeout(5000);
>      connection.setReadTimeout(10000);
>      InputStream input = connection.getInputStream();
>      ByteArrayOutputStream output = new ByteArrayOutputStream();
>      try
>      {
>          byte[] buffer = new byte[8192];
>          for (int count; (count = input.read(buffer)) > 0; )
>          {
>              output.write(buffer, 0, count);
>          }
>          videoFrame.getPictureFormat().getPicture().setImage(pres.getImages().addImage(output.toByteArray()));
>      } finally {
>          if (input != null) input.close();
>          if (output != null) output.close();
>      }
>  }
>  
>  The following examples shows how to extract Video from slide of PowerPoint Presentation.
>  
>  // Instantiate a Presentation object that represents a presentation file
>  Presentation presentation = new Presentation("Video.pptx");
>  try {
>      for (ISlide slide : presentation.getSlides())
>      {
>          for (IShape shape : presentation.getSlides().get_Item(0).getShapes())
>          {
>              if (shape instanceof VideoFrame)
>              {
>                  IVideoFrame vf = (IVideoFrame) shape;
>                  String type = vf.getEmbeddedVideo().getContentType();
>                  int ss = type.lastIndexOf('/');
>                  type = type.substring(ss + 1);
>                  byte[] buffer = vf.getEmbeddedVideo().getBinaryData();
>                  FileOutputStream fop = new FileOutputStream("NewVideo_out." + type);
>                  try
>                  {
>                      fop.write(buffer);
>                      fop.flush();
>                      fop.close();
>                  }
>                  finally
>                  {
>                      if (presentation != null) presentation.dispose();
>                  }
>              }
>          }
>      }
>  } catch(IOException e) {
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**반환:**
[IVideoCollection](../../com.aspose.slides/ivideocollection)

### getSlideShowSettings() {#getSlideShowSettings--}
```
public final SlideShowSettings getSlideShowSettings()
```

프레젠테이션의 슬라이드 쇼 설정을 반환합니다.

**반환:**
[SlideShowSettings](../../com.aspose.slides/slideshowsettings)

### getDigitalSignatures() {#getDigitalSignatures--}
```
public final IDigitalSignatureCollection getDigitalSignatures()
```

프레젠테이션 서명에 사용된 서명 컬렉션을 반환합니다. 읽기 전용 [IDigitalSignatureCollection](../../com.aspose.slides/idigitalsignaturecollection).

--------------------

> ```
> Presentation pres = new Presentation("SomePresentationSigned.pptx");
>  try
>  {
>      if (pres.getDigitalSignatures().size() > 0)
>      {
>          boolean allSignaturesAreValid = true;
>          System.out.println("Signatures used to sign the presentation: ");
>          for (IDigitalSignature signature : pres.getDigitalSignatures())
>          {
>             System.out.println(signature.getCertificate().hashCode() + ", "
>                   + signature.getSignTime().toString() + " -- " + (signature.isValid() ? "VALID" : "INVALID"));
>             allSignaturesAreValid &= signature.isValid();
>          }
>          if (allSignaturesAreValid)
>             System.out.println("Presentation is genuine, all signatures are valid.");
>          else
>             System.out.println("Presentation has been modified since signing.");
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**반환:**
[IDigitalSignatureCollection](../../com.aspose.slides/idigitalsignaturecollection)

### getCustomData() {#getCustomData--}
```
public final ICustomData getCustomData()
```

프레젠테이션의 사용자 정의 데이터를 반환합니다. 읽기 전용 [ICustomData](../../com.aspose.slides/icustomdata).

**반환:**
[ICustomData](../../com.aspose.slides/icustomdata)

### getAllCustomXmlParts() {#getAllCustomXmlParts--}
```
public final ICustomXmlPart[] getAllCustomXmlParts()
```

프레젠테이션의 모든 사용자 정의 데이터 파트를 반환합니다. 읽기 전용 ICustomXmlPart[].

--------------------

> ```
> The following examples show how to clear all custom xml parts from PowerPoint Presentation.
>  
>  Presentation pres = new Presentation("PresentationWithCustomXml.pptx");
>  try {
>      // 모든 사용자 정의 XML 파트를 순회합니다
>      for (ICustomXmlPart item : pres.getAllCustomXmlParts())
>      {
>          item.remove();
>      }
>      pres.save("out.pptx", SaveFormat.Pptx);
>  }
>  finally
>  {
>      if (pres != null) pres.dispose();
>  }
> ```

**반환:**
com.aspose.slides.ICustomXmlPart[]

### getVbaProject() {#getVbaProject--}
```
public final IVbaProject getVbaProject()
```

프레젠테이션 매크로가 포함된 VBA 프로젝트를 가져오거나 설정합니다. 읽기/쓰기 [IVbaProject](../../com.aspose.slides/ivbaproject).

**반환:**
[IVbaProject](../../com.aspose.slides/ivbaproject)

### setVbaProject(IVbaProject value) {#setVbaProject-com.aspose.slides.IVbaProject-}
```
public final void setVbaProject(IVbaProject value)
```

프레젠테이션 매크로가 포함된 VBA 프로젝트를 가져오거나 설정합니다. 읽기/쓰기 [IVbaProject](../../com.aspose.slides/ivbaproject).

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [IVbaProject](../../com.aspose.slides/ivbaproject) |  |

### getHyperlinkQueries() {#getHyperlinkQueries--}
```
public final IHyperlinkQueries getHyperlinkQueries()
```

모든 프레젠테이션 슬라이드(마스터, 레이아웃, 노트 슬라이드 제외)에 포함된 모든 하이퍼링크에 쉽게 접근할 수 있게 합니다. 읽기 전용 [IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries).

**반환:**
[IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries)

### getViewProperties() {#getViewProperties--}
```
public final IViewProperties {
```

프레젠테이션 전체 뷰 속성을 가져옵니다. 읽기 전용 [IViewProperties](../../com.aspose.slides/iviewproperties).

**반환:**
[IViewProperties](../../com.aspose.slides/iviewproperties)

### getFirstSlideNumber() {#getFirstSlideNumber--}
```
public final int getFirstSlideNumber()
```

프레젠테이션의 첫 슬라이드 번호를 나타냅니다.

**반환:**
int

### setFirstSlideNumber(int value) {#setFirstSlideNumber-int-}
```
public final void setFirstSlideNumber(int value)
```

프레젠테이션의 첫 슬라이드 번호를 나타냅니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | int |  |

### getSensitivityLabels() {#getSensitivityLabels--}
```
public final ISensitivityLabelCollection getSensitivityLabels()
```

프레젠테이션 문서에 적용된 민감도 레이블 컬렉션을 반환합니다. 읽기 전용 [ISensitivityLabelCollection](../../com.aspose.slides/isensitivitylabelcollection).

--------------------

> ```
> Presentation pres = new Presentation("SomePresentation.pptx");
>  try {
>      ISensitivityLabelCollection sensitivityLabels = pres.getSensitivityLabels();
> 
>      // 적용된 레이블을 출력합니다
>      for (ISensitivityLabel sensitivityLabel : sensitivityLabels)
>          System.out.println("Label Id " + sensitivityLabel.getId() + " from Azure AD site " + sensitivityLabel.getSiteId());
> 
>      // 새 레이블을 추가합니다
>      String labelIdString = "{xxxxxxxx-xxxx-xxxx-xxxx-xxxxxxxxxxxx}"; // 정책에서 민감도 레이블 Id를 가져옵니다
>      UUID siteIdGuid = UUID.fromString("{xxxxxxxx-xxxx-xxxx-xxxx-xxxxxxxxxxxx}"); // 정책에서 Azure AD 사이트 식별자를 가져옵니다
>      ISensitivityLabel label = sensitivityLabels.add(labelIdString, siteIdGuid, true, SensitivityLabelAssignmentType.Privileged);
>      label.getContentMarkTypes().addItem(SensitivityLabelContentType.Footer);
> 
>      pres.save("SensitivityLabel.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**반환:**
[ISensitivityLabelCollection](../../com.aspose.slides/isensitivitylabelcollection)

### getSlideById(long id) {#getSlideById-long-}
```
public final IBaseSlide getSlideById(long id)
```

Id에 따라 Slide, MasterSlide 또는 LayoutSlide를 반환합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| id | long | 슬라이드의 Id. |

**반환:**
[IBaseSlide](../../com.aspose.slides/ibaseslide) - IBaseSlide 객체.

### getSourceFormat() {#getSourceFormat--}
```
public final int getSourceFormat()
```

프레젠테이션이 로드된 형식에 대한 정보를 반환합니다. 읽기 전용 [SourceFormat](../../com.aspose.slides/sourceformat).

**반환:**
int

### getMasterTheme() {#getMasterTheme--}
```
public final IMasterTheme getMasterTheme()
```

마스터 테마를 반환합니다. 읽기 전용 [IMasterTheme](../../com.aspose.slides/imastertheme).

--------------------

> ```
> The following examples shows how to change a theme effect by altering parts of elements of PowerPoint Presentation.
>  
>  //프레젠테이션 파일을 나타내는 Presentation 객체를 인스턴스화합니다
>  Presentation pres = new Presentation("Subtle_Moderate_Intense.pptx");
>  try {
>      pres.getMasterTheme().getFormatScheme().getLineStyles().get_Item(0).getFillFormat().getSolidFillColor().setColor(Color.RED);
>      ((FillFormat)pres.getMasterTheme().getFormatScheme().getLineStyles().get_Item(2)).setFillType(FillType.Solid);
>      ((FillFormat)pres.getMasterTheme().getFormatScheme().getLineStyles().get_Item(2)).getSolidFillColor().setColor(Color.GREEN);
>      ((EffectStyle)pres.getMasterTheme().getFormatScheme().getLineStyles().get_Item(2)).getEffectFormat().getOuterShadowEffect().setDistance(10f);
>      pres.save("Design_04_Subtle_Moderate_Intense-out.pptx", SaveFormat.Pptx);
>  }
>  finally
>  {
>      if (pres != null) pres.dispose();
>  }
> ```


**반환:**
[IMasterTheme](../../com.aspose.slides/imastertheme)

### save(String fname, int format) {#save-java.lang.String-int-}
```
public final void save(String fname, int format)
```

프레젠테이션의 모든 슬라이드를 지정된 형식의 파일에 저장합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| fname | java.lang.String | 생성된 파일의 경로. |
| format | int | 내보낼 데이터의 형식. |

### save(OutputStream stream, int format) {#save-java.io.OutputStream-int-}
```
public final void save(OutputStream stream, int format)
```

프레젠테이션의 모든 슬라이드를 지정된 형식의 스트림에 저장합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| stream | java.io.OutputStream | 출력 스트림. |
| format | int | 내보낼 데이터의 형식. |

### save(String fname, int format, ISaveOptions options) {#save-java.lang.String-int-com.aspose.slides.ISaveOptions-}
```
public final void save(String fname, int format, ISaveOptions options)
```

프레젠테이션의 모든 슬라이드를 지정된 형식 및 추가 옵션으로 파일에 저장합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| fname | java.lang.String | 생성된 파일의 경로. |
| format | int | 내보낼 데이터의 형식. |
| options | [ISaveOptions](../../com.aspose.slides/isaveoptions) | 추가 형식 옵션. |

### save(OutputStream stream, int format, ISaveOptions options) {#save-java.io.OutputStream-int-com.aspose.slides.ISSaveOptions-}
```
public final void save(OutputStream stream, int format, ISaveOptions options)
```

프레젠테이션의 모든 슬라이드를 지정된 형식 및 추가 옵션으로 스트림에 저장합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| stream | java.io.OutputStream | 출력 스트림. |
| format | int | 내보낼 데이터의 형식. |
| options | [ISaveOptions](../../com.aspose.slides/isaveoptions) | 추가 형식 옵션. |

### save(IXamlOptions options) {#save-com.aspose.slides.IXamlOptions-}
```
public final void save(IXamlOptions options)
```

프레젠테이션의 모든 슬라이드를 XAML 마크업을 나타내는 파일 집합에 저장합니다.

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      XamlOptions xamlOptions = new XamlOptions();
>      xamlOptions.setExportHiddenSlides(true);
> 
>      pres.save(xamlOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| options | [IXamlOptions](../../com.aspose.slides/ixamloptions) | XAML 형식 옵션. |

### getImages(IRenderingOptions options) {#getImages-com.aspose.slides.IRenderingOptions-}
```
public final IImage[] getImages(IRenderingOptions options)
```

프레젠테이션의 모든 슬라이드에 대한 Image 객체를 반환합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Tiff 옵션. |

**반환:**
com.aspose.slides.IImage[] - Image 객체.

### getImages(IRenderingOptions options, int[] slides) {#getImages-com.aspose.slides.IRenderingOptions-int---}
```
public final IImage[] getImages(IRenderingOptions options, int[] slides)
```

지정된 슬라이드에 대한 썸네일 Image 객체를 반환합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Tiff 옵션. |
| slides | int[] | 1부터 시작하는 슬라이드 위치 배열. |

**반환:**
com.aspose.slides.IImage[] - Image 객체.

### getImages(IRenderingOptions options, float scaleX, float scaleY) {#getImages-com.aspose.slides.IRenderingOptions-float-float-}
```
public final IImage[] getImages(IRenderingOptions options, float scaleX, float scaleY)
```

맞춤 스케일링으로 프레젠테이션의 모든 슬라이드에 대한 썸네일 Image 객체를 반환합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Tiff 옵션. |
| scaleX | float | X축 방향으로 이 썸네일을 스케일링할 값. |
| scaleY | float | Y축 방향으로 이 썸네일을 스케일링할 값. |

**반환:**
com.aspose.slides.IImage[] - Image 객체.

### getImages(IRenderingOptions options, int[] slides, float scaleX, float scaleY) {#getImages-com.aspose.slides.IRenderingOptions-int---float-float-}
```
public final IImage[] getImages(IRenderingOptions options, int[] slides, float scaleX, float scaleY)
```

맞춤 스케일링으로 지정된 슬라이드에 대한 썸네일 Image 객체를 반환합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Tiff 옵션. |
| slides | int[] | 1부터 시작하는 슬라이드 위치 배열. |
| scaleX | float | X축 방향으로 이 썸네일을 스케일링할 값. |
| scaleY | float | Y축 방향으로 이 썸네일을 스케일링할 값. |

**반환:**
com.aspose.slides.IImage[] - Image 객체.

### getImages(IRenderingOptions options, Size imageSize) {#getImages-com.aspose.slides.IRenderingOptions-com.aspose.slides.android.Size-}
```
public final IImage[] getImages(IRenderingOptions options, Size imageSize)
```

지정된 크기로 프레젠테이션의 모든 슬라이드에 대한 썸네일 Image 객체를 반환합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Tiff 옵션. |
| imageSize | [Size](../../com.aspose.slides.android/size) | 생성할 이미지의 크기. |

**반환:**
com.aspose.slides.IImage[] - Image 객체.

### getImages(IRenderingOptions options, int[] slides, Size imageSize) {#getImages-com.aspose.slides.IRenderingOptions-int---com.aspose.slides.android.Size-}
```
public final IImage[] getImages(IRenderingOptions options, int[] slides, Size imageSize)
```

지정된 크기로 지정된 슬라이드에 대한 썸네일 Image 객체를 반환합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Tiff 옵션. |
| slides | int[] | 1부터 시작하는 슬라이드 위치 배열. |
| imageSize | [Size](../../com.aspose.slides.android/size) | 생성할 이미지의 크기. |

**반환:**
com.aspose.slides.IImage[] - Image 객체.

### save(String fname, int[] slides, int format) {#save-java.lang.String-int---int-}
```
public final void save(String fname, int[] slides, int format)
```

지정된 슬라이드를 페이지 번호를 유지하면서 지정된 형식의 파일에 저장합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| fname | java.lang.String | 생성된 파일의 경로. |
| slides | int[] | 1부터 시작하는 슬라이드 위치 배열. |
| format | int | 내보낼 데이터의 형식. |

### save(String fname, int[] slides, int format, ISaveOptions options) {#save-java.lang.String-int---int-com.aspose.slides.ISaveOptions-}
```
public final void save(String fname, int[] slides, int format, ISaveOptions options)
```

지정된 슬라이드를 페이지 번호를 유지하면서 지정된 형식의 파일에 저장합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| fname | java.lang.String | 생성된 파일의 경로. |
| slides | int[] | 1부터 시작하는 슬라이드 위치 배열. |
| format | int | 내보낼 데이터의 형식. |
| options | [ISaveOptions](../../com.aspose.slides/isaveoptions) | 추가 형식 옵션. |

### save(OutputStream stream, int[] slides, int format) {#save-java.io.OutputStream-int---int-}
```
public final void save(OutputStream stream, int[] slides, int format)
```

지정된 슬라이드를 페이지 번호를 유지하면서 지정된 형식의 스트림에 저장합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| stream | java.io.OutputStream | 출력 스트림. |
| slides | int[] | 1부터 시작하는 슬라이드 위치 배열. |
| format | int | 내보낼 데이터의 형식. |

### save(OutputStream stream, int[] slides, int format, ISaveOptions options) {#save-java.io.OutputStream-int---int-com.aspose.slides.ISaveOptions-}
```
public final void save(OutputStream stream, int[] slides, int format, ISaveOptions options)
```

지정된 슬라이드를 페이지 번호를 유지하면서 지정된 형식의 스트림에 저장합니다.

--------------------

> ```
> The following example shows how to convert PowerPoint to PNG.
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      for (int index = 0; index < pres.getSlides().size(); index++) {
>          ISlide slide = pres.getSlides().get_Item(index);
>          FileOutputStream out = new FileOutputStream("slide_" + index + ".png");
>          slide.getThumbnail().compress(android.graphics.Bitmap.CompressFormat.PNG, 100, out);
>          out.flush();
>          out.close();
>      }
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to convert PowerPoint to PNG with custom dimensions.
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      float scaleX = 2f;
>      float scaleY = 2f;
>      for (int index = 0; index < pres.getSlides().size(); index++) {
>          ISlide slide = pres.getSlides().get_Item(index);
>          FileOutputStream out = new FileOutputStream("slide_" + index + ".png");
>          slide.getThumbnail(scaleX, scaleY).compress(android.graphics.Bitmap.CompressFormat.PNG, 100, out);
>          out.flush();
>          out.close();
>      }
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to convert PowerPoint to PNG with custom size.
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      com.aspose.slides.android.Size size = new com.aspose.slides.android.Size(960, 720);
>      for (int index = 0; index < pres.getSlides().size(); index++) {
>          ISlide slide = pres.getSlides().get_Item(index);
>          FileOutputStream out = new FileOutputStream("slide_" + index + ".png");
>          slide.getThumbnail(size).compress(android.graphics.Bitmap.CompressFormat.PNG, 100, out);
>          out.flush();
>          out.close();
>      }
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| stream | java.io.OutputStream | 출력 스트림. |
| slides | int[] | 1부터 시작하는 슬라이드 위치 배열. |
| format | int | 내보낼 데이터의 형식. |
| options | [ISaveOptions](../../com.aspose.slides/isaveoptions) | 추가 형식 옵션. |

### joinPortionsWithSameFormatting() {#joinPortionsWithSameFormatting--}
```
public final void joinPortionsWithSameFormatting()
```

모든 슬라이드의 모든 허용된 도형 내 모든 단락에서 동일한 서식의 실행(run)을 결합합니다.

### dispose() {#dispose--}
```
public final void dispose()
```

이 Presentation 객체가 사용한 모든 리소스를 해제합니다.

### getPresentation() {#getPresentation--}
```
public              
```

텍스트의 상위 프레젠테이션을 반환합니다. 읽기 전용 [IPresentation](../../com.aspose.slides/ipresentation).

**반환:**
[IPresentation](../../com.aspose.slides/ipresentation)

### highlightText(String text, Integer highlightColor) {#highlightText-java.lang.String-java.lang.Integer-}
```
public final void highlightText(String text, Integer highlightColor)
```

샘플 텍스트와 일치하는 모든 항목을 지정된 색상으로 강조합니다.

> ```
> 다음 코드 샘플은 PowerPoint 프레젠테이션에서 텍스트를 강조하는 방법을 보여줍니다.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      // 모든 개별 'the' 발생을 강조합니다
>      presentation.highlightText("the", Color.MAGENTA);
>      presentation.save("SomePresentation-out2.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| text | java.lang.String | 강조할 텍스트. |
| highlightColor | java.lang.Integer | 텍스트를 강조할 색상. |

### highlightText(String text, Integer highlightColor, ITextSearchOptions options, IFindResultCallback callback) {#highlightText-java.lang.String-java.lang.Integer-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-}
```
public final void highlightText(String text, Integer highlightColor, ITextSearchOptions options, IFindResultCallback callback)
```

샘플 텍스트와 일치하는 모든 항목을 지정된 색상으로 강조합니다.

> ```
> The following code sample shows how to highlight text in a PowerPoint presentation.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      TextSearchOptions textSearchOptions = new TextSearchOptions();
>      textSearchOptions.setWholeWordsOnly(true);
>      // 모든 개별 'the' 발생을 강조합니다
>      presentation.highlightText("the", Color.MAGENTA, textSearchOptions, null);
>      presentation.save("SomePresentation-out2.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| text | java.lang.String | 강조할 텍스트. |
| highlightColor | java.lang.Integer | 텍스트를 강조할 색상. |
| options | [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions) | 텍스트 검색 옵션 [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions). |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | 검색 결과를 받기 위한 콜백 객체 [IFindResultCallback](../../com.aspose.slides/ifindresultcallback). |

### highlightRegex(Pattern regex, Integer highlightColor, IFindResultCallback callback) {#highlightRegex-java.util.regex.Pattern-java.lang.Integer-com.aspose.slides.IFindResultCallback-}
```
public final void highlightRegex(Pattern regex, Integer highlightColor, IFindResultCallback callback)
```

정규식과 일치하는 모든 항목을 지정된 색상으로 강조합니다.

> ```
> The following code sample shows how to highlight text in a PowerPoint Presentation using a regular expression.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      Pattern regex = Pattern.compile("\\b[^\\s]{10,}\\b");
>      // 10자 이상인 모든 단어를 강조합니다
>      presentation.highlightRegex(regex, Color.BLUE, null);
>      presentation.save("SomePresentation-out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| regex | java.util.regex.Pattern | 강조할 문자열을 얻기 위한 정규식. |
| highlightColor | java.lang.Integer | 텍스트를 강조할 색상. |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | 검색 결과를 받기 위한 콜백 객체 [IFindResultCallback](../../com.aspose.slides/ifindresultcallback). |

### replaceText(String oldText, String newText, ITextSearchOptions options, IFindResultCallback callback) {#replaceText-java.lang.String-java.lang.String-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-}
```
public final void replaceText(String oldText, String newText, ITextSearchOptions options, IFindResultCallback callback)
```

지정된 텍스트의 모든 발생을 다른 지정된 텍스트로 바꿉니다.

> ```
> The following sample code shows how to replace one specified string with another specified string.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx")
>  try {
>      TextSearchOptions textSearchOptions = new TextSearchOptions();
>      textSearchOptions.setWholeWordsOnly(true);
>      // 모든 개별 'the' 발생을 '***'로 교체합니다
>      presentation.replaceText("the", "***", textSearchOptions, null);
>      presentation.save("SomePresentation-out2.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| oldText | java.lang.String | 교체될 문자열. |
| newText | java.lang.String | oldText의 모든 발생을 교체할 문자열. |
| options | [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions) | 텍스트 검색 옵션 [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions). |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | 검색 결과를 받기 위한 콜백 객체 [IFindResultCallback](../../com.aspose.slides/ifindresultcallback). |

### replaceRegex(Pattern regex, String newText, IFindResultCallback callback) {#replaceRegex-java.util.regex.Pattern-java.lang.String-com.aspose.slides.IFindResultCallback-}
```
public final void replaceRegex(Pattern regex, String newText, IFindResultCallback callback)
```

정규식과 일치하는 모든 항목을 지정된 문자열로 바꿉니다.

> ```
> The following code sample shows how to replace text using regular expression with the specified string.
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      Pattern regex = Pattern.compile("\\b[^\\s]{10,}\\b");
>      // 10자 이상인 모든 단어를 '***'로 교체합니다
>      presentation.replaceRegex(regex, "***", null);
>      presentation.save("SomePresentation-out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| regex | java.util.regex.Pattern | 교체할 문자열을 얻기 위한 정규식. |
| newText | java.lang.String | 교체될 문자열을 모두 교체할 문자열. |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | 검색 결과를 받기 위한 콜백 객체 [IFindResultCallback](../../com.aspose.slides/ifindresultcallback). |