---
title: GetEntity()
second_title: Aspose.Slides for C++ API リファレンス
description: URI を実際のリソースを含むオブジェクトにマッピングします。
type: docs
weight: 14
url: /ja/aspose.slides.import/iexternalresourceresolver/getentity/
---
## IExternalResourceResolver::GetEntity(System::String) メソッド


URI を実際のリソースを含むオブジェクトにマッピングします。

```cpp
virtual System::SharedPtr<System::IO::Stream> Aspose::Slides::Import::IExternalResourceResolver::GetEntity(System::String absoluteUri)=0
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| absoluteUri | [System::String](../../../system/string/) | オブジェクトへの絶対 URI。 |

### 戻り値

リソースをストリームできない場合は、[System::IO::Stream](../../../system.io/stream/) オブジェクトまたは null が返されます。

## 参照

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [String](../../../system/string/)
* Class [IExternalResourceResolver](../)
* Namespace [Aspose::Slides::Import](../../)
* Library [Aspose.Slides](../../../)