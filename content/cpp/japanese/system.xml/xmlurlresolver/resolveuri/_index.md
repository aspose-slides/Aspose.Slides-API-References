---
title: ResolveUri()
second_title: Aspose.Slides for C++ API リファレンス
description: ベース URI と相対 URI から絶対 URI を解決します。
type: docs
weight: 66
url: /ja/system.xml/xmlurlresolver/resolveuri/
---
## XmlUrlResolver::ResolveUri(SharedPtr\<Uri\>, String) メソッド

ベース URI と相対 URI から絶対 URI を解決します。

```cpp
SharedPtr<Uri> System::Xml::XmlUrlResolver::ResolveUri(SharedPtr<Uri> baseUri, String relativeUri) override
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| baseUri | [SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | 相対 URI を解決するために使用されるベース URI。 |
| relativeUri | [String](../../../system/string/) | 解決する URI。URI は絶対または相対のいずれかです。絶対の場合、この値は実質的に **baseUri** の値を置き換えます。相対の場合、**baseUri** と組み合わせて絶対 URI を作成します。 |

### 戻り値

相対 URI を解決できない場合は **nullptr** を返す絶対 URI。

## 参照

* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [Uri](../../../system/uri/)
* クラス [String](../../../system/string/)
* クラス [XmlUrlResolver](../)
* 名前空間 [System::Xml](../../)
* ライブラリ [Aspose.Slides](../../../)