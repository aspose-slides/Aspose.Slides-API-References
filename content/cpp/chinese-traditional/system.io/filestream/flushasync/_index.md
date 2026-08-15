---
title: FlushAsync()
second_title: Aspose.Slides for C++ API 參考文件
description: 非同步清除此流的所有緩衝區，將任何緩衝的資料寫入底層裝置，並監視取消請求。
type: docs
weight: 157
url: /zh-hant/system.io/filestream/flushasync/
---
## FileStream::FlushAsync(const Threading::CancellationToken\&) 方法


非同步地清除此流的所有緩衝區，將任何緩衝的資料寫入底層裝置，並監視取消請求。

```cpp
TaskPtr System::IO::FileStream::FlushAsync(const Threading::CancellationToken &cancellationToken) override
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| cancellationToken | const [Threading::CancellationToken](../../../system.threading/cancellationtoken/)\& | 用於監視取消請求的代幣。 |

### 返回值

表示非同步刷新操作的任務。

## 相關參考

* Typedef [TaskPtr](../../../system/taskptr/)
* 類別 [CancellationToken](../../../system.threading/cancellationtoken/)
* 類別 [FileStream](../)
* 命名空間 [System::IO](../../)
* 函式庫 [Aspose.Slides](../../../)