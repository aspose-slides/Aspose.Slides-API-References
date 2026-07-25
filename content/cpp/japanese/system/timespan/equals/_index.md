---
title: Equals()
second_title: Aspose.Slides for C++ API リファレンス
description: 現在のオブジェクトが表す時間間隔が、指定されたオブジェクトが表す時間間隔と等しいかどうかを判断します。
type: docs
weight: 40
url: /ja/system/timespan/equals/
---
## TimeSpan::Equals(TimeSpan) const メソッド

現在のオブジェクトが表す時間間隔が、指定されたオブジェクトが表す時間間隔と等しいかどうかを判断します。

```cpp
constexpr bool System::TimeSpan::Equals(TimeSpan value) const
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | [TimeSpan](../) | 現在のオブジェクトと比較するための [TimeSpan](../) オブジェクト |

### 戻り値

現在のオブジェクトと指定されたオブジェクトが同じ時間間隔を表す場合は true、そうでなければ false

## TimeSpan::Equals(const SharedPtr\<Object\>\&) const メソッド

現在のオブジェクトが表す時間間隔が、指定されたオブジェクトが表す時間間隔と等しいかどうかを判断します。

```cpp
bool System::TimeSpan::Equals(const SharedPtr<Object> &obj) const
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| obj | const [SharedPtr](../../sharedptr/)\<[Object](../../object/)\>\& | 現在のオブジェクトと比較するための [TimeSpan](../) オブジェクト |

### 戻り値

現在のオブジェクトと指定されたオブジェクトが同じ時間間隔を表す場合は true、そうでなければ false

## TimeSpan::Equals(TimeSpan, TimeSpan) メソッド

指定されたオブジェクトが同じ時間間隔を表す場合は true、そうでなければ false を返します。

```cpp
static constexpr bool System::TimeSpan::Equals(TimeSpan a, TimeSpan b)
```

## 参照

* Typedef [SharedPtr](../../sharedptr/)
* クラス [TimeSpan](../)
* クラス [Object](../../object/)
* 名前空間 [System](../../)
* ライブラリ [Aspose.Slides](../../../)