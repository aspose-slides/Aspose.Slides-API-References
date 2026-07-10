---
title: Effect
second_title: Aspose.Slides for Android via Java API 参考
description: 表示动画效果。
type: docs
url: /zh/com.aspose.slides/effect/
---
**继承:**  
java.lang.Object

**所有实现的接口:**  
[com.aspose.slides.IEffect](../../com.aspose.slides/ieffect), com.aspose.slides.IDOMObject  
```
public class Effect implements IEffect, IDOMObject
```

表示动画效果。

## 方法

| 方法 | 描述 |
| --- | --- |
| [getSequence()](#getSequence--) | 返回一个效果的序列。 |
| [getTextAnimation()](#getTextAnimation--) | TextAnimation 只读 [ITextAnimation](../../com.aspose.slides/itextanimation)。 |
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
| [getSound()](#getSound--) | 定义嵌入的声音用于效果。 |
| [setSound(IAudio value)](#setSound-com.aspose.slides.IAudio-) | 定义嵌入的声音用于效果。 |
| [getStopPreviousSound()](#getStopPreviousSound--) | 此属性指定动画效果是否停止前一个声音。 |
| [setStopPreviousSound(boolean value)](#setStopPreviousSound-boolean-) | 此属性指定动画效果是否停止前一个声音。 |
| [getAfterAnimationType()](#getAfterAnimationType--) | 定义效果的后动画类型。 |
| [setAfterAnimationType(int value)](#setAfterAnimationType-int-) | 定义效果的后动画类型。 |
| [getAfterAnimationColor()](#getAfterAnimationColor--) | 定义效果的后动画颜色。 |
| [setAfterAnimationColor(IColorFormat value)](#setAfterAnimationColor-com.aspose.slides.IColorFormat-) | 定义效果的后动画颜色。 |
| [getAnimateTextType()](#getAnimateTextType--) | 定义效果的文字动画类型。 |
| [setAnimateTextType(int value)](#setAnimateTextType-int-) | 定义效果的文字动画类型。 |
| [getDelayBetweenTextParts()](#getDelayBetweenTextParts--) | 定义动画文本部分（单词或字母）之间的延迟。 |
| [setDelayBetweenTextParts(float value)](#setDelayBetweenTextParts-float-) | 定义动画文本部分（单词或字母）之间的延迟。 |
| [getParent_Immediate()](#getParent-Immediate--) |  |

### getSequence() {#getSequence--}
```
public final ISequence getSequence()
```

返回一个效果的序列。只读 [ISequence](../../com.aspose.slides/isequence)。

**返回:**  
[ISequence](../../com.aspose.slides/isequence)

### getTextAnimation() {#getTextAnimation--}
```
public final ITextAnimation getTextAnimation()
```

TextAnimation 只读 [ITextAnimation](../../com.aspose.slides/itextanimation)。

**返回:**  
[ITextAnimation](../../com.aspose.slides/itextanimation)

### getPresetClassType() {#getPresetClassType--}
```
public final int getPresetClassType()
```

定义效果的类。可读写 [EffectPresetClassType](../../com.aspose.slides/effectpresetclasstype)。

**返回:**  
int

### setPresetClassType(int value) {#setPresetClassType-int-}
```
public final void setPresetClassType(int value)
```

定义效果的类。可读写 [EffectPresetClassType](../../com.aspose.slides/effectpresetclasstype)。

**参数:**  
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getType() {#getType--}
```
public final int getType()
```

定义效果的类型。可读写 [EffectType](../../com.aspose.slides/effecttype)。

**返回:**  
int

### setType(int value) {#setType-int-}
```
public final void setType(int value)
```

定义效果的类型。可读写 [EffectType](../../com.aspose.slides/effecttype)。

**参数:**  
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getSubtype() {#getSubtype--}
```
public final int getSubtype()
```

定义效果的子类型。可读写 [EffectSubtype](../../com.aspose.slides/effectsubtype)。

**返回:**  
int

### setSubtype(int value) {#setSubtype-int-}
```
public final void setSubtype(int value)
```

定义效果的子类型。可读写 [EffectSubtype](../../com.aspose.slides/effectsubtype)。

**参数:**  
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getBehaviors() {#getBehaviors--}
```
public final IBehaviorCollection getBehaviors()
```

返回效果的行为集合。可读写 [IBehaviorCollection](../../com.aspose.slides/ibehaviorcollection)。

**返回:**  
[IBehaviorCollection](../../com.aspose.slides/ibehaviorcollection)

### setBehaviors(IBehaviorCollection value) {#setBehaviors-com.aspose.slides.IBehaviorCollection-}
```
public final void setBehaviors(IBehaviorCollection value)
```

返回效果的行为集合。可读写 [IBehaviorCollection](../../com.aspose.slides/ibehaviorcollection)。

**参数:**  
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [IBehaviorCollection](../../com.aspose.slides/ibehaviorcollection) |  |

### getTiming() {#getTiming--}
```
public final ITiming getTiming()
```

定义效果的时间值。可读写 [ITiming](../../com.aspose.slides/itiming)。

**返回:**  
[ITiming](../../com.aspose.slides/itiming)

### setTiming(ITiming value) {#setTiming-com.aspose.slides.ITiming-}
```
public final void setTiming(ITiming value)
```

定义效果的时间值。可读写 [ITiming](../../com.aspose.slides/itiming)。

**参数:**  
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [ITiming](../../com.aspose.slides/itiming) |  |

### getTargetShape() {#getTargetShape--}
```
public final IShape getTargetShape()
```

返回效果的目标形状。只读 [IShape](../../com.aspose.slides/ishape)。

**返回:**  
[IShape](../../com.aspose.slides/ishape)

### getSound() {#getSound--}
```
public final IAudio getSound()
```

定义嵌入的声音用于效果。可读写 [IAudio](../../com.aspose.slides/iaudio)。

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
> 
>      // Gets the effects sequence for the slide
>      ISequence effectsSequence = slide.getTimeline().getMainSequence();
> 
>      for (IEffect effect : effectsSequence)
>      {
>          if (effect.getSound() == null)
>              continue;
> 
>          // Extracts the effect sound in byte array
>          byte[] audio = effect.getSound().getBinaryData();
>      }
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Returns:**
[IAudio](../../com.aspose.slides/iaudio)
### setSound(IAudio value) {#setSound-com.aspose.slides.IAudio-}
```
public final void setSound(IAudio value)
```
Defined embedded sound for effect. Read/write [IAudio](../../com.aspose.slides/iaudio).

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
>          // 将效果声音提取为字节数组
>          byte[] audio = effect.getSound().getBinaryData();
>      }
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IAudio](../../com.aspose.slides/iaudio) |  |

### getStopPreviousSound() {#getStopPreviousSound--}
```
public final boolean getStopPreviousSound()
```
This attribute specifies if the animation effect stops the previous sound. Read/write  boolean .

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
>          // 将第二个效果的增强/声音更改为“停止先前的声音”
>          secondSlideEffect.setStopPreviousSound(true);
>      }
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```
```
public final void setStopPreviousSound(boolean value)
```

This attribute specifies if the animation effect stops the previous sound. Read/write  boolean .

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
>          // 将第二个效果的增强/声音更改为“停止先前的声音”
>          secondSlideEffect.setStopPreviousSound(true);
>      }
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getAfterAnimationType() {#getAfterAnimationType--}
```
public final int getAfterAnimationType()
```
Defines an after animation type for effect. Read/write [AfterAnimationType](../../com.aspose.slides/afteranimationtype)(\#getAfterAnimationType.getAfterAnimationType/\#setAfterAnimationType(int).setAfterAnimationType(int)).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // 获取第一张幻灯片的第一个效果。
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // 将效果的后动画更改为“在下一次单击鼠标时隐藏”
>      firstSlideEffect.setAfterAnimationType(AfterAnimationType.HideOnNextMouseClick);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Returns:**
int
### setAfterAnimationType(int value) {#setAfterAnimationType-int-}
```
public final void setAfterAnimationType(int value)
```

Defines an after animation type for effect. Read/write [AfterAnimationType](../../com.aspose.slides/afteranimationtype)(\#getAfterAnimationType.getAfterAnimationType/\#setAfterAnimationType(int).setAfterAnimationType(int)).

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

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getAfterAnimationColor() {#getAfterAnimationColor--}
```
public final IColorFormat getAfterAnimationColor()
```
Defines an after animation color for effect. Read/write [IColorFormat](../../com.aspose.slides/icolorformat).

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
>      firstSlideEffect.getAfterAnimationColor().setColor(Color.BLUE);
>  }finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Returns:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### setAfterAnimationColor(IColorFormat value) {#setAfterAnimationColor-com.aspose.slides.IColorFormat-}
```
public final void setAfterAnimationColor(IColorFormat value)
```
Defines an after animation color for effect. Read/write [IColorFormat](../../com.aspose.slides/icolorformat).

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
>      firstSlideEffect.getAfterAnimationColor().setColor(Color.BLUE);
>  }finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IColorFormat](../../com.aspose.slides/icolorformat) |  |

### getAnimateTextType() {#getAnimateTextType--}
```
public final int getAnimateTextType()
```

Defines an animate text type for effect. The shape text can be animated by letter, by word or all at once. Read/write  AnimateTextType (\#getAnimateTextType.getAnimateTextType/\#setAnimateTextType(int).setAnimateTextType(int)).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // 获取第一张幻灯片的第一个效果。
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // 将效果的动画文本类型更改为 "By letter"
>      firstSlideEffect.setAnimateTextType(AnimateTextType.ByLetter);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Returns:**
int
### setAnimateTextType(int value) {#setAnimateTextType-int-}
```
public final void setAnimateTextType(int value)
```


Defines an animate text type for effect. The shape text can be animated by letter, by word or all at once. Read/write  AnimateTextType (\#getAnimateTextType.getAnimateTextType/\#setAnimateTextType(int).setAnimateTextType(int)).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // Get the first effect of the first slide.
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // Change the effect Animate text type to "By letter"
>      firstSlideEffect.setAnimateTextType(AnimateTextType.ByLetter);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getDelayBetweenTextParts() {#getDelayBetweenTextParts--}
```
public final float getDelayBetweenTextParts()
```

Defines a delay between animated text parts (words or letters). A positive value specifies the percentage of effect duration. A negative value specifies the delay in seconds. Read/write  float .

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // 获取第一张幻灯片的第一个效果。
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // 将效果的动画文本类型更改为 "By word"
>      firstSlideEffect.setAnimateTextType(AnimateTextType.ByWord);
> 
>      // 将动画文本部分之间的延迟设置为效果持续时间的 20%。
>      firstSlideEffect.setDelayBetweenTextParts(20f);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Returns:**
float
### setDelayBetweenTextParts(float value) {#setDelayBetweenTextParts-float-}
```
public final void setDelayBetweenTextParts(float value)
```

Defines a delay between animated text parts (words or letters). A positive value specifies the percentage of effect duration. A negative value specifies the delay in seconds. Read/write  float .

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
>      // 将动画文本部分之间的延迟设置为效果持续时间的 20%。
>      firstSlideEffect.setDelayBetweenTextParts(20f);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()


返回 Parent_Immediate 对象。只读 IDOMObject。

**返回:**  
com.aspose.slides.IDOMObject
