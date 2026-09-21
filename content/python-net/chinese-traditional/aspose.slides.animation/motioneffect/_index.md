---
title: MotionEffect class
second_title: Aspose.Slides for Python via .NET API 參考文件
description: 
type: docs
url: /zh-hant/aspose.slides.animation/motioneffect/
---
## MotionEffect 類別

表示效果的運動效果行為。

**Inheritance:**[`MotionEffect`](/slides/python-net/zh-hant/aspose.slides.animation/motioneffect) → [`Behavior`](/slides/python-net/zh-hant/aspose.slides.animation/behavior)

MotionEffect 類型公開以下成員：

## 建構式

| 建構式 | 說明 |
| :- | :- |
| [`__init__(self)`](/slides/python-net/zh-hant/aspose.slides.animation/motioneffect/__init__/#) | 建立新實例。 |

## 屬性

| 屬性 | 說明 |
| :- | :- |
| [`accumulate`](/slides/python-net/zh-hant/aspose.slides.animation/motioneffect/accumulate/) | 表示是否累積動畫行為。<br/>            讀/寫 [`NullableBool`](/slides/python-net/zh-hant/aspose.slides/nullablebool)。 |
| [`additive`](/slides/python-net/zh-hant/aspose.slides.animation/motioneffect/additive/) | 表示目前的動畫行為是否與其他執行中的動畫結合。<br/>            讀/寫 [`BehaviorAdditiveType`](/slides/python-net/zh-hant/aspose.slides.animation/behavioradditivetype)。 |
| [`properties`](/slides/python-net/zh-hant/aspose.slides.animation/motioneffect/properties/) | 表示行為的屬性。<br/>            唯讀 [`IBehaviorPropertyCollection`](/slides/python-net/zh-hant/aspose.slides.animation/ibehaviorpropertycollection)。 |
| [`timing`](/slides/python-net/zh-hant/aspose.slides.animation/motioneffect/timing/) | 表示效果行為的時間屬性。<br/>            讀/寫 [`ITiming`](/slides/python-net/zh-hant/aspose.slides.animation/itiming)。 |
| [`from_address`](/slides/python-net/zh-hant/aspose.slides.animation/motioneffect/from_address/) | 指定動畫開始的 x/y 座標（以百分比表示）。<br/>            讀/寫 **aspose.slides.PointF**。 |
| [`to`](/slides/python-net/zh-hant/aspose.slides.animation/motioneffect/to/) | 指定動畫運動效果的目標位置（以百分比表示）。<br/>            讀/寫 **aspose.slides.PointF**。 |
| [`by`](/slides/python-net/zh-hant/aspose.slides.animation/motioneffect/by/) | 描述動畫的相對偏移值（以百分比表示）。<br/>            讀/寫 **aspose.slides.PointF**。 |
| [`rotation_center`](/slides/python-net/zh-hant/aspose.slides.animation/motioneffect/rotation_center/) | 描述用於將運動路徑旋轉 X 角度的旋轉中心。<br/>            讀/寫 **aspose.slides.PointF**。 |
| [`origin`](/slides/python-net/zh-hant/aspose.slides.animation/motioneffect/origin/) | 指定運動路徑的起點相對於什麼，例如投影片的版面配置，<br/>            或父層。<br/>            讀/寫 [`MotionOriginType`](/slides/python-net/zh-hant/aspose.slides.animation/motionorigintype)。 |
| [`path`](/slides/python-net/zh-hant/aspose.slides.animation/motioneffect/path/) | 指定路徑基元及其座標，用於動畫運動。<br/>            讀/寫 [`IMotionPath`](/slides/python-net/zh-hant/aspose.slides.animation/imotionpath)。 |
| [`path_edit_mode`](/slides/python-net/zh-hant/aspose.slides.animation/motioneffect/path_edit_mode/) | 指定當形狀移動時，運動路徑的移動方式。<br/>            讀/寫 [`MotionPathEditMode`](/slides/python-net/zh-hant/aspose.slides.animation/motionpatheditmode)。 |
| [`angle`](/slides/python-net/zh-hant/aspose.slides.animation/motioneffect/angle/) | 描述運動路徑的相對角度。<br/>            讀/寫 **float**。 |

### 另請參閱
* 類別 [`Behavior`](/slides/python-net/zh-hant/aspose.slides.animation/behavior)
* 類別 [`MotionEffect`](/slides/python-net/zh-hant/aspose.slides.animation/motioneffect)
* 模組 [`aspose.slides.animation`](/slides/python-net/zh-hant/aspose.slides.animation)
* 程式庫 [`Aspose.Slides`](/slides/python-net)