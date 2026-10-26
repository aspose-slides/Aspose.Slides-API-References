---
title: Add()
second_title: Aspose.Slides for C++ API リファレンス
description: 新しいグラデーションストップを作成し、コレクションの末尾に追加します。
type: docs
weight: 53
url: /ja/aspose.slides/gradientstopcollection/add/
---
## GradientStopCollection::Add(float, System::Drawing::Color) メソッド

新しいグラデーションストップを作成し、コレクションの末尾に追加します。

```cpp
System::SharedPtr<IGradientStop> Aspose::Slides::GradientStopCollection::Add(float position, System::Drawing::Color color) override
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| position | **float** | 新しいグラデーションストップの位置。 |
| color | [System::Drawing::Color](../../../system.drawing/color/) | 新しいグラデーションストップの色。 |

### 戻り値

コレクション内の新しいグラデーションストップのインデックス。

## GradientStopCollection::Add(float, PresetColor) メソッド

新しいグラデーションストップを作成し、コレクションの末尾に追加します。

```cpp
System::SharedPtr<IGradientStop> Aspose::Slides::GradientStopCollection::Add(float position, PresetColor presetColor) override
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| position | **float** | 新しいグラデーションストップの位置。 |
| presetColor | [PresetColor](../../presetcolor/) | 新しいグラデーションストップの色。 |

### 戻り値

コレクション内の新しいグラデーションストップのインデックス。

## GradientStopCollection::Add(float, SchemeColor) メソッド

新しいグラデーションストップを作成し、コレクションの末尾に追加します。

```cpp
System::SharedPtr<IGradientStop> Aspose::Slides::GradientStopCollection::Add(float position, SchemeColor schemeColor) override
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| position | **float** | 新しいグラデーションストップの位置。 |
| schemeColor | [SchemeColor](../../schemecolor/) | 新しいグラデーションストップの色。 |

### 戻り値

コレクション内の新しいグラデーションストップのインデックス。

## 参照

* Enum [PresetColor](../../presetcolor/)
* Enum [SchemeColor](../../schemecolor/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* クラス [IGradientStop](../../igradientstop/)
* クラス [Color](../../../system.drawing/color/)
* クラス [GradientStopCollection](../)
* 名前空間 [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)