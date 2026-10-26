---
title: ReadOnlySpan
second_title: Aspose.Slides for C++ API 參考
description: 用於在 Span 類別內部的前置作業。
type: docs
weight: 1210
url: /zh-hant/system/readonlyspan/
---
## ReadOnlySpan 類別

供在 [Span](../span/) 類別 中使用。

```cpp
template<typename T>class ReadOnlySpan : public System::Details::SpanCore<const T, ReadOnlySpan<T>, Span<T>>
```

### 模板參數

| 參數 | 說明 |
| --- | --- |
| T | 跨度中元素的類型。本類別提供一種型別安全的方式，以唯讀方式處理連續的物件序列。它可用於封裝陣列、堆疊陣列或原始指標，同時保持界限檢查。[ReadOnlySpan](./) 不擁有其指向的記憶體——它僅是現有記憶體的視圖。 |
## 方法

| 方法 | 說明 |
| --- | --- |
|  [ReadOnlySpan](./readonlyspan/)(const [Span](../span/)\<T\>\&) | 從一般跨度建構唯讀跨度。 |
| static [ThisType](./) [to_ReadOnlySpan](./to_readonlyspan/)(const typename BaseType::ArrayPtrT\&) | 將陣列轉換為 [ReadOnlySpan](./)。 |
## 備註


表示任意記憶體的唯讀連續區域。

## 另請參閱

* 命名空間 [System](../)
* 函式庫 [Aspose.Slides](../../)