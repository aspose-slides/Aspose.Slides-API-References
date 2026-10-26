---
title: Audio
second_title: Aspose.Slides for Java API 참조
description: 임베디드 오디오 파일을 나타냅니다.
type: docs
url: /ko/com.aspose.slides/audio/
---
**Inheritance:**  
java.lang.Object, com.aspose.slides.DomObject

**All Implemented Interfaces:**  
[com.aspose.slides.IAudio](../../com.aspose.slides/iaudio)  
```
public class Audio extends DomObject<AudioCollection> implements IAudio
```

임베디드 오디오 파일을 나타냅니다.

## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getContentType()](#getContentType--) | 오디오의 MIME 유형을 반환합니다(\#getBinaryData.getBinaryData). |
| [setContentType(String value)](#setContentType-java.lang.String-) | 오디오의 MIME 유형을 반환합니다(\#getBinaryData.getBinaryData). |
| [getBinaryData()](#getBinaryData--) | 오디오 데이터 복사본을 반환합니다. |
| [getStream()](#getStream--) | 읽기를 위한 Stream 스트림을 반환합니다. |

### getContentType() {#getContentType--}
```
public final String getContentType()
```

오디오의 MIME 유형을 반환합니다(\#getBinaryData.getBinaryData). 읽기 전용 String.

**반환:**  
java.lang.String

### setContentType(String value) {#setContentType-java.lang.String-}
```
public final void setContentType(String value)
```

오디오의 MIME 유형을 반환합니다(\#getBinaryData.getBinaryData). 읽기 전용 String.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | java.lang.String |  |

### getBinaryData() {#getBinaryData--}
```
public final byte[] getBinaryData()
```

오디오 데이터 복사본을 반환합니다. 대량의 데이터인 경우 \#getStream.getStream 메서드를 사용하여 메모리에 오디오 데이터를 불필요하게 로드하거나 OutOfMemoryException이 발생하는 것을 방지하는 것을 고려하십시오. 읽기 전용 byte[].

**반환:**  
byte[]

### getStream() {#getStream--}
```
public final InputStream getStream()
```

읽기를 위한 Stream 스트림을 반환합니다. 'using'을 사용하거나 사용 후 스트림을 닫으십시오.

**반환:**  
java.io.InputStream - 읽기를 위한 Stream.