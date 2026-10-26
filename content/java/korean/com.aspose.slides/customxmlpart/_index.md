---
title: CustomXmlPart
second_title: Aspose.Slides for Java API 레퍼런스
description: 사용자 지정 XML 파트를 나타냅니다.
type: docs
url: /ko/com.aspose.slides/customxmlpart/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.slides.ICustomXmlPart](../../com.aspose.slides/icustomxmlpart)
```
public class CustomXmlPart implements ICustomXmlPart
```

사용자 지정 XML 파트를 나타냅니다.
## Methods

| Method | Description |
| --- | --- |
| [getXmlData()](#getXmlData--) | xml 데이터를 반환하거나 설정합니다. |
| [setXmlData(byte[] value)](#setXmlData-byte---) | xml 데이터를 반환하거나 설정합니다. |
| [getXmlAsString()](#getXmlAsString--) | UTF-8 문자열로 xml 데이터를 반환하거나 설정합니다. |
| [setXmlAsString(String value)](#setXmlAsString-java.lang.String-) | UTF-8 문자열로 xml 데이터를 반환하거나 설정합니다. |
| [getItemId()](#getItemId--) | Office Open XML 문서 내에서 단일 사용자 지정 XML 파트를 고유하게 식별하는 전역 고유 식별자(GUID)를 지정합니다. |
| [setItemId(UUID value)](#setItemId-java.util.UUID-) | Office Open XML 문서 내에서 단일 사용자 지정 XML 파트를 고유하게 식별하는 전역 고유 식별자(GUID)를 지정합니다. |
| [getNamespaceSchemas()](#getNamespaceSchemas--) | 사용자 지정 XML 파트와 연결된 컬렉션 XML 스키마를 반환합니다. |
| [remove()](#remove--) | 프레젠테이션에서 사용자 지정 XML 파트를 제거합니다. |
### getXmlData() {#getXmlData--}
```
public final byte[] getXmlData()
```


xml 데이터를 반환하거나 설정합니다. 읽기/쓰기 byte[].

**Returns:**
byte[]
### setXmlData(byte[] value) {#setXmlData-byte---}
```
public final void setXmlData(byte[] value)
```


xml 데이터를 반환하거나 설정합니다. 읽기/쓰기 byte[].

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte[] |  |

### getXmlAsString() {#getXmlAsString--}
```
public final String getXmlAsString()
```


UTF-8 문자열로 xml 데이터를 반환하거나 설정합니다. 읽기/쓰기 String.

**Returns:**
java.lang.String
### setXmlAsString(String value) {#setXmlAsString-java.lang.String-}
```
public final void setXmlAsString(String value)
```


UTF-8 문자열로 xml 데이터를 반환하거나 설정합니다. 읽기/쓰기 String.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getItemId() {#getItemId--}
```
public final UUID getItemId()
```


Office Open XML 문서 내에서 단일 사용자 지정 XML 파트를 고유하게 식별하는 전역 고유 식별자(GUID)를 지정합니다. 읽기 전용 java.util.UUID.

**Returns:**
java.util.UUID
### setItemId(UUID value) {#setItemId-java.util.UUID-}
```
public final void setItemId(UUID value)
```


Office Open XML 문서 내에서 단일 사용자 지정 XML 파트를 고유하게 식별하는 전역 고유 식별자(GUID)를 지정합니다. 읽기 전용 java.util.UUID.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.util.UUID |  |

### getNamespaceSchemas() {#getNamespaceSchemas--}
```
public final String[] getNamespaceSchemas()
```


사용자 지정 XML 파트와 연결된 컬렉션 XML 스키마를 반환합니다. 읽기 전용 String[].

**Returns:**
java.lang.String[]
### remove() {#remove--}
```
public final void remove()
```


프레젠테이션에서 사용자 지정 XML 파트를 제거합니다.