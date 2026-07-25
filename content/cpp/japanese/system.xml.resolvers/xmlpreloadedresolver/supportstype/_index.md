---
title: SupportsType()
second_title: Aspose.Slides for C++ APIリファレンス
description: リゾルバーがストリーム以外の他のタイプをサポートしているかどうかを判定します。
type: docs
weight: 66
url: /ja/system.xml.resolvers/xmlpreloadedresolver/supportstype/
---
## XmlPreloadedResolver::SupportsType(SharedPtr\<Uri\>, const TypeInfo\&) method

リゾルバーがストリーム以外の他のタイプをサポートしているかどうかを判定します。

```cpp
bool System::Xml::Resolvers::XmlPreloadedResolver::SupportsType(SharedPtr<Uri> absoluteUri, const TypeInfo &type) override
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| absoluteUri | [SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | チェックする絶対 URI。 |
| type | const [TypeInfo](../../../system/typeinfo/)\& | 返す Type。 |

## 戻り値

**true** が Type をサポートしている場合；それ以外は **false**。

## 参照

* Typedef [SharedPtr](../../../system/sharedptr/)
* クラス [Uri](../../../system/uri/)
* クラス [TypeInfo](../../../system/typeinfo/)
* クラス [XmlPreloadedResolver](../)
* 名前空間 [System::Xml::Resolvers](../../)
* ライブラリ [Aspose.Slides](../../../)