---
title: IRevealTransition
second_title: Tham khảo API Aspose.Slides cho Java
description: Hiệu ứng chuyển tiếp slide Reveal.
type: docs
url: /vi/com.aspose.slides/irevealtransition/
---
**Tất cả các giao diện được triển khai:**
[com.aspose.slides.ITransitionValueBase](../../com.aspose.slides/itransitionvaluebase)
```
public interface IRevealTransition extends ITransitionValueBase
```

Hiển thị hiệu ứng chuyển tiếp slide.
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getDirection()](#getDirection--) | Direction of transition. |
| [setDirection(int value)](#setDirection-int-) | Direction of transition. |
| [getThroughBlack()](#getThroughBlack--) | Specifies whether the transition fades through black. |
| [setThroughBlack(boolean value)](#setThroughBlack-boolean-) | Specifies whether the transition fades through black. |
### getDirection() {#getDirection--}
```
public abstract int getDirection()
```

Hướng của chuyển tiếp. Đọc/ghi [TransitionLeftRightDirectionType](../../com.aspose.slides/transitionleftrightdirectiontype).

**Trả về:**
int
### setDirection(int value) {#setDirection-int-}
```
public abstract void setDirection(int value)
```

Hướng của chuyển tiếp. Đọc/ghi [TransitionLeftRightDirectionType](../../com.aspose.slides/transitionleftrightdirectiontype).

**Tham số:**
| Tham số | Type | Mô tả |
| --- | --- | --- |
| value | int |  |

### getThroughBlack() {#getThroughBlack--}
```
public abstract boolean getThroughBlack()
```

Xác định liệu chuyển tiếp có mờ dần qua màu đen hay không. Đọc/ghi boolean.

**Trả về:**
boolean
### setThroughBlack(boolean value) {#setThroughBlack-boolean-}
```
public abstract void setThroughBlack(boolean value)
```

Xác định liệu chuyển tiếp có mờ dần qua màu đen hay không. Đọc/ghi boolean.

**Tham số:**
| Tham số | Type | Mô tả |
| --- | --- | --- |
| value | boolean |  |