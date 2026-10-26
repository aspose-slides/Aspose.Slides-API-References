---
title: ILoadOptions
second_title: Aspose.Slides for Java API Reference
description: 프레젠테이션을 로드할 때 형식이나 기본 글꼴과 같은 추가 옵션을 지정할 수 있습니다.
type: docs
url: /ko/com.aspose.slides/iloadoptions/
---```
public interface ILoadOptions
```

프레젠테이션을 로드할 때 추가 옵션(예: 형식 또는 기본 글꼴)을 지정할 수 있습니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getLoadFormat()](#getLoadFormat--) | 프레젠테이션을 로드할 형식을 반환하거나 설정합니다. |
| [setLoadFormat(int value)](#setLoadFormat-int-) | 프레젠테이션을 로드할 형식을 반환하거나 설정합니다. |
| [getDefaultRegularFont()](#getDefaultRegularFont--) | 소스 글꼴을 찾을 수 없는 경우 사용할 Regular 글꼴을 반환하거나 설정합니다. |
| [setDefaultRegularFont(String value)](#setDefaultRegularFont-java.lang.String-) | 소스 글꼴을 찾을 수 없는 경우 사용할 Regular 글꼴을 반환하거나 설정합니다. |
| [getDefaultSymbolFont()](#getDefaultSymbolFont--) | 소스 글꼴을 찾을 수 없는 경우 사용할 Symbol 글꼴을 반환하거나 설정합니다. |
| [setDefaultSymbolFont(String value)](#setDefaultSymbolFont-java.lang.String-) | 소스 글꼴을 찾을 수 없는 경우 사용할 Symbol 글꼴을 반환하거나 설정합니다. |
| [getDefaultAsianFont()](#getDefaultAsianFont--) | 소스 글꼴을 찾을 수 없는 경우 사용할 Asian 글꼴을 반환하거나 설정합니다. |
| [setDefaultAsianFont(String value)](#setDefaultAsianFont-java.lang.String-) | 소스 글꼴을 찾을 수 없는 경우 사용할 Asian 글꼴을 반환하거나 설정합니다. |
| [getPassword()](#getPassword--) | 비밀번호를 가져오거나 설정합니다. |
| [setPassword(String value)](#setPassword-java.lang.String-) | 비밀번호를 가져오거나 설정합니다. |
| [getOnlyLoadDocumentProperties()](#getOnlyLoadDocumentProperties--) | 프레젠테이션 파일이 비밀번호로 보호된 경우에 의미가 있는 속성입니다. |
| [setOnlyLoadDocumentProperties(boolean value)](#setOnlyLoadDocumentProperties-boolean-) | 프레젠테이션 파일이 비밀번호로 보호된 경우에 의미가 있는 속성입니다. |
| [getWarningCallback()](#getWarningCallback--) | 경고를 수신하고 로드 프로세스를 계속할지 중단할지를 결정하는 객체를 반환하거나 설정합니다. |
| [setWarningCallback(IWarningCallback value)](#setWarningCallback-com.aspose.slides.IWarningCallback-) | 경고를 수신하고 로드 프로세스를 계속할지 중단할지를 결정하는 객체를 반환하거나 설정합니다. |
| [getBlobManagementOptions()](#getBlobManagementOptions--) | Binary Large Objects (BLOB) 처리 동작을 관리하는 데 사용할 수 있는 옵션을 나타냅니다. |
| [setBlobManagementOptions(IBlobManagementOptions value)](#setBlobManagementOptions-com.aspose.slides.IBlobManagementOptions-) | Binary Large Objects (BLOB) 처리 동작을 관리하는 데 사용할 수 있는 옵션을 나타냅니다. |
| [getDocumentLevelFontSources()](#getDocumentLevelFontSources--) | 프레젠테이션에서 사용할 외부 글꼴의 소스를 지정합니다. |
| [setDocumentLevelFontSources(IFontSources value)](#setDocumentLevelFontSources-com.aspose.slides.IFontSources-) | 프레젠테이션에서 사용할 외부 글꼴의 소스를 지정합니다. |
| [getInterruptionToken()](#getInterruptionToken--) | 중단 요청을 모니터링하는 토큰입니다. |
| [setInterruptionToken(IInterruptionToken value)](#setInterruptionToken-com.aspose.slides.IInterruptionToken-) | 중단 요청을 모니터링하는 토큰입니다. |
| [getResourceLoadingCallback()](#getResourceLoadingCallback--) | 외부 리소스 로드를 관리하는 콜백 인터페이스를 반환하거나 설정합니다. |
| [setResourceLoadingCallback(IResourceLoadingCallback value)](#setResourceLoadingCallback-com.aspose.slides.IResourceLoadingCallback-) | 외부 리소스 로드를 관리하는 콜백 인터페이스를 반환하거나 설정합니다. |
| [getSpreadsheetOptions()](#getSpreadsheetOptions--) | 추가 스프레드시트 동작을 지정하는 데 사용할 수 있는 옵션을 나타냅니다. |
| [setSpreadsheetOptions(ISpreadsheetOptions value)](#setSpreadsheetOptions-com.aspose.slides.ISpreadsheetOptions-) | 추가 스프레드시트 동작을 지정하는 데 사용할 수 있는 옵션을 나타냅니다. |
| [getDefaultTextLanguage()](#getDefaultTextLanguage--) | 프레젠테이션 텍스트의 기본 언어를 반환하거나 설정합니다. |
| [setDefaultTextLanguage(String value)](#setDefaultTextLanguage-java.lang.String-) | 프레젠테이션 텍스트의 기본 언어를 반환하거나 설정합니다. |
| [getDeleteEmbeddedBinaryObjects()](#getDeleteEmbeddedBinaryObjects--) | Aspose.Slides가 프레젠테이션 로드 중에 모든 내장 바이너리 개체를 삭제할지 여부를 결정합니다. |
| [setDeleteEmbeddedBinaryObjects(boolean value)](#setDeleteEmbeddedBinaryObjects-boolean-) | Aspose.Slides가 프레젠테이션 로드 중에 모든 내장 바이너리 개체를 삭제할지 여부를 결정합니다. |
### getLoadFormat() {#getLoadFormat--}
```
public abstract int getLoadFormat()
```

프레젠테이션을 로드할 형식을 반환하거나 설정합니다. 읽기/쓰기 [LoadFormat](../../com.aspose.slides/loadformat).

**반환:**  
int
### setLoadFormat(int value) {#setLoadFormat-int-}
```
public abstract void setLoadFormat(int value)
```

프레젠테이션을 로드할 형식을 반환하거나 설정합니다. 읽기/쓰기 [LoadFormat](../../com.aspose.slides/loadformat).

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | int |  |
### getDefaultRegularFont() {#getDefaultRegularFont--}
```
public abstract String getDefaultRegularFont()
```

소스 글꼴을 찾을 수 없는 경우 사용할 Regular 글꼴을 반환하거나 설정합니다. 읽기/쓰기 String.

**반환:**  
java.lang.String
### setDefaultRegularFont(String value) {#setDefaultRegularFont-java.lang.String-}
```
public abstract void setDefaultRegularFont(String value)
```

소스 글꼴을 찾을 수 없는 경우 사용할 Regular 글꼴을 반환하거나 설정합니다. 읽기/쓰기 String.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | java.lang.String |  |
### getDefaultSymbolFont() {#getDefaultSymbolFont--}
```
public abstract String getDefaultSymbolFont()
```

소스 글꼴을 찾을 수 없는 경우 사용할 Symbol 글꼴을 반환하거나 설정합니다. 읽기/쓰기 String.

**반환:**  
java.lang.String
### setDefaultSymbolFont(String value) {#setDefaultSymbolFont-java.lang.String-}
```
public abstract void setDefaultSymbolFont(String value)
```

소스 글꼴을 찾을 수 없는 경우 사용할 Symbol 글꼴을 반환하거나 설정합니다. 읽기/쓰기 String.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | java.lang.String |  |
### getDefaultAsianFont() {#getDefaultAsianFont--}
```
public abstract String getDefaultAsianFont()
```

소스 글꼴을 찾을 수 없는 경우 사용할 Asian 글꼴을 반환하거나 설정합니다. 읽기/쓰기 String.

**반환:**  
java.lang.String
### setDefaultAsianFont(String value) {#setDefaultAsianFont-java.lang.String-}
```
public abstract void setDefaultAsianFont(String value)
```

소스 글꼴을 찾을 수 없는 경우 사용할 Asian 글꼴을 반환하거나 설정합니다. 읽기/쓰기 String.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | java.lang.String |  |
### getPassword() {#getPassword--}
```
public abstract String getPassword()
```

비밀번호를 가져오거나 설정합니다. 읽기/쓰기 String.

값: 비밀번호.

**반환:**  
java.lang.String
### setPassword(String value) {#setPassword-java.lang.String-}
```
public abstract void setPassword(String value)
```

비밀번호를 가져오거나 설정합니다. 읽기/쓰기 String.

값: 비밀번호.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | java.lang.String |  |
### getOnlyLoadDocumentProperties() {#getOnlyLoadDocumentProperties--}
```
public abstract boolean getOnlyLoadDocumentProperties()
```

이 속성은 프레젠테이션 파일이 비밀번호로 보호된 경우에 의미가 있습니다. true 값은 암호화된 프레젠테이션 파일에서 문서 속성만 로드하고 비밀번호는 무시해야 함을 의미합니다. false 값은 올바른 비밀번호를 사용하여 전체 암호화된 프레젠테이션을 로드해야 함을 의미합니다. 프레젠테이션이 암호화되지 않은 경우 이 속성 값은 항상 무시됩니다. 암호화된 파일의 문서 속성이 공개되지 않았고 속성 값이 true인 경우 문서 속성을 로드할 수 없으며 예외가 발생합니다. 읽기/쓰기 boolean.

**반환:**  
boolean
### setOnlyLoadDocumentProperties(boolean value) {#setOnlyLoadDocumentProperties-boolean-}
```
public abstract void setOnlyLoadDocumentProperties(boolean value)
```

이 속성은 프레젠테이션 파일이 비밀번호로 보호된 경우에 의미가 있습니다. true 값은 암호화된 프레젠테이션 파일에서 문서 속성만 로드하고 비밀번호는 무시해야 함을 의미합니다. false 값은 올바른 비밀번호를 사용하여 전체 암호화된 프레젠테이션을 로드해야 함을 의미합니다. 프레젠테이션이 암호화되지 않은 경우 이 속성 값은 항상 무시됩니다. 암호화된 파일의 문서 속성이 공개되지 않았고 속성 값이 true인 경우 문서 속성을 로드할 수 없으며 예외가 발생합니다. 읽기/쓰기 boolean.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | boolean |  |
### getWarningCallback() {#getWarningCallback--}
```
public abstract IWarningCallback getWarningCallback()
```

경고를 수신하고 로드 프로세스를 계속할지 중단할지를 결정하는 객체를 반환하거나 설정합니다. 읽기/쓰기 [IWarningCallback](../../com.aspose.slides/iwarningcallback).

**반환:**  
[IWarningCallback](../../com.aspose.slides/iwarningcallback)
### setWarningCallback(IWarningCallback value) {#setWarningCallback-com.aspose.slides.IWarningCallback-}
```
public abstract void setWarningCallback(IWarningCallback value)
```

경고를 수신하고 로드 프로세스를 계속할지 중단할지를 결정하는 객체를 반환하거나 설정합니다. 읽기/쓰기 [IWarningCallback](../../com.aspose.slides/iwarningcallback).

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | [IWarningCallback](../../com.aspose.slides/iwarningcallback) |  |
### getBlobManagementOptions() {#getBlobManagementOptions--}
```
public abstract IBlobManagementOptions getBlobManagementOptions()
```

Binary Large Objects (BLOB) 처리 동작을 관리하는 데 사용할 수 있는 옵션을 나타냅니다. 예를 들어 임시 파일 사용이나 메모리 내 최대 BLOB 바이트 수와 같은 옵션입니다. 이러한 옵션은 특정 환경이나 요구 사항에 맞는 최적의 성능/메모리 사용 비율을 설정하기 위한 것입니다.

--------------------

Binary Large Object (BLOB)는 단일 엔터티로 저장된 바이너리 데이터이며, 즉 BLOB는 오디오, 비디오 또는 프레젠테이션 자체가 될 수 있습니다.

**반환:**  
[IBlobManagementOptions](../../com.aspose.slides/iblobmanagementoptions)
### setBlobManagementOptions(IBlobManagementOptions value) {#setBlobManagementOptions-com.aspose.slides.IBlobManagementOptions-}
```
public abstract void setBlobManagementOptions(IBlobManagementOptions value)
```

Binary Large Objects (BLOB) 처리 동작을 관리하는 데 사용할 수 있는 옵션을 나타냅니다. 예를 들어 임시 파일 사용이나 메모리 내 최대 BLOB 바이트 수와 같은 옵션입니다. 이러한 옵션은 특정 환경이나 요구 사항에 맞는 최적의 성능/메모리 사용 비율을 설정하기 위한 것입니다.

--------------------

Binary Large Object (BLOB)는 단일 엔터티로 저장된 바이너리 데이터이며, 즉 BLOB는 오디오, 비디오 또는 프레젠테이션 자체가 될 수 있습니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | [IBlobManagementOptions](../../com.aspose.slides/iblobmanagementoptions) |  |
### getDocumentLevelFontSources() {#getDocumentLevelFontSources--}
```
public abstract IFontSources getDocumentLevelFontSources()
```

프레젠테이션에서 사용할 외부 글꼴의 소스를 지정합니다. 이러한 글꼴은 프레젠테이션 전체 수명 동안 사용 가능하며 다른 프레젠테이션과 공유되지 않습니다.

**반환:**  
[IFontSources](../../com.aspose.slides/ifontsources)
### setDocumentLevelFontSources(IFontSources value) {#setDocumentLevelFontSources-com.aspose.slides.IFontSources-}
```
public abstract void setDocumentLevelFontSources(IFontSources value)
```

프레젠테이션에서 사용할 외부 글꼴의 소스를 지정합니다. 이러한 글꼴은 프레젠테이션 전체 수명 동안 사용 가능하며 다른 프레젠테이션과 공유되지 않습니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | [IFontSources](../../com.aspose.slides/ifontsources) |  |
### getInterruptionToken() {#getInterruptionToken--}
```
public abstract IInterruptionToken getInterruptionToken()
```

중단 요청을 모니터링하는 토큰입니다.

--------------------

이 토큰은 전체 [IPresentation](../../com.aspose.slides/ipresentation) 인스턴스 수명을 관리합니다. 프레젠테이션 로드 또는 저장과 같은 장시간 실행 작업은 [IInterruptionTokenSource](../../com.aspose.slides/iinterruptiontokensource)의 [IInterruptionTokenSource.interrupt](../../com.aspose.slides/iinterruptiontokensource\#interrupt) 메서드를 호출하여 중단됩니다.

**반환:**  
[IInterruptionToken](../../com.aspose.slides/iinterruptiontoken)
### setInterruptionToken(IInterruptionToken value) {#setInterruptionToken-com.aspose.slides.IInterruptionToken-}
```
public abstract void setInterruptionToken(IInterruptionToken value)
```

중단 요청을 모니터링하는 토큰입니다.

--------------------

이 토큰은 전체 [IPresentation](../../com.aspose.slides/ipresentation) 인스턴스 수명을 관리합니다. 프레젠테이션 로드 또는 저장과 같은 장시간 실행 작업은 [IInterruptionTokenSource](../../com.aspose.slides/iinterruptiontokensource)의 [IInterruptionTokenSource.interrupt](../../com.aspose.slides/iinterruptiontokensource\#interrupt) 메서드를 호출하여 중단됩니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | [IInterruptionToken](../../com.aspose.slides/iinterruptiontoken) |  |
### getResourceLoadingCallback() {#getResourceLoadingCallback--}
```
public abstract IResourceLoadingCallback getResourceLoadingCallback()
```

외부 리소스 로드를 관리하는 콜백 인터페이스를 반환하거나 설정합니다. 읽기/쓰기 [IResourceLoadingCallback](../../com.aspose.slides/iresourceloadingcallback).

**반환:**  
[IResourceLoadingCallback](../../com.aspose.slides/iresourceloadingcallback)
### setResourceLoadingCallback(IResourceLoadingCallback value) {#setResourceLoadingCallback-com.aspose.slides.IResourceLoadingCallback-}
```
public abstract void setResourceLoadingCallback(IResourceLoadingCallback value)
```

외부 리소스 로드를 관리하는 콜백 인터페이스를 반환하거나 설정합니다. 읽기/쓰기 [IResourceLoadingCallback](../../com.aspose.slides/iresourceloadingcallback).

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | [IResourceLoadingCallback](../../com.aspose.slides/iresourceloadingcallback) |  |
### getSpreadsheetOptions() {#getSpreadsheetOptions--}
```
public abstract ISpreadsheetOptions getSpreadsheetOptions()
```

추가 스프레드시트 동작을 지정하는 데 사용할 수 있는 옵션을 나타냅니다.

**반환:**  
[ISpreadsheetOptions](../../com.aspose.slides/ispreadsheetoptions)
### setSpreadsheetOptions(ISpreadsheetOptions value) {#setSpreadsheetOptions-com.aspose.slides.ISpreadsheetOptions-}
```
public abstract void setSpreadsheetOptions(ISpreadsheetOptions value)
```

추가 스프레드시트 동작을 지정하는 데 사용할 수 있는 옵션을 나타냅니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | [ISpreadsheetOptions](../../com.aspose.slides/ispreadsheetoptions) |  |
### getDefaultTextLanguage() {#getDefaultTextLanguage--}
```
public abstract String getDefaultTextLanguage()
```

프레젠테이션 텍스트의 기본 언어를 반환하거나 설정합니다. 읽기/쓰기 String.

--------------------

> ```
> Example:
>   
>  // 로드 옵션을 사용하여 기본 텍스트 문화 정의
>  LoadOptions loadOptions = new LoadOptions();
>  loadOptions.setDefaultTextLanguage("en-US");
>  Presentation pres = new Presentation(loadOptions);
>  try {
>      // 텍스트가 있는 새로운 사각형 도형 추가
>      IAutoShape shp = pres.getSlides().get_Item(0).getShapes().addAutoShape(ShapeType.Rectangle, 50, 50, 150, 50);
>      shp.getTextFrame().setText("New Text");
>      // 첫 번째 구절 언어 확인
>      System.out.println(shp.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0).getPortionFormat().getLanguageId());
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**반환:**  
java.lang.String
### setDefaultTextLanguage(String value) {#setDefaultTextLanguage-java.lang.String-}
```
public abstract void setDefaultTextLanguage(String value)
```

프레젠테이션 텍스트의 기본 언어를 반환하거나 설정합니다. 읽기/쓰기 String.

--------------------

> ```
> Example:
>   
>  // 로드 옵션을 사용하여 기본 텍스트 문화 정의
>  LoadOptions loadOptions = new LoadOptions();
>  loadOptions.setDefaultTextLanguage("en-US");
>  Presentation pres = new Presentation(loadOptions);
>  try {
>      // 텍스트가 있는 새로운 사각형 도형 추가
>      IAutoShape shp = pres.getSlides().get_Item(0).getShapes().addAutoShape(ShapeType.Rectangle, 50, 50, 150, 50);
>      shp.getTextFrame().setText("New Text");
>      // 첫 번째 구절 언어 확인
>      System.out.println(shp.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0).getPortionFormat().getLanguageId());
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | java.lang.String |  |
### getDeleteEmbeddedBinaryObjects() {#getDeleteEmbeddedBinaryObjects--}
```
public abstract boolean getDeleteEmbeddedBinaryObjects()
```

프레젠테이션 로드 중에 Aspose.Slides가 모든 내장 바이너리 개체를 삭제할지 여부를 결정합니다.

내장 바이너리 개체의 유형:
 *  
 *  
 *  

읽기/쓰기 boolean .

--------------------

> ```
> The following example shows how to load the presentation without any embedded binary objects.
>  
>  LoadOptions loadOptions = new LoadOptions();
>  loadOptions.setDeleteEmbeddedBinaryObjects(true);
>  Presentation pres = new Presentation("pres.ppt", loadOptions);
>  try {
>      pres.save("output_WithoutBinaryObjects.ppt", SaveFormat.Ppt);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

--------------------

기본값은 **false** 입니다.

**반환:**  
boolean
### setDeleteEmbeddedBinaryObjects(boolean value) {#setDeleteEmbeddedBinaryObjects-boolean-}
```
public abstract void setDeleteEmbeddedBinaryObjects(boolean value)
```

프레젠테이션 로드 중에 Aspose.Slides가 모든 내장 바이너리 개체를 삭제할지 여부를 결정합니다.

내장 바이너리 개체의 유형:
 *  
 *  
 *  

읽기/쓰기 boolean .

--------------------

> ```
> The following example shows how to load the presentation without any embedded binary objects.
>  
>  LoadOptions loadOptions = new LoadOptions();
>  loadOptions.setDeleteEmbeddedBinaryObjects(true);
>  Presentation pres = new Presentation("pres.ppt", loadOptions);
>  try {
>      pres.save("output_WithoutBinaryObjects.ppt", SaveFormat.Ppt);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

--------------------

기본값은 **false** 입니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | boolean |  |