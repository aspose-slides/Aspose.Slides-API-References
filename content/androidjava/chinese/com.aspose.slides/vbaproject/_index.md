---
title: VbaProject
second_title: Aspose.Slides for Android via Java API 参考
description: 表示包含演示宏的 VBA 项目。
type: docs
url: /zh/com.aspose.slides/vbaproject/
---
**继承:**  
java.lang.Object

**所有实现的接口:**  
[com.aspose.slides.IVbaProject](../../com.aspose.slides/ivbaproject)  
```
public final class VbaProject implements IVbaProject
```

表示包含演示宏的 VBA 项目。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [VbaProject()](#VbaProject--) | 此构造函数从头创建新的 VBA 项目。 |
| [VbaProject(byte[] data)](#VbaProject-byte---) | 此构造函数从 OLE 容器的二进制表示加载 VBA 项目。 |

## 方法

| 方法 | 描述 |
| --- | --- |
| [getName()](#getName--) | 返回 VBA 项目的名称。 |
| [getModules()](#getModules--) | 返回 VBA 项目中包含的全部模块列表。 |
| [getReferences()](#getReferences--) | 返回 VBA 项目中包含的全部引用列表。 |
| [toBinary()](#toBinary--) | 返回 VBA 项目的二进制表示（OLE 容器） |
| [isPasswordProtected()](#isPasswordProtected--) | 指示 VBAProject 是否受密码保护以查看项目属性。 |

### VbaProject() {#VbaProject--}
```
public VbaProject()
```

此构造函数从头创建新的 VBA 项目。项目将使用 1252 Windows Latin 1 (ANSI) 代码页创建。

### VbaProject(byte[] data) {#VbaProject-byte---}
```
public VbaProject(byte[] data)
```

此构造函数从 OLE 容器的二进制表示加载 VBA 项目。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| data | byte[] |  |

### getName() {#getName--}
```
public final String getName()
```

返回 VBA 项目的名称。只读 String。

**返回:**
java.lang.String

### getModules() {#getModules--}
```
public final IVbaModuleCollection getModules()
```

返回 VBA 项目中包含的全部模块列表。只读 [IVbaModuleCollection](../../com.aspose.slides/ivbamodulecollection)。

**返回:**
[IVbaModuleCollection](../../com.aspose.slides/ivbamodulecollection)

### getReferences() {#getReferences--}
```
public final IVbaReferenceCollection getReferences()
```

返回 VBA 项目中包含的全部引用列表。只读 [IVbaReferenceCollection](../../com.aspose.slides/ivbareferencecollection)。

**返回:**
[IVbaReferenceCollection](../../com.aspose.slides/ivbareferencecollection)

### toBinary() {#toBinary--}
```
public final byte[] toBinary()
```

返回 VBA 项目的二进制表示（OLE 容器）。

**返回:**
byte[] - VBA 项目的二进制表示（OLE 容器）

### isPasswordProtected() {#isPasswordProtected--}
```
public final boolean isPasswordProtected()
```

指示 VBAProject 是否受密码保护以查看项目属性。只读 boolean 。

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

**返回:**  
boolean