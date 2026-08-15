---
title: XmlPreloadedResolver()
second_title: Aspose.Slides for C++ API 參考文件
description: 初始化 XmlPreloadedResolver 類別的新執行個體。
type: docs
weight: 27
url: /zh-hant/system.xml.resolvers/xmlpreloadedresolver/xmlpreloadedresolver/
---
## XmlPreloadedResolver::XmlPreloadedResolver() 建構函式


初始化 [XmlPreloadedResolver](../) 類別的新執行個體。

```cpp
System::Xml::Resolvers::XmlPreloadedResolver::XmlPreloadedResolver()
```

## XmlPreloadedResolver::XmlPreloadedResolver(XmlKnownDtds) 建構函式


初始化 [XmlPreloadedResolver](../) 類別的新執行個體，並使用指定的預先載入之已知 DTD。

```cpp
System::Xml::Resolvers::XmlPreloadedResolver::XmlPreloadedResolver(XmlKnownDtds preloadedDtds)
```


### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| preloadedDtds | [XmlKnownDtds](../../xmlknowndtds/) | 應預先填入快取的已知 DTD。 |

## XmlPreloadedResolver::XmlPreloadedResolver(const SharedPtr\<XmlResolver\>\&) 建構函式


初始化 [XmlPreloadedResolver](../) 類別的新執行個體，並使用指定的備援解析器。

```cpp
System::Xml::Resolvers::XmlPreloadedResolver::XmlPreloadedResolver(const SharedPtr<XmlResolver> &fallbackResolver)
```


### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| fallbackResolver | const [SharedPtr](../../../system/sharedptr/)\<[XmlResolver](../../../system.xml/xmlresolver/)\>\& | [XmlResolver](../../../system.xml/xmlresolver/) 或您自己的解析器。 |

## XmlPreloadedResolver::XmlPreloadedResolver(const SharedPtr\<XmlResolver\>\&, XmlKnownDtds) 建構函式


初始化 [XmlPreloadedResolver](../) 類別的新執行個體，並使用指定的備援解析器與預先載入之已知 DTD。

```cpp
System::Xml::Resolvers::XmlPreloadedResolver::XmlPreloadedResolver(const SharedPtr<XmlResolver> &fallbackResolver, XmlKnownDtds preloadedDtds)
```


### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| fallbackResolver | const [SharedPtr](../../../system/sharedptr/)\<[XmlResolver](../../../system.xml/xmlresolver/)\>\& | [XmlResolver](../../../system.xml/xmlresolver/) 或您自己的解析器。 |
| preloadedDtds | [XmlKnownDtds](../../xmlknowndtds/) | 應預先填入快取的已知 DTD。 |

## XmlPreloadedResolver::XmlPreloadedResolver(const SharedPtr\<XmlResolver\>\&, XmlKnownDtds, const SharedPtr\<Collections::Generic::IEqualityComparer\<SharedPtr\<Uri\>\>\>\&) 建構函式


初始化 [XmlPreloadedResolver](../) 類別的新執行個體，並使用指定的備援解析器、預先載入之已知 DTD 與 URI 等價比較器。

```cpp
System::Xml::Resolvers::XmlPreloadedResolver::XmlPreloadedResolver(const SharedPtr<XmlResolver> &fallbackResolver, XmlKnownDtds preloadedDtds, const SharedPtr<Collections::Generic::IEqualityComparer<SharedPtr<Uri>>> &uriComparer)
```


### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| fallbackResolver | const [SharedPtr](../../../system/sharedptr/)\<[XmlResolver](../../../system.xml/xmlresolver/)\>\& | [XmlResolver](../../../system.xml/xmlresolver/) 或您自己的解析器。 |
| preloadedDtds | [XmlKnownDtds](../../xmlknowndtds/) | 應預先填入快取的已知 DTD。 |
| uriComparer | const [SharedPtr](../../../system/sharedptr/)\<[Collections::Generic::IEqualityComparer](../../../system.collections.generic/iequalitycomparer/)\<[SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\>\>\>\& | 用於比較 URI 時實作 IEqualityComparer 介面的比較器。 |

## 另請參閱

* 列舉 [XmlKnownDtds](../../xmlknowndtds/)
* 型別別名 [SharedPtr](../../../system/sharedptr/)
* 類別 [XmlPreloadedResolver](../)
* 類別 [XmlResolver](../../../system.xml/xmlresolver/)
* 類別 [IEqualityComparer](../../../system.collections.generic/iequalitycomparer/)
* 類別 [Uri](../../../system/uri/)
* 命名空間 [System::Xml::Resolvers](../../)
* 函式庫 [Aspose.Slides](../../../)