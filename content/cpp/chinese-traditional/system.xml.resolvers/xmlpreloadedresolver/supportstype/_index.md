---
title: SupportsType()
second_title: Aspose.Slides for C++ API 參考
description: 判斷解析器是否支援除 Stream 之外的其他類型。
type: docs
weight: 66
url: /zh-hant/system.xml.resolvers/xmlpreloadedresolver/supportstype/
---
## XmlPreloadedResolver::SupportsType(SharedPtr\<Uri\>, const TypeInfo\&) method


判斷解析器是否支援除 Stream 之外的其他類型。

```cpp
bool System::Xml::Resolvers::XmlPreloadedResolver::SupportsType(SharedPtr<Uri> absoluteUri, const TypeInfo &type) override
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| absoluteUri | [SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | 要檢查的絕對 URI。 |
| type | const [TypeInfo](../../../system/typeinfo/)\& | 要返回的類型。 |

### 回傳值

**true** 如果支援該類型則為 **true**；否則為 **false**。

## 另請參閱

* 型別定義 [SharedPtr](../../../system/sharedptr/)
* 類別 [Uri](../../../system/uri/)
* 類別 [TypeInfo](../../../system/typeinfo/)
* 類別 [XmlPreloadedResolver](../)
* 命名空間 [System::Xml::Resolvers](../../)
* 函式庫 [Aspose.Slides](../../../)