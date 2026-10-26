---
title: LoadOptions
second_title: Java API 레퍼런스를 통한 Android용 Aspose.Slides
description: 프레젠테이션을 로드할 때 포맷이나 기본 글꼴과 같은 추가 옵션을 지정할 수 있습니다.
type: docs
url: /ko/com.aspose.slides/loadoptions/
---
**Inheritance:**  
java.lang.Object

**All Implemented Interfaces:**  
[com.aspose.slides.ILoadOptions](../../com.aspose.slides/iloadoptions)  
```
public class LoadOptions implements ILoadOptions
```

프레젠테이션을 로드할 때 추가 옵션(예: 포맷 또는 기본 글꼴)을 지정할 수 있습니다.

## 생성자

| 생성자 | 설명 |
| --- | --- |
| [LoadOptions()](#LoadOptions--) | 새 기본 로드 옵션을 생성합니다. |
| [LoadOptions(int loadFormat)](#LoadOptions-int-) | 새 로드 옵션을 생성합니다. |

## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getLoadFormat()](#getLoadFormat--) | 로드할 프레젠테이션의 포맷을 가져오거나 설정합니다. |
| [setLoadFormat(int value)](#setLoadFormat-int-) | 로드할 프레젠테이션의 포맷을 가져오거나 설정합니다. |
| [getDefaultRegularFont()](#getDefaultRegularFont--) | 원본 글꼴을 찾을 수 없을 경우 사용할 기본 글꼴을 가져오거나 설정합니다. |
| [setDefaultRegularFont(String value)](#setDefaultRegularFont-java.lang.String-) | 원본 글꼴을 찾을 수 없을 경우 사용할 기본 글꼴을 가져오거나 설정합니다. |
| [getDefaultSymbolFont()](#getDefaultSymbolFont--) | 원본 글꼴을 찾을 수 없을 경우 사용할 Symbol 글꼴을 가져오거나 설정합니다. |
| [setDefaultSymbolFont(String value)](#setDefaultSymbolFont-java.lang.String-) | 원본 글꼴을 찾을 수 없을 경우 사용할 Symbol 글꼴을 가져오거나 설정합니다. |
| [getDefaultAsianFont()](#getDefaultAsianFont--) | 원본 글꼴을 찾을 수 없을 경우 사용할 Asian 글꼴을 가져오거나 설정합니다. |
| [setDefaultAsianFont(String value)](#setDefaultAsianFont-java.lang.String-) | 원본 글꼴을 찾을 수 없을 경우 사용할 Asian 글꼴을 가져오거나 설정합니다. |
| [getPassword()](#getPassword--) | 비밀번호를 가져오거나 설정합니다. |
| [setPassword(String value)](#setPassword-java.lang.String-) | 비밀번호를 가져오거나 설정합니다. |
| [getOnlyLoadDocumentProperties()](#getOnlyLoadDocumentProperties--) | 이 속성은 프레젠테이션 파일이 비밀번호로 보호된 경우에 의미가 있습니다. |
| [setOnlyLoadDocumentProperties(boolean value)](#setOnlyLoadDocumentProperties-boolean-) | 이 속성은 프레젠테이션 파일이 비밀번호로 보호된 경우에 의미가 있습니다. |
| [getWarningCallback()](#getWarningCallback--) | 경고를 수신하고 로드 프로세스를 계속할지 중단할지를 결정하는 객체를 가져오거나 설정합니다. |
| [setWarningCallback(IWarningCallback value)](#setWarningCallback-com.aspose.slides.IWarningCallback-) | 경고를 수신하고 로드 프로세스를 계속할지 중단할지를 결정하는 객체를 가져오거나 설정합니다. |
| [getBlobManagementOptions()](#getBlobManagementOptions--) | 임시 파일 사용 또는 메모리 내 최대 BLOB 바이트 수와 같이 Binary Large Objects(BLOB) 처리 동작을 관리하는 옵션을 나타냅니다. |
| [setBlobManagementOptions(IBlobManagementOptions value)](#setBlobManagementOptions-com.aspose.slides.IBlobManagementOptions-) | 임시 파일 사용 또는 메모리 내 최대 BLOB 바이트 수와 같이 Binary Large Objects(BLOB) 처리 동작을 관리하는 옵션을 나타냅니다. |
| [getDocumentLevelFontSources()](#getDocumentLevelFontSources--) | 프레젠테이션에서 사용할 외부 글꼴의 소스를 지정합니다. |
| [setDocumentLevelFontSources(IFontSources value)](#setDocumentLevelFontSources-com.aspose.slides.IFontSources-) | 프레젠테이션에서 사용할 외부 글꼴의 소스를 지정합니다. |
| [getInterruptionToken()](#getInterruptionToken--) | 중단 요청을 모니터링하는 토큰입니다. |
| [setInterruptionToken(IInterruptionToken value)](#setInterruptionToken-com.aspose.slides.IInterruptionToken-) | 중단 요청을 모니터링하는 토큰입니다. |
| [getResourceLoadingCallback()](#getResourceLoadingCallback--) | 외부 리소스 로드를 관리하는 콜백 인터페이스를 가져오거나 설정합니다. |
| [setResourceLoadingCallback(IResourceLoadingCallback value)](#setResourceLoadingCallback-com.aspose.slides.IResourceLoadingCallback-) | 외부 리소스 로드를 관리하는 콜백 인터페이스를 가져오거나 설정합니다. |
| [getSpreadsheetOptions()](#getSpreadsheetOptions--) | 스프레드시트 옵션을 가져옵니다. |
| [setSpreadsheetOptions(ISpreadsheetOptions value)](#setSpreadsheetOptions-com.aspose.slides.ISpreadsheetOptions-) | 스프레드시트 옵션을 가져옵니다. |
| [getDefaultTextLanguage()](#getDefaultTextLanguage--) | 프레젠테이션 텍스트의 기본 언어를 가져오거나 설정합니다. |
| [setDefaultTextLanguage(String value)](#setDefaultTextLanguage-java.lang.String-) | 프레젠테이션 텍스트의 기본 언어를 가져오거나 설정합니다. |
| [getDeleteEmbeddedBinaryObjects()](#getDeleteEmbeddedBinaryObjects--) | 프레젠테이션 로드 중에 Aspose.Slides가 모든 임베디드 바이너리 객체를 삭제할지 여부를 결정합니다. |
| [setDeleteEmbeddedBinaryObjects(boolean value)](#setDeleteEmbeddedBinaryObjects-boolean-) | 프레젠테이션 로드 중에 Aspose.Slides가 모든 임베디드 바이너리 객체를 삭제할지 여부를 결정합니다. |

### LoadOptions() {#LoadOptions--}
```
public LoadOptions()
```

새 기본 로드 옵션을 생성합니다.

### LoadOptions(int loadFormat) {#LoadOptions-int-}
```
public LoadOptions(int loadFormat)
```

새 로드 옵션을 생성합니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| loadFormat | int | 로드할 프레젠테이션의 포맷입니다. |

### getLoadFormat() {#getLoadFormat--}
```
public final int getLoadFormat()
```

로드할 프레젠테이션의 포맷을 가져오거나 설정합니다. 읽기/쓰기 [LoadFormat](../../com.aspose.slides/loadformat).

**반환값:**  
int

### setLoadFormat(int value) {#setLoadFormat-int-}
```
public final void setLoadFormat(int value)
```

로드할 프레젠테이션의 포맷을 가져오거나 설정합니다. 읽기/쓰기 [LoadFormat](../../com.aspose.slides/loadformat).

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | int |  |

### getDefaultRegularFont() {#getDefaultRegularFont--}
```
public final String getDefaultRegularFont()
```

원본 글꼴을 찾을 수 없을 경우 사용할 기본 Regular 글꼴을 가져오거나 설정합니다. 읽기/쓰기 String.

--------------------

> ```
> The following example shows how to set default fonts for rendering PowerPoint Presentation.
>  
>  // 기본 regular 및 asian 글꼴을 정의하기 위해 로드 옵션 사용
>  LoadOptions loadOptions = new LoadOptions(LoadFormat.Auto);
>  loadOptions.setDefaultRegularFont("Wingdings");
>  loadOptions.setDefaultAsianFont("Wingdings");
>  // 프레젠테이션 로드
>  Presentation pres = new Presentation("DefaultFonts.pptx", loadOptions);
>  try {
>      // 슬라이드 썸네일 생성
>      android.graphics.Bitmap slideImage = pres.getSlides().get_Item(0).getThumbnail(1, 1);
>      FileOutputStream fos = null;
>      try {
>          fos = new FileOutputStream("output_out.png");
>          slideImage.compress(android.graphics.Bitmap.CompressFormat.PNG, 100, fos);
>      } catch (IOException e) {
>          throw new RuntimeException(e);
>      } finally {
>          if (fos != null) {
>              try {
>                  fos.close();
>              } catch (IOException e) {
>                  e.printStackTrace();
>              }
>          }
>      }
>      // PDF 생성
>      pres.save("output_out.pdf", SaveFormat.Pdf);
>      // XPS 생성
>      pres.save("output_out.xps", SaveFormat.Xps);
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**반환값:**  
java.lang.String

### setDefaultRegularFont(String value) {#setDefaultRegularFont-java.lang.String-}
```
public final void setDefaultRegularFont(String value)
```

원본 글꼴을 찾을 수 없을 경우 사용할 기본 Regular 글꼴을 가져오거나 설정합니다. 읽기/쓰기 String.

--------------------

> ```
> The following example shows how to set default fonts for rendering PowerPoint Presentation.
>  
>  // 기본 regular 및 asian 글꼴을 정의하기 위해 로드 옵션 사용
>  LoadOptions loadOptions = new LoadOptions(LoadFormat.Auto);
>  loadOptions.setDefaultRegularFont("Wingdings");
>  loadOptions.setDefaultAsianFont("Wingdings");
>  // 프레젠테이션 로드
>  Presentation pres = new Presentation("DefaultFonts.pptx", loadOptions);
>  try {
>      // 슬라이드 썸네일 생성
>      android.graphics.Bitmap slideImage = pres.getSlides().get_Item(0).getThumbnail(1, 1);
>      FileOutputStream fos = null;
>      try {
>          fos = new FileOutputStream("output_out.png");
>          slideImage.compress(android.graphics.Bitmap.CompressFormat.PNG, 100, fos);
>      } catch (IOException e) {
>          throw new RuntimeException(e);
>      } finally {
>          if (fos != null) {
>              try {
>                  fos.close();
>              } catch (IOException e) {
>                  e.printStackTrace();
>              }
>          }
>      }
>      // PDF 생성
>      pres.save("output_out.pdf", SaveFormat.Pdf);
>      // XPS 생성
>      pres.save("output_out.xps", SaveFormat.Xps);
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | java.lang.String |  |

### getDefaultSymbolFont() {#getDefaultSymbolFont--}
```
public final String getDefaultSymbolFont()
```

원본 글꼴을 찾을 수 없을 경우 사용할 Symbol 글꼴을 가져오거나 설정합니다. 읽기/쓰기 String.

**반환값:**  
java.lang.String

### setDefaultSymbolFont(String value) {#setDefaultSymbolFont-java.lang.String-}
```
public final void setDefaultSymbolFont(String value)
```

원본 글꼴을 찾을 수 없을 경우 사용할 Symbol 글꼴을 가져오거나 설정합니다. 읽기/쓰기 String.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | java.lang.String |  |

### getDefaultAsianFont() {#getDefaultAsianFont--}
```
public final String getDefaultAsianFont()
```

원본 글꼴을 찾을 수 없을 경우 사용할 Asian 글꼴을 가져오거나 설정합니다. 읽기/쓰기 String.

**반환값:**  
java.lang.String

### setDefaultAsianFont(String value) {#setDefaultAsianFont-java.lang.String-}
```
public final void setDefaultAsianFont(String value)
```

원본 글꼴을 찾을 수 없을 경우 사용할 Asian 글꼴을 가져오거나 설정합니다. 읽기/쓰기 String.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | java.lang.String |  |

### getPassword() {#getPassword--}
```
public final String getPassword()
```

비밀번호를 가져오거나 설정합니다. 읽기/쓰기 String.

--------------------

> ```
> The following sample code shows how to open password protected PowerPoint Presentation.
>  
>  LoadOptions loadOptions = new LoadOptions();
>  loadOptions.setPassword("YOUR_PASSWORD");
>  Presentation pres = new Presentation("pres.pptx", loadOptions);
>  try {
>  // 복호화된 프레젠테이션으로 작업
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


값: 비밀번호.

**반환값:**  
java.lang.String

### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```

비밀번호를 가져오거나 설정합니다. 읽기/쓰기 String.

--------------------

> ```
> The following sample code shows how to open password protected PowerPoint Presentation.
>  
>  LoadOptions loadOptions = new LoadOptions();
>  loadOptions.setPassword("YOUR_PASSWORD");
>  Presentation pres = new Presentation("pres.pptx", loadOptions);
>  try {
>  // 복호화된 프레젠테이션으로 작업
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


값: 비밀번호.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | java.lang.String |  |

### getOnlyLoadDocumentProperties() {#getOnlyLoadDocumentProperties--}
```
public final boolean getOnlyLoadDocumentProperties()
```

이 속성은 프레젠테이션 파일이 비밀번호로 보호된 경우에 의미가 있습니다. true 값은 암호화된 프레젠테이션 파일에서 문서 속성만 로드하고 비밀번호는 무시함을 의미합니다. false 값은 올바른 비밀번호를 사용하여 전체 암호화된 프레젠테이션을 로드함을 의미합니다. 프레젠테이션이 암호화되지 않은 경우 이 속성 값은 항상 무시됩니다. 암호화된 파일의 문서 속성이 공개되지 않았고 속성 값이 true인 경우 문서 속성을 로드할 수 없으며 예외가 발생합니다. 읽기/쓰기 boolean.

**반환값:**  
boolean

### setOnlyLoadDocumentProperties(boolean value) {#setOnlyLoadDocumentProperties-boolean-}
```
public final void setOnlyLoadDocumentProperties(boolean value)
```

이 속성은 프레젠테이션 파일이 비밀번호로 보호된 경우에 의미가 있습니다. true 값은 암호화된 프레젠테이션 파일에서 문서 속성만 로드하고 비밀번호는 무시함을 의미합니다. false 값은 올바른 비밀번호를 사용하여 전체 암호화된 프레젠테이션을 로드함을 의미합니다. 프레젠테이션이 암호화되지 않은 경우 이 속성 값은 항상 무시됩니다. 암호화된 파일의 문서 속성이 공개되지 않았고 속성 값이 true인 경우 문서 속성을 로드할 수 없으며 예외가 발생합니다. 읽기/쓰기 boolean.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | boolean |  |

### getWarningCallback() {#getWarningCallback--}
```
public final IWarningCallback getWarningCallback()
```

경고를 수신하고 로드 프로세스를 계속할지 중단할지를 결정하는 객체를 가져오거나 설정합니다. 읽기/쓰기 [IWarningCallback](../../com.aspose.slides/iwarningcallback).

**반환값:**  
[IWarningCallback](../../com.aspose.slides/iwarningcallback)

### setWarningCallback(IWarningCallback value) {#setWarningCallback-com.aspose.slides.IWarningCallback-}
```
public final void setWarningCallback(IWarningCallback value)
```

경고를 수신하고 로드 프로세스를 계속할지 중단할지를 결정하는 객체를 가져오거나 설정합니다. 읽기/쓰기 [IWarningCallback](../../com.aspose.slides/iwarningcallback).

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | [IWarningCallback](../../com.aspose.slides/iwarningcallback) |  |

### getBlobManagementOptions() {#getBlobManagementOptions--}
```
public final IBlobManagementOptions getBlobManagementOptions()
```

Binary Large Objects(BLOB) 처리 동작을 관리하는 옵션을 나타냅니다. 예를 들어 임시 파일 사용 또는 메모리 내 최대 BLOB 바이트 수와 같이 BLOB 처리를 제어할 수 있습니다. 이러한 옵션은 특정 환경이나 요구 사항에 맞게 최고의 성능/메모리 사용 비율을 설정하기 위한 것입니다.

--------------------

Binary Large Object(BLOB)는 단일 엔터티로 저장된 바이너리 데이터이며, 예를 들어 오디오, 비디오 또는 프레젠테이션 자체가 될 수 있습니다.

**반환값:**  
[IBlobManagementOptions](../../com.aspose.slides/iblobmanagementoptions)

### setBlobManagementOptions(IBlobManagementOptions value) {#setBlobManagementOptions-com.aspose.slides.IBlobManagementOptions-}
```
public final void setBlobManagementOptions(IBlobManagementOptions value)
```

Binary Large Objects(BLOB) 처리 동작을 관리하는 옵션을 나타냅니다. 예를 들어 임시 파일 사용 또는 메모리 내 최대 BLOB 바이트 수와 같이 BLOB 처리를 제어할 수 있습니다. 이러한 옵션은 특정 환경이나 요구 사항에 맞게 최고의 성능/메모리 사용 비율을 설정하기 위한 것입니다.

--------------------

Binary Large Object(BLOB)는 단일 엔터티로 저장된 바이너리 데이터이며, 예를 들어 오디오, 비디오 또는 프레젠테이션 자체가 될 수 있습니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | [IBlobManagementOptions](../../com.aspose.slides/iblobmanagementoptions) |  |

### getDocumentLevelFontSources() {#getDocumentLevelFontSources--}
```
public final IFontSources getDocumentLevelFontSources()
```

프레젠테이션에서 사용할 외부 글꼴의 소스를 지정합니다. 이 글꼴은 프레젠테이션 전체 수명 동안 사용 가능하며 다른 프레젠테이션과 공유되지 않습니다.

--------------------

> ```
> The following example shows how to specify custom fonts used with PowerPoint Presentation.
>  
>  File file = new File("customfonts/CustomFont1.ttf");
>  byte memoryFont1[] = new byte[(int) file.length()];
>  BufferedInputStream bis = new BufferedInputStream(new FileInputStream(file));
>  DataInputStream dis = new DataInputStream(bis);
>  dis.readFully(memoryFont1);
>  file = new File("customfonts/CustomFont2.ttf");
>  byte memoryFont2[] = new byte[(int) file.length()];
>  bis = new BufferedInputStream(new FileInputStream(file));
>  dis = new DataInputStream(bis);
>  dis.readFully(memoryFont2);
>  LoadOptions loadOptions = new LoadOptions();
>  loadOptions.getDocumentLevelFontSources().setFontFolders(new String[] { "assets\\fonts", "global\\fonts" });
>  loadOptions.getDocumentLevelFontSources().setMemoryFonts(new byte[][] { memoryFont1, memoryFont2 });
>  IPresentation presentation = new Presentation("MyPresentation.pptx", loadOptions);
>  try {
>  // 프레젠테이션 작업
>  // CustomFont1, CustomFont2 및 assets\fonts와 global\fonts 폴더 및 그 하위 폴더의 글꼴이 프레젠테이션에서 사용 가능합니다.
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**반환값:**  
[IFontSources](../../com.aspose.slides/ifontsources)

### setDocumentLevelFontSources(IFontSources value) {#setDocumentLevelFontSources-com.aspose.slides.IFontSources-}
```
public final void setDocumentLevelFontSources(IFontSources value)
```

프레젠테이션에서 사용할 외부 글꼴의 소스를 지정합니다. 이 글꼴은 프레젠테이션 전체 수명 동안 사용 가능하며 다른 프레젠테이션과 공유되지 않습니다.

--------------------

> ```
> The following example shows how to specify custom fonts used with PowerPoint Presentation.
>  
>  File file = new File("customfonts/CustomFont1.ttf");
>  byte memoryFont1[] = new byte[(int) file.length()];
>  BufferedInputStream bis = new BufferedInputStream(new FileInputStream(file));
>  DataInputStream dis = new DataInputStream(bis);
>  dis.readFully(memoryFont1);
>  file = new File("customfonts/CustomFont2.ttf");
>  byte memoryFont2[] = new byte[(int) file.length()];
>  bis = new BufferedInputStream(new FileInputStream(file));
>  dis = new DataInputStream(bis);
>  dis.readFully(memoryFont2);
>  LoadOptions loadOptions = new LoadOptions();
>  loadOptions.getDocumentLevelFontSources().setFontFolders(new String[] { "assets\\fonts", "global\\fonts" });
>  loadOptions.getDocumentLevelFontSources().setMemoryFonts(new byte[][] { memoryFont1, memoryFont2 });
>  IPresentation presentation = new Presentation("MyPresentation.pptx", loadOptions);
>  try {
>  //프레젠테이션 작업
>  //CustomFont1, CustomFont2 및 assets\fonts와 global\fonts 폴더 및 하위 폴더의 글꼴이 프레젠테이션에서 사용 가능합니다.
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | [IFontSources](../../com.aspose.slides/ifontsources) |  |

### getInterruptionToken() {#getInterruptionToken--}
```
public final IInterruptionToken getInterruptionToken()
```

중단 요청을 모니터링하는 토큰입니다.

--------------------

이 토큰은 전체 [IPresentation](../../com.aspose.slides/ipresentation) 인스턴스 수명을 관리합니다. 로드 또는 저장과 같은 장기 실행 작업은 [InterruptionTokenSource.interrupt](../../com.aspose.slides/interruptiontokensource\#interrupt) 메서드를 호출하여 [InterruptionTokenSource](../../com.aspose.slides/interruptiontokensource)를 통해 중단됩니다.

**반환값:**  
[IInterruptionToken](../../com.aspose.slides/iinterruptiontoken)

### setInterruptionToken(IInterruptionToken value) {#setInterruptionToken-com.aspose.slides.IInterruptionToken-}
```
public final void setInterruptionToken(IInterruptionToken value)
```

중단 요청을 모니터링하는 토큰입니다.

--------------------

이 토큰은 전체 [IPresentation](../../com.aspose.slides/ipresentation) 인스턴스 수명을 관리합니다. 로드 또는 저장과 같은 장기 실행 작업은 [InterruptionTokenSource.interrupt](../../com.aspose.slides/interruptiontokensource\#interrupt) 메서드를 호출하여 [InterruptionTokenSource](../../com.aspose.slides/interruptiontokensource)를 통해 중단됩니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | [IInterruptionToken](../../com.aspose.slides/iinterruptiontoken) |  |

### getResourceLoadingCallback() {#getResourceLoadingCallback--}
```
public final IResourceLoadingCallback getResourceLoadingCallback()
```

외부 리소스 로드를 관리하는 콜백 인터페이스를 가져오거나 설정합니다. 읽기/쓰기 [IResourceLoadingCallback](../../com.aspose.slides/iresourceloadingcallback).

**반환값:**  
[IResourceLoadingCallback](../../com.aspose.slides/iresourceloadingcallback)

### setResourceLoadingCallback(IResourceLoadingCallback value) {#setResourceLoadingCallback-com.aspose.slides.IResourceLoadingCallback-}
```
public final void setResourceLoadingCallback(IResourceLoadingCallback value)
```

외부 리소스 로드를 관리하는 콜백 인터페이스를 가져오거나 설정합니다. 읽기/쓰기 [IResourceLoadingCallback](../../com.aspose.slides/iresourceloadingcallback).

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | [IResourceLoadingCallback](../../com.aspose.slides/iresourceloadingcallback) |  |

### getSpreadsheetOptions() {#getSpreadsheetOptions--}
```
public final ISpreadsheetOptions getSpreadsheetOptions()
```

스프레드시트 옵션을 가져옵니다. 예를 들어 차트에 대한 수식 계산에 영향을 줄 수 있습니다.

**반환값:**  
[ISpreadsheetOptions](../../com.aspose.slides/ispreadsheetoptions)

### setSpreadsheetOptions(ISpreadsheetOptions value) {#setSpreadsheetOptions-com.aspose.slides.ISpreadsheetOptions-}
```
public final void setSpreadsheetOptions(ISpreadsheetOptions value)
```

스프레드시트 옵션을 가져옵니다. 예를 들어 차트에 대한 수식 계산에 영향을 줄 수 있습니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | [ISpreadsheetOptions](../../com.aspose.slides/ispreadsheetoptions) |  |

### getDefaultTextLanguage() {#getDefaultTextLanguage--}
```
public final String getDefaultTextLanguage()
```

프레젠테이션 텍스트의 기본 언어를 가져오거나 설정합니다. 읽기/쓰기 String.

--------------------

> ```
> Example:
>   
>  // 로드 옵션을 사용해 기본 텍스트 문화 지정
>  LoadOptions loadOptions = new LoadOptions();
>  loadOptions.setDefaultTextLanguage("en-US");
>  Presentation pres = new Presentation(loadOptions);
>  try {
>      // 텍스트가 포함된 새로운 사각형 셰이프 추가
>      IAutoShape shp = pres.getSlides().get_Item(0).getShapes().addAutoShape(ShapeType.Rectangle, 50, 50, 150, 50);
>      shp.getTextFrame().setText("New Text");
>      // 첫 번째 포션의 언어 확인
>      System.out.println(shp.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0).getPortionFormat().getLanguageId());
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**반환값:**  
java.lang.String

### setDefaultTextLanguage(String value) {#setDefaultTextLanguage-java.lang.String-}
```
public final void setDefaultTextLanguage(String value)
```

프레젠테이션 텍스트의 기본 언어를 가져오거나 설정합니다. 읽기/쓰기 String.

--------------------

> ```
> Example:
>   
>  // 로드 옵션을 사용해 기본 텍스트 문화 지정
>  LoadOptions loadOptions = new LoadOptions();
>  loadOptions.setDefaultTextLanguage("en-US");
>  Presentation pres = new Presentation(loadOptions);
>  try {
>      // 텍스트가 포함된 새로운 사각형 셰이프 추가
>      IAutoShape shp = pres.getSlides().get_Item(0).getShapes().addAutoShape(ShapeType.Rectangle, 50, 50, 150, 50);
>      shp.getTextFrame().setText("New Text");
>      // 첫 번째 포션의 언어 확인
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
public final boolean getDeleteEmbeddedBinaryObjects()
```

프레젠테이션 로드 중에 Aspose.Slides가 모든 임베디드 바이너리 객체를 삭제할지 여부를 결정합니다.

임베디드 바이너리 객체 유형:

읽기/쓰기 boolean.

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

**반환값:**  
boolean

### setDeleteEmbeddedBinaryObjects(boolean value) {#setDeleteEmbeddedBinaryObjects-boolean-}
```
public final void setDeleteEmbeddedBinaryObjects(boolean value)
```

프레젠테이션 로드 중에 Aspose.Slides가 모든 임베디드 바이너리 객체를 삭제할지 여부를 결정합니다.

임베디드 바이너리 객체 유형:

읽기/쓰기 boolean.

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