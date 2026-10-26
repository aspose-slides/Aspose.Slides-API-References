---
title: operator==()
second_title: Aspose.Slides for C++ API 參考
description: ResultValueTask 的相等運算子。
type: docs
weight: 131
url: /zh-hant/system.threading.tasks/resultvaluetask/operator_equal_equal/
---
## ResultValueTask::operator==(const ResultValueTask\&) const 方法


用於 [ResultValueTask](../) 的等號運算子。

```cpp
bool System::Threading::Tasks::ResultValueTask<T>::operator==(const ResultValueTask &other) const
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| other | const [ResultValueTask](../)\& | 與此實例比較的另一個 [ResultValueTask](../)。 |

### 返回值

bool True 如果兩個任務具有相同的結果值或引用相同的底層任務；否則為 false。

## 備註

如果任一實例包含直接結果值，則直接比較結果。否則，比較底層任務指針。

## 另請參閱

* 類別 [ResultValueTask](../)
* 命名空間 [System::Threading::Tasks](../../)
* 函式庫 [Aspose.Slides](../../../)