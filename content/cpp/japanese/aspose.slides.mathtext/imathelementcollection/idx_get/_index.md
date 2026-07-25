---
title: idx_get()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定されたインデックスの要素を取得します。読み取り専用 IMathElement.
type: docs
weight: 14
url: /ja/aspose.slides.mathtext/imathelementcollection/idx_get/
---
## IMathElementCollection::idx_get(int32_t) メソッド

指定されたインデックスの要素を取得します。読み取り専用 [IMathElement](../../imathelement/)。

```cpp
virtual System::SharedPtr<IMathElement> Aspose::Slides::MathText::IMathElementCollection::idx_get(int32_t index)=0
```

### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| index | **int32_t** | 取得する項目のゼロベースインデックス |
## 備考



例: 
```cpp
auto collection = System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"x"));
auto firstElem = collection->idx_get(0);
```

## 参照

* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [IMathElement](../../imathelement/)
* クラス [IMathElementCollection](../)
* 名前空間 [Aspose::Slides::MathText](../../)
* ライブラリ [Aspose.Slides](../../../)