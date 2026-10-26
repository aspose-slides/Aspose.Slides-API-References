---
title: IAudio
second_title: Aspose.Slides for Java API Reference
description: 삽입된 오디오 파일을 나타냅니다.
type: docs
url: /ko/com.aspose.slides/iaudio/
---```
public interface IAudio
```

삽입된 오디오 파일을 나타냅니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getContentType()](#getContentType--) | 오디오의 MIME 유형을 반환합니다, (\#getBinaryData.getBinaryData)에서 인코딩됨. |
| [getBinaryData()](#getBinaryData--) | 오디오 데이터의 복사본을 반환합니다. |
| [getStream()](#getStream--) | 읽기를 위한 Stream을 반환합니다. |
### getContentType() {#getContentType--}
```
public abstract String getContentType()
```


오디오의 MIME 유형을 반환합니다, (\#getBinaryData.getBinaryData)에서 인코딩됨. 읽기 전용 String.

**반환:**  
java.lang.String
### getBinaryData() {#getBinaryData--}
```
public abstract byte[] getBinaryData()
```


오디오 데이터의 복사본을 반환합니다. 대량의 데이터를 다룰 경우 \#getStream.getStream 메서드를 사용하여 메모리에 불필요하게 오디오 데이터를 로드하거나 OutOfMemoryException을 방지하십시오. 읽기 전용 byte[].

**반환:**  
byte[]
### getStream() {#getStream--}
```
public abstract InputStream getStream()
```


읽기를 위한 Stream을 반환합니다. 사용 후 'using'을 사용하거나 스트림을 닫으십시오.

**반환:**  
java.io.InputStream - 읽기용 스트림.