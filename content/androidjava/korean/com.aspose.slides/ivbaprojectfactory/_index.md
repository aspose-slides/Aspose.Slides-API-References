---
title: IVbaProjectFactory
second_title: Aspose.Slides for Android via Java API 레퍼런스
description: COM 인터페이스를 통해 VBA 프로젝트를 생성할 수 있습니다
type: docs
url: /ko/com.aspose.slides/ivbaprojectfactory/
---```
public interface IVbaProjectFactory
```

COM 인터페이스를 통해 VBA 프로젝트를 생성할 수 있습니다
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [createVbaProject()](#createVbaProject--) | Creates new VBA project. |
| [readVbaProject(byte[] data)](#readVbaProject-byte---) | Reads VBA project from OLE container. |
### createVbaProject() {#createVbaProject--}
```
public abstract IVbaProject createVbaProject()
```


새 VBA 프로젝트를 생성합니다.

**반환:**
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

**반환:**
[IVbaProject](../../com.aspose.slides/ivbaproject) - 읽은 VBA 프로젝트