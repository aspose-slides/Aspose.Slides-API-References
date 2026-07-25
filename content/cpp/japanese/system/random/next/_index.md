---
title: Next()
second_title: Aspose.Slides for C++ API リファレンス
description: int32 の最大値未満の非負の乱数を返します。
type: docs
weight: 27
url: /ja/system/random/next/
---
## Random::Next() メソッド

int32 の最大値未満の非負の乱数を返します。

```cpp
virtual int32_t System::Random::Next()
```

## Random::Next(int32_t) メソッド

指定された最大値未満の非負の乱数を返します。

```cpp
virtual int32_t System::Random::Next(int32_t maxValue)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| maxValue | **int32_t** | メソッドによって生成される値はこの値未満になります |

## Random::Next(int32_t, int32_t) メソッド

指定された範囲内の乱数を返します。

```cpp
virtual int32_t System::Random::Next(int32_t minValue, int32_t maxValue)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| minValue | **int32_t** | メソッドによって生成される値はこの値より大きくなります |
| maxValue | **int32_t** | メソッドによって生成される値はこの値未満になります |

## 参照

* クラス [Random](../)
* 名前空間 [System](../../)
* ライブラリ [Aspose.Slides](../../../)