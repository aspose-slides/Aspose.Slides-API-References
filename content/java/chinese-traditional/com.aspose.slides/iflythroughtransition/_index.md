---
title: IFlyThroughTransition
second_title: Aspose.Slides for Java API 參考
description: 滑動式投影片過渡效果。
type: docs
url: /zh-hant/com.aspose.slides/iflythroughtransition/
---
**已實作的介面：**
[com.aspose.slides.ITransitionValueBase](../../com.aspose.slides/itransitionvaluebase)
```
public interface IFlyThroughTransition extends ITransitionValueBase
```

滑動式投影片過渡效果。
## 方法

| 方法 | 說明 |
| --- | --- |
| [getDirection()](#getDirection--) | 過渡方向。 |
| [setDirection(int value)](#setDirection-int-) | 過渡方向。 |
| [hasBounce()](#hasBounce--) | 指定在過渡期間投影片的移動包含彈跳。 |
| [setBounce(boolean value)](#setBounce-boolean-) | 指定在過渡期間投影片的移動包含彈跳。 |
### getDirection() {#getDirection--}
```
public abstract int getDirection()
```


過渡方向。讀/寫 [TransitionInOutDirectionType](../../com.aspose.slides/transitioninoutdirectiontype)。

**返回值：**
int
### setDirection(int value) {#setDirection-int-}
```
public abstract void setDirection(int value)
```


過渡方向。讀/寫 [TransitionInOutDirectionType](../../com.aspose.slides/transitioninoutdirectiontype)。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | int |  |

### hasBounce() {#hasBounce--}
```
public abstract boolean hasBounce()
```


指定在過渡期間投影片的移動包含彈跳。讀/寫 boolean。

**返回值：**
boolean
### setBounce(boolean value) {#setBounce-boolean-}
```
public abstract void setBounce(boolean value)
```


指定在過渡期間投影片的移動包含彈跳。讀/寫 boolean。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | boolean |  |