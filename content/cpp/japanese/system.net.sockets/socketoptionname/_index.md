---
title: SocketOptionName
second_title: Aspose.Slides for C++ API リファレンス
description: Socket クラスのソケットオプション名を定義します。
type: docs
weight: 248
url: /ja/system.net.sockets/socketoptionname/
---
## SocketOptionName 列挙型

[Socket](../socket/) クラスのソケットオプション名を定義します。

```cpp
enum class SocketOptionName
```

### 値

| 名前 | 値 | 説明 |
| --- | --- | --- |
| Debug | 1 | デバッグ情報を記録します。 |
| AcceptConnection | 2 | ソケットが受信接続を待ち受けているかどうかを示します。 |
| ReuseAddress | 4 | ソケットを既に使用中のアドレスにバインドできるかどうかを示します。 |
| KeepAlive | 8 | ソケット接続に対して「Keep-Alive」パケットを有効にします。 |
| DontRoute | 16 | パケットがインターフェースのアドレスへ直接送信されるかどうかを示します。 |
| Broadcast | 32 | ソケットがブロードキャストメッセージを送信できるかどうかを示します。 |
| UseLoopback | 64 | 可能な場合はハードウェアをバイパスします。 |
| Linger | 128 | システムはデータが送信できるまで、クローズの試みでプロセスをブロックします。 |
| OutOfBandInline | 256 | 帯外データを通常のデータストリームで受信します。 |
| DontLinger | n/a | ソケットが残存せずに閉じられるかどうかを示します。 |
| ExclusiveAddressUse | n/a | ソケットはバインドされたアドレスを排他的に使用します。 |
| SendBuffer | 4097 | 送信バッファサイズを指定します。 |
| ReceiveBuffer | 4098 | 受信バッファサイズを指定します。 |
| SendLowWater | 4099 | 送信操作に必要な最小データ量を指定します。 |
| ReceiveLowWater | 4100 | 受信操作に必要な最小データ量を指定します。 |
| SendTimeout | 4101 | 同期送信操作のタイムアウトを指定します。 |
| ReceiveTimeout | 4102 | 同期受信操作のタイムアウトを指定します。 |
| Error | 4103 | エラー状態を返し、クリアします。 |
| Type | 4104 | ソケットのタイプを返します。 |
| ReuseUnicastPort | 12295 | システムがアウトバウンド接続のためにエフェメラルポートの割り当てを遅延させるかどうかを示します。 |
| MaxConnections | 2147483647 | このオプションはサポートされていません。リスニング時の最大キュー長を指定するために使用されていました。 |
| IPOptions | 1 | 送信データグラムに挿入すべき IP オプションを指定します。 |
| HeaderIncluded | 2 | ヘッダーが送信データグラムに含まれます。 |
| TypeOfService | 3 | IP ヘッダーのサービスフィールドのタイプを変更します。 |
| IpTimeToLive | 4 | IP の TTL（有効期限）です。 |
| MulticastInterface | 9 | 送信マルチキャストパケット用のインターフェースを設定します。 |
| MulticastTimeToLive | 10 | IP マルチキャストの TTL（有効期限）です。 |
| MulticastLoopback | 11 | IP マルチキャストのループバックです。 |
| AddMembership | 12 | IP グループメンバーシップを追加します。 |
| DropMembership | 13 | IP グループメンバーシップを削除します。 |
| DontFragment | 14 | IP データグラムをフラグメントしません。 |
| AddSourceMembership | 15 | IP グループ/ソースに参加します。 |
| DropSourceMembership | 16 | IP グループ/ソースを離脱します。 |
| BlockSource | 17 | IP グループ/ソースをブロックします。 |
| UnblockSource | 18 | IP グループ/ソースのブロックを解除します。 |
| PacketInformation | 19 | IPv4 のパケット情報を受信します。 |
| HopLimit | 21 | パケットの HOP カウントを含む整数を提供します。 |
| IPProtectionLevel | 23 | IPv6 ソケットを指定されたスコープに制限できるようにします。 |
| IPv6Only | 27 | ソケットは IPv6 パケットの送受信のみが許可されています。 |
| NoDelay | 1 | 送信パケットの統合に対する Nagle アルゴリズムを無効にします。 |
| BsdUrgent | 2 | RFC-1222 で定義された緊急データを使用します。 |
| Expedited | 2 | RFC-1222 で定義された高速データを使用します。 |
| NoChecksum | 1 | チェックサムをゼロに設定した UDP データグラムを送信します。 |
| ChecksumCoverage | 20 | UDP のチェックサムカバレッジを設定または取得します。 |
| UpdateAcceptContext | 28683 | リスニングソケットと同じプロパティでクライアントソケットを更新します。 |
| UpdateConnectContext | 28688 | リスニングソケットと同じプロパティでクライアントソケットを更新します。 |

## 参照

* 名前空間 [System::Net::Sockets](../)
* ライブラリ [Aspose.Slides](../../)