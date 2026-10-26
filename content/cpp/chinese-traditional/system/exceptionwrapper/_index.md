---
title: ExceptionWrapper
second_title: Aspose.Slides for C++ API 參考文件
description: 表示從 Exception 類別衍生的例外之包裝器的範本。
type: docs
weight: 833
url: /zh-hant/system/exceptionwrapper/
---
## ExceptionWrapper 類別


Template that represents wrapper of exceptions that are derived from Exception class.

```cpp
template<typename T>class ExceptionWrapper
```

## 方法

| 方法 | 說明 |
| --- | --- |
|  [ExceptionWrapper](./exceptionwrapper/)(std::nullptr_t) | 建立一個不代表任何例外的 [ExceptionWrapper](./) 類別 null 實例。 |
|  [ExceptionWrapper](./exceptionwrapper/)(const [ExceptionPtr](../exceptionptr/)\&) | 建立一個包含傳入指標的 [ExceptionWrapper](./) 類別實例。 |
|  [ExceptionWrapper](./exceptionwrapper/)(const [ExceptionWrapper](./)\&) | 複製建構函式。 |
|  [ExceptionWrapper](./exceptionwrapper/)([ExceptionWrapper](./)\&&) | 移動建構函式。 |
| explicit  [ExceptionWrapper](./exceptionwrapper/)(Args\&&...) | 將參數轉發至 Exception 類別的建構函式，並建立持有新 Exception 類別實例的智慧指標的建構函式。 |
| static void * [operator new](./operator_new/)(std::size_t) |  |
| static void * [operator new[]](./operator_new[]/)(std::size_t) |  |
|  [operator SharedPtr< Object >](./operator_sharedptr_less_object__greater/)() | 隱式轉型運算子至 SharedPtr<Object> |
| T * [operator->](./operator_minus_greater/)() const | 允許存取 Exception 物件的成員。 |
| [ExceptionWrapper](./)\& [operator=](./operator_equal/)(const [ExceptionWrapper](./)\&) | 指派運算子。 |
| [ExceptionWrapper](./)\& [operator=](./operator_equal/)([ExceptionWrapper](./)\&&) | 移動指派運算子。 |
| static const [System::TypeInfo](../typeinfo/)\& [Type](./type/)() | 取得 Exception 類型的 [System::TypeInfo](../typeinfo/) 物件的快捷方式。 |
## 型別別名

| 型別別名 | 說明 |
| --- | --- |
| [ExceptionType](./exceptiontype/) | 用於型別轉換函式。 |
## 另請參閱

* 命名空間 [System](../)
* 函式庫 [Aspose.Slides](../../)