---
title: ICaptions
second_title: Aspose.Slides for Android via Java API Reference
description: Represents the WebVTT closed captions.
type: docs
url: /ko/com.aspose.slides/icaptions/
---```
public interface ICaptions
```

닫힌 자막을 나타냅니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getCaptionId()](#getCaptionId--) | 닫힌 자막의 전역 고유 식별자(GUID)를 반환합니다. |
| [getLabel()](#getLabel--) | 닫힌 자막의 레이블을 반환하거나 설정합니다. |
| [setLabel(String value)](#setLabel-java.lang.String-) | 닫힌 자막의 레이블을 반환하거나 설정합니다. |
| [getBinaryData()](#getBinaryData--) | 닫힌 자막의 바이너리 데이터를 반환합니다. |
| [getDataAsString()](#getDataAsString--) | 닫힌 자막 데이터를 UTF-8 인코딩 문자열로 반환합니다. 읽기 전용 String. |
### getCaptionId() {#getCaptionId--}
```
public abstract UUID getCaptionId()
```


닫힌 자막의 전역 고유 식별자(GUID)를 반환합니다. 읽기 전용 java.util.UUID.

**반환값:**
java.util.UUID
### getLabel() {#getLabel--}
```
public abstract String getLabel()
```


닫힌 자막의 레이블을 반환하거나 설정합니다. 읽기/쓰기 String.

**반환값:**
java.lang.String
### setLabel(String value) {#setLabel-java.lang.String-}
```
public abstract void setLabel(String value)
```


닫힌 자막의 레이블을 반환하거나 설정합니다. 읽기/쓰기 String.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | java.lang.String |  |

### getBinaryData() {#getBinaryData--}
```
public abstract byte[] getBinaryData()
```


닫힌 자막의 바이너리 데이터를 반환합니다. 읽기 전용 byte[].

**반환값:**
byte[]
### getDataAsString() {#getDataAsString--}
```
public abstract String getDataAsString()
```


닫힌 자막 데이터를 UTF-8 인코딩 문자열로 반환합니다. 읽기 전용 String.

**반환값:**
java.lang.String