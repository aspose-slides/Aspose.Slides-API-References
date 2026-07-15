---
title: TextAnimation
second_title: Aspose.Slides for Android via Java API 參考文件
description: 表示文字動畫。
type: docs
url: /zh-hant/com.aspose.slides/textanimation/
---
**繼承：**
java.lang.Object

**所有已實作的介面：**
[com.aspose.slides.ITextAnimation](../../com.aspose.slides/itextanimation)
```
public class TextAnimation implements ITextAnimation
```

表示文字動畫。
## 建構函式

| 建構函式 | 說明 |
| --- | --- |
| [TextAnimation()](#TextAnimation--) |  |
## 方法

| 方法 | 說明 |
| --- | --- |
| [addEffect(int effectType, int subtype, int triggerType)](#addEffect-int-int-int-) | 將新的效果新增至目前序列的結尾，以加入群組文字動畫的結尾。 |
| [getBuildType()](#getBuildType--) | 建構類型列表（例如 |
| [setBuildType(int value)](#setBuildType-int-) | 建構類型列表（例如 |
| [getEffectAnimateBackgroundShape()](#getEffectAnimateBackgroundShape--) | 與群組相關的形狀效果，或無（null）。 |
| [setEffectAnimateBackgroundShape(IEffect value)](#setEffectAnimateBackgroundShape-com.aspose.slides.IEffect-) | 與群組相關的形狀效果，或無（null）。 |
### TextAnimation() {#TextAnimation--}
```
public TextAnimation()
```

### addEffect(int effectType, int subtype, int triggerType) {#addEffect-int-int-int-}
```
public final IEffect addEffect(int effectType, int subtype, int triggerType)
```

將新的效果新增至目前序列的結尾，以加入群組文字動畫的結尾。僅當文字段落的計數大於或等於此群組效果的計數時才有效！

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| effectType | int | 動畫效果的類型 [EffectType](../../com.aspose.slides/effecttype) |
| subtype | int | 動畫效果的子類型 [EffectSubtype](../../com.aspose.slides/effectsubtype) |
| triggerType | int | 效果的觸發類型 [EffectTriggerType](../../com.aspose.slides/effecttriggertype) |

**傳回：**
[IEffect](../../com.aspose.slides/ieffect) - 新效果物件 [IEffect](../../com.aspose.slides/ieffect)
### getBuildType() {#getBuildType--}
```
public final int getBuildType()
```

文字動畫的建構類型列表（例如段落 1、2、3、一次全部）。讀/寫 [BuildType](../../com.aspose.slides/buildtype)。

**傳回：**
int
### setBuildType(int value) {#setBuildType-int-}
```
public final void setBuildType(int value)
```

文字動畫的建構類型列表（例如段落 1、2、3、一次全部）。讀/寫 [BuildType](../../com.aspose.slides/buildtype)。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | int |  |
### getEffectAnimateBackgroundShape() {#getEffectAnimateBackgroundShape--}
```
public final IEffect getEffectAnimateBackgroundShape()
```

與群組相關的形狀效果，或無（null）。讀/寫 [IEffect](../../com.aspose.slides/ieffect)。

**傳回：**
[IEffect](../../com.aspose.slides/ieffect)
### setEffectAnimateBackgroundShape(IEffect value) {#setEffectAnimateBackgroundShape-com.aspose.slides.IEffect-}
```
public final void setEffectAnimateBackgroundShape(IEffect value)
```

與群組相關的形狀效果，或無（null）。讀/寫 [IEffect](../../com.aspose.slides/ieffect)。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | [IEffect](../../com.aspose.slides/ieffect) |  |