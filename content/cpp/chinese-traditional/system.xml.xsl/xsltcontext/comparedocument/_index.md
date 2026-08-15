---
title: CompareDocument()
second_title: Aspose.Slides for C++ API 參考
description: 當在衍生類別中被覆寫時，根據 XSLT 處理器載入文件的順序（即 XslTransform 類別），比較兩個文件的基礎統一資源標識符 (URIs)。
type: docs
weight: 53
url: /zh-hant/system.xml.xsl/xsltcontext/comparedocument/
---
## XsltContext::CompareDocument(String, String) 方法

當在衍生類別中被覆寫時，根據 XSLT 處理器載入文件的順序（即 [XslTransform](../../xsltransform/) 類別），比較兩個文件的基礎統一資源標識符 (URIs)。

```cpp
virtual int32_t System::Xml::Xsl::XsltContext::CompareDocument(String baseUri, String nextbaseUri)=0
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| baseUri | [String](../../../system/string/) | 要比較的第一個文件的基礎 URI。 |
| nextbaseUri | [String](../../../system/string/) | 要比較的第二個文件的基礎 URI。 |

## 回傳值

整數值，用於描述兩個基礎 URI 的相對順序：-1 表示 **baseUri** 在 **nextbaseUri** 之前；0 表示兩個基礎 URI 相同；1 表示 **baseUri** 在 **nextbaseUri** 之後。

## 另請參閱

* 類別 [String](../../../system/string/)
* 類別 [XsltContext](../)
* 命名空間 [System::Xml::Xsl](../../)
* 函式庫 [Aspose.Slides](../../../)