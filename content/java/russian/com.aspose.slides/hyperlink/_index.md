---
title: Hyperlink
second_title: Справочник API Aspose.Slides для Java
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
| [Hyperlink(String url)](#Hyperlink-java.lang.String-) | Creates an instance of a hyperlink. |
| [Hyperlink(ISlide slide)](#Hyperlink-com.aspose.slides.ISlide-) | Creates an instance of a hyperlink which points to specific slide. |
| [Hyperlink(Hyperlink source, String targetFrame, String tooltip, boolean history, boolean stopSoundsOnClick, boolean highlightClick)](#Hyperlink-com.aspose.slides.Hyperlink-java.lang.String-java.lang.String-boolean-boolean-boolean-) | Creates an instance of a hyperlink using another hyperlink as source, overriding secondary properties. |
## Методы

| Метод | Описание |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getNoAction()](#getNoAction--) | Returns a special "do nothing" hyperlink. |
| [getMedia()](#getMedia--) | Returns a special "play mediafile" hyperlink. |
| [getNextSlide()](#getNextSlide--) | Returns a hyperlink to the next slide. |
| [getPreviousSlide()](#getPreviousSlide--) | Returns a hyperlink to the previous slide. |
| [getFirstSlide()](#getFirstSlide--) | Returns a hyperlink to the first slide of the presentation. |
| [getLastSlide()](#getLastSlide--) | Returns a hyperlink to the last slide of the presentation. |
| [getLastVievedSlide()](#getLastVievedSlide--) | Returns a hyperlink to the last viewed slide. |
| [getEndShow()](#getEndShow--) | Returns a hyperlink which ends the show. |
| [getActionType()](#getActionType--) | Returns type of Hyperlink's action. |
| [getExternalUrl()](#getExternalUrl--) | Specifies the external URL. |
| [getTargetSlide()](#getTargetSlide--) | If the Hyperlink targets specific slide returns this slide. |
| [getExternalUrlOriginal()](#getExternalUrlOriginal--) | Represents a hyperlink that is set for this portion without regard to the actual content of the portion. |
| [getTargetFrame()](#getTargetFrame--) | Returns the frame within the parent HTML frameset for the target of the parent hyperlink when one exists. |
| [setTargetFrame(String value)](#setTargetFrame-java.lang.String-) | Returns the frame within the parent HTML frameset for the target of the parent hyperlink when one exists. |
| [getTooltip()](#getTooltip--) | Returns the string which may be surfaced in a user interface as associated with the parent hyperlink. |
| [setTooltip(String value)](#setTooltip-java.lang.String-) | Returns the string which may be surfaced in a user interface as associated with the parent hyperlink. |
| [getHistory()](#getHistory--) | Determines whether the target of the parent hyperlink shall be added to a list of viewed hyperlinks when it is invoked. |
| [setHistory(boolean value)](#setHistory-boolean-) | Determines whether the target of the parent hyperlink shall be added to a list of viewed hyperlinks when it is invoked. |
| [getHighlightClick()](#getHighlightClick--) | Determines whether the hyperlink should be highlighted on click. |
| [setHighlightClick(boolean value)](#setHighlightClick-boolean-) | Determines whether the hyperlink should be highlighted on click. |
| [getStopSoundOnClick()](#getStopSoundOnClick--) | Determines whether the sound should be stopped on hyperlink click. |
| [setStopSoundOnClick(boolean value)](#setStopSoundOnClick-boolean-) | Determines whether the sound should be stopped on hyperlink click. |
| [getSound()](#getSound--) | Represents the playing sound of the hyperlink. |
| [setSound(IAudio value)](#setSound-com.aspose.slides.IAudio-) | Represents the playing sound of the hyperlink. |
| [getColorSource()](#getColorSource--) | Represents the source of hyperlink color - either styles or portion format. |
| [setColorSource(int value)](#setColorSource-int-) | Represents the source of hyperlink color - either styles or portion format. |
| [equals(Object obj)](#equals-java.lang.Object-) | Determines whether the two Hyperlink instances are equal. |
| [equals(IHyperlink hlink)](#equals-com.aspose.slides.IHyperlink-) | Determines whether the two Hyperlink instances are equal. |
| [op_Equality(Hyperlink hlink1, Hyperlink hlink2)](#op-Equality-com.aspose.slides.Hyperlink-com.aspose.slides.Hyperlink-) | Tests two hyperlinks for equality. |
| [op_Inequality(Hyperlink hlink1, Hyperlink hlink2)](#op-Inequality-com.aspose.slides.Hyperlink-com.aspose.slides.Hyperlink-) | Tests two hyperlinks for inequality. |
| [hashCode()](#hashCode--) | Serves as a hash function for a particular type, suitable for use in hashing algorithms and data structures like a hash table. |
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

Создает экземпляр гиперссылки, который указывает на конкретный слайд. Примечание: созданная гиперссылка должна быть назначена объекту из той же презентации, иначе ссылка будет сохранена как NoAction.

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
| targetFrame | java.lang.String | Целевой фрейм |
| tooltip | java.lang.String | Текст всплывающей подсказки |
| history | boolean | Определяет, будет ли цель родительской гиперссылки добавлена в список просмотренных гиперссылок при её вызове. |
| stopSoundsOnClick | boolean | Определяет, будет ли звук остановлен при щелчке по гиперссылке. |
| highlightClick | boolean | Определяет, будет ли гиперссылка выделена при щелчке. |
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

Возвращает специальную гиперссылку "do nothing". Только для чтения [Hyperlink](../../com.aspose.slides/hyperlink).

**Возвращает:**
[Hyperlink](../../com.aspose.slides/hyperlink)
### getMedia() {#getMedia--}
```
public static Hyperlink getMedia()
```

Возвращает специальную гиперссылку "play mediafile". Используется в AudioFrame и VideoFrame. Только для чтения [Hyperlink](../../com.aspose.slides/hyperlink).

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

Возвращает гиперссылку, которая завершает показ. Только для чтения [Hyperlink](../../com.aspose.slides/hyperlink).

**Возвращает:**
[Hyperlink](../../com.aspose.slides/hyperlink)
### getActionType() {#getActionType--}
```
public final int getActionType()
```

Возвращает тип действия Hyperlink. Только для чтения [HyperlinkActionType](../../com.aspose.slides/hyperlinkactiontype).

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

Если Hyperlink указывает конкретный слайд, возвращает этот слайд. Только для чтения [ISlide](../../com.aspose.slides/islide).

**Возвращает:**
[ISlide](../../com.aspose.slides/islide)
### getExternalUrlOriginal() {#getExternalUrlOriginal--}
```
public final String getExternalUrlOriginal()
```

Представляет гиперссылку, установленную для этой части без учета реального содержания части.

--------------------

PowerPoint имеет особое поведение для ссылок и соответствующего им текста в части. Он позволяет создавать текст для гиперссылки в виде действительного URL, отличного от реального адреса ссылки. В этом случае, когда вы просматриваете ссылку в окне редактирования, она будет изменена, чтобы соответствовать текстовой части. Это свойство представляет оригинальное значение гиперссылки.

**Возвращает:**
java.lang.String
### getTargetFrame() {#getTargetFrame--}
```
public final String getTargetFrame()
```

Возвращает фрейм внутри родительского HTML-фреймсета для цели родительской гиперссылки, если такой существует. Только для чтения String.

**Возвращает:**
java.lang.String
### setTargetFrame(String value) {#setTargetFrame-java.lang.String-}
```
public final void setTargetFrame(String value)
```

Возвращает фрейм внутри родительского HTML-фреймсета для цели родительской гиперссылки, если такой существует. Чтение/запись String.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String |  |
### getTooltip() {#getTooltip--}
```
public final String getTooltip()
```

Возвращает строку, которая может быть отображена в пользовательском интерфейсе как связанная с родительской гиперссылкой. Чтение/запись String.

**Возвращает:**
java.lang.String
### setTooltip(String value) {#setTooltip-java.lang.String-}
```
public final void setTooltip(String value)
```

Возвращает строку, которая может быть отображена в пользовательском интерфейсе как связанная с родительской гиперссылкой. Чтение/запись String.

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

Определяет, будет ли гиперссылка выделена при щелчке. Чтение/запись boolean.

**Возвращает:**
boolean
### setHighlightClick(boolean value) {#setHighlightClick-boolean-}
```
public final void setHighlightClick(boolean value)
```

Определяет, будет ли гиперссылка выделена при щелчке. Чтение/запись boolean.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |
### getStopSoundOnClick() {#getStopSoundOnClick--}
```
public final boolean getStopSoundOnClick()
```

Определяет, будет ли звук остановлен при щелчке по гиперссылке. Чтение/запись boolean.

**Возвращает:**
boolean
### setStopSoundOnClick(boolean value) {#setStopSoundOnClick-boolean-}
```
public final void setStopSoundOnClick(boolean value)
```

Определяет, будет ли звук остановлен при щелчке по гиперссылке. Чтение/запись boolean.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |
### getSound() {#getSound--}
```
public final IAudio getSound()
```

Представляет воспроизводимый звук гиперссылки. Чтение/запись [IAudio](../../com.aspose.slides/iaudio).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
> 
>      // Получить гиперссылку первой фигуры
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

Представляет воспроизводимый звук гиперссылки. Чтение/запись [IAudio](../../com.aspose.slides/iaudio).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
> 
>      // Получить гиперссылку первой фигуры
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

Представляет источник цвета гиперссылки — либо стили, либо формат части. Чтение/запись [HyperlinkColorSource](../../com.aspose.slides/hyperlinkcolorsource).

**Возвращает:**
int
### setColorSource(int value) {#setColorSource-int-}
```
public final void setColorSource(int value)
```

Представляет источник цвета гиперссылки — либо стили, либо формат части. Чтение/запись [HyperlinkColorSource](../../com.aspose.slides/hyperlinkcolorsource).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

Определяет, равны ли два экземпляра Hyperlink.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| obj | java.lang.Object | Гиперссылка для сравнения с текущей гиперссылкой. |

**Возвращает:**
boolean - **true** если указанная гиперссылка равна текущей; иначе **false**.
### equals(IHyperlink hlink) {#equals-com.aspose.slides.IHyperlink-}
```
public final boolean equals(IHyperlink hlink)
```

Определяет, равны ли два экземпляра Hyperlink.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| hlink | [IHyperlink](../../com.aspose.slides/ihyperlink) | Гиперссылка для сравнения с текущей гиперссылкой. |

**Возвращает:**
boolean - **true** если указанная гиперссылка равна текущей; иначе **false**.
### op_Equality(Hyperlink hlink1, Hyperlink hlink2) {#op-Equality-com.aspose.slides.Hyperlink-com.aspose.slides.Hyperlink-}
```
public static boolean op_Equality(Hyperlink hlink1, Hyperlink hlink2)
```

Тестирует две гиперссылки на равенство.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| hlink1 | [Hyperlink](../../com.aspose.slides/hyperlink) | Первая гиперссылка для теста. |
| hlink2 | [Hyperlink](../../com.aspose.slides/hyperlink) | Вторая гиперссылка для теста. |

**Возвращает:**
boolean - **true** если гиперссылки равны.
### op_Inequality(Hyperlink hlink1, Hyperlink hlink2) {#op-Inequality-com.aspose.slides.Hyperlink-com.aspose.slides.Hyperlink-}
```
public static boolean op_Inequality(Hyperlink hlink1, Hyperlink hlink2)
```

Тестирует две гиперссылки на неравенство.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| hlink1 | [Hyperlink](../../com.aspose.slides/hyperlink) | Первая гиперссылка для теста. |
| hlink2 | [Hyperlink](../../com.aspose.slides/hyperlink) | Вторая гиперссылка для теста. |

**Возвращает:**
boolean - **false** если гиперссылки равны.
### hashCode() {#hashCode--}
```
public int hashCode()
```

Служит хэш-функцией для данного типа, пригодной для использования в хеш-алгоритмах и структурах данных, таких как хеш-таблица.

**Возвращает:**
int - Хеш-код для URL.
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Возвращает объект Parent_Immediate. Только для чтения IDOMObject.

**Возвращает:**
com.aspose.slides.IDOMObject