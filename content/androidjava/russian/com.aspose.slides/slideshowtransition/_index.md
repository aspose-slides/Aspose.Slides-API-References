---
title: SlideShowTransition
second_title: Aspose.Slides для Android через справочник Java API
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
| [getSound()](#getSound--) | Возвращает или задает встроенные аудиоданные. |
| [setSound(IAudio value)](#setSound-com.aspose.slides.IAudio-) | Возвращает или задает встроенные аудиоданные. |
| [getSoundMode()](#getSoundMode--) | Устанавливает или возвращает режим звука для перехода слайда. |
| [setSoundMode(int value)](#setSoundMode-int-) | Устанавливает или возвращает режим звука для перехода слайда. |
| [getSoundLoop()](#getSoundLoop--) | Этот атрибут указывает, будет ли звук зацикливаться до наступления следующего звукового события в слайд-шоу. |
| [setSoundLoop(boolean value)](#setSoundLoop-boolean-) | Этот атрибут указывает, будет ли звук зацикливаться до наступления следующего звукового события в слайд-шоу. |
| [getAdvanceOnClick()](#getAdvanceOnClick--) | Указывает, будет ли щелчок мыши переключать слайд или нет. |
| [setAdvanceOnClick(boolean value)](#setAdvanceOnClick-boolean-) | Указывает, будет ли щелчок мыши переключать слайд или нет. |
| [getAdvanceAfter()](#getAdvanceAfter--) | Этот атрибут указывает, перейдет ли слайд-шоу к следующему слайду через определённое время. |
| [setAdvanceAfter(boolean value)](#setAdvanceAfter-boolean-) | Этот атрибут указывает, перейдет ли слайд-шоу к следующему слайду через определённое время. |
| [getAdvanceAfterTime()](#getAdvanceAfterTime--) | Указывает время в миллисекундах, после которого должен начаться переход. |
| [setAdvanceAfterTime(long value)](#setAdvanceAfterTime-long-) | Указывает время в миллисекундах, после которого должен начаться переход. |
| [getSpeed()](#getSpeed--) | Указывает скорость перехода, используемую при переходе от текущего слайда к следующему. |
| [setSpeed(int value)](#setSpeed-int-) | Указывает скорость перехода, используемую при переходе от текущего слайда к следующему. |
| [getValue()](#getValue--) | Значение перехода слайд-шоу. |
| [getType()](#getType--) | Тип перехода. |
| [setType(int value)](#setType-int-) | Тип перехода. |
| [getSoundIsBuiltIn()](#getSoundIsBuiltIn--) | Указывает, является ли этот звук встроенным. |
| [setSoundIsBuiltIn(boolean value)](#setSoundIsBuiltIn-boolean-) | Указывает, является ли этот звук встроенным. |
| [getSoundName()](#getSoundName--) | Указывает человекочитаемое имя звука перехода. |
| [setSoundName(String value)](#setSoundName-java.lang.String-) | Указывает человекочитаемое имя звука перехода. |
| [getDuration()](#getDuration--) | Получает или задает длительность эффекта перехода слайда в миллисекундах. |
| [setDuration(int value)](#setDuration-int-) | Получает или задает длительность эффекта перехода слайда в миллисекундах. |
| [equals(Object obj)](#equals-java.lang.Object-) | Определяет, равны ли два экземпляра SlideShowTransition. |
| [hashCode()](#hashCode--) | Служит хеш-функцией для конкретного типа, пригодной для использования в хеш-алгоритмах и структурах данных, таких как хеш-таблица. |

### getSound() {#getSound--}
```
public final IAudio getSound()
```

Возвращает или задает встроенные аудиоданные. Чтение/запись [IAudio](../../com.aspose.slides/iaudio).

**Возвращаемое значение:**
[IAudio](../../com.aspose.slides/iaudio)

### setSound(IAudio value) {#setSound-com.aspose.slides.IAudio-}
```
public final void setSound(IAudio value)
```

Возвращает или задает встроенные аудиоданные. Чтение/запись [IAudio](../../com.aspose.slides/iaudio).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [IAudio](../../com.aspose.slides/iaudio) |  |

### getSoundMode() {#getSoundMode--}
```
public final int getSoundMode()
```

Устанавливает или возвращает режим звука для перехода слайда. Чтение/запись [TransitionSoundMode](../../com.aspose.slides/transitionsoundmode).

**Возвращаемое значение:**
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

Этот атрибут указывает, будет ли звук зацикливаться до наступления следующего звукового события в слайд-шоу. Чтение/запись boolean.

**Возвращаемое значение:**
boolean

### setSoundLoop(boolean value) {#setSoundLoop-boolean-}
```
public final void setSoundLoop(boolean value)
```

Этот атрибут указывает, будет ли звук зацикливаться до наступления следующего звукового события в слайд-шоу. Чтение/запись boolean.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |

### getAdvanceOnClick() {#getAdvanceOnClick--}
```
public final boolean getAdvanceOnClick()
```

Указывает, будет ли щелчок мыши переключать слайд или нет. Если атрибут не указан, считается значение true. Чтение/запись boolean.

**Возвращаемое значение:**
boolean

### setAdvanceOnClick(boolean value) {#setAdvanceOnClick-boolean-}
```
public final void setAdvanceOnClick(boolean value)
```

Указывает, будет ли щелчок мыши переключать слайд или нет. Если атрибут не указан, считается значение true. Чтение/запись boolean.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |

### getAdvanceAfter() {#getAdvanceAfter--}
```
public final boolean getAdvanceAfter()
```

Этот атрибут указывает, перейдет ли слайд-шоу к следующему слайду через определённое время. Чтение/запись boolean.

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
>          // Получить значение времени Advance Slide After
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
public final void setAdvanceAfter(boolean value)
```

Этот атрибут указывает, перейдет ли слайд-шоу к следующему слайду через определённое время. Чтение/запись boolean.

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
>          // Получить значение времени Advance Slide After
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

Указывает время в миллисекундах, после которого должен начаться переход. Этот параметр может использоваться совместно с атрибутом advClick. Если атрибут не указан, считается, что авто-переход не будет происходить. Чтение/запись long.

**Возвращаемое значение:**
long

### setAdvanceAfterTime(long value) {#setAdvanceAfterTime-long-}
```
public final void setAdvanceAfterTime(long value)
```

Указывает время в миллисекундах, после которого должен начаться переход. Этот параметр может использоваться совместно с атрибутом advClick. Если атрибут не указан, считается, что авто-переход не будет происходить. Чтение/запись long.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | long |  |

### getSpeed() {#getSpeed--}
```
public final int getSpeed()
```

Указывает скорость перехода, используемую при переходе от текущего слайда к следующему. Чтение/запись [TransitionSpeed](../../com.aspose.slides/transitionspeed).

**Возвращаемое значение:**
int

### setSpeed(int value) {#setSpeed-int-}
```
public final void setSpeed(int value)
```

Указывает скорость перехода, используемую при переходе от текущего слайда к следующему. Чтение/запись [TransitionSpeed](../../com.aspose.slides/transitionspeed).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getValue() {#getValue--}
```
public final ITransitionValueBase getValue()
```

Значение перехода слайд-шоу. Только чтение [ITransitionValueBase](../../com.aspose.slides/itransitionvaluebase).

**Возвращаемое значение:**
[ITransitionValueBase](../../com.aspose.slides/itransitionvaluebase)

### getType() {#getType--}
```
public final int getType()
```

Тип перехода. Чтение/запись [TransitionType](../../com.aspose.slides/transitiontype).

**Возвращаемое значение:**
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

Указывает, является ли этот звук встроенным. Если атрибут установлен в true, генерирующее приложение должно проверить атрибут name, указанный для этого звука в списке встроенных звуков, и при необходимости отобразить пользовательское имя или интерфейс. Чтение/запись boolean.

**Возвращаемое значение:**
boolean

### setSoundIsBuiltIn(boolean value) {#setSoundIsBuiltIn-boolean-}
```
public final void setSoundIsBuiltIn(boolean value)
```

Указывает, является ли этот звук встроенным. Если атрибут установлен в true, генерирующее приложение должно проверить атрибут name, указанный для этого звука в списке встроенных звуков, и при необходимости отобразить пользовательское имя или интерфейс. Чтение/запись boolean.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |

### getSoundName() {#getSoundName--}
```
public final String getSoundName()
```

Указывает человекочитаемое имя звука перехода. Свойство Sound (\#getSound.getSound/\#setSound(IAudio).setSound(IAudio)) должно быть назначено для получения или установки имени звука. Чтение/запись String.

**Возвращаемое значение:**
java.lang.String

### setSoundName(String value) {#setSoundName-java.lang.String-}
```
public final void setSoundName(String value)
```

Указывает человекочитаемое имя звука перехода. Свойство Sound (\#getSound.getSound/\#setSound(IAudio).setSound(IAudio)) должно быть назначено для получения или установки имени звука. Чтение/запись String.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String |  |

### getDuration() {#getDuration--}
```
public final int getDuration()
```

Получает или задает длительность эффекта перехода слайда в миллисекундах. Чтение/запись int.

--------------------

Соответствует атрибуту p14:dur элемента p:transition в схеме PresentationML. Если не установлен, длительность определяется автоматически на основе свойства \#getSpeed.getSpeed/\#setSpeed(int).setSpeed(int) и типа перехода.

**Возвращаемое значение:**
int

### setDuration(int value) {#setDuration-int-}
```
public final void setDuration(int value)
```

Получает или задает длительность эффекта перехода слайда в миллисекундах. Чтение/запись int.

--------------------

Соответствует атрибуту p14:dur элемента p:transition в схеме PresentationML. Если не установлен, длительность определяется автоматически на основе свойства \#getSpeed.getSpeed/\#setSpeed(int).setSpeed(int) и типа перехода.

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
| obj | java.lang.Object | SlideShowTransition, с которым сравнивается текущий SlideShowTransition. |

**Возвращаемое значение:**
boolean -  **true**  если указанный SlideShowTransition равен текущему SlideShowTransition; иначе  **false** .

### hashCode() {#hashCode--}
```
public int hashCode()
```

Служит хеш-функцией для конкретного типа, пригодной для использования в хеш-алгоритмах и структурах данных, таких как хеш-таблица.

**Возвращаемое значение:**
int - 23454

--------------------

Переопределено, чтобы удовлетворить компилятор. Всегда возвращает константу, потому что объект изменяемый.