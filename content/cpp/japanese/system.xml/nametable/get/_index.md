---
title: Get()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定された値を持つ内部化された文字列を返します。
type: docs
weight: 27
url: /ja/system.xml/nametable/get/
---
## NameTable::Get(const String\&) method

指定された値を持つ内部化された文字列を返します。

```cpp
const String & System::Xml::NameTable::Get(const String &value) override
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | const [String](../../../system/string/)\& | 検索する名前。 |

### 戻り値

文字列がまだ内部化されていない場合は **nullptr**、それ以外は内部化された文字列オブジェクト。

## NameTable::Get(const ArrayPtr\<char16_t\>\&, int32_t, int32_t) method

指定された配列の特定の文字範囲と同じ文字を含む内部化された文字列を返します。

```cpp
const String & System::Xml::NameTable::Get(const ArrayPtr<char16_t> &key, int32_t start, int32_t len) override
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| key | const [ArrayPtr](../../../system/arrayptr/)\<char16_t\>\& | 検索する名前を含む文字配列。 |
| start | **int32_t** | 名前の最初の文字を示す、配列内の0ベースインデックス。 |
| len | **int32_t** | 名前の文字数。 |

### 戻り値

文字列がまだ内部化されていない場合は **nullptr**、それ以外は内部化された文字列です。**len** がゼロの場合、[String::Empty](../../../system/string/empty/) が返されます。

## See Also

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [String](../../../system/string/)
* Class [NameTable](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)