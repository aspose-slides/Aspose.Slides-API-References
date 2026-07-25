---
title: ConfigureAwait()
second_title: Aspose.Slides for C++ API リファレンス
description: この結果タスクの await がコンテキストのキャプチャに関してどのように動作すべきかを構成します。
type: docs
weight: 27
url: /ja/system.threading.tasks/resulttask/configureawait/
---
## ResultTask::ConfigureAwait(bool) const メソッド


この結果タスクの await がコンテキストのキャプチャに関してどのように動作すべきかを構成します。

```cpp
Runtime::CompilerServices::ConfiguredResultTaskAwaitable<T> System::Threading::Tasks::ResultTask<T>::ConfigureAwait(bool continueOnCapturedContext) const
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| continueOnCapturedContext | **bool** | キャプチャされたコンテキストで継続するかどうか |

### 戻り値

Runtime::CompilerServices::ConfiguredResultTaskAwaitable<T> 結果のための構成された awaitable

## 備考



これにより、async/await パターンのコンテキスト フローに対する細かな制御が可能になります。

## 参照

* クラス [ConfiguredResultTaskAwaitable](../../../system.runtime.compilerservices/configuredresulttaskawaitable/)
* クラス [ResultTask](../)
* 名前空間 [System::Threading::Tasks](../../)
* ライブラリ [Aspose.Slides](../../../)