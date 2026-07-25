---
title: idx_get()
second_title: Aspose.Slides の C++ API リファレンス
description: 指定されたインデックスの IMathElement を取得します。
type: docs
weight: 27
url: /ja/aspose.slides.mathtext/mathblock/idx_get/
---
## MathBlock::idx_get(int32_t) method


指定されたインデックスで[IMathElement](../../imathelement/)を取得します。

```cpp
System::SharedPtr<IMathElement> Aspose::Slides::MathText::MathBlock::idx_get(int32_t index) override
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| index | **int32_t** | 項目のゼロベースインデックス |

### 戻り値

数式要素。

## 備考



例: 
```cpp
auto mathBlock = System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"x"));
auto firstElem = mathBlock->idx_get(0);
```

## 参照

* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [IMathElement](../../imathelement/)
* クラス [MathBlock](../)
* 名前空間 [Aspose::Slides::MathText](../../)
* ライブラリ [Aspose.Slides](../../../)