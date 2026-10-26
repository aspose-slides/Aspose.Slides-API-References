---
title: LookupPrefix()
second_title: Aspose.Slides for C++ API 參考文件
description: 當在衍生類別中覆寫時，會回傳在目前命名空間範圍內為該命名空間 URI 定義的最接近前置詞。
type: docs
weight: 352
url: /zh-hant/system.xml/xmlwriter/lookupprefix/
---
## XmlWriter::LookupPrefix(String) 方法


當在衍生類別中覆寫時，會回傳在目前命名空間範圍內為該命名空間 URI 定義的最接近前置詞。

```cpp
virtual String System::Xml::XmlWriter::LookupPrefix(String ns)=0
```


### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| ns | [String](../../../system/string/) | 要尋找其前置詞的命名空間 URI。 |

### 返回值

符合的前置詞，若在目前範圍中找不到匹配的命名空間 URI，則為 **nullptr**。

## 另見

* 類別 [String](../../../system/string/)
* 類別 [XmlWriter](../)
* 命名空間 [System::Xml](../../)
* 函式庫 [Aspose.Slides](../../../)