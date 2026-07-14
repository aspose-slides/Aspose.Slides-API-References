---
title: CustomData
second_title: Java API 레퍼런스를 통한 Android용 Aspose.Slides
description: 사용자 정의 데이터를 위한 컨테이너를 나타냅니다.
type: docs
url: /ko/com.aspose.slides/customdata/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.slides.ICustomData](../../com.aspose.slides/icustomdata), com.aspose.slides.IDOMObject
```
public class CustomData implements ICustomData, IDOMObject
```

사용자 정의 데이터 컨테이너를 나타냅니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getTags()](#getTags--) | Customer Data Tags 컬렉션을 반환합니다. |
| [getCustomXmlParts()](#getCustomXmlParts--) | custom xml parts 컬렉션을 반환합니다. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
### getTags() {#getTags--}
```
public final ITagCollection getTags()
```


Customer Data Tags 컬렉션을 반환합니다. 읽기 전용 [ITagCollection](../../com.aspose.slides/itagcollection).

**반환값:**
[ITagCollection](../../com.aspose.slides/itagcollection)
### getCustomXmlParts() {#getCustomXmlParts--}
```
public final ICustomXmlPartCollection getCustomXmlParts()
```


custom xml parts 컬렉션을 반환합니다. 읽기 전용 [ICustomXmlPartCollection](../../com.aspose.slides/icustomxmlpartcollection).

**반환값:**
[ICustomXmlPartCollection](../../com.aspose.slides/icustomxmlpartcollection)
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```


Parent_Immediate 객체를 반환합니다. 읽기 전용 IDOMObject.

**반환값:**
com.aspose.slides.IDOMObject