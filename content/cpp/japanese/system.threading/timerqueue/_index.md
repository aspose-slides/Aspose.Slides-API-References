---
title: TimerQueue
second_title: Aspose.Slides for C++ API リファレンス
description: タイマーオブジェクトを処理するキューです。これは単なる実装です。タイマーオブジェクトは自らそこに登録されるため、使用する際に自分で登録する必要はありません—代わりに Timer クラス API を使用してください。これはアクセス関数によってメモリ管理が行われるシングルトン型です。直接インスタンスを作成してはいけません。
type: docs
weight: 261
url: /ja/system.threading/timerqueue/
---
## TimerQueue クラス

[Timer](../timer/) オブジェクトを処理するキューです。これは単なる実装です。[Timer](../timer/) オブジェクトは自らそこに登録されますので、使用するために自分で登録する必要はありません – 代わりに [Timer](../timer/) クラス API を使用してください。これはアクセス関数によってメモリ管理が行われるシングルトン型です。直接インスタンスを作成してはいけません。

```cpp
class TimerQueue
```

## メソッド

| メソッド | 説明 |
| --- | --- |
| **bool** [Add](./add/)([Timer](../timer/) *) | キューにタイマーを登録します。 |
| **bool** [Delete](./delete/)([Timer](../timer/) *) | キューからタイマーを削除します。 |
| static [TimerQueue](./)\& [GetInstance](./getinstance/)() | 実装シングルトンです。 |
| static void [JoinWorkerThread](./joinworkerthread/)() | ワーカースレッドに参加します。必要に応じて無限に待機します。 |
| void [operator=](./operator_equal/)(const [TimerQueue](./)\&) | コピーできません。 |
|  [TimerQueue](./timerqueue/)(const [TimerQueue](./)\&) | コピーできません。 |

## 参照

* 名前空間 [System::Threading](../)
* ライブラリ [Aspose.Slides](../../)