---
title: Add()
second_title: Aspose.Slides for C++ API 參考
description: 將位元組陣列新增至 XmlPreloadedResolver 儲存區，並將其映射至 URI。若儲存區已經為相同的 URI 包含映射，則會覆寫現有的映射。
type: docs
weight: 79
url: /zh-hant/system.xml.resolvers/xmlpreloadedresolver/add/
---
## XmlPreloadedResolver::Add(const SharedPtr\<Uri\>\&, const ArrayPtr\<uint8_t\>\&) 方法

將位元組陣列新增至 [XmlPreloadedResolver](../) 儲存區，並將其映射到 URI。若儲存區已經為相同的 URI 包含映射，則會覆寫現有的映射。

```cpp
void System::Xml::Resolvers::XmlPreloadedResolver::Add(const SharedPtr<Uri> &uri, const ArrayPtr<uint8_t> &value)
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| uri | const [SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\>\& | 被新增至 [XmlPreloadedResolver](../) 儲存區之資料的 URI。 |
| value | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | 與提供之 URI 對應之資料的位元組陣列。 |

## XmlPreloadedResolver::Add(const SharedPtr\<Uri\>\&, const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) 方法

將位元組陣列新增至 [XmlPreloadedResolver](../) 儲存區，並將其映射到 URI。若儲存區已經為相同的 URI 包含映射，則會覆寫現有的映射。

```cpp
void System::Xml::Resolvers::XmlPreloadedResolver::Add(const SharedPtr<Uri> &uri, const ArrayPtr<uint8_t> &value, int32_t offset, int32_t count)
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| uri | const [SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\>\& | 被新增至 [XmlPreloadedResolver](../) 儲存區之資料的 URI。 |
| value | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | 與提供之 URI 對應之資料的位元組陣列。 |
| offset | **int32_t** | 資料在提供之位元組陣列中的起始偏移量。 |
| count | **int32_t** | 自提供的偏移量起，從位元組陣列中讀取的位元組數量。 |

## XmlPreloadedResolver::Add(const SharedPtr\<Uri\>\&, const SharedPtr\<IO::Stream\>\&) 方法

將 Stream 新增至 [XmlPreloadedResolver](../) 儲存區，並將其映射到 URI。若儲存區已經為相同的 URI 包含映射，則會覆寫現有的映射。

```cpp
void System::Xml::Resolvers::XmlPreloadedResolver::Add(const SharedPtr<Uri> &uri, const SharedPtr<IO::Stream> &value)
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| uri | const [SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\>\& | 被新增至 [XmlPreloadedResolver](../) 儲存區之資料的 URI。 |
| value | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | 與提供之 URI 對應之資料的 Stream。 |

## XmlPreloadedResolver::Add(const SharedPtr\<Uri\>\&, const String\&) 方法

將 string 與預載資料新增至 [XmlPreloadedResolver](../) 儲存區，並將其映射到 URI。若儲存區已經為相同的 URI 包含映射，則會覆寫現有的映射。

```cpp
void System::Xml::Resolvers::XmlPreloadedResolver::Add(const SharedPtr<Uri> &uri, const String &value)
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| uri | const [SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\>\& | 被新增至 [XmlPreloadedResolver](../) 儲存區之資料的 URI。 |
| value | const [String](../../../system/string/)\& | 與提供之 URI 對應之資料的 [String](../../../system/string/)。 |

## 另見

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [Uri](../../../system/uri/)
* Class [XmlPreloadedResolver](../)
* Class [Stream](../../../system.io/stream/)
* Class [String](../../../system/string/)
* Namespace [System::Xml::Resolvers](../../)
* Library [Aspose.Slides](../../../)