---
title: BasicSystemOStreamWrapper
second_title: Aspose.Slides for C++ API 參考
description: "表示一個類似 std::ostream 的封裝器，使用 BasicSystemIOStreamBuf 作為內部緩衝區。"
type: docs
weight: 79
url: /zh-hant/system.io/basicsystemostreamwrapper/
---
## BasicSystemOStreamWrapper 類別

表示一個類似 std::ostream 的包裝器，使用 [BasicSystemIOStreamBuf](../basicsystemiostreambuf/) 作為內部緩衝區。

```cpp
template<typename Elem,typename Traits>class BasicSystemOStreamWrapper : public std::basic_ostream<Elem, std::char_traits<Elem>>
```

## 方法

| 方法 | 說明 |
| --- | --- |
| void [AssignRV](./assignrv/)([BasicSystemOStreamWrapper](./)\&&) | 在移動建構函式與移動指派運算子中使用，以重設指標並呼叫 [swap()](./swap/)。 |
| [BasicSystemOStreamWrapper](./basicsystemostreamwrapper/)([SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>, [SystemIOStreamWrappingMode](../systemiostreamwrappingmode/)) | 建立 [BasicSystemOStreamWrapper](./) 的新實例。 |
| [BasicSystemOStreamWrapper](./basicsystemostreamwrapper/)(const [BasicSystemOStreamWrapper](./)\&) | 複製建構函式。已刪除。 |
| [BasicSystemOStreamWrapper](./basicsystemostreamwrapper/)([BasicSystemOStreamWrapper](./)\&&) | 移動建構函式。 |
| [BasicSystemOStreamWrapper](./)\& [operator=](./operator_equal/)(const [BasicSystemOStreamWrapper](./)\&) | 複製指派運算子。已刪除。 |
| [BasicSystemOStreamWrapper](./)\& [operator=](./operator_equal/)([BasicSystemOStreamWrapper](./)\&&) | 移動指派運算子。 |
| void [swap](./swap/)([BasicSystemOStreamWrapper](./)\&) | 呼叫 swap *this 與 **right**，如果它們不相等。 |

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