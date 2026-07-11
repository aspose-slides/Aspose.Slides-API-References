---
title: ParagraphFormat
second_title: Справочник API Java для Aspose.Slides для Android
description: Этот класс содержит свойства форматирования абзаца.
type: docs
url: /ru/com.aspose.slides/paragraphformat/
---
**Наследование:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**Все реализованные интерфейсы:**
[com.aspose.slides.IParagraphFormat](../../com.aspose.slides/iparagraphformat), [com.aspose.slides.IChartParagraphFormat](../../com.aspose.slides/ichartparagraphformat)
```
public final class ParagraphFormat extends PVIObject implements IParagraphFormat, IChartParagraphFormat
```

Этот класс содержит свойства форматирования абзаца. В отличие от [IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata), все свойства этого класса изменяемы.

--------------------

Этот класс используется для получения и изменения свойств форматирования абзаца, определённых для конкретного абзаца. Это означает, что при получении значений наследование не применяется, поэтому в большинстве случаев вы получите значения, означающие «неопределено».

Чтобы получить эффективные значения параметров форматирования, включая унаследованные, необходимо использовать метод [getEffective](../../com.aspose.slides/paragraphformat\#getEffective), который возвращает экземпляр [IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata).

## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [ParagraphFormat()](#ParagraphFormat--) | Создаёт новый экземпляр класса [ParagraphFormat](../../com.aspose.slides/paragraphformat). |

## Методы

| Метод | Описание |
| --- | --- |
| [getBullet()](#getBullet--) | Возвращает формат маркера абзаца. |
| [getDepth()](#getDepth--) | Возвращает или задаёт глубину абзаца. |
| [setDepth(short value)](#setDepth-short-) | Возвращает или задаёт глубину абзаца. |
| [getAlignment()](#getAlignment--) | Возвращает или задаёт выравнивание текста в абзаце без наследования. |
| [setAlignment(int value)](#setAlignment-int-) | Возвращает или задаёт выравнивание текста в абзаце без наследования. |
| [getSpaceWithin()](#getSpaceWithin--) | Возвращает или задаёт величину интервала между базовыми линиями в абзаце. |
| [setSpaceWithin(float value)](#setSpaceWithin-float-) | Возвращает или задаёт величину интервала между базовыми линиями в абзаце. |
| [getSpaceBefore()](#getSpaceBefore--) | Возвращает или задаёт количество пространства перед первой строкой в абзаце без наследования. |
| [setSpaceBefore(float value)](#setSpaceBefore-float-) | Возвращает или задаёт количество пространства перед первой строкой в абзаце без наследования. |
| [getSpaceAfter()](#getSpaceAfter--) | Возвращает или задаёт количество пространства после последней строки в абзаце без наследования. |
| [setSpaceAfter(float value)](#setSpaceAfter-float-) | Возвращает или задаёт количество пространства после последней строки в абзаце без наследования. |
| [getEastAsianLineBreak()](#getEastAsianLineBreak--) | Определяет, используется ли разрыв строки восточноазиатского типа в абзаце. |
| [setEastAsianLineBreak(byte value)](#setEastAsianLineBreak-byte-) | Определяет, используется ли разрыв строки восточноазиатского типа в абзаце. |
| [getRightToLeft()](#getRightToLeft--) | Определяет, используется ли написание справа налево в абзаце. |
| [setRightToLeft(byte value)](#setRightToLeft-byte-) | Определяет, используется ли написание справа налево в абзаце. |
| [getLatinLineBreak()](#getLatinLineBreak--) | Определяет, используется ли разрыв строки латинского типа в абзаце. |
| [setLatinLineBreak(byte value)](#setLatinLineBreak-byte-) | Определяет, используется ли разрыв строки латинского типа в абзаце. |
| [getHangingPunctuation()](#getHangingPunctuation--) | Определяет, используется ли висячая пунктуация в абзаце. |
| [setHangingPunctuation(byte value)](#setHangingPunctuation-byte-) | Определяет, используется ли висячая пунктуация в абзаце. |
| [getMarginLeft()](#getMarginLeft--) | Возвращает или задаёт левый отступ в абзаце без наследования. |
| [setMarginLeft(float value)](#setMarginLeft-float-) | Возвращает или задаёт левый отступ в абзаце без наследования. |
| [getMarginRight()](#getMarginRight--) | Возвращает или задаёт правый отступ в абзаце без наследования. |
| [setMarginRight(float value)](#setMarginRight-float-) | Возвращает или задаёт правый отступ в абзаце без наследования. |
| [getIndent()](#getIndent--) | Возвращает или задаёт отступ первой строки/висячий отступ абзаца без наследования. |
| [setIndent(float value)](#setIndent-float-) | Возвращает или задаёт отступ первой строки/висячий отступ абзаца без наследования. |
| [getDefaultTabSize()](#getDefaultTabSize--) | Возвращает или задаёт размер табуляции по умолчанию без наследования. |
| [setDefaultTabSize(float value)](#setDefaultTabSize-float-) | Возвращает или задаёт размер табуляции по умолчанию без наследования. |
| [getTabs()](#getTabs--) | Возвращает табуляции абзаца. |
| [getFontAlignment()](#getFontAlignment--) | Возвращает или задаёт выравнивание шрифта в абзаце без наследования. |
| [setFontAlignment(int value)](#setFontAlignment-int-) | Возвращает или задаёт выравнивание шрифта в абзаце без наследования. |
| [getDefaultPortionFormat()](#getDefaultPortionFormat--) | Возвращает формат фрагмента по умолчанию абзаца. |
| [getEffective()](#getEffective--) | Получает эффективные данные форматирования абзаца с учётом наследования. |
| [getVersion()](#getVersion--) |  |

### ParagraphFormat() {#ParagraphFormat--}
```
public ParagraphFormat()
```

Создаёт новый экземпляр класса [ParagraphFormat](../../com.aspose.slides/paragraphformat).

### getBullet() {#getBullet--}
```
public final IBulletFormat getBullet()
```

Возвращает формат маркера абзаца. Только для чтения [IBulletFormat](../../com.aspose.slides/ibulletformat).

**Возвращаемое значение:**
[IBulletFormat](../../com.aspose.slides/ibulletformat)

### getDepth() {#getDepth--}
```
public final short getDepth()
```

Возвращает или задаёт глубину абзаца. Значение 0 означает неопределённое значение. Чтение/запись short .

**Возвращаемое значение:**
short

### setDepth(short value) {#setDepth-short-}
```
public final void setDepth(short value)
```

Возвращает или задаёт глубину абзаца. Значение 0 означает неопределённое значение. Чтение/запись short .

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | short |  |

### getAlignment() {#getAlignment--}
```
public final int getAlignment()
```

Возвращает или задаёт выравнивание текста в абзаце без наследования. Чтение/запись [TextAlignment](../../com.aspose.slides/textalignment).

--------------------

> ```
> The following sample code shows how to Align Text Paragraphs in PowerPoint Presentation.
>  
>  // Создайте объект Presentation, представляющий файл PPTX
>  Presentation pres = new Presentation("ParagraphsAlignment.pptx");
>  try {
>      // Доступ к первому слайду
>      ISlide slide = pres.getSlides().get_Item(0);
>      // Доступ к первому и второму заполнительному элементу на слайде и приведение к типу AutoShape
>      ITextFrame tf1 = ((IAutoShape)slide.getShapes().get_Item(0)).getTextFrame();
>      ITextFrame tf2 = ((IAutoShape)slide.getShapes().get_Item(1)).getTextFrame();
>      // Изменить текст в обоих заполнителях
>      tf1.setText("Center Align by Aspose");
>      tf2.setText("Center Align by Aspose");
>      // Получение первого абзаца из заполнителей
>      IParagraph para1 = tf1.getParagraphs().get_Item(0);
>      IParagraph para2 = tf2.getParagraphs().get_Item(0);
>      // Выравнивание текста абзаца по центру
>      para1.getParagraphFormat().setAlignment(TextAlignment.Center);
>      para2.getParagraphFormat().setAlignment(TextAlignment.Center);
>      // Сохранить презентацию в файл PPTX
>      pres.save("Centeralign_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Возвращаемое значение:**
int

### setAlignment(int value) {#setAlignment-int-}
```
public final void setAlignment(int value)
```

Возвращает или задаёт выравнивание текста в абзаце без наследования. Чтение/запись [TextAlignment](../../com.aspose.slides/textalignment).

--------------------

> ```
> The following sample code shows how to Align Text Paragraphs in PowerPoint Presentation.
>  
>  // Создайте объект Presentation, представляющий файл PPTX
>  Presentation pres = new Presentation("ParagraphsAlignment.pptx");
>  try {
>      // Доступ к первому слайду
>      ISlide slide = pres.getSlides().get_Item(0);
>      // Доступ к первому и второму заполнительному элементу на слайде и приведение к типу AutoShape
>      ITextFrame tf1 = ((IAutoShape)slide.getShapes().get_Item(0)).getTextFrame();
>      ITextFrame tf2 = ((IAutoShape)slide.getShapes().get_Item(1)).getTextFrame();
>      // Изменить текст в обоих заполнителях
>      tf1.setText("Center Align by Aspose");
>      tf2.setText("Center Align by Aspose");
>      // Получение первого абзаца из заполнителей
>      IParagraph para1 = tf1.getParagraphs().get_Item(0);
>      IParagraph para2 = tf2.getParagraphs().get_Item(0);
>      // Выравнивание текста абзаца по центру
>      para1.getParagraphFormat().setAlignment(TextAlignment.Center);
>      para2.getParagraphFormat().setAlignment(TextAlignment.Center);
>      //Сохранить презентацию в файл PPTX
>      pres.save("Centeralign_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getSpaceWithin() {#getSpaceWithin--}
```
public final float getSpaceWithin()
```

Возвращает или задаёт величину пространства между базовыми линиями в абзаце. Положительное значение означает процент, отрицательное — размер в пунктах. Наследование не применяется. Чтение/запись float .

**Возвращаемое значение:**
float

### setSpaceWithin(float value) {#setSpaceWithin-float-}
```
public final void setSpaceWithin(float value)
```

Возвращает или задаёт величину пространства между базовыми линиями в абзаце. Положительное значение означает процент, отрицательное — размер в пунктах. Наследование не применяется. Чтение/запись float .

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | float |  |

### getSpaceBefore() {#getSpaceBefore--}
```
public final float getSpaceBefore()
```

Возвращает или задаёт количество пространства перед первой строкой в абзаце без наследования. Положительное значение указывает процент от размера шрифта, отрицательное — размер в пунктах. Чтение/запись float .

**Возвращаемое значение:**
float

### setSpaceBefore(float value) {#setSpaceBefore-float-}
```
public final void setSpaceBefore(float value)
```

Возвращает или задаёт количество пространства перед первой строкой в абзаце без наследования. Положительное значение указывает процент от размера шрифта, отрицательное — размер в пунктах. Чтение/запись float .

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | float |  |

### getSpaceAfter() {#getSpaceAfter--}
```
public final float getSpaceAfter()
```

Возвращает или задаёт количество пространства после последней строки в абзаце без наследования. Положительное значение указывает процент от размера шрифта, отрицательное — размер в пунктах. Чтение/запись float .

**Возвращаемое значение:**
float

### setSpaceAfter(float value) {#setSpaceAfter-float-}
```
public final void setSpaceAfter(float value)
```

Возвращает или задаёт количество пространства после последней строки в абзаце без наследования. Положительное значение указывает процент от размера шрифта, отрицательное — размер в пунктах. Чтение/запись float .

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | float |  |

### getEastAsianLineBreak() {#getEastAsianLineBreak--}
```
public final byte getEastAsianLineBreak()
```

Определяет, используется ли разрыв строки восточноазиатского типа в абзаце. Наследование не применяется. Чтение/запись [NullableBool](../../com.aspose.slides/nullablebool).

**Возвращаемое значение:**
byte

### setEastAsianLineBreak(byte value) {#setEastAsianLineBreak-byte-}
```
public final void setEastAsianLineBreak(byte value)
```

Определяет, используется ли разрыв строки восточноазиатского типа в абзаце. Наследование не применяется. Чтение/запись [NullableBool](../../com.aspose.slides/nullablebool).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | byte |  |

### getRightToLeft() {#getRightToLeft--}
```
public final byte getRightToLeft()
```

Определяет, используется ли написание справа налево в абзаце. Наследование не применяется. Чтение/запись [NullableBool](../../com.aspose.slides/nullablebool).

**Возвращаемое значение:**
byte

### setRightToLeft(byte value) {#setRightToLeft-byte-}
```
public final void setRightToLeft(byte value)
```

Определяет, используется ли написание справа налево в абзаце. Наследование не применяется. Чтение/запись [NullableBool](../../com.aspose.slides/nullablebool).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | byte |  |

### getLatinLineBreak() {#getLatinLineBreak--}
```
public final byte getLatinLineBreak()
```

Определяет, используется ли разрыв строки латинского типа в абзаце. Наследование не применяется. Чтение/запись [NullableBool](../../com.aspose.slides/nullablebool).

**Возвращаемое значение:**
byte

### setLatinLineBreak(byte value) {#setLatinLineBreak-byte-}
```
public final void setLatinLineBreak(byte value)
```

Определяет, используется ли разрыв строки латинского типа в абзаце. Наследование не применяется. Чтение/запись [NullableBool](../../com.aspose.slides/nullablebool).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | byte |  |

### getHangingPunctuation() {#getHangingPunctuation--}
```
public final byte getHangingPunctuation()
```

Определяет, используется ли висячая пунктуация в абзаце. Наследование не применяется. Чтение/запись [NullableBool](../../com.aspose.slides/nullablebool).

**Возвращаемое значение:**
byte

### setHangingPunctuation(byte value) {#setHangingPunctuation-byte-}
```
public final void setHangingPunctuation(byte value)
```

Определяет, используется ли висячая пунктуация в абзаце. Наследование не применяется. Чтение/запись [NullableBool](../../com.aspose.slides/nullablebool).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | byte |  |

### getMarginLeft() {#getMarginLeft--}
```
public final float getMarginLeft()
```

Возвращает или задаёт левый отступ в абзаце без наследования. Чтение/запись float .

**Возвращаемое значение:**
float

### setMarginLeft(float value) {#setMarginLeft-float-}
```
public final void setMarginLeft(float value)
```

Возвращает или задаёт левый отступ в абзаце без наследования. Чтение/запись float .

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | float |  |

### getMarginRight() {#getMarginRight--}
```
public final float getMarginRight()
```

Возвращает или задаёт правый отступ в абзаце без наследования. Чтение/запись float .

**Возвращаемое значение:**
float

### setMarginRight(float value) {#setMarginRight-float-}
```
public final void setMarginRight(float value)
```

Возвращает или задаёт правый отступ в абзаце без наследования. Чтение/запись float .

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | float |  |

### getIndent() {#getIndent--}
```
public final float getIndent()
```

Возвращает или задаёт отступ первой строки/висячий отступ абзаца без наследования. Висячий отступ можно задать отрицательными значениями. Чтение/запись float .

**Возвращаемое значение:**
float

### setIndent(float value) {#setIndent-float-}
```
public final void setIndent(float value)
```

Возвращает или задаёт отступ первой строки/висячий отступ абзаца без наследования. Висячий отступ можно задать отрицательными значениями. Чтение/запись float .

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | float |  |

### getDefaultTabSize() {#getDefaultTabSize--}
```
public final float getDefaultTabSize()
```

Возвращает или задаёт размер табуляции по умолчанию без наследования. Чтение/запись float .

**Возвращаемое значение:**
float

### setDefaultTabSize(float value) {#setDefaultTabSize-float-}
```
public final void setDefaultTabSize(float value)
```

Возвращает или задаёт размер табуляции по умолчанию без наследования. Чтение/запись float .

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | float |  |

### getTabs() {#getTabs--}
```
public final ITabCollection getTabs()
```

Возвращает табуляции абзаца. Наследование не применяется. Только для чтения [ITabCollection](../../com.aspose.slides/itabcollection).

**Возвращаемое значение:**
[ITabCollection](../../com.aspose.slides/itabcollection)

### getFontAlignment() {#getFontAlignment--}
```
public final int getFontAlignment()
```

Возвращает или задаёт выравнивание шрифта в абзаце без наследования. Чтение/запись [FontAlignment](../../com.aspose.slides/fontalignment).

**Возвращаемое значение:**
int

### setFontAlignment(int value) {#setFontAlignment-int-}
```
public final void setFontAlignment(int value)
```

Возвращает или задаёт выравнивание шрифта в абзаце без наследования. Чтение/запись [FontAlignment](../../com.aspose.slides/fontalignment).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getDefaultPortionFormat() {#getDefaultPortionFormat--}
```
public final IPortionFormat getDefaultPortionFormat()
```

Возвращает формат фрагмента по умолчанию абзаца. Наследование не применяется. Только для чтения [IPortionFormat](../../com.aspose.slides/iportionformat).

**Возвращаемое значение:**
[IPortionFormat](../../com.aspose.slides/iportionformat)

### getEffective() {#getEffective--}
```
public final IParagraphFormatEffectiveData getEffective()
```

Получает эффективные данные форматирования абзаца с учётом наследования.

--------------------

> ```
> This example demonstrates getting some effective paragraph format properties.
>  
>  Presentation pres = new Presentation("MyPresentation.pptx");
>  try
>  {
>  	IAutoShape shape = (IAutoShape)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>  	IParagraphFormatEffectiveData effectiveParagraphFormat = shape.getTextFrame().getParagraphs().get_Item(0).getParagraphFormat().getEffective();
>  	System.out.println("Text alignment: " + effectiveParagraphFormat.getAlignment());
>  	System.out.println("Indent: " + effectiveParagraphFormat.getIndent());
>  	System.out.println("Bullet type: " + effectiveParagraphFormat.getBullet().getType());
>  } finally {
>   if (pres != null) pres.dispose();
>  }
> ```


**Возвращаемое значение:**
[IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata) - A [IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata).

### getVersion() {#getVersion--}
```
public long getVersion()
```

Версия. Только для чтения long.

**Возвращаемое значение:**
long