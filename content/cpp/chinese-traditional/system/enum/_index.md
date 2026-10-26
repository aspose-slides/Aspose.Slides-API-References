---
title: Enum
second_title: Aspose.Slides for C++ API 參考文件
description: 提供對 enum 類型值執行某些操作的方法。這是一個沒有實例服務的靜態類型。絕不應以任何方式建立其實例。
type: docs
weight: 1587
url: /zh-hant/system/enum/
---
## 列舉結構

提供對 enum 類型值執行某些操作的方法。這是一個靜態類型，沒有實例服務。絕不應以任何方式建立其實例。

```cpp
template<class E,class Guard>class Enum
```

### 範本參數

| 參數 | 說明 |
| --- | --- |
| E | 類別所處理的 enum 值的類型 |
| Guard | 服務類型參數，其目的是確保 **E** 為可列舉類型 |
## 方法

| 方法 | 說明 |
| --- | --- |
| static int [Compare](./compare/)(E, T) | 對指定列舉常數的值執行算術比較。 |
| static std::enable_if\<std::is_same\<T, E\>::value||std::is_convertible\<T, [UnderlyingType](./underlyingtype/)\>::value, [String](../string/)\>::type [GetDescription](./getdescription/)(T) | 傳回具有指定值的列舉常數名稱。 |
| static std::enable_if\<std::is_same\<T, E\>::value||std::is_convertible\<T, [UnderlyingType](./underlyingtype/)\>::value, [String](../string/)\>::type [GetName](./getname/)(T) | 傳回具有指定值的列舉常數名稱。 |
| static [ArrayPtr](../arrayptr/)\<[String](../string/)\> [GetNames](./getnames/)() | 傳回包含列舉 **E** 所有成員名稱的陣列。 |
| static const [System::TypeInfo](../typeinfo/)\& [GetUnderlyingType](./getunderlyingtype/)() | 傳回列舉的底層類型。 |
| static [ArrayPtr](../arrayptr/)\<E\> [GetValues](./getvalues/)() | 傳回包含列舉 **E** 所有成員的陣列。 |
| static **bool** [HasFlag](./hasflag/)(E, E) | 判斷在指定 enum 值的位元表示中，是否已設定指定的位元。 |
| static **bool** [IsDefined](./isdefined/)(E) | 判斷指定值是否為列舉類型 **E** 的成員。 |
| static std::enable_if\<std::is_convertible\<T, [UnderlyingType](./underlyingtype/)\>::value, **bool**\>::type [IsDefined](./isdefined/)(T) | 判斷指定值是否為列舉類型 **T** 的成員。 |
| static **bool** [IsDefined](./isdefined/)(const [String](../string/)\&) | 判斷具有指定名稱的值是否為 enum **E** 成員之一。 |
| static E [Parse](./parse/)(const [String](../string/)\&, **bool**) | 將指定字串轉換為等價的 enum 常數。 |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, E\&) | 嘗試將指定字串轉換為等價的 enum 常數。 |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, **bool**, E\&) | 嘗試將指定字串轉換為等價的 enum 常數。 |
## 型別別名

| 型別別名 | 說明 |
| --- | --- |
| [UnderlyingType](./underlyingtype/) | 列舉底層類型的別名。 |

## 參見

* 名稱空間 [System](../)
* 函式庫 [Aspose.Slides](../../)