---
title: BasicSystemIOStreamBuf
second_title: Aspose.Slides for C++ API 參考文件
description: "表示一個緩衝區，封裝 System::IO::Stream 類似的串流，並允許它們作為 std::iostream 類似的串流內部緩衝區使用。"
type: docs
weight: 40
url: /zh-hant/system.io/basicsystemiostreambuf/
---
## BasicSystemIOStreamBuf 類別

表示一個緩衝區，封裝 [System::IO::Stream](../stream/)-類似的串流，並允許它們作為 std::iostream-類似的串流內部緩衝區使用。

```cpp
template<typename Elem,typename Traits>class BasicSystemIOStreamBuf : public std::basic_streambuf<Elem, std::char_traits<Elem>>
```

## 方法

| 方法 | 說明 |
| --- | --- |
| void [AssignRV](./assignrv/)([BasicSystemIOStreamBuf](./)\&&) | 在移動建構函式與移動指派運算子中使用，以重設指標並呼叫 [swap()](./swap/)。 |
| explicit  [BasicSystemIOStreamBuf](./basicsystemiostreambuf/)() | 建立 [BasicSystemIOStreamBuf](./) 的新實例。 |
| explicit  [BasicSystemIOStreamBuf](./basicsystemiostreambuf/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>\&, [SystemIOStreamWrappingMode](../systemiostreamwrappingmode/), const std::locale\&) | 建立 [BasicSystemIOStreamBuf](./) 的新實例。 |
|  [BasicSystemIOStreamBuf](./basicsystemiostreambuf/)(const [BasicSystemIOStreamBuf](./)\&) | 複製建構函式。已刪除。 |
|  [BasicSystemIOStreamBuf](./basicsystemiostreambuf/)([BasicSystemIOStreamBuf](./)\&&) | 移動建構函式。 |
| [BasicSystemIOStreamBuf](./)\& [operator=](./operator_equal/)(const [BasicSystemIOStreamBuf](./)\&) | 複製指派運算子。已刪除。 |
| [BasicSystemIOStreamBuf](./)\& [operator=](./operator_equal/)([BasicSystemIOStreamBuf](./)\&&) | 移動指派運算子。 |
| void [swap](./swap/)([BasicSystemIOStreamBuf](./)\&) | 若它們不相等，則呼叫交換 *this 與 right。 |
|  [~BasicSystemIOStreamBuf](./~basicsystemiostreambuf/)() override | 解構函式。 |

## 型別別名

| 型別別名 | 說明 |
| --- | --- |
| [char_type](./char_type/) |  |
| [traits_type](./traits_type/) |  |
| [Mysb](./mysb/) |  |
| [int_type](./int_type/) |  |
| [pos_type](./pos_type/) |  |
| [off_type](./off_type/) |  |

## 另請參閱

* 命名空間 [System::IO](../)
* 函式庫 [Aspose.Slides](../../)