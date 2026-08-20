---
title: Video
second_title: Aspose.Slides for Java API 레퍼런스
description: 프레젠테이션에 삽입된 이미지를 나타냅니다.
type: docs
url: /ko/com.aspose.slides/video/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.slides.IVideo](../../com.aspose.slides/ivideo), com.aspose.slides.IDOMObject
```
public class Video implements IVideo, IDOMObject
```

프레젠테이션에 삽입된 이미지를 나타냅니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getContentType()](#getContentType--) | 비디오의 MIME 타입을 반환합니다, (\#getBinaryData.getBinaryData)에서 인코딩됩니다. |
| [getBinaryData()](#getBinaryData--) | 오디오 데이터의 복사본을 반환합니다. |
| [getStream()](#getStream--) | 읽기를 위한 Stream 스트림을 반환합니다. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
### getContentType() {#getContentType--}
```
public final String getContentType()
```

비디오의 MIME 타입을 반환합니다, (\#getBinaryData.getBinaryData)에서 인코딩됩니다. 읽기 전용 String.

**Returns:**
java.lang.String
### getBinaryData() {#getBinaryData--}
```
public final byte[] getBinaryData()
```

오디오 데이터의 복사본을 반환합니다. 데이터 양이 많을 경우 비디오 데이터가 메모리로 로드되는 것을 방지하거나 OutOfMemoryException을 피하기 위해 \#getStream.getStream 메서드 사용을 고려하십시오. 읽기 전용 byte[].

**Returns:**
byte[]
### getStream() {#getStream--}
```
public final InputStream getStream()
```

읽기를 위한 Stream 스트림을 반환합니다. 사용 후 'using'을 사용하거나 스트림을 닫으세요.

**Returns:**
java.io.InputStream - 읽기를 위한 Stream.
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Parent_Immediate 객체를 반환합니다. 읽기 전용 IDOMObject.

**Returns:**
com.aspose.slides.IDOMObject