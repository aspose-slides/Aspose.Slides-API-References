---
title: IBulletFormatEffectiveData
second_title: Aspose.Slides for Android via Java API Reference
description: 효과적인 단락 글머리 기호 서식 속성을 포함하는 불변 객체입니다.
type: docs
url: /ko/com.aspose.slides/ibulletformateffectivedata/
---```
public interface IBulletFormatEffectiveData
```

효과적인 단락 글머리 기호 서식 속성을 포함하는 불변 객체입니다.

--------------------

This interface is used as a part of [IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata).
## Methods

| 메서드 | 설명 |
| --- | --- |
| [getType()](#getType--) | 단락의 글머리 기호 유형을 반환합니다. |
| [getChar()](#getChar--) | 단락의 글머리 기호 문자를 반환합니다. |
| [getActualBulletValue()](#getActualBulletValue--) | 상위 단락에 대한 실제 글머리 기호 값을 반환합니다. |
| [getFont()](#getFont--) | 단락의 글머리 기호 글꼴을 반환합니다. |
| [getHeight()](#getHeight--) | 단락의 글머리 기호 높이를 반환합니다. |
| [getNumberedBulletStartWith()](#getNumberedBulletStartWith--) | 번호 매기기 글머리 기호 그룹에 사용되는 첫 번째 번호를 반환합니다. |
| [getNumberedBulletStyle()](#getNumberedBulletStyle--) | 번호 매기기 글머리 기호의 스타일을 반환합니다. |
| [isBulletHardColor()](#isBulletHardColor--) | 글머리 기호가 자체 색상을 가지고 있는지 또는 단락의 첫 번째 구간에서 색상을 상속받는지 판단합니다. |
| [isBulletHardFont()](#isBulletHardFont--) | 글머리 기호가 자체 글꼴을 가지고 있는지 또는 단락의 첫 번째 구간에서 글꼴을 상속받는지 판단합니다. |
| [getPicture()](#getPicture--) | 단락에서 글머리 기호로 사용되는 그림을 반환합니다. |
| [getFillFormat()](#getFillFormat--) | 단락의 글머리 기호 채우기 서식을 반환합니다. |
### getType() {#getType--}
```
public abstract byte getType()
```


단락의 글머리 기호 유형을 반환합니다. 읽기 전용 [BulletType](../../com.aspose.slides/bullettype).

**반환:**
byte
### getChar() {#getChar--}
```
public abstract char getChar()
```


단락의 글머리 기호 문자를 반환합니다. 읽기 전용 char.

**반환:**
char
### getActualBulletValue() {#getActualBulletValue--}
```
public abstract String getActualBulletValue()
```


상위 단락에 대한 실제 글머리 기호 값을 반환합니다. 읽기 전용 String.

**반환:**
java.lang.String
### getFont() {#getFont--}
```
public abstract IFontData getFont()
```


단락의 글머리 기호 글꼴을 반환합니다. 읽기 전용 [IFontData](../../com.aspose.slides/ifontdata).

**반환:**
[IFontData](../../com.aspose.slides/ifontdata)
### getHeight() {#getHeight--}
```
public abstract float getHeight()
```


단락의 글머리 기호 높이를 반환합니다. 읽기 전용 float.

**반환:**
float
### getNumberedBulletStartWith() {#getNumberedBulletStartWith--}
```
public abstract short getNumberedBulletStartWith()
```


번호 매기기 글머리 기호 그룹에 사용되는 첫 번째 번호를 반환합니다. 읽기 전용 short.

**반환:**
short
### getNumberedBulletStyle() {#getNumberedBulletStyle--}
```
public abstract byte getNumberedBulletStyle()
```


번호 매기기 글머리 기호의 스타일을 반환합니다. 읽기 전용 [NumberedBulletStyle](../../com.aspose.slides/numberedbulletstyle).

**반환:**
byte
### isBulletHardColor() {#isBulletHardColor--}
```
public abstract boolean isBulletHardColor()
```


글머리 기호가 자체 색상을 가지고 있는지 또는 단락의 첫 번째 구간에서 색상을 상속받는지 판단합니다. 자체 색상이 있으면 **true**, 상속받으면 **false**를 반환합니다. 읽기 전용 boolean.

**반환:**
boolean
### isBulletHardFont() {#isBulletHardFont--}
```
public abstract boolean isBulletHardFont()
```


글머리 기호가 자체 글꼴을 가지고 있는지 또는 단락의 첫 번째 구간에서 글꼴을 상속받는지 판단합니다. 자체 글꼴이 있으면 **true**, 상속받으면 **true**를 반환합니다. 읽기 전용 boolean.

**반환:**
boolean
### getPicture() {#getPicture--}
```
public abstract IPictureEffectiveData getPicture()
```


단락에서 글머리 기호로 사용되는 그림을 반환합니다. 읽기 전용 [IPictureEffectiveData](../../com.aspose.slides/ipictureeffectivedata).

**반환:**
[IPictureEffectiveData](../../com.aspose.slides/ipictureeffectivedata)
### getFillFormat() {#getFillFormat--}
```
public abstract IFillFormatEffectiveData getFillFormat()
```


단락의 글머리 기호 채우기 서식을 반환합니다. 읽기 전용 [IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata).

--------------------

> ```
> This example demonstrates retrieving bullet's fill effective data.
>  
>  Presentation pres = new Presentation("SomePresentation.pptx");
>  try {
>      // 첫 번째 슬라이드의 첫 번째 도형이 텍스트가 있는 AutoShape이라고 가정합니다...
>      // 텍스트 단락의 글머리 기호에 대한 정보를 출력합니다
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


**반환:**
[IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata)