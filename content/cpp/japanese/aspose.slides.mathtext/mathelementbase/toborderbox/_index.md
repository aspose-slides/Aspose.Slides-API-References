---
title: ToBorderBox()
second_title: Aspose.Slides for C++ API リファレンス
description: この要素をボーダーボックスに配置します
type: docs
weight: 248
url: /ja/aspose.slides.mathtext/mathelementbase/toborderbox/
---
## MathElementBase::ToBorderBox() メソッド

この要素をボーダーボックスに配置します

```cpp
System::SharedPtr<IMathBorderBox> Aspose::Slides::MathText::MathElementBase::ToBorderBox() override
```

### 戻り値

この要素が内部に配置されたボーダーボックス

## 備考



例: 
```cpp
auto borderBox = System::MakeObject<MathematicalText>(u"x+y+z")->ToBorderBox();
```

## MathElementBase::ToBorderBox(bool, bool, bool, bool, bool, bool, bool, bool) メソッド

この要素をボーダーボックスに配置します

```cpp
System::SharedPtr<IMathBorderBox> Aspose::Slides::MathText::MathElementBase::ToBorderBox(bool hideTop, bool hideBottom, bool hideLeft, bool hideRight, bool strikethroughHorizontal, bool strikethroughVertical, bool strikethroughBottomLeftToTopRight, bool strikethroughTopLeftToBottomRight) override
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| hideTop | **bool** | 上端を非表示 |
| hideBottom | **bool** | 下端を非表示 |
| hideLeft | **bool** | 左端を非表示 |
| hideRight | **bool** | 右端を非表示 |
| strikethroughHorizontal | **bool** | ボーダーボックスの水平取り消し線 |
| strikethroughVertical | **bool** | ボーダーボックスの垂直取り消し線 |
| strikethroughBottomLeftToTopRight | **bool** | ボーダーボックスの左下から右上への取り消し線 |
| strikethroughTopLeftToBottomRight | **bool** | ボーダーボックスの左上から右下への取り消し線 |

### 戻り値

この要素が内部に配置されたボーダーボックス

## 備考



例: 
```cpp
auto borderBox = System::MakeObject<MathematicalText>(u"x+y+z")->ToBorderBox(false, false, true, true, false, false, false, false);
```

## 参照

* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [IMathBorderBox](../../imathborderbox/)
* クラス [MathElementBase](../)
* 名前空間 [Aspose::Slides::MathText](../../)
* ライブラリ [Aspose.Slides](../../../)