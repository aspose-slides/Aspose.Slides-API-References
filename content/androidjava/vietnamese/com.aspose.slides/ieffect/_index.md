---
title: IEffect
second_title: Aspose.Slides for Android via Java API Reference
description: Đại diện cho hiệu ứng hoạt hình.
type: docs
url: /vi/com.aspose.slides/ieffect/
---```
public interface IEffect
```

Đại diện cho hiệu ứng hoạt hình.
## Phương thức

| Method | Description |
| --- | --- |
| [getSequence()](#getSequence--) | Trả về một chuỗi cho hiệu ứng. |
| [getTextAnimation()](#getTextAnimation--) | Trả về hoạt hình văn bản. |
| [getPresetClassType()](#getPresetClassType--) | Xác định lớp của hiệu ứng. |
| [setPresetClassType(int value)](#setPresetClassType-int-) | Xác định lớp của hiệu ứng. |
| [getType()](#getType--) | Xác định loại của hiệu ứng. |
| [setType(int value)](#setType-int-) | Xác định loại của hiệu ứng. |
| [getSubtype()](#getSubtype--) | Xác định phân loại phụ của hiệu ứng. |
| [setSubtype(int value)](#setSubtype-int-) | Xác định phân loại phụ của hiệu ứng. |
| [getBehaviors()](#getBehaviors--) | Trả về tập hợp các hành vi cho hiệu ứng. |
| [setBehaviors(IBehaviorCollection value)](#setBehaviors-com.aspose.slides.IBehaviorCollection-) | Trả về tập hợp các hành vi cho hiệu ứng. |
| [getTiming()](#getTiming--) | Xác định giá trị thời gian cho hiệu ứng. |
| [setTiming(ITiming value)](#setTiming-com.aspose.slides.ITiming-) | Xác định giá trị thời gian cho hiệu ứng. |
| [getTargetShape()](#getTargetShape--) | Trả về hình dạng mục tiêu cho hiệu ứng. |
| [getSound()](#getSound--) | Đã xác định âm thanh nhúng cho hiệu ứng. |
| [setSound(IAudio value)](#setSound-com.aspose.slides.IAudio-) | Đã xác định âm thanh nhúng cho hiệu ứng. |
| [getStopPreviousSound()](#getStopPreviousSound--) | Thuộc tính này chỉ định liệu hiệu ứng hoạt hình có dừng âm thanh trước đó hay không. |
| [setStopPreviousSound(boolean value)](#setStopPreviousSound-boolean-) | Thuộc tính này chỉ định liệu hiệu ứng hoạt hình có dừng âm thanh trước đó hay không. |
| [getAfterAnimationType()](#getAfterAnimationType--) | Đã xác định loại hoạt hình sau cho hiệu ứng. |
| [setAfterAnimationType(int value)](#setAfterAnimationType-int-) | Đã xác định loại hoạt hình sau cho hiệu ứng. |
| [getAfterAnimationColor()](#getAfterAnimationColor--) | Đã xác định màu sắc hoạt hình sau cho hiệu ứng. |
| [setAfterAnimationColor(IColorFormat value)](#setAfterAnimationColor-com.aspose.slides.IColorFormat-) | Đã xác định màu sắc hoạt hình sau cho hiệu ứng. |
| [getAnimateTextType()](#getAnimateTextType--) | Xác định loại văn bản hoạt hình cho hiệu ứng. |
| [setAnimateTextType(int value)](#setAnimateTextType-int-) | Xác định loại văn bản hoạt hình cho hiệu ứng. |
| [getDelayBetweenTextParts()](#getDelayBetweenTextParts--) | Xác định độ trễ giữa các phần văn bản được hoạt hình (từ hoặc ký tự). |
| [setDelayBetweenTextParts(float value)](#setDelayBetweenTextParts-float-) | Xác định độ trễ giữa các phần văn bản được hoạt hình (từ hoặc ký tự). |
### getSequence() {#getSequence--}
```
public abstract ISequence getSequence()
```

Trả về một chuỗi cho hiệu ứng. Chỉ đọc [ISequence](../../com.aspose.slides/isequence).

**Trả về:**
[ISequence](../../com.aspose.slides/isequence)
### getTextAnimation() {#getTextAnimation--}
```
public abstract ITextAnimation getTextAnimation()
```

Trả về hoạt hình văn bản. Chỉ đọc [ITextAnimation](../../com.aspose.slides/itextanimation).

**Trả về:**
[ITextAnimation](../../com.aspose.slides/itextanimation)
### getPresetClassType() {#getPresetClassType--}
```
public abstract int getPresetClassType()
```

Xác định lớp của hiệu ứng. Đọc/ghi [EffectPresetClassType](../../com.aspose.slides/effectpresetclasstype).

**Trả về:**
int
### setPresetClassType(int value) {#setPresetClassType-int-}
```
public abstract void setPresetClassType(int value)
```

Xác định lớp của hiệu ứng. Đọc/ghi [EffectPresetClassType](../../com.aspose.slides/effectpresetclasstype).

**Tham số:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |
### getType() {#getType--}
```
public abstract int getType()
```

Xác định loại của hiệu ứng. Đọc/ghi [EffectType](../../com.aspose.slides/effecttype).

**Trả về:**
int
### setType(int value) {#setType-int-}
```
public abstract void setType(int value)
```

Xác định loại của hiệu ứng. Đọc/ghi [EffectType](../../com.aspose.slides/effecttype).

**Tham số:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |
### getSubtype() {#getSubtype--}
```
public abstract int getSubtype()
```

Xác định phân loại phụ của hiệu ứng. Đọc/ghi [EffectSubtype](../../com.aspose.slides/effectsubtype).

**Trả về:**
int
### setSubtype(int value) {#setSubtype-int-}
```
public abstract void setSubtype(int value)
```

Xác định phân loại phụ của hiệu ứng. Đọc/ghi [EffectSubtype](../../com.aspose.slides/effectsubtype).

**Tham số:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |
### getBehaviors() {#getBehaviors--}
```
public abstract IBehaviorCollection getBehaviors()
```

Trả về tập hợp các hành vi cho hiệu ứng. Đọc/ghi [IBehaviorCollection](../../com.aspose.slides/ibehaviorcollection).

**Trả về:**
[IBehaviorCollection](../../com.aspose.slides/ibehaviorcollection)
### setBehaviors(IBehaviorCollection value) {#setBehaviors-com.aspose.slides.IBehaviorCollection-}
```
public abstract void setBehaviors(IBehaviorCollection value)
```

Trả về tập hợp các hành vi cho hiệu ứng. Đọc/ghi [IBehaviorCollection](../../com.aspose.slides/ibehaviorcollection).

**Tham số:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IBehaviorCollection](../../com.aspose.slides/ibehaviorcollection) |  |
### getTiming() {#getTiming--}
```
public abstract ITiming getTiming()
```

Xác định giá trị thời gian cho hiệu ứng. Đọc/ghi [ITiming](../../com.aspose.slides/itiming).

**Trả về:**
[ITiming](../../com.aspose.slides/itiming)
### setTiming(ITiming value) {#setTiming-com.aspose.slides.ITiming-}
```
public abstract void setTiming(ITiming value)
```

Xác định giá trị thời gian cho hiệu ứng. Đọc/ghi [ITiming](../../com.aspose.slides/itiming).

**Tham số:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [ITiming](../../com.aspose.slides/itiming) |  |
### getTargetShape() {#getTargetShape--}
```
public abstract IShape getTargetShape()
```

Trả về hình dạng mục tiêu cho hiệu ứng. Chỉ đọc [IShape](../../com.aspose.slides/ishape).

**Trả về:**
[IShape](../../com.aspose.slides/ishape)
### getSound() {#getSound--}
```
public abstract IAudio getSound()
```

Đã xác định âm thanh nhúng cho hiệu ứng. Đọc/ghi [IAudio](../../com.aspose.slides/iaudio).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
> 
>      // Lấy chuỗi hiệu ứng cho slide
>      ISequence effectsSequence = slide.getTimeline().getMainSequence();
> 
>      for (IEffect effect : effectsSequence)
>      {
>          if (effect.getSound() == null)
>              continue;
> 
>          // Trích xuất âm thanh hiệu ứng dưới dạng mảng byte
>          byte[] audio = effect.getSound().getBinaryData();
>      }
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Trả về:**
[IAudio](../../com.aspose.slides/iaudio)
### setSound(IAudio value) {#setSound-com.aspose.slides.IAudio-}
```
public abstract void setSound(IAudio value)
```

Đã xác định âm thanh nhúng cho hiệu ứng. Đọc/ghi [IAudio](../../com.aspose.slides/iaudio).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
> 
>      // Lấy chuỗi hiệu ứng cho slide
>      ISequence effectsSequence = slide.getTimeline().getMainSequence();
> 
>      for (IEffect effect : effectsSequence)
>      {
>          if (effect.getSound() == null)
>              continue;
> 
>          // Trích xuất âm thanh hiệu ứng dưới dạng mảng byte
>          byte[] audio = effect.getSound().getBinaryData();
>      }
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Tham số:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IAudio](../../com.aspose.slides/iaudio) |  |
### getStopPreviousSound() {#getStopPreviousSound--}
```
public abstract boolean getStopPreviousSound()
```

Thuộc tính này chỉ định liệu hiệu ứng hoạt hình có dừng âm thanh trước đó hay không. Đọc/ghi  boolean .

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // Lấy hiệu ứng đầu tiên của slide đầu tiên.
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // Lấy hiệu ứng đầu tiên của slide thứ hai.
>      IEffect secondSlideEffect = presentation.getSlides().get_Item(1).getTimeline().getMainSequence().get_Item(0);
> 
>      if (firstSlideEffect.getSound() != null)
>      {
>          // Thay đổi âm thanh của hiệu ứng thứ hai thành "Stop Previous Sound"
>          secondSlideEffect.setStopPreviousSound(true);
>      }
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Trả về:**
boolean
### setStopPreviousSound(boolean value) {#setStopPreviousSound-boolean-}
```
public abstract void setStopPreviousSound(boolean value)
```

Thuộc tính này chỉ định liệu hiệu ứng hoạt hình có dừng âm thanh trước đó hay không. Đọc/ghi  boolean .

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // Lấy hiệu ứng đầu tiên của slide đầu tiên.
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // Lấy hiệu ứng đầu tiên của slide thứ hai.
>      IEffect secondSlideEffect = presentation.getSlides().get_Item(1).getTimeline().getMainSequence().get_Item(0);
> 
>      if (firstSlideEffect.getSound() != null)
>      {
>          // Thay đổi âm thanh của hiệu ứng thứ hai thành "Stop Previous Sound"
>          secondSlideEffect.setStopPreviousSound(true);
>      }
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Tham số:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |
### getAfterAnimationType() {#getAfterAnimationType--}
```
public abstract int getAfterAnimationType()
```

Đã xác định loại hoạt hình sau cho hiệu ứng. Đọc/ ghi  AfterAnimationType (\#getAfterAnimationType.getAfterAnimationType/\#setAfterAnimationType(int).setAfterAnimationType(int)).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // Lấy hiệu ứng đầu tiên của slide đầu tiên.
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // Thay đổi After animation của hiệu ứng thành "Hide on Next Mouse Click"
>      firstSlideEffect.setAfterAnimationType(AfterAnimationType.HideOnNextMouseClick);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Trả về:**
int
### setAfterAnimationType(int value) {#setAfterAnimationType-int-}
```
public abstract void setAfterAnimationType(int value)
```

Đã xác định loại hoạt hình sau cho hiệu ứng. Đọc/ ghi  AfterAnimationType (\#getAfterAnimationType.getAfterAnimationType/\#setAfterAnimationType(int).setAfterAnimationType(int)).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // Lấy hiệu ứng đầu tiên của slide đầu tiên.
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // Thay đổi After animation của hiệu ứng thành "Hide on Next Mouse Click"
>      firstSlideEffect.setAfterAnimationType(AfterAnimationType.HideOnNextMouseClick);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Tham số:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |
### getAfterAnimationColor() {#getAfterAnimationColor--}
```
public abstract IColorFormat getAfterAnimationColor()
```

Đã xác định màu sắc hoạt hình sau cho hiệu ứng. Đọc/ghi [IColorFormat](../../com.aspose.slides/icolorformat).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // Lấy hiệu ứng đầu tiên của slide đầu tiên.
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // Thay đổi loại After animation của hiệu ứng thành "Color"
>      firstSlideEffect.setAfterAnimationType(AfterAnimationType.Color);
> 
>      // Đặt màu After animation của hiệu ứng.
>      firstSlideEffect.getAfterAnimationColor().setColor(Color.BLUE);
>  }finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Trả về:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### setAfterAnimationColor(IColorFormat value) {#setAfterAnimationColor-com.aspose.slides.IColorFormat-}
```
public abstract void setAfterAnimationColor(IColorFormat value)
```

Đã xác định màu sắc hoạt hình sau cho hiệu ứng. Đọc/ghi [IColorFormat](../../com.aspose.slides/icolorformat).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // Lấy hiệu ứng đầu tiên của slide đầu tiên.
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // Thay đổi loại After animation của hiệu ứng thành "Color"
>      firstSlideEffect.setAfterAnimationType(AfterAnimationType.Color);
> 
>      // Đặt màu After animation của hiệu ứng.
>      firstSlideEffect.getAfterAnimationColor().setColor(Color.BLUE);
>  }finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Tham số:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IColorFormat](../../com.aspose.slides/icolorformat) |  |
### getAnimateTextType() {#getAnimateTextType--}
```
public abstract int getAnimateTextType()
```

Xác định loại văn bản hoạt hình cho hiệu ứng. Văn bản hình dạng có thể được hoạt hình theo ký tự, theo từ hoặc toàn bộ một lúc. Đọc/ghi  AnimateTextType (\#getAnimateTextType.getAnimateTextType/\#setAnimateTextType(int).setAnimateTextType(int)).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>     // Lấy hiệu ứng đầu tiên của slide đầu tiên.
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // Thay đổi loại Animate text của hiệu ứng thành "By letter"
>      firstSlideEffect.setAnimateTextType(AnimateTextType.ByLetter);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Trả về:**
int
### setAnimateTextType(int value) {#setAnimateTextType-int-}
```
public abstract void setAnimateTextType(int value)
```

Xác định loại văn bản hoạt hình cho hiệu ứng. Văn bản hình dạng có thể được hoạt hình theo ký tự, theo từ hoặc toàn bộ một lúc. Đọc/ghi  AnimateTextType (\#getAnimateTextType.getAnimateTextType/\#setAnimateTextType(int).setAnimateTextType(int)).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>     // Lấy hiệu ứng đầu tiên của slide đầu tiên.
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // Thay đổi loại Animate text của hiệu ứng thành "By letter"
>      firstSlideEffect.setAnimateTextType(AnimateTextType.ByLetter);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Tham số:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |
### getDelayBetweenTextParts() {#getDelayBetweenTextParts--}
```
public abstract float getDelayBetweenTextParts()
```

Xác định độ trễ giữa các phần văn bản được hoạt hình (từ hoặc ký tự). Giá trị dương chỉ phần trăm thời lượng hiệu ứng. Giá trị âm chỉ độ trễ tính bằng giây. Đọc/ghi  float .

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>     // Lấy hiệu ứng đầu tiên của slide đầu tiên.
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // Thay đổi loại Animate text của hiệu ứng thành "By word"
>      firstSlideEffect.setAnimateTextType(AnimateTextType.ByWord);
> 
>      // Đặt độ trễ giữa các phần văn bản được hoạt hình thành 20% thời lượng hiệu ứng.
>      firstSlideEffect.setDelayBetweenTextParts(20f);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Trả về:**
float
### setDelayBetweenTextParts(float value) {#setDelayBetweenTextParts-float-}
```
public abstract void setDelayBetweenTextParts(float value)
```

Xác định độ trễ giữa các phần văn bản được hoạt hình (từ hoặc ký tự). Giá trị dương chỉ phần trăm thời lượng hiệu ứng. Giá trị âm chỉ độ trễ tính bằng giây. Đọc/ghi  float .

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>     // Lấy hiệu ứng đầu tiên của slide đầu tiên.
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // Thay đổi loại Animate text của hiệu ứng thành "By word"
>      firstSlideEffect.setAnimateTextType(AnimateTextType.ByWord);
> 
>      // Đặt độ trễ giữa các phần văn bản được hoạt hình thành 20% thời lượng hiệu ứng.
>      firstSlideEffect.setDelayBetweenTextParts(20f);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Tham số:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |