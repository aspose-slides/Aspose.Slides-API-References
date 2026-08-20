---
title: IVbaProject
second_title: Aspose.Slides for Java API Reference
description: VBA 매크로가 포함된 프레젠테이션 프로젝트를 나타냅니다.
type: docs
url: /ko/com.aspose.slides/ivbaproject/
---```
public interface IVbaProject
```

VBA 매크로가 포함된 프레젠테이션 프로젝트를 나타냅니다.
## 메서드

| Method | Description |
| --- | --- |
| [getName()](#getName--) | VBA 프로젝트의 이름을 반환합니다. |
| [getModules()](#getModules--) | VBA 프로젝트에 포함된 모든 모듈의 목록을 반환합니다. |
| [getReferences()](#getReferences--) | VBA 프로젝트에 포함된 모든 참조의 목록을 반환합니다. |
| [toBinary()](#toBinary--) | VBA 프로젝트의 이진 표현을 OLE 컨테이너로 반환합니다. |
| [isPasswordProtected()](#isPasswordProtected--) | VBAProject가 프로젝트 속성을 보기 위해 암호로 보호되는지 여부를 나타냅니다. |
### getName() {#getName--}
```
public abstract String getName()
```

VBA 프로젝트의 이름을 반환합니다. 읽기 전용 String.

**Returns:**
java.lang.String
### getModules() {#getModules--}
```
public abstract IVbaModuleCollection getModules()
```

VBA 프로젝트에 포함된 모든 모듈의 목록을 반환합니다. 읽기 전용 [IVbaModuleCollection](../../com.aspose.slides/ivbamodulecollection).

**Returns:**
[IVbaModuleCollection](../../com.aspose.slides/ivbamodulecollection)
### getReferences() {#getReferences--}
```
public abstract IVbaReferenceCollection getReferences()
```

VBA 프로젝트에 포함된 모든 참조의 목록을 반환합니다. 읽기 전용 [IVbaReferenceCollection](../../com.aspose.slides/ivbareferencecollection).

**Returns:**
[IVbaReferenceCollection](../../com.aspose.slides/ivbareferencecollection)
### toBinary() {#toBinary--}
```
public abstract byte[] toBinary()
```

VBA 프로젝트의 이진 표현을 OLE 컨테이너로 반환합니다. 읽기 전용 byte[].

**Returns:**
byte[] - Binary representation of the VBA project as OLE container
### isPasswordProtected() {#isPasswordProtected--}
```
public abstract boolean isPasswordProtected()
```

VBAProject가 프로젝트 속성을 보기 위해 암호로 보호되는지 여부를 나타냅니다. 읽기 전용 boolean.

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


**Returns:**
boolean