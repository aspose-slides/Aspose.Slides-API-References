---
title: AudioCollection
second_title: Java API 참조를 통한 Android용 Aspose.Slides
description: 임베디드 오디오 파일의 컬렉션을 나타냅니다.
type: docs
url: /ko/com.aspose.slides/audiocollection/
---
**상속:**  
java.lang.Object, com.aspose.slides.DomObject

**모든 구현된 인터페이스:**  
[com.aspose.slides.IAudioCollection](../../com.aspose.slides/iaudiocollection)  
```
public class AudioCollection extends DomObject<Presentation> implements IAudioCollection
```

임베디드 오디오 파일의 컬렉션을 나타냅니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [size()](#size--) | 컬렉션에 있는 오디오 파일 수를 반환합니다. |
| [get_Item(int index)](#get-Item-int-) | 지정된 인덱스에 있는 요소를 가져옵니다. |
| [addAudio(IAudio audio)](#addAudio-com.aspose.slides.IAudio-) | 다른 프레젠테이션에서 오디오 파일 복사본을 추가합니다. |
| [addAudio(InputStream stream)](#addAudio-java.io.InputStream-) | 스트림에서 오디오를 생성하고 프레젠테이션에 추가합니다. |
| [addAudio(InputStream stream, int loadingStreamBehavior)](#addAudio-java.io.InputStream-int-) | 스트림에서 오디오를 생성하고 프레젠테이션에 추가합니다. |
| [addAudio(byte[] audioData)](#addAudio-byte---) | 바이트 배열에서 오디오를 생성하고 프레젠테이션에 추가합니다. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | 지정된 인덱스부터 지정된 배열에 오디오를 복사합니다. |
| [isSynchronized()](#isSynchronized--) | 컬렉션에 대한 접근이 동기화(스레드 안전)되는지 여부를 나타내는 값을 반환합니다. |
| [getSyncRoot()](#getSyncRoot--) | 동기화 루트를 반환합니다. |
| [iterator()](#iterator--) | 컬렉션을 반복하는 열거자를 반환합니다. |
| [iteratorJava()](#iteratorJava--) | 전체 컬렉션에 대한 java 이터레이터를 반환합니다. |
### size() {#size--}
```
public final int size()
```

컬렉션에 있는 오디오 파일 수를 반환합니다. 읽기 전용 int.

**반환:**  
int
### get_Item(int index) {#get-Item-int-}
```
public final IAudio get_Item(int index)
```

지정된 인덱스에 있는 요소를 가져옵니다. 읽기 전용 [IAudio](../../com.aspose.slides/iaudio).

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| index | int |  |

**반환:**
[IAudio](../../com.aspose.slides/iaudio)
### addAudio(IAudio audio) {#addAudio-com.aspose.slides.IAudio-}
```
public final IAudio addAudio(IAudio audio)
```

다른 프레젠테이션에서 오디오 파일 복사본을 추가합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| audio | [IAudio](../../com.aspose.slides/iaudio) | 소스 오디오. |

**반환:**
[IAudio](../../com.aspose.slides/iaudio) - 추가된 오디오.
### addAudio(InputStream stream) {#addAudio-java.io.InputStream-}
```
public final IAudio addAudio(InputStream stream)
```

스트림에서 오디오를 생성하고 프레젠테이션에 추가합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| stream | java.io.InputStream | 오디오를 추가할 스트림. |

**반환:**
[IAudio](../../com.aspose.slides/iaudio) - 추가된 오디오.
### addAudio(InputStream stream, int loadingStreamBehavior) {#addAudio-java.io.InputStream-int-}
```
public final IAudio addAudio(InputStream stream, int loadingStreamBehavior)
```

스트림에서 오디오를 생성하고 프레젠테이션에 추가합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| stream | java.io.InputStream | 오디오를 추가할 스트림. |
| loadingStreamBehavior | int | 스트림에 적용될 동작. |

**반환:**
[IAudio](../../com.aspose.slides/iaudio) - 추가된 오디오.
### addAudio(byte[] audioData) {#addAudio-byte---}
```
public final IAudio addAudio(byte[] audioData)
```

바이트 배열에서 오디오를 생성하고 프레젠테이션에 추가합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| audioData | byte[] | 오디오 바이트. |

**반환:**
[IAudio](../../com.aspose.slides/iaudio) - 추가된 오디오.
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

지정된 인덱스부터 지정된 배열에 오디오를 복사합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | 배열. |
| index | int | 인덱스. |
### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

컬렉션에 대한 접근이 동기화(스레드 안전)되는지 여부를 나타내는 값을 반환합니다. 읽기 전용 boolean.

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
public final System.Collections.Generic.IGenericEnumerator<IAudio> iterator()
```

컬렉션을 반복하는 열거자를 반환합니다.

**반환:**  
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IAudio> - 컬렉션을 반복하는 데 사용할 수 있는 IGenericEnumerator.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IAudio> iteratorJava()
```

전체 컬렉션에 대한 java 이터레이터를 반환합니다.

**반환:**  
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IAudio> - 전체 컬렉션에 대한 java.util.Iterator.