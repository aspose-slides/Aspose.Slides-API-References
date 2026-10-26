---
title: ResolveUri()
second_title: Aspose.Slides for C++ API リファレンス
description: ベース URI と相対 URI から絶対 URI を解決します。
type: docs
weight: 1
url: /ja/aspose.slides.import/externalresourceresolver/resolveuri/
---
## ExternalResourceResolver::ResolveUri(System::String, System::String) メソッド

ベース URI と相対 URI から絶対 URI を解決します。

```cpp
System::String Aspose::Slides::Import::ExternalResourceResolver::ResolveUri(System::String baseUri, System::String relativeUri) override
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| baseUri | [System::String](../../../system/string/) | リンク対象オブジェクトのベース URI |
| relativeUri | [System::String](../../../system/string/) | リンクされたオブジェクトへの相対 URI。 |

### 戻り値

相対 URI を解決できない場合は、絶対 URI または null が返されます。

## 参照

* クラス [String](../../../system/string/)
* クラス [ExternalResourceResolver](../)
* 名前空間 [Aspose::Slides::Import](../../)
* ライブラリ [Aspose.Slides](../../../)