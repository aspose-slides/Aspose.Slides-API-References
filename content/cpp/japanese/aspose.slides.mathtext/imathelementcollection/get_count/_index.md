---
title: get_Count()
second_title: Aspose.Slides for C++ API リファレンス
description: コレクションに実際に含まれている要素の数を取得します。読み取り専用 int32_t.
type: docs
weight: 1
url: /ja/aspose.slides.mathtext/imathelementcollection/get_count/
---
## IMathElementCollection::get_Count() メソッド

コレクションに実際に含まれている要素の数を取得します。読み取り専用 **int32_t**.

```cpp
virtual int32_t Aspose::Slides::MathText::IMathElementCollection::get_Count()=0
```

## 備考

例:
```cpp
auto collection = System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"x"));
int32_t count = collection->get_Count();
```

## 関連項目

* クラス [IMathElementCollection](../)
* 名前空間 [Aspose::Slides::MathText](../../)
* ライブラリ [Aspose.Slides](../../../)