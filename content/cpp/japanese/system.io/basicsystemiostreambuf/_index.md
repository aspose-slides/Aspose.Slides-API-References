---
title: BasicSystemIOStreamBuf
second_title: Aspose.Slides for C++ API リファレンス
description: "System::IO::Stream のようなストリームをラップし、std::iostream のようなストリームの内部バッファとして使用できるバッファを表します。"
type: docs
weight: 40
url: /ja/system.io/basicsystemiostreambuf/
---
## BasicSystemIOStreamBuf クラス


[System::IO::Stream](../stream/) のようなストリームをラップし、std::iostream のようなストリームの内部バッファとして使用できるバッファを表します。

```cpp
template<typename Elem,typename Traits>class BasicSystemIOStreamBuf : public std::basic_streambuf<Elem, std::char_traits<Elem>>
```

## メソッド

| Method | 説明 |
| --- | --- |
| void [AssignRV](./assignrv/)([BasicSystemIOStreamBuf](./)\&&) | ムーブコンストラクタおよびムーブ代入演算子で使用され、ポインタをリセットし [swap()](./swap/) を呼び出します。 |
| explicit  [BasicSystemIOStreamBuf](./basicsystemiostreambuf/)() | [BasicSystemIOStreamBuf](./) の新しいインスタンスを構築します。 |
| explicit  [BasicSystemIOStreamBuf](./basicsystemiostreambuf/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>\&, [SystemIOStreamWrappingMode](../systemiostreamwrappingmode/), const std::locale\&) | [BasicSystemIOStreamBuf](./) の新しいインスタンスを構築します。 |
|  [BasicSystemIOStreamBuf](./basicsystemiostreambuf/)(const [BasicSystemIOStreamBuf](./)\&) | コピーコンストラクタ。削除されています。 |
|  [BasicSystemIOStreamBuf](./basicsystemiostreambuf/)([BasicSystemIOStreamBuf](./)\&&) | ムーブコンストラクタ。 |
| [BasicSystemIOStreamBuf](./)\& [operator=](./operator_equal/)(const [BasicSystemIOStreamBuf](./)\&) | コピー代入演算子。削除されています。 |
| [BasicSystemIOStreamBuf](./)\& [operator=](./operator_equal/)([BasicSystemIOStreamBuf](./)\&&) | ムーブ代入演算子。 |
| void [swap](./swap/)([BasicSystemIOStreamBuf](./)\&) | *this と right を交換する呼び出し（等しくない場合）。 |
|  [~BasicSystemIOStreamBuf](./~basicsystemiostreambuf/)() override | デストラクタ。 |

## タイプ定義

| Typedef | 説明 |
| --- | --- |
| [char_type](./char_type/) |  |
| [traits_type](./traits_type/) |  |
| [Mysb](./mysb/) |  |
| [int_type](./int_type/) |  |
| [pos_type](./pos_type/) |  |
| [off_type](./off_type/) |  |

## 参照

* 名前空間 [System::IO](../)
* ライブラリ [Aspose.Slides](../../)