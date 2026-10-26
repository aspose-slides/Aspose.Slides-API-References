---
title: IEffect
second_title: Aspose.Slides for Android via Java API Reference
description: Represents animation effect.
type: docs
url: /ru/com.aspose.slides/ieffect/
---```
public interface IEffect
```

Представляет анимационный эффект.
## Методы

| Метод | Описание |
| --- | --- |
| [getSequence()](#getSequence--) | Возвращает последовательность для эффекта. |
| [getTextAnimation()](#getTextAnimation--) | Возвращает текстовую анимацию. |
| [getPresetClassType()](#getPresetClassType--) | Определяет класс эффекта. |
| [setPresetClassType(int value)](#setPresetClassType-int-) | Определяет класс эффекта. |
| [getType()](#getType--) | Определяет тип эффекта. |
| [setType(int value)](#setType-int-) | Определяет тип эффекта. |
| [getSubtype()](#getSubtype--) | Определяет подтип эффекта. |
| [setSubtype(int value)](#setSubtype-int-) | Определяет подтип эффекта. |
| [getBehaviors()](#getBehaviors--) | Возвращает коллекцию поведения для эффекта. |
| [setBehaviors(IBehaviorCollection value)](#setBehaviors-com.aspose.slides.IBehaviorCollection-) | Возвращает коллекцию поведения для эффекта. |
| [getTiming()](#getTiming--) | Определяет значение тайминга для эффекта. |
| [setTiming(ITiming value)](#setTiming-com.aspose.slides.ITiming-) | Определяет значение тайминга для эффекта. |
| [getTargetShape()](#getTargetShape--) | Возвращает целевую форму для эффекта. |
| [getSound()](#getSound--) | Определён встроенный звук для эффекта. |
| [setSound(IAudio value)](#setSound-com.aspose.slides.IAudio-) | Определён встроенный звук для эффекта. |
| [getStopPreviousSound()](#getStopPreviousSound--) | Этот атрибут указывает, останавливает ли анимационный эффект предыдущий звук. |
| [setStopPreviousSound(boolean value)](#setStopPreviousSound-boolean-) | Этот атрибут указывает, останавливает ли анимационный эффект предыдущий звук. |
| [getAfterAnimationType()](#getAfterAnimationType--) | Определён тип последующей анимации для эффекта. |
| [setAfterAnimationType(int value)](#setAfterAnimationType-int-) | Определён тип последующей анимации для эффекта. |
| [getAfterAnimationColor()](#getAfterAnimationColor--) | Определён цвет последующей анимации для эффекта. |
| [setAfterAnimationColor(IColorFormat value)](#setAfterAnimationColor-com.aspose.slides.IColorFormat-) | Определён цвет последующей анимации для эффекта. |
| [getAnimateTextType()](#getAnimateTextType--) | Определяет тип анимированного текста для эффекта. |
| [setAnimateTextType(int value)](#setAnimateTextType-int-) | Определяет тип анимированного текста для эффекта. |
| [getDelayBetweenTextParts()](#getDelayBetweenTextParts--) | Определяет задержку между частями анимированного текста (словами или буквами). |
| [setDelayBetweenTextParts(float value)](#setDelayBetweenTextParts-float-) | Определяет задержку между частями анимированного текста (словами или буквами). |
### getSequence() {#getSequence--}
```
public abstract ISequence getSequence()
```


Возвращает последовательность для эффекта. Только для чтения [ISequence](../../com.aspose.slides/isequence).

**Возвращает:**
[ISequence](../../com.aspose.slides/isequence)
### getTextAnimation() {#getTextAnimation--}
```
public abstract ITextAnimation getTextAnimation()
```


Возвращает текстовую анимацию. Только для чтения [ITextAnimation](../../com.aspose.slides/itextanimation).

**Возвращает:**
[ITextAnimation](../../com.aspose.slides/itextanimation)
### getPresetClassType() {#getPresetClassType--}
```
public abstract int getPresetClassType()
```


Определяет класс эффекта. Чтение/запись [EffectPresetClassType](../../com.aspose.slides/effectpresetclasstype).

**Возвращает:**
int
### setPresetClassType(int value) {#setPresetClassType-int-}
```
public abstract void setPresetClassType(int value)
```


Определяет класс эффекта. Чтение/запись [EffectPresetClassType](../../com.aspose.slides/effectpresetclasstype).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getType() {#getType--}
```
public abstract int getType()
```


Определяет тип эффекта. Чтение/запись [EffectType](../../com.aspose.slides/effecttype).

**Возвращает:**
int
### setType(int value) {#setType-int-}
```
public abstract void setType(int value)
```


Определяет тип эффекта. Чтение/запись [EffectType](../../com.aspose.slides/effecttype).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getSubtype() {#getSubtype--}
```
public abstract int getSubtype()
```


Определяет подтип эффекта. Чтение/запись [EffectSubtype](../../com.aspose.slides/effectsubtype).

**Возвращает:**
int
### setSubtype(int value) {#setSubtype-int-}
```
public abstract void setSubtype(int value)
```


Определяет подтип эффекта. Чтение/запись [EffectSubtype](../../com.aspose.slides/effectsubtype).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getBehaviors() {#getBehaviors--}
```
public abstract IBehaviorCollection getBehaviors()
```


Возвращает коллекцию поведения для эффекта. Чтение/запись [IBehaviorCollection](../../com.aspose.slides/ibehaviorcollection).

**Возвращает:**
[IBehaviorCollection](../../com.aspose.slides/ibehaviorcollection)
### setBehaviors(IBehaviorCollection value) {#setBehaviors-com.aspose.slides.IBehaviorCollection-}
```
public abstract void setBehaviors(IBehaviorCollection value)
```


Возвращает коллекцию поведения для эффекта. Чтение/запись [IBehaviorCollection](../../com.aspose.slides/ibehaviorcollection).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [IBehaviorCollection](../../com.aspose.slides/ibehaviorcollection) |  |

### getTiming() {#getTiming--}
```
public abstract ITiming getTiming()
```


Определяет значение тайминга для эффекта. Чтение/запись [ITiming](../../com.aspose.slides/itiming).

**Возвращает:**
[ITiming](../../com.aspose.slides/itiming)
### setTiming(ITiming value) {#setTiming-com.aspose.slides.ITiming-}
```
public abstract void setTiming(ITiming value)
```


Определяет значение тайминга для эффекта. Чтение/запись [ITiming](../../com.aspose.slides/itiming).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [ITiming](../../com.aspose.slides/itiming) |  |

### getTargetShape() {#getTargetShape--}
```
public abstract IShape getTargetShape()
```


Возвращает целевую форму для эффекта. Только для чтения [IShape](../../com.aspose.slides/ishape).

**Возвращает:**
[IShape](../../com.aspose.slides/ishape)
### getSound() {#getSound--}
```
public abstract IAudio getSound()
```


Определён встроенный звук для эффекта. Чтение/запись [IAudio](../../com.aspose.slides/iaudio).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
> 
>      // Получает последовательность эффектов для слайда
>      ISequence effectsSequence = slide.getTimeline().getMainSequence();
> 
>      for (IEffect effect : effectsSequence)
>      {
>          if (effect.getSound() == null)
>              continue;
> 
>          // Извлекает звук эффекта в массив байтов
>          byte[] audio = effect.getSound().getBinaryData();
>      }
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Возвращает:**
[IAudio](../../com.aspose.slides/iaudio)
### setSound(IAudio value) {#setSound-com.aspose.slides.IAudio-}
```
public abstract void setSound(IAudio value)
```


Определён встроенный звук для эффекта. Чтение/запись [IAudio](../../com.aspose.slides/iaudio).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
> 
>      // Получает последовательность эффектов для слайда
>      ISequence effectsSequence = slide.getTimeline().getMainSequence();
> 
>      for (IEffect effect : effectsSequence)
>      {
>          if (effect.getSound() == null)
>              continue;
> 
>          // Извлекает звук эффекта в массив байтов
>          byte[] audio = effect.getSound().getBinaryData();
>      }
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [IAudio](../../com.aspose.slides/iaudio) |  |

### getStopPreviousSound() {#getStopPreviousSound--}
```
public abstract boolean getStopPreviousSound()
```


Этот атрибут указывает, останавливает ли анимационный эффект предыдущий звук. Чтение/запись boolean .

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // Получить первый эффект первого слайда.
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // Получить первый эффект второго слайда.
>      IEffect secondSlideEffect = presentation.getSlides().get_Item(1).getTimeline().getMainSequence().get_Item(0);
> 
>      if (firstSlideEffect.getSound() != null)
>      {
>          // Изменить звук второго эффекта на "Stop Previous Sound"
>          secondSlideEffect.setStopPreviousSound(true);
>      }
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Возвращает:**
boolean
### setStopPreviousSound(boolean value) {#setStopPreviousSound-boolean-}
```
public abstract void setStopPreviousSound(boolean value)
```


Этот атрибут указывает, останавливает ли анимационный эффект предыдущий звук. Чтение/запись boolean .

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // Получить первый эффект первого слайда.
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // Получить первый эффект второго слайда.
>      IEffect secondSlideEffect = presentation.getSlides().get_Item(1).getTimeline().getMainSequence().get_Item(0);
> 
>      if (firstSlideEffect.getSound() != null)
>      {
>          // Изменить звук второго эффекта на "Stop Previous Sound"
>          secondSlideEffect.setStopPreviousSound(true);
>      }
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |

### getAfterAnimationType() {#getAfterAnimationType--}
```
public abstract int getAfterAnimationType()
```


Определён тип последующей анимации для эффекта. Чтение/запись AfterAnimationType (\#getAfterAnimationType.getAfterAnimationType/\#setAfterAnimationType(int).setAfterAnimationType(int)).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // Получить первый эффект первого слайда.
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // Изменить эффект последующей анимации на "Hide on Next Mouse Click"
>      firstSlideEffect.setAfterAnimationType(AfterAnimationType.HideOnNextMouseClick);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Возвращает:**
int
### setAfterAnimationType(int value) {#setAfterAnimationType-int-}
```
public abstract void setAfterAnimationType(int value)
```


Определён тип последующей анимации для эффекта. Чтение/запись AfterAnimationType (\#getAfterAnimationType.getAfterAnimationType/\#setAfterAnimationType(int).setAfterAnimationType(int)).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // Получить первый эффект первого слайда.
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // Изменить эффект последующей анимации на "Hide on Next Mouse Click"
>      firstSlideEffect.setAfterAnimationType(AfterAnimationType.HideOnNextMouseClick);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getAfterAnimationColor() {#getAfterAnimationColor--}
```
public abstract IColorFormat getAfterAnimationColor()
```


Определён цвет последующей анимации для эффекта. Чтение/запись [IColorFormat](../../com.aspose.slides/icolorformat).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // Получить первый эффект первого слайда.
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // Изменить тип последующей анимации эффекта на "Color"
>      firstSlideEffect.setAfterAnimationType(AfterAnimationType.Color);
> 
>      // Установить цвет последующей анимации эффекта.
>      firstSlideEffect.getAfterAnimationColor().setColor(Color.BLUE);
>  }finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Возвращает:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### setAfterAnimationColor(IColorFormat value) {#setAfterAnimationColor-com.aspose.slides.IColorFormat-}
```
public abstract void setAfterAnimationColor(IColorFormat value)
```


Определён цвет последующей анимации для эффекта. Чтение/запись [IColorFormat](../../com.aspose.slides/icolorformat).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // Получить первый эффект первого слайда.
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // Изменить тип последующей анимации эффекта на "Color"
>      firstSlideEffect.setAfterAnimationType(AfterAnimationType.Color);
> 
>      // Установить цвет последующей анимации эффекта.
>      firstSlideEffect.getAfterAnimationColor().setColor(Color.BLUE);
>  }finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [IColorFormat](../../com.aspose.slides/icolorformat) |  |

### getAnimateTextType() {#getAnimateTextType--}
```
public abstract int getAnimateTextType()
```


Определяет тип анимированного текста для эффекта. Текст фигуры может быть анимирован по буквам, по словам или сразу полностью. Чтение/запись AnimateTextType (\#getAnimateTextType.getAnimateTextType/\#setAnimateTextType(int).setAnimateTextType(int)).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>     // Получить первый эффект первого слайда.
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // Изменить тип анимированного текста эффекта на "By letter"
>      firstSlideEffect.setAnimateTextType(AnimateTextType.ByLetter);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Возвращает:**
int
### setAnimateTextType(int value) {#setAnimateTextType-int-}
```
public abstract void setAnimateTextType(int value)
```


Определяет тип анимированного текста для эффекта. Текст фигуры может быть анимирован по буквам, по словам или сразу полностью. Чтение/запись AnimateTextType (\#getAnimateTextType.getAnimateTextType/\#setAnimateTextType(int).setAnimateTextType(int)).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>     // Получить первый эффект первого слайда.
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // Изменить тип анимированного текста эффекта на "By letter"
>      firstSlideEffect.setAnimateTextType(AnimateTextType.ByLetter);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | float |  |

### getDelayBetweenTextParts() {#getDelayBetweenTextParts--}
```
public abstract float getDelayBetweenTextParts()
```


Определяет задержку между частями анимированного текста (словами или буквами). Положительное значение задаёт процент от длительности эффекта. Отрицательное значение задаёт задержку в секундах. Чтение/запись float .

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // Изменить тип анимированного текста эффекта на "By word"
>      firstSlideEffect.setAnimateTextType(AnimateTextType.ByWord);
> 
>      // Установить задержку между частями анимированного текста на 20% длительности эффекта.
>      firstSlideEffect.setDelayBetweenTextParts(20f);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Возвращает:**
float
### setDelayBetweenTextParts(float value) {#setDelayBetweenTextParts-float-}
```
public abstract void setDelayBetweenTextParts(float value)
```


Определяет задержку между частями анимированного текста (словами или буквами). Положительное значение задаёт процент от длительности эффекта. Отрицательное значение задаёт задержку в секундах. Чтение/запись float .

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>     // Получить первый эффект первого слайда.
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // Изменить тип анимированного текста эффекта на "By word"
>      firstSlideEffect.setAnimateTextType(AnimateTextType.ByWord);
> 
>      // Установить задержку между частями анимированного текста на 20% длительности эффекта.
>      firstSlideEffect.setDelayBetweenTextParts(20f);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | float |  |