---
title: ToArray()
second_title: Aspose.Slides for C++ API リファレンス
description: このルールのすべてのフォールバックフォントを含む配列を作成し、返します。
type: docs
weight: 105
url: /ja/aspose.slides/ifontfallbackrule/toarray/
---
## IFontFallBackRule::ToArray() メソッド

このルールのすべてのフォールバックフォントを含む配列を作成し、返します。

```cpp
virtual System::ArrayPtr<System::String> Aspose::Slides::IFontFallBackRule::ToArray()=0
```

### 戻り値

[System::String](../../../system/string/) の配列

## 備考



```cpp
// フォントのリストを含むルールを作成します。
auto newRule = MakeObject<FontFallBackRule>(0x3040, 0x309F, u"MS Mincho, MS Gothic, Tahoma, Times New Roman");
//すべてのフォント名を配列として取得
ArrayPtr<String> fontNames = newRule->ToArray();
```

## IFontFallBackRule::ToArray(int32_t, int32_t) メソッド

リスト内の指定された範囲からすべてのフォールバックフォントを含む配列を作成し、返します。

```cpp
virtual System::ArrayPtr<System::String> Aspose::Slides::IFontFallBackRule::ToArray(int32_t startIndex, int32_t count)=0
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| startIndex | **int32_t** | 追加する最初のフォントのインデックス。 |
| count | **int32_t** | 追加するフォントの数。 |

### 戻り値

[System::String](../../../system/string/) の配列

## 備考



```cpp
// フォントのリストを含むルールを作成します。
auto newRule = MakeObject<FontFallBackRule>(0x3040, 0x309F, u"MS Mincho, MS Gothic, Tahoma, Times New Roman");
//最後の2つのフォント名を配列として取得します
ArrayPtr<String> fontNames = newRule->ToArray(2, 2);
```

## 参照

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [String](../../../system/string/)
* Class [IFontFallBackRule](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)