---
title: IBulletFormatEffectiveData
second_title: Aspose.Slides for Android via Java API Reference
description: Immutable object which contains effective paragraph bullet formatting properties.
type: docs
url: /ru/com.aspose.slides/ibulletformateffectivedata/
---```
public interface IBulletFormatEffectiveData
```

Неизменяемый объект, содержащий эффективные свойства форматирования маркеров абзаца.

--------------------

Этот интерфейс используется как часть [IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata).
## Методы

| Метод | Описание |
| --- | --- |
| [getType()](#getType--) | Возвращает тип маркера абзаца. |
| [getChar()](#getChar--) | Возвращает символ маркера абзаца. |
| [getActualBulletValue()](#getActualBulletValue--) | Возвращает фактическое значение маркера для родительского абзаца. |
| [getFont()](#getFont--) | Возвращает шрифт маркера абзаца. |
| [getHeight()](#getHeight--) | Возвращает высоту маркера абзаца. |
| [getNumberedBulletStartWith()](#getNumberedBulletStartWith--) | Возвращает первое число, используемое для группы нумерованных маркеров. |
| [getNumberedBulletStyle()](#getNumberedBulletStyle--) | Возвращает стиль нумерованного маркера. |
| [isBulletHardColor()](#isBulletHardColor--) | Определяет, имеет ли маркер собственный цвет или наследует его от первой части абзаца. |
| [isBulletHardFont()](#isBulletHardFont--) | Определяет, имеет ли маркер собственный шрифт или наследует его от первой части абзаца. |
| [getPicture()](#getPicture--) | Возвращает изображение, используемое в качестве маркера в абзаце. |
| [getFillFormat()](#getFillFormat--) | Возвращает формат заполнения маркера абзаца. |
### getType() {#getType--}
```
public abstract byte getType()
```


Возвращает тип маркера абзаца. Только для чтения [BulletType](../../com.aspose.slides/bullettype).

**Возвращает:**
byte
### getChar() {#getChar--}
```
public abstract char getChar()
```


Возвращает символ маркера абзаца. Только для чтения char.

**Возвращает:**
char
### getActualBulletValue() {#getActualBulletValue--}
```
public abstract String getActualBulletValue()
```


Возвращает фактическое значение маркера для родительского абзаца. Только для чтения String.

**Возвращает:**
java.lang.String
### getFont() {#getFont--}
```
public abstract IFontData getFont()
```


Возвращает шрифт маркера абзаца. Только для чтения [IFontData](../../com.aspose.slides/ifontdata).

**Возвращает:**
[IFontData](../../com.aspose.slides/ifontdata)
### getHeight() {#getHeight--}
```
public abstract float getHeight()
```


Возвращает высоту маркера абзаца. Только для чтения float.

**Возвращает:**
float
### getNumberedBulletStartWith() {#getNumberedBulletStartWith--}
```
public abstract short getNumberedBulletStartWith()
```


Возвращает первое число, используемое для группы нумерованных маркеров. Только для чтения short.

**Возвращает:**
short
### getNumberedBulletStyle() {#getNumberedBulletStyle--}
```
public abstract byte getNumberedBulletStyle()
```


Возвращает стиль нумерованного маркера. Только для чтения [NumberedBulletStyle](../../com.aspose.slides/numberedbulletstyle).

**Возвращает:**
byte
### isBulletHardColor() {#isBulletHardColor--}
```
public abstract boolean isBulletHardColor()
```


Определяет, имеет ли маркер собственный цвет или наследует его от первой части абзаца. Возвращает **true**, если у маркера есть собственный цвет, и **false**, если он наследует цвет от первой части абзаца. Только для чтения boolean.

**Возвращает:**
boolean
### isBulletHardFont() {#isBulletHardFont--}
```
public abstract boolean isBulletHardFont()
```


Определяет, имеет ли маркер собственный шрифт или наследует его от первой части абзаца. Возвращает **true**, если у маркера есть собственный шрифт, и **true**, если он наследует шрифт от первой части абзаца. Только для чтения boolean.

**Возвращает:**
boolean
### getPicture() {#getPicture--}
```
public abstract IPictureEffectiveData getPicture()
```


Возвращает изображение, используемое в качестве маркера в абзаце. Только для чтения [IPictureEffectiveData](../../com.aspose.slides/ipictureeffectivedata).

**Возвращает:**
[IPictureEffectiveData](../../com.aspose.slides/ipictureeffectivedata)
### getFillFormat() {#getFillFormat--}
```
public abstract IFillFormatEffectiveData getFillFormat()
```


Возвращает формат заполнения маркера абзаца. Только для чтения [IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata).

--------------------

> ```
> This example demonstrates retrieving bullet's fill effective data.
>  
>  Presentation pres = new Presentation("SomePresentation.pptx");
>  try {
>      // Предполагается, что первая фигура на первом слайде является AutoShape с некоторым текстом...
>      // Вывести информацию о маркерах абзацев текста
>      AutoShape autoShape = (AutoShape)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      for (IParagraph para : autoShape.getTextFrame().getParagraphs())
>      {
>          IBulletFormatEffectiveData bulletFormatEffective = para.getParagraphFormat().getBullet().getEffective();
>          System.out.println("Bullet type: " + bulletFormatEffective.getType());
>          if (bulletFormatEffective.getType() != BulletType.None)
>          {
>              System.out.println("Bullet fill type: " + bulletFormatEffective.getFillFormat().getFillType());
>              switch (bulletFormatEffective.getFillFormat().getFillType())
>              {
>                  case FillType.Solid:
>                      System.out.println("Solid fill color: " + bulletFormatEffective.getFillFormat().getSolidFillColor());
>                      break;
>                  case FillType.Gradient:
>                      System.out.println("Gradient stops count: " + bulletFormatEffective.getFillFormat().getGradientFormat().getGradientStops().size());
>                      for (IGradientStopEffectiveData gradStop : bulletFormatEffective.getFillFormat().getGradientFormat().getGradientStops())
>                          System.out.println(gradStop.getPosition() + ": " + gradStop.getColor());
>                      break;
>                  case FillType.Pattern:
>                      System.out.println("Pattern style: " + bulletFormatEffective.getFillFormat().getPatternFormat().getPatternStyle());
>                      System.out.println("Fore color: " + bulletFormatEffective.getFillFormat().getPatternFormat().getForeColor());
>                      System.out.println("Back color: " + bulletFormatEffective.getFillFormat().getPatternFormat().getBackColor());
>                      break;
>              }
>          }
>          System.out.println();
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Возвращает:**
[IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata)