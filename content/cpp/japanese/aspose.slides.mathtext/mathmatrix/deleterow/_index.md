---
title: DeleteRow()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定された行を削除します
type: docs
weight: 313
url: /ja/aspose.slides.mathtext/mathmatrix/deleterow/
---
## MathMatrix::DeleteRow(int32_t) メソッド


指定された行を削除します

```cpp
void Aspose::Slides::MathText::MathMatrix::DeleteRow(int32_t rowIndex) override
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| rowIndex | **int32_t** | 削除する行のゼロベースインデックス。 |
## 備考



例: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->DeleteRow(0);
```

## 参照

* クラス [MathMatrix](../)
* 名前空間 [Aspose::Slides::MathText](../../)
* ライブラリ [Aspose.Slides](../../../)