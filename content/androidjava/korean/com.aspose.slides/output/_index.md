---
title: Output
second_title: Java API를 통한 Android용 Aspose.Slides 레퍼런스
description: IWebDocument에 대한 출력 요소의 컬렉션을 나타냅니다.
type: docs
url: /ko/com.aspose.slides/output/
---
**상속:**
java.lang.Object
```
public final class Output
```

IWebDocument에 대한 출력 요소의 컬렉션을 나타냅니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [<TContextObject>add(String path, String templateKey, TContextObject contextObject)](#-TContextObject-add-java.lang.String-java.lang.String-TContextObject-) | 컨텍스트 객체에 대한 출력 요소를 추가합니다. |
| [add(String path, IPPImage image)](#add-java.lang.String-com.aspose.slides.IPPImage-) | 이미지에 대한 출력 요소를 추가합니다. |
| [add(String path, IImage image)](#add-java.lang.String-com.aspose.slides.IImage-) | 이미지에 대한 출력 요소를 추가합니다. |
| [add(String path, IVideo video)](#add-java.lang.String-com.aspose.slides.IVideo-) | 비디오에 대한 출력 요소를 추가합니다. |
| [add(String path, IFontData fontData, int fontStyle)](#add-java.lang.String-com.aspose.slides.IFontData-int-) | 지정된 폰트에 대한 출력 파일 요소를 생성하고 추가합니다. |
| [add(String path, String textContent)](#add-java.lang.String-java.lang.String-) | 텍스트 내용에 대한 출력 요소를 추가합니다. |
| [bindResource(IOutputFile outputFile, Object obj)](#bindResource-com.aspose.slides.IOutputFile-java.lang.Object-) | 리소스를 출력 파일에 바인드합니다. |
| [getResourcePath(Object obj)](#getResourcePath-java.lang.Object-) | 주어진 리소스에 대한 경로를 반환합니다. |
### <TContextObject>add(String path, String templateKey, TContextObject contextObject) {#-TContextObject-add-java.lang.String-java.lang.String-TContextObject-}
```
public final IOutputFile <TContextObject>add(String path, String templateKey, TContextObject contextObject)
```

컨텍스트 객체에 대한 출력 요소를 추가합니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| path | java.lang.String | 출력 경로. |
| templateKey | java.lang.String | 출력 전에 컨텍스트 객체 변환에 사용되는 템플릿의 키. |
| contextObject | TContextObject | 컨텍스트 객체. |

**반환값:**
[IOutputFile](../../com.aspose.slides/ioutputfile) - [IOutputFile](../../com.aspose.slides/ioutputfile) 컨텍스트 객체용 객체.

### add(String path, IPPImage image) {#add-java.lang.String-com.aspose.slides.IPPImage-}
```
public final IOutputFile add(String path, IPPImage image)
```

이미지에 대한 출력 요소를 추가합니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| path | java.lang.String | 출력 경로. |
| image | [IPPImage](../../com.aspose.slides/ippimage) | 출력할 이미지. |

**반환값:**
[IOutputFile](../../com.aspose.slides/ioutputfile) - [IOutputFile](../../com.aspose.slides/ioutputfile) 이미지용 객체.

### add(String path, IImage image) {#add-java.lang.String-com.aspose.slides.IImage-}
```
public final IOutputFile add(String path, IImage image)
```

이미지에 대한 출력 요소를 추가합니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| path | java.lang.String | 출력 경로. |
| image | [IImage](../../com.aspose.slides/iimage) | 출력할 이미지. |

**반환값:**
[IOutputFile](../../com.aspose.slides/ioutputfile) - [IOutputFile](../../com.aspose.slides/ioutputfile) 이미지용 객체.

### add(String path, IVideo video) {#add-java.lang.String-com.aspose.slides.IVideo-}
```
public final IOutputFile add(String path, IVideo video)
```

비디오에 대한 출력 요소를 추가합니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| path | java.lang.String | 출력 경로. |
| video | [IVideo](../../com.aspose.slides/ivideo) | 출력할 비디오. |

**반환값:**
[IOutputFile](../../com.aspose.slides/ioutputfile) - [IOutputFile](../../com.aspose.slides/ioutputfile) 비디오용 객체.

### add(String path, IFontData fontData, int fontStyle) {#add-java.lang.String-com.aspose.slides.IFontData-int-}
```
public final IOutputFile add(String path, IFontData fontData, int fontStyle)
```

지정된 폰트에 대한 출력 파일 요소를 생성하고 추가합니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| path | java.lang.String | 폰트 출력이 저장될 파일 경로. |
| fontData | [IFontData](../../com.aspose.slides/ifontdata) | 출력에 기록될 폰트 데이터. |
| fontStyle | int | 폰트 스타일 (예: Regular, Bold, Italic). |

**반환값:**
[IOutputFile](../../com.aspose.slides/ioutputfile) - 생성된 폰트를 위한 [IOutputFile](../../com.aspose.slides/ioutputfile) 인스턴스.

### add(String path, String textContent) {#add-java.lang.String-java.lang.String-}
```
public final IOutputFile add(String path, String textContent)
```

텍스트 내용에 대한 출력 요소를 추가합니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| path | java.lang.String | 출력 경로. |
| textContent | java.lang.String | 출력할 내용. |

**반환값:**
[IOutputFile](../../com.aspose.slides/ioutputfile) - [IOutputFile](../../com.aspose.slides/ioutputfile) 텍스트 내용용 객체.

### bindResource(IOutputFile outputFile, Object obj) {#bindResource-com.aspose.slides.IOutputFile-java.lang.Object-}
```
public final void bindResource(IOutputFile outputFile, Object obj)
```

리소스를 출력 파일에 바인드합니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| outputFile | [IOutputFile](../../com.aspose.slides/ioutputfile) | 출력 파일. |
| obj | java.lang.Object | 리소스 객체. |

### getResourcePath(Object obj) {#getResourcePath-java.lang.Object-}
```
public final String getResourcePath(Object obj)
```

주어진 리소스에 대한 경로를 반환합니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| obj | java.lang.Object | 리소스 객체. |

**반환값:**
java.lang.String - 리소스 경로.