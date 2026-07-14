---
title: IAudioCollection
second_title: Java API를 통한 Aspose.Slides for Android 레퍼런스
description: 임베디드 오디오 파일 컬렉션을 나타냅니다.
type: docs
url: /ko/com.aspose.slides/iaudiocollection/
---
**모든 구현된 인터페이스:**
com.aspose.slides.IGenericCollection
```
public interface IAudioCollection extends IGenericCollection<IAudio>
```

임베디드 오디오 파일의 컬렉션을 나타냅니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | 지정된 인덱스에 있는 요소를 가져옵니다. |
| [addAudio(IAudio audio)](#addAudio-com.aspose.slides.IAudio-) | 다른 프레젠테이션에서 오디오 파일의 복사본을 추가합니다. |
| [addAudio(InputStream stream)](#addAudio-java.io.InputStream-) | 스트림에서 오디오를 생성하고 프레젠테이션에 추가합니다. |
| [addAudio(InputStream stream, int loadingStreamBehavior)](#addAudio-java.io.InputStream-int-) | 스트림에서 오디오를 생성하고 프레젠테이션에 추가합니다. |
| [addAudio(byte[] audioData)](#addAudio-byte---) | 바이트 배열에서 오디오를 생성하고 프레젠테이션에 추가합니다. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IAudio get_Item(int index)
```

지정된 인덱스에 있는 요소를 가져옵니다. 읽기 전용 [IAudio](../../com.aspose.slides/iaudio).

**매개변수:**
| 매개변수 | 타입 | 설명 |
| --- | --- | --- |
| index | int |  |

**반환값:**
[IAudio](../../com.aspose.slides/iaudio)
### addAudio(IAudio audio) {#addAudio-com.aspose.slides.IAudio-}
```
public abstract IAudio addAudio(IAudio audio)
```

다른 프레젠테이션에서 오디오 파일의 복사본을 추가합니다.

**매개변수:**
| 매개변수 | 타입 | 설명 |
| --- | --- | --- |
| audio | [IAudio](../../com.aspose.slides/iaudio) | 소스 오디오. |

**반환값:**
[IAudio](../../com.aspose.slides/iaudio) - 추가된 오디오.
### addAudio(InputStream stream) {#addAudio-java.io.InputStream-}
```
public abstract IAudio addAudio(InputStream stream)
```

스트림에서 오디오를 생성하고 프레젠테이션에 추가합니다.

**매개변수:**
| 매개변수 | 타입 | 설명 |
| --- | --- | --- |
| stream | java.io.InputStream | 오디오를 추가할 스트림. |

**반환값:**
[IAudio](../../com.aspose.slides/iaudio) - 추가된 오디오.
### addAudio(InputStream stream, int loadingStreamBehavior) {#addAudio-java.io.InputStream-int-}
```
public abstract IAudio addAudio(InputStream stream, int loadingStreamBehavior)
```

스트림에서 오디오를 생성하고 프레젠테이션에 추가합니다.

**매개변수:**
| 매개변수 | 타입 | 설명 |
| --- | --- | --- |
| stream | java.io.InputStream | 비디오 오디오를 추가할 스트림. |
| loadingStreamBehavior | int | 스트림에 적용될 [LoadingStreamBehavior](../../com.aspose.slides/loadingstreambehavior). |

**반환값:**
[IAudio](../../com.aspose.slides/iaudio) - 추가된 오디오.
### addAudio(byte[] audioData) {#addAudio-byte---}
```
public abstract IAudio addAudio(byte[] audioData)
```

바이트 배열에서 오디오를 생성하고 프레젠테이션에 추가합니다.

**매개변수:**
| 매개변수 | 타입 | 설명 |
| --- | --- | --- |
| audioData | byte[] | 오디오 바이트. |

**반환값:**
[IAudio](../../com.aspose.slides/iaudio) - 추가된 오디오.