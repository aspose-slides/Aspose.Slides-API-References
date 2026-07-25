---
title: RemoveParam()
second_title: Aspose.Slides for C++ API リファレンス
description: XsltArgumentList からパラメータを削除します。
type: docs
weight: 66
url: /ja/system.xml.xsl/xsltargumentlist/removeparam/
---
## XsltArgumentList::RemoveParam(const String\&, const String\&) メソッド

パラメータを [XsltArgumentList](../) から削除します。

```cpp
SharedPtr<Object> System::Xml::Xsl::XsltArgumentList::RemoveParam(const String &name, const String &namespaceUri)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| name | const [String](../../../system/string/)\& | 削除するパラメータの名前。[XsltArgumentList](../) は、渡された名前が有効なローカル名であるかどうかをチェックしませんが、名前は **nullptr** であってはなりません。 |
| namespaceUri | const [String](../../../system/string/)\& | 削除するパラメータの名前空間 URI。 |

### 戻り値

パラメータオブジェクト、または見つからなかった場合は **nullptr** が返されます。

## 参照

* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [Object](../../../system/object/)
* クラス [String](../../../system/string/)
* クラス [XsltArgumentList](../)
* 名前空間 [System::Xml::Xsl](../../)
* ライブラリ [Aspose.Slides](../../../)