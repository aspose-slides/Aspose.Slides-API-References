---
title: ResolveUri()
second_title: Aspose.Slides for C++ API リファレンス
description: ベースURIと相対URIから絶対URIを解決します。
type: docs
weight: 40
url: /ja/system.xml.resolvers/xmlpreloadedresolver/resolveuri/
---
## XmlPreloadedResolver::ResolveUri(SharedPtr\<Uri\>, String) method

ベースURIと相対URIから絶対URIを解決します。

```cpp
SharedPtr<Uri> System::Xml::Resolvers::XmlPreloadedResolver::ResolveUri(SharedPtr<Uri> baseUri, String relativeUri) override
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| baseUri | [SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | 相対URIの解決に使用されるベースURI。 |
| relativeUri | [String](../../../system/string/) | 解決対象のURI。URIは絶対でも相対でもかまいません。絶対の場合、この値は **baseUri** の値を実質的に置き換えます。相対の場合、**baseUri** と結合して絶対URIを作成します。 |

### 戻り値

[Uri](../../../system/uri/) は、絶対URIを表すか、相対URIを解決できない場合は **nullptr** を返します。

## 参照

* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [Uri](../../../system/uri/)
* クラス [String](../../../system/string/)
* クラス [XmlPreloadedResolver](../)
* 名前空間 [System::Xml::Resolvers](../../)
* ライブラリ [Aspose.Slides](../../../)