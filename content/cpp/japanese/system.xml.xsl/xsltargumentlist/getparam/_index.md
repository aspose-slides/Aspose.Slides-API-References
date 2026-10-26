---
title: GetParam()
second_title: Aspose.Slides for C++ API リファレンス
description: 名前空間修飾名に関連付けられたパラメータを返します。
type: docs
weight: 14
url: /ja/system.xml.xsl/xsltargumentlist/getparam/
---
## XsltArgumentList::GetParam(const String\&, const String\&) メソッド

名前空間修飾名に関連付けられたパラメータを返します。

```cpp
SharedPtr<Object> System::Xml::Xsl::XsltArgumentList::GetParam(const String &name, const String &namespaceUri)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| name | const [String](../../../system/string/)\& | パラメータの名前。[XsltArgumentList](../) は、渡された名前が有効なローカル名であることを確認しませんが、名前は **nullptr** にできません。 |
| namespaceUri | const [String](../../../system/string/)\& | パラメータに関連付けられた名前空間 URI。 |

### 戻り値

パラメータオブジェクト、または見つからなかった場合は **nullptr**。

## 参照

* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [Object](../../../system/object/)
* クラス [String](../../../system/string/)
* クラス [XsltArgumentList](../)
* 名前空間 [System::Xml::Xsl](../../)
* ライブラリ [Aspose.Slides](../../../)