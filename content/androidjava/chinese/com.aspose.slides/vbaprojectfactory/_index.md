---
title: VbaProjectFactory
second_title: Aspose.Slides for Android via Java API 参考
description: 允许通过 COM 接口创建 VBA 项目
type: docs
url: /zh/com.aspose.slides/vbaprojectfactory/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.slides.IVbaProjectFactory](../../com.aspose.slides/ivbaprojectfactory)
```
public class VbaProjectFactory implements IVbaProjectFactory
```

允许通过 COM 接口创建 VBA 项目

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [VbaProjectFactory()](#VbaProjectFactory--) |  |

## 方法

| 方法 | 描述 |
| --- | --- |
| [getInstance()](#getInstance--) | VBA 项目工厂的静态实例。 |
| [createVbaProject()](#createVbaProject--) | 创建新的 VBA 项目。 |
| [readVbaProject(byte[] data)](#readVbaProject-byte---) | 从 OLE 容器读取 VBA 项目。 |

### VbaProjectFactory() {#VbaProjectFactory--}
```
public VbaProjectFactory()
```

### getInstance() {#getInstance--}
```
public static VbaProjectFactory getInstance()
```

VBA 项目工厂的静态实例。只读 [VbaProjectFactory](../../com.aspose.slides/vbaprojectfactory)。

**返回值：**
[VbaProjectFactory](../../com.aspose.slides/vbaprojectfactory)

### createVbaProject() {#createVbaProject--}
```
public final IVbaProject createVbaProject()
```

创建新的 VBA 项目。

**返回值：**
[IVbaProject](../../com.aspose.slides/ivbaproject) - 新 VBA 项目

### readVbaProject(byte[] data) {#readVbaProject-byte---}
```
public final IVbaProject readVbaProject(byte[] data)
```

从 OLE 容器读取 VBA 项目。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| data | byte[] |  |

**返回值：**
[IVbaProject](../../com.aspose.slides/ivbaproject) - 读取的 VBA 项目