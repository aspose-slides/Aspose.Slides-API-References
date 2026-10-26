---
title: CancellationTokenRegistration
second_title: Aspose.Slides for C++ API リファレンス
description: キャンセル トークン コールバックの登録を表します。
type: docs
weight: 27
url: /ja/system.threading/cancellationtokenregistration/
---
## CancellationTokenRegistration クラス


キャンセル トークン コールバックの登録を表します。

```cpp
class CancellationTokenRegistration
```

## メソッド

| メソッド | 説明 |
| --- | --- |
| void [Dispose](./dispose/)() | 登録を破棄し、関連付けられた [CancellationTokenSource](../cancellationtokensource/) からコールバックを削除します。このメソッドを呼び出した後、関連付けられた [CancellationTokenSource](../cancellationtokensource/) がキャンセルされたときに登録されたコールバックはもう呼び出されません。 |
## 備考


このクラスは、キャンセル トークンからコールバックの登録解除を可能にします。破棄されると、関連付けられた [CancellationTokenSource](../cancellationtokensource/) からコールバックが削除されます。 
このクラスは直接作成すべきではなく、[CancellationToken](../cancellationtoken/) の登録メソッドによって返されます。 

## 参照

* 名前空間 [System::Threading](../)
* ライブラリ [Aspose.Slides](../../)