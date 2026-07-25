---
title: Add()
second_title: Aspose.Slides for C++ APIリファレンス
description: バイト配列を XmlPreloadedResolver ストアに追加し、URI にマッピングします。ストアに同じ URI のマッピングが既に存在する場合、既存のマッピングは上書きされます。
type: docs
weight: 79
url: /ja/system.xml.resolvers/xmlpreloadedresolver/add/
---
## XmlPreloadedResolver::Add(const SharedPtr\<Uri\>\&, const ArrayPtr\<uint8_t\>\&) メソッド

[XmlPreloadedResolver](../) ストアにバイト配列を追加し、URI にマッピングします。ストアに同じ URI のマッピングが既に存在する場合、既存のマッピングは上書きされます。

```cpp
void System::Xml::Resolvers::XmlPreloadedResolver::Add(const SharedPtr<Uri> &uri, const ArrayPtr<uint8_t> &value)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| uri | const [SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\>\& | [XmlPreloadedResolver](../) ストアに追加されるデータの URI。 |
| value | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | 提供された URI に対応するデータを含むバイト配列。 |

## XmlPreloadedResolver::Add(const SharedPtr\<Uri\>\&, const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) メソッド

[XmlPreloadedResolver](../) ストアにバイト配列を追加し、URI にマッピングします。ストアに同じ URI のマッピングが既に存在する場合、既存のマッピングは上書きされます。

```cpp
void System::Xml::Resolvers::XmlPreloadedResolver::Add(const SharedPtr<Uri> &uri, const ArrayPtr<uint8_t> &value, int32_t offset, int32_t count)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| uri | const [SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\>\& | [XmlPreloadedResolver](../) ストアに追加されるデータの URI。 |
| value | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | 提供された URI に対応するデータを含むバイト配列。 |
| offset | **int32_t** | データが開始する位置（提供されたバイト配列内のオフセット）。 |
| count | **int32_t** | 提供されたオフセットから開始し、バイト配列から読み取るバイト数。 |

## XmlPreloadedResolver::Add(const SharedPtr\<Uri\>\&, const SharedPtr\<IO::Stream\>\&) メソッド

[XmlPreloadedResolver](../) ストアにストリームを追加し、URI にマッピングします。ストアに同じ URI のマッピングが既に存在する場合、既存のマッピングは上書きされます。

```cpp
void System::Xml::Resolvers::XmlPreloadedResolver::Add(const SharedPtr<Uri> &uri, const SharedPtr<IO::Stream> &value)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| uri | const [SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\>\& | [XmlPreloadedResolver](../) ストアに追加されるデータの URI。 |
| value | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | 提供された URI に対応するデータを含むストリーム。 |

## XmlPreloadedResolver::Add(const SharedPtr\<Uri\>\&, const String\&) メソッド

[XmlPreloadedResolver](../) ストアに事前ロードされたデータを含む文字列を追加し、URI にマッピングします。ストアに同じ URI のマッピングが既に存在する場合、既存のマッピングは上書きされます。

```cpp
void System::Xml::Resolvers::XmlPreloadedResolver::Add(const SharedPtr<Uri> &uri, const String &value)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| uri | const [SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\>\& | [XmlPreloadedResolver](../) ストアに追加されるデータの URI。 |
| value | const [String](../../../system/string/)\& | 提供された URI に対応するデータを含む [String](../../../system/string/)。 |

## 参照

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [Uri](../../../system/uri/)
* Class [XmlPreloadedResolver](../)
* Class [Stream](../../../system.io/stream/)
* Class [String](../../../system/string/)
* Namespace [System::Xml::Resolvers](../../)
* Library [Aspose.Slides](../../../)