---
title: operator==()
second_title: Aspose.Slides for C++ API リファレンス
description: ResultValueTask の等価演算子。
type: docs
weight: 131
url: /ja/system.threading.tasks/resultvaluetask/operator_equal_equal/
---
## ResultValueTask::operator==(const ResultValueTask\&) const メソッド

等価演算子 [ResultValueTask](../) 用。

```cpp
bool System::Threading::Tasks::ResultValueTask<T>::operator==(const ResultValueTask &other) const
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| other | const [ResultValueTask](../)\& | このインスタンスと比較するための他の [ResultValueTask](../)。 |

### 戻り値

bool 両方のタスクが同じ結果値を持つか、同じ基礎タスクを参照している場合は true。それ以外の場合は false。

## 備考

いずれかのインスタンスが直接の結果値を含む場合、結果を直接比較します。それ以外の場合は、基礎タスクのポインタを比較します。

## 参照

* クラス [ResultValueTask](../)
* 名前空間 [System::Threading::Tasks](../../)
* ライブラリ [Aspose.Slides](../../../)