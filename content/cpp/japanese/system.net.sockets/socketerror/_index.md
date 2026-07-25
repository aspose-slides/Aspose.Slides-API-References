---
title: SocketError
second_title: Aspose.Slides for C++ API リファレンス
description: ソケットエラーの種類を列挙します。
type: docs
weight: 209
url: /ja/system.net.sockets/socketerror/
---
## SocketError 列挙体

ソケットエラーの種類を列挙します。

```cpp
enum class SocketError
```

### 値

| 名前 | 値 | 説明 |
| --- | --- | --- |
| Success | 0 | ソケット操作が正常に完了しました。 |
| SocketError | -1 | 特定されていないソケットエラーが発生しました。 |
| Interrupted | 10004 | ブロックされたソケット呼び出しがキャンセルされました。 |
| AccessDenied | 10013 | ソケットへのアクセスが拒否されました。 |
| Fault | 10014 | 無効なポインタアドレスが検出されました。 |
| InvalidArgument | 10022 | 無効な引数が提供されました。 |
| TooManyOpenSockets | 10024 | 基になるソケットプロバイダーで開かれているソケットが多すぎます。 |
| WouldBlock | 10035 | ノンブロッキングソケットで操作をすぐに完了できません。 |
| InProgress | 10036 | ブロックされる操作が進行中です。 |
| AlreadyInProgress | 10037 | ノンブロッキングソケットで既に実行中の操作があります。 |
| NotSocket | 10038 | ソケットでない対象にソケット操作を呼び出そうとしました。 |
| DestinationAddressRequired | 10039 | 必要なアドレスがソケット操作から省略されています。 |
| MessageSize | 10040 | データグラムが長すぎます。 |
| ProtocolType | 10041 | このソケットはプロトコルタイプをサポートしていません。 |
| ProtocolOption | 10042 | 未知、無効、またはサポートされていないオプションまたはレベルが使用されています。 |
| ProtocolNotSupported | 10043 | プロトコルが実装されていないか、構成されていません。 |
| SocketNotSupported | 10044 | アドレスファミリが指定されたソケットをサポートしていません。 |
| OperationNotSupported | 10045 | プロトコルファミリがアドレスファミリをサポートしていません。 |
| ProtocolFamilyNotSupported | 10046 | プロトコルファミリが実装されていないか、構成されていません。 |
| AddressFamilyNotSupported | 10047 | 指定されたアドレスファミリはサポートされていません。 |
| AddressAlreadyInUse | 10048 | アドレスは一度しか使用できません。 |
| AddressNotAvailable | 10049 | 選択された IP アドレスはこのコンテキストで有効ではありません。 |
| NetworkDown | 10050 | ネットワークが利用できません。 |
| NetworkUnreachable | 10051 | リモートホストへのルートが存在しません。 |
| NetworkReset | 10052 | アプリケーションがタイムアウトした接続に 'Keep-Alive' を設定しようとしました。 |
| ConnectionAborted | 10053 | 接続が中止されました。 |
| ConnectionReset | 10054 | 接続がリモートピアによってリセットされました。 |
| NoBufferSpaceAvailable | 10055 | ソケット操作用の空きバッファ領域が利用できません。 |
| IsConnected | 10056 | ソケットは既に接続されています。 |
| NotConnected | 10057 | アプリケーションがデータの送受信を試みましたが、ソケットが接続されていません。 |
| Shutdown | 10058 | ソケットが既に閉じられているため、データの送受信要求は禁止されています。 |
| TimedOut | 10060 | 接続試行がタイムアウトしたか、接続されたホストが応答しませんでした。 |
| ConnectionRefused | 10061 | リモートホストが接続を明示的に拒否しています。 |
| HostDown | 10064 | リモートホストがダウンしているため操作が失敗しました。 |
| HostUnreachable | 10065 | 指定されたホストへのネットワークルートが存在しません。 |
| ProcessLimit | 10067 | 基になるソケットプロバイダーを使用しているプロセスが多すぎます。 |
| SystemNotReady | 10091 | ネットワークサブシステムが利用できません。 |
| VersionNotSupported | 10092 | 基になるソケットプロバイダーのバージョンが範囲外です。 |
| NotInitialized | 10093 | 基になるソケットプロバイダーが初期化されていません。 |
| Disconnecting | 10101 | 正常なシャットダウンが進行中です。 |
| TypeNotFound | 10109 | 指定されたクラスが見つかりません。 |
| HostNotFound | 11001 | 指定されたホストが不明です。 |
| TryAgain | 11002 | ホスト名が解決できません。 |
| NoRecovery | 11003 | エラーが回復不能であるか、要求されたデータベースが見つかりません。 |
| NoData | 11004 | 要求された名前または IP アドレスがネームサーバに見つかりません。 |

## 参照

* 名前空間 [System::Net::Sockets](../)
* ライブラリ [Aspose.Slides](../../)