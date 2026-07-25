---
title: SupportsType()
second_title: Aspose.Slides for C++ API リファレンス
description: リゾルバーが Stream 以外の型を返すことを可能にします。
type: docs
weight: 40
url: /ja/system.xml/xmlresolver/supportstype/
---
## XmlResolver::SupportsType(SharedPtr\<Uri\>, const TypeInfo\&) メソッド


リゾルバーが Stream 以外の型を返すことを可能にします。

```cpp
virtual bool System::Xml::XmlResolver::SupportsType(SharedPtr<Uri> absoluteUri, const TypeInfo &type)
```


### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| absoluteUri | [SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | URI です。 |
| type | const [TypeInfo](../../../system/typeinfo/)\& | 返す型です。 |

### 戻り値

**true** は **type** がサポートされていることを示し、そうでない場合は **false** です。

## 参照

* Typedef [SharedPtr](../../../system/sharedptr/)
* クラス [Uri](../../../system/uri/)
* クラス [TypeInfo](../../../system/typeinfo/)
* クラス [XmlResolver](../)
* 名前空間 [System::Xml](../../)
* Library [Aspose.Slides](../../../)