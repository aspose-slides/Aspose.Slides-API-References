---
title: VbaReferenceFactory
second_title: Aspose.Slides for Java API 레퍼런스
description: COM 인터페이스를 통해 VBA 프로젝트 참조를 생성할 수 있습니다.
type: docs
url: /ko/com.aspose.slides/vbareferencefactory/
---
**상속:**
java.lang.Object

**구현된 모든 인터페이스:**
[com.aspose.slides.IVbaReferenceFactory](../../com.aspose.slides/ivbareferencefactory)
```
public class VbaReferenceFactory implements IVbaReferenceFactory
```

COM 인터페이스를 통해 VBA 프로젝트 참조를 생성할 수 있습니다.
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [VbaReferenceFactory()](#VbaReferenceFactory--) |  |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getInstance()](#getInstance--) | VBA 프로젝트 참조 팩토리 정적 인스턴스. |
| [createOleTypeLibReference(String name, String libid)](#createOleTypeLibReference-java.lang.String-java.lang.String-) | 새 OLE Automation 타입 라이브러리 참조를 생성합니다. |
### VbaReferenceFactory() {#VbaReferenceFactory--}
```
public VbaReferenceFactory()
```


### getInstance() {#getInstance--}
```
public static VbaReferenceFactory getInstance()
```


VBA 프로젝트 참조 팩토리 정적 인스턴스. 읽기 전용 [VbaReferenceFactory](../../com.aspose.slides/vbareferencefactory).

**반환값:**
[VbaReferenceFactory](../../com.aspose.slides/vbareferencefactory)
### createOleTypeLibReference(String name, String libid) {#createOleTypeLibReference-java.lang.String-java.lang.String-}
```
public final IVbaReferenceOleTypeLib createOleTypeLibReference(String name, String libid)
```


새 OLE Automation 타입 라이브러리 참조를 생성합니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| name | java.lang.String |  |
| libid | java.lang.String |  |

**반환값:**
[IVbaReferenceOleTypeLib](../../com.aspose.slides/ivbareferenceoletypelib) - 새 OLE Automation 타입 라이브러리 참조