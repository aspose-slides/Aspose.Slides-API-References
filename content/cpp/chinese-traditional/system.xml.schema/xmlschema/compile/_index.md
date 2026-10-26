---
title: Compile()
second_title: Aspose.Slides for C++ API 參考
description: 將 XML SchemaObject Model (SOM) 編譯為驗證用的綱要資訊。用於檢查程式化建構的 SOM 的語法與語意結構。語意驗證檢查在編譯期間執行。
type: docs
weight: 352
url: /zh-hant/system.xml.schema/xmlschema/compile/
---
## XmlSchema::Compile(ValidationEventHandler) 方法

將 XML [Schema](../../)[Object](../../../system/object/) 模型 (SOM) 編譯為驗證用的綱要資訊。用於檢查程式化建構的 SOM 的語法與語意結構。語意驗證檢查在編譯期間執行。

```cpp
void System::Xml::Schema::XmlSchema::Compile(ValidationEventHandler validationEventHandler)
```

### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| validationEventHandler | [ValidationEventHandler](../../validationeventhandler/) | 接收有關 XML [Schema](../../) 驗證錯誤資訊的驗證事件處理程序。 |

## XmlSchema::Compile(ValidationEventHandler, const SharedPtr\<XmlResolver\>\&) 方法

將 XML [Schema](../../)[Object](../../../system/object/) 模型 (SOM) 編譯為驗證用的綱要資訊。用於檢查程式化建構的 SOM 的語法與語意結構。語意驗證檢查在編譯期間執行。

```cpp
void System::Xml::Schema::XmlSchema::Compile(ValidationEventHandler validationEventHandler, const SharedPtr<XmlResolver> &resolver)
```

### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| validationEventHandler | [ValidationEventHandler](../../validationeventhandler/) | 接收有關 XML [Schema](../../) 驗證錯誤資訊的驗證事件處理程序。 |
| resolver | const [SharedPtr](../../../system/sharedptr/)\<[XmlResolver](../../../system.xml/xmlresolver/)\>\& | 用於解析 **include** 和 **import** 元素中引用之命名空間的 [XmlResolver](../../../system.xml/xmlresolver/)。 |

## 另請參閱

* 型別別名 [ValidationEventHandler](../../validationeventhandler/)
* 型別別名 [SharedPtr](../../../system/sharedptr/)
* 類別 [XmlSchema](../)
* 類別 [XmlResolver](../../../system.xml/xmlresolver/)
* 命名空間 [System::Xml::Schema](../../)
* 程式庫 [Aspose.Slides](../../../)