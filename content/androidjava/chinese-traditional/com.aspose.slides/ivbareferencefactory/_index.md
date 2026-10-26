---
title: IVbaReferenceFactory
second_title: Aspose.Slides for Android 透過 Java API 參考
description: 允許透過 COM 介面建立 VBA 專案參考
type: docs
url: /zh-hant/com.aspose.slides/ivbareferencefactory/
---```
public interface IVbaReferenceFactory
```

允許透過 COM 介面建立 VBA 專案參考
## 方法

| 方法 | 描述 |
| --- | --- |
| [createOleTypeLibReference(String name, String libid)](#createOleTypeLibReference-java.lang.String-java.lang.String-) | 建立新的 OLE Automation type library 參考。 |
### createOleTypeLibReference(String name, String libid) {#createOleTypeLibReference-java.lang.String-java.lang.String-}
```
public abstract IVbaReferenceOleTypeLib createOleTypeLibReference(String name, String libid)
```

建立新的 OLE Automation type library 參考。

**參數:**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| name | java.lang.String | VBA 專案參考的名稱 String |
| libid | java.lang.String | Automation type library 的識別碼 String |

**回傳值:**
[IVbaReferenceOleTypeLib](../../com.aspose.slides/ivbareferenceoletypelib) - 新的 OLE Automation type library 參考 [IVbaReferenceOleTypeLib](../../com.aspose.slides/ivbareferenceoletypelib)