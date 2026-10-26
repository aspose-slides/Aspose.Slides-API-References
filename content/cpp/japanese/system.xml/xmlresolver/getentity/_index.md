---
title: GetEntity()
second_title: Aspose.Slides for C++ API リファレンス
description: 派生クラスでオーバーライドされた場合、URI を実際のリソースを含むオブジェクトにマップします。
type: docs
weight: 14
url: /ja/system.xml/xmlresolver/getentity/
---
## XmlResolver::GetEntity(SharedPtr\<Uri\>, String, const TypeInfo\&) メソッド

派生クラスでオーバーライドされた場合、URI を実際のリソースを含むオブジェクトにマップします。

```cpp
virtual SharedPtr<Object> System::Xml::XmlResolver::GetEntity(SharedPtr<Uri> absoluteUri, String role, const TypeInfo &ofObjectToReturn)=0
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| absoluteUri | [SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | [XmlResolver::ResolveUri(SharedPtr<Uri>, String)](../resolveuri/) 呼び出しから返される URI。 |
| role | [String](../../../system/string/) | 現在は使用されていません。 |
| ofObjectToReturn | const [TypeInfo](../../../system/typeinfo/)\& | 返すオブジェクトの型。現在のバージョンでは Stream オブジェクトのみが返されます。 |

### 戻り値

ストリームオブジェクト、またはストリーム以外の型が指定された場合は **nullptr** が返されます。

## 関連項目

* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [Object](../../../system/object/)
* クラス [Uri](../../../system/uri/)
* クラス [String](../../../system/string/)
* クラス [TypeInfo](../../../system/typeinfo/)
* クラス [XmlResolver](../)
* 名前空間 [System::Xml](../../)
* ライブラリ [Aspose.Slides](../../../)