---
title: IAudio
second_title: Java API 참조용 Aspose.Slides for Android
description: 내장된 오디오 파일을 나타냅니다.
type: docs
url: /ko/com.aspose.slides/iaudio/
---```
public interface IAudio
```

내장된 오디오 파일을 나타냅니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getContentType()](#getContentType--) | 오디오의 MIME 유형을 반환합니다(\#getBinaryData.getBinaryData 로 인코딩됨). |
| [getBinaryData()](#getBinaryData--) | 오디오 데이터의 복사본을 반환합니다. |
| [getStream()](#getStream--) | 읽기를 위한 Stream 스트림을 반환합니다. |
### getContentType() {#getContentType--}
```
public abstract String getContentType()
```

오디오의 MIME 유형을 반환합니다(\#getBinaryData.getBinaryData 로 인코딩됨). 읽기 전용 String.

**Returns:**
java.lang.String
### getBinaryData() {#getBinaryData--}
```
public abstract byte[] getBinaryData()
```

오디오 데이터의 복사본을 반환합니다. 데이터 양이 많은 경우 \#getStream.getStream 메서드를 사용하여 메모리로 오디오 데이터를 불필요하게 로드하거나 OutOfMemoryException이 발생하는 것을 방지하는 것을 고려하십시오. 읽기 전용 byte[].

**Returns:**
byte[]
### getStream() {#getStream--}
```
public abstract InputStream getStream()
```

읽기를 위한 Stream 스트림을 반환합니다. 'using'을 사용하거나 사용 후 스트림을 닫으십시오.

**Returns:**
java.io.InputStream - 읽기를 위한 스트림.