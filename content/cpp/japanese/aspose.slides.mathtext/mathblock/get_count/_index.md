---
title: get_Count()
second_title: Aspose.Slides の C++ 用 API リファレンス
description: コレクションに実際に含まれている子数学要素の数を取得します。読み取り専用 int32_t.
type: docs
weight: 1
url: /ja/aspose.slides.mathtext/mathblock/get_count/
---
## MathBlock::get_Count() メソッド


コレクションに実際に含まれている子数学要素の数を取得します。読み取り専用 **int32_t**。

```cpp
int32_t Aspose::Slides::MathText::MathBlock::get_Count() override
```

## 備考


例: 
```cpp
auto mathBlock = System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"x"));
int32_t count = mathBlock->get_Count();
```

## 参照

* クラス [MathBlock](../)
* 名前空間 [Aspose::Slides::MathText](../../)
* ライブラリ [Aspose.Slides](../../../)