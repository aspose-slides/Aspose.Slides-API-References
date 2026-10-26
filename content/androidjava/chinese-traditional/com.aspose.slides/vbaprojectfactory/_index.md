---
title: VbaProjectFactory
second_title: Aspose.Slides for Android 之 Java API 參考
description: 允許透過 COM 介面建立 VBA 專案
type: docs
url: /zh-hant/com.aspose.slides/vbaprojectfactory/
---
**繼承關係:**
java.lang.Object

**所有已實作介面:**
[com.aspose.slides.IVbaProjectFactory](../../com.aspose.slides/ivbaprojectfactory)
```
public class VbaProjectFactory implements IVbaProjectFactory
```

允許透過 COM 介面建立 VBA 專案
## 建構子

| 建構子 | 說明 |
| --- | --- |
| [VbaProjectFactory()](#VbaProjectFactory--) |  |
## 方法

| 方法 | 說明 |
| --- | --- |
| [getInstance()](#getInstance--) | VBA 專案工廠靜態實例。 |
| [createVbaProject()](#createVbaProject--) | 建立新的 VBA 專案。 |
| [readVbaProject(byte[] data)](#readVbaProject-byte---) | 從 OLE 容器讀取 VBA 專案。 |
### VbaProjectFactory() {#VbaProjectFactory--}
```
public VbaProjectFactory()
```


### getInstance() {#getInstance--}
```
public static VbaProjectFactory getInstance()
```


VBA 專案工廠靜態實例。唯讀 [VbaProjectFactory](../../com.aspose.slides/vbaprojectfactory)。

**回傳值:**
[VbaProjectFactory](../../com.aspose.slides/vbaprojectfactory)
### createVbaProject() {#createVbaProject--}
```
public final IVbaProject createVbaProject()
```


建立新的 VBA 專案。

**回傳值:**
[IVbaProject](../../com.aspose.slides/ivbaproject) - 新的 VBA project
### readVbaProject(byte[] data) {#readVbaProject-byte---}
```
public final IVbaProject readVbaProject(byte[] data)
```


從 OLE 容器讀取 VBA 專案。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| data | byte[] |  |

**回傳值:**
[IVbaProject](../../com.aspose.slides/ivbaproject) - 讀取 VBA project