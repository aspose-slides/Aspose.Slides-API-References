---
title: IRevealTransition
second_title: Aspose.Slides for Android 的 Java API 參考
description: 顯示投影片過渡效果。
type: docs
url: /zh-hant/com.aspose.slides/irevealtransition/
---
**所有已實作的介面：**
[com.aspose.slides.ITransitionValueBase](../../com.aspose.slides/itransitionvaluebase)
```
public interface IRevealTransition extends ITransitionValueBase
```

顯示投影片過渡效果。
## 方法

| 方法 | 描述 |
| --- | --- |
| [getDirection()](#getDirection--) | 過渡的方向。 |
| [setDirection(int value)](#setDirection-int-) | 過渡的方向。 |
| [getThroughBlack()](#getThroughBlack--) | 指定過渡是否透過黑色淡出。 |
| [setThroughBlack(boolean value)](#setThroughBlack-boolean-) | 指定過渡是否透過黑色淡出。 |
### getDirection() {#getDirection--}
```
public abstract int getDirection()
```

過渡方向。讀寫 [TransitionLeftRightDirectionType](../../com.aspose.slides/transitionleftrightdirectiontype)。

**返回：**
int
### setDirection(int value) {#setDirection-int-}
```
public abstract void setDirection(int value)
```

過渡方向。讀寫 [TransitionLeftRightDirectionType](../../com.aspose.slides/transitionleftrightdirectiontype)。

**參數：**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| value | int |  |
### getThroughBlack() {#getThroughBlack--}
```
public abstract boolean getThroughBlack()
```

指定過渡是否透過黑色淡出。讀寫 boolean。

**返回：**
boolean
### setThroughBlack(boolean value) {#setThroughBlack-boolean-}
```
public abstract void setThroughBlack(boolean value)
```

指定過渡是否透過黑色淡出。讀寫 boolean。

**參數：**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| value | boolean |  |