---
title: GetEntity()
second_title: Aspose.Slides C++ 用 API リファレンス
description: URI を実際のリソースを含むオブジェクトにマッピングします。
type: docs
weight: 53
url: /ja/system.xml.resolvers/xmlpreloadedresolver/getentity/
---
## XmlPreloadedResolver::GetEntity(SharedPtr\<Uri\>, String, const TypeInfo\&) メソッド

URI を実際のリソースを含むオブジェクトにマッピングします。

```cpp
SharedPtr<Object> System::Xml::Resolvers::XmlPreloadedResolver::GetEntity(SharedPtr<Uri> absoluteUri, String role, const TypeInfo &ofObjectToReturn) override
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| absoluteUri | [SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | [XmlResolver::ResolveUri(SharedPtr<Uri>,String)](../../../system.xml/xmlresolver/resolveuri/) 呼び出しで返される URI。 |
| role | [String](../../../system/string/) | 現在は使用されていません。 |
| ofObjectToReturn | const [TypeInfo](../../../system/typeinfo/)\& | 戻り値オブジェクトの型。[XmlPreloadedResolver](../) は、[String](../../../system/string/) として追加された URI に対して Stream オブジェクトと TextReader オブジェクトをサポートします。要求された型がリゾルバでサポートされていない場合、例外がスローされます。このリゾルバが特定の **Type** をサポートしているかどうかを判断するには、XmlPreloadedResolver::SupportsType(SharedPtr<Uri>,TypeInfo) メソッドを使用してください。 |

### 戻り値

実際のソースに対応する Stream または TextReader オブジェクトです。

## 参照

* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [Object](../../../system/object/)
* クラス [Uri](../../../system/uri/)
* クラス [String](../../../system/string/)
* クラス [TypeInfo](../../../system/typeinfo/)
* クラス [XmlPreloadedResolver](../)
* 名前空間 [System::Xml::Resolvers](../../)
* ライブラリ [Aspose.Slides](../../../)