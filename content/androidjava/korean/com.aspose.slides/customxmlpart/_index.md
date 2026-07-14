---
title: CustomXmlPart
second_title: Java API 레퍼런스를 통한 Android용 Aspose.Slides
description: 사용자 정의 XML 파트를 나타냅니다.
type: docs
url: /ko/com.aspose.slides/customxmlpart/
---
**상속:**
java.lang.Object

**구현된 모든 인터페이스:**
[com.aspose.slides.ICustomXmlPart](../../com.aspose.slides/icustomxmlpart)
```
public class CustomXmlPart implements ICustomXmlPart
```

사용자 정의 XML 파트를 나타냅니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getXmlData()](#getXmlData--) | XML 데이터를 반환하거나 설정합니다. |
| [setXmlData(byte[] value)](#setXmlData-byte---) | XML 데이터를 반환하거나 설정합니다. |
| [getXmlAsString()](#getXmlAsString--) | XML 데이터를 UTF-8 문자열로 반환하거나 설정합니다. |
| [setXmlAsString(String value)](#setXmlAsString-java.lang.String-) | XML 데이터를 UTF-8 문자열로 반환하거나 설정합니다. |
| [getItemId()](#getItemId--) | Office Open XML 문서 내에서 단일 사용자 정의 XML 파트를 고유하게 식별하는 전역 고유 식별자(GUID)를 지정합니다. |
| [setItemId(UUID value)](#setItemId-java.util.UUID-) | Office Open XML 문서 내에서 단일 사용자 정의 XML 파트를 고유하게 식별하는 전역 고유 식별자(GUID)를 지정합니다. |
| [getNamespaceSchemas()](#getNamespaceSchemas--) | 사용자 정의 XML 파트와 연결된 컬렉션 XML 스키마를 반환합니다. |
| [remove()](#remove--) | 프레젠테이션에서 사용자 정의 XML 파트를 제거합니다. |

### getXmlData() {#getXmlData--}
```
public final byte[] getXmlData()
```

XML 데이터를 반환하거나 설정합니다. 읽기/쓰기 byte[].

**반환:**
byte[]

### setXmlData(byte[] value) {#setXmlData-byte---}
```
public final void setXmlData(byte[] value)
```

XML 데이터를 반환하거나 설정합니다. 읽기/쓰기 byte[].

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | byte[] |  |

### getXmlAsString() {#getXmlAsString--}
```
public final String getXmlAsString()
```

XML 데이터를 UTF-8 문자열로 반환하거나 설정합니다. 읽기/쓰기 String.

**반환:**
java.lang.String

### setXmlAsString(String value) {#setXmlAsString-java.lang.String-}
```
public final void setXmlAsString(String value)
```

XML 데이터를 UTF-8 문자열로 반환하거나 설정합니다. 읽기/쓰기 String.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | java.lang.String |  |

### getItemId() {#getItemId--}
```
public final UUID getItemId()
```

Office Open XML 문서 내에서 단일 사용자 정의 XML 파트를 고유하게 식별하는 전역 고유 식별자(GUID)를 지정합니다. 읽기 전용 java.util.UUID.

**반환:**
java.util.UUID

### setItemId(UUID value) {#setItemId-java.util.UUID-}
```
public final void setItemId(UUID value)
```

Office Open XML 문서 내에서 단일 사용자 정의 XML 파트를 고유하게 식별하는 전역 고유 식별자(GUID)를 지정합니다. 읽기 전용 java.util.UUID.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | java.util.UUID |  |

### getNamespaceSchemas() {#getNamespaceSchemas--}
```
public final String[] getNamespaceSchemas()
```

사용자 정의 XML 파트와 연결된 컬렉션 XML 스키마를 반환합니다. 읽기 전용 String[].

**반환:**
java.lang.String[]

### remove() {#remove--}
```
public final void remove()
```

프레젠테이션에서 사용자 정의 XML 파트를 제거합니다.