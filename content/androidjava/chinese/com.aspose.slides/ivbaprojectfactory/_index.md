---
title: IVbaProjectFactory
second_title: Aspose.Slides for Android via Java API Reference
description: 允许通过 COM 接口创建 VBA 项目
type: docs
url: /zh/com.aspose.slides/ivbaprojectfactory/
---```
public interface IVbaProjectFactory
```

允许通过 COM 接口创建 VBA 项目
## 方法

| 方法 | 描述 |
| --- | --- |
| [createVbaProject()](#createVbaProject--) | 创建新的 VBA 项目。 |
| [readVbaProject(byte[] data)](#readVbaProject-byte---) | 从 OLE 容器读取 VBA 项目。 |
### createVbaProject() {#createVbaProject--}
```
public abstract IVbaProject createVbaProject()
```

创建新的 VBA 项目。

**返回值：**
[IVbaProject](../../com.aspose.slides/ivbaproject) - 新的 VBA 项目
### readVbaProject(byte[] data) {#readVbaProject-byte---}
```
public abstract IVbaProject readVbaProject(byte[] data)
```

从 OLE 容器读取 VBA 项目。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| data | byte[] | Ole 数据 byte[] |

**返回值：**
[IVbaProject](../../com.aspose.slides/ivbaproject) - 读取的 VBA 项目