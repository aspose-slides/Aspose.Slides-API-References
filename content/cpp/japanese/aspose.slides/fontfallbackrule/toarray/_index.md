---
title: ToArray()
second_title: Aspose.Slides for C++ API リファレンス
description: このルールのすべてのフォールバックフォントを含む配列を作成し、返します。
type: docs
weight: 144
url: /ja/aspose.slides/fontfallbackrule/toarray/
---
## FontFallBackRule::ToArray() メソッド


このルールのすべてのフォールバックフォントを含む配列を作成し、返します。

```cpp
System::ArrayPtr<System::String> Aspose::Slides::FontFallBackRule::ToArray() override
```


### 戻り値

[System::String](../../../system/string/) の配列
## 補足



```cpp
// フォントのリストを含むルールを作成します。
auto newRule = MakeObject<FontFallBackRule>(0x3040, 0x309F, u"MS Mincho, MS Gothic, Tahoma, Times New Roman");
// すべてのフォント名を配列として取得します。
ArrayPtr<String> fontNames = newRule->ToArray();
```


## FontFallBackRule::ToArray(int32_t, int32_t) メソッド


リストの指定された範囲からすべてのフォールバックフォントを含む配列を作成し、返します。

```cpp
System::ArrayPtr<System::String> Aspose::Slides::FontFallBackRule::ToArray(int32_t startIndex, int32_t count) override
```


### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| startIndex | **int32_t** | 追加する最初のフォントのインデックス。 |
| count | **int32_t** | 追加するフォントの数。 |

### 戻り値

[System::String](../../../system/string/) の配列
## 補足



```cpp
// フォントのリストを含むルールを作成します。
auto newRule = MakeObject<FontFallBackRule>(0x3040, 0x309F, u"MS Mincho, MS Gothic, Tahoma, Times New Roman");
// 最後の2つのフォント名を配列として取得します。
ArrayPtr<String> fontNames = newRule->ToArray(2, 2);
```


## 参照

* Typedef [ArrayPtr](../../../system/arrayptr/)
* クラス [String](../../../system/string/)
* クラス [FontFallBackRule](../)
* 名前空間 [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)