---
title: Span
second_title: Aspose.Slides C++ API 參考
description: "表示一個與 C++20 的 std::span 類似的任意記憶體連續區域。"
type: docs
weight: 1262
url: /zh-hant/system/span/
---
## Span 類別


表示一個與 C++20 的 std::span 類似的任意記憶體連續區域。

```cpp
template<typename T>class Span : public System::Details::SpanCore<T, Span<T>, Span<T>>
```


### 模板參數

| 參數 | 說明 |
| --- | --- |
| T | span 中元素的類型。此類別提供一種型別安全的方式來處理連續的物件序列。它可用於封裝陣列、堆疊陣列或原始指標，同時保持邊界檢查。[Span](./) 不擁有它指向的記憶體 - 它只是對現有記憶體的視圖。 |
## 方法

| 方法 | 說明 |
| --- | |
| void [Clear](./clear/)() const | 透過將所有元素設為預設值來清除 span 的內容。 |
| void [Fill](./fill/)(const T\&) const | 以指定的值填滿 span。 |
| static [ThisType](./) [to_Span](./to_span/)(const typename BaseType::ArrayPtrT\&) | 將陣列轉換為 [Span](./)。 |

## 另請參閱

* 命名空間 [System](../)
* 函式庫 [Aspose.Slides](../../)