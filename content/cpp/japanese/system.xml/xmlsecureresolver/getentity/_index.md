---
title: GetEntity()
second_title: Aspose.Slides for C++ API リファレンス
description: URI を実際のリソースが含まれるオブジェクトにマッピングします。
type: docs
weight: 27
url: /ja/system.xml/xmlsecureresolver/getentity/
---
## XmlSecureResolver::GetEntity(SharedPtr\<Uri\>, String, const TypeInfo\&) メソッド

URI を実際のリソースが含まれるオブジェクトにマッピングします。

```cpp
SharedPtr<Object> System::Xml::XmlSecureResolver::GetEntity(SharedPtr<Uri> absoluteUri, String role, const TypeInfo &ofObjectToReturn) override
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| absoluteUri | [SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | [XmlSecureResolver::ResolveUri(SharedPtr<Uri>, String)](../resolveuri/) 呼び出しから返される URI。 |
| role | [String](../../../system/string/) | 現在は使用されていません。 |
| ofObjectToReturn | const [TypeInfo](../../../system/typeinfo/)\& | 返すオブジェクトの型。現在のバージョンでは Stream オブジェクトのみが返されます。 |

### 戻り値

基底の [XmlResolver](../../xmlresolver/) 上で **GetEntity** を呼び出すことにより返されるストリームです。Stream 以外の型が指定された場合、メソッドは **nullptr** を返します。

## 関連項目

* Typedef [SharedPtr](../../../system/sharedptr/)
* クラス [Object](../../../system/object/)
* クラス [Uri](../../../system/uri/)
* クラス [String](../../../system/string/)
* クラス [TypeInfo](../../../system/typeinfo/)
* クラス [XmlSecureResolver](../)
* 名前空間 [System::Xml](../../)
* ライブラリ [Aspose.Slides](../../../)