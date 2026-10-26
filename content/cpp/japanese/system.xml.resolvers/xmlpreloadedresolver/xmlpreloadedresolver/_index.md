---
title: XmlPreloadedResolver()
second_title: Aspose.Slides の C++ 用 API リファレンス
description: XmlPreloadedResolver クラスの新しいインスタンスを初期化します。
type: docs
weight: 27
url: /ja/system.xml.resolvers/xmlpreloadedresolver/xmlpreloadedresolver/
---
## XmlPreloadedResolver::XmlPreloadedResolver() コンストラクタ

[XmlPreloadedResolver](../) クラスの新しいインスタンスを初期化します。

```cpp
System::Xml::Resolvers::XmlPreloadedResolver::XmlPreloadedResolver()
```

## XmlPreloadedResolver::XmlPreloadedResolver(XmlKnownDtds) コンストラクタ

[XmlPreloadedResolver](../) クラスの新しいインスタンスを、指定された事前ロード済みの既知 DTD で初期化します。

```cpp
System::Xml::Resolvers::XmlPreloadedResolver::XmlPreloadedResolver(XmlKnownDtds preloadedDtds)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| preloadedDtds | [XmlKnownDtds](../../xmlknowndtds/) | キャッシュに事前に格納すべき既知 DTD 。 |

## XmlPreloadedResolver::XmlPreloadedResolver(const SharedPtr\<XmlResolver\>\&) コンストラクタ

[XmlPreloadedResolver](../) クラスの新しいインスタンスを、指定されたフォールバックリゾルバで初期化します。

```cpp
System::Xml::Resolvers::XmlPreloadedResolver::XmlPreloadedResolver(const SharedPtr<XmlResolver> &fallbackResolver)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| fallbackResolver | const [SharedPtr](../../../system/sharedptr/)\<[XmlResolver](../../../system.xml/xmlresolver/)\>\& | [XmlResolver](../../../system.xml/xmlresolver/) または独自のリゾルバ 。 |

## XmlPreloadedResolver::XmlPreloadedResolver(const SharedPtr\<XmlResolver\>\&, XmlKnownDtds) コンストラクタ

[XmlPreloadedResolver](../) クラスの新しいインスタンスを、指定されたフォールバックリゾルバと事前ロード済みの既知 DTD で初期化します。

```cpp
System::Xml::Resolvers::XmlPreloadedResolver::XmlPreloadedResolver(const SharedPtr<XmlResolver> &fallbackResolver, XmlKnownDtds preloadedDtds)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| fallbackResolver | const [SharedPtr](../../../system/sharedptr/)\<[XmlResolver](../../../system.xml/xmlresolver/)\>\& | [XmlResolver](../../../system.xml/xmlresolver/) または独自のリゾルバ 。 |
| preloadedDtds | [XmlKnownDtds](../../xmlknowndtds/) | キャッシュに事前に格納すべき既知 DTD 。 |

## XmlPreloadedResolver::XmlPreloadedResolver(const SharedPtr\<XmlResolver\>\&, XmlKnownDtds, const SharedPtr\<Collections::Generic::IEqualityComparer\<SharedPtr\<Uri\>\>\>\&) コンストラクタ

[XmlPreloadedResolver](../) クラスの新しいインスタンスを、指定されたフォールバックリゾルバ、事前ロード済みの既知 DTD、そして URI 等価比較子で初期化します。

```cpp
System::Xml::Resolvers::XmlPreloadedResolver::XmlPreloadedResolver(const SharedPtr<XmlResolver> &fallbackResolver, XmlKnownDtds preloadedDtds, const SharedPtr<Collections::Generic::IEqualityComparer<SharedPtr<Uri>>> &uriComparer)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| fallbackResolver | const [SharedPtr](../../../system/sharedptr/)\<[XmlResolver](../../../system.xml/xmlresolver/)\>\& | [XmlResolver](../../../system.xml/xmlresolver/) または独自のリゾルバ 。 |
| preloadedDtds | [XmlKnownDtds](../../xmlknowndtds/) | キャッシュに事前に格納すべき既知 DTD 。 |
| uriComparer | const [SharedPtr](../../../system/sharedptr/)\<[Collections::Generic::IEqualityComparer](../../../system.collections.generic/iequalitycomparer/)\<[SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\>\>\>\& | URI を比較するときに使用する IEqualityComparer インタフェースの実装 。 |

## 参照

* Enum [XmlKnownDtds](../../xmlknowndtds/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* クラス [XmlPreloadedResolver](../)
* クラス [XmlResolver](../../../system.xml/xmlresolver/)
* クラス [IEqualityComparer](../../../system.collections.generic/iequalitycomparer/)
* クラス [Uri](../../../system/uri/)
* 名前空間 [System::Xml::Resolvers](../../)
* Library [Aspose.Slides](../../../)