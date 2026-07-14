---
title: VideoCollection
second_title: Aspose.Slides for Android Java API 레퍼런스를 통해
description: Video 객체의 컬렉션을 나타냅니다.
type: docs
url: /ko/com.aspose.slides/videocollection/
---
**상속:**  
java.lang.Object, com.aspose.slides.DomObject

**구현된 모든 인터페이스:**  
[com.aspose.slides.IVideoCollection](../../com.aspose.slides/ivideocollection)  
```
public class VideoCollection extends DomObject<Presentation> implements IVideoCollection
```

Video 개체의 컬렉션을 나타냅니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [size()](#size--) | 컬렉션에 있는 비디오 파일 수를 반환합니다. |
| [get_Item(int index)](#get-Item-int-) | 지정된 인덱스에 있는 요소를 가져옵니다. |
| [addVideo(IVideo video)](#addVideo-com.aspose.slides.IVideo-) | 다른 프레젠테이션에서 비디오 파일의 복사본을 추가합니다. |
| [addVideo(InputStream stream, int loadingStreamBehavior)](#addVideo-java.io.InputStream-int-) | 스트림에서 비디오를 생성하여 프레젠테이션에 추가합니다. |
| [addVideo(byte[] videoData)](#addVideo-byte---) | 바이트 배열에서 비디오를 생성하여 프레젠테이션에 추가합니다. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | 지정된 인덱스부터 지정된 배열에 비디오를 복사합니다. |
| [isSynchronized()](#isSynchronized--) | 컬렉션에 대한 접근이 동기화(스레드 안전)되는지를 나타내는 값을 반환합니다. |
| [getSyncRoot()](#getSyncRoot--) | 동기화 루트를 반환합니다. |
| [iterator()](#iterator--) | 컬렉션을 반복하는 열거자를 반환합니다. |
| [iteratorJava()](#iteratorJava--) | 전체 컬렉션에 대한 java 반복자를 반환합니다. |
### size() {#size--}
```
public final int size()
```

컬렉션에 있는 비디오 파일 수를 반환합니다. 읽기 전용 int.

**반환:**  
int
### get_Item(int index) {#get-Item-int-}
```
public final IVideo get_Item(int index)
```

지정된 인덱스에 있는 요소를 가져옵니다. 읽기 전용 [IVideo](../../com.aspose.slides/ivideo).

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| index | int |  |

**반환:**
[IVideo](../../com.aspose.slides/ivideo)
### addVideo(IVideo video) {#addVideo-com.aspose.slides.IVideo-}
```
public final IVideo addVideo(IVideo video)
```

다른 프레젠테이션에서 비디오 파일의 복사본을 추가합니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| video | [IVideo](../../com.aspose.slides/ivideo) | 소스 비디오. |

**반환:**
[IVideo](../../com.aspose.slides/ivideo) - 추가된 비디오.
### addVideo(InputStream stream, int loadingStreamBehavior) {#addVideo-java.io.InputStream-int-}
```
public final IVideo addVideo(InputStream stream, int loadingStreamBehavior)
```

스트림에서 비디오를 생성하여 프레젠테이션에 추가합니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| stream | java.io.InputStream | 비디오 파일을 추가할 스트림. |
| loadingStreamBehavior | int | 스트림에 적용될 동작. |

**반환:**
[IVideo](../../com.aspose.slides/ivideo) - 추가된 [IVideo](../../com.aspose.slides/ivideo).
### addVideo(byte[] videoData) {#addVideo-byte---}
```
public final IVideo addVideo(byte[] videoData)
```

바이트 배열에서 비디오를 생성하여 프레젠테이션에 추가합니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| videoData | byte[] | 비디오 바이트. |

**반환:**
[IVideo](../../com.aspose.slides/ivideo) - 추가된 비디오.
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

지정된 인덱스부터 지정된 배열에 비디오를 복사합니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | 배열. |
| index | int | 인덱스. |
### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

컬렉션에 대한 접근이 동기화(스레드 안전)되는지를 나타내는 값을 반환합니다. 읽기 전용 boolean.

**반환:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

동기화 루트를 반환합니다. 읽기 전용 Object.

**반환:**
java.lang.Object
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IVideo> iterator()
```

컬렉션을 반복하는 열거자를 반환합니다.

**반환:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IVideo> - 컬렉션을 반복하는 데 사용할 수 있는 IGenericEnumerator
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IVideo> iteratorJava()
```

전체 컬렉션에 대한 java 반복자를 반환합니다.

**반환:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IVideo> - 전체 컬렉션에 대한 java.util.Iterator