---
title: ToXmlString()
second_title: Aspose.Slides for C++ API 參考
description: 以 XML 格式匯出所有參數。尚未實作。
type: docs
weight: 157
url: /zh-hant/system.security.cryptography/ecdsabotan/toxmlstring/
---
## ECDsaBotan::ToXmlString(bool) 方法


以 XML 格式匯出所有參數。尚未實作。

```cpp
String System::Security::Cryptography::ECDsaBotan::ToXmlString(bool include_private_parameters) override
```


### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| include_private_parameters | **bool** | True 代表匯出私有及公開參數，false 代表僅匯出公開參數。 |

### 回傳值

XML 編碼的參數。

## ECDsaBotan::ToXmlString(ECKeyXmlFormat) 方法


以 XML 格式匯出所有參數。

```cpp
String System::Security::Cryptography::ECDsaBotan::ToXmlString(ECKeyXmlFormat format)
```


### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| format | [ECKeyXmlFormat](../../eckeyxmlformat/) | 結果 XML 字串的格式。 |

### 回傳值

XML 編碼的參數。

## 另請參閱

* 列舉 [ECKeyXmlFormat](../../eckeyxmlformat/)
* 類別 [String](../../../system/string/)
* 類別 [ECDsaBotan](../)
* 命名空間 [System::Security::Cryptography](../../)
* 函式庫 [Aspose.Slides](../../../)