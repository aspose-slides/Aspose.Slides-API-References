---
title: operator<<()
second_title: Aspose.Slides for C++ API リファレンス
description: UTF-8 エンコーディングを使用してストリームにデータを挿入します。
type: docs
weight: 716
url: /ja/system.collections.generic/operator_less_less/
---
## System::Collections::Generic::operator<<(std::ostream\&, const KeyValuePair\<TKey, TValue\>\&) function

UTF-8 エンコーディングを使用してストリームにデータを挿入します。

```cpp
template<typename TKey,typename TValue> std::ostream & System::Collections::Generic::operator<<(std::ostream &stream, const KeyValuePair<TKey, TValue> &pair)
```

### テンプレートパラメータ

| パラメータ | 説明 |
| --- | --- |
| TKey | キー型。 |
| TValue | 値型。 |

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| stream | std::ostream\& | データを挿入する出力ストリーム。 |
| pair | const [KeyValuePair](../keyvaluepair/)\<TKey, TValue\>\& | [Data](../../system.data/) を挿入します。 |

### 戻り値

**stream**.

## System::Collections::Generic::operator<<(std::wostream\&, const KeyValuePair\<TKey, TValue\>\&) function

ストリームにデータを挿入します。

```cpp
template<typename TKey,typename TValue> std::wostream & System::Collections::Generic::operator<<(std::wostream &stream, const KeyValuePair<TKey, TValue> &pair)
```

### テンプレートパラメータ

| パラメータ | 説明 |
| --- | --- |
| TKey | キー型。 |
| TValue | 値型。 |

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| stream | std::wostream\& | データを挿入する出力ストリーム。 |
| pair | const [KeyValuePair](../keyvaluepair/)\<TKey, TValue\>\& | [Data](../../system.data/) を挿入します。 |

### 戻り値

**stream**.

## 関連項目

* クラス [KeyValuePair](../keyvaluepair/)
* 名前空間 [System::Collections::Generic](../)
* ライブラリ [Aspose.Slides](../../)