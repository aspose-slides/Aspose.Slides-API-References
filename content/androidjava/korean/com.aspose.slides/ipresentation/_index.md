---
title: IPresentation
second_title: Java API 레퍼런스를 이용한 Aspose.Slides for Android
description: 프레젠테이션 문서
type: docs
url: /ko/com.aspose.slides/ipresentation/
---
**구현된 모든 인터페이스:**
[com.aspose.slides.IPresentationComponent](../../com.aspose.slides/ipresentationcomponent), com.aspose.ms.System.IDisposable
```
public interface IPresentation extends IPresentationComponent, System.IDisposable
```

프레젠테이션 문서
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getCurrentDateTime()](#getCurrentDateTime--) | datetime 필드의 내용을 대체할 날짜와 시간을 반환하거나 설정합니다. |
| [setCurrentDateTime(Date value)](#setCurrentDateTime-java.util.Date-) | datetime 필드의 내용을 대체할 날짜와 시간을 반환하거나 설정합니다. |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | 프레젠테이션의 HeaderFooter 관리자를 반환합니다. |
| [getProtectionManager()](#getProtectionManager--) | 이 프레젠테이션의 권한 관리자를 가져옵니다. |
| [getSlides()](#getSlides--) | 프레젠테이션에 정의된 모든 슬라이드의 목록을 반환합니다. |
| [getSections()](#getSections--) | 프레젠테이션에 정의된 모든 슬라이드 섹션의 목록을 반환합니다. |
| [getSlideSize()](#getSlideSize--) | 슬라이드 크기 객체를 반환합니다. |
| [getNotesSize()](#getNotesSize--) | 노트 슬라이드 크기 객체를 반환합니다. |
| [getLayoutSlides()](#getLayoutSlides--) | 프레젠테이션에 정의된 모든 레이아웃 슬라이드의 목록을 반환합니다. |
| [getMasters()](#getMasters--) | 프레젠테이션에 정의된 모든 마스터 슬라이드의 목록을 반환합니다. |
| [getMasterNotesSlideManager()](#getMasterNotesSlideManager--) | 노트 마스터 관리자를 반환합니다. |
| [getMasterHandoutSlideManager()](#getMasterHandoutSlideManager--) | 핸드아웃 마스터 관리자를 반환합니다. |
| [getFontsManager()](#getFontsManager--) | 글꼴 관리자를 반환합니다. |
| [getDefaultTextStyle()](#getDefaultTextStyle--) | 쉐이프의 기본 텍스트 스타일을 반환합니다. |
| [getCommentAuthors()](#getCommentAuthors--) | 댓글 작성자 컬렉션을 반환합니다. |
| [getDocumentProperties()](#getDocumentProperties--) | 표준 및 사용자 정의 문서 속성을 포함하는 DocumentProperties 객체를 반환합니다. |
| [getImages()](#getImages--) | 프레젠테이션에 포함된 모든 이미지 컬렉션을 반환합니다. |
| [getAudios()](#getAudios--) | 프레젠테이션에 포함된 모든 Embedded 오디오 파일 컬렉션을 반환합니다. |
| [getVideos()](#getVideos--) | 프레젠테이션에 포함된 모든 Embedded 비디오 파일 컬렉션을 반환합니다. |
| [getCustomData()](#getCustomData--) | 프레젠테이션의 사용자 정의 데이터를 반환합니다. |
| [getVbaProject()](#getVbaProject--) | 프레젠테이션 매크로가 포함된 VBA 프로젝트를 가져옵니다. |
| [setVbaProject(IVbaProject value)](#setVbaProject-com.aspose.slides.IVbaProject-) | 프레젠테이션 매크로가 포함된 VBA 프로젝트를 가져옵니다. |
| [getSourceFormat()](#getSourceFormat--) | 프레젠테이션이 로드된 형식에 대한 정보를 반환합니다. |
| [getMasterTheme()](#getMasterTheme--) | 프레젠테이션의 마스터 테마를 반환합니다. |
| [getHyperlinkQueries()](#getHyperlinkQueries--) | 모든 프레젠테이션 슬라이드에 포함된 모든 하이퍼링크에 쉽게 접근할 수 있도록 제공합니다 (마스터, 레이아웃, 노트 슬라이드 제외). |
| [getViewProperties()](#getViewProperties--) | 프레젠테이션 전체 뷰 속성을 가져옵니다. |
| [getFirstSlideNumber()](#getFirstSlideNumber--) | 프레젠테이션의 첫 번째 슬라이드 번호를 나타냅니다. |
| [setFirstSlideNumber(int value)](#setFirstSlideNumber-int-) | 프레젠테이션의 첫 번째 슬라이드 번호를 나타냅니다. |
| [getAllCustomXmlParts()](#getAllCustomXmlParts--) | 프레젠테이션의 모든 사용자 정의 데이터 파트를 반환합니다. |
| [getDigitalSignatures()](#getDigitalSignatures--) | 프레젠테이션에 서명하는 데 사용된 서명 컬렉션을 반환합니다. |
| [getSensitivityLabels()](#getSensitivityLabels--) | 프레젠테이션 문서에 적용된 민감도 레이블 컬렉션을 반환합니다. |
| [save(String fname, int format)](#save-java.lang.String-int-) | 프레젠테이션의 모든 슬라이드를 지정된 형식으로 파일에 저장합니다. |
| [save(OutputStream stream, int format)](#save-java.io.OutputStream-int-) | 프레젠테이션의 모든 슬라이드를 지정된 형식으로 스트림에 저장합니다. |
| [save(String fname, int format, ISaveOptions options)](#save-java.lang.String-int-com.aspose.slides.ISaveOptions-) | 프레젠테이션의 모든 슬라이드를 지정된 형식으로 파일에 저장하고 추가 옵션을 적용합니다. |
| [save(OutputStream stream, int format, ISaveOptions options)](#save-java.io.OutputStream-int-com.aspose.slides.ISaveOptions-) | 프레젠테이션의 모든 슬라이드를 지정된 형식으로 스트림에 저장하고 추가 옵션을 적용합니다. |
| [save(String fname, int[] slides, int format)](#save-java.lang.String-int---int-) | 지정된 슬라이드를 지정된 형식으로 파일에 저장합니다. |
| [save(String fname, int[] slides, int format, ISaveOptions options)](#save-java.lang.String-int---int-com.aspose.slides.ISaveOptions-) | 지정된 슬라이드를 지정된 형식으로 파일에 저장합니다. |
| [save(OutputStream stream, int[] slides, int format)](#save-java.io.OutputStream-int---int-) | 지정된 슬라이드를 지정된 형식으로 스트림에 저장합니다. |
| [save(OutputStream stream, int[] slides, int format, ISaveOptions options)](#save-java.io.OutputStream-int---int-com.aspose.slides.ISaveOptions-) | 지정된 슬라이드를 지정된 형식으로 스트림에 저장합니다. |
| [save(IXamlOptions options)](#save-com.aspose.slides.IXamlOptions-) | 프레젠테이션의 모든 슬라이드를 XAML 마크업을 나타내는 파일 집합에 저장합니다. |
| [getImages(IRenderingOptions options)](#getImages-com.aspose.slides.IRenderingOptions-) | 프레젠테이션의 모든 슬라이드에 대한 썸네일 이미지 객체를 반환합니다. |
| [getImages(IRenderingOptions options, int[] slides)](#getImages-com.aspose.slides.IRenderingOptions-int---) | 지정된 슬라이드에 대한 썸네일 IImage 객체를 반환합니다. |
| [getImages(IRenderingOptions options, float scaleX, float scaleY)](#getImages-com.aspose.slides.IRenderingOptions-float-float-) | 맞춤 스케일링을 적용한 프레젠테이션의 모든 슬라이드에 대한 썸네일 이미지 객체를 반환합니다. |
| [getImages(IRenderingOptions options, int[] slides, float scaleX, float scaleY)](#getImages-com.aspose.slides.IRenderingOptions-int---float-float-) | 지정된 슬라이드에 대한 썸네일 이미지 객체를 맞춤 스케일링으로 반환합니다. |
| [getImages(IRenderingOptions options, Size imageSize)](#getImages-com.aspose.slides.IRenderingOptions-com.aspose.slides.android.Size-) | 지정된 크기로 프레젠테이션의 모든 슬라이드에 대한 썸네일 이미지 객체를 반환합니다. |
| [getImages(IRenderingOptions options, int[] slides, Size imageSize)](#getImages-com.aspose.slides.IRenderingOptions-int---com.aspose.slides.android.Size-) | 지정된 슬라이드에 대한 썸네일 이미지 객체를 지정된 크기로 반환합니다. |
| [getSlideById(long id)](#getSlideById-long-) | ID로 Slide, MasterSlide 또는 LayoutSlide를 반환합니다. |
| [joinPortionsWithSameFormatting()](#joinPortionsWithSameFormatting--) | 모든 슬라이드의 모든 허용 가능한 쉐이프에서 모든 단락에 대해 동일한 서식의 런을 병합합니다. |
| [highlightText(String text, Integer highlightColor)](#highlightText-java.lang.String-java.lang.Integer-) | 샘플 텍스트와 일치하는 모든 항목을 지정된 색상으로 강조 표시합니다. |
| [highlightText(String text, Integer highlightColor, ITextSearchOptions options, IFindResultCallback callback)](#highlightText-java.lang.String-java.lang.Integer-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-) | 샘플 텍스트와 일치하는 모든 항목을 지정된 색상으로 강조 표시합니다. |
| [highlightRegex(Pattern regex, Integer highlightColor, IFindResultCallback callback)](#highlightRegex-java.util.regex.Pattern-java.lang.Integer-com.aspose.slides.IFindResultCallback-) | 정규식과 일치하는 모든 항목을 지정된 색상으로 강조 표시합니다. |
| [replaceText(String oldText, String newText, ITextSearchOptions options, IFindResultCallback callback)](#replaceText-java.lang.String-java.lang.String-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-) | 지정된 텍스트의 모든 발생을 다른 지정된 텍스트로 교체합니다. |
| [replaceRegex(Pattern regex, String newText, IFindResultCallback callback)](#replaceRegex-java.util.regex.Pattern-java.lang.String-com.aspose.slides.IFindResultCallback-) | 정규식과 일치하는 모든 항목을 지정된 문자열로 교체합니다. |

### getCurrentDateTime() {#getCurrentDateTime--}
```
public abstract Date getCurrentDateTime()
```

datetime 필드의 내용을 대체할 날짜와 시간을 반환하거나 설정합니다. 기본적으로 이 Presentation 객체가 생성된 시간입니다. 읽기/쓰기 java.util.Date.

**반환:**  
java.util.Date

### setCurrentDateTime(Date value) {#setCurrentDateTime-java.util.Date-}
```
public abstract void setCurrentDateTime(Date value)
```

datetime 필드의 내용을 대체할 날짜와 시간을 반환하거나 설정합니다. 기본적으로 이 Presentation 객체가 생성된 시간입니다. 읽기/쓰기 java.util.Date.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | java.util.Date |  |

### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public abstract IPresentationHeaderFooterManager getHeaderFooterManager()
```

프레젠테이션의 HeaderFooter 관리자를 반환합니다. 읽기 전용 [IPresentationHeaderFooterManager](../../com.aspose.slides/ipresentationheaderfootermanager).

**반환:**  
[IPresentationHeaderFooterManager](../../com.aspose.slides/ipresentationheaderfootermanager)

### getProtectionManager() {#getProtectionManager--}
```
public abstract IProtectionManager getProtectionManager()
```

이 프레젠테이션의 권한 관리자를 가져옵니다. 읽기 전용 [IProtectionManager](../../com.aspose.slides/iprotectionmanager).

**반환:**  
[IProtectionManager](../../com.aspose.slides/iprotectionmanager)

### getSlides() {#getSlides--}
```
public abstract ISlideCollection getSlides()
```

프레젠테이션에 정의된 모든 슬라이드의 목록을 반환합니다. 읽기 전용 [ISlideCollection](../../com.aspose.slides/islidecollection).

**반환:**  
[ISlideCollection](../../com.aspose.slides/islidecollection)

### getSections() {#getSections--}
```
public abstract ISectionCollection getSections()
```

프레젠테이션에 정의된 모든 슬라이드 섹션의 목록을 반환합니다. 읽기 전용 [ISectionCollection](../../com.aspose.slides/isectioncollection).

**반환:**  
[ISectionCollection](../../com.aspose.slides/isectioncollection)

### getSlideSize() {#getSlideSize--}
```
public abstract ISlideSize getSlideSize()
```

슬라이드 크기 객체를 반환합니다. 읽기 전용 [ISlideSize](../../com.aspose.slides/islidesize).

**반환:**  
[ISlideSize](../../com.aspose.slides/islidesize)

### getNotesSize() {#getNotesSize--}
```
public abstract INotesSize getNotesSize()
```

노트 슬라이드 크기 객체를 반환합니다. 읽기 전용 [INotesSize](../../com.aspose.slides/inotessize).

**반환:**  
[INotesSize](../../com.aspose.slides/inotessize)

### getLayoutSlides() {#getLayoutSlides--}
```
public abstract IGlobalLayoutSlideCollection getLayoutSlides()
```

프레젠테이션에 정의된 모든 레이아웃 슬라이드의 목록을 반환합니다. 읽기 전용 [IGlobalLayoutSlideCollection](../../com.aspose.slides/igloballayoutslidecollection).

--------------------

대체 API에 접근하여 IMasterSlide.LayoutSlides 속성을 사용해 레이아웃 슬라이드를 추가/삽입/제거/복제할 수 있습니다.

**반환:**  
[IGlobalLayoutSlideCollection](../../com.aspose.slides/igloballayoutslidecollection)

### getMasters() {#getMasters--}
```
public abstract IMasterSlideCollection getMasters()
```

프레젠테이션에 정의된 모든 마스터 슬라이드의 목록을 반환합니다. 읽기 전용 [IMasterSlideCollection](../../com.aspose.slides/imasterslidecollection).

**반환:**  
[IMasterSlideCollection](../../com.aspose.slides/imasterslidecollection)

### getMasterNotesSlideManager() {#getMasterNotesSlideManager--}
```
public abstract IMasterNotesSlideManager getMasterNotesSlideManager()
```

노트 마스터 관리자를 반환합니다. 읽기 전용 [IMasterNotesSlideManager](../../com.aspose.slides/imasternotesslidemanager).

**반환:**  
[IMasterNotesSlideManager](../../com.aspose.slides/imasternotesslidemanager)

### getMasterHandoutSlideManager() {#getMasterHandoutSlideManager--}
```
public abstract IMasterHandoutSlideManager getMasterHandoutSlideManager()
```

핸드아웃 마스터 관리자를 반환합니다. 읽기 전용 [IMasterHandoutSlideManager](../../com.aspose.slides/imasterhandoutslidemanager).

**반환:**  
[IMasterHandoutSlideManager](../../com.aspose.slides/imasterhandoutslidemanager)

### getFontsManager() {#getFontsManager--}
```
public abstract IFontsManager getFontsManager()
```

글꼴 관리자를 반환합니다. 읽기 전용 [IFontsManager](../../com.aspose.slides/ifontsmanager).

**반환:**  
[IFontsManager](../../com.aspose.slides/ifontsmanager)

### getDefaultTextStyle() {#getDefaultTextStyle--}
```
public abstract ITextStyle getDefaultTextStyle()
```

쉐이프의 기본 텍스트 스타일을 반환합니다. 읽기 전용 [ITextStyle](../../com.aspose.slides/itextstyle).

**반환:**  
[ITextStyle](../../com.aspose.slides/itextstyle)

### getCommentAuthors() {#getCommentAuthors--}
```
public abstract ICommentAuthorCollection getCommentAuthors()
```

댓글 작성자 컬렉션을 반환합니다. 읽기 전용 [ICommentAuthorCollection](../../com.aspose.slides/icommentauthorcollection).

**반환:**  
[ICommentAuthorCollection](../../com.aspose.slides/icommentauthorcollection)

### getDocumentProperties() {#getDocumentProperties--}
```
public abstract IDocumentProperties getDocumentProperties()
```

표준 및 사용자 정의 문서 속성을 포함하는 DocumentProperties 객체를 반환합니다. 읽기 전용 [IDocumentProperties](../../com.aspose.slides/idocumentproperties).

**반환:**  
[IDocumentProperties](../../com.aspose.slides/idocumentproperties)

### getImages() {#getImages--}
```
public abstract IImageCollection getImages()
```

프레젠테이션에 포함된 모든 이미지 컬렉션을 반환합니다. 읽기 전용 [IImageCollection](../../com.aspose.slides/iimagecollection).

**반환:**  
[IImageCollection](../../com.aspose.slides/iimagecollection)

### getAudios() {#getAudios--}
```
public abstract IAudioCollection getAudios()
```

프레젠테이션에 포함된 모든 Embedded 오디오 파일 컬렉션을 반환합니다. 읽기 전용 [IAudioCollection](../../com.aspose.slides/iaudiocollection).

**반환:**  
[IAudioCollection](../../com.aspose.slides/iaudiocollection)

### getVideos() {#getVideos--}
```
public abstract IVideoCollection getVideos()
```

프레젠테이션에 포함된 모든 Embedded 비디오 파일 컬렉션을 반환합니다. 읽기 전용 [IVideoCollection](../../com.aspose.slides/ivideocollection).

**반환:**  
[IVideoCollection](../../com.aspose.slides/ivideocollection)

### getCustomData() {#getCustomData--}
```
public abstract ICustomData getCustomData()
```

프레젠테이션의 사용자 정의 데이터를 반환합니다. 읽기 전용 [ICustomData](../../com.aspose.slides/icustomdata).

**반환:**  
[ICustomData](../../com.aspose.slides/icustomdata)

### getVbaProject() {#getVbaProject--}
```
public abstract IVbaProject getVbaProject()
```

프레젠테이션 매크로가 포함된 VBA 프로젝트를 가져옵니다. 읽기/쓰기 [IVbaProject](../../com.aspose.slides/ivbaproject).

**반환:**  
[IVbaProject](../../com.aspose.slides/ivbaproject)

### setVbaProject(IVbaProject value) {#setVbaProject-com.aspose.slides.IVbaProject-}
```
public abstract void setVbaProject(IVbaProject value)
```

프레젠테이션 매크로가 포함된 VBA 프로젝트를 가져옵니다. 읽기/쓰기 [IVbaProject](../../com.aspose.slides/ivbaproject).

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [IVbaProject](../../com.aspose.slides/ivbaproject) |  |

### getSourceFormat() {#getSourceFormat--}
```
public abstract int getSourceFormat()
```

프레젠테이션이 로드된 형식에 대한 정보를 반환합니다. 읽기 전용 [SourceFormat](../../com.aspose.slides/sourceformat).

**반환:**  
int

### getMasterTheme() {#getMasterTheme--}
```
public abstract IMasterTheme getMasterTheme()
```

프레젠테이션의 마스터 테마를 반환합니다. 읽기 전용 [IMasterTheme](../../com.aspose.slides/imastertheme).

**반환:**  
[IMasterTheme](../../com.aspose.slides/imastertheme)

### getHyperlinkQueries() {#getHyperlinkQueries--}
```
public abstract IHyperlinkQueries getHyperlinkQueries()
```

모든 프레젠테이션 슬라이드에 포함된 모든 하이퍼링크에 쉽게 접근할 수 있도록 제공합니다 (마스터, 레이아웃, 노트 슬라이드 제외). 읽기 전용 [IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries).

**반환:**  
[IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries)

### getViewProperties() {#getViewProperties--}
```
public abstract IViewProperties getViewProperties()
```

프레젠테이션 전체 뷰 속성을 가져옵니다. 읽기 전용 [IViewProperties](../../com.aspose.slides/iviewproperties).

**반환:**  
[IViewProperties](../../com.aspose.slides/iviewproperties)

### getFirstSlideNumber() {#getFirstSlideNumber--}
```
public abstract int getFirstSlideNumber()
```

프레젠테이션의 첫 번째 슬라이드 번호를 나타냅니다. 읽기/쓰기 int.

**반환:**  
int

### setFirstSlideNumber(int value) {#setFirstSlideNumber-int-}
```
public abstract void setFirstSlideNumber(int value)
```

프레젠테이션의 첫 번째 슬라이드 번호를 나타냅니다. 읽기/쓰기 int.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | int |  |

### getAllCustomXmlParts() {#getAllCustomXmlParts--}
```
public abstract ICustomXmlPart[] getAllCustomXmlParts()
```

프레젠테이션의 모든 사용자 정의 데이터 파트를 반환합니다. 읽기 전용 ICustomXmlPart[].

**반환:**  
com.aspose.slides.ICustomXmlPart[]

### getDigitalSignatures() {#getDigitalSignatures--}
```
public abstract IDigitalSignatureCollection getDigitalSignatures()
```

프레젠테이션에 서명하는 데 사용된 서명 컬렉션을 반환합니다. 읽기 전용 [IDigitalSignatureCollection](../../com.aspose.slides/idigitalsignaturecollection).

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
>                    + signature.getSignTime().toString() + " -- " + (signature.isValid() ? "VALID" : "INVALID"));
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

### getSensitivityLabels() {#getSensitivityLabels--}
```
public abstract ISensitivityLabelCollection getSensitivityLabels()
```

프레젠테이션 문서에 적용된 민감도 레이블 컬렉션을 반환합니다. 읽기 전용 [ISensitivityLabelCollection](../../com.aspose.slides/isensitivitylabelcollection).

--------------------

> ```
> Presentation pres = new Presentation("SomePresentation.pptx");
>  try {
>      ISensitivityLabelCollection sensitivityLabels = pres.getSensitivityLabels();
> 
>      // 적용된 라벨을 출력합니다
>      for (ISensitivityLabel sensitivityLabel : sensitivityLabels)
>          System.out.println("Label Id " + sensitivityLabel.getId() + " from Azure AD site " + sensitivityLabel.getSiteId());
> 
>      // 새 라벨을 추가합니다
>      String labelIdString = "{xxxxxxxx-xxxx-xxxx-xxxx-xxxxxxxxxxxx}"; // 정책에서 민감도 라벨 ID를 가져옵니다
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

### save(String fname, int format) {#save-java.lang.String-int-}
```
public abstract void save(String fname, int format)
```

프레젠테이션의 모든 슬라이드를 지정된 형식으로 파일에 저장합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| fname | java.lang.String | 생성된 파일의 경로. |
| format | int | 내보낼 데이터 형식. |

### save(OutputStream stream, int format) {#save-java.io.OutputStream-int-}
```
public abstract void save(OutputStream stream, int format)
```

프레젠테이션의 모든 슬라이드를 지정된 형식으로 스트림에 저장합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| stream | java.io.OutputStream | 출력 스트림. |
| format | int | 내보낼 데이터 형식. |

### save(String fname, int format, ISaveOptions options) {#save-java.lang.String-int-com.aspose.slides.ISaveOptions-}
```
public abstract void save(String fname, int format, ISaveOptions options)
```

프레젠테이션의 모든 슬라이드를 지정된 형식으로 파일에 저장하고 추가 옵션을 적용합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| fname | java.lang.String | 생성된 파일의 경로. |
| format | int | 내보낼 데이터 형식. |
| options | [ISaveOptions](../../com.aspose.slides/isaveoptions) | 추가 형식 옵션. |

### save(OutputStream stream, int format, ISaveOptions options) {#save-java.io.OutputStream-int-com.aspose.slides.ISaveOptions-}
```
public abstract void save(OutputStream stream, int format, ISaveOptions options)
```

프레젠테이션의 모든 슬라이드를 지정된 형식으로 스트림에 저장하고 추가 옵션을 적용합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| stream | java.io.OutputStream | 출력 스트림. |
| format | int | 내보낼 데이터 형식. |
| options | [ISaveOptions](../../com.aspose.slides/isaveoptions) | 추가 형식 옵션. |

### save(String fname, int[] slides, int format) {#save-java.lang.String-int---int-}
```
public abstract void save(String fname, int[] slides, int format)
```

지정된 슬라이드를 지정된 형식으로 파일에 저장합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| fname | java.lang.String | 생성된 파일의 경로. |
| slides | int[] | 슬라이드 위치 배열(1부터 시작). |
| format | int | 내보낼 데이터 형식. |

### save(String fname, int[] slides, int format, ISaveOptions options) {#save-java.lang.String-int---int-com.aspose.slides.ISaveOptions-}
```
public abstract void save(String fname, int[] slides, int format, ISaveOptions options)
```

지정된 슬라이드를 지정된 형식으로 파일에 저장합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| fname | java.lang.String | 생성된 파일의 경로. |
| slides | int[] | 슬라이드 위치 배열(1부터 시작). |
| format | int | 내보낼 데이터 형식. |
| options | [ISaveOptions](../../com.aspose.slides/isaveoptions) | 추가 형식 옵션. |

### save(OutputStream stream, int[] slides, int format) {#save-java.io.OutputStream-int---int-}
```
public abstract void save(OutputStream stream, int[] slides, int format)
```

지정된 슬라이드를 지정된 형식으로 스트림에 저장합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| stream | java.io.OutputStream | 출력 스트림. |
| slides | int[] | 슬라이드 위치 배열(1부터 시작). |
| format | int | 내보낼 데이터 형식. |

### save(OutputStream stream, int[] slides, int format, ISaveOptions options) {#save-java.io.OutputStream-int---int-com.aspose.slides.ISaveOptions-}
```
public abstract void save(OutputStream stream, int[] slides, int format, ISaveOptions options)
```

지정된 슬라이드를 지정된 형식으로 스트림에 저장합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| stream | java.io.OutputStream | 출력 스트림. |
| slides | int[] | 슬라이드 위치 배열(1부터 시작). |
| format | int | 내보낼 데이터 형식. |
| options | [ISaveOptions](../../com.aspose.slides/isaveoptions) | 추가 형식 옵션. |

### save(IXamlOptions options) {#save-com.aspose.slides.IXamlOptions-}
```
public abstract void save(IXamlOptions options)
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
public abstract IImage[] getImages(IRenderingOptions options)
```

프레젠테이션의 모든 슬라이드에 대한 썸네일 이미지 객체를 반환합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | 렌더링 옵션. |

**반환:**  
com.aspose.slides.IImage[] - IImage 객체.

### getImages(IRenderingOptions options, int[] slides) {#getImages-com.aspose.slides.IRenderingOptions-int---}
```
public abstract IImage[] getImages(IRenderingOptions options, int[] slides)
```

지정된 슬라이드에 대한 썸네일 IImage 객체를 반환합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | 렌더링 옵션. |
| slides | int[] | 슬라이드 위치 배열(1부터 시작). |

**반환:**  
com.aspose.slides.IImage[] - IImage 객체.

### getImages(IRenderingOptions options, float scaleX, float scaleY) {#getImages-com.aspose.slides.IRenderingOptions-float-float-}
```
public abstract IImage[] getImages(IRenderingOptions options, float scaleX, float scaleY)
```

맞춤 스케일링을 적용한 프레젠테이션의 모든 슬라이드에 대한 썸네일 이미지 객체를 반환합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | 렌더링 옵션. |
| scaleX | float | x축 방향으로 스케일링할 값. |
| scaleY | float | y축 방향으로 스케일링할 값. |

**반환:**  
com.aspose.slides.IImage[] - Bitmap 객체.

### getImages(IRenderingOptions options, int[] slides, float scaleX, float scaleY) {#getImages-com.aspose.slides.IRenderingOptions-int---float-float-}
```
public abstract IImage[] getImages(IRenderingOptions options, int[] slides, float scaleX, float scaleY)
```

지정된 슬라이드에 맞춤 스케일링을 적용한 썸네일 이미지 객체를 반환합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | 렌더링 옵션. |
| slides | int[] | 슬라이드 위치 배열(1부터 시작). |
| scaleX | float | x축 방향으로 스케일링할 값. |
| scaleY | float | y축 방향으로 스케일링할 값. |

**반환:**  
com.aspose.slides.IImage[] - IImage 객체.

### getImages(IRenderingOptions options, Size imageSize) {#getImages-com.aspose.slides.IRenderingOptions-com.aspose.slides.android.Size-}
```
public abstract IImage[] getImages(IRenderingOptions options, Size imageSize)
```

지정된 크기로 프레젠테이션의 모든 슬라이드에 대한 썸네일 이미지 객체를 반환합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | 렌더링 옵션. |
| imageSize | [Size](../../com.aspose.slides.android/size) | 생성할 이미지의 크기. |

**반환:**  
com.aspose.slides.IImage[] - IImage 객체.

### getImages(IRenderingOptions options, int[] slides, Size imageSize) {#getImages-com.aspose.slides.IRenderingOptions-int---com.aspose.slides.android.Size-}
```
public abstract IImage[] getImages(IRenderingOptions options, int[] slides, Size imageSize)
```

지정된 슬라이드에 지정된 크기로 썸네일 이미지 객체를 반환합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | 렌더링 옵션. |
| slides | int[] | 슬라이드 위치 배열(1부터 시작). |
| imageSize | [Size](../../com.aspose.slides.android/size) | 생성할 이미지의 크기. |

**반환:**  
com.aspose.slides.IImage[] - IImage 객체.

### getSlideById(long id) {#getSlideById-long-}
```
public abstract IBaseSlide getSlideById(long id)
```

ID로 Slide, MasterSlide 또는 LayoutSlide를 반환합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| id | long | 슬라이드 ID. |

**반환:**  
[IBaseSlide](../../com.aspose.slides/ibaseslide) - IBaseSlide 객체.

### joinPortionsWithSameFormatting() {#joinPortionsWithSameFormatting--}
```
public abstract void joinPortionsWithSameFormatting()
```

모든 슬라이드의 모든 허용 가능한 쉐이프에서 모든 단락에 대해 동일한 서식의 런을 병합합니다.

### highlightText(String text, Integer highlightColor) {#highlightText-java.lang.String-java.lang.Integer-}
```
public abstract void highlightText(String text, Integer highlightColor)
```

샘플 텍스트와 일치하는 모든 항목을 지정된 색상으로 강조 표시합니다.

--------------------

> ```
> The following code sample shows how to highlight text in a PowerPoint presentation.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      // highlighting all separate 'the' occurrences
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
public abstract void highlightText(String text, Integer highlightColor, ITextSearchOptions options, IFindResultCallback callback)
```

샘플 텍스트와 일치하는 모든 항목을 지정된 색상으로 강조 표시합니다.

--------------------

> ```
> The following code sample shows how to highlight text in a PowerPoint presentation.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      // highlighting all separate 'the' occurrences
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
| options | [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions) | 텍스트 검색 옵션 [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions). |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | 검색 결과를 수신할 콜백 객체 [IFindResultCallback](../../com.aspose.slides/ifindresultcallback). |

### highlightRegex(Pattern regex, Integer highlightColor, IFindResultCallback callback) {#highlightRegex-java.util.regex.Pattern-java.lang.Integer-com.aspose.slides.IFindResultCallback-}
```
public abstract void highlightRegex(Pattern regex, Integer highlightColor, IFindResultCallback callback)
```

정규식과 일치하는 모든 항목을 지정된 색상으로 강조 표시합니다.

--------------------

> ```
> The following code sample shows how to highlight text in a PowerPoint Presentation using a regular expression.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      // highlighting all separate 'the' occurrences
>      presentation.highlightText("the", Color.MAGENTA);
>      presentation.save("SomePresentation-out2.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| regex | java.util.regex.Pattern | 강조할 문자열을 얻기 위한 정규식. |
| highlightColor | java.lang.Integer | 텍스트를 강조할 색상. |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | 검색 결과를 수신할 콜백 객체 [IFindResultCallback](../../com.aspose.slides/ifindresultcallback). |

### replaceText(String oldText, String newText, ITextSearchOptions options, IFindResultCallback callback) {#replaceText-java.lang.String-java.lang.String-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-}
```
public abstract void replaceText(String oldText, String newText, ITextSearchOptions options, IFindResultCallback callback)
```

지정된 텍스트의 모든 발생을 다른 지정된 텍스트로 교체합니다.

--------------------

> ```
> The following sample code shows how to replace one specified string with another specified string.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx")
>  try {
>      TextSearchOptions textSearchOptions = new TextSearchOptions();
>      textSearchOptions.setWholeWordsOnly(true);
>      // 모든 별도 'the' 발생을 '***'로 교체합니다
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
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | 검색 결과를 수신할 콜백 객체 [IFindResultCallback](../../com.aspose.slides/ifindresultcallback). |

### replaceRegex(Pattern regex, String newText, IFindResultCallback callback) {#replaceRegex-java.util.regex.Pattern-java.lang.String-com.aspose.slides.IFindResultCallback-}
```
public abstract void replaceRegex(Pattern regex, String newText, IFindResultCallback callback)
```

정규식과 일치하는 모든 항목을 지정된 문자열로 교체합니다.

--------------------

> ```
> The following code sample shows how to replace text using regular expression with the specified string.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx")
>  try {
>      TextSearchOptions textSearchOptions = new TextSearchOptions();
>      textSearchOptions.setWholeWordsOnly(true);
>      // 모든 별도 'the' 발생을 '***'로 교체합니다
>      presentation.replaceText("the", "***", textSearchOptions, null);
>      presentation.save("SomePresentation-out2.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| regex | java.util.regex.Pattern | 교체할 문자열을 찾기 위한 정규식. |
| newText | java.lang.String | 교체할 문자열. |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | 검색 결과를 수신할 콜백 객체 [IFindResultCallback](../../com.aspose.slides/ifindresultcallback). |