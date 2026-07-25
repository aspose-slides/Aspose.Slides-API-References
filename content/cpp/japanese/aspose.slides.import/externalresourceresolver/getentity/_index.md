---
title: GetEntity()
second_title: Aspose.Slides for C++ API リファレンス
description: URI を実際のリソースを含むオブジェクトにマッピングします。
type: docs
weight: 14
url: /ja/aspose.slides.import/externalresourceresolver/getentity/
---
## ExternalResourceResolver::GetEntity(System::String) メソッド

URI を実際のリソースを含むオブジェクトにマッピングします。

```cpp
System::SharedPtr<System::IO::Stream> Aspose::Slides::Import::ExternalResourceResolver::GetEntity(System::String absoluteUri) override
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| absoluteUri | [System::String](../../../system/string/) | オブジェクトへの絶対 URI。 |

### 戻り値

リソースをストリームできない場合は、[System::IO::Stream](../../../system.io/stream/) オブジェクトまたは null が返されます。

## 参照

* Typedef [SharedPtr](../../../system/sharedptr/)
* クラス [Stream](../../../system.io/stream/)
* クラス [String](../../../system/string/)
* クラス [ExternalResourceResolver](../)
* 名前空間 [Aspose::Slides::Import](../../)
* Library [Aspose.Slides](../../../)