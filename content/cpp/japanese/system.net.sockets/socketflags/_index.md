---
title: SocketFlags
second_title: Aspose.Slides for C++ API リファレンス
description: ソケットメッセージの定数値を提供します。
type: docs
weight: 222
url: /ja/system.net.sockets/socketflags/
---
## SocketFlags 列挙体

ソケットメッセージの定数値を提供します。

```cpp
enum class SocketFlags
```

### 値

| 名前 | 値 | 説明 |
| --- | --- | --- |
| None | 0 | この呼び出しではフラグが使用されていません。 |
| OutOfBand | 1 | 帯域外データが処理されています。 |
| Peek | 2 | 受信メッセージを先読みします。 |
| DontRoute | 4 | ルーティングテーブルを使用せずにメッセージを送信します。 |
| Truncated | 256 | メッセージが指定されたバッファに収まりきらないほど大きく、切り捨てられました。 |
| ControlDataTruncated | 512 | 制御データが64KBを超えていて内部バッファに収まらないため、切り捨てられました。 |
| Broadcast | 1024 | ブロードキャストパケットです。 |
| Multicast | 2048 | マルチキャストパケットです。 |
| Partial | 32768 | メッセージが部分的に送信または受信されました。 |

## 参照

* 名前空間 [System::Net::Sockets](../)
* ライブラリ [Aspose.Slides](../../)