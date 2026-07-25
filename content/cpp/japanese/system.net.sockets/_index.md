---
title: "System::Net::Sockets"
second_title: Aspose.Slides for C++ API リファレンス
description: 
type: docs
weight: 729
url: /ja/system.net.sockets/
---
## クラス

| クラス | 説明 |
| --- | --- |
| [Details_SocketException](./details_socketexception/) | ソケットエラーが発生したときにスローされる例外を表します。このクラスのインスタンスを手動で作成しないでください。代わりに SocketException クラスを使用してください。SocketException クラスのインスタンスを [System::SmartPtr](../system/smartptr/) にラップしないでください。 |
| [IPPacketInformation](./ippacketinformation/) | パケットに関する情報を表します。このクラスのオブジェクトは [System::MakeObject()](../system/makeobject/) 関数を使用してのみ割り当てるべきです。このタイプのインスタンスをスタック上で作成したり operator new を使用したりしないでください。そうしないとランタイムエラーやアサーション違反が発生します。常にこのクラスを [System::SmartPtr](../system/smartptr/) ポインタでラップし、そのポインタを関数への引数として渡してください。 |
| [LingerOption](./lingeroption/) | ソケットが Close() または Close() メソッドの呼び出し後も接続されたままになるかどうかを指定します。また、データ送信が継続する場合にソケットが接続されたままでいる期間も指定します。このクラスのオブジェクトは [System::MakeObject()](../system/makeobject/) 関数を使用してのみ割り当てるべきです。このタイプのインスタンスをスタック上で作成したり operator new を使用したりしないでください。そうしないとランタイムエラーやアサーション違反が発生します。常にこのクラスを [System::SmartPtr](../system/smartptr/) ポインタでラップし、そのポインタを関数への引数として渡してください。 |
| [NetworkStream](./networkstream/) | ネットワークアクセス用のデータの基礎ストリームを提供します。このクラスのオブジェクトは [System::MakeObject()](../system/makeobject/) 関数を使用してのみ割り当てるべきです。このタイプのインスタンスをスタック上で作成したり operator new を使用したりしないでください。そうしないとランタイムエラーやアサーション違反が発生します。常にこのクラスを [System::SmartPtr](../system/smartptr/) ポインタでラップし、そのポインタを関数への引数として渡してください。 |
| [Socket](./socket/) | [Socket](./socket/) クラスは Berkeley sockets インターフェイスを実装しています。 |
| [TcpClient](./tcpclient/) | TCP ネットワークサービス用のクライアントを表します。このクラスのオブジェクトは [System::MakeObject()](../system/makeobject/) 関数を使用してのみ割り当てるべきです。このタイプのインスタンスをスタック上で作成したり operator new を使用したりしないでください。そうしないとランタイムエラーやアサーション違反が発生します。常にこのクラスを [System::SmartPtr](../system/smartptr/) ポインタでラップし、そのポインタを関数への引数として渡してください。 |
| [TcpListener](./tcplistener/) | TCP ネットワークサービス用のリスナーを表します。このクラスのオブジェクトは [System::MakeObject()](../system/makeobject/) 関数を使用してのみ割り当てるべきです。このタイプのインスタンスをスタック上で作成したり operator new を使用したりしないでください。そうしないとランタイムエラーやアサーション違反が発生します。常にこのクラスを [System::SmartPtr](../system/smartptr/) ポインタでラップし、そのポインタを関数への引数として渡してください。 |
| [UdpClient](./udpclient/) | ユーザーデータグラムプロトコル (UDP) ネットワークサービスを提供します。このクラスのオブジェクトは [System::MakeObject()](../system/makeobject/) 関数を使用してのみ割り当てるべきです。このタイプのインスタンスをスタック上で作成したり operator new を使用したりしないでください。そうしないとランタイムエラーやアサーション違反が発生します。常にこのクラスを [System::SmartPtr](../system/smartptr/) ポインタでラップし、そのポインタを関数への引数として渡してください。 |

## 関数

| 関数 | 説明 |
| --- | --- |
| **bool** [operator==](./operator_equal_equal/)([IPPacketInformation](./ippacketinformation/), [IPPacketInformation](./ippacketinformation/)) |  |
| **bool** [operator!=](./operator_not_equal/)([IPPacketInformation](./ippacketinformation/), [IPPacketInformation](./ippacketinformation/)) |  |

## 列挙型

| 列挙型 | 説明 |
| --- | --- |
| [SocketType](./sockettype/) | ソケットタイプを列挙します。 |
| [AddressFamily](./addressfamily/) | アドレスファミリを列挙します。 |
| [IOControlCode](./iocontrolcode/) | [IO](../system.io/) の制御コードを列挙します。 |
| [ProtocolFamily](./protocolfamily/) | プロトコルファミリを列挙します。 |
| [ProtocolType](./protocoltype/) | プロトコルタイプを列挙します。 |
| [SelectMode](./selectmode/) | ソケットのステータスをポーリングするモードを指定します。 |
| [SocketError](./socketerror/) | ソケットエラータイプを列挙します。 |
| [SocketFlags](./socketflags/) | ソケットメッセージの定数値を提供します。 |
| [SocketOptionLevel](./socketoptionlevel/) | '[Socket](./socket/)' クラスのソケットオプションレベルを定義します。 |
| [SocketOptionName](./socketoptionname/) | [Socket](./socket/) クラスのソケットオプション名を定義します。 |
| [SocketShutdown](./socketshutdown/) | [Socket.Shutdown](./socket/shutdown/) メソッドで使用される定数を定義します。 |

## 型エイリアス

| 型エイリアス | 説明 |
| --- | --- |
| [SocketException](./socketexception/) |  |