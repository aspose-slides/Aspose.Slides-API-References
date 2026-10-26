---
title: ResolveUri()
second_title: Aspose.Slides for C++ API リファレンス
description: ベースURIと相対URIから絶対URIを解決します。
type: docs
weight: 1
url: /ja/aspose.slides.import/iexternalresourceresolver/resolveuri/
---
## IExternalResourceResolver::ResolveUri(System::String, System::String) メソッド


ベースURIと相対URIから絶対URIを解決します。

```cpp
virtual System::String Aspose::Slides::Import::IExternalResourceResolver::ResolveUri(System::String baseUri, System::String relativeUri)=0
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| baseUri | [System::String](../../../system/string/) | リンク対象オブジェクトのベースURI |
| relativeUri | [System::String](../../../system/string/) | リンクされたオブジェクトへの相対URI |

### 戻り値

相対URIを解決できない場合は、絶対URIまたは null が返されます。

## 参照

* クラス [String](../../../system/string/)
* クラス [IExternalResourceResolver](../)
* 名前空間 [Aspose::Slides::Import](../../)
* ライブラリ [Aspose.Slides](../../../)