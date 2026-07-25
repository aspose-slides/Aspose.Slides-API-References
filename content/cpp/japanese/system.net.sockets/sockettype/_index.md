---
title: SocketType
second_title: Aspose.Slides for C++ API リファレンス
description: ソケットタイプを列挙します。
type: docs
weight: 131
url: /ja/system.net.sockets/sockettype/
---
## SocketType 列挙型

ソケットタイプを列挙します。

```cpp
enum class SocketType
```

### 値

| 名前 | 値 | 説明 |
| --- | --- | --- |
| Stream | 1 | データの重複や境界の保持なしで、信頼性があり双方向の接続指向バイトストリームをサポートするタイプ。 |
| Dgram | 2 | 固定最大長の接続レスで信頼性のないメッセージ（データグラム）をサポートするタイプ。 |
| Raw | 3 | 基盤となる転送プロトコルへのアクセスをサポートするタイプ。 |
| Rdm | 4 | 接続レスでメッセージ指向、信頼性のあるメッセージ配信をサポートし、データ内のメッセージ境界を保持するタイプ。 |
| Seqpacket | 5 | ネットワーク上で順序付けられたバイトストリームの接続指向かつ信頼性のある双方向転送を提供するタイプ。 |
| Unknown | n/a | 不明なタイプ。 |

## 参照

* 名前空間 [System::Net::Sockets](../)
* ライブラリ [Aspose.Slides](../../)