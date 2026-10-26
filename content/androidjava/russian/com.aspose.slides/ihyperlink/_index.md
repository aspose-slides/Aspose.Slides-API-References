---
title: IHyperlink
second_title: Aspose.Slides for Android via Java API Reference
description: Represents a hyperlink.
type: docs
url: /ru/com.aspose.slides/ihyperlink/
---```
public interface IHyperlink
```

Представляет гиперссылку.
## Методы

| Метод | Описание |
| --- | --- |
| [getActionType()](#getActionType--) | Возвращает тип действия HyperLinkEx. |
| [getExternalUrl()](#getExternalUrl--) | Указывает внешний URL. Если это свойство не равно null, то свойство TargetSlide становится null. |
| [getExternalUrlOriginal()](#getExternalUrlOriginal--) | Представляет гиперссылку, установленную для этой части без учёта фактического содержания части. |
| [getTargetSlide()](#getTargetSlide--) | Если HyperlinkEx направлен на конкретный слайд, возвращает этот слайд. |
| [getTargetFrame()](#getTargetFrame--) | Возвращает кадр внутри родительского набора HTML-фреймов для цели родительской гиперссылки, если он существует. |
| [setTargetFrame(String value)](#setTargetFrame-java.lang.String-) | Возвращает кадр внутри родительского набора HTML-фреймов для цели родительской гиперссылки, если он существует. |
| [getTooltip()](#getTooltip--) | Возвращает строку, которая может отображаться в пользовательском интерфейсе и ассоциирована с родительской гиперссылкой. |
| [setTooltip(String value)](#setTooltip-java.lang.String-) | Возвращает строку, которая может отображаться в пользовательском интерфейсе и ассоциирована с родительской гиперссылкой. |
| [getHistory()](#getHistory--) | Определяет, будет ли цель родительской гиперссылки добавлена в список просмотренных гиперссылок при её вызове. |
| [setHistory(boolean value)](#setHistory-boolean-) | Определяет, будет ли цель родительской гиперссылки добавлена в список просмотренных гиперссылок при её вызове. |
| [getHighlightClick()](#getHighlightClick--) | Определяет, должна ли гиперссылка быть выделена при щелчке. |
| [setHighlightClick(boolean value)](#setHighlightClick-boolean-) | Определяет, должна ли гиперссылка быть выделена при щелчке. |
| [getStopSoundOnClick()](#getStopSoundOnClick--) | Определяет, должно ли воспроизводимое звуковое сопровождение остановиться при щелчке по гиперссылке. |
| [setStopSoundOnClick(boolean value)](#setStopSoundOnClick-boolean-) | Определяет, должно ли воспроизводимое звуковое сопровождение остановиться при щелчке по гиперссылке. |
| [getSound()](#getSound--) | Представляет воспроизводимый звук гиперссылки. |
| [setSound(IAudio value)](#setSound-com.aspose.slides.IAudio-) | Представляет воспроизводимый звук гиперссылки. |
| [getColorSource()](#getColorSource--) | Представляет источник цвета гиперссылки — стили или формат части. |
| [setColorSource(int value)](#setColorSource-int-) | Представляет источник цвета гиперссылки — стили или формат части. |
| [equals(IHyperlink hlink)](#equals-com.aspose.slides.IHyperlink-) | Определяет, равны ли два экземпляра Hyperlink. |

### getActionType() {#getActionType--}
```
public abstract int getActionType()
```


Возвращает тип действия HyperLinkEx. Только для чтения [HyperlinkActionType](../../com.aspose.slides/hyperlinkactiontype).

**Возвращает:**
int

### getExternalUrl() {#getExternalUrl--}
```
public abstract String getExternalUrl()
```


Указывает внешний URL. Если это свойство не равно null, то свойство TargetSlide становится null. Только для чтения String.

**Возвращает:**
java.lang.String

### getExternalUrlOriginal() {#getExternalUrlOriginal--}
```
public abstract String getExternalUrlOriginal()
```


Представляет гиперссылку, установленную для этой части без учёта фактического содержания части.

--------------------

PowerPoint ведёт себя особым образом с ссылками и соответствующим им текстом в части. Он позволяет создавать текст для гиперссылки в виде корректного URL, отличного от реального адреса ссылки. В этом случае, когда вы просматриваете ссылку в окне редактирования, она будет изменена, чтобы соответствовать текстовой части. Это свойство представляет исходное значение гиперссылки.

**Возвращает:**
java.lang.String

### getTargetSlide() {#getTargetSlide--}
```
public abstract ISlide getTargetSlide()
```


Если HyperlinkEx направлен на конкретный слайд, возвращает этот слайд. Если свойство не равно null, то свойство ExternalUrl становится null. Только для чтения [ISlide](../../com.aspose.slides/islide).

**Возвращает:**
[ISlide](../../com.aspose.slides/islide)

### getTargetFrame() {#getTargetFrame--}
```
public abstract String getTargetFrame()
```


Возвращает кадр внутри родительского набора HTML-фреймов для цели родительской гиперссылки, если он существует. Чтение/запись String.

**Возвращает:**
java.lang.String

### setTargetFrame(String value) {#setTargetFrame-java.lang.String-}
```
public abstract void setTargetFrame(String value)
```


Возвращает кадр внутри родительского набора HTML-фреймов для цели родительской гиперссылки, если он существует. Чтение/запись String.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String |  |

### getTooltip() {#getTooltip--}
```
public abstract String getTooltip()
```


Возвращает строку, которая может отображаться в пользовательском интерфейсе и ассоциирована с родительской гиперссылкой. Чтение/запись String.

**Возвращает:**
java.lang.String

### setTooltip(String value) {#setTooltip-java.lang.String-}
```
public abstract void setTooltip(String value)
```


Возвращает строку, которая может отображаться в пользовательском интерфейсе и ассоциирована с родительской гиперссылкой. Чтение/запись String.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String |  |

### getHistory() {#getHistory--}
```
public abstract boolean getHistory()
```


Определяет, будет ли цель родительской гиперссылки добавлена в список просмотренных гиперссылок при её вызове. Чтение/запись boolean.

**Возвращает:**
boolean

### setHistory(boolean value) {#setHistory-boolean-}
```
public abstract void setHistory(boolean value)
```


Определяет, будет ли цель родительской гиперссылки добавлена в список просмотренных гиперссылок при её вызове. Чтение/запись boolean.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |

### getHighlightClick() {#getHighlightClick--}
```
public abstract boolean getHighlightClick()
```


Определяет, должна ли гиперссылка быть выделена при щелчке. Чтение/запись boolean.

**Возвращает:**
boolean

### setHighlightClick(boolean value) {#setHighlightClick-boolean-}
```
public abstract void setHighlightClick(boolean value)
```


Определяет, должна ли гиперссылка быть выделена при щелчке. Чтение/запись boolean.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |

### getStopSoundOnClick() {#getStopSoundOnClick--}
```
public abstract boolean getStopSoundOnClick()
```


Определяет, должно ли воспроизводимое звуковое сопровождение остановиться при щелчке по гиперссылке. Чтение/запись boolean.

**Возвращает:**
boolean

### setStopSoundOnClick(boolean value) {#setStopSoundOnClick-boolean-}
```
public abstract void setStopSoundOnClick(boolean value)
```


Определяет, должно ли воспроизводимое звуковое сопровождение остановиться при щелчке по гиперссылке. Чтение/запись boolean.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |

### getSound() {#getSound--}
```
public abstract IAudio getSound()
```


Представляет воспроизводимый звук гиперссылки. Чтение/запись [IAudio](../../com.aspose.slides/iaudio).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
> 
>      // Получить первую гиперссылку формы
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
public abstract void setSound(IAudio value)
```


Представляет воспроизводимый звук гиперссылки. Чтение/запись [IAudio](../../com.aspose.slides/iaudio).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
> 
>      // Получить первую гиперссылку формы
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
public abstract int getColorSource()
```


Представляет источник цвета гиперссылки — стили или формат части. Чтение/запись [HyperlinkColorSource](../../com.aspose.slides/hyperlinkcolorsource).

**Возвращает:**
int

### setColorSource(int value) {#setColorSource-int-}
```
public abstract void setColorSource(int value)
```


Представляет источник цвета гиперссылки — стили или формат части. Чтение/запись [HyperlinkColorSource](../../com.aspose.slides/hyperlinkcolorsource).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### equals(IHyperlink hlink) {#equals-com.aspose.slides.IHyperlink-}
```
public abstract boolean equals(IHyperlink hlink)
```


Определяет, равны ли два экземпляра Hyperlink.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| hlink | [IHyperlink](../../com.aspose.slides/ihyperlink) | Гиперссылка, с которой сравнивается текущая гиперссылка. |

**Возвращает:**
boolean - **true** если указанные гиперссылка равна текущей; иначе **false**.