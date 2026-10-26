---
title: GetEntity()
second_title: Aspose.Slides for C++ APIリファレンス
description: URI を実際のリソースを含むオブジェクトにマッピングします。
type: docs
weight: 14
url: /ja/aspose.slides.import/htmlexternalresolver/getentity/
---
## HtmlExternalResolver::GetEntity(System::String) メソッド


URI を実際のリソースを含むオブジェクトにマッピングします。

```cpp
System::SharedPtr<System::IO::Stream> Aspose::Slides::Import::HtmlExternalResolver::GetEntity(System::String absoluteUri) override
```


### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| absoluteUri | [System::String](../../../system/string/) | オブジェクトへの絶対 URI。 |

### 戻り値

リソースをストリームできない場合は [System::IO::Stream](../../../system.io/stream/) オブジェクトまたは null が返されます。

## 関連項目

* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [Stream](../../../system.io/stream/)
* クラス [String](../../../system/string/)
* クラス [HtmlExternalResolver](../)
* 名前空間 [Aspose::Slides::Import](../../)
* ライブラリ [Aspose.Slides](../../../)