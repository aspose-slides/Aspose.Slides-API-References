---
title: HasFeature()
second_title: Aspose.Slides for C++ API リファレンス
description: Document Object Model (DOM) 実装が特定の機能を実装しているかテストします。
type: docs
weight: 14
url: /ja/system.xml/xmlimplementation/hasfeature/
---
## XmlImplementation::HasFeature(const String\&, const String\&) メソッド


Document [Object](../../../system/object/) Model (DOM) 実装が特定の機能を実装しているかテストします。

```cpp
bool System::Xml::XmlImplementation::HasFeature(const String &strFeature, const String &strVersion)
```


### 引数

| パラメータ | 型 | 説明 |
|---|---|---|
| strFeature | const [String](../../../system/string/)\& | テストする機能のパッケージ名。この名前は大文字小文字を区別しません。 |
| strVersion | const [String](../../../system/string/)\& | テストするパッケージ名のバージョン番号です。バージョンが指定されていない場合 (**nullptr**) は、機能の任意のバージョンをサポートしていることになり、メソッドは **true** を返します。 |

### 戻り値

**true** は指定されたバージョンで機能が実装されている場合、そうでなければ **false**。

## 備考



以下の表は **HasFeature** が **true** を返す組み合わせを示しています。

| strFeature | strVersion |
|---|---|
| XML | 1.0 |
| XML | 2.0 |


## 参照

* クラス [String](../../../system/string/)
* クラス [XmlImplementation](../)
* 名前空間 [System::Xml](../../)
* ライブラリ [Aspose.Slides](../../../)