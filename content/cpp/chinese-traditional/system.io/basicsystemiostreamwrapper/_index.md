---
title: BasicSystemIOStreamWrapper
second_title: Aspose.Slides for C++ API 參考
description: "代表一個類似 std::iostream 的包裝器，使用 BasicSystemIOStreamBuf 作為內部緩衝區。"
type: docs
weight: 53
url: /zh-hant/system.io/basicsystemiostreamwrapper/
---
## BasicSystemIOStreamWrapper 類別

代表一個類似 std::iostream 的包裝器，使用 [BasicSystemIOStreamBuf](../basicsystemiostreambuf/) 作為內部緩衝區。

```cpp
template<typename Elem,typename Traits>class BasicSystemIOStreamWrapper : public std::basic_iostream<Elem, std::char_traits<Elem>>
```

## Methods

| Method | Description |
| --- | --- |
| void [AssignRV](./assignrv/)([BasicSystemIOStreamWrapper](./)\&&) | 在移動建構函式和移動指派運算子中使用，以重設指標並呼叫 [swap()](./swap/)。 |
|  [BasicSystemIOStreamWrapper](./basicsystemiostreamwrapper/)([SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>, [SystemIOStreamWrappingMode](../systemiostreamwrappingmode/)) | 建構 [BasicSystemIOStreamWrapper](./) 的新實例。 |
|  [BasicSystemIOStreamWrapper](./basicsystemiostreamwrapper/)(const [BasicSystemIOStreamWrapper](./)\&) | 拷貝建構函式。已刪除。 |
|  [BasicSystemIOStreamWrapper](./basicsystemiostreamwrapper/)([BasicSystemIOStreamWrapper](./)\&&) | 移動建構函式。 |
| [BasicSystemIOStreamWrapper](./)\& [operator=](./operator_equal/)(const [BasicSystemIOStreamWrapper](./)\&) | 拷貝指派運算子。已刪除。 |
| [BasicSystemIOStreamWrapper](./)\& [operator=](./operator_equal/)([BasicSystemIOStreamWrapper](./)\&&) | 移動指派運算子。 |
| void [swap](./swap/)([BasicSystemIOStreamWrapper](./)\&) | 如果兩者不相等，呼叫 swap *this 和 **right**。 |

## Typedefs

| Typedef | Description |
| --- | --- |
| [char_type](./char_type/) |  |
| [traits_type](./traits_type/) |  |
| [Mybase](./mybase/) |  |
| [Mysb](./mysb/) |  |

## See Also

* 命名空間 [System::IO](../)
* 函式庫 [Aspose.Slides](../../)