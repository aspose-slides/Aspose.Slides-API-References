---
title: BasicSystemIStreamWrapper
second_title: Aspose.Slides for C++ API 參考
description: "表示一個類似 std::istream 的包裝器，使用 BasicSystemIOStreamBuf 作為內部緩衝區。"
type: docs
weight: 66
url: /zh-hant/system.io/basicsystemistreamwrapper/
---
## BasicSystemIStreamWrapper 類別

表示一個類似 std::istream 的包裝器，使用 [BasicSystemIOStreamBuf](../basicsystemiostreambuf/) 作為內部緩衝區。

```cpp
template<typename Elem,typename Traits>class BasicSystemIStreamWrapper : public std::basic_istream<Elem, std::char_traits<Elem>>
```

## 方法

| 方法 | 說明 |
| --- | --- |
| void [AssignRV](./assignrv/)([BasicSystemIStreamWrapper](./)\&&) | 用於移動建構函式和移動指派運算子，以重設指標並呼叫 [swap()](./swap/)。 |
|  [BasicSystemIStreamWrapper](./basicsystemistreamwrapper/)([SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>, [SystemIOStreamWrappingMode](../systemiostreamwrappingmode/)) | 建立 [BasicSystemIStreamWrapper](./) 的新實例。 |
|  [BasicSystemIStreamWrapper](./basicsystemistreamwrapper/)(const [BasicSystemIStreamWrapper](./)\&) | 複製建構函式。已刪除。 |
|  [BasicSystemIStreamWrapper](./basicsystemistreamwrapper/)([BasicSystemIStreamWrapper](./)\&&) | 移動建構函式。 |
| [BasicSystemIStreamWrapper](./)\& [operator=](./operator_equal/)(const [BasicSystemIStreamWrapper](./)\&) | 複製指派運算子。已刪除。 |
| [BasicSystemIStreamWrapper](./)\& [operator=](./operator_equal/)([BasicSystemIStreamWrapper](./)\&&) | 移動指派運算子。 |
| void [swap](./swap/)([BasicSystemIStreamWrapper](./)\&) | 呼叫 swap *this 與 **right**，若它們不相等。 |
## 型別別名

| 型別別名 | 說明 |
| --- | --- |
| [char_type](./char_type/) |  |
| [traits_type](./traits_type/) |  |
| [Mybase](./mybase/) |  |
| [Mysb](./mysb/) |  |
## 另請參閱

* 命名空間 [System::IO](../)
* 函式庫 [Aspose.Slides](../../)