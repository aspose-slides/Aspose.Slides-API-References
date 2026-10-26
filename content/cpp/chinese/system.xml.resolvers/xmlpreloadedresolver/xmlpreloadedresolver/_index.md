---
title: XmlPreloadedResolver()
second_title: Aspose.Slides for C++ API 参考
description: 初始化 XmlPreloadedResolver 类的新实例。
type: docs
weight: 27
url: /zh/system.xml.resolvers/xmlpreloadedresolver/xmlpreloadedresolver/
---
## XmlPreloadedResolver::XmlPreloadedResolver() 构造函数

初始化 [XmlPreloadedResolver](../) 类的新实例。

```cpp
System::Xml::Resolvers::XmlPreloadedResolver::XmlPreloadedResolver()
```

## XmlPreloadedResolver::XmlPreloadedResolver(XmlKnownDtds) 构造函数

使用指定的预加载已知 DTD 初始化 [XmlPreloadedResolver](../) 类的新实例。

```cpp
System::Xml::Resolvers::XmlPreloadedResolver::XmlPreloadedResolver(XmlKnownDtds preloadedDtds)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| preloadedDtds | [XmlKnownDtds](../../xmlknowndtds/) | 应预填充到缓存中的已知 DTD。 |

## XmlPreloadedResolver::XmlPreloadedResolver(const SharedPtr\<XmlResolver\>\&) 构造函数

使用指定的回退解析器初始化 [XmlPreloadedResolver](../) 类的新实例。

```cpp
System::Xml::Resolvers::XmlPreloadedResolver::XmlPreloadedResolver(const SharedPtr<XmlResolver> &fallbackResolver)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| fallbackResolver | const [SharedPtr](../../../system/sharedptr/)\<[XmlResolver](../../../system.xml/xmlresolver/)\>\& | [XmlResolver](../../../system.xml/xmlresolver/) 或您自己的解析器。 |

## XmlPreloadedResolver::XmlPreloadedResolver(const SharedPtr\<XmlResolver\>\&, XmlKnownDtds) 构造函数

使用指定的回退解析器和预加载已知 DTD 初始化 [XmlPreloadedResolver](../) 类的新实例。

```cpp
System::Xml::Resolvers::XmlPreloadedResolver::XmlPreloadedResolver(const SharedPtr<XmlResolver> &fallbackResolver, XmlKnownDtds preloadedDtds)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| fallbackResolver | const [SharedPtr](../../../system/sharedptr/)\<[XmlResolver](../../../system.xml/xmlresolver/)\>\& | [XmlResolver](../../../system.xml/xmlresolver/) 或您自己的解析器。 |
| preloadedDtds | [XmlKnownDtds](../../xmlknowndtds/) | 应预填充到缓存中的已知 DTD。 |

## XmlPreloadedResolver::XmlPreloadedResolver(const SharedPtr\<XmlResolver\>\&, XmlKnownDtds, const SharedPtr\<Collections::Generic::IEqualityComparer\<SharedPtr\<Uri\>\>\>\&) 构造函数

使用指定的回退解析器、预加载已知 DTD 和 URI 相等比较器初始化 [XmlPreloadedResolver](../) 类的新实例。

```cpp
System::Xml::Resolvers::XmlPreloadedResolver::XmlPreloadedResolver(const SharedPtr<XmlResolver> &fallbackResolver, XmlKnownDtds preloadedDtds, const SharedPtr<Collections::Generic::IEqualityComparer<SharedPtr<Uri>>> &uriComparer)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| fallbackResolver | const [SharedPtr](../../../system/sharedptr/)\<[XmlResolver](../../../system.xml/xmlresolver/)\>\& | [XmlResolver](../../../system.xml/xmlresolver/) 或您自己的解析器。 |
| preloadedDtds | [XmlKnownDtds](../../xmlknowndtds/) | 应预填充到缓存中的已知 DTD。 |
| uriComparer | const [SharedPtr](../../../system/sharedptr/)\<[Collections::Generic::IEqualityComparer](../../../system.collections.generic/iequalitycomparer/)\<[SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\>\>\>\& | 比较 URI 时使用的 IEqualityComparer 接口的实现。 |

## 另见

* Enum [XmlKnownDtds](../../xmlknowndtds/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* 类 [XmlPreloadedResolver](../)
* 类 [XmlResolver](../../../system.xml/xmlresolver/)
* 类 [IEqualityComparer](../../../system.collections.generic/iequalitycomparer/)
* 类 [Uri](../../../system/uri/)
* 命名空间 [System::Xml::Resolvers](../../)
* Library [Aspose.Slides](../../../)