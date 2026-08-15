---
title: DownloadData()
second_title: Aspose.Slides for C++ API 參考
description: 以下載指定的資源作為位元組陣列。
type: docs
weight: 79
url: /zh-hant/system.net/webclient/downloaddata/
---
## WebClient::DownloadData(const String\&) const 方法

下載指定的資源作為位元組陣列。

```cpp
ByteArrayPtr System::Net::WebClient::DownloadData(const String &address) const
```

### 參數

| 參數 | 型別 | 說明 |
| --- | --- | --- |
| address | const [String](../../../system/string/)\& | 資源的 URI。 |

### 傳回值

包含請求資源的位元組陣列。

## WebClient::DownloadData(const SharedPtr\<Uri\>\&) const 方法

下載指定的資源作為位元組陣列。

```cpp
ByteArrayPtr System::Net::WebClient::DownloadData(const SharedPtr<Uri> &address) const
```

### 參數

| 參數 | 型別 | 說明 |
| --- | --- | --- |
| address | const [SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\>\& | 資源的 URI。 |

### 傳回值

包含請求資源的位元組陣列。

## 另請參閱

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* 類別 [String](../../../system/string/)
* 類別 [WebClient](../)
* 類別 [Uri](../../../system/uri/)
* 命名空間 [System::Net](../../)
* Library [Aspose.Slides](../../../)