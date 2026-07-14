---
title: VbaReferenceFactory
second_title: Java API 참조를 통한 Android용 Aspose.Slides
description: COM 인터페이스를 통해 VBA 프로젝트 참조를 만들 수 있습니다.
type: docs
url: /ko/com.aspose.slides/vbareferencefactory/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.slides.IVbaReferenceFactory](../../com.aspose.slides/ivbareferencefactory)
```
public class VbaReferenceFactory implements IVbaReferenceFactory
```

COM 인터페이스를 통해 VBA 프로젝트 참조를 만들 수 있습니다.
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [VbaReferenceFactory()](#VbaReferenceFactory--) |  |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getInstance()](#getInstance--) | VBA 프로젝트 참조 팩토리 정적 인스턴스. |
| [createOleTypeLibReference(String name, String libid)](#createOleTypeLibReference-java.lang.String-java.lang.String-) | 새로운 OLE Automation 타입 라이브러리 참조를 생성합니다. |
### VbaReferenceFactory() {#VbaReferenceFactory--}
```
public VbaReferenceFactory()
```


### getInstance() {#getInstance--}
```
public static VbaReferenceFactory getInstance()
```


VBA 프로젝트 참조 팩토리 정적 인스턴스. 읽기 전용 [VbaReferenceFactory](../../com.aspose.slides/vbareferencefactory).

**반환:**
[VbaReferenceFactory](../../com.aspose.slides/vbareferencefactory)
### createOleTypeLibReference(String name, String libid) {#createOleTypeLibReference-java.lang.String-java.lang.String-}
```
public final IVbaReferenceOleTypeLib createOleTypeLibReference(String name, String libid)
```


새로운 OLE Automation 타입 라이브러리 참조를 생성합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| name | java.lang.String |  |
| libid | java.lang.String |  |

**반환:**
[IVbaReferenceOleTypeLib](../../com.aspose.slides/ivbareferenceoletypelib) - 새로운 OLE Automation 타입 라이브러리 참조