---
title: ConfigureAwait()
second_title: Aspose.Slides for C++ API リファレンス
description: このタスクの awaiter を構成します。
type: docs
weight: 79
url: /ja/system.threading.tasks/valuetask/configureawait/
---
## ValueTask::ConfigureAwait(bool) const メソッド

このタスクの awaiter を構成します。

```cpp
Runtime::CompilerServices::ConfiguredValueTaskAwaitable System::Threading::Tasks::ValueTask::ConfigureAwait(bool continueOnCapturedContext) const
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| continueOnCapturedContext | **bool** | true は、続行をキャプチャされた元のコンテキストに戻すことを試みます。そうでない場合は false。 |

### 戻り値

ConfiguredValueTaskAwaitable このタスクに対して awaiter の動作を構成するオブジェクトです。

## 参照

* クラス [ConfiguredValueTaskAwaitable](../../../system.runtime.compilerservices/configuredvaluetaskawaitable/)
* クラス [ValueTask](../)
* 名前空間 [System::Threading::Tasks](../../)
* ライブラリ [Aspose.Slides](../../../)