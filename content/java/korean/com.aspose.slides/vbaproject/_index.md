---
title: VbaProject
second_title: Aspose.Slides for Java API 레퍼런스
description: 프레젠테이션 매크로가 포함된 VBA 프로젝트를 나타냅니다.
type: docs
url: /ko/com.aspose.slides/vbaproject/
---
**상속:**
java.lang.Object

**구현된 모든 인터페이스:**
[com.aspose.slides.IVbaProject](../../com.aspose.slides/ivbaproject)
```
public final class VbaProject implements IVbaProject
```

프레젠테이션 매크로가 포함된 VBA 프로젝트를 나타냅니다.
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [VbaProject()](#VbaProject--) | 이 생성자는 새 VBA 프로젝트를 처음부터 만듭니다. |
| [VbaProject(byte[] data)](#VbaProject-byte---) | 이 생성자는 OLE 컨테이너의 이진 표현에서 VBA 프로젝트를 로드합니다. |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getName()](#getName--) | VBA 프로젝트의 이름을 반환합니다. |
| [getModules()](#getModules--) | VBA 프로젝트에 포함된 모든 모듈의 목록을 반환합니다. |
| [getReferences()](#getReferences--) | VBA 프로젝트에 포함된 모든 참조의 목록을 반환합니다. |
| [toBinary()](#toBinary--) | VBA 프로젝트를 OLE 컨테이너로서 이진 표현을 반환합니다. |
| [isPasswordProtected()](#isPasswordProtected--) | VBAProject가 프로젝트 속성을 보기 위해 비밀번호로 보호되는지 여부를 나타냅니다. |
### VbaProject() {#VbaProject--}
```
public VbaProject()
```

이 생성자는 새 VBA 프로젝트를 처음부터 만듭니다. 프로젝트는 1252 Windows Latin 1 (ANSI) 코드 페이지에 생성됩니다.

### VbaProject(byte[] data) {#VbaProject-byte---}
```
public VbaProject(byte[] data)
```

이 생성자는 OLE 컨테이너의 이진 표현에서 VBA 프로젝트를 로드합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| data | byte[] |  |
### getName() {#getName--}
```
public final String getName()
```

VBA 프로젝트의 이름을 반환합니다. 읽기 전용 문자열.

**반환값:**
java.lang.String
### getModules() {#getModules--}
```
public final IVbaModuleCollection getModules()
```

VBA 프로젝트에 포함된 모든 모듈의 목록을 반환합니다. 읽기 전용 [IVbaModuleCollection](../../com.aspose.slides/ivbamodulecollection).

**반환값:**
[IVbaModuleCollection](../../com.aspose.slides/ivbamodulecollection)
### getReferences() {#getReferences--}
```
public final IVbaReferenceCollection getReferences()
```

VBA 프로젝트에 포함된 모든 참조의 목록을 반환합니다. 읽기 전용 [IVbaReferenceCollection](../../com.aspose.slides/ivbareferencecollection).

**반환값:**
[IVbaReferenceCollection](../../com.aspose.slides/ivbareferencecollection)
### toBinary() {#toBinary--}
```
public final byte[] toBinary()
```

VBA 프로젝트를 OLE 컨테이너로서 이진 표현을 반환합니다.

**반환값:**
byte[] - OLE 컨테이너로서 VBA 프로젝트의 이진 표현
### isPasswordProtected() {#isPasswordProtected--}
```
public final boolean isPasswordProtected()
```

VBAProject가 프로젝트 속성을 보기 위해 비밀번호로 보호되는지 여부를 나타냅니다. 읽기 전용 부울.

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptm");
>  try {
>      if (presentation.getVbaProject().isPasswordProtected())
>          System.out.println("The VBAProject '" + presentation.getVbaProject().getName() +
>              "' is protected by password to view project properties.");
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**반환값:**
boolean