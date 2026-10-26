---
title: Dispose()
second_title: Aspose.Slides for C++ API リファレンス
description: 登録を破棄し、関連付けられた CancellationTokenSource からコールバックを削除します。このメソッドを呼び出した後、関連付けられた CancellationTokenSource がキャンセルされたときに登録されたコールバックは呼び出されなくなります。
type: docs
weight: 1
url: /ja/system.threading/cancellationtokenregistration/dispose/
---
## CancellationTokenRegistration::Dispose() メソッド

登録を破棄し、関連付けられた [CancellationTokenSource](../../cancellationtokensource/) からコールバックを削除します。このメソッドを呼び出した後、関連付けられた [CancellationTokenSource](../../cancellationtokensource/) がキャンセルされたときに登録されたコールバックは呼び出されなくなります。

```cpp
void System::Threading::CancellationTokenRegistration::Dispose()
```

## 備考

このメソッドを複数回呼び出しても安全です。後続の呼び出しは何の影響も与えません。

## 参照

* クラス [CancellationTokenRegistration](../)
* 名前空間 [System::Threading](../../)
* ライブラリ [Aspose.Slides](../../../)