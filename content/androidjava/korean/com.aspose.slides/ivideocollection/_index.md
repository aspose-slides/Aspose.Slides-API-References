---
title: IVideoCollection
second_title: Java API 참조를 통한 Android용 Aspose.Slides
description: Video 개체의 컬렉션을 나타냅니다.
type: docs
url: /ko/com.aspose.slides/ivideocollection/
---
**구현된 모든 인터페이스:**
com.aspose.slides.IGenericCollection
```
public interface IVideoCollection extends IGenericCollection<IVideo>
```

Video 개체의 컬렉션을 나타냅니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | 지정된 인덱스에 있는 요소를 가져옵니다. |
| [addVideo(IVideo video)](#addVideo-com.aspose.slides.IVideo-) | 다른 프레젠테이션에서 비디오 파일의 복사본을 추가합니다. |
| [addVideo(InputStream stream, int loadingStreamBehavior)](#addVideo-java.io.InputStream-int-) | 스트림에서 프레젠테이션에 비디오를 생성하고 추가합니다. |
| [addVideo(byte[] videoData)](#addVideo-byte---) | 바이트 배열에서 프레젠테이션에 비디오를 생성하고 추가합니다. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IVideo get_Item(int index)
```

지정된 인덱스에 있는 요소를 가져옵니다. 읽기 전용 [IVideo](../../com.aspose.slides/ivideo).

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| index | int |  |

**반환값:**
[IVideo](../../com.aspose.slides/ivideo)
### addVideo(IVideo video) {#addVideo-com.aspose.slides.IVideo-}
```
public abstract IVideo addVideo(IVideo video)
```

다른 프레젠테이션에서 비디오 파일의 복사본을 추가합니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| video | [IVideo](../../com.aspose.slides/ivideo) | 소스 비디오. |

**반환값:**
[IVideo](../../com.aspose.slides/ivideo) - 추가된 비디오.
### addVideo(InputStream stream, int loadingStreamBehavior) {#addVideo-java.io.InputStream-int-}
```
public abstract IVideo addVideo(InputStream stream, int loadingStreamBehavior)
```

스트림에서 프레젠테이션에 비디오를 생성하고 추가합니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| stream | java.io.InputStream | 비디오 파일을 추가할 스트림. |
| loadingStreamBehavior | int | 스트림에 적용될 동작입니다. |

**반환값:**
[IVideo](../../com.aspose.slides/ivideo) - 추가된 [IVideo](../../com.aspose.slides/ivideo).
### addVideo(byte[] videoData) {#addVideo-byte---}
```
public abstract IVideo addVideo(byte[] videoData)
```

바이트 배열에서 프레젠테이션에 비디오를 생성하고 추가합니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| videoData | byte[] | 비디오 바이트. |

**반환값:**
[IVideo](../../com.aspose.slides/ivideo) - 추가된 비디오.