---
title: ResolveUri()
second_title: Aspose.Slides for C++ API リファレンス
description: 基底URIと相対URIから絶対URIを解決し、基礎となる XmlResolver 上で ResolveUri を呼び出します。
type: docs
weight: 40
url: /ja/system.xml/xmlsecureresolver/resolveuri/
---
## XmlSecureResolver::ResolveUri(SharedPtr\<Uri\>, String) メソッド


基底URIと相対URIから絶対URIを解決し、基礎となる [XmlResolver](../../xmlresolver/) 上で **ResolveUri** を呼び出します。

```cpp
SharedPtr<Uri> System::Xml::XmlSecureResolver::ResolveUri(SharedPtr<Uri> baseUri, String relativeUri) override
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| baseUri | [SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | 相対URIを解決するために使用される基底URIです。 |
| relativeUri | [String](../../../system/string/) | 解決対象のURI。URIは絶対でも相対でもかまいません。絶対の場合、この値は実質的に **baseUri** の値を置き換えます。相対の場合、**baseUri** と結合して絶対URIを作成します。 |

### 戻り値

絶対URI、または相対URIを解決できない場合は **nullptr**（基礎となる [XmlResolver](../../xmlresolver/) 上で **ResolveUri** を呼び出した結果として返されます）。

## 参照

* Typedef [SharedPtr](../../../system/sharedptr/)
* クラス [Uri](../../../system/uri/)
* クラス [String](../../../system/string/)
* クラス [XmlSecureResolver](../)
* 名前空間 [System::Xml](../../)
* ライブラリ [Aspose.Slides](../../../)