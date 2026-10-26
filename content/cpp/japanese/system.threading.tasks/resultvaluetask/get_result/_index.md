---
title: get_Result()
second_title: Aspose.Slides for C++ API リファレンス
description: 完了したタスクの結果を取得します。
type: docs
weight: 66
url: /ja/system.threading.tasks/resultvaluetask/get_result/
---
## ResultValueTask::get_Result() メソッド


完了したタスクの結果を取得します。

```cpp
T System::Threading::Tasks::ResultValueTask<T>::get_Result()
```


### 戻り値

T 結果の値。
## 備考



タスクが ResultTask<T> によって裏付けられている場合、このメソッドは結果を待機し、キャッシュします。以降の呼び出しは待機せずにキャッシュされた値を返します。 

## 参照

* クラス [ResultValueTask](../)
* 名前空間 [System::Threading::Tasks](../../)
* ライブラリ [Aspose.Slides](../../../)