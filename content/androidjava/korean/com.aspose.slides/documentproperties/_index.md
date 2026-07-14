---
title: DocumentProperties
second_title: Android용 Java API를 통한 Aspose.Slides 레퍼런스
description: 프레젠테이션의 속성을 나타냅니다.
type: docs
url: /ko/com.aspose.slides/documentproperties/
---
**상속:**  
java.lang.Object

**구현된 모든 인터페이스:**  
[com.aspose.slides.IDocumentProperties](../../com.aspose.slides/idocumentproperties), com.aspose.slides.IGenericCloneable, java.lang.Cloneable  
```
public class DocumentProperties implements IDocumentProperties, IGenericCloneable<IDocumentProperties>, Cloneable
```

프레젠테이션의 속성을 나타냅니다.

--------------------

> ```
> The following example shows how to access built-in Properties of PowerPoint Presentation.
>  
>  // Presentation 클래스를 인스턴스화하여 프레젠테이션을 나타냅니다
>  Presentation pres = new Presentation("AccessBuiltin Properties.pptx");
>  try {
>      // Presentation과 연결된 IDocumentProperties 객체에 대한 참조를 생성합니다
>      IDocumentProperties documentProperties = pres.getDocumentProperties();
>      // 내장 속성을 표시합니다
>      System.out.println("Category : " + documentProperties.getCategory());
>      System.out.println("Current Status : " + documentProperties.getContentStatus());
>      System.out.println("Creation Date : " + documentProperties.getCreatedTime());
>      System.out.println("Author : " + documentProperties.getAuthor());
>      System.out.println("Description : " + documentProperties.getComments());
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to modify built-in Properties of PowerPoint Presentation.
>  
>  // Presentation 클래스를 인스턴스화하여 프레젠테이션을 나타냅니다
>  Presentation pres = new Presentation("ModifyBuiltinProperties.pptx");
>  try {
>      // Presentation과 연결된 IDocumentProperties 객체에 대한 참조를 생성합니다
>      IDocumentProperties documentProperties = pres.getDocumentProperties();
>      // 내장 속성을 설정합니다
>      documentProperties.setAuthor("Aspose.Slides for Android via Java");
>      documentProperties.setTitle("Modifying Presentation Properties");
>      documentProperties.setSubject("Aspose Subject");
>      // 프레젠테이션을 파일에 저장합니다
>      pres.save("DocumentProperties_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

## 생성자

| 생성자 | 설명 |
| --- | --- |
| [DocumentProperties()](#DocumentProperties--) | 클래스 [DocumentProperties](../../com.aspose.slides/documentproperties)의 새 인스턴스를 초기화합니다. |

## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getAppVersion()](#getAppVersion--) | 앱 버전을 반환합니다. |
| [getNameOfApplication()](#getNameOfApplication--) | 응용 프로그램의 이름을 반환하거나 설정합니다. |
| [setNameOfApplication(String value)](#setNameOfApplication-java.lang.String-) | 응용 프로그램의 이름을 반환하거나 설정합니다. |
| [getCompany()](#getCompany--) | 회사 속성을 반환하거나 설정합니다. |
| [setCompany(String value)](#setCompany-java.lang.String-) | 회사 속성을 반환하거나 설정합니다. |
| [getManager()](#getManager--) | 관리자 속성을 반환하거나 설정합니다. |
| [setManager(String value)](#setManager-java.lang.String-) | 관리자 속성을 반환하거나 설정합니다. |
| [getPresentationFormat()](#getPresentationFormat--) | 프레젠테이션의 의도된 형식을 반환하거나 설정합니다. |
| [setPresentationFormat(String value)](#setPresentationFormat-java.lang.String-) | 프레젠테이션의 의도된 형식을 반환하거나 설정합니다. |
| [getSharedDoc()](#getSharedDoc--) | 프레젠테이션이 여러 사람과 공유되는지 여부를 판단합니다. |
| [setSharedDoc(boolean value)](#setSharedDoc-boolean-) | 프레젠테이션이 여러 사람과 공유되는지 여부를 판단합니다. |
| [getApplicationTemplate()](#getApplicationTemplate--) | 응용 프로그램의 템플릿을 반환하거나 설정합니다. |
| [setApplicationTemplate(String value)](#setApplicationTemplate-java.lang.String-) | 응용 프로그램의 템플릿을 반환하거나 설정합니다. |
| [getTotalEditingTime()](#getTotalEditingTime--) | 프레젠테이션의 총 편집 시간을 반환합니다. |
| [setTotalEditingTime(double value)](#setTotalEditingTime-double-) | 프레젠테이션의 총 편집 시간을 반환합니다. |
| [getTitle()](#getTitle--) | 프레젠테이션의 제목을 반환하거나 설정합니다. |
| [setTitle(String value)](#setTitle-java.lang.String-) | 프레젠테이션의 제목을 반환하거나 설정합니다. |
| [getSubject()](#getSubject--) | 프레젠테이션의 주제를 반환하거나 설정합니다. |
| [setSubject(String value)](#setSubject-java.lang.String-) | 프레젠테이션의 주제를 반환하거나 설정합니다. |
| [getAuthor()](#getAuthor--) | 프레젠테이션의 저자를 반환하거나 설정합니다. |
| [setAuthor(String value)](#setAuthor-java.lang.String-) | 프레젠테이션의 저자를 반환하거나 설정합니다. |
| [getKeywords()](#getKeywords--) | 프레젠테이션의 키워드를 반환하거나 설정합니다. |
| [setKeywords(String value)](#setKeywords-java.lang.String-) | 프레젠테이션의 키워드를 반환하거나 설정합니다. |
| [getComments()](#getComments--) | 프레젠테이션의 설명을 반환하거나 설정합니다. |
| [setComments(String value)](#setComments-java.lang.String-) | 프레젠테이션의 설명을 반환하거나 설정합니다. |
| [getCategory()](#getCategory--) | 프레젠테이션의 카테고리를 반환하거나 설정합니다. |
| [setCategory(String value)](#setCategory-java.lang.String-) | 프레젠테이션의 카테고리를 반환하거나 설정합니다. |
| [getCreatedTime()](#getCreatedTime--) | 프레젠테이션이 생성된 날짜를 반환합니다. |
| [setCreatedTime(Date value)](#setCreatedTime-java.util.Date-) | 프레젠테이션이 생성된 날짜를 반환합니다. |
| [getLastSavedTime()](#getLastSavedTime--) | 프레젠테이션이 마지막으로 수정된 날짜를 반환합니다. |
| [setLastSavedTime(Date value)](#setLastSavedTime-java.util.Date-) | 프레젠테이션이 마지막으로 수정된 날짜를 반환합니다. |
| [getLastPrinted()](#getLastPrinted--) | 프레젠테이션이 마지막으로 인쇄된 날짜를 반환합니다. |
| [setLastPrinted(Date value)](#setLastPrinted-java.util.Date-) | 프레젠테이션이 마지막으로 인쇄된 날짜를 반환합니다. |
| [getLastSavedBy()](#getLastSavedBy--) | 마지막으로 프레젠테이션을 수정한 사람의 이름을 반환하거나 설정합니다. |
| [setLastSavedBy(String value)](#setLastSavedBy-java.lang.String-) | 마지막으로 프레젠테이션을 수정한 사람의 이름을 반환하거나 설정합니다. |
| [getRevisionNumber()](#getRevisionNumber--) | 프레젠테이션의 리비전 번호를 반환하거나 설정합니다. |
| [setRevisionNumber(int value)](#setRevisionNumber-int-) | 프레젠테이션의 리비전 번호를 반환하거나 설정합니다. |
| [getContentStatus()](#getContentStatus--) | 프레젠테이션의 콘텐츠 상태를 반환하거나 설정합니다. |
| [setContentStatus(String value)](#setContentStatus-java.lang.String-) | 프레젠테이션의 콘텐츠 상태를 반환하거나 설정합니다. |
| [getContentType()](#getContentType--) | 프레젠테이션의 콘텐츠 유형을 반환하거나 설정합니다. |
| [setContentType(String value)](#setContentType-java.lang.String-) | 프레젠테이션의 콘텐츠 유형을 반환하거나 설정합니다. |
| [getHyperlinkBase()](#getHyperlinkBase--) | HyperlinkBase 문서 속성을 반환하거나 설정합니다. |
| [setHyperlinkBase(String value)](#setHyperlinkBase-java.lang.String-) | HyperlinkBase 문서 속성을 반환하거나 설정합니다. |
| [getCountOfCustomProperties()](#getCountOfCustomProperties--) | 컬렉션에 실제 포함된 사용자 정의 속성 수를 반환합니다. |
| [getCustomPropertyName(int index)](#getCustomPropertyName-int-) | 지정된 인덱스에 있는 사용자 정의 속성 이름을 반환합니다. |
| [removeCustomProperty(String name)](#removeCustomProperty-java.lang.String-) | 지정된 이름과 연결된 사용자 정의 속성을 제거합니다. |
| [containsCustomProperty(String name)](#containsCustomProperty-java.lang.String-) | 지정된 이름을 가진 사용자 정의 속성의 존재 여부를 확인합니다. |
| [get_Item(String name)](#get-Item-java.lang.String-) | 지정된 이름과 연결된 사용자 정의 속성을 반환하거나 설정합니다. |
| [set_Item(String name, Object value)](#set-Item-java.lang.String-java.lang.Object-) | 지정된 이름과 연결된 사용자 정의 속성을 반환하거나 설정합니다. |
| [getCustomPropertyValue(String name, boolean[] value)](#getCustomPropertyValue-java.lang.String-boolean---) |  |
| [getCustomPropertyValue(String name, int[] value)](#getCustomPropertyValue-java.lang.String-int---) |  |
| [getCustomPropertyValue(String name, Date[] value)](#getCustomPropertyValue-java.lang.String-java.util.Date---) |  |
| [getCustomPropertyValue(String name, String[] value)](#getCustomPropertyValue-java.lang.String-java.lang.String---) |  |
| [getCustomPropertyValue(String name, float[] value)](#getCustomPropertyValue-java.lang.String-float---) |  |
| [getCustomPropertyValue(String name, double[] value)](#getCustomPropertyValue-java.lang.String-double---) |  |
| [setCustomPropertyValue(String name, boolean value)](#setCustomPropertyValue-java.lang.String-boolean-) | 지정된 이름의 부울 사용자 정의 속성을 설정합니다. |
| [setCustomPropertyValue(String name, int value)](#setCustomPropertyValue-java.lang.String-int-) | 지정된 이름의 정수 사용자 정의 속성을 설정합니다. |
| [setCustomPropertyValue(String name, Date value)](#setCustomPropertyValue-java.lang.String-java.util.Date-) | 지정된 이름의 DateTime 사용자 정의 속성을 설정합니다. |
| [setCustomPropertyValue(String name, String value)](#setCustomPropertyValue-java.lang.String-java.lang.String-) | 지정된 이름의 문자열 사용자 정의 속성을 설정합니다. |
| [setCustomPropertyValue(String name, float value)](#setCustomPropertyValue-java.lang.String-float-) | 지정된 이름의 부동소수점 사용자 정의 속성을 설정합니다. |
| [setCustomPropertyValue(String name, double value)](#setCustomPropertyValue-java.lang.String-double-) | 지정된 이름의 배정밀도 부동소수점 사용자 정의 속성을 설정합니다. |
| [clearCustomProperties()](#clearCustomProperties--) | 모든 사용자 정의 속성을 제거합니다. |
| [getSensitivityLabels()](#getSensitivityLabels--) | 사용자 정의 문서 속성(Microsoft Information Protection SDK 메타데이터)에서 민감도 레이블 배열을 가져옵니다. |
| [clearBuiltInProperties()](#clearBuiltInProperties--) | 모든 builtIn 속성을 지우고 기본값으로 설정합니다. |
| [getScaleCrop()](#getScaleCrop--) | 문서 썸네일의 표시 모드를 나타냅니다. |
| [setScaleCrop(boolean value)](#setScaleCrop-boolean-) | 문서 썸네일의 표시 모드를 나타냅니다. |
| [getLinksUpToDate()](#getLinksUpToDate--) | 문서의 하이퍼링크가 최신 상태인지 여부를 나타냅니다. |
| [setLinksUpToDate(boolean value)](#setLinksUpToDate-boolean-) | 문서의 하이퍼링크가 최신 상태인지 여부를 나타냅니다. |
| [getHyperlinksChanged()](#getHyperlinksChanged--) | 이 파트에서 하나 이상의 하이퍼링크가 제작자에 의해 독점적으로 업데이트되었음을 지정합니다. |
| [setHyperlinksChanged(boolean value)](#setHyperlinksChanged-boolean-) | 이 파트에서 하나 이상의 하이퍼링크가 제작자에 의해 독점적으로 업데이트되었음을 지정합니다. |
| [getSlides()](#getSlides--) | 프레젠테이션 문서의 전체 슬라이드 수를 반환합니다. |
| [getHiddenSlides()](#getHiddenSlides--) | 프레젠테이션 문서에서 숨겨진 슬라이드 수를 반환합니다. |
| [getNotes()](#getNotes--) | 노트가 포함된 프레젠테이션 슬라이드 수를 반환합니다. |
| [getParagraphs()](#getParagraphs--) | 문서에서 찾은 전체 단락 수를 반환합니다(해당되는 경우). |
| [getWords()](#getWords--) | 문서에 포함된 전체 단어 수를 반환합니다. |
| [getMultimediaClips()](#getMultimediaClips--) | 문서에 존재하는 전체 오디오 또는 비디오 클립 수를 반환합니다. |
| [getTitlesOfParts()](#getTitlesOfParts--) | 각 문서 파트의 제목을 지정합니다. |
| [getHeadingPairs()](#getHeadingPairs--) | 문서 파트의 그룹화 및 각 그룹의 파트 수를 나타냅니다. |
| [deepClone()](#deepClone--) | 현재 객체를 복제합니다 |
| [cloneT()](#cloneT--) | 현재 객체를 복제합니다 |

### DocumentProperties() {#DocumentProperties--}
```
public DocumentProperties()
```

클래스 [DocumentProperties](../../com.aspose.slides/documentproperties)의 새 인스턴스를 초기화합니다.

### getAppVersion() {#getAppVersion--}
```
public final String getAppVersion()
```

앱 버전을 반환합니다. 읽기 전용 String.

**반환:**  
java.lang.String

### getNameOfApplication() {#getNameOfApplication--}
```
public final String getNameOfApplication()
```

응용 프로그램의 이름을 반환하거나 설정합니다. 읽기/쓰기 String.

**반환:**  
java.lang.String

### setNameOfApplication(String value) {#setNameOfApplication-java.lang.String-}
```
public final void setNameOfApplication(String value)
```

응용 프로그램의 이름을 반환하거나 설정합니다. 읽기/쓰기 String.

**매개변수:**  
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | java.lang.String |  |

### getCompany() {#getCompany--}
```
public final String getCompany()
```

회사 속성을 반환하거나 설정합니다. 읽기/쓰기 String.

**반환:**  
java.lang.String

### setCompany(String value) {#setCompany-java.lang.String-}
```
public final void setCompany(String value)
```

회사 속성을 반환하거나 설정합니다. 읽기/쓰기 String.

**매개변수:**  
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | java.lang.String |  |

### getManager() {#getManager--}
```
public final String getManager()
```

관리자 속성을 반환하거나 설정합니다. 읽기/쓰기 String.

**반환:**  
java.lang.String

### setManager(String value) {#setManager-java.lang.String-}
```
public final void setManager(String value)
```

관리자 속성을 반환하거나 설정합니다. 읽기/쓰기 String.

**매개변수:**  
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | java.lang.String |  |

### getPresentationFormat() {#getPresentationFormat--}
```
public final String getPresentationFormat()
```

프레젠테이션의 의도된 형식을 반환하거나 설정합니다. 읽기/쓰기 String.

**반환:**  
java.lang.String

### setPresentationFormat(String value) {#setPresentationFormat-java.lang.String-}
```
public final void setPresentationFormat(String value)
```

프레젠테이션의 의도된 형식을 반환하거나 설정합니다. 읽기/쓰기 String.

**매개변수:**  
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | java.lang.String |  |

### getSharedDoc() {#getSharedDoc--}
```
public final boolean getSharedDoc()
```

프레젠테이션이 여러 사람과 공유되는지 여부를 판단합니다. 읽기/쓰기 boolean.

**반환:**  
boolean

### setSharedDoc(boolean value) {#setSharedDoc-boolean-}
```
public final void setSharedDoc(boolean value)
```

프레젠테이션이 여러 사람과 공유되는지 여부를 판단합니다. 읽기/쓰기 boolean.

**매개변수:**  
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | boolean |  |

### getApplicationTemplate() {#getApplicationTemplate--}
```
public final String getApplicationTemplate()
```

응용 프로그램의 템플릿을 반환하거나 설정합니다. 읽기/쓰기 String.

**반환:**  
java.lang.String

### setApplicationTemplate(String value) {#setApplicationTemplate-java.lang.String-}
```
public final void setApplicationTemplate(String value)
```

응용 프로그램의 템플릿을 반환하거나 설정합니다. 읽기/쓰기 String.

**매개변수:**  
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | java.lang.String |  |

### getTotalEditingTime() {#getTotalEditingTime--}
```
public final double getTotalEditingTime()
```

프레젠테이션의 총 편집 시간을 반환합니다. 읽기/쓰기 double.

**반환:**  
double

### setTotalEditingTime(double value) {#setTotalEditingTime-double-}
```
public final void setTotalEditingTime(double value)
```

프레젠테이션의 총 편집 시간을 반환합니다. 읽기/쓰기 double.

**매개변수:**  
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | double |  |

### getTitle() {#getTitle--}
```
public final String getTitle()
```

프레젠테이션의 제목을 반환하거나 설정합니다. 읽기/쓰기 String.

**반환:**  
java.lang.String

### setTitle(String value) {#setTitle-java.lang.String-}
```
public final void setTitle(String value)
```

프레젠테이션의 제목을 반환하거나 설정합니다. 읽기/쓰기 String.

**매개변수:**  
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | java.lang.String |  |

### getSubject() {#getSubject--}
```
public final String getSubject()
```

프레젠테이션의 주제를 반환하거나 설정합니다. 읽기/쓰기 String.

**반환:**  
java.lang.String

### setSubject(String value) {#setSubject-java.lang.String-}
```
public final void setSubject(String value)
```

프레젠테이션의 주제를 반환하거나 설정합니다. 읽기/쓰기 String.

**매개변수:**  
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | java.lang.String |  |

### getAuthor() {#getAuthor--}
```
public final String getAuthor()
```

프레젠테이션의 저자를 반환하거나 설정합니다. 읽기/쓰기 String.

**반환:**  
java.lang.String

### setAuthor(String value) {#setAuthor-java.lang.String-}
```
public final void setAuthor(String value)
```

프레젠테이션의 저자를 반환하거나 설정합니다. 읽기/쓰기 String.

**매개변수:**  
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | java.lang.String |  |

### getKeywords() {#getKeywords--}
```
public final String getKeywords()
```

프레젠테이션의 키워드를 반환하거나 설정합니다. 읽기/쓰기 String.

**반환:**  
java.lang.String

### setKeywords(String value) {#setKeywords-java.lang.String-}
```
public final void setKeywords(String value)
```

프레젠테이션의 키워드를 반환하거나 설정합니다. 읽기/쓰기 String.

**매개변수:**  
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | java.lang.String |  |

### getComments() {#getComments--}
```
public final String getComments()
```

프레젠테이션의 설명을 반환하거나 설정합니다. 읽기/쓰기 String.

**반환:**  
java.lang.String

### setComments(String value) {#setComments-java.lang.String-}
```
public final void setComments(String value)
```

프레젠테이션의 설명을 반환하거나 설정합니다. 읽기/쓰기 String.

**매개변수:**  
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | java.lang.String |  |

### getCategory() {#getCategory--}
```
public final String getCategory()
```

프레젠테이션의 카테고리를 반환하거나 설정합니다. 읽기/쓰기 String.

**반환:**  
java.lang.String

### setCategory(String value) {#setCategory-java.lang.String-}
```
public final void setCategory(String value)
```

프레젠테이션의 카테고리를 반환하거나 설정합니다. 읽기/쓰기 String.

**매개변수:**  
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | java.lang.String |  |

### getCreatedTime() {#getCreatedTime--}
```
public final Date getCreatedTime()
```

프레젠테이션이 생성된 날짜를 반환합니다. UTC 기준입니다. 읽기/쓰기 java.util.Date.

**반환:**  
java.util.Date

### setCreatedTime(Date value) {#setCreatedTime-java.util.Date-}
```
public final void setCreatedTime(Date value)
```

프레젠테이션이 생성된 날짜를 반환합니다. UTC 기준입니다. 읽기/쓰기 java.util.Date.

**매개변수:**  
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | java.util.Date |  |

### getLastSavedTime() {#getLastSavedTime--}
```
public final Date getLastSavedTime()
```

프레젠테이션이 마지막으로 수정된 날짜를 반환합니다. UTC 기준입니다. Presentation.DocumentProperties의 경우 읽기 전용이며, IPresentation 객체 저장 과정에서 내부적으로 업데이트됩니다. 메서드 [IPresentationInfo.readDocumentProperties](../../com.aspose.slides/ipresentationinfo\#readDocumentProperties)가 반환하는 DocumentProperties 인스턴스를 통해 변경할 수 있습니다. 자세한 내용은 [IPresentationInfo.updateDocumentProperties(IDocumentProperties)](../../com.aspose.slides/ipresentationinfo\#updateDocumentProperties-IDocumentProperties-) 메서드 요약의 예제를 참조하십시오.

**반환:**  
java.util.Date

### setLastSavedTime(Date value) {#setLastSavedTime-java.util.Date-}
```
public final void setLastSavedTime(Date value)
```

프레젠테이션이 마지막으로 수정된 날짜를 반환합니다. UTC 기준이며, Presentation.DocumentProperties의 경우 읽기 전용입니다. 메서드 [IPresentationInfo.readDocumentProperties](../../com.aspose.slides/ipresentationinfo\#readDocumentProperties)가 반환하는 DocumentProperties 인스턴스를 통해 변경할 수 있습니다. 자세한 내용은 [IPresentationInfo.updateDocumentProperties(IDocumentProperties)](../../com.aspose.slides/ipresentationinfo\#updateDocumentProperties-IDocumentProperties-) 메서드 요약의 예제를 참조하십시오.

**매개변수:**  
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | java.util.Date |  |

### getLastPrinted() {#getLastPrinted--}
```
public final Date getLastPrinted()
```

프레젠테이션이 마지막으로 인쇄된 날짜를 반환합니다. 읽기/쓰기 java.util.Date.

**반환:**  
java.util.Date

### setLastPrinted(Date value) {#setLastPrinted-java.util.Date-}
```
public final void setLastPrinted(Date value)
```

프레젠테이션이 마지막으로 인쇄된 날짜를 반환합니다. 읽기/쓰기 java.util.Date.

**매개변수:**  
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | java.util.Date |  |

### getLastSavedBy() {#getLastSavedBy--}
```
public final String getLastSavedBy()
```

마지막으로 프레젠테이션을 수정한 사람의 이름을 반환하거나 설정합니다. 읽기/쓰기 String.

**반환:**  
java.lang.String

### setLastSavedBy(String value) {#setLastSavedBy-java.lang.String-}
```
public final void setLastSavedBy(String value)
```

마지막으로 프레젠테이션을 수정한 사람의 이름을 반환하거나 설정합니다. 읽기/쓰기 String.

**매개변수:**  
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | java.lang.String |  |

### getRevisionNumber() {#getRevisionNumber--}
```
public final int getRevisionNumber()
```

프레젠테이션의 리비전 번호를 반환하거나 설정합니다. 읽기/쓰기 int.

**반환:**  
int

### setRevisionNumber(int value) {#setRevisionNumber-int-}
```
public final void setRevisionNumber(int value)
```

프레젠테이션의 리비전 번호를 반환하거나 설정합니다. 읽기/쓰기 int.

**매개변수:**  
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | int |  |

### getContentStatus() {#getContentStatus--}
```
public final String getContentStatus()
```

프레젠테이션의 콘텐츠 상태를 반환하거나 설정합니다. 읽기/쓰기 String.

**반환:**  
java.lang.String

### setContentStatus(String value) {#setContentStatus-java.lang.String-}
```
public final void setContentStatus(String value)
```

프레젠테이션의 콘텐츠 상태를 반환하거나 설정합니다. 읽기/쓰기 String.

**매개변수:**  
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | java.lang.String |  |

### getContentType() {#getContentType--}
```
public final String getContentType()
```

프레젠테이션의 콘텐츠 유형을 반환하거나 설정합니다. 읽기/쓰기 String.

**반환:**  
java.lang.String

### setContentType(String value) {#setContentType-java.lang.String-}
```
public final void setContentType(String value)
```

프레젠테이션의 콘텐츠 유형을 반환하거나 설정합니다. 읽기/쓰기 String.

**매개변수:**  
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | java.lang.String |  |

### getHyperlinkBase() {#getHyperlinkBase--}
```
public final String getHyperlinkBase()
```

HyperlinkBase 문서 속성을 반환하거나 설정합니다. 읽기/쓰기 String.

**반환:**  
java.lang.String

### setHyperlinkBase(String value) {#setHyperlinkBase-java.lang.String-}
```
public final void setHyperlinkBase(String value)
```

HyperlinkBase 문서 속성을 반환하거나 설정합니다. 읽기/쓰기 String.

**매개변수:**  
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | java.lang.String |  |

### getCountOfCustomProperties() {#getCountOfCustomProperties--}
```
public final int getCountOfCustomProperties()
```

컬렉션에 실제 포함된 사용자 정의 속성 수를 반환합니다. 읽기 전용 int.

**반환:**  
int

### getCustomPropertyName(int index) {#getCustomPropertyName-int-}
```
public final String getCustomPropertyName(int index)
```

지정된 인덱스에 있는 사용자 정의 속성 이름을 반환합니다.

**매개변수:**  
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| index | int | 사용자 정의 속성을 가져올 0부터 시작하는 인덱스 |

**반환:**  
java.lang.String - 지정된 인덱스의 사용자 정의 속성 이름.

### removeCustomProperty(String name) {#removeCustomProperty-java.lang.String-}
```
public final boolean removeCustomProperty(String name)
```

지정된 이름과 연결된 사용자 정의 속성을 제거합니다.

**매개변수:**  
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| name | java.lang.String | 제거할 사용자 정의 속성의 이름 |

**반환:**  
boolean - 속성이 제거되면 true, 그렇지 않으면 false.

### containsCustomProperty(String name) {#containsCustomProperty-java.lang.String-}
```
public final boolean containsCustomProperty(String name)
```

지정된 이름을 가진 사용자 정의 속성의 존재 여부를 확인합니다.

**매개변수:**  
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| name | java.lang.String | 확인할 사용자 정의 속성의 이름 |

**반환:**  
boolean - 속성이 존재하면 true, 그렇지 않으면 false.

### get_Item(String name) {#get-Item-java.lang.String-}
```
public final Object get_Item(String name)
```

지정된 이름과 연결된 사용자 정의 속성을 반환하거나 설정합니다. 읽기/쓰기 Object.

값은 **int**, **float**, **String**, **boolean** 또는 **Date** 일 수 있습니다.

**매개변수:**  
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| name | java.lang.String |  |

**반환:**  
java.lang.Object

### set_Item(String name, Object value) {#set-Item-java.lang.String-java.lang.Object-}
```
public final void set_Item(String name, Object value)
```

지정된 이름과 연결된 사용자 정의 속성을 반환하거나 설정합니다. 읽기/쓰기 Object.

값은 **int**, **float**, **String**, **boolean** 또는 **Date** 일 수 있습니다.

**매개변수:**  
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| name | java.lang.String |  |
| value | java.lang.Object |  |

### getCustomPropertyValue(String name, boolean[] value) {#getCustomPropertyValue-java.lang.String-boolean---}
```
public final void getCustomPropertyValue(String name, boolean[] value)
```

지정된 이름의 부울 값을 사용자 정의 속성에서 가져옵니다.

**매개변수:**  
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| name | java.lang.String | 가져올 사용자 정의 속성의 이름 |
| value | boolean[] | 사용자 정의 속성 값 |

### getCustomPropertyValue(String name, int[] value) {#getCustomPropertyValue-java.lang.String-int---}
```
public final void getCustomPropertyValue(String name, int[] value)
```

지정된 이름의 정수 값을 사용자 정의 속성에서 가져옵니다.

**매개변수:**  
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| name | java.lang.String | 가져올 사용자 정의 속성의 이름 |
| value | int[] | 사용자 정의 속성 값 |

### getCustomPropertyValue(String name, Date[] value) {#getCustomPropertyValue-java.lang.String-java.util.Date---}
```
public final void getCustomPropertyValue(String name, Date[] value)
```

지정된 이름의 DateTime 값을 사용자 정의 속성에서 가져옵니다.

**매개변수:**  
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| name | java.lang.String | 가져올 사용자 정의 속성의 이름 |
| value | java.util.Date[] | 사용자 정의 속성 값 |

### getCustomPropertyValue(String name, String[] value) {#getCustomPropertyValue-java.lang.String-java.lang.String---}
```
public final void getCustomPropertyValue(String name, String[] value)
```

지정된 이름의 문자열 값을 사용자 정의 속성에서 가져옵니다.

**매개변수:**  
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| name | java.lang.String | 가져올 사용자 정의 속성의 이름 |
| value | java.lang.String[] | 사용자 정의 속성 값 |

### getCustomPropertyValue(String name, float[] value) {#getCustomPropertyValue-java.lang.String-float---}
```
public final void getCustomPropertyValue(String name, float[] value)
```

지정된 이름의 부동소수점 값을 사용자 정의 속성에서 가져옵니다.

**매개변수:**  
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| name | java.lang.String | 가져올 사용자 정의 속성의 이름 |
| value | float[] | 사용자 정의 속성 값 |

### getCustomPropertyValue(String name, double[] value) {#getCustomPropertyValue-java.lang.String-double---}
```
public final void getCustomPropertyValue(String name, double[] value)
```

지정된 이름의 배정밀도 부동소수점 값을 사용자 정의 속성에서 가져옵니다.

**매개변수:**  
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| name | java.lang.String | 가져올 사용자 정의 속성의 이름 |
| value | double[] | 사용자 정의 속성 값 |

### setCustomPropertyValue(String name, boolean value) {#setCustomPropertyValue-java.lang.String-boolean-}
```
public final void setCustomPropertyValue(String name, boolean value)
```

지정된 이름의 부울 사용자 정의 속성을 설정합니다.

**매개변수:**  
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| name | java.lang.String | 설정할 사용자 정의 속성의 이름 |
| value | boolean | 사용자 정의 속성 값 |

### setCustomPropertyValue(String name, int value) {#setCustomPropertyValue-java.lang.String-int-}
```
public final void setCustomPropertyValue(String name, int value)
```

지정된 이름의 정수 사용자 정의 속성을 설정합니다.

**매개변수:**  
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| name | java.lang.String | 설정할 사용자 정의 속성의 이름 |
| value | int | 사용자 정의 속성 값 |

### setCustomPropertyValue(String name, Date value) {#setCustomPropertyValue-java.lang.String-java.util.Date-}
```
public final void setCustomPropertyValue(String name, Date value)
```

지정된 이름의 DateTime 사용자 정의 속성을 설정합니다.

**매개변수:**  
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| name | java.lang.String | 설정할 사용자 정의 속성의 이름 |
| value | java.util.Date | 사용자 정의 속성 값 |

### setCustomPropertyValue(String name, String value) {#setCustomPropertyValue-java.lang.String-java.lang.String-}
```
public final void setCustomPropertyValue(String name, String value)
```

지정된 이름의 문자열 사용자 정의 속성을 설정합니다.

**매개변수:**  
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| name | java.lang.String | 설정할 사용자 정의 속성의 이름 |
| value | java.lang.String | 사용자 정의 속성 값 |

### setCustomPropertyValue(String name, float value) {#setCustomPropertyValue-java.lang.String-float-}
```
public final void setCustomPropertyValue(String name, float value)
```

지정된 이름의 부동소수점 사용자 정의 속성을 설정합니다.

**매개변수:**  
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| name | java.lang.String | 설정할 사용자 정의 속성의 이름 |
| value | float | 사용자 정의 속성 값 |

### setCustomPropertyValue(String name, double value) {#setCustomPropertyValue-java.lang.String-double-}
```
public final void setCustomPropertyValue(String name, double value)
```

지정된 이름의 배정밀도 부동소수점 사용자 정의 속성을 설정합니다.

**매개변수:**  
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| name | java.lang.String | 설정할 사용자 정의 속성의 이름 |
| value | double | 사용자 정의 속성 값 |

### clearCustomProperties() {#clearCustomProperties--}
```
public final void clearCustomProperties()
```

모든 사용자 정의 속성을 제거합니다.

### getSensitivityLabels() {#getSensitivityLabels--}
```
public final ISensitivityLabel[] getSensitivityLabels()
```

사용자 정의 문서 속성(Microsoft Information Protection SDK 메타데이터)에서 민감도 레이블 배열을 가져옵니다.

> ```
> The following code shows how to move the sensitivity labels information from the custom document properties 
>   to the modern SensitivityLabels collection:
>   
>  Presentation pres = new Presentation("SomePresentation.pptx");
>  try {
>      // 사용자 정의 문서 속성에서 민감도 레이블을 가져옵니다
>      ISensitivityLabel[] mipSensitivityLabels = pres.getDocumentProperties().getSensitivityLabels();
>      ISensitivityLabelCollection sensitivityLabels = pres.getSensitivityLabels();
>      for (ISensitivityLabel sensitivityLabel : mipSensitivityLabels)
>      {
>          // 컬렉션에 레이블을 추가합니다
>          // 여기에서 레이블 정보의 유효성을 확인하는 검사를 추가할 수 있습니다 (레이블이 사용 가능한지 등)
>          sensitivityLabels.add(sensitivityLabel);
>      }
>      pres.save("SensitivityLabel.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**반환:**  
com.aspose.slides.ISensitivityLabel[]

### clearBuiltInProperties() {#clearBuiltInProperties--}
```
public final void clearBuiltInProperties()
```

모든 builtIn 속성을 지우고 기본값으로 설정합니다.

### getScaleCrop() {#getScaleCrop--}
```
public final boolean getScaleCrop()
```

문서 썸네일의 표시 모드를 나타냅니다. 이 요소를 **true** 로 설정하면 썸네일을 화면에 맞게 확대/축소합니다. **false** 로 설정하면 화면에 맞는 부분만 표시하도록 썸네일을 자릅니다. 읽기/쓰기 boolean.

**반환:**  
boolean

### setScaleCrop(boolean value) {#setScaleCrop-boolean-}
```
public final void setScaleCrop(boolean value)
```

문서 썸네일의 표시 모드를 나타냅니다. 이 요소를 **true** 로 설정하면 썸네일을 화면에 맞게 확대/축소합니다. **false** 로 설정하면 화면에 맞는 부분만 표시하도록 썸네일을 자릅니다. 읽기/쓰기 boolean.

**매개변수:**  
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | boolean |  |

### getLinksUpToDate() {#getLinksUpToDate--}
```
public final boolean getLinksUpToDate()
```

문서의 하이퍼링크가 최신 상태인지 여부를 나타냅니다. 이 요소를 **true** 로 설정하면 하이퍼링크가 업데이트된 것으로 표시합니다. **false** 로 설정하면 하이퍼링크가 오래된 것으로 표시합니다. 읽기/쓰기 boolean.

**반환:**  
boolean

### setLinksUpToDate(boolean value) {#setLinksUpToDate-boolean-}
```
public final void setLinksUpToDate(boolean value)
```

문서의 하이퍼링크가 최신 상태인지 여부를 나타냅니다. 이 요소를 **true** 로 설정하면 하이퍼링크가 업데이트된 것으로 표시합니다. **false** 로 설정하면 하이퍼링크가 오래된 것으로 표시합니다. 읽기/쓰기 boolean.

**매개변수:**  
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | boolean |  |

### getHyperlinksChanged() {#getHyperlinksChanged--}
```
public final boolean getHyperlinksChanged()
```

이 파트에서 하나 이상의 하이퍼링크가 제작자에 의해 독점적으로 업데이트되었음을 지정합니다. 다음 제작자가 문서를 열면 이 파트에 지정된 새 하이퍼링크로 관계가 업데이트됩니다. 읽기/쓰기 boolean.

**반환:**  
boolean

### setHyperlinksChanged(boolean value) {#setHyperlinksChanged-boolean-}
```
public final void setHyperlinksChanged(boolean value)
```

이 파트에서 하나 이상의 하이퍼링크가 제작자에 의해 독점적으로 업데이트되었음을 지정합니다. 다음 제작자가 문서를 열면 이 파트에 지정된 새 하이퍼링크로 관계가 업데이트됩니다. 읽기/쓰기 boolean.

**매개변수:**  
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | boolean |  |

### getSlides() {#getSlides--}
```
public final int getSlides()
```

프레젠테이션 문서의 전체 슬라이드 수를 반환합니다. 읽기 전용 int.

**반환:**  
int

### getHiddenSlides() {#getHiddenSlides--}
```
public final int getHiddenSlides()
```

프레젠테이션 문서에서 숨겨진 슬라이드 수를 반환합니다. 읽기 전용 int.

**반환:**  
int

### getNotes() {#getNotes--}
```
public final int getNotes()
```

노트가 포함된 프레젠테이션 슬라이드 수를 반환합니다. 읽기 전용 int.

**반환:**  
int

### getParagraphs() {#getParagraphs--}
```
public final int getParagraphs()
```

해당되는 경우 문서에서 찾은 전체 단락 수를 반환합니다. 읽기 전용 int.

**반환:**  
int

### getWords() {#getWords--}
```
public final int getWords()
```

문서에 포함된 전체 단어 수를 반환합니다. 읽기 전용 int.

**반환:**  
int

### getMultimediaClips() {#getMultimediaClips--}
```
public final int getMultimediaClips()
```

문서에 존재하는 전체 오디오 또는 비디오 클립 수를 반환합니다. 읽기 전용 int.

**반환:**  
int

### getTitlesOfParts() {#getTitlesOfParts--}
```
public final String[] getTitlesOfParts()
```

각 문서 파트의 제목을 지정합니다. 이 파트들은 실제 문서 파트가 아니라 문서 섹션의 개념적 표현입니다. 읽기 전용 String[].

**반환:**  
java.lang.String[]

### getHeadingPairs() {#getHeadingPairs--}
```
public final IHeadingPair[] getHeadingPairs()
```

문서 파트의 그룹화 및 각 그룹의 파트 수를 나타냅니다. 읽기 전용 IHeadingPair[].

**반환:**  
com.aspose.slides.IHeadingPair[]

### deepClone() {#deepClone--}
```
public final Object deepClone()
```

현재 객체를 복제합니다.

**반환:**  
java.lang.Object - Clone

### cloneT() {#cloneT--}
```
public final IDocumentProperties cloneT()
```

현재 객체를 복제합니다.

**반환:**  
[IDocumentProperties](../../com.aspose.slides/idocumentproperties) - Clone