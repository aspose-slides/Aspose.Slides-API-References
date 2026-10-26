---
title: TraceEventType
second_title: Aspose.Slides for C++ API リファレンス
description: トレースの原因となったイベントの種類を識別します。
type: docs
weight: 157
url: /ja/system.diagnostics/traceeventtype/
---
## TraceEventType 列挙型

トレースを引き起こしたイベントの種類を識別します。

```cpp
enum class TraceEventType
```

### 値

| 名前 | 値 | 説明 |
| --- | --- | --- |
| Critical | 1 | 致命的なエラーまたはアプリケーションのクラッシュ。 |
| Error | 2 | 回復可能なエラー。 |
| Warning | 4 | 致命的でない問題。 |
| Information | 8 | 情報メッセージ。 |
| Verbose | 16 | デバッグトレース。 |
| Start | 256 | 論理操作の開始。 |
| Stop | 512 | 論理操作の停止。 |
| Suspend | 1024 | 論理操作の一時停止。 |
| Resume | 2048 | 論理操作の再開。 |
| Transfer | 4096 | 相関 ID の変更。 |

## 参照

* 名前空間 [System::Diagnostics](../)
* ライブラリ [Aspose.Slides](../../)