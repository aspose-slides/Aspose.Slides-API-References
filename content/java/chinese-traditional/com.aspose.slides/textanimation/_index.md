---
title: TextAnimation
second_title: Aspose.Slides for Java API 參考
description: 表示文字動畫。
type: docs
url: /zh-hant/com.aspose.slides/textanimation/
---
**繼承:**
java.lang.Object

**所有已實作的介面:**
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
| [addEffect(int effectType, int subtype, int triggerType)](#addEffect-int-int-int-) | 將新效果新增至目前序列的末端，以結束群組文字動畫。 |
| [getBuildType()](#getBuildType--) | 建構類型清單（例如 |
| [setBuildType(int value)](#setBuildType-int-) | 建構類型清單（例如 |
| [getEffectAnimateBackgroundShape()](#getEffectAnimateBackgroundShape--) | 與群組相關聯的形狀效果，或無（null）。 |
| [setEffectAnimateBackgroundShape(IEffect value)](#setEffectAnimateBackgroundShape-com.aspose.slides.IEffect-) | 與群組相關聯的形狀效果，或無（null）。 |

### TextAnimation() {#TextAnimation--}
```
public TextAnimation()
```

### addEffect(int effectType, int subtype, int triggerType) {#addEffect-int-int-int-}
```
public final IEffect addEffect(int effectType, int subtype, int triggerType)
```

將新效果新增至目前序列的末端，以結束群組文字動畫。僅在文字段落的數量大於或等於此群組效果的計數時有效！

**參數：**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| effectType | int | 動畫效果的類型 [EffectType](../../com.aspose.slides/effecttype) |
| subtype | int | 動畫效果的子類型 [EffectSubtype](../../com.aspose.slides/effectsubtype) |
| triggerType | int | 效果的觸發類型 [EffectTriggerType](../../com.aspose.slides/effecttriggertype) |

**傳回值：**
[IEffect](../../com.aspose.slides/ieffect) - 新效果物件 [IEffect](../../com.aspose.slides/ieffect)

### getBuildType() {#getBuildType--}
```
public final int getBuildType()
```

文字動畫的建構類型清單（例如段落 1、2、3、一次全部）。讀寫 [BuildType](../../com.aspose.slides/buildtype)。

**傳回值：**
int

### setBuildType(int value) {#setBuildType-int-}
```
public final void setBuildType(int value)
```

文字動畫的建構類型清單（例如段落 1、2、3、一次全部）。讀寫 [BuildType](../../com.aspose.slides/buildtype)。

**參數：**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| value | int |  |

### getEffectAnimateBackgroundShape() {#getEffectAnimateBackgroundShape--}
```
public final IEffect getEffectAnimateBackgroundShape()
```

與群組相關聯的形狀效果，或無（null）。讀寫 [IEffect](../../com.aspose.slides/ieffect)。

**傳回值：**
[IEffect](../../com.aspose.slides/ieffect)

### setEffectAnimateBackgroundShape(IEffect value) {#setEffectAnimateBackgroundShape-com.aspose.slides.IEffect-}
```
public final void setEffectAnimateBackgroundShape(IEffect value)
```

與群組相關聯的形狀效果，或無 null）。讀寫 [IEffect](../../com.aspose.slides/ieffect)。

**參數：**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| value | [IEffect](../../com.aspose.slides/ieffect) |  |