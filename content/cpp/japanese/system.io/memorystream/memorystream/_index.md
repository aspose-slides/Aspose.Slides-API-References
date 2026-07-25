---
title: MemoryStream()
second_title: Aspose.Slides for C++ API リファレンス
description: 初期容量が0のMemoryStreamクラスの新しいインスタンスを作成します。
type: docs
weight: 1
url: /ja/system.io/memorystream/memorystream/
---
## MemoryStream::MemoryStream() コンストラクタ

[MemoryStream](../) クラスの新しいインスタンスを作成します。初期容量は 0 です。

```cpp
System::IO::MemoryStream::MemoryStream()
```

## MemoryStream::MemoryStream(int) コンストラクタ

[MemoryStream](../) クラスの新しいインスタンスを作成します。指定されたサイズのメモリ バッファに基づくストリームを表します。

```cpp
System::IO::MemoryStream::MemoryStream(int capacity_)
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| capacity_ | int | 作成されるオブジェクトが表すストリームに関連付けられたメモリ バッファのサイズ（バイト単位） |

## MemoryStream::MemoryStream(const ArrayPtr\<uint8_t\>\&, bool) コンストラクタ

[MemoryStream](../) クラスの新しいインスタンスを作成します。指定されたメモリ バッファに接続されたメモリ ストリームを表します。パラメーターはストリームが書き込み可能かどうかを指定します。

```cpp
System::IO::MemoryStream::MemoryStream(const ArrayPtr<uint8_t> &content, bool writable=1)
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| content | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | 作成されるオブジェクトが表すストリームの基盤となるメモリ バッファとして使用されるバイト配列 |
| writable | **bool** | ストリームを書き込み可能にすべきかどうかを指定します |

## MemoryStream::MemoryStream(const ArrayPtr\<uint8_t\>\&, int, int, bool, bool) コンストラクタ

[MemoryStream](../) クラスの新しいインスタンスを作成します。指定されたインデックスから開始し、指定された要素数を含む、指定されたメモリ バッファのセグメントに接続されたメモリ ストリームを表します。パラメーターはストリームが書き込み可能かどうか、およびメソッド GetBytes() を呼び出すことができるかどうかを指定します。

```cpp
System::IO::MemoryStream::MemoryStream(const ArrayPtr<uint8_t> &content, int index, int count, bool writable=1, bool publiclyVisible=false)
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| content | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | 作成されるオブジェクトが表すストリームの基盤となるメモリ バッファとして使用されるセグメントのバイト配列 |
| index | int | **content** の中でセグメントが開始する要素の 0 から始まるインデックス |
| count | int | セグメントに含まれる **content** の要素数 |
| writable | **bool** | ストリームを書き込み可能にすべきかどうかを指定します |
| publiclyVisible | **bool** | 基礎となるメモリ バッファを GetByte() メソッドの呼び出し元に公開するかどうかを指定します |

## 参照

* typedef [ArrayPtr](../../../system/arrayptr/)
* クラス [MemoryStream](../)
* 名前空間 [System::IO](../../)
* ライブラリ [Aspose.Slides](../../../)