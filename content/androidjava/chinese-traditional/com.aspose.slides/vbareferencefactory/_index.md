---
title: VbaReferenceFactory
second_title: Aspose.Slides for Android 透過 Java API 參考
description: 允許透過 COM 介面建立 VBA 專案參考
type: docs
url: /zh-hant/com.aspose.slides/vbareferencefactory/
---
**繼承：**
java.lang.Object

**已實作的介面：**
[com.aspose.slides.IVbaReferenceFactory](../../com.aspose.slides/ivbareferencefactory)
```
public class VbaReferenceFactory implements IVbaReferenceFactory
```

允許透過 COM 介面建立 VBA 專案參考
## 建構函式

| 建構函式 | 說明 |
| --- | --- |
| [VbaReferenceFactory()](#VbaReferenceFactory--) |  |
## 方法

| 方法 | 說明 |
| --- | --- |
| [getInstance()](#getInstance--) | VBA 專案參考工廠的靜態實例。 |
| [createOleTypeLibReference(String name, String libid)](#createOleTypeLibReference-java.lang.String-java.lang.String-) | 建立新的 OLE Automation 類型庫參考。 |
### VbaReferenceFactory() {#VbaReferenceFactory--}
```
public VbaReferenceFactory()
```

### getInstance() {#getInstance--}
```
public static VbaReferenceFactory getInstance()
```

VBA 專案參考工廠的靜態實例。唯讀 [VbaReferenceFactory](../../com.aspose.slides/vbareferencefactory)。

**傳回：**
[VbaReferenceFactory](../../com.aspose.slides/vbareferencefactory)
### createOleTypeLibReference(String name, String libid) {#createOleTypeLibReference-java.lang.String-java.lang.String-}
```
public final IVbaReferenceOleTypeLib createOleTypeLibReference(String name, String libid)
```

建立新的 OLE Automation 類型庫參考。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| name | java.lang.String |  |
| libid | java.lang.String |  |

**傳回：**
[IVbaReferenceOleTypeLib](../../com.aspose.slides/ivbareferenceoletypelib) - 新的 OLE Automation 類型庫參考