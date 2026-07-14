---
title: VbaProjectFactory
second_title: Java API 레퍼런스를 통한 Android용 Aspose.Slides
description: COM 인터페이스를 통해 VBA 프로젝트를 생성할 수 있습니다
type: docs
url: /ko/com.aspose.slides/vbaprojectfactory/
---
**상속:**
java.lang.Object

**구현된 모든 인터페이스:**
[com.aspose.slides.IVbaProjectFactory](../../com.aspose.slides/ivbaprojectfactory)
```
public class VbaProjectFactory implements IVbaProjectFactory
```

COM 인터페이스를 통해 VBA 프로젝트를 생성할 수 있습니다
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [VbaProjectFactory()](#VbaProjectFactory--) |  |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getInstance()](#getInstance--) | VBA 프로젝트 팩터리 정적 인스턴스. |
| [createVbaProject()](#createVbaProject--) | 새 VBA 프로젝트를 생성합니다. |
| [readVbaProject(byte[] data)](#readVbaProject-byte---) | OLE 컨테이너에서 VBA 프로젝트를 읽습니다. |
### VbaProjectFactory() {#VbaProjectFactory--}
```
public VbaProjectFactory()
```


### getInstance() {#getInstance--}
```
public static VbaProjectFactory getInstance()
```


VBA 프로젝트 팩터리 정적 인스턴스. 읽기 전용 [VbaProjectFactory](../../com.aspose.slides/vbaprojectfactory).

**반환:**
[VbaProjectFactory](../../com.aspose.slides/vbaprojectfactory)
### createVbaProject() {#createVbaProject--}
```
public final IVbaProject createVbaProject()
```


새 VBA 프로젝트를 생성합니다.

**반환:**
[IVbaProject](../../com.aspose.slides/ivbaproject) - 새 VBA 프로젝트
### readVbaProject(byte[] data) {#readVbaProject-byte---}
```
public final IVbaProject readVbaProject(byte[] data)
```


OLE 컨테이너에서 VBA 프로젝트를 읽습니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| data | byte[] |  |

**반환:**
[IVbaProject](../../com.aspose.slides/ivbaproject) - 읽은 VBA 프로젝트