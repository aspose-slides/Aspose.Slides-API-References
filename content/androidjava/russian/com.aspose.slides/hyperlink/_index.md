---
title: Hyperlink
second_title: Aspose.Slides для Android через справочник Java API
description: Представляет гиперссылку.
type: docs
url: /ru/com.aspose.slides/hyperlink/
---
**Наследование:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**Все реализованные интерфейсы:**
[com.aspose.slides.IHyperlink](../../com.aspose.slides/ihyperlink), com.aspose.slides.IDOMObject
```
public final class Hyperlink extends PVIObject implements IHyperlink, IDOMObject
```

Представляет гиперссылку.

## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [Hyperlink(String url)](#Hyperlink-java.lang.String-) | Создает экземпляр гиперссылки. |
| [Hyperlink(ISlide slide)](#Hyperlink-com.aspose.slides.ISlide-) | Создает экземпляр гиперссылки, указывающей на конкретный слайд. |
| [Hyperlink(Hyperlink source, String targetFrame, String tooltip, boolean history, boolean stopSoundsOnClick, boolean highlightClick)](#Hyperlink-com.aspose.slides.Hyperlink-java.lang.String-java.lang.String-boolean-boolean-boolean-) | Создает экземпляр гиперссылки, используя другую гиперссылку в качестве источника, переопределяя вторичные свойства. |

## Методы

| Метод | Описание |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getNoAction()](#getNoAction--) | Возвращает специальную «ничего не делать» гиперссылку. |
| [getMedia()](#getMedia--) | Возвращает специальную «воспроизвести mediafile» гиперссылку. |
| [getNextSlide()](#getNextSlide--) | Возвращает гиперссылку на следующий слайд. |
| [getPreviousSlide()](#getPreviousSlide--) | Возвращает гиперссылку на предыдущий слайд. |
| [getFirstSlide()](#getFirstSlide--) | Возвращает гиперссылку на первый слайд презентации. |
| [getLastSlide()](#getLastSlide--) | Возвращает гиперссылку на последний слайд презентации. |
| [getLastVievedSlide()](#getLastVievedSlide--) | Возвращает гиперссылку на последний просмотренный слайд. |
| [getEndShow()](#getEndShow--) | Возвращает гиперссылку, завершающую показ. |
| [getActionType()](#getActionType--) | Возвращает тип действия гиперссылки. |
| [getExternalUrl()](#getExternalUrl--) | Указывает внешний URL. |
| [getTargetSlide()](#getTargetSlide--) | Если гиперссылка указывает на конкретный слайд, возвращает этот слайд. |
| [getExternalUrlOriginal()](#getExternalUrlOriginal--) | Представляет гиперссылку, установленную для этой части независимо от реального содержимого части. |
| [getTargetFrame()](#getTargetFrame--) | Возвращает кадр в родительском наборе HTML-кадров для цели родительской гиперссылки, если он существует. |
| [setTargetFrame(String value)](#setTargetFrame-java.lang.String-) | Возвращает кадр в родительском наборе HTML-кадров для цели родительской гиперссылки, если он существует. |
| [getTooltip()](#getTooltip--) | Возвращает строку, которая может отображаться в пользовательском интерфейсе как связанная с родительской гиперссылкой. |
| [setTooltip(String value)](#setTooltip-java.lang.String-) | Возвращает строку, которая может отображаться в пользовательском интерфейсе как связанная с родительской гиперссылкой. |
| [getHistory()](#getHistory--) | Определяет, будет ли цель родительской гиперссылки добавлена в список просмотренных гиперссылок при её вызове. |
| [setHistory(boolean value)](#setHistory-boolean-) | Определяет, будет ли цель родительской гиперссылки добавлена в список просмотренных гиперссылок при её вызове. |
| [getHighlightClick()](#getHighlightClick--) | Определяет, должна ли гиперссылка подсвечиваться при клике. |
| [setHighlightClick(boolean value)](#setHighlightClick-boolean-) | Определяет, должна ли гиперссылка подсвечиваться при клике. |
| [getStopSoundOnClick()](#getStopSoundOnClick--) | Определяет, должно ли воспроизведение звука быть остановлено при клике по гиперссылке. |
| [setStopSoundOnClick(boolean value)](#setStopSoundOnClick-boolean-) | Определяет, должно ли воспроизведение звука быть остановлено при клике по гиперссылке. |
| [getSound()](#getSound--) | Представляет звук, воспроизводимый гиперссылкой. |
| [setSound(IAudio value)](#setSound-com.aspose.slides.IAudio-) | Представляет звук, воспроизводимый гиперссылкой. |
| [getColorSource()](#getColorSource--) | Представляет источник цвета гиперссылки — стили или формат части. |
| [setColorSource(int value)](#setColorSource-int-) | Представляет источник цвета гиперссылки — стили или формат части. |
| [equals(Object obj)](#equals-java.lang.Object-) | Определяет, равны ли два объекта Hyperlink. |
| [equals(IHyperlink hlink)](#equals-com.aspose.slides.IHyperlink-) | Определяет, равны ли два объекта Hyperlink. |
| [op_Equality(Hyperlink hlink1, Hyperlink hlink2)](#op-Equality-com.aspose.slides.Hyperlink-com.aspose.slides.Hyperlink-) | Тестирует две гиперссылки на равенство. |
| [op_Inequality(Hyperlink hlink1, Hyperlink hlink2)](#op-Inequality-com.aspose.slides.Hyperlink-com.aspose.slides.Hyperlink-) | Тестирует две гиперссылки на неравенство. |
| [hashCode()](#hashCode--) | Служит функцией хеширования для конкретного типа, пригодной для использования в алгоритмах хеширования и структурах данных, таких как хеш-таблица. |
| [getParent_Immediate()](#getParent-Immediate--) |  |

### Hyperlink(String url) {#Hyperlink-java.lang.String-}
```
public Hyperlink(String url)
```

Создает экземпляр гиперссылки.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| url | java.lang.String | URL гиперссылки. |

### Hyperlink(ISlide slide) {#Hyperlink-com.aspose.slides.ISlide-}
```
public Hyperlink(ISlide slide)
```

Создает экземпляр гиперссылки, указывающей на конкретный слайд. Примечание: созданную гиперссылку следует назначить объекту из той же презентации, иначе ссылка будет сохранена как NoAction.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| slide | [ISlide](../../com.aspose.slides/islide) | Целевой слайд. |

### Hyperlink(Hyperlink source, String targetFrame, String tooltip, boolean history, boolean stopSoundsOnClick, boolean highlightClick) {#Hyperlink-com.aspose.slides.Hyperlink-java.lang.String-java.lang.String-boolean-boolean-boolean-}
```
public Hyperlink(Hyperlink source, String targetFrame, String tooltip, boolean history, boolean stopSoundsOnClick, boolean highlightClick)
```

Создает экземпляр гиперссылки, используя другую гиперссылку в качестве источника, переопределяя вторичные свойства.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| source | [Hyperlink](../../com.aspose.slides/hyperlink) | Исходная гиперссылка |
| targetFrame | java.lang.String | Целевой кадр |
| tooltip | java.lang.String | Текст подсказки |
| history | boolean | Определяет, будет ли цель родительской гиперссылки добавлена в список просмотренных гиперссылок при её вызове. |
| stopSoundsOnClick | boolean | Определяет, должно ли воспроизведение звука быть остановлено при клике по гиперссылке. |
| highlightClick | boolean | Определяет, должна ли гиперссылка подсвечиваться при клике. |

### getVersion() {#getVersion--}
```
public long getVersion()
```

Версия. Только для чтения long.

**Возвращает:**
long

### getNoAction() {#getNoAction--}
```
public static Hyperlink getNoAction()
```

Возвращает специальную «ничего не делать» гиперссылку. Только для чтения [Hyperlink](../../com.aspose.slides/hyperlink).

**Возвращает:**
[Hyperlink](../../com.aspose.slides/hyperlink)

### getMedia() {#getMedia--}
```
public static Hyperlink getMedia()
```

Возвращает специальную «воспроизвести mediafile» гиперссылку. Используется в AudioFrame и VideoFrame. Только для чтения [Hyperlink](../../com.aspose.slides/hyperlink).

**Возвращает:**
[Hyperlink](../../com.aspose.slides/hyperlink)

### getNextSlide() {#getNextSlide--}
```
public static Hyperlink getNextSlide()
```

Возвращает гиперссылку на следующий слайд. Только для чтения [Hyperlink](../../com.aspose.slides/hyperlink).

**Возвращает:**
[Hyperlink](../../com.aspose.slides/hyperlink)

### getPreviousSlide() {#getPreviousSlide--}
```
public static Hyperlink getPreviousSlide()
```

Возвращает гиперссылку на предыдущий слайд. Только для чтения [Hyperlink](../../com.aspose.slides/hyperlink).

**Возвращает:**
[Hyperlink](../../com.aspose.slides/hyperlink)

### getFirstSlide() {#getFirstSlide--}
```
public static Hyperlink getFirstSlide()
```

Возвращает гиперссылку на первый слайд презентации. Только для чтения [Hyperlink](../../com.aspose.slides/hyperlink).

**Возвращает:**
[Hyperlink](../../com.aspose.slides/hyperlink)

### getLastSlide() {#getLastSlide--}
```
public static Hyperlink getLastSlide()
```

Возвращает гиперссылку на последний слайд презентации. Только для чтения [Hyperlink](../../com.aspose.slides/hyperlink).

**Возвращает:**
[Hyperlink](../../com.aspose.slides/hyperlink)

### getLastVievedSlide() {#getLastVievedSlide--}
```
public static Hyperlink getLastVievedSlide()
```

Возвращает гиперссылку на последний просмотренный слайд. Только для чтения [Hyperlink](../../com.aspose.slides/hyperlink).

**Возвращает:**
[Hyperlink](../../com.aspose.slides/hyperlink)

### getEndShow() {#getEndShow--}
```
public static Hyperlink getEndShow()
```

Возвращает гиперссылку, завершающую показ. Только для чтения [Hyperlink](../../com.aspose.slides/hyperlink).

**Возвращает:**
[Hyperlink](../../com.aspose.slides/hyperlink)

### getActionType() {#getActionType--}
```
public final int getActionType()
```

Возвращает тип действия гиперссылки. Только для чтения [HyperlinkActionType](../../com.aspose.slides/hyperlinkactiontype).

**Возвращает:**
int

### getExternalUrl() {#getExternalUrl--}
```
public final String getExternalUrl()
```

Указывает внешний URL. Только для чтения String.

**Возвращает:**
java.lang.String

### getTargetSlide() {#getTargetSlide--}
```
public final ISlide getTargetSlide()
```

Если гиперссылка указывает на конкретный слайд, возвращает этот слайд. Только для чтения [ISlide](../../com.aspose.slides/islide).

**Возвращает:**
[ISlide](../../com.aspose.slides/islide)

### getExternalUrlOriginal() {#getExternalUrlOriginal--}
```
public final String getExternalUrlOriginal()
```

Представляет гиперссылку, установленную для этой части независимо от реального содержимого части.

--------------------

PowerPoint ведет себя особым образом со ссылками и их соответствующим текстом в части. Он позволяет создать текст для гиперссылки в виде действительного URL, отличного от реального адреса ссылки. В этом случае, когда вы просматриваете ссылку в окне редактирования, она будет изменена, чтобы соответствовать текстовой части. Это свойство представляет исходное значение гиперссылки.

**Возвращает:**
java.lang.String

### getTargetFrame() {#getTargetFrame--}
```
public final String getTargetFrame()
```

Возвращает кадр в родительском наборе HTML-кадров для цели родительской гиперссылки, если он существует. Чтение/запись String.

**Возвращает:**
java.lang.String

### setTargetFrame(String value) {#setTargetFrame-java.lang.String-}
```
public final void setTargetFrame(String value)
```

Возвращает кадр в родительском наборе HTML-кадров для цели родительской гиперссылки, если он существует. Чтение/запись String.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String |  |

### getTooltip() {#getTooltip--}
```
public final String getTooltip()
```

Возвращает строку, которая может отображаться в пользовательском интерфейсе как связанная с родительской гиперссылкой. Чтение/запись String.

**Возвращает:**
java.lang.String

### setTooltip(String value) {#setTooltip-java.lang.String-}
```
public final void setTooltip(String value)
```

Возвращает строку, которая может отображаться в пользовательском интерфейсе как связанная с родительской гиперссылкой. Чтение/запись String.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String |  |

### getHistory() {#getHistory--}
```
public final boolean getHistory()
```

Определяет, будет ли цель родительской гиперссылки добавлена в список просмотренных гиперссылок при её вызове. Чтение/запись boolean.

**Возвращает:**
boolean

### setHistory(boolean value) {#setHistory-boolean-}
```
public final void setHistory(boolean value)
```

Определяет, будет ли цель родительской гиперссылки добавлена в список просмотренных гиперссылок при её вызове. Чтение/запись boolean.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |

### getHighlightClick() {#getHighlightClick--}
```
public final boolean getHighlightClick()
```

Определяет, должна ли гиперссылка подсвечиваться при клике. Чтение/запись boolean.

**Возвращает:**
boolean

### setHighlightClick(boolean value) {#setHighlightClick-boolean-}
```
public final void setHighlightClick(boolean value)
```

Определяет, должна ли гиперссылка подсвечиваться при клике. Чтение/запись boolean.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |

### getStopSoundOnClick() {#getStopSoundOnClick--}
```
public final boolean getStopSoundOnClick()
```

Определяет, должно ли воспроизведение звука быть остановлено при клике по гиперссылке. Чтение/запись boolean.

**Возвращает:**
boolean

### setStopSoundOnClick(boolean value) {#setStopSoundOnClick-boolean-}
```
public final void setStopSoundOnClick(boolean value)
```

Определяет, должно ли воспроизведение звука быть остановлено при клике по гиперссылке. Чтение/запись boolean.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |

### getSound() {#getSound--}
```
public final IAudio getSound()
```

Представляет звук, воспроизводимый гиперссылкой. Чтение/запись [IAudio](../../com.aspose.slides/iaudio).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
> 
>      // Получить гиперссылку первой формы
>      IHyperlink link = presentation.getSlides().get_Item(0).getShapes().get_Item(0).getHyperlinkClick();
> 
>      if (link.getSound() != null)
>      {
>          // Извлечь звук гиперссылки в массив байтов
>          byte[] audioData = link.getSound().getBinaryData();
>      }
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Возвращает:**
[IAudio](../../com.aspose.slides/iaudio)

### setSound(IAudio value) {#setSound-com.aspose.slides.IAudio-}
```
public final void setSound(IAudio value)
```

Представляет звук, воспроизводимый гиперссылкой. Чтение/запись [IAudio](../../com.aspose.slides/iaudio).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
> 
>      // Получить гиперссылку первой формы
>      IHyperlink link = presentation.getSlides().get_Item(0).getShapes().get_Item(0).getHyperlinkClick();
> 
>      if (link.getSound() != null)
>      {
>          // Извлечь звук гиперссылки в массив байтов
>          byte[] audioData = link.getSound().getBinaryData();
>      }
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [IAudio](../../com.aspose.slides/iaudio) |  |

### getColorSource() {#getColorSource--}
```
public final int getColorSource()
```

Представляет источник цвета гиперссылки — стили или формат части. Чтение/запись [HyperlinkColorSource](../../com.aspose.slides/hyperlinkcolorsource).

**Возвращает:**
int

### setColorSource(int value) {#setColorSource-int-}
```
public final void setColorSource(int value)
```

Представляет источник цвета гиперссылки — стили или формат части. Чтение/запись [HyperlinkColorSource](../../com.aspose.slides/hyperlinkcolorsource).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

Определяет, равны ли два объекта Hyperlink.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| obj | java.lang.Object | Hyperlink для сравнения с текущим Hyperlink. |

**Возвращает:**
boolean — **true**, если указанный Hyperlink равен текущему; иначе **false**.

### equals(IHyperlink hlink) {#equals-com.aspose.slides.IHyperlink-}
```
public final boolean equals(IHyperlink hlink)
```

Определяет, равны ли два объекта Hyperlink.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| hlink | [IHyperlink](../../com.aspose.slides/ihyperlink) | Hyperlink для сравнения с текущим Hyperlink. |

**Возвращает:**
boolean — **true**, если указанный Hyperlink равен текущему; иначе **false**.

### op_Equality(Hyperlink hlink1, Hyperlink hlink2) {#op-Equality-com.aspose.slides.Hyperlink-com.aspose.slides.Hyperlink-}
```
public static boolean op_Equality(Hyperlink hlink1, Hyperlink hlink2)
```

Тестирует две гиперссылки на равенство.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| hlink1 | [Hyperlink](../../com.aspose.slides/hyperlink) | Первая гиперссылка для тестирования. |
| hlink2 | [Hyperlink](../../com.aspose.slides/hyperlink) | Вторая гиперссылка для тестирования. |

**Возвращает:**
boolean — **true**, если гиперссылки равны.

### op_Inequality(Hyperlink hlink1, Hyperlink hlink2) {#op-Inequality-com.aspose.slides.Hyperlink-com.aspose.slides.Hyperlink-}
```
public static boolean op_Inequality(Hyperlink hlink1, Hyperlink hlink2)
```

Тестирует две гиперссылки на неравенство.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| hlink1 | [Hyperlink](../../com.aspose.slides/hyperlink) | Первая гиперссылка для тестирования. |
| hlink2 | [Hyperlink](../../com.aspose.slides/hyperlink) | Вторая гиперссылка для тестирования. |

**Возвращает:**
boolean — **false**, если гиперссылки равны.

### hashCode() {#hashCode--}
```
public int hashCode()
```

Служит функцией хеширования для конкретного типа, пригодной для использования в алгоритмах хеширования и структурах данных, таких как хеш-таблица.

**Возвращает:**
int — Хеш-код для URL.

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Возвращает объект Parent_Immediate. Только для чтения IDOMObject.

**Возвращает:**
com.aspose.slides.IDOMObject