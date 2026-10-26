---
title: ResolveUri()
second_title: Aspose.Slides for C++ API リファレンス
description: 派生クラスでオーバーライドされた場合、ベース URI と相対 URI から絶対 URI を解決します。
type: docs
weight: 27
url: /ja/system.xml/xmlresolver/resolveuri/
---
## XmlResolver::ResolveUri(SharedPtr\<Uri\>, String) メソッド

派生クラスでオーバーライドされた場合、ベース URI と相対 URI から絶対 URI を解決します。

```cpp
virtual SharedPtr<Uri> System::Xml::XmlResolver::ResolveUri(SharedPtr<Uri> baseUri, String relativeUri)
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| baseUri | [SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | 相対 URI を解決するために使用されるベース URI。 |
| relativeUri | [String](../../../system/string/) | 解決対象の URI。URI は絶対パスまたは相対パスのいずれかです。絶対パスの場合、この値は実質的に **baseUri** の値を置き換えます。相対パスの場合、**baseUri** と組み合わせて絶対 URI を構成します。 |

### 戻り値

相対 URI を解決できない場合は **nullptr**、それ以外は絶対 URI が返されます。

## 参照

* Typedef [SharedPtr](../../../system/sharedptr/)
* クラス [Uri](../../../system/uri/)
* クラス [String](../../../system/string/)
* クラス [XmlResolver](../)
* 名前空間 [System::Xml](../../)
* ライブラリ [Aspose.Slides](../../../)