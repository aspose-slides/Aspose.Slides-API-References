---
title: SupportsType()
second_title: Aspose.Slides for C++ API 參考
description: 使解析器能返回除 Stream 之外的類型。
type: docs
weight: 40
url: /zh-hant/system.xml/xmlresolver/supportstype/
---
## XmlResolver::SupportsType(SharedPtr\<Uri\>, const TypeInfo\&) 方法

啟用解析器返回除 Stream 之外的類型。

```cpp
virtual bool System::Xml::XmlResolver::SupportsType(SharedPtr<Uri> absoluteUri, const TypeInfo &type)
```

### 參數

| 參數 | 型別 | 說明 |
| --- | --- | --- |
| absoluteUri | [SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | URI。 |
| type | const [TypeInfo](../../../system/typeinfo/)\& | 要返回的類型。 |

### 回傳值

**true** if the **type** is supported; otherwise, **false**.

## 另請參閱

* 型別定義 [SharedPtr](../../../system/sharedptr/)
* 類別 [Uri](../../../system/uri/)
* 類別 [TypeInfo](../../../system/typeinfo/)
* 類別 [XmlResolver](../)
* 命名空間 [System::Xml](../../)
* 函式庫 [Aspose.Slides](../../../)