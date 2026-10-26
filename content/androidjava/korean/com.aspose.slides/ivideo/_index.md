---
title: IVideo
second_title: Aspose.Slides for Android via Java API Reference
description: Represents a video embedded into a presentation.
type: docs
url: /ko/com.aspose.slides/ivideo/
---```
public interface IVideo
```

프레젠테이션에 삽입된 비디오를 나타냅니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getContentType()](#getContentType--) | 비디오의 MIME 유형을 (\#getBinaryData.getBinaryData)에서 인코딩된 형태로 반환합니다. |
| [getBinaryData()](#getBinaryData--) | 오디오 데이터의 복사본을 반환합니다. |
| [getStream()](#getStream--) | 읽기를 위한 Stream 스트림을 반환합니다. |
### getContentType() {#getContentType--}
```
public abstract String getContentType()
```

비디오의 MIME 유형을 (\#getBinaryData.getBinaryData)에서 인코딩된 형태로 반환합니다. 읽기 전용 String.

**반환:**
java.lang.String
### getBinaryData() {#getBinaryData--}
```
public abstract byte[] getBinaryData()
```

오디오 데이터의 복사본을 반환합니다. 데이터 양이 많을 경우 \#getStream.getStream 메서드를 사용하여 비디오 데이터를 메모리로 불필요하게 로드하거나 OutOfMemoryException이 발생하는 것을 방지하세요. 읽기 전용 byte[].

**반환:**
byte[]
### getStream() {#getStream--}
```
public abstract InputStream getStream()
```

읽기를 위한 Stream 스트림을 반환합니다. 사용 후 'using'을 사용하거나 스트림을 닫으세요.

**반환:**
java.io.InputStream - Stream for reading.