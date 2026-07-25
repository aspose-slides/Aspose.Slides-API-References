---
title: ConfigureAwait()
second_title: Aspose.Slides for C++ API リファレンス
description: このタスクの awaiter を構成します。
type: docs
weight: 92
url: /ja/system.threading.tasks/resultvaluetask/configureawait/
---
## ResultValueTask::ConfigureAwait(bool) const メソッド

このタスクの awaiter を構成します。

```cpp
Runtime::CompilerServices::ConfiguredResultValueTaskAwaitable<T> System::Threading::Tasks::ResultValueTask<T>::ConfigureAwait(bool continueOnCapturedContext) const
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| continueOnCapturedContext | **bool** | true の場合、取得した元のコンテキストに続行をマーシャルしようとします。false の場合はそうしません。 |

### 戻り値

ConfiguredResultValueTaskAwaitable<T> このタスクの awaiter の動作を設定するオブジェクト。

## 参照

* クラス [ConfiguredResultValueTaskAwaitable](../../../system.runtime.compilerservices/configuredresultvaluetaskawaitable/)
* クラス [ResultValueTask](../)
* 名前空間 [System::Threading::Tasks](../../)
* ライブラリ [Aspose.Slides](../../../)