---
title: Add()
second_title: Aspose.Slides for C++ APIリファレンス
description: 新しいグラデーション ストップを作成し、コレクションの末尾に追加します。
type: docs
weight: 14
url: /ja/aspose.slides/igradientstopcollection/add/
---
## IGradientStopCollection::Add(float, System::Drawing::Color) メソッド

新しいグラデーション ストップを作成し、コレクションの末尾に追加します。

```cpp
virtual System::SharedPtr<IGradientStop> Aspose::Slides::IGradientStopCollection::Add(float position, System::Drawing::Color color)=0
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| position | **float** | 新しいグラデーション ストップの位置。 |
| color | [System::Drawing::Color](../../../system.drawing/color/) | 新しいグラデーション ストップの色。 |

### 戻り値

コレクション内の新しいグラデーション ストップのインデックス。

## IGradientStopCollection::Add(float, PresetColor) メソッド

新しいグラデーション ストップを作成し、コレクションの末尾に追加します。

```cpp
virtual System::SharedPtr<IGradientStop> Aspose::Slides::IGradientStopCollection::Add(float position, PresetColor presetColor)=0
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| position | **float** | 新しいグラデーション ストップの位置。 |
| presetColor | [PresetColor](../../presetcolor/) | 新しいグラデーション ストップの色。 |

### 戻り値

コレクション内の新しいグラデーション ストップのインデックス。

## IGradientStopCollection::Add(float, SchemeColor) メソッド

新しいグラデーション ストップを作成し、コレクションの末尾に追加します。

```cpp
virtual System::SharedPtr<IGradientStop> Aspose::Slides::IGradientStopCollection::Add(float position, SchemeColor schemeColor)=0
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| position | **float** | 新しいグラデーション ストップの位置。 |
| schemeColor | [SchemeColor](../../schemecolor/) | 新しいグラデーション ストップの色。 |

### 戻り値

コレクション内の新しいグラデーション ストップのインデックス。

## 参照

* 列挙型 [PresetColor](../../presetcolor/)
* 列挙型 [SchemeColor](../../schemecolor/)
* typedef [SharedPtr](../../../system/sharedptr/)
* クラス [IGradientStop](../../igradientstop/)
* クラス [Color](../../../system.drawing/color/)
* クラス [IGradientStopCollection](../)
* 名前空間 [Aspose::Slides](../../)
* ライブラリ [Aspose.Slides](../../../)