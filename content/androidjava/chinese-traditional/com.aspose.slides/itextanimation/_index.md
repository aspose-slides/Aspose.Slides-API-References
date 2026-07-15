---
title: ITextAnimation
second_title: Aspose.Slides for Android via Java API Reference
description: Represent text animation.
type: docs
url: /zh-hant/com.aspose.slides/itextanimation/
---```
public interface ITextAnimation
```

表示文字動畫。
## 方法

| 方法 | 說明 |
| --- | --- |
| [addEffect(int effectType, int subtype, int triggerType)](#addEffect-int-int-int-) | 在目前序列的末尾新增效果，於群組文字動畫的結尾處。 |
| [getBuildType()](#getBuildType--) | 建構類型清單（例如 |
| [setBuildType(int value)](#setBuildType-int-) | 建構類型清單（例如 |
| [getEffectAnimateBackgroundShape()](#getEffectAnimateBackgroundShape--) | 與群組相關聯的形狀效果或未關聯（null） 讀/寫 [IEffect](../../com.aspose.slides/ieffect)。 |
| [setEffectAnimateBackgroundShape(IEffect value)](#setEffectAnimateBackgroundShape-com.aspose.slides.IEffect-) | 與群組相關聯的形狀效果或未關聯（null） 讀/寫 [IEffect](../../com.aspose.slides/ieffect)。 |
### addEffect(int effectType, int subtype, int triggerType) {#addEffect-int-int-int-}
```
public abstract IEffect addEffect(int effectType, int subtype, int triggerType)
```


在目前序列的末尾新增效果，於群組文字動畫的結尾處。僅在文字段落數量大於或等於此群組的效果數量時有效！

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| effectType | int | 動畫效果的類型 [EffectType](../../com.aspose.slides/effecttype) |
| subtype | int | 動畫效果的子類型 [EffectSubtype](../../com.aspose.slides/effectsubtype) |
| triggerType | int | 效果的觸發類型 [EffectTriggerType](../../com.aspose.slides/effecttriggertype) |

**返回:**
[IEffect](../../com.aspose.slides/ieffect) - 新的效果物件 [IEffect](../../com.aspose.slides/ieffect)
### getBuildType() {#getBuildType--}
```
public abstract int getBuildType()
```


文字動畫的建構類型清單（例如段落 1、2、3、一次全部）。讀/寫 \#getBuildType.getBuildType/\#setBuildType(int).setBuildType(int)。

**返回:**
int
### setBuildType(int value) {#setBuildType-int-}
```
public abstract void setBuildType(int value)
```


文字動畫的建構類型清單（例如段落 1、2、3、一次全部）。讀/寫 \#getBuildType.getBuildType/\#setBuildType(int).setBuildType(int)。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | int |  |

### getEffectAnimateBackgroundShape() {#getEffectAnimateBackgroundShape--}
```
public abstract IEffect getEffectAnimateBackgroundShape()
```


與群組相關聯的形狀效果或未關聯（null） 讀/寫 [IEffect](../../com.aspose.slides/ieffect)。

**返回:**
[IEffect](../../com.aspose.slides/ieffect)
### setEffectAnimateBackgroundShape(IEffect value) {#setEffectAnimateBackgroundShape-com.aspose.slides.IEffect-}
```
public abstract void setEffectAnimateBackgroundShape(IEffect value)
```


與群組相關聯的形狀效果或未關聯（null） 讀/寫 [IEffect](../../com.aspose.slides/ieffect)。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | [IEffect](../../com.aspose.slides/ieffect) |  |