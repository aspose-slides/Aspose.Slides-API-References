---
title: PortionFormat
second_title: Справочник API Aspose.Slides для Android на Java
description: Этот класс содержит свойства форматирования текстовых частей.
type: docs
url: /ru/com.aspose.slides/portionformat/
---
**Наследование:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject), [com.aspose.slides.BasePortionFormat](../../com.aspose.slides/baseportionformat)

**Все реализованные интерфейсы:**
[com.aspose.slides.IPortionFormat](../../com.aspose.slides/iportionformat)
```
public final class PortionFormat extends BasePortionFormat implements IPortionFormat
```

Этот класс содержит свойства форматирования части текста. В отличие от [IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata), все свойства этого класса доступны для записи.

--------------------

> ```
> The following examples shows you how to assign the Latin font to a Paragraph's portion of PowerPoint Presentation.
>  
>  //Создайте объект презентации, представляющий файл презентации
>  Presentation pres = new Presentation("demo.pptx");
>  try {
>      IAutoShape shape = pres.getSlides().get_Item(0).getShapes().addAutoShape(ShapeType.Rectangle, 10, 10, 100, 100);
>      Paragraph paragraph = new Paragraph();
>      Portion portion = new Portion("Theme text format");
>      paragraph.getPortions().add(portion);
>      shape.getTextFrame().getParagraphs().add(paragraph);
>      // Aspose.Slides использует эти специальные идентификаторы (аналогичные тем, что используются в PowerPoint):
>      // +mn-lt - Шрифт тела Latin (Minor Latin Font)
>      // +mj-lt -Шрифт заголовка Latin (Major Latin Font)
>      // +mn-ea - Шрифт тела East Asian (Minor East Asian Font)
>      // +mj-ea - Шрифт тела East Asian (Minor East Asian Font)
>      portion.getPortionFormat().setLatinFont(new FontData("+mn-lt"));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


--------------------

Этот класс используется для получения и изменения свойств форматирования части текста, определённых для конкретной части. Это означает, что при получении значений наследование не применяется, поэтому в большинстве случаев вы получите значения, означающие «неопределено».

Чтобы получить эффективные значения параметров форматирования, включая унаследованные, необходимо использовать метод [getEffective](../../com.aspose.slides/portionformat\#getEffective), который возвращает экземпляр [IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata).

## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [PortionFormat()](#PortionFormat--) | Инициализирует новый экземпляр класса [PortionFormat](../../com.aspose.slides/portionformat). |

## Методы

| Метод | Описание |
| --- | --- |
| [getBookmarkId()](#getBookmarkId--) | Возвращает или задаёт идентификатор закладки. |
| [setBookmarkId(String value)](#setBookmarkId-java.lang.String-) | Возвращает или задаёт идентификатор закладки. |
| [getSmartTagClean()](#getSmartTagClean--) | Определяет, следует ли очищать смарт-тег. |
| [setSmartTagClean(boolean value)](#setSmartTagClean-boolean-) | Определяет, следует ли очищать смарт-тег. |
| [getHyperlinkClick()](#getHyperlinkClick--) | Возвращает или задаёт гиперссылку, определённую для щелчка мышью. |
| [setHyperlinkClick(IHyperlink value)](#setHyperlinkClick-com.aspose.slides.IHyperlink-) | Возвращает или задаёт гиперссылку, определённую для щелчка мышью. |
| [getHyperlinkMouseOver()](#getHyperlinkMouseOver--) | Возвращает или задаёт гиперссылку, определённую для наведения мыши. |
| [setHyperlinkMouseOver(IHyperlink value)](#setHyperlinkMouseOver-com.aspose.slides.IHyperlink-) | Возвращает или задаёт гиперссылку, определённую для наведения мыши. |
| [getHyperlinkManager()](#getHyperlinkManager--) | Менеджер гиперссылок. |
| [getEffective()](#getEffective--) | Получает эффективные данные форматирования части с учётом наследования. |

### PortionFormat() {#PortionFormat--}
```
public PortionFormat()
```

Инициализирует новый экземпляр класса [PortionFormat](../../com.aspose.slides/portionformat).

### getBookmarkId() {#getBookmarkId--}
```
public final String getBookmarkId()
```

Возвращает или задаёт идентификатор закладки. Чтение/запись String.

**Возвращает:**
java.lang.String

### setBookmarkId(String value) {#setBookmarkId-java.lang.String-}
```
public final void setBookmarkId(String value)
```

Возвращает или задаёт идентификатор закладки. Чтение/запись String.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String |  |

### getSmartTagClean() {#getSmartTagClean--}
```
public final boolean getSmartTagClean()
```

Определяет, следует ли очищать смарт-тег. Наследование не применяется. Чтение/запись  boolean .

**Возвращает:**
boolean

### setSmartTagClean(boolean value) {#setSmartTagClean-boolean-}
```
public final void setSmartTagClean(boolean value)
```

Определяет, следует ли очищать смарт-тег. Наследование не применяется. Чтение/запись  boolean .

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |

### getHyperlinkClick() {#getHyperlinkClick--}
```
public final IHyperlink getHyperlinkClick()
```

Возвращает или задаёт гиперссылку, определённую для щелчка мышью. Чтение/запись [IHyperlink](../../com.aspose.slides/ihyperlink).

**Возвращает:**
[IHyperlink](../../com.aspose.slides/ihyperlink)

### setHyperlinkClick(IHyperlink value) {#setHyperlinkClick-com.aspose.slides.IHyperlink-}
```
public final void setHyperlinkClick(IHyperlink value)
```

Возвращает или задаёт гиперссылку, определённую для щелчка мышью. Чтение/запись [IHyperlink](../../com.aspose.slides/ihyperlink).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [IHyperlink](../../com.aspose.slides/ihyperlink) |  |

### getHyperlinkMouseOver() {#getHyperlinkMouseOver--}
```
public final IHyperlink getHyperlinkMouseOver()
```

Возвращает или задаёт гиперссылку, определённую для наведения мыши. Чтение/запись [IHyperlink](../../com.aspose.slides/ihyperlink).

**Возвращает:**
[IHyperlink](../../com.aspose.slides/ihyperlink)

### setHyperlinkMouseOver(IHyperlink value) {#setHyperlinkMouseOver-com.aspose.slides.IHyperlink-}
```
public final void setHyperlinkMouseOver(IHyperlink value)
```

Возвращает или задаёт гиперссылку, определённую для наведения мыши. Чтение/запись [IHyperlink](../../com.aspose.slides/ihyperlink).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [IHyperlink](../../com.aspose.slides/ihyperlink) |  |

### getHyperlinkManager() {#getHyperlinkManager--}
```
public final IHyperlinkManager getHyperlinkManager()
```

Менеджер гиперссылок. Только чтение [IHyperlinkManager](../../com.aspose.slides/ihyperlinkmanager).

**Возвращает:**
[IHyperlinkManager](../../com.aspose.slides/ihyperlinkmanager)

### getEffective() {#getEffective--}
```
public final IPortionFormatEffectiveData getEffective()
```

Получает эффективные данные форматирования части с учётом наследования.

--------------------

> ```
> This example demonstrates getting some effective portion format properties.
>  
>  Presentation pres = new Presentation("MyPresentation.pptx");
>  try
>  {
>  	IAutoShape shape = (IAutoShape)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>  	IPortionFormatEffectiveData effectivePortionFormat = shape.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0).getPortionFormat().getEffective();
>  	System.out.println("Latin font: " + effectivePortionFormat.getLatinFont().getFontName());
>  	System.out.println("Font height: " + effectivePortionFormat.getFontHeight());
>  	System.out.println("Fill type: " + effectivePortionFormat.getFillFormat().getFillType());
>  } finally {
>   if (pres != null) pres.dispose();
>  }
> ```


**Возвращает:**
[IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata) - A [IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata).