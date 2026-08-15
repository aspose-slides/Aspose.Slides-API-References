---
title: MemoryMarshal
second_title: Aspose.Slides for C++ API 參考文件
description: 提供記憶體編組實作。僅為相容已翻譯的程式碼而存在，因為 C++ 端不支援受管理的程式碼。這是一個靜態類型，沒有實例服務。絕不可以任何方式建立其實例。
type: docs
weight: 27
url: /zh-hant/system.runtime.interopservices/memorymarshal/
---
## MemoryMarshal 類別


提供記憶體編組實作。僅為相容已翻譯的程式碼而存在，因為 C++ 端不支援受管理的程式碼。這是一個靜態類型，沒有實例服務。絕不可以任何方式建立其實例。

```cpp
class MemoryMarshal
```

## 方法

| 方法 | 說明 |
| --- | --- |
| static [Span](../../system/span/)\<**uint8_t**\> [AsBytes](./asbytes/)(const [Span](../../system/span/)\<T\>\&) | 將一個原始類型 T 的 [Span](../../system/span/) 轉換為位元組的 [Span](../../system/span/)。 |
| static [Span](../../system/span/)\<TTo\> [Cast](./cast/)(const [Span](../../system/span/)\<TFrom\>\&) | 將一個原始類型 TFrom 的 [Span](../../system/span/) 轉換為另一個原始類型 TTo。 |
## 另請參閱

* 命名空間 [System::Runtime::InteropServices](../)
* 程式庫 [Aspose.Slides](../../)