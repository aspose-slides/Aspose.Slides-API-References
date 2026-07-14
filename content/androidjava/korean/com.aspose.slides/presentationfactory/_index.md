---
title: PresentationFactory
second_title: Java API 레퍼런스를 사용한 Android용 Aspose.Slides
description: COM 인터페이스를 통해 프레젠테이션을 생성할 수 있습니다.
type: docs
url: /ko/com.aspose.slides/presentationfactory/
---
**상속:**  
java.lang.Object

**구현된 모든 인터페이스:**  
[com.aspose.slides.IPresentationFactory](../../com.aspose.slides/ipresentationfactory)  
```
public class PresentationFactory implements IPresentationFactory
```

COM 인터페이스를 통해 프레젠테이션을 생성할 수 있습니다

--------------------

> ```
> The following example shows how to checking a Presentation Format.
>  
>  IPresentationInfo info = PresentationFactory.getInstance().getPresentationInfo("pres.pptx");
>  System.out.println(info.getLoadFormat()); // PPTX
>  IPresentationInfo info2 = PresentationFactory.getInstance().getPresentationInfo("pres.ppt");
>  System.out.println(info2.getLoadFormat()); // PPT
>  IPresentationInfo info3 = PresentationFactory.getInstance().getPresentationInfo("pres.odp");
>  System.out.println(info3.getLoadFormat()); // ODP
>  
>  The following example shows how to getting the properties of a Presentation.
>  
>  IPresentationInfo info = PresentationFactory.getInstance().getPresentationInfo("pres.pptx");
>  IDocumentProperties props = info.readDocumentProperties();
>  System.out.println(props.getCreatedTime());
>  System.out.println(props.getSubject());
>  System.out.println(props.getTitle());
>  // ..
>  
>  The following example shows how to updating the properties of a Presentation.
>  
>  IPresentationInfo info = PresentationFactory.getInstance().getPresentationInfo("pres.pptx");
>  IDocumentProperties props = info.readDocumentProperties();
>  props.setTitle("My title");
>  info.updateDocumentProperties(props);
> ```
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [PresentationFactory()](#PresentationFactory--) |  |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getInstance()](#getInstance--) | Presentation factory static instance. |
| [createPresentation()](#createPresentation--) | Creates new presentation. |
| [createPresentation(ILoadOptions options)](#createPresentation-com.aspose.slides.ILoadOptions-) | Creates new presentation with additional load options |
| [getPresentationInfo(String file)](#getPresentationInfo-java.lang.String-) | Creates new PresentationInfo object from file and binds presentation to it. |
| [getPresentationInfo(InputStream stream)](#getPresentationInfo-java.io.InputStream-) | Creates new PresentationInfo object from stream and binds presentation to it. |
| [readPresentation(byte[] data)](#readPresentation-byte---) | Reads an existing presentation from array |
| [readPresentation(byte[] data, ILoadOptions options)](#readPresentation-byte---com.aspose.slides.ILoadOptions-) | Reads an existing presentation from array with additional load options |
| [readPresentation(InputStream stream)](#readPresentation-java.io.InputStream-) | Reads an existing presentation from stream |
| [readPresentation(InputStream stream, ILoadOptions options)](#readPresentation-java.io.InputStream-com.aspose.slides.ILoadOptions-) | Reads an existing presentation from stream with additional load options |
| [readPresentation(String file)](#readPresentation-java.lang.String-) | Reads an existing presentation from file |
| [readPresentation(String file, ILoadOptions options)](#readPresentation-java.lang.String-com.aspose.slides.ILoadOptions-) | Reads an existing presentation from stream with additional load options |
| [getPresentationText(String file, int mode)](#getPresentationText-java.lang.String-int-) | Retrieves the raw text from the slides |
| [getPresentationText(InputStream stream, int mode)](#getPresentationText-java.io.InputStream-int-) | Retrieves the raw text from the slides |
| [getPresentationText(InputStream stream, int mode, ILoadOptions options)](#getPresentationText-java.io.InputStream-int-com.aspose.slides.ILoadOptions-) | Retrieves the raw text from the slides |
### PresentationFactory() {#PresentationFactory--}
```
public PresentationFactory()
```

### getInstance() {#getInstance--}
```
public static PresentationFactory getInstance()
```

프레젠테이션 팩터리 정적 인스턴스. 읽기 전용 [PresentationFactory](../../com.aspose.slides/presentationfactory).

**반환값:**  
[PresentationFactory](../../com.aspose.slides/presentationfactory)
### createPresentation() {#createPresentation--}
```
public final IPresentation createPresentation()
```

새 프레젠테이션을 생성합니다.

**반환값:**  
[IPresentation](../../com.aspose.slides/ipresentation) - 새 프레젠테이션
### createPresentation(ILoadOptions options) {#createPresentation-com.aspose.slides.ILoadOptions-}
```
public final IPresentation createPresentation(ILoadOptions options)
```

추가 로드 옵션으로 새 프레젠테이션을 생성합니다.

**매개 변수:**  
| 매개 변수 | 유형 | 설명 |
| --- | --- | --- |
| options | [ILoadOptions](../../com.aspose.slides/iloadoptions) | 로드 옵션 |

**반환값:**  
[IPresentation](../../com.aspose.slides/ipresentation) - 새 프레젠테이션
### getPresentationInfo(String file) {#getPresentationInfo-java.lang.String-}
```
public final IPresentationInfo getPresentationInfo(String file)
```

파일에서 새 PresentationInfo 객체를 생성하고 프레젠테이션에 바인딩합니다.

**매개 변수:**  
| 매개 변수 | 유형 | 설명 |
| --- | --- | --- |
| file | java.lang.String | 프레젠테이션 파일. |

**반환값:**  
[IPresentationInfo](../../com.aspose.slides/ipresentationinfo) - 프레젠테이션에 바인딩된 프레젠테이션 정보.
### getPresentationInfo(InputStream stream) {#getPresentationInfo-java.io.InputStream-}
```
public final IPresentationInfo getPresentationInfo(InputStream stream)
```

스트림에서 새 PresentationInfo 객체를 생성하고 프레젠테이션에 바인딩합니다. 지정된 스트림에 있는 프레젠테이션에 대한 정보를 가져옵니다.

**매개 변수:**  
| 매개 변수 | 유형 | 설명 |
| --- | --- | --- |
| stream | java.io.InputStream | 프레젠테이션 스트림. |

**반환값:**  
[IPresentationInfo](../../com.aspose.slides/ipresentationinfo) - 프레젠테이션에 바인딩된 프레젠테이션 정보.
### readPresentation(byte[] data) {#readPresentation-byte---}
```
public final IPPresentation readPresentation(byte[] data)
```

배열에서 기존 프레젠테이션을 읽습니다.

**매개 변수:**  
| 매개 변수 | 유형 | 설명 |
| --- | --- | --- |
| data | byte[] | 읽을 배열 |

**반환값:**  
[IPresentation](../../com.aspose.slides/ipresentation) - 읽은 프레젠테이션
### readPresentation(byte[] data, ILoadOptions options) {#readPresentation-byte---com.aspose.slides.ILoadOptions-}
```
public final IPresentation readPresentation(byte[] data, ILoadOptions options)
```

추가 로드 옵션으로 배열에서 기존 프레젠테이션을 읽습니다.

**매개 변수:**  
| 매개 변수 | 유형 | 설명 |
| --- | --- | --- |
| data | byte[] | 읽을 배열 |
| options | [ILoadOptions](../../com.aspose.slides/iloadoptions) | 로드 옵션 |

**반환값:**  
[IPresentation](../../com.aspose.slides/ipresentation) - 읽은 프레젠테이션
### readPresentation(InputStream stream) {#readPresentation-java.io.InputStream-}
```
public final IPresentation readPresentation(InputStream stream)
```

스트림에서 기존 프레젠테이션을 읽습니다.

**매개 변수:**  
| 매개 변수 | 유형 | 설명 |
| --- | --- | --- |
| stream | java.io.InputStream | 읽을 입력 스트림 |

**반환값:**  
[IPresentation](../../com.aspose.slides/ipresentation) - 읽은 프레젠테이션
### readPresentation(InputStream stream, ILoadOptions options) {#readPresentation-java.io.InputStream-com.aspose.slides.ILoadOptions-}
```
public final IPresentation readPresentation(InputStream stream, ILoadOptions options)
```

추가 로드 옵션으로 스트림에서 기존 프레젠테이션을 읽습니다.

**매개 변수:**  
| 매개 변수 | 유형 | 설명 |
| --- | --- | --- |
| stream | java.io.InputStream | 읽을 입력 스트림 |
| options | [ILoadOptions](../../com.aspose.slides/iloadoptions) | 로드 옵션 |

**반환값:**  
[IPresentation](../../com.aspose.slides/ipresentation) - 읽은 프레젠테이션
### readPresentation(String file) {#readPresentation-java.lang.String-}
```
public final IPresentation readPresentation(String file)
```

파일에서 기존 프레젠테이션을 읽습니다.

**매개 변수:**  
| 매개 변수 | 유형 | 설명 |
| --- | --- | --- |
| file | java.lang.String | 파일 이름 |

**반환값:**  
[IPresentation](../../com.aspose.slides/ipresentation) - 읽은 프레젠테이션
### readPresentation(String file, ILoadOptions options) {#readPresentation-java.lang.String-com.aspose.slides.ILoadOptions-}
```
public final IPresentation readPresentation(String file, ILoadOptions options)
```

추가 로드 옵션으로 파일에서 기존 프레젠테이션을 읽습니다.

**매개 변수:**  
| 매개 변수 | 유형 | 설명 |
| --- | --- | --- |
| file | java.lang.String | 파일 이름 |
| options | [ILoadOptions](../../com.aspose.slides/iloadoptions) | 로드 옵션 |

**반환값:**  
[IPresentation](../../com.aspose.slides/ipresentation) - 읽은 프레젠테이션
### getPresentationText(String file, int mode) {#getPresentationText-java.lang.String-int-}
```
public final IPresentationText getPresentationText(String file, int mode)
```

슬라이드의 원시 텍스트를 가져옵니다.

**매개 변수:**  
| 매개 변수 | 유형 | 설명 |
| --- | --- | --- |
| file | java.lang.String | 입력 파일 |
| mode | int | 추출 모드 |

**반환값:**  
[IPresentationText](../../com.aspose.slides/ipresentationtext) - 원시 슬라이드 텍스트를 나타내는 SlideText 배열을 포함하는 PresentationText 인스턴스
### getPresentationText(InputStream stream, int mode) {#getPresentationText-java.io.InputStream-int-}
```
public final IPPresentationText getPresentationText(InputStream stream, int mode)
```

슬라이드의 원시 텍스트를 가져옵니다.

**매개 변수:**  
| 매개 변수 | 유형 | 설명 |
| --- | --- | --- |
| stream | java.io.InputStream | 입력 스트림 |
| mode | int | 추출 모드 |

**반환값:**  
[IPresentationText](../../com.aspose.slides/ipresentationtext) - 원시 슬라이드 텍스트를 나타내는 SlideText 배열을 포함하는 PresentationText 인스턴스
### getPresentationText(InputStream stream, int mode, ILoadOptions options) {#getPresentationText-java.io.InputStream-int-com.aspose.slides.ILoadOptions-}
```
public final IPresentationText getPresentationText(InputStream stream, int mode, ILoadOptions options)
```

슬라이드의 원시 텍스트를 가져옵니다.

**매개 변수:**  
| 매개 변수 | 유형 | 설명 |
| --- | --- | --- |
| stream | java.io.InputStream | 입력 스트림 |
| mode | int | 추출 모드 |
| options | [ILoadOptions](../../com.aspose.slides/iloadoptions) | 로드 옵션 |

**반환값:**  
[IPresentationText](../../com.aspose.slides/ipresentationtext) - 원시 슬라이드 텍스트를 나타내는 SlideText 배열을 포함하는 PresentationText 인스턴스