---
title: idx_get()
second_title: Aspose.Slides for C++ API リファレンス
description: 名前付きアイテムを取得します。
type: docs
weight: 1
url: /ja/system.data.common/dbdatareader/idx_get/
---
## DbDataReader::idx_get(String) メソッド

名前付きアイテムを取得します。

```cpp
virtual SharedPtr<Object> System::Data::Common::DbDataReader::idx_get(String name)=0
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| name | [String](../../../system/string/) | アイテム名。 |

### 戻り値

ボックス化されたアイテムの値。

## DbDataReader::idx_get(int) メソッド

インデックスでアイテムを取得します。

```cpp
virtual SharedPtr<Object> System::Data::Common::DbDataReader::idx_get(int ordinal)=0
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| ordinal | int | アイテムのインデックス。 |

### 戻り値

ボックス化されたアイテムの値。

## 参照

* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [Object](../../../system/object/)
* クラス [String](../../../system/string/)
* クラス [DbDataReader](../)
* 名前空間 [System::Data::Common](../../)
* ライブラリ [Aspose.Slides](../../../)