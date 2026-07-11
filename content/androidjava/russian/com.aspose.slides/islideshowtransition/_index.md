---
title: ISlideShowTransition
second_title: Aspose.Slides for Android via Java API Reference
description: Represents slide show transition.
type: docs
url: /ru/com.aspose.slides/islideshowtransition/
---```
public interface ISlideShowTransition
```

Представляет переход слайд-шоу.
## Методы

| Метод | Описание |
| --- | --- |
| [getSound()](#getSound--) | Возвращает или задает встроенные аудио-данные. |
| [setSound(IAudio value)](#setSound-com.aspose.slides.IAudio-) | Возвращает или задает встроенные аудио-данные. |
| [getSoundMode()](#getSoundMode--) | Задает или возвращает режим звука для перехода слайда. |
| [setSoundMode(int value)](#setSoundMode-int-) | Задает или возвращает режим звука для перехода слайда. |
| [getSoundLoop()](#getSoundLoop--) | Этот атрибут указывает, будет ли звук зацикливаться до наступления следующего звукового события в слайдшоу. |
| [setSoundLoop(boolean value)](#setSoundLoop-boolean-) | Этот атрибут указывает, будет ли звук зацикливаться до наступления следующего звукового события в слайдшоу. |
| [getAdvanceOnClick()](#getAdvanceOnClick--) | Указывает, будет ли щелчок мыши переходить к следующему слайду. |
| [setAdvanceOnClick(boolean value)](#setAdvanceOnClick-boolean-) | Указывает, будет ли щелчок мыши переходить к следующему слайду. |
| [getAdvanceAfter()](#getAdvanceAfter--) | Этот атрибут определяет, будет ли слайдшоу переходить к следующему слайду через определённое время. |
| [setAdvanceAfter(boolean value)](#setAdvanceAfter-boolean-) | Этот атрибут определяет, будет ли слайдшоу переходить к следующему слайду через определённое время. |
| [getAdvanceAfterTime()](#getAdvanceAfterTime--) | Указывает время в миллисекундах, после которого должен начаться переход. |
| [setAdvanceAfterTime(long value)](#setAdvanceAfterTime-long-) | Указывает время в миллисекундах, после которого должен начаться переход. |
| [getSpeed()](#getSpeed--) | Указывает скорость перехода, используемую при переходе от текущего слайда к следующему. |
| [setSpeed(int value)](#setSpeed-int-) | Указывает скорость перехода, используемую при переходе от текущего слайда к следующему. |
| [getValue()](#getValue--) | Значение перехода слайд-шоу. |
| [getType()](#getType--) | Тип перехода. |
| [setType(int value)](#setType-int-) | Тип перехода. |
| [getSoundIsBuiltIn()](#getSoundIsBuiltIn--) | Указывает, является ли этот звук встроенным. |
| [setSoundIsBuiltIn(boolean value)](#setSoundIsBuiltIn-boolean-) | Указывает, является ли этот звук встроенным. |
| [getSoundName()](#getSoundName--) | Указывает человекочитаемое название звука перехода. |
| [setSoundName(String value)](#setSoundName-java.lang.String-) | Указывает человекочитаемое название звука перехода. |
| [getDuration()](#getDuration--) | Получает или задает длительность эффекта перехода слайда в миллисекундах. |
| [setDuration(int value)](#setDuration-int-) | Получает или задает длительность эффекта перехода слайда в миллисекундах. |
### getSound() {#getSound--}
```
public abstract IAudio getSound()
```

Возвращает или задает встроенные аудио-данные. Чтение-запись [IAudio](../../com.aspose.slides/iaudio).

**Возвращаемое значение:**
[IAudio](../../com.aspose.slides/iaudio)
### setSound(IAudio value) {#setSound-com.aspose.slides.IAudio-}
```
public abstract void setSound(IAudio value)
```

Возвращает или задает встроенные аудио-данные. Чтение-запись [IAudio](../../com.aspose.slides/iaudio).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [IAudio](../../com.aspose.slides/iaudio) |  |
### getSoundMode() {#getSoundMode--}
```
public abstract int getSoundMode()
```

Задает или возвращает режим звука для перехода слайда. Чтение-запись [TransitionSoundMode](../../com.aspose.slides/transitionsoundmode).

**Возвращаемое значение:**
int
### setSoundMode(int value) {#setSoundMode-int-}
```
public abstract void setSoundMode(int value)
```

Задает или возвращает режим звука для перехода слайда. Чтение-запись [TransitionSoundMode](../../com.aspose.slides/transitionsoundmode).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |
### getSoundLoop() {#getSoundLoop--}
```
public abstract boolean getSoundLoop()
```

Этот атрибут указывает, будет ли звук зацикливаться до наступления следующего звукового события в слайдшоу. Чтение-запись boolean.

**Возвращаемое значение:**
boolean
### setSoundLoop(boolean value) {#setSoundLoop-boolean-}
```
public abstract void setSoundLoop(boolean value)
```

Этот атрибут указывает, будет ли звук зацикливаться до наступления следующего звукового события в слайдшоу. Чтение-запись boolean.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |
### getAdvanceOnClick() {#getAdvanceOnClick--}
```
public abstract boolean getAdvanceOnClick()
```

Указывает, будет ли щелчок мыши переходить к следующему слайду. Если этот атрибут не указан, считается значение true. Чтение-запись boolean.

**Возвращаемое значение:**
boolean
### setAdvanceOnClick(boolean value) {#setAdvanceOnClick-boolean-}
```
public abstract void setAdvanceOnClick(boolean value)
```

Указывает, будет ли щелчок мыши переходить к следующему слайду. Если этот атрибут не указан, считается значение true. Чтение-запись boolean.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |
### getAdvanceAfter() {#getAdvanceAfter--}
```
public abstract boolean getAdvanceAfter()
```

Этот атрибут определяет, будет ли слайдшоу переходить к следующему слайду через определённое время. Чтение-запись boolean.

--------------------

> ```
> Presentation pres = new Presentation("demo.pptx");
>  try {
>      // Получить первый переход слайда
>      ISlideShowTransition slideTransition = pres.getSlides().get_Item(0).getSlideShowTransition();
> 
>      // Проверить, установлен ли флаг Advance Slide After
>      if (slideTransition.getAdvanceAfter())
>      {
>          // Получить значение Advance Slide After Time
>          long advanceAfterTime = slideTransition.getAdvanceAfterTime();
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Возвращаемое значение:**
boolean
### setAdvanceAfter(boolean value) {#setAdvanceAfter-boolean-}
```
public abstract void setAdvanceAfter(boolean value)
```

Этот атрибут определяет, будет ли слайдшоу переходить к следующему слайду через определённое время. Чтение-запись boolean.

--------------------

> ```
> Presentation pres = new Presentation("demo.pptx");
>  try {
>      // Получить первый переход слайда
>      ISlideShowTransition slideTransition = pres.getSlides().get_Item(0).getSlideShowTransition();
> 
>      // Проверить, установлен ли флаг Advance Slide After
>      if (slideTransition.getAdvanceAfter())
>      {
>          // Получить значение Advance Slide After Time
>          long advanceAfterTime = slideTransition.getAdvanceAfterTime();
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |
### getAdvanceAfterTime() {#getAdvanceAfterTime--}
```
public abstract long getAdvanceAfterTime()
```

Указывает время в миллисекундах, после которого должен начаться переход. Эта настройка может использоваться вместе с атрибутом advClick. Если этот атрибут не указан, считается, что автоматический переход не будет происходить. Чтение-запись long.

**Возвращаемое значение:**
long
### setAdvanceAfterTime(long value) {#setAdvanceAfterTime-long-}
```
public abstract void setAdvanceAfterTime(long value)
```

Указывает время в миллисекундах, после которого должен начаться переход. Эта настройка может использоваться вместе с атрибутом advClick. Если этот атрибут не указан, считается, что автоматический переход не будет происходить. Чтение-запись long.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | long |  |
### getSpeed() {#getSpeed--}
```
public abstract int getSpeed()
```

Указывает скорость перехода, используемую при переходе от текущего слайда к следующему. Чтение-запись [TransitionSpeed](../../com.aspose.slides/transitionspeed).

**Возвращаемое значение:**
int
### setSpeed(int value) {#setSpeed-int-}
```
public abstract void setSpeed(int value)
```

Указывает скорость перехода, используемую при переходе от текущего слайда к следующему. Чтение-запись [TransitionSpeed](../../com.aspose.slides/transitionspeed).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |
### getValue() {#getValue--}
```
public abstract ITransitionValueBase getValue()
```

Значение перехода слайд-шоу. Только-для-чтения [ITransitionValueBase](../../com.aspose.slides/itransitionvaluebase).

**Возвращаемое значение:**
[ITransitionValueBase](../../com.aspose.slides/itransitionvaluebase)
### getType() {#getType--}
```
public abstract int getType()
```

Тип перехода. Чтение-запись [TransitionType](../../com.aspose.slides/transitiontype).

**Возвращаемое значение:**
int
### setType(int value) {#setType-int-}
```
public abstract void setType(int value)
```

Тип перехода. Чтение-запись [TransitionType](../../com.aspose.slides/transitiontype).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |
### getSoundIsBuiltIn() {#getSoundIsBuiltIn--}
```
public abstract boolean getSoundIsBuiltIn()
```

Указывает, является ли этот звук встроенным. Если этот атрибут установлен в true, приложение-генератор будет уведомлено проверить атрибут name, указанный для этого звука в списке встроенных звуков, и при необходимости отобразит пользовательское имя или интерфейс. Чтение-запись boolean.

**Возвращаемое значение:**
boolean
### setSoundIsBuiltIn(boolean value) {#setSoundIsBuiltIn-boolean-}
```
public abstract void setSoundIsBuiltIn(boolean value)
```

Указывает, является ли этот звук встроенным. Если этот атрибут установлен в true, приложение-генератор будет уведомлено проверить атрибут name, указанный для этого звука в списке встроенных звуков, и при необходимости отобразит пользовательское имя или интерфейс. Чтение-запись boolean.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |
### getSoundName() {#getSoundName--}
```
public abstract String getSoundName()
```

Указывает человекочитаемое название звука перехода. Свойство (\#getSound.getSound/\#setSound(IAudio).setSound(IAudio)) должно быть назначено для получения или установки имени звука. Чтение-запись String.

**Возвращаемое значение:**
java.lang.String
### setSoundName(String value) {#setSoundName-java.lang.String-}
```
public abstract void setSoundName(String value)
```

Указывает человекочитаемое название звука перехода. Свойство \#getSound.getSound/\#setSound(IAudio).setSound(IAudio) должно быть назначено для получения или установки имени звука. Чтение-запись String.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String |  |
### getDuration() {#getDuration--}
```
public abstract int getDuration()
```

Получает или задает длительность эффекта перехода слайда в миллисекундах. Чтение-запись int.

--------------------

Соответствует атрибуту p14:dur элемента p:transition в схеме PresentationML. Если не установлен, длительность определяется автоматически на основе свойства \#getSpeed.getSpeed/\#setSpeed(int).setSpeed(int) и типа перехода.

**Возвращаемое значение:**
int
### setDuration(int value) {#setDuration-int-}
```
public abstract void setDuration(int value)
```

Получает или задает длительность эффекта перехода слайда в миллисекундах. Чтение-запись int.

--------------------

Соответствует атрибуту p14:dur элемента p:transition в схеме PresentationML. Если не установлен, длительность определяется автоматически на основе свойства \#getSpeed.getSpeed/\#setSpeed(int).setSpeed(int) и типа перехода.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |