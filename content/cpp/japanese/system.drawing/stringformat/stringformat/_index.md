---
title: StringFormat()
second_title: Aspose.Slides for C++ API リファレンス
description: StringFormat クラスの新しいインスタンスを構築します。
type: docs
weight: 1
url: /ja/system.drawing/stringformat/stringformat/
---
## StringFormat::StringFormat() コンストラクタ


[StringFormat](../) クラスの新しいインスタンスを構築します。

```cpp
System::Drawing::StringFormat::StringFormat()
```

## StringFormat::StringFormat(StringFormatFlags, int32_t) コンストラクタ


[StringFormat](../) クラスの新しいインスタンスを、指定されたフォーマットフラグと **int32_t** 言語で構築します。

```cpp
System::Drawing::StringFormat::StringFormat(StringFormatFlags options, int32_t language=0)
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| options | [StringFormatFlags](../../stringformatflags/) | 作成されるオブジェクトが表す文字列フォーマットを指定する StringFormatFlags 列挙体値のビット単位の組み合わせ |
| language | **int32_t** | テキストの言語 |

## StringFormat::StringFormat(const SharedPtr\<StringFormat\>\&) コンストラクタ


コピーコンストラクタ。

```cpp
System::Drawing::StringFormat::StringFormat(const SharedPtr<StringFormat> &format)
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| format | const [SharedPtr](../../../system/sharedptr/)\<[StringFormat](../)\>\& | コピー元の [StringFormat](../) オブジェクト |

## 参照

* 列挙体 [StringFormatFlags](../../stringformatflags/)
* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [StringFormat](../)
* 名前空間 [System::Drawing](../../)
* ライブラリ [Aspose.Slides](../../../)