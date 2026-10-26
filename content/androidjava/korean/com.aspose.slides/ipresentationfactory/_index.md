---
title: IPresentationFactory
second_title: Aspose.Slides for Android via Java API Reference
description: COM 인터페이스를 통해 프레젠테이션을 생성할 수 있습니다.
type: docs
url: /ko/com.aspose.slides/ipresentationfactory/
---```
public interface IPresentationFactory
```

COM 인터페이스를 통해 프레젠테이션을 생성할 수 있습니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [createPresentation()](#createPresentation--) | Creates new presentation. |
| [createPresentation(ILoadOptions options)](#createPresentation-com.aspose.slides.ILoadOptions-) | Creates new presentation with additional load options |
| [getPresentationInfo(String file)](#getPresentationInfo-java.lang.String-) | Gets info about presentation in specified file. |
| [getPresentationInfo(InputStream stream)](#getPresentationInfo-java.io.InputStream-) | Gets info about presentation in specified stream. |
| [readPresentation(byte[] data)](#readPresentation-byte---) | Reads an existing presentation from array |
| [readPresentation(byte[] data, ILoadOptions options)](#readPresentation-byte---com.aspose.slides.ILoadOptions-) | Reads an existing presentation from array with additional load options |
| [readPresentation(InputStream stream)](#readPresentation-java.io.InputStream-) | Reads an existing presentation from stream |
| [readPresentation(InputStream stream, ILoadOptions options)](#readPresentation-java.io.InputStream-com.aspose.slides.ILoadOptions-) | Reads an existing presentation from stream with additional load options |
| [readPresentation(String file)](#readPresentation-java.lang.String-) | Reads an existing presentation from file |
| [readPresentation(String file, ILoadOptions options)](#readPresentation-java.lang.String-com.aspose.slides.ILoadOptions-) | Reads an existing presentation from stream with additional load options |
| [getPresentationText(String file, int mode)](#getPresentationText-java.lang.String-int-) | Retrieves the raw text from the slides |
| [getPresentationText(InputStream stream, int mode)](#getPresentationText-java.io.InputStream-int-) | Retrieves the raw text from the slides |
| [getPresentationText(InputStream stream, int mode, ILoadOptions options)](#getPresentationText-java.io.InputStream-int-com.aspose.slides.ILoadOptions-) | Retrieves the raw text from the slides |
### createPresentation() {#createPresentation--}
```
public abstract IPresentation createPresentation()
```

새 프레젠테이션을 생성합니다.

**반환값:**  
[IPresentation](../../com.aspose.slides/ipresentation) - 새 프레젠테이션
### createPresentation(ILoadOptions options) {#createPresentation-com.aspose.slides.ILoadOptions-}
```
public abstract IPresentation createPresentation(ILoadOptions options)
```

추가 로드 옵션으로 새 프레젠테이션을 생성합니다.

**매개변수:**
| 매개변수 | 타입 | 설명 |
| --- | --- | --- |
| options | [ILoadOptions](../../com.aspose.slides/iloadoptions) | 로드 옵션 |

**반환값:**  
[IPresentation](../../com.aspose.slides/ipresentation) - 새 프레젠테이션
### getPresentationInfo(String file) {#getPresentationInfo-java.lang.String-}
```
public abstract IPresentationInfo getPresentationInfo(String file)
```

지정된 파일의 프레젠테이션에 대한 정보를 가져옵니다.

**매개변수:**
| 매개변수 | 타입 | 설명 |
| --- | --- | --- |
| file | java.lang.String | 프레젠테이션 파일. |

**반환값:**  
[IPresentationInfo](../../com.aspose.slides/ipresentationinfo) - 프레젠테이션 정보
### getPresentationInfo(InputStream stream) {#getPresentationInfo-java.io.InputStream-}
```
public abstract IPresentationInfo getPresentationInfo(InputStream stream)
```

지정된 스트림의 프레젠테이션에 대한 정보를 가져옵니다.

**매개변수:**
| 매개변수 | 타입 | 설명 |
| --- | --- | --- |
| stream | java.io.InputStream | 프레젠테이션 스트림. |

**반환값:**  
[IPresentationInfo](../../com.aspose.slides/ipresentationinfo) - 프레젠테이션 정보.
### readPresentation(byte[] data) {#readPresentation-byte---}
```
public abstract IPresentation readPresentation(byte[] data)
```

배열에서 기존 프레젠테이션을 읽어옵니다.

**매개변수:**
| 매개변수 | 타입 | 설명 |
| --- | --- | --- |
| data | byte[] | 읽을 배열 |

**반환값:**  
[IPresentation](../../com.aspose.slides/ipresentation) - 읽은 프레젠테이션
### readPresentation(byte[] data, ILoadOptions options) {#readPresentation-byte---com.aspose.slides.ILoadOptions-}
```
public abstract IPresentation readPresentation(byte[] data, ILoadOptions options)
```

배열에서 기존 프레젠테이션을 추가 로드 옵션과 함께 읽어옵니다.

**매개변수:**
| 매개변수 | 타입 | 설명 |
| --- | --- | --- |
| data | byte[] | 읽을 배열 |
| options | [ILoadOptions](../../com.aspose.slides/iloadoptions) | 로드 옵션 |

**반환값:**  
[IPresentation](../../com.aspose.slides/ipresentation) - 읽은 프레젠테이션
### readPresentation(InputStream stream) {#readPresentation-java.io.InputStream-}
```
public abstract IPresentation readPresentation(InputStream stream)
```

스트림에서 기존 프레젠테이션을 읽어옵니다.

**매개변수:**
| 매개변수 | 타입 | 설명 |
| --- | --- | --- |
| stream | java.io.InputStream | 읽을 입력 스트림 |

**반환값:**  
[IPresentation](../../com.aspose.slides/ipresentation) - 읽은 프레젠테이션
### readPresentation(InputStream stream, ILoadOptions options) {#readPresentation-java.io.InputStream-com.aspose.slides.ILoadOptions-}
```
public abstract IPresentation readPresentation(InputStream stream, ILoadOptions options)
```

스트림에서 기존 프레젠테이션을 추가 로드 옵션과 함께 읽어옵니다.

**매개변수:**
| 매개변수 | 타입 | 설명 |
| --- | --- | --- |
| stream | java.io.InputStream | 읽을 입력 스트림 |
| options | [ILoadOptions](../../com.aspose.slides/iloadoptions) | 로드 옵션 |

**반환값:**  
[IPresentation](../../com.aspose.slides/ipresentation) - 읽은 프레젠테이션
### readPresentation(String file) {#readPresentation-java.lang.String-}
```
public abstract IPresentation readPresentation(String file)
```

파일에서 기존 프레젠테이션을 읽어옵니다.

**매개변수:**
| 매개변수 | 타입 | 설명 |
| --- | --- | --- |
| file | java.lang.String | 파일 이름 |

**반환값:**  
[IPresentation](../../com.aspose.slides/ipresentation) - 읽은 프레젠테이션
### readPresentation(String file, ILoadOptions options) {#readPresentation-java.lang.String-com.aspose.slides.ILoadOptions-}
```
public abstract IPresentation readPresentation(String file, ILoadOptions options)
```

파일에서 기존 프레젠테이션을 추가 로드 옵션과 함께 읽어옵니다.

**매개변수:**
| 매개변수 | 타입 | 설명 |
| --- | --- | --- |
| file | java.lang.String | 파일 이름 |
| options | [ILoadOptions](../../com.aspose.slides/iloadoptions) | 로드 옵션 |

**반환값:**  
[IPresentation](../../com.aspose.slides/ipresentation) - 읽은 프레젠테이션
### getPresentationText(String file, int mode) {#getPresentationText-java.lang.String-int-}
```
public abstract IPresentationText getPresentationText(String file, int mode)
```

슬라이드에서 원시 텍스트를 가져옵니다.

**매개변수:**
| 매개변수 | 타입 | 설명 |
| --- | --- | --- |
| file | java.lang.String | 입력 파일 |
| mode | int | 추출 모드 |

**반환값:**  
[IPresentationText](../../com.aspose.slides/ipresentationtext) - 원시 슬라이드 텍스트를 나타내는 SlideText 배열을 포함하는 PresentationText 인스턴스
### getPresentationText(InputStream stream, int mode) {#getPresentationText-java.io.InputStream-int-}
```
public abstract IPresentationText getPresentationText(InputStream stream, int mode)
```

슬라이드에서 원시 텍스트를 가져옵니다.

**매개변수:**
| 매개변수 | 타입 | 설명 |
| --- | --- | --- |
| stream | java.io.InputStream | 입력 스트림 |
| mode | int | 추출 모드 |

**반환값:**  
[IPresentationText](../../com.aspose.slides/ipresentationtext) - 원시 슬라이드 텍스트를 나타내는 SlideText 배열을 포함하는 PresentationText 인스턴스
### getPresentationText(InputStream stream, int mode, ILoadOptions options) {#getPresentationText-java.io.InputStream-int-com.aspose.slides.ILoadOptions-}
```
public abstract IPresentationText getPresentationText(InputStream stream, int mode, ILoadOptions options)
```

슬라이드에서 원시 텍스트를 가져옵니다.

**매개변수:**
| 매개변수 | 타입 | 설명 |
| --- | --- | --- |
| stream | java.io.InputStream | 입력 스트림 |
| mode | int | 추출 모드 |
| options | [ILoadOptions](../../com.aspose.slides/iloadoptions) | 로드 옵션 |

**반환값:**  
[IPresentationText](../../com.aspose.slides/ipresentationtext) - 원시 슬라이드 텍스트를 나타내는 SlideText 배열을 포함하는 PresentationText 인스턴스