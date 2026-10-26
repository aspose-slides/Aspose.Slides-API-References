---
title: IDocumentProperties
second_title: Aspose.Slides for Android via Java API Reference
description: Represents properties of a presentation.
type: docs
url: /ko/com.aspose.slides/idocumentproperties/
---```
public interface IDocumentProperties
```

프레젠테이션의 속성을 나타냅니다.
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
| [getSharedDoc()](#getSharedDoc--) | 프레젠테이션이 여러 사람과 공유되는지 여부를 확인합니다. |
| [setSharedDoc(boolean value)](#setSharedDoc-boolean-) | 프레젠테이션이 여러 사람과 공유되는지 여부를 확인합니다. |
| [getApplicationTemplate()](#getApplicationTemplate--) | 응용 프로그램의 템플릿을 반환하거나 설정합니다. |
| [setApplicationTemplate(String value)](#setApplicationTemplate-java.lang.String-) | 응용 프로그램의 템플릿을 반환하거나 설정합니다. |
| [getTotalEditingTime()](#getTotalEditingTime--) | 프레젠테이션의 총 편집 시간입니다. |
| [setTotalEditingTime(double value)](#setTotalEditingTime-double-) | 프레젠테이션의 총 편집 시간입니다. |
| [getTitle()](#getTitle--) | 프레젠테이션의 제목을 반환하거나 설정합니다. |
| [setTitle(String value)](#setTitle-java.lang.String-) | 프레젠테이션의 제목을 반환하거나 설정합니다. |
| [getSubject()](#getSubject--) | 프레젠테이션의 주제를 반환하거나 설정합니다. |
| [setSubject(String value)](#setSubject-java.lang.String-) | 프레젠테이션의 주제를 반환하거나 설정합니다. |
| [getAuthor()](#getAuthor--) | 프레젠테이션의 저자를 반환하거나 설정합니다. |
| [setAuthor(String value)](#setAuthor-java.lang.String-) | 프레젠테이션의 저자를 반환하거나 설정합니다. |
| [getKeywords()](#getKeywords--) | 프레젠테이션의 키워드를 반환하거나 설정합니다. |
| [setKeywords(String value)](#setKeywords-java.lang.String-) | 프레젠테이션의 키워드를 반환하거나 설정합니다. |
| [getComments()](#getComments--) | 프레젠테이션의 주석을 반환하거나 설정합니다. |
| [setComments(String value)](#setComments-java.lang.String-) | 프레젠테이션의 주석을 반환하거나 설정합니다. |
| [getCategory()](#getCategory--) | 프레젠테이션의 카테고리를 반환하거나 설정합니다. |
| [setCategory(String value)](#setCategory-java.lang.String-) | 프레젠테이션의 카테고리를 반환하거나 설정합니다. |
| [getCreatedTime()](#getCreatedTime--) | 프레젠테이션이 생성된 날짜를 반환합니다. |
| [setCreatedTime(Date value)](#setCreatedTime-java.util.Date-) | 프레젠테이션이 생성된 날짜를 반환합니다. |
| [getLastSavedTime()](#getLastSavedTime--) | 프레젠테이션이 마지막으로 수정된 날짜를 반환합니다. |
| [setLastSavedTime(Date value)](#setLastSavedTime-java.util.Date-) | 프레젠테이션이 마지막으로 수정된 날짜를 반환합니다. |
| [getLastPrinted()](#getLastPrinted--) | 프레젠테이션이 마지막으로 인쇄된 날짜를 반환합니다. |
| [setLastPrinted(Date value)](#setLastPrinted-java.util.Date-) | 프레젠테이션이 마지막으로 인쇄된 날짜를 반환합니다. |
| [getLastSavedBy()](#getLastSavedBy--) | 프레젠테이션을 마지막으로 수정한 사람의 이름을 반환하거나 설정합니다. |
| [setLastSavedBy(String value)](#setLastSavedBy-java.lang.String-) | 프레젠테이션을 마지막으로 수정한 사람의 이름을 반환하거나 설정합니다. |
| [getRevisionNumber()](#getRevisionNumber--) | 프레젠테이션 개정 번호를 반환하거나 설정합니다. |
| [setRevisionNumber(int value)](#setRevisionNumber-int-) | 프레젠테이션 개정 번호를 반환하거나 설정합니다. |
| [getContentStatus()](#getContentStatus--) | 프레젠테이션의 콘텐츠 상태를 반환하거나 설정합니다. |
| [setContentStatus(String value)](#setContentStatus-java.lang.String-) | 프레젠테이션의 콘텐츠 상태를 반환하거나 설정합니다. |
| [getContentType()](#getContentType--) | 프레젠테이션의 콘텐츠 유형을 반환하거나 설정합니다. |
| [setContentType(String value)](#setContentType-java.lang.String-) | 프레젠테이션의 콘텐츠 유형을 반환하거나 설정합니다. |
| [getHyperlinkBase()](#getHyperlinkBase--) | HyperlinkBase 문서 속성을 반환하거나 설정합니다. |
| [setHyperlinkBase(String value)](#setHyperlinkBase-java.lang.String-) | HyperlinkBase 문서 속성을 반환하거나 설정합니다. |
| [getScaleCrop()](#getScaleCrop--) | 문서 썸네일의 표시 모드를 나타냅니다. |
| [setScaleCrop(boolean value)](#setScaleCrop-boolean-) | 문서 썸네일의 표시 모드를 나타냅니다. |
| [getLinksUpToDate()](#getLinksUpToDate--) | 문서 내 하이퍼링크가 최신인지 여부를 나타냅니다. |
| [setLinksUpToDate(boolean value)](#setLinksUpToDate-boolean-) | 문서 내 하이퍼링크가 최신인지 여부를 나타냅니다. |
| [getHyperlinksChanged()](#getHyperlinksChanged--) | 제작자가 이 파트에서 독점적으로 하나 이상의 하이퍼링크를 업데이트했음을 지정합니다. |
| [setHyperlinksChanged(boolean value)](#setHyperlinksChanged-boolean-) | 제작자가 이 파트에서 독점적으로 하나 이상의 하이퍼링크를 업데이트했음을 지정합니다. |
| [getSlides()](#getSlides--) | 프레젠테이션 문서의 전체 슬라이드 수를 지정합니다. |
| [getHiddenSlides()](#getHiddenSlides--) | 프레젠테이션 문서의 숨겨진 슬라이드 수를 지정합니다. |
| [getNotes()](#getNotes--) | 노트가 포함된 프레젠테이션 슬라이드 수를 지정합니다. |
| [getParagraphs()](#getParagraphs--) | 해당되는 경우 문서에서 발견된 전체 단락 수를 지정합니다. |
| [getWords()](#getWords--) | 문서에 포함된 전체 단어 수를 지정합니다. |
| [getMultimediaClips()](#getMultimediaClips--) | 문서에 포함된 사운드 또는 비디오 클립의 총 수를 지정합니다. |
| [getTitlesOfParts()](#getTitlesOfParts--) | 각 문서 파트의 제목을 지정합니다. |
| [getHeadingPairs()](#getHeadingPairs--) | 문서 파트의 그룹화와 각 그룹의 파트 수를 나타냅니다. |
| [getCountOfCustomProperties()](#getCountOfCustomProperties--) | 컬렉션에 실제로 포함된 사용자 정의 속성 수를 반환합니다. |
| [getCustomPropertyName(int index)](#getCustomPropertyName-int-) | 지정된 인덱스의 사용자 정의 속성 이름을 반환합니다. |
| [removeCustomProperty(String name)](#removeCustomProperty-java.lang.String-) | 지정된 이름과 연관된 사용자 정의 속성을 제거합니다. |
| [containsCustomProperty(String name)](#containsCustomProperty-java.lang.String-) | 지정된 이름의 사용자 정의 속성 존재 여부를 확인합니다. |
| [get_Item(String name)](#get-Item-java.lang.String-) | 지정된 이름과 연관된 사용자 정의 속성을 반환하거나 설정합니다. |
| [set_Item(String name, Object value)](#set-Item-java.lang.String-java.lang.Object-) | 지정된 이름과 연관된 사용자 정의 속성을 반환하거나 설정합니다. |
| [clearCustomProperties()](#clearCustomProperties--) | 모든 사용자 정의 속성을 제거합니다. |
| [clearBuiltInProperties()](#clearBuiltInProperties--) | 모든 내장 속성을 지우고 기본값으로 설정합니다. |
| [getCustomPropertyValue(String name, boolean[] value)](#getCustomPropertyValue-java.lang.String-boolean---) | 사용자 정의 속성에서 지정된 이름의 boolean 값을 가져옵니다. |
| [getCustomPropertyValue(String name, int[] value)](#getCustomPropertyValue-java.lang.String-int---) | 사용자 정의 속성에서 지정된 이름의 integer 값을 가져옵니다. |
| [getCustomPropertyValue(String name, Date[] value)](#getCustomPropertyValue-java.lang.String-java.util.Date---) | 사용자 정의 속성에서 지정된 이름의 DateTime 값을 가져옵니다. |
| [getCustomPropertyValue(String name, String[] value)](#getCustomPropertyValue-java.lang.String-java.lang.String---) | 사용자 정의 속성에서 지정된 이름의 string 값을 가져옵니다. |
| [getCustomPropertyValue(String name, float[] value)](#getCustomPropertyValue-java.lang.String-float---) | 사용자 정의 속성에서 지정된 이름의 float 값을 가져옵니다. |
| [getCustomPropertyValue(String name, double[] value)](#getCustomPropertyValue-java.lang.String-double---) | 사용자 정의 속성에서 지정된 이름의 double 값을 가져옵니다. |
| [setCustomPropertyValue(String name, boolean value)](#setCustomPropertyValue-java.lang.String-boolean-) | 지정된 이름의 boolean 사용자 정의 속성을 설정합니다. |
| [setCustomPropertyValue(String name, int value)](#setCustomPropertyValue-java.lang.String-int-) | 지정된 이름의 integer 사용자 정의 속성을 설정합니다. |
| [setCustomPropertyValue(String name, Date value)](#setCustomPropertyValue-java.lang.String-java.util.Date-) | 지정된 이름의 DateTime 사용자 정의 속성을 설정합니다. |
| [setCustomPropertyValue(String name, String value)](#setCustomPropertyValue-java.lang.String-java.lang.String-) | 지정된 이름의 string 사용자 정의 속성을 설정합니다. |
| [setCustomPropertyValue(String name, float value)](#setCustomPropertyValue-java.lang.String-float-) | 지정된 이름의 float 사용자 정의 속성을 설정합니다. |
| [setCustomPropertyValue(String name, double value)](#setCustomPropertyValue-java.lang.String-double-) | 지정된 이름의 double 사용자 정의 속성을 설정합니다. |
| [getSensitivityLabels()](#getSensitivityLabels--) | 사용자 정의 문서 속성(Microsoft Information Protection SDK Metadata)에서 민감도 레이블 배열을 가져옵니다. |
### getAppVersion() {#getAppVersion--}
```
public abstract String getAppVersion()
```


앱 버전을 반환합니다. 읽기 전용 String.

--------------------

이 요소의 내용은 X와 Y가 숫자 값을 나타내는 형태인 XX.YYYY이어야 합니다. 그렇지 않으면 문서는 비규격으로 간주됩니다. Aspose.Slides는 버전을 XX.YY.ZZ 형식으로 표시합니다. 여기서: XX - 주요 버전, YY - 부 버전, ZZ - 패치 버전. 예를 들어 값 23.0105는 Aspose.Slides 버전 23.1.5를 의미합니다.

**반환값:**
java.lang.String
### getNameOfApplication() {#getNameOfApplication--}
```
public abstract String getNameOfApplication()
```


응용 프로그램의 이름을 반환하거나 설정합니다. 읽기/쓰기 String.

**반환값:**
java.lang.String
### setNameOfApplication(String value) {#setNameOfApplication-java.lang.String-}
```
public abstract void setNameOfApplication(String value)
```


응용 프로그램의 이름을 반환하거나 설정합니다. 읽기/쓰기 String.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | java.lang.String |  |

### getCompany() {#getCompany--}
```
public abstract String getCompany()
```


회사 속성을 반환하거나 설정합니다. 읽기/쓰기 String.

**반환값:**
java.lang.String
### setCompany(String value) {#setCompany-java.lang.String-}
```
public abstract void setCompany(String value)
```


회사 속성을 반환하거나 설정합니다. 읽기/쓰기 String.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | java.lang.String |  |

### getManager() {#getManager--}
```
public abstract String getManager()
```


관리자 속성을 반환하거나 설정합니다. 읽기/쓰기 String.

**반환값:**
java.lang.String
### setManager(String value) {#setManager-java.lang.String-}
```
public abstract void setManager(String value)
```


관리자 속성을 반환하거나 설정합니다. 읽기/쓰기 String.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | java.lang.String |  |

### getPresentationFormat() {#getPresentationFormat--}
```
public abstract String getPresentationFormat()
```


프레젠테이션의 의도된 형식을 반환하거나 설정합니다. 읽기/쓰기 String.

**반환값:**
java.lang.String
### setPresentationFormat(String value) {#setPresentationFormat-java.lang.String-}
```
public abstract void setPresentationFormat(String value)
```


프레젠테이션의 의도된 형식을 반환하거나 설정합니다. 읽기/쓰기 String.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | java.lang.String |  |

### getSharedDoc() {#getSharedDoc--}
```
public abstract boolean getSharedDoc()
```


프레젠테이션이 여러 사람과 공유되는지 여부를 확인합니다. 읽기/쓰기 boolean.

**반환값:**
boolean
### setSharedDoc(boolean value) {#setSharedDoc-boolean-}
```
public abstract void setSharedDoc(boolean value)
```


프레젠테이션이 여러 사람과 공유되는지 여부를 확인합니다. 읽기/쓰기 boolean.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | boolean |  |

### getApplicationTemplate() {#getApplicationTemplate--}
```
public abstract String getApplicationTemplate()
```


응용 프로그램의 템플릿을 반환하거나 설정합니다. 읽기/쓰기 String.

**반환값:**
java.lang.String
### setApplicationTemplate(String value) {#setApplicationTemplate-java.lang.String-}
```
public abstract void setApplicationTemplate(String value)
```


응용 프로그램의 템플릿을 반환하거나 설정합니다. 읽기/쓰기 String.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | java.lang.String |  |

### getTotalEditingTime() {#getTotalEditingTime--}
```
public abstract double getTotalEditingTime()
```


프레젠테이션의 총 편집 시간입니다. 읽기/쓰기 double.

**반환값:**
double
### setTotalEditingTime(double value) {#setTotalEditingTime-double-}
```
public abstract void setTotalEditingTime(double value)
```


프레젠테이션의 총 편집 시간입니다. 읽기/쓰기 double.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | double |  |

### getTitle() {#getTitle--}
```
public abstract String getTitle()
```


프레젠테이션의 제목을 반환하거나 설정합니다. 읽기/쓰기 String.

**반환값:**
java.lang.String
### setTitle(String value) {#setTitle-java.lang.String-}
```
public abstract void setTitle(String value)
```


프레젠테이션의 제목을 반환하거나 설정합니다. 읽기/쓰기 String.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | java.lang.String |  |

### getSubject() {#getSubject--}
```
public abstract String getSubject()
```


프레젠테이션의 주제를 반환하거나 설정합니다. 읽기/쓰기 String.

**반환값:**
java.lang.String
### setSubject(String value) {#setSubject-java.lang.String-}
```
public abstract void setSubject(String value)
```


프레젠테이션의 주제를 반환하거나 설정합니다. 읽기/쓰기 String.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | java.lang.String |  |

### getAuthor() {#getAuthor--}
```
public abstract String getAuthor()
```


프레젠테이션의 저자를 반환하거나 설정합니다. 읽기/쓰기 String.

**반환값:**
java.lang.String
### setAuthor(String value) {#setAuthor-java.lang.String-}
```
public abstract void setAuthor(String value)
```


프레젠테이션의 저자를 반환하거나 설정합니다. 읽기/쓰기 String.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | java.lang.String |  |

### getKeywords() {#getKeywords--}
```
public abstract String getKeywords()
```


프레젠테이션의 키워드를 반환하거나 설정합니다. 읽기/쓰기 String.

**반환값:**
java.lang.String
### setKeywords(String value) {#setKeywords-java.lang.String-}
```
public abstract void setKeywords(String value)
```


프레젠테이션의 키워드를 반환하거나 설정합니다. 읽기/쓰기 String.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | java.lang.String |  |

### getComments() {#getComments--}
```
public abstract String getComments()
```


프레젠테이션의 주석을 반환하거나 설정합니다. 읽기/쓰기 String.

**반환값:**
java.lang.String
### setComments(String value) {#setComments-java.lang.String-}
```
public abstract void setComments(String value)
```


프레젠테이션의 주석을 반환하거나 설정합니다. 읽기/쓰기 String.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | java.lang.String |  |

### getCategory() {#getCategory--}
```
public abstract String getCategory()
```


프레젠테이션의 카테고리를 반환하거나 설정합니다. 읽기/쓰기 String.

**반환값:**
java.lang.String
### setCategory(String value) {#setCategory-java.lang.String-}
```
public abstract void setCategory(String value)
```


프레젠테이션의 카테고리를 반환하거나 설정합니다. 읽기/쓰기 String.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | java.lang.String |  |

### getCreatedTime() {#getCreatedTime--}
```
public abstract Date getCreatedTime()
```


프레젠테이션이 생성된 날짜를 반환합니다. 값은 UTC 기준입니다. 읽기/쓰기 java.util.Date.

**반환값:**
java.util.Date
### setCreatedTime(Date value) {#setCreatedTime-java.util.Date-}
```
public abstract void setCreatedTime(Date value)
```


프레젠테이션이 생성된 날짜를 반환합니다. 값은 UTC 기준입니다. 읽기/쓰기 java.util.Date.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | java.util.Date |  |

### getLastSavedTime() {#getLastSavedTime--}
```
public abstract Date getLastSavedTime()
```


프레젠테이션이 마지막으로 수정된 날짜를 반환합니다. 값은 UTC 기준입니다. Presentation.DocumentProperties의 경우 읽기 전용(저장 프로세스 중 내부적으로 업데이트됨). 메서드 [IPresentationInfo.readDocumentProperties](../../com.aspose.slides/ipresentationinfo\#readDocumentProperties)가 반환하는 DocumentProperties 인스턴스를 통해 변경할 수 있습니다. 예제는 [IPresentationInfo.updateDocumentProperties(IDocumentProperties)](../../com.aspose.slides/ipresentationinfo\#updateDocumentProperties-IDocumentProperties-) 메서드 요약을 참고하세요.

**반환값:**
java.util.Date
### setLastSavedTime(Date value) {#setLastSavedTime-java.util.Date-}
```
public abstract void setLastSavedTime(Date value)
```


프레젠테이션이 마지막으로 수정된 날짜를 반환합니다. 값은 UTC 기준입니다. Presentation.DocumentProperties의 경우 읽기 전용(저장 프로세스 중 내부적으로 업데이트됨). 메서드 [IPresentationInfo.readDocumentProperties](../../com.aspose.slides/ipresentationinfo\#readDocumentProperties)가 반환하는 DocumentProperties 인스턴스를 통해 변경할 수 있습니다. 예제는 [IPresentationInfo.updateDocumentProperties(IDocumentProperties)](../../com.aspose.slides/ipresentationinfo\#updateDocumentProperties-IDocumentProperties-) 메서드 요약을 참고하세요.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | java.util.Date |  |

### getLastPrinted() {#getLastPrinted--}
```
public abstract Date getLastPrinted()
```


프레젠테이션이 마지막으로 인쇄된 날짜를 반환합니다. 읽기/쓰기 java.util.Date.

**반환값:**
java.util.Date
### setLastPrinted(Date value) {#setLastPrinted-java.util.Date-}
```
public abstract void setLastPrinted(Date value)
```


프레젠테이션이 마지막으로 인쇄된 날짜를 반환합니다. 읽기/쓰기 java.util.Date.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | java.util.Date |  |

### getLastSavedBy() {#getLastSavedBy--}
```
public abstract String getLastSavedBy()
```


프레젠테이션을 마지막으로 수정한 사람의 이름을 반환하거나 설정합니다. 읽기/쓰기 String.

**반환값:**
java.lang.String
### setLastSavedBy(String value) {#setLastSavedBy-java.lang.String-}
```
public abstract void setLastSavedBy(String value)
```


프레젠테이션을 마지막으로 수정한 사람의 이름을 반환하거나 설정합니다. 읽기/쓰기 String.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | java.lang.String |  |

### getRevisionNumber() {#getRevisionNumber--}
```
public abstract int getRevisionNumber()
```


프레젠테이션 개정 번호를 반환하거나 설정합니다. 읽기/쓰기 int.

**반환값:**
int
### setRevisionNumber(int value) {#setRevisionNumber-int-}
```
public abstract void setRevisionNumber(int value)
```


프레젠테이션 개정 번호를 반환하거나 설정합니다. 읽기/쓰기 int.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | int |  |

### getContentStatus() {#getContentStatus--}
```
public abstract String getContentStatus()
```


프레젠테이션의 콘텐츠 상태를 반환하거나 설정합니다. 읽기/쓰기 String.

**반환값:**
java.lang.String
### setContentStatus(String value) {#setContentStatus-java.lang.String-}
```
public abstract void setContentStatus(String value)
```


프레젠테이션의 콘텐츠 상태를 반환하거나 설정합니다. 읽기/쓰기 String.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | java.lang.String |  |

### getContentType() {#getContentType--}
```
public abstract String getContentType()
```


프레젠테이션의 콘텐츠 유형을 반환하거나 설정합니다. 읽기/쓰기 String.

**반환값:**
java.lang.String
### setContentType(String value) {#setContentType-java.lang.String-}
```
public abstract void setContentType(String value)
```


프레젠테이션의 콘텐츠 유형을 반환하거나 설정합니다. 읽기/쓰기 String.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | java.lang.String |  |

### getHyperlinkBase() {#getHyperlinkBase--}
```
public abstract String getHyperlinkBase()
```


HyperlinkBase 문서 속성을 반환하거나 설정합니다. 읽기/쓰기 String.

**반환값:**
java.lang.String
### setHyperlinkBase(String value) {#setHyperlinkBase-java.lang.String-}
```
public abstract void setHyperlinkBase(String value)
```


HyperlinkBase 문서 속성을 반환하거나 설정합니다. 읽기/쓰기 String.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | java.lang.String |  |

### getScaleCrop() {#getScaleCrop--}
```
public abstract boolean getScaleCrop()
```


문서 썸네일의 표시 모드를 나타냅니다. 이 요소를 **true** 로 설정하면 썸네일을 디스플레이에 맞게 확대합니다. **false** 로 설정하면 디스플레이에 맞게 썸네일을 잘라 표시합니다. 읽기/쓰기 boolean.

**반환값:**
boolean
### setScaleCrop(boolean value) {#setScaleCrop-boolean-}
```
public abstract void setScaleCrop(boolean value)
```


문서 썸네일의 표시 모드를 나타냅니다. 이 요소를 **true** 로 설정하면 썸네일을 디스플레이에 맞게 확대합니다. **false** 로 설정하면 디스플레이에 맞게 썸네일을 잘라 표시합니다. 읽기/쓰기 boolean.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | boolean |  |

### getLinksUpToDate() {#getLinksUpToDate--}
```
public abstract boolean getLinksUpToDate()
```


문서 내 하이퍼링크가 최신인지 여부를 나타냅니다. 이 요소를 **true** 로 설정하면 하이퍼링크가 업데이트되었음을 나타냅니다. **false** 로 설정하면 하이퍼링크가 오래되었음을 나타냅니다. 읽기/쓰기 boolean.

**반환값:**
boolean
### setLinksUpToDate(boolean value) {#setLinksUpToDate-boolean-}
```
public abstract void setLinksUpToDate(boolean value)
```


문서 내 하이퍼링크가 최신인지 여부를 나타냅니다. 이 요소를 **true** 로 설정하면 하이퍼링크가 업데이트되었음을 나타냅니다. **false** 로 설정하면 하이퍼링크가 오래되었음을 나타냅니다. 읽기/쓰기 boolean.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | boolean |  |

### getHyperlinksChanged() {#getHyperlinksChanged--}
```
public abstract boolean getHyperlinksChanged()
```


제작자가 이 파트에서 독점적으로 하나 이상의 하이퍼링크를 업데이트했음을 지정합니다. 다음 제작자가 문서를 열면 이 파트에 지정된 새 하이퍼링크로 관계가 업데이트됩니다. 읽기/쓰기 boolean.

**반환값:**
boolean
### setHyperlinksChanged(boolean value) {#setHyperlinksChanged-boolean-}
```
public abstract void setHyperlinksChanged(boolean value)
```


제작자가 이 파트에서 독점적으로 하나 이상의 하이퍼링크를 업데이트했음을 지정합니다. 다음 제작자가 문서를 열면 이 파트에 지정된 새 하이퍼링크로 관계가 업데이트됩니다. 읽기/쓰기 boolean.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | boolean |  |

### getSlides() {#getSlides--}
```
public abstract int getSlides()
```


프레젠테이션 문서의 전체 슬라이드 수를 지정합니다. 읽기 전용 int.

**반환값:**
int
### getHiddenSlides() {#getHiddenSlides--}
```
public abstract int getHiddenSlides()
```


프레젠테이션 문서의 숨겨진 슬라이드 수를 지정합니다. 읽기 전용 int.

**반환값:**
int
### getNotes() {#getNotes--}
```
public abstract int getNotes()
```


노트가 포함된 프레젠테이션 슬라이드 수를 지정합니다. 읽기 전용 int.

**반환값:**
int
### getParagraphs() {#getParagraphs--}
```
public abstract int getParagraphs()
```


해당되는 경우 문서에서 발견된 전체 단락 수를 지정합니다. 읽기 전용 int.

**반환값:**
int
### getWords() {#getWords--}
```
public abstract int getWords()
```


문서에 포함된 전체 단어 수를 지정합니다. 읽기 전용 int.

**반환값:**
int
### getMultimediaClips() {#getMultimediaClips--}
```
public abstract int getMultimediaClips()
```


문서에 포함된 사운드 또는 비디오 클립의 총 수를 지정합니다. 읽기 전용 int.

**반환값:**
int
### getTitlesOfParts() {#getTitlesOfParts--}
```
public abstract String[] getTitlesOfParts()
```


각 문서 파트의 제목을 지정합니다. 이러한 파트는 실제 문서 파트가 아니라 문서 섹션을 개념적으로 나타냅니다. 읽기 전용 String[].

**반환값:**
java.lang.String[]
### getHeadingPairs() {#getHeadingPairs--}
```
public abstract IHeadingPair[] getHeadingPairs()
```


문서 파트의 그룹화와 각 그룹의 파트 수를 나타냅니다. 읽기 전용 IHeadingPair[].

**반환값:**
com.aspose.slides.IHeadingPair[]
### getCountOfCustomProperties() {#getCountOfCustomProperties--}
```
public abstract int getCountOfCustomProperties()
```


컬렉션에 실제로 포함된 사용자 정의 속성 수를 반환합니다. 읽기 전용 int.

**반환값:**
int
### getCustomPropertyName(int index) {#getCustomPropertyName-int-}
```
public abstract String getCustomPropertyName(int index)
```


지정된 인덱스의 사용자 정의 속성 이름을 반환합니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| index | int | 가져올 사용자 정의 속성의 0 기반 인덱스입니다. |

**반환값:**
java.lang.String - 지정된 인덱스의 사용자 정의 속성 이름.
### removeCustomProperty(String name) {#removeCustomProperty-java.lang.String-}
```
public abstract boolean removeCustomProperty(String name)
```


지정된 이름과 연관된 사용자 정의 속성을 제거합니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| name | java.lang.String | 제거할 사용자 정의 속성의 이름입니다. |

**반환값:**
boolean - 속성이 제거되면 true, 그렇지 않으면 false.
### containsCustomProperty(String name) {#containsCustomProperty-java.lang.String-}
```
public abstract boolean containsCustomProperty(String name)
```


지정된 이름의 사용자 정의 속성 존재 여부를 확인합니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| name | java.lang.String | 확인할 사용자 정의 속성의 이름입니다. |

**반환값:**
boolean - 속성이 존재하면 true, 그렇지 않으면 false.
### get_Item(String name) {#get-Item-java.lang.String-}
```
public abstract Object get_Item(String name)
```


지정된 이름과 연관된 사용자 정의 속성을 반환하거나 설정합니다. 읽기/쓰기 Object.

--------------------

값은 **int**, **float**, **double**, **String**, **boolean** 또는 **Date**일 수 있습니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| name | java.lang.String |  |

**반환값:**
java.lang.Object
### set_Item(String name, Object value) {#set-Item-java.lang.String-java.lang.Object-}
```
public abstract void set_Item(String name, Object value)
```


지정된 이름과 연관된 사용자 정의 속성을 반환하거나 설정합니다. 읽기/쓰기 Object.

--------------------

값은 **int**, **float**, **double**, **String**, **boolean** 또는 **Date**일 수 있습니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| name | java.lang.String |  |
| value | java.lang.Object |  |

### clearCustomProperties() {#clearCustomProperties--}
```
public abstract void clearCustomProperties()
```


모든 사용자 정의 속성을 제거합니다.

### clearBuiltInProperties() {#clearBuiltInProperties--}
```
public abstract void clearBuiltInProperties()
```


모든 내장 속성을 지우고 기본값으로 설정합니다.

### getCustomPropertyValue(String name, boolean[] value) {#getCustomPropertyValue-java.lang.String-boolean---}
```
public abstract void getCustomPropertyValue(String name, boolean[] value)
```


사용자 정의 속성에서 지정된 이름의 boolean 값을 가져옵니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| name | java.lang.String | 가져올 사용자 정의 속성의 이름 |
| value | boolean[] | 사용자 정의 속성 값 |

### getCustomPropertyValue(String name, int[] value) {#getCustomPropertyValue-java.lang.String-int---}
```
public abstract void getCustomPropertyValue(String name, int[] value)
```


사용자 정의 속성에서 지정된 이름의 integer 값을 가져옵니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| name | java.lang.String | 가져올 사용자 정의 속성의 이름 |
| value | int[] | 사용자 정의 속성 값 |

### getCustomPropertyValue(String name, Date[] value) {#getCustomPropertyValue-java.lang.String-java.util.Date---}
```
public abstract void getCustomPropertyValue(String name, Date[] value)
```


사용자 정의 속성에서 지정된 이름의 DateTime 값을 가져옵니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| name | java.lang.String | 가져올 사용자 정의 속성의 이름 |
| value | java.util.Date[] | 사용자 정의 속성 값 |

### getCustomPropertyValue(String name, String[] value) {#getCustomPropertyValue-java.lang.String-java.lang.String---}
```
public abstract void getCustomPropertyValue(String name, String[] value)
```


사용자 정의 속성에서 지정된 이름의 string 값을 가져옵니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| name | java.lang.String | 가져올 사용자 정의 속성의 이름 |
| value | java.lang.String[] | 사용자 정의 속성 값 |

### getCustomPropertyValue(String name, float[] value) {#getCustomPropertyValue-java.lang.String-float---}
```
public abstract void getCustomPropertyValue(String name, float[] value)
```


사용자 정의 속성에서 지정된 이름의 float 값을 가져옵니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| name | java.lang.String | 가져올 사용자 정의 속성의 이름 |
| value | float[] | 사용자 정의 속성 값 |

### getCustomPropertyValue(String name, double[] value) {#getCustomPropertyValue-java.lang.String-double---}
```
public abstract void getCustomPropertyValue(String name, double[] value)
```


사용자 정의 속성에서 지정된 이름의 double 값을 가져옵니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| name | java.lang.String | 가져올 사용자 정의 속성의 이름. |
| value | double[] | 사용자 정의 속성 값 |

### setCustomPropertyValue(String name, boolean value) {#setCustomPropertyValue-java.lang.String-boolean-}
```
public abstract void setCustomPropertyValue(String name, boolean value)
```


지정된 이름의 boolean 사용자 정의 속성을 설정합니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| name | java.lang.String | 설정할 사용자 정의 속성의 이름 |
| value | boolean | 사용자 정의 속성 값 |

### setCustomPropertyValue(String name, int value) {#setCustomPropertyValue-java.lang.String-int-}
```
public abstract void setCustomPropertyValue(String name, int value)
```


지정된 이름의 integer 사용자 정의 속성을 설정합니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| name | java.lang.String | 설정할 사용자 정의 속성의 이름 |
| value | int | 사용자 정의 속성 값 |

### setCustomPropertyValue(String name, Date value) {#setCustomPropertyValue-java.lang.String-java.util.Date-}
```
public abstract void setCustomPropertyValue(String name, Date value)
```


지정된 이름의 DateTime 사용자 정의 속성을 설정합니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| name | java.lang.String | 설정할 사용자 정의 속성의 이름 |
| value | java.util.Date | 사용자 정의 속성 값 |

### setCustomPropertyValue(String name, String value) {#setCustomPropertyValue-java.lang.String-java.lang.String-}
```
public abstract void setCustomPropertyValue(String name, String value)
```


지정된 이름의 string 사용자 정의 속성을 설정합니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| name | java.lang.String | 설정할 사용자 정의 속성의 이름 |
| value | java.lang.String | 사용자 정의 속성 값 |

### setCustomPropertyValue(String name, float value) {#setCustomPropertyValue-java.lang.String-float-}
```
public abstract void setCustomPropertyValue(String name, float value)
```


지정된 이름의 float 사용자 정의 속성을 설정합니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| name | java.lang.String | 설정할 사용자 정의 속성의 이름 |
| value | float | 사용자 정의 속성 값 |

### setCustomPropertyValue(String name, double value) {#setCustomPropertyValue-java.lang.String-double-}
```
public abstract void setCustomPropertyValue(String name, double value)
```


지정된 이름의 double 사용자 정의 속성을 설정합니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| name | java.lang.String | 설정할 사용자 정의 속성의 이름 |
| value | double | 사용자 정의 속성 값 |

### getSensitivityLabels() {#getSensitivityLabels--}
```
public abstract ISensitivityLabel[] getSensitivityLabels()
```


사용자 정의 문서 속성(Microsoft Information Protection SDK Metadata)에서 민감도 레이블 배열을 가져옵니다.

--------------------

> ```
> The following code shows how to move the sensitivity labels information from the custom document properties 
>   to the modern SensitivityLabels collection:
>   
>  Presentation pres = new Presentation("SomePresentation.pptx");
>  try {
>      // Get sensitivity labels from the custom document properties
>      ISensitivityLabel[] mipSensitivityLabels = pres.getDocumentProperties().getSensitivityLabels();
>      ISensitivityLabelCollection sensitivityLabels = pres.getSensitivityLabels();
>      for (ISensitivityLabel sensitivityLabel : mipSensitivityLabels)
>      {
>          // Add label to the collection
>          // Here you can add a check for the validity of the label information (the label is available, etc)
>          sensitivityLabels.add(sensitivityLabel);
>      }
>      pres.save("SensitivityLabel.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**반환값:**
com.aspose.slides.ISensitivityLabel[]