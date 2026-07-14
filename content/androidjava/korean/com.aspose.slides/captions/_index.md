---
title: Captions
second_title: Java API 레퍼런스를 통한 Android용 Aspose.Slides
description: WebVTT 닫힌 캡션을 나타냅니다.
type: docs
url: /ko/com.aspose.slides/captions/
---
**상속:**  
java.lang.Object

**모든 구현된 인터페이스:**  
[com.aspose.slides.ICaptions](../../com.aspose.slides/icaptions)  
```
public class Captions implements ICaptions
```

WebVTT 닫힌 캡션을 나타냅니다.

## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getCaptionId()](#getCaptionId--) | 닫힌 캡션의 전역 고유 식별자(GUID)를 반환합니다. |
| [getLabel()](#getLabel--) | 닫힌 캡션의 레이블을 반환하거나 설정합니다. |
| [setLabel(String value)](#setLabel-java.lang.String-) | 닫힌 캡션의 레이블을 반환하거나 설정합니다. |
| [getBinaryData()](#getBinaryData--) | 닫힌 캡션의 바이너리 데이터를 반환합니다. |
| [getDataAsString()](#getDataAsString--) | 닫힌 캡션 데이터를 UTF-8 인코딩 문자열로 반환합니다. 읽기 전용 String. |

### getCaptionId() {#getCaptionId--}
```
public final UUID getCaptionId()
```

닫힌 캡션의 전역 고유 식별자(GUID)를 반환합니다. 읽기 전용 java.util.UUID.

**반환값:**  
java.util.UUID

### getLabel() {#getLabel--}
```
public final String getLabel()
```

닫힌 캡션의 레이블을 반환하거나 설정합니다. 읽기/쓰기 String.

**반환값:**  
java.lang.String

### setLabel(String value) {#setLabel-java.lang.String-}
```
public final void setLabel(String value)
```

닫힌 캡션의 레이블을 반환하거나 설정합니다. 읽기/쓰기 String.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | java.lang.String |  |

### getBinaryData() {#getBinaryData--}
```
public final byte[] getBinaryData()
```

닫힌 캡션의 바이너리 데이터를 반환합니다. 읽기 전용 byte[] .

**반환값:**  
byte[]

### getDataAsString() {#getDataAsString--}
```
public final String getDataAsString()
```

닫힌 캡션 데이터를 UTF-8 인코딩 문자열로 반환합니다. 읽기 전용 String.

**반환값:**  
java.lang.String