---
title: BasicSystemIStreamWrapper
second_title: Aspose.Slides for C++ API リファレンス
description: "内部バッファとして BasicSystemIOStreamBuf を使用する std::istream ライクなラッパーを表します。"
type: docs
weight: 66
url: /ja/system.io/basicsystemistreamwrapper/
---
## BasicSystemIStreamWrapper クラス


内部バッファとして [BasicSystemIOStreamBuf](../basicsystemiostreambuf/) を使用する std::istream のようなラッパーを表します。

```cpp
template<typename Elem,typename Traits>class BasicSystemIStreamWrapper : public std::basic_istream<Elem, std::char_traits<Elem>>
```

## メソッド

| メソッド | 説明 |
| --- | --- |
| void [AssignRV](./assignrv/)([BasicSystemIStreamWrapper](./)\&&) | ムーブ コンストラクタおよび ムーブ 代入演算子でポインタをリセットし、[swap()](./swap/) を呼び出すために使用されます。 |
| [BasicSystemIStreamWrapper](./basicsystemistreamwrapper/)([SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>, [SystemIOStreamWrappingMode](../systemiostreamwrappingmode/)) | 新しい [BasicSystemIStreamWrapper](./) のインスタンスを構築します。 |
| [BasicSystemIStreamWrapper](./basicsystemistreamwrapper/)(const [BasicSystemIStreamWrapper](./)\&) | コピー コンストラクタ。削除されています。 |
| [BasicSystemIStreamWrapper](./basicsystemistreamwrapper/)([BasicSystemIStreamWrapper](./)\&&) | ムーブ コンストラクタ。 |
| [BasicSystemIStreamWrapper](./)\& [operator=](./operator_equal/)(const [BasicSystemIStreamWrapper](./)\&) | コピー 代入演算子。削除されています。 |
| [BasicSystemIStreamWrapper](./)\& [operator=](./operator_equal/)([BasicSystemIStreamWrapper](./)\&&) | ムーブ 代入演算子。 |
| void [swap](./swap/)([BasicSystemIStreamWrapper](./)\&) | *this と **right** が等しくない場合に swap を呼び出します。 |

## 型定義

| 型定義 | 説明 |
| --- | --- |
| [char_type](./char_type/) |  |
| [traits_type](./traits_type/) |  |
| [Mybase](./mybase/) |  |
| [Mysb](./mysb/) |  |

## 参照

* 名前空間 [System::IO](../)
* ライブラリ [Aspose.Slides](../../)