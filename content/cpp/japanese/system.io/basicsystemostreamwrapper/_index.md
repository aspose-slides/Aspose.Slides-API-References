---
title: BasicSystemOStreamWrapper
second_title: Aspose.Slides for C++ API リファレンス
description: "内部バッファとして BasicSystemIOStreamBuf を使用する std::ostream ライクのラッパーを表します。"
type: docs
weight: 79
url: /ja/system.io/basicsystemostreamwrapper/
---
## BasicSystemOStreamWrapper クラス

内部バッファとして [BasicSystemIOStreamBuf](../basicsystemiostreambuf/) を使用する std::ostream ライクのラッパーを表します。

```cpp
template<typename Elem,typename Traits>class BasicSystemOStreamWrapper : public std::basic_ostream<Elem, std::char_traits<Elem>>
```

## メソッド

| メソッド | 説明 |
| --- | --- |
| void [AssignRV](./assignrv/)([BasicSystemOStreamWrapper](./)\&&) | ムーブコンストラクタおよびムーブ代入演算子で使用され、ポインタをリセットし [swap()](./swap/) を呼び出します。 |
|  [BasicSystemOStreamWrapper](./basicsystemostreamwrapper/)([SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>, [SystemIOStreamWrappingMode](../systemiostreamwrappingmode/)) | [BasicSystemOStreamWrapper](./) の新しいインスタンスを構築します。 |
|  [BasicSystemOStreamWrapper](./basicsystemostreamwrapper/)(const [BasicSystemOStreamWrapper](./)\&) | コピーコンストラクタ。削除済み。 |
|  [BasicSystemOStreamWrapper](./basicsystemostreamwrapper/)([BasicSystemOStreamWrapper](./)\&&) | ムーブコンストラクタ。 |
| [BasicSystemOStreamWrapper](./)\& [operator=](./operator_equal/)(const [BasicSystemOStreamWrapper](./)\&) | コピー代入演算子。削除済み。 |
| [BasicSystemOStreamWrapper](./)\& [operator=](./operator_equal/)([BasicSystemOStreamWrapper](./)\&&) | ムーブ代入演算子。 |
| void [swap](./swap/)([BasicSystemOStreamWrapper](./)\&) | 等しくない場合に *this と **right** を入れ替える呼び出しです。 |
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