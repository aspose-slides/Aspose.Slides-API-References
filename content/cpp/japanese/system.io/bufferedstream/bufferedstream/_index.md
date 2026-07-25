---
title: BufferedStream()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定されたストリームをラップし、4096 バイトのバッファを使用する BufferedStream オブジェクトを構築します。
type: docs
weight: 1
url: /ja/system.io/bufferedstream/bufferedstream/
---
## BufferedStream::BufferedStream(const SharedPtr\<Stream\>\&) constructor

指定されたストリームをラップし、4096 バイトのバッファを使用する [BufferedStream](../) オブジェクトを構築します。

```cpp
System::IO::BufferedStream::BufferedStream(const SharedPtr<Stream> &stream)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| stream | const [SharedPtr](../../../system/sharedptr/)\<[Stream](../../stream/)\>\& | 基になる [Stream](../../stream/) オブジェクト |

## BufferedStream::BufferedStream(const SharedPtr\<Stream\>\&, int) constructor

指定されたストリームをラップし、指定されたサイズのバッファを使用する [BufferedStream](../) オブジェクトを構築します。

```cpp
System::IO::BufferedStream::BufferedStream(const SharedPtr<Stream> &stream, int bufferSize)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| stream | const [SharedPtr](../../../system/sharedptr/)\<[Stream](../../stream/)\>\& | 基になる [Stream](../../stream/) オブジェクト |
| bufferSize | int | バッファのサイズ（バイト単位） |

## 参照

* Typedef [SharedPtr](../../../system/sharedptr/)
* クラス [Stream](../../stream/)
* クラス [BufferedStream](../)
* 名前空間 [System::IO](../../)
* ライブラリ [Aspose.Slides](../../../)