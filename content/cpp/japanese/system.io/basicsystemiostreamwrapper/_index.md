---
title: BasicSystemIOStreamWrapper
second_title: Aspose.Slides for C++ API リファレンス
description: "内部バッファとして BasicSystemIOStreamBuf を使用した std::iostream ライクなラッパーを表します。"
type: docs
weight: 53
url: /ja/system.io/basicsystemiostreamwrapper/
---
## BasicSystemIOStreamWrapper クラス

内部バッファとして [BasicSystemIOStreamBuf](../basicsystemiostreambuf/) を使用した std::iostream ライクなラッパーを表します。

```cpp
template<typename Elem,typename Traits>class BasicSystemIOStreamWrapper : public std::basic_iostream<Elem, std::char_traits<Elem>>
```

## メソッド

| メソッド | 説明 |
| --- | --- |
| void [AssignRV](./assignrv/)([BasicSystemIOStreamWrapper](./)\&&) | ムーブコンストラクタとムーブ代入演算子で、ポインタをリセットし [swap()](./swap/) を呼び出すために使用されます。 |
|  [BasicSystemIOStreamWrapper](./basicsystemiostreamwrapper/)([SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>, [SystemIOStreamWrappingMode](../systemiostreamwrappingmode/)) | [BasicSystemIOStreamWrapper](./) の新しいインスタンスを構築します。 |
|  [BasicSystemIOStreamWrapper](./basicsystemiostreamwrapper/)(const [BasicSystemIOStreamWrapper](./)\&) | コピーコンストラクタ。削除されています。 |
|  [BasicSystemIOStreamWrapper](./basicsystemiostreamwrapper/)([BasicSystemIOStreamWrapper](./)\&&) | ムーブコンストラクタ。 |
| [BasicSystemIOStreamWrapper](./)\& [operator=](./operator_equal/)(const [BasicSystemIOStreamWrapper](./)\&) | コピー代入演算子。削除されています。 |
| [BasicSystemIOStreamWrapper](./)\& [operator=](./operator_equal/)([BasicSystemIOStreamWrapper](./)\&&) | ムーブ代入演算子。 |
| void [swap](./swap/)([BasicSystemIOStreamWrapper](./)\&) | 等しくない場合に *this と **right** を swap します。 |

## 型定義

| 型エイリアス | 説明 |
| --- | --- |
| [char_type](./char_type/) |  |
| [traits_type](./traits_type/) |  |
| [Mybase](./mybase/) |  |
| [Mysb](./mysb/) |  |

## 参照

* 名前空間 [System::IO](../)
* ライブラリ [Aspose.Slides](../../)