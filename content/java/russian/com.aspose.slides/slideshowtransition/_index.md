---
title: SlideShowTransition
second_title: Справочник API Aspose.Slides для Java
description: Представляет переход слайд-шоу.
type: docs
url: /ru/com.aspose.slides/slideshowtransition/
---
**Наследование:**
java.lang.Object, com.aspose.slides.DomObject

**Все реализованные интерфейсы:**
[com.aspose.slides.ISlideShowTransition](../../com.aspose.slides/islideshowtransition)
```
public class SlideShowTransition extends DomObject<BaseSlide> implements ISlideShowTransition
```

Представляет переход слайд-шоу.
## Методы

| Метод | Описание |
| --- | --- |
| [getSound()](#getSound--) | Возвращает или задаёт встроенные аудиоданные. |
| [setSound(IAudio value)](#setSound-com.aspose.slides.IAudio-) | Возвращает или задаёт встроенные аудиоданные. |
| [getSoundMode()](#getSoundMode--) | Устанавливает или возвращает режим звука для перехода слайда. |
| [setSoundMode(int value)](#setSoundMode-int-) | Устанавливает или возвращает режим звука для перехода слайда. |
| [getSoundLoop()](#getSoundLoop--) | Этот атрибут указывает, будет ли звук воспроизводиться в цикле до появления следующего звукового события в слайд-шоу. |
| [setSoundLoop(boolean value)](#setSoundLoop-boolean-) | Этот атрибут указывает, будет ли звук воспроизводиться в цикле до появления следующего звукового события в слайд-шоу. |
| [getAdvanceOnClick()](#getAdvanceOnClick--) | Определяет, будет ли кликом мыши переключаться слайд. |
| [setAdvanceOnClick(boolean value)](#setAdvanceOnClick-boolean-) | Определяет, будет ли кликом мыши переключаться слайд. |
| [getAdvanceAfter()](#getAdvanceAfter--) | Этот атрибут указывает, будет ли слайд-шоу переходить к следующему слайду через определённое время. |
| [setAdvanceAfter(boolean value)](#setAdvanceAfter-boolean-) | Этот атрибут указывает, будет ли слайд-шоу переходить к следующему слайду через определённое время. |
| [getAdvanceAfterTime()](#getAdvanceAfterTime--) | Задаёт время в миллисекундах, после которого должен начаться переход. |
| [setAdvanceAfterTime(long value)](#setAdvanceAfterTime-long-) | Задаёт время в миллисекундах, после которого должен начаться переход. |
| [getSpeed()](#getSpeed--) | Задаёт скорость перехода, используемую при переходе от текущего слайда к следующему. |
| [setSpeed(int value)](#setSpeed-int-) | Задаёт скорость перехода, используемую при переходе от текущего слайда к следующему. |
| [getValue()](#getValue--) | Значение перехода слайд-шоу. |
| [getType()](#getType--) | Тип перехода. |
| [setType(int value)](#setType-int-) | Тип перехода. |
| [getSoundIsBuiltIn()](#getSoundIsBuiltIn--) | Указывает, является ли данный звук встроенным. |
| [setSoundIsBuiltIn(boolean value)](#setSoundIsBuiltIn-boolean-) | Указывает, является ли данный звук встроенным. |
| [getSoundName()](#getSoundName--) | Задаёт читаемое человеком имя звука перехода. |
| [setSoundName(String value)](#setSoundName-java.lang.String-) | Задаёт читаемое человеком имя звука перехода. |
| [getDuration()](#getDuration--) | Получает или задаёт длительность эффекта перехода слайда в миллисекундах. |
| [setDuration(int value)](#setDuration-int-) | Получает или задаёт длительность эффекта перехода слайда в миллисекундах. |
| [equals(Object obj)](#equals-java.lang.Object-) | Определяет, равны ли два экземпляра SlideShowTransition. |
| [hashCode()](#hashCode--) | Служит хеш-функцией для конкретного типа, подходящей для использования в хеш-алгоритмах и структурах данных, таких как хеш-таблица. |

### getSound() {#getSound--}
```
public final IAudio getSound()
```

Возвращает или задаёт встроенные аудиоданные. Чтение/запись [IAudio](../../com.aspose.slides/iaudio).

**Возврат:**
[IAudio](../../com.aspose.slides/iaudio)

### setSound(IAudio value) {#setSound-com.aspose.slides.IAudio-}
```
public final void setSound(IAudio value)
```

Возвращает или задаёт встроенные аудиоданные. Чтение/запись [IAudio](../../com.aspose.slides/iaudio).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [IAudio](../../com.aspose.slides/iaudio) |  |

### getSoundMode() {#getSoundMode--}
```
public final int getSoundMode()
```

Устанавливает или возвращает режим звука для перехода слайда. Чтение/запись [TransitionSoundMode](../../com.aspose.slides/transitionsoundmode).

**Возврат:**
int

### setSoundMode(int value) {#setSoundMode-int-}
```
public final void setSoundMode(int value)
```

Устанавливает или возвращает режим звука для перехода слайда. Чтение/запись [TransitionSoundMode](../../com.aspose.slides/transitionsoundmode).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getSoundLoop() {#getSoundLoop--}
```
public final boolean getSoundLoop()
```

Этот атрибут указывает, будет ли звук воспроизводиться в цикле до появления следующего звукового события в слайд-шоу. Чтение/запись boolean.

**Возврат:**
boolean

### setSoundLoop(boolean value) {#setSoundLoop-boolean-}
```
public final void setSoundLoop(boolean value)
```

Этот атрибут указывает, будет ли звук воспроизводиться в цикле до появления следующего звукового события в слайд-шоу. Чтение/запись boolean.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |

### getAdvanceOnClick() {#getAdvanceOnClick--}
```
public final boolean getAdvanceOnClick()
```

Определяет, будет ли кликом мыши переключаться слайд. Если атрибут не указан, предполагается значение true. Чтение/запись boolean.

**Возврат:**
boolean

### setAdvanceOnClick(boolean value) {#setAdvanceOnClick-boolean-}
```
public final void setAdvanceOnClick(boolean value)
```

Определяет, будет ли кликом мыши переключаться слайд. Если атрибут не указан, предполагается значение true. Чтение/запись boolean.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |

### getAdvanceAfter() {#getAdvanceAfter--}
```
public final boolean getAdvanceAfter()
```

Этот атрибут указывает, будет ли слайд-шоу переходить к следующему слайду через определённое время. Чтение/запись boolean.

> ```
> Presentation pres = new Presentation("demo.pptx");
>  try {
>      // Получить первый переход слайда
>      ISlideShowTransition slideTransition = pres.getSlides().get_Item(0).getSlideShowTransition();
> 
>      // Проверить, установлен ли флаг автоматического перехода после
>      if (slideTransition.getAdvanceAfter())
>      {
>          // Получить значение времени автоматического перехода
>          long advanceAfterTime = slideTransition.getAdvanceAfterTime();
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Возврат:**
boolean

### setAdvanceAfter(boolean value) {#setAdvanceAfter-boolean-}
```
public final void setAdvanceAfter(boolean value)
```

Этот атрибут указывает, будет ли слайд-шоу переходить к следующему слайду через определённое время. Чтение/запись boolean.

> ```
> Presentation pres = new Presentation("demo.pptx");
>  try {
>      // Получить первый переход слайда
>      ISlideShowTransition slideTransition = pres.getSlides().get_Item(0).getSlideShowTransition();
> 
>      // Проверить, установлен ли флаг автоматического перехода после
>      if (slideTransition.getAdvanceAfter())
>      {
>          // Получить значение времени автоматического перехода
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
public final long getAdvanceAfterTime()
```

Задаёт время в миллисекундах, после которого должен начаться переход. Этот параметр может использоваться совместно с атрибутом advClick. Если атрибут не указан, считается, что автоматический переход не будет происходить. Чтение/запись long.

**Возврат:**
long

### setAdvanceAfterTime(long value) {#setAdvanceAfterTime-long-}
```
public final void setAdvanceAfterTime(long value)
```

Задаёт время в миллисекундах, после которого должен начаться переход. Этот параметр может использоваться совместно с атрибутом advClick. Если атрибут не указан, считается, что автоматический переход не будет происходить. Чтение/запись long.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | long |  |

### getSpeed() {#getSpeed--}
```
public final int getSpeed()
```

Задаёт скорость перехода, используемую при переходе от текущего слайда к следующему. Чтение/запись [TransitionSpeed](../../com.aspose.slides/transitionspeed).

**Возврат:**
int

### setSpeed(int value) {#setSpeed-int-}
```
public final void setSpeed(int value)
```

Задаёт скорость перехода, используемую при переходе от текущего слайда к следующему. Чтение/запись [TransitionSpeed](../../com.aspose.slides/transitionspeed).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getValue() {#getValue--}
```
public final ITransitionValueBase getValue()
```

Значение перехода слайд-шоу. Только для чтения [ITransitionValueBase](../../com.aspose.slides/itransitionvaluebase).

**Возврат:**
[ITransitionValueBase](../../com.aspose.slides/itransitionvaluebase)

### getType() {#getType--}
```
public final int getType()
```

Тип перехода. Чтение/запись [TransitionType](../../com.aspose.slides/transitiontype).

**Возврат:**
int

### setType(int value) {#setType-int-}
```
public final void setType(int value)
```

Тип перехода. Чтение/запись [TransitionType](../../com.aspose.slides/transitiontype).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getSoundIsBuiltIn() {#getSoundIsBuiltIn--}
```
public final boolean getSoundIsBuiltIn()
```

Указывает, является ли данный звук встроенным. Если атрибут установлен в true, то приложение-генератор проверяет атрибут name, указанный для этого звука в списке встроенных звуков, и при необходимости отображает пользовательское имя или интерфейс. Чтение-запись boolean.

**Возврат:**
boolean

### setSoundIsBuiltIn(boolean value) {#setSoundIsBuiltIn-boolean-}
```
public final void setSoundIsBuiltIn(boolean value)
```

Указывает, является ли данный звук встроенным. Если атрибут установлен в true, то приложение-генератор проверяет атрибут name, указанный для этого звука в списке встроенных звуков, и при необходимости отображает пользовательское имя или интерфейс. Чтение-запись boolean.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |

### getSoundName() {#getSoundName--}
```
public final String getSoundName()
```

Задаёт читаемое человеком имя звука перехода. Свойство Sound (\#getSound.getSound/\#setSound(IAudio).setSound(IAudio)) должно быть назначено для получения или установки имени звука. Чтение-запись String.

**Возврат:**
java.lang.String

### setSoundName(String value) {#setSoundName-java.lang.String-}
```
public final void setSoundName(String value)
```

Задаёт читаемое человеком имя звука перехода. Свойство Sound (\#getSound.getSound/\#setSound(IAudio).setSound(IAudio)) должно быть назначено для получения или установки имени звука. Чтение-запись String.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String |  |

### getDuration() {#getDuration--}
```
public final int getDuration()
```

Получает или задаёт длительность эффекта перехода слайда в миллисекундах. Чтение/запись int.

--------------------

Соответствует атрибуту p14:dur элемента p:transition в схеме PresentationML. Если не установлено, длительность определяется автоматически на основе свойства \#getSpeed.getSpeed/\#setSpeed(int).setSpeed(int) и типа перехода.

**Возврат:**
int

### setDuration(int value) {#setDuration-int-}
```
public final void setDuration(int value)
```

Получает или задаёт длительность эффекта перехода слайда в миллисекундах. Чтение/запись int.

--------------------

Соответствует атрибуту p14:dur элемента p:transition в схеме PresentationML. Если не установлено, длительность определяется автоматически на основе свойства \#getSpeed.getSpeed/\#setSpeed(int).setSpeed(int) и типа перехода.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

Определяет, равны ли два экземпляра SlideShowTransition. Чтение/запись boolean.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| obj | java.lang.Object | SlideShowTransition для сравнения с текущим объектом. |

**Возврат:**
boolean - **true**  если указанный SlideShowTransition равен текущему; иначе **false**.

### hashCode() {#hashCode--}
```
public boolean equals(Object obj)
```

Служит хеш-функцией для конкретного типа, подходящей для использования в хеш-алгоритмах и структурах данных, таких как хеш-таблица.

**Возврат:**
int - 23454

--------------------

Переопределено, чтобы компилятор был доволен. Всегда возвращает константу, потому что объект изменяемый.