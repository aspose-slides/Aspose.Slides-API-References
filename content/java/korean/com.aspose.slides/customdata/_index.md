---
title: CustomData
second_title: Aspose.Slides for Java API 참조
description: 사용자 정의 데이터의 컨테이너를 나타냅니다.
type: docs
url: /ko/com.aspose.slides/customdata/
---
**상속:**  
java.lang.Object

**구현된 모든 인터페이스:**  
[com.aspose.slides.ICustomData](../../com.aspose.slides/icustomdata), com.aspose.slides.IDOMObject  
```
public class CustomData implements ICustomData, IDOMObject
```

사용자 정의 데이터의 컨테이너를 나타냅니다.

## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getTags()](#getTags--) | Customer Data Tags 컬렉션을 반환합니다. |
| [getCustomXmlParts()](#getCustomXmlParts--) | 사용자 정의 xml 파트 컬렉션을 반환합니다. |
| [getParent_Immediate()](#getParent-Immediate--) |  |

### getTags() {#getTags--}
```
public final ITagCollection getTags()
```

Customer Data Tags 컬렉션을 반환합니다. 읽기 전용 [ITagCollection](../../com.aspose.slides/itagcollection).

**반환:**  
[ITagCollection](../../com.aspose.slides/itagcollection)

### getCustomXmlParts() {#getCustomXmlParts--}
```
public final ICustomXmlPartCollection getCustomXmlParts()
```

custom xml 파트 컬렉션을 반환합니다. 읽기 전용 [ICustomXmlPartCollection](../../com.aspose.slides/icustomxmlpartcollection).

**반환:**  
[ICustomXmlPartCollection](../../com.aspose.slides/icustomxmlpartcollection)

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Parent_Immediate 객체를 반환합니다. 읽기 전용 IDOMObject.

**반환:**  
com.aspose.slides.IDOMObject