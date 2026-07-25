---
title: FromResult()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定された結果で正常に完了したタスクを作成します。
type: docs
weight: 144
url: /ja/system.threading.tasks/fromresult/
---
## System::Threading::Tasks::FromResult(TResult) 関数

指定された結果で正常に完了したタスクを作成します。

```cpp
template<typename TResult> RTaskPtr<TResult> System::Threading::Tasks::FromResult(TResult result)
```

### テンプレート パラメータ

| Parameter | Description |
| --- | --- |
| TResult | タスクの結果の型です。 |

### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| result | TResult | タスクを完了させる結果値。 |

### 戻り値

正常に完了したタスクです。

## 参照

* Typedef [RTaskPtr](../../system/rtaskptr/)
* Namespace [System::Threading::Tasks](../)
* Library [Aspose.Slides](../../)