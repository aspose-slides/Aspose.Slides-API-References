---
title: IVbaReferenceFactory
second_title: Aspose.Slides for Android via Java API Reference
description: Allows to create VBA project references via COM interface
type: docs
url: /ko/com.aspose.slides/ivbareferencefactory/
---```
public interface IVbaReferenceFactory
```

COM 인터페이스를 통해 VBA 프로젝트 참조를 생성할 수 있습니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [createOleTypeLibReference(String name, String libid)](#createOleTypeLibReference-java.lang.String-java.lang.String-) | 새 OLE Automation 타입 라이브러리 참조를 생성합니다. |
### createOleTypeLibReference(String name, String libid) {#createOleTypeLibReference-java.lang.String-java.lang.String-}
```
public abstract IVbaReferenceOleTypeLib createOleTypeLibReference(String name, String libid)
```


새 OLE Automation 타입 라이브러리 참조를 생성합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| name | java.lang.String | VBA 프로젝트 참조의 이름 String |
| libid | java.lang.String | Automation 타입 라이브러리 식별자 String |

**반환값:**
[IVbaReferenceOleTypeLib](../../com.aspose.slides/ivbareferenceoletypelib) - 새 OLE Automation 타입 라이브러리 참조 [IVbaReferenceOleTypeLib](../../com.aspose.slides/ivbareferenceoletypelib)