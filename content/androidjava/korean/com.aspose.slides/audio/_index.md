---
title: Audio
second_title: Java API 레퍼런스를 통한 Aspose.Slides for Android
description: 내장 오디오 파일을 나타냅니다.
type: docs
url: /ko/com.aspose.slides/audio/
---
**상속:**  
java.lang.Object, com.aspose.slides.DomObject

**구현된 모든 인터페이스:**  
[com.aspose.slides.IAudio](../../com.aspose.slides/iaudio)  
```
public class Audio extends DomObject<AudioCollection> implements IAudio
```

내장 오디오 파일을 나타냅니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getContentType()](#getContentType--) | 오디오의 MIME 타입을 반환합니다, (\#getBinaryData.getBinaryData)에서 인코딩됩니다. 읽기 전용 String. |
| [setContentType(String value)](#setContentType-java.lang.String-) | 오디오의 MIME 타입을 반환합니다, (\#getBinaryData.getBinaryData)에서 인코딩됩니다. 읽기 전용 String. |
| [getBinaryData()](#getBinaryData--) | 오디오 데이터의 복사본을 반환합니다. |
| [getStream()](#getStream--) | 읽기용 Stream 스트림을 반환합니다. |
### getContentType() {#getContentType--}
```
public final String getContentType()
```

오디오의 MIME 타입을 반환합니다, (\#getBinaryData.getBinaryData)에서 인코딩됩니다. 읽기 전용 String.

**반환:**  
java.lang.String
### setContentType(String value) {#setContentType-java.lang.String-}
```
public final void setContentType(String value)
```

오디오의 MIME 타입을 반환합니다, (\#getBinaryData.getBinaryData)에서 인코딩됩니다. 읽기 전용 String.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | java.lang.String |  |
### getBinaryData() {#getBinaryData--}
```
public final byte[] getBinaryData()
```

오디오 데이터의 복사본을 반환합니다. 대량의 데이터를 다룰 경우 \#getStream.getStream 메서드 사용을 고려하여 메모리로 오디오 데이터를 불필요하게 로드하거나 OutOfMemoryException이 발생하는 것을 방지하십시오. 읽기 전용 byte[].

**반환:**  
byte[]
### getStream() {#getStream--}
```
public final InputStream getStream()
```

읽기용 Stream 스트림을 반환합니다. 사용 후 'using'을 사용하거나 스트림을 닫으세요.

**반환:**  
java.io.InputStream - 읽기용 스트림.