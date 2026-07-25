---
title: NetworkStream()
second_title: Aspose.Slides for C++ API リファレンス
description: 新しいインスタンスを作成します。
type: docs
weight: 170
url: /ja/system.net.sockets/networkstream/networkstream/
---
## NetworkStream::NetworkStream(System::SharedPtr\<System::Net::Sockets::Socket\>) コンストラクタ

新しいインスタンスを作成します。

```cpp
System::Net::Sockets::NetworkStream::NetworkStream(System::SharedPtr<System::Net::Sockets::Socket> socket)
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| socket | [System::SharedPtr](../../../system/sharedptr/)\<[System::Net::Sockets::Socket](../../socket/)\> | 送受信に使用されるソケットです。 |

## NetworkStream::NetworkStream(System::SharedPtr\<System::Net::Sockets::Socket\>, System::IO::FileAccess, bool) コンストラクタ

新しいインスタンスを作成します。

```cpp
System::Net::Sockets::NetworkStream::NetworkStream(System::SharedPtr<System::Net::Sockets::Socket> socket, System::IO::FileAccess access, bool ownsSocket)
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| socket | [System::SharedPtr](../../../system/sharedptr/)\<[System::Net::Sockets::Socket](../../socket/)\> | 送受信に使用されるソケットです。 |
| access | [System::IO::FileAccess](../../../system.io/fileaccess/) | 指定されたソケットに対してインスタンスに付与されるアクセス種別を指定します。 |
| ownsSocket | **bool** | 値が true の場合、現在のインスタンスが指定されたソケットの所有権を取得するかどうかを示す値です。 |

## NetworkStream::NetworkStream(System::SharedPtr\<System::Net::Sockets::Socket\>, bool) コンストラクタ

新しいインスタンスを作成します。

```cpp
System::Net::Sockets::NetworkStream::NetworkStream(System::SharedPtr<System::Net::Sockets::Socket> socket, bool ownsSocket)
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| socket | [System::SharedPtr](../../../system/sharedptr/)\<[System::Net::Sockets::Socket](../../socket/)\> | 送受信に使用されるソケットです。 |
| ownsSocket | **bool** | 値が true の場合、現在のインスタンスが指定されたソケットの所有権を取得するかどうかを示す値です。 |

## 参照

* 列挙体 [FileAccess](../../../system.io/fileaccess/)
* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [Socket](../../socket/)
* クラス [NetworkStream](../)
* 名前空間 [System::Net::Sockets](../../)
* ライブラリ [Aspose.Slides](../../../)