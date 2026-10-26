---
title: IVbaProjectFactory
second_title: Aspose.Slides for Java API Reference
description: Allows to create VBA project via COM interface
type: docs
url: /ko/com.aspose.slides/ivbaprojectfactory/
---```
public interface IVbaProjectFactory
```

VBA 프로젝트를 COM 인터페이스를 통해 생성합니다.
## 메서드

| Method | Description |
| --- | --- |
| [createVbaProject()](#createVbaProject--) | 새 VBA 프로젝트를 생성합니다. |
| [readVbaProject(byte[] data)](#readVbaProject-byte---) | OLE 컨테이너에서 VBA 프로젝트를 읽습니다. |
### createVbaProject() {#createVbaProject--}
```
public abstract IVbaProject createVbaProject()
```

새 VBA 프로젝트를 생성합니다.

**반환값:**
[IVbaProject](../../com.aspose.slides/ivbaproject) - 새 VBA 프로젝트
### readVbaProject(byte[] data) {#readVbaProject-byte---}
```
public abstract IVbaProject readVbaProject(byte[] data)
```

OLE 컨테이너에서 VBA 프로젝트를 읽습니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| data | byte[] | Ole 데이터 byte[] |

**반환값:**
[IVbaProject](../../com.aspose.slides/ivbaproject) - 읽은 VBA 프로젝트