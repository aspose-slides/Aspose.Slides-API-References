---
title: TextStyle
second_title: Aspose.Slides для Android через справочник Java API
description: Этот класс содержит свойства форматирования текстового стиля.
type: docs
url: /ru/com.aspose.slides/textstyle/
---
**Наследование:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**Все реализованные интерфейсы:**
[com.aspose.slides.ITextStyle](../../com.aspose.slides/itextstyle), com.aspose.slides.IStyleColorOwner
```
public final class TextStyle extends PVIObject implements ITextStyle, IStyleColorOwner
```

Этот класс содержит свойства форматирования текстового стиля.
## Методы

| Метод | Описание |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getLevel(int index)](#getLevel-int-) | Если уровень стиля существует, возвращает его, в противном случае возвращает null. |
| [getDefaultParagraphFormat()](#getDefaultParagraphFormat--) | Свойства абзаца по умолчанию. |
| [getEffective()](#getEffective--) | Получает эффективные данные форматирования текстового стиля с учётом наследования. |
### getVersion() {#getVersion--}
```
public long getVersion()
```


Версия. Только для чтения long.

**Возвращает:**
long
### getLevel(int index) {#getLevel-int-}
```
public final IParagraphFormat getLevel(int index)
```


Если уровень стиля существует, возвращает его, в противном случае возвращает null.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int | Нулевой индекс уровня. Должен находиться в интервале 0..8. |

**Возвращает:**
[IParagraphFormat](../../com.aspose.slides/iparagraphformat) - Форматирование уровня [IParagraphFormat](../../com.aspose.slides/iparagraphformat).
### getDefaultParagraphFormat() {#getDefaultParagraphFormat--}
```
public final IParagraphFormat getDefaultParagraphFormat()
```


Свойства абзаца по умолчанию. Только для чтения [IParagraphFormat](../../com.aspose.slides/iparagraphformat).

**Возвращает:**
[IParagraphFormat](../../com.aspose.slides/iparagraphformat)
### getEffective() {#getEffective--}
```
public final ITextStyleEffectiveData getEffective()
```


Получает эффективные данные форматирования текстового стиля с учётом наследования.

--------------------

> ```
> This example demonstrates getting some of effective text style properties.
>  
>  Presentation pres = new Presentation("MyPresentation.pptx");
>  try
>  {
>      IAutoShape shape = (IAutoShape)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      ITextStyleEffectiveData effectiveTextStyle = shape.getTextFrame().getTextFrameFormat().getTextStyle().getEffective();
>      for (int i = 0; i <= 8; i++)
>      {
>          IParagraphFormatEffectiveData effectiveStyleLevel = effectiveTextStyle.getLevel(i);
>          System.out.println("= Effective paragraph formatting for style level #" + i + " =");
>          System.out.println("Depth: " + effectiveStyleLevel.getDepth());
>          System.out.println("Indent: " + effectiveStyleLevel.getIndent());
>          System.out.println("Alignment: " + effectiveStyleLevel.getAlignment());
>          System.out.println("Font alignment: " + effectiveStyleLevel.getFontAlignment());
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Возвращает:**
[ITextStyleEffectiveData](../../com.aspose.slides/itextstyleeffectivedata) - Экземпляр [ITextStyleEffectiveData](../../com.aspose.slides/itextstyleeffectivedata).