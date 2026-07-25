---
title: GetEntity()
second_title: Aspose.Slides for C++ API リファレンス
description: URI を実際のリソースを含むオブジェクトにマッピングします。
type: docs
weight: 53
url: /ja/system.xml/xmlurlresolver/getentity/
---
## XmlUrlResolver::GetEntity(SharedPtr\<Uri\>, String, const TypeInfo\&) メソッド


URI を実際のリソースを含むオブジェクトにマッピングします。

```cpp
SharedPtr<Object> System::Xml::XmlUrlResolver::GetEntity(SharedPtr<Uri> absoluteUri, String role, const TypeInfo &ofObjectToReturn) override
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| absoluteUri | [SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | [XmlResolver::ResolveUri(SharedPtr<Uri>, String)](../../xmlresolver/resolveuri/) 呼び出しから返される URI。 |
| role | [String](../../../system/string/) | 現在は使用されていません。 |
| ofObjectToReturn | const [TypeInfo](../../../system/typeinfo/)\& | 返されるオブジェクトの型。現在の実装では Stream オブジェクトのみが返されます。 |

### 戻り値

Stream オブジェクト、または Stream 以外の型が指定された場合は **nullptr** が返されます。

## 参照

* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [Object](../../../system/object/)
* クラス [Uri](../../../system/uri/)
* クラス [String](../../../system/string/)
* クラス [TypeInfo](../../../system/typeinfo/)
* クラス [XmlUrlResolver](../)
* 名前空間 [System::Xml](../../)
* ライブラリ [Aspose.Slides](../../../)