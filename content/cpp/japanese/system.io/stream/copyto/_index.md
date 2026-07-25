---
title: CopyTo()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定されたストリームにバイトをコピーします。
type: docs
weight: 209
url: /ja/system.io/stream/copyto/
---
## Stream::CopyTo(const SharedPtr\<Stream\>\&) メソッド

指定されたストリームにバイトをコピーします。

```cpp
void System::IO::Stream::CopyTo(const SharedPtr<Stream> &destination)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| destination | const [SharedPtr](../../../system/sharedptr/)\<[Stream](../)\>\& | データがコピーされる[Stream](../)。 |

## Stream::CopyTo(const SharedPtr\<Stream\>\&, int32_t) メソッド

指定されたバッファサイズを使用して、指定されたストリームにバイトをコピーします。

```cpp
void System::IO::Stream::CopyTo(const SharedPtr<Stream> &destination, int32_t buffer_size)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| destination | const [SharedPtr](../../../system/sharedptr/)\<[Stream](../)\>\& | データがコピーされる[Stream](../)。 |
| buffer_size | **int32_t** | バッファのサイズ。 |

## 参照

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)