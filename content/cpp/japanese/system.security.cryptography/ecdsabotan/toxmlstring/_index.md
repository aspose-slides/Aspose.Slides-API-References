---
title: ToXmlString()
second_title: Aspose.Slides for C++ APIリファレンス
description: すべてのパラメータを XML 形式でエクスポートします。未実装です。
type: docs
weight: 157
url: /ja/system.security.cryptography/ecdsabotan/toxmlstring/
---
## ECDsaBotan::ToXmlString(bool) メソッド

すべてのパラメータを XML 形式でエクスポートします。未実装です。

```cpp
String System::Security::Cryptography::ECDsaBotan::ToXmlString(bool include_private_parameters) override
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| include_private_parameters | **bool** | True を指定するとプライベート パラメータとパブリック パラメータの両方をエクスポートし、false を指定するとパブリック パラメータのみをエクスポートします。 |

### 戻り値

XML エンコードされたパラメータ。

## ECDsaBotan::ToXmlString(ECKeyXmlFormat) メソッド

すべてのパラメータを XML 形式でエクスポートします。

```cpp
String System::Security::Cryptography::ECDsaBotan::ToXmlString(ECKeyXmlFormat format)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| format | [ECKeyXmlFormat](../../eckeyxmlformat/) | 結果の XML 文字列の形式です。 |

### 戻り値

XML エンコードされたパラメータ。

## 関連項目

* 列挙型 [ECKeyXmlFormat](../../eckeyxmlformat/)
* クラス [String](../../../system/string/)
* クラス [ECDsaBotan](../)
* 名前空間 [System::Security::Cryptography](../../)
* ライブラリ [Aspose.Slides](../../../)