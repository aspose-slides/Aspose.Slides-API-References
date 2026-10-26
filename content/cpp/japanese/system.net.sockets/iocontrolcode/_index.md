---
title: IOControlCode
second_title: Aspose.Slides for C++ API リファレンス
description: IO 制御コードを列挙します。
type: docs
weight: 157
url: /ja/system.net.sockets/iocontrolcode/
---
## IOControlCode 列挙型


[IO](../../system.io/) の制御コードを列挙します。

```cpp
enum class IOControlCode : int64_t
```

### 値

| 名前 | 値 | 説明 |
| --- | --- | --- |
| AsyncIO | -2147195267 | ソケットの非同期 I/O モードを有効または無効にします。 |
| NonBlockingIO | -2147195266 | ソケットをノンブロッキングとしてマークします。 |
| DataToRead | 1074030207 | 読み取り可能なバイト数を返します。 |
| OobDataRead | 1074033415 | 受信待ちの帯域外データに関する情報を返します。 |
| AssociateHandle | -2013265919 | このソケットを、指定されたコンパニオン インターフェイスのハンドルに関連付けます。 |
| EnableCircularQueuing | 671088642 | 受信メッセージキューが満杯の場合、最も古いキューイングされたデータグラムを受信したものと置き換えます。 |
| Flush | 671088644 | このソケットに関連付けられた送信キューの現在の内容を破棄します。 |
| GetBroadcastAddress | 1207959557 | 現在のソケットのアドレス ファミリに対するブロードキャスト アドレスを含む SOCKADDR 構造体を返します。 |
| GetExtensionFunctionPointer | -939524090 | 関連付けられたサービス プロバイダーがサポートする、指定された拡張関数へのポインタを取得します。 |
| GetQos | -939524089 | ソケットに関連付けられた QOS 構造体を取得します。 |
| GetGroupQos | -939524088 | ソケット グループの QOS 属性を返します。 |
| MultipointLoopback | -2013265911 | ローカル コンピュータ上のアプリケーションが（同じソケットである必要はなく）マルチキャスト セッションで送信したデータが、ループバック インターフェイス上のマルチキャスト 宛先グループに参加したソケットで受信されるかどうかを制御します。 |
| MulticastScope | -2013265910 | マルチキャスト パケットがルータで転送される回数（TTL、またはホップ カウントとも呼ばれる）を制御します。 |
| SetQos | -2013265909 | ソケットの QOS 属性を設定します。 |
| SetGroupQos | -2013265908 | ソケット グループの QOS 属性を設定します。 |
| TranslateHandle | -939524083 | コンパニオン インターフェイスのコンテキストで有効なソケットのハンドルを返します。 |
| RoutingInterfaceQuery | -939524076 | 指定されたリモート アドレスに接続するために使用できるインターフェイス アドレスを返します。 |
| RoutingInterfaceChange | -2013265899 | リモート エンドポイントにアクセスするために使用されるローカル インターフェイスが変更されたときに通知を受け取ることを有効にします。 |
| AddressListQuery | 1207959574 | ソケットがバインドできるローカル インターフェイスの一覧を返します。 |
| AddressListChange | 671088663 | ソケットのプロトコル ファミリに対するローカル インターフェイスの一覧が変更されたときに通知を受け取ることを有効にします。 |
| QueryTargetPnpHandle | 1207959576 | 基礎となるプロバイダーの SOCKET ハンドルを取得します。 |
| NamespaceChange | -2013265895 | 名前空間クエリが無効になるとき、ソケットが通知を受け取るかどうかを制御します。 |
| AddressListSort | -939524071 | IPv6 と IPv4 の宛先アドレスの一覧をソートし、接続に使用できる最適なアドレスを決定します。 |
| ReceiveAll | -1744830463 | ネットワーク上のすべての IPv4 パケットを受信できるようにします。 |
| ReceiveAllMulticast | -1744830462 | ネットワーク上のすべてのマルチキャスト IPv4 パケットを受信できるようにします。 |
| ReceiveAllIgmpMulticast | -1744830461 | ネットワーク上のすべての IGMP パケットを受信できるようにします。 |
| KeepAliveValues | -1744830460 | TCP キープアライブ パケットの送信とその送信間隔を制御します。 |
| AbsorbRouterAlert | -1744830459 | この値は Winsock 2 の 'SIO_ABSORB_RTRALERT' 定数と等価です。 |
| UnicastInterface | -1744830458 | 送信ユニキャスト パケットに使用するインターフェイスを設定します。 |
| LimitBroadcasts | -1744830457 | この値は Winsock 2 の 'SIO_LIMIT_BROADCASTS' 定数と等価です。 |
| BindToInterface | -1744830456 | ソケットを指定されたインターフェイス インデックスにバインドします。 |
| MulticastInterface | -1744830455 | 送信マルチキャスト パケットに使用するインターフェイスを設定します。 |
| AddMulticastGroupOnInterface | -1744830454 | インデックスで識別されるインターフェイスを使用してマルチキャスト グループに参加します。 |
| DeleteMulticastGroupFromInterface | -1744830453 | ソケットをマルチキャスト グループから削除します。 |

## 参照

* 名前空間 [System::Net::Sockets](../)
* ライブラリ [Aspose.Slides](../../)