---
title: DownloadData()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定されたリソースをバイト配列としてダウンロードします。
type: docs
weight: 79
url: /ja/system.net/webclient/downloaddata/
---
## WebClient::DownloadData(const String\&) const method

指定されたリソースをバイト配列としてダウンロードします。

```cpp
ByteArrayPtr System::Net::WebClient::DownloadData(const String &address) const
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| address | const [String](../../../system/string/)\& | リソースの URI。 |

### 戻り値

要求されたリソースを含むバイト配列です。

## WebClient::DownloadData(const SharedPtr\<Uri\>\&) const method

指定されたリソースをバイト配列としてダウンロードします。

```cpp
ByteArrayPtr System::Net::WebClient::DownloadData(const SharedPtr<Uri> &address) const
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| address | const [SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\>\& | リソースの URI。 |

### 戻り値

要求されたリソースを含むバイト配列です。

## 参照

* 型定義 [ByteArrayPtr](../../../system/bytearrayptr/)
* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [String](../../../system/string/)
* クラス [WebClient](../)
* クラス [Uri](../../../system/uri/)
* 名前空間 [System::Net](../../)
* ライブラリ [Aspose.Slides](../../../)