---
title: Cancel()
second_title: Aspose.Slides for C++ API リファレンス
description: キャンセル要求を通知します。
type: docs
weight: 40
url: /ja/system.threading/cancellationtokensource/cancel/
---
## CancellationTokenSource::Cancel() メソッド


キャンセル要求を通知します。

```cpp
void System::Threading::CancellationTokenSource::Cancel()
```

## 備考



登録されたすべてのコールバックが呼び出されます。

以降の [get_IsCancellationRequested()](../get_iscancellationrequested/) の呼び出しは true を返します。

この呼び出し中にコールバックは同期的に実行されます。

## 参照

* クラス [CancellationTokenSource](../)
* 名前空間 [System::Threading](../../)
* ライブラリ [Aspose.Slides](../../../)