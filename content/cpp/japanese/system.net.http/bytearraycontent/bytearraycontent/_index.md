---
title: ByteArrayContent()
second_title: Aspose.Slides for C++ API リファレンス
description: 新しいインスタンスを作成します。
type: docs
weight: 1
url: /ja/system.net.http/bytearraycontent/bytearraycontent/
---
## ByteArrayContent::ByteArrayContent(System::ArrayPtr\<uint8_t\>) コンストラクタ

新しいインスタンスを作成します。

```cpp
System::Net::Http::ByteArrayContent::ByteArrayContent(System::ArrayPtr<uint8_t> content)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| content | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | 新しいインスタンスを初期化するために使用されるコンテンツ。 |

## ByteArrayContent::ByteArrayContent(System::ArrayPtr\<uint8_t\>, int32_t, int32_t) コンストラクタ

新しいインスタンスを作成します。

```cpp
System::Net::Http::ByteArrayContent::ByteArrayContent(System::ArrayPtr<uint8_t> content, int32_t offset, int32_t count)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| content | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | 新しいインスタンスを初期化するために使用されるコンテンツ。 |
| offset | **int32_t** | 指定された配列内のバイト単位のオフセット。 |
| count | **int32_t** | 'offset' パラメータから開始する、指定された配列内のバイト数。 |

## 参照

* 型定義 [ArrayPtr](../../../system/arrayptr/)
* クラス [ByteArrayContent](../)
* 名前空間 [System::Net::Http](../../)
* ライブラリ [Aspose.Slides](../../../)