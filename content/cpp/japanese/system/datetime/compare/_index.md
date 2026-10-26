---
title: Compare()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定された DateTime クラスのインスタンスが表す 2 つの値を比較し、時間軸上でのそれらの相対的な位置を示す値を返します。
type: docs
weight: 846
url: /ja/system/datetime/compare/
---
## DateTime::Compare(DateTime, DateTime) メソッド

指定された [DateTime](../) クラスのインスタンスが表す 2 つの値を比較し、時間軸上でのそれらの相対的な位置を示す値を返します。

```cpp
static constexpr int System::DateTime::Compare(DateTime t1, DateTime t2)
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| t1 | [DateTime](../) | 最初の比較対象 |
| t2 | [DateTime](../) | 2 番目の比較対象 |

### 戻り値

**t1** が **t2** よりも早い場合は 0 未満の値、**t1** が **t2** と同じ場合は 0、**t1** が **t2** よりも遅い場合は 0 超の値を返します。

## 関連項目

* クラス [DateTime](../)
* 名前空間 [System](../../)
* ライブラリ [Aspose.Slides](../../../)