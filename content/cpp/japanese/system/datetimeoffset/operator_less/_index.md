---
title: operator<()
second_title: Aspose.Slides for C++ API リファレンス
description: 現在のオブジェクトが、指定された DateTimeOffset オブジェクトが表す値よりも以前の日付と時刻の値を表すかどうかを判断します。
type: docs
weight: 560
url: /ja/system/datetimeoffset/operator_less/
---
## DateTimeOffset::operator<(const DateTimeOffset\&) const メソッド


現在のオブジェクトが、指定された [DateTimeOffset](../) オブジェクトが表す値よりも以前の日付と時刻の値を表すかどうかを判断します。

```cpp
bool System::DateTimeOffset::operator<(const DateTimeOffset &other) const
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| other | const [DateTimeOffset](../)\& | 現在のオブジェクトと比較するための [DateTimeOffset](../) オブジェクト |

## 戻り値

現在のオブジェクトが表す日付と時刻の値が **other** が表す値よりも早い場合は true、そうでない場合は false

## DateTimeOffset::operator<(std::nullptr_t) const メソッド




```cpp
constexpr bool System::DateTimeOffset::operator<(std::nullptr_t) const
```

## 参照

* クラス [DateTimeOffset](../)
* 名前空間 [System](../../)
* ライブラリ [Aspose.Slides](../../../)