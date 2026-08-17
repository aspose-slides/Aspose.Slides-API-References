---
title: IEffect
second_title: Aspose.Slides Java API 参考
description: 表示动画效果。
type: docs
url: /zh/com.aspose.slides/ieffect/
---```
public interface IEffect
```

表示动画效果。
## 方法

| 方法 | 描述 |
| --- | --- |
| [getSequence()](#getSequence--) | 返回效果的序列。 |
| [getTextAnimation()](#getTextAnimation--) | 返回文本动画。 |
| [getPresetClassType()](#getPresetClassType--) | 定义效果的类。 |
| [setPresetClassType(int value)](#setPresetClassType-int-) | 定义效果的类。 |
| [getType()](#getType--) | 定义效果的类型。 |
| [setType(int value)](#setType-int-) | 定义效果的类型。 |
| [getSubtype()](#getSubtype--) | 定义效果的子类型。 |
| [setSubtype(int value)](#setSubtype-int-) | 定义效果的子类型。 |
| [getBehaviors()](#getBehaviors--) | 返回效果的行为集合。 |
| [setBehaviors(IBehaviorCollection value)](#setBehaviors-com.aspose.slides.IBehaviorCollection-) | 返回效果的行为集合。 |
| [getTiming()](#getTiming--) | 定义效果的时间值。 |
| [setTiming(ITiming value)](#setTiming-com.aspose.slides.ITiming-) | 定义效果的时间值。 |
| [getTargetShape()](#getTargetShape--) | 返回效果的目标形状。 |
| [getSound()](#getSound--) | 定义效果的嵌入式声音。 |
| [setSound(IAudio value)](#setSound-com.aspose.slides.IAudio-) | 定义效果的嵌入式声音。 |
| [getStopPreviousSound()](#getStopPreviousSound--) | 此属性指定动画效果是否停止前一个声音。 |
| [setStopPreviousSound(boolean value)](#setStopPreviousSound-boolean-) | 此属性指定动画效果是否停止前一个声音。 |
| [getAfterAnimationType()](#getAfterAnimationType--) | 定义效果的后动画类型。 |
| [setAfterAnimationType(int value)](#setAfterAnimationType-int-) | 定义效果的后动画类型。 |
| [getAfterAnimationColor()](#getAfterAnimationColor--) | 定义效果的后动画颜色。 |
| [setAfterAnimationColor(IColorFormat value)](#setAfterAnimationColor-com.aspose.slides.IColorFormat-) | 定义效果的后动画颜色。 |
| [getAnimateTextType()](#getAnimateTextType--) | 定义效果的文字动画类型。 |
| [setAnimateTextType(int value)](#setAnimateTextType-int-) | 定义效果的文字动画类型。 |
| [getDelayBetweenTextParts()](#getDelayBetweenTextParts--) | 定义动画文字部分（单词或字母）之间的延迟。 |
| [setDelayBetweenTextParts(float value)](#setDelayBetweenTextParts-float-) | 定义动画文字部分（单词或字母）之间的延迟。 |
### getSequence() {#getSequence--}
```
public abstract ISequence getSequence()
```

返回效果的序列。只读 [ISequence](../../com.aspose.slides/isequence)。

**返回：**
[ISequence](../../com.aspose.slides/isequence)
### getTextAnimation() {#getTextAnimation--}
```
public abstract ITextAnimation getTextAnimation()
```

返回文本动画。只读 [ITextAnimation](../../com.aspose.slides/itextanimation)。

**返回：**
[ITextAnimation](../../com.aspose.slides/itextanimation)
### getPresetClassType() {#getPresetClassType--}
```
public abstract int getPresetClassType()
```

定义效果的类。读写 [EffectPresetClassType](../../com.aspose.slides/effectpresetclasstype)。

**返回：**
int
### setPresetClassType(int value) {#setPresetClassType-int-}
```
public abstract void setPresetClassType(int value)
```

定义效果的类。读写 [EffectPresetClassType](../../com.aspose.slides/effectpresetclasstype)。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |
### getType() {#getType--}
```
public abstract int getType()
```

定义效果的类型。读写 [EffectType](../../com.aspose.slides/effecttype)。

**返回：**
int
### setType(int value) {#setType-int-}
```
public abstract void setType(int value)
```

定义效果的类型。读写 [EffectType](../../com.aspose.slides/effecttype)。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |
### getSubtype() {#getSubtype--}
```
public abstract int getSubtype()
```

定义效果的子类型。读写 [EffectSubtype](../../com.aspose.slides/effectsubtype)。

**返回：**
int
### setSubtype(int value) {#setSubtype-int-}
```
public abstract void setSubtype(int value)
```

定义效果的子类型。读写 [EffectSubtype](../../com.aspose.slides/effectsubtype)。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |
### getBehaviors() {#getBehaviors--}
```
public abstract IBehaviorCollection getBehaviors()
```

返回效果的行为集合。读写 [IBehaviorCollection](../../com.aspose.slides/ibehaviorcollection)。

**返回：**
[IBehaviorCollection](../../com.aspose.slides/ibehaviorcollection)
### setBehaviors(IBehaviorCollection value) {#setBehaviors-com.aspose.slides.IBehaviorCollection-}
```
public abstract void setBehaviors(IBehaviorCollection value)
```

返回效果的行为集合。读写 [IBehaviorCollection](../../com.aspose.slides/ibehaviorcollection)。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [IBehaviorCollection](../../com.aspose.slides/ibehaviorcollection) |  |
### getTiming() {#getTiming--}
```
public abstract ITiming getTiming()
```

定义效果的时间值。读写 [ITiming](../../com.aspose.slides/itiming)。

**返回：**
[ITiming](../../com.aspose.slides/itiming)
### setTiming(ITiming value) {#setTiming-com.aspose.slides.ITiming-}
```
public abstract void setTiming(ITiming value)
```

定义效果的时间值。读写 [ITiming](../../com.aspose.slides/itiming)。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [ITiming](../../com.aspose.slides/itiming) |  |
### getTargetShape() {#getTargetShape--}
```
public abstract IShape getTargetShape()
```

返回效果的目标形状。只读 [IShape](../../com.aspose.slides/ishape)。

**返回：**
[IShape](../../com.aspose.slides/ishape)
### getSound() {#getSound--}
```
public abstract IAudio getSound()
```

定义效果的嵌入式声音。读写 [IAudio](../../com.aspose.slides/iaudio)。

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
> 
>      // 获取幻灯片的效果序列
>      ISequence effectsSequence = slide.getTimeline().getMainSequence();
> 
>      for (IEffect effect : effectsSequence)
>      {
>          if (effect.getSound() == null)
>              continue;
> 
>          // 提取效果声音为字节数组
>          byte[] audio = effect.getSound().getBinaryData();
>      }
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**返回：**
[IAudio](../../com.aspose.slides/iaudio)
### setSound(IAudio value) {#setSound-com.aspose.slides.IAudio-}
```
public abstract void setSound(IAudio value)
```

定义效果的嵌入式声音。读写 [IAudio](../../com.aspose.slides/iaudio)。

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
> 
>      // 获取幻灯片的效果序列
>      ISequence effectsSequence = slide.getTimeline().getMainSequence();
> 
>      for (IEffect effect : effectsSequence)
>      {
>          if (effect.getSound() == null)
>              continue;
> 
>          // 提取效果声音为字节数组
>          byte[] audio = effect.getSound().getBinaryData();
>      }
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [IAudio](../../com.aspose.slides/iaudio) |  |
### getStopPreviousSound() {#getStopPreviousSound--}
```
public abstract boolean getStopPreviousSound()
```

此属性指定动画效果是否停止前一个声音。读写  boolean .

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // 获取第一张幻灯片的第一个效果。
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // 获取第二张幻灯片的第一个效果。
>      IEffect secondSlideEffect = presentation.getSlides().get_Item(1).getTimeline().getMainSequence().get_Item(0);
> 
>      if (firstSlideEffect.getSound() != null)
>      {
>          // 将第二个效果的增强/声音更改为“Stop Previous Sound”
>          secondSlideEffect.setStopPreviousSound(true);
>      }
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**返回：**
boolean
### setStopPreviousSound(boolean value) {#setStopPreviousSound-boolean-}
```
public abstract void setStopPreviousSound(boolean value)
```

此属性指定动画效果是否停止前一个声音。读写  boolean .

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // 获取第一张幻灯片的第一个效果。
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // 获取第二张幻灯片的第一个效果。
>      IEffect secondSlideEffect = presentation.getSlides().get_Item(1).getTimeline().getMainSequence().get_Item(0);
> 
>      if (firstSlideEffect.getSound() != null)
>      {
>          // 将第二个效果的增强/声音更改为“Stop Previous Sound”
>          secondSlideEffect.setStopPreviousSound(true);
>      }
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |
### getAfterAnimationType() {#getAfterAnimationType--}
```
public abstract int getAfterAnimationType()
```

定义效果的后动画类型。读写  AfterAnimationType (\#getAfterAnimationType.getAfterAnimationType/\#setAfterAnimationType(int).setAfterAnimationType(int)).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // 获取第一张幻灯片的第一个效果。
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // 将效果的后动画更改为 "Hide on Next Mouse Click"
>      firstSlideEffect.setAfterAnimationType(AfterAnimationType.HideOnNextMouseClick);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**返回：**
int
### setAfterAnimationType(int value) {#setAfterAnimationType-int-}
```
public abstract void setAfterAnimationType(int value)
```

定义效果的后动画类型。读写  AfterAnimationType (\#getAfterAnimationType.getAfterAnimationType/\#setAfterAnimationType(int).setAfterAnimationType(int)).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // 获取第一张幻灯片的第一个效果。
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // 将效果的后动画更改为 "Hide on Next Mouse Click"
>      firstSlideEffect.setAfterAnimationType(AfterAnimationType.HideOnNextMouseClick);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |
### getAfterAnimationColor() {#getAfterAnimationColor--}
```
public abstract IColorFormat getAfterAnimationColor()
```

定义效果的后动画颜色。读写 [IColorFormat](../../com.aspose.slides/icolorformat)。

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // 获取第一张幻灯片的第一个效果。
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // 将效果的后动画类型更改为 "Color"
> 
>      // 设置效果的后动画颜色。
>      firstSlideEffect.getAfterAnimationColor().setColor(new java.awt.Color(0, 255, 0, 255));
>  }finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**返回：**
[IColorFormat](../../com.aspose.slides/icolorformat)
### setAfterAnimationColor(IColorFormat value) {#setAfterAnimationColor-com.aspose.slides.IColorFormat-}
```
public abstract void setAfterAnimationColor(IColorFormat value)
```

定义效果的后动画颜色。读写 [IColorFormat](../../com.aspose.slides/icolorformat)。

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // 获取第一张幻灯片的第一个效果。
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // 将效果的后动画类型更改为 "Color"
>      firstSlideEffect.setAfterAnimationType(AfterAnimationType.Color);
> 
>      // 设置效果的后动画颜色。
>      firstSlideEffect.getAfterAnimationColor().setColor(new java.awt.Color(0, 255, 0, 255));
>  }finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [IColorFormat](../../com.aspose.slides/icolorformat) |  |
### getAnimateTextType() {#getAnimateTextType--}
```
public abstract int getAnimateTextType()
```

定义效果的文字动画类型。形状文字可以按字母、按单词或一次全部动画。读写  AnimateTextType (\#getAnimateTextType.getAnimateTextType/\#setAnimateTextType(int).setAnimateTextType(int)).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>     // 获取第一张幻灯片的第一个效果。
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // 将效果的动画文本类型更改为 "By letter"
>      firstSlideEffect.setAnimateTextType(AnimateTextType.ByLetter);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**返回：**
int
### setAnimateTextType(int value) {#setAnimateTextType-int-}
```
public abstract void setAnimateTextType(int value)
```

定义效果的文字动画类型。形状文字可以按字母、按单词或一次全部动画。读写  AnimateTextType (\#getAnimateTextType.getAnimateTextType/\#setAnimateTextType(int).setAnimateTextType(int)).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>     // 获取第一张幻灯片的第一个效果。
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // 将效果的动画文本类型更改为 "By letter"
>      firstSlideEffect.setAnimateTextType(AnimateTextType.ByLetter);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |
### getDelayBetweenTextParts() {#getDelayBetweenTextParts--}
```
public abstract float getDelayBetweenTextParts()
```

定义动画文字部分（单词或字母）之间的延迟。正值表示效果持续时间的百分比。负值表示以秒为单位的延迟。读写  float .

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>     // 获取第一张幻灯片的第一个效果。
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // 将效果的动画文本类型更改为 "By word"
>      firstSlideEffect.setAnimateTextType(AnimateTextType.ByWord);
> 
>      // 将动画文本部件之间的延迟设置为效果持续时间的 20%。
>      firstSlideEffect.setDelayBetweenTextParts(20f);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**返回：**
float
### setDelayBetweenTextParts(float value) {#setDelayBetweenTextParts-float-}
```
public abstract void setDelayBetweenTextParts(float value)
```

定义动画文字部分（单词或字母）之间的延迟。正值表示效果持续时间的百分比。负值表示以秒为单位的延迟。读写  float .

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>     // 获取第一张幻灯片的第一个效果。
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // 将效果的动画文本类型更改为 "By word"
>      firstSlideEffect.setAnimateTextType(AnimateTextType.ByWord);
> 
>      // 将动画文本部件之间的延迟设置为效果持续时间的 20%。
>      firstSlideEffect.setDelayBetweenTextParts(20f);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | float |  |