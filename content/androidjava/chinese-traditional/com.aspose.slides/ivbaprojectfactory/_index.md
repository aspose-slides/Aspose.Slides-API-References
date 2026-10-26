---
title: IVbaProjectFactory
second_title: Aspose.Slides for Android via Java API Reference
description: Allows to create VBA project via COM interface
type: docs
url: /zh-hant/com.aspose.slides/ivbaprojectfactory/
---```
public interface IVbaProjectFactory
```

允許透過 COM 介面建立 VBA 專案
## 方法

| 方法 | 描述 |
| --- | --- |
| [createVbaProject()](#createVbaProject--) | 建立新的 VBA 專案。 |
| [readVbaProject(byte[] data)](#readVbaProject-byte---) | 從 OLE 容器讀取 VBA 專案。 |
### createVbaProject() {#createVbaProject--}
```
public abstract IVbaProject createVbaProject()
```


建立新的 VBA 專案。

**返回：**
[IVbaProject](../../com.aspose.slides/ivbaproject) - 新 VBA 專案
### readVbaProject(byte[] data) {#readVbaProject-byte---}
```
public abstract IVbaProject readVbaProject(byte[] data)
```


從 OLE 容器讀取 VBA 專案。

**參數：**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| data | byte[] | Ole 資料 byte[] |

**返回：**
[IVbaProject](../../com.aspose.slides/ivbaproject) - 讀取的 VBA 專案