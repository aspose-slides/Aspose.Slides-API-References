---
title: KeyValuePair()
second_title: Aspose.Slides for C++ API リファレンス
description: Null キーと値のペア初期化子。
type: docs
weight: 1
url: /ja/system.collections.generic/keyvaluepair/keyvaluepair/
---
## KeyValuePair::KeyValuePair() コンストラクタ

Null キーと値のペア初期化子。

```cpp
System::Collections::Generic::KeyValuePair<TKey, TValue>::KeyValuePair()
```

## KeyValuePair::KeyValuePair(const TKey\&, const TValue\&) コンストラクタ

コンストラクタ。

```cpp
System::Collections::Generic::KeyValuePair<TKey, TValue>::KeyValuePair(const TKey &key, const TValue &value)
```

### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| key | const TKey\& | キー。 |
| value | const TValue\& | 値。 |

## KeyValuePair::KeyValuePair(const std::pair\<OtherK, OtherV\>\&) コンストラクタ

型変換コンストラクタ。

```cpp
template<typename OtherK,typename OtherV> System::Collections::Generic::KeyValuePair<TKey, TValue>::KeyValuePair(const std::pair<OtherK, OtherV> &pair)
```

### テンプレート パラメータ

| Parameter | Description |
| --- | --- |
| OtherK | その他のキー型。 |
| OtherV | その他の値型。 |

### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| pair | const std::pair\<OtherK, OtherV\>\& | ペアの値。 |

## 参照

* クラス [KeyValuePair](../)
* 名前空間 [System::Collections::Generic](../../)
* ライブラリ [Aspose.Slides](../../../)