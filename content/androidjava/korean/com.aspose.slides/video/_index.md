---
title: Video
second_title: Java API 레퍼런스를 통한 Android용 Aspose.Slides
description: 프레젠테이션에 삽입된 이미지를 나타냅니다.
type: docs
url: /ko/com.aspose.slides/video/
---
**상속:**
java.lang.Object

**구현된 모든 인터페이스:**
[com.aspose.slides.IVideo](../../com.aspose.slides/ivideo), com.aspose.slides.IDOMObject
```
public class Video implements IVideo, IDOMObject
```

프레젠테이션에 삽입된 이미지를 나타냅니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getContentType()](#getContentType--) | 비디오의 MIME 유형을 반환합니다, (\#getBinaryData.getBinaryData)에서 인코딩됩니다. 읽기 전용 String. |
| [getBinaryData()](#getBinaryData--) | 오디오 데이터의 복사본을 반환합니다. 대량의 데이터가 있는 경우 메모리로 비디오 데이터를 불필요하게 로드하거나 OutOfMemoryException이 발생하는 것을 방지하기 위해 \#getStream.getStream 메서드 사용을 고려하십시오. 읽기 전용 byte[]. |
| [getStream()](#getStream--) | 읽기용 Stream 스트림을 반환합니다. 사용 후 'using'을 사용하거나 스트림을 닫으십시오. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
### getContentType() {#getContentType--}
```
public final String getContentType()
```

비디오의 MIME 유형을 반환합니다, (\#getBinaryData.getBinaryData)에서 인코딩됩니다. 읽기 전용 String.

**반환값:**
java.lang.String
### getBinaryData() {#getBinaryData--}
```
public final byte[] getBinaryData()
```

오디오 데이터의 복사본을 반환합니다. 대량의 데이터가 있는 경우 메모리로 비디오 데이터를 불필요하게 로드하거나 OutOfMemoryException이 발생하는 것을 방지하기 위해 \#getStream.getStream 메서드 사용을 고려하십시오. 읽기 전용 byte[].

**반환값:**
byte[]
### getStream() {#getStream--}
```
public final InputStream getStream()
```

읽기용 Stream 스트림을 반환합니다. 사용 후 'using'을 사용하거나 스트림을 닫으십시오.

**반환값:**
java.io.InputStream - 읽기용 Stream.
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Parent_Immediate 객체를 반환합니다. 읽기 전용 IDOMObject.

**반환값:**
com.aspose.slides.IDOMObject