---
title: SoapParameterStyle
second_title: Aspose.Slides for C++ API リファレンス
description: SOAP メッセージにおけるパラメータ形式を列挙します。
type: docs
weight: 183
url: /ja/system.web.services.protocols/soapparameterstyle/
---
## SoapParameterStyle 列挙型

SOAP メッセージのパラメータ形式を列挙します。

```cpp
enum class SoapParameterStyle
```

### 値

| Name | Value | Description |
| --- | --- | --- |
| Default | 0 | クラスに '[SoapDocumentServiceAttribute](../soapdocumentserviceattribute/)' が適用されていない場合、デフォルト値は 'Wrapped' です。 |
| Bare | 1 | パラメータは 'Body' 要素の後に続く XML 要素に配置されます。 |
| Wrapped | 2 | パラメータは 'Body' 要素の後に続く単一の XML 要素内にカプセル化されます。 |

## 関連項目

* 名前空間 [System::Web::Services::Protocols](../)
* ライブラリ [Aspose.Slides](../../)