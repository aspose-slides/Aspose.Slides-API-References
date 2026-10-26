---
title: IVideo
second_title: Aspose.Slides for Java API Reference
description: 프레젠테이션에 삽입된 비디오를 나타냅니다.
type: docs
url: /ko/com.aspose.slides/ivideo/
---```
public interface IVideo
```

프레젠테이션에 삽입된 비디오를 나타냅니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getContentType()](#getContentType--) | 비디오의 MIME 유형을 반환합니다 (\#getBinaryData.getBinaryData). |
| [getBinaryData()](#getBinaryData--) | 오디오 데이터의 복사본을 반환합니다. |
| [getStream()](#getStream--) | 읽기를 위한 Stream 스트림을 반환합니다. |
### getContentType() {#getContentType--}
```
public abstract String getContentType()
```

비디오의 MIME 유형을 반환합니다(\#getBinaryData.getBinaryData). 읽기 전용 String.

**반환:**  
java.lang.String
### getBinaryData() {#getBinaryData--}
```
public abstract byte[] getBinaryData()
```

오디오 데이터의 복사본을 반환합니다. 대량의 데이터인 경우 \#getStream.getStream 메서드를 사용하여 비디오 데이터가 메모리로 불필요하게 로드되거나 OutOfMemoryException이 발생하는 것을 방지하십시오. 읽기 전용 byte[].

**반환:**  
byte[]
### getStream() {#getStream--}
```
public abstract InputStream getStream()
```

읽기를 위한 Stream 스트림을 반환합니다. 사용 후 'using'을 사용하거나 스트림을 닫으십시오.

**반환:**  
java.io.InputStream - 읽기를 위한 스트림.